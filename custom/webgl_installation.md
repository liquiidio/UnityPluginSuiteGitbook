WebGL builds will require the index.html file to be customised.

<!--Download the full customised file <a download="index.html" href="/custom/downloads/index.html" title="Custom HTML file">here</a>.--> 
Download the full customised file [here](/custom/downloads/index.html).

Ensure that this line is added to make websockets work.

<details>
  <summary>Spoiler warning</summary>
  
  Spoiler text. Note that it's important to have a space after the summary tag. You should be able to write any markdown you want inside the `<details>` tag... just make sure you close `<details>` afterward.
  
  ```javascript
  console.log("I'm a code block!");
  ```
  
</details>

```js
window.unityInstance = unityInstance;
```


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
