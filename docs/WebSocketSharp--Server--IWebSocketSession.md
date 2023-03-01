# interface `WebSocketSharp::Server::IWebSocketSession` 

Exposes the access to the information in a WebSocket session.

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public ` [`WebSocketState`](WebSocketSharp.md)` ` [`ConnectionState`](WebSocketSharp--Server.md) | Gets the current state of the WebSocket connection for the session.
`public ` [`WebSocketContext`](WebSocketSharp--Net--WebSockets--WebSocketContext.md)` ` [`Context`](WebSocketSharp--Server.md) | Gets the information in the WebSocket handshake request.
`public string ` [`ID`](WebSocketSharp--Server.md) | Gets the unique ID of the session.
`public string ` [`Protocol`](WebSocketSharp--Server.md) | Gets the name of the WebSocket subprotocol for the session.
`public DateTime ` [`StartTime`](WebSocketSharp--Server.md) | Gets the time that the session has started.

## Members

##### `public ` [`WebSocketState`](WebSocketSharp.md)` ` [`ConnectionState`](WebSocketSharp--Server.md) 

Gets the current state of the WebSocket connection for the session.

One of the WebSocketState enum values. 

It indicates the current state of the connection.

##### `public ` [`WebSocketContext`](WebSocketSharp--Net--WebSockets--WebSocketContext.md)` ` [`Context`](WebSocketSharp--Server.md) 

Gets the information in the WebSocket handshake request.

A WebSocketContext instance that provides the access to the information in the handshake request.

##### `public string ` [`ID`](WebSocketSharp--Server.md) 

Gets the unique ID of the session.

A string that represents the unique ID of the session.

##### `public string ` [`Protocol`](WebSocketSharp--Server.md) 

Gets the name of the WebSocket subprotocol for the session.

A string that represents the name of the subprotocol if present.

##### `public DateTime ` [`StartTime`](WebSocketSharp--Server.md) 

Gets the time that the session has started.

A DateTime that represents the time that the session has started.

