## class `AtomicAssetsApiClient::Templates::TemplatesApi` 

### Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public inline TemplatesDto `[`Templates`](#class_atomic_assets_api_client_1_1_templates_1_1_templates_api_1a25e67d4b511a23a1b839ddda3f068270)`()` | This function will return a list of templates that are available to the user.
`public inline TemplatesDto `[`Templates`](#class_atomic_assets_api_client_1_1_templates_1_1_templates_api_1a8ea5c7db0240a2a35df4a5102fc54dc6)`(TemplatesUriParameterBuilder templatesUriParameterBuilder)` | This function will return a TemplatesDto object that contains a list of templates that match the criteria specified in the TemplatesUriParameterBuilder object.
`public inline TemplateDto `[`Template`](#class_atomic_assets_api_client_1_1_templates_1_1_templates_api_1a2407db816a9531d64ebb2a45e1baf94f)`(string collectionName, string templateId)` | This function will return a TemplateDto object from the API.
`public inline StatsDto `[`TemplateStats`](#class_atomic_assets_api_client_1_1_templates_1_1_templates_api_1aae016864d3b9036a46fe974edda95bdb)`(string collectionName, string templateId)` | This function will return a StatsDto object that contains the number of documents that have been indexed using the specified template.
`public inline LogsDto `[`TemplateLogs`](#class_atomic_assets_api_client_1_1_templates_1_1_templates_api_1aafe2d7ea95fef1f9e52b0542ab98da04)`(string collectionName, string templateId)` | This function returns a list of logs for a specific template.
`public inline LogsDto `[`TemplateLogs`](#class_atomic_assets_api_client_1_1_templates_1_1_templates_api_1abfe898a4671b389c83d65ebb70439e4d)`(string collectionName, string templateId, TemplatesUriParameterBuilder templatesUriParameterBuilder)` | This function returns a list of logs for a specific template.
`private readonly string `[`_requestUriBase`](#class_atomic_assets_api_client_1_1_templates_1_1_templates_api_1a1854c4909a1013a684af16fb52e8a387) | 
`private Uri `[`TemplatesUri`](#class_atomic_assets_api_client_1_1_templates_1_1_templates_api_1a70668a91db02b5409d48e972387179ce)`()` | 
`private Uri `[`TemplatesUri`](#class_atomic_assets_api_client_1_1_templates_1_1_templates_api_1a3120a9b5fd6173bdc6e13bf34ddcd6d1)`(TemplatesUriParameterBuilder templatessUriParameterBuilder)` | 
`private Uri `[`TemplateUri`](#class_atomic_assets_api_client_1_1_templates_1_1_templates_api_1a495ebc65461d52505612c98c313f1326)`(string collectionName, string templateId)` | 
`private Uri `[`TemplateStatsUri`](#class_atomic_assets_api_client_1_1_templates_1_1_templates_api_1a5829798696aa9ecddd5e5f1c3e8ec1bc)`(string collectionName, string templateId)` | 
`private Uri `[`TemplateLogsUri`](#class_atomic_assets_api_client_1_1_templates_1_1_templates_api_1a689ae101f2c19a4f3947dbdd0ee964e7)`(string collectionName, string templateId)` | 
`private Uri `[`TemplateLogsUri`](#class_atomic_assets_api_client_1_1_templates_1_1_templates_api_1acdf94dbd49b55bf713e8087ab05c4daf)`(string collectionName, string templateId, TemplatesUriParameterBuilder templatesUriParameterBuilder)` | 

### Members

#### `public inline TemplatesDto `[`Templates`](#class_atomic_assets_api_client_1_1_templates_1_1_templates_api_1a25e67d4b511a23a1b839ddda3f068270)`()` 

This function will return a list of templates that are available to the user.

#### Returns
A TemplatesDto object

#### `public inline TemplatesDto `[`Templates`](#class_atomic_assets_api_client_1_1_templates_1_1_templates_api_1a8ea5c7db0240a2a35df4a5102fc54dc6)`(TemplatesUriParameterBuilder templatesUriParameterBuilder)` 

This function will return a TemplatesDto object that contains a list of templates that match the criteria specified in the TemplatesUriParameterBuilder object.

#### Parameters
* `TemplatesUriParameterBuilder` This is a class that contains all the parameters that can be passed to the API.

#### Returns
A TemplatesDto object.

#### `public inline TemplateDto `[`Template`](#class_atomic_assets_api_client_1_1_templates_1_1_templates_api_1a2407db816a9531d64ebb2a45e1baf94f)`(string collectionName, string templateId)` 

This function will return a TemplateDto object from the API.

#### Parameters
* `collectionName` The name of the collection you want to create the template in.

* `templateId` The id of the template you want to retrieve.

#### Returns
A TemplateDto object

#### `public inline StatsDto `[`TemplateStats`](#class_atomic_assets_api_client_1_1_templates_1_1_templates_api_1aae016864d3b9036a46fe974edda95bdb)`(string collectionName, string templateId)` 

This function will return a StatsDto object that contains the number of documents that have been indexed using the specified template.

#### Parameters
* `collectionName` The name of the collection you want to get the stats for.

* `templateId` The id of the template you want to get stats for.

#### Returns
A StatsDto object

#### `public inline LogsDto `[`TemplateLogs`](#class_atomic_assets_api_client_1_1_templates_1_1_templates_api_1aafe2d7ea95fef1f9e52b0542ab98da04)`(string collectionName, string templateId)` 

This function returns a list of logs for a specific template.

#### Parameters
* `collectionName` The name of the collection you want to get the logs for.

* `templateId` The id of the template you want to get the logs for.

#### Returns
A list of logs for a specific template.

#### `public inline LogsDto `[`TemplateLogs`](#class_atomic_assets_api_client_1_1_templates_1_1_templates_api_1abfe898a4671b389c83d65ebb70439e4d)`(string collectionName, string templateId, TemplatesUriParameterBuilder templatesUriParameterBuilder)` 

This function returns a list of logs for a specific template.

#### Parameters
* `collectionName` The name of the collection you want to get the logs for.

* `templateId` The id of the template you want to get the logs for.

* `TemplatesUriParameterBuilder` This is a class that contains all the parameters that can be passed to the API.

#### Returns
A LogsDto object

#### `private readonly string `[`_requestUriBase`](#class_atomic_assets_api_client_1_1_templates_1_1_templates_api_1a1854c4909a1013a684af16fb52e8a387) 

#### `private Uri `[`TemplatesUri`](#class_atomic_assets_api_client_1_1_templates_1_1_templates_api_1a70668a91db02b5409d48e972387179ce)`()` 

#### `private Uri `[`TemplatesUri`](#class_atomic_assets_api_client_1_1_templates_1_1_templates_api_1a3120a9b5fd6173bdc6e13bf34ddcd6d1)`(TemplatesUriParameterBuilder templatessUriParameterBuilder)` 

#### `private Uri `[`TemplateUri`](#class_atomic_assets_api_client_1_1_templates_1_1_templates_api_1a495ebc65461d52505612c98c313f1326)`(string collectionName, string templateId)` 

#### `private Uri `[`TemplateStatsUri`](#class_atomic_assets_api_client_1_1_templates_1_1_templates_api_1a5829798696aa9ecddd5e5f1c3e8ec1bc)`(string collectionName, string templateId)` 

#### `private Uri `[`TemplateLogsUri`](#class_atomic_assets_api_client_1_1_templates_1_1_templates_api_1a689ae101f2c19a4f3947dbdd0ee964e7)`(string collectionName, string templateId)` 

#### `private Uri `[`TemplateLogsUri`](#class_atomic_assets_api_client_1_1_templates_1_1_templates_api_1acdf94dbd49b55bf713e8087ab05c4daf)`(string collectionName, string templateId, TemplatesUriParameterBuilder templatesUriParameterBuilder)` 

