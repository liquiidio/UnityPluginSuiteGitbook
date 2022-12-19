# class `AtomicAssetsApiClient::Schemas::SchemasUriParameterBuilder` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public SchemasUriParameterBuilder `[`WithCollectionName`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_uri_parameter_builder_1af3432832f998b281e1d7e7df2497ce57)`(string collectionName)` | `WithCollectionName` is a function that takes a string as a parameter and returns an `SchemasUriParameterBuilder` object
`public SchemasUriParameterBuilder `[`WithSchemaName`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_uri_parameter_builder_1aa1572666f2afe6b6422daff1d7c27f71)`(string schemaName)` | This function sets the schema name for the query.
`public SchemasUriParameterBuilder `[`WithMatch`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_uri_parameter_builder_1aa2b7800ca324592d54ce2de19b2b8d19)`(string match)` | `WithMatch` sets the `match` parameter
`public SchemasUriParameterBuilder `[`WithCollectionBlacklist`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_uri_parameter_builder_1a72b75064f56cbac34561576ca226be69)`(string[] collectionBlacklist)` | `WithCollectionBlacklist` is a function that takes an array of strings and returns an `SchemasUriParameterBuilder` object
`public SchemasUriParameterBuilder `[`WithCollectionWhitelist`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_uri_parameter_builder_1a15a4a8205b786acffa5809ef9866e2f4)`(string[] collectionWhitelist)` | `WithCollectionWhitelist` is a function that takes an array of strings and returns an `SchemasUriParameterBuilder` object
`public SchemasUriParameterBuilder `[`WithAuthorisedAccount`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_uri_parameter_builder_1a198ebbdd0c202d5930e576c49a572b71)`(string authorisedAccount)` | `WithAuthorisedAccount` sets the `authorisedAccount` parameter
`public SchemasUriParameterBuilder `[`WithIds`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_uri_parameter_builder_1a7f556adc0fd92ed55e869112bd6e9d57)`(string[] ids)` | This function takes an array of strings and joins them together with a comma.
`public SchemasUriParameterBuilder `[`WithLowerBound`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_uri_parameter_builder_1add535eb34ac25778b16811a11e7b05f7)`(string lowerBound)` | `WithLowerBound` sets the lower bound of the `account_ids` parameter
`public SchemasUriParameterBuilder `[`WithUpperBound`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_uri_parameter_builder_1acf2aaff862d79e4e0d81cba4c11457fd)`(string upperBound)` | `WithUpperBound` sets the upper bound of the range of accounts to be returned
`public SchemasUriParameterBuilder `[`WithBefore`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_uri_parameter_builder_1ab97e5a3c2ad374ffaaa7b3daf63865f0)`(int before)` | `WithBefore` sets the `_before` variable to the value of the `before` parameter
`public SchemasUriParameterBuilder `[`WithAfter`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_uri_parameter_builder_1a090af84d20ab951e0aa264938d5a4c06)`(int after)` | `WithAfter` sets the `_after` variable to the value of the `after` parameter
`public SchemasUriParameterBuilder `[`WithPage`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_uri_parameter_builder_1a2c6c1311c2dda195bd297edd5b68c75e)`(int page)` | `WithPage` sets the `_page` variable to the value of the `page` parameter
`public SchemasUriParameterBuilder `[`WithLimit`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_uri_parameter_builder_1a88e6a6e3614e47a93cb37513e695b9b1)`(int limit)` | `WithLimit` sets the `_limit` variable to the value of the `limit` parameter
`public SchemasUriParameterBuilder `[`WithOrder`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_uri_parameter_builder_1a67ebfab389161f2e890516a3ebe9031d)`(SortStrategy sorting)` | This function sets the sort strategy for the query.
`public SchemasUriParameterBuilder `[`WithSort`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_uri_parameter_builder_1a53c9183c04d79345180abf2738db70bd)`(string sort)` | It sets the sort parameter.
`public string `[`Build`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_uri_parameter_builder_1a933ab72b517a9c3879ef78b27a2483bf)`()` | It builds a query string based on the parameters that have been set.
`private string `[`_collectionName`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_uri_parameter_builder_1a10ec2fa990c6478bc519b1e57e1ab2aa) | 
`private string `[`_authorisedAccount`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_uri_parameter_builder_1a5a6c4dfbab849af1ded34201e3f5a886) | 
`private string `[`_schemaName`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_uri_parameter_builder_1a2f9a887fd4dfcf60bfe4240a27085724) | 
`private string `[`_match`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_uri_parameter_builder_1a5151210a8aa5d34ea523afbb052deb11) | 
`private string `[`_collectionBlacklist`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_uri_parameter_builder_1a11b225f8984dd9ab3ab5fcec261245c4) | 
`private string `[`_collectionWhitelist`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_uri_parameter_builder_1a525c994ce1a584f4d763ac9d5c1b3cb5) | 
`private string `[`_ids`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_uri_parameter_builder_1a2a9be788653dd13950b2f00bfce1970b) | 
`private string `[`_lowerBound`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_uri_parameter_builder_1a47926893a523918c50a931018c47480d) | 
`private string `[`_upperBound`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_uri_parameter_builder_1add1abf9a00e7bb81efb866424f4f34dc) | 
`private int? `[`_before`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_uri_parameter_builder_1aab4304cf3e09c19e898fe9224a0d723a) | 
`private int? `[`_after`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_uri_parameter_builder_1ae1483718c3d317e0b6046ada434c53ae) | 
`private int? `[`_page`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_uri_parameter_builder_1a4dea13c8190a694fe00b24309b1814f8) | 
`private int? `[`_limit`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_uri_parameter_builder_1a353a19a0da576dc8f69a61548a710395) | 
`private SortStrategy? `[`_sortStrategy`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_uri_parameter_builder_1a122ea78edfd15b44a8a547a7046b8651) | 
`private string `[`_sort`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_uri_parameter_builder_1a3ac373edf19e058d7fae7f4c4ba485f4) | 

## Members

### `public SchemasUriParameterBuilder `[`WithCollectionName`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_uri_parameter_builder_1af3432832f998b281e1d7e7df2497ce57)`(string collectionName)` 

`WithCollectionName` is a function that takes a string as a parameter and returns an `SchemasUriParameterBuilder` object

#### Parameters
* `collectionName` The name of the collection you want to query.

#### Returns
The SchemasUriParameterBuilder object.

### `public SchemasUriParameterBuilder `[`WithSchemaName`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_uri_parameter_builder_1aa1572666f2afe6b6422daff1d7c27f71)`(string schemaName)` 

This function sets the schema name for the query.

#### Parameters
* `schemaName` The name of the schema to use.

#### Returns
The ShemasUriParameterBuilder object.

### `public SchemasUriParameterBuilder `[`WithMatch`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_uri_parameter_builder_1aa2b7800ca324592d54ce2de19b2b8d19)`(string match)` 

`WithMatch` sets the `match` parameter

#### Parameters
* `match` The match parameter is used to filter the results. The match parameter is a string that is matched against the account name.

#### Returns
The SchemasUriParameterBuilder object.

### `public SchemasUriParameterBuilder `[`WithCollectionBlacklist`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_uri_parameter_builder_1a72b75064f56cbac34561576ca226be69)`(string[] collectionBlacklist)` 

`WithCollectionBlacklist` is a function that takes an array of strings and returns an `SchemasUriParameterBuilder` object

#### Parameters
* `collectionBlacklist` A list of collections to exclude from the results.

#### Returns
The SchemasUriParameterBuilder object.

### `public SchemasUriParameterBuilder `[`WithCollectionWhitelist`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_uri_parameter_builder_1a15a4a8205b786acffa5809ef9866e2f4)`(string[] collectionWhitelist)` 

`WithCollectionWhitelist` is a function that takes an array of strings and returns an `SchemasUriParameterBuilder` object

#### Parameters
* `collectionWhitelist` A list of collections to include in the response.

#### Returns
The SchemasUriParameterBuilder object.

### `public SchemasUriParameterBuilder `[`WithAuthorisedAccount`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_uri_parameter_builder_1a198ebbdd0c202d5930e576c49a572b71)`(string authorisedAccount)` 

`WithAuthorisedAccount` sets the `authorisedAccount` parameter

#### Parameters
* `authorisedAccount` The authorisedAccount parameter is used to filter the results the provided account can edit.

#### Returns
The SchemasUriParameterBuilder object.

### `public SchemasUriParameterBuilder `[`WithIds`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_uri_parameter_builder_1a7f556adc0fd92ed55e869112bd6e9d57)`(string[] ids)` 

This function takes an array of strings and joins them together with a comma.

#### Parameters
* `ids` A comma-separated list of account IDs.

#### Returns
The SchemasUriParameterBuilder object.

### `public SchemasUriParameterBuilder `[`WithLowerBound`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_uri_parameter_builder_1add535eb34ac25778b16811a11e7b05f7)`(string lowerBound)` 

`WithLowerBound` sets the lower bound of the `account_ids` parameter

#### Parameters
* `lowerBound` The lower bound of the accounts to retrieve.

#### Returns
The SchemasUriParameterBuilder object.

### `public SchemasUriParameterBuilder `[`WithUpperBound`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_uri_parameter_builder_1acf2aaff862d79e4e0d81cba4c11457fd)`(string upperBound)` 

`WithUpperBound` sets the upper bound of the range of accounts to be returned

#### Parameters
* `upperBound` The upper bound of the range to query.

#### Returns
The SchemasUriParameterBuilder object.

### `public SchemasUriParameterBuilder `[`WithBefore`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_uri_parameter_builder_1ab97e5a3c2ad374ffaaa7b3daf63865f0)`(int before)` 

`WithBefore` sets the `_before` variable to the value of the `before` parameter

#### Parameters
* `before` The previous values of the results to return.

#### Returns
The SchemasUriParameterBuilder object.

### `public SchemasUriParameterBuilder `[`WithAfter`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_uri_parameter_builder_1a090af84d20ab951e0aa264938d5a4c06)`(int after)` 

`WithAfter` sets the `_after` variable to the value of the `after` parameter

#### Parameters
* `after` The later values of the results to return.

#### Returns
The SchemasUriParameterBuilder object.

### `public SchemasUriParameterBuilder `[`WithPage`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_uri_parameter_builder_1a2c6c1311c2dda195bd297edd5b68c75e)`(int page)` 

`WithPage` sets the `_page` variable to the value of the `page` parameter

#### Parameters
* `page` The page number of the results to return.

#### Returns
The SchemasUriParameterBuilder object.

### `public SchemasUriParameterBuilder `[`WithLimit`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_uri_parameter_builder_1a88e6a6e3614e47a93cb37513e695b9b1)`(int limit)` 

`WithLimit` sets the `_limit` variable to the value of the `limit` parameter

#### Parameters
* `limit` The number of results to return.

#### Returns
The SchemasUriParameterBuilder object.

### `public SchemasUriParameterBuilder `[`WithOrder`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_uri_parameter_builder_1a67ebfab389161f2e890516a3ebe9031d)`(SortStrategy sorting)` 

This function sets the sort strategy for the query.

#### Parameters
* `SortStrategy` 

#### Returns
The builder object itself.

### `public SchemasUriParameterBuilder `[`WithSort`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_uri_parameter_builder_1a53c9183c04d79345180abf2738db70bd)`(string sort)` 

It sets the sort parameter.

#### Parameters
* `sort` The sort order of the results.

#### Returns
A new instance of the SchemasUriParameterBuilder class.

### `public string `[`Build`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_uri_parameter_builder_1a933ab72b517a9c3879ef78b27a2483bf)`()` 

It builds a query string based on the parameters that have been set.

#### Returns
A string that contains the parameters for the query.

### `private string `[`_collectionName`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_uri_parameter_builder_1a10ec2fa990c6478bc519b1e57e1ab2aa) 

### `private string `[`_authorisedAccount`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_uri_parameter_builder_1a5a6c4dfbab849af1ded34201e3f5a886) 

### `private string `[`_schemaName`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_uri_parameter_builder_1a2f9a887fd4dfcf60bfe4240a27085724) 

### `private string `[`_match`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_uri_parameter_builder_1a5151210a8aa5d34ea523afbb052deb11) 

### `private string `[`_collectionBlacklist`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_uri_parameter_builder_1a11b225f8984dd9ab3ab5fcec261245c4) 

### `private string `[`_collectionWhitelist`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_uri_parameter_builder_1a525c994ce1a584f4d763ac9d5c1b3cb5) 

### `private string `[`_ids`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_uri_parameter_builder_1a2a9be788653dd13950b2f00bfce1970b) 

### `private string `[`_lowerBound`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_uri_parameter_builder_1a47926893a523918c50a931018c47480d) 

### `private string `[`_upperBound`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_uri_parameter_builder_1add1abf9a00e7bb81efb866424f4f34dc) 

### `private int? `[`_before`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_uri_parameter_builder_1aab4304cf3e09c19e898fe9224a0d723a) 

### `private int? `[`_after`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_uri_parameter_builder_1ae1483718c3d317e0b6046ada434c53ae) 

### `private int? `[`_page`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_uri_parameter_builder_1a4dea13c8190a694fe00b24309b1814f8) 

### `private int? `[`_limit`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_uri_parameter_builder_1a353a19a0da576dc8f69a61548a710395) 

### `private SortStrategy? `[`_sortStrategy`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_uri_parameter_builder_1a122ea78edfd15b44a8a547a7046b8651) 

### `private string `[`_sort`](#class_atomic_assets_api_client_1_1_schemas_1_1_schemas_uri_parameter_builder_1a3ac373edf19e058d7fae7f4c4ba485f4) 

