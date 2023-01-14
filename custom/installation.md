# Installation

_**Requires Unity 2019.1+ with .NET 4.x+ Runtime**_

This package can be included into your project by either:

1. Installing the package via Unity's Package Manager (UPM) in the editor (recommended).
2. Importing the .unitypackage which you can download [here](https://github.com/orgs/liquiidio/packages?repo_name=UniversalAuthenticatorLibrarySharp). (TODO! Get final URL)
3. Manually add the files from the repo.
4. Installing it via NuGet. (for Standard .NET users)

#### 1. Installing via Unity Package Manager (UPM).

In your Unity project:

1. Open the Package Manager Window/Tab
2. Click Add Package From Git URL
3. Enter URL: 

Both Canvas and UIToolkit: `https://github.com/liquiidio/UniversalAuthenticatorLibrarySharp.git#upm_full` (TODO! Get final URL)

Just canvas: `https://github.com/liquiidio/UniversalAuthenticatorLibrarySharp.git#upm_canvas` (TODO! Get final URL)

Both Canvas and UIToolkit: `https://github.com/liquiidio/UniversalAuthenticatorLibrarySharp.git#upm_uitoolkit` (TODO! Get final URL)

***

#### 2. Importing the Unity Package.

Download the [UnityPackage here](https://github.com/orgs/liquiidio/packages?repo_name=UniversalAuthenticatorLibrarySharp). (TODO! Get final URL)

Then in your Unity project:

1. Open up the import a custom package window
2. Navigate to where you downloaded the file and open it.
3. Check all the relevant files needed (if this is a first time import, just select ALL) and click on import.

***

#### 3. Install manually.

Download this [project here](https://github.com/liquiidio/UniversalAuthenticatorLibrarySharp/releases).

  * [zip](https://github.com/liquiidio/UniversalAuthenticatorLibrarySharp/archive/refs/tags/1.0.0.zip) (TODO! Get final URL)
  * [tar.gz](https://github.com/liquiidio/UniversalAuthenticatorLibrarySharp/archive/refs/tags/1.0.0.tar.gz) (TODO! Get final URL)

Then in your Unity project, copy the sources from `UniversalAuthenticatorLibrarySharp` into your Unity `Assets` directory.

***

#### 4. Install via NuGet (for Standard .NET users only - No Unity3D)

#### .NET CLI (TODO!: Get correct command)

`>dotnet add package Liquiid.io.UniversalAuthenticatorLibrarySharp --version 1.0.24`

#### Package Manager (TODO!: Get correct command)

`PM> Install-Package Liquiid.io.UniversalAuthenticatorLibrarySharp -Version 1.0.24`
