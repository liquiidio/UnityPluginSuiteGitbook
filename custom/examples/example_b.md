#### Chain
Get the ABI for a contract based on its account name
```csharp
       var chainClient = new ChainClient(new HttpClient());
       var abi = await chainClient.GetAbiAsync("eosio");
```
