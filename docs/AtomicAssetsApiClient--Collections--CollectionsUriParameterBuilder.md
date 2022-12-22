# class `AtomicAssetsApiClient::Collections::CollectionsUriParameterBuilder` 

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public ` [`CollectionsUriParameterBuilder`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder)` ` [`WithAuthor`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder_1ae456148aed84a464aab20ee43665750a)`(string author)` | `WithAuthor` sets the `author` parameter
`public ` [`CollectionsUriParameterBuilder`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder)` ` [`WithMatch`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder_1adefbe91edff96db187a1e3b23d7c7766)`(string match)` | `WithMatch` sets the `match` parameter
`public ` [`CollectionsUriParameterBuilder`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder)` ` [`WithCollectionBlacklist`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder_1a0156166418fae08028a828dda03ea92a)`(string[] collectionBlacklist)` | `WithCollectionBlacklist` is a function that takes an array of strings and returns an `AssetsUriParameterBuilder` object
`public ` [`CollectionsUriParameterBuilder`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder)` ` [`WithCollectionWhitelist`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder_1acd97fc96a67333c4b69eaf1c80063958)`(string[] collectionWhitelist)` | `WithCollectionWhitelist` is a function that takes an array of strings and returns an `CollectionsUriParameterBuilder` object
`public ` [`CollectionsUriParameterBuilder`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder)` ` [`WithAuthorisedAccount`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder_1a71d95cd4ccb4d3e148d24043fb936175)`(string authorisedAccount)` | `WithAuthorisedAccount` sets the `authorisedAccount` parameter
`public ` [`CollectionsUriParameterBuilder`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder)` ` [`WithIds`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder_1acd5f8394565b62858c8ce28b912388b6)`(string[] ids)` | This function takes an array of strings and joins them together with a comma.
`public ` [`CollectionsUriParameterBuilder`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder)` ` [`WithNotifyAccount`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder_1a4d3941504c9b050b93fad1edbefb51da)`(string notifyAccount)` | `WithNotifyAccount` sets the `notifyAccount` parameter
`public ` [`CollectionsUriParameterBuilder`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder)` ` [`WithLowerBound`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder_1a7752249152d69369110d622c549bc340)`(string lowerBound)` | `WithLowerBound` sets the lower bound of the `account_ids` parameter
`public ` [`CollectionsUriParameterBuilder`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder)` ` [`WithUpperBound`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder_1aafc65336a98f5e84867165e447f2f639)`(string upperBound)` | `WithUpperBound` sets the upper bound of the range of accounts to be returned
`public ` [`CollectionsUriParameterBuilder`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder)` ` [`WithBefore`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder_1a46b58fa9ab3b082e19e69456e8850d8e)`(int before)` | `WithBefore` sets the `_before` variable to the value of the `before` parameter
`public ` [`CollectionsUriParameterBuilder`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder)` ` [`WithAfter`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder_1a9d8d7aba2d2ae6bdec9e9b23d95a9595)`(int after)` | `WithAfter` sets the `_after` variable to the value of the `after` parameter
`public ` [`CollectionsUriParameterBuilder`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder)` ` [`WithPage`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder_1a1b1d62378b6ea39fee85e5f7b014e235)`(int page)` | `WithPage` sets the `_page` variable to the value of the `page` parameter
`public ` [`CollectionsUriParameterBuilder`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder)` ` [`WithLimit`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder_1aa6ad1937b11c448990ec6d76683026af)`(int limit)` | `WithLimit` sets the `_limit` variable to the value of the `limit` parameter
`public ` [`CollectionsUriParameterBuilder`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder)` ` [`WithOrder`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder_1aa3c44ce00b2581fd596c286729f58291)`(` [`SortStrategy`](AtomicAssetsApiClient.md)` sorting)` | This function sets the sort strategy for the query.
`public ` [`CollectionsUriParameterBuilder`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder)` ` [`WithSort`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder_1a8ddb47c59bb3989f9c216a1efc5f91e9)`(string sort)` | `WithSort` is a function that takes a string as an argument and returns a `CollectionsUriParameterBuilder` object.
`public string ` [`Build`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder_1a933ab72b517a9c3879ef78b27a2483bf)`()` | It takes all the properties of the class and builds a query string based on the values of those properties.
`private string ` [`_author`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder_1a65e941a52e3bfe2a9e26ef7c97c7359a) | A private variable that is used to store the value of the author parameter.
`private string ` [`_match`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder_1a5151210a8aa5d34ea523afbb052deb11) | A private variable that is used to store the value of the match parameter.
`private string ` [`_authorisedAccount`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder_1a5a6c4dfbab849af1ded34201e3f5a886) | A private variable that is used to store the value of the authorisedAccount parameter.
`private string ` [`_notifyAccount`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder_1a68443b0373a87f7b7698727c5fedd56f) | A private variable that is used to store the value of the notifyAccount parameter.
`private string ` [`_collectionBlacklist`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder_1a11b225f8984dd9ab3ab5fcec261245c4) | A private variable that is used to store the value of the collectionBlacklist parameter.
`private string ` [`_collectionWhitelist`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder_1a525c994ce1a584f4d763ac9d5c1b3cb5) | A private variable that is used to store the value of the collectionWhitelist parameter.
`private string ` [`_ids`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder_1a2a9be788653dd13950b2f00bfce1970b) | A private variable that is used to store the value of the Ids parameter.
`private string ` [`_lowerBound`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder_1a47926893a523918c50a931018c47480d) | A private variable that is used to store the value of the lowerBound parameter.
`private string ` [`_upperBound`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder_1add1abf9a00e7bb81efb866424f4f34dc) | A private variable that is used to store the value of the upperBound parameter.
`private int? ` [`_before`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder_1aab4304cf3e09c19e898fe9224a0d723a) | A nullable integer specifying the previous timestamp.
`private int? ` [`_after`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder_1ae1483718c3d317e0b6046ada434c53ae) | A nullable integer specifying the next timestamp.
`private int? ` [`_page`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder_1a4dea13c8190a694fe00b24309b1814f8) | A nullable integer specifying the page.
`private int? ` [`_limit`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder_1a353a19a0da576dc8f69a61548a710395) | A nullable integer specifying the limit of returned values.
`private ` [`SortStrategy`](AtomicAssetsApiClient.md)`? ` [`_sortStrategy`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder_1a122ea78edfd15b44a8a547a7046b8651) | A nullable enum specifying the sortStrategy.
`private string ` [`_sort`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder_1a3ac373edf19e058d7fae7f4c4ba485f4) | A private variable that is used to store the value of the sort parameter.

## Members

##### `public ` [`CollectionsUriParameterBuilder`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder)` ` [`WithAuthor`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder_1ae456148aed84a464aab20ee43665750a)`(string author)` 

`WithAuthor` sets the `author` parameter

#### Parameters
* `author` The author parameter is used to filter the results. The owner parameter is a string that is matched against the account name.

#### Returns
The CollectionsUriParameterBuilder object.

##### `public ` [`CollectionsUriParameterBuilder`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder)` ` [`WithMatch`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder_1adefbe91edff96db187a1e3b23d7c7766)`(string match)` 

`WithMatch` sets the `match` parameter

#### Parameters
* `match` The match parameter is used to filter the results. The match parameter is a string that is matched against the account name.

#### Returns
The CollectionsUriParameterBuilder object.

##### `public ` [`CollectionsUriParameterBuilder`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder)` ` [`WithCollectionBlacklist`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder_1a0156166418fae08028a828dda03ea92a)`(string[] collectionBlacklist)` 

`WithCollectionBlacklist` is a function that takes an array of strings and returns an `AssetsUriParameterBuilder` object

#### Parameters
* `collectionBlacklist` A list of collections to exclude from the results.

#### Returns
The CollectionsUriParameterBuilder object.

##### `public ` [`CollectionsUriParameterBuilder`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder)` ` [`WithCollectionWhitelist`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder_1acd97fc96a67333c4b69eaf1c80063958)`(string[] collectionWhitelist)` 

`WithCollectionWhitelist` is a function that takes an array of strings and returns an `CollectionsUriParameterBuilder` object

#### Parameters
* `collectionWhitelist` A list of collections to include in the response.

#### Returns
The CollectionsUriParameterBuilder object.

##### `public ` [`CollectionsUriParameterBuilder`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder)` ` [`WithAuthorisedAccount`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder_1a71d95cd4ccb4d3e148d24043fb936175)`(string authorisedAccount)` 

`WithAuthorisedAccount` sets the `authorisedAccount` parameter

#### Parameters
* `authorisedAccount` The authorisedAccount parameter is used to filter the results. The authorisedAccount parameter is a string that is matched against the account name.

#### Returns
The CollectionsUriParameterBuilder object.

##### `public ` [`CollectionsUriParameterBuilder`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder)` ` [`WithIds`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder_1acd5f8394565b62858c8ce28b912388b6)`(string[] ids)` 

This function takes an array of strings and joins them together with a comma.

#### Parameters
* `ids` A comma-separated list of account IDs.

#### Returns
The CollectionsUriParameterBuilder object.

##### `public ` [`CollectionsUriParameterBuilder`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder)` ` [`WithNotifyAccount`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder_1a4d3941504c9b050b93fad1edbefb51da)`(string notifyAccount)` 

`WithNotifyAccount` sets the `notifyAccount` parameter

#### Parameters
* `notifyAccount` The notifyAccount parameter is used to filter the results. The notifyAccount parameter is a string that is matched against the account name.

#### Returns
The CollectionsUriParameterBuilder object.

##### `public ` [`CollectionsUriParameterBuilder`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder)` ` [`WithLowerBound`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder_1a7752249152d69369110d622c549bc340)`(string lowerBound)` 

`WithLowerBound` sets the lower bound of the `account_ids` parameter

#### Parameters
* `lowerBound` The lower bound of the accounts to retrieve.

#### Returns
The CollectionsUriParameterBuilder object.

##### `public ` [`CollectionsUriParameterBuilder`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder)` ` [`WithUpperBound`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder_1aafc65336a98f5e84867165e447f2f639)`(string upperBound)` 

`WithUpperBound` sets the upper bound of the range of accounts to be returned

#### Parameters
* `upperBound` The upper bound of the range to query.

#### Returns
The CollectionsUriParameterBuilder object.

##### `public ` [`CollectionsUriParameterBuilder`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder)` ` [`WithBefore`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder_1a46b58fa9ab3b082e19e69456e8850d8e)`(int before)` 

`WithBefore` sets the `_before` variable to the value of the `before` parameter

#### Parameters
* `before` The previous values of the results to return.

#### Returns
The CollectionsUriParameterBuilder object.

##### `public ` [`CollectionsUriParameterBuilder`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder)` ` [`WithAfter`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder_1a9d8d7aba2d2ae6bdec9e9b23d95a9595)`(int after)` 

`WithAfter` sets the `_after` variable to the value of the `after` parameter

#### Parameters
* `after` The after values of the results to return.

#### Returns
The CollectionsUriParameterBuilder object.

##### `public ` [`CollectionsUriParameterBuilder`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder)` ` [`WithPage`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder_1a1b1d62378b6ea39fee85e5f7b014e235)`(int page)` 

`WithPage` sets the `_page` variable to the value of the `page` parameter

#### Parameters
* `page` The page number of the results to return.

#### Returns
The CollectionsUriParameterBuilder object.

##### `public ` [`CollectionsUriParameterBuilder`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder)` ` [`WithLimit`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder_1aa6ad1937b11c448990ec6d76683026af)`(int limit)` 

`WithLimit` sets the `_limit` variable to the value of the `limit` parameter

#### Parameters
* `limit` The number of results to return.

#### Returns
The CollectionsUriParameterBuilder object.

##### `public ` [`CollectionsUriParameterBuilder`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder)` ` [`WithOrder`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder_1aa3c44ce00b2581fd596c286729f58291)`(` [`SortStrategy`](AtomicAssetsApiClient.md)` sorting)` 

This function sets the sort strategy for the query.

#### Parameters
* `SortStrategy` 

#### Returns
The builder object itself.

##### `public ` [`CollectionsUriParameterBuilder`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder)` ` [`WithSort`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder_1a8ddb47c59bb3989f9c216a1efc5f91e9)`(string sort)` 

`WithSort` is a function that takes a string as an argument and returns a `CollectionsUriParameterBuilder` object.

#### Parameters
* `sort` The sort parameter is used to sort the result set in ascending or descending order.

#### Returns
The builder object itself.

##### `public string ` [`Build`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder_1a933ab72b517a9c3879ef78b27a2483bf)`()` 

It takes all the properties of the class and builds a query string based on the values of those properties.

#### Returns
A string of parameters to be used in a query.

##### `private string ` [`_author`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder_1a65e941a52e3bfe2a9e26ef7c97c7359a) 

A private variable that is used to store the value of the author parameter.

##### `private string ` [`_match`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder_1a5151210a8aa5d34ea523afbb052deb11) 

A private variable that is used to store the value of the match parameter.

##### `private string ` [`_authorisedAccount`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder_1a5a6c4dfbab849af1ded34201e3f5a886) 

A private variable that is used to store the value of the authorisedAccount parameter.

##### `private string ` [`_notifyAccount`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder_1a68443b0373a87f7b7698727c5fedd56f) 

A private variable that is used to store the value of the notifyAccount parameter.

##### `private string ` [`_collectionBlacklist`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder_1a11b225f8984dd9ab3ab5fcec261245c4) 

A private variable that is used to store the value of the collectionBlacklist parameter.

##### `private string ` [`_collectionWhitelist`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder_1a525c994ce1a584f4d763ac9d5c1b3cb5) 

A private variable that is used to store the value of the collectionWhitelist parameter.

##### `private string ` [`_ids`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder_1a2a9be788653dd13950b2f00bfce1970b) 

A private variable that is used to store the value of the Ids parameter.

##### `private string ` [`_lowerBound`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder_1a47926893a523918c50a931018c47480d) 

A private variable that is used to store the value of the lowerBound parameter.

##### `private string ` [`_upperBound`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder_1add1abf9a00e7bb81efb866424f4f34dc) 

A private variable that is used to store the value of the upperBound parameter.

##### `private int? ` [`_before`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder_1aab4304cf3e09c19e898fe9224a0d723a) 

A nullable integer specifying the previous timestamp.

##### `private int? ` [`_after`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder_1ae1483718c3d317e0b6046ada434c53ae) 

A nullable integer specifying the next timestamp.

##### `private int? ` [`_page`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder_1a4dea13c8190a694fe00b24309b1814f8) 

A nullable integer specifying the page.

##### `private int? ` [`_limit`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder_1a353a19a0da576dc8f69a61548a710395) 

A nullable integer specifying the limit of returned values.

##### `private ` [`SortStrategy`](AtomicAssetsApiClient.md)`? ` [`_sortStrategy`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder_1a122ea78edfd15b44a8a547a7046b8651) 

A nullable enum specifying the sortStrategy.

##### `private string ` [`_sort`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_uri_parameter_builder_1a3ac373edf19e058d7fae7f4c4ba485f4) 

A private variable that is used to store the value of the sort parameter.

