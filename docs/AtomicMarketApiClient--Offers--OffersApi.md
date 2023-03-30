# OffersApi

## Summary

| Members                                                                                                                                                                                                                                                                                                                                                                  | Descriptions                                                                                                                                               |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `public` [`OffersDto`](AtomicMarketApiClient--Offers--OffersDto.md) `` [`Offers`](AtomicMarketApiClient--Offers--OffersApi.md#class\_atomic\_market\_api\_client\_1\_1\_offers\_1\_1\_offers\_api\_1a6ad9622cb51a2bfb25dce65cc64dacd3)`()`                                                                                                                               | This function will make a GET request to the `/offers` endpoint and return the response as a `OffersDto` object.                                           |
| `public` [`OffersDto`](AtomicMarketApiClient--Offers--OffersDto.md) `` [`Offers`](AtomicMarketApiClient--Offers--OffersApi.md#class\_atomic\_market\_api\_client\_1\_1\_offers\_1\_1\_offers\_api\_1a8a2c0fdc617e6862e7bfc84e5ab7bca8)`(` [`OffersUriParameterBuilder`](AtomicMarketApiClient--Offers--OffersUriParameterBuilder.md) `offersUriParameterBuilder)`        | It takes a `OffersUriParameterBuilder` object as a parameter, builds a `HttpRequestMessage` object, sends it to the API, and returns a `OffersDto` object. |
| `public` [`OfferDto`](AtomicMarketApiClient--Offers--OfferDto.md) `` [`Offer`](AtomicMarketApiClient--Offers--OffersApi.md#class\_atomic\_market\_api\_client\_1\_1\_offers\_1\_1\_offers\_api\_1ae093d07f4cfa336003425539a0a92a13)`(string offerId)`                                                                                                                    | It builds an HTTP GET request to the `OfferUri` endpoint, sends the request to the API, and returns the response as an `OfferDto` object.                  |
| `public` [`LogsDto`](AtomicMarketApiClient--LogsDto.md) `` [`OfferLogs`](AtomicMarketApiClient--Offers--OffersApi.md#class\_atomic\_market\_api\_client\_1\_1\_offers\_1\_1\_offers\_api\_1ab8311c9a2d3602ab9cb14d0cad5f9c13)`(string offerId)`                                                                                                                          | This function returns a list of logs for a given offer.                                                                                                    |
| `public` [`LogsDto`](AtomicMarketApiClient--LogsDto.md) `` [`OfferLogs`](AtomicMarketApiClient--Offers--OffersApi.md#class\_atomic\_market\_api\_client\_1\_1\_offers\_1\_1\_offers\_api\_1a5403da960dc8ab3c59e75be746be37a7)`(string offerId,` [`OffersUriParameterBuilder`](AtomicMarketApiClient--Offers--OffersUriParameterBuilder.md) `schemasUriParameterBuilder)` | This function returns a list of logs for a specific offer.                                                                                                 |
| `private readonly string` [`_requestUriBase`](AtomicMarketApiClient--Offers--OffersApi.md#class\_atomic\_market\_api\_client\_1\_1\_offers\_1\_1\_offers\_api\_1a1854c4909a1013a684af16fb52e8a387)                                                                                                                                                                       |                                                                                                                                                            |
| `private Uri` [`OffersUri`](AtomicMarketApiClient--Offers--OffersApi.md#class\_atomic\_market\_api\_client\_1\_1\_offers\_1\_1\_offers\_api\_1ada4f3a19377ef670d6e90db76983d1e5)`()`                                                                                                                                                                                     | It returns a new Uri object with the value of the \_requestUriBase field, a forward slash, and the word "offers".                                          |
| `private Uri` [`OffersUri`](AtomicMarketApiClient--Offers--OffersApi.md#class\_atomic\_market\_api\_client\_1\_1\_offers\_1\_1\_offers\_api\_1a7193d9a8040525ada787f90854c047f8)`(` [`OffersUriParameterBuilder`](AtomicMarketApiClient--Offers--OffersUriParameterBuilder.md) `offersUriParameterBuilder)`                                                              | It takes a `OffersUriParameterBuilder` object and returns a `Uri` object.                                                                                  |
| `private Uri` [`OfferUri`](AtomicMarketApiClient--Offers--OffersApi.md#class\_atomic\_market\_api\_client\_1\_1\_offers\_1\_1\_offers\_api\_1a20b72164e6cdeeb7fe55ada62c70f6cb)`(string offerId)`                                                                                                                                                                        | It returns a URI for the offer with the given ID.                                                                                                          |
| `private Uri` [`OfferLogsUri`](AtomicMarketApiClient--Offers--OffersApi.md#class\_atomic\_market\_api\_client\_1\_1\_offers\_1\_1\_offers\_api\_1a30e9bba1b128fcfdd45beac4c5529ddc)`(string offerId)`                                                                                                                                                                    | It returns a URI for the offer logs endpoint.                                                                                                              |
| `private Uri` [`OfferLogsUri`](AtomicMarketApiClient--Offers--OffersApi.md#class\_atomic\_market\_api\_client\_1\_1\_offers\_1\_1\_offers\_api\_1a1b159d8d73aa0ae3b1e72fc84bf13b6d)`(string offerId,` [`OffersUriParameterBuilder`](AtomicMarketApiClient--Offers--OffersUriParameterBuilder.md) `offersUriParameterBuilder)`                                            | It takes an offerId and an OffersUriParameterBuilder and returns a Uri.                                                                                    |

## Members

**`public`** [**`OffersDto`**](AtomicMarketApiClient--Offers--OffersDto.md) **``** [**`Offers`**](AtomicMarketApiClient--Offers--OffersApi.md#class\_atomic\_market\_api\_client\_1\_1\_offers\_1\_1\_offers\_api\_1a6ad9622cb51a2bfb25dce65cc64dacd3)**`()`**

This function will make a GET request to the `/offers` endpoint and return the response as a `OffersDto` object.

#### Returns

A list of offers

**`public`** [**`OffersDto`**](AtomicMarketApiClient--Offers--OffersDto.md) **``** [**`Offers`**](AtomicMarketApiClient--Offers--OffersApi.md#class\_atomic\_market\_api\_client\_1\_1\_offers\_1\_1\_offers\_api\_1a8a2c0fdc617e6862e7bfc84e5ab7bca8)**`(` ** [**`OffersUriParameterBuilder`**](AtomicMarketApiClient--Offers--OffersUriParameterBuilder.md) **`offersUriParameterBuilder)`**

It takes a `OffersUriParameterBuilder` object as a parameter, builds a `HttpRequestMessage` object, sends it to the API, and returns a `OffersDto` object.

#### Parameters

* `OffersUriParameterBuilder` This is a class that contains all the parameters that can be passed to the API.

#### Returns

A list of offers.

**`public`** [**`OfferDto`**](AtomicMarketApiClient--Offers--OfferDto.md) **``** [**`Offer`**](AtomicMarketApiClient--Offers--OffersApi.md#class\_atomic\_market\_api\_client\_1\_1\_offers\_1\_1\_offers\_api\_1ae093d07f4cfa336003425539a0a92a13)**`(string offerId)`**

It builds an HTTP GET request to the `OfferUri` endpoint, sends the request to the API, and returns the response as an `OfferDto` object.

#### Parameters

* `offerId` The offer id of the offer you want to retrieve.

#### Returns

A single offer

**`public`** [**`LogsDto`**](AtomicMarketApiClient--LogsDto.md) **``** [**`OfferLogs`**](AtomicMarketApiClient--Offers--OffersApi.md#class\_atomic\_market\_api\_client\_1\_1\_offers\_1\_1\_offers\_api\_1ab8311c9a2d3602ab9cb14d0cad5f9c13)**`(string offerId)`**

This function returns a list of logs for a given offer.

#### Parameters

* `offerId` The offer ID of the offer you want to get the logs for.

#### Returns

A list of logs for the offer.

**`public`** [**`LogsDto`**](AtomicMarketApiClient--LogsDto.md) **``** [**`OfferLogs`**](AtomicMarketApiClient--Offers--OffersApi.md#class\_atomic\_market\_api\_client\_1\_1\_offers\_1\_1\_offers\_api\_1a5403da960dc8ab3c59e75be746be37a7)**`(string offerId,`** [**`OffersUriParameterBuilder`**](AtomicMarketApiClient--Offers--OffersUriParameterBuilder.md) **`schemasUriParameterBuilder)`**

This function returns a list of logs for a specific offer.

#### Parameters

* `offerId` The offer id of the offer you want to get the logs for.
* `OffersUriParameterBuilder` This is a class that contains all the parameters that can be passed to the API.

#### Returns

A list of logs for the offer.

**`private readonly string`** [**`_requestUriBase`**](AtomicMarketApiClient--Offers--OffersApi.md#class\_atomic\_market\_api\_client\_1\_1\_offers\_1\_1\_offers\_api\_1a1854c4909a1013a684af16fb52e8a387)

**`private Uri`** [**`OffersUri`**](AtomicMarketApiClient--Offers--OffersApi.md#class\_atomic\_market\_api\_client\_1\_1\_offers\_1\_1\_offers\_api\_1ada4f3a19377ef670d6e90db76983d1e5)**`()`**

It returns a new Uri object with the value of the \_requestUriBase field, a forward slash, and the word "offers".

**`private Uri`** [**`OffersUri`**](AtomicMarketApiClient--Offers--OffersApi.md#class\_atomic\_market\_api\_client\_1\_1\_offers\_1\_1\_offers\_api\_1a7193d9a8040525ada787f90854c047f8)**`(` ** [**`OffersUriParameterBuilder`**](AtomicMarketApiClient--Offers--OffersUriParameterBuilder.md) **`offersUriParameterBuilder)`**

It takes a `OffersUriParameterBuilder` object and returns a `Uri` object.

#### Parameters

* `OffersUriParameterBuilder` This is a class that builds the query string parameters for the offers endpoint.

**`private Uri`** [**`OfferUri`**](AtomicMarketApiClient--Offers--OffersApi.md#class\_atomic\_market\_api\_client\_1\_1\_offers\_1\_1\_offers\_api\_1a20b72164e6cdeeb7fe55ada62c70f6cb)**`(string offerId)`**

It returns a URI for the offer with the given ID.

#### Parameters

* `offerId` The offer ID of the offer you want to get.

**`private Uri`** [**`OfferLogsUri`**](AtomicMarketApiClient--Offers--OffersApi.md#class\_atomic\_market\_api\_client\_1\_1\_offers\_1\_1\_offers\_api\_1a30e9bba1b128fcfdd45beac4c5529ddc)**`(string offerId)`**

It returns a URI for the offer logs endpoint.

#### Parameters

* `offerId` The ID of the offer you want to get logs for.

**`private Uri`** [**`OfferLogsUri`**](AtomicMarketApiClient--Offers--OffersApi.md#class\_atomic\_market\_api\_client\_1\_1\_offers\_1\_1\_offers\_api\_1a1b159d8d73aa0ae3b1e72fc84bf13b6d)**`(string offerId,`** [**`OffersUriParameterBuilder`**](AtomicMarketApiClient--Offers--OffersUriParameterBuilder.md) **`offersUriParameterBuilder)`**

It takes an offerId and an OffersUriParameterBuilder and returns a Uri.

#### Parameters

* `offerId` The offer ID of the offer you want to get the logs for.
* `OffersUriParameterBuilder` This is a class that builds the query string parameters for the request.
