# BuyOffersUriParameterBuilder

```
class AtomicMarketApiClient::BuyOffers::BuyOffersUriParameterBuilder
  : public IUriParameterBuilder
```

## Summary

| Members                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | Descriptions                                                                                                                                                                    |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `public` [`BuyOffersUriParameterBuilder`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder) `` [`WithState`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1ad1d57ac008fce06cefe6f737403ded76)`(params` [`State`](AtomicMarketApiClient.md) `states)`         | `WithState` takes a list of `State`s and returns a `BuyOffersUriParameterBuilder` with the `_state` property set to a comma separated list of the `int` values of the `State`s. |
| `public` [`BuyOffersUriParameterBuilder`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder) `` [`WithMaxAssets`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a04337bf2ef03afffa3f6919cd4d159bd)`(int maxAssets)`                                           | `WithMaxAssets` sets the `_maxAssets` variable                                                                                                                                  |
| `public` [`BuyOffersUriParameterBuilder`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder) `` [`WithMinAssets`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a36d5d80b95e3ec47dbe2d9f0901f7fae)`(int minAssets)`                                           | `WithMinAssets` sets the `_minAssets` variable to the value of the `minAssets` parameter                                                                                        |
| `public` [`BuyOffersUriParameterBuilder`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder) `` [`WithShowSellerContracts`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a7bc149df66d6d266fb7da1fc8d45f4ca)`(bool showSellerContracts)`                      | It sets the value of the private variable \_showSellerContracts to the value of the parameter showSellerContracts.                                                              |
| `public` [`BuyOffersUriParameterBuilder`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder) `` [`WithContractWhitelist`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1ac6d4d16440a837a08583aac126f8c900)`(bool contractWhitelist)`                          | `WithContractWhitelist` is a function that takes a boolean value and returns a `BuyOffersUriParameterBuilder` object                                                            |
| `public` [`BuyOffersUriParameterBuilder`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder) `` [`WithSellerBlacklist`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a8dd00acee021dba4d6435d6ff069d2ec)`(bool sellerBlacklist)`                              | `WithSellerBlacklist` sets the `_sellerBlacklist` field to the value of the `sellerBlacklist` parameter                                                                         |
| `public` [`BuyOffersUriParameterBuilder`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder) `` [`WithAssetId`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a06aa361597137d4866df61aa4be3eaad)`(int assetId)`                                               | `WithAssetId` sets the `_assetId` variable to the value of the `asset_id` parameter                                                                                             |
| `public` [`BuyOffersUriParameterBuilder`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder) `` [`WithMarketplace`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a0acfc5fa5151f97b7a759bf0f6a65e41)`(string marketplace)`                                    | `WithMarketplace` sets the `marketplace` parameter                                                                                                                              |
| `public` [`BuyOffersUriParameterBuilder`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder) `` [`WithMakerMarketplace`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a96020e008cd1cee457aabaf5280794a8)`(string makerMarketplace)`                          | `WithMakerMarketplace` sets the `makerMarketplace` parameter                                                                                                                    |
| `public` [`BuyOffersUriParameterBuilder`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder) `` [`WithTakerMarketplace`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a577a1385e2a2b6cb06229b562a19cfeb)`(string takerMarketplace)`                          | `WithTakerMarketplace` sets the `takerMarketplace` parameter                                                                                                                    |
| `public` [`BuyOffersUriParameterBuilder`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder) `` [`WithSymbol`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1aa59e8f84dfa764e44d8fbb5ba236f8aa)`(string symbol)`                                              | `WithSymbol` is a function that takes a string as a parameter and returns a `BuyOffersUriParameterBuilder` object.                                                              |
| `public` [`BuyOffersUriParameterBuilder`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder) `` [`WithSeller`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a67580fa4e652092ec5207b10c4147715)`(string seller)`                                              | `WithSeller` sets the `seller` parameter                                                                                                                                        |
| `public` [`BuyOffersUriParameterBuilder`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder) `` [`WithBuyer`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1adca4dcf4e63354d86c019a4d652422db)`(string buyer)`                                                | `WithBuyer` sets the `buyer` parameter                                                                                                                                          |
| `public` [`BuyOffersUriParameterBuilder`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder) `` [`WithMinPrice`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1ab8d0a121574368409cda1249e0297cc4)`(int minPrice)`                                             | `WithMinPrice` sets the `_minPrice` variable to the value of the `minPrice` parameter                                                                                           |
| `public` [`BuyOffersUriParameterBuilder`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder) `` [`WithMaxPrice`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a4c1866db567c2caa324b9576c782ee0c)`(int maxPrice)`                                             | `WithMaxPrice` sets the `_maxPrice` variable to the value of the `maxPrice` parameter                                                                                           |
| `public` [`BuyOffersUriParameterBuilder`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder) `` [`WithMinTemplateMint`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1aa27c9a4b609dddf1fdc149a0a8d8926a)`(int minTemplateMint)`                               | `WithMinTemplateMint` sets the `_minTemplateMint` variable to the value of the `minTemplateMint` parameter                                                                      |
| `public` [`BuyOffersUriParameterBuilder`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder) `` [`WithMaxTemplateMint`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a65d226b09278093614b67210908262b4)`(int maxTemplateMint)`                               | `WithMaxTemplateMint` sets the `_maxTemplateMint` variable to the value of the `maxTemplateMint` parameter                                                                      |
| `public` [`BuyOffersUriParameterBuilder`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder) `` [`WithOwner`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a543b2861cf67c93707354ed5f574e4ba)`(string owner)`                                                | `WithOwner` sets the `owner` parameter                                                                                                                                          |
| `public` [`BuyOffersUriParameterBuilder`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder) `` [`WithBurned`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a55f2bbdb2f55004093a28de4dc1465ce)`(bool burned)`                                                | `WithBurned` sets the `_burned` field to the value of the `burned` parameter                                                                                                    |
| `public` [`BuyOffersUriParameterBuilder`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder) `` [`WithCollectionName`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a88bf9feb5fdf55504be6681f137e9b2e)`(string collectionName)`                              | `WithCollectionName` is a function that takes a string as a parameter and returns an `BuyOffersUriParameterBuilder` object                                                      |
| `public` [`BuyOffersUriParameterBuilder`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder) `` [`WithSchemaName`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1acfae2469372c85d4d047af0ab102c024)`(string schemaName)`                                      | This function sets the schema name for the query.                                                                                                                               |
| `public` [`BuyOffersUriParameterBuilder`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder) `` [`WithTemplateId`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1aefefc1b4bc929a0d0d86bb88df7c374a)`(string templateId)`                                      | It sets the value of the templateId variable.                                                                                                                                   |
| `public` [`BuyOffersUriParameterBuilder`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder) `` [`WithIsTransferable`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a3a6dbdabe529064b880b858dc5c34503)`(bool isTransferable)`                                | `WithIsTransferable` sets the `_isTransferable` field to the value of the `isTransferable` parameter                                                                            |
| `public` [`BuyOffersUriParameterBuilder`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder) `` [`WithIsBurnable`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a4c0e3f9ee3375eab0889f3c7cba5d7d2)`(bool isBurnable)`                                        | `WithIsBurnable` sets the `_isBurnable` field to the value of the `isBurnable` parameter                                                                                        |
| `public` [`BuyOffersUriParameterBuilder`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder) `` [`WithMatch`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a9f4a1cf45953d187e703042c0af612d6)`(string match)`                                                | `WithMatch` sets the `match` parameter                                                                                                                                          |
| `public` [`BuyOffersUriParameterBuilder`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder) `` [`WithCollectionBlacklist`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1aa6d0074266a4608e693590d8cb09a379)`(string[] collectionBlacklist)`                  | `WithCollectionBlacklist` is a function that takes an array of strings and returns an `BuyOffersUriParameterBuilder` object                                                     |
| `public` [`BuyOffersUriParameterBuilder`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder) `` [`WithCollectionWhitelist`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a94a9f8bbf2f3c6fcb338ff302c0716b5)`(string[] collectionWhitelist)`                  | `WithCollectionWhitelist` is a function that takes an array of strings and returns an `BuyOffersUriParameterBuilder` object                                                     |
| `public` [`BuyOffersUriParameterBuilder`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder) `` [`WithIds`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1aae8d094a1dbd124f37251b8001c8566f)`(string[] ids)`                                                  | This function takes an array of strings and joins them together with a comma.                                                                                                   |
| `public` [`BuyOffersUriParameterBuilder`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder) `` [`WithLowerBound`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a5731767078d7979c27487fa37805a14e)`(string lowerBound)`                                      | `WithLowerBound` sets the lower bound of the `account_ids` parameter                                                                                                            |
| `public` [`BuyOffersUriParameterBuilder`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder) `` [`WithUpperBound`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a504058d26a60d5c83936a959bd1a7eaa)`(string upperBound)`                                      | `WithUpperBound` sets the upper bound of the range of accounts to be returned                                                                                                   |
| `public` [`BuyOffersUriParameterBuilder`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder) `` [`WithBefore`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a3e1122046db1740d5fd3274213d9eaf4)`(int before)`                                                 | `WithBefore` sets the `_before` variable to the value of the `before` parameter                                                                                                 |
| `public` [`BuyOffersUriParameterBuilder`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder) `` [`WithAfter`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a3057e050bf7054593aa959fcdc028b1c)`(int after)`                                                   | `WithAfter` sets the `_after` variable to the value of the `after` parameter                                                                                                    |
| `public` [`BuyOffersUriParameterBuilder`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder) `` [`WithPage`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a7db8f1d764e3f81768b7d1820e13b1a3)`(int page)`                                                     | `WithPage` sets the `_page` variable to the value of the `page` parameter                                                                                                       |
| `public` [`BuyOffersUriParameterBuilder`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder) `` [`WithLimit`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a6fdc43968793eec37e4ed6b72b0dadff)`(int limit)`                                                   | `WithLimit` sets the `_limit` variable to the value of the `limit` parameter                                                                                                    |
| `public` [`BuyOffersUriParameterBuilder`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder) `` [`WithOrder`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a5cba5a767a3d1174cf57cc6adf4917fc)`(` [`SortStrategy`](AtomicMarketApiClient--Core.md) `sorting)` | This function sets the sort strategy for the query.                                                                                                                             |
| `public` [`BuyOffersUriParameterBuilder`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder) `` [`WithSort`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a00d65b0190e84f48ae1bbb611da90824)`(string sort)`                                                  | `WithSort` is a function that takes a string as a parameter and returns a `BuyOffersUriParameterBuilder` object                                                                 |
| `public string` [`Build`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a933ab72b517a9c3879ef78b27a2483bf)`()`                                                                                                                                                                                                                                                                  | It builds a query string based on the parameters that have been set.                                                                                                            |
| `private string` [`_state`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a9577beb4165c1157d2e7f8f0ff065dde)                                                                                                                                                                                                                                                                    | A private variable that is used to store the value of the state parameter.                                                                                                      |
| `private int?` [`_maxAssets`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1ae7334a7aa0ba955ac129865639f42b11)                                                                                                                                                                                                                                                                  | A nullable integer specfying max assets per listing.                                                                                                                            |
| `private int?` [`_minAssets`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a2787cd3c00b52a44e78964a580457204)                                                                                                                                                                                                                                                                  | A nullable integer specfying min assets per listing.                                                                                                                            |
| `private bool?` [`_showSellerContracts`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a162ce2b45598492d8053511dc8f5aaf0)                                                                                                                                                                                                                                                       | A nullable boolean specfying which sellerContracts to show.                                                                                                                     |
| `private bool?` [`_contractWhitelist`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a3ee1d446d0a7dc9c0a1c68409eace1b0)                                                                                                                                                                                                                                                         | A nullable boolean specfying accounts with contracts.                                                                                                                           |
| `private bool?` [`_sellerBlacklist`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1aeee97135fe3bd4392111f70290af4e0f)                                                                                                                                                                                                                                                           | A nullable boolean specfying listing from sellers.                                                                                                                              |
| `private int?` [`_assetId`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a47b08a4420914a94240cbab6145522a5)                                                                                                                                                                                                                                                                    | <p>A nullable integer specifying the assetId.<br></p>                                                                                                                           |
| `private string` [`_marketplace`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a9a3415610f1a82df64700fb430f6a369)                                                                                                                                                                                                                                                              | A private variable that is used to store the value of the maketplace parameter.                                                                                                 |
| `private string` [`_makerMarketplace`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1ae9ff2ea7ebb9f92f243fcf032613b846)                                                                                                                                                                                                                                                         | A private variable that is used to store the value of the makerMarketplace parameter.                                                                                           |
| `private string` [`_takerMarketplace`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a1cf7d3f1334cd998d136622cb2333fd1)                                                                                                                                                                                                                                                         | A private variable that is used to store the value of the takerMarketplace parameter.                                                                                           |
| `private string` [`_symbol`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a26c189f7d4c40f40f09ace24c4ccb945)                                                                                                                                                                                                                                                                   | A private variable that is used to store the value of the symbol parameter.                                                                                                     |
| `private string` [`_seller`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a519a8fc19333a31cc8096bf4836f6101)                                                                                                                                                                                                                                                                   | A private variable that is used to store the value of the seller parameter.                                                                                                     |
| `private string` [`_buyer`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a5f3e23f4ac11074e75a05a39c775f65c)                                                                                                                                                                                                                                                                    | A private variable that is used to store the value of the buyer parameter.                                                                                                      |
| `private int?` [`_minPrice`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a966cc104ab35aeadc15268d2d9362555)                                                                                                                                                                                                                                                                   | <p>A nullable integer specifying the min price.<br></p>                                                                                                                         |
| `private int?` [`_maxPrice`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a9e95e6e4dfcd570c9838dbac9b7fab7b)                                                                                                                                                                                                                                                                   | <p>A nullable integer specifying the max price.<br></p>                                                                                                                         |
| `private int?` [`_minTemplateMint`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a480d12afcb85503c094e6c8001b5b46a)                                                                                                                                                                                                                                                            | <p>A nullable integer specifying the minTemplateMint.<br></p>                                                                                                                   |
| `private int?` [`_maxTemplateMint`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a6582a101a3e6766ec8fe47d29d5015b8)                                                                                                                                                                                                                                                            | <p>A nullable integer specifying the maxTemplateMint.<br></p>                                                                                                                   |
| `private string` [`_owner`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1ac091a560bcb5025581c60ad2b3e1f3bb)                                                                                                                                                                                                                                                                    | A private variable that is used to store the value of the owner parameter.                                                                                                      |
| `private bool?` [`_burned`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a88325c0b6dc8cb4a570b2faaca18efa7)                                                                                                                                                                                                                                                                    | A nullable boolean specfying burned assets.                                                                                                                                     |
| `private string` [`_collectionName`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a10ec2fa990c6478bc519b1e57e1ab2aa)                                                                                                                                                                                                                                                           | A private variable that is used to store the value of the collectionName parameter.                                                                                             |
| `private string` [`_schemaName`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a2f9a887fd4dfcf60bfe4240a27085724)                                                                                                                                                                                                                                                               | A private variable that is used to store the value of the schemaName parameter.                                                                                                 |
| `private string` [`_templateId`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a06f918051fc7b04615854510caa85934)                                                                                                                                                                                                                                                               | A private variable that is used to store the value of the templateId parameter.                                                                                                 |
| `private bool?` [`_isTransferable`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a44e26246620bd9d4efa97c195a356672)                                                                                                                                                                                                                                                            | A nullable boolean specfying transferable assets.                                                                                                                               |
| `private bool?` [`_isBurnable`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a6020acf0c5cb6f447cfe5ba95579e74d)                                                                                                                                                                                                                                                                | A nullable boolean specfying burnable assets.                                                                                                                                   |
| `private string` [`_match`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a5151210a8aa5d34ea523afbb052deb11)                                                                                                                                                                                                                                                                    | A private variable that is used to store the value of the match parameter.                                                                                                      |
| `private string` [`_collectionBlacklist`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a11b225f8984dd9ab3ab5fcec261245c4)                                                                                                                                                                                                                                                      | A private variable that is used to store the value of the collectionBlacklist parameter.                                                                                        |
| `private string` [`_collectionWhitelist`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a525c994ce1a584f4d763ac9d5c1b3cb5)                                                                                                                                                                                                                                                      | A private variable that is used to store the value of the collectionWhitelist parameter.                                                                                        |
| `private string` [`_ids`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a2a9be788653dd13950b2f00bfce1970b)                                                                                                                                                                                                                                                                      | A private variable that is used to store the value of the ids parameter.                                                                                                        |
| `private string` [`_lowerBound`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a47926893a523918c50a931018c47480d)                                                                                                                                                                                                                                                               | A private variable that is used to store the value of the lowerBound parameter.                                                                                                 |
| `private string` [`_upperBound`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1add1abf9a00e7bb81efb866424f4f34dc)                                                                                                                                                                                                                                                               | A private variable that is used to store the value of the upperBound parameter.                                                                                                 |
| `private int?` [`_before`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1aab4304cf3e09c19e898fe9224a0d723a)                                                                                                                                                                                                                                                                     | A nullable integer specifying the previous timestamp.                                                                                                                           |
| `private int?` [`_after`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1ae1483718c3d317e0b6046ada434c53ae)                                                                                                                                                                                                                                                                      | <p>A nullable integer specifying the next timestamp.<br></p>                                                                                                                    |
| `private int?` [`_page`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a4dea13c8190a694fe00b24309b1814f8)                                                                                                                                                                                                                                                                       | <p>A nullable integer specifying the page.<br></p>                                                                                                                              |
| `private int?` [`_limit`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a353a19a0da576dc8f69a61548a710395)                                                                                                                                                                                                                                                                      | A nullable integer specifying the limit of returned values.                                                                                                                     |
| `private` [`SortStrategy`](AtomicMarketApiClient--Core.md)`?` [`_sortStrategy`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a122ea78edfd15b44a8a547a7046b8651)                                                                                                                                                                                                                | A nullable enum specifying the sortStrategy.                                                                                                                                    |
| `private string` [`_sort`](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a3ac373edf19e058d7fae7f4c4ba485f4)                                                                                                                                                                                                                                                                     | Declaring a private variable called \_sort.                                                                                                                                     |

## Members

**`public`** [**`BuyOffersUriParameterBuilder`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder) **``** [**`WithState`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1ad1d57ac008fce06cefe6f737403ded76)**`(params`** [**`State`**](AtomicMarketApiClient.md) **`states)`**

`WithState` takes a list of `State`s and returns a `BuyOffersUriParameterBuilder` with the `_state` property set to a comma separated list of the `int` values of the `State`s.

#### Returns

The BuyOffersUriParameterBuilder object.

**`public`** [**`BuyOffersUriParameterBuilder`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder) **``** [**`WithMaxAssets`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a04337bf2ef03afffa3f6919cd4d159bd)**`(int maxAssets)`**

`WithMaxAssets` sets the `_maxAssets` variable

#### Parameters

* `maxAssets` Max assets per listing returns.

#### Returns

The BuyOffersUriParameterBuilder object.

**`public`** [**`BuyOffersUriParameterBuilder`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder) **``** [**`WithMinAssets`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a36d5d80b95e3ec47dbe2d9f0901f7fae)**`(int minAssets)`**

`WithMinAssets` sets the `_minAssets` variable to the value of the `minAssets` parameter

#### Parameters

* `minAssets` The minimum number of assets the offer must have.

#### Returns

The BuyOffersUriParameterBuilder object.

**`public`** [**`BuyOffersUriParameterBuilder`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder) **``** [**`WithShowSellerContracts`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a7bc149df66d6d266fb7da1fc8d45f4ca)**`(bool showSellerContracts)`**

It sets the value of the private variable \_showSellerContracts to the value of the parameter showSellerContracts.

#### Parameters

* `showSellerContracts` If true, the response will include the seller's contract details.

#### Returns

The BuyOffersUriParameterBuilder object.

**`public`** [**`BuyOffersUriParameterBuilder`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder) **``** [**`WithContractWhitelist`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1ac6d4d16440a837a08583aac126f8c900)**`(bool contractWhitelist)`**

`WithContractWhitelist` is a function that takes a boolean value and returns a `BuyOffersUriParameterBuilder` object

#### Parameters

* `contractWhitelist` If true, only offers from contracts in the whitelist will be returned.

#### Returns

The BuyOffersUriParameterBuilder object.

**`public`** [**`BuyOffersUriParameterBuilder`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder) **``** [**`WithSellerBlacklist`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a8dd00acee021dba4d6435d6ff069d2ec)**`(bool sellerBlacklist)`**

`WithSellerBlacklist` sets the `_sellerBlacklist` field to the value of the `sellerBlacklist` parameter

#### Parameters

* `sellerBlacklist` Doesnot show listing from sellers.

#### Returns

The BuyOffersUriParameterBuilder object.

**`public`** [**`BuyOffersUriParameterBuilder`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder) **``** [**`WithAssetId`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a06aa361597137d4866df61aa4be3eaad)**`(int assetId)`**

`WithAssetId` sets the `_assetId` variable to the value of the `asset_id` parameter

#### Parameters

* `assetId` Shows the asset id in the offer.

#### Returns

The BuyOffersUriParameterBuilder object.

**`public`** [**`BuyOffersUriParameterBuilder`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder) **``** [**`WithMarketplace`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a0acfc5fa5151f97b7a759bf0f6a65e41)**`(string marketplace)`**

`WithMarketplace` sets the `marketplace` parameter

#### Parameters

* `marketplace` It filters by all sales where a certain marketplace is either taker or maker marketplace.

#### Returns

The BuyOffersUriParameterBuilder object.

**`public`** [**`BuyOffersUriParameterBuilder`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder) **``** [**`WithMakerMarketplace`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a96020e008cd1cee457aabaf5280794a8)**`(string makerMarketplace)`**

`WithMakerMarketplace` sets the `makerMarketplace` parameter

#### Parameters

* `makerMarketplace` separate multiple with ",".

#### Returns

The BuyOffersUriParameterBuilder object.

**`public`** [**`BuyOffersUriParameterBuilder`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder) **``** [**`WithTakerMarketplace`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a577a1385e2a2b6cb06229b562a19cfeb)**`(string takerMarketplace)`**

`WithTakerMarketplace` sets the `takerMarketplace` parameter

#### Parameters

* `takerMarketplace` separate multiple with ",".

#### Returns

The BuyOffersUriParameterBuilder object.

**`public`** [**`BuyOffersUriParameterBuilder`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder) **``** [**`WithSymbol`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1aa59e8f84dfa764e44d8fbb5ba236f8aa)**`(string symbol)`**

`WithSymbol` is a function that takes a string as a parameter and returns a `BuyOffersUriParameterBuilder` object.

#### Parameters

* `symbol` The symbol of the asset to get offers for.

#### Returns

The BuyOffersUriParameterBuilder object.

**`public`** [**`BuyOffersUriParameterBuilder`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder) **``** [**`WithSeller`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a67580fa4e652092ec5207b10c4147715)**`(string seller)`**

`WithSeller` sets the `seller` parameter

#### Parameters

* `seller` Filter by seller.

#### Returns

The BuyOffersUriParameterBuilder object.

**`public`** [**`BuyOffersUriParameterBuilder`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder) **``** [**`WithBuyer`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1adca4dcf4e63354d86c019a4d652422db)**`(string buyer)`**

`WithBuyer` sets the `buyer` parameter

#### Parameters

* `buyer` Filter by buyer.

#### Returns

The BuyOffersUriParameterBuilder object.

**`public`** [**`BuyOffersUriParameterBuilder`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder) **``** [**`WithMinPrice`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1ab8d0a121574368409cda1249e0297cc4)**`(int minPrice)`**

`WithMinPrice` sets the `_minPrice` variable to the value of the `minPrice` parameter

#### Parameters

* `minPrice` The lower price limit.

#### Returns

The BuyOffersUriParameterBuilder object.

**`public`** [**`BuyOffersUriParameterBuilder`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder) **``** [**`WithMaxPrice`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a4c1866db567c2caa324b9576c782ee0c)**`(int maxPrice)`**

`WithMaxPrice` sets the `_maxPrice` variable to the value of the `maxPrice` parameter

#### Parameters

* `maxPrice` The upper price limit.

#### Returns

The BuyOffersUriParameterBuilder object.

**`public`** [**`BuyOffersUriParameterBuilder`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder) **``** [**`WithMinTemplateMint`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1aa27c9a4b609dddf1fdc149a0a8d8926a)**`(int minTemplateMint)`**

`WithMinTemplateMint` sets the `_minTemplateMint` variable to the value of the `minTemplateMint` parameter

#### Parameters

* `minTemplateMint` Min template mint.

#### Returns

The BuyOffersUriParameterBuilder object.

**`public`** [**`BuyOffersUriParameterBuilder`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder) **``** [**`WithMaxTemplateMint`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a65d226b09278093614b67210908262b4)**`(int maxTemplateMint)`**

`WithMaxTemplateMint` sets the `_maxTemplateMint` variable to the value of the `maxTemplateMint` parameter

#### Parameters

* `maxTemplateMint` Max template mint.

#### Returns

The BuyOffersUriParameterBuilder object.

**`public`** [**`BuyOffersUriParameterBuilder`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder) **``** [**`WithOwner`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a543b2861cf67c93707354ed5f574e4ba)**`(string owner)`**

`WithOwner` sets the `owner` parameter

#### Parameters

* `owner` The owner parameter is used to filter the results. The owner parameter is a string that is matched against the account name.

#### Returns

The BuyOffersUriParameterBuilder object.

**`public`** [**`BuyOffersUriParameterBuilder`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder) **``** [**`WithBurned`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a55f2bbdb2f55004093a28de4dc1465ce)**`(bool burned)`**

`WithBurned` sets the `_burned` field to the value of the `burned` parameter

#### Parameters

* `burned` It filters for burned assets.

#### Returns

The BuyOffersUriParameterBuilder object.

**`public`** [**`BuyOffersUriParameterBuilder`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder) **``** [**`WithCollectionName`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a88bf9feb5fdf55504be6681f137e9b2e)**`(string collectionName)`**

`WithCollectionName` is a function that takes a string as a parameter and returns an `BuyOffersUriParameterBuilder` object

#### Parameters

* `collectionName` The name of the collection you want to query.

#### Returns

The BuyOffersUriParameterBuilder object.

**`public`** [**`BuyOffersUriParameterBuilder`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder) **``** [**`WithSchemaName`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1acfae2469372c85d4d047af0ab102c024)**`(string schemaName)`**

This function sets the schema name for the query.

#### Parameters

* `schemaName` The name of the schema to use.

#### Returns

The BuyOffersUriParameterBuilder object.

**`public`** [**`BuyOffersUriParameterBuilder`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder) **``** [**`WithTemplateId`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1aefefc1b4bc929a0d0d86bb88df7c374a)**`(string templateId)`**

It sets the value of the templateId variable.

#### Parameters

* `templateId` Results based on only transfers which cointain assets of template.

#### Returns

The BuyOffersUriParameterBuilder object.

**`public`** [**`BuyOffersUriParameterBuilder`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder) **``** [**`WithIsTransferable`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a3a6dbdabe529064b880b858dc5c34503)**`(bool isTransferable)`**

`WithIsTransferable` sets the `_isTransferable` field to the value of the `isTransferable` parameter

#### Parameters

* `isTransferable` The isTransferable parameter filters for transferable assets.

#### Returns

The BuyOffersUriParameterBuilder object.

**`public`** [**`BuyOffersUriParameterBuilder`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder) **``** [**`WithIsBurnable`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a4c0e3f9ee3375eab0889f3c7cba5d7d2)**`(bool isBurnable)`**

`WithIsBurnable` sets the `_isBurnable` field to the value of the `isBurnable` parameter

#### Parameters

* `isBurnable` Filters for burnable assets.

#### Returns

The BuyOffersUriParameterBuilder object.

**`public`** [**`BuyOffersUriParameterBuilder`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder) **``** [**`WithMatch`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a9f4a1cf45953d187e703042c0af612d6)**`(string match)`**

`WithMatch` sets the `match` parameter

#### Parameters

* `match` Search for input in asset name on template data.

#### Returns

The BuyOffersUriParameterBuilder object.

**`public`** [**`BuyOffersUriParameterBuilder`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder) **``** [**`WithCollectionBlacklist`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1aa6d0074266a4608e693590d8cb09a379)**`(string[] collectionBlacklist)`**

`WithCollectionBlacklist` is a function that takes an array of strings and returns an `BuyOffersUriParameterBuilder` object

#### Parameters

* `collectionBlacklist` A list of collections to exclude from the results.

#### Returns

The BuyOffersUriParameterBuilder object.

**`public`** [**`BuyOffersUriParameterBuilder`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder) **``** [**`WithCollectionWhitelist`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a94a9f8bbf2f3c6fcb338ff302c0716b5)**`(string[] collectionWhitelist)`**

`WithCollectionWhitelist` is a function that takes an array of strings and returns an `BuyOffersUriParameterBuilder` object

#### Parameters

* `collectionWhitelist` A list of collections to include in the response.

#### Returns

The BuyOffersUriParameterBuilder object.

**`public`** [**`BuyOffersUriParameterBuilder`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder) **``** [**`WithIds`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1aae8d094a1dbd124f37251b8001c8566f)**`(string[] ids)`**

This function takes an array of strings and joins them together with a comma.

#### Parameters

* `ids` A comma-separated list of account IDs.

#### Returns

The BuyOffersUriParameterBuilder object.

**`public`** [**`BuyOffersUriParameterBuilder`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder) **``** [**`WithLowerBound`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a5731767078d7979c27487fa37805a14e)**`(string lowerBound)`**

`WithLowerBound` sets the lower bound of the `account_ids` parameter

#### Parameters

* `lowerBound` The lower bound of the primary key

#### Returns

The BuyOffersUriParameterBuilder object.

**`public`** [**`BuyOffersUriParameterBuilder`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder) **``** [**`WithUpperBound`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a504058d26a60d5c83936a959bd1a7eaa)**`(string upperBound)`**

`WithUpperBound` sets the upper bound of the range of accounts to be returned

#### Parameters

* `upperBound` The upper bound of the primary key.

#### Returns

The BuyOffersUriParameterBuilder object.

**`public`** [**`BuyOffersUriParameterBuilder`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder) **``** [**`WithBefore`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a3e1122046db1740d5fd3274213d9eaf4)**`(int before)`**

`WithBefore` sets the `_before` variable to the value of the `before` parameter

#### Parameters

* `before` The previous values of the results to return.

#### Returns

The BuyOffersUriParameterBuilder object.

**`public`** [**`BuyOffersUriParameterBuilder`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder) **``** [**`WithAfter`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a3057e050bf7054593aa959fcdc028b1c)**`(int after)`**

`WithAfter` sets the `_after` variable to the value of the `after` parameter

#### Parameters

* `after` The later values of the results to return.

#### Returns

The BuyOffersUriParameterBuilder object.

**`public`** [**`BuyOffersUriParameterBuilder`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder) **``** [**`WithPage`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a7db8f1d764e3f81768b7d1820e13b1a3)**`(int page)`**

`WithPage` sets the `_page` variable to the value of the `page` parameter

#### Parameters

* `page` The page number of the results to return.

#### Returns

The BuyOffersUriParameterBuilder object.

**`public`** [**`BuyOffersUriParameterBuilder`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder) **``** [**`WithLimit`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a6fdc43968793eec37e4ed6b72b0dadff)**`(int limit)`**

`WithLimit` sets the `_limit` variable to the value of the `limit` parameter

#### Parameters

* `limit` The number of results to return.

#### Returns

The BuyOffersUriParameterBuilder object.

**`public`** [**`BuyOffersUriParameterBuilder`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder) **``** [**`WithOrder`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a5cba5a767a3d1174cf57cc6adf4917fc)**`(` ** [**`SortStrategy`**](AtomicMarketApiClient--Core.md) **`sorting)`**

This function sets the sort strategy for the query.

#### Parameters

* `SortStrategy`

#### Returns

The builder object itself.

**`public`** [**`BuyOffersUriParameterBuilder`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder) **``** [**`WithSort`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a00d65b0190e84f48ae1bbb611da90824)**`(string sort)`**

`WithSort` is a function that takes a string as a parameter and returns a `BuyOffersUriParameterBuilder` object

#### Parameters

* `sort` The sort order of the results.

#### Returns

A BuyOffersUriParameterBuilder object.

**`public string`** [**`Build`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a933ab72b517a9c3879ef78b27a2483bf)**`()`**

It builds a query string based on the parameters that have been set.

#### Returns

A string that contains the parameters for the query.

**`private string`** [**`_state`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a9577beb4165c1157d2e7f8f0ff065dde)

A private variable that is used to store the value of the state parameter.

**`private int?`** [**`_maxAssets`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1ae7334a7aa0ba955ac129865639f42b11)

A nullable integer specfying max assets per listing.

**`private int?`** [**`_minAssets`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a2787cd3c00b52a44e78964a580457204)

A nullable integer specfying min assets per listing.

**`private bool?`** [**`_showSellerContracts`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a162ce2b45598492d8053511dc8f5aaf0)

A nullable boolean specfying which sellerContracts to show.

**`private bool?`** [**`_contractWhitelist`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a3ee1d446d0a7dc9c0a1c68409eace1b0)

A nullable boolean specfying accounts with contracts.

**`private bool?`** [**`_sellerBlacklist`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1aeee97135fe3bd4392111f70290af4e0f)

A nullable boolean specfying listing from sellers.

**`private int?`** [**`_assetId`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a47b08a4420914a94240cbab6145522a5)

A nullable integer specifying the assetId.\


**`private string`** [**`_marketplace`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a9a3415610f1a82df64700fb430f6a369)

A private variable that is used to store the value of the maketplace parameter.

**`private string`** [**`_makerMarketplace`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1ae9ff2ea7ebb9f92f243fcf032613b846)

A private variable that is used to store the value of the makerMarketplace parameter.

**`private string`** [**`_takerMarketplace`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a1cf7d3f1334cd998d136622cb2333fd1)

A private variable that is used to store the value of the takerMarketplace parameter.

**`private string`** [**`_symbol`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a26c189f7d4c40f40f09ace24c4ccb945)

A private variable that is used to store the value of the symbol parameter.

**`private string`** [**`_seller`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a519a8fc19333a31cc8096bf4836f6101)

A private variable that is used to store the value of the seller parameter.

**`private string`** [**`_buyer`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a5f3e23f4ac11074e75a05a39c775f65c)

A private variable that is used to store the value of the buyer parameter.

**`private int?`** [**`_minPrice`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a966cc104ab35aeadc15268d2d9362555)

A nullable integer specifying the min price.\


**`private int?`** [**`_maxPrice`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a9e95e6e4dfcd570c9838dbac9b7fab7b)

A nullable integer specifying the max price.\


**`private int?`** [**`_minTemplateMint`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a480d12afcb85503c094e6c8001b5b46a)

A nullable integer specifying the minTemplateMint.\


**`private int?`** [**`_maxTemplateMint`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a6582a101a3e6766ec8fe47d29d5015b8)

A nullable integer specifying the maxTemplateMint.\


**`private string`** [**`_owner`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1ac091a560bcb5025581c60ad2b3e1f3bb)

A private variable that is used to store the value of the owner parameter.

**`private bool?`** [**`_burned`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a88325c0b6dc8cb4a570b2faaca18efa7)

A nullable boolean specfying burned assets.

**`private string`** [**`_collectionName`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a10ec2fa990c6478bc519b1e57e1ab2aa)

A private variable that is used to store the value of the collectionName parameter.

**`private string`** [**`_schemaName`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a2f9a887fd4dfcf60bfe4240a27085724)

A private variable that is used to store the value of the schemaName parameter.

**`private string`** [**`_templateId`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a06f918051fc7b04615854510caa85934)

A private variable that is used to store the value of the templateId parameter.

**`private bool?`** [**`_isTransferable`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a44e26246620bd9d4efa97c195a356672)

A nullable boolean specfying transferable assets.

**`private bool?`** [**`_isBurnable`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a6020acf0c5cb6f447cfe5ba95579e74d)

A nullable boolean specfying burnable assets.

**`private string`** [**`_match`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a5151210a8aa5d34ea523afbb052deb11)

A private variable that is used to store the value of the match parameter.

**`private string`** [**`_collectionBlacklist`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a11b225f8984dd9ab3ab5fcec261245c4)

A private variable that is used to store the value of the collectionBlacklist parameter.

**`private string`** [**`_collectionWhitelist`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a525c994ce1a584f4d763ac9d5c1b3cb5)

A private variable that is used to store the value of the collectionWhitelist parameter.

**`private string`** [**`_ids`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a2a9be788653dd13950b2f00bfce1970b)

A private variable that is used to store the value of the ids parameter.

**`private string`** [**`_lowerBound`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a47926893a523918c50a931018c47480d)

A private variable that is used to store the value of the lowerBound parameter.

**`private string`** [**`_upperBound`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1add1abf9a00e7bb81efb866424f4f34dc)

A private variable that is used to store the value of the upperBound parameter.

**`private int?`** [**`_before`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1aab4304cf3e09c19e898fe9224a0d723a)

A nullable integer specifying the previous timestamp.

**`private int?`** [**`_after`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1ae1483718c3d317e0b6046ada434c53ae)

A nullable integer specifying the next timestamp.\


**`private int?`** [**`_page`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a4dea13c8190a694fe00b24309b1814f8)

A nullable integer specifying the page.\


**`private int?`** [**`_limit`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a353a19a0da576dc8f69a61548a710395)

A nullable integer specifying the limit of returned values.

**`private`** [**`SortStrategy`**](AtomicMarketApiClient--Core.md)**`?`** [**`_sortStrategy`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a122ea78edfd15b44a8a547a7046b8651)

A nullable enum specifying the sortStrategy.

**`private string`** [**`_sort`**](AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_buy\_offers\_1\_1\_buy\_offers\_uri\_parameter\_builder\_1a3ac373edf19e058d7fae7f4c4ba485f4)

Declaring a private variable called \_sort.
