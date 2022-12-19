## class `AtomicMarketApiClient::BuyOffers::BuyOffersUriParameterBuilder` 

```
class AtomicMarketApiClient::BuyOffers::BuyOffersUriParameterBuilder
  : public IUriParameterBuilder
```

### Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public inline BuyOffersUriParameterBuilder `[`WithState`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1ad1d57ac008fce06cefe6f737403ded76)`(params State[] states)` | `WithState` takes a list of `State`s and returns a `BuyOffersUriParameterBuilder` with the `_state` property set to a comma separated list of the `int` values of the `State`s.
`public inline BuyOffersUriParameterBuilder `[`WithMaxAssets`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a04337bf2ef03afffa3f6919cd4d159bd)`(int maxAssets)` | `WithMaxAssets` sets the `_maxAssets` variable
`public inline BuyOffersUriParameterBuilder `[`WithMinAssets`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a36d5d80b95e3ec47dbe2d9f0901f7fae)`(int minAssets)` | `WithMinAssets` sets the `_minAssets` variable to the value of the `minAssets` parameter
`public inline BuyOffersUriParameterBuilder `[`WithShowSellerContracts`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a7bc149df66d6d266fb7da1fc8d45f4ca)`(bool showSellerContracts)` | It sets the value of the private variable _showSellerContracts to the value of the parameter showSellerContracts.
`public inline BuyOffersUriParameterBuilder `[`WithContractWhitelist`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1ac6d4d16440a837a08583aac126f8c900)`(bool contractWhitelist)` | `WithContractWhitelist` is a function that takes a boolean value and returns a `BuyOffersUriParameterBuilder` object
`public inline BuyOffersUriParameterBuilder `[`WithSellerBlacklist`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a8dd00acee021dba4d6435d6ff069d2ec)`(bool sellerBlacklist)` | `WithSellerBlacklist` sets the `_sellerBlacklist` field to the value of the `sellerBlacklist` parameter
`public inline BuyOffersUriParameterBuilder `[`WithAssetId`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a06aa361597137d4866df61aa4be3eaad)`(int assetId)` | `WithAssetId` sets the `_assetId` variable to the value of the `asset_id` parameter
`public inline BuyOffersUriParameterBuilder `[`WithMarketplace`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a0acfc5fa5151f97b7a759bf0f6a65e41)`(string marketplace)` | `WithMarketplace` sets the `marketplace` parameter
`public inline BuyOffersUriParameterBuilder `[`WithMakerMarketplace`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a96020e008cd1cee457aabaf5280794a8)`(string makerMarketplace)` | `WithMakerMarketplace` sets the `makerMarketplace` parameter
`public inline BuyOffersUriParameterBuilder `[`WithTakerMarketplace`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a577a1385e2a2b6cb06229b562a19cfeb)`(string takerMarketplace)` | `WithTakerMarketplace` sets the `takerMarketplace` parameter
`public inline BuyOffersUriParameterBuilder `[`WithSymbol`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1aa59e8f84dfa764e44d8fbb5ba236f8aa)`(string symbol)` | `WithSymbol` is a function that takes a string as a parameter and returns a `BuyOffersUriParameterBuilder` object.
`public inline BuyOffersUriParameterBuilder `[`WithSeller`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a67580fa4e652092ec5207b10c4147715)`(string seller)` | `WithSeller` sets the `seller` parameter
`public inline BuyOffersUriParameterBuilder `[`WithBuyer`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1adca4dcf4e63354d86c019a4d652422db)`(string buyer)` | `WithBuyer` sets the `buyer` parameter
`public inline BuyOffersUriParameterBuilder `[`WithMinPrice`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1ab8d0a121574368409cda1249e0297cc4)`(int minPrice)` | `WithMinPrice` sets the `_minPrice` variable to the value of the `minPrice` parameter
`public inline BuyOffersUriParameterBuilder `[`WithMaxPrice`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a4c1866db567c2caa324b9576c782ee0c)`(int maxPrice)` | `WithMaxPrice` sets the `_maxPrice` variable to the value of the `maxPrice` parameter
`public inline BuyOffersUriParameterBuilder `[`WithMinTemplateMint`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1aa27c9a4b609dddf1fdc149a0a8d8926a)`(int minTemplateMint)` | `WithMinTemplateMint` sets the `_minTemplateMint` variable to the value of the `minTemplateMint` parameter
`public inline BuyOffersUriParameterBuilder `[`WithMaxTemplateMint`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a65d226b09278093614b67210908262b4)`(int maxTemplateMint)` | `WithMaxTemplateMint` sets the `_maxTemplateMint` variable to the value of the `maxTemplateMint` parameter
`public inline BuyOffersUriParameterBuilder `[`WithOwner`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a543b2861cf67c93707354ed5f574e4ba)`(string owner)` | `WithOwner` sets the `owner` parameter
`public inline BuyOffersUriParameterBuilder `[`WithBurned`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a55f2bbdb2f55004093a28de4dc1465ce)`(bool burned)` | `WithBurned` sets the `_burned` field to the value of the `burned` parameter
`public inline BuyOffersUriParameterBuilder `[`WithCollectionName`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a88bf9feb5fdf55504be6681f137e9b2e)`(string collectionName)` | `WithCollectionName` is a function that takes a string as a parameter and returns an `BuyOffersUriParameterBuilder` object
`public inline BuyOffersUriParameterBuilder `[`WithSchemaName`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1acfae2469372c85d4d047af0ab102c024)`(string schemaName)` | This function sets the schema name for the query
`public inline BuyOffersUriParameterBuilder `[`WithTemplateId`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1aefefc1b4bc929a0d0d86bb88df7c374a)`(string templateId)` | It sets the value of the templateId variable.
`public inline BuyOffersUriParameterBuilder `[`WithIsTransferable`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a3a6dbdabe529064b880b858dc5c34503)`(bool isTransferable)` | `WithIsTransferable` sets the `_isTransferable` field to the value of the `isTransferable` parameter
`public inline BuyOffersUriParameterBuilder `[`WithIsBurnable`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a4c0e3f9ee3375eab0889f3c7cba5d7d2)`(bool isBurnable)` | `WithIsBurnable` sets the `_isBurnable` field to the value of the `isBurnable` parameter
`public inline BuyOffersUriParameterBuilder `[`WithMatch`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a9f4a1cf45953d187e703042c0af612d6)`(string match)` | `WithMatch` sets the `match` parameter
`public inline BuyOffersUriParameterBuilder `[`WithCollectionBlacklist`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1aa6d0074266a4608e693590d8cb09a379)`(string[] collectionBlacklist)` | `WithCollectionBlacklist` is a function that takes an array of strings and returns an `BuyOffersUriParameterBuilder` object
`public inline BuyOffersUriParameterBuilder `[`WithCollectionWhitelist`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a94a9f8bbf2f3c6fcb338ff302c0716b5)`(string[] collectionWhitelist)` | `WithCollectionWhitelist` is a function that takes an array of strings and returns an `BuyOffersUriParameterBuilder` object
`public inline BuyOffersUriParameterBuilder `[`WithIds`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1aae8d094a1dbd124f37251b8001c8566f)`(string[] ids)` | This function takes an array of strings and joins them together with a comma
`public inline BuyOffersUriParameterBuilder `[`WithLowerBound`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a5731767078d7979c27487fa37805a14e)`(string lowerBound)` | `WithLowerBound` sets the lower bound of the `account_ids` parameter
`public inline BuyOffersUriParameterBuilder `[`WithUpperBound`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a504058d26a60d5c83936a959bd1a7eaa)`(string upperBound)` | `WithUpperBound` sets the upper bound of the range of accounts to be returned
`public inline BuyOffersUriParameterBuilder `[`WithBefore`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a3e1122046db1740d5fd3274213d9eaf4)`(int before)` | `WithBefore` sets the `_before` variable to the value of the `before` parameter
`public inline BuyOffersUriParameterBuilder `[`WithAfter`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a3057e050bf7054593aa959fcdc028b1c)`(int after)` | `WithAfter` sets the `_after` variable to the value of the `after` parameter
`public inline BuyOffersUriParameterBuilder `[`WithPage`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a7db8f1d764e3f81768b7d1820e13b1a3)`(int page)` | `WithPage` sets the `_page` variable to the value of the `page` parameter
`public inline BuyOffersUriParameterBuilder `[`WithLimit`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a6fdc43968793eec37e4ed6b72b0dadff)`(int limit)` | `WithLimit` sets the `_limit` variable to the value of the `limit` parameter
`public inline BuyOffersUriParameterBuilder `[`WithOrder`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a5cba5a767a3d1174cf57cc6adf4917fc)`(SortStrategy sorting)` | This function sets the sort strategy for the query
`public inline BuyOffersUriParameterBuilder `[`WithSort`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a00d65b0190e84f48ae1bbb611da90824)`(string sort)` | `WithSort` is a function that takes a string as a parameter and returns a `BuyOffersUriParameterBuilder` object
`public inline string `[`Build`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a933ab72b517a9c3879ef78b27a2483bf)`()` | It builds a query string based on the parameters that have been set.
`private string `[`_state`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a9577beb4165c1157d2e7f8f0ff065dde) | 
`private int? `[`_maxAssets`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1ae7334a7aa0ba955ac129865639f42b11) | 
`private int? `[`_minAssets`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a2787cd3c00b52a44e78964a580457204) | 
`private bool? `[`_showSellerContracts`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a162ce2b45598492d8053511dc8f5aaf0) | 
`private bool? `[`_contractWhitelist`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a3ee1d446d0a7dc9c0a1c68409eace1b0) | 
`private bool? `[`_sellerBlacklist`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1aeee97135fe3bd4392111f70290af4e0f) | 
`private int? `[`_assetId`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a47b08a4420914a94240cbab6145522a5) | 
`private string `[`_marketplace`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a9a3415610f1a82df64700fb430f6a369) | 
`private string `[`_makerMarketplace`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1ae9ff2ea7ebb9f92f243fcf032613b846) | 
`private string `[`_takerMarketplace`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a1cf7d3f1334cd998d136622cb2333fd1) | 
`private string `[`_symbol`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a26c189f7d4c40f40f09ace24c4ccb945) | 
`private string `[`_seller`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a519a8fc19333a31cc8096bf4836f6101) | 
`private string `[`_buyer`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a5f3e23f4ac11074e75a05a39c775f65c) | 
`private int? `[`_minPrice`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a966cc104ab35aeadc15268d2d9362555) | 
`private int? `[`_maxPrice`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a9e95e6e4dfcd570c9838dbac9b7fab7b) | 
`private int? `[`_minTemplateMint`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a480d12afcb85503c094e6c8001b5b46a) | 
`private int? `[`_maxTemplateMint`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a6582a101a3e6766ec8fe47d29d5015b8) | 
`private string `[`_owner`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1ac091a560bcb5025581c60ad2b3e1f3bb) | 
`private bool? `[`_burned`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a88325c0b6dc8cb4a570b2faaca18efa7) | 
`private string `[`_collectionName`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a10ec2fa990c6478bc519b1e57e1ab2aa) | 
`private string `[`_schemaName`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a2f9a887fd4dfcf60bfe4240a27085724) | 
`private string `[`_templateId`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a06f918051fc7b04615854510caa85934) | 
`private bool? `[`_isTransferable`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a44e26246620bd9d4efa97c195a356672) | 
`private bool? `[`_isBurnable`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a6020acf0c5cb6f447cfe5ba95579e74d) | 
`private string `[`_match`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a5151210a8aa5d34ea523afbb052deb11) | 
`private string `[`_collectionBlacklist`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a11b225f8984dd9ab3ab5fcec261245c4) | 
`private string `[`_collectionWhitelist`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a525c994ce1a584f4d763ac9d5c1b3cb5) | 
`private string `[`_ids`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a2a9be788653dd13950b2f00bfce1970b) | 
`private string `[`_lowerBound`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a47926893a523918c50a931018c47480d) | 
`private string `[`_upperBound`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1add1abf9a00e7bb81efb866424f4f34dc) | 
`private int? `[`_before`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1aab4304cf3e09c19e898fe9224a0d723a) | 
`private int? `[`_after`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1ae1483718c3d317e0b6046ada434c53ae) | 
`private int? `[`_page`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a4dea13c8190a694fe00b24309b1814f8) | 
`private int? `[`_limit`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a353a19a0da576dc8f69a61548a710395) | 
`private SortStrategy? `[`_sortStrategy`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a122ea78edfd15b44a8a547a7046b8651) | 
`private string `[`_sort`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a3ac373edf19e058d7fae7f4c4ba485f4) | 

### Members

#### `public inline BuyOffersUriParameterBuilder `[`WithState`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1ad1d57ac008fce06cefe6f737403ded76)`(params State[] states)` 

`WithState` takes a list of `State`s and returns a `BuyOffersUriParameterBuilder` with the `_state` property set to a comma separated list of the `int` values of the `State`s.

#### Returns
The BuyOffersUriParameterBuilder object.

#### `public inline BuyOffersUriParameterBuilder `[`WithMaxAssets`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a04337bf2ef03afffa3f6919cd4d159bd)`(int maxAssets)` 

`WithMaxAssets` sets the `_maxAssets` variable

#### Parameters
* `maxAssets` Max assets per listing returns.

#### Returns
The BuyOffersUriParameterBuilder object.

#### `public inline BuyOffersUriParameterBuilder `[`WithMinAssets`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a36d5d80b95e3ec47dbe2d9f0901f7fae)`(int minAssets)` 

`WithMinAssets` sets the `_minAssets` variable to the value of the `minAssets` parameter

#### Parameters
* `minAssets` The minimum number of assets the offer must have.

#### Returns
The BuyOffersUriParameterBuilder object.

#### `public inline BuyOffersUriParameterBuilder `[`WithShowSellerContracts`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a7bc149df66d6d266fb7da1fc8d45f4ca)`(bool showSellerContracts)` 

It sets the value of the private variable _showSellerContracts to the value of the parameter showSellerContracts.

#### Parameters
* `showSellerContracts` If true, the response will include the seller's contract details.

#### Returns
The BuyOffersUriParameterBuilder object.

#### `public inline BuyOffersUriParameterBuilder `[`WithContractWhitelist`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1ac6d4d16440a837a08583aac126f8c900)`(bool contractWhitelist)` 

`WithContractWhitelist` is a function that takes a boolean value and returns a `BuyOffersUriParameterBuilder` object

#### Parameters
* `contractWhitelist` If true, only offers from contracts in the whitelist will be returned.

#### Returns
The BuyOffersUriParameterBuilder object.

#### `public inline BuyOffersUriParameterBuilder `[`WithSellerBlacklist`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a8dd00acee021dba4d6435d6ff069d2ec)`(bool sellerBlacklist)` 

`WithSellerBlacklist` sets the `_sellerBlacklist` field to the value of the `sellerBlacklist` parameter

#### Parameters
* `sellerBlacklist` Doesnot show listing from sellers.

#### Returns
The BuyOffersUriParameterBuilder object.

#### `public inline BuyOffersUriParameterBuilder `[`WithAssetId`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a06aa361597137d4866df61aa4be3eaad)`(int assetId)` 

`WithAssetId` sets the `_assetId` variable to the value of the `asset_id` parameter

#### Parameters
* `assetId` Shows the asset id in the offer.

#### Returns
The BuyOffersUriParameterBuilder object.

#### `public inline BuyOffersUriParameterBuilder `[`WithMarketplace`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a0acfc5fa5151f97b7a759bf0f6a65e41)`(string marketplace)` 

`WithMarketplace` sets the `marketplace` parameter

#### Parameters
* `marketplace` It filters by all sales where a certain marketplace is either taker or maker marketplace.

#### Returns
The BuyOffersUriParameterBuilder object.

#### `public inline BuyOffersUriParameterBuilder `[`WithMakerMarketplace`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a96020e008cd1cee457aabaf5280794a8)`(string makerMarketplace)` 

`WithMakerMarketplace` sets the `makerMarketplace` parameter

#### Parameters
* `makerMarketplace` separate multiple with ",".

#### Returns
The BuyOffersUriParameterBuilder object.

#### `public inline BuyOffersUriParameterBuilder `[`WithTakerMarketplace`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a577a1385e2a2b6cb06229b562a19cfeb)`(string takerMarketplace)` 

`WithTakerMarketplace` sets the `takerMarketplace` parameter

#### Parameters
* `takerMarketplace` separate multiple with ",".

#### Returns
The BuyOffersUriParameterBuilder object.

#### `public inline BuyOffersUriParameterBuilder `[`WithSymbol`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1aa59e8f84dfa764e44d8fbb5ba236f8aa)`(string symbol)` 

`WithSymbol` is a function that takes a string as a parameter and returns a `BuyOffersUriParameterBuilder` object.

#### Parameters
* `symbol` The symbol of the asset to get offers for.

#### Returns
The BuyOffersUriParameterBuilder object.

#### `public inline BuyOffersUriParameterBuilder `[`WithSeller`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a67580fa4e652092ec5207b10c4147715)`(string seller)` 

`WithSeller` sets the `seller` parameter

#### Parameters
* `seller` Filter by seller.

#### Returns
The BuyOffersUriParameterBuilder object.

#### `public inline BuyOffersUriParameterBuilder `[`WithBuyer`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1adca4dcf4e63354d86c019a4d652422db)`(string buyer)` 

`WithBuyer` sets the `buyer` parameter

#### Parameters
* `buyer` Filter by buyer.

#### Returns
The BuyOffersUriParameterBuilder object.

#### `public inline BuyOffersUriParameterBuilder `[`WithMinPrice`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1ab8d0a121574368409cda1249e0297cc4)`(int minPrice)` 

`WithMinPrice` sets the `_minPrice` variable to the value of the `minPrice` parameter

#### Parameters
* `minPrice` The lower price limit.

#### Returns
The BuyOffersUriParameterBuilder object.

#### `public inline BuyOffersUriParameterBuilder `[`WithMaxPrice`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a4c1866db567c2caa324b9576c782ee0c)`(int maxPrice)` 

`WithMaxPrice` sets the `_maxPrice` variable to the value of the `maxPrice` parameter

#### Parameters
* `maxPrice` The upper price limit.

#### Returns
The BuyOffersUriParameterBuilder object.

#### `public inline BuyOffersUriParameterBuilder `[`WithMinTemplateMint`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1aa27c9a4b609dddf1fdc149a0a8d8926a)`(int minTemplateMint)` 

`WithMinTemplateMint` sets the `_minTemplateMint` variable to the value of the `minTemplateMint` parameter

#### Parameters
* `minTemplateMint` Min template mint.

#### Returns
The BuyOffersUriParameterBuilder object.

#### `public inline BuyOffersUriParameterBuilder `[`WithMaxTemplateMint`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a65d226b09278093614b67210908262b4)`(int maxTemplateMint)` 

`WithMaxTemplateMint` sets the `_maxTemplateMint` variable to the value of the `maxTemplateMint` parameter

#### Parameters
* `maxTemplateMint` Max template mint.

#### Returns
The BuyOffersUriParameterBuilder object.

#### `public inline BuyOffersUriParameterBuilder `[`WithOwner`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a543b2861cf67c93707354ed5f574e4ba)`(string owner)` 

`WithOwner` sets the `owner` parameter

#### Parameters
* `owner` The owner parameter is used to filter the results. The owner parameter is a string that is matched against the account name.

#### Returns
The BuyOffersUriParameterBuilder object.

#### `public inline BuyOffersUriParameterBuilder `[`WithBurned`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a55f2bbdb2f55004093a28de4dc1465ce)`(bool burned)` 

`WithBurned` sets the `_burned` field to the value of the `burned` parameter

#### Parameters
* `burned` It filters for burned assets.

#### Returns
The BuyOffersUriParameterBuilder object.

#### `public inline BuyOffersUriParameterBuilder `[`WithCollectionName`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a88bf9feb5fdf55504be6681f137e9b2e)`(string collectionName)` 

`WithCollectionName` is a function that takes a string as a parameter and returns an `BuyOffersUriParameterBuilder` object

#### Parameters
* `collectionName` The name of the collection you want to query.

#### Returns
The BuyOffersUriParameterBuilder object.

#### `public inline BuyOffersUriParameterBuilder `[`WithSchemaName`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1acfae2469372c85d4d047af0ab102c024)`(string schemaName)` 

This function sets the schema name for the query

#### Parameters
* `schemaName` The name of the schema to use.

#### Returns
The BuyOffersUriParameterBuilder object.

#### `public inline BuyOffersUriParameterBuilder `[`WithTemplateId`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1aefefc1b4bc929a0d0d86bb88df7c374a)`(string templateId)` 

It sets the value of the templateId variable.

#### Parameters
* `templateId` Results based on only transfers which cointain assets of template.

#### Returns
The BuyOffersUriParameterBuilder object.

#### `public inline BuyOffersUriParameterBuilder `[`WithIsTransferable`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a3a6dbdabe529064b880b858dc5c34503)`(bool isTransferable)` 

`WithIsTransferable` sets the `_isTransferable` field to the value of the `isTransferable` parameter

#### Parameters
* `isTransferable` The isTransferable parameter filters for transferable assets.

#### Returns
The BuyOffersUriParameterBuilder object.

#### `public inline BuyOffersUriParameterBuilder `[`WithIsBurnable`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a4c0e3f9ee3375eab0889f3c7cba5d7d2)`(bool isBurnable)` 

`WithIsBurnable` sets the `_isBurnable` field to the value of the `isBurnable` parameter

#### Parameters
* `isBurnable` Filters for burnable assets.

#### Returns
The BuyOffersUriParameterBuilder object.

#### `public inline BuyOffersUriParameterBuilder `[`WithMatch`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a9f4a1cf45953d187e703042c0af612d6)`(string match)` 

`WithMatch` sets the `match` parameter

#### Parameters
* `match` Search for input in asset name on template data.

#### Returns
The BuyOffersUriParameterBuilder object.

#### `public inline BuyOffersUriParameterBuilder `[`WithCollectionBlacklist`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1aa6d0074266a4608e693590d8cb09a379)`(string[] collectionBlacklist)` 

`WithCollectionBlacklist` is a function that takes an array of strings and returns an `BuyOffersUriParameterBuilder` object

#### Parameters
* `collectionBlacklist` A list of collections to exclude from the results.

#### Returns
The BuyOffersUriParameterBuilder object.

#### `public inline BuyOffersUriParameterBuilder `[`WithCollectionWhitelist`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a94a9f8bbf2f3c6fcb338ff302c0716b5)`(string[] collectionWhitelist)` 

`WithCollectionWhitelist` is a function that takes an array of strings and returns an `BuyOffersUriParameterBuilder` object

#### Parameters
* `collectionWhitelist` A list of collections to include in the response.

#### Returns
The BuyOffersUriParameterBuilder object.

#### `public inline BuyOffersUriParameterBuilder `[`WithIds`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1aae8d094a1dbd124f37251b8001c8566f)`(string[] ids)` 

This function takes an array of strings and joins them together with a comma

#### Parameters
* `ids` A comma-separated list of account IDs.

#### Returns
The BuyOffersUriParameterBuilder object.

#### `public inline BuyOffersUriParameterBuilder `[`WithLowerBound`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a5731767078d7979c27487fa37805a14e)`(string lowerBound)` 

`WithLowerBound` sets the lower bound of the `account_ids` parameter

#### Parameters
* `lowerBound` The lower bound of the primary key

#### Returns
The BuyOffersUriParameterBuilder object.

#### `public inline BuyOffersUriParameterBuilder `[`WithUpperBound`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a504058d26a60d5c83936a959bd1a7eaa)`(string upperBound)` 

`WithUpperBound` sets the upper bound of the range of accounts to be returned

#### Parameters
* `upperBound` The upper bound of the primary key.

#### Returns
The BuyOffersUriParameterBuilder object.

#### `public inline BuyOffersUriParameterBuilder `[`WithBefore`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a3e1122046db1740d5fd3274213d9eaf4)`(int before)` 

`WithBefore` sets the `_before` variable to the value of the `before` parameter

#### Parameters
* `before` The previous values of the results to return.

#### Returns
The BuyOffersUriParameterBuilder object.

#### `public inline BuyOffersUriParameterBuilder `[`WithAfter`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a3057e050bf7054593aa959fcdc028b1c)`(int after)` 

`WithAfter` sets the `_after` variable to the value of the `after` parameter

#### Parameters
* `after` The later values of the results to return.

#### Returns
The BuyOffersUriParameterBuilder object.

#### `public inline BuyOffersUriParameterBuilder `[`WithPage`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a7db8f1d764e3f81768b7d1820e13b1a3)`(int page)` 

`WithPage` sets the `_page` variable to the value of the `page` parameter

#### Parameters
* `page` The page number of the results to return.

#### Returns
The BuyOffersUriParameterBuilder object.

#### `public inline BuyOffersUriParameterBuilder `[`WithLimit`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a6fdc43968793eec37e4ed6b72b0dadff)`(int limit)` 

`WithLimit` sets the `_limit` variable to the value of the `limit` parameter

#### Parameters
* `limit` The number of results to return.

#### Returns
The BuyOffersUriParameterBuilder object.

#### `public inline BuyOffersUriParameterBuilder `[`WithOrder`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a5cba5a767a3d1174cf57cc6adf4917fc)`(SortStrategy sorting)` 

This function sets the sort strategy for the query

#### Parameters
* `SortStrategy` 

#### Returns
The builder object itself.

#### `public inline BuyOffersUriParameterBuilder `[`WithSort`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a00d65b0190e84f48ae1bbb611da90824)`(string sort)` 

`WithSort` is a function that takes a string as a parameter and returns a `BuyOffersUriParameterBuilder` object

#### Parameters
* `sort` The sort order of the results.

#### Returns
A BuyOffersUriParameterBuilder object.

#### `public inline string `[`Build`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a933ab72b517a9c3879ef78b27a2483bf)`()` 

It builds a query string based on the parameters that have been set.

#### Returns
A string that contains the parameters for the query.

#### `private string `[`_state`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a9577beb4165c1157d2e7f8f0ff065dde) 

#### `private int? `[`_maxAssets`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1ae7334a7aa0ba955ac129865639f42b11) 

#### `private int? `[`_minAssets`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a2787cd3c00b52a44e78964a580457204) 

#### `private bool? `[`_showSellerContracts`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a162ce2b45598492d8053511dc8f5aaf0) 

#### `private bool? `[`_contractWhitelist`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a3ee1d446d0a7dc9c0a1c68409eace1b0) 

#### `private bool? `[`_sellerBlacklist`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1aeee97135fe3bd4392111f70290af4e0f) 

#### `private int? `[`_assetId`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a47b08a4420914a94240cbab6145522a5) 

#### `private string `[`_marketplace`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a9a3415610f1a82df64700fb430f6a369) 

#### `private string `[`_makerMarketplace`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1ae9ff2ea7ebb9f92f243fcf032613b846) 

#### `private string `[`_takerMarketplace`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a1cf7d3f1334cd998d136622cb2333fd1) 

#### `private string `[`_symbol`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a26c189f7d4c40f40f09ace24c4ccb945) 

#### `private string `[`_seller`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a519a8fc19333a31cc8096bf4836f6101) 

#### `private string `[`_buyer`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a5f3e23f4ac11074e75a05a39c775f65c) 

#### `private int? `[`_minPrice`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a966cc104ab35aeadc15268d2d9362555) 

#### `private int? `[`_maxPrice`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a9e95e6e4dfcd570c9838dbac9b7fab7b) 

#### `private int? `[`_minTemplateMint`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a480d12afcb85503c094e6c8001b5b46a) 

#### `private int? `[`_maxTemplateMint`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a6582a101a3e6766ec8fe47d29d5015b8) 

#### `private string `[`_owner`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1ac091a560bcb5025581c60ad2b3e1f3bb) 

#### `private bool? `[`_burned`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a88325c0b6dc8cb4a570b2faaca18efa7) 

#### `private string `[`_collectionName`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a10ec2fa990c6478bc519b1e57e1ab2aa) 

#### `private string `[`_schemaName`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a2f9a887fd4dfcf60bfe4240a27085724) 

#### `private string `[`_templateId`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a06f918051fc7b04615854510caa85934) 

#### `private bool? `[`_isTransferable`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a44e26246620bd9d4efa97c195a356672) 

#### `private bool? `[`_isBurnable`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a6020acf0c5cb6f447cfe5ba95579e74d) 

#### `private string `[`_match`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a5151210a8aa5d34ea523afbb052deb11) 

#### `private string `[`_collectionBlacklist`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a11b225f8984dd9ab3ab5fcec261245c4) 

#### `private string `[`_collectionWhitelist`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a525c994ce1a584f4d763ac9d5c1b3cb5) 

#### `private string `[`_ids`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a2a9be788653dd13950b2f00bfce1970b) 

#### `private string `[`_lowerBound`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a47926893a523918c50a931018c47480d) 

#### `private string `[`_upperBound`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1add1abf9a00e7bb81efb866424f4f34dc) 

#### `private int? `[`_before`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1aab4304cf3e09c19e898fe9224a0d723a) 

#### `private int? `[`_after`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1ae1483718c3d317e0b6046ada434c53ae) 

#### `private int? `[`_page`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a4dea13c8190a694fe00b24309b1814f8) 

#### `private int? `[`_limit`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a353a19a0da576dc8f69a61548a710395) 

#### `private SortStrategy? `[`_sortStrategy`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a122ea78edfd15b44a8a547a7046b8651) 

#### `private string `[`_sort`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder_1a3ac373edf19e058d7fae7f4c4ba485f4) 

