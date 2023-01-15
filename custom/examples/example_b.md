#### Chain
To get the ABI for a contract based on its account name, use the following lines:
```csharp
       var chainClient = new ChainClient(new HttpClient());
       var abi = await chainClient.GetAbiAsync("eosio");
```
