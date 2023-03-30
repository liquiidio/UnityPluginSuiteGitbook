---
description: Example showing how to query the Collections Endpoint
---

# CollectionsExample

```csharp
public async Task CollectionsExample()
{
    // Get all burns by a specific account
    var collection = await AtomicAssetsApiFactory.Version1.CollectionsApi.Collection("somecollection");

    // Print diverse Data  about the collection to the Console
    Console.WriteLine(collection.Data.Data);
    Console.WriteLine(collection.Data.CollectionName);
    Console.WriteLine(collection.Data.AllowNotify);
    Console.WriteLine(collection.Data.Author);
    Console.WriteLine(collection.Data.Contract);
    Console.WriteLine(collection.Data.CreatedAtBlock);
    Console.WriteLine(collection.Data.CreatedAtTime);
    Console.WriteLine(collection.Data.MarketFee);
    Console.WriteLine(collection.Data.Name);
}
```
