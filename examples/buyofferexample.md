---
description: Example showing how to query the BuyOffer Endpoint
---

# BuyOfferExample

```csharp
public async Task BuyOfferExample()
{
    // Get a specific buyoffer by it's buyofferId
    var buyoffer = await AtomicMarketApiFactory.Version1.BuyOffersApi.BuyOffer(35346346);


    // Print diverse Data about the buyOffer 
    Console.WriteLine(buyoffer.Data.Collection.CreatedAtBlock);
    Console.WriteLine(buyoffer.Data.Collection.Name);
    Console.WriteLine(buyoffer.Data.Collection.AllowNotify);
    Console.WriteLine(buyoffer.Data.Collection.Author);
    Console.WriteLine(buyoffer.Data.Collection.CollectionName);
    Console.WriteLine(buyoffer.Data.Collection.CreatedAtTime);
    Console.WriteLine(buyoffer.Data.Collection.Img);
    Console.WriteLine(buyoffer.Data.Collection.MarketFee);

    // Print diverse Data about the Assets being part of this BuyOffer
    foreach (var asset in buyoffer.Data.Assets)
    {
        Console.WriteLine(asset.AssetId);
        Console.WriteLine(asset.Burnable);
        Console.WriteLine(asset.BurnedAtBlock);
        Console.WriteLine(asset.BurnedAtTime);
        Console.WriteLine(asset.BurnedByAccount);
        Console.WriteLine(asset.Contract);
        Console.WriteLine(asset.Collection.Author);
        Console.WriteLine(asset.Collection.Name);
        Console.WriteLine(asset.Collection.Img);
    }
}
```
