# HistoryClientExample

```csharp
public async Task HistoryClientExample()
{
    var historyClient = new HistoryClient(new HttpHandler());

    // Query historical Actions of an Account
    var actions = await historyClient.GetActionsAsync(account: "someaccount", limit: 10, cancellationToken: CancellationToken.None);

    // Print diverse Data related to these Actions
    foreach (var action in actions.Actions)
    {
        Console.WriteLine(action.BlockNum);
        Console.WriteLine(action.TrxId);
        Console.WriteLine(action.Act.Name);
        Console.WriteLine(action.Act.Account);
        Console.WriteLine(action.CpuUsageUs);
        Console.WriteLine(action.ActionOrdinal);
        Console.WriteLine(action.CreatorActionOrdinal);
        Console.WriteLine(action.GlobalSequence);
        Console.WriteLine(action.Parent);
        Console.WriteLine(action.Producer);
        Console.WriteLine(action.Receiver);
        Console.WriteLine(action.NetUsageWords);
        Console.WriteLine(action.Timestamp);

        foreach (var notified in action.Notified)
        {
            Console.Write(notified);
        }

        foreach (var accountRamDelta in action.AccountRamDeltas)
        {
            Console.WriteLine(accountRamDelta.Account);
            Console.WriteLine(accountRamDelta.Delta);
        }
    }
}
```
