# class `AtomicMarketApiClient::BuyOffers::BuyOffersApi` 

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public ` [`BuyOffersDto`](.github/workflows/documentation/md/AtomicMarketApiClient--BuyOffers--BuyOffersDto.md#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_dto)` ` [`BuyOffers`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_api_1a0e6b99940a905cfd19485063f9fd0b3a)`()` | This function will return a list of buy offers for a given market.
`public ` [`BuyOffersDto`](.github/workflows/documentation/md/AtomicMarketApiClient--BuyOffers--BuyOffersDto.md#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_dto)` ` [`BuyOffers`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_api_1a10d849398ec68f3b4ab532a305338392)`(` [`BuyOffersUriParameterBuilder`](.github/workflows/documentation/md/AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder)` uriParametersBuilder)` | It takes a `BuyOffersUriParameterBuilder` object as a parameter, builds a `HttpRequestMessage` object, sends it to the API, and returns a `BuyOffersDto` object.
`public ` [`BuyOfferDto`](.github/workflows/documentation/md/AtomicMarketApiClient--BuyOffers--BuyOfferDto.md#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offer_dto)` ` [`BuyOffer`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_api_1a93bddeca4f54c498859c1971d6e1e880)`(int id)` | This function will return a BuyOfferDto object from the API.
`public ` [`LogsDto`](.github/workflows/documentation/md/AtomicMarketApiClient--LogsDto.md#class_atomic_market_api_client_1_1_logs_dto)` ` [`BuyOffersLogs`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_api_1a34728ea9bf4b7355eaeb587ab801b9ad)`(int id)` | This function returns a list of logs for a specific buy offer.
`public ` [`LogsDto`](.github/workflows/documentation/md/AtomicMarketApiClient--LogsDto.md#class_atomic_market_api_client_1_1_logs_dto)` ` [`BuyOffersLogs`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_api_1a87428b414e7c5c121c4a674044092edd)`(int id, ` [`BuyOffersUriParameterBuilder`](.github/workflows/documentation/md/AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder)` uriParametersBuilder)` | This function returns a list of logs for a specific buy offer.
`private readonly string ` [`_requestUriBase`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_api_1a1854c4909a1013a684af16fb52e8a387) | 
`private Uri ` [`BuyOffersUri`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_api_1a77184baf47cda5ecb4754ef80463e995)`()` | It returns a URI that points to the buy offers endpoint.
`private Uri ` [`BuyOffersUri`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_api_1a5659174e3eb65e6307a8c9729c3f4eb4)`(` [`IUriParameterBuilder`](.github/workflows/documentation/md/AtomicMarketApiClient--Core.md#interface_atomic_market_api_client_1_1_core_1_1_i_uri_parameter_builder)` uriParameterBuilder)` | It returns a URI for the buy offers endpoint.
`private Uri ` [`BuyOffersUri`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_api_1a388a01bee41055f5cccdf8764e5d62e5)`(int id)` | It returns a URI for a specific buy offer.
`private Uri ` [`BuyOffersLogsUri`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_api_1a7076f6e8b7ec4dabaa498a2d2d01b54b)`(int id)` | It returns a URI for the buy offer logs endpoint.
`private Uri ` [`BuyOffersLogsUri`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_api_1a7ed3e53878f5d4cddbd4793a0e3cafda)`(int id, ` [`IUriParameterBuilder`](.github/workflows/documentation/md/AtomicMarketApiClient--Core.md#interface_atomic_market_api_client_1_1_core_1_1_i_uri_parameter_builder)` uriParameterBuilder)` | This function returns a URI for the BuyOffersLogs endpoint

## Members

##### `public ` [`BuyOffersDto`](.github/workflows/documentation/md/AtomicMarketApiClient--BuyOffers--BuyOffersDto.md#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_dto)` ` [`BuyOffers`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_api_1a0e6b99940a905cfd19485063f9fd0b3a)`()` 

This function will return a list of buy offers for a given market.

#### Returns
A list of buy offers.

##### `public ` [`BuyOffersDto`](.github/workflows/documentation/md/AtomicMarketApiClient--BuyOffers--BuyOffersDto.md#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_dto)` ` [`BuyOffers`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_api_1a10d849398ec68f3b4ab532a305338392)`(` [`BuyOffersUriParameterBuilder`](.github/workflows/documentation/md/AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder)` uriParametersBuilder)` 

It takes a `BuyOffersUriParameterBuilder` object as a parameter, builds a `HttpRequestMessage` object, sends it to the API, and returns a `BuyOffersDto` object.

#### Parameters
* `BuyOffersUriParameterBuilder` This is a class that inherits from the IUriParameterBuilder interface. This interface is used to build the query string parameters for the API call.

#### Returns
A BuyOffersDto object.

##### `public ` [`BuyOfferDto`](.github/workflows/documentation/md/AtomicMarketApiClient--BuyOffers--BuyOfferDto.md#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offer_dto)` ` [`BuyOffer`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_api_1a93bddeca4f54c498859c1971d6e1e880)`(int id)` 

This function will return a BuyOfferDto object from the API.

#### Parameters
* `id` The id of the buy offer you want to retrieve.

#### Returns
A BuyOfferDto object

##### `public ` [`LogsDto`](.github/workflows/documentation/md/AtomicMarketApiClient--LogsDto.md#class_atomic_market_api_client_1_1_logs_dto)` ` [`BuyOffersLogs`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_api_1a34728ea9bf4b7355eaeb587ab801b9ad)`(int id)` 

This function returns a list of logs for a specific buy offer.

#### Parameters
* `id` The id of the buy offer.

#### Returns
A list of logs for the buy offer with the given id.

##### `public ` [`LogsDto`](.github/workflows/documentation/md/AtomicMarketApiClient--LogsDto.md#class_atomic_market_api_client_1_1_logs_dto)` ` [`BuyOffersLogs`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_api_1a87428b414e7c5c121c4a674044092edd)`(int id, ` [`BuyOffersUriParameterBuilder`](.github/workflows/documentation/md/AtomicMarketApiClient--BuyOffers--BuyOffersUriParameterBuilder.md#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_uri_parameter_builder)` uriParametersBuilder)` 

This function returns a list of logs for a specific buy offer.

#### Parameters
* `id` The id of the buy offer

* `BuyOffersUriParameterBuilder` This is a class that contains all the parameters that can be passed to the API.

#### Returns
A list of logs for the buy offer.

##### `private readonly string ` [`_requestUriBase`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_api_1a1854c4909a1013a684af16fb52e8a387) 

##### `private Uri ` [`BuyOffersUri`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_api_1a77184baf47cda5ecb4754ef80463e995)`()` 

It returns a URI that points to the buy offers endpoint.

##### `private Uri ` [`BuyOffersUri`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_api_1a5659174e3eb65e6307a8c9729c3f4eb4)`(` [`IUriParameterBuilder`](.github/workflows/documentation/md/AtomicMarketApiClient--Core.md#interface_atomic_market_api_client_1_1_core_1_1_i_uri_parameter_builder)` uriParameterBuilder)` 

It returns a URI for the buy offers endpoint.

#### Parameters
* `IUriParameterBuilder` This is an interface that is used to build the query string parameters for the request.

##### `private Uri ` [`BuyOffersUri`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_api_1a388a01bee41055f5cccdf8764e5d62e5)`(int id)` 

It returns a URI for a specific buy offer.

#### Parameters
* `id` The id of the buy offer you want to get.

##### `private Uri ` [`BuyOffersLogsUri`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_api_1a7076f6e8b7ec4dabaa498a2d2d01b54b)`(int id)` 

It returns a URI for the buy offer logs endpoint.

#### Parameters
* `id` The id of the buy offer you want to get the logs for.

##### `private Uri ` [`BuyOffersLogsUri`](#class_atomic_market_api_client_1_1_buy_offers_1_1_buy_offers_api_1a7ed3e53878f5d4cddbd4793a0e3cafda)`(int id, ` [`IUriParameterBuilder`](.github/workflows/documentation/md/AtomicMarketApiClient--Core.md#interface_atomic_market_api_client_1_1_core_1_1_i_uri_parameter_builder)` uriParameterBuilder)` 

This function returns a URI for the BuyOffersLogs endpoint

#### Parameters
* `id` The id of the buy offer you want to get the logs for.

* `IUriParameterBuilder` This is an interface that is used to build the query string parameters.

