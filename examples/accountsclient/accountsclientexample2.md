---
description: Example showing how to use the AccountsClient
---

# AccountsClientExample2

```csharp
public async Task Test2()
{
    var accountsClient = new AccountsClient(new HttpHandler());

    // Request all Accounts that are controlled by an individual Account
    var controlledAccounts = await accountsClient.GetControlledAccountsAsync(controllingAccount: "someaccount",
        cancellationToken: CancellationToken.None);

    foreach (var controlledAccount in controlledAccounts.ControlledAccounts)
    {
        // Print all controlled Accounts
        Console.WriteLine(controlledAccount);
    }
}
```
