---
description: Example showing how to use the ChainClient
---

# ChainClientExample

```csharp
public async Task ChainClientExample()
{
    var chainClient = new ChainClient(new HttpHandler());

    // Request Account related Data
    var account = await chainClient.GetAccountAsync(accountName: "someaccount", cancellationToken: CancellationToken.None);

    // Print diverse Account related Data
    Console.WriteLine(account.AccountName);
    Console.WriteLine(account.CoreLiquidBalance);
    Console.WriteLine(account.CpuLimit);
    Console.WriteLine(account.CpuWeight);
    Console.WriteLine(account.Created);
    Console.WriteLine(account.HeadBlockNum);
    Console.WriteLine(account.HeadBlockTime);
    Console.WriteLine(account.LastCodeUpdate);
    Console.WriteLine(account.NetLimit);
    Console.WriteLine(account.NetWeight);

    // Print all permissions of this Account
    foreach (var permission in account.Permissions)
    {
        Console.WriteLine(permission);
    }
}
```
