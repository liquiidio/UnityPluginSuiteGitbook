# class `AtomicAssetsApiClient::Templates::TemplatesApi` 

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public async Task< ` [`TemplatesDto`](AtomicAssetsApiClient--Templates--TemplatesDto.md)` > ` [`Templates`](#class_atomic_assets_api_client_1_1_templates_1_1_templates_api_1a86541ec88b827efe8636521c4d77aa08)`()` | This function will return a list of templates that are available to the user.
`public async Task< ` [`TemplatesDto`](AtomicAssetsApiClient--Templates--TemplatesDto.md)` > ` [`Templates`](#class_atomic_assets_api_client_1_1_templates_1_1_templates_api_1a67c922f0333ddaa25ea23f31bd1f6bcf)`(` [`TemplatesUriParameterBuilder`](AtomicAssetsApiClient--Templates--TemplatesUriParameterBuilder.md)` templatesUriParameterBuilder)` | This function will return a TemplatesDto object that contains a list of templates that match the criteria specified in the TemplatesUriParameterBuilder object.
`public async Task< ` [`TemplateDto`](AtomicAssetsApiClient--Templates--TemplateDto.md)` > ` [`Template`](#class_atomic_assets_api_client_1_1_templates_1_1_templates_api_1a5e52879fcc80f9a83259afb9bc83f98f)`(string collectionName, string templateId)` | This function will return a TemplateDto object from the API.
`public async Task< ` [`StatsDto`](AtomicAssetsApiClient--StatsDto.md)` > ` [`TemplateStats`](#class_atomic_assets_api_client_1_1_templates_1_1_templates_api_1a9141c096683dd1d450d8abfc99d13aec)`(string collectionName, string templateId)` | This function will return a StatsDto object that contains the number of documents that have been indexed using the specified template.
`public async Task< ` [`LogsDto`](AtomicAssetsApiClient--LogsDto.md)` > ` [`TemplateLogs`](#class_atomic_assets_api_client_1_1_templates_1_1_templates_api_1a80ca39fcd7ef1546a317d842deb16840)`(string collectionName, string templateId)` | This function returns a list of logs for a specific template.
`public async Task< ` [`LogsDto`](AtomicAssetsApiClient--LogsDto.md)` > ` [`TemplateLogs`](#class_atomic_assets_api_client_1_1_templates_1_1_templates_api_1ac27731853a526f4fb2167714814f58c7)`(string collectionName, string templateId, ` [`TemplatesUriParameterBuilder`](AtomicAssetsApiClient--Templates--TemplatesUriParameterBuilder.md)` templatesUriParameterBuilder)` | This function returns a list of logs for a specific template.
`private readonly string ` [`_requestUriBase`](#class_atomic_assets_api_client_1_1_templates_1_1_templates_api_1a1854c4909a1013a684af16fb52e8a387) | 
`private readonly ` [`IHttpHandler`](AtomicAssetsApiClient.md)` ` [`_httpHandler`](#class_atomic_assets_api_client_1_1_templates_1_1_templates_api_1a278528cd3027ee0a4ca8e04964f99674) | 
`private Uri ` [`TemplatesUri`](#class_atomic_assets_api_client_1_1_templates_1_1_templates_api_1a70668a91db02b5409d48e972387179ce)`()` | It returns a new `Uri` object that is the base URI for the templates endpoint
`private Uri ` [`TemplatesUri`](#class_atomic_assets_api_client_1_1_templates_1_1_templates_api_1a3120a9b5fd6173bdc6e13bf34ddcd6d1)`(` [`TemplatesUriParameterBuilder`](AtomicAssetsApiClient--Templates--TemplatesUriParameterBuilder.md)` templatessUriParameterBuilder)` | It takes a `TemplatesUriParameterBuilder` object as a parameter and returns a `Uri` object.
`private Uri ` [`TemplateUri`](#class_atomic_assets_api_client_1_1_templates_1_1_templates_api_1a495ebc65461d52505612c98c313f1326)`(string collectionName, string templateId)` | It returns a URI for a specific template in a specific collection
`private Uri ` [`TemplateStatsUri`](#class_atomic_assets_api_client_1_1_templates_1_1_templates_api_1a5829798696aa9ecddd5e5f1c3e8ec1bc)`(string collectionName, string templateId)` | This function returns a Uri that can be used to get the stats for a template
`private Uri ` [`TemplateLogsUri`](#class_atomic_assets_api_client_1_1_templates_1_1_templates_api_1a689ae101f2c19a4f3947dbdd0ee964e7)`(string collectionName, string templateId)` | This function returns a Uri for the logs of a template
`private Uri ` [`TemplateLogsUri`](#class_atomic_assets_api_client_1_1_templates_1_1_templates_api_1acdf94dbd49b55bf713e8087ab05c4daf)`(string collectionName, string templateId, ` [`TemplatesUriParameterBuilder`](AtomicAssetsApiClient--Templates--TemplatesUriParameterBuilder.md)` templatesUriParameterBuilder)` | This function returns a Uri for the logs of a template

## Members

##### `public async Task< ` [`TemplatesDto`](AtomicAssetsApiClient--Templates--TemplatesDto.md)` > ` [`Templates`](#class_atomic_assets_api_client_1_1_templates_1_1_templates_api_1a86541ec88b827efe8636521c4d77aa08)`()` 

This function will return a list of templates that are available to the user.

#### Returns
A TemplatesDto object

##### `public async Task< ` [`TemplatesDto`](AtomicAssetsApiClient--Templates--TemplatesDto.md)` > ` [`Templates`](#class_atomic_assets_api_client_1_1_templates_1_1_templates_api_1a67c922f0333ddaa25ea23f31bd1f6bcf)`(` [`TemplatesUriParameterBuilder`](AtomicAssetsApiClient--Templates--TemplatesUriParameterBuilder.md)` templatesUriParameterBuilder)` 

This function will return a TemplatesDto object that contains a list of templates that match the criteria specified in the TemplatesUriParameterBuilder object.

#### Parameters
* `TemplatesUriParameterBuilder` This is a class that contains all the parameters that can be passed to the API.

#### Returns
A TemplatesDto object.

##### `public async Task< ` [`TemplateDto`](AtomicAssetsApiClient--Templates--TemplateDto.md)` > ` [`Template`](#class_atomic_assets_api_client_1_1_templates_1_1_templates_api_1a5e52879fcc80f9a83259afb9bc83f98f)`(string collectionName, string templateId)` 

This function will return a TemplateDto object from the API.

#### Parameters
* `collectionName` The name of the collection you want to create the template in.

* `templateId` The id of the template you want to retrieve.

#### Returns
A TemplateDto object

##### `public async Task< ` [`StatsDto`](AtomicAssetsApiClient--StatsDto.md)` > ` [`TemplateStats`](#class_atomic_assets_api_client_1_1_templates_1_1_templates_api_1a9141c096683dd1d450d8abfc99d13aec)`(string collectionName, string templateId)` 

This function will return a StatsDto object that contains the number of documents that have been indexed using the specified template.

#### Parameters
* `collectionName` The name of the collection you want to get the stats for.

* `templateId` The id of the template you want to get stats for.

#### Returns
A StatsDto object

##### `public async Task< ` [`LogsDto`](AtomicAssetsApiClient--LogsDto.md)` > ` [`TemplateLogs`](#class_atomic_assets_api_client_1_1_templates_1_1_templates_api_1a80ca39fcd7ef1546a317d842deb16840)`(string collectionName, string templateId)` 

This function returns a list of logs for a specific template.

#### Parameters
* `collectionName` The name of the collection you want to get the logs for.

* `templateId` The id of the template you want to get the logs for.

#### Returns
A list of logs for a specific template.

##### `public async Task< ` [`LogsDto`](AtomicAssetsApiClient--LogsDto.md)` > ` [`TemplateLogs`](#class_atomic_assets_api_client_1_1_templates_1_1_templates_api_1ac27731853a526f4fb2167714814f58c7)`(string collectionName, string templateId, ` [`TemplatesUriParameterBuilder`](AtomicAssetsApiClient--Templates--TemplatesUriParameterBuilder.md)` templatesUriParameterBuilder)` 

This function returns a list of logs for a specific template.

#### Parameters
* `collectionName` The name of the collection you want to get the logs for.

* `templateId` The id of the template you want to get the logs for.

* `TemplatesUriParameterBuilder` This is a class that contains all the parameters that can be passed to the API.

#### Returns
A LogsDto object

##### `private readonly string ` [`_requestUriBase`](#class_atomic_assets_api_client_1_1_templates_1_1_templates_api_1a1854c4909a1013a684af16fb52e8a387) 

##### `private readonly ` [`IHttpHandler`](AtomicAssetsApiClient.md)` ` [`_httpHandler`](#class_atomic_assets_api_client_1_1_templates_1_1_templates_api_1a278528cd3027ee0a4ca8e04964f99674) 

##### `private Uri ` [`TemplatesUri`](#class_atomic_assets_api_client_1_1_templates_1_1_templates_api_1a70668a91db02b5409d48e972387179ce)`()` 

It returns a new `Uri` object that is the base URI for the templates endpoint

##### `private Uri ` [`TemplatesUri`](#class_atomic_assets_api_client_1_1_templates_1_1_templates_api_1a3120a9b5fd6173bdc6e13bf34ddcd6d1)`(` [`TemplatesUriParameterBuilder`](AtomicAssetsApiClient--Templates--TemplatesUriParameterBuilder.md)` templatessUriParameterBuilder)` 

It takes a `TemplatesUriParameterBuilder` object as a parameter and returns a `Uri` object.

#### Parameters
* `TemplatesUriParameterBuilder` A class that builds the query string parameters for the templates endpoint.

##### `private Uri ` [`TemplateUri`](#class_atomic_assets_api_client_1_1_templates_1_1_templates_api_1a495ebc65461d52505612c98c313f1326)`(string collectionName, string templateId)` 

It returns a URI for a specific template in a specific collection

#### Parameters
* `collectionName` The name of the collection that the template belongs to.

* `templateId` The name of the template you want to use.

##### `private Uri ` [`TemplateStatsUri`](#class_atomic_assets_api_client_1_1_templates_1_1_templates_api_1a5829798696aa9ecddd5e5f1c3e8ec1bc)`(string collectionName, string templateId)` 

This function returns a Uri that can be used to get the stats for a template

#### Parameters
* `collectionName` The name of the collection you want to use.

* `templateId` The template ID of the template you want to get stats for.

##### `private Uri ` [`TemplateLogsUri`](#class_atomic_assets_api_client_1_1_templates_1_1_templates_api_1a689ae101f2c19a4f3947dbdd0ee964e7)`(string collectionName, string templateId)` 

This function returns a Uri for the logs of a template

#### Parameters
* `collectionName` The name of the collection that the template belongs to.

* `templateId` The ID of the template you want to get logs for.

##### `private Uri ` [`TemplateLogsUri`](#class_atomic_assets_api_client_1_1_templates_1_1_templates_api_1acdf94dbd49b55bf713e8087ab05c4daf)`(string collectionName, string templateId, ` [`TemplatesUriParameterBuilder`](AtomicAssetsApiClient--Templates--TemplatesUriParameterBuilder.md)` templatesUriParameterBuilder)` 

This function returns a Uri for the logs of a template

#### Parameters
* `collectionName` The name of the collection that the template belongs to.

* `templateId` The id of the template you want to get logs for.

* `TemplatesUriParameterBuilder` This is a class that builds the query string parameters for the request.

