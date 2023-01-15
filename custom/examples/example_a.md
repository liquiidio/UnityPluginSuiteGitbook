#### Accounts
To query various details about a specific account on the blockchain, create a method and add the following lines:
```csharp
       var accountsClient = new AccountsClient(new HttpClient());
       var account = await accountsClient.GetAccountAsync("eosio");
```
