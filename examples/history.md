#### History
To get actions for a specific account, use the following lines:
```csharp
       var historyClient = new HistoryClient(new HttpClient());
       var actions = await historyClient.GetActionsAsync(null, null, "kingcoolcorv");
```
