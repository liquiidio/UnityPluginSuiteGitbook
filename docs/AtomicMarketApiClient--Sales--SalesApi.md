# SalesApi

## Summary

| Members                                                                                                                                                                                                                                                                                                                                                    | Descriptions                                                                                                                                                                                        |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `public` [`SalesDto`](AtomicMarketApiClient--Sales--SalesDto.md) `` [`Sales`](AtomicMarketApiClient--Sales--SalesApi.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_api\_1aa0e37cd4086cddc4ba41ff9855d83b9b)`()`                                                                                                                         | It builds an HTTP request, sends it to the API, and returns the response as a SalesDto object.                                                                                                      |
| `public` [`SaleDto`](AtomicMarketApiClient--Sales--SaleDto.md) `` [`Sale`](AtomicMarketApiClient--Sales--SalesApi.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_api\_1a98a3e978a8fbea5e89099f424aee67c4)`(int id)`                                                                                                                      | This function will return a `SaleDto` object from the API.                                                                                                                                          |
| `public` [`SalesDto`](AtomicMarketApiClient--Sales--SalesDto.md) `` [`Sales`](AtomicMarketApiClient--Sales--SalesApi.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_api\_1a8542ba9eda33d0fb33cf44eceaf27ff8)`(` [`SalesUriParameterBuilder`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md) `uriParameterBuilder)`           | It returns a SalesDto object.                                                                                                                                                                       |
| `public` [`SalesDto`](AtomicMarketApiClient--Sales--SalesDto.md) `` [`SalesByTemplate`](AtomicMarketApiClient--Sales--SalesApi.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_api\_1a00f707e3432812eefca67e359b8f7968)`(` [`SalesUriParameterBuilder`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md) `uriParameterBuilder)` | It returns a list of sales.                                                                                                                                                                         |
| `public` [`LogsDto`](AtomicMarketApiClient--LogsDto.md) `` [`SalesLogs`](AtomicMarketApiClient--Sales--SalesApi.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_api\_1acd26501f9678db3b73773e6c34add5d0)`(int id)`                                                                                                                        | This function will return a list of logs for a specific sales order.                                                                                                                                |
| `public` [`LogsDto`](AtomicMarketApiClient--LogsDto.md) `` [`SalesLogs`](AtomicMarketApiClient--Sales--SalesApi.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_api\_1a9ebb72bee2396ee66b1910d701d1d123)`(int id,` [`SalesUriParameterBuilder`](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md) `salesUriParameterBuilder)`    | This function returns a list of logs for a specific sales order.                                                                                                                                    |
| `private readonly string` [`_requestUriBase`](AtomicMarketApiClient--Sales--SalesApi.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_api\_1a1854c4909a1013a684af16fb52e8a387)                                                                                                                                                             |                                                                                                                                                                                                     |
| `private Uri` [`SalesUri`](AtomicMarketApiClient--Sales--SalesApi.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_api\_1a40df74fdccb558ba58338c9fdff8c5cb)`()`                                                                                                                                                                            | It returns a new Uri object with the value of the \_requestUriBase field concatenated with the string "/sales".                                                                                     |
| `private Uri` [`SalesUri`](AtomicMarketApiClient--Sales--SalesApi.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_api\_1a914051441775e99ff18a3552ec756af1)`(` [`IUriParameterBuilder`](AtomicMarketApiClient--Core.md) `salesUriParameterBuilder)`                                                                                        | It takes a `IUriParameterBuilder` as a parameter and returns a `Uri` that is the base request URI with the `/sales` path and the URI parameters built by the `IUriParameterBuilder` appended to it. |
| `private Uri` [`SaleUri`](AtomicMarketApiClient--Sales--SalesApi.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_api\_1a29b670b4d544f1da685ec58f7c8b017b)`(int saleId)`                                                                                                                                                                   | It returns a URI for a sale.                                                                                                                                                                        |
| `private Uri` [`SaleTemplatesUri`](AtomicMarketApiClient--Sales--SalesApi.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_api\_1a2ba48db7c4a7ff8dc946105d3485dd6e)`(` [`IUriParameterBuilder`](AtomicMarketApiClient--Core.md) `salesUriParameterBuilder)`                                                                                | It returns a URI for the `/sales/templates` endpoint.                                                                                                                                               |
| `private Uri` [`SalesLogsUri`](AtomicMarketApiClient--Sales--SalesApi.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_api\_1a3a4cb097be63d1826678f6ccd67e5a21)`(int saleId)`                                                                                                                                                              | It returns a URI for the sales logs endpoint.                                                                                                                                                       |
| `private Uri` [`SalesLogsUri`](AtomicMarketApiClient--Sales--SalesApi.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_api\_1a5ea3cd7f9aa1bc36d78f61c90d44944c)`(int saleId,` [`IUriParameterBuilder`](AtomicMarketApiClient--Core.md) `salesUriParameterBuilder)`                                                                         | It returns a URI for the sales logs endpoint.                                                                                                                                                       |

## Members

**`public`** [**`SalesDto`**](AtomicMarketApiClient--Sales--SalesDto.md) **``** [**`Sales`**](AtomicMarketApiClient--Sales--SalesApi.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_api\_1aa0e37cd4086cddc4ba41ff9855d83b9b)**`()`**

It builds an HTTP request, sends it to the API, and returns the response as a SalesDto object.

#### Returns

A SalesDto object

**`public`** [**`SaleDto`**](AtomicMarketApiClient--Sales--SaleDto.md) **``** [**`Sale`**](AtomicMarketApiClient--Sales--SalesApi.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_api\_1a98a3e978a8fbea5e89099f424aee67c4)**`(int id)`**

This function will return a `SaleDto` object from the API.

#### Parameters

* `id` The id of the sale you want to retrieve.

#### Returns

A SaleDto object

**`public`** [**`SalesDto`**](AtomicMarketApiClient--Sales--SalesDto.md) **``** [**`Sales`**](AtomicMarketApiClient--Sales--SalesApi.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_api\_1a8542ba9eda33d0fb33cf44eceaf27ff8)**`(` ** [**`SalesUriParameterBuilder`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md) **`uriParameterBuilder)`**

It returns a SalesDto object.

#### Parameters

* `SalesUriParameterBuilder` This is a class that contains all the parameters that you want to pass to the API.

#### Returns

A SalesDto object.

**`public`** [**`SalesDto`**](AtomicMarketApiClient--Sales--SalesDto.md) **``** [**`SalesByTemplate`**](AtomicMarketApiClient--Sales--SalesApi.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_api\_1a00f707e3432812eefca67e359b8f7968)**`(` ** [**`SalesUriParameterBuilder`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md) **`uriParameterBuilder)`**

It returns a list of sales.

#### Parameters

* `SalesUriParameterBuilder` This is a class that contains the parameters that will be used to build the URI.

#### Returns

A SalesDto object.

**`public`** [**`LogsDto`**](AtomicMarketApiClient--LogsDto.md) **``** [**`SalesLogs`**](AtomicMarketApiClient--Sales--SalesApi.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_api\_1acd26501f9678db3b73773e6c34add5d0)**`(int id)`**

This function will return a list of logs for a specific sales order.

#### Parameters

* `id` The id of the sales order you want to get the logs for.

#### Returns

A list of logs for a specific sale.

**`public`** [**`LogsDto`**](AtomicMarketApiClient--LogsDto.md) **``** [**`SalesLogs`**](AtomicMarketApiClient--Sales--SalesApi.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_api\_1a9ebb72bee2396ee66b1910d701d1d123)**`(int id,`** [**`SalesUriParameterBuilder`**](AtomicMarketApiClient--Sales--SalesUriParameterBuilder.md) **`salesUriParameterBuilder)`**

This function returns a list of logs for a specific sales order.

#### Parameters

* `id` The id of the sales order
* `SalesUriParameterBuilder` This is a class that contains all the parameters that can be passed to the API.

#### Returns

A LogsDto object

**`private readonly string`** [**`_requestUriBase`**](AtomicMarketApiClient--Sales--SalesApi.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_api\_1a1854c4909a1013a684af16fb52e8a387)

**`private Uri`** [**`SalesUri`**](AtomicMarketApiClient--Sales--SalesApi.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_api\_1a40df74fdccb558ba58338c9fdff8c5cb)**`()`**

It returns a new Uri object with the value of the \_requestUriBase field concatenated with the string "/sales".

**`private Uri`** [**`SalesUri`**](AtomicMarketApiClient--Sales--SalesApi.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_api\_1a914051441775e99ff18a3552ec756af1)**`(` ** [**`IUriParameterBuilder`**](AtomicMarketApiClient--Core.md) **`salesUriParameterBuilder)`**

It takes a `IUriParameterBuilder` as a parameter and returns a `Uri` that is the base request URI with the `/sales` path and the URI parameters built by the `IUriParameterBuilder` appended to it.

#### Parameters

* `IUriParameterBuilder` This is an interface that is used to build the query string parameters for the request.

**`private Uri`** [**`SaleUri`**](AtomicMarketApiClient--Sales--SalesApi.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_api\_1a29b670b4d544f1da685ec58f7c8b017b)**`(int saleId)`**

It returns a URI for a sale.

#### Parameters

* `saleId` The id of the sale to be retrieved.

**`private Uri`** [**`SaleTemplatesUri`**](AtomicMarketApiClient--Sales--SalesApi.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_api\_1a2ba48db7c4a7ff8dc946105d3485dd6e)**`(` ** [**`IUriParameterBuilder`**](AtomicMarketApiClient--Core.md) **`salesUriParameterBuilder)`**

It returns a URI for the `/sales/templates` endpoint.

#### Parameters

* `IUriParameterBuilder` This is a class that is used to build the query string parameters for the request.

**`private Uri`** [**`SalesLogsUri`**](AtomicMarketApiClient--Sales--SalesApi.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_api\_1a3a4cb097be63d1826678f6ccd67e5a21)**`(int saleId)`**

It returns a URI for the sales logs endpoint.

#### Parameters

* `saleId` The id of the sale you want to get the logs for.

**`private Uri`** [**`SalesLogsUri`**](AtomicMarketApiClient--Sales--SalesApi.md#class\_atomic\_market\_api\_client\_1\_1\_sales\_1\_1\_sales\_api\_1a5ea3cd7f9aa1bc36d78f61c90d44944c)**`(int saleId,`** [**`IUriParameterBuilder`**](AtomicMarketApiClient--Core.md) **`salesUriParameterBuilder)`**

It returns a URI for the sales logs endpoint.

#### Parameters

* `saleId` The id of the sale you want to get the logs for.
* `IUriParameterBuilder` This is an interface that is used to build the query string parameters for the request.
