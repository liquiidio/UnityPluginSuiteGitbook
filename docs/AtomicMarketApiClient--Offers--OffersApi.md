# class `AtomicMarketApiClient::Offers::OffersApi` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public OffersDto `[`Offers`](#class_atomic_market_api_client_1_1_offers_1_1_offers_api_1a6ad9622cb51a2bfb25dce65cc64dacd3)`()` | This function will make a GET request to the `/offers` endpoint and return the response as a <br/><br/>`OffersDto` object
`public OffersDto `[`Offers`](#class_atomic_market_api_client_1_1_offers_1_1_offers_api_1a8a2c0fdc617e6862e7bfc84e5ab7bca8)`(OffersUriParameterBuilder offersUriParameterBuilder)` | It takes a `OffersUriParameterBuilder` object as a parameter, builds a `HttpRequestMessage` object, sends it to the API, and returns a `OffersDto` object.
`public OfferDto `[`Offer`](#class_atomic_market_api_client_1_1_offers_1_1_offers_api_1ae093d07f4cfa336003425539a0a92a13)`(string offerId)` | It builds an HTTP GET request to the `OfferUri` endpoint, sends the request to the API, and <br/><br/>returns the response as an `OfferDto` object
`public LogsDto `[`OfferLogs`](#class_atomic_market_api_client_1_1_offers_1_1_offers_api_1ab8311c9a2d3602ab9cb14d0cad5f9c13)`(string offerId)` | This function returns a list of logs for a given offer.
`public LogsDto `[`OfferLogs`](#class_atomic_market_api_client_1_1_offers_1_1_offers_api_1a5403da960dc8ab3c59e75be746be37a7)`(string offerId, OffersUriParameterBuilder schemasUriParameterBuilder)` | This function returns a list of logs for a specific offer.
`private readonly string `[`_requestUriBase`](#class_atomic_market_api_client_1_1_offers_1_1_offers_api_1a1854c4909a1013a684af16fb52e8a387) | 
`private Uri `[`OffersUri`](#class_atomic_market_api_client_1_1_offers_1_1_offers_api_1ada4f3a19377ef670d6e90db76983d1e5)`()` | 
`private Uri `[`OffersUri`](#class_atomic_market_api_client_1_1_offers_1_1_offers_api_1a7193d9a8040525ada787f90854c047f8)`(OffersUriParameterBuilder offersUriParameterBuilder)` | 
`private Uri `[`OfferUri`](#class_atomic_market_api_client_1_1_offers_1_1_offers_api_1a20b72164e6cdeeb7fe55ada62c70f6cb)`(string offerId)` | 
`private Uri `[`OfferLogsUri`](#class_atomic_market_api_client_1_1_offers_1_1_offers_api_1a30e9bba1b128fcfdd45beac4c5529ddc)`(string offerId)` | 
`private Uri `[`OfferLogsUri`](#class_atomic_market_api_client_1_1_offers_1_1_offers_api_1a1b159d8d73aa0ae3b1e72fc84bf13b6d)`(string offerId, OffersUriParameterBuilder offersUriParameterBuilder)` | 

## Members

### `public OffersDto `[`Offers`](#class_atomic_market_api_client_1_1_offers_1_1_offers_api_1a6ad9622cb51a2bfb25dce65cc64dacd3)`()` 

This function will make a GET request to the `/offers` endpoint and return the response as a 

`OffersDto` object

#### Returns
A list of offers

### `public OffersDto `[`Offers`](#class_atomic_market_api_client_1_1_offers_1_1_offers_api_1a8a2c0fdc617e6862e7bfc84e5ab7bca8)`(OffersUriParameterBuilder offersUriParameterBuilder)` 

It takes a `OffersUriParameterBuilder` object as a parameter, builds a `HttpRequestMessage` object, sends it to the API, and returns a `OffersDto` object.

#### Parameters
* `OffersUriParameterBuilder` This is a class that contains all the parameters that can be passed to the API.

#### Returns
A list of offers.

### `public OfferDto `[`Offer`](#class_atomic_market_api_client_1_1_offers_1_1_offers_api_1ae093d07f4cfa336003425539a0a92a13)`(string offerId)` 

It builds an HTTP GET request to the `OfferUri` endpoint, sends the request to the API, and 

returns the response as an `OfferDto` object

#### Parameters
* `offerId` The offer id of the offer you want to retrieve.

#### Returns
A single offer

### `public LogsDto `[`OfferLogs`](#class_atomic_market_api_client_1_1_offers_1_1_offers_api_1ab8311c9a2d3602ab9cb14d0cad5f9c13)`(string offerId)` 

This function returns a list of logs for a given offer.

#### Parameters
* `offerId` The offer ID of the offer you want to get the logs for.

#### Returns
A list of logs for the offer.

### `public LogsDto `[`OfferLogs`](#class_atomic_market_api_client_1_1_offers_1_1_offers_api_1a5403da960dc8ab3c59e75be746be37a7)`(string offerId, OffersUriParameterBuilder schemasUriParameterBuilder)` 

This function returns a list of logs for a specific offer.

#### Parameters
* `offerId` The offer id of the offer you want to get the logs for.

* `OffersUriParameterBuilder` This is a class that contains all the parameters that can be passed to the API.

#### Returns
A list of logs for the offer.

### `private readonly string `[`_requestUriBase`](#class_atomic_market_api_client_1_1_offers_1_1_offers_api_1a1854c4909a1013a684af16fb52e8a387) 

### `private Uri `[`OffersUri`](#class_atomic_market_api_client_1_1_offers_1_1_offers_api_1ada4f3a19377ef670d6e90db76983d1e5)`()` 

### `private Uri `[`OffersUri`](#class_atomic_market_api_client_1_1_offers_1_1_offers_api_1a7193d9a8040525ada787f90854c047f8)`(OffersUriParameterBuilder offersUriParameterBuilder)` 

### `private Uri `[`OfferUri`](#class_atomic_market_api_client_1_1_offers_1_1_offers_api_1a20b72164e6cdeeb7fe55ada62c70f6cb)`(string offerId)` 

### `private Uri `[`OfferLogsUri`](#class_atomic_market_api_client_1_1_offers_1_1_offers_api_1a30e9bba1b128fcfdd45beac4c5529ddc)`(string offerId)` 

### `private Uri `[`OfferLogsUri`](#class_atomic_market_api_client_1_1_offers_1_1_offers_api_1a1b159d8d73aa0ae3b1e72fc84bf13b6d)`(string offerId, OffersUriParameterBuilder offersUriParameterBuilder)` 

