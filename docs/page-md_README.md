# page `md_README` 

## Anchor Link Sharp
Anchor Link SharpA native integration compatible with Unity3D and C# allowing users and developers to connect and communicate with Anchor Wallet and ESR-based applications. The Anchor & ESR Integration consists of multiple libraries for the ESR-Protocol, the Anchor-integration, Transports etc. which will be included via Submodules while being packaged and published as a single Package.

Link to >>AnchorLinkTransportSharp<< and >>ESR Sharp<<

## Installation (!TODO!)
Installation (!TODO!)**_Requires Unity 2019.1+ with .NET 4.x+ Runtime_**

This package can be included into your project by either:

1. Installing the package via Unity's Package Manager (UPM) in the editor (recommended).

1. Importing the .unitypackage which you can download here.

1. Manually add the files in this repo.

1. Installing it via NuGet.

#### 1. Installing via Unity Package Manager (UPM).
1. Installing via Unity Package Manager (UPM).In your Unity project:

1. Open the Package Manager Window/Tab

1. Click Add Package From Git URL 

### 3. Enter URL:  <tt>https://github.com/endel/NativeWebSocket.git#upm</tt>
3. Enter URL:  <tt>https://github.com/endel/NativeWebSocket.git#upm</tt>

#### 2. Importing the Unity Package.
2. Importing the Unity Package.Download the UnityPackage here. Then in your Unity project:

1. Open up the import a custom package window

1. Navigate to where you downloaded the file and open it. 

### 3. Check all the relevant files needed (if this is a first time import, just select ALL) and click on import.
3. Check all the relevant files needed (if this is a first time import, just select ALL) and click on import.

#### 3. Install manually.
3. Install manually.Download this project there here. Then in your Unity project:

1. Copy the sources from `NativeWebSocket/Assets/WebSocket` into your `Assets` directory.

#### 4. Install via NuGet
4. Install via NuGetBlack magic

### Usage (!TODO!)
Usage (!TODO!).NET and Unity3D-compatible (Desktop, Mobile, WebGL) ApiClient for the different APIs. Endpoints have its own set of parameters that you may build up and pass in to the relevant function.

#### Examples
ExamplesBased on the different endpoints

new AnchorLink(new LinkOptions() { Transport = this.Transport, // Uncomment this for and EOS session //ChainId = "aca376f206b8fc25a6ed44dbdc66547c36c6c33e3a119ffbeaef943642f0e906", //Rpc = "https://eos.greymass.com",

<br/>// WAX session
        ChainId = "1064487b3cd1a897ce03ae5b6a865651747e2e152090f99c1d19d44e01aea5a4",
        Rpc = "https://api.wax.liquidstudios.io",
        ZlibProvider = new NetZlibProvider(),
        Storage = new PlayerPrefsStorage()
    });

### Additional examples (!TODO!)
Additional examples (!TODO!)These are examples based on the specific plugin/package usage. Achor link - Creating and signing different kinds of transactions. <br/>

#### An example
An exampleAnchorLink

Token Transfer // transfer tokens using a session
    private async Task Transfer(string frmAcc, string toAcc, string qnty, string memo)
    {
        var action = new EosSharp.Core.Api.v1.Action()
        {
            account = "eosio.token",
            name = "transfer",
            authorization = new List<PermissionLevel>() { _session.Auth },
            data = new Dictionary<string, object>
            {
                {"from", frmAcc},
                {"to", toAcc},
                {"quantity", qnty},
                {"memo", memo}
            }
        };

        //Debug.Log($"Session {_session.Identifier}");
        //Debug.Log($"Link: {_link.ChainId}");

        try
        {
            var transactResult = await _link.Transact(new TransactArgs() { Action = action });
            // OR (see next line)
            //var transactResult = await _session.Transact(new TransactArgs() { Action = action });
            Debug.Log($"Transaction broadcast! {transactResult.Processed}");

            waitCoroutine = StartCoroutine(SwitchPanels(Transport.currentPanel, CustomActionsPanel, 1.5f));

        }
        catch (Exception e)
        {
            Debug.Log(e);
            throw;
        }
    }
 Link? (!TODO!)

* NFT Transfer - link

* Create Permission - link

* Get Balanaces - link

