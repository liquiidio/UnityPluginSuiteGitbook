## class `AtomicMarketApiClient::Sales::SalesApi` 

### Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public inline SalesDto `[`Sales`](#class_atomic_market_api_client_1_1_sales_1_1_sales_api_1aa0e37cd4086cddc4ba41ff9855d83b9b)`()` | It builds an HTTP request, sends it to the API, and returns the response as a SalesDto object
`public inline SaleDto `[`Sale`](#class_atomic_market_api_client_1_1_sales_1_1_sales_api_1a98a3e978a8fbea5e89099f424aee67c4)`(int id)` | This function will return a `SaleDto` object from the API
`public inline SalesDto `[`Sales`](#class_atomic_market_api_client_1_1_sales_1_1_sales_api_1a8542ba9eda33d0fb33cf44eceaf27ff8)`(SalesUriParameterBuilder uriParameterBuilder)` | It returns a SalesDto object.
`public inline SalesDto `[`SalesByTemplate`](#class_atomic_market_api_client_1_1_sales_1_1_sales_api_1a00f707e3432812eefca67e359b8f7968)`(SalesUriParameterBuilder uriParameterBuilder)` | It returns a list of sales.
`public inline LogsDto `[`SalesLogs`](#class_atomic_market_api_client_1_1_sales_1_1_sales_api_1acd26501f9678db3b73773e6c34add5d0)`(int id)` | This function will return a list of logs for a specific sales order.
`public inline LogsDto `[`SalesLogs`](#class_atomic_market_api_client_1_1_sales_1_1_sales_api_1a9ebb72bee2396ee66b1910d701d1d123)`(int id, SalesUriParameterBuilder salesUriParameterBuilder)` | This function returns a list of logs for a specific sales order.
`private readonly string `[`_requestUriBase`](#class_atomic_market_api_client_1_1_sales_1_1_sales_api_1a1854c4909a1013a684af16fb52e8a387) | 
`private Uri `[`SalesUri`](#class_atomic_market_api_client_1_1_sales_1_1_sales_api_1a40df74fdccb558ba58338c9fdff8c5cb)`()` | 
`private Uri `[`SalesUri`](#class_atomic_market_api_client_1_1_sales_1_1_sales_api_1a914051441775e99ff18a3552ec756af1)`(IUriParameterBuilder salesUriParameterBuilder)` | 
`private Uri `[`SaleUri`](#class_atomic_market_api_client_1_1_sales_1_1_sales_api_1a29b670b4d544f1da685ec58f7c8b017b)`(int saleId)` | 
`private Uri `[`SaleTemplatesUri`](#class_atomic_market_api_client_1_1_sales_1_1_sales_api_1a2ba48db7c4a7ff8dc946105d3485dd6e)`(IUriParameterBuilder salesUriParameterBuilder)` | 
`private Uri `[`SalesLogsUri`](#class_atomic_market_api_client_1_1_sales_1_1_sales_api_1a3a4cb097be63d1826678f6ccd67e5a21)`(int saleId)` | 
`private Uri `[`SalesLogsUri`](#class_atomic_market_api_client_1_1_sales_1_1_sales_api_1a5ea3cd7f9aa1bc36d78f61c90d44944c)`(int saleId, IUriParameterBuilder salesUriParameterBuilder)` | 

### Members

#### `public inline SalesDto `[`Sales`](#class_atomic_market_api_client_1_1_sales_1_1_sales_api_1aa0e37cd4086cddc4ba41ff9855d83b9b)`()` 

It builds an HTTP request, sends it to the API, and returns the response as a SalesDto object

#### Returns
A SalesDto object

#### `public inline SaleDto `[`Sale`](#class_atomic_market_api_client_1_1_sales_1_1_sales_api_1a98a3e978a8fbea5e89099f424aee67c4)`(int id)` 

This function will return a `SaleDto` object from the API

#### Parameters
* `id` The id of the sale you want to retrieve.

#### Returns
A SaleDto object

#### `public inline SalesDto `[`Sales`](#class_atomic_market_api_client_1_1_sales_1_1_sales_api_1a8542ba9eda33d0fb33cf44eceaf27ff8)`(SalesUriParameterBuilder uriParameterBuilder)` 

It returns a SalesDto object.

#### Parameters
* `SalesUriParameterBuilder` This is a class that contains all the parameters that you want to pass to the API.

#### Returns
A SalesDto object.

#### `public inline SalesDto `[`SalesByTemplate`](#class_atomic_market_api_client_1_1_sales_1_1_sales_api_1a00f707e3432812eefca67e359b8f7968)`(SalesUriParameterBuilder uriParameterBuilder)` 

It returns a list of sales.

#### Parameters
* `SalesUriParameterBuilder` This is a class that contains the parameters that will be used to build the URI.

#### Returns
A SalesDto object.

#### `public inline LogsDto `[`SalesLogs`](#class_atomic_market_api_client_1_1_sales_1_1_sales_api_1acd26501f9678db3b73773e6c34add5d0)`(int id)` 

This function will return a list of logs for a specific sales order.

#### Parameters
* `id` The id of the sales order you want to get the logs for.

#### Returns
A list of logs for a specific sale.

#### `public inline LogsDto `[`SalesLogs`](#class_atomic_market_api_client_1_1_sales_1_1_sales_api_1a9ebb72bee2396ee66b1910d701d1d123)`(int id, SalesUriParameterBuilder salesUriParameterBuilder)` 

This function returns a list of logs for a specific sales order.

#### Parameters
* `id` The id of the sales order

* `SalesUriParameterBuilder` This is a class that contains all the parameters that can be passed to the API.

#### Returns
A LogsDto object

#### `private readonly string `[`_requestUriBase`](#class_atomic_market_api_client_1_1_sales_1_1_sales_api_1a1854c4909a1013a684af16fb52e8a387) 

#### `private Uri `[`SalesUri`](#class_atomic_market_api_client_1_1_sales_1_1_sales_api_1a40df74fdccb558ba58338c9fdff8c5cb)`()` 

#### `private Uri `[`SalesUri`](#class_atomic_market_api_client_1_1_sales_1_1_sales_api_1a914051441775e99ff18a3552ec756af1)`(IUriParameterBuilder salesUriParameterBuilder)` 

#### `private Uri `[`SaleUri`](#class_atomic_market_api_client_1_1_sales_1_1_sales_api_1a29b670b4d544f1da685ec58f7c8b017b)`(int saleId)` 

#### `private Uri `[`SaleTemplatesUri`](#class_atomic_market_api_client_1_1_sales_1_1_sales_api_1a2ba48db7c4a7ff8dc946105d3485dd6e)`(IUriParameterBuilder salesUriParameterBuilder)` 

#### `private Uri `[`SalesLogsUri`](#class_atomic_market_api_client_1_1_sales_1_1_sales_api_1a3a4cb097be63d1826678f6ccd67e5a21)`(int saleId)` 

#### `private Uri `[`SalesLogsUri`](#class_atomic_market_api_client_1_1_sales_1_1_sales_api_1a5ea3cd7f9aa1bc36d78f61c90d44944c)`(int saleId, IUriParameterBuilder salesUriParameterBuilder)` 

