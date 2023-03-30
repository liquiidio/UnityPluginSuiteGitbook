---
description: Example showing how to query the Sales Endpoint
---

# SalesExample

```csharp
public async Task SalesExample()
{
    // Get all Sales for a specific collection
    var sales = await AtomicMarketApiFactory.Version1.SalesApi.Sales(new SalesUriParameterBuilder().WithCollectionName("somecollection"));

    // Iterate all Sales matching the collectionName
    foreach (var sale in sales.Data)
    {
        // Print diverse Data about the Collection
        Console.WriteLine(sale.Collection.CreatedAtBlock);
        Console.WriteLine(sale.Collection.AllowNotify);
        Console.WriteLine(sale.Collection.Author);
        Console.WriteLine(sale.Collection.Name);
        Console.WriteLine(sale.Collection.CollectionName);
        Console.WriteLine(sale.Collection.CreatedAtTime);
        Console.WriteLine(sale.Collection.MarketFee);


        // Print diverse Data about the Assets being part of this Collection
        foreach (var asset in sale.Assets)
        {
            Console.WriteLine(asset.AssetId);
            Console.WriteLine(asset.Burnable);
            Console.WriteLine(asset.BurnedAtBlock);
            Console.WriteLine(asset.BurnedAtTime);
            Console.WriteLine(asset.BurnedByAccount);
            Console.WriteLine(asset.Collection.Author);
            Console.WriteLine(asset.Collection.Name);
            Console.WriteLine(asset.Collection.CollectionName);
            Console.WriteLine(asset.Collection.CreatedAtBlock);
            Console.WriteLine(asset.Collection.CreatedAtTime);
            Console.WriteLine(asset.Contract);
            Console.WriteLine(asset.MintedAtTime);
            Console.WriteLine(asset.Name);
            Console.WriteLine(asset.TemplateMint);
        }
    }
}
```
