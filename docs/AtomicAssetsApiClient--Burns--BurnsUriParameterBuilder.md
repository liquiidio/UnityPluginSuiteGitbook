# class `AtomicAssetsApiClient::Burns::BurnsUriParameterBuilder` 

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public ` [`BurnsUriParameterBuilder`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_uri_parameter_builder)` ` [`WithCollectionName`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_uri_parameter_builder_1a6b0b20dbc97204c4fff8ac3a1b5ad778)`(string collectionName)` | `WithCollectionName` is a function that takes a string as a parameter and returns an `BurnsUriParameterBuilder` object
`public ` [`BurnsUriParameterBuilder`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_uri_parameter_builder)` ` [`WithSchemaName`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_uri_parameter_builder_1ad08753c17c7565ad4aab2aeb23e3f94e)`(string schemaName)` | This function sets the schema name for the query.
`public ` [`BurnsUriParameterBuilder`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_uri_parameter_builder)` ` [`WithTemplateId`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_uri_parameter_builder_1a58e1162efc3a891226f913753785fbdf)`(string templateId)` | It sets the value of the templateId variable.
`public ` [`BurnsUriParameterBuilder`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_uri_parameter_builder)` ` [`WithCollectionBlacklist`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_uri_parameter_builder_1af54bad0bcea14dc812c4f978ce96d588)`(string[] collectionBlacklist)` | `WithCollectionBlacklist` is a function that takes an array of strings and returns an `BurnsUriParameterBuilder` object
`public ` [`BurnsUriParameterBuilder`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_uri_parameter_builder)` ` [`WithCollectionWhitelist`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_uri_parameter_builder_1a19a29bf65ee5d83cb23c83f10b0f369c)`(string[] collectionWhitelist)` | `WithCollectionWhitelist` is a function that takes an array of strings and returns an `BurnsUriParameterBuilder` object
`public ` [`BurnsUriParameterBuilder`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_uri_parameter_builder)` ` [`WithIds`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_uri_parameter_builder_1ac1a5a0a582c7183ecb8aacd36cc10330)`(string[] ids)` | This function takes an array of strings and joins them together with a comma.
`public ` [`BurnsUriParameterBuilder`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_uri_parameter_builder)` ` [`WithLowerBound`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_uri_parameter_builder_1a99982432d3fcc77da0ea670cda73b5eb)`(string lowerBound)` | `WithLowerBound` sets the lower bound of the `account_ids` parameter
`public ` [`BurnsUriParameterBuilder`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_uri_parameter_builder)` ` [`WithUpperBound`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_uri_parameter_builder_1a2edef568006825e385d167479628dd9e)`(string upperBound)` | `WithUpperBound` sets the upper bound of the range of accounts to be returned
`public ` [`BurnsUriParameterBuilder`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_uri_parameter_builder)` ` [`WithPage`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_uri_parameter_builder_1a010dc4c7c88d9ae3ab469af928a2f3e8)`(int page)` | `WithPage` sets the `_page` variable to the value of the `page` parameter
`public ` [`BurnsUriParameterBuilder`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_uri_parameter_builder)` ` [`WithLimit`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_uri_parameter_builder_1a9aa9888884b4aa9833c132f88b6d17a6)`(int limit)` | `WithLimit` sets the `_limit` variable to the value of the `limit` parameter
`public ` [`BurnsUriParameterBuilder`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_uri_parameter_builder)` ` [`WithOrder`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_uri_parameter_builder_1a7fce18e7a4c84645bbcd9c6114a9352f)`(` [`SortStrategy`](.github/workflows/documentation/md/AtomicAssetsApiClient.md#namespace_atomic_assets_api_client_1a1a2688049f7c9dc4f77213ca78b6de0f)` sorting)` | This function sets the sort strategy for the query.
`public string ` [`Build`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_uri_parameter_builder_1a933ab72b517a9c3879ef78b27a2483bf)`()` | It builds a query string based on the parameters that have been set.
`private string ` [`_collectionName`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_uri_parameter_builder_1a10ec2fa990c6478bc519b1e57e1ab2aa) | 
`private string ` [`_schemaName`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_uri_parameter_builder_1a2f9a887fd4dfcf60bfe4240a27085724) | 
`private string ` [`_templateId`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_uri_parameter_builder_1a06f918051fc7b04615854510caa85934) | 
`private string ` [`_collectionBlacklist`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_uri_parameter_builder_1a11b225f8984dd9ab3ab5fcec261245c4) | 
`private string ` [`_collectionWhitelist`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_uri_parameter_builder_1a525c994ce1a584f4d763ac9d5c1b3cb5) | 
`private string ` [`_ids`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_uri_parameter_builder_1a2a9be788653dd13950b2f00bfce1970b) | 
`private string ` [`_lowerBound`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_uri_parameter_builder_1a47926893a523918c50a931018c47480d) | 
`private string ` [`_upperBound`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_uri_parameter_builder_1add1abf9a00e7bb81efb866424f4f34dc) | 
`private int? ` [`_page`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_uri_parameter_builder_1a4dea13c8190a694fe00b24309b1814f8) | 
`private int? ` [`_limit`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_uri_parameter_builder_1a353a19a0da576dc8f69a61548a710395) | 
`private ` [`SortStrategy`](.github/workflows/documentation/md/AtomicAssetsApiClient.md#namespace_atomic_assets_api_client_1a1a2688049f7c9dc4f77213ca78b6de0f)`? ` [`_sortStrategy`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_uri_parameter_builder_1a122ea78edfd15b44a8a547a7046b8651) | 

## Members

##### `public ` [`BurnsUriParameterBuilder`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_uri_parameter_builder)` ` [`WithCollectionName`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_uri_parameter_builder_1a6b0b20dbc97204c4fff8ac3a1b5ad778)`(string collectionName)` 

`WithCollectionName` is a function that takes a string as a parameter and returns an `BurnsUriParameterBuilder` object

#### Parameters
* `collectionName` The name of the collection you want to query.

#### Returns
The BurnsUriParameterBuilder object.

##### `public ` [`BurnsUriParameterBuilder`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_uri_parameter_builder)` ` [`WithSchemaName`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_uri_parameter_builder_1ad08753c17c7565ad4aab2aeb23e3f94e)`(string schemaName)` 

This function sets the schema name for the query.

#### Parameters
* `schemaName` The name of the schema to use.

#### Returns
The AccountsUriParameterBuilder object.

##### `public ` [`BurnsUriParameterBuilder`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_uri_parameter_builder)` ` [`WithTemplateId`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_uri_parameter_builder_1a58e1162efc3a891226f913753785fbdf)`(string templateId)` 

It sets the value of the templateId variable.

#### Parameters
* `templateId` The ID of the template to use for the account.

#### Returns
The BurnsUriParameterBuilder object.

##### `public ` [`BurnsUriParameterBuilder`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_uri_parameter_builder)` ` [`WithCollectionBlacklist`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_uri_parameter_builder_1af54bad0bcea14dc812c4f978ce96d588)`(string[] collectionBlacklist)` 

`WithCollectionBlacklist` is a function that takes an array of strings and returns an `BurnsUriParameterBuilder` object

#### Parameters
* `collectionBlacklist` A list of collections to exclude from the results.

#### Returns
The BurnsUriParameterBuilder object.

##### `public ` [`BurnsUriParameterBuilder`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_uri_parameter_builder)` ` [`WithCollectionWhitelist`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_uri_parameter_builder_1a19a29bf65ee5d83cb23c83f10b0f369c)`(string[] collectionWhitelist)` 

`WithCollectionWhitelist` is a function that takes an array of strings and returns an `BurnsUriParameterBuilder` object

#### Parameters
* `collectionWhitelist` A list of collections to include in the response.

#### Returns
The BurnsUriParameterBuilder object.

##### `public ` [`BurnsUriParameterBuilder`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_uri_parameter_builder)` ` [`WithIds`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_uri_parameter_builder_1ac1a5a0a582c7183ecb8aacd36cc10330)`(string[] ids)` 

This function takes an array of strings and joins them together with a comma.

#### Parameters
* `ids` A comma-separated list of account IDs.

#### Returns
The BurnsUriParameterBuilder object.

##### `public ` [`BurnsUriParameterBuilder`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_uri_parameter_builder)` ` [`WithLowerBound`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_uri_parameter_builder_1a99982432d3fcc77da0ea670cda73b5eb)`(string lowerBound)` 

`WithLowerBound` sets the lower bound of the `account_ids` parameter

#### Parameters
* `lowerBound` The lower bound of the accounts to retrieve.

#### Returns
The BurnsUriParameterBuilder object.

##### `public ` [`BurnsUriParameterBuilder`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_uri_parameter_builder)` ` [`WithUpperBound`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_uri_parameter_builder_1a2edef568006825e385d167479628dd9e)`(string upperBound)` 

`WithUpperBound` sets the upper bound of the range of accounts to be returned

#### Parameters
* `upperBound` The upper bound of the range to query.

#### Returns
The BurnsUriParameterBuilder object.

##### `public ` [`BurnsUriParameterBuilder`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_uri_parameter_builder)` ` [`WithPage`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_uri_parameter_builder_1a010dc4c7c88d9ae3ab469af928a2f3e8)`(int page)` 

`WithPage` sets the `_page` variable to the value of the `page` parameter

#### Parameters
* `page` The page number of the results to return.

#### Returns
The BurnsUriParameterBuilder object.

##### `public ` [`BurnsUriParameterBuilder`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_uri_parameter_builder)` ` [`WithLimit`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_uri_parameter_builder_1a9aa9888884b4aa9833c132f88b6d17a6)`(int limit)` 

`WithLimit` sets the `_limit` variable to the value of the `limit` parameter

#### Parameters
* `limit` The number of results to return.

#### Returns
The BurnsUriParameterBuilder object.

##### `public ` [`BurnsUriParameterBuilder`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_uri_parameter_builder)` ` [`WithOrder`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_uri_parameter_builder_1a7fce18e7a4c84645bbcd9c6114a9352f)`(` [`SortStrategy`](.github/workflows/documentation/md/AtomicAssetsApiClient.md#namespace_atomic_assets_api_client_1a1a2688049f7c9dc4f77213ca78b6de0f)` sorting)` 

This function sets the sort strategy for the query.

#### Parameters
* `SortStrategy` 

#### Returns
The builder object itself.

##### `public string ` [`Build`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_uri_parameter_builder_1a933ab72b517a9c3879ef78b27a2483bf)`()` 

It builds a query string based on the parameters that have been set.

#### Returns
A string that contains the parameters for the query.

##### `private string ` [`_collectionName`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_uri_parameter_builder_1a10ec2fa990c6478bc519b1e57e1ab2aa) 

##### `private string ` [`_schemaName`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_uri_parameter_builder_1a2f9a887fd4dfcf60bfe4240a27085724) 

##### `private string ` [`_templateId`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_uri_parameter_builder_1a06f918051fc7b04615854510caa85934) 

##### `private string ` [`_collectionBlacklist`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_uri_parameter_builder_1a11b225f8984dd9ab3ab5fcec261245c4) 

##### `private string ` [`_collectionWhitelist`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_uri_parameter_builder_1a525c994ce1a584f4d763ac9d5c1b3cb5) 

##### `private string ` [`_ids`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_uri_parameter_builder_1a2a9be788653dd13950b2f00bfce1970b) 

##### `private string ` [`_lowerBound`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_uri_parameter_builder_1a47926893a523918c50a931018c47480d) 

##### `private string ` [`_upperBound`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_uri_parameter_builder_1add1abf9a00e7bb81efb866424f4f34dc) 

##### `private int? ` [`_page`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_uri_parameter_builder_1a4dea13c8190a694fe00b24309b1814f8) 

##### `private int? ` [`_limit`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_uri_parameter_builder_1a353a19a0da576dc8f69a61548a710395) 

##### `private ` [`SortStrategy`](.github/workflows/documentation/md/AtomicAssetsApiClient.md#namespace_atomic_assets_api_client_1a1a2688049f7c9dc4f77213ca78b6de0f)`? ` [`_sortStrategy`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_uri_parameter_builder_1a122ea78edfd15b44a8a547a7046b8651) 

