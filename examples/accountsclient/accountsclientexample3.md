---
description: Example showing how to use the AccountsClient
---

# AccountsClientExample3

```csharp
public async Task AccountsClientExample3()
{
    var accountsClient = new AccountsClient(new HttpHandler());

    // Request all Accounts that are controlled by an individual Account
    var tokens = await accountsClient.GetTokensAsync(account: "someaccount", cancellationToken: CancellationToken.None);

    // Print the Account Name of the Token Owner
    Console.WriteLine(tokens.Account);

    foreach (var token in tokens.Tokens)
    {
        // Print all Tokens
        Console.WriteLine($"{token.Amount}{token.Symbol} of contract {token.Contract} with precision {token.Precision}");
    }
}
```
