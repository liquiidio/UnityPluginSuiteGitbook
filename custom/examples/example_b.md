## Example calling the /v1/assets endpoint with parameters
 ### Initialise the Assets API
```csharp
     var assetsApi = AtomicAssetsApiFactory.Version1.AssetsApi();
```
 
 ### Build up the AssetsParameters with the AssetsUriParameterBuilder
```csharp
     var builder = new AssetsUriParameterBuilder().WithLimit(1);
```
 
 ### Call the /assets endpoint, passing in the builder
```csharp
     var assets = assetsApi.Assets(builder);
```
 
 ### Print all asset ids
```csharp
     assets.Data.ToList().ForEach(a => Console.WriteLine(a.AssetId));
```
