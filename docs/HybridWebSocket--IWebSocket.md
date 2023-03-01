# interface `HybridWebSocket::IWebSocket` 

WebSocket class interface shared by both native and JSLIB implementation.

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public void ` [`Connect`](HybridWebSocket.md)`()` | Open WebSocket connection.
`public void ` [`Close`](HybridWebSocket.md)`(` [`WebSocketCloseCode`](HybridWebSocket.md)` code, string reason)` | Close WebSocket connection with optional status code and reason.
`public void ` [`Send`](HybridWebSocket.md)`(byte[] data)` | Send binary data over the socket.
`public ` [`WebSocketState`](HybridWebSocket.md)` ` [`GetState`](HybridWebSocket.md)`()` | Return WebSocket connection state.

## Members

##### `public void ` [`Connect`](HybridWebSocket.md)`()` 

Open WebSocket connection.

##### `public void ` [`Close`](HybridWebSocket.md)`(` [`WebSocketCloseCode`](HybridWebSocket.md)` code, string reason)` 

Close WebSocket connection with optional status code and reason.

#### Parameters
* `code` Close status code.

* `reason` Reason string.

##### `public void ` [`Send`](HybridWebSocket.md)`(byte[] data)` 

Send binary data over the socket.

#### Parameters
* `data` Payload data.

##### `public ` [`WebSocketState`](HybridWebSocket.md)` ` [`GetState`](HybridWebSocket.md)`()` 

Return WebSocket connection state.

#### Returns
The state.

