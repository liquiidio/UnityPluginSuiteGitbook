# StatsUriParameterBuilder

```
class AtomicMarketApiClient::Stats::StatsUriParameterBuilder
  : public IUriParameterBuilder
```

## Summary

| Members                                                                                                                                                                                                                                                                                                                                                                                                                                                     | Descriptions                                                                                                            |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------- |
| `public` [`StatsUriParameterBuilder`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder) `` [`WithState`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1afacbb9af5cc8692b6ff66fca36e9aea1)`(params` [`State`](AtomicMarketApiClient.md) `states)`         | `WithState` takes a list of `State`s and converts them to a comma separated string of integers                          |
| `public` [`StatsUriParameterBuilder`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder) `` [`WithMaxAssets`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a15ab3bb20b061bac3c1605caba51e7cb)`(int maxAssets)`                                           | `WithMaxAssets` sets the `_maxAssets` variable                                                                          |
| `public` [`StatsUriParameterBuilder`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder) `` [`WithMinAssets`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1abe332aabff2de5296414193d6c6a98a2)`(int minAssets)`                                           | `WithMinAssets` sets the `_minAssets` variable                                                                          |
| `public` [`StatsUriParameterBuilder`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder) `` [`WithShowSellerContracts`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1ac6d047c08898302bbca537d36f7c0d0a)`(bool showSellerContracts)`                      | `WithShowSellerContracts` sets the `_showSellerContracts` field to the value of the `showSellerContracts` parameter     |
| `public` [`StatsUriParameterBuilder`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder) `` [`WithContractWhitelist`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1ae10a102d57179cc7148d6aa2cf7907f5)`(bool contractWhitelist)`                          | `WithContractWhitelist` sets the `_contractWhitelist` field to the value of the `contractWhitelist` parameter           |
| `public` [`StatsUriParameterBuilder`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder) `` [`WithSellerBlacklist`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a18ef0454b005b5876dbf81489908363f)`(bool sellerBlacklist)`                              | `WithSellerBlacklist` sets the `_sellerBlacklist` field to the value of the `sellerBlacklist` parameter                 |
| `public` [`StatsUriParameterBuilder`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder) `` [`WithAssetId`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a6dda80efe0b76fbf65cd12fac57a5666)`(int assetId)`                                               | `WithAssetId` sets the `_assetId` variable to the value of the `asset_id` parameter                                     |
| `public` [`StatsUriParameterBuilder`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder) `` [`WithMarketplace`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a4a0310a73e8d27779f290cabae22ffdc)`(string marketplace)`                                    | `WithMarketplace` sets the `marketplace` parameter                                                                      |
| `public` [`StatsUriParameterBuilder`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder) `` [`WithMakerMarketplace`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1aab2b3ec3ff80a21ddf5d4696346aafdf)`(string makerMarketplace)`                          | `WithMakerMarketplace` sets the `makerMarketplace` parameter                                                            |
| `public` [`StatsUriParameterBuilder`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder) `` [`WithTakerMarketplace`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a02b3344ed345896a67911e63013793e9)`(string takerMarketplace)`                          | `WithTakerMarketplace` sets the `takerMarketplace` parameter                                                            |
| `public` [`StatsUriParameterBuilder`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder) `` [`WithSymbol`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1ab9f6a7d45ff21a2da764fcba6e1f853e)`(string symbol)`                                              | `WithSymbol` sets the `symbol` parameter                                                                                |
| `public` [`StatsUriParameterBuilder`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder) `` [`WithSeller`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a3f165107f0ef895935684d0bf88bc13a)`(string seller)`                                              | `WithSeller` sets the `seller` parameter                                                                                |
| `public` [`StatsUriParameterBuilder`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder) `` [`WithBuyer`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a53a82ddfd3331e1708660082f9463b25)`(string buyer)`                                                | `WithBuyer` sets the `buyer` parameter                                                                                  |
| `public` [`StatsUriParameterBuilder`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder) `` [`WithMinPrice`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a433a457c4efb48b247104b2f9271a46c)`(int minPrice)`                                             | `WithMinPrice` sets the `_minPrice` variable to the value of the `minPrice` parameter                                   |
| `public` [`StatsUriParameterBuilder`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder) `` [`WithMaxPrice`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a543e4790854676957ca473948aaacc99)`(int maxPrice)`                                             | `WithMaxPrice` sets the `_maxPrice` variable to the value of the `maxPrice` parameter                                   |
| `public` [`StatsUriParameterBuilder`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder) `` [`WithMinTemplateMint`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1ab3b33d8f99b126b15b1137d2988e05a2)`(int minTemplateMint)`                               | `WithMinTemplateMint` sets the `_minTemplateMint` variable to the value of the `minTemplateMint` parameter              |
| `public` [`StatsUriParameterBuilder`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder) `` [`WithMaxTemplateMint`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a3b03a397cac0850cc9dbba81b5fb9db5)`(int maxTemplateMint)`                               | `WithMaxTemplateMint` sets the `_maxTemplateMint` variable to the value of the `maxTemplateMint` parameter              |
| `public` [`StatsUriParameterBuilder`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder) `` [`WithOwner`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a61619eeb67d9e9fcbdc6f2ab8799f8d9)`(string owner)`                                                | `WithOwner` sets the `owner` parameter                                                                                  |
| `public` [`StatsUriParameterBuilder`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder) `` [`WithBurned`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a557bd448fc212b7f2b5dd75a6fc05dc3)`(bool burned)`                                                | `WithBurned` sets the `_burned` field to the value of the `burned` parameter                                            |
| `public` [`StatsUriParameterBuilder`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder) `` [`WithCollectionName`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a65cb6725dba73c88c48690815e7a8a68)`(string collectionName)`                              | `WithCollectionName` is a function that takes a string as a parameter and returns a `StatsUriParameterBuilder` object.  |
| `public` [`StatsUriParameterBuilder`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder) `` [`WithSchemaName`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1af94aa92850e03847192925b77e5a796b)`(string schemaName)`                                      | This function sets the schema name for the query.                                                                       |
| `public` [`StatsUriParameterBuilder`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder) `` [`WithTemplateId`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a482ceebdcabb8eaa56c93b504e31d863)`(string templateId)`                                      | It sets the value of the templateId variable.                                                                           |
| `public` [`StatsUriParameterBuilder`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder) `` [`WithIsTransferable`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a99c34c35a6f6b4fbcb772ceb45e8e3fd)`(bool isTransferable)`                                | `WithIsTransferable` sets the `_isTransferable` field to the value of the `isTransferable` parameter                    |
| `public` [`StatsUriParameterBuilder`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder) `` [`WithIsBurnable`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a1f71e8c25977c67ccb2c98168320a257)`(bool isBurnable)`                                        | `WithIsBurnable` sets the `_isBurnable` field to the value of the `isBurnable` parameter                                |
| `public` [`StatsUriParameterBuilder`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder) `` [`WithMatch`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1ae87b6d9717f1a5fb6ded7c6cb9758f09)`(string match)`                                                | `WithMatch` sets the `match` parameter                                                                                  |
| `public` [`StatsUriParameterBuilder`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder) `` [`WithCollectionBlacklist`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a12e635a0d314098a31b1c49e1f7d2919)`(string[] collectionBlacklist)`                  | `WithCollectionBlacklist` is a function that takes an array of strings and returns an `StatsUriParameterBuilder` object |
| `public` [`StatsUriParameterBuilder`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder) `` [`WithCollectionWhitelist`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1ac8a4ac66ce03f633c94e5e95c1eeb724)`(string[] collectionWhitelist)`                  | `WithCollectionWhitelist` is a function that takes an array of strings and returns an `StatsUriParameterBuilder` object |
| `public` [`StatsUriParameterBuilder`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder) `` [`WithIds`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a4474d23a6cc148c33a902aa6345a606b)`(string[] ids)`                                                  | This function takes an array of strings and joins them together with a comma.                                           |
| `public` [`StatsUriParameterBuilder`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder) `` [`WithLowerBound`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a1d0e72cbe1d21811a5aa90591586fc63)`(string lowerBound)`                                      | `WithLowerBound` sets the lower bound of the `account_ids` parameter                                                    |
| `public` [`StatsUriParameterBuilder`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder) `` [`WithUpperBound`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1aabdbca85a09d95c59a41e934a3e3657d)`(string upperBound)`                                      | `WithUpperBound` sets the upper bound of the range of accounts to be returned                                           |
| `public` [`StatsUriParameterBuilder`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder) `` [`WithBefore`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a87fd7ec0d121029a35ae311d3a0e8eb4)`(int before)`                                                 | `WithBefore` sets the `_before` variable to the value of the `before` parameter                                         |
| `public` [`StatsUriParameterBuilder`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder) `` [`WithAfter`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1aa0fa14716037c21d14363e4f177e8b1f)`(int after)`                                                   | `WithAfter` sets the `_after` variable to the value of the `after` parameter                                            |
| `public` [`StatsUriParameterBuilder`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder) `` [`WithPage`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a58e92b45338b6cb8adfc0da4ceb1a8dd)`(int page)`                                                     | `WithPage` sets the `_page` variable to the value of the `page` parameter                                               |
| `public` [`StatsUriParameterBuilder`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder) `` [`WithLimit`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1ae53959225ddb917572ac9cfc06ffafd3)`(int limit)`                                                   | `WithLimit` sets the `_limit` variable to the value of the `limit` parameter                                            |
| `public` [`StatsUriParameterBuilder`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder) `` [`WithOrder`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a6494b12ba6819baaf471db2f0a20bc9e)`(` [`SortStrategy`](AtomicMarketApiClient--Core.md) `sorting)` | This function sets the sort strategy for the query.                                                                     |
| `public` [`StatsUriParameterBuilder`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder) `` [`WithSort`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a4f4b753e9568dc813f6c9353d0defc35)`(string sort)`                                                  | `WithSort` is a function that takes a string as an argument and returns a `StatsUriParameterBuilder` object.            |
| `public string` [`Build`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a933ab72b517a9c3879ef78b27a2483bf)`()`                                                                                                                                                                                                                                          | It builds a query string based on the parameters that have been set.                                                    |
| `private string` [`_state`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a9577beb4165c1157d2e7f8f0ff065dde)                                                                                                                                                                                                                                            | A private variable that is used to store the value of the state parameter.                                              |
| `private int?` [`_maxAssets`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1ae7334a7aa0ba955ac129865639f42b11)                                                                                                                                                                                                                                          | A nullable integer specfying max assets per listing.                                                                    |
| `private int?` [`_minAssets`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a2787cd3c00b52a44e78964a580457204)                                                                                                                                                                                                                                          | A nullable integer specfying min assets per listing.                                                                    |
| `private bool?` [`_showSellerContracts`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a162ce2b45598492d8053511dc8f5aaf0)                                                                                                                                                                                                                               | A nullable boolean specfying which sellerContracts to show.                                                             |
| `private bool?` [`_contractWhitelist`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a3ee1d446d0a7dc9c0a1c68409eace1b0)                                                                                                                                                                                                                                 | A nullable boolean specfying accounts with contracts.                                                                   |
| `private bool?` [`_sellerBlacklist`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1aeee97135fe3bd4392111f70290af4e0f)                                                                                                                                                                                                                                   | A nullable boolean specfying listing from sellers.                                                                      |
| `private int?` [`_assetId`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a47b08a4420914a94240cbab6145522a5)                                                                                                                                                                                                                                            | <p>A nullable integer specifying the assetId.<br></p>                                                                   |
| `private string` [`_marketplace`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a9a3415610f1a82df64700fb430f6a369)                                                                                                                                                                                                                                      | A private variable that is used to store the value of the maketplace parameter.                                         |
| `private string` [`_makerMarketplace`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1ae9ff2ea7ebb9f92f243fcf032613b846)                                                                                                                                                                                                                                 | A private variable that is used to store the value of the makerMarketplace parameter.                                   |
| `private string` [`_takerMarketplace`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a1cf7d3f1334cd998d136622cb2333fd1)                                                                                                                                                                                                                                 | A private variable that is used to store the value of the takerMarketplace parameter.                                   |
| `private string` [`_symbol`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a26c189f7d4c40f40f09ace24c4ccb945)                                                                                                                                                                                                                                           | A private variable that is used to store the value of the symbol parameter.                                             |
| `private string` [`_seller`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a519a8fc19333a31cc8096bf4836f6101)                                                                                                                                                                                                                                           | A private variable that is used to store the value of the seller parameter.                                             |
| `private string` [`_buyer`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a5f3e23f4ac11074e75a05a39c775f65c)                                                                                                                                                                                                                                            | A private variable that is used to store the value of the buyer parameter.                                              |
| `private int?` [`_minPrice`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a966cc104ab35aeadc15268d2d9362555)                                                                                                                                                                                                                                           | <p>A nullable integer specifying the min price.<br></p>                                                                 |
| `private int?` [`_maxPrice`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a9e95e6e4dfcd570c9838dbac9b7fab7b)                                                                                                                                                                                                                                           | <p>A nullable integer specifying the max price.<br></p>                                                                 |
| `private int?` [`_minTemplateMint`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a480d12afcb85503c094e6c8001b5b46a)                                                                                                                                                                                                                                    | <p>A nullable integer specifying the minTemplateMint.<br></p>                                                           |
| `private int?` [`_maxTemplateMint`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a6582a101a3e6766ec8fe47d29d5015b8)                                                                                                                                                                                                                                    | <p>A nullable integer specifying the maxTemplateMint.<br></p>                                                           |
| `private string` [`_owner`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1ac091a560bcb5025581c60ad2b3e1f3bb)                                                                                                                                                                                                                                            | A private variable that is used to store the value of the owner parameter.                                              |
| `private bool?` [`_burned`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a88325c0b6dc8cb4a570b2faaca18efa7)                                                                                                                                                                                                                                            | A nullable boolean specfying burned assets.                                                                             |
| `private string` [`_collectionName`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a10ec2fa990c6478bc519b1e57e1ab2aa)                                                                                                                                                                                                                                   | A private variable that is used to store the value of the collectionName parameter.                                     |
| `private string` [`_schemaName`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a2f9a887fd4dfcf60bfe4240a27085724)                                                                                                                                                                                                                                       | A private variable that is used to store the value of the schemaName parameter.                                         |
| `private string` [`_templateId`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a06f918051fc7b04615854510caa85934)                                                                                                                                                                                                                                       | A private variable that is used to store the value of the templateId parameter.                                         |
| `private bool?` [`_isTransferable`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a44e26246620bd9d4efa97c195a356672)                                                                                                                                                                                                                                    | A nullable boolean specfying transferable assets.                                                                       |
| `private bool?` [`_isBurnable`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a6020acf0c5cb6f447cfe5ba95579e74d)                                                                                                                                                                                                                                        | A nullable boolean specfying burnable assets.                                                                           |
| `private string` [`_match`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a5151210a8aa5d34ea523afbb052deb11)                                                                                                                                                                                                                                            | A private variable that is used to store the value of the match parameter.                                              |
| `private string` [`_collectionBlacklist`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a11b225f8984dd9ab3ab5fcec261245c4)                                                                                                                                                                                                                              | A private variable that is used to store the value of the collectionBlacklist parameter.                                |
| `private string` [`_collectionWhitelist`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a525c994ce1a584f4d763ac9d5c1b3cb5)                                                                                                                                                                                                                              | A private variable that is used to store the value of the collectionWhitelist parameter.                                |
| `private string` [`_ids`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a2a9be788653dd13950b2f00bfce1970b)                                                                                                                                                                                                                                              | A private variable that is used to store the value of the ids parameter.                                                |
| `private string` [`_lowerBound`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a47926893a523918c50a931018c47480d)                                                                                                                                                                                                                                       | A private variable that is used to store the value of the lowerBound parameter.                                         |
| `private string` [`_upperBound`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1add1abf9a00e7bb81efb866424f4f34dc)                                                                                                                                                                                                                                       | A private variable that is used to store the value of the upperBound parameter.                                         |
| `private int?` [`_before`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1aab4304cf3e09c19e898fe9224a0d723a)                                                                                                                                                                                                                                             | A nullable integer specifying the previous timestamp.                                                                   |
| `private int?` [`_after`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1ae1483718c3d317e0b6046ada434c53ae)                                                                                                                                                                                                                                              | <p>A nullable integer specifying the next timestamp.<br></p>                                                            |
| `private int?` [`_page`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a4dea13c8190a694fe00b24309b1814f8)                                                                                                                                                                                                                                               | <p>A nullable integer specifying the page.<br></p>                                                                      |
| `private int?` [`_limit`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a353a19a0da576dc8f69a61548a710395)                                                                                                                                                                                                                                              | A nullable integer specifying the limit of returned values.                                                             |
| `private` [`SortStrategy`](AtomicMarketApiClient--Core.md)`?` [`_sortStrategy`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a122ea78edfd15b44a8a547a7046b8651)                                                                                                                                                                                        | A nullable enum specifying the sortStrategy.                                                                            |
| `private string` [`_sort`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a3ac373edf19e058d7fae7f4c4ba485f4)                                                                                                                                                                                                                                             | Declaring a private variable called \_sort.                                                                             |

## Members

**`public`** [**`StatsUriParameterBuilder`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder) **``** [**`WithState`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1afacbb9af5cc8692b6ff66fca36e9aea1)**`(params`** [**`State`**](AtomicMarketApiClient.md) **`states)`**

`WithState` takes a list of `State`s and converts them to a comma separated string of integers

#### Returns

A StatsUriParameterBuilder object.

**`public`** [**`StatsUriParameterBuilder`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder) **``** [**`WithMaxAssets`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a15ab3bb20b061bac3c1605caba51e7cb)**`(int maxAssets)`**

`WithMaxAssets` sets the `_maxAssets` variable

#### Parameters

* `maxAssets` Max assets per listing returns.

#### Returns

The StatssUriParameterBuilder object.

**`public`** [**`StatsUriParameterBuilder`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder) **``** [**`WithMinAssets`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1abe332aabff2de5296414193d6c6a98a2)**`(int minAssets)`**

`WithMinAssets` sets the `_minAssets` variable

#### Parameters

* `minAssets` Min assets per listing returns.

#### Returns

The StatsUriParameterBuilder object.

**`public`** [**`StatsUriParameterBuilder`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder) **``** [**`WithShowSellerContracts`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1ac6d047c08898302bbca537d36f7c0d0a)**`(bool showSellerContracts)`**

`WithShowSellerContracts` sets the `_showSellerContracts` field to the value of the `showSellerContracts` parameter

#### Parameters

* `showSellerContracts` If false,no seller contracts are shown except if they are in contract whitelist.

#### Returns

The StatsUriParameterBuilder object.

**`public`** [**`StatsUriParameterBuilder`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder) **``** [**`WithContractWhitelist`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1ae10a102d57179cc7148d6aa2cf7907f5)**`(bool contractWhitelist)`**

`WithContractWhitelist` sets the `_contractWhitelist` field to the value of the `contractWhitelist` parameter

#### Parameters

* `contractWhitelist` Shows accounts even if they are contracts.

#### Returns

The StatsUriParameterBuilder object.

**`public`** [**`StatsUriParameterBuilder`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder) **``** [**`WithSellerBlacklist`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a18ef0454b005b5876dbf81489908363f)**`(bool sellerBlacklist)`**

`WithSellerBlacklist` sets the `_sellerBlacklist` field to the value of the `sellerBlacklist` parameter

#### Parameters

* `sellerBlacklist` Doesnot show listing from sellers.

#### Returns

The StatsUriParameterBuilder object.

**`public`** [**`StatsUriParameterBuilder`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder) **``** [**`WithAssetId`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a6dda80efe0b76fbf65cd12fac57a5666)**`(int assetId)`**

`WithAssetId` sets the `_assetId` variable to the value of the `asset_id` parameter

#### Parameters

* `assetId` Shows the asset id in the offer.

#### Returns

The StatsUriParameterBuilder object.

**`public`** [**`StatsUriParameterBuilder`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder) **``** [**`WithMarketplace`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a4a0310a73e8d27779f290cabae22ffdc)**`(string marketplace)`**

`WithMarketplace` sets the `marketplace` parameter

#### Parameters

* `marketplace` It filters by all sales where a certain marketplace is either taker or maker marketplace.

#### Returns

The StatsUriParameterBuilder object.

**`public`** [**`StatsUriParameterBuilder`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder) **``** [**`WithMakerMarketplace`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1aab2b3ec3ff80a21ddf5d4696346aafdf)**`(string makerMarketplace)`**

`WithMakerMarketplace` sets the `makerMarketplace` parameter

#### Parameters

* `makerMarketplace` separate multiple with ",".

#### Returns

The StatsUriParameterBuilder object.

**`public`** [**`StatsUriParameterBuilder`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder) **``** [**`WithTakerMarketplace`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a02b3344ed345896a67911e63013793e9)**`(string takerMarketplace)`**

`WithTakerMarketplace` sets the `takerMarketplace` parameter

#### Parameters

* `takerMarketplace` separate multiple with ",".

#### Returns

The StatsUriParameterBuilder object.

**`public`** [**`StatsUriParameterBuilder`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder) **``** [**`WithSymbol`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1ab9f6a7d45ff21a2da764fcba6e1f853e)**`(string symbol)`**

`WithSymbol` sets the `symbol` parameter

#### Parameters

* `symbol` Token symbol.

#### Returns

The StatsUriParameterBuilder object.

**`public`** [**`StatsUriParameterBuilder`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder) **``** [**`WithSeller`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a3f165107f0ef895935684d0bf88bc13a)**`(string seller)`**

`WithSeller` sets the `seller` parameter

#### Parameters

* `seller` Filter by seller.

#### Returns

The StatsUriParameterBuilder object.

**`public`** [**`StatsUriParameterBuilder`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder) **``** [**`WithBuyer`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a53a82ddfd3331e1708660082f9463b25)**`(string buyer)`**

`WithBuyer` sets the `buyer` parameter

#### Parameters

* `buyer` Filter by buyer.

#### Returns

The StatsUriParameterBuilder object.

**`public`** [**`StatsUriParameterBuilder`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder) **``** [**`WithMinPrice`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a433a457c4efb48b247104b2f9271a46c)**`(int minPrice)`**

`WithMinPrice` sets the `_minPrice` variable to the value of the `minPrice` parameter

#### Parameters

* `minPrice` The lower price limit.

#### Returns

The StatsUriParameterBuilder object.

**`public`** [**`StatsUriParameterBuilder`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder) **``** [**`WithMaxPrice`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a543e4790854676957ca473948aaacc99)**`(int maxPrice)`**

`WithMaxPrice` sets the `_maxPrice` variable to the value of the `maxPrice` parameter

#### Parameters

* `maxPrice` The upper price limit.

#### Returns

The StatsUriParameterBuilder object.

**`public`** [**`StatsUriParameterBuilder`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder) **``** [**`WithMinTemplateMint`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1ab3b33d8f99b126b15b1137d2988e05a2)**`(int minTemplateMint)`**

`WithMinTemplateMint` sets the `_minTemplateMint` variable to the value of the `minTemplateMint` parameter

#### Parameters

* `minTemplateMint` Min template mint.

#### Returns

The StatsUriParameterBuilder object.

**`public`** [**`StatsUriParameterBuilder`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder) **``** [**`WithMaxTemplateMint`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a3b03a397cac0850cc9dbba81b5fb9db5)**`(int maxTemplateMint)`**

`WithMaxTemplateMint` sets the `_maxTemplateMint` variable to the value of the `maxTemplateMint` parameter

#### Parameters

* `maxTemplateMint` Max template mint.

#### Returns

The StatsUriParameterBuilder object.

**`public`** [**`StatsUriParameterBuilder`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder) **``** [**`WithOwner`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a61619eeb67d9e9fcbdc6f2ab8799f8d9)**`(string owner)`**

`WithOwner` sets the `owner` parameter

#### Parameters

* `owner` The owner parameter is used to filter the results. The owner parameter is a string that is matched against the account name.

#### Returns

The StatsUriParameterBuilder object.

**`public`** [**`StatsUriParameterBuilder`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder) **``** [**`WithBurned`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a557bd448fc212b7f2b5dd75a6fc05dc3)**`(bool burned)`**

`WithBurned` sets the `_burned` field to the value of the `burned` parameter

#### Parameters

* `burned` It filters for burned assets.

#### Returns

The StatsUriParameterBuilder object.

**`public`** [**`StatsUriParameterBuilder`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder) **``** [**`WithCollectionName`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a65cb6725dba73c88c48690815e7a8a68)**`(string collectionName)`**

`WithCollectionName` is a function that takes a string as a parameter and returns a `StatsUriParameterBuilder` object.

#### Parameters

* `collectionName` The name of the collection you want to get stats for.

#### Returns

The StatsUriParameterBuilder object.

**`public`** [**`StatsUriParameterBuilder`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder) **``** [**`WithSchemaName`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1af94aa92850e03847192925b77e5a796b)**`(string schemaName)`**

This function sets the schema name for the query.

#### Parameters

* `schemaName` The name of the schema to use.

#### Returns

The StatsUriParameterBuilder object.

**`public`** [**`StatsUriParameterBuilder`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder) **``** [**`WithTemplateId`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a482ceebdcabb8eaa56c93b504e31d863)**`(string templateId)`**

It sets the value of the templateId variable.

#### Parameters

* `templateId` Results based on only transfers which cointain assets of template.

#### Returns

The StatsUriParameterBuilder object.

**`public`** [**`StatsUriParameterBuilder`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder) **``** [**`WithIsTransferable`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a99c34c35a6f6b4fbcb772ceb45e8e3fd)**`(bool isTransferable)`**

`WithIsTransferable` sets the `_isTransferable` field to the value of the `isTransferable` parameter

#### Parameters

* `isTransferable` The isTransferable parameter filters for transferable assets.

#### Returns

The StatsUriParameterBuilder object.

**`public`** [**`StatsUriParameterBuilder`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder) **``** [**`WithIsBurnable`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a1f71e8c25977c67ccb2c98168320a257)**`(bool isBurnable)`**

`WithIsBurnable` sets the `_isBurnable` field to the value of the `isBurnable` parameter

#### Parameters

* `isBurnable` Filters for burnable assets.

#### Returns

The StatsUriParameterBuilder object.

**`public`** [**`StatsUriParameterBuilder`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder) **``** [**`WithMatch`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1ae87b6d9717f1a5fb6ded7c6cb9758f09)**`(string match)`**

`WithMatch` sets the `match` parameter

#### Parameters

* `match` Search for input in asset name on template data.

#### Returns

The StatsUriParameterBuilder object.

**`public`** [**`StatsUriParameterBuilder`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder) **``** [**`WithCollectionBlacklist`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a12e635a0d314098a31b1c49e1f7d2919)**`(string[] collectionBlacklist)`**

`WithCollectionBlacklist` is a function that takes an array of strings and returns an `StatsUriParameterBuilder` object

#### Parameters

* `collectionBlacklist` A list of collections to exclude from the results.

#### Returns

The StatsUriParameterBuilder object.

**`public`** [**`StatsUriParameterBuilder`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder) **``** [**`WithCollectionWhitelist`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1ac8a4ac66ce03f633c94e5e95c1eeb724)**`(string[] collectionWhitelist)`**

`WithCollectionWhitelist` is a function that takes an array of strings and returns an `StatsUriParameterBuilder` object

#### Parameters

* `collectionWhitelist` A list of collections to include in the response.

#### Returns

The StatsUriParameterBuilder object.

**`public`** [**`StatsUriParameterBuilder`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder) **``** [**`WithIds`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a4474d23a6cc148c33a902aa6345a606b)**`(string[] ids)`**

This function takes an array of strings and joins them together with a comma.

#### Parameters

* `ids` A comma-separated list of account IDs.

#### Returns

The StatsUriParameterBuilder object.

**`public`** [**`StatsUriParameterBuilder`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder) **``** [**`WithLowerBound`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a1d0e72cbe1d21811a5aa90591586fc63)**`(string lowerBound)`**

`WithLowerBound` sets the lower bound of the `account_ids` parameter

#### Parameters

* `lowerBound` The lower bound of the primary key

#### Returns

The StatsUriParameterBuilder object.

**`public`** [**`StatsUriParameterBuilder`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder) **``** [**`WithUpperBound`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1aabdbca85a09d95c59a41e934a3e3657d)**`(string upperBound)`**

`WithUpperBound` sets the upper bound of the range of accounts to be returned

#### Parameters

* `upperBound` The upper bound of the primary key.

#### Returns

The StatsUriParameterBuilder object.

**`public`** [**`StatsUriParameterBuilder`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder) **``** [**`WithBefore`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a87fd7ec0d121029a35ae311d3a0e8eb4)**`(int before)`**

`WithBefore` sets the `_before` variable to the value of the `before` parameter

#### Parameters

* `before` The previous values of the results to return.

#### Returns

The StatsUriParameterBuilder object.

**`public`** [**`StatsUriParameterBuilder`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder) **``** [**`WithAfter`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1aa0fa14716037c21d14363e4f177e8b1f)**`(int after)`**

`WithAfter` sets the `_after` variable to the value of the `after` parameter

#### Parameters

* `after` The later values of the results to return.

#### Returns

The StatsUriParameterBuilder object.

**`public`** [**`StatsUriParameterBuilder`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder) **``** [**`WithPage`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a58e92b45338b6cb8adfc0da4ceb1a8dd)**`(int page)`**

`WithPage` sets the `_page` variable to the value of the `page` parameter

#### Parameters

* `page` The page number of the results to return.

#### Returns

The StatsUriParameterBuilder object.

**`public`** [**`StatsUriParameterBuilder`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder) **``** [**`WithLimit`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1ae53959225ddb917572ac9cfc06ffafd3)**`(int limit)`**

`WithLimit` sets the `_limit` variable to the value of the `limit` parameter

#### Parameters

* `limit` The number of results to return.

#### Returns

The StatsUriParameterBuilder object.

**`public`** [**`StatsUriParameterBuilder`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder) **``** [**`WithOrder`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a6494b12ba6819baaf471db2f0a20bc9e)**`(` ** [**`SortStrategy`**](AtomicMarketApiClient--Core.md) **`sorting)`**

This function sets the sort strategy for the query.

#### Parameters

* `SortStrategy`

#### Returns

The builder object itself.

**`public`** [**`StatsUriParameterBuilder`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder) **``** [**`WithSort`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a4f4b753e9568dc813f6c9353d0defc35)**`(string sort)`**

`WithSort` is a function that takes a string as an argument and returns a `StatsUriParameterBuilder` object.

#### Parameters

* `sort` The field to sort by.

#### Returns

A StatsUriParameterBuilder object.

**`public string`** [**`Build`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a933ab72b517a9c3879ef78b27a2483bf)**`()`**

It builds a query string based on the parameters that have been set.

#### Returns

A string that contains the parameters for the query.

**`private string`** [**`_state`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a9577beb4165c1157d2e7f8f0ff065dde)

A private variable that is used to store the value of the state parameter.

**`private int?`** [**`_maxAssets`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1ae7334a7aa0ba955ac129865639f42b11)

A nullable integer specfying max assets per listing.

**`private int?`** [**`_minAssets`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a2787cd3c00b52a44e78964a580457204)

A nullable integer specfying min assets per listing.

**`private bool?`** [**`_showSellerContracts`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a162ce2b45598492d8053511dc8f5aaf0)

A nullable boolean specfying which sellerContracts to show.

**`private bool?`** [**`_contractWhitelist`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a3ee1d446d0a7dc9c0a1c68409eace1b0)

A nullable boolean specfying accounts with contracts.

**`private bool?`** [**`_sellerBlacklist`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1aeee97135fe3bd4392111f70290af4e0f)

A nullable boolean specfying listing from sellers.

**`private int?`** [**`_assetId`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a47b08a4420914a94240cbab6145522a5)

A nullable integer specifying the assetId.\


**`private string`** [**`_marketplace`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a9a3415610f1a82df64700fb430f6a369)

A private variable that is used to store the value of the maketplace parameter.

**`private string`** [**`_makerMarketplace`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1ae9ff2ea7ebb9f92f243fcf032613b846)

A private variable that is used to store the value of the makerMarketplace parameter.

**`private string`** [**`_takerMarketplace`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a1cf7d3f1334cd998d136622cb2333fd1)

A private variable that is used to store the value of the takerMarketplace parameter.

**`private string`** [**`_symbol`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a26c189f7d4c40f40f09ace24c4ccb945)

A private variable that is used to store the value of the symbol parameter.

**`private string`** [**`_seller`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a519a8fc19333a31cc8096bf4836f6101)

A private variable that is used to store the value of the seller parameter.

**`private string`** [**`_buyer`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a5f3e23f4ac11074e75a05a39c775f65c)

A private variable that is used to store the value of the buyer parameter.

**`private int?`** [**`_minPrice`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a966cc104ab35aeadc15268d2d9362555)

A nullable integer specifying the min price.\


**`private int?`** [**`_maxPrice`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a9e95e6e4dfcd570c9838dbac9b7fab7b)

A nullable integer specifying the max price.\


**`private int?`** [**`_minTemplateMint`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a480d12afcb85503c094e6c8001b5b46a)

A nullable integer specifying the minTemplateMint.\


**`private int?`** [**`_maxTemplateMint`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a6582a101a3e6766ec8fe47d29d5015b8)

A nullable integer specifying the maxTemplateMint.\


**`private string`** [**`_owner`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1ac091a560bcb5025581c60ad2b3e1f3bb)

A private variable that is used to store the value of the owner parameter.

**`private bool?`** [**`_burned`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a88325c0b6dc8cb4a570b2faaca18efa7)

A nullable boolean specfying burned assets.

**`private string`** [**`_collectionName`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a10ec2fa990c6478bc519b1e57e1ab2aa)

A private variable that is used to store the value of the collectionName parameter.

**`private string`** [**`_schemaName`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a2f9a887fd4dfcf60bfe4240a27085724)

A private variable that is used to store the value of the schemaName parameter.

**`private string`** [**`_templateId`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a06f918051fc7b04615854510caa85934)

A private variable that is used to store the value of the templateId parameter.

**`private bool?`** [**`_isTransferable`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a44e26246620bd9d4efa97c195a356672)

A nullable boolean specfying transferable assets.

**`private bool?`** [**`_isBurnable`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a6020acf0c5cb6f447cfe5ba95579e74d)

A nullable boolean specfying burnable assets.

**`private string`** [**`_match`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a5151210a8aa5d34ea523afbb052deb11)

A private variable that is used to store the value of the match parameter.

**`private string`** [**`_collectionBlacklist`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a11b225f8984dd9ab3ab5fcec261245c4)

A private variable that is used to store the value of the collectionBlacklist parameter.

**`private string`** [**`_collectionWhitelist`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a525c994ce1a584f4d763ac9d5c1b3cb5)

A private variable that is used to store the value of the collectionWhitelist parameter.

**`private string`** [**`_ids`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a2a9be788653dd13950b2f00bfce1970b)

A private variable that is used to store the value of the ids parameter.

**`private string`** [**`_lowerBound`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a47926893a523918c50a931018c47480d)

A private variable that is used to store the value of the lowerBound parameter.

**`private string`** [**`_upperBound`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1add1abf9a00e7bb81efb866424f4f34dc)

A private variable that is used to store the value of the upperBound parameter.

**`private int?`** [**`_before`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1aab4304cf3e09c19e898fe9224a0d723a)

A nullable integer specifying the previous timestamp.

**`private int?`** [**`_after`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1ae1483718c3d317e0b6046ada434c53ae)

A nullable integer specifying the next timestamp.\


**`private int?`** [**`_page`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a4dea13c8190a694fe00b24309b1814f8)

A nullable integer specifying the page.\


**`private int?`** [**`_limit`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a353a19a0da576dc8f69a61548a710395)

A nullable integer specifying the limit of returned values.

**`private`** [**`SortStrategy`**](AtomicMarketApiClient--Core.md)**`?`** [**`_sortStrategy`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a122ea78edfd15b44a8a547a7046b8651)

A nullable enum specifying the sortStrategy.

**`private string`** [**`_sort`**](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md#class\_atomic\_market\_api\_client\_1\_1\_stats\_1\_1\_stats\_uri\_parameter\_builder\_1a3ac373edf19e058d7fae7f4c4ba485f4)

Declaring a private variable called \_sort.
