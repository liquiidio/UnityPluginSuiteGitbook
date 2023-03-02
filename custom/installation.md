# Installation

_**Requires Unity 2019.1+ with .NET 4.x+ Runtime**_

This package can be included into your project by either:

1. Installing the package via Unity's Package Manager (UPM) in the editor (recommended).
2. Importing the .unitypackage which you can download [here](https://github.com/liquiidio/UniversalAuthenticatorLibrarySharp/releases/latest/download/universalauthenticatorlibrarysharp.unitypackage). 
3. Manually add the files from the repo.

**Dependencies**

_None of the dependencies is contained in this Package_ and no matter which installation method you choose, you _have to install it manually_ in addition to this Package.

_**EosSharp**_

1. EosSharp is a library containing the necessary functionallity to serialize and deserialize Actions, Transactions, Blocks and other Data
2. In addition it contains the necessary functionallity for all kinds of cryptographic operations
3. Lastly it contains the functionallity allowing you and the AnchorLink-Library to access EOSIO or LEAP-based Nodes via their APIs.

<details>

<summary>EosSharp package installation</summary>
 
 
 
Follow the Instructions in [ ](https://liquiidio.gitbook.io/unity-plugin-suite/v/eossharp/installation)[*EosSharp*](https://liquiidio.gitbook.io/unity-plugin-suite/v/eossharp/installation)\
 \
__Or install the Package directly via UPM__
  
Installing via Unity Package Manager (UPM).

In your Unity project:

1. Open the Package Manager Window/Tab
2. Click Add Package From Git URL
3. Enter URL: `https://github.com/liquiidio/EosSharp-Private.git#upm`

</details>

_**AnchorLinkSharp**_

Allows users and developers to connect and communicate with Anchor Wallet and ESR-based applications. The Anchor & ESR Integration consists of multiple libraries for the ESR-Protocol, the Anchor-integration, Transports among others.

<details>

<summary>AnchorLinkSharp package installation</summary>
 
 
 
Follow the Instructions in [ ](https://liquiidio.gitbook.io/unity-plugin-suite/v/anchorlink/installation)[*AnchorLinkSharp*](https://liquiidio.gitbook.io/unity-plugin-suite/v/anchorlink/installation)\
 \
__Or install the Package directly via UPM__
  
Installing via Unity Package Manager (UPM).

In your Unity project:

1. Open the Package Manager Window/Tab
2. Click Add Package From Git URL
3. Enter URL: `https://github.com/liquiidio/AnchorLinkSharp-Private.git#upm`

</details>

_**WaxCloudWallet (WCW)**_

A combination of local HttpListeners receiving OAuth-Callbacks from WCW-related web-adresses opened through the WebView-Plugin, gathering necessary initial information like OAuth-Tokens, followed by regular non-browser-based (non-WebView required) communication with the WCW-API/Server.

 <details>

<summary>WCW package installation</summary>
 
 
 
Follow the Instructions in [ ](https://liquiidio.gitbook.io/unity-plugin-suite/v/wcwunity/installation)[*WCW*](https://liquiidio.gitbook.io/unity-plugin-suite/v/wcwunity/installation)\
 \
__Or install the Package directly via UPM__
  
Installing via Unity Package Manager (UPM).

In your Unity project:

1. Open the Package Manager Window/Tab
2. Click Add Package From Git URL
3. Enter URL: `https://github.com/liquiidio/WcwUnityWebGl.git#upm`

</details>

***

#### 1. Installing via Unity Package Manager (UPM).

In your Unity project:

1. Open the Package Manager Window/Tab
2. Click Add Package From Git URL
3. Enter URL: 

`https://github.com/liquiidio/UniversalAuthenticatorLibrarySharp.git#upm` 

***

#### 2. Importing the Unity Package.

Download the [UnityPackage here](https://github.com/liquiidio/UniversalAuthenticatorLibrarySharp/releases/latest/download/universalauthenticatorlibrarysharp.unitypackage). 

Then in your Unity project:

1. Open up the import a custom package window
2. Navigate to where you downloaded the file and open it.
3. Check all the relevant files needed (if this is a first time import, just select ALL) and click on import.

***

#### 3. Install manually.

Download this [project here](https://github.com/liquiidio/UniversalAuthenticatorLibrarySharp/releases/latest).

  * [zip](https://github.com/liquiidio/UniversalAuthenticatorLibrarySharp/archive/refs/tags/1.0.13.zip)
  * [tar.gz](https://github.com/liquiidio/UniversalAuthenticatorLibrarySharp/archive/refs/tags/1.0.13.tar.gz) 

Then in your Unity project, copy the sources from `UniversalAuthenticatorLibrarySharp` into your Unity `Assets` directory.
