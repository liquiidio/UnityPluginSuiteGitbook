# class `WebSocketSharp::Net::HttpListenerRequest` 

Represents an incoming HTTP request to a HttpListener instance.

This class cannot be inherited.

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public string[] ` [`AcceptTypes`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1a6bb3b702ee770f852caf2358b3f2dc2b) | Gets the media types that are acceptable for the client.
`public int ` [`ClientCertificateError`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1a4e777e487aca0b7a9ba004031ec218e8) | Gets an error code that identifies a problem with the certificate provided by the client.
`public Encoding ` [`ContentEncoding`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1a3b73e62f4fc485701d7c6d6189a296ac) | Gets the encoding for the entity body data included in the request.
`public long ` [`ContentLength64`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1a6e76a9a5054c08ac664e8d036d82e880) | Gets the length in bytes of the entity body data included in the request.
`public string ` [`ContentType`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1a0165f247dbf0c1289501b8a0074beb3c) | Gets the media type of the entity body data included in the request.
`public ` [`CookieCollection`](WebSocketSharp--Net--CookieCollection.md)` ` [`Cookies`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1a571891b00833bfdc2aa6c6dc9541614e) | Gets the cookies included in the request.
`public bool ` [`HasEntityBody`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1aaa7f2df6e8ae1d5383717c82fb678082) | Gets a value indicating whether the request has the entity body data.
`public NameValueCollection ` [`Headers`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1a17b72b642f009151e61cda9a0e4696fd) | Gets the headers included in the request.
`public string ` [`HttpMethod`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1a8036503d303c2f4f31f021e00f6daa00) | Gets the HTTP method specified by the client.
`public Stream ` [`InputStream`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1a0ab3295f8da4cf946973ae4a94fd36af) | Gets a stream that contains the entity body data included in the request.
`public bool ` [`IsAuthenticated`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1a113748123407c45ee6c5faed4bd20edd) | Gets a value indicating whether the client is authenticated.
`public bool ` [`IsLocal`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1a0cf39c5047e171d9636886f431e7b185) | Gets a value indicating whether the request is sent from the local computer.
`public bool ` [`IsSecureConnection`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1a2e95aabb97642bfa26a167dfe4a7d2bb) | Gets a value indicating whether a secure connection is used to send the request.
`public bool ` [`IsWebSocketRequest`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1a3a0d84b9922cc76d96c6aa3c418f6b34) | Gets a value indicating whether the request is a WebSocket handshake request.
`public bool ` [`KeepAlive`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1a1c9be1b9167d79bb07276e725bb454f6) | Gets a value indicating whether a persistent connection is requested.
`public System.Net.IPEndPoint ` [`LocalEndPoint`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1a0fd9e1c09db7dd86e0644fc4e28901ae) | Gets the endpoint to which the request is sent.
`public Version ` [`ProtocolVersion`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1a0b380e8a26c1791c4de3b3292c12b3e9) | Gets the HTTP version specified by the client.
`public NameValueCollection ` [`QueryString`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1ad1978eecc1cc95c4a628d1ee49c7772f) | Gets the query string included in the request.
`public string ` [`RawUrl`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1a2b56b85c982da38296657c10b3048c3f) | Gets the raw URL specified by the client.
`public System.Net.IPEndPoint ` [`RemoteEndPoint`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1a689b34ca83e0530862014ce288276063) | Gets the endpoint from which the request is sent.
`public Guid ` [`RequestTraceIdentifier`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1a0e78bfbd5308e0d5010501d4e7af4ef3) | Gets the trace identifier of the request.
`public Uri ` [`Url`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1a8228cbbd65e3f8ccba81b3176ac491ed) | Gets the URL requested by the client.
`public Uri ` [`UrlReferrer`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1a473ee034b897a8fac77e6a6f1be1639e) | Gets the URI of the resource from which the requested URL was obtained.
`public string ` [`UserAgent`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1a155177a9cd84656c5b177a090e0f92a6) | Gets the user agent from which the request is originated.
`public string ` [`UserHostAddress`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1aa46e6bea361b0d6b4e593de537730c7b) | Gets the IP address and port number to which the request is sent.
`public string ` [`UserHostName`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1a13f9a50481a14248db1f321ee5ab7bec) | Gets the server host name requested by the client.
`public string[] ` [`UserLanguages`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1af2f9f1559900b342e4df08b7dbeca781) | Gets the natural languages that are acceptable for the client.
`public IAsyncResult ` [`BeginGetClientCertificate`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1ab468f5fdbc6049f0ebb946ac590edf23)`(AsyncCallback requestCallback, object state)` | Begins getting the certificate provided by the client asynchronously.
`public X509Certificate2 ` [`EndGetClientCertificate`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1a8cbeeb6456a03f55b7865b3c9c95cb28)`(IAsyncResult asyncResult)` | Ends an asynchronous operation to get the certificate provided by the client.
`public X509Certificate2 ` [`GetClientCertificate`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1acc3b2358bf977e03b347ee2f505f3779)`()` | Gets the certificate provided by the client.
`public override string ` [`ToString`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1aa73e7c4dd1df5fd5fbf81c7764ee1533)`()` | Returns a string that represents the current instance.
`private string[] ` [`_acceptTypes`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1aaef7a53e457f1c47d140f67d07b5f970) | 
`private bool ` [`_chunked`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1ad898c86316bcddd462e548923c3f57dc) | 
`private ` [`HttpConnection`](WebSocketSharp--Net--HttpConnection.md)` ` [`_connection`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1aadd62565d7e46d3f6cf6207ecf2267be) | 
`private Encoding ` [`_contentEncoding`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1a314c8dd4d7dfc33cd6948e84fae12509) | 
`private long ` [`_contentLength`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1a4ab603fe0403c7ce2737ccc98d4ab9a7) | 
`private ` [`HttpListenerContext`](WebSocketSharp--Net--HttpListenerContext.md)` ` [`_context`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1acce8d94df9e8bf7da6c2d6888e9f5391) | 
`private ` [`CookieCollection`](WebSocketSharp--Net--CookieCollection.md)` ` [`_cookies`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1ae2054e3379559490b8e8704754ae0eb0) | 
`private ` [`WebHeaderCollection`](WebSocketSharp--Net--WebHeaderCollection.md)` ` [`_headers`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1a6540483f7f73f46c6c5b52bbbed7ecd1) | 
`private string ` [`_httpMethod`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1a9a9e2b38af7b0323c65f3144017ecafa) | 
`private Stream ` [`_inputStream`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1ae799a700df6e0e59863b7296fe2fb2ad) | 
`private Version ` [`_protocolVersion`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1a73e218e33ce3e7ff9d0c5a040ab552a5) | 
`private NameValueCollection ` [`_queryString`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1a24298c922140b3c6d1923083db07ec9c) | 
`private string ` [`_rawUrl`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1a696585d51304265279a00cf126471901) | 
`private Guid ` [`_requestTraceIdentifier`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1ac23028ccc640d08d1d82868b2ada2db8) | 
`private Uri ` [`_url`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1ab1eb41fecf4eda6dd59b55863584b828) | 
`private Uri ` [`_urlReferrer`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1ad7acb25fb5510aac87d339dc6d63b537) | 
`private bool ` [`_urlSet`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1ac8e715c3da08af0eff4b4bf12caeebc8) | 
`private string ` [`_userHostName`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1a8979a33c17f6abccb41a1b1cdaf788cf) | 
`private string[] ` [`_userLanguages`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1a5a73b47dea21163e63692180f622a40a) | 
`private void ` [`finishInitialization10`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1ae1c0b78462eb6c1597cd5410909a9fec)`()` | 
`private Encoding ` [`getContentEncoding`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1ac6bf346b1265e489ea7a5b220547fa8c)`()` | 
`private ` [`RequestStream`](WebSocketSharp--Net--RequestStream.md)` ` [`getInputStream`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1a308c1236ac7e830ef3ea2d71a7d9d3bc)`()` | 
`private static static ` [`HttpListenerRequest`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1acfbb6b52b34e573f9a801c4675890c0d)`()` | 

## Members

##### `public string[] ` [`AcceptTypes`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1a6bb3b702ee770f852caf2358b3f2dc2b) 

Gets the media types that are acceptable for the client.

An array of string that contains the names of the media types specified in the value of the Accept header. 

`null` if the header is not present.

##### `public int ` [`ClientCertificateError`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1a4e777e487aca0b7a9ba004031ec218e8) 

Gets an error code that identifies a problem with the certificate provided by the client.

An int that represents an error code. 

#### Exceptions
* `NotSupportedException` This property is not supported.

##### `public Encoding ` [`ContentEncoding`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1a3b73e62f4fc485701d7c6d6189a296ac) 

Gets the encoding for the entity body data included in the request.

A Encoding converted from the charset value of the Content-Type header. 

Encoding.UTF8 if the charset value is not available.

##### `public long ` [`ContentLength64`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1a6e76a9a5054c08ac664e8d036d82e880) 

Gets the length in bytes of the entity body data included in the request.

A long converted from the value of the Content-Length header. 

-1 if the header is not present.

##### `public string ` [`ContentType`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1a0165f247dbf0c1289501b8a0074beb3c) 

Gets the media type of the entity body data included in the request.

A string that represents the value of the Content-Type header. 

`null` if the header is not present.

##### `public ` [`CookieCollection`](WebSocketSharp--Net--CookieCollection.md)` ` [`Cookies`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1a571891b00833bfdc2aa6c6dc9541614e) 

Gets the cookies included in the request.

A CookieCollection that contains the cookies. 

An empty collection if not included.

##### `public bool ` [`HasEntityBody`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1aaa7f2df6e8ae1d5383717c82fb678082) 

Gets a value indicating whether the request has the entity body data.

`true` if the request has the entity body data; otherwise, `false`.

##### `public NameValueCollection ` [`Headers`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1a17b72b642f009151e61cda9a0e4696fd) 

Gets the headers included in the request.

A NameValueCollection that contains the headers.

##### `public string ` [`HttpMethod`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1a8036503d303c2f4f31f021e00f6daa00) 

Gets the HTTP method specified by the client.

A string that represents the HTTP method specified in the request line.

##### `public Stream ` [`InputStream`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1a0ab3295f8da4cf946973ae4a94fd36af) 

Gets a stream that contains the entity body data included in the request.

A Stream that contains the entity body data. 

Stream.Null if the entity body data is not available.

##### `public bool ` [`IsAuthenticated`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1a113748123407c45ee6c5faed4bd20edd) 

Gets a value indicating whether the client is authenticated.

`true` if the client is authenticated; otherwise, `false`.

##### `public bool ` [`IsLocal`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1a0cf39c5047e171d9636886f431e7b185) 

Gets a value indicating whether the request is sent from the local computer.

`true` if the request is sent from the same computer as the server; otherwise, `false`.

##### `public bool ` [`IsSecureConnection`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1a2e95aabb97642bfa26a167dfe4a7d2bb) 

Gets a value indicating whether a secure connection is used to send the request.

`true` if the connection is secure; otherwise, `false`.

##### `public bool ` [`IsWebSocketRequest`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1a3a0d84b9922cc76d96c6aa3c418f6b34) 

Gets a value indicating whether the request is a WebSocket handshake request.

`true` if the request is a WebSocket handshake request; otherwise, `false`.

##### `public bool ` [`KeepAlive`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1a1c9be1b9167d79bb07276e725bb454f6) 

Gets a value indicating whether a persistent connection is requested.

`true` if the request specifies that the connection is kept open; otherwise, `false`.

##### `public System.Net.IPEndPoint ` [`LocalEndPoint`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1a0fd9e1c09db7dd86e0644fc4e28901ae) 

Gets the endpoint to which the request is sent.

A System.Net.IPEndPoint that represents the server IP address and port number.

##### `public Version ` [`ProtocolVersion`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1a0b380e8a26c1791c4de3b3292c12b3e9) 

Gets the HTTP version specified by the client.

A Version that represents the HTTP version specified in the request line.

##### `public NameValueCollection ` [`QueryString`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1ad1978eecc1cc95c4a628d1ee49c7772f) 

Gets the query string included in the request.

A NameValueCollection that contains the query parameters. 

An empty collection if not included.

##### `public string ` [`RawUrl`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1a2b56b85c982da38296657c10b3048c3f) 

Gets the raw URL specified by the client.

A string that represents the request target specified in the request line.

##### `public System.Net.IPEndPoint ` [`RemoteEndPoint`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1a689b34ca83e0530862014ce288276063) 

Gets the endpoint from which the request is sent.

A System.Net.IPEndPoint that represents the client IP address and port number.

##### `public Guid ` [`RequestTraceIdentifier`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1a0e78bfbd5308e0d5010501d4e7af4ef3) 

Gets the trace identifier of the request.

A Guid that represents the trace identifier.

##### `public Uri ` [`Url`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1a8228cbbd65e3f8ccba81b3176ac491ed) 

Gets the URL requested by the client.

A Uri that represents the URL parsed from the request. 

`null` if the URL cannot be parsed.

##### `public Uri ` [`UrlReferrer`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1a473ee034b897a8fac77e6a6f1be1639e) 

Gets the URI of the resource from which the requested URL was obtained.

A Uri converted from the value of the Referer header. 

`null` if the header value is not available.

##### `public string ` [`UserAgent`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1a155177a9cd84656c5b177a090e0f92a6) 

Gets the user agent from which the request is originated.

A string that represents the value of the User-Agent header. 

`null` if the header is not present.

##### `public string ` [`UserHostAddress`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1aa46e6bea361b0d6b4e593de537730c7b) 

Gets the IP address and port number to which the request is sent.

A string that represents the server IP address and port number.

##### `public string ` [`UserHostName`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1a13f9a50481a14248db1f321ee5ab7bec) 

Gets the server host name requested by the client.

A string that represents the value of the Host header. 

It includes the port number if provided. 

`null` if the header is not present.

##### `public string[] ` [`UserLanguages`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1af2f9f1559900b342e4df08b7dbeca781) 

Gets the natural languages that are acceptable for the client.

An array of string that contains the names of the natural languages specified in the value of the Accept-Language header. 

`null` if the header is not present.

##### `public IAsyncResult ` [`BeginGetClientCertificate`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1ab468f5fdbc6049f0ebb946ac590edf23)`(AsyncCallback requestCallback, object state)` 

Begins getting the certificate provided by the client asynchronously.

#### Returns
An IAsyncResult instance that indicates the status of the operation. 

#### Parameters
* `requestCallback` An AsyncCallback delegate that invokes the method called when the operation is complete. 

* `state` An object that represents a user defined object to pass to the callback delegate. 

#### Exceptions
* `NotSupportedException` This method is not supported.

##### `public X509Certificate2 ` [`EndGetClientCertificate`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1a8cbeeb6456a03f55b7865b3c9c95cb28)`(IAsyncResult asyncResult)` 

Ends an asynchronous operation to get the certificate provided by the client.

#### Returns
A X509Certificate2 that represents an X.509 certificate provided by the client. 

#### Parameters
* `asyncResult` An IAsyncResult instance returned when the operation started. 

#### Exceptions
* `NotSupportedException` This method is not supported.

##### `public X509Certificate2 ` [`GetClientCertificate`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1acc3b2358bf977e03b347ee2f505f3779)`()` 

Gets the certificate provided by the client.

#### Returns
A X509Certificate2 that represents an X.509 certificate provided by the client. 

#### Exceptions
* `NotSupportedException` This method is not supported.

##### `public override string ` [`ToString`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1aa73e7c4dd1df5fd5fbf81c7764ee1533)`()` 

Returns a string that represents the current instance.

#### Returns
A string that contains the request line and headers included in the request.

##### `private string[] ` [`_acceptTypes`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1aaef7a53e457f1c47d140f67d07b5f970) 

##### `private bool ` [`_chunked`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1ad898c86316bcddd462e548923c3f57dc) 

##### `private ` [`HttpConnection`](WebSocketSharp--Net--HttpConnection.md)` ` [`_connection`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1aadd62565d7e46d3f6cf6207ecf2267be) 

##### `private Encoding ` [`_contentEncoding`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1a314c8dd4d7dfc33cd6948e84fae12509) 

##### `private long ` [`_contentLength`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1a4ab603fe0403c7ce2737ccc98d4ab9a7) 

##### `private ` [`HttpListenerContext`](WebSocketSharp--Net--HttpListenerContext.md)` ` [`_context`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1acce8d94df9e8bf7da6c2d6888e9f5391) 

##### `private ` [`CookieCollection`](WebSocketSharp--Net--CookieCollection.md)` ` [`_cookies`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1ae2054e3379559490b8e8704754ae0eb0) 

##### `private ` [`WebHeaderCollection`](WebSocketSharp--Net--WebHeaderCollection.md)` ` [`_headers`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1a6540483f7f73f46c6c5b52bbbed7ecd1) 

##### `private string ` [`_httpMethod`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1a9a9e2b38af7b0323c65f3144017ecafa) 

##### `private Stream ` [`_inputStream`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1ae799a700df6e0e59863b7296fe2fb2ad) 

##### `private Version ` [`_protocolVersion`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1a73e218e33ce3e7ff9d0c5a040ab552a5) 

##### `private NameValueCollection ` [`_queryString`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1a24298c922140b3c6d1923083db07ec9c) 

##### `private string ` [`_rawUrl`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1a696585d51304265279a00cf126471901) 

##### `private Guid ` [`_requestTraceIdentifier`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1ac23028ccc640d08d1d82868b2ada2db8) 

##### `private Uri ` [`_url`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1ab1eb41fecf4eda6dd59b55863584b828) 

##### `private Uri ` [`_urlReferrer`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1ad7acb25fb5510aac87d339dc6d63b537) 

##### `private bool ` [`_urlSet`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1ac8e715c3da08af0eff4b4bf12caeebc8) 

##### `private string ` [`_userHostName`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1a8979a33c17f6abccb41a1b1cdaf788cf) 

##### `private string[] ` [`_userLanguages`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1a5a73b47dea21163e63692180f622a40a) 

##### `private void ` [`finishInitialization10`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1ae1c0b78462eb6c1597cd5410909a9fec)`()` 

##### `private Encoding ` [`getContentEncoding`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1ac6bf346b1265e489ea7a5b220547fa8c)`()` 

##### `private ` [`RequestStream`](WebSocketSharp--Net--RequestStream.md)` ` [`getInputStream`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1a308c1236ac7e830ef3ea2d71a7d9d3bc)`()` 

##### `private static static ` [`HttpListenerRequest`](#class_web_socket_sharp_1_1_net_1_1_http_listener_request_1acfbb6b52b34e573f9a801c4675890c0d)`()` 

