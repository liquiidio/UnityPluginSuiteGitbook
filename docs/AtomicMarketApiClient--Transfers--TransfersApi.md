# class `AtomicMarketApiClient::Transfers::TransfersApi` 

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public async Task< ` [`TransfersDto`](AtomicMarketApiClient--Transfers--TransfersDto.md)` > ` [`Transfers`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_api_1a644cc808e9c449e4899c1befcd9db9d6)`()` | This function will return a list of all transfers for the current user.
`public async Task< ` [`TransfersDto`](AtomicMarketApiClient--Transfers--TransfersDto.md)` > ` [`Transfers`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_api_1a5f34ecfb0fd3f456f80dce37510a7772)`(` [`TransfersUriParameterBuilder`](AtomicMarketApiClient--Transfers--TransfersUriParameterBuilder.md)` transfersUriParameterBuilder)` | It returns a list of transfers.
`private readonly string ` [`_requestUriBase`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_api_1a1854c4909a1013a684af16fb52e8a387) | 
`private readonly ` [`IHttpHandler`](AtomicMarketApiClient.md)` ` [`_httpHandler`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_api_1a278528cd3027ee0a4ca8e04964f99674) | 
`private Uri ` [`TransfersUri`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_api_1a75e5cf6cddb62fc9e45fbf831b1d71d1)`()` | It returns a URI for the transfers endpoint.
`private Uri ` [`TransfersUri`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_api_1a9388420fefbd204d7f362bc1386dc980)`(` [`TransfersUriParameterBuilder`](AtomicMarketApiClient--Transfers--TransfersUriParameterBuilder.md)` transfersUriParameterBuilder)` | 

## Members

##### `public async Task< ` [`TransfersDto`](AtomicMarketApiClient--Transfers--TransfersDto.md)` > ` [`Transfers`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_api_1a644cc808e9c449e4899c1befcd9db9d6)`()` 

This function will return a list of all transfers for the current user.

#### Returns
A list of transfers

##### `public async Task< ` [`TransfersDto`](AtomicMarketApiClient--Transfers--TransfersDto.md)` > ` [`Transfers`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_api_1a5f34ecfb0fd3f456f80dce37510a7772)`(` [`TransfersUriParameterBuilder`](AtomicMarketApiClient--Transfers--TransfersUriParameterBuilder.md)` transfersUriParameterBuilder)` 

It returns a list of transfers.

#### Parameters
* `TransfersUriParameterBuilder` This is a class that contains all the parameters that can be passed to the API.

#### Returns
A TransfersDto object.

##### `private readonly string ` [`_requestUriBase`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_api_1a1854c4909a1013a684af16fb52e8a387) 

##### `private readonly ` [`IHttpHandler`](AtomicMarketApiClient.md)` ` [`_httpHandler`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_api_1a278528cd3027ee0a4ca8e04964f99674) 

##### `private Uri ` [`TransfersUri`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_api_1a75e5cf6cddb62fc9e45fbf831b1d71d1)`()` 

It returns a URI for the transfers endpoint.

##### `private Uri ` [`TransfersUri`](#class_atomic_market_api_client_1_1_transfers_1_1_transfers_api_1a9388420fefbd204d7f362bc1386dc980)`(` [`TransfersUriParameterBuilder`](AtomicMarketApiClient--Transfers--TransfersUriParameterBuilder.md)` transfersUriParameterBuilder)` 

