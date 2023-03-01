# page `md_README` 

[](https://github.com/liquiidio/HyperionApiClient-Private/actions/workflows/build.yml)[](https://github.com/liquiidio/HyperionApiClient-Private/actions/workflows/test.yml)[](https://github.com/liquiidio/HyperionApiClient-Private/actions/workflows/docs.yml)[](https://github.com/liquiidio/HyperionApiClient-Private/actions/workflows/deploy.yml)

## HyperionApiClient
HyperionApiClient*.NET and Unity3D-compatible (Desktop, Mobile, WebGL) Client-Library for Hyperion History APIs*

*See [Hyperion History by EosRio](https://eosrio.io/hyperion/)*

### ### INSTALLATION
### INSTALLATIONA step by step series of examples that tell you how to get a package. There is the Unity package,Unity Package Manager GitHub and Nuget Package.

1. Say what the steps will be for each package

Give the example

1. A step by step explanation on how to clone and import the repository

give the instructions

### Usage
Usage.NET and Unity3D-compatible (Desktop, Mobile, WebGL) ApiClient for the different APIs. Endpoints have its own set of parameters that you may build up and pass in to the relevant function.

## ### Examples
### Examples

## HyperionApiClient
HyperionApiClient*.NET and Unity3D-compatible (Desktop, Mobile, WebGL) Client-Library for Hyperion History APIs*

*See [Hyperion History by EosRio](https://eosrio.io/hyperion/)*

## Installation
Installation**_Requires Unity 2019.1+ with .NET 4.x+ Runtime_**

This package can be included into your project by either:

1. Installing the package via Unity's Package Manager (UPM) in the editor (recommended).

1. Importing the .unitypackage which you can download [here](https://github.com/liquiidio/HyperionApiClient-Private/releases/latest/download/hyperion.unitypackage).

1. Manually add the files in this repo. 

### 4. Installing it via NuGet.
4. Installing it via NuGet.

#### 1. Installing via Unity Package Manager (UPM).
1. Installing via Unity Package Manager (UPM).In your Unity project:

1. Open the Package Manager Window/Tab

1. Click on + icon and then click on "Add Package From Git URL"

1. Enter URL: `[https://github.com/liquiidio/HyperionApiClient-Private.git](https://github.com/liquiidio/HyperionApiClient-Private.git)#upm`

#### 2. Importing the Unity Package.
2. Importing the Unity Package.Download the [UnityPackage here](https://github.com/liquiidio/HyperionApiClient-Private/releases/latest/download/hyperion.unitypackage).

1. Open up the import a custom package window

1. Navigate to where you downloaded the file and open it.

1. Check all the relevant files needed (if this is a first time import, just select ALL) and click on import.

#### 3. Install manually.
3. Install manually.Download this [project here](https://github.com/liquiidio/HyperionApiClient-Private/releases/latest).

* [zip](https://github.com/liquiidio/HyperionApiClient-Private/archive/refs/tags/1.0.10.zip)

* [tar.gz](https://github.com/liquiidio/HyperionApiClient-Private/archive/refs/tags/1.0.10.tar.gz)

Then in your Unity project, copy the sources from `[HyperionApiClient](HyperionApiClient.md)` into your Unity `Assets` directory.

#### 4. Install via NuGet (for Standard .NET users only - No Unity3D)
4. Install via NuGet (for Standard .NET users only - No Unity3D)
#### .NET CLI
.NET CLI`> dotnet add package Liquiid.io.Hyperion --version 1.0.3`

#### Package Manager
Package Manager`PM> Install-Package Liquiid.io.Hyperion -Version 1.0.3`

## Usage
Usage.NET and Unity3D-compatible (Desktop, Mobile, WebGL) ApiClient for the different APIs. Endpoints have its own set of parameters that you may build up and pass in to the relevant function.

## Examples
Examples
## Accounts
AccountsQuery various details about a specific account on the blockchain. 
```cpp
var accountsClient = new AccountsClient(new HttpClient());
var account = await accountsClient.GetAccountAsync("eosio");
```

## Chain
ChainGet the ABI for a contract based on its account name 
```cpp
var chainClient = new ChainClient(new HttpClient());
var abi = await chainClient.GetAbiAsync("eosio");
```

## History
HistoryGet actions for a specific Account 
```cpp
var historyClient = new HistoryClient(new HttpClient());
var actions = await historyClient.GetActionsAsync(null, null, "kingcoolcorv");
```

## Stats
StatsGet action and transaction stats for a given period 
```cpp
var statsClient = new StatsClient(new HttpClient());
var actionUsage = await statsClient.GetActionUsageAsync("1h");
```

## Status
StatusGet Information about the health of the API 
```cpp
var statusClient = new StatusClient(new HttpClient());
var health = await statusClient.HealthAsync();
```

## System
SystemGet Information about Accounts voting for Block Producers 
```cpp
var systemClient = new SystemClient(new HttpClient());
var voters = await systemClient.GetVotersAsync();
```

