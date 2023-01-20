 ### Getting a filtered assets list that is available for trading
 ```csharp

async Task GettingFilteredAssetsList()
{
    // Initialize the v1 assets API
    var assetsApi = AtomicAssetsApiFactory.Version1.AssetsApi;

    // Build up the AssetsParameters with the AssetsUriParameterBuilder
    // This can be used to fine tune the kind of results we want
    // For example, here were limiting the results to just five assets
    // More information can be found on the documentation
    var builder = new AssetsUriParameterBuilder().WithLimit(5);

    //Getting all the assets that are available for trading on the exchange.
    var assets = await assetsApi.Assets(builder);

    // Print their IDs on the console.
    assets.Data.ToList().ForEach(a => Console.WriteLine(a.AssetId));
}

 ```
