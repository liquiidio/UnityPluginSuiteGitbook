#### Stats
Get action and transaction stats for a given period
```csharp
       var statsClient = new StatsClient(new HttpClient());
       var actionUsage = await statsClient.GetActionUsageAsync("1h");
```
