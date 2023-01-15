#### System
To get information about accounts voting for Block Producers, use the following lines:
```csharp
       var systemClient = new SystemClient(new HttpClient());
       var voters = await systemClient.GetVotersAsync();
