# class `WebSocketSharp::Net::HttpListenerResponse` 

```
class WebSocketSharp::Net::HttpListenerResponse
  : public IDisposable
```

Represents an HTTP response to an HTTP request received by a HttpListener instance.

This class cannot be inherited.

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`package bool ` [`CloseConnection`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1ad2994676b848b63db32454361fa7662c) | 
`package ` [`WebHeaderCollection`](WebSocketSharp--Net--WebHeaderCollection.md)` ` [`FullHeaders`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a0d3f9d32db1924002d77f82cc58cdfc7) | 
`package bool ` [`HeadersSent`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a5bde98695018327001e5c151bb66bad3) | 
`package string ` [`StatusLine`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a842b11714692d05404784b3c6c7d846e) | 
`public Encoding ` [`ContentEncoding`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a3b73e62f4fc485701d7c6d6189a296ac) | Gets or sets the encoding for the entity body data included in the response.
`public long ` [`ContentLength64`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a6e76a9a5054c08ac664e8d036d82e880) | Gets or sets the number of bytes in the entity body data included in the response.
`public string ` [`ContentType`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a0165f247dbf0c1289501b8a0074beb3c) | Gets or sets the media type of the entity body included in the response.
`public ` [`CookieCollection`](WebSocketSharp--Net--CookieCollection.md)` ` [`Cookies`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a571891b00833bfdc2aa6c6dc9541614e) | Gets or sets the collection of cookies sent with the response.
`public ` [`WebHeaderCollection`](WebSocketSharp--Net--WebHeaderCollection.md)` ` [`Headers`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a8b3c309de61f38e225a156f3b6cd5242) | Gets or sets the collection of the HTTP headers sent to the client.
`public bool ` [`KeepAlive`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a1c9be1b9167d79bb07276e725bb454f6) | Gets or sets a value indicating whether the server requests a persistent connection.
`public Stream ` [`OutputStream`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a1ab277caae94522e4e8b69f409fe6fad) | Gets a stream instance to which the entity body data can be written.
`public Version ` [`ProtocolVersion`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a0b380e8a26c1791c4de3b3292c12b3e9) | Gets or sets the HTTP version used for the response.
`public string ` [`RedirectLocation`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1ae8692b57ae78aefbfb0890589e7dc4f7) | Gets or sets the URL to which the client is redirected to locate a requested resource.
`public bool ` [`SendChunked`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a26e7658878bfca70f1712ac96b9c82f0) | Gets or sets a value indicating whether the response uses the chunked transfer encoding.
`public int ` [`StatusCode`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a5025d650f325c75a520675895ddb477d) | Gets or sets the HTTP status code returned to the client.
`public string ` [`StatusDescription`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a990ec8a6439fd34a16d559c32f179972) | Gets or sets the description of the HTTP status code returned to the client.
`public void ` [`Abort`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a12b9283f52eaf7610afe4b04fbca2ff0)`()` | Closes the connection to the client without sending a response.
`public void ` [`AppendCookie`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a80109128c2276f85efe7c4141c1fdc89)`(` [`Cookie`](WebSocketSharp--Net--Cookie.md)` cookie)` | Appends the specified cookie to the cookies sent with the response.
`public void ` [`AppendHeader`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a9a691f44f31c48b23e03deae5856bc7b)`(string name, string value)` | Appends an HTTP header with the specified name and value to the headers for the response.
`public void ` [`Close`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a7f7a3199c392465d0767c6506c1af5b4)`()` | Sends the response to the client and releases the resources used by this instance.
`public void ` [`Close`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a6e641bd8579e7525618a19636df2fc82)`(byte[] responseEntity, bool willBlock)` | Sends the response with the specified entity body data to the client and releases the resources used by this instance.
`public void ` [`CopyFrom`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a528101688d1f20610d101b1144274d09)`(` [`HttpListenerResponse`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response)` templateResponse)` | Copies some properties from the specified response instance to this instance.
`public void ` [`Redirect`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1afc01710dc4a5eb15ce6824f1be961135)`(string url)` | Configures the response to redirect the client's request to the specified URL.
`public void ` [`SetCookie`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1aebf7816b302fd17dff92187e8ae2f27a)`(` [`Cookie`](WebSocketSharp--Net--Cookie.md)` cookie)` | Adds or updates a cookie in the cookies sent with the response.
`public void ` [`SetHeader`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a45c871ae44d42d36fd966ef316304dc2)`(string name, string value)` | Adds or updates an HTTP header with the specified name and value in the headers for the response.
`private bool ` [`_closeConnection`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a356f2d1495a091a4a74c5c4bf0712494) | 
`private Encoding ` [`_contentEncoding`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a314c8dd4d7dfc33cd6948e84fae12509) | 
`private long ` [`_contentLength`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a4ab603fe0403c7ce2737ccc98d4ab9a7) | 
`private string ` [`_contentType`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a2ab019061c65a0536653df7ab0fb295b) | 
`private ` [`HttpListenerContext`](WebSocketSharp--Net--HttpListenerContext.md)` ` [`_context`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1acce8d94df9e8bf7da6c2d6888e9f5391) | 
`private ` [`CookieCollection`](WebSocketSharp--Net--CookieCollection.md)` ` [`_cookies`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1ae2054e3379559490b8e8704754ae0eb0) | 
`private bool ` [`_disposed`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1aa0695b8700eaefdf30302d9b2daf447b) | 
`private ` [`WebHeaderCollection`](WebSocketSharp--Net--WebHeaderCollection.md)` ` [`_headers`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a6540483f7f73f46c6c5b52bbbed7ecd1) | 
`private bool ` [`_headersSent`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a73c3bc3274ac7d0a7be0e04a9bf03266) | 
`private bool ` [`_keepAlive`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1aeab32575665c4b096866edd7675ac6f1) | 
`private ` [`ResponseStream`](WebSocketSharp--Net--ResponseStream.md)` ` [`_outputStream`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a5040da5db9a032349232b23e50e861c0) | 
`private Uri ` [`_redirectLocation`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a7360034271a71e01a9a24ca8592285b8) | 
`private bool ` [`_sendChunked`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a9f01324db2b61d8e6841a4a9649ce792) | 
`private int ` [`_statusCode`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a624b9bff29015a544d35701c61966182) | 
`private string ` [`_statusDescription`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a4ac2702691be3d4b701b6448c3d0ba6e) | 
`private Version ` [`_version`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a48a6a40e2301b8126fe4de7ba57807cd) | 
`private bool ` [`canSetCookie`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a18a4002a8fd250b70852d69346bb27be)`(` [`Cookie`](WebSocketSharp--Net--Cookie.md)` cookie)` | 
`private void ` [`close`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1ac55aa072031a68a49d85a2d72496ab80)`(bool force)` | 
`private void ` [`close`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a709cfe2edb14d9b6a118d55246b265e9)`(byte[] responseEntity, int bufferLength, bool willBlock)` | 
`private IEnumerable< ` [`Cookie`](WebSocketSharp--Net--Cookie.md)` > ` [`findCookie`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a28d84f4752f0494c3e8c8ec67b934b15)`(` [`Cookie`](WebSocketSharp--Net--Cookie.md)` cookie)` | 
`private void IDisposable. ` [`Dispose`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a44dd5de4474284f22b70c3e0fbdc07f4)`()` | Releases all resources used by this instance.
`private static string ` [`createContentTypeHeaderText`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a6c1ff9a7434293dcb1a209d83bec8f21)`(string value, Encoding encoding)` | 
`private static bool ` [`isValidForContentType`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a27810c04e4ad292220870775dcc885d0)`(string value)` | 
`private static bool ` [`isValidForStatusDescription`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a6bedd29544f8ba0e1217939f6fe10c45)`(string value)` | 

## Members

##### `package bool ` [`CloseConnection`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1ad2994676b848b63db32454361fa7662c) 

##### `package ` [`WebHeaderCollection`](WebSocketSharp--Net--WebHeaderCollection.md)` ` [`FullHeaders`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a0d3f9d32db1924002d77f82cc58cdfc7) 

##### `package bool ` [`HeadersSent`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a5bde98695018327001e5c151bb66bad3) 

##### `package string ` [`StatusLine`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a842b11714692d05404784b3c6c7d846e) 

##### `public Encoding ` [`ContentEncoding`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a3b73e62f4fc485701d7c6d6189a296ac) 

Gets or sets the encoding for the entity body data included in the response.

A Encoding that represents the encoding for the entity body data. 

`null` if no encoding is specified. 

The default value is `null`. 

#### Exceptions
* `InvalidOperationException` The response is already being sent. 

* `ObjectDisposedException` This instance is closed.

##### `public long ` [`ContentLength64`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a6e76a9a5054c08ac664e8d036d82e880) 

Gets or sets the number of bytes in the entity body data included in the response.

A long that represents the number of bytes in the entity body data. 

It is used for the value of the Content-Length header. 

The default value is zero. 

#### Exceptions
* `ArgumentOutOfRangeException` The value specified for a set operation is less than zero. 

* `InvalidOperationException` The response is already being sent. 

* `ObjectDisposedException` This instance is closed.

##### `public string ` [`ContentType`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a0165f247dbf0c1289501b8a0074beb3c) 

Gets or sets the media type of the entity body included in the response.

A string that represents the media type of the entity body. 

It is used for the value of the Content-Type header. 

`null` if no media type is specified. 

The default value is `null`. 

#### Exceptions
* `ArgumentException` The value specified for a set operation is an empty string. 

-or- 

The value specified for a set operation contains an invalid character. 

* `InvalidOperationException` The response is already being sent. 

* `ObjectDisposedException` This instance is closed.

##### `public ` [`CookieCollection`](WebSocketSharp--Net--CookieCollection.md)` ` [`Cookies`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a571891b00833bfdc2aa6c6dc9541614e) 

Gets or sets the collection of cookies sent with the response.

A CookieCollection that contains the cookies sent with the response.

##### `public ` [`WebHeaderCollection`](WebSocketSharp--Net--WebHeaderCollection.md)` ` [`Headers`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a8b3c309de61f38e225a156f3b6cd5242) 

Gets or sets the collection of the HTTP headers sent to the client.

A WebHeaderCollection that contains the headers sent to the client. 

#### Exceptions
* `InvalidOperationException` The value specified for a set operation is not valid for a response.

##### `public bool ` [`KeepAlive`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a1c9be1b9167d79bb07276e725bb454f6) 

Gets or sets a value indicating whether the server requests a persistent connection.

`true` if the server requests a persistent connection; otherwise, `false`. 

The default value is `true`. 

#### Exceptions
* `InvalidOperationException` The response is already being sent. 

* `ObjectDisposedException` This instance is closed.

##### `public Stream ` [`OutputStream`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a1ab277caae94522e4e8b69f409fe6fad) 

Gets a stream instance to which the entity body data can be written.

A Stream instance to which the entity body data can be written. 

#### Exceptions
* `ObjectDisposedException` This instance is closed.

##### `public Version ` [`ProtocolVersion`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a0b380e8a26c1791c4de3b3292c12b3e9) 

Gets or sets the HTTP version used for the response.

A Version that represents the HTTP version used for the response. 

#### Exceptions
* `ArgumentNullException` The value specified for a set operation is `null`. 

* `ArgumentException` The value specified for a set operation does not have its Major property set to 1. 

-or- 

The value specified for a set operation does not have its Minor property set to either 0 or 1. 

* `InvalidOperationException` The response is already being sent. 

* `ObjectDisposedException` This instance is closed.

##### `public string ` [`RedirectLocation`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1ae8692b57ae78aefbfb0890589e7dc4f7) 

Gets or sets the URL to which the client is redirected to locate a requested resource.

A string that represents the absolute URL for the redirect location. 

It is used for the value of the Location header. 

`null` if no redirect location is specified. 

The default value is `null`. 

#### Exceptions
* `ArgumentException` The value specified for a set operation is an empty string. 

-or- 

The value specified for a set operation is not an absolute URL. 

* `InvalidOperationException` The response is already being sent. 

* `ObjectDisposedException` This instance is closed.

##### `public bool ` [`SendChunked`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a26e7658878bfca70f1712ac96b9c82f0) 

Gets or sets a value indicating whether the response uses the chunked transfer encoding.

`true` if the response uses the chunked transfer encoding; otherwise, `false`. 

The default value is `false`. 

#### Exceptions
* `InvalidOperationException` The response is already being sent. 

* `ObjectDisposedException` This instance is closed.

##### `public int ` [`StatusCode`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a5025d650f325c75a520675895ddb477d) 

Gets or sets the HTTP status code returned to the client.

An int that represents the HTTP status code for the response to the request. 

The default value is 200. It indicates that the request has succeeded. 

#### Exceptions
* `InvalidOperationException` The response is already being sent. 

* `ObjectDisposedException` This instance is closed. 

* `System.Net.ProtocolViolationException` The value specified for a set operation is invalid. 

Valid values are between 100 and 999 inclusive.

##### `public string ` [`StatusDescription`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a990ec8a6439fd34a16d559c32f179972) 

Gets or sets the description of the HTTP status code returned to the client.

A string that represents the description of the HTTP status code for the response to the request. 

The default value is the  RFC 2616

description for the StatusCode property value. 

An empty string if an RFC 2616 description does not exist. 

#### Exceptions
* `ArgumentNullException` The value specified for a set operation is `null`. 

* `ArgumentException` The value specified for a set operation contains an invalid character. 

* `InvalidOperationException` The response is already being sent. 

* `ObjectDisposedException` This instance is closed.

##### `public void ` [`Abort`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a12b9283f52eaf7610afe4b04fbca2ff0)`()` 

Closes the connection to the client without sending a response.

##### `public void ` [`AppendCookie`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a80109128c2276f85efe7c4141c1fdc89)`(` [`Cookie`](WebSocketSharp--Net--Cookie.md)` cookie)` 

Appends the specified cookie to the cookies sent with the response.

#### Parameters
* `cookie` A Cookie to append. 

#### Exceptions
* `ArgumentNullException` *cookie*  is `null`.

##### `public void ` [`AppendHeader`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a9a691f44f31c48b23e03deae5856bc7b)`(string name, string value)` 

Appends an HTTP header with the specified name and value to the headers for the response.

#### Parameters
* `name` A string that specifies the name of the header to append. 

* `value` A string that specifies the value of the header to append. 

#### Exceptions
* `ArgumentNullException` *name*  is `null`. 

* `ArgumentException` *name*  is an empty string. 

-or- 

*name*  is a string of spaces. 

-or- 

*name*  contains an invalid character. 

-or- 

*value*  contains an invalid character. 

-or- 

*name*  is a restricted header name. 

* `ArgumentOutOfRangeException` The length of *value*  is greater than 65,535 characters. 

* `InvalidOperationException` The current headers do not allow the header.

##### `public void ` [`Close`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a7f7a3199c392465d0767c6506c1af5b4)`()` 

Sends the response to the client and releases the resources used by this instance.

##### `public void ` [`Close`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a6e641bd8579e7525618a19636df2fc82)`(byte[] responseEntity, bool willBlock)` 

Sends the response with the specified entity body data to the client and releases the resources used by this instance.

#### Parameters
* `responseEntity` An array of byte that contains the entity body data. 

* `willBlock` A bool: `true` if this method blocks execution while flushing the stream to the client; otherwise, `false`. 

#### Exceptions
* `ArgumentNullException` *responseEntity*  is `null`. 

* `ObjectDisposedException` This instance is closed.

##### `public void ` [`CopyFrom`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a528101688d1f20610d101b1144274d09)`(` [`HttpListenerResponse`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response)` templateResponse)` 

Copies some properties from the specified response instance to this instance.

#### Parameters
* `templateResponse` A HttpListenerResponse to copy. 

#### Exceptions
* `ArgumentNullException` *templateResponse*  is `null`.

##### `public void ` [`Redirect`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1afc01710dc4a5eb15ce6824f1be961135)`(string url)` 

Configures the response to redirect the client's request to the specified URL.

This method sets the RedirectLocation property to *url* , the StatusCode property to 302, and the StatusDescription property to "Found". 

#### Parameters
* `url` A string that specifies the absolute URL to which the client is redirected to locate a requested resource. 

#### Exceptions
* `ArgumentNullException` *url*  is `null`. 

* `ArgumentException` *url*  is an empty string. 

-or- 

*url*  is not an absolute URL. 

* `InvalidOperationException` The response is already being sent. 

* `ObjectDisposedException` This instance is closed.

##### `public void ` [`SetCookie`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1aebf7816b302fd17dff92187e8ae2f27a)`(` [`Cookie`](WebSocketSharp--Net--Cookie.md)` cookie)` 

Adds or updates a cookie in the cookies sent with the response.

#### Parameters
* `cookie` A Cookie to set. 

#### Exceptions
* `ArgumentNullException` *cookie*  is `null`. 

* `ArgumentException` *cookie*  already exists in the cookies but it cannot be updated.

##### `public void ` [`SetHeader`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a45c871ae44d42d36fd966ef316304dc2)`(string name, string value)` 

Adds or updates an HTTP header with the specified name and value in the headers for the response.

#### Parameters
* `name` A string that specifies the name of the header to set. 

* `value` A string that specifies the value of the header to set. 

#### Exceptions
* `ArgumentNullException` *name*  is `null`. 

* `ArgumentException` *name*  is an empty string. 

-or- 

*name*  is a string of spaces. 

-or- 

*name*  contains an invalid character. 

-or- 

*value*  contains an invalid character. 

-or- 

*name*  is a restricted header name. 

* `ArgumentOutOfRangeException` The length of *value*  is greater than 65,535 characters. 

* `InvalidOperationException` The current headers do not allow the header.

##### `private bool ` [`_closeConnection`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a356f2d1495a091a4a74c5c4bf0712494) 

##### `private Encoding ` [`_contentEncoding`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a314c8dd4d7dfc33cd6948e84fae12509) 

##### `private long ` [`_contentLength`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a4ab603fe0403c7ce2737ccc98d4ab9a7) 

##### `private string ` [`_contentType`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a2ab019061c65a0536653df7ab0fb295b) 

##### `private ` [`HttpListenerContext`](WebSocketSharp--Net--HttpListenerContext.md)` ` [`_context`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1acce8d94df9e8bf7da6c2d6888e9f5391) 

##### `private ` [`CookieCollection`](WebSocketSharp--Net--CookieCollection.md)` ` [`_cookies`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1ae2054e3379559490b8e8704754ae0eb0) 

##### `private bool ` [`_disposed`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1aa0695b8700eaefdf30302d9b2daf447b) 

##### `private ` [`WebHeaderCollection`](WebSocketSharp--Net--WebHeaderCollection.md)` ` [`_headers`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a6540483f7f73f46c6c5b52bbbed7ecd1) 

##### `private bool ` [`_headersSent`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a73c3bc3274ac7d0a7be0e04a9bf03266) 

##### `private bool ` [`_keepAlive`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1aeab32575665c4b096866edd7675ac6f1) 

##### `private ` [`ResponseStream`](WebSocketSharp--Net--ResponseStream.md)` ` [`_outputStream`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a5040da5db9a032349232b23e50e861c0) 

##### `private Uri ` [`_redirectLocation`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a7360034271a71e01a9a24ca8592285b8) 

##### `private bool ` [`_sendChunked`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a9f01324db2b61d8e6841a4a9649ce792) 

##### `private int ` [`_statusCode`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a624b9bff29015a544d35701c61966182) 

##### `private string ` [`_statusDescription`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a4ac2702691be3d4b701b6448c3d0ba6e) 

##### `private Version ` [`_version`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a48a6a40e2301b8126fe4de7ba57807cd) 

##### `private bool ` [`canSetCookie`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a18a4002a8fd250b70852d69346bb27be)`(` [`Cookie`](WebSocketSharp--Net--Cookie.md)` cookie)` 

##### `private void ` [`close`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1ac55aa072031a68a49d85a2d72496ab80)`(bool force)` 

##### `private void ` [`close`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a709cfe2edb14d9b6a118d55246b265e9)`(byte[] responseEntity, int bufferLength, bool willBlock)` 

##### `private IEnumerable< ` [`Cookie`](WebSocketSharp--Net--Cookie.md)` > ` [`findCookie`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a28d84f4752f0494c3e8c8ec67b934b15)`(` [`Cookie`](WebSocketSharp--Net--Cookie.md)` cookie)` 

##### `private void IDisposable. ` [`Dispose`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a44dd5de4474284f22b70c3e0fbdc07f4)`()` 

Releases all resources used by this instance.

##### `private static string ` [`createContentTypeHeaderText`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a6c1ff9a7434293dcb1a209d83bec8f21)`(string value, Encoding encoding)` 

##### `private static bool ` [`isValidForContentType`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a27810c04e4ad292220870775dcc885d0)`(string value)` 

##### `private static bool ` [`isValidForStatusDescription`](#class_web_socket_sharp_1_1_net_1_1_http_listener_response_1a6bedd29544f8ba0e1217939f6fe10c45)`(string value)` 

