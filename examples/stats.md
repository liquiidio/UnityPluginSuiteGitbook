#### Stats
To get action and transaction stats for a given period, create a new method and add these lines:
```csharp
       var statsClient = new StatsClient(new HttpClient());
       var actionUsage = await statsClient.GetActionUsageAsync("1h");
```
