# class `WebSocketSharp::Net::WebSockets::WebSocketContext` 

Exposes the access to the information in a WebSocket handshake request.

This class is an abstract class.

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public abstract ` [`CookieCollection`](WebSocketSharp--Net--CookieCollection.md)` ` [`CookieCollection`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_web_socket_context_1a08fd9ad34eb4742b16808ba7ff33962e) | Gets the HTTP cookies included in the handshake request.
`public abstract NameValueCollection ` [`Headers`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_web_socket_context_1ad27e377e188be8166ee5e5bba717de6b) | Gets the HTTP headers included in the handshake request.
`public abstract string ` [`Host`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_web_socket_context_1aa32ae660ee6490023fa53e78c4359124) | Gets the value of the Host header included in the handshake request.
`public abstract bool ` [`IsAuthenticated`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_web_socket_context_1a8f4e8fd8494bf8c2c81bbb0f56381c04) | Gets a value indicating whether the client is authenticated.
`public abstract bool ` [`IsLocal`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_web_socket_context_1ad1d9e7fdf542f1dac41c175579b4d1eb) | Gets a value indicating whether the handshake request is sent from the local computer.
`public abstract bool ` [`IsSecureConnection`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_web_socket_context_1af8ce6d6f0e0004d5165ab71ac043691b) | Gets a value indicating whether a secure connection is used to send the handshake request.
`public abstract bool ` [`IsWebSocketRequest`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_web_socket_context_1ab4f6e28467a655f2c6c69e59be37b0a0) | Gets a value indicating whether the request is a WebSocket handshake request.
`public abstract string ` [`Origin`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_web_socket_context_1aa81a3dc6bdb3d18e78cb040e18d75d2f) | Gets the value of the Origin header included in the handshake request.
`public abstract NameValueCollection ` [`QueryString`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_web_socket_context_1a1383b5de4f6b40d62b3e4ddb85099941) | Gets the query string included in the handshake request.
`public abstract Uri ` [`RequestUri`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_web_socket_context_1a7d2af62188e56c7ef43f7fa12f5ecb7e) | Gets the URI requested by the client.
`public abstract string ` [`SecWebSocketKey`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_web_socket_context_1a09b9ed6d839a8f5a6e351b988bacc847) | Gets the value of the Sec-WebSocket-Key header included in the handshake request.
`public abstract IEnumerable< string > ` [`SecWebSocketProtocols`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_web_socket_context_1aa5f8a5e5f301de7c6296289f720fc692) | Gets the names of the subprotocols from the Sec-WebSocket-Protocol header included in the handshake request.
`public abstract string ` [`SecWebSocketVersion`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_web_socket_context_1abecf380ce7d08830c1547abcdfe8a55e) | Gets the value of the Sec-WebSocket-Version header included in the handshake request.
`public abstract System.Net.IPEndPoint ` [`ServerEndPoint`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_web_socket_context_1ae4e69ad9fccff35fe27aa3351fa8e905) | Gets the endpoint to which the handshake request is sent.
`public abstract IPrincipal ` [`User`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_web_socket_context_1a7196b24d6ca4118a1844a251dbf589aa) | Gets the client information.
`public abstract System.Net.IPEndPoint ` [`UserEndPoint`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_web_socket_context_1a1ba46f66731275c1e618cc4833fe7281) | Gets the endpoint from which the handshake request is sent.
`public abstract ` [`WebSocket`](WebSocketSharp--WebSocket.md)` ` [`WebSocket`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_web_socket_context_1a4c73e7ffe1a34c2d0058671cdabb6bc6) | Gets the WebSocket instance used for two-way communication between the client and server.
`protected ` [`WebSocketContext`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_web_socket_context_1a76fc2e1f64951741684fde84c3c85010)`()` | Initializes a new instance of the WebSocketContext class.

## Members

##### `public abstract ` [`CookieCollection`](WebSocketSharp--Net--CookieCollection.md)` ` [`CookieCollection`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_web_socket_context_1a08fd9ad34eb4742b16808ba7ff33962e) 

Gets the HTTP cookies included in the handshake request.

A [WebSocketSharp.Net.CookieCollection](WebSocketSharp--Net--CookieCollection.md) that contains the cookies.

##### `public abstract NameValueCollection ` [`Headers`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_web_socket_context_1ad27e377e188be8166ee5e5bba717de6b) 

Gets the HTTP headers included in the handshake request.

A NameValueCollection that contains the headers.

##### `public abstract string ` [`Host`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_web_socket_context_1aa32ae660ee6490023fa53e78c4359124) 

Gets the value of the Host header included in the handshake request.

A string that represents the server host name requested by the client.

##### `public abstract bool ` [`IsAuthenticated`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_web_socket_context_1a8f4e8fd8494bf8c2c81bbb0f56381c04) 

Gets a value indicating whether the client is authenticated.

`true` if the client is authenticated; otherwise, `false`.

##### `public abstract bool ` [`IsLocal`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_web_socket_context_1ad1d9e7fdf542f1dac41c175579b4d1eb) 

Gets a value indicating whether the handshake request is sent from the local computer.

`true` if the handshake request is sent from the same computer as the server; otherwise, `false`.

##### `public abstract bool ` [`IsSecureConnection`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_web_socket_context_1af8ce6d6f0e0004d5165ab71ac043691b) 

Gets a value indicating whether a secure connection is used to send the handshake request.

`true` if the connection is secure; otherwise, `false`.

##### `public abstract bool ` [`IsWebSocketRequest`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_web_socket_context_1ab4f6e28467a655f2c6c69e59be37b0a0) 

Gets a value indicating whether the request is a WebSocket handshake request.

`true` if the request is a WebSocket handshake request; otherwise, `false`.

##### `public abstract string ` [`Origin`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_web_socket_context_1aa81a3dc6bdb3d18e78cb040e18d75d2f) 

Gets the value of the Origin header included in the handshake request.

A string that represents the value of the Origin header.

##### `public abstract NameValueCollection ` [`QueryString`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_web_socket_context_1a1383b5de4f6b40d62b3e4ddb85099941) 

Gets the query string included in the handshake request.

A NameValueCollection that contains the query parameters.

##### `public abstract Uri ` [`RequestUri`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_web_socket_context_1a7d2af62188e56c7ef43f7fa12f5ecb7e) 

Gets the URI requested by the client.

A Uri that represents the URI parsed from the request.

##### `public abstract string ` [`SecWebSocketKey`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_web_socket_context_1a09b9ed6d839a8f5a6e351b988bacc847) 

Gets the value of the Sec-WebSocket-Key header included in the handshake request.

A string that represents the value of the Sec-WebSocket-Key header. 

The value is used to prove that the server received a valid WebSocket handshake request.

##### `public abstract IEnumerable< string > ` [`SecWebSocketProtocols`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_web_socket_context_1aa5f8a5e5f301de7c6296289f720fc692) 

Gets the names of the subprotocols from the Sec-WebSocket-Protocol header included in the handshake request.

An T:System.Collections.Generic.IEnumerable<string> instance. 

It provides an enumerator which supports the iteration over the collection of the names of the subprotocols.

##### `public abstract string ` [`SecWebSocketVersion`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_web_socket_context_1abecf380ce7d08830c1547abcdfe8a55e) 

Gets the value of the Sec-WebSocket-Version header included in the handshake request.

A string that represents the WebSocket protocol version specified by the client.

##### `public abstract System.Net.IPEndPoint ` [`ServerEndPoint`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_web_socket_context_1ae4e69ad9fccff35fe27aa3351fa8e905) 

Gets the endpoint to which the handshake request is sent.

A System.Net.IPEndPoint that represents the server IP address and port number.

##### `public abstract IPrincipal ` [`User`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_web_socket_context_1a7196b24d6ca4118a1844a251dbf589aa) 

Gets the client information.

A IPrincipal instance that represents identity, authentication, and security roles for the client.

##### `public abstract System.Net.IPEndPoint ` [`UserEndPoint`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_web_socket_context_1a1ba46f66731275c1e618cc4833fe7281) 

Gets the endpoint from which the handshake request is sent.

A System.Net.IPEndPoint that represents the client IP address and port number.

##### `public abstract ` [`WebSocket`](WebSocketSharp--WebSocket.md)` ` [`WebSocket`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_web_socket_context_1a4c73e7ffe1a34c2d0058671cdabb6bc6) 

Gets the WebSocket instance used for two-way communication between the client and server.

A [WebSocketSharp.WebSocket](WebSocketSharp--WebSocket.md).

##### `protected ` [`WebSocketContext`](#class_web_socket_sharp_1_1_net_1_1_web_sockets_1_1_web_socket_context_1a76fc2e1f64951741684fde84c3c85010)`()` 

Initializes a new instance of the WebSocketContext class.

