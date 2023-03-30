---
description: Example showing how to use the StatsClient
---

# StatsClientExample

```csharp
public async Task StatsClientExample()
{
    var statsClient = new StatsClient(new HttpHandler());

    // Query information about missed Blocks by Producers
    var producerstats = await statsClient.GetMissedBlocksAsync(producer: "someproducer");

    foreach (var producerstatsEvent in producerstats.Events)
    {
        Console.WriteLine(producerstatsEvent.LastBlock);
        Console.WriteLine(producerstatsEvent.Producer);
        Console.WriteLine(producerstatsEvent.ScheduleVersion);
        Console.WriteLine(producerstatsEvent.Size);
        Console.WriteLine(producerstatsEvent.Timestamp);
    }
}
```
