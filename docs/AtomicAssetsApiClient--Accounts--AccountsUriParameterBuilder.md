# class `AtomicAssetsApiClient::Accounts::AccountsUriParameterBuilder` 

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public ` [`AccountsUriParameterBuilder`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder)` ` [`WithMatch`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder_1a627b3ee2d323b5cdf38584a9217bd3f1)`(string match)` | `WithMatch` sets the `match` parameter
`public ` [`AccountsUriParameterBuilder`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder)` ` [`WithHideOffers`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder_1ad4b813a5251a94dd616cec740236d197)`(bool hideOffers)` | `WithHideOffers` sets the `_hideOffers` field to the value of the `hideOffers` parameter
`public ` [`AccountsUriParameterBuilder`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder)` ` [`WithCollectionName`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder_1a3ddd26216d39319bb4e9bfe1fe05a521)`(string collectionName)` | `WithCollectionName` is a function that takes a string as a parameter and returns an `AccountsUriParameterBuilder` object
`public ` [`AccountsUriParameterBuilder`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder)` ` [`WithSchemaName`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder_1a40753911e5d3b71c24c96963ac51c505)`(string schemaName)` | This function sets the schema name for the query.
`public ` [`AccountsUriParameterBuilder`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder)` ` [`WithTemplateId`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder_1a19169fbef2fee06291042615608fbc90)`(string templateId)` | It sets the value of the templateId variable.
`public ` [`AccountsUriParameterBuilder`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder)` ` [`WithCollectionBlacklist`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder_1a21c3ab9c66bbc428ac0d5a509c706d2b)`(string[] collectionBlacklist)` | `WithCollectionBlacklist` is a function that takes an array of strings and returns an `AccountsUriParameterBuilder` object
`public ` [`AccountsUriParameterBuilder`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder)` ` [`WithCollectionWhitelist`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder_1a8164c7221fd7c5a0ba2642d7e424db63)`(string[] collectionWhitelist)` | `WithCollectionWhitelist` is a function that takes an array of strings and returns an `AccountsUriParameterBuilder` object
`public ` [`AccountsUriParameterBuilder`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder)` ` [`WithIds`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder_1a75fa29922de14cedf2b8b53cc4724a8b)`(string[] ids)` | This function takes an array of strings and joins them together with a comma.
`public ` [`AccountsUriParameterBuilder`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder)` ` [`WithLowerBound`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder_1af0b389e7e8655fe12125d89586356034)`(string lowerBound)` | `WithLowerBound` sets the lower bound of the `account_ids` parameter
`public ` [`AccountsUriParameterBuilder`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder)` ` [`WithUpperBound`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder_1a9a23e816133435e2faac5eca3c8788d1)`(string upperBound)` | `WithUpperBound` sets the upper bound of the range of accounts to be returned
`public ` [`AccountsUriParameterBuilder`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder)` ` [`WithPage`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder_1afd839412cf872baef0cbef3ed9ebf850)`(int page)` | `WithPage` sets the `_page` variable to the value of the `page` parameter
`public ` [`AccountsUriParameterBuilder`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder)` ` [`WithLimit`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder_1af64d10b4de3df2ab1cb525ba22c1d5d2)`(int limit)` | `WithLimit` sets the `_limit` variable to the value of the `limit` parameter
`public ` [`AccountsUriParameterBuilder`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder)` ` [`WithOrder`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder_1a208c7ec3b1735911de948f9056319031)`(` [`SortStrategy`](AtomicAssetsApiClient.md)` sorting)` | This function sets the sort strategy for the query.
`public string ` [`Build`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder_1a933ab72b517a9c3879ef78b27a2483bf)`()` | It builds a query string based on the parameters that have been set.
`private string ` [`_match`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder_1a5151210a8aa5d34ea523afbb052deb11) | 
`private string ` [`_collectionName`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder_1a10ec2fa990c6478bc519b1e57e1ab2aa) | 
`private string ` [`_schemaName`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder_1a2f9a887fd4dfcf60bfe4240a27085724) | 
`private string ` [`_templateId`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder_1a06f918051fc7b04615854510caa85934) | 
`private bool? ` [`_hideOffers`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder_1a5d1a8bcf6c17c11dee4582a653ca807b) | 
`private string ` [`_collectionBlacklist`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder_1a11b225f8984dd9ab3ab5fcec261245c4) | 
`private string ` [`_collectionWhitelist`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder_1a525c994ce1a584f4d763ac9d5c1b3cb5) | 
`private string ` [`_ids`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder_1a2a9be788653dd13950b2f00bfce1970b) | 
`private string ` [`_lowerBound`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder_1a47926893a523918c50a931018c47480d) | 
`private string ` [`_upperBound`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder_1add1abf9a00e7bb81efb866424f4f34dc) | 
`private int? ` [`_page`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder_1a4dea13c8190a694fe00b24309b1814f8) | 
`private int? ` [`_limit`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder_1a353a19a0da576dc8f69a61548a710395) | 
`private ` [`SortStrategy`](AtomicAssetsApiClient.md)`? ` [`_sortStrategy`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder_1a122ea78edfd15b44a8a547a7046b8651) | 

## Members

##### `public ` [`AccountsUriParameterBuilder`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder)` ` [`WithMatch`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder_1a627b3ee2d323b5cdf38584a9217bd3f1)`(string match)` 

`WithMatch` sets the `match` parameter

#### Parameters
* `match` The match parameter is used to filter the results. The match parameter is a string that is matched against the account name.

#### Returns
The AccountsUriParameterBuilder object.

##### `public ` [`AccountsUriParameterBuilder`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder)` ` [`WithHideOffers`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder_1ad4b813a5251a94dd616cec740236d197)`(bool hideOffers)` 

`WithHideOffers` sets the `_hideOffers` field to the value of the `hideOffers` parameter

#### Parameters
* `hideOffers` If true, the response will not include any offers.

#### Returns
The AccountsUriParameterBuilder object.

##### `public ` [`AccountsUriParameterBuilder`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder)` ` [`WithCollectionName`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder_1a3ddd26216d39319bb4e9bfe1fe05a521)`(string collectionName)` 

`WithCollectionName` is a function that takes a string as a parameter and returns an `AccountsUriParameterBuilder` object

#### Parameters
* `collectionName` The name of the collection you want to query.

#### Returns
The AccountsUriParameterBuilder object.

##### `public ` [`AccountsUriParameterBuilder`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder)` ` [`WithSchemaName`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder_1a40753911e5d3b71c24c96963ac51c505)`(string schemaName)` 

This function sets the schema name for the query.

#### Parameters
* `schemaName` The name of the schema to use.

#### Returns
The AccountsUriParameterBuilder object.

##### `public ` [`AccountsUriParameterBuilder`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder)` ` [`WithTemplateId`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder_1a19169fbef2fee06291042615608fbc90)`(string templateId)` 

It sets the value of the templateId variable.

#### Parameters
* `templateId` The ID of the template to use for the account.

#### Returns
The AccountsUriParameterBuilder object.

##### `public ` [`AccountsUriParameterBuilder`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder)` ` [`WithCollectionBlacklist`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder_1a21c3ab9c66bbc428ac0d5a509c706d2b)`(string[] collectionBlacklist)` 

`WithCollectionBlacklist` is a function that takes an array of strings and returns an `AccountsUriParameterBuilder` object

#### Parameters
* `collectionBlacklist` A list of collections to exclude from the results.

#### Returns
The AccountsUriParameterBuilder object.

##### `public ` [`AccountsUriParameterBuilder`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder)` ` [`WithCollectionWhitelist`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder_1a8164c7221fd7c5a0ba2642d7e424db63)`(string[] collectionWhitelist)` 

`WithCollectionWhitelist` is a function that takes an array of strings and returns an `AccountsUriParameterBuilder` object

#### Parameters
* `collectionWhitelist` A list of collections to include in the response.

#### Returns
The AccountsUriParameterBuilder object.

##### `public ` [`AccountsUriParameterBuilder`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder)` ` [`WithIds`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder_1a75fa29922de14cedf2b8b53cc4724a8b)`(string[] ids)` 

This function takes an array of strings and joins them together with a comma.

#### Parameters
* `ids` A comma-separated list of account IDs.

#### Returns
A string

##### `public ` [`AccountsUriParameterBuilder`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder)` ` [`WithLowerBound`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder_1af0b389e7e8655fe12125d89586356034)`(string lowerBound)` 

`WithLowerBound` sets the lower bound of the `account_ids` parameter

#### Parameters
* `lowerBound` The lower bound of the accounts to retrieve.

#### Returns
The AccountsUriParameterBuilder object.

##### `public ` [`AccountsUriParameterBuilder`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder)` ` [`WithUpperBound`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder_1a9a23e816133435e2faac5eca3c8788d1)`(string upperBound)` 

`WithUpperBound` sets the upper bound of the range of accounts to be returned

#### Parameters
* `upperBound` The upper bound of the range to query.

#### Returns
The AccountsUriParameterBuilder object.

##### `public ` [`AccountsUriParameterBuilder`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder)` ` [`WithPage`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder_1afd839412cf872baef0cbef3ed9ebf850)`(int page)` 

`WithPage` sets the `_page` variable to the value of the `page` parameter

#### Parameters
* `page` The page number of the results to return.

#### Returns
The AccountsUriParameterBuilder object.

##### `public ` [`AccountsUriParameterBuilder`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder)` ` [`WithLimit`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder_1af64d10b4de3df2ab1cb525ba22c1d5d2)`(int limit)` 

`WithLimit` sets the `_limit` variable to the value of the `limit` parameter

#### Parameters
* `limit` The number of results to return.

#### Returns
The AccountsUriParameterBuilder object.

##### `public ` [`AccountsUriParameterBuilder`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder)` ` [`WithOrder`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder_1a208c7ec3b1735911de948f9056319031)`(` [`SortStrategy`](AtomicAssetsApiClient.md)` sorting)` 

This function sets the sort strategy for the query.

#### Parameters
* `SortStrategy` 

#### Returns
The builder object itself.

##### `public string ` [`Build`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder_1a933ab72b517a9c3879ef78b27a2483bf)`()` 

It builds a query string based on the parameters that have been set.

#### Returns
A string that contains the parameters for the query.

##### `private string ` [`_match`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder_1a5151210a8aa5d34ea523afbb052deb11) 

##### `private string ` [`_collectionName`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder_1a10ec2fa990c6478bc519b1e57e1ab2aa) 

##### `private string ` [`_schemaName`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder_1a2f9a887fd4dfcf60bfe4240a27085724) 

##### `private string ` [`_templateId`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder_1a06f918051fc7b04615854510caa85934) 

##### `private bool? ` [`_hideOffers`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder_1a5d1a8bcf6c17c11dee4582a653ca807b) 

##### `private string ` [`_collectionBlacklist`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder_1a11b225f8984dd9ab3ab5fcec261245c4) 

##### `private string ` [`_collectionWhitelist`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder_1a525c994ce1a584f4d763ac9d5c1b3cb5) 

##### `private string ` [`_ids`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder_1a2a9be788653dd13950b2f00bfce1970b) 

##### `private string ` [`_lowerBound`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder_1a47926893a523918c50a931018c47480d) 

##### `private string ` [`_upperBound`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder_1add1abf9a00e7bb81efb866424f4f34dc) 

##### `private int? ` [`_page`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder_1a4dea13c8190a694fe00b24309b1814f8) 

##### `private int? ` [`_limit`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder_1a353a19a0da576dc8f69a61548a710395) 

##### `private ` [`SortStrategy`](AtomicAssetsApiClient.md)`? ` [`_sortStrategy`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_uri_parameter_builder_1a122ea78edfd15b44a8a547a7046b8651) 

