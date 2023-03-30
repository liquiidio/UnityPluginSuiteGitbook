# AuctionExample

```csharp
public async Task AuctionExample()
{
    // Get a specific Auction by it's actionId
    var someAuction = await AtomicMarketApiFactory.Version1.AuctionsApi.Auction(1234);

    // Print diverse Data about this Auction
    Console.WriteLine(someAuction.Data.CreatedAtBlock);
    Console.WriteLine(someAuction.Data.Collection.CreatedAtBlock);
    Console.WriteLine(someAuction.Data.Collection.Name);
    Console.WriteLine(someAuction.Data.Collection.AllowNotify);
    Console.WriteLine(someAuction.Data.Collection.Author);
    Console.WriteLine(someAuction.Data.Collection.CollectionName);
    Console.WriteLine(someAuction.Data.Collection.MarketFee);

    // Print diverse Data about the Assets being part of this Auction
    foreach (var asset in someAuction.Data.Assets)
    {
        Console.WriteLine(asset.AssetId);
        Console.WriteLine(asset.Burnable);
        Console.WriteLine(asset.BurnedAtBlock);
        Console.WriteLine(asset.BurnedAtTime);
        Console.WriteLine(asset.BurnedByAccount);
        Console.WriteLine(asset.Contract);
        Console.WriteLine(asset.MintedAtBlock);
        Console.WriteLine(asset.MintedAtTime);
        Console.WriteLine(asset.Name);
        Console.WriteLine(asset.Owner);
        Console.WriteLine(asset.AssetId);
    }
}
```
