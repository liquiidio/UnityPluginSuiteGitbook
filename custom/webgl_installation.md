WebGL builds will require the index.html file to be customised.

Download the full customised file [here](/custom/downloads/index.html).

**Ensure that this line is added to make websockets work.**
```js
window.unityInstance = unityInstance;
```



### Final script should have this included

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
