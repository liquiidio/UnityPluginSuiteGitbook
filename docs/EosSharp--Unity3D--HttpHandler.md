# class `EosSharp::Unity3D::HttpHandler` 

```
class EosSharp::Unity3D::HttpHandler
  : public IHttpHandler
```

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`private Dictionary< string, object > ` [`ResponseCache`](#class_eos_sharp_1_1_unity3_d_1_1_http_handler_1a7876042dff97e43c52e7d513f587f93d) | 
`public void ` [`ClearResponseCache`](#class_eos_sharp_1_1_unity3_d_1_1_http_handler_1a905c1143ac0ce07cb71dbb15a60f281e)`()` | Clear cached responses from requests called with Post/GetWithCacheAsync.
`public async Task< TResponseData > ` [`PostJsonAsync< TResponseData >`](#class_eos_sharp_1_1_unity3_d_1_1_http_handler_1a3acdabc747f5839c8beed189ba7abe06)`(string url, object data)` | Make post request with data converted to json asynchronously.
`public Task< TResponseData > ` [`PostJsonAsync< TResponseData >`](#class_eos_sharp_1_1_unity3_d_1_1_http_handler_1ad8c1c8b93d652ff78180c3667748c36c)`(string url, object data, CancellationToken cancellationToken)` | Make post request with data converted to json asynchronously.
`public async Task< TResponseData > ` [`PostJsonWithCacheAsync< TResponseData >`](#class_eos_sharp_1_1_unity3_d_1_1_http_handler_1a8ca47b5765835b92420fd6bc994b7c2c)`(string url, object data, bool reload)` | Make post request with data converted to json asynchronously. Response is cached based on input (url, data)
`public Task< TResponseData > ` [`PostJsonWithCacheAsync< TResponseData >`](#class_eos_sharp_1_1_unity3_d_1_1_http_handler_1aa4ee8fb2e366dfe1fdc96c74dce5e2ee)`(string url, object data, CancellationToken cancellationToken, bool reload)` | Make post request with data converted to json asynchronously. Response is cached based on input (url, data)
`public async Task< TResponseData > ` [`GetJsonAsync< TResponseData >`](#class_eos_sharp_1_1_unity3_d_1_1_http_handler_1af5b8a45e43a0ae7cc75ea8ea9159ccc4)`(string url)` | Make get request asynchronously.
`public Task< TResponseData > ` [`GetJsonAsync< TResponseData >`](#class_eos_sharp_1_1_unity3_d_1_1_http_handler_1ae3ed7e871278e7dd7def051a32f85c06)`(string url, CancellationToken cancellationToken)` | Make get request asynchronously.
`public async Task< Stream > ` [`SendAsync`](#class_eos_sharp_1_1_unity3_d_1_1_http_handler_1ac92403d0bd960ebce1d47218d70ca5f3)`(HttpRequestMessage request)` | Generic http request sent asynchronously.
`public async Task< Stream > ` [`SendAsync`](#class_eos_sharp_1_1_unity3_d_1_1_http_handler_1a497b180a695ff626038781cb6b47046c)`(HttpRequestMessage request, CancellationToken cancellationToken)` | Generic http request sent asynchronously.
`public void ` [`UpdateResponseDataCache< TResponseData >`](#class_eos_sharp_1_1_unity3_d_1_1_http_handler_1a200c11cf47d108dfee0a09787641aacb)`(string hashKey, TResponseData responseData)` | Upsert response data in the data store.
`public string ` [`GetRequestHashKey`](#class_eos_sharp_1_1_unity3_d_1_1_http_handler_1a8ed4413ae2e52a2698c85154127f471a)`(string url, object data)` | Calculate request unique hash key.
`public async Task< Stream > ` [`BuildSendResponse`](#class_eos_sharp_1_1_unity3_d_1_1_http_handler_1a0cb6ca360fbbbb71291f4886c599ffed)`(HttpResponseMessage response)` | Convert response to stream.
`public async Task< string > ` [`StreamToStringAsync`](#class_eos_sharp_1_1_unity3_d_1_1_http_handler_1ae8dcc1de6289cc996178a5caff5523e1)`(Stream stream)` | Convert stream to a string.
`private static UnityWebRequest ` [`BuildUnityWebRequest`](#class_eos_sharp_1_1_unity3_d_1_1_http_handler_1a73110762fd141498d5f63e663a0df785)`(string url, string verb, object data)` | Build unity web request.
`private static ` [`ApiErrorException`](EosSharp--Core--Exceptions--ApiErrorException.md)` ` [`BuildApiError`](#class_eos_sharp_1_1_unity3_d_1_1_http_handler_1a0441a51ae8eb1c0b43dbdad687af713f)`(string content, int statusCode)` | Build Api Error from response content and http status code.
`private static void ` [`CheckUnityWebRequestErrors`](#class_eos_sharp_1_1_unity3_d_1_1_http_handler_1a7a0dd14ec9e852f47f2f702bf569607c)`(UnityWebRequest uwr)` | Checks Unity web request for errors and throws.

## Members

##### `private Dictionary< string, object > ` [`ResponseCache`](#class_eos_sharp_1_1_unity3_d_1_1_http_handler_1a7876042dff97e43c52e7d513f587f93d) 

##### `public void ` [`ClearResponseCache`](#class_eos_sharp_1_1_unity3_d_1_1_http_handler_1a905c1143ac0ce07cb71dbb15a60f281e)`()` 

Clear cached responses from requests called with Post/GetWithCacheAsync.

##### `public async Task< TResponseData > ` [`PostJsonAsync< TResponseData >`](#class_eos_sharp_1_1_unity3_d_1_1_http_handler_1a3acdabc747f5839c8beed189ba7abe06)`(string url, object data)` 

Make post request with data converted to json asynchronously.

#### Parameters
* `TResponseData` Response type

#### Parameters
* `url` Url to send the request

* `data` data sent in the body

#### Returns
Response data deserialized to type TResponseData

##### `public Task< TResponseData > ` [`PostJsonAsync< TResponseData >`](#class_eos_sharp_1_1_unity3_d_1_1_http_handler_1ad8c1c8b93d652ff78180c3667748c36c)`(string url, object data, CancellationToken cancellationToken)` 

Make post request with data converted to json asynchronously.

#### Parameters
* `TResponseData` Response type

#### Parameters
* `url` Url to send the request

* `data` data sent in the body

* `cancellationToken` Notification that operation should be canceled

#### Returns
Response data deserialized to type TResponseData

##### `public async Task< TResponseData > ` [`PostJsonWithCacheAsync< TResponseData >`](#class_eos_sharp_1_1_unity3_d_1_1_http_handler_1a8ca47b5765835b92420fd6bc994b7c2c)`(string url, object data, bool reload)` 

Make post request with data converted to json asynchronously. Response is cached based on input (url, data)

#### Parameters
* `TResponseData` Response type

#### Parameters
* `url` Url to send the request

* `data` data sent in the body

* `reload` ignore cached value and make a request caching the result

#### Returns
Response data deserialized to type TResponseData

##### `public Task< TResponseData > ` [`PostJsonWithCacheAsync< TResponseData >`](#class_eos_sharp_1_1_unity3_d_1_1_http_handler_1aa4ee8fb2e366dfe1fdc96c74dce5e2ee)`(string url, object data, CancellationToken cancellationToken, bool reload)` 

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

##### `public async Task< TResponseData > ` [`GetJsonAsync< TResponseData >`](#class_eos_sharp_1_1_unity3_d_1_1_http_handler_1af5b8a45e43a0ae7cc75ea8ea9159ccc4)`(string url)` 

Make get request asynchronously.

#### Parameters
* `TResponseData` Response type

#### Parameters
* `url` Url to send the request

#### Returns
Response data deserialized to type TResponseData

##### `public Task< TResponseData > ` [`GetJsonAsync< TResponseData >`](#class_eos_sharp_1_1_unity3_d_1_1_http_handler_1ae3ed7e871278e7dd7def051a32f85c06)`(string url, CancellationToken cancellationToken)` 

Make get request asynchronously.

#### Parameters
* `TResponseData` Response type

#### Parameters
* `url` Url to send the request

* `cancellationToken` Notification that operation should be canceled

#### Returns
Response data deserialized to type TResponseData

##### `public async Task< Stream > ` [`SendAsync`](#class_eos_sharp_1_1_unity3_d_1_1_http_handler_1ac92403d0bd960ebce1d47218d70ca5f3)`(HttpRequestMessage request)` 

Generic http request sent asynchronously.

#### Parameters
* `request` request body

#### Returns
Stream with response

##### `public async Task< Stream > ` [`SendAsync`](#class_eos_sharp_1_1_unity3_d_1_1_http_handler_1a497b180a695ff626038781cb6b47046c)`(HttpRequestMessage request, CancellationToken cancellationToken)` 

Generic http request sent asynchronously.

#### Parameters
* `request` request body

/// 
#### Parameters
* `cancellationToken` Notification that operation should be canceled

#### Returns
Stream with response

##### `public void ` [`UpdateResponseDataCache< TResponseData >`](#class_eos_sharp_1_1_unity3_d_1_1_http_handler_1a200c11cf47d108dfee0a09787641aacb)`(string hashKey, TResponseData responseData)` 

Upsert response data in the data store.

#### Parameters
* `TResponseData` response data type

#### Parameters
* `hashKey` data key

* `responseData` response data

##### `public string ` [`GetRequestHashKey`](#class_eos_sharp_1_1_unity3_d_1_1_http_handler_1a8ed4413ae2e52a2698c85154127f471a)`(string url, object data)` 

Calculate request unique hash key.

#### Parameters
* `url` Url to send the request

* `data` data sent in the body

#### Returns

##### `public async Task< Stream > ` [`BuildSendResponse`](#class_eos_sharp_1_1_unity3_d_1_1_http_handler_1a0cb6ca360fbbbb71291f4886c599ffed)`(HttpResponseMessage response)` 

Convert response to stream.

#### Parameters
* `response` response object

#### Returns
Stream with response

##### `public async Task< string > ` [`StreamToStringAsync`](#class_eos_sharp_1_1_unity3_d_1_1_http_handler_1ae8dcc1de6289cc996178a5caff5523e1)`(Stream stream)` 

Convert stream to a string.

#### Parameters
* `stream` 

#### Returns

##### `private static UnityWebRequest ` [`BuildUnityWebRequest`](#class_eos_sharp_1_1_unity3_d_1_1_http_handler_1a73110762fd141498d5f63e663a0df785)`(string url, string verb, object data)` 

Build unity web request.

#### Parameters
* `url` Url to send the request

* `verb` Http verb

* `data` data sent in the body

#### Returns

##### `private static ` [`ApiErrorException`](EosSharp--Core--Exceptions--ApiErrorException.md)` ` [`BuildApiError`](#class_eos_sharp_1_1_unity3_d_1_1_http_handler_1a0441a51ae8eb1c0b43dbdad687af713f)`(string content, int statusCode)` 

Build Api Error from response content and http status code.

#### Parameters
* `content` content to build

* `statusCode` status code

#### Returns
ApiError object

##### `private static void ` [`CheckUnityWebRequestErrors`](#class_eos_sharp_1_1_unity3_d_1_1_http_handler_1a7a0dd14ec9e852f47f2f702bf569607c)`(UnityWebRequest uwr)` 

Checks Unity web request for errors and throws.

#### Parameters
* `uwr`

