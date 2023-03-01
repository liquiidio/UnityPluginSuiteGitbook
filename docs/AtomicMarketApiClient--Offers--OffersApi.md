# class `AtomicMarketApiClient::Offers::OffersApi` 

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public async Task< ` [`OffersDto`](AtomicMarketApiClient--Offers--OffersDto.md)` > ` [`Offers`](#class_atomic_market_api_client_1_1_offers_1_1_offers_api_1ac7904d229bf01ed1cf9088857088f328)`()` | This function will make a GET request to the `/offers` endpoint and return the response as a `OffersDto` object.
`public async Task< ` [`OffersDto`](AtomicMarketApiClient--Offers--OffersDto.md)` > ` [`Offers`](#class_atomic_market_api_client_1_1_offers_1_1_offers_api_1a3df5230fa2516d40b48ff572b1e746d3)`(` [`OffersUriParameterBuilder`](AtomicMarketApiClient--Offers--OffersUriParameterBuilder.md)` offersUriParameterBuilder)` | It takes a `OffersUriParameterBuilder` object as a parameter, builds a `HttpRequestMessage` object, sends it to the API, and returns a `OffersDto` object.
`public async Task< ` [`OfferDto`](AtomicMarketApiClient--Offers--OfferDto.md)` > ` [`Offer`](#class_atomic_market_api_client_1_1_offers_1_1_offers_api_1a348ecbb8b99105f87c2cc850c6d0b313)`(string offerId)` | It builds an HTTP GET request to the `OfferUri` endpoint, sends the request to the API, and returns the response as an `OfferDto` object.
`public async Task< ` [`LogsDto`](AtomicMarketApiClient--LogsDto.md)` > ` [`OfferLogs`](#class_atomic_market_api_client_1_1_offers_1_1_offers_api_1a6596ae4aebd62ae677f10d1f86c541b5)`(string offerId)` | This function returns a list of logs for a given offer.
`public async Task< ` [`LogsDto`](AtomicMarketApiClient--LogsDto.md)` > ` [`OfferLogs`](#class_atomic_market_api_client_1_1_offers_1_1_offers_api_1a4977797ba6462aff4f03b727f2925802)`(string offerId, ` [`OffersUriParameterBuilder`](AtomicMarketApiClient--Offers--OffersUriParameterBuilder.md)` schemasUriParameterBuilder)` | This function returns a list of logs for a specific offer.
`private readonly string ` [`_requestUriBase`](#class_atomic_market_api_client_1_1_offers_1_1_offers_api_1a1854c4909a1013a684af16fb52e8a387) | 
`private readonly ` [`IHttpHandler`](AtomicMarketApiClient.md)` ` [`_httpHandler`](#class_atomic_market_api_client_1_1_offers_1_1_offers_api_1a278528cd3027ee0a4ca8e04964f99674) | 
`private Uri ` [`OffersUri`](#class_atomic_market_api_client_1_1_offers_1_1_offers_api_1ada4f3a19377ef670d6e90db76983d1e5)`()` | It returns a new Uri object with the value of the _requestUriBase field, a forward slash, and the word "offers".
`private Uri ` [`OffersUri`](#class_atomic_market_api_client_1_1_offers_1_1_offers_api_1a7193d9a8040525ada787f90854c047f8)`(` [`OffersUriParameterBuilder`](AtomicMarketApiClient--Offers--OffersUriParameterBuilder.md)` offersUriParameterBuilder)` | It takes a `OffersUriParameterBuilder` object and returns a `Uri` object.
`private Uri ` [`OfferUri`](#class_atomic_market_api_client_1_1_offers_1_1_offers_api_1a20b72164e6cdeeb7fe55ada62c70f6cb)`(string offerId)` | It returns a URI for the offer with the given ID.
`private Uri ` [`OfferLogsUri`](#class_atomic_market_api_client_1_1_offers_1_1_offers_api_1a30e9bba1b128fcfdd45beac4c5529ddc)`(string offerId)` | It returns a URI for the offer logs endpoint.
`private Uri ` [`OfferLogsUri`](#class_atomic_market_api_client_1_1_offers_1_1_offers_api_1a1b159d8d73aa0ae3b1e72fc84bf13b6d)`(string offerId, ` [`OffersUriParameterBuilder`](AtomicMarketApiClient--Offers--OffersUriParameterBuilder.md)` offersUriParameterBuilder)` | It takes an offerId and an OffersUriParameterBuilder and returns a Uri.

## Members

##### `public async Task< ` [`OffersDto`](AtomicMarketApiClient--Offers--OffersDto.md)` > ` [`Offers`](#class_atomic_market_api_client_1_1_offers_1_1_offers_api_1ac7904d229bf01ed1cf9088857088f328)`()` 

This function will make a GET request to the `/offers` endpoint and return the response as a `OffersDto` object.

#### Returns
A list of offers

##### `public async Task< ` [`OffersDto`](AtomicMarketApiClient--Offers--OffersDto.md)` > ` [`Offers`](#class_atomic_market_api_client_1_1_offers_1_1_offers_api_1a3df5230fa2516d40b48ff572b1e746d3)`(` [`OffersUriParameterBuilder`](AtomicMarketApiClient--Offers--OffersUriParameterBuilder.md)` offersUriParameterBuilder)` 

It takes a `OffersUriParameterBuilder` object as a parameter, builds a `HttpRequestMessage` object, sends it to the API, and returns a `OffersDto` object.

#### Parameters
* `OffersUriParameterBuilder` This is a class that contains all the parameters that can be passed to the API.

#### Returns
A list of offers.

##### `public async Task< ` [`OfferDto`](AtomicMarketApiClient--Offers--OfferDto.md)` > ` [`Offer`](#class_atomic_market_api_client_1_1_offers_1_1_offers_api_1a348ecbb8b99105f87c2cc850c6d0b313)`(string offerId)` 

It builds an HTTP GET request to the `OfferUri` endpoint, sends the request to the API, and returns the response as an `OfferDto` object.

#### Parameters
* `offerId` The offer id of the offer you want to retrieve.

#### Returns
A single offer

##### `public async Task< ` [`LogsDto`](AtomicMarketApiClient--LogsDto.md)` > ` [`OfferLogs`](#class_atomic_market_api_client_1_1_offers_1_1_offers_api_1a6596ae4aebd62ae677f10d1f86c541b5)`(string offerId)` 

This function returns a list of logs for a given offer.

#### Parameters
* `offerId` The offer ID of the offer you want to get the logs for.

#### Returns
A list of logs for the offer.

##### `public async Task< ` [`LogsDto`](AtomicMarketApiClient--LogsDto.md)` > ` [`OfferLogs`](#class_atomic_market_api_client_1_1_offers_1_1_offers_api_1a4977797ba6462aff4f03b727f2925802)`(string offerId, ` [`OffersUriParameterBuilder`](AtomicMarketApiClient--Offers--OffersUriParameterBuilder.md)` schemasUriParameterBuilder)` 

This function returns a list of logs for a specific offer.

#### Parameters
* `offerId` The offer id of the offer you want to get the logs for.

* `OffersUriParameterBuilder` This is a class that contains all the parameters that can be passed to the API.

#### Returns
A list of logs for the offer.

##### `private readonly string ` [`_requestUriBase`](#class_atomic_market_api_client_1_1_offers_1_1_offers_api_1a1854c4909a1013a684af16fb52e8a387) 

##### `private readonly ` [`IHttpHandler`](AtomicMarketApiClient.md)` ` [`_httpHandler`](#class_atomic_market_api_client_1_1_offers_1_1_offers_api_1a278528cd3027ee0a4ca8e04964f99674) 

##### `private Uri ` [`OffersUri`](#class_atomic_market_api_client_1_1_offers_1_1_offers_api_1ada4f3a19377ef670d6e90db76983d1e5)`()` 

It returns a new Uri object with the value of the _requestUriBase field, a forward slash, and the word "offers".

##### `private Uri ` [`OffersUri`](#class_atomic_market_api_client_1_1_offers_1_1_offers_api_1a7193d9a8040525ada787f90854c047f8)`(` [`OffersUriParameterBuilder`](AtomicMarketApiClient--Offers--OffersUriParameterBuilder.md)` offersUriParameterBuilder)` 

It takes a `OffersUriParameterBuilder` object and returns a `Uri` object.

#### Parameters
* `OffersUriParameterBuilder` This is a class that builds the query string parameters for the offers endpoint.

##### `private Uri ` [`OfferUri`](#class_atomic_market_api_client_1_1_offers_1_1_offers_api_1a20b72164e6cdeeb7fe55ada62c70f6cb)`(string offerId)` 

It returns a URI for the offer with the given ID.

#### Parameters
* `offerId` The offer ID of the offer you want to get.

##### `private Uri ` [`OfferLogsUri`](#class_atomic_market_api_client_1_1_offers_1_1_offers_api_1a30e9bba1b128fcfdd45beac4c5529ddc)`(string offerId)` 

It returns a URI for the offer logs endpoint.

#### Parameters
* `offerId` The ID of the offer you want to get logs for.

##### `private Uri ` [`OfferLogsUri`](#class_atomic_market_api_client_1_1_offers_1_1_offers_api_1a1b159d8d73aa0ae3b1e72fc84bf13b6d)`(string offerId, ` [`OffersUriParameterBuilder`](AtomicMarketApiClient--Offers--OffersUriParameterBuilder.md)` offersUriParameterBuilder)` 

It takes an offerId and an OffersUriParameterBuilder and returns a Uri.

#### Parameters
* `offerId` The offer ID of the offer you want to get the logs for.

* `OffersUriParameterBuilder` This is a class that builds the query string parameters for the request.

