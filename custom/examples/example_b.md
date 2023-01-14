## Example calling the /v1/assets endpoint with parameters
### Initialise the Assets API
```csharp
     var assetsApi = AtomicAssetsApiFactory.Version1.AssetsApi;
```
 
### Build up the AssetsParameters with the AssetsUriParameterBuilder
```csharp
     var builder = new AssetsUriParameterBuilder().WithLimit(1);
```
 
### Call the /assets endpoint, passing in the builder
```csharp
     var assets = await assetsApi.Assets(builder);
```


### Print all asset ids

```csharp
assets.Data.ToList().ForEach(a => Console.WriteLine(a.AssetId));
 ```

1099567200114

1099567200113  

1099567200112  

1099567200111 

1099567200110  

1099567200109  

1099567200108 

1099567200107 

1099567200106 
