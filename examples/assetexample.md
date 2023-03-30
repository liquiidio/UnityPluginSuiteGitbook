# AssetExample

```csharp
public async Task AssetExample()
{
    // Get a specific Asset by it's assetId
    var someAsset = await AtomicMarketApiFactory.Version1.AssetsApi.Asset("someassetId");

    // Print diverse Data about the asset
    Console.WriteLine(someAsset.Data.AssetId);
    Console.WriteLine(someAsset.Data.Burnable);
    Console.WriteLine(someAsset.Data.Contract);
    Console.WriteLine(someAsset.Data.MintedAtBlock);
    Console.WriteLine(someAsset.Data.MintedAtTime);
    Console.WriteLine(someAsset.Data.Name);
    Console.WriteLine(someAsset.Data.Owner);
    Console.WriteLine(someAsset.Data.Contract);

    // Print diverse Data about the backed Tokens
    foreach (var backedToken in someAsset.Data.BackedTokens)
    {
        Console.WriteLine(backedToken.Amount);
        Console.WriteLine(backedToken.TokenContract);
        Console.WriteLine(backedToken.TokenPrecision);
        Console.WriteLine(backedToken.TokenSymbol);
    }

    // Print diverse Data about the collection this asset belongs to
    Console.WriteLine(someAsset.Data.Collection.Name);
    Console.WriteLine(someAsset.Data.Collection.AllowNotify);
    Console.WriteLine(someAsset.Data.Collection.Author);
    Console.WriteLine(someAsset.Data.Collection.CollectionName);
    Console.WriteLine(someAsset.Data.Collection.CreatedAtBlock);
    Console.WriteLine(someAsset.Data.Collection.CreatedAtTime);
    Console.WriteLine(someAsset.Data.Collection.Image);
    Console.WriteLine(someAsset.Data.Collection.MarketFee);

    // Print information about authorized accounts
    foreach (var authorizedAccount in someAsset.Data.Collection.AuthorizedAccounts)
    {
        Console.WriteLine(authorizedAccount);
    }

    // Print information about notified accounts
    foreach (var notifyAccount in someAsset.Data.Collection.NotifyAccounts)
    {
        Console.Write(notifyAccount);
    }
}
```
