To get information about the health of the API, create a new method and add the following:
```csharp
       var statusClient = new StatusClient(new HttpClient());
       var health = await statusClient.HealthAsync();
```
