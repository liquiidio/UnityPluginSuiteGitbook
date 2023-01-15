## Example calling the /v1/assets endpoint
 ### Initialise the Assets API
```csharp
     var assetsApi = AtomicAssetsApiFactory.Version1.AssetsApi;
```
 
 ### Call the assets endpoint
```csharp
     var assets = await assetsApi.Assets();
```
 
 ### Print all asset ids
```csharp
     assets.Data.ToList().ForEach(a => Console.WriteLine(a.AssetId));
```
 
 ##### Example output
 
1099567200114

1099567200113  

1099567200112  

1099567200111 

1099567200110  

1099567200109  

1099567200108 

1099567200107 

1099567200106  
