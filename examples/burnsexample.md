---
description: Example showing how to query the Burns Endpoint
---

# BurnsExample

```csharp
public async Task BurnsExample()
{
    // Get all burns by a specific account
    var burns = await AtomicAssetsApiFactory.Version1.BurnsApi.Account("someaccount");

    Console.WriteLine(burns.Data.Assets);

    // Print data about the collections the burned Assets belonged to
    foreach (var collection in burns.Data.Collections)
    {
        Console.WriteLine(collection.Assets);
        Console.WriteLine(collection.CollectionName);
    }

    // Print data about the templates the burned Assets belonged to
    foreach (var template in burns.Data.Templates)
    {
        Console.WriteLine(template.Assets);
        Console.WriteLine(template.CollectionName);
        Console.WriteLine(template.TemplateId);
    }
}
```
