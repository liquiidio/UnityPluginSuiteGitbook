# class `AtomicMarketApiClient::Pricing::PricingApi` 

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public async Task< ` [`PricesDto`](AtomicMarketApiClient--Pricing--PricesDto.md)` > ` [`Sales`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_api_1ac340c925ee602c1eabbab5be032285c0)`()` | This function will return a list of prices for all the sales that have been made.
`public async Task< ` [`PricesDto`](AtomicMarketApiClient--Pricing--PricesDto.md)` > ` [`Sales`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_api_1a87afc36bc86f106ec20bb04b2954a523)`(` [`PricingUriParametersBuilder`](AtomicMarketApiClient--Pricing--PricingUriParametersBuilder.md)` uriParametersBuilder)` | This function will return a list of prices for a given product, based on the parameters passed in the uriParametersBuilder.
`public async Task< ` [`PricesDto`](AtomicMarketApiClient--Pricing--PricesDto.md)` > ` [`Days`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_api_1a0bc7d621c5e61011734a0d7315dbe2f2)`()` | This function will return a list of prices for the last 30 days.
`public async Task< ` [`PricesDto`](AtomicMarketApiClient--Pricing--PricesDto.md)` > ` [`Days`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_api_1a5080b186070aa704ec0faa7b8870a343)`(` [`PricingUriParametersBuilder`](AtomicMarketApiClient--Pricing--PricingUriParametersBuilder.md)` uriParametersBuilder)` | This function will return a `PricesDto` object that contains the prices for the specified date range.
`public async Task< ` [`TemplatesDto`](AtomicMarketApiClient--Pricing--TemplatesDto.md)` > ` [`Templates`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_api_1a86541ec88b827efe8636521c4d77aa08)`()` | This function will return a list of templates that are available for use.
`public async Task< ` [`TemplatesDto`](AtomicMarketApiClient--Pricing--TemplatesDto.md)` > ` [`Templates`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_api_1ac0b6361ae22e7900345647af93173410)`(` [`PricingUriParametersBuilder`](AtomicMarketApiClient--Pricing--PricingUriParametersBuilder.md)` uriParametersBuilder)` | This function will return a list of templates that are available for the given parameters.
`public async Task< ` [`AssetsDto`](AtomicMarketApiClient--Assets--AssetsDto.md)` > ` [`Assets`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_api_1a8a565ae05b3153f229a850676468d101)`()` | This function will return a list of all the assets that are available for trading on the exchange.
`public async Task< ` [`AssetPricingDto`](AtomicMarketApiClient--Pricing--AssetPricingDto.md)` > ` [`Assets`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_api_1a689c82c1cfab06d0c460845c3a02c6a0)`(` [`PricingUriParametersBuilder`](AtomicMarketApiClient--Pricing--PricingUriParametersBuilder.md)` uriParametersBuilder)` | This function will return a list of assets that are available for pricing.
`private readonly string ` [`_requestUriBase`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_api_1a1854c4909a1013a684af16fb52e8a387) | 
`private readonly ` [`IHttpHandler`](AtomicMarketApiClient.md)` ` [`_httpHandler`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_api_1a278528cd3027ee0a4ca8e04964f99674) | 
`private Uri ` [`SalesUri`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_api_1a40df74fdccb558ba58338c9fdff8c5cb)`()` | It returns a `Uri` object that is the base URI for the sales endpoint.
`private Uri ` [`SalesUri`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_api_1a483214393cf288850506d0329012e6af)`(` [`IUriParameterBuilder`](AtomicMarketApiClient.md)` uriParameterBuilder)` | It returns a URI for the sales endpoint.
`private Uri ` [`DaysUri`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_api_1a87ddd2563a44aa86c74ddff9150accd6)`()` | It returns a `Uri` object that represents the URL for the API endpoint that returns the sales data for the last 30 days.
`private Uri ` [`DaysUri`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_api_1a42a804fa079726477ab3de3949fb7b15)`(` [`IUriParameterBuilder`](AtomicMarketApiClient.md)` uriParameterBuilder)` | It returns a URI for the `/prices/sales/days` endpoint.
`private Uri ` [`TemplatesUri`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_api_1a70668a91db02b5409d48e972387179ce)`()` | It returns a `Uri` object that represents the URL of the API endpoint that returns the list of templates.
`private Uri ` [`TemplatesUri`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_api_1a30cb80a82c84d990c2a4d561ba86516e)`(` [`IUriParameterBuilder`](AtomicMarketApiClient.md)` uriParameterBuilder)` | It returns a URI for the `/prices/templates` endpoint
`private Uri ` [`AssetsUri`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_api_1ae492984f10f05c5b2c55dff3eeac11c1)`()` | It returns a `Uri` object that points to the `/prices/assets` endpoint.
`private Uri ` [`AssetsUri`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_api_1aea89cf6aa0da1ceb2030d2c0fbd9f19e)`(` [`IUriParameterBuilder`](AtomicMarketApiClient.md)` uriParameterBuilder)` | It returns a URI for the `/prices/assets` endpoint.

## Members

##### `public async Task< ` [`PricesDto`](AtomicMarketApiClient--Pricing--PricesDto.md)` > ` [`Sales`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_api_1ac340c925ee602c1eabbab5be032285c0)`()` 

This function will return a list of prices for all the sales that have been made.

#### Returns
A list of prices for the sales of the product.

##### `public async Task< ` [`PricesDto`](AtomicMarketApiClient--Pricing--PricesDto.md)` > ` [`Sales`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_api_1a87afc36bc86f106ec20bb04b2954a523)`(` [`PricingUriParametersBuilder`](AtomicMarketApiClient--Pricing--PricingUriParametersBuilder.md)` uriParametersBuilder)` 

This function will return a list of prices for a given product, based on the parameters passed in the uriParametersBuilder.

#### Parameters
* `PricingUriParametersBuilder` This is a class that contains the parameters that will be passed to the API.

#### Returns
A list of prices for the given parameters.

##### `public async Task< ` [`PricesDto`](AtomicMarketApiClient--Pricing--PricesDto.md)` > ` [`Days`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_api_1a0bc7d621c5e61011734a0d7315dbe2f2)`()` 

This function will return a list of prices for the last 30 days.

#### Returns
A list of prices for the last 30 days.

##### `public async Task< ` [`PricesDto`](AtomicMarketApiClient--Pricing--PricesDto.md)` > ` [`Days`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_api_1a5080b186070aa704ec0faa7b8870a343)`(` [`PricingUriParametersBuilder`](AtomicMarketApiClient--Pricing--PricingUriParametersBuilder.md)` uriParametersBuilder)` 

This function will return a `PricesDto` object that contains the prices for the specified date range.

#### Parameters
* `PricingUriParametersBuilder` This is a class that contains the parameters that are required to make the request.

#### Returns
A list of prices for the given date range.

##### `public async Task< ` [`TemplatesDto`](AtomicMarketApiClient--Pricing--TemplatesDto.md)` > ` [`Templates`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_api_1a86541ec88b827efe8636521c4d77aa08)`()` 

This function will return a list of templates that are available for use.

#### Returns
A list of templates

##### `public async Task< ` [`TemplatesDto`](AtomicMarketApiClient--Pricing--TemplatesDto.md)` > ` [`Templates`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_api_1ac0b6361ae22e7900345647af93173410)`(` [`PricingUriParametersBuilder`](AtomicMarketApiClient--Pricing--PricingUriParametersBuilder.md)` uriParametersBuilder)` 

This function will return a list of templates that are available for the given parameters.

#### Parameters
* `PricingUriParametersBuilder` This is a class that contains the parameters that are required to make the request.

#### Returns
A TemplatesDto object.

##### `public async Task< ` [`AssetsDto`](AtomicMarketApiClient--Assets--AssetsDto.md)` > ` [`Assets`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_api_1a8a565ae05b3153f229a850676468d101)`()` 

This function will return a list of all the assets that are available for trading on the exchange.

#### Returns
A list of assets.

##### `public async Task< ` [`AssetPricingDto`](AtomicMarketApiClient--Pricing--AssetPricingDto.md)` > ` [`Assets`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_api_1a689c82c1cfab06d0c460845c3a02c6a0)`(` [`PricingUriParametersBuilder`](AtomicMarketApiClient--Pricing--PricingUriParametersBuilder.md)` uriParametersBuilder)` 

This function will return a list of assets that are available for pricing.

#### Parameters
* `PricingUriParametersBuilder` This is a class that contains all the parameters that can be passed to the API.

#### Returns
A list of assets.

##### `private readonly string ` [`_requestUriBase`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_api_1a1854c4909a1013a684af16fb52e8a387) 

##### `private readonly ` [`IHttpHandler`](AtomicMarketApiClient.md)` ` [`_httpHandler`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_api_1a278528cd3027ee0a4ca8e04964f99674) 

##### `private Uri ` [`SalesUri`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_api_1a40df74fdccb558ba58338c9fdff8c5cb)`()` 

It returns a `Uri` object that is the base URI for the sales endpoint.

##### `private Uri ` [`SalesUri`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_api_1a483214393cf288850506d0329012e6af)`(` [`IUriParameterBuilder`](AtomicMarketApiClient.md)` uriParameterBuilder)` 

It returns a URI for the sales endpoint.

#### Parameters
* `IUriParameterBuilder` This is an interface that is used to build the query string parameters for the request.

##### `private Uri ` [`DaysUri`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_api_1a87ddd2563a44aa86c74ddff9150accd6)`()` 

It returns a `Uri` object that represents the URL for the API endpoint that returns the sales data for the last 30 days.

##### `private Uri ` [`DaysUri`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_api_1a42a804fa079726477ab3de3949fb7b15)`(` [`IUriParameterBuilder`](AtomicMarketApiClient.md)` uriParameterBuilder)` 

It returns a URI for the `/prices/sales/days` endpoint.

#### Parameters
* `IUriParameterBuilder` This is an interface that is used to build the query string parameters for the request.

##### `private Uri ` [`TemplatesUri`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_api_1a70668a91db02b5409d48e972387179ce)`()` 

It returns a `Uri` object that represents the URL of the API endpoint that returns the list of templates.

##### `private Uri ` [`TemplatesUri`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_api_1a30cb80a82c84d990c2a4d561ba86516e)`(` [`IUriParameterBuilder`](AtomicMarketApiClient.md)` uriParameterBuilder)` 

It returns a URI for the `/prices/templates` endpoint

#### Parameters
* `IUriParameterBuilder` This is a class that is used to build the query string parameters for the request.

##### `private Uri ` [`AssetsUri`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_api_1ae492984f10f05c5b2c55dff3eeac11c1)`()` 

It returns a `Uri` object that points to the `/prices/assets` endpoint.

##### `private Uri ` [`AssetsUri`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_api_1aea89cf6aa0da1ceb2030d2c0fbd9f19e)`(` [`IUriParameterBuilder`](AtomicMarketApiClient.md)` uriParameterBuilder)` 

It returns a URI for the `/prices/assets` endpoint.

#### Parameters
* `IUriParameterBuilder` This is a class that is used to build the query string parameters for the request.

