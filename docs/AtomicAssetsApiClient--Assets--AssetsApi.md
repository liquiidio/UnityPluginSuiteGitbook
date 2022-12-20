# class `AtomicAssetsApiClient::Assets::AssetsApi` 

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public ` [`AssetsDto`](.github/workflows/documentation/md/AtomicAssetsApiClient--Assets--AssetsDto.md#class_atomic_assets_api_client_1_1_assets_1_1_assets_dto)` ` [`Assets`](#class_atomic_assets_api_client_1_1_assets_1_1_assets_api_1acdb8d694084b095eb723eeaeb4c23adc)`()` | This function will return a list of all the assets that are available for trading on the exchange.
`public ` [`AssetsDto`](.github/workflows/documentation/md/AtomicAssetsApiClient--Assets--AssetsDto.md#class_atomic_assets_api_client_1_1_assets_1_1_assets_dto)` ` [`Assets`](#class_atomic_assets_api_client_1_1_assets_1_1_assets_api_1adc55e98828b607f5b6163cf6f571a2e0)`(` [`AssetsUriParameterBuilder`](.github/workflows/documentation/md/AtomicAssetsApiClient--Assets--AssetsUriParameterBuilder.md#class_atomic_assets_api_client_1_1_assets_1_1_assets_uri_parameter_builder)` assetsUriParameterBuilder)` | This function will return a list of assets based on the parameters passed in.
`public ` [`AssetDto`](.github/workflows/documentation/md/AtomicAssetsApiClient--Assets--AssetDto.md#class_atomic_assets_api_client_1_1_assets_1_1_asset_dto)` ` [`Asset`](#class_atomic_assets_api_client_1_1_assets_1_1_assets_api_1a8e72956dc29bff81c4855bf7c82c1959)`(string assetId)` | This function will return an AssetDto object from the API.
`public ` [`StatsDto`](.github/workflows/documentation/md/AtomicAssetsApiClient--StatsDto.md#class_atomic_assets_api_client_1_1_stats_dto)` ` [`AssetStats`](#class_atomic_assets_api_client_1_1_assets_1_1_assets_api_1a77880d824d173d2d7d5a205eee08a90e)`(string assetId)` | It returns the stats of an asset.
`public ` [`LogsDto`](.github/workflows/documentation/md/AtomicAssetsApiClient--LogsDto.md#class_atomic_assets_api_client_1_1_logs_dto)` ` [`AssetLogs`](#class_atomic_assets_api_client_1_1_assets_1_1_assets_api_1a7185cc74320faa73cbd1bdb5244002c5)`(string assetId)` | It returns the logs of an asset.
`public ` [`LogsDto`](.github/workflows/documentation/md/AtomicAssetsApiClient--LogsDto.md#class_atomic_assets_api_client_1_1_logs_dto)` ` [`AssetLogs`](#class_atomic_assets_api_client_1_1_assets_1_1_assets_api_1a4fe06e212c3432f70ecdb650d47a4a1d)`(string assetId, ` [`AssetsUriParameterBuilder`](.github/workflows/documentation/md/AtomicAssetsApiClient--Assets--AssetsUriParameterBuilder.md#class_atomic_assets_api_client_1_1_assets_1_1_assets_uri_parameter_builder)` assetsUriParameterBuilder)` | This function returns a list of logs for a given asset.
`private readonly string ` [`_requestUriBase`](#class_atomic_assets_api_client_1_1_assets_1_1_assets_api_1a1854c4909a1013a684af16fb52e8a387) | 
`private Uri ` [`AssetsUri`](#class_atomic_assets_api_client_1_1_assets_1_1_assets_api_1ae492984f10f05c5b2c55dff3eeac11c1)`()` | 
`private Uri ` [`AssetsUri`](#class_atomic_assets_api_client_1_1_assets_1_1_assets_api_1af05b4c0efc0e0c3c29cfe110a2db404f)`(` [`AssetsUriParameterBuilder`](.github/workflows/documentation/md/AtomicAssetsApiClient--Assets--AssetsUriParameterBuilder.md#class_atomic_assets_api_client_1_1_assets_1_1_assets_uri_parameter_builder)` assetsUriParameterBuilder)` | 
`private Uri ` [`AssetUri`](#class_atomic_assets_api_client_1_1_assets_1_1_assets_api_1aad28b71538e9bb09f0d021d107cb77ad)`(string assetId)` | 
`private Uri ` [`AssetStatsUri`](#class_atomic_assets_api_client_1_1_assets_1_1_assets_api_1a42f959437e709f64ce97e7a7c8c02466)`(string assetId)` | 
`private Uri ` [`AssetLogsUri`](#class_atomic_assets_api_client_1_1_assets_1_1_assets_api_1ac8295373df37326f5ccd5a9511ed9e2e)`(string assetId)` | 
`private Uri ` [`AssetLogsUri`](#class_atomic_assets_api_client_1_1_assets_1_1_assets_api_1ac05cfb4a5ff1c123d460a6999935c0cc)`(string assetId, ` [`AssetsUriParameterBuilder`](.github/workflows/documentation/md/AtomicAssetsApiClient--Assets--AssetsUriParameterBuilder.md#class_atomic_assets_api_client_1_1_assets_1_1_assets_uri_parameter_builder)` assetsUriParameterBuilder)` | 

## Members

##### `public ` [`AssetsDto`](.github/workflows/documentation/md/AtomicAssetsApiClient--Assets--AssetsDto.md#class_atomic_assets_api_client_1_1_assets_1_1_assets_dto)` ` [`Assets`](#class_atomic_assets_api_client_1_1_assets_1_1_assets_api_1acdb8d694084b095eb723eeaeb4c23adc)`()` 

This function will return a list of all the assets that are available for trading on the exchange.

#### Returns
A list of assets.

##### `public ` [`AssetsDto`](.github/workflows/documentation/md/AtomicAssetsApiClient--Assets--AssetsDto.md#class_atomic_assets_api_client_1_1_assets_1_1_assets_dto)` ` [`Assets`](#class_atomic_assets_api_client_1_1_assets_1_1_assets_api_1adc55e98828b607f5b6163cf6f571a2e0)`(` [`AssetsUriParameterBuilder`](.github/workflows/documentation/md/AtomicAssetsApiClient--Assets--AssetsUriParameterBuilder.md#class_atomic_assets_api_client_1_1_assets_1_1_assets_uri_parameter_builder)` assetsUriParameterBuilder)` 

This function will return a list of assets based on the parameters passed in.

#### Parameters
* `AssetsUriParameterBuilder` This is a class that contains all the parameters that can be passed to the API.

#### Returns
A list of assets.

##### `public ` [`AssetDto`](.github/workflows/documentation/md/AtomicAssetsApiClient--Assets--AssetDto.md#class_atomic_assets_api_client_1_1_assets_1_1_asset_dto)` ` [`Asset`](#class_atomic_assets_api_client_1_1_assets_1_1_assets_api_1a8e72956dc29bff81c4855bf7c82c1959)`(string assetId)` 

This function will return an AssetDto object from the API.

#### Parameters
* `assetId` The id of the asset you want to retrieve.

#### Returns
An AssetDto object

##### `public ` [`StatsDto`](.github/workflows/documentation/md/AtomicAssetsApiClient--StatsDto.md#class_atomic_assets_api_client_1_1_stats_dto)` ` [`AssetStats`](#class_atomic_assets_api_client_1_1_assets_1_1_assets_api_1a77880d824d173d2d7d5a205eee08a90e)`(string assetId)` 

It returns the stats of an asset.

#### Parameters
* `assetId` The asset id of the asset you want to get the stats for.

#### Returns
A StatsDto object

##### `public ` [`LogsDto`](.github/workflows/documentation/md/AtomicAssetsApiClient--LogsDto.md#class_atomic_assets_api_client_1_1_logs_dto)` ` [`AssetLogs`](#class_atomic_assets_api_client_1_1_assets_1_1_assets_api_1a7185cc74320faa73cbd1bdb5244002c5)`(string assetId)` 

It returns the logs of an asset.

#### Parameters
* `assetId` The asset id of the asset you want to get the logs for.

#### Returns
A list of logs for the asset.

##### `public ` [`LogsDto`](.github/workflows/documentation/md/AtomicAssetsApiClient--LogsDto.md#class_atomic_assets_api_client_1_1_logs_dto)` ` [`AssetLogs`](#class_atomic_assets_api_client_1_1_assets_1_1_assets_api_1a4fe06e212c3432f70ecdb650d47a4a1d)`(string assetId, ` [`AssetsUriParameterBuilder`](.github/workflows/documentation/md/AtomicAssetsApiClient--Assets--AssetsUriParameterBuilder.md#class_atomic_assets_api_client_1_1_assets_1_1_assets_uri_parameter_builder)` assetsUriParameterBuilder)` 

This function returns a list of logs for a given asset.

#### Parameters
* `assetId` The id of the asset you want to get logs for.

* `AssetsUriParameterBuilder` This is a class that contains all the parameters that can be passed to the API.

#### Returns
A list of logs for the asset.

##### `private readonly string ` [`_requestUriBase`](#class_atomic_assets_api_client_1_1_assets_1_1_assets_api_1a1854c4909a1013a684af16fb52e8a387) 

##### `private Uri ` [`AssetsUri`](#class_atomic_assets_api_client_1_1_assets_1_1_assets_api_1ae492984f10f05c5b2c55dff3eeac11c1)`()` 

##### `private Uri ` [`AssetsUri`](#class_atomic_assets_api_client_1_1_assets_1_1_assets_api_1af05b4c0efc0e0c3c29cfe110a2db404f)`(` [`AssetsUriParameterBuilder`](.github/workflows/documentation/md/AtomicAssetsApiClient--Assets--AssetsUriParameterBuilder.md#class_atomic_assets_api_client_1_1_assets_1_1_assets_uri_parameter_builder)` assetsUriParameterBuilder)` 

##### `private Uri ` [`AssetUri`](#class_atomic_assets_api_client_1_1_assets_1_1_assets_api_1aad28b71538e9bb09f0d021d107cb77ad)`(string assetId)` 

##### `private Uri ` [`AssetStatsUri`](#class_atomic_assets_api_client_1_1_assets_1_1_assets_api_1a42f959437e709f64ce97e7a7c8c02466)`(string assetId)` 

##### `private Uri ` [`AssetLogsUri`](#class_atomic_assets_api_client_1_1_assets_1_1_assets_api_1ac8295373df37326f5ccd5a9511ed9e2e)`(string assetId)` 

##### `private Uri ` [`AssetLogsUri`](#class_atomic_assets_api_client_1_1_assets_1_1_assets_api_1ac05cfb4a5ff1c123d460a6999935c0cc)`(string assetId, ` [`AssetsUriParameterBuilder`](.github/workflows/documentation/md/AtomicAssetsApiClient--Assets--AssetsUriParameterBuilder.md#class_atomic_assets_api_client_1_1_assets_1_1_assets_uri_parameter_builder)` assetsUriParameterBuilder)` 

