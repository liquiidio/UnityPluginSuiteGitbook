---
description: Example showing how to query the Account Endpoint
---

# AccountExample

```csharp
public async Task AccountExample()
{
    // Get data for a specific account by it's account name
    var someAccount = await AtomicAssetsApiFactory.Version1.AccountsApi.Account("someaccount");

    // Iterate the data
    foreach (var data in someAccount.Data)
    {
        // Print information about individual Assets to the Console
        Console.WriteLine(data.Assets);
        foreach (var collection in data.Collections)
        {
            Console.WriteLine(collection.Assets);
        }

        // Print information about individual TEmplates to the Console
        foreach (var template in data.Templates)
        {
            Console.WriteLine(template.Assets);
            Console.WriteLine(template.TemplateId);
        }
    }
}

public async Task AssetExample()
{
    // Get data for a specific Asset by it's AssetId
    var someAsset = await AtomicAssetsApiFactory.Version1.AssetsApi.Asset("someassetid");

    // Print diverse Data about the Asset to the Console
    Console.WriteLine(someAsset.Data.AssetId);
    Console.WriteLine(someAsset.Data.Burnable);
    Console.WriteLine(someAsset.Data.Contract);
    Console.WriteLine(someAsset.Data.MintedAtBlock);
    Console.WriteLine(someAsset.Data.MintedAtTime);
    Console.WriteLine(someAsset.Data.Name);
    Console.WriteLine(someAsset.Data.Owner);
    Console.WriteLine(someAsset.Data.Contract);

    // Print Data about backed tokens to the Console
    foreach (var backedToken in someAsset.Data.BackedTokens)
    {
        Console.WriteLine(backedToken.Amount);
        Console.WriteLine(backedToken.TokenContract);
        Console.WriteLine(backedToken.TokenPrecision);
        Console.WriteLine(backedToken.TokenSymbol);
    }

    // Print diverse Data about the Collection the Asset the belongs to to the Console
    Console.WriteLine(someAsset.Data.Collection.Name);
    Console.WriteLine(someAsset.Data.Collection.AllowNotify);
    Console.WriteLine(someAsset.Data.Collection.Author);
    Console.WriteLine(someAsset.Data.Collection.CollectionName);
    Console.WriteLine(someAsset.Data.Collection.CreatedAtBlock);
    Console.WriteLine(someAsset.Data.Collection.CreatedAtTime);
    Console.WriteLine(someAsset.Data.Collection.Image);
    Console.WriteLine(someAsset.Data.Collection.MarketFee);

    // Print the authorized Accounts
    foreach (var authorizedAccount in someAsset.Data.Collection.AuthorizedAccounts)
    {
        Console.WriteLine(authorizedAccount);
    }

    // Print the notified Accounts
    foreach (var notifyAccount in someAsset.Data.Collection.NotifyAccounts)
    {
        Console.Write(notifyAccount);
    }
}
```
