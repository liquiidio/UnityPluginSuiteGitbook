# Installation

_**Requires Unity 2019.1+ with .NET 4.x+ Runtime**_

This package can be included into your project by either:

1. Installing the package via Unity's Package Manager (UPM) in the editor (recommended).
2. Importing the .unitypackage which you can download [here](https://github.com/orgs/liquiidio/packages?repo\_name=AnchorLinkTransportSharp). (TODO! Get final URL)
3. Manually add the files from the repo.
4. Installing it via NuGet. (for Standard .NET users)

**Dependencies**

_**EosSharp**_

1. EosSharp is a library containing the necessary functionallity to serialize and deserialize Actions, Transactions, Blocks and other Data
2. In addition it contains the necessary functionallity for all kinds of cryptographic operations
3. Lastly it contains the functionallity allowing you to and the AnchorLink-Library to access EOSIO or LEAP-based Nodes via their APIS

_EosSharp is not contained in this Package_ and no matter which installation method you choose, you _have to install it manually_ in addition to this Package. \
\
If you havn't already installed it please follow the instructions in the section for EosSharp of this GitBook.

#### 1. Installing via Unity Package Manager (UPM).

In your Unity project:

1. Open the Package Manager Window/Tab
2. Click Add Package From Git URL
3. Enter URL: `https://github.com/endel/AnchorLinkTransportSharp.git#unity` (TODO! Get final URL)

#### 2. Importing the Unity Package.

Download the [UnityPackage here](https://github.com/orgs/liquiidio/packages?repo\_name=AnchorLinkTransportSharp). (TODO! Get final URL)

Then in your Unity project:

1. Open up the import a custom package window
2. Navigate to where you downloaded the file and open it.
3. Check all the relevant files needed (if this is a first time import, just select ALL) and click on import.

***

#### 3. Install manually.

Download this [project here](https://github.com/liquiidio/AnchorLinkTransportSharp/releases).

* [zip](https://github.com/orgs/liquiidio/packages?repo\_name=AnchorLinkTransportSharp) (TODO! Get final URL)
* [tar.gz](https://github.com/orgs/liquiidio/packages?repo\_name=AnchorLinkTransportSharp) (TODO! Get final URL)

Then in your Unity project, copy the sources from `AnchorLinkTransportSharp` into your Unity `Assets` directory.

***

#### 4. Install via NuGet (for Standard .NET users only - No Unity3D)

#### .NET CLI (TODO!: Get correct command)

`>dotnet add package Liquiid.io.AnchorLinkTransportSharp --version 1.0.24`

#### Package Manager (TODO!: Get correct command)

`PM> Install-Package Liquiid.io.AnchorLinkTransportSharp -Version 1.0.24`
