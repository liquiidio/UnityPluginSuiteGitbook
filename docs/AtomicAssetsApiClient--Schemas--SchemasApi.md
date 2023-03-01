# class `AtomicAssetsApiClient::Schemas::SchemasApi` 

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public async Task< ` [`SchemasDto`](AtomicAssetsApiClient--Schemas--SchemasDto.md)` > ` [`Schemas`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_api_1ab9002abfbc07fb7dae114a66cabaac5a)`()` | This function will return a `SchemasDto` object that contains a list of all the schemas that are available in the API.
`public async Task< ` [`SchemasDto`](AtomicAssetsApiClient--Schemas--SchemasDto.md)` > ` [`Schemas`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_api_1a44616d88205c7afa1496ca9e7a8df5f5)`(` [`SchemasUriParameterBuilder`](AtomicAssetsApiClient--Schemas--SchemasUriParameterBuilder.md)` schemasUriParameterBuilder)` | This function will return a list of schemas that match the criteria specified in the `SchemasUriParameterBuilder` object.
`public async Task< ` [`SchemaDto`](AtomicAssetsApiClient--Schemas--SchemaDto.md)` > ` [`Schema`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_api_1acb58c1d18d9c2f6a0aa54482fb64a4e3)`(string collectionName, string schemaName)` | This function will return a schema object for the specified collection and schema name.
`public async Task< ` [`StatsDto`](AtomicAssetsApiClient--StatsDto.md)` > ` [`SchemaStats`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_api_1ac17198710d41cfe90393f543c0a23cc9)`(string collectionName, string schemaName)` | It returns the stats of a schema.
`public async Task< ` [`LogsDto`](AtomicAssetsApiClient--LogsDto.md)` > ` [`SchemaLogs`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_api_1ab6aea7f4fbdffbbadd2e5956ffd0f77c)`(string collectionName, string schemaName)` | This function returns a list of logs for a specific schema.
`public async Task< ` [`LogsDto`](AtomicAssetsApiClient--LogsDto.md)` > ` [`SchemaLogs`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_api_1a4188f706ceb39653d1e0f5123cbed790)`(string collectionName, string schemaName, ` [`SchemasUriParameterBuilder`](AtomicAssetsApiClient--Schemas--SchemasUriParameterBuilder.md)` schemasUriParameterBuilder)` | This function returns a list of logs for a specific schema.
`private readonly string ` [`_requestUriBase`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_api_1a1854c4909a1013a684af16fb52e8a387) | 
`private readonly ` [`IHttpHandler`](AtomicAssetsApiClient.md)` ` [`_httpHandler`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_api_1a278528cd3027ee0a4ca8e04964f99674) | 
`private Uri ` [`SchemasUri`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_api_1a1a498badf0002f7181835480737d5dd8)`()` | It returns a URI that points to the schemas endpoint.
`private Uri ` [`SchemasUri`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_api_1a79bc27edb0e05705096dd6721a9a9e26)`(` [`SchemasUriParameterBuilder`](AtomicAssetsApiClient--Schemas--SchemasUriParameterBuilder.md)` schemasUriParameterBuilder)` | It takes a `SchemasUriParameterBuilder` object as a parameter, and returns a `Uri` object.
`private Uri ` [`SchemaUri`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_api_1a591edd6511a415a8554155da1b7b6751)`(string collectionName, string schemaName)` | It returns a URI for a specific schema in a specific collection
`private Uri ` [`SchemaStatsUri`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_api_1a8726dba637901b79588b0ec8d3e25fb6)`(string collectionName, string schemaName)` | It returns a URI that points to the stats for a specific schema in a specific collection.
`private Uri ` [`SchemaLogsUri`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_api_1a4d189f4a5b707893aaab098c9b2d5b7f)`(string collectionName, string schemaName)` | This function returns a URI for the schema logs endpoint
`private Uri ` [`SchemaLogsUri`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_api_1afd46daaf197c05d3daba0a1815332428)`(string collectionName, string schemaName, ` [`SchemasUriParameterBuilder`](AtomicAssetsApiClient--Schemas--SchemasUriParameterBuilder.md)` schemasUriParameterBuilder)` | It returns a URI for the schema logs endpoint.

## Members

##### `public async Task< ` [`SchemasDto`](AtomicAssetsApiClient--Schemas--SchemasDto.md)` > ` [`Schemas`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_api_1ab9002abfbc07fb7dae114a66cabaac5a)`()` 

This function will return a `SchemasDto` object that contains a list of all the schemas that are available in the API.

#### Returns
A SchemasDto object.

##### `public async Task< ` [`SchemasDto`](AtomicAssetsApiClient--Schemas--SchemasDto.md)` > ` [`Schemas`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_api_1a44616d88205c7afa1496ca9e7a8df5f5)`(` [`SchemasUriParameterBuilder`](AtomicAssetsApiClient--Schemas--SchemasUriParameterBuilder.md)` schemasUriParameterBuilder)` 

This function will return a list of schemas that match the criteria specified in the `SchemasUriParameterBuilder` object.

#### Parameters
* `SchemasUriParameterBuilder` This is a class that contains all the parameters that can be passed to the API.

#### Returns
A list of schemas.

##### `public async Task< ` [`SchemaDto`](AtomicAssetsApiClient--Schemas--SchemaDto.md)` > ` [`Schema`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_api_1acb58c1d18d9c2f6a0aa54482fb64a4e3)`(string collectionName, string schemaName)` 

This function will return a schema object for the specified collection and schema name.

#### Parameters
* `collectionName` The name of the collection you want to get the schema for.

* `schemaName` The name of the schema you want to retrieve.

#### Returns
A SchemaDto object.

##### `public async Task< ` [`StatsDto`](AtomicAssetsApiClient--StatsDto.md)` > ` [`SchemaStats`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_api_1ac17198710d41cfe90393f543c0a23cc9)`(string collectionName, string schemaName)` 

It returns the stats of a schema.

#### Parameters
* `collectionName` The name of the collection you want to get the stats for.

* `schemaName` The name of the schema you want to get stats for.

#### Returns
A StatsDto object

##### `public async Task< ` [`LogsDto`](AtomicAssetsApiClient--LogsDto.md)` > ` [`SchemaLogs`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_api_1ab6aea7f4fbdffbbadd2e5956ffd0f77c)`(string collectionName, string schemaName)` 

This function returns a list of logs for a specific schema.

#### Parameters
* `collectionName` The name of the collection you want to get the logs for.

* `schemaName` The name of the schema you want to get logs for.

#### Returns
A list of logs for the schema.

##### `public async Task< ` [`LogsDto`](AtomicAssetsApiClient--LogsDto.md)` > ` [`SchemaLogs`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_api_1a4188f706ceb39653d1e0f5123cbed790)`(string collectionName, string schemaName, ` [`SchemasUriParameterBuilder`](AtomicAssetsApiClient--Schemas--SchemasUriParameterBuilder.md)` schemasUriParameterBuilder)` 

This function returns a list of logs for a specific schema.

#### Parameters
* `collectionName` The name of the collection you want to get the schema logs for.

* `schemaName` The name of the schema you want to get the logs for.

* `SchemasUriParameterBuilder` This is a class that contains the parameters that can be passed to the API.

#### Returns
A LogsDto object.

##### `private readonly string ` [`_requestUriBase`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_api_1a1854c4909a1013a684af16fb52e8a387) 

##### `private readonly ` [`IHttpHandler`](AtomicAssetsApiClient.md)` ` [`_httpHandler`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_api_1a278528cd3027ee0a4ca8e04964f99674) 

##### `private Uri ` [`SchemasUri`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_api_1a1a498badf0002f7181835480737d5dd8)`()` 

It returns a URI that points to the schemas endpoint.

##### `private Uri ` [`SchemasUri`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_api_1a79bc27edb0e05705096dd6721a9a9e26)`(` [`SchemasUriParameterBuilder`](AtomicAssetsApiClient--Schemas--SchemasUriParameterBuilder.md)` schemasUriParameterBuilder)` 

It takes a `SchemasUriParameterBuilder` object as a parameter, and returns a `Uri` object.

#### Parameters
* `SchemasUriParameterBuilder` A class that builds the query string parameters for the schemas endpoint.

##### `private Uri ` [`SchemaUri`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_api_1a591edd6511a415a8554155da1b7b6751)`(string collectionName, string schemaName)` 

It returns a URI for a specific schema in a specific collection

#### Parameters
* `collectionName` The name of the collection you want to create the schema in.

* `schemaName` The name of the schema to be created.

##### `private Uri ` [`SchemaStatsUri`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_api_1a8726dba637901b79588b0ec8d3e25fb6)`(string collectionName, string schemaName)` 

It returns a URI that points to the stats for a specific schema in a specific collection.

#### Parameters
* `collectionName` The name of the collection you want to get the schema stats for.

* `schemaName` The name of the schema.

##### `private Uri ` [`SchemaLogsUri`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_api_1a4d189f4a5b707893aaab098c9b2d5b7f)`(string collectionName, string schemaName)` 

This function returns a URI for the schema logs endpoint

#### Parameters
* `collectionName` The name of the collection you want to create a schema for.

* `schemaName` The name of the schema.

##### `private Uri ` [`SchemaLogsUri`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_api_1afd46daaf197c05d3daba0a1815332428)`(string collectionName, string schemaName, ` [`SchemasUriParameterBuilder`](AtomicAssetsApiClient--Schemas--SchemasUriParameterBuilder.md)` schemasUriParameterBuilder)` 

It returns a URI for the schema logs endpoint.

#### Parameters
* `collectionName` The name of the collection.

* `schemaName` The name of the schema.

* `SchemasUriParameterBuilder` This is a class that helps you build the query parameters for the request.

