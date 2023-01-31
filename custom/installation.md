# Installation

_**Requires Unity 2019.1+ with .NET 4.x+ Runtime**_

This package can be included into your project by either:

1. Installing the package via Unity's Package Manager (UPM) in the editor (recommended).
2. Importing the .unitypackage which you can download [here](https://github.com/liquiidio/AtomicAssetsApiClient-Private/releases/latest/download/io.liquiid.atomicassets.unitypackage). (TODO! Get final URL)
3. Manually add the files from the repo.
4. Installing it via NuGet. (for Standard .NET users)

#### 1. Installing via Unity Package Manager (UPM).

In your Unity project:

1. Open the Package Manager Window/Tab
2. Click Add Package From Git URL
3. Enter URL: `https://github.com/liquiidio/AtomicAssetsApiClient-Private.git#upm` (TODO! Get final URL)

***

#### 2. Importing the Unity Package.

Download the [UnityPackage here](https://github.com/liquiidio/AtomicAssetsApiClient-Private/releases/latest/download/io.liquiid.atomicassets.unitypackage). (TODO! Get final URL)

Then in your Unity project:

1. Open up the import a custom package window
2. Navigate to where you downloaded the file and open it.
3. Check all the relevant files needed (if this is a first time import, just select ALL) and click on import.

***

#### 3. Install manually.

Download this [project here](https://github.com/liquiidio/AtomicAssetsApiClient-Private/releases).

  * [zip](https://github.com/liquiidio/AtomicAssetsApiClient-Private/archive/refs/tags/1.0.33.zip) (TODO! Get final URL)
  * [tar.gz](https://github.com/liquiidio/AtomicAssetsApiClient-Private/archive/refs/tags/1.0.33.tar.gz) (TODO! Get final URL)

Then in your Unity project, copy the sources from `AtomicAssetsApiClient` into your Unity `Assets` directory.

***

#### 4. Install via NuGet (for Standard .NET users only - No Unity3D)

#### .NET CLI

`> dotnet add package Liquiid.io.AtomicAssets --version 1.0.24`

#### Package Manager

`PM> Install-Package Liquiid.io.AtomicAssets -Version 1.0.24`
