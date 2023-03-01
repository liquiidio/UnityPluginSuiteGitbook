# namespace `WebSocketSharp` 

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`enum ` [`ByteOrder`](#namespace_web_socket_sharp_1aaeb92d42f5a6e27b8ba19f18d69d142b)            | Specifies the byte order.
`enum ` [`CloseStatusCode`](#namespace_web_socket_sharp_1a71e4ae47558874c032d0f6383fb819ec)            | Indicates the status code for the [WebSocket](WebSocketSharp--WebSocket.md) connection close.
`enum ` [`CompressionMethod`](#namespace_web_socket_sharp_1a51f8f83c4eacdb95ee9b9acebd3d325b)            | Specifies the method for compression.
`enum ` [`Fin`](#namespace_web_socket_sharp_1a5dd4fc710152d497dce23d9b1af378c3)            | Indicates whether a [WebSocket](WebSocketSharp--WebSocket.md) frame is the final frame of a message.
`enum ` [`LogLevel`](#namespace_web_socket_sharp_1aca1fd1d8935433e6ba2e3918214e07f9)            | Specifies the logging level.
`enum ` [`Mask`](#namespace_web_socket_sharp_1a4f9243aa087b81b3954b190891e51271)            | Indicates whether the payload data of a [WebSocket](WebSocketSharp--WebSocket.md) frame is masked.
`enum ` [`Opcode`](#namespace_web_socket_sharp_1af4e942a6bee75507aada023528fce047)            | Indicates the [WebSocket](WebSocketSharp--WebSocket.md) frame type.
`enum ` [`Rsv`](#namespace_web_socket_sharp_1acf02ec6a7ff7f68711c32f6d20dfeecc)            | Indicates whether each RSV (RSV1, RSV2, and RSV3) of a [WebSocket](WebSocketSharp--WebSocket.md) frame is non-zero.
`enum ` [`WebSocketState`](#namespace_web_socket_sharp_1a2b292fb93ca005027038450a8b222b43)            | Indicates the state of a [WebSocket](WebSocketSharp--WebSocket.md) connection.
`class ` [`CloseEventArgs`](WebSocketSharp--CloseEventArgs.md) | Represents the event data for the WebSocket.OnClose event.
`class ` [`ErrorEventArgs`](WebSocketSharp--ErrorEventArgs.md) | Represents the event data for the WebSocket.OnError event.
`class ` [`Ext`](WebSocketSharp--Ext.md) | Provides a set of static methods for websocket-sharp.
`class ` [`HttpBase`](WebSocketSharp--HttpBase.md) | 
`class ` [`HttpRequest`](WebSocketSharp--HttpRequest.md) | 
`class ` [`HttpResponse`](WebSocketSharp--HttpResponse.md) | 
`class ` [`LogData`](WebSocketSharp--LogData.md) | Represents a log data used by the Logger class.
`class ` [`Logger`](WebSocketSharp--Logger.md) | Provides a set of methods and properties for logging.
`class ` [`MessageEventArgs`](WebSocketSharp--MessageEventArgs.md) | Represents the event data for the WebSocket.OnMessage event.
`class ` [`PayloadData`](WebSocketSharp--PayloadData.md) | 
`class ` [`WebSocket`](WebSocketSharp--WebSocket.md) | Implements the WebSocket interface.
`class ` [`WebSocketException`](WebSocketSharp--WebSocketException.md) | The exception that is thrown when a fatal error occurs in the WebSocket communication.
`class ` [`WebSocketFrame`](WebSocketSharp--WebSocketFrame.md) | 

## Members

##### `enum ` [`ByteOrder`](#namespace_web_socket_sharp_1aaeb92d42f5a6e27b8ba19f18d69d142b) 

Specifies the byte order.

##### `enum ` [`CloseStatusCode`](#namespace_web_socket_sharp_1a71e4ae47558874c032d0f6383fb819ec) 

Indicates the status code for the [WebSocket](WebSocketSharp--WebSocket.md) connection close.

The values of this enumeration are defined in  Section 7.4

of RFC 6455. 

"Reserved value" cannot be sent as a status code in closing handshake by an endpoint.

##### `enum ` [`CompressionMethod`](#namespace_web_socket_sharp_1a51f8f83c4eacdb95ee9b9acebd3d325b) 

Specifies the method for compression.

The methods are defined in  Compression Extensions for [WebSocket](WebSocketSharp--WebSocket.md)

.

##### `enum ` [`Fin`](#namespace_web_socket_sharp_1a5dd4fc710152d497dce23d9b1af378c3) 

Indicates whether a [WebSocket](WebSocketSharp--WebSocket.md) frame is the final frame of a message.

The values of this enumeration are defined in Section 5.2

of RFC 6455.

##### `enum ` [`LogLevel`](#namespace_web_socket_sharp_1aca1fd1d8935433e6ba2e3918214e07f9) 

Specifies the logging level.

##### `enum ` [`Mask`](#namespace_web_socket_sharp_1a4f9243aa087b81b3954b190891e51271) 

Indicates whether the payload data of a [WebSocket](WebSocketSharp--WebSocket.md) frame is masked.

The values of this enumeration are defined in Section 5.2

of RFC 6455.

##### `enum ` [`Opcode`](#namespace_web_socket_sharp_1af4e942a6bee75507aada023528fce047) 

Indicates the [WebSocket](WebSocketSharp--WebSocket.md) frame type.

The values of this enumeration are defined in  Section 5.2

of RFC 6455.

##### `enum ` [`Rsv`](#namespace_web_socket_sharp_1acf02ec6a7ff7f68711c32f6d20dfeecc) 

Indicates whether each RSV (RSV1, RSV2, and RSV3) of a [WebSocket](WebSocketSharp--WebSocket.md) frame is non-zero.

The values of this enumeration are defined in Section 5.2

of RFC 6455.

##### `enum ` [`WebSocketState`](#namespace_web_socket_sharp_1a2b292fb93ca005027038450a8b222b43) 

Indicates the state of a [WebSocket](WebSocketSharp--WebSocket.md) connection.

The values of this enumeration are defined in  The [WebSocket](WebSocketSharp--WebSocket.md) API

.

