# page `md_eosiosigningrequestsharp_README` 

## EOSIO Request Signing Sharp (!TODO!)
EOSIO Request Signing Sharp (!TODO!)Connects with EOSIO Signing Request (ESR) protocol library. The full specification for ESR (Revision 3) is available [here](https://github.com/eosio-eps/EEPs/blob/master/EEPS/eep-7.md).

The ESR protocol allows for an application (dapp) to generate signature requests (transactions) which can then be passed to signers (wallets) for signature creation. These signature requests can be used within URI links, QR Codes, or other transports between applications and signers.

## Installation
Installation**_Requires Unity 2019.1+ with .NET 4.x+ Runtime_**

This package can be included into your project by either:

1. Installing the package via Unity's Package Manager (UPM) in the editor (recommended).

1. Importing the .unitypackage which you can download here.

1. Manually add the files in this repo. 

### 4. Installing it via NuGet.
4. Installing it via NuGet.

#### 1. Installing via Unity Package Manager (UPM).
1. Installing via Unity Package Manager (UPM).In your Unity project:

1. Open the Package Manager Window/Tab

1. Click on + icon and then click on "Add Package From Git URL"

1. Enter URL: `[https://github.com/endel/NativeWebSocket.git](https://github.com/endel/NativeWebSocket.git)#upm`

### // (!TODO!) ADD CORRECT LINK AND RELEVANT SCREENSHOT
// (!TODO!) ADD CORRECT LINK AND RELEVANT SCREENSHOT

#### 2. Importing the Unity Package.
2. Importing the Unity Package.Download the UnityPackage here <<&ndash; (Hyper link this). Then in your Unity project:

1. Open up the import a custom package window

1. Navigate to where you downloaded the file and open it.

1. Check all the relevant files needed (if this is a first time import, just select ALL) and click on import. (!TODO!) // ADD THE CORRECT SCREENSHOT FOR IMPORT WINDOW

#### 3. Install manually. (!TODO!)
3. Install manually. (!TODO!)Download this project there here <<&ndash; (Hyper link this to the zip download). Then in your Unity project:

1. Copy the sources from `NativeWebSocket/Assets/WebSocket` into your `Assets` directory.

#### 4. Install via NuGet (!TODO!)
4. Install via NuGet (!TODO!)

## Usage (!TODO!)
Usage (!TODO!).NET and Unity3D-compatible (Desktop, Mobile, WebGL) ApiClient for the different APIs. Endpoints have its own set of parameters that you may build up and pass in to the relevant function.

#### Examples (!TODO!)
Examples (!TODO!)Based on the different endpoints

```cpp
new AnchorLink(new LinkOptions()
            {
                Transport = this.Transport,
                // Uncomment this for and EOS session
                //ChainId = "aca376f206b8fc25a6ed44dbdc66547c36c6c33e3a119ffbeaef943642f0e906",
                //Rpc = "https://eos.greymass.com",
```
<br/>
```cpp
// WAX session
        ChainId = "1064487b3cd1a897ce03ae5b6a865651747e2e152090f99c1d19d44e01aea5a4",
        Rpc = "https://api.wax.liquidstudios.io",
        ZlibProvider = new NetZlibProvider(),
        Storage = new PlayerPrefsStorage()
    });
```

### Additional examples (!TODO!)
Additional examples (!TODO!)These are examples based on the specific plugin/package usage. Achor link - Creating and signing different kinds of transactions. <br/>

#### An example (!TODO!)
An example (!TODO!)AnchorLink

Token Transfer 
```cpp
// transfer tokens using a session
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
            var transactResult = await _link.Transact(new TransactArgs() { [Action](#_main_view_8cs_1a24e91c56095a0673d92c6eac6e069a3c) = action });
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
```
 Link? (!TODO!)

* NFT Transfer - link

* Create Permission - link

* Get Balanaces - link

