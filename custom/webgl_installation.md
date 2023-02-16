# WebGL Installation

WebGL builds will require the index.html file to be customised.

Download the full customised file [here](downloads/index.html).

An additional .js file to be included next to the customised html file. Download the .js file [here](downloads/waxjs.js)

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
window.addEventListener('paste', function (e) {
      const str = e.clipboardData.getData('text');
      // In this case OnBrowserClipboardPaste(...) in the class CanvasExample is called while passing str as parameter
      window.unityInstance.SendMessage('CanvasExample', 'OnBrowserClipboardPaste', str);
     });
```
