# Quick Start

**Quick Start**

1. Add one of the Transport-Prefabs (UiToolkitTransport or CanvasTransport) to your Scene.
2. Instantiate a new AnchorLink-object in one of your scripts, assign the Transport and configure your AnchorLink for the usage with WAX and the endpoints of your choice.

```csharp
   [SerializeField]
   internal UnityTransport Transport;
   internal AnchorLink myLink;

   public void Start(){
	   myLink = new AnchorLink(new LinkOptions()
	   {
		   Transport = this.Transport,
		   ChainId = "1064487b3cd1a897ce03ae5b6a865651747e2e152090f99c1d19d44e01aea5a4",
		   Rpc = "https://api.wax.liquidstudios.io",
	  });
  }
```
