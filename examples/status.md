Get Information about the health of the API
```csharp
       var statusClient = new StatusClient(new HttpClient());
       var health = await statusClient.HealthAsync();
```
