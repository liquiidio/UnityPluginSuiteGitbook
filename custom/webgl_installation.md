WebGL builds will require the index.html file to be customised.

<!--Download the full customised file <a download="index.html" href="/custom/downloads/index.html" title="Custom HTML file">here</a>.--> 
Download the full customised file [here](/custom/downloads/index.html).


[Installation](https://github.com/liquiidio/UnityPluginSuiteGitbook/blob/anchorlinksharp/custom/downloads/index.html)

```js
      script.onload = () => {
        createUnityInstance(canvas, config, (progress) => {
          progressBarFull.style.width = 100 * progress + "%";
        }).then((unityInstance) => {
	  // !!!
	   window.unityInstance = unityInstance; // <-- this line must be added to make websockets work!!!
          // !!!
          loadingBar.style.display = "none";
          fullscreenButton.onclick = () => {
            unityInstance.SetFullscreen(1);
          };
        }).catch((message) => {
          alert(message);
        });
```
