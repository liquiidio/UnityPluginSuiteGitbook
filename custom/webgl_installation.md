---
cover: ../.gitbook/assets/UNITY3DxWAX-1920x360_Devs_03.png
coverY: 0
---

# WebGL Installation

WebGL builds will require the index.html file to be customised.

Download the full customised file [here](downloads/index.html).

**Important!** waxjs.js needs to be included in your build, next to the customised html file and needs to be loaded by your html file. Download waxjs.js [here](https://github.com/worldwide-asset-exchange/waxjs/tree/develop/dist-web)

> **Ensure that this line is added to make websockets work.**

```js
window.unityInstance = unityInstance;
```

<details>

<summary>Further reading</summary>

WebAssembly for [security](https://webassembly.org/docs/security/) purposes does not have Networking-Capabilities.

Read more here: (https://webassembly.org/docs/security/)

</details>

#### Final script should have this included

```js
      script.onload = () => {
        createUnityInstance(canvas, config, (progress) => {
          progressBarFull.style.width = 100 * progress + "%";
          }).then((unityInstance) => {
	  
	  // !!! IMPORTANT
	  window.unityInstance = unityInstance; // <-- THIS LINE MUST BE ADDED TO ENSURE WEBSOCKETS WORK!!!
          // !!! IMPORTANT
	  
          loadingBar.style.display = "none";
          fullscreenButton.onclick = () => {
          unityInstance.SetFullscreen(1);
          };
        }).catch((message) => {
          alert(message);
        });
```

#### Additional snippets

Unity WebGL requires an event listener to paste from the OS clipboard. Use the following structure in `script.onload`.

```js
	// !!!
	// !!! adding this Listener allows to copy-paste date from outside the WebGL-Build into the WebGL-Build
        window.addEventListener('paste', function (e) {
		const str = e.clipboardData.getData('text');
		// Calls Method OnBrowserClipboardPaste in class WaxCloudWalletMainPanel while passing str as argument
           	window.unityInstance.SendMessage('WaxCloudWalletMainPanel', 'OnBrowserClipboardPaste', str);
        });
	// !!!
     });
```
