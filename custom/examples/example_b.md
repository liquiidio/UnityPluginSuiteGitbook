#### Chain
To get the ABI for a contract based on its account name, create a new method and use these lines:
```csharp
       var chainClient = new ChainClient(new HttpClient());
       var abi = await chainClient.GetAbiAsync("eosio");
```
