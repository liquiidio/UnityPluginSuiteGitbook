---
description: Example showing how to query the Offers Endpoint
---

# OffersExample

```csharp
public async Task OffersExample()
{
    // Get a offer by it's identifier
    var offer = await AtomicAssetsApiFactory.Version1.OffersApi.Offer("someofferId");

    // Print diverse Data about the offer to the Console
    Console.WriteLine(offer.Data.Data);
    Console.WriteLine(offer.Data.Contract);
    Console.WriteLine(offer.Data.CreatedAtBlock);
    Console.WriteLine(offer.Data.CreatedAtTime);
    Console.WriteLine(offer.Data.IsRecipientContract);
    Console.WriteLine(offer.Data.IsSenderContract);
    Console.WriteLine(offer.Data.Memo);
    Console.WriteLine(offer.Data.OfferId);
    Console.WriteLine(offer.Data.RecipientName);

    // Print diverse Data about the Recipient Asset
    foreach (var recipientAsset in offer.Data.RecipientAssets)
    {
        Console.WriteLine(recipientAsset.Collection.Name);
        Console.WriteLine(recipientAsset.Name);
        Console.WriteLine(recipientAsset.Contract);
        Console.WriteLine(recipientAsset.Burnable);
        Console.WriteLine(recipientAsset.MintedAtBlock);
        Console.WriteLine(recipientAsset.MintedAtTime);
    }

    // Print diverse Data about the Sender Asset
    foreach (var senderAsset in offer.Data.SenderAssets)
    {
        Console.WriteLine(senderAsset.Collection.Name);
        Console.WriteLine(senderAsset.Name);
        Console.WriteLine(senderAsset.Contract);
        Console.WriteLine(senderAsset.Burnable);
        Console.WriteLine(senderAsset.MintedAtBlock);
        Console.WriteLine(senderAsset.MintedAtTime);
    }
}
```
