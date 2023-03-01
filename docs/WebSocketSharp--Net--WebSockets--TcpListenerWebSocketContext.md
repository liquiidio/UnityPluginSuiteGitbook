# class `WebSocketSharp::Net::WebSockets::TcpListenerWebSocketContext` 

```
class WebSocketSharp::Net::WebSockets::TcpListenerWebSocketContext
  : public WebSocketContext
```

Provides the access to the information in a WebSocket handshake request to a TcpListener instance.

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`package ` [`Logger`](WebSocketSharp--Logger.md)` ` [`Log`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_tcp_listener_web_socket_context_1af2ed886ec3d2b2fd42fd0c5dad2f8cc5) | 
`package Stream ` [`Stream`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_tcp_listener_web_socket_context_1a389e58abbb7b2860d86cb6406557a12c) | 
`public override ` [`CookieCollection`](WebSocketSharp--Net--CookieCollection.md)` ` [`CookieCollection`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_tcp_listener_web_socket_context_1a020a40cfe46647c51e551f18792557f5) | Gets the HTTP cookies included in the handshake request.
`public override NameValueCollection ` [`Headers`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_tcp_listener_web_socket_context_1af805b1ce4afce449dd5e6eb450ba9d46) | Gets the HTTP headers included in the handshake request.
`public override string ` [`Host`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_tcp_listener_web_socket_context_1a3b83d9f51609775175674665b4a86665) | Gets the value of the Host header included in the handshake request.
`public override bool ` [`IsAuthenticated`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_tcp_listener_web_socket_context_1aa3c5d1dc8b23f641c08311b9dd007b2c) | Gets a value indicating whether the client is authenticated.
`public override bool ` [`IsLocal`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_tcp_listener_web_socket_context_1a448a8a9045fcd703bdc097ca537cd991) | Gets a value indicating whether the handshake request is sent from the local computer.
`public override bool ` [`IsSecureConnection`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_tcp_listener_web_socket_context_1a14662c4926c3d02eb202627d8c4fb81b) | Gets a value indicating whether a secure connection is used to send the handshake request.
`public override bool ` [`IsWebSocketRequest`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_tcp_listener_web_socket_context_1a0fe7035cc5799b94aa8f411b9ba0adb1) | Gets a value indicating whether the request is a WebSocket handshake request.
`public override string ` [`Origin`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_tcp_listener_web_socket_context_1a60ec9276b93382b4274fb80c53c83bc3) | Gets the value of the Origin header included in the handshake request.
`public override NameValueCollection ` [`QueryString`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_tcp_listener_web_socket_context_1ad9b4410cddcc5ef3a835573978f3ae72) | Gets the query string included in the handshake request.
`public override Uri ` [`RequestUri`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_tcp_listener_web_socket_context_1ae1c7d22356a1f11d5b5942dfd56d8a6d) | Gets the URI requested by the client.
`public override string ` [`SecWebSocketKey`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_tcp_listener_web_socket_context_1accc57d14f238bc9c6106e46523510d4b) | Gets the value of the Sec-WebSocket-Key header included in the handshake request.
`public override IEnumerable< string > ` [`SecWebSocketProtocols`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_tcp_listener_web_socket_context_1af310340c928809a21a3234eefb366f7b) | Gets the names of the subprotocols from the Sec-WebSocket-Protocol header included in the handshake request.
`public override string ` [`SecWebSocketVersion`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_tcp_listener_web_socket_context_1a0ee0e4d6d9cbea7dec4b91e38df443b1) | Gets the value of the Sec-WebSocket-Version header included in the handshake request.
`public override System.Net.IPEndPoint ` [`ServerEndPoint`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_tcp_listener_web_socket_context_1a0b116b66180e209815fa5dc07631a839) | Gets the endpoint to which the handshake request is sent.
`public override IPrincipal ` [`User`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_tcp_listener_web_socket_context_1a4afc8d84241127d98ee29e85d5b0b3bd) | Gets the client information.
`public override System.Net.IPEndPoint ` [`UserEndPoint`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_tcp_listener_web_socket_context_1a4ee932601fe725b88b920651f39ac6f5) | Gets the endpoint from which the handshake request is sent.
`public override ` [`WebSocket`](WebSocketSharp--WebSocket.md)` ` [`WebSocket`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_tcp_listener_web_socket_context_1a05c989264be32d71375f9ec19d4320fa) | Gets the WebSocket instance used for two-way communication between the client and server.
`public override string ` [`ToString`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_tcp_listener_web_socket_context_1aa73e7c4dd1df5fd5fbf81c7764ee1533)`()` | Returns a string that represents the current instance.
`private ` [`Logger`](WebSocketSharp--Logger.md)` ` [`_log`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_tcp_listener_web_socket_context_1ab09157ab30052b0f1bf60fe26410d6ee) | 
`private NameValueCollection ` [`_queryString`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_tcp_listener_web_socket_context_1a24298c922140b3c6d1923083db07ec9c) | 
`private ` [`HttpRequest`](WebSocketSharp--HttpRequest.md)` ` [`_request`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_tcp_listener_web_socket_context_1acf6982f7ba4951ae31de213c96d893a0) | 
`private Uri ` [`_requestUri`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_tcp_listener_web_socket_context_1aa4ed9d00f2a53aa0605a464914dcc3cb) | 
`private bool ` [`_secure`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_tcp_listener_web_socket_context_1a2f7b5b309c5830b8532939ca02946b44) | 
`private System.Net.EndPoint ` [`_serverEndPoint`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_tcp_listener_web_socket_context_1a21e6b7aaecb530794daf70c5b4bb660b) | 
`private ` [`Stream`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_tcp_listener_web_socket_context_1a389e58abbb7b2860d86cb6406557a12c)` ` [`_stream`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_tcp_listener_web_socket_context_1ae5401654b26ad72d9da131e0a3db7eb8) | 
`private TcpClient ` [`_tcpClient`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_tcp_listener_web_socket_context_1a90eb17ad2d30dea9b36901e5dbb080dc) | 
`private IPrincipal ` [`_user`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_tcp_listener_web_socket_context_1a7c335d89e2fa2f5ae5e5d9011be63685) | 
`private System.Net.EndPoint ` [`_userEndPoint`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_tcp_listener_web_socket_context_1a142dd8cc7c1da8d1f0bc49ea99f8f1a4) | 
`private ` [`WebSocket`](WebSocketSharp--WebSocket.md)` ` [`_websocket`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_tcp_listener_web_socket_context_1a6b4391ac74acffa01a6b60fe34ebca39) | 
`private ` [`HttpRequest`](WebSocketSharp--HttpRequest.md)` ` [`sendAuthenticationChallenge`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_tcp_listener_web_socket_context_1a73080a43021f3bc0305ea1dc8b3af0c1)`(string challenge)` | 

## Members

##### `package ` [`Logger`](WebSocketSharp--Logger.md)` ` [`Log`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_tcp_listener_web_socket_context_1af2ed886ec3d2b2fd42fd0c5dad2f8cc5) 

##### `package Stream ` [`Stream`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_tcp_listener_web_socket_context_1a389e58abbb7b2860d86cb6406557a12c) 

##### `public override ` [`CookieCollection`](WebSocketSharp--Net--CookieCollection.md)` ` [`CookieCollection`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_tcp_listener_web_socket_context_1a020a40cfe46647c51e551f18792557f5) 

Gets the HTTP cookies included in the handshake request.

A [WebSocketSharp.Net.CookieCollection](WebSocketSharp--Net--CookieCollection.md) that contains the cookies. 

An empty collection if not included.

##### `public override NameValueCollection ` [`Headers`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_tcp_listener_web_socket_context_1af805b1ce4afce449dd5e6eb450ba9d46) 

Gets the HTTP headers included in the handshake request.

A NameValueCollection that contains the headers.

##### `public override string ` [`Host`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_tcp_listener_web_socket_context_1a3b83d9f51609775175674665b4a86665) 

Gets the value of the Host header included in the handshake request.

A string that represents the server host name requested by the client. 

It includes the port number if provided.

##### `public override bool ` [`IsAuthenticated`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_tcp_listener_web_socket_context_1aa3c5d1dc8b23f641c08311b9dd007b2c) 

Gets a value indicating whether the client is authenticated.

`true` if the client is authenticated; otherwise, `false`.

##### `public override bool ` [`IsLocal`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_tcp_listener_web_socket_context_1a448a8a9045fcd703bdc097ca537cd991) 

Gets a value indicating whether the handshake request is sent from the local computer.

`true` if the handshake request is sent from the same computer as the server; otherwise, `false`.

##### `public override bool ` [`IsSecureConnection`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_tcp_listener_web_socket_context_1a14662c4926c3d02eb202627d8c4fb81b) 

Gets a value indicating whether a secure connection is used to send the handshake request.

`true` if the connection is secure; otherwise, `false`.

##### `public override bool ` [`IsWebSocketRequest`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_tcp_listener_web_socket_context_1a0fe7035cc5799b94aa8f411b9ba0adb1) 

Gets a value indicating whether the request is a WebSocket handshake request.

`true` if the request is a WebSocket handshake request; otherwise, `false`.

##### `public override string ` [`Origin`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_tcp_listener_web_socket_context_1a60ec9276b93382b4274fb80c53c83bc3) 

Gets the value of the Origin header included in the handshake request.

A string that represents the value of the Origin header. 

`null` if the header is not present.

##### `public override NameValueCollection ` [`QueryString`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_tcp_listener_web_socket_context_1ad9b4410cddcc5ef3a835573978f3ae72) 

Gets the query string included in the handshake request.

A NameValueCollection that contains the query parameters. 

An empty collection if not included.

##### `public override Uri ` [`RequestUri`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_tcp_listener_web_socket_context_1ae1c7d22356a1f11d5b5942dfd56d8a6d) 

Gets the URI requested by the client.

A Uri that represents the URI parsed from the request. 

`null` if the URI cannot be parsed.

##### `public override string ` [`SecWebSocketKey`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_tcp_listener_web_socket_context_1accc57d14f238bc9c6106e46523510d4b) 

Gets the value of the Sec-WebSocket-Key header included in the handshake request.

A string that represents the value of the Sec-WebSocket-Key header. 

The value is used to prove that the server received a valid WebSocket handshake request. 

`null` if the header is not present.

##### `public override IEnumerable< string > ` [`SecWebSocketProtocols`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_tcp_listener_web_socket_context_1af310340c928809a21a3234eefb366f7b) 

Gets the names of the subprotocols from the Sec-WebSocket-Protocol header included in the handshake request.

An T:System.Collections.Generic.IEnumerable<string> instance. 

It provides an enumerator which supports the iteration over the collection of the names of the subprotocols.

##### `public override string ` [`SecWebSocketVersion`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_tcp_listener_web_socket_context_1a0ee0e4d6d9cbea7dec4b91e38df443b1) 

Gets the value of the Sec-WebSocket-Version header included in the handshake request.

A string that represents the WebSocket protocol version specified by the client. 

`null` if the header is not present.

##### `public override System.Net.IPEndPoint ` [`ServerEndPoint`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_tcp_listener_web_socket_context_1a0b116b66180e209815fa5dc07631a839) 

Gets the endpoint to which the handshake request is sent.

A System.Net.IPEndPoint that represents the server IP address and port number.

##### `public override IPrincipal ` [`User`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_tcp_listener_web_socket_context_1a4afc8d84241127d98ee29e85d5b0b3bd) 

Gets the client information.

A IPrincipal instance that represents identity, authentication, and security roles for the client. 

`null` if the client is not authenticated.

##### `public override System.Net.IPEndPoint ` [`UserEndPoint`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_tcp_listener_web_socket_context_1a4ee932601fe725b88b920651f39ac6f5) 

Gets the endpoint from which the handshake request is sent.

A System.Net.IPEndPoint that represents the client IP address and port number.

##### `public override ` [`WebSocket`](WebSocketSharp--WebSocket.md)` ` [`WebSocket`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_tcp_listener_web_socket_context_1a05c989264be32d71375f9ec19d4320fa) 

Gets the WebSocket instance used for two-way communication between the client and server.

A [WebSocketSharp.WebSocket](WebSocketSharp--WebSocket.md).

##### `public override string ` [`ToString`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_tcp_listener_web_socket_context_1aa73e7c4dd1df5fd5fbf81c7764ee1533)`()` 

Returns a string that represents the current instance.

#### Returns
A string that contains the request line and headers included in the handshake request.

##### `private ` [`Logger`](WebSocketSharp--Logger.md)` ` [`_log`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_tcp_listener_web_socket_context_1ab09157ab30052b0f1bf60fe26410d6ee) 

##### `private NameValueCollection ` [`_queryString`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_tcp_listener_web_socket_context_1a24298c922140b3c6d1923083db07ec9c) 

##### `private ` [`HttpRequest`](WebSocketSharp--HttpRequest.md)` ` [`_request`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_tcp_listener_web_socket_context_1acf6982f7ba4951ae31de213c96d893a0) 

##### `private Uri ` [`_requestUri`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_tcp_listener_web_socket_context_1aa4ed9d00f2a53aa0605a464914dcc3cb) 

##### `private bool ` [`_secure`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_tcp_listener_web_socket_context_1a2f7b5b309c5830b8532939ca02946b44) 

##### `private System.Net.EndPoint ` [`_serverEndPoint`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_tcp_listener_web_socket_context_1a21e6b7aaecb530794daf70c5b4bb660b) 

##### `private ` [`Stream`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_tcp_listener_web_socket_context_1a389e58abbb7b2860d86cb6406557a12c)` ` [`_stream`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_tcp_listener_web_socket_context_1ae5401654b26ad72d9da131e0a3db7eb8) 

##### `private TcpClient ` [`_tcpClient`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_tcp_listener_web_socket_context_1a90eb17ad2d30dea9b36901e5dbb080dc) 

##### `private IPrincipal ` [`_user`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_tcp_listener_web_socket_context_1a7c335d89e2fa2f5ae5e5d9011be63685) 

##### `private System.Net.EndPoint ` [`_userEndPoint`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_tcp_listener_web_socket_context_1a142dd8cc7c1da8d1f0bc49ea99f8f1a4) 

##### `private ` [`WebSocket`](WebSocketSharp--WebSocket.md)` ` [`_websocket`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_tcp_listener_web_socket_context_1a6b4391ac74acffa01a6b60fe34ebca39) 

##### `private ` [`HttpRequest`](WebSocketSharp--HttpRequest.md)` ` [`sendAuthenticationChallenge`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_tcp_listener_web_socket_context_1a73080a43021f3bc0305ea1dc8b3af0c1)`(string challenge)` 

