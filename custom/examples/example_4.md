## Getting assets available for trading on the exchange

```csharp

async Task GettingAllTheAssets()
{
    // Initialize the v1 assets API
    var assetsApi = AtomicMarketApiFactory.Version1.AssetsApi;

    //Getting all the assets that are available for trading on the exchange.
    var assets = await assetsApi.Assets();

    // Print their IDs on the console.
    assets.Data.ToList().ForEach(a => Console.WriteLine(a.AssetId));
}

 ```
