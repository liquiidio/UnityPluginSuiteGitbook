---
description: Example showing how to query the Transfers Endpoint
---

# TransfersExample

```csharp
public async Task TransfersExample()
{
    // Get a all transfers from a specific account and a specific collection
    var transfers = await AtomicAssetsApiFactory.Version1.TransfersApi.Transfers(new TransfersUriParameterBuilder().WithAccount("someAccount").WithCollectionName("someCollection"));

    // iterate each transfer
    foreach (var transfer in transfers.Data)
    {
        Console.WriteLine(transfer.Contract);

        // Print diverse data about the individual assets transfered
        foreach (var asset in transfer.Assets)
        {
            Console.WriteLine(asset.Name);
            Console.WriteLine(asset.Owner);
            Console.WriteLine(asset.Contract);
            Console.WriteLine(asset.Collection.Name);
        }
    }
}
```
