---
description: Example showing how to query the Schemas Endpoint
---

# SchemasExample

```csharp
public async Task SchemasExample()
{
    // Get a schema by collection and schemaName
    var schema = await AtomicAssetsApiFactory.Version1.SchemasApi.Schema("collectionName", "schemaName");

    // Print diverse Data about the schema
    Console.WriteLine(schema.Data.Contract);
    Console.WriteLine(schema.Data.CreatedAtBlock);
    Console.WriteLine(schema.Data.CreatedAtTime);
    Console.WriteLine(schema.Data.SchemaName);

    // Print the individual parts o the format
    foreach (var format in schema.Data.Format)
    {
        Console.WriteLine(format.Name);
        Console.WriteLine(format.Type);
    }

    // Print diverse Data about the collection this schema belongs to
    Console.WriteLine(schema.Data.Collection.Name);
    Console.WriteLine(schema.Data.Collection.Author);
    Console.WriteLine(schema.Data.Collection.CollectionName);
    Console.WriteLine(schema.Data.Collection.Image);

}
```
