# SalesUriParameterBuilder

```
class AtomicMarketApiClient::Sales::SalesUriParameterBuilder
  : public IUriParameterBuilder
```

## Summary

| Members                                                                                                                                                                                                                                                                                                                                                                                                                                                     | Descriptions                                                                                                            |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------- |
| `public` [`SalesUriParameterBuilder`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder) `` [`WithState`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a86a45df5fbd7b8e856862532a64a4f2e)`(params` [`State`](AtomicMarketApiClient.md) `states)`         | `WithState` is a function that takes an array of strings and returns an `SalesUriParameterBuilder` object               |
| `public` [`SalesUriParameterBuilder`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder) `` [`WithMaxAssets`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a76c7fc41d88b240adcdbde353906eca5)`(int maxAssets)`                                           | `WithMaxAssets` sets the `_maxAssets` variable                                                                          |
| `public` [`SalesUriParameterBuilder`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder) `` [`WithMinAssets`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a33744ffa60e39119821b9f1ecad5cdc9)`(int minAssets)`                                           | `WithMinAssets` sets the `_minAssets` variable                                                                          |
| `public` [`SalesUriParameterBuilder`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder) `` [`WithShowSellerContracts`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a2f6ffc1f4ef5b03100b645c6599ecdf2)`(bool showSellerContracts)`                      | `WithShowSellerContracts` sets the `_showSellerContracts` field to the value of the `showSellerContracts` parameter     |
| `public` [`SalesUriParameterBuilder`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder) `` [`WithContractWhitelist`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a5e4d425d315f917862e4c78788d2930b)`(bool contractWhitelist)`                          | It sets the value of the \_contractWhitelist variable to the value of the contractWhitelist parameter.                  |
| `public` [`SalesUriParameterBuilder`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder) `` [`WithSellerBlacklist`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a3480cf3f78c169002ba0f419db7f8053)`(bool sellerBlacklist)`                              | `WithSellerBlacklist` is a function that takes a boolean value and returns a `SalesUriParameterBuilder` object          |
| `public` [`SalesUriParameterBuilder`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder) `` [`WithAssetId`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a3b5dfa3833684a07bc963f8ab531153c)`(int assetId)`                                               | `WithAssetId` is a function that takes an `int` and returns a `SalesUriParameterBuilder`                                |
| `public` [`SalesUriParameterBuilder`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder) `` [`WithMarketplace`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a81168a183ed2c43ff92df412e519447f)`(string marketplace)`                                    | `WithMarketplace` sets the `marketplace` parameter                                                                      |
| `public` [`SalesUriParameterBuilder`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder) `` [`WithMakerMarketplace`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1abec54c81d3c249ab5efcbc5a874ee7d8)`(string makerMarketplace)`                          | `WithMakerMarketplace` sets the `makerMarketplace` parameter                                                            |
| `public` [`SalesUriParameterBuilder`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder) `` [`WithTakerMarketplace`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a34490c70be51d5fed428b03bd5fb6d4c)`(string takerMarketplace)`                          | `WithTakerMarketplace` sets the `takerMarketplace` parameter                                                            |
| `public` [`SalesUriParameterBuilder`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder) `` [`WithSymbol`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1ae88f29ef451889790fe9f238d1484bee)`(string symbol)`                                              | A function that is used to set the symbol of the stock.                                                                 |
| `public` [`SalesUriParameterBuilder`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder) `` [`WithSeller`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a875d56605fa72b5001e700e794304d46)`(string seller)`                                              | `WithSeller` sets the `seller` parameter                                                                                |
| `public` [`SalesUriParameterBuilder`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder) `` [`WithBuyer`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1ad2e01fe4231d233a45e83dfb1ac82cce)`(string buyer)`                                                | `WithBuyer` sets the `buyer` parameter                                                                                  |
| `public` [`SalesUriParameterBuilder`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder) `` [`WithMinPrice`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1aa42cce1be0ef8410b134b8ce6d01a762)`(int minPrice)`                                             | `WithMinPrice` sets the `_minPrice` variable to the value of the `minPrice` parameter                                   |
| `public` [`SalesUriParameterBuilder`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder) `` [`WithMaxPrice`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1ac0c5fc8ee4cd5345c56c4f8dc568bd54)`(int maxPrice)`                                             | `WithMaxPrice` sets the `_maxPrice` variable to the value of the `maxPrice` parameter                                   |
| `public` [`SalesUriParameterBuilder`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder) `` [`WithMinTemplateMint`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1afd7983afa38b43cf2cc0e1bd0bd7de65)`(int minTemplateMint)`                               | `WithMinTemplateMint` sets the `_minTemplateMint` variable to the value of the `minTemplateMint` parameter              |
| `public` [`SalesUriParameterBuilder`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder) `` [`WithMaxTemplateMint`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a78a5e48c71bcf004394a8244789b2819)`(int maxTemplateMint)`                               | `WithMaxTemplateMint` sets the `_maxTemplateMint` variable to the value of the `maxTemplateMint` parameter              |
| `public` [`SalesUriParameterBuilder`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder) `` [`WithOwner`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a5467e07b8aaaf30642c8c6179d29984f)`(string owner)`                                                | `WithOwner` sets the `owner` parameter                                                                                  |
| `public` [`SalesUriParameterBuilder`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder) `` [`WithBurned`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a59c20393d8eacfc6c31ac27f6b0361b3)`(bool burned)`                                                | `WithBurned` sets the `_burned` field to the value of the `burned` parameter                                            |
| `public` [`SalesUriParameterBuilder`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder) `` [`WithCollectionName`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a3dc8b2720cab5bd6871ef19b8e01f888)`(string collectionName)`                              | `WithCollectionName` is a function that takes a string as a parameter and returns an `SalesUriParameterBuilder` object  |
| `public` [`SalesUriParameterBuilder`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder) `` [`WithSchemaName`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a54fe71c7e24e31be9ffcb00d2a1dbda4)`(string schemaName)`                                      | This function sets the schema name for the query.                                                                       |
| `public` [`SalesUriParameterBuilder`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder) `` [`WithTemplateId`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a2c4012ec7000907b114ef380f06d5720)`(string templateId)`                                      | It sets the value of the templateId variable.                                                                           |
| `public` [`SalesUriParameterBuilder`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder) `` [`WithIsTransferable`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1aff9cbcdf13b38f8635f2f316373ce366)`(bool isTransferable)`                                | `WithIsTransferable` sets the `_isTransferable` field to the value of the `isTransferable` parameter                    |
| `public` [`SalesUriParameterBuilder`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder) `` [`WithIsBurnable`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a9ebcf9f924c1db28c7cf96589e43f5cc)`(bool isBurnable)`                                        | `WithIsBurnable` sets the `_isBurnable` field to the value of the `isBurnable` parameter                                |
| `public` [`SalesUriParameterBuilder`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder) `` [`WithMatch`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1ac32454a0152e8f0123fea8b42493757b)`(string match)`                                                | `WithMatch` sets the `match` parameter                                                                                  |
| `public` [`SalesUriParameterBuilder`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder) `` [`WithCollectionBlacklist`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1adc5fd2699fadf6dd701d2bc758a9e47b)`(string[] collectionBlacklist)`                  | `WithCollectionBlacklist` is a function that takes an array of strings and returns an `SalesUriParameterBuilder` object |
| `public` [`SalesUriParameterBuilder`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder) `` [`WithCollectionWhitelist`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a4c6192f84cce56be9e6b80943918cacc)`(string[] collectionWhitelist)`                  | `WithCollectionWhitelist` is a function that takes an array of strings and returns an `SalesUriParameterBuilder` object |
| `public` [`SalesUriParameterBuilder`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder) `` [`WithIds`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a4f0c82a359bd71a367c7b4432c7ca42b)`(string[] ids)`                                                  | This function takes an array of strings and joins them together with a comma.                                           |
| `public` [`SalesUriParameterBuilder`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder) `` [`WithLowerBound`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a40dcbac822908ef8cb6c5bca2655d643)`(string lowerBound)`                                      | `WithLowerBound` sets the lower bound of the `account_ids` parameter                                                    |
| `public` [`SalesUriParameterBuilder`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder) `` [`WithUpperBound`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1ab9fc1b5779aa717826e06551139316ca)`(string upperBound)`                                      | `WithUpperBound` sets the upper bound of the range of accounts to be returned                                           |
| `public` [`SalesUriParameterBuilder`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder) `` [`WithBefore`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a256a74441516c8691f91bc507203cac8)`(int before)`                                                 | `WithBefore` sets the `_before` variable to the value of the `before` parameter                                         |
| `public` [`SalesUriParameterBuilder`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder) `` [`WithAfter`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1aab02bf05e9c019d8bb6f2b0a5a0712a4)`(int after)`                                                   | `WithAfter` sets the `_after` variable to the value of the `after` parameter                                            |
| `public` [`SalesUriParameterBuilder`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder) `` [`WithPage`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1ac1859744cba9862df4d50f592c9cfd3b)`(int page)`                                                     | `WithPage` sets the `_page` variable to the value of the `page` parameter                                               |
| `public` [`SalesUriParameterBuilder`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder) `` [`WithLimit`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a46d49579bbdf1539139fecf1a6adebcd)`(int limit)`                                                   | `WithLimit` sets the `_limit` variable to the value of the `limit` parameter                                            |
| `public` [`SalesUriParameterBuilder`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder) `` [`WithOrder`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a7bffd7098963c702d0871a5706e76c40)`(` [`SortStrategy`](AtomicMarketApiClient--Core.md) `sorting)` | This function sets the sort strategy for the query.                                                                     |
| `public` [`SalesUriParameterBuilder`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder) `` [`WithSort`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a7dfb9ebde66b8ca18245d42aaf9b2fb3)`(string sort)`                                                  | It sets the sort parameter to the value passed in.                                                                      |
| `public string` [`Build`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a933ab72b517a9c3879ef78b27a2483bf)`()`                                                                                                                                                                                                                                          | It builds a query string based on the parameters that have been set.                                                    |
| `private string` [`_state`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a9577beb4165c1157d2e7f8f0ff065dde)                                                                                                                                                                                                                                            | A private variable that is used to store the value of the state parameter.                                              |
| `private int?` [`_maxAssets`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1ae7334a7aa0ba955ac129865639f42b11)                                                                                                                                                                                                                                          | A nullable integer specfying max assets per listing.                                                                    |
| `private int?` [`_minAssets`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a2787cd3c00b52a44e78964a580457204)                                                                                                                                                                                                                                          | A nullable integer specfying min assets per listing.                                                                    |
| `private bool?` [`_showSellerContracts`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a162ce2b45598492d8053511dc8f5aaf0)                                                                                                                                                                                                                               | A nullable boolean specfying which sellerContracts to show.                                                             |
| `private bool?` [`_contractWhitelist`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a3ee1d446d0a7dc9c0a1c68409eace1b0)                                                                                                                                                                                                                                 | A nullable boolean specfying accounts with contracts.                                                                   |
| `private bool?` [`_sellerBlacklist`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1aeee97135fe3bd4392111f70290af4e0f)                                                                                                                                                                                                                                   | A nullable boolean specfying listing from sellers.                                                                      |
| `private int?` [`_assetId`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a47b08a4420914a94240cbab6145522a5)                                                                                                                                                                                                                                            | <p>A nullable integer specifying the assetId.<br></p>                                                                   |
| `private string` [`_marketplace`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a9a3415610f1a82df64700fb430f6a369)                                                                                                                                                                                                                                      | A private variable that is used to store the value of the maketplace parameter.                                         |
| `private string` [`_makerMarketplace`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1ae9ff2ea7ebb9f92f243fcf032613b846)                                                                                                                                                                                                                                 | A private variable that is used to store the value of the makerMarketplace parameter.                                   |
| `private string` [`_takerMarketplace`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a1cf7d3f1334cd998d136622cb2333fd1)                                                                                                                                                                                                                                 | A private variable that is used to store the value of the takerMarketplace parameter.                                   |
| `private string` [`_symbol`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a26c189f7d4c40f40f09ace24c4ccb945)                                                                                                                                                                                                                                           | A private variable that is used to store the value of the symbol parameter.                                             |
| `private string` [`_seller`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a519a8fc19333a31cc8096bf4836f6101)                                                                                                                                                                                                                                           | A private variable that is used to store the value of the seller parameter.                                             |
| `private string` [`_buyer`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a5f3e23f4ac11074e75a05a39c775f65c)                                                                                                                                                                                                                                            | A private variable that is used to store the value of the buyer parameter.                                              |
| `private int?` [`_minPrice`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a966cc104ab35aeadc15268d2d9362555)                                                                                                                                                                                                                                           | <p>A nullable integer specifying the min price.<br></p>                                                                 |
| `private int?` [`_maxPrice`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a9e95e6e4dfcd570c9838dbac9b7fab7b)                                                                                                                                                                                                                                           | <p>A nullable integer specifying the max price.<br></p>                                                                 |
| `private int?` [`_minTemplateMint`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a480d12afcb85503c094e6c8001b5b46a)                                                                                                                                                                                                                                    | A nullable integer specifying the minTemplateMint.                                                                      |
| `private int?` [`_maxTemplateMint`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a6582a101a3e6766ec8fe47d29d5015b8)                                                                                                                                                                                                                                    | <p>A nullable integer specifying the maxTemplateMint.<br></p>                                                           |
| `private string` [`_owner`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1ac091a560bcb5025581c60ad2b3e1f3bb)                                                                                                                                                                                                                                            | A private variable that is used to store the value of the owner parameter.                                              |
| `private bool?` [`_burned`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a88325c0b6dc8cb4a570b2faaca18efa7)                                                                                                                                                                                                                                            | A nullable boolean specfying burned assets.                                                                             |
| `private string` [`_collectionName`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a10ec2fa990c6478bc519b1e57e1ab2aa)                                                                                                                                                                                                                                   | A private variable that is used to store the value of the collectionName parameter.                                     |
| `private string` [`_schemaName`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a2f9a887fd4dfcf60bfe4240a27085724)                                                                                                                                                                                                                                       | A private variable that is used to store the value of the schemaName parameter.                                         |
| `private string` [`_templateId`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a06f918051fc7b04615854510caa85934)                                                                                                                                                                                                                                       | A private variable that is used to store the value of the templateId parameter.                                         |
| `private bool?` [`_isTransferable`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a44e26246620bd9d4efa97c195a356672)                                                                                                                                                                                                                                    | A nullable boolean specfying transferable assets.                                                                       |
| `private bool?` [`_isBurnable`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a6020acf0c5cb6f447cfe5ba95579e74d)                                                                                                                                                                                                                                        | A nullable boolean specfying burnable assets.                                                                           |
| `private string` [`_match`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a5151210a8aa5d34ea523afbb052deb11)                                                                                                                                                                                                                                            | A private variable that is used to store the value of the match parameter.                                              |
| `private string` [`_collectionBlacklist`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a11b225f8984dd9ab3ab5fcec261245c4)                                                                                                                                                                                                                              | A private variable that is used to store the value of the collectionBlacklist parameter.                                |
| `private string` [`_collectionWhitelist`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a525c994ce1a584f4d763ac9d5c1b3cb5)                                                                                                                                                                                                                              | A private variable that is used to store the value of the collectionWhitelist parameter.                                |
| `private string` [`_ids`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a2a9be788653dd13950b2f00bfce1970b)                                                                                                                                                                                                                                              | A private variable that is used to store the value of the ids parameter.                                                |
| `private string` [`_lowerBound`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a47926893a523918c50a931018c47480d)                                                                                                                                                                                                                                       | A private variable that is used to store the value of the lowerBound parameter.                                         |
| `private string` [`_upperBound`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1add1abf9a00e7bb81efb866424f4f34dc)                                                                                                                                                                                                                                       | A private variable that is used to store the value of the upperBound parameter.                                         |
| `private int?` [`_before`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1aab4304cf3e09c19e898fe9224a0d723a)                                                                                                                                                                                                                                             | A nullable integer specifying the previous timestamp.                                                                   |
| `private int?` [`_after`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1ae1483718c3d317e0b6046ada434c53ae)                                                                                                                                                                                                                                              | A nullable integer specifying the next timestamp.                                                                       |
| `private int?` [`_page`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a4dea13c8190a694fe00b24309b1814f8)                                                                                                                                                                                                                                               | A nullable integer specifying the page.                                                                                 |
| `private int?` [`_limit`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a353a19a0da576dc8f69a61548a710395)                                                                                                                                                                                                                                              | A nullable integer specifying the limit of returned values.                                                             |
| `private` [`SortStrategy`](AtomicMarketApiClient--Core.md)`?` [`_sortStrategy`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a122ea78edfd15b44a8a547a7046b8651)                                                                                                                                                                                        | A nullable enum specifying the sortStrategy.                                                                            |
| `private string` [`_sort`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a3ac373edf19e058d7fae7f4c4ba485f4)                                                                                                                                                                                                                                             | Declaring a private variable called \_sort.                                                                             |

## Members

**`public`** [**`SalesUriParameterBuilder`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder) **``** [**`WithState`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a86a45df5fbd7b8e856862532a64a4f2e)**`(params`** [**`State`**](AtomicMarketApiClient.md) **`states)`**

`WithState` is a function that takes an array of strings and returns an `SalesUriParameterBuilder` object

#### Parameters

* `state` Filters by sales state.

#### Returns

The SalesUriParameterBuilder object.

**`public`** [**`SalesUriParameterBuilder`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder) **``** [**`WithMaxAssets`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a76c7fc41d88b240adcdbde353906eca5)**`(int maxAssets)`**

`WithMaxAssets` sets the `_maxAssets` variable

#### Parameters

* `maxAssets` Max assets per listing returns.

#### Returns

The SalesUriParameterBuilder object.

**`public`** [**`SalesUriParameterBuilder`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder) **``** [**`WithMinAssets`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a33744ffa60e39119821b9f1ecad5cdc9)**`(int minAssets)`**

`WithMinAssets` sets the `_minAssets` variable

#### Parameters

* `minAssets` Min assets per listing returns.

#### Returns

The SalesUriParameterBuilder object.

**`public`** [**`SalesUriParameterBuilder`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder) **``** [**`WithShowSellerContracts`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a2f6ffc1f4ef5b03100b645c6599ecdf2)**`(bool showSellerContracts)`**

`WithShowSellerContracts` sets the `_showSellerContracts` field to the value of the `showSellerContracts` parameter

#### Parameters

* `showSellerContracts` If false,no seller contracts are shown except if they are in contract whitelist.

#### Returns

The SalesUriParameterBuilder object.

**`public`** [**`SalesUriParameterBuilder`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder) **``** [**`WithContractWhitelist`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a5e4d425d315f917862e4c78788d2930b)**`(bool contractWhitelist)`**

It sets the value of the \_contractWhitelist variable to the value of the contractWhitelist parameter.

#### Parameters

* `contractWhitelist` If true, only contracts that are in the whitelist will be returned.

#### Returns

The SalesUriParameterBuilder object is being returned.

**`public`** [**`SalesUriParameterBuilder`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder) **``** [**`WithSellerBlacklist`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a3480cf3f78c169002ba0f419db7f8053)**`(bool sellerBlacklist)`**

`WithSellerBlacklist` is a function that takes a boolean value and returns a `SalesUriParameterBuilder` object

#### Parameters

* `sellerBlacklist` If true, the seller will be added to the blacklist.

#### Returns

The SalesUriParameterBuilder object.

**`public`** [**`SalesUriParameterBuilder`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder) **``** [**`WithAssetId`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a3b5dfa3833684a07bc963f8ab531153c)**`(int assetId)`**

`WithAssetId` is a function that takes an `int` and returns a `SalesUriParameterBuilder`

#### Parameters

* `assetId` The ID of the asset you want to sell.

#### Returns

The SalesUriParameterBuilder object.

**`public`** [**`SalesUriParameterBuilder`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder) **``** [**`WithMarketplace`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a81168a183ed2c43ff92df412e519447f)**`(string marketplace)`**

`WithMarketplace` sets the `marketplace` parameter

#### Parameters

* `marketplace` It filters by all sales where a certain marketplace is either taker or maker marketplace.

#### Returns

The SalesUriParameterBuilder object.

**`public`** [**`SalesUriParameterBuilder`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder) **``** [**`WithMakerMarketplace`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1abec54c81d3c249ab5efcbc5a874ee7d8)**`(string makerMarketplace)`**

`WithMakerMarketplace` sets the `makerMarketplace` parameter

#### Parameters

* `makerMarketplace` separate multiple with ",".

#### Returns

The SalesUriParameterBuilder object.

**`public`** [**`SalesUriParameterBuilder`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder) **``** [**`WithTakerMarketplace`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a34490c70be51d5fed428b03bd5fb6d4c)**`(string takerMarketplace)`**

`WithTakerMarketplace` sets the `takerMarketplace` parameter

#### Parameters

* `takerMarketplace` separate multiple with ",".

#### Returns

The SalesUriParameterBuilder object.

**`public`** [**`SalesUriParameterBuilder`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder) **``** [**`WithSymbol`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1ae88f29ef451889790fe9f238d1484bee)**`(string symbol)`**

A function that is used to set the symbol of the stock.

#### Parameters

* `symbol` The symbol of the stock you want to get the sales data for.

#### Returns

The SalesUriParameterBuilder object is being returned.

**`public`** [**`SalesUriParameterBuilder`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder) **``** [**`WithSeller`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a875d56605fa72b5001e700e794304d46)**`(string seller)`**

`WithSeller` sets the `seller` parameter

#### Parameters

* `seller` Filter by seller.

#### Returns

The SalesUriParameterBuilder object.

**`public`** [**`SalesUriParameterBuilder`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder) **``** [**`WithBuyer`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1ad2e01fe4231d233a45e83dfb1ac82cce)**`(string buyer)`**

`WithBuyer` sets the `buyer` parameter

#### Parameters

* `buyer` Filter by buyer.

#### Returns

The SalesUriParameterBuilder object.

**`public`** [**`SalesUriParameterBuilder`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder) **``** [**`WithMinPrice`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1aa42cce1be0ef8410b134b8ce6d01a762)**`(int minPrice)`**

`WithMinPrice` sets the `_minPrice` variable to the value of the `minPrice` parameter

#### Parameters

* `minPrice` The lower price limit.

#### Returns

The SalesUriParameterBuilder object.

**`public`** [**`SalesUriParameterBuilder`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder) **``** [**`WithMaxPrice`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1ac0c5fc8ee4cd5345c56c4f8dc568bd54)**`(int maxPrice)`**

`WithMaxPrice` sets the `_maxPrice` variable to the value of the `maxPrice` parameter

#### Parameters

* `maxPrice` The upper price limit.

#### Returns

The SalesUriParameterBuilder object.

**`public`** [**`SalesUriParameterBuilder`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder) **``** [**`WithMinTemplateMint`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1afd7983afa38b43cf2cc0e1bd0bd7de65)**`(int minTemplateMint)`**

`WithMinTemplateMint` sets the `_minTemplateMint` variable to the value of the `minTemplateMint` parameter

#### Parameters

* `minTemplateMint` Min template mint.

#### Returns

The SalesUriParameterBuilder object.

**`public`** [**`SalesUriParameterBuilder`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder) **``** [**`WithMaxTemplateMint`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a78a5e48c71bcf004394a8244789b2819)**`(int maxTemplateMint)`**

`WithMaxTemplateMint` sets the `_maxTemplateMint` variable to the value of the `maxTemplateMint` parameter

#### Parameters

* `maxTemplateMint` Max template mint.

#### Returns

The SalesUriParameterBuilder object.

**`public`** [**`SalesUriParameterBuilder`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder) **``** [**`WithOwner`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a5467e07b8aaaf30642c8c6179d29984f)**`(string owner)`**

`WithOwner` sets the `owner` parameter

#### Parameters

* `owner` The owner parameter is used to filter the results. The owner parameter is a string that is matched against the account name.

#### Returns

The SalesUriParameterBuilder object.

**`public`** [**`SalesUriParameterBuilder`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder) **``** [**`WithBurned`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a59c20393d8eacfc6c31ac27f6b0361b3)**`(bool burned)`**

`WithBurned` sets the `_burned` field to the value of the `burned` parameter

#### Parameters

* `burned` It filters for burned assets.

#### Returns

The SalesUriParameterBuilder object.

**`public`** [**`SalesUriParameterBuilder`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder) **``** [**`WithCollectionName`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a3dc8b2720cab5bd6871ef19b8e01f888)**`(string collectionName)`**

`WithCollectionName` is a function that takes a string as a parameter and returns an `SalesUriParameterBuilder` object

#### Parameters

* `collectionName` The name of the collection you want to query.

#### Returns

The SalesUriParameterBuilder object.

**`public`** [**`SalesUriParameterBuilder`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder) **``** [**`WithSchemaName`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a54fe71c7e24e31be9ffcb00d2a1dbda4)**`(string schemaName)`**

This function sets the schema name for the query.

#### Parameters

* `schemaName` The name of the schema to use.

#### Returns

The SalesUriParameterBuilder object.

**`public`** [**`SalesUriParameterBuilder`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder) **``** [**`WithTemplateId`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a2c4012ec7000907b114ef380f06d5720)**`(string templateId)`**

It sets the value of the templateId variable.

#### Parameters

* `templateId` Results based on only transfers which cointain assets of template.

#### Returns

The SalesUriParameterBuilder object.

**`public`** [**`SalesUriParameterBuilder`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder) **``** [**`WithIsTransferable`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1aff9cbcdf13b38f8635f2f316373ce366)**`(bool isTransferable)`**

`WithIsTransferable` sets the `_isTransferable` field to the value of the `isTransferable` parameter

#### Parameters

* `isTransferable` The isTransferable parameter filters for transferable assets.

#### Returns

The SalesUriParameterBuilder object.

**`public`** [**`SalesUriParameterBuilder`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder) **``** [**`WithIsBurnable`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a9ebcf9f924c1db28c7cf96589e43f5cc)**`(bool isBurnable)`**

`WithIsBurnable` sets the `_isBurnable` field to the value of the `isBurnable` parameter

#### Parameters

* `isBurnable` Filters for burnable assets.

#### Returns

The SalesUriParameterBuilder object.

**`public`** [**`SalesUriParameterBuilder`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder) **``** [**`WithMatch`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1ac32454a0152e8f0123fea8b42493757b)**`(string match)`**

`WithMatch` sets the `match` parameter

#### Parameters

* `match` Search for input in asset name on template data.

#### Returns

The SalesUriParameterBuilder object.

**`public`** [**`SalesUriParameterBuilder`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder) **``** [**`WithCollectionBlacklist`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1adc5fd2699fadf6dd701d2bc758a9e47b)**`(string[] collectionBlacklist)`**

`WithCollectionBlacklist` is a function that takes an array of strings and returns an `SalesUriParameterBuilder` object

#### Parameters

* `collectionBlacklist` A list of collections to exclude from the results.

#### Returns

The SalesUriParameterBuilder object.

**`public`** [**`SalesUriParameterBuilder`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder) **``** [**`WithCollectionWhitelist`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a4c6192f84cce56be9e6b80943918cacc)**`(string[] collectionWhitelist)`**

`WithCollectionWhitelist` is a function that takes an array of strings and returns an `SalesUriParameterBuilder` object

#### Parameters

* `collectionWhitelist` A list of collections to include in the response.

#### Returns

The SalesUriParameterBuilder object.

**`public`** [**`SalesUriParameterBuilder`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder) **``** [**`WithIds`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a4f0c82a359bd71a367c7b4432c7ca42b)**`(string[] ids)`**

This function takes an array of strings and joins them together with a comma.

#### Parameters

* `ids` A comma-separated list of account IDs.

#### Returns

The SalesUriParameterBuilder object.

**`public`** [**`SalesUriParameterBuilder`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder) **``** [**`WithLowerBound`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a40dcbac822908ef8cb6c5bca2655d643)**`(string lowerBound)`**

`WithLowerBound` sets the lower bound of the `account_ids` parameter

#### Parameters

* `lowerBound` The lower bound of the primary key

#### Returns

The SalesUriParameterBuilder object.

**`public`** [**`SalesUriParameterBuilder`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder) **``** [**`WithUpperBound`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1ab9fc1b5779aa717826e06551139316ca)**`(string upperBound)`**

`WithUpperBound` sets the upper bound of the range of accounts to be returned

#### Parameters

* `upperBound` The upper bound of the primary key.

#### Returns

The SalesUriParameterBuilder object.

**`public`** [**`SalesUriParameterBuilder`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder) **``** [**`WithBefore`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a256a74441516c8691f91bc507203cac8)**`(int before)`**

`WithBefore` sets the `_before` variable to the value of the `before` parameter

#### Parameters

* `before` The previous values of the results to return.

#### Returns

The SalesUriParameterBuilder object.

**`public`** [**`SalesUriParameterBuilder`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder) **``** [**`WithAfter`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1aab02bf05e9c019d8bb6f2b0a5a0712a4)**`(int after)`**

`WithAfter` sets the `_after` variable to the value of the `after` parameter

#### Parameters

* `after` The later values of the results to return.

#### Returns

The SalesUriParameterBuilder object.

**`public`** [**`SalesUriParameterBuilder`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder) **``** [**`WithPage`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1ac1859744cba9862df4d50f592c9cfd3b)**`(int page)`**

`WithPage` sets the `_page` variable to the value of the `page` parameter

#### Parameters

* `page` The page number of the results to return.

#### Returns

The SalesUriParameterBuilder object.

**`public`** [**`SalesUriParameterBuilder`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder) **``** [**`WithLimit`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a46d49579bbdf1539139fecf1a6adebcd)**`(int limit)`**

`WithLimit` sets the `_limit` variable to the value of the `limit` parameter

#### Parameters

* `limit` The number of results to return.

#### Returns

The SalesUriParameterBuilder object.

**`public`** [**`SalesUriParameterBuilder`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder) **``** [**`WithOrder`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a7bffd7098963c702d0871a5706e76c40)**`(` ** [**`SortStrategy`**](AtomicMarketApiClient--Core.md) **`sorting)`**

This function sets the sort strategy for the query.

#### Parameters

* `SortStrategy`

#### Returns

The builder object itself.

**`public`** [**`SalesUriParameterBuilder`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder) **``** [**`WithSort`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a7dfb9ebde66b8ca18245d42aaf9b2fb3)**`(string sort)`**

It sets the sort parameter to the value passed in.

#### Parameters

* `sort` The sort order of the results.

#### Returns

The SalesUriParameterBuilder object is being returned.

**`public string`** [**`Build`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a933ab72b517a9c3879ef78b27a2483bf)**`()`**

It builds a query string based on the parameters that have been set.

#### Returns

A string that contains the parameters for the query.

**`private string`** [**`_state`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a9577beb4165c1157d2e7f8f0ff065dde)

A private variable that is used to store the value of the state parameter.

**`private int?`** [**`_maxAssets`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1ae7334a7aa0ba955ac129865639f42b11)

A nullable integer specfying max assets per listing.

**`private int?`** [**`_minAssets`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a2787cd3c00b52a44e78964a580457204)

A nullable integer specfying min assets per listing.

**`private bool?`** [**`_showSellerContracts`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a162ce2b45598492d8053511dc8f5aaf0)

A nullable boolean specfying which sellerContracts to show.

**`private bool?`** [**`_contractWhitelist`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a3ee1d446d0a7dc9c0a1c68409eace1b0)

A nullable boolean specfying accounts with contracts.

**`private bool?`** [**`_sellerBlacklist`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1aeee97135fe3bd4392111f70290af4e0f)

A nullable boolean specfying listing from sellers.

**`private int?`** [**`_assetId`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a47b08a4420914a94240cbab6145522a5)

A nullable integer specifying the assetId.\


**`private string`** [**`_marketplace`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a9a3415610f1a82df64700fb430f6a369)

A private variable that is used to store the value of the maketplace parameter.

**`private string`** [**`_makerMarketplace`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1ae9ff2ea7ebb9f92f243fcf032613b846)

A private variable that is used to store the value of the makerMarketplace parameter.

**`private string`** [**`_takerMarketplace`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a1cf7d3f1334cd998d136622cb2333fd1)

A private variable that is used to store the value of the takerMarketplace parameter.

**`private string`** [**`_symbol`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a26c189f7d4c40f40f09ace24c4ccb945)

A private variable that is used to store the value of the symbol parameter.

**`private string`** [**`_seller`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a519a8fc19333a31cc8096bf4836f6101)

A private variable that is used to store the value of the seller parameter.

**`private string`** [**`_buyer`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a5f3e23f4ac11074e75a05a39c775f65c)

A private variable that is used to store the value of the buyer parameter.

**`private int?`** [**`_minPrice`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a966cc104ab35aeadc15268d2d9362555)

A nullable integer specifying the min price.\


**`private int?`** [**`_maxPrice`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a9e95e6e4dfcd570c9838dbac9b7fab7b)

A nullable integer specifying the max price.\


**`private int?`** [**`_minTemplateMint`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a480d12afcb85503c094e6c8001b5b46a)

A nullable integer specifying the minTemplateMint.

**`private int?`** [**`_maxTemplateMint`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a6582a101a3e6766ec8fe47d29d5015b8)

A nullable integer specifying the maxTemplateMint.\


**`private string`** [**`_owner`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1ac091a560bcb5025581c60ad2b3e1f3bb)

A private variable that is used to store the value of the owner parameter.

**`private bool?`** [**`_burned`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a88325c0b6dc8cb4a570b2faaca18efa7)

A nullable boolean specfying burned assets.

**`private string`** [**`_collectionName`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a10ec2fa990c6478bc519b1e57e1ab2aa)

A private variable that is used to store the value of the collectionName parameter.

**`private string`** [**`_schemaName`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a2f9a887fd4dfcf60bfe4240a27085724)

A private variable that is used to store the value of the schemaName parameter.

**`private string`** [**`_templateId`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a06f918051fc7b04615854510caa85934)

A private variable that is used to store the value of the templateId parameter.

**`private bool?`** [**`_isTransferable`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a44e26246620bd9d4efa97c195a356672)

A nullable boolean specfying transferable assets.

**`private bool?`** [**`_isBurnable`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a6020acf0c5cb6f447cfe5ba95579e74d)

A nullable boolean specfying burnable assets.

**`private string`** [**`_match`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a5151210a8aa5d34ea523afbb052deb11)

A private variable that is used to store the value of the match parameter.

**`private string`** [**`_collectionBlacklist`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a11b225f8984dd9ab3ab5fcec261245c4)

A private variable that is used to store the value of the collectionBlacklist parameter.

**`private string`** [**`_collectionWhitelist`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a525c994ce1a584f4d763ac9d5c1b3cb5)

A private variable that is used to store the value of the collectionWhitelist parameter.

**`private string`** [**`_ids`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a2a9be788653dd13950b2f00bfce1970b)

A private variable that is used to store the value of the ids parameter.

**`private string`** [**`_lowerBound`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a47926893a523918c50a931018c47480d)

A private variable that is used to store the value of the lowerBound parameter.

**`private string`** [**`_upperBound`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1add1abf9a00e7bb81efb866424f4f34dc)

A private variable that is used to store the value of the upperBound parameter.

**`private int?`** [**`_before`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1aab4304cf3e09c19e898fe9224a0d723a)

A nullable integer specifying the previous timestamp.

**`private int?`** [**`_after`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1ae1483718c3d317e0b6046ada434c53ae)

A nullable integer specifying the next timestamp.

**`private int?`** [**`_page`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a4dea13c8190a694fe00b24309b1814f8)

A nullable integer specifying the page.

**`private int?`** [**`_limit`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a353a19a0da576dc8f69a61548a710395)

A nullable integer specifying the limit of returned values.

**`private`** [**`SortStrategy`**](AtomicMarketApiClient--Core.md)**`?`** [**`_sortStrategy`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a122ea78edfd15b44a8a547a7046b8651)

A nullable enum specifying the sortStrategy.

**`private string`** [**`_sort`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_uri\_parameter\_builder\_1a3ac373edf19e058d7fae7f4c4ba485f4)

Declaring a private variable called \_sort.
