## class `AtomicMarketApiClient::Auctions::AuctionsUriParameterBuilder` 

```
class AtomicMarketApiClient::Auctions::AuctionsUriParameterBuilder
  : public IUriParameterBuilder
```

### Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public AuctionsUriParameterBuilder `[`WithState`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a91161e076e2ee3ef00ffa83b485da347)`(params State[] states)` | `WithState` takes a list of `State`s and converts them to a comma separated string of integers
`public AuctionsUriParameterBuilder `[`WithMaxAssets`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a4368f2779fe3d38781a7a07d81c5e32b)`(int maxAssets)` | `WithMaxAssets` sets the `_maxAssets` variable
`public AuctionsUriParameterBuilder `[`WithMinAssets`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1af0d6bc6df7ddb31d214982ac1fa206b9)`(int minAssets)` | `WithMinAssets` sets the `_minAssets` variable
`public AuctionsUriParameterBuilder `[`WithShowSellerContracts`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1af06c246a642fd64a4f6f7f761d75d839)`(bool showSellerContracts)` | `WithShowSellerContracts` sets the `_showSellerContracts` field to the value of the `showSellerContracts` parameter
`public AuctionsUriParameterBuilder `[`WithContractWhitelist`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a73a93893820f8710704f289afcc01331)`(bool contractWhitelist)` | `WithContractWhitelist` sets the `_contractWhitelist` field to the value of the `contractWhitelist` parameter
`public AuctionsUriParameterBuilder `[`WithSellerBlacklist`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1ac59d0efed800b19ee06b13cb9bc1c866)`(bool sellerBlacklist)` | `WithSellerBlacklist` sets the `_sellerBlacklist` field to the value of the `sellerBlacklist` parameter
`public AuctionsUriParameterBuilder `[`WithAssetId`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1aaeb9287f2b32977885e37649a3843851)`(int assetId)` | `WithAssetId` sets the `_assetId` variable to the value of the `asset_id` parameter
`public AuctionsUriParameterBuilder `[`WithMarketplace`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a7036592db9165d4313411ba13364ac13)`(string marketplace)` | `WithMarketplace` sets the `marketplace` parameter
`public AuctionsUriParameterBuilder `[`WithMakerMarketplace`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a98ab1fa88d14b97e8ba5f9e2fc47a1b7)`(string makerMarketplace)` | `WithMakerMarketplace` sets the `makerMarketplace` parameter
`public AuctionsUriParameterBuilder `[`WithTakerMarketplace`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a26885cefc4fa36935f17c46e68feefa1)`(string takerMarketplace)` | `WithTakerMarketplace` sets the `takerMarketplace` parameter
`public AuctionsUriParameterBuilder `[`WithSymbol`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1ae1ce66e0894c18252eddec3ae3f479f6)`(string symbol)` | `WithSymbol` sets the `symbol` parameter
`public AuctionsUriParameterBuilder `[`WithSeller`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a9da27faa076cc1345440206d173f23e2)`(string seller)` | `WithSeller` sets the `seller` parameter
`public AuctionsUriParameterBuilder `[`WithBuyer`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a1abf106296a6cf17584bc5c7305eec83)`(string buyer)` | `WithBuyer` sets the `buyer` parameter
`public AuctionsUriParameterBuilder `[`WithMinPrice`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1ac2fa887a41ed2647ab1b317cebbd1a8c)`(int minPrice)` | `WithMinPrice` sets the `_minPrice` variable to the value of the `minPrice` parameter
`public AuctionsUriParameterBuilder `[`WithMaxPrice`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a2f40d040467cc29f2e7c42d66e70f748)`(int maxPrice)` | `WithMaxPrice` sets the `_maxPrice` variable to the value of the `maxPrice` parameter
`public AuctionsUriParameterBuilder `[`WithMinTemplateMint`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1aef21c23d0ec4e13e655bf032ce371a7a)`(int minTemplateMint)` | `WithMinTemplateMint` sets the `_minTemplateMint` variable to the value of the `minTemplateMint` parameter
`public AuctionsUriParameterBuilder `[`WithMaxTemplateMint`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1aee5e1f62892cc6dbd5dbb8d6f7c5132d)`(int maxTemplateMint)` | `WithMaxTemplateMint` sets the `_maxTemplateMint` variable to the value of the `maxTemplateMint` parameter
`public AuctionsUriParameterBuilder `[`WithOwner`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1af42d78c47a782479286a67e56cb3575b)`(string owner)` | `WithOwner` sets the `owner` parameter
`public AuctionsUriParameterBuilder `[`WithBurned`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a4ed0a5a95f1ab5154207e2e69ef61664)`(bool burned)` | `WithBurned` sets the `_burned` field to the value of the `burned` parameter
`public AuctionsUriParameterBuilder `[`WithCollectionName`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1afed6c221e1c0732ab1d736f9e7728d00)`(string collectionName)` | `WithCollectionName` is a function that takes a string as a parameter and returns an `AuctionsUriParameterBuilder` object
`public AuctionsUriParameterBuilder `[`WithSchemaName`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a1dcb95228dd3bf3c4ff6d10d437e6745)`(string schemaName)` | This function sets the schema name for the query
`public AuctionsUriParameterBuilder `[`WithTemplateId`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1aebf636f319b0979d68ab35b3fe44b629)`(string templateId)` | It sets the value of the templateId variable.
`public AuctionsUriParameterBuilder `[`WithIsTransferable`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a47a55b931aef8bedda2d5e5d4ba21f00)`(bool isTransferable)` | `WithIsTransferable` sets the `_isTransferable` field to the value of the `isTransferable` parameter
`public AuctionsUriParameterBuilder `[`WithIsBurnable`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a476dd6b17e7d7b61047f5e7f58f3eedc)`(bool isBurnable)` | `WithIsBurnable` sets the `_isBurnable` field to the value of the `isBurnable` parameter
`public AuctionsUriParameterBuilder `[`WithMatch`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1aadf20273f71d5a1797e52ec602493b8f)`(string match)` | `WithMatch` sets the `match` parameter
`public AuctionsUriParameterBuilder `[`WithCollectionBlacklist`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a9e6142c9ae57fe54d848cd09059296e9)`(string[] collectionBlacklist)` | `WithCollectionBlacklist` is a function that takes an array of strings and returns an `AuctionsUriParameterBuilder` object
`public AuctionsUriParameterBuilder `[`WithCollectionWhitelist`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a84c07a027bb19d4252cd83e74e19dc1d)`(string[] collectionWhitelist)` | `WithCollectionWhitelist` is a function that takes an array of strings and returns an `AuctionsUriParameterBuilder` object
`public AuctionsUriParameterBuilder `[`WithIds`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a896d6b1ef9a5640dc0553238c47cf113)`(string[] ids)` | This function takes an array of strings and joins them together with a comma
`public AuctionsUriParameterBuilder `[`WithLowerBound`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a2537cfa64369223b20d626a06d730254)`(string lowerBound)` | `WithLowerBound` sets the lower bound of the `account_ids` parameter
`public AuctionsUriParameterBuilder `[`WithUpperBound`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1aebee308b54abe33bf20e77ea712fa47c)`(string upperBound)` | `WithUpperBound` sets the upper bound of the range of accounts to be returned
`public AuctionsUriParameterBuilder `[`WithBefore`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a41eb50583e6c20b12b314dd1465cfc8a)`(int before)` | `WithBefore` sets the `_before` variable to the value of the `before` parameter
`public AuctionsUriParameterBuilder `[`WithAfter`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a8cacff7cab1864b1ce8ae9e61e657ed5)`(int after)` | `WithAfter` sets the `_after` variable to the value of the `after` parameter
`public AuctionsUriParameterBuilder `[`WithPage`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a822e83817b5f8fc6b692ce4584da3a00)`(int page)` | `WithPage` sets the `_page` variable to the value of the `page` parameter
`public AuctionsUriParameterBuilder `[`WithLimit`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a5c895d53e96fff01bec67a0d0f01776f)`(int limit)` | `WithLimit` sets the `_limit` variable to the value of the `limit` parameter
`public AuctionsUriParameterBuilder `[`WithOrder`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1aa2152b5b399407ee93cd8105a188b4bc)`(SortStrategy sorting)` | This function sets the sort strategy for the query
`public AuctionsUriParameterBuilder `[`WithSort`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1abbd1c36bc897a6a489ca7caab6a45534)`(string sort)` | It sets the sort parameter to the value passed in.
`public string `[`Build`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a933ab72b517a9c3879ef78b27a2483bf)`()` | It builds a query string based on the parameters that have been set.
`private string `[`_state`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a9577beb4165c1157d2e7f8f0ff065dde) | 
`private int? `[`_maxAssets`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1ae7334a7aa0ba955ac129865639f42b11) | 
`private int? `[`_minAssets`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a2787cd3c00b52a44e78964a580457204) | 
`private bool? `[`_showSellerContracts`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a162ce2b45598492d8053511dc8f5aaf0) | 
`private bool? `[`_contractWhitelist`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a3ee1d446d0a7dc9c0a1c68409eace1b0) | 
`private bool? `[`_sellerBlacklist`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1aeee97135fe3bd4392111f70290af4e0f) | 
`private int? `[`_assetId`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a47b08a4420914a94240cbab6145522a5) | 
`private string `[`_marketplace`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a9a3415610f1a82df64700fb430f6a369) | 
`private string `[`_makerMarketplace`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1ae9ff2ea7ebb9f92f243fcf032613b846) | 
`private string `[`_takerMarketplace`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a1cf7d3f1334cd998d136622cb2333fd1) | 
`private string `[`_symbol`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a26c189f7d4c40f40f09ace24c4ccb945) | 
`private string `[`_seller`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a519a8fc19333a31cc8096bf4836f6101) | 
`private string `[`_buyer`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a5f3e23f4ac11074e75a05a39c775f65c) | 
`private int? `[`_minPrice`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a966cc104ab35aeadc15268d2d9362555) | 
`private int? `[`_maxPrice`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a9e95e6e4dfcd570c9838dbac9b7fab7b) | 
`private int? `[`_minTemplateMint`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a480d12afcb85503c094e6c8001b5b46a) | 
`private int? `[`_maxTemplateMint`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a6582a101a3e6766ec8fe47d29d5015b8) | 
`private string `[`_owner`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1ac091a560bcb5025581c60ad2b3e1f3bb) | 
`private bool? `[`_burned`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a88325c0b6dc8cb4a570b2faaca18efa7) | 
`private string `[`_collectionName`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a10ec2fa990c6478bc519b1e57e1ab2aa) | 
`private string `[`_schemaName`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a2f9a887fd4dfcf60bfe4240a27085724) | 
`private string `[`_templateId`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a06f918051fc7b04615854510caa85934) | 
`private bool? `[`_isTransferable`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a44e26246620bd9d4efa97c195a356672) | 
`private bool? `[`_isBurnable`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a6020acf0c5cb6f447cfe5ba95579e74d) | 
`private string `[`_match`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a5151210a8aa5d34ea523afbb052deb11) | 
`private string `[`_collectionBlacklist`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a11b225f8984dd9ab3ab5fcec261245c4) | 
`private string `[`_collectionWhitelist`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a525c994ce1a584f4d763ac9d5c1b3cb5) | 
`private string `[`_ids`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a2a9be788653dd13950b2f00bfce1970b) | 
`private string `[`_lowerBound`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a47926893a523918c50a931018c47480d) | 
`private string `[`_upperBound`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1add1abf9a00e7bb81efb866424f4f34dc) | 
`private int? `[`_before`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1aab4304cf3e09c19e898fe9224a0d723a) | 
`private int? `[`_after`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1ae1483718c3d317e0b6046ada434c53ae) | 
`private int? `[`_page`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a4dea13c8190a694fe00b24309b1814f8) | 
`private int? `[`_limit`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a353a19a0da576dc8f69a61548a710395) | 
`private SortStrategy? `[`_sortStrategy`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a122ea78edfd15b44a8a547a7046b8651) | 
`private string `[`_sort`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a3ac373edf19e058d7fae7f4c4ba485f4) | 

### Members

#### `public AuctionsUriParameterBuilder `[`WithState`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a91161e076e2ee3ef00ffa83b485da347)`(params State[] states)` 

`WithState` takes a list of `State`s and converts them to a comma separated string of integers

#### Parameters
* `state` Filters by auction state.

#### Returns
The AuctionsUriParameterBuilder object.

#### `public AuctionsUriParameterBuilder `[`WithMaxAssets`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a4368f2779fe3d38781a7a07d81c5e32b)`(int maxAssets)` 

`WithMaxAssets` sets the `_maxAssets` variable

#### Parameters
* `maxAssets` Max assets per listing returns.

#### Returns
The AuctionsUriParameterBuilder object.

#### `public AuctionsUriParameterBuilder `[`WithMinAssets`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1af0d6bc6df7ddb31d214982ac1fa206b9)`(int minAssets)` 

`WithMinAssets` sets the `_minAssets` variable

#### Parameters
* `minAssets` Min assets per listing returns.

#### Returns
The AuctionsUriParameterBuilder object.

#### `public AuctionsUriParameterBuilder `[`WithShowSellerContracts`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1af06c246a642fd64a4f6f7f761d75d839)`(bool showSellerContracts)` 

`WithShowSellerContracts` sets the `_showSellerContracts` field to the value of the `showSellerContracts` parameter

#### Parameters
* `showSellerContracts` If false,no seller contracts are shown except if they are in contract whitelist.

#### Returns
The AuctionsUriParameterBuilder object.

#### `public AuctionsUriParameterBuilder `[`WithContractWhitelist`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a73a93893820f8710704f289afcc01331)`(bool contractWhitelist)` 

`WithContractWhitelist` sets the `_contractWhitelist` field to the value of the `contractWhitelist` parameter

#### Parameters
* `contractWhitelist` Shows accounts even if they are contracts.

#### Returns
The AuctionsUriParameterBuilder object.

#### `public AuctionsUriParameterBuilder `[`WithSellerBlacklist`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1ac59d0efed800b19ee06b13cb9bc1c866)`(bool sellerBlacklist)` 

`WithSellerBlacklist` sets the `_sellerBlacklist` field to the value of the `sellerBlacklist` parameter

#### Parameters
* `sellerBlacklist` Doesnot show listing from sellers.

#### Returns
The AuctionsUriParameterBuilder object.

#### `public AuctionsUriParameterBuilder `[`WithAssetId`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1aaeb9287f2b32977885e37649a3843851)`(int assetId)` 

`WithAssetId` sets the `_assetId` variable to the value of the `asset_id` parameter

#### Parameters
* `assetId` Shows the asset id in the offer.

#### Returns
The AuctionsUriParameterBuilder object.

#### `public AuctionsUriParameterBuilder `[`WithMarketplace`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a7036592db9165d4313411ba13364ac13)`(string marketplace)` 

`WithMarketplace` sets the `marketplace` parameter

#### Parameters
* `marketplace` It filters by all sales where a certain marketplace is either taker or maker marketplace.

#### Returns
The AuctionsUriParameterBuilder object.

#### `public AuctionsUriParameterBuilder `[`WithMakerMarketplace`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a98ab1fa88d14b97e8ba5f9e2fc47a1b7)`(string makerMarketplace)` 

`WithMakerMarketplace` sets the `makerMarketplace` parameter

#### Parameters
* `makerMarketplace` separate multiple with ",".

#### Returns
The AuctionsUriParameterBuilder object.

#### `public AuctionsUriParameterBuilder `[`WithTakerMarketplace`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a26885cefc4fa36935f17c46e68feefa1)`(string takerMarketplace)` 

`WithTakerMarketplace` sets the `takerMarketplace` parameter

#### Parameters
* `takerMarketplace` separate multiple with ",".

#### Returns
The AuctionsUriParameterBuilder object.

#### `public AuctionsUriParameterBuilder `[`WithSymbol`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1ae1ce66e0894c18252eddec3ae3f479f6)`(string symbol)` 

`WithSymbol` sets the `symbol` parameter

#### Parameters
* `symbol` Filters by symbol.

#### Returns
The AuctionsUriParameterBuilder object.

#### `public AuctionsUriParameterBuilder `[`WithSeller`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a9da27faa076cc1345440206d173f23e2)`(string seller)` 

`WithSeller` sets the `seller` parameter

#### Parameters
* `seller` Filter by seller.

#### Returns
The AuctionsUriParameterBuilder object.

#### `public AuctionsUriParameterBuilder `[`WithBuyer`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a1abf106296a6cf17584bc5c7305eec83)`(string buyer)` 

`WithBuyer` sets the `buyer` parameter

#### Parameters
* `buyer` Filter by buyer.

#### Returns
The AuctionsUriParameterBuilder object.

#### `public AuctionsUriParameterBuilder `[`WithMinPrice`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1ac2fa887a41ed2647ab1b317cebbd1a8c)`(int minPrice)` 

`WithMinPrice` sets the `_minPrice` variable to the value of the `minPrice` parameter

#### Parameters
* `minPrice` The lower price limit.

#### Returns
The AuctionsUriParameterBuilder object.

#### `public AuctionsUriParameterBuilder `[`WithMaxPrice`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a2f40d040467cc29f2e7c42d66e70f748)`(int maxPrice)` 

`WithMaxPrice` sets the `_maxPrice` variable to the value of the `maxPrice` parameter

#### Parameters
* `maxPrice` The upper price limit.

#### Returns
The AuctionsUriParameterBuilder object.

#### `public AuctionsUriParameterBuilder `[`WithMinTemplateMint`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1aef21c23d0ec4e13e655bf032ce371a7a)`(int minTemplateMint)` 

`WithMinTemplateMint` sets the `_minTemplateMint` variable to the value of the `minTemplateMint` parameter

#### Parameters
* `minTemplateMint` Min template mint.

#### Returns
The AuctionsUriParameterBuilder object.

#### `public AuctionsUriParameterBuilder `[`WithMaxTemplateMint`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1aee5e1f62892cc6dbd5dbb8d6f7c5132d)`(int maxTemplateMint)` 

`WithMaxTemplateMint` sets the `_maxTemplateMint` variable to the value of the `maxTemplateMint` parameter

#### Parameters
* `maxTemplateMint` Max template mint.

#### Returns
The AuctionsUriParameterBuilder object.

#### `public AuctionsUriParameterBuilder `[`WithOwner`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1af42d78c47a782479286a67e56cb3575b)`(string owner)` 

`WithOwner` sets the `owner` parameter

#### Parameters
* `owner` The owner parameter is used to filter the results. The owner parameter is a string that is matched against the account name.

#### Returns
The AuctionsUriParameterBuilder object.

#### `public AuctionsUriParameterBuilder `[`WithBurned`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a4ed0a5a95f1ab5154207e2e69ef61664)`(bool burned)` 

`WithBurned` sets the `_burned` field to the value of the `burned` parameter

#### Parameters
* `burned` It filters for burned assets.

#### Returns
The AuctionsUriParameterBuilder object.

#### `public AuctionsUriParameterBuilder `[`WithCollectionName`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1afed6c221e1c0732ab1d736f9e7728d00)`(string collectionName)` 

`WithCollectionName` is a function that takes a string as a parameter and returns an `AuctionsUriParameterBuilder` object

#### Parameters
* `collectionName` The name of the collection you want to query.

#### Returns
The AuctionsUriParameterBuilder object.

#### `public AuctionsUriParameterBuilder `[`WithSchemaName`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a1dcb95228dd3bf3c4ff6d10d437e6745)`(string schemaName)` 

This function sets the schema name for the query

#### Parameters
* `schemaName` The name of the schema to use.

#### Returns
The AuctionsUriParameterBuilder object.

#### `public AuctionsUriParameterBuilder `[`WithTemplateId`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1aebf636f319b0979d68ab35b3fe44b629)`(string templateId)` 

It sets the value of the templateId variable.

#### Parameters
* `templateId` Results based on only transfers which cointain assets of template.

#### Returns
The AuctionsUriParameterBuilder object.

#### `public AuctionsUriParameterBuilder `[`WithIsTransferable`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a47a55b931aef8bedda2d5e5d4ba21f00)`(bool isTransferable)` 

`WithIsTransferable` sets the `_isTransferable` field to the value of the `isTransferable` parameter

#### Parameters
* `isTransferable` The isTransferable parameter filters for transferable assets.

#### Returns
The AuctionsUriParameterBuilder object.

#### `public AuctionsUriParameterBuilder `[`WithIsBurnable`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a476dd6b17e7d7b61047f5e7f58f3eedc)`(bool isBurnable)` 

`WithIsBurnable` sets the `_isBurnable` field to the value of the `isBurnable` parameter

#### Parameters
* `isBurnable` Filters for burnable assets.

#### Returns
The AuctionsUriParameterBuilder object.

#### `public AuctionsUriParameterBuilder `[`WithMatch`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1aadf20273f71d5a1797e52ec602493b8f)`(string match)` 

`WithMatch` sets the `match` parameter

#### Parameters
* `match` Search for input in asset name on template data.

#### Returns
The AuctionsUriParameterBuilder object.

#### `public AuctionsUriParameterBuilder `[`WithCollectionBlacklist`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a9e6142c9ae57fe54d848cd09059296e9)`(string[] collectionBlacklist)` 

`WithCollectionBlacklist` is a function that takes an array of strings and returns an `AuctionsUriParameterBuilder` object

#### Parameters
* `collectionBlacklist` A list of collections to exclude from the results.

#### Returns
The AuctionsUriParameterBuilder object.

#### `public AuctionsUriParameterBuilder `[`WithCollectionWhitelist`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a84c07a027bb19d4252cd83e74e19dc1d)`(string[] collectionWhitelist)` 

`WithCollectionWhitelist` is a function that takes an array of strings and returns an `AuctionsUriParameterBuilder` object

#### Parameters
* `collectionWhitelist` A list of collections to include in the response.

#### Returns
The AuctionsUriParameterBuilder object.

#### `public AuctionsUriParameterBuilder `[`WithIds`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a896d6b1ef9a5640dc0553238c47cf113)`(string[] ids)` 

This function takes an array of strings and joins them together with a comma

#### Parameters
* `ids` A comma-separated list of account IDs.

#### Returns
The AuctionsUriParameterBuilder object.

#### `public AuctionsUriParameterBuilder `[`WithLowerBound`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a2537cfa64369223b20d626a06d730254)`(string lowerBound)` 

`WithLowerBound` sets the lower bound of the `account_ids` parameter

#### Parameters
* `lowerBound` The lower bound of the primary key

#### Returns
The AuctionsUriParameterBuilder object.

#### `public AuctionsUriParameterBuilder `[`WithUpperBound`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1aebee308b54abe33bf20e77ea712fa47c)`(string upperBound)` 

`WithUpperBound` sets the upper bound of the range of accounts to be returned

#### Parameters
* `upperBound` The upper bound of the primary key.

#### Returns
The AuctionsUriParameterBuilder object.

#### `public AuctionsUriParameterBuilder `[`WithBefore`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a41eb50583e6c20b12b314dd1465cfc8a)`(int before)` 

`WithBefore` sets the `_before` variable to the value of the `before` parameter

#### Parameters
* `before` The previous values of the results to return.

#### Returns
The AuctionsUriParameterBuilder object.

#### `public AuctionsUriParameterBuilder `[`WithAfter`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a8cacff7cab1864b1ce8ae9e61e657ed5)`(int after)` 

`WithAfter` sets the `_after` variable to the value of the `after` parameter

#### Parameters
* `after` The later values of the results to return.

#### Returns
The AuctionsUriParameterBuilder object.

#### `public AuctionsUriParameterBuilder `[`WithPage`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a822e83817b5f8fc6b692ce4584da3a00)`(int page)` 

`WithPage` sets the `_page` variable to the value of the `page` parameter

#### Parameters
* `page` The page number of the results to return.

#### Returns
The AuctionsUriParameterBuilder object.

#### `public AuctionsUriParameterBuilder `[`WithLimit`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a5c895d53e96fff01bec67a0d0f01776f)`(int limit)` 

`WithLimit` sets the `_limit` variable to the value of the `limit` parameter

#### Parameters
* `limit` The number of results to return.

#### Returns
The AuctionsUriParameterBuilder object.

#### `public AuctionsUriParameterBuilder `[`WithOrder`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1aa2152b5b399407ee93cd8105a188b4bc)`(SortStrategy sorting)` 

This function sets the sort strategy for the query

#### Parameters
* `SortStrategy` 

#### Returns
The builder object itself.

#### `public AuctionsUriParameterBuilder `[`WithSort`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1abbd1c36bc897a6a489ca7caab6a45534)`(string sort)` 

It sets the sort parameter to the value passed in.

#### Parameters
* `sort` The sort order of the results.

<br/>
 <return> The AuctionsUriParameterBuilder.object <br/>
 </return> <br/>

#### `public string `[`Build`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a933ab72b517a9c3879ef78b27a2483bf)`()` 

It builds a query string based on the parameters that have been set.

#### Returns
A string that contains the parameters for the query.

#### `private string `[`_state`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a9577beb4165c1157d2e7f8f0ff065dde) 

#### `private int? `[`_maxAssets`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1ae7334a7aa0ba955ac129865639f42b11) 

#### `private int? `[`_minAssets`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a2787cd3c00b52a44e78964a580457204) 

#### `private bool? `[`_showSellerContracts`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a162ce2b45598492d8053511dc8f5aaf0) 

#### `private bool? `[`_contractWhitelist`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a3ee1d446d0a7dc9c0a1c68409eace1b0) 

#### `private bool? `[`_sellerBlacklist`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1aeee97135fe3bd4392111f70290af4e0f) 

#### `private int? `[`_assetId`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a47b08a4420914a94240cbab6145522a5) 

#### `private string `[`_marketplace`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a9a3415610f1a82df64700fb430f6a369) 

#### `private string `[`_makerMarketplace`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1ae9ff2ea7ebb9f92f243fcf032613b846) 

#### `private string `[`_takerMarketplace`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a1cf7d3f1334cd998d136622cb2333fd1) 

#### `private string `[`_symbol`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a26c189f7d4c40f40f09ace24c4ccb945) 

#### `private string `[`_seller`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a519a8fc19333a31cc8096bf4836f6101) 

#### `private string `[`_buyer`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a5f3e23f4ac11074e75a05a39c775f65c) 

#### `private int? `[`_minPrice`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a966cc104ab35aeadc15268d2d9362555) 

#### `private int? `[`_maxPrice`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a9e95e6e4dfcd570c9838dbac9b7fab7b) 

#### `private int? `[`_minTemplateMint`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a480d12afcb85503c094e6c8001b5b46a) 

#### `private int? `[`_maxTemplateMint`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a6582a101a3e6766ec8fe47d29d5015b8) 

#### `private string `[`_owner`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1ac091a560bcb5025581c60ad2b3e1f3bb) 

#### `private bool? `[`_burned`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a88325c0b6dc8cb4a570b2faaca18efa7) 

#### `private string `[`_collectionName`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a10ec2fa990c6478bc519b1e57e1ab2aa) 

#### `private string `[`_schemaName`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a2f9a887fd4dfcf60bfe4240a27085724) 

#### `private string `[`_templateId`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a06f918051fc7b04615854510caa85934) 

#### `private bool? `[`_isTransferable`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a44e26246620bd9d4efa97c195a356672) 

#### `private bool? `[`_isBurnable`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a6020acf0c5cb6f447cfe5ba95579e74d) 

#### `private string `[`_match`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a5151210a8aa5d34ea523afbb052deb11) 

#### `private string `[`_collectionBlacklist`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a11b225f8984dd9ab3ab5fcec261245c4) 

#### `private string `[`_collectionWhitelist`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a525c994ce1a584f4d763ac9d5c1b3cb5) 

#### `private string `[`_ids`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a2a9be788653dd13950b2f00bfce1970b) 

#### `private string `[`_lowerBound`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a47926893a523918c50a931018c47480d) 

#### `private string `[`_upperBound`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1add1abf9a00e7bb81efb866424f4f34dc) 

#### `private int? `[`_before`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1aab4304cf3e09c19e898fe9224a0d723a) 

#### `private int? `[`_after`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1ae1483718c3d317e0b6046ada434c53ae) 

#### `private int? `[`_page`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a4dea13c8190a694fe00b24309b1814f8) 

#### `private int? `[`_limit`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a353a19a0da576dc8f69a61548a710395) 

#### `private SortStrategy? `[`_sortStrategy`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a122ea78edfd15b44a8a547a7046b8651) 

#### `private string `[`_sort`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder_1a3ac373edf19e058d7fae7f4c4ba485f4) 

