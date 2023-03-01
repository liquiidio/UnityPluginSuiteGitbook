# class `AtomicAssetsApiClient::HttpHandler` 

```
class AtomicAssetsApiClient::HttpHandler
  : public IHttpHandler
```

Http Handler implementation using System.Net.Http.HttpClient.

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`private Dictionary< string, object > ` [`ResponseCache`](#class_atomic_assets_api_client_1_1_http_handler_1a7876042dff97e43c52e7d513f587f93d) | 
`public void ` [`ClearResponseCache`](#class_atomic_assets_api_client_1_1_http_handler_1a905c1143ac0ce07cb71dbb15a60f281e)`()` | Clear cached responses from requests called with Post/GetWithCacheAsync.
`public async Task< TResponseData > ` [`PostJsonAsync< TResponseData >`](#class_atomic_assets_api_client_1_1_http_handler_1a3acdabc747f5839c8beed189ba7abe06)`(string url, object data)` | Make post request with data converted to json asynchronously.
`public async Task< TResponseData > ` [`PostJsonAsync< TResponseData >`](#class_atomic_assets_api_client_1_1_http_handler_1a6fb5dd92b77fcaeb2038038edae5551d)`(string url, object data, CancellationToken cancellationToken)` | Make post request with data converted to json asynchronously.
`public async Task< TResponseData > ` [`GetJsonAsync< TResponseData >`](#class_atomic_assets_api_client_1_1_http_handler_1af5b8a45e43a0ae7cc75ea8ea9159ccc4)`(string url)` | Make get request asynchronously.
`public async Task< TResponseData > ` [`GetJsonAsync< TResponseData >`](#class_atomic_assets_api_client_1_1_http_handler_1a8d9d37e8e56ae19c5c23757e1d7a9f62)`(string url, CancellationToken cancellationToken)` | Make get request asynchronously.
`public async Task< Stream > ` [`SendAsync`](#class_atomic_assets_api_client_1_1_http_handler_1ac92403d0bd960ebce1d47218d70ca5f3)`(HttpRequestMessage request)` | Generic http request sent asynchronously.
`public async Task< Stream > ` [`SendAsync`](#class_atomic_assets_api_client_1_1_http_handler_1a497b180a695ff626038781cb6b47046c)`(HttpRequestMessage request, CancellationToken cancellationToken)` | Generic http request sent asynchronously.
`public void ` [`UpdateResponseDataCache< TResponseData >`](#class_atomic_assets_api_client_1_1_http_handler_1a200c11cf47d108dfee0a09787641aacb)`(string hashKey, TResponseData responseData)` | Upsert response data in the data store.
`public async Task< Stream > ` [`BuildSendResponse`](#class_atomic_assets_api_client_1_1_http_handler_1a0cb6ca360fbbbb71291f4886c599ffed)`(HttpResponseMessage response)` | Convert response to stream.
`public async Task< string > ` [`StreamToStringAsync`](#class_atomic_assets_api_client_1_1_http_handler_1ae8dcc1de6289cc996178a5caff5523e1)`(Stream stream)` | Convert stream to a string.
`public TData ` [`DeserializeJsonFromStream< TData >`](#class_atomic_assets_api_client_1_1_http_handler_1afdb550f8a0dfdb3ad82fd599cd8f89ee)`(Stream stream)` | Generic method to convert a stream with json data to any type.
`public HttpRequestMessage ` [`BuildJsonRequestMessage`](#class_atomic_assets_api_client_1_1_http_handler_1a50135374e42f516b4f9d7fd7926f6c9c)`(string url, object data)` | Build json request data from object data.

## Members

##### `private Dictionary< string, object > ` [`ResponseCache`](#class_atomic_assets_api_client_1_1_http_handler_1a7876042dff97e43c52e7d513f587f93d) 

##### `public void ` [`ClearResponseCache`](#class_atomic_assets_api_client_1_1_http_handler_1a905c1143ac0ce07cb71dbb15a60f281e)`()` 

Clear cached responses from requests called with Post/GetWithCacheAsync.

##### `public async Task< TResponseData > ` [`PostJsonAsync< TResponseData >`](#class_atomic_assets_api_client_1_1_http_handler_1a3acdabc747f5839c8beed189ba7abe06)`(string url, object data)` 

Make post request with data converted to json asynchronously.

#### Parameters
* `TResponseData` Response type

#### Parameters
* `url` Url to send the request

* `data` data sent in the body

#### Returns
Response data deserialized to type TResponseData

##### `public async Task< TResponseData > ` [`PostJsonAsync< TResponseData >`](#class_atomic_assets_api_client_1_1_http_handler_1a6fb5dd92b77fcaeb2038038edae5551d)`(string url, object data, CancellationToken cancellationToken)` 

Make post request with data converted to json asynchronously.

#### Parameters
* `TResponseData` Response type

#### Parameters
* `url` Url to send the request

* `data` data sent in the body

* `cancellationToken` Notification that operation should be canceled

#### Returns
Response data deserialized to type TResponseData

##### `public async Task< TResponseData > ` [`GetJsonAsync< TResponseData >`](#class_atomic_assets_api_client_1_1_http_handler_1af5b8a45e43a0ae7cc75ea8ea9159ccc4)`(string url)` 

Make get request asynchronously.

#### Parameters
* `TResponseData` Response type

#### Parameters
* `url` Url to send the request

#### Returns
Response data deserialized to type TResponseData

##### `public async Task< TResponseData > ` [`GetJsonAsync< TResponseData >`](#class_atomic_assets_api_client_1_1_http_handler_1a8d9d37e8e56ae19c5c23757e1d7a9f62)`(string url, CancellationToken cancellationToken)` 

Make get request asynchronously.

#### Parameters
* `TResponseData` Response type

#### Parameters
* `url` Url to send the request

* `cancellationToken` Notification that operation should be canceled

#### Returns
Response data deserialized to type TResponseData

##### `public async Task< Stream > ` [`SendAsync`](#class_atomic_assets_api_client_1_1_http_handler_1ac92403d0bd960ebce1d47218d70ca5f3)`(HttpRequestMessage request)` 

Generic http request sent asynchronously.

#### Parameters
* `request` request body

#### Returns
Stream with response

##### `public async Task< Stream > ` [`SendAsync`](#class_atomic_assets_api_client_1_1_http_handler_1a497b180a695ff626038781cb6b47046c)`(HttpRequestMessage request, CancellationToken cancellationToken)` 

Generic http request sent asynchronously.

#### Parameters
* `request` request body

/// 
#### Parameters
* `cancellationToken` Notification that operation should be canceled

#### Returns
Stream with response

##### `public void ` [`UpdateResponseDataCache< TResponseData >`](#class_atomic_assets_api_client_1_1_http_handler_1a200c11cf47d108dfee0a09787641aacb)`(string hashKey, TResponseData responseData)` 

Upsert response data in the data store.

#### Parameters
* `TResponseData` response data type

#### Parameters
* `hashKey` data key

* `responseData` response data

##### `public async Task< Stream > ` [`BuildSendResponse`](#class_atomic_assets_api_client_1_1_http_handler_1a0cb6ca360fbbbb71291f4886c599ffed)`(HttpResponseMessage response)` 

Convert response to stream.

#### Parameters
* `response` response object

#### Returns
Stream with response

##### `public async Task< string > ` [`StreamToStringAsync`](#class_atomic_assets_api_client_1_1_http_handler_1ae8dcc1de6289cc996178a5caff5523e1)`(Stream stream)` 

Convert stream to a string.

#### Parameters
* `stream` 

#### Returns

##### `public TData ` [`DeserializeJsonFromStream< TData >`](#class_atomic_assets_api_client_1_1_http_handler_1afdb550f8a0dfdb3ad82fd599cd8f89ee)`(Stream stream)` 

Generic method to convert a stream with json data to any type.

#### Parameters
* `TData` type to convert

#### Parameters
* `stream` stream with json content

#### Returns
TData object

##### `public HttpRequestMessage ` [`BuildJsonRequestMessage`](#class_atomic_assets_api_client_1_1_http_handler_1a50135374e42f516b4f9d7fd7926f6c9c)`(string url, object data)` 

Build json request data from object data.

#### Parameters
* `url` Url to send the request

* `data` object data

#### Returns
request message

