# class `AtomicMarketApiClient::Sales::SalesApi` 

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public async Task< ` [`SalesDto`](AtomicMarketApiClient--Sales--SalesDto.md)` > ` [`Sales`](#class_atomic_market_api_client_1_1_sales_1_1_sales_api_1ac812e90e195c900bf42740aa1b8b4e43)`()` | It builds an HTTP request, sends it to the API, and returns the response as a SalesDto object.
`public async Task< ` [`SaleDto`](AtomicMarketApiClient--Sales--SaleDto.md)` > ` [`Sale`](#class_atomic_market_api_client_1_1_sales_1_1_sales_api_1ae290015906a9c865836233d2cf0a7e94)`(int id)` | This function will return a `SaleDto` object from the API.
`public async Task< ` [`SalesDto`](AtomicMarketApiClient--Sales--SalesDto.md)` > ` [`Sales`](#class_atomic_market_api_client_1_1_sales_1_1_sales_api_1af7e32ade487739a410837c8174800bac)`(` [`SalesUriParameterBuilder`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md)` uriParameterBuilder)` | It returns a SalesDto object.
`public async Task< ` [`SalesDto`](AtomicMarketApiClient--Sales--SalesDto.md)` > ` [`SalesByTemplate`](#class_atomic_market_api_client_1_1_sales_1_1_sales_api_1ac63dd5529936a0e48d6f13d00773500b)`(` [`SalesUriParameterBuilder`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md)` uriParameterBuilder)` | It returns a list of sales.
`public async Task< ` [`LogsDto`](AtomicMarketApiClient--LogsDto.md)` > ` [`SalesLogs`](#class_atomic_market_api_client_1_1_sales_1_1_sales_api_1a255d5eb71b86ee81343d7e42d8080499)`(int id)` | This function will return a list of logs for a specific sales order.
`public async Task< ` [`LogsDto`](AtomicMarketApiClient--LogsDto.md)` > ` [`SalesLogs`](#class_atomic_market_api_client_1_1_sales_1_1_sales_api_1a4a61d1dace1a235a75fc3fb7c11e9090)`(int id, ` [`SalesUriParameterBuilder`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md)` salesUriParameterBuilder)` | This function returns a list of logs for a specific sales order.
`private readonly string ` [`_requestUriBase`](#class_atomic_market_api_client_1_1_sales_1_1_sales_api_1a1854c4909a1013a684af16fb52e8a387) | 
`private readonly ` [`IHttpHandler`](AtomicMarketApiClient.md)` ` [`_httpHandler`](#class_atomic_market_api_client_1_1_sales_1_1_sales_api_1a278528cd3027ee0a4ca8e04964f99674) | 
`private Uri ` [`SalesUri`](#class_atomic_market_api_client_1_1_sales_1_1_sales_api_1a40df74fdccb558ba58338c9fdff8c5cb)`()` | 
`private Uri ` [`SalesUri`](#class_atomic_market_api_client_1_1_sales_1_1_sales_api_1a914051441775e99ff18a3552ec756af1)`(` [`IUriParameterBuilder`](AtomicMarketApiClient.md)` salesUriParameterBuilder)` | It takes a `IUriParameterBuilder` as a parameter and returns a `Uri` that is the base request URI with the `/sales` path and the URI parameters built by the `IUriParameterBuilder` appended to it.
`private Uri ` [`SaleUri`](#class_atomic_market_api_client_1_1_sales_1_1_sales_api_1a29b670b4d544f1da685ec58f7c8b017b)`(int saleId)` | It returns a URI for a sale.
`private Uri ` [`SaleTemplatesUri`](#class_atomic_market_api_client_1_1_sales_1_1_sales_api_1a2ba48db7c4a7ff8dc946105d3485dd6e)`(` [`IUriParameterBuilder`](AtomicMarketApiClient.md)` salesUriParameterBuilder)` | It returns a URI for the `/sales/templates` endpoint.
`private Uri ` [`SalesLogsUri`](#class_atomic_market_api_client_1_1_sales_1_1_sales_api_1a3a4cb097be63d1826678f6ccd67e5a21)`(int saleId)` | It returns a URI for the sales logs endpoint.
`private Uri ` [`SalesLogsUri`](#class_atomic_market_api_client_1_1_sales_1_1_sales_api_1a5ea3cd7f9aa1bc36d78f61c90d44944c)`(int saleId, ` [`IUriParameterBuilder`](AtomicMarketApiClient.md)` salesUriParameterBuilder)` | It returns a URI for the sales logs endpoint.

## Members

##### `public async Task< ` [`SalesDto`](AtomicMarketApiClient--Sales--SalesDto.md)` > ` [`Sales`](#class_atomic_market_api_client_1_1_sales_1_1_sales_api_1ac812e90e195c900bf42740aa1b8b4e43)`()` 

It builds an HTTP request, sends it to the API, and returns the response as a SalesDto object.

#### Returns
A SalesDto object

##### `public async Task< ` [`SaleDto`](AtomicMarketApiClient--Sales--SaleDto.md)` > ` [`Sale`](#class_atomic_market_api_client_1_1_sales_1_1_sales_api_1ae290015906a9c865836233d2cf0a7e94)`(int id)` 

This function will return a `SaleDto` object from the API.

#### Parameters
* `id` The id of the sale you want to retrieve.

#### Returns
A SaleDto object

##### `public async Task< ` [`SalesDto`](AtomicMarketApiClient--Sales--SalesDto.md)` > ` [`Sales`](#class_atomic_market_api_client_1_1_sales_1_1_sales_api_1af7e32ade487739a410837c8174800bac)`(` [`SalesUriParameterBuilder`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md)` uriParameterBuilder)` 

It returns a SalesDto object.

#### Parameters
* `SalesUriParameterBuilder` This is a class that contains all the parameters that you want to pass to the API.

#### Returns
A SalesDto object.

##### `public async Task< ` [`SalesDto`](AtomicMarketApiClient--Sales--SalesDto.md)` > ` [`SalesByTemplate`](#class_atomic_market_api_client_1_1_sales_1_1_sales_api_1ac63dd5529936a0e48d6f13d00773500b)`(` [`SalesUriParameterBuilder`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md)` uriParameterBuilder)` 

It returns a list of sales.

#### Parameters
* `SalesUriParameterBuilder` This is a class that contains the parameters that will be used to build the URI.

#### Returns
A SalesDto object.

##### `public async Task< ` [`LogsDto`](AtomicMarketApiClient--LogsDto.md)` > ` [`SalesLogs`](#class_atomic_market_api_client_1_1_sales_1_1_sales_api_1a255d5eb71b86ee81343d7e42d8080499)`(int id)` 

This function will return a list of logs for a specific sales order.

#### Parameters
* `id` The id of the sales order you want to get the logs for.

#### Returns
A list of logs for a specific sale.

##### `public async Task< ` [`LogsDto`](AtomicMarketApiClient--LogsDto.md)` > ` [`SalesLogs`](#class_atomic_market_api_client_1_1_sales_1_1_sales_api_1a4a61d1dace1a235a75fc3fb7c11e9090)`(int id, ` [`SalesUriParameterBuilder`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md)` salesUriParameterBuilder)` 

This function returns a list of logs for a specific sales order.

#### Parameters
* `id` The id of the sales order

* `SalesUriParameterBuilder` This is a class that contains all the parameters that can be passed to the API.

#### Returns
A LogsDto object

##### `private readonly string ` [`_requestUriBase`](#class_atomic_market_api_client_1_1_sales_1_1_sales_api_1a1854c4909a1013a684af16fb52e8a387) 

##### `private readonly ` [`IHttpHandler`](AtomicMarketApiClient.md)` ` [`_httpHandler`](#class_atomic_market_api_client_1_1_sales_1_1_sales_api_1a278528cd3027ee0a4ca8e04964f99674) 

##### `private Uri ` [`SalesUri`](#class_atomic_market_api_client_1_1_sales_1_1_sales_api_1a40df74fdccb558ba58338c9fdff8c5cb)`()` 

##### `private Uri ` [`SalesUri`](#class_atomic_market_api_client_1_1_sales_1_1_sales_api_1a914051441775e99ff18a3552ec756af1)`(` [`IUriParameterBuilder`](AtomicMarketApiClient.md)` salesUriParameterBuilder)` 

It takes a `IUriParameterBuilder` as a parameter and returns a `Uri` that is the base request URI with the `/sales` path and the URI parameters built by the `IUriParameterBuilder` appended to it.

#### Parameters
* `IUriParameterBuilder` This is an interface that is used to build the query string parameters for the request.

##### `private Uri ` [`SaleUri`](#class_atomic_market_api_client_1_1_sales_1_1_sales_api_1a29b670b4d544f1da685ec58f7c8b017b)`(int saleId)` 

It returns a URI for a sale.

#### Parameters
* `saleId` The id of the sale to be retrieved.

##### `private Uri ` [`SaleTemplatesUri`](#class_atomic_market_api_client_1_1_sales_1_1_sales_api_1a2ba48db7c4a7ff8dc946105d3485dd6e)`(` [`IUriParameterBuilder`](AtomicMarketApiClient.md)` salesUriParameterBuilder)` 

It returns a URI for the `/sales/templates` endpoint.

#### Parameters
* `IUriParameterBuilder` This is a class that is used to build the query string parameters for the request.

##### `private Uri ` [`SalesLogsUri`](#class_atomic_market_api_client_1_1_sales_1_1_sales_api_1a3a4cb097be63d1826678f6ccd67e5a21)`(int saleId)` 

It returns a URI for the sales logs endpoint.

#### Parameters
* `saleId` The id of the sale you want to get the logs for.

##### `private Uri ` [`SalesLogsUri`](#class_atomic_market_api_client_1_1_sales_1_1_sales_api_1a5ea3cd7f9aa1bc36d78f61c90d44944c)`(int saleId, ` [`IUriParameterBuilder`](AtomicMarketApiClient.md)` salesUriParameterBuilder)` 

It returns a URI for the sales logs endpoint.

#### Parameters
* `saleId` The id of the sale you want to get the logs for.

* `IUriParameterBuilder` This is an interface that is used to build the query string parameters for the request.

