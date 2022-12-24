# class `AtomicAssetsApiClient::Offers::OffersApi` 

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public ` [`OffersDto`](AtomicAssetsApiClient--Offers--OffersDto.md)` ` [`Offers`](#class_atomic_assets_api_client_1_1_offers_1_1_offers_api_1a6ad9622cb51a2bfb25dce65cc64dacd3)`()` | This function will make a GET request to the `Offers` endpoint and return the response as a `OffersDto` object.
`public ` [`OffersDto`](AtomicAssetsApiClient--Offers--OffersDto.md)` ` [`Offers`](#class_atomic_assets_api_client_1_1_offers_1_1_offers_api_1a8a2c0fdc617e6862e7bfc84e5ab7bca8)`(` [`OffersUriParameterBuilder`](AtomicAssetsApiClient--Offers--OffersUriParameterBuilder.md)` offersUriParameterBuilder)` | It takes a `OffersUriParameterBuilder` object as a parameter, builds a `HttpRequestMessage` object, sends it to the API, and returns the response as a `OffersDto` object.
`public ` [`OfferDto`](AtomicAssetsApiClient--Offers--OfferDto.md)` ` [`Offer`](#class_atomic_assets_api_client_1_1_offers_1_1_offers_api_1ae093d07f4cfa336003425539a0a92a13)`(string offerId)` | This function will return an OfferDto object if the API call is successful. Otherwise, it will throw an exception.
`public ` [`LogsDto`](AtomicAssetsApiClient--LogsDto.md)` ` [`OfferLogs`](#class_atomic_assets_api_client_1_1_offers_1_1_offers_api_1ab8311c9a2d3602ab9cb14d0cad5f9c13)`(string offerId)` | This function will return a list of logs for a specific offer.
`public ` [`LogsDto`](AtomicAssetsApiClient--LogsDto.md)` ` [`OfferLogs`](#class_atomic_assets_api_client_1_1_offers_1_1_offers_api_1a5403da960dc8ab3c59e75be746be37a7)`(string offerId, ` [`OffersUriParameterBuilder`](AtomicAssetsApiClient--Offers--OffersUriParameterBuilder.md)` schemasUriParameterBuilder)` | This function returns a list of logs for a specific offer.
`private readonly string ` [`_requestUriBase`](#class_atomic_assets_api_client_1_1_offers_1_1_offers_api_1a1854c4909a1013a684af16fb52e8a387) | 
`private Uri ` [`OffersUri`](#class_atomic_assets_api_client_1_1_offers_1_1_offers_api_1ada4f3a19377ef670d6e90db76983d1e5)`()` | It returns a new `Uri` object that is built from the `_requestUriBase` field and the <br/><br/>`/offers` path
`private Uri ` [`OffersUri`](#class_atomic_assets_api_client_1_1_offers_1_1_offers_api_1a7193d9a8040525ada787f90854c047f8)`(` [`OffersUriParameterBuilder`](AtomicAssetsApiClient--Offers--OffersUriParameterBuilder.md)` offersUriParameterBuilder)` | It takes a `OffersUriParameterBuilder` object as a parameter and returns a `Uri` object.
`private Uri ` [`OfferUri`](#class_atomic_assets_api_client_1_1_offers_1_1_offers_api_1a20b72164e6cdeeb7fe55ada62c70f6cb)`(string offerId)` | It takes an offer ID and returns a URI.
`private Uri ` [`OfferLogsUri`](#class_atomic_assets_api_client_1_1_offers_1_1_offers_api_1a30e9bba1b128fcfdd45beac4c5529ddc)`(string offerId)` | It returns a URI for the offer logs endpoint
`private Uri ` [`OfferLogsUri`](#class_atomic_assets_api_client_1_1_offers_1_1_offers_api_1a1b159d8d73aa0ae3b1e72fc84bf13b6d)`(string offerId, ` [`OffersUriParameterBuilder`](AtomicAssetsApiClient--Offers--OffersUriParameterBuilder.md)` offersUriParameterBuilder)` | It returns a URI for the offer logs endpoint.

## Members

##### `public ` [`OffersDto`](AtomicAssetsApiClient--Offers--OffersDto.md)` ` [`Offers`](#class_atomic_assets_api_client_1_1_offers_1_1_offers_api_1a6ad9622cb51a2bfb25dce65cc64dacd3)`()` 

This function will make a GET request to the `Offers` endpoint and return the response as a `OffersDto` object.

#### Returns
A list of offers

##### `public ` [`OffersDto`](AtomicAssetsApiClient--Offers--OffersDto.md)` ` [`Offers`](#class_atomic_assets_api_client_1_1_offers_1_1_offers_api_1a8a2c0fdc617e6862e7bfc84e5ab7bca8)`(` [`OffersUriParameterBuilder`](AtomicAssetsApiClient--Offers--OffersUriParameterBuilder.md)` offersUriParameterBuilder)` 

It takes a `OffersUriParameterBuilder` object as a parameter, builds a `HttpRequestMessage` object, sends it to the API, and returns the response as a `OffersDto` object.

#### Parameters
* `OffersUriParameterBuilder` This is a class that contains all the parameters that can be passed to the API.

#### Returns
A list of offers.

##### `public ` [`OfferDto`](AtomicAssetsApiClient--Offers--OfferDto.md)` ` [`Offer`](#class_atomic_assets_api_client_1_1_offers_1_1_offers_api_1ae093d07f4cfa336003425539a0a92a13)`(string offerId)` 

This function will return an OfferDto object if the API call is successful. Otherwise, it will throw an exception.

#### Parameters
* `offerId` The id of the offer you want to retrieve.

#### Returns
A single offer

##### `public ` [`LogsDto`](AtomicAssetsApiClient--LogsDto.md)` ` [`OfferLogs`](#class_atomic_assets_api_client_1_1_offers_1_1_offers_api_1ab8311c9a2d3602ab9cb14d0cad5f9c13)`(string offerId)` 

This function will return a list of logs for a specific offer.

#### Parameters
* `offerId` The offer ID of the offer you want to get the logs for.

#### Returns
A list of logs for the offer.

##### `public ` [`LogsDto`](AtomicAssetsApiClient--LogsDto.md)` ` [`OfferLogs`](#class_atomic_assets_api_client_1_1_offers_1_1_offers_api_1a5403da960dc8ab3c59e75be746be37a7)`(string offerId, ` [`OffersUriParameterBuilder`](AtomicAssetsApiClient--Offers--OffersUriParameterBuilder.md)` schemasUriParameterBuilder)` 

This function returns a list of logs for a specific offer.

#### Parameters
* `offerId` The offer id of the offer you want to get the logs for.

* `OffersUriParameterBuilder` This is a class that contains all the parameters that can be passed to the API.

#### Returns
A LogsDto object

##### `private readonly string ` [`_requestUriBase`](#class_atomic_assets_api_client_1_1_offers_1_1_offers_api_1a1854c4909a1013a684af16fb52e8a387) 

##### `private Uri ` [`OffersUri`](#class_atomic_assets_api_client_1_1_offers_1_1_offers_api_1ada4f3a19377ef670d6e90db76983d1e5)`()` 

It returns a new `Uri` object that is built from the `_requestUriBase` field and the 

`/offers` path

##### `private Uri ` [`OffersUri`](#class_atomic_assets_api_client_1_1_offers_1_1_offers_api_1a7193d9a8040525ada787f90854c047f8)`(` [`OffersUriParameterBuilder`](AtomicAssetsApiClient--Offers--OffersUriParameterBuilder.md)` offersUriParameterBuilder)` 

It takes a `OffersUriParameterBuilder` object as a parameter and returns a `Uri` object.

#### Parameters
* `OffersUriParameterBuilder` A class that builds the query string parameters for the request.

##### `private Uri ` [`OfferUri`](#class_atomic_assets_api_client_1_1_offers_1_1_offers_api_1a20b72164e6cdeeb7fe55ada62c70f6cb)`(string offerId)` 

It takes an offer ID and returns a URI.

#### Parameters
* `offerId` The offer ID of the offer you want to get.

##### `private Uri ` [`OfferLogsUri`](#class_atomic_assets_api_client_1_1_offers_1_1_offers_api_1a30e9bba1b128fcfdd45beac4c5529ddc)`(string offerId)` 

It returns a URI for the offer logs endpoint

#### Parameters
* `offerId` The ID of the offer you want to get logs for.

##### `private Uri ` [`OfferLogsUri`](#class_atomic_assets_api_client_1_1_offers_1_1_offers_api_1a1b159d8d73aa0ae3b1e72fc84bf13b6d)`(string offerId, ` [`OffersUriParameterBuilder`](AtomicAssetsApiClient--Offers--OffersUriParameterBuilder.md)` offersUriParameterBuilder)` 

It returns a URI for the offer logs endpoint.

#### Parameters
* `offerId` The offer ID

* `OffersUriParameterBuilder` This is a class that builds the query string parameters for the request.

