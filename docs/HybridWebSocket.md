# namespace `HybridWebSocket` 

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`enum ` [`WebSocketState`](#namespace_hybrid_web_socket_1a84047dc3e004de841d87c90be9dcd0f0)            | Enum representing [WebSocket](HybridWebSocket--WebSocket.md) connection state.
`enum ` [`WebSocketCloseCode`](#namespace_hybrid_web_socket_1ac75914dd7882c4cfb109b1d9b04f0305)            | Web socket close codes.
`public delegate void ` [`WebSocketOpenEventHandler`](#namespace_hybrid_web_socket_1aa4d44138c1b46c6435594ea3485e42ff)`()`            | Handler for [WebSocket](HybridWebSocket--WebSocket.md) Open event.
`public delegate void ` [`WebSocketMessageEventHandler`](#namespace_hybrid_web_socket_1aa9d4da10cb1412b5d4ece11a4ed93bb7)`(byte[] data)`            | Handler for message received from [WebSocket](HybridWebSocket--WebSocket.md).
`public delegate void ` [`WebSocketErrorEventHandler`](#namespace_hybrid_web_socket_1a619576d3ec1fd04833a0235e7e080e8e)`(string errorMsg)`            | Handler for an error event received from [WebSocket](HybridWebSocket--WebSocket.md).
`public delegate void ` [`WebSocketCloseEventHandler`](#namespace_hybrid_web_socket_1ab59ba81d4ee00b0d513e069c2b67545e)`(` [`WebSocketCloseCode`](#namespace_hybrid_web_socket_1ac75914dd7882c4cfb109b1d9b04f0305)` closeCode)`            | Handler for [WebSocket](HybridWebSocket--WebSocket.md) Close event.
`class ` [`WebSocket`](HybridWebSocket--WebSocket.md) | 
`class ` [`WebSocketException`](HybridWebSocket--WebSocketException.md) | Generic WebSocket exception class.
`class ` [`WebSocketFactory`](HybridWebSocket--WebSocketFactory.md) | Class providing static access methods to work with JSLIB WebSocket or [WebSocketSharp](WebSocketSharp.md) interface.
`class ` [`WebSocketHelpers`](HybridWebSocket--WebSocketHelpers.md) | Various helpers to work mainly with enums and exceptions.
`class ` [`WebSocketInvalidArgumentException`](HybridWebSocket--WebSocketInvalidArgumentException.md) | Invalid argument exception raised when bad arguments are passed to a method.
`class ` [`WebSocketInvalidStateException`](HybridWebSocket--WebSocketInvalidStateException.md) | Invalid state exception raised when trying to invoke action which cannot be done due to different then required state.
`class ` [`WebSocketUnexpectedException`](HybridWebSocket--WebSocketUnexpectedException.md) | Web socket exception raised when an error was not expected, probably due to corrupted internal state.
`interface ` [`IWebSocket`](#interface_hybrid_web_socket_1_1_i_web_socket) | WebSocket class interface shared by both native and JSLIB implementation.

## Members

##### `enum ` [`WebSocketState`](#namespace_hybrid_web_socket_1a84047dc3e004de841d87c90be9dcd0f0) 

Enum representing [WebSocket](HybridWebSocket--WebSocket.md) connection state.

##### `enum ` [`WebSocketCloseCode`](#namespace_hybrid_web_socket_1ac75914dd7882c4cfb109b1d9b04f0305) 

Web socket close codes.

##### `public delegate void ` [`WebSocketOpenEventHandler`](#namespace_hybrid_web_socket_1aa4d44138c1b46c6435594ea3485e42ff)`()` 

Handler for [WebSocket](HybridWebSocket--WebSocket.md) Open event.

##### `public delegate void ` [`WebSocketMessageEventHandler`](#namespace_hybrid_web_socket_1aa9d4da10cb1412b5d4ece11a4ed93bb7)`(byte[] data)` 

Handler for message received from [WebSocket](HybridWebSocket--WebSocket.md).

##### `public delegate void ` [`WebSocketErrorEventHandler`](#namespace_hybrid_web_socket_1a619576d3ec1fd04833a0235e7e080e8e)`(string errorMsg)` 

Handler for an error event received from [WebSocket](HybridWebSocket--WebSocket.md).

##### `public delegate void ` [`WebSocketCloseEventHandler`](#namespace_hybrid_web_socket_1ab59ba81d4ee00b0d513e069c2b67545e)`(` [`WebSocketCloseCode`](#namespace_hybrid_web_socket_1ac75914dd7882c4cfb109b1d9b04f0305)` closeCode)` 

Handler for [WebSocket](HybridWebSocket--WebSocket.md) Close event.

