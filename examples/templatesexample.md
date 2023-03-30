---
description: Example showing how to query the Templates Endpoint
---

# TemplatesExample

```csharp
public async Task TemplatesExample()
{
    // Get a template by collection and templateId
    var template = await AtomicAssetsApiFactory.Version1.TemplatesApi.Template("collectionName", "templateId");

    // Print diverse Data about the template
    Console.WriteLine(template.Data.Contract);
    Console.WriteLine(template.Data.CreatedAtBlock);
    Console.WriteLine(template.Data.CreatedAtTime);
    Console.WriteLine(template.Data.IsBurnable);
    Console.WriteLine(template.Data.IsTransferable);
    Console.WriteLine(template.Data.IssuedSupply);
    Console.WriteLine(template.Data.MaxSupply);
    Console.WriteLine(template.Data.TemplateId);
}
```
