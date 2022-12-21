# class `AtomicMarketApiClient::Transfers::TransfersUriParameterBuilder` 

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public ` [`TransfersUriParameterBuilder`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder)` ` [`WithAccount`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder_1af59f4a8a6840fa5a1550d02f7fb7a2dd)`(string account)` | `WithAccount` sets the `account` parameter
`public ` [`TransfersUriParameterBuilder`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder)` ` [`WithRecipient`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder_1a1153d8af3a5ddb610848a06498d9a4dd)`(string recipient)` | `WithRecipient` sets the `recipient` parameter
`public ` [`TransfersUriParameterBuilder`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder)` ` [`WithAssetId`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder_1ad6c2cf65c7cbcf992a6c552103c54823)`(string assetId)` | `WithAssetId` sets the assetId parameter
`public ` [`TransfersUriParameterBuilder`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder)` ` [`WithSender`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder_1ac7e6fec43448d261bdb09915f403bff8)`(string sender)` | `WithSender` sets the `sender` parameter
`public ` [`TransfersUriParameterBuilder`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder)` ` [`WithCollectionName`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder_1abc3a11082b9bc76a77a32c42ec37722b)`(string collectionName)` | 
`public ` [`TransfersUriParameterBuilder`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder)` ` [`WithSchemaName`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder_1a41f09cb31c7e928fe07e985ceeed6690)`(string schemaName)` | This function sets the schema name for the query.
`public ` [`TransfersUriParameterBuilder`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder)` ` [`WithTemplateId`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder_1a0b95df82022ced696713fbce52c008c3)`(string templateId)` | It sets the value of the templateId variable.
`public ` [`TransfersUriParameterBuilder`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder)` ` [`WithCollectionBlacklist`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder_1af40daebe2d6ae323cd6dbe84216f5841)`(string[] collectionBlacklist)` | `WithCollectionBlacklist` is a function that takes an array of strings and returns an `TransfersUriParameterBuilder` object
`public ` [`TransfersUriParameterBuilder`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder)` ` [`WithCollectionWhitelist`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder_1af515834be5fe24240fd21a2edd32a47e)`(string[] collectionWhitelist)` | `WithCollectionWhitelist` is a function that takes an array of strings and returns an `TransfersUriParameterBuilder` object
`public ` [`TransfersUriParameterBuilder`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder)` ` [`WithPage`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder_1a81116c0e2c466a1d667869646d62e2a0)`(int page)` | `WithPage` sets the `_page` variable to the value of the `page` parameter
`public ` [`TransfersUriParameterBuilder`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder)` ` [`WithLimit`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder_1a756c268697783b5604274f09f913cdcf)`(int limit)` | `WithLimit` sets the `_limit` variable to the value of the `limit` parameter
`public ` [`TransfersUriParameterBuilder`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder)` ` [`WithOrder`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder_1a9301a8382257d4b63d98703a5e704856)`(` [`SortStrategy`](.github/workflows/documentation/md/AtomicMarketApiClient--Core.md#namespace_atomic_market_api_client_1_1_core_1a1a2688049f7c9dc4f77213ca78b6de0f)` sorting)` | This function sets the sort strategy for the query.
`public ` [`TransfersUriParameterBuilder`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder)` ` [`WithSort`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder_1adf4159f0405483ab0dfad67097a8982d)`(string sort)` | It sets the sort parameter for the request.
`public string ` [`Build`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder_1a933ab72b517a9c3879ef78b27a2483bf)`()` | It builds a query string based on the parameters that have been set.
`private string ` [`_account`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder_1aa5823aa98a8362446f2f023628121726) | A private variable that is used to store the value of the account parameter.
`private string ` [`_sender`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder_1a9b2c3cb8c5158b682e95ceb6c25c52c6) | A private variable that is used to store the value of the sender parameter.
`private string ` [`_recipient`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder_1ab3841993274a2c1b32645ac088381cd7) | A private variable that is used to store the value of the recipient parameter.
`private string ` [`_assetId`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder_1a0dee4cb5aed35aa63cbc2976053d6892) | A private variable that is used to store the value of the assetId parameter.
`private string ` [`_templateId`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder_1a06f918051fc7b04615854510caa85934) | A private variable that is used to store the value of the templateId parameter.
`private string ` [`_schemaName`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder_1a2f9a887fd4dfcf60bfe4240a27085724) | A private variable that is used to store the value of the schemaName parameter.
`private string ` [`_collectionName`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder_1a10ec2fa990c6478bc519b1e57e1ab2aa) | A private variable that is used to store the value of the collectionName parameter.
`private string ` [`_collectionBlacklist`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder_1a11b225f8984dd9ab3ab5fcec261245c4) | A private variable that is used to store the value of the collectionBlacklist parameter.
`private string ` [`_collectionWhitelist`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder_1a525c994ce1a584f4d763ac9d5c1b3cb5) | A private variable that is used to store the value of the collectionWhitelist parameter.
`private int? ` [`_page`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder_1a4dea13c8190a694fe00b24309b1814f8) | A nullable integer specifying the page. <br/>
`private int? ` [`_limit`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder_1a353a19a0da576dc8f69a61548a710395) | A nullable integer specifying the limit of returned values.
`private ` [`SortStrategy`](.github/workflows/documentation/md/AtomicMarketApiClient--Core.md#namespace_atomic_market_api_client_1_1_core_1a1a2688049f7c9dc4f77213ca78b6de0f)`? ` [`_sortStrategy`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder_1a122ea78edfd15b44a8a547a7046b8651) | A nullable enum specifying the sortStrategy.
`private string ` [`_sort`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder_1a3ac373edf19e058d7fae7f4c4ba485f4) | A private variable that is used to store the value of the sort parameter.

## Members

##### `public ` [`TransfersUriParameterBuilder`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder)` ` [`WithAccount`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder_1af59f4a8a6840fa5a1550d02f7fb7a2dd)`(string account)` 

`WithAccount` sets the `account` parameter

#### Parameters
* `account` Notified account.

#### Returns
The TransfersUriParameterBuilder object.

##### `public ` [`TransfersUriParameterBuilder`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder)` ` [`WithRecipient`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder_1a1153d8af3a5ddb610848a06498d9a4dd)`(string recipient)` 

`WithRecipient` sets the `recipient` parameter

#### Parameters
* `recipient` Results base on transfer recipient.

#### Returns
The TransfersUriParameterBuilder object.

##### `public ` [`TransfersUriParameterBuilder`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder)` ` [`WithAssetId`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder_1ad6c2cf65c7cbcf992a6c552103c54823)`(string assetId)` 

`WithAssetId` sets the assetId parameter

#### Parameters
* `assetId` The assetId parameter shows transfers based on a certain assetId.

#### Returns
The TransfersUriParameterBuilder object.

##### `public ` [`TransfersUriParameterBuilder`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder)` ` [`WithSender`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder_1ac7e6fec43448d261bdb09915f403bff8)`(string sender)` 

`WithSender` sets the `sender` parameter

#### Parameters
* `sender` The sender parameter is used to filter the results. The sender parameter is a string that is matched against the account name.

#### Returns
The TransfersUriParameterBuilder object. 

summary> `WithCollectionName` is a function that takes a string as a parameter and returns an `TransfersUriParameterBuilder` object

#### Parameters
* `collectionName` The name of the collection you want to query.

#### Returns
The TransfersUriParameterBuilder object.

##### `public ` [`TransfersUriParameterBuilder`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder)` ` [`WithCollectionName`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder_1abc3a11082b9bc76a77a32c42ec37722b)`(string collectionName)` 

##### `public ` [`TransfersUriParameterBuilder`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder)` ` [`WithSchemaName`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder_1a41f09cb31c7e928fe07e985ceeed6690)`(string schemaName)` 

This function sets the schema name for the query.

#### Parameters
* `schemaName` The name of the schema to use.

#### Returns
The TransfersUriParameterBuilder object.

##### `public ` [`TransfersUriParameterBuilder`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder)` ` [`WithTemplateId`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder_1a0b95df82022ced696713fbce52c008c3)`(string templateId)` 

It sets the value of the templateId variable.

#### Parameters
* `templateId` Results based on only transfers which cointain assets of template.

#### Returns
The TranfersUriParameterBuilder object.

##### `public ` [`TransfersUriParameterBuilder`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder)` ` [`WithCollectionBlacklist`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder_1af40daebe2d6ae323cd6dbe84216f5841)`(string[] collectionBlacklist)` 

`WithCollectionBlacklist` is a function that takes an array of strings and returns an `TransfersUriParameterBuilder` object

#### Parameters
* `collectionBlacklist` A list of collections to exclude from the results.

#### Returns
The TransfersUriParameterBuilder object.

##### `public ` [`TransfersUriParameterBuilder`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder)` ` [`WithCollectionWhitelist`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder_1af515834be5fe24240fd21a2edd32a47e)`(string[] collectionWhitelist)` 

`WithCollectionWhitelist` is a function that takes an array of strings and returns an `TransfersUriParameterBuilder` object

#### Parameters
* `collectionWhitelist` A list of collections to include in the response.

#### Returns
The TransfersUriParameterBuilder object.

##### `public ` [`TransfersUriParameterBuilder`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder)` ` [`WithPage`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder_1a81116c0e2c466a1d667869646d62e2a0)`(int page)` 

`WithPage` sets the `_page` variable to the value of the `page` parameter

#### Parameters
* `page` The page number of the results to return.

#### Returns
The TransfersUriParameterBuilder object.

##### `public ` [`TransfersUriParameterBuilder`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder)` ` [`WithLimit`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder_1a756c268697783b5604274f09f913cdcf)`(int limit)` 

`WithLimit` sets the `_limit` variable to the value of the `limit` parameter

#### Parameters
* `limit` The number of results to return.

#### Returns
The TranfersUriParameterBuilder object.

##### `public ` [`TransfersUriParameterBuilder`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder)` ` [`WithOrder`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder_1a9301a8382257d4b63d98703a5e704856)`(` [`SortStrategy`](.github/workflows/documentation/md/AtomicMarketApiClient--Core.md#namespace_atomic_market_api_client_1_1_core_1a1a2688049f7c9dc4f77213ca78b6de0f)` sorting)` 

This function sets the sort strategy for the query.

#### Parameters
* `SortStrategy` 

#### Returns
The builder object itself.

##### `public ` [`TransfersUriParameterBuilder`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder)` ` [`WithSort`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder_1adf4159f0405483ab0dfad67097a8982d)`(string sort)` 

It sets the sort parameter for the request.

#### Parameters
* `sort` The order in which to sort the results.

#### Returns
A TransfersUriParameterBuilder object.

##### `public string ` [`Build`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder_1a933ab72b517a9c3879ef78b27a2483bf)`()` 

It builds a query string based on the parameters that have been set.

#### Returns
A string that contains the parameters for the query.

##### `private string ` [`_account`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder_1aa5823aa98a8362446f2f023628121726) 

A private variable that is used to store the value of the account parameter.

##### `private string ` [`_sender`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder_1a9b2c3cb8c5158b682e95ceb6c25c52c6) 

A private variable that is used to store the value of the sender parameter.

##### `private string ` [`_recipient`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder_1ab3841993274a2c1b32645ac088381cd7) 

A private variable that is used to store the value of the recipient parameter.

##### `private string ` [`_assetId`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder_1a0dee4cb5aed35aa63cbc2976053d6892) 

A private variable that is used to store the value of the assetId parameter.

##### `private string ` [`_templateId`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder_1a06f918051fc7b04615854510caa85934) 

A private variable that is used to store the value of the templateId parameter.

##### `private string ` [`_schemaName`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder_1a2f9a887fd4dfcf60bfe4240a27085724) 

A private variable that is used to store the value of the schemaName parameter.

##### `private string ` [`_collectionName`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder_1a10ec2fa990c6478bc519b1e57e1ab2aa) 

A private variable that is used to store the value of the collectionName parameter.

##### `private string ` [`_collectionBlacklist`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder_1a11b225f8984dd9ab3ab5fcec261245c4) 

A private variable that is used to store the value of the collectionBlacklist parameter.

##### `private string ` [`_collectionWhitelist`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder_1a525c994ce1a584f4d763ac9d5c1b3cb5) 

A private variable that is used to store the value of the collectionWhitelist parameter.

##### `private int? ` [`_page`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder_1a4dea13c8190a694fe00b24309b1814f8) 

A nullable integer specifying the page. <br/>

##### `private int? ` [`_limit`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder_1a353a19a0da576dc8f69a61548a710395) 

A nullable integer specifying the limit of returned values.

##### `private ` [`SortStrategy`](.github/workflows/documentation/md/AtomicMarketApiClient--Core.md#namespace_atomic_market_api_client_1_1_core_1a1a2688049f7c9dc4f77213ca78b6de0f)`? ` [`_sortStrategy`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder_1a122ea78edfd15b44a8a547a7046b8651) 

A nullable enum specifying the sortStrategy.

##### `private string ` [`_sort`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_uri_parameter_builder_1a3ac373edf19e058d7fae7f4c4ba485f4) 

A private variable that is used to store the value of the sort parameter.

