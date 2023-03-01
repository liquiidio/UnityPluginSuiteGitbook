# page `md_README` 

[](https://github.com/liquiidio/AtomicAssetsApiClient-Private/actions/workflows/dotnet-build.yml)[](https://github.com/liquiidio/AtomicAssetsApiClient-Private/actions/workflows/dotnet-test.yml)

## AtomicMarketApiClient
AtomicMarketApiClient.NET and Unity3D-compatible (Desktop, Mobile, WebGL) ApiClient for AtomicMarket

## Installation
Installation**_Requires Unity 2019.1+ with .NET 4.x+ Runtime_**

This package can be included into your project by either:

1. Installing the package via Unity's Package Manager (UPM) in the editor (recommended).

1. Importing the .unitypackage which you can download [here](https://github.com/liquiidio/AtomicMarketApiClient-Private/releases/latest/download/atomicmarket.unitypackage).

1. Manually add the files in this repo. 

### 4. Installing it via NuGet.
4. Installing it via NuGet.

#### 1. Installing via Unity Package Manager (UPM).
1. Installing via Unity Package Manager (UPM).In your Unity project:

1. Open the Package Manager Window/Tab

1. Click on + icon and then click on "Add Package From Git URL"

1. Enter URL: `[https://github.com/liquiidio/AtomicMarketApiClient-Private.git](https://github.com/liquiidio/AtomicMarketApiClient-Private.git)#upm`

#### 2. Importing the Unity Package.
2. Importing the Unity Package.Download the [UnityPackage here](https://github.com/liquiidio/AtomicMarketApiClient-Private/releases/latest/download/atomicmarket.unitypackage).

Then in your Unity project:

1. Open up the import a custom package window

1. Navigate to where you downloaded the file and open it.

1. Check all the relevant files needed (if this is a first time import, just select ALL) and click on import.

#### 3. Install manually.
3. Install manually.Download this [project here](https://github.com/liquiidio/AtomicMarketApiClient-Private/releases/latest).

* [zip](https://github.com/liquiidio/AtomicMarketApiClient-Private/archive/refs/tags/1.0.10.zip)

* [tar.gz](https://github.com/liquiidio/AtomicMarketApiClient-Private/archive/refs/tags/1.0.10.tar.gz)

Then in your Unity project, copy the sources from `[AtomicMarketApiClient](AtomicMarketApiClient.md)` into your Unity `Assets` directory.

#### 4. Install via NuGet (for Standard .NET users only - No Unity3D)
4. Install via NuGet (for Standard .NET users only - No Unity3D)
#### .NET CLI
.NET CLI`> dotnet add package Liquiid.io.AtomicMarket --version 1.0.6`

#### Package Manager
Package Manager`PM> Install-Package Liquiid.io.AtomicMarket -Version 1.0.6`

## Usage
Usage.NET and Unity3D-compatible (Desktop, Mobile, WebGL) ApiClient for the different APIs. Endpoints have its own set of parameters that you may build up and pass in to the relevant function.

## Examples
Examples

### Example calling the /v1/assets endpoint
Example calling the /v1/assets endpoint

#### Initialise the Assets API
Initialise the Assets API
```cpp
var assetsApi = AtomicAssetsApiFactory.Version1.AssetsApi;
```

#### Call the assets endpoint
Call the assets endpoint
```cpp
var assets = await assetsApi.Assets();
```

#### Print all asset ids
Print all asset ids
```cpp
assets.Data.ToList().ForEach(a => Console.WriteLine(a.AssetId));
```

## Example output

1099567200114

1099567200113 <br/>

1099567200112 <br/>

1099567200111

1099567200110 <br/>

1099567200109 <br/>

1099567200108

1099567200107

1099567200106 <br/>
 ...

### Example calling the /v1/assets endpoint with parameters
Example calling the /v1/assets endpoint with parameters

#### Initialise the Assets API
Initialise the Assets API
```cpp
var assetsApi = AtomicAssetsApiFactory.Version1.AssetsApi;
```

#### Build up the AssetsParameters with the AssetsUriParameterBuilder
Build up the AssetsParameters with the AssetsUriParameterBuilder
```cpp
var builder = new AssetsUriParameterBuilder().WithLimit(1);
```

#### Call the assets endpoint, passing in the builder
Call the assets endpoint, passing in the builder
```cpp
var assets = await assetsApi.Assets(builder);
```

#### Print all asset ids
Print all asset ids
```cpp
assets.Data.ToList().ForEach(a => Console.WriteLine(a.AssetId));
```
## Example output

1099567200114

1099567200113 <br/>

1099567200112 <br/>

1099567200111

1099567200110 <br/>

1099567200109 <br/>

1099567200108

1099567200107

1099567200106

....

