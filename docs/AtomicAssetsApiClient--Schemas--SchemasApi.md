## class `AtomicAssetsApiClient::Schemas::SchemasApi` 

### Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public SchemasDto `[`Schemas`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_api_1ab9e752b76dbad14f4940f2471db7e1c0)`()` | This function will return a `SchemasDto` object that contains a list of all the schemas that are available in the API.
`public SchemasDto `[`Schemas`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_api_1a1e653311a7a7b77065d37fda7c52aa66)`(SchemasUriParameterBuilder schemasUriParameterBuilder)` | This function will return a list of schemas that match the criteria specified in the `SchemasUriParameterBuilder` object.
`public SchemaDto `[`Schema`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_api_1a9474dd30438b70ef4f199b829e449c42)`(string collectionName, string schemaName)` | This function will return a schema object for the specified collection and schema name.
`public StatsDto `[`SchemaStats`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_api_1a54dfa68d9be1fd02b2b97e67c37be57b)`(string collectionName, string schemaName)` | It returns the stats of a schema.
`public LogsDto `[`SchemaLogs`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_api_1a17158c4d15091467d59996c07a340b97)`(string collectionName, string schemaName)` | This function returns a list of logs for a specific schema.
`public LogsDto `[`SchemaLogs`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_api_1a03d307684126064615e0b2a832a0b929)`(string collectionName, string schemaName, SchemasUriParameterBuilder schemasUriParameterBuilder)` | This function returns a list of logs for a specific schema.
`private readonly string `[`_requestUriBase`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_api_1a1854c4909a1013a684af16fb52e8a387) | 
`private Uri `[`SchemasUri`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_api_1a1a498badf0002f7181835480737d5dd8)`()` | 
`private Uri `[`SchemasUri`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_api_1a79bc27edb0e05705096dd6721a9a9e26)`(SchemasUriParameterBuilder schemasUriParameterBuilder)` | 
`private Uri `[`SchemaUri`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_api_1a591edd6511a415a8554155da1b7b6751)`(string collectionName, string schemaName)` | 
`private Uri `[`SchemaStatsUri`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_api_1a8726dba637901b79588b0ec8d3e25fb6)`(string collectionName, string schemaName)` | 
`private Uri `[`SchemaLogsUri`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_api_1a4d189f4a5b707893aaab098c9b2d5b7f)`(string collectionName, string schemaName)` | 
`private Uri `[`SchemaLogsUri`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_api_1afd46daaf197c05d3daba0a1815332428)`(string collectionName, string schemaName, SchemasUriParameterBuilder schemasUriParameterBuilder)` | 

### Members

#### `public SchemasDto `[`Schemas`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_api_1ab9e752b76dbad14f4940f2471db7e1c0)`()` 

This function will return a `SchemasDto` object that contains a list of all the schemas that are available in the API.

#### Returns
A SchemasDto object.

#### `public SchemasDto `[`Schemas`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_api_1a1e653311a7a7b77065d37fda7c52aa66)`(SchemasUriParameterBuilder schemasUriParameterBuilder)` 

This function will return a list of schemas that match the criteria specified in the `SchemasUriParameterBuilder` object.

#### Parameters
* `SchemasUriParameterBuilder` This is a class that contains all the parameters that can be passed to the API.

#### Returns
A list of schemas.

#### `public SchemaDto `[`Schema`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_api_1a9474dd30438b70ef4f199b829e449c42)`(string collectionName, string schemaName)` 

This function will return a schema object for the specified collection and schema name.

#### Parameters
* `collectionName` The name of the collection you want to get the schema for.

* `schemaName` The name of the schema you want to retrieve.

#### Returns
A SchemaDto object.

#### `public StatsDto `[`SchemaStats`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_api_1a54dfa68d9be1fd02b2b97e67c37be57b)`(string collectionName, string schemaName)` 

It returns the stats of a schema.

#### Parameters
* `collectionName` The name of the collection you want to get the stats for.

* `schemaName` The name of the schema you want to get stats for.

#### Returns
A StatsDto object

#### `public LogsDto `[`SchemaLogs`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_api_1a17158c4d15091467d59996c07a340b97)`(string collectionName, string schemaName)` 

This function returns a list of logs for a specific schema.

#### Parameters
* `collectionName` The name of the collection you want to get the logs for.

* `schemaName` The name of the schema you want to get logs for.

#### Returns
A list of logs for the schema.

#### `public LogsDto `[`SchemaLogs`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_api_1a03d307684126064615e0b2a832a0b929)`(string collectionName, string schemaName, SchemasUriParameterBuilder schemasUriParameterBuilder)` 

This function returns a list of logs for a specific schema.

#### Parameters
* `collectionName` The name of the collection you want to get the schema logs for.

* `schemaName` The name of the schema you want to get the logs for.

* `SchemasUriParameterBuilder` This is a class that contains the parameters that can be passed to the API.

#### Returns
A LogsDto object.

#### `private readonly string `[`_requestUriBase`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_api_1a1854c4909a1013a684af16fb52e8a387) 

#### `private Uri `[`SchemasUri`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_api_1a1a498badf0002f7181835480737d5dd8)`()` 

#### `private Uri `[`SchemasUri`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_api_1a79bc27edb0e05705096dd6721a9a9e26)`(SchemasUriParameterBuilder schemasUriParameterBuilder)` 

#### `private Uri `[`SchemaUri`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_api_1a591edd6511a415a8554155da1b7b6751)`(string collectionName, string schemaName)` 

#### `private Uri `[`SchemaStatsUri`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_api_1a8726dba637901b79588b0ec8d3e25fb6)`(string collectionName, string schemaName)` 

#### `private Uri `[`SchemaLogsUri`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_api_1a4d189f4a5b707893aaab098c9b2d5b7f)`(string collectionName, string schemaName)` 

#### `private Uri `[`SchemaLogsUri`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_api_1afd46daaf197c05d3daba0a1815332428)`(string collectionName, string schemaName, SchemasUriParameterBuilder schemasUriParameterBuilder)` 

