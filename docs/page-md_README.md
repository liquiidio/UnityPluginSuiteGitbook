# page `md_README` 

[](https://github.com/liquiidio/AnchorLinkSharp-Private/actions/workflows/docs.yml)<br/>[](https://github.com/liquiidio/AnchorLinkSharp-Private/actions/workflows/deploy.yml)

## Anchor Link Sharp
Anchor Link SharpA native integration compatible with Unity3D and C# allowing users and developers to connect and communicate with Anchor Wallet and ESR-based applications. The Anchor & ESR Integration consists of multiple libraries for the ESR-Protocol, the Anchor-integration, Transports etc. which will be included via Submodules while being packaged and published as a single Package.

**Dependencies**

***NativeWebsocket***

WebSocket is a protocol that allows for real-time, two-way communication between a client and a server over a single, long-lived TCP connection. You can get installation instructions from this [link](https://github.com/endel/NativeWebSocket)

***[EosSharp](EosSharp.md)***

1. [EosSharp](EosSharp.md) is a library containing the necessary functionallity to serialize and deserialize Actions, Transactions, Blocks and other Data

1. In addition it contains the necessary functionallity for all kinds of cryptographic operations

1. Lastly it contains the functionallity allowing you and the AnchorLink-Library to access EOSIO or LEAP-based Nodes via their APIs.

*[EosSharp](EosSharp.md) is not contained in this Package* and no matter which installation method you choose, you *have to install it manually* in addition to this Package. \ \ If you havn't already installed it please follow the instructions in the section for [EosSharp](EosSharp.md) of this GitBook.

## Installation
Installation**_Requires Unity 2019.1+ with .NET 4.x+ Runtime_**

This package can be included into your project by either:

1. Installing the package via Unity's Package Manager (UPM) in the editor (recommended).

1. Importing the .unitypackage which you can download [here](https://github.com/liquiidio/AnchorLinkSharp-Private/releases/latest/download/anchorlinksharp.unitypackage).

1. Manually add the files in this repo.

1. Installing it via NuGet. (for Standard .NET users)

#### 1. Installing via Unity Package Manager (UPM).
1. Installing via Unity Package Manager (UPM).In your Unity project:

1. Open the Package Manager Window/Tab

1. Click on + icon and then click on "Add Package From Git URL"

1. Enter URL: `[https://github.com/liquiidio/AnchorLinkSharp-Private.git](https://github.com/liquiidio/AnchorLinkSharp-Private.git)#upm`

#### 2. Importing the Unity Package.
2. Importing the Unity Package.Download the [UnityPackage here](https://github.com/liquiidio/AnchorLinkSharp-Private/releases/latest/download/anchorlinksharp.unitypackage).

Then in your Unity project:

1. Open up the import a custom package window

1. Navigate to where you downloaded the file and open it.

1. Check all the relevant files needed (if this is a first time import, just select ALL) and click on import.

#### 3. Install manually.
3. Install manually.Download this [project here](https://github.com/liquiidio/AnchorLinkSharp-Private/releases/latest).

* [zip](https://github.com/liquiidio/AnchorLinkSharp-Private/archive/refs/tags/1.0.13.zip)<br/>

* [tar.gz](https://github.com/liquiidio/AnchorLinkSharp-Private/archive/refs/tags/1.0.13.tar.gz)<br/>

Then in your Unity project, copy the sources from `[AnchorLinkSharp](AnchorLinkSharp.md)` into your Unity `Assets` directory.

#### 4. Install via NuGet (for Standard .NET users only - No Unity3D)
4. Install via NuGet (for Standard .NET users only - No Unity3D)
#### .NET CLI
.NET CLI`>dotnet add package Liquiid.io.AnchorLinkSharp --version 1.0.3`

#### Package Manager
Package Manager`PM> Install-Package Liquiid.io.AnchorLinkSharp -Version 1.0.3`

## Usage
Usage.NET and Unity3D-compatible (Desktop, Mobile, WebGL) ApiClient for the different APIs. Endpoints have its own set of parameters that you may build up and pass in to the relevant function.

## Examples
Examples

#### Quick Start
Quick Start

1. Add one of the Transport-Prefabs (UiToolkitTransport or CanvasTransport) to your Scene.

1. Instantiate a new AnchorLink-object in one of your scripts, assign the Transport and configure your AnchorLink for the usage with WAX and the endpoints of your choice.

```cpp
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

#### Login
Login

1. Add a method calling the Login(identifier)-Method of the previously instantiated AnchorLink.

1. When this Method is called from your UI, the Transport will show and Ask the User to Open Anchor to Login.

1. After succesfull Login, data about the Account selected and additional session-data is returned your Application, available for use within the session-variable returned.

1. Storing the Session will allow you to to promt the User with a Transact-Request without the user having to Login again.

```cpp
internal LinkSession mySession;
internal async Task LoginAndStoreSession()
{
    try
    {
        var loginResult = await myLink.Login(Identifier);
        mySession = loginResult.Session;
        Debug.Log($"{mySession.Auth.actor} logged-in");
    }
    catch (Exception ex)
    {
        Debug.LogError(ex.Message);
    }
}
```

#### Transact (without Session)
Transact (without Session)

1. To transact without a Session, create a Method and pass a [EosSharp](EosSharp.md) Action-Object to it.

1. Call await AnchorLink.Transact(new TransactArgs(){Action = action); to transact.

1. When this Method is called from your UI or other Code, the Transport will show and Ask the User to Open Anchor to Login and afterwards to Sign a Transaction containing the Action passed.

```cpp
internal async Task TransactWithoutSession([EosSharp](EosSharp.md).[Core](EosSharp--Core.md).[Api](EosSharp--Core--Api.md).[v1](EosSharp--Core--Api--v1.md).[Action](EosSharp--Core--Api--v1--Action.md) action)
{
    var transactResult = await myLink.Transact(new TransactArgs() { [Action](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c) = action });
    Debug.Log($"Transaction broadcast! {transactResult.Processed}");
}
```

#### Transact (with Session)
Transact (with Session)

1. To transact without a Session, create a Method and pass a [EosSharp](EosSharp.md) Action-Object to it.

1. Call await LinkSession.Transact(new TransactArgs(){Action = action); to transact.

1. When this Method is called from your UI or other Code, the Transport will show and Ask the User to Sign a Transaction containing the Action passed (without requiring the User to Login again). 
```cpp
internal async Task TransactWithoutSession([EosSharp](EosSharp.md).[Core](EosSharp--Core.md).[Api](EosSharp--Core--Api.md).[v1](EosSharp--Core--Api--v1.md).[Action](EosSharp--Core--Api--v1--Action.md) action)
{
    var transactResult = await mySession.Transact(new TransactArgs() { [Action](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c) = action });
    Debug.Log($"Transaction broadcast! {transactResult.Processed}");
}
```

#### Token Transfer
Token Transfer

1. Following Example shows how a Token Transfer Action could be created and passed to the Transact-Method using a Session.

```cpp
// transfer tokens using a session
private async Task Transfer(string frmAcc, string toAcc, string qnty, string memo)
{
    var action = new [EosSharp](EosSharp.md).[Core](EosSharp--Core.md).[Api](EosSharp--Core--Api.md).[v1](EosSharp--Core--Api--v1.md).[Action](EosSharp--Core--Api--v1--Action.md)()
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

    try
    {
        var transactResult = await mySession.Transact(new TransactArgs() { [Action](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c) = action });
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

