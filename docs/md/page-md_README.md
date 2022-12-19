# page `md_README` 

## HyperionApiClient
HyperionApiClient

[](https://github.com/liquiidio/HyperionApiClient-Private/actions/workflows/dotnet-build.yml)[](https://github.com/liquiidio/HyperionApiClient-Private/actions/workflows/dotnet-test.yml)

*.NET and Unity3D-compatible (Desktop, Mobile, WebGL) Client-Library for Hyperion History APIs*

*See [Hyperion History by EosRio](https://eosrio.io/hyperion/)*

### ### INSTALLATION
### INSTALLATIONA step by step series of examples that tell you how to get a package. There is the Unity package,Unity Package Manager GitHub and Nuget Package.

1. Say what the steps will be for each package

Give the example

1. A step by step explanation on how to clone and import the repository

give the instructions

### Usage
Usage.NET and Unity3D-compatible (Desktop, Mobile, WebGL) ApiClient for the different APIs. Endpoints have its own set of parameters that you may build up and pass in to the relevant function.

#### Examples
Examples
#### Accounts
AccountsQuery various details about a specific account on the blockchain. 
```cpp
var accountsClient = new AccountsClient(new HttpClient());
var account = await accountsClient.GetAccountAsync("eosio");
```

#### Chain
ChainGet the ABI for a contract based on its account name 
```cpp
var chainClient = new ChainClient(new HttpClient());
var abi = await chainClient.GetAbiAsync("eosio");
```

#### History
HistoryGet actions for a specific Account 
```cpp
var historyClient = new HistoryClient(new HttpClient());
var actions = await historyClient.GetActionsAsync(null, null, "kingcoolcorv");
```

#### Stats
StatsGet action and transaction stats for a given period 
```cpp
var statsClient = new StatsClient(new HttpClient());
var actionUsage = await statsClient.GetActionUsageAsync("1h");
```

#### Status
StatusGet Information about the health of the API 
```cpp
var statusClient = new StatusClient(new HttpClient());
var health = await statusClient.HealthAsync();
```

#### System
SystemGet Information about Accounts voting for Block Producers 
```cpp
var systemClient = new SystemClient(new HttpClient());
var voters = await systemClient.GetVotersAsync();
```

