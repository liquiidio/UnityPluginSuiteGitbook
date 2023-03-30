# AssetDto

## Summary

| Members                                                                                                                                                                                                                                                                                                                             | Descriptions                           |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------- |
| `class` [`BackedTokensDto`](AtomicMarketApiClient--Sales--SaleDto--DataDto--AssetDto--BackedTokensDto.md)                                                                                                                                                                                                                           |                                        |
| `class` [`SchemaDto`](AtomicMarketApiClient--Sales--SaleDto--DataDto--AssetDto--SchemaDto.md)                                                                                                                                                                                                                                       |                                        |
| `class` [`TemplateDto`](AtomicMarketApiClient--Sales--SaleDto--DataDto--AssetDto--TemplateDto.md)                                                                                                                                                                                                                                   |                                        |
| `public string` [`Contract`](AtomicMarketApiClient--Sales--SaleDto--DataDto--AssetDto.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sale\_dto\_1\_1\_data\_dto\_1\_1\_asset\_dto\_1a9b4baf8484b98d89513d7776a8877d0e)                                                                                                   | The name of the Smart Contract.        |
| `public string` [`AssetId`](AtomicMarketApiClient--Sales--SaleDto--DataDto--AssetDto.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sale\_dto\_1\_1\_data\_dto\_1\_1\_asset\_dto\_1a0066ff0d119e607c3ec5491c7aac86ff)                                                                                                    | The Unique Identifier of the Asset.    |
| `public string` [`Owner`](AtomicMarketApiClient--Sales--SaleDto--DataDto--AssetDto.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sale\_dto\_1\_1\_data\_dto\_1\_1\_asset\_dto\_1a2bb39ac02455d05833c5f88b6ddc87ee)                                                                                                      | The Owner.                             |
| `public string` [`Name`](AtomicMarketApiClient--Sales--SaleDto--DataDto--AssetDto.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sale\_dto\_1\_1\_data\_dto\_1\_1\_asset\_dto\_1a7ee9065718e6628dc7791b756fa6c0f9)                                                                                                       | The Name.                              |
| `public bool` [`Transferable`](AtomicMarketApiClient--Sales--SaleDto--DataDto--AssetDto.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sale\_dto\_1\_1\_data\_dto\_1\_1\_asset\_dto\_1ab0a2025837cfad369c22e114d1c93d42)                                                                                                 | Indicates if an Asset is transferable. |
| `public bool` [`Burnable`](AtomicMarketApiClient--Sales--SaleDto--DataDto--AssetDto.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sale\_dto\_1\_1\_data\_dto\_1\_1\_asset\_dto\_1a50c30f69b54db362be32720d5cc433bd)                                                                                                     | Indicates if an Asset is burnable.     |
| `public string` [`TemplateMint`](AtomicMarketApiClient--Sales--SaleDto--DataDto--AssetDto.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sale\_dto\_1\_1\_data\_dto\_1\_1\_asset\_dto\_1a82c766587c3554c5c8b1b16e2cf29799)                                                                                               | The Mint-Number of this Template.      |
| `public` [`CollectionDto`](AtomicMarketApiClient--Sales--SaleDto--DataDto--CollectionDto.md) `` [`Collection`](AtomicMarketApiClient--Sales--SaleDto--DataDto--AssetDto.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sale\_dto\_1\_1\_data\_dto\_1\_1\_asset\_dto\_1ac6d9b0c1cef1d8ad020fa9b6fc1c3319)                 | The Collection this belongs to.        |
| `public` [`SchemaDto`](AtomicMarketApiClient--Sales--SaleDto--DataDto--AssetDto--SchemaDto.md) `` [`Schema`](AtomicMarketApiClient--Sales--SaleDto--DataDto--AssetDto.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sale\_dto\_1\_1\_data\_dto\_1\_1\_asset\_dto\_1ad93c55d7b2a8254b86543bda80750a31)                   | The Schema this belongs to.            |
| `public` [`TemplateDto`](AtomicMarketApiClient--Sales--SaleDto--DataDto--AssetDto--TemplateDto.md) `` [`Template`](AtomicMarketApiClient--Sales--SaleDto--DataDto--AssetDto.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sale\_dto\_1\_1\_data\_dto\_1\_1\_asset\_dto\_1a8d65cc2a5ff793ff3eb7a51b7d72e43f)             | The Template this belongs to.          |
| `public object` [`MutableData`](AtomicMarketApiClient--Sales--SaleDto--DataDto--AssetDto.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sale\_dto\_1\_1\_data\_dto\_1\_1\_asset\_dto\_1a517f1227ead52951840392f73f535a52)                                                                                                | The Mutable Data.                      |
| `public object` [`Data`](AtomicMarketApiClient--Sales--SaleDto--DataDto--AssetDto.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sale\_dto\_1\_1\_data\_dto\_1\_1\_asset\_dto\_1a248bfced8a2a84c147f9b20efe3e669a)                                                                                                       |                                        |
| `public object` [`ImmutableData`](AtomicMarketApiClient--Sales--SaleDto--DataDto--AssetDto.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sale\_dto\_1\_1\_data\_dto\_1\_1\_asset\_dto\_1a9fed56023309e1abafab5d3a66612ffd)                                                                                              | The Immutable Data.                    |
| `public` [`BackedTokensDto`](AtomicMarketApiClient--Sales--SaleDto--DataDto--AssetDto--BackedTokensDto.md) `` [`BackedTokens`](AtomicMarketApiClient--Sales--SaleDto--DataDto--AssetDto.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sale\_dto\_1\_1\_data\_dto\_1\_1\_asset\_dto\_1ace4511d1490d9905e3f19026c18dbc96) | Tokens by which this Asset is backed.  |
| `public string` [`BurnedByAccount`](AtomicMarketApiClient--Sales--SaleDto--DataDto--AssetDto.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sale\_dto\_1\_1\_data\_dto\_1\_1\_asset\_dto\_1aa5cda192438e7fb3d7476fd141781f01)                                                                                            |                                        |
| `public string` [`BurnedAtBlock`](AtomicMarketApiClient--Sales--SaleDto--DataDto--AssetDto.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sale\_dto\_1\_1\_data\_dto\_1\_1\_asset\_dto\_1a33628aede1491a3c2ee851bc168ef66d)                                                                                              | The Block-Number this was burned.      |
| `public string` [`BurnedAtTime`](AtomicMarketApiClient--Sales--SaleDto--DataDto--AssetDto.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sale\_dto\_1\_1\_data\_dto\_1\_1\_asset\_dto\_1a664d94dbbc9b356664c27342061abbe7)                                                                                               | The Time this was burned.              |
| `public string` [`UpdatedAtBlock`](AtomicMarketApiClient--Sales--SaleDto--DataDto--AssetDto.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sale\_dto\_1\_1\_data\_dto\_1\_1\_asset\_dto\_1a6bb57b5afa05403c9d9c39296178c9ef)                                                                                             | Block-Number this was last updated.    |
| `public string` [`UpdatedAtTime`](AtomicMarketApiClient--Sales--SaleDto--DataDto--AssetDto.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sale\_dto\_1\_1\_data\_dto\_1\_1\_asset\_dto\_1a72262f869452135882a475b6636de902)                                                                                              | Time this was last updated.            |
| `public string` [`TransferredAtBlock`](AtomicMarketApiClient--Sales--SaleDto--DataDto--AssetDto.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sale\_dto\_1\_1\_data\_dto\_1\_1\_asset\_dto\_1ab2e154e0d51a36f9dd001bd6ccda4571)                                                                                         | Block this was last transferred.       |
| `public string` [`TransferredAtTime`](AtomicMarketApiClient--Sales--SaleDto--DataDto--AssetDto.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sale\_dto\_1\_1\_data\_dto\_1\_1\_asset\_dto\_1abaf0a7b245b0a4891c81c278b57898b7)                                                                                          | Time this was last transferred.        |
| `public string` [`MintedAtBlock`](AtomicMarketApiClient--Sales--SaleDto--DataDto--AssetDto.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sale\_dto\_1\_1\_data\_dto\_1\_1\_asset\_dto\_1aece51bb353a548fed2f074df53cc3dc2)                                                                                              | Block this Asset was minted.           |
| `public string` [`MintedAtTime`](AtomicMarketApiClient--Sales--SaleDto--DataDto--AssetDto.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sale\_dto\_1\_1\_data\_dto\_1\_1\_asset\_dto\_1a02bd8923fc7b1802cd28ec5286c14d0e)                                                                                               | Time this Asset was minted.            |

## Members

**`class`** [**`BackedTokensDto`**](AtomicMarketApiClient--Sales--SaleDto--DataDto--AssetDto--BackedTokensDto.md)

**`class`** [**`SchemaDto`**](AtomicMarketApiClient--Sales--SaleDto--DataDto--AssetDto--SchemaDto.md)

**`class`** [**`TemplateDto`**](AtomicMarketApiClient--Sales--SaleDto--DataDto--AssetDto--TemplateDto.md)

**`public string`** [**`Contract`**](AtomicMarketApiClient--Sales--SaleDto--DataDto--AssetDto.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sale\_dto\_1\_1\_data\_dto\_1\_1\_asset\_dto\_1a9b4baf8484b98d89513d7776a8877d0e)

The name of the Smart Contract.

**`public string`** [**`AssetId`**](AtomicMarketApiClient--Sales--SaleDto--DataDto--AssetDto.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sale\_dto\_1\_1\_data\_dto\_1\_1\_asset\_dto\_1a0066ff0d119e607c3ec5491c7aac86ff)

The Unique Identifier of the Asset.

**`public string`** [**`Owner`**](AtomicMarketApiClient--Sales--SaleDto--DataDto--AssetDto.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sale\_dto\_1\_1\_data\_dto\_1\_1\_asset\_dto\_1a2bb39ac02455d05833c5f88b6ddc87ee)

The Owner.

**`public string`** [**`Name`**](AtomicMarketApiClient--Sales--SaleDto--DataDto--AssetDto.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sale\_dto\_1\_1\_data\_dto\_1\_1\_asset\_dto\_1a7ee9065718e6628dc7791b756fa6c0f9)

The Name.

**`public bool`** [**`Transferable`**](AtomicMarketApiClient--Sales--SaleDto--DataDto--AssetDto.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sale\_dto\_1\_1\_data\_dto\_1\_1\_asset\_dto\_1ab0a2025837cfad369c22e114d1c93d42)

Indicates if an Asset is transferable.

**`public bool`** [**`Burnable`**](AtomicMarketApiClient--Sales--SaleDto--DataDto--AssetDto.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sale\_dto\_1\_1\_data\_dto\_1\_1\_asset\_dto\_1a50c30f69b54db362be32720d5cc433bd)

Indicates if an Asset is burnable.

**`public string`** [**`TemplateMint`**](AtomicMarketApiClient--Sales--SaleDto--DataDto--AssetDto.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sale\_dto\_1\_1\_data\_dto\_1\_1\_asset\_dto\_1a82c766587c3554c5c8b1b16e2cf29799)

The Mint-Number of this Template.

**`public`** [**`CollectionDto`**](AtomicMarketApiClient--Sales--SaleDto--DataDto--CollectionDto.md) **``** [**`Collection`**](AtomicMarketApiClient--Sales--SaleDto--DataDto--AssetDto.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sale\_dto\_1\_1\_data\_dto\_1\_1\_asset\_dto\_1ac6d9b0c1cef1d8ad020fa9b6fc1c3319)

The Collection this belongs to.

**`public`** [**`SchemaDto`**](AtomicMarketApiClient--Sales--SaleDto--DataDto--AssetDto--SchemaDto.md) **``** [**`Schema`**](AtomicMarketApiClient--Sales--SaleDto--DataDto--AssetDto.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sale\_dto\_1\_1\_data\_dto\_1\_1\_asset\_dto\_1ad93c55d7b2a8254b86543bda80750a31)

The Schema this belongs to.

**`public`** [**`TemplateDto`**](AtomicMarketApiClient--Sales--SaleDto--DataDto--AssetDto--TemplateDto.md) **``** [**`Template`**](AtomicMarketApiClient--Sales--SaleDto--DataDto--AssetDto.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sale\_dto\_1\_1\_data\_dto\_1\_1\_asset\_dto\_1a8d65cc2a5ff793ff3eb7a51b7d72e43f)

The Template this belongs to.

**`public object`** [**`MutableData`**](AtomicMarketApiClient--Sales--SaleDto--DataDto--AssetDto.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sale\_dto\_1\_1\_data\_dto\_1\_1\_asset\_dto\_1a517f1227ead52951840392f73f535a52)

The Mutable Data.

**`public object`** [**`Data`**](AtomicMarketApiClient--Sales--SaleDto--DataDto--AssetDto.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sale\_dto\_1\_1\_data\_dto\_1\_1\_asset\_dto\_1a248bfced8a2a84c147f9b20efe3e669a)

**`public object`** [**`ImmutableData`**](AtomicMarketApiClient--Sales--SaleDto--DataDto--AssetDto.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sale\_dto\_1\_1\_data\_dto\_1\_1\_asset\_dto\_1a9fed56023309e1abafab5d3a66612ffd)

The Immutable Data.

**`public`** [**`BackedTokensDto`**](AtomicMarketApiClient--Sales--SaleDto--DataDto--AssetDto--BackedTokensDto.md) **``** [**`BackedTokens`**](AtomicMarketApiClient--Sales--SaleDto--DataDto--AssetDto.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sale\_dto\_1\_1\_data\_dto\_1\_1\_asset\_dto\_1ace4511d1490d9905e3f19026c18dbc96)

Tokens by which this Asset is backed.

**`public string`** [**`BurnedByAccount`**](AtomicMarketApiClient--Sales--SaleDto--DataDto--AssetDto.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sale\_dto\_1\_1\_data\_dto\_1\_1\_asset\_dto\_1aa5cda192438e7fb3d7476fd141781f01)

**`public string`** [**`BurnedAtBlock`**](AtomicMarketApiClient--Sales--SaleDto--DataDto--AssetDto.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sale\_dto\_1\_1\_data\_dto\_1\_1\_asset\_dto\_1a33628aede1491a3c2ee851bc168ef66d)

The Block-Number this was burned.

**`public string`** [**`BurnedAtTime`**](AtomicMarketApiClient--Sales--SaleDto--DataDto--AssetDto.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sale\_dto\_1\_1\_data\_dto\_1\_1\_asset\_dto\_1a664d94dbbc9b356664c27342061abbe7)

The Time this was burned.

**`public string`** [**`UpdatedAtBlock`**](AtomicMarketApiClient--Sales--SaleDto--DataDto--AssetDto.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sale\_dto\_1\_1\_data\_dto\_1\_1\_asset\_dto\_1a6bb57b5afa05403c9d9c39296178c9ef)

Block-Number this was last updated.

**`public string`** [**`UpdatedAtTime`**](AtomicMarketApiClient--Sales--SaleDto--DataDto--AssetDto.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sale\_dto\_1\_1\_data\_dto\_1\_1\_asset\_dto\_1a72262f869452135882a475b6636de902)

Time this was last updated.

**`public string`** [**`TransferredAtBlock`**](AtomicMarketApiClient--Sales--SaleDto--DataDto--AssetDto.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sale\_dto\_1\_1\_data\_dto\_1\_1\_asset\_dto\_1ab2e154e0d51a36f9dd001bd6ccda4571)

Block this was last transferred.

**`public string`** [**`TransferredAtTime`**](AtomicMarketApiClient--Sales--SaleDto--DataDto--AssetDto.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sale\_dto\_1\_1\_data\_dto\_1\_1\_asset\_dto\_1abaf0a7b245b0a4891c81c278b57898b7)

Time this was last transferred.

**`public string`** [**`MintedAtBlock`**](AtomicMarketApiClient--Sales--SaleDto--DataDto--AssetDto.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sale\_dto\_1\_1\_data\_dto\_1\_1\_asset\_dto\_1aece51bb353a548fed2f074df53cc3dc2)

Block this Asset was minted.

**`public string`** [**`MintedAtTime`**](AtomicMarketApiClient--Sales--SaleDto--DataDto--AssetDto.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sale\_dto\_1\_1\_data\_dto\_1\_1\_asset\_dto\_1a02bd8923fc7b1802cd28ec5286c14d0e)

Time this Asset was minted.
