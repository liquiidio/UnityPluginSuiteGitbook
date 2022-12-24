# interface `EosSharp::Core::Interfaces::IHttpHandler` 

Http handler interface for cross platform specific implementations.

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public void ` [`ClearResponseCache`](EosSharp--Core--Interfaces.md)`()` | Clear cached responses from requests called with Post/GetWithCacheAsync.
`public Task< TResponseData > ` [`PostJsonAsync< TResponseData >`](EosSharp--Core--Interfaces.md)`(string url, object data)` | Make post request with data converted to json asynchronously.
`public Task< TResponseData > ` [`PostJsonAsync< TResponseData >`](EosSharp--Core--Interfaces.md)`(string url, object data, CancellationToken cancellationToken)` | Make post request with data converted to json asynchronously.
`public Task< TResponseData > ` [`PostJsonWithCacheAsync< TResponseData >`](EosSharp--Core--Interfaces.md)`(string url, object data, bool reload)` | Make post request with data converted to json asynchronously. Response is cached based on input (url, data)
`public Task< TResponseData > ` [`PostJsonWithCacheAsync< TResponseData >`](EosSharp--Core--Interfaces.md)`(string url, object data, CancellationToken cancellationToken, bool reload)` | Make post request with data converted to json asynchronously. Response is cached based on input (url, data)
`public Task< TResponseData > ` [`GetJsonAsync< TResponseData >`](EosSharp--Core--Interfaces.md)`(string url)` | Make get request asynchronously.
`public Task< TResponseData > ` [`GetJsonAsync< TResponseData >`](EosSharp--Core--Interfaces.md)`(string url, CancellationToken cancellationToken)` | Make get request asynchronously.
`public Task< Stream > ` [`SendAsync`](EosSharp--Core--Interfaces.md)`(HttpRequestMessage request)` | Generic http request sent asynchronously.
`public Task< Stream > ` [`SendAsync`](EosSharp--Core--Interfaces.md)`(HttpRequestMessage request, CancellationToken cancellationToken)` | Generic http request sent asynchronously.
`public void ` [`UpdateResponseDataCache< TResponseData >`](EosSharp--Core--Interfaces.md)`(string hashKey, TResponseData responseData)` | Upsert response data in the data store.
`public string ` [`GetRequestHashKey`](EosSharp--Core--Interfaces.md)`(string url, object data)` | Calculate request unique hash key.
`public Task< Stream > ` [`BuildSendResponse`](EosSharp--Core--Interfaces.md)`(HttpResponseMessage response)` | Convert response to stream.
`public Task< string > ` [`StreamToStringAsync`](EosSharp--Core--Interfaces.md)`(Stream stream)` | Convert stream to a string.

## Members

##### `public void ` [`ClearResponseCache`](EosSharp--Core--Interfaces.md)`()` 

Clear cached responses from requests called with Post/GetWithCacheAsync.

##### `public Task< TResponseData > ` [`PostJsonAsync< TResponseData >`](EosSharp--Core--Interfaces.md)`(string url, object data)` 

Make post request with data converted to json asynchronously.

#### Parameters
* `TResponseData` Response type

#### Parameters
* `url` Url to send the request

* `data` data sent in the body

#### Returns
Response data deserialized to type TResponseData

##### `public Task< TResponseData > ` [`PostJsonAsync< TResponseData >`](EosSharp--Core--Interfaces.md)`(string url, object data, CancellationToken cancellationToken)` 

Make post request with data converted to json asynchronously.

#### Parameters
* `TResponseData` Response type

#### Parameters
* `url` Url to send the request

* `data` data sent in the body

* `cancellationToken` Notification that operation should be canceled

#### Returns
Response data deserialized to type TResponseData

##### `public Task< TResponseData > ` [`PostJsonWithCacheAsync< TResponseData >`](EosSharp--Core--Interfaces.md)`(string url, object data, bool reload)` 

Make post request with data converted to json asynchronously. Response is cached based on input (url, data)

#### Parameters
* `TResponseData` Response type

#### Parameters
* `url` Url to send the request

* `data` data sent in the body

* `reload` ignore cached value and make a request caching the result

#### Returns
Response data deserialized to type TResponseData

##### `public Task< TResponseData > ` [`PostJsonWithCacheAsync< TResponseData >`](EosSharp--Core--Interfaces.md)`(string url, object data, CancellationToken cancellationToken, bool reload)` 

Make post request with data converted to json asynchronously. Response is cached based on input (url, data)

#### Parameters
* `TResponseData` Response type

#### Parameters
* `url` Url to send the request

* `data` data sent in the body

* `cancellationToken` Notification that operation should be canceled

* `reload` ignore cached value and make a request caching the result

#### Returns
Response data deserialized to type TResponseData

##### `public Task< TResponseData > ` [`GetJsonAsync< TResponseData >`](EosSharp--Core--Interfaces.md)`(string url)` 

Make get request asynchronously.

#### Parameters
* `TResponseData` Response type

#### Parameters
* `url` Url to send the request

#### Returns
Response data deserialized to type TResponseData

##### `public Task< TResponseData > ` [`GetJsonAsync< TResponseData >`](EosSharp--Core--Interfaces.md)`(string url, CancellationToken cancellationToken)` 

Make get request asynchronously.

#### Parameters
* `TResponseData` Response type

#### Parameters
* `url` Url to send the request

* `cancellationToken` Notification that operation should be canceled

#### Returns
Response data deserialized to type TResponseData

##### `public Task< Stream > ` [`SendAsync`](EosSharp--Core--Interfaces.md)`(HttpRequestMessage request)` 

Generic http request sent asynchronously.

#### Parameters
* `request` request body

#### Returns
Stream with response

##### `public Task< Stream > ` [`SendAsync`](EosSharp--Core--Interfaces.md)`(HttpRequestMessage request, CancellationToken cancellationToken)` 

Generic http request sent asynchronously.

#### Parameters
* `request` request body

/// 
#### Parameters
* `cancellationToken` Notification that operation should be canceled

#### Returns
Stream with response

##### `public void ` [`UpdateResponseDataCache< TResponseData >`](EosSharp--Core--Interfaces.md)`(string hashKey, TResponseData responseData)` 

Upsert response data in the data store.

#### Parameters
* `TResponseData` response data type

#### Parameters
* `hashKey` data key

* `responseData` response data

##### `public string ` [`GetRequestHashKey`](EosSharp--Core--Interfaces.md)`(string url, object data)` 

Calculate request unique hash key.

#### Parameters
* `url` Url to send the request

* `data` data sent in the body

#### Returns

##### `public Task< Stream > ` [`BuildSendResponse`](EosSharp--Core--Interfaces.md)`(HttpResponseMessage response)` 

Convert response to stream.

#### Parameters
* `response` response object

#### Returns
Stream with response

##### `public Task< string > ` [`StreamToStringAsync`](EosSharp--Core--Interfaces.md)`(Stream stream)` 

Convert stream to a string.

#### Parameters
* `stream` 

#### Returns

