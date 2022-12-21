# class `AtomicMarketApiClient::Offers::OffersDto::DataDto::AssetDto` 

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`class ` [`BackedTokensDto`](.github/workflows/documentation/md/AtomicMarketApiClient--Offers--OffersDto--DataDto--AssetDto--BackedTokensDto.md#class_atomic_market_api_client_1_1_offers_1_1_offers_dto_1_1_data_dto_1_1_asset_dto_1_1_backed_tokens_dto)        | 
`class ` [`CollectionDto`](.github/workflows/documentation/md/AtomicMarketApiClient--Offers--OffersDto--DataDto--AssetDto--CollectionDto.md#class_atomic_market_api_client_1_1_offers_1_1_offers_dto_1_1_data_dto_1_1_asset_dto_1_1_collection_dto)        | 
`class ` [`SchemaDto`](.github/workflows/documentation/md/AtomicMarketApiClient--Offers--OffersDto--DataDto--AssetDto--SchemaDto.md#class_atomic_market_api_client_1_1_offers_1_1_offers_dto_1_1_data_dto_1_1_asset_dto_1_1_schema_dto)        | 
`class ` [`TemplateDto`](.github/workflows/documentation/md/AtomicMarketApiClient--Offers--OffersDto--DataDto--AssetDto--TemplateDto.md#class_atomic_market_api_client_1_1_offers_1_1_offers_dto_1_1_data_dto_1_1_asset_dto_1_1_template_dto)        | 
`public string ` [`Contract`](#class_atomic_market_api_client_1_1_offers_1_1_offers_dto_1_1_data_dto_1_1_asset_dto_1a9b4baf8484b98d89513d7776a8877d0e) | The name of the Smart Contract.
`public string ` [`AssetId`](#class_atomic_market_api_client_1_1_offers_1_1_offers_dto_1_1_data_dto_1_1_asset_dto_1a0066ff0d119e607c3ec5491c7aac86ff) | The Unique Identifier of the Asset.
`public string ` [`Owner`](#class_atomic_market_api_client_1_1_offers_1_1_offers_dto_1_1_data_dto_1_1_asset_dto_1a2bb39ac02455d05833c5f88b6ddc87ee) | The Owner.
`public bool ` [`Transferable`](#class_atomic_market_api_client_1_1_offers_1_1_offers_dto_1_1_data_dto_1_1_asset_dto_1ab0a2025837cfad369c22e114d1c93d42) | Indicates if an Asset is transferable.
`public bool ` [`Burnable`](#class_atomic_market_api_client_1_1_offers_1_1_offers_dto_1_1_data_dto_1_1_asset_dto_1a50c30f69b54db362be32720d5cc433bd) | Indicates if an Asset is burnable.
`public ` [`CollectionDto`](.github/workflows/documentation/md/AtomicMarketApiClient--Offers--OffersDto--DataDto--AssetDto--CollectionDto.md#class_atomic_market_api_client_1_1_offers_1_1_offers_dto_1_1_data_dto_1_1_asset_dto_1_1_collection_dto)` ` [`Collection`](#class_atomic_market_api_client_1_1_offers_1_1_offers_dto_1_1_data_dto_1_1_asset_dto_1ac6d9b0c1cef1d8ad020fa9b6fc1c3319) | The Collection this belongs to.
`public ` [`SchemaDto`](.github/workflows/documentation/md/AtomicMarketApiClient--Offers--OffersDto--DataDto--AssetDto--SchemaDto.md#class_atomic_market_api_client_1_1_offers_1_1_offers_dto_1_1_data_dto_1_1_asset_dto_1_1_schema_dto)` ` [`Schema`](#class_atomic_market_api_client_1_1_offers_1_1_offers_dto_1_1_data_dto_1_1_asset_dto_1ad93c55d7b2a8254b86543bda80750a31) | The Schema this belongs to.
`public ` [`TemplateDto`](.github/workflows/documentation/md/AtomicMarketApiClient--Offers--OffersDto--DataDto--AssetDto--TemplateDto.md#class_atomic_market_api_client_1_1_offers_1_1_offers_dto_1_1_data_dto_1_1_asset_dto_1_1_template_dto)` ` [`Template`](#class_atomic_market_api_client_1_1_offers_1_1_offers_dto_1_1_data_dto_1_1_asset_dto_1a8d65cc2a5ff793ff3eb7a51b7d72e43f) | The Template this belongs to.
`public object ` [`MutableData`](#class_atomic_market_api_client_1_1_offers_1_1_offers_dto_1_1_data_dto_1_1_asset_dto_1a517f1227ead52951840392f73f535a52) | The Mutable Data.
`public object ` [`ImmutableData`](#class_atomic_market_api_client_1_1_offers_1_1_offers_dto_1_1_data_dto_1_1_asset_dto_1a9fed56023309e1abafab5d3a66612ffd) | The Immutable Data.
`public string ` [`TemplateMint`](#class_atomic_market_api_client_1_1_offers_1_1_offers_dto_1_1_data_dto_1_1_asset_dto_1a82c766587c3554c5c8b1b16e2cf29799) | The Mint-Number of this Template.
`public ` [`BackedTokensDto`](.github/workflows/documentation/md/AtomicMarketApiClient--Offers--OffersDto--DataDto--AssetDto--BackedTokensDto.md#class_atomic_market_api_client_1_1_offers_1_1_offers_dto_1_1_data_dto_1_1_asset_dto_1_1_backed_tokens_dto)` ` [`BackedTokens`](#class_atomic_market_api_client_1_1_offers_1_1_offers_dto_1_1_data_dto_1_1_asset_dto_1ace4511d1490d9905e3f19026c18dbc96) | Tokens by which this Asset is backed.
`public string ` [`UpdatedAtBlock`](#class_atomic_market_api_client_1_1_offers_1_1_offers_dto_1_1_data_dto_1_1_asset_dto_1a6bb57b5afa05403c9d9c39296178c9ef) | Block-Number this was last updated.
`public string ` [`UpdatedAtTime`](#class_atomic_market_api_client_1_1_offers_1_1_offers_dto_1_1_data_dto_1_1_asset_dto_1a72262f869452135882a475b6636de902) | Time this was last updated.
`public string ` [`TransferredAtBlock`](#class_atomic_market_api_client_1_1_offers_1_1_offers_dto_1_1_data_dto_1_1_asset_dto_1ab2e154e0d51a36f9dd001bd6ccda4571) | Block this was last transferred.
`public string ` [`TransferredAtTime`](#class_atomic_market_api_client_1_1_offers_1_1_offers_dto_1_1_data_dto_1_1_asset_dto_1abaf0a7b245b0a4891c81c278b57898b7) | Time this was last transferred.
`public string ` [`MintedAtBlock`](#class_atomic_market_api_client_1_1_offers_1_1_offers_dto_1_1_data_dto_1_1_asset_dto_1aece51bb353a548fed2f074df53cc3dc2) | Block this Asset was minted.
`public string ` [`MintedAtTime`](#class_atomic_market_api_client_1_1_offers_1_1_offers_dto_1_1_data_dto_1_1_asset_dto_1a02bd8923fc7b1802cd28ec5286c14d0e) | Time this Asset was minted.
`public string ` [`Name`](#class_atomic_market_api_client_1_1_offers_1_1_offers_dto_1_1_data_dto_1_1_asset_dto_1a7ee9065718e6628dc7791b756fa6c0f9) | The Name.

## Members

##### `class ` [`BackedTokensDto`](.github/workflows/documentation/md/AtomicMarketApiClient--Offers--OffersDto--DataDto--AssetDto--BackedTokensDto.md#class_atomic_market_api_client_1_1_offers_1_1_offers_dto_1_1_data_dto_1_1_asset_dto_1_1_backed_tokens_dto) 

##### `class ` [`CollectionDto`](.github/workflows/documentation/md/AtomicMarketApiClient--Offers--OffersDto--DataDto--AssetDto--CollectionDto.md#class_atomic_market_api_client_1_1_offers_1_1_offers_dto_1_1_data_dto_1_1_asset_dto_1_1_collection_dto) 

##### `class ` [`SchemaDto`](.github/workflows/documentation/md/AtomicMarketApiClient--Offers--OffersDto--DataDto--AssetDto--SchemaDto.md#class_atomic_market_api_client_1_1_offers_1_1_offers_dto_1_1_data_dto_1_1_asset_dto_1_1_schema_dto) 

##### `class ` [`TemplateDto`](.github/workflows/documentation/md/AtomicMarketApiClient--Offers--OffersDto--DataDto--AssetDto--TemplateDto.md#class_atomic_market_api_client_1_1_offers_1_1_offers_dto_1_1_data_dto_1_1_asset_dto_1_1_template_dto) 

##### `public string ` [`Contract`](#class_atomic_market_api_client_1_1_offers_1_1_offers_dto_1_1_data_dto_1_1_asset_dto_1a9b4baf8484b98d89513d7776a8877d0e) 

The name of the Smart Contract.

##### `public string ` [`AssetId`](#class_atomic_market_api_client_1_1_offers_1_1_offers_dto_1_1_data_dto_1_1_asset_dto_1a0066ff0d119e607c3ec5491c7aac86ff) 

The Unique Identifier of the Asset.

##### `public string ` [`Owner`](#class_atomic_market_api_client_1_1_offers_1_1_offers_dto_1_1_data_dto_1_1_asset_dto_1a2bb39ac02455d05833c5f88b6ddc87ee) 

The Owner.

##### `public bool ` [`Transferable`](#class_atomic_market_api_client_1_1_offers_1_1_offers_dto_1_1_data_dto_1_1_asset_dto_1ab0a2025837cfad369c22e114d1c93d42) 

Indicates if an Asset is transferable.

##### `public bool ` [`Burnable`](#class_atomic_market_api_client_1_1_offers_1_1_offers_dto_1_1_data_dto_1_1_asset_dto_1a50c30f69b54db362be32720d5cc433bd) 

Indicates if an Asset is burnable.

##### `public ` [`CollectionDto`](.github/workflows/documentation/md/AtomicMarketApiClient--Offers--OffersDto--DataDto--AssetDto--CollectionDto.md#class_atomic_market_api_client_1_1_offers_1_1_offers_dto_1_1_data_dto_1_1_asset_dto_1_1_collection_dto)` ` [`Collection`](#class_atomic_market_api_client_1_1_offers_1_1_offers_dto_1_1_data_dto_1_1_asset_dto_1ac6d9b0c1cef1d8ad020fa9b6fc1c3319) 

The Collection this belongs to.

##### `public ` [`SchemaDto`](.github/workflows/documentation/md/AtomicMarketApiClient--Offers--OffersDto--DataDto--AssetDto--SchemaDto.md#class_atomic_market_api_client_1_1_offers_1_1_offers_dto_1_1_data_dto_1_1_asset_dto_1_1_schema_dto)` ` [`Schema`](#class_atomic_market_api_client_1_1_offers_1_1_offers_dto_1_1_data_dto_1_1_asset_dto_1ad93c55d7b2a8254b86543bda80750a31) 

The Schema this belongs to.

##### `public ` [`TemplateDto`](.github/workflows/documentation/md/AtomicMarketApiClient--Offers--OffersDto--DataDto--AssetDto--TemplateDto.md#class_atomic_market_api_client_1_1_offers_1_1_offers_dto_1_1_data_dto_1_1_asset_dto_1_1_template_dto)` ` [`Template`](#class_atomic_market_api_client_1_1_offers_1_1_offers_dto_1_1_data_dto_1_1_asset_dto_1a8d65cc2a5ff793ff3eb7a51b7d72e43f) 

The Template this belongs to.

##### `public object ` [`MutableData`](#class_atomic_market_api_client_1_1_offers_1_1_offers_dto_1_1_data_dto_1_1_asset_dto_1a517f1227ead52951840392f73f535a52) 

The Mutable Data.

##### `public object ` [`ImmutableData`](#class_atomic_market_api_client_1_1_offers_1_1_offers_dto_1_1_data_dto_1_1_asset_dto_1a9fed56023309e1abafab5d3a66612ffd) 

The Immutable Data.

##### `public string ` [`TemplateMint`](#class_atomic_market_api_client_1_1_offers_1_1_offers_dto_1_1_data_dto_1_1_asset_dto_1a82c766587c3554c5c8b1b16e2cf29799) 

The Mint-Number of this Template.

##### `public ` [`BackedTokensDto`](.github/workflows/documentation/md/AtomicMarketApiClient--Offers--OffersDto--DataDto--AssetDto--BackedTokensDto.md#class_atomic_market_api_client_1_1_offers_1_1_offers_dto_1_1_data_dto_1_1_asset_dto_1_1_backed_tokens_dto)` ` [`BackedTokens`](#class_atomic_market_api_client_1_1_offers_1_1_offers_dto_1_1_data_dto_1_1_asset_dto_1ace4511d1490d9905e3f19026c18dbc96) 

Tokens by which this Asset is backed.

##### `public string ` [`UpdatedAtBlock`](#class_atomic_market_api_client_1_1_offers_1_1_offers_dto_1_1_data_dto_1_1_asset_dto_1a6bb57b5afa05403c9d9c39296178c9ef) 

Block-Number this was last updated.

##### `public string ` [`UpdatedAtTime`](#class_atomic_market_api_client_1_1_offers_1_1_offers_dto_1_1_data_dto_1_1_asset_dto_1a72262f869452135882a475b6636de902) 

Time this was last updated.

##### `public string ` [`TransferredAtBlock`](#class_atomic_market_api_client_1_1_offers_1_1_offers_dto_1_1_data_dto_1_1_asset_dto_1ab2e154e0d51a36f9dd001bd6ccda4571) 

Block this was last transferred.

##### `public string ` [`TransferredAtTime`](#class_atomic_market_api_client_1_1_offers_1_1_offers_dto_1_1_data_dto_1_1_asset_dto_1abaf0a7b245b0a4891c81c278b57898b7) 

Time this was last transferred.

##### `public string ` [`MintedAtBlock`](#class_atomic_market_api_client_1_1_offers_1_1_offers_dto_1_1_data_dto_1_1_asset_dto_1aece51bb353a548fed2f074df53cc3dc2) 

Block this Asset was minted.

##### `public string ` [`MintedAtTime`](#class_atomic_market_api_client_1_1_offers_1_1_offers_dto_1_1_data_dto_1_1_asset_dto_1a02bd8923fc7b1802cd28ec5286c14d0e) 

Time this Asset was minted.

##### `public string ` [`Name`](#class_atomic_market_api_client_1_1_offers_1_1_offers_dto_1_1_data_dto_1_1_asset_dto_1a7ee9065718e6628dc7791b756fa6c0f9) 

The Name.

