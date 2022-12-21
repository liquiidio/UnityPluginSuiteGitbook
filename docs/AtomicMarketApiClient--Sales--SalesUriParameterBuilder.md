# class `AtomicMarketApiClient::Sales::SalesUriParameterBuilder` 

```
class AtomicMarketApiClient::Sales::SalesUriParameterBuilder
  : public IUriParameterBuilder
```

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public ` [`SalesUriParameterBuilder`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder)` ` [`WithState`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a86a45df5fbd7b8e856862532a64a4f2e)`(params ` [`State`](.github/workflows/documentation/md/AtomicMarketApiClient.md#namespace_atomic_market_api_client_1ac975e092be6aef4456c9af8ddc8e33bf)` states)` | `WithState` is a function that takes an array of strings and returns an `SalesUriParameterBuilder` object
`public ` [`SalesUriParameterBuilder`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder)` ` [`WithMaxAssets`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a76c7fc41d88b240adcdbde353906eca5)`(int maxAssets)` | `WithMaxAssets` sets the `_maxAssets` variable
`public ` [`SalesUriParameterBuilder`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder)` ` [`WithMinAssets`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a33744ffa60e39119821b9f1ecad5cdc9)`(int minAssets)` | `WithMinAssets` sets the `_minAssets` variable
`public ` [`SalesUriParameterBuilder`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder)` ` [`WithShowSellerContracts`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a2f6ffc1f4ef5b03100b645c6599ecdf2)`(bool showSellerContracts)` | `WithShowSellerContracts` sets the `_showSellerContracts` field to the value of the `showSellerContracts` parameter
`public ` [`SalesUriParameterBuilder`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder)` ` [`WithContractWhitelist`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a5e4d425d315f917862e4c78788d2930b)`(bool contractWhitelist)` | It sets the value of the _contractWhitelist variable to the value of the contractWhitelist parameter.
`public ` [`SalesUriParameterBuilder`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder)` ` [`WithSellerBlacklist`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a3480cf3f78c169002ba0f419db7f8053)`(bool sellerBlacklist)` | `WithSellerBlacklist` is a function that takes a boolean value and returns a `SalesUriParameterBuilder` object
`public ` [`SalesUriParameterBuilder`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder)` ` [`WithAssetId`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a3b5dfa3833684a07bc963f8ab531153c)`(int assetId)` | `WithAssetId` is a function that takes an `int` and returns a `SalesUriParameterBuilder`
`public ` [`SalesUriParameterBuilder`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder)` ` [`WithMarketplace`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a81168a183ed2c43ff92df412e519447f)`(string marketplace)` | `WithMarketplace` sets the `marketplace` parameter
`public ` [`SalesUriParameterBuilder`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder)` ` [`WithMakerMarketplace`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1abec54c81d3c249ab5efcbc5a874ee7d8)`(string makerMarketplace)` | `WithMakerMarketplace` sets the `makerMarketplace` parameter
`public ` [`SalesUriParameterBuilder`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder)` ` [`WithTakerMarketplace`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a34490c70be51d5fed428b03bd5fb6d4c)`(string takerMarketplace)` | `WithTakerMarketplace` sets the `takerMarketplace` parameter
`public ` [`SalesUriParameterBuilder`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder)` ` [`WithSymbol`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1ae88f29ef451889790fe9f238d1484bee)`(string symbol)` | A function that is used to set the symbol of the stock.
`public ` [`SalesUriParameterBuilder`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder)` ` [`WithSeller`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a875d56605fa72b5001e700e794304d46)`(string seller)` | `WithSeller` sets the `seller` parameter
`public ` [`SalesUriParameterBuilder`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder)` ` [`WithBuyer`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1ad2e01fe4231d233a45e83dfb1ac82cce)`(string buyer)` | `WithBuyer` sets the `buyer` parameter
`public ` [`SalesUriParameterBuilder`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder)` ` [`WithMinPrice`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1aa42cce1be0ef8410b134b8ce6d01a762)`(int minPrice)` | `WithMinPrice` sets the `_minPrice` variable to the value of the `minPrice` parameter
`public ` [`SalesUriParameterBuilder`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder)` ` [`WithMaxPrice`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1ac0c5fc8ee4cd5345c56c4f8dc568bd54)`(int maxPrice)` | `WithMaxPrice` sets the `_maxPrice` variable to the value of the `maxPrice` parameter
`public ` [`SalesUriParameterBuilder`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder)` ` [`WithMinTemplateMint`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1afd7983afa38b43cf2cc0e1bd0bd7de65)`(int minTemplateMint)` | `WithMinTemplateMint` sets the `_minTemplateMint` variable to the value of the `minTemplateMint` parameter
`public ` [`SalesUriParameterBuilder`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder)` ` [`WithMaxTemplateMint`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a78a5e48c71bcf004394a8244789b2819)`(int maxTemplateMint)` | `WithMaxTemplateMint` sets the `_maxTemplateMint` variable to the value of the `maxTemplateMint` parameter
`public ` [`SalesUriParameterBuilder`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder)` ` [`WithOwner`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a5467e07b8aaaf30642c8c6179d29984f)`(string owner)` | `WithOwner` sets the `owner` parameter
`public ` [`SalesUriParameterBuilder`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder)` ` [`WithBurned`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a59c20393d8eacfc6c31ac27f6b0361b3)`(bool burned)` | `WithBurned` sets the `_burned` field to the value of the `burned` parameter
`public ` [`SalesUriParameterBuilder`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder)` ` [`WithCollectionName`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a3dc8b2720cab5bd6871ef19b8e01f888)`(string collectionName)` | `WithCollectionName` is a function that takes a string as a parameter and returns an `SalesUriParameterBuilder` object
`public ` [`SalesUriParameterBuilder`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder)` ` [`WithSchemaName`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a54fe71c7e24e31be9ffcb00d2a1dbda4)`(string schemaName)` | This function sets the schema name for the query.
`public ` [`SalesUriParameterBuilder`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder)` ` [`WithTemplateId`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a2c4012ec7000907b114ef380f06d5720)`(string templateId)` | It sets the value of the templateId variable.
`public ` [`SalesUriParameterBuilder`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder)` ` [`WithIsTransferable`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1aff9cbcdf13b38f8635f2f316373ce366)`(bool isTransferable)` | `WithIsTransferable` sets the `_isTransferable` field to the value of the `isTransferable` parameter
`public ` [`SalesUriParameterBuilder`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder)` ` [`WithIsBurnable`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a9ebcf9f924c1db28c7cf96589e43f5cc)`(bool isBurnable)` | `WithIsBurnable` sets the `_isBurnable` field to the value of the `isBurnable` parameter
`public ` [`SalesUriParameterBuilder`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder)` ` [`WithMatch`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1ac32454a0152e8f0123fea8b42493757b)`(string match)` | `WithMatch` sets the `match` parameter
`public ` [`SalesUriParameterBuilder`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder)` ` [`WithCollectionBlacklist`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1adc5fd2699fadf6dd701d2bc758a9e47b)`(string[] collectionBlacklist)` | `WithCollectionBlacklist` is a function that takes an array of strings and returns an `SalesUriParameterBuilder` object
`public ` [`SalesUriParameterBuilder`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder)` ` [`WithCollectionWhitelist`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a4c6192f84cce56be9e6b80943918cacc)`(string[] collectionWhitelist)` | `WithCollectionWhitelist` is a function that takes an array of strings and returns an `SalesUriParameterBuilder` object
`public ` [`SalesUriParameterBuilder`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder)` ` [`WithIds`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a4f0c82a359bd71a367c7b4432c7ca42b)`(string[] ids)` | This function takes an array of strings and joins them together with a comma.
`public ` [`SalesUriParameterBuilder`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder)` ` [`WithLowerBound`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a40dcbac822908ef8cb6c5bca2655d643)`(string lowerBound)` | `WithLowerBound` sets the lower bound of the `account_ids` parameter
`public ` [`SalesUriParameterBuilder`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder)` ` [`WithUpperBound`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1ab9fc1b5779aa717826e06551139316ca)`(string upperBound)` | `WithUpperBound` sets the upper bound of the range of accounts to be returned
`public ` [`SalesUriParameterBuilder`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder)` ` [`WithBefore`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a256a74441516c8691f91bc507203cac8)`(int before)` | `WithBefore` sets the `_before` variable to the value of the `before` parameter
`public ` [`SalesUriParameterBuilder`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder)` ` [`WithAfter`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1aab02bf05e9c019d8bb6f2b0a5a0712a4)`(int after)` | `WithAfter` sets the `_after` variable to the value of the `after` parameter
`public ` [`SalesUriParameterBuilder`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder)` ` [`WithPage`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1ac1859744cba9862df4d50f592c9cfd3b)`(int page)` | `WithPage` sets the `_page` variable to the value of the `page` parameter
`public ` [`SalesUriParameterBuilder`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder)` ` [`WithLimit`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a46d49579bbdf1539139fecf1a6adebcd)`(int limit)` | `WithLimit` sets the `_limit` variable to the value of the `limit` parameter
`public ` [`SalesUriParameterBuilder`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder)` ` [`WithOrder`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a7bffd7098963c702d0871a5706e76c40)`(` [`SortStrategy`](.github/workflows/documentation/md/AtomicMarketApiClient--Core.md#namespace_atomic_market_api_client_1_1_core_1a1a2688049f7c9dc4f77213ca78b6de0f)` sorting)` | This function sets the sort strategy for the query.
`public ` [`SalesUriParameterBuilder`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder)` ` [`WithSort`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a7dfb9ebde66b8ca18245d42aaf9b2fb3)`(string sort)` | It sets the sort parameter to the value passed in.
`public string ` [`Build`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a933ab72b517a9c3879ef78b27a2483bf)`()` | It builds a query string based on the parameters that have been set.
`private string ` [`_state`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a9577beb4165c1157d2e7f8f0ff065dde) | 
`private int? ` [`_maxAssets`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1ae7334a7aa0ba955ac129865639f42b11) | 
`private int? ` [`_minAssets`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a2787cd3c00b52a44e78964a580457204) | 
`private bool? ` [`_showSellerContracts`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a162ce2b45598492d8053511dc8f5aaf0) | 
`private bool? ` [`_contractWhitelist`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a3ee1d446d0a7dc9c0a1c68409eace1b0) | 
`private bool? ` [`_sellerBlacklist`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1aeee97135fe3bd4392111f70290af4e0f) | 
`private int? ` [`_assetId`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a47b08a4420914a94240cbab6145522a5) | 
`private string ` [`_marketplace`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a9a3415610f1a82df64700fb430f6a369) | 
`private string ` [`_makerMarketplace`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1ae9ff2ea7ebb9f92f243fcf032613b846) | 
`private string ` [`_takerMarketplace`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a1cf7d3f1334cd998d136622cb2333fd1) | 
`private string ` [`_symbol`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a26c189f7d4c40f40f09ace24c4ccb945) | 
`private string ` [`_seller`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a519a8fc19333a31cc8096bf4836f6101) | 
`private string ` [`_buyer`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a5f3e23f4ac11074e75a05a39c775f65c) | 
`private int? ` [`_minPrice`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a966cc104ab35aeadc15268d2d9362555) | 
`private int? ` [`_maxPrice`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a9e95e6e4dfcd570c9838dbac9b7fab7b) | 
`private int? ` [`_minTemplateMint`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a480d12afcb85503c094e6c8001b5b46a) | 
`private int? ` [`_maxTemplateMint`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a6582a101a3e6766ec8fe47d29d5015b8) | 
`private string ` [`_owner`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1ac091a560bcb5025581c60ad2b3e1f3bb) | 
`private bool? ` [`_burned`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a88325c0b6dc8cb4a570b2faaca18efa7) | 
`private string ` [`_collectionName`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a10ec2fa990c6478bc519b1e57e1ab2aa) | 
`private string ` [`_schemaName`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a2f9a887fd4dfcf60bfe4240a27085724) | 
`private string ` [`_templateId`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a06f918051fc7b04615854510caa85934) | 
`private bool? ` [`_isTransferable`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a44e26246620bd9d4efa97c195a356672) | 
`private bool? ` [`_isBurnable`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a6020acf0c5cb6f447cfe5ba95579e74d) | 
`private string ` [`_match`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a5151210a8aa5d34ea523afbb052deb11) | 
`private string ` [`_collectionBlacklist`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a11b225f8984dd9ab3ab5fcec261245c4) | 
`private string ` [`_collectionWhitelist`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a525c994ce1a584f4d763ac9d5c1b3cb5) | 
`private string ` [`_ids`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a2a9be788653dd13950b2f00bfce1970b) | 
`private string ` [`_lowerBound`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a47926893a523918c50a931018c47480d) | 
`private string ` [`_upperBound`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1add1abf9a00e7bb81efb866424f4f34dc) | 
`private int? ` [`_before`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1aab4304cf3e09c19e898fe9224a0d723a) | 
`private int? ` [`_after`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1ae1483718c3d317e0b6046ada434c53ae) | 
`private int? ` [`_page`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a4dea13c8190a694fe00b24309b1814f8) | 
`private int? ` [`_limit`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a353a19a0da576dc8f69a61548a710395) | 
`private ` [`SortStrategy`](.github/workflows/documentation/md/AtomicMarketApiClient--Core.md#namespace_atomic_market_api_client_1_1_core_1a1a2688049f7c9dc4f77213ca78b6de0f)`? ` [`_sortStrategy`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a122ea78edfd15b44a8a547a7046b8651) | 
`private string ` [`_sort`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a3ac373edf19e058d7fae7f4c4ba485f4) | 

## Members

##### `public ` [`SalesUriParameterBuilder`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder)` ` [`WithState`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a86a45df5fbd7b8e856862532a64a4f2e)`(params ` [`State`](.github/workflows/documentation/md/AtomicMarketApiClient.md#namespace_atomic_market_api_client_1ac975e092be6aef4456c9af8ddc8e33bf)` states)` 

`WithState` is a function that takes an array of strings and returns an `SalesUriParameterBuilder` object

#### Parameters
* `state` Filters by sales state.

#### Returns
The SalesUriParameterBuilder object.

##### `public ` [`SalesUriParameterBuilder`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder)` ` [`WithMaxAssets`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a76c7fc41d88b240adcdbde353906eca5)`(int maxAssets)` 

`WithMaxAssets` sets the `_maxAssets` variable

#### Parameters
* `maxAssets` Max assets per listing returns.

#### Returns
The SalesUriParameterBuilder object.

##### `public ` [`SalesUriParameterBuilder`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder)` ` [`WithMinAssets`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a33744ffa60e39119821b9f1ecad5cdc9)`(int minAssets)` 

`WithMinAssets` sets the `_minAssets` variable

#### Parameters
* `minAssets` Min assets per listing returns.

#### Returns
The SalesUriParameterBuilder object.

##### `public ` [`SalesUriParameterBuilder`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder)` ` [`WithShowSellerContracts`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a2f6ffc1f4ef5b03100b645c6599ecdf2)`(bool showSellerContracts)` 

`WithShowSellerContracts` sets the `_showSellerContracts` field to the value of the `showSellerContracts` parameter

#### Parameters
* `showSellerContracts` If false,no seller contracts are shown except if they are in contract whitelist.

#### Returns
The SalesUriParameterBuilder object.

##### `public ` [`SalesUriParameterBuilder`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder)` ` [`WithContractWhitelist`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a5e4d425d315f917862e4c78788d2930b)`(bool contractWhitelist)` 

It sets the value of the _contractWhitelist variable to the value of the contractWhitelist parameter.

#### Parameters
* `contractWhitelist` If true, only contracts that are in the whitelist will be returned.

#### Returns
The SalesUriParameterBuilder object is being returned.

##### `public ` [`SalesUriParameterBuilder`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder)` ` [`WithSellerBlacklist`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a3480cf3f78c169002ba0f419db7f8053)`(bool sellerBlacklist)` 

`WithSellerBlacklist` is a function that takes a boolean value and returns a `SalesUriParameterBuilder` object

#### Parameters
* `sellerBlacklist` If true, the seller will be added to the blacklist.

#### Returns
The SalesUriParameterBuilder object.

##### `public ` [`SalesUriParameterBuilder`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder)` ` [`WithAssetId`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a3b5dfa3833684a07bc963f8ab531153c)`(int assetId)` 

`WithAssetId` is a function that takes an `int` and returns a `SalesUriParameterBuilder`

#### Parameters
* `assetId` The ID of the asset you want to sell.

#### Returns
The SalesUriParameterBuilder object.

##### `public ` [`SalesUriParameterBuilder`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder)` ` [`WithMarketplace`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a81168a183ed2c43ff92df412e519447f)`(string marketplace)` 

`WithMarketplace` sets the `marketplace` parameter

#### Parameters
* `marketplace` It filters by all sales where a certain marketplace is either taker or maker marketplace.

#### Returns
The SalesUriParameterBuilder object.

##### `public ` [`SalesUriParameterBuilder`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder)` ` [`WithMakerMarketplace`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1abec54c81d3c249ab5efcbc5a874ee7d8)`(string makerMarketplace)` 

`WithMakerMarketplace` sets the `makerMarketplace` parameter

#### Parameters
* `makerMarketplace` separate multiple with ",".

#### Returns
The SalesUriParameterBuilder object.

##### `public ` [`SalesUriParameterBuilder`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder)` ` [`WithTakerMarketplace`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a34490c70be51d5fed428b03bd5fb6d4c)`(string takerMarketplace)` 

`WithTakerMarketplace` sets the `takerMarketplace` parameter

#### Parameters
* `takerMarketplace` separate multiple with ",".

#### Returns
The SalesUriParameterBuilder object.

##### `public ` [`SalesUriParameterBuilder`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder)` ` [`WithSymbol`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1ae88f29ef451889790fe9f238d1484bee)`(string symbol)` 

A function that is used to set the symbol of the stock.

#### Parameters
* `symbol` The symbol of the stock you want to get the sales data for.

#### Returns
The SalesUriParameterBuilder object is being returned.

##### `public ` [`SalesUriParameterBuilder`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder)` ` [`WithSeller`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a875d56605fa72b5001e700e794304d46)`(string seller)` 

`WithSeller` sets the `seller` parameter

#### Parameters
* `seller` Filter by seller.

#### Returns
The SalesUriParameterBuilder object.

##### `public ` [`SalesUriParameterBuilder`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder)` ` [`WithBuyer`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1ad2e01fe4231d233a45e83dfb1ac82cce)`(string buyer)` 

`WithBuyer` sets the `buyer` parameter

#### Parameters
* `buyer` Filter by buyer.

#### Returns
The SalesUriParameterBuilder object.

##### `public ` [`SalesUriParameterBuilder`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder)` ` [`WithMinPrice`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1aa42cce1be0ef8410b134b8ce6d01a762)`(int minPrice)` 

`WithMinPrice` sets the `_minPrice` variable to the value of the `minPrice` parameter

#### Parameters
* `minPrice` The lower price limit.

#### Returns
The SalesUriParameterBuilder object.

##### `public ` [`SalesUriParameterBuilder`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder)` ` [`WithMaxPrice`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1ac0c5fc8ee4cd5345c56c4f8dc568bd54)`(int maxPrice)` 

`WithMaxPrice` sets the `_maxPrice` variable to the value of the `maxPrice` parameter

#### Parameters
* `maxPrice` The upper price limit.

#### Returns
The SalesUriParameterBuilder object.

##### `public ` [`SalesUriParameterBuilder`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder)` ` [`WithMinTemplateMint`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1afd7983afa38b43cf2cc0e1bd0bd7de65)`(int minTemplateMint)` 

`WithMinTemplateMint` sets the `_minTemplateMint` variable to the value of the `minTemplateMint` parameter

#### Parameters
* `minTemplateMint` Min template mint.

#### Returns
The SalesUriParameterBuilder object.

##### `public ` [`SalesUriParameterBuilder`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder)` ` [`WithMaxTemplateMint`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a78a5e48c71bcf004394a8244789b2819)`(int maxTemplateMint)` 

`WithMaxTemplateMint` sets the `_maxTemplateMint` variable to the value of the `maxTemplateMint` parameter

#### Parameters
* `maxTemplateMint` Max template mint.

#### Returns
The SalesUriParameterBuilder object.

##### `public ` [`SalesUriParameterBuilder`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder)` ` [`WithOwner`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a5467e07b8aaaf30642c8c6179d29984f)`(string owner)` 

`WithOwner` sets the `owner` parameter

#### Parameters
* `owner` The owner parameter is used to filter the results. The owner parameter is a string that is matched against the account name.

#### Returns
The SalesUriParameterBuilder object.

##### `public ` [`SalesUriParameterBuilder`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder)` ` [`WithBurned`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a59c20393d8eacfc6c31ac27f6b0361b3)`(bool burned)` 

`WithBurned` sets the `_burned` field to the value of the `burned` parameter

#### Parameters
* `burned` It filters for burned assets.

#### Returns
The SalesUriParameterBuilder object.

##### `public ` [`SalesUriParameterBuilder`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder)` ` [`WithCollectionName`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a3dc8b2720cab5bd6871ef19b8e01f888)`(string collectionName)` 

`WithCollectionName` is a function that takes a string as a parameter and returns an `SalesUriParameterBuilder` object

#### Parameters
* `collectionName` The name of the collection you want to query.

#### Returns
The SalesUriParameterBuilder object.

##### `public ` [`SalesUriParameterBuilder`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder)` ` [`WithSchemaName`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a54fe71c7e24e31be9ffcb00d2a1dbda4)`(string schemaName)` 

This function sets the schema name for the query.

#### Parameters
* `schemaName` The name of the schema to use.

#### Returns
The SalesUriParameterBuilder object.

##### `public ` [`SalesUriParameterBuilder`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder)` ` [`WithTemplateId`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a2c4012ec7000907b114ef380f06d5720)`(string templateId)` 

It sets the value of the templateId variable.

#### Parameters
* `templateId` Results based on only transfers which cointain assets of template.

#### Returns
The SalesUriParameterBuilder object.

##### `public ` [`SalesUriParameterBuilder`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder)` ` [`WithIsTransferable`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1aff9cbcdf13b38f8635f2f316373ce366)`(bool isTransferable)` 

`WithIsTransferable` sets the `_isTransferable` field to the value of the `isTransferable` parameter

#### Parameters
* `isTransferable` The isTransferable parameter filters for transferable assets.

#### Returns
The SalesUriParameterBuilder object.

##### `public ` [`SalesUriParameterBuilder`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder)` ` [`WithIsBurnable`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a9ebcf9f924c1db28c7cf96589e43f5cc)`(bool isBurnable)` 

`WithIsBurnable` sets the `_isBurnable` field to the value of the `isBurnable` parameter

#### Parameters
* `isBurnable` Filters for burnable assets.

#### Returns
The SalesUriParameterBuilder object.

##### `public ` [`SalesUriParameterBuilder`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder)` ` [`WithMatch`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1ac32454a0152e8f0123fea8b42493757b)`(string match)` 

`WithMatch` sets the `match` parameter

#### Parameters
* `match` Search for input in asset name on template data.

#### Returns
The SalesUriParameterBuilder object.

##### `public ` [`SalesUriParameterBuilder`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder)` ` [`WithCollectionBlacklist`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1adc5fd2699fadf6dd701d2bc758a9e47b)`(string[] collectionBlacklist)` 

`WithCollectionBlacklist` is a function that takes an array of strings and returns an `SalesUriParameterBuilder` object

#### Parameters
* `collectionBlacklist` A list of collections to exclude from the results.

#### Returns
The SalesUriParameterBuilder object.

##### `public ` [`SalesUriParameterBuilder`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder)` ` [`WithCollectionWhitelist`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a4c6192f84cce56be9e6b80943918cacc)`(string[] collectionWhitelist)` 

`WithCollectionWhitelist` is a function that takes an array of strings and returns an `SalesUriParameterBuilder` object

#### Parameters
* `collectionWhitelist` A list of collections to include in the response.

#### Returns
The SalesUriParameterBuilder object.

##### `public ` [`SalesUriParameterBuilder`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder)` ` [`WithIds`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a4f0c82a359bd71a367c7b4432c7ca42b)`(string[] ids)` 

This function takes an array of strings and joins them together with a comma.

#### Parameters
* `ids` A comma-separated list of account IDs.

#### Returns
The SalesUriParameterBuilder object.

##### `public ` [`SalesUriParameterBuilder`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder)` ` [`WithLowerBound`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a40dcbac822908ef8cb6c5bca2655d643)`(string lowerBound)` 

`WithLowerBound` sets the lower bound of the `account_ids` parameter

#### Parameters
* `lowerBound` The lower bound of the primary key

#### Returns
The SalesUriParameterBuilder object.

##### `public ` [`SalesUriParameterBuilder`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder)` ` [`WithUpperBound`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1ab9fc1b5779aa717826e06551139316ca)`(string upperBound)` 

`WithUpperBound` sets the upper bound of the range of accounts to be returned

#### Parameters
* `upperBound` The upper bound of the primary key.

#### Returns
The SalesUriParameterBuilder object.

##### `public ` [`SalesUriParameterBuilder`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder)` ` [`WithBefore`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a256a74441516c8691f91bc507203cac8)`(int before)` 

`WithBefore` sets the `_before` variable to the value of the `before` parameter

#### Parameters
* `before` The previous values of the results to return.

#### Returns
The SalesUriParameterBuilder object.

##### `public ` [`SalesUriParameterBuilder`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder)` ` [`WithAfter`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1aab02bf05e9c019d8bb6f2b0a5a0712a4)`(int after)` 

`WithAfter` sets the `_after` variable to the value of the `after` parameter

#### Parameters
* `after` The later values of the results to return.

#### Returns
The SalesUriParameterBuilder object.

##### `public ` [`SalesUriParameterBuilder`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder)` ` [`WithPage`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1ac1859744cba9862df4d50f592c9cfd3b)`(int page)` 

`WithPage` sets the `_page` variable to the value of the `page` parameter

#### Parameters
* `page` The page number of the results to return.

#### Returns
The SalesUriParameterBuilder object.

##### `public ` [`SalesUriParameterBuilder`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder)` ` [`WithLimit`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a46d49579bbdf1539139fecf1a6adebcd)`(int limit)` 

`WithLimit` sets the `_limit` variable to the value of the `limit` parameter

#### Parameters
* `limit` The number of results to return.

#### Returns
The SalesUriParameterBuilder object.

##### `public ` [`SalesUriParameterBuilder`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder)` ` [`WithOrder`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a7bffd7098963c702d0871a5706e76c40)`(` [`SortStrategy`](.github/workflows/documentation/md/AtomicMarketApiClient--Core.md#namespace_atomic_market_api_client_1_1_core_1a1a2688049f7c9dc4f77213ca78b6de0f)` sorting)` 

This function sets the sort strategy for the query.

#### Parameters
* `SortStrategy` 

#### Returns
The builder object itself.

##### `public ` [`SalesUriParameterBuilder`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder)` ` [`WithSort`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a7dfb9ebde66b8ca18245d42aaf9b2fb3)`(string sort)` 

It sets the sort parameter to the value passed in.

#### Parameters
* `sort` The sort order of the results.

#### Returns
The SalesUriParameterBuilder object is being returned.

##### `public string ` [`Build`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a933ab72b517a9c3879ef78b27a2483bf)`()` 

It builds a query string based on the parameters that have been set.

#### Returns
A string that contains the parameters for the query.

##### `private string ` [`_state`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a9577beb4165c1157d2e7f8f0ff065dde) 

##### `private int? ` [`_maxAssets`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1ae7334a7aa0ba955ac129865639f42b11) 

##### `private int? ` [`_minAssets`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a2787cd3c00b52a44e78964a580457204) 

##### `private bool? ` [`_showSellerContracts`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a162ce2b45598492d8053511dc8f5aaf0) 

##### `private bool? ` [`_contractWhitelist`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a3ee1d446d0a7dc9c0a1c68409eace1b0) 

##### `private bool? ` [`_sellerBlacklist`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1aeee97135fe3bd4392111f70290af4e0f) 

##### `private int? ` [`_assetId`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a47b08a4420914a94240cbab6145522a5) 

##### `private string ` [`_marketplace`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a9a3415610f1a82df64700fb430f6a369) 

##### `private string ` [`_makerMarketplace`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1ae9ff2ea7ebb9f92f243fcf032613b846) 

##### `private string ` [`_takerMarketplace`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a1cf7d3f1334cd998d136622cb2333fd1) 

##### `private string ` [`_symbol`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a26c189f7d4c40f40f09ace24c4ccb945) 

##### `private string ` [`_seller`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a519a8fc19333a31cc8096bf4836f6101) 

##### `private string ` [`_buyer`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a5f3e23f4ac11074e75a05a39c775f65c) 

##### `private int? ` [`_minPrice`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a966cc104ab35aeadc15268d2d9362555) 

##### `private int? ` [`_maxPrice`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a9e95e6e4dfcd570c9838dbac9b7fab7b) 

##### `private int? ` [`_minTemplateMint`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a480d12afcb85503c094e6c8001b5b46a) 

##### `private int? ` [`_maxTemplateMint`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a6582a101a3e6766ec8fe47d29d5015b8) 

##### `private string ` [`_owner`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1ac091a560bcb5025581c60ad2b3e1f3bb) 

##### `private bool? ` [`_burned`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a88325c0b6dc8cb4a570b2faaca18efa7) 

##### `private string ` [`_collectionName`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a10ec2fa990c6478bc519b1e57e1ab2aa) 

##### `private string ` [`_schemaName`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a2f9a887fd4dfcf60bfe4240a27085724) 

##### `private string ` [`_templateId`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a06f918051fc7b04615854510caa85934) 

##### `private bool? ` [`_isTransferable`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a44e26246620bd9d4efa97c195a356672) 

##### `private bool? ` [`_isBurnable`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a6020acf0c5cb6f447cfe5ba95579e74d) 

##### `private string ` [`_match`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a5151210a8aa5d34ea523afbb052deb11) 

##### `private string ` [`_collectionBlacklist`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a11b225f8984dd9ab3ab5fcec261245c4) 

##### `private string ` [`_collectionWhitelist`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a525c994ce1a584f4d763ac9d5c1b3cb5) 

##### `private string ` [`_ids`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a2a9be788653dd13950b2f00bfce1970b) 

##### `private string ` [`_lowerBound`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a47926893a523918c50a931018c47480d) 

##### `private string ` [`_upperBound`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1add1abf9a00e7bb81efb866424f4f34dc) 

##### `private int? ` [`_before`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1aab4304cf3e09c19e898fe9224a0d723a) 

##### `private int? ` [`_after`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1ae1483718c3d317e0b6046ada434c53ae) 

##### `private int? ` [`_page`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a4dea13c8190a694fe00b24309b1814f8) 

##### `private int? ` [`_limit`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a353a19a0da576dc8f69a61548a710395) 

##### `private ` [`SortStrategy`](.github/workflows/documentation/md/AtomicMarketApiClient--Core.md#namespace_atomic_market_api_client_1_1_core_1a1a2688049f7c9dc4f77213ca78b6de0f)`? ` [`_sortStrategy`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a122ea78edfd15b44a8a547a7046b8651) 

##### `private string ` [`_sort`](#class_atomic_market_api_client_1_1_sales_1_1_sales_uri_parameter_builder_1a3ac373edf19e058d7fae7f4c4ba485f4) 

