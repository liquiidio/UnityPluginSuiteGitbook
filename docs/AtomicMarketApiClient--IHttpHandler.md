# interface `AtomicMarketApiClient::IHttpHandler` 

Http handler interface for cross platform specific implementations.

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public void ` [`ClearResponseCache`](AtomicMarketApiClient.md)`()` | Clear cached responses from requests called with Post/GetWithCacheAsync.
`public Task< TResponseData > ` [`PostJsonAsync< TResponseData >`](AtomicMarketApiClient.md)`(string url, object data)` | Make post request with data converted to json asynchronously.
`public Task< TResponseData > ` [`PostJsonAsync< TResponseData >`](AtomicMarketApiClient.md)`(string url, object data, CancellationToken cancellationToken)` | Make post request with data converted to json asynchronously.
`public Task< TResponseData > ` [`GetJsonAsync< TResponseData >`](AtomicMarketApiClient.md)`(string url)` | Make get request asynchronously.
`public Task< TResponseData > ` [`GetJsonAsync< TResponseData >`](AtomicMarketApiClient.md)`(string url, CancellationToken cancellationToken)` | Make get request asynchronously.
`public Task< Stream > ` [`SendAsync`](AtomicMarketApiClient.md)`(HttpRequestMessage request)` | Generic http request sent asynchronously.
`public Task< Stream > ` [`SendAsync`](AtomicMarketApiClient.md)`(HttpRequestMessage request, CancellationToken cancellationToken)` | Generic http request sent asynchronously.
`public void ` [`UpdateResponseDataCache< TResponseData >`](AtomicMarketApiClient.md)`(string hashKey, TResponseData responseData)` | Upsert response data in the data store.
`public Task< Stream > ` [`BuildSendResponse`](AtomicMarketApiClient.md)`(HttpResponseMessage response)` | Convert response to stream.
`public Task< string > ` [`StreamToStringAsync`](AtomicMarketApiClient.md)`(Stream stream)` | Convert stream to a string.

## Members

##### `public void ` [`ClearResponseCache`](AtomicMarketApiClient.md)`()` 

Clear cached responses from requests called with Post/GetWithCacheAsync.

##### `public Task< TResponseData > ` [`PostJsonAsync< TResponseData >`](AtomicMarketApiClient.md)`(string url, object data)` 

Make post request with data converted to json asynchronously.

#### Parameters
* `TResponseData` Response type

#### Parameters
* `url` Url to send the request

* `data` data sent in the body

#### Returns
Response data deserialized to type TResponseData

##### `public Task< TResponseData > ` [`PostJsonAsync< TResponseData >`](AtomicMarketApiClient.md)`(string url, object data, CancellationToken cancellationToken)` 

Make post request with data converted to json asynchronously.

#### Parameters
* `TResponseData` Response type

#### Parameters
* `url` Url to send the request

* `data` data sent in the body

* `cancellationToken` Notification that operation should be canceled

#### Returns
Response data deserialized to type TResponseData

##### `public Task< TResponseData > ` [`GetJsonAsync< TResponseData >`](AtomicMarketApiClient.md)`(string url)` 

Make get request asynchronously.

#### Parameters
* `TResponseData` Response type

#### Parameters
* `url` Url to send the request

#### Returns
Response data deserialized to type TResponseData

##### `public Task< TResponseData > ` [`GetJsonAsync< TResponseData >`](AtomicMarketApiClient.md)`(string url, CancellationToken cancellationToken)` 

Make get request asynchronously.

#### Parameters
* `TResponseData` Response type

#### Parameters
* `url` Url to send the request

* `cancellationToken` Notification that operation should be canceled

#### Returns
Response data deserialized to type TResponseData

##### `public Task< Stream > ` [`SendAsync`](AtomicMarketApiClient.md)`(HttpRequestMessage request)` 

Generic http request sent asynchronously.

#### Parameters
* `request` request body

#### Returns
Stream with response

##### `public Task< Stream > ` [`SendAsync`](AtomicMarketApiClient.md)`(HttpRequestMessage request, CancellationToken cancellationToken)` 

Generic http request sent asynchronously.

#### Parameters
* `request` request body

/// 
#### Parameters
* `cancellationToken` Notification that operation should be canceled

#### Returns
Stream with response

##### `public void ` [`UpdateResponseDataCache< TResponseData >`](AtomicMarketApiClient.md)`(string hashKey, TResponseData responseData)` 

Upsert response data in the data store.

#### Parameters
* `TResponseData` response data type

#### Parameters
* `hashKey` data key

* `responseData` response data

##### `public Task< Stream > ` [`BuildSendResponse`](AtomicMarketApiClient.md)`(HttpResponseMessage response)` 

Convert response to stream.

#### Parameters
* `response` response object

#### Returns
Stream with response

##### `public Task< string > ` [`StreamToStringAsync`](AtomicMarketApiClient.md)`(Stream stream)` 

Convert stream to a string.

#### Parameters
* `stream` 

#### Returns

