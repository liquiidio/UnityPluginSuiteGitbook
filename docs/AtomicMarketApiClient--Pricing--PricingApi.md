# class `AtomicMarketApiClient::Pricing::PricingApi` 

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public ` [`PricesDto`](.github/workflows/documentation/md/AtomicMarketApiClient--Pricing--PricesDto.md#class_atomic_market_api_client_1_1_pricing_1_1_prices_dto)` ` [`Sales`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_api_1a7b19a3f28a071ca6c5a70f9133b19d80)`()` | This function will return a list of prices for all the sales that have been made.
`public ` [`PricesDto`](.github/workflows/documentation/md/AtomicMarketApiClient--Pricing--PricesDto.md#class_atomic_market_api_client_1_1_pricing_1_1_prices_dto)` ` [`Sales`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_api_1a554610d6565779c71629e36fdcef3a5b)`(` [`PricingUriParametersBuilder`](.github/workflows/documentation/md/AtomicMarketApiClient--Pricing--PricingUriParametersBuilder.md#class_atomic_market_api_client_1_1_pricing_1_1_pricing_uri_parameters_builder)` uriParametersBuilder)` | This function will return a list of prices for a given product, based on the parameters passed in the uriParametersBuilder.
`public ` [`PricesDto`](.github/workflows/documentation/md/AtomicMarketApiClient--Pricing--PricesDto.md#class_atomic_market_api_client_1_1_pricing_1_1_prices_dto)` ` [`Days`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_api_1a0838ebc8a3e3c8997df176ec9fd307ac)`()` | This function will return a list of prices for the last 30 days.
`public ` [`PricesDto`](.github/workflows/documentation/md/AtomicMarketApiClient--Pricing--PricesDto.md#class_atomic_market_api_client_1_1_pricing_1_1_prices_dto)` ` [`Days`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_api_1a16a545af2b512f02dc4f4722d76c2c0a)`(` [`PricingUriParametersBuilder`](.github/workflows/documentation/md/AtomicMarketApiClient--Pricing--PricingUriParametersBuilder.md#class_atomic_market_api_client_1_1_pricing_1_1_pricing_uri_parameters_builder)` uriParametersBuilder)` | This function will return a `PricesDto` object that contains the prices for the specified date range.
`public ` [`TemplatesDto`](.github/workflows/documentation/md/AtomicMarketApiClient--Pricing--TemplatesDto.md#class_atomic_market_api_client_1_1_pricing_1_1_templates_dto)` ` [`Templates`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_api_1a25e67d4b511a23a1b839ddda3f068270)`()` | This function will return a list of templates that are available for use.
`public ` [`TemplatesDto`](.github/workflows/documentation/md/AtomicMarketApiClient--Pricing--TemplatesDto.md#class_atomic_market_api_client_1_1_pricing_1_1_templates_dto)` ` [`Templates`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_api_1ae1a111ff5ee44f2877d5aa85647dc483)`(` [`PricingUriParametersBuilder`](.github/workflows/documentation/md/AtomicMarketApiClient--Pricing--PricingUriParametersBuilder.md#class_atomic_market_api_client_1_1_pricing_1_1_pricing_uri_parameters_builder)` uriParametersBuilder)` | This function will return a list of templates that are available for the given parameters.
`public ` [`AssetsDto`](.github/workflows/documentation/md/AtomicMarketApiClient--Assets--AssetsDto.md#class_atomic_market_api_client_1_1_assets_1_1_assets_dto)` ` [`Assets`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_api_1acdb8d694084b095eb723eeaeb4c23adc)`()` | This function will return a list of all the assets that are available for trading on the exchange.
`public ` [`AssetsDto`](.github/workflows/documentation/md/AtomicMarketApiClient--Assets--AssetsDto.md#class_atomic_market_api_client_1_1_assets_1_1_assets_dto)` ` [`Assets`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_api_1a98ad65774a84e715194cd38ae8fd12b9)`(` [`PricingUriParametersBuilder`](.github/workflows/documentation/md/AtomicMarketApiClient--Pricing--PricingUriParametersBuilder.md#class_atomic_market_api_client_1_1_pricing_1_1_pricing_uri_parameters_builder)` uriParametersBuilder)` | This function will return a list of assets that are available for pricing.
`private readonly string ` [`_requestUriBase`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_api_1a1854c4909a1013a684af16fb52e8a387) | 
`private Uri ` [`SalesUri`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_api_1a40df74fdccb558ba58338c9fdff8c5cb)`()` | It returns a `Uri` object that is the base URI for the sales endpoint.
`private Uri ` [`SalesUri`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_api_1a483214393cf288850506d0329012e6af)`(` [`IUriParameterBuilder`](.github/workflows/documentation/md/AtomicMarketApiClient--Core.md#interface_atomic_market_api_client_1_1_core_1_1_i_uri_parameter_builder)` uriParameterBuilder)` | It returns a URI for the sales endpoint.
`private Uri ` [`DaysUri`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_api_1a87ddd2563a44aa86c74ddff9150accd6)`()` | It returns a `Uri` object that represents the URL for the API endpoint that returns the sales data for the last 30 days.
`private Uri ` [`DaysUri`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_api_1a42a804fa079726477ab3de3949fb7b15)`(` [`IUriParameterBuilder`](.github/workflows/documentation/md/AtomicMarketApiClient--Core.md#interface_atomic_market_api_client_1_1_core_1_1_i_uri_parameter_builder)` uriParameterBuilder)` | It returns a URI for the `/prices/sales/days` endpoint.
`private Uri ` [`TemplatesUri`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_api_1a70668a91db02b5409d48e972387179ce)`()` | It returns a `Uri` object that represents the URL of the API endpoint that returns the list of templates.
`private Uri ` [`TemplatesUri`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_api_1a30cb80a82c84d990c2a4d561ba86516e)`(` [`IUriParameterBuilder`](.github/workflows/documentation/md/AtomicMarketApiClient--Core.md#interface_atomic_market_api_client_1_1_core_1_1_i_uri_parameter_builder)` uriParameterBuilder)` | It returns a URI for the `/prices/templates` endpoint
`private Uri ` [`AssetsUri`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_api_1ae492984f10f05c5b2c55dff3eeac11c1)`()` | It returns a `Uri` object that points to the `/prices/assets` endpoint.
`private Uri ` [`AssetsUri`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_api_1aea89cf6aa0da1ceb2030d2c0fbd9f19e)`(` [`IUriParameterBuilder`](.github/workflows/documentation/md/AtomicMarketApiClient--Core.md#interface_atomic_market_api_client_1_1_core_1_1_i_uri_parameter_builder)` uriParameterBuilder)` | It returns a URI for the `/prices/assets` endpoint.

## Members

##### `public ` [`PricesDto`](.github/workflows/documentation/md/AtomicMarketApiClient--Pricing--PricesDto.md#class_atomic_market_api_client_1_1_pricing_1_1_prices_dto)` ` [`Sales`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_api_1a7b19a3f28a071ca6c5a70f9133b19d80)`()` 

This function will return a list of prices for all the sales that have been made.

#### Returns
A list of prices for the sales of the product.

##### `public ` [`PricesDto`](.github/workflows/documentation/md/AtomicMarketApiClient--Pricing--PricesDto.md#class_atomic_market_api_client_1_1_pricing_1_1_prices_dto)` ` [`Sales`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_api_1a554610d6565779c71629e36fdcef3a5b)`(` [`PricingUriParametersBuilder`](.github/workflows/documentation/md/AtomicMarketApiClient--Pricing--PricingUriParametersBuilder.md#class_atomic_market_api_client_1_1_pricing_1_1_pricing_uri_parameters_builder)` uriParametersBuilder)` 

This function will return a list of prices for a given product, based on the parameters passed in the uriParametersBuilder.

#### Parameters
* `PricingUriParametersBuilder` This is a class that contains the parameters that will be passed to the API.

#### Returns
A list of prices for the given parameters.

##### `public ` [`PricesDto`](.github/workflows/documentation/md/AtomicMarketApiClient--Pricing--PricesDto.md#class_atomic_market_api_client_1_1_pricing_1_1_prices_dto)` ` [`Days`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_api_1a0838ebc8a3e3c8997df176ec9fd307ac)`()` 

This function will return a list of prices for the last 30 days.

#### Returns
A list of prices for the last 30 days.

##### `public ` [`PricesDto`](.github/workflows/documentation/md/AtomicMarketApiClient--Pricing--PricesDto.md#class_atomic_market_api_client_1_1_pricing_1_1_prices_dto)` ` [`Days`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_api_1a16a545af2b512f02dc4f4722d76c2c0a)`(` [`PricingUriParametersBuilder`](.github/workflows/documentation/md/AtomicMarketApiClient--Pricing--PricingUriParametersBuilder.md#class_atomic_market_api_client_1_1_pricing_1_1_pricing_uri_parameters_builder)` uriParametersBuilder)` 

This function will return a `PricesDto` object that contains the prices for the specified date range.

#### Parameters
* `PricingUriParametersBuilder` This is a class that contains the parameters that are required to make the request.

#### Returns
A list of prices for the given date range.

##### `public ` [`TemplatesDto`](.github/workflows/documentation/md/AtomicMarketApiClient--Pricing--TemplatesDto.md#class_atomic_market_api_client_1_1_pricing_1_1_templates_dto)` ` [`Templates`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_api_1a25e67d4b511a23a1b839ddda3f068270)`()` 

This function will return a list of templates that are available for use.

#### Returns
A list of templates

##### `public ` [`TemplatesDto`](.github/workflows/documentation/md/AtomicMarketApiClient--Pricing--TemplatesDto.md#class_atomic_market_api_client_1_1_pricing_1_1_templates_dto)` ` [`Templates`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_api_1ae1a111ff5ee44f2877d5aa85647dc483)`(` [`PricingUriParametersBuilder`](.github/workflows/documentation/md/AtomicMarketApiClient--Pricing--PricingUriParametersBuilder.md#class_atomic_market_api_client_1_1_pricing_1_1_pricing_uri_parameters_builder)` uriParametersBuilder)` 

This function will return a list of templates that are available for the given parameters.

#### Parameters
* `PricingUriParametersBuilder` This is a class that contains the parameters that are required to make the request.

#### Returns
A TemplatesDto object.

##### `public ` [`AssetsDto`](.github/workflows/documentation/md/AtomicMarketApiClient--Assets--AssetsDto.md#class_atomic_market_api_client_1_1_assets_1_1_assets_dto)` ` [`Assets`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_api_1acdb8d694084b095eb723eeaeb4c23adc)`()` 

This function will return a list of all the assets that are available for trading on the exchange.

#### Returns
A list of assets.

##### `public ` [`AssetsDto`](.github/workflows/documentation/md/AtomicMarketApiClient--Assets--AssetsDto.md#class_atomic_market_api_client_1_1_assets_1_1_assets_dto)` ` [`Assets`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_api_1a98ad65774a84e715194cd38ae8fd12b9)`(` [`PricingUriParametersBuilder`](.github/workflows/documentation/md/AtomicMarketApiClient--Pricing--PricingUriParametersBuilder.md#class_atomic_market_api_client_1_1_pricing_1_1_pricing_uri_parameters_builder)` uriParametersBuilder)` 

This function will return a list of assets that are available for pricing.

#### Parameters
* `PricingUriParametersBuilder` This is a class that contains all the parameters that can be passed to the API.

#### Returns
A list of assets.

##### `private readonly string ` [`_requestUriBase`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_api_1a1854c4909a1013a684af16fb52e8a387) 

##### `private Uri ` [`SalesUri`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_api_1a40df74fdccb558ba58338c9fdff8c5cb)`()` 

It returns a `Uri` object that is the base URI for the sales endpoint.

##### `private Uri ` [`SalesUri`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_api_1a483214393cf288850506d0329012e6af)`(` [`IUriParameterBuilder`](.github/workflows/documentation/md/AtomicMarketApiClient--Core.md#interface_atomic_market_api_client_1_1_core_1_1_i_uri_parameter_builder)` uriParameterBuilder)` 

It returns a URI for the sales endpoint.

#### Parameters
* `IUriParameterBuilder` This is an interface that is used to build the query string parameters for the request.

##### `private Uri ` [`DaysUri`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_api_1a87ddd2563a44aa86c74ddff9150accd6)`()` 

It returns a `Uri` object that represents the URL for the API endpoint that returns the sales data for the last 30 days.

##### `private Uri ` [`DaysUri`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_api_1a42a804fa079726477ab3de3949fb7b15)`(` [`IUriParameterBuilder`](.github/workflows/documentation/md/AtomicMarketApiClient--Core.md#interface_atomic_market_api_client_1_1_core_1_1_i_uri_parameter_builder)` uriParameterBuilder)` 

It returns a URI for the `/prices/sales/days` endpoint.

#### Parameters
* `IUriParameterBuilder` This is an interface that is used to build the query string parameters for the request.

##### `private Uri ` [`TemplatesUri`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_api_1a70668a91db02b5409d48e972387179ce)`()` 

It returns a `Uri` object that represents the URL of the API endpoint that returns the list of templates.

##### `private Uri ` [`TemplatesUri`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_api_1a30cb80a82c84d990c2a4d561ba86516e)`(` [`IUriParameterBuilder`](.github/workflows/documentation/md/AtomicMarketApiClient--Core.md#interface_atomic_market_api_client_1_1_core_1_1_i_uri_parameter_builder)` uriParameterBuilder)` 

It returns a URI for the `/prices/templates` endpoint

#### Parameters
* `IUriParameterBuilder` This is a class that is used to build the query string parameters for the request.

##### `private Uri ` [`AssetsUri`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_api_1ae492984f10f05c5b2c55dff3eeac11c1)`()` 

It returns a `Uri` object that points to the `/prices/assets` endpoint.

##### `private Uri ` [`AssetsUri`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_api_1aea89cf6aa0da1ceb2030d2c0fbd9f19e)`(` [`IUriParameterBuilder`](.github/workflows/documentation/md/AtomicMarketApiClient--Core.md#interface_atomic_market_api_client_1_1_core_1_1_i_uri_parameter_builder)` uriParameterBuilder)` 

It returns a URI for the `/prices/assets` endpoint.

#### Parameters
* `IUriParameterBuilder` This is a class that is used to build the query string parameters for the request.

