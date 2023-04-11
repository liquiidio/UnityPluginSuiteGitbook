---
cover: broken-reference
coverY: 0
---

# Installation

_**Requires Unity 2019.1+ with .NET 4.x+ Runtime**_

This package can be included into your project by either:

1. Installing the package via Unity's Package Manager (UPM) in the editor (recommended).
2. Importing the .unitypackage which you can download [here](https://github.com/liquiidio/WcwUnityWebGl/releases/latest/download/wcwunity.unitypackage).
3. Manually add the files from the repo.

**Dependencies**

_None of the dependencies is contained in this Package_ and no matter which installation method you choose, you _have to install it manually_ in addition to this Package.

_**EosSharp**_

1. EosSharp is a library containing the necessary functionallity to serialize and deserialize Actions, Transactions, Blocks and other Data
2. In addition it contains the necessary functionallity for all kinds of cryptographic operations
3. Lastly it contains the functionallity allowing you and the AnchorLink-Library to access EOSIO or LEAP-based Nodes via their APIs.

<details>

<summary>EosSharp package installation</summary>

Follow the Instructions in[_EosSharp_](https://liquiidio.gitbook.io/unity-plugin-suite/v/eossharp/installation)\
\
**Or install the Package directly via UPM**

Installing via Unity Package Manager (UPM).

In your Unity project:

1. Open the Package Manager Window/Tab
2. Click Add Package From Git URL
3. Enter URL: `https://github.com/liquiidio/EosSharp.git#upm`

</details>

***

#### 1. Recommended - Installing via Unity Package Manager (UPM).

In your Unity project:

1. Open the Package Manager Window/Tab
2. Click Add Package From Git URL
3. Enter URL: `https://github.com/liquiidio/WcwUnity.git#upm`

***

#### 2. Importing the Unity Package.

Download the [UnityPackage here](https://github.com/liquiidio/WcwUnityWebGl/releases/latest/download/wcwunity.unitypackage).

Then in your Unity project:

1. Open up the import a custom package window
2. Navigate to where you downloaded the file and open it.
3. Check all the relevant files needed (if this is a first time import, just select ALL) and click on import.

***

#### 3. Install manually.

Download this [project here](https://github.com/liquiidio/WcwUnityWebGl/releases/latest).

* [zip](https://github.com/liquiidio/WcwUnityWebGl/archive/refs/tags/1.0.10.zip)
* [tar.gz](https://github.com/liquiidio/WcwUnityWebGl/archive/refs/tags/1.0.10.tar.gz)

Then in your Unity project, copy the sources from `WCWUnity` into your Unity `Assets` directory.
