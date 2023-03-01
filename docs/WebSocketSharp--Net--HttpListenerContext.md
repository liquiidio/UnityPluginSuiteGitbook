# class `WebSocketSharp::Net::HttpListenerContext` 

Provides the access to the HTTP request and response objects used by the HttpListener class.

This class cannot be inherited.

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`package ` [`HttpConnection`](WebSocketSharp--Net--HttpConnection.md)` ` [`Connection`](#class_web_socket_sharp_1_1_net_1_1_http_listener_context_1aeaa7be3c75c65303ec9355d32cdf7d76) | 
`package string ` [`ErrorMessage`](#class_web_socket_sharp_1_1_net_1_1_http_listener_context_1a4a0b9b632a14e17b26850b7c5ddb6096) | 
`package int ` [`ErrorStatusCode`](#class_web_socket_sharp_1_1_net_1_1_http_listener_context_1aebdea36d31d330d3ba9ac07f360e6728) | 
`package bool ` [`HasErrorMessage`](#class_web_socket_sharp_1_1_net_1_1_http_listener_context_1acdb2b73c2fc92d9a40f52cbb371eb5e5) | 
`package ` [`HttpListener`](WebSocketSharp--Net--HttpListener.md)` ` [`Listener`](#class_web_socket_sharp_1_1_net_1_1_http_listener_context_1a5f59445330f7cdaec56e697910f1a018) | 
`public ` [`HttpListenerRequest`](WebSocketSharp--Net--HttpListenerRequest.md)` ` [`Request`](#class_web_socket_sharp_1_1_net_1_1_http_listener_context_1a0f2368ed8a6de977e8c6ceba56420c8a) | Gets the HTTP request object that represents a client request.
`public ` [`HttpListenerResponse`](WebSocketSharp--Net--HttpListenerResponse.md)` ` [`Response`](#class_web_socket_sharp_1_1_net_1_1_http_listener_context_1a6e691750661f8d2066e59078e0e3078d) | Gets the HTTP response object used to send a response to the client.
`public IPrincipal ` [`User`](#class_web_socket_sharp_1_1_net_1_1_http_listener_context_1adf66d13cfa13babb9d8dba518c5413a3) | Gets the client information (identity, authentication, and security roles).
`public ` [`HttpListenerWebSocketContext`](WebSocketSharp--Net--WebSockets--HttpListenerWebSocketContext.md)` ` [`AcceptWebSocket`](#class_web_socket_sharp_1_1_net_1_1_http_listener_context_1ab4c14790725a54619c784a46b1f4e571)`(string protocol)` | Accepts a WebSocket handshake request.
`private ` [`HttpConnection`](WebSocketSharp--Net--HttpConnection.md)` ` [`_connection`](#class_web_socket_sharp_1_1_net_1_1_http_listener_context_1aadd62565d7e46d3f6cf6207ecf2267be) | 
`private string ` [`_errorMessage`](#class_web_socket_sharp_1_1_net_1_1_http_listener_context_1aa8c9b8acb1d73ef5189d9c23e89f733e) | 
`private int ` [`_errorStatusCode`](#class_web_socket_sharp_1_1_net_1_1_http_listener_context_1ac9a5d5a6344396c45e59250a648011d7) | 
`private ` [`HttpListener`](WebSocketSharp--Net--HttpListener.md)` ` [`_listener`](#class_web_socket_sharp_1_1_net_1_1_http_listener_context_1ab5753944447cd49f99da3ec676f16769) | 
`private ` [`HttpListenerRequest`](WebSocketSharp--Net--HttpListenerRequest.md)` ` [`_request`](#class_web_socket_sharp_1_1_net_1_1_http_listener_context_1ac9a7645399d3455b67fe3939e070da6e) | 
`private ` [`HttpListenerResponse`](WebSocketSharp--Net--HttpListenerResponse.md)` ` [`_response`](#class_web_socket_sharp_1_1_net_1_1_http_listener_context_1a3801a43a4ae7736589bbba4556e24c11) | 
`private IPrincipal ` [`_user`](#class_web_socket_sharp_1_1_net_1_1_http_listener_context_1a7c335d89e2fa2f5ae5e5d9011be63685) | 
`private ` [`HttpListenerWebSocketContext`](WebSocketSharp--Net--WebSockets--HttpListenerWebSocketContext.md)` ` [`_websocketContext`](#class_web_socket_sharp_1_1_net_1_1_http_listener_context_1acd08f639b6e9dd80c8401140864e9980) | 
`private void ` [`sendAuthenticationChallenge`](#class_web_socket_sharp_1_1_net_1_1_http_listener_context_1ac6900ff9f81c5b41f4ca8beeb74085c2)`(string challenge)` | 
`private static string ` [`createErrorContent`](#class_web_socket_sharp_1_1_net_1_1_http_listener_context_1af6d25c2cbecf7584695b8ec06ead4fce)`(int statusCode, string statusDescription, string message)` | 

## Members

##### `package ` [`HttpConnection`](WebSocketSharp--Net--HttpConnection.md)` ` [`Connection`](#class_web_socket_sharp_1_1_net_1_1_http_listener_context_1aeaa7be3c75c65303ec9355d32cdf7d76) 

##### `package string ` [`ErrorMessage`](#class_web_socket_sharp_1_1_net_1_1_http_listener_context_1a4a0b9b632a14e17b26850b7c5ddb6096) 

##### `package int ` [`ErrorStatusCode`](#class_web_socket_sharp_1_1_net_1_1_http_listener_context_1aebdea36d31d330d3ba9ac07f360e6728) 

##### `package bool ` [`HasErrorMessage`](#class_web_socket_sharp_1_1_net_1_1_http_listener_context_1acdb2b73c2fc92d9a40f52cbb371eb5e5) 

##### `package ` [`HttpListener`](WebSocketSharp--Net--HttpListener.md)` ` [`Listener`](#class_web_socket_sharp_1_1_net_1_1_http_listener_context_1a5f59445330f7cdaec56e697910f1a018) 

##### `public ` [`HttpListenerRequest`](WebSocketSharp--Net--HttpListenerRequest.md)` ` [`Request`](#class_web_socket_sharp_1_1_net_1_1_http_listener_context_1a0f2368ed8a6de977e8c6ceba56420c8a) 

Gets the HTTP request object that represents a client request.

A HttpListenerRequest that represents the client request.

##### `public ` [`HttpListenerResponse`](WebSocketSharp--Net--HttpListenerResponse.md)` ` [`Response`](#class_web_socket_sharp_1_1_net_1_1_http_listener_context_1a6e691750661f8d2066e59078e0e3078d) 

Gets the HTTP response object used to send a response to the client.

A HttpListenerResponse that represents a response to the client request.

##### `public IPrincipal ` [`User`](#class_web_socket_sharp_1_1_net_1_1_http_listener_context_1adf66d13cfa13babb9d8dba518c5413a3) 

Gets the client information (identity, authentication, and security roles).

A IPrincipal instance or `null` if not authenticated. 

The instance describes the client.

##### `public ` [`HttpListenerWebSocketContext`](WebSocketSharp--Net--WebSockets--HttpListenerWebSocketContext.md)` ` [`AcceptWebSocket`](#class_web_socket_sharp_1_1_net_1_1_http_listener_context_1ab4c14790725a54619c784a46b1f4e571)`(string protocol)` 

Accepts a WebSocket handshake request.

#### Returns
A HttpListenerWebSocketContext that represents the WebSocket handshake request. 

#### Parameters
* `protocol` A string that specifies the subprotocol supported on the WebSocket connection. 

#### Exceptions
* `ArgumentException` *protocol*  is empty. 

-or- 

*protocol*  contains an invalid character. 

* `InvalidOperationException` This method has already been called.

##### `private ` [`HttpConnection`](WebSocketSharp--Net--HttpConnection.md)` ` [`_connection`](#class_web_socket_sharp_1_1_net_1_1_http_listener_context_1aadd62565d7e46d3f6cf6207ecf2267be) 

##### `private string ` [`_errorMessage`](#class_web_socket_sharp_1_1_net_1_1_http_listener_context_1aa8c9b8acb1d73ef5189d9c23e89f733e) 

##### `private int ` [`_errorStatusCode`](#class_web_socket_sharp_1_1_net_1_1_http_listener_context_1ac9a5d5a6344396c45e59250a648011d7) 

##### `private ` [`HttpListener`](WebSocketSharp--Net--HttpListener.md)` ` [`_listener`](#class_web_socket_sharp_1_1_net_1_1_http_listener_context_1ab5753944447cd49f99da3ec676f16769) 

##### `private ` [`HttpListenerRequest`](WebSocketSharp--Net--HttpListenerRequest.md)` ` [`_request`](#class_web_socket_sharp_1_1_net_1_1_http_listener_context_1ac9a7645399d3455b67fe3939e070da6e) 

##### `private ` [`HttpListenerResponse`](WebSocketSharp--Net--HttpListenerResponse.md)` ` [`_response`](#class_web_socket_sharp_1_1_net_1_1_http_listener_context_1a3801a43a4ae7736589bbba4556e24c11) 

##### `private IPrincipal ` [`_user`](#class_web_socket_sharp_1_1_net_1_1_http_listener_context_1a7c335d89e2fa2f5ae5e5d9011be63685) 

##### `private ` [`HttpListenerWebSocketContext`](WebSocketSharp--Net--WebSockets--HttpListenerWebSocketContext.md)` ` [`_websocketContext`](#class_web_socket_sharp_1_1_net_1_1_http_listener_context_1acd08f639b6e9dd80c8401140864e9980) 

##### `private void ` [`sendAuthenticationChallenge`](#class_web_socket_sharp_1_1_net_1_1_http_listener_context_1ac6900ff9f81c5b41f4ca8beeb74085c2)`(string challenge)` 

##### `private static string ` [`createErrorContent`](#class_web_socket_sharp_1_1_net_1_1_http_listener_context_1af6d25c2cbecf7584695b8ec06ead4fce)`(int statusCode, string statusDescription, string message)` 

