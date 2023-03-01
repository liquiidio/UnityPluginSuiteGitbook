# namespace `WebSocketSharp::Net` 

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`enum ` [`AuthenticationSchemes`](#namespace_web_socket_sharp_1_1_net_1a25926eceb26224dfd35a54e69f5dec15)            | Specifies the scheme for authentication.
`enum ` [`HttpHeaderType`](#namespace_web_socket_sharp_1_1_net_1a0ca3b898a28ccb04a7af2cc771c384b4)            | 
`enum ` [`HttpRequestHeader`](#namespace_web_socket_sharp_1_1_net_1abdaf027ba341884b07218f836497f4f3)            | Indicates the HTTP header that may be specified in a client request.
`enum ` [`HttpResponseHeader`](#namespace_web_socket_sharp_1_1_net_1af965174270dc3b8f92b5725e4b2248d6)            | Indicates the HTTP header that can be specified in a server response.
`enum ` [`HttpStatusCode`](#namespace_web_socket_sharp_1_1_net_1ab80f66127508dfced7a0fe1929fe12cc)            | Indicates the HTTP status code that can be specified in a server response.
`enum ` [`InputChunkState`](#namespace_web_socket_sharp_1_1_net_1ae44b2fbfb73e77c8537578e9622e6a4b)            | 
`enum ` [`InputState`](#namespace_web_socket_sharp_1_1_net_1aecfb003a08d29c0b75cd266ca0cadb76)            | 
`enum ` [`LineState`](#namespace_web_socket_sharp_1_1_net_1a1f8598b431e9fc31669d1ebc6937d082)            | 
`class ` [`AuthenticationBase`](WebSocketSharp--Net--AuthenticationBase.md) | 
`class ` [`AuthenticationChallenge`](WebSocketSharp--Net--AuthenticationChallenge.md) | 
`class ` [`AuthenticationResponse`](WebSocketSharp--Net--AuthenticationResponse.md) | 
`class ` [`Chunk`](WebSocketSharp--Net--Chunk.md) | 
`class ` [`ChunkedRequestStream`](WebSocketSharp--Net--ChunkedRequestStream.md) | 
`class ` [`ChunkStream`](WebSocketSharp--Net--ChunkStream.md) | 
`class ` [`ClientSslConfiguration`](WebSocketSharp--Net--ClientSslConfiguration.md) | Stores the parameters for the SslStream used by clients.
`class ` [`Cookie`](WebSocketSharp--Net--Cookie.md) | Provides a set of methods and properties used to manage an HTTP cookie.
`class ` [`CookieCollection`](WebSocketSharp--Net--CookieCollection.md) | Provides a collection of instances of the Cookie class.
`class ` [`CookieException`](WebSocketSharp--Net--CookieException.md) | The exception that is thrown when a Cookie gets an error.
`class ` [`EndPointListener`](WebSocketSharp--Net--EndPointListener.md) | 
`class ` [`EndPointManager`](WebSocketSharp--Net--EndPointManager.md) | 
`class ` [`HttpBasicIdentity`](WebSocketSharp--Net--HttpBasicIdentity.md) | Holds the username and password from an HTTP Basic authentication attempt.
`class ` [`HttpConnection`](WebSocketSharp--Net--HttpConnection.md) | 
`class ` [`HttpDigestIdentity`](WebSocketSharp--Net--HttpDigestIdentity.md) | Holds the username and other parameters from an HTTP Digest authentication attempt.
`class ` [`HttpHeaderInfo`](WebSocketSharp--Net--HttpHeaderInfo.md) | 
`class ` [`HttpListener`](WebSocketSharp--Net--HttpListener.md) | Provides a simple, programmatically controlled HTTP listener.
`class ` [`HttpListenerAsyncResult`](WebSocketSharp--Net--HttpListenerAsyncResult.md) | 
`class ` [`HttpListenerContext`](WebSocketSharp--Net--HttpListenerContext.md) | Provides the access to the HTTP request and response objects used by the HttpListener class.
`class ` [`HttpListenerException`](WebSocketSharp--Net--HttpListenerException.md) | The exception that is thrown when a HttpListener gets an error processing an HTTP request.
`class ` [`HttpListenerPrefix`](WebSocketSharp--Net--HttpListenerPrefix.md) | 
`class ` [`HttpListenerPrefixCollection`](WebSocketSharp--Net--HttpListenerPrefixCollection.md) | Provides a collection used to store the URI prefixes for a instance of the HttpListener class.
`class ` [`HttpListenerRequest`](WebSocketSharp--Net--HttpListenerRequest.md) | Represents an incoming HTTP request to a HttpListener instance.
`class ` [`HttpListenerResponse`](WebSocketSharp--Net--HttpListenerResponse.md) | Represents an HTTP response to an HTTP request received by a HttpListener instance.
`class ` [`HttpStreamAsyncResult`](WebSocketSharp--Net--HttpStreamAsyncResult.md) | 
`class ` [`HttpUtility`](WebSocketSharp--Net--HttpUtility.md) | 
`class ` [`HttpVersion`](WebSocketSharp--Net--HttpVersion.md) | Provides the HTTP version numbers.
`class ` [`NetworkCredential`](WebSocketSharp--Net--NetworkCredential.md) | Provides the credentials for the password-based authentication.
`class ` [`QueryStringCollection`](WebSocketSharp--Net--QueryStringCollection.md) | 
`class ` [`ReadBufferState`](WebSocketSharp--Net--ReadBufferState.md) | 
`class ` [`RequestStream`](WebSocketSharp--Net--RequestStream.md) | 
`class ` [`ResponseStream`](WebSocketSharp--Net--ResponseStream.md) | 
`class ` [`ServerSslConfiguration`](WebSocketSharp--Net--ServerSslConfiguration.md) | Stores the parameters for the SslStream used by servers.
`class ` [`WebHeaderCollection`](WebSocketSharp--Net--WebHeaderCollection.md) | Provides a collection of the HTTP headers associated with a request or response.

## Members

##### `enum ` [`AuthenticationSchemes`](#namespace_web_socket_sharp_1_1_net_1a25926eceb26224dfd35a54e69f5dec15) 

Specifies the scheme for authentication.

##### `enum ` [`HttpHeaderType`](#namespace_web_socket_sharp_1_1_net_1a0ca3b898a28ccb04a7af2cc771c384b4) 

##### `enum ` [`HttpRequestHeader`](#namespace_web_socket_sharp_1_1_net_1abdaf027ba341884b07218f836497f4f3) 

Indicates the HTTP header that may be specified in a client request.

The headers of this enumeration are defined in RFC 2616

or RFC 6455

.

##### `enum ` [`HttpResponseHeader`](#namespace_web_socket_sharp_1_1_net_1af965174270dc3b8f92b5725e4b2248d6) 

Indicates the HTTP header that can be specified in a server response.

The headers of this enumeration are defined in RFC 2616

or RFC 6455

.

##### `enum ` [`HttpStatusCode`](#namespace_web_socket_sharp_1_1_net_1ab80f66127508dfced7a0fe1929fe12cc) 

Indicates the HTTP status code that can be specified in a server response.

The values of this enumeration are defined in RFC 2616

.

##### `enum ` [`InputChunkState`](#namespace_web_socket_sharp_1_1_net_1ae44b2fbfb73e77c8537578e9622e6a4b) 

##### `enum ` [`InputState`](#namespace_web_socket_sharp_1_1_net_1aecfb003a08d29c0b75cd266ca0cadb76) 

##### `enum ` [`LineState`](#namespace_web_socket_sharp_1_1_net_1a1f8598b431e9fc31669d1ebc6937d082) 

