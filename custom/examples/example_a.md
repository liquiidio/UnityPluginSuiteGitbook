#### Accounts
Query various details about a specific account on the blockchain.
```csharp
       var accountsClient = new AccountsClient(new HttpClient());
       var account = await accountsClient.GetAccountAsync("eosio");
```
