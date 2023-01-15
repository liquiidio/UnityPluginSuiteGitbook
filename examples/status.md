To get information about the health of the API, use the following lines:
```csharp
       var statusClient = new StatusClient(new HttpClient());
       var health = await statusClient.HealthAsync();
```
