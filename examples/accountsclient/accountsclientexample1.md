---
description: Example showing how to use the AccountsClient
---

# AccountsClientExample1

```csharp
public async Task AccountsClientExample1()
{
    // Instantiate an AccountsClient
    var accountsClient = new AccountsClient(new HttpHandler());

    // Call the GetAccountAsync-Endpoint to retreive Account-related Data
    var getAccountsResult = await accountsClient.GetAccountAsync(account: "someacount",limit: 10, skip: 10, cancellationToken: CancellationToken.None);

    Console.WriteLine(getAccountsResult.Account);

    foreach (var action in getAccountsResult.Actions)
    {
        // Print diverse Information about the individual Actions received to the Console
        Console.WriteLine(action.Act.Account);
        Console.WriteLine(action.Act.Name);
        Console.WriteLine(action.ActionOrdinal);
        Console.WriteLine(action.BlockNum);
        Console.WriteLine(action.CpuUsageUs);
        Console.WriteLine(action.CreatorActionOrdinal);
        Console.WriteLine(action.GlobalSequence);
        Console.WriteLine(action.NetUsageWords);
        Console.WriteLine(action.Parent);
        Console.WriteLine(action.Notified);
        Console.WriteLine(action.Producer);
        Console.WriteLine(action.Receiver);
        Console.WriteLine(action.TrxId);
        
        // Print information about all Notified Accounts to the Console
        foreach (var notified in action.Notified)
        {
            Console.WriteLine(notified);
        }
        // Print information about all AccountRamDeltas to the Console
        foreach (var accountRamDelta in action.AccountRamDeltas)
        {
            Console.WriteLine(accountRamDelta.Account);
            Console.WriteLine(accountRamDelta.Delta);
        }
    }
}
```
