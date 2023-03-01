# class `HybridWebSocket::WebSocket` 

```
class HybridWebSocket::WebSocket
  : public IWebSocket
```

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public ` [`WebSocket`](#class_hybrid_web_socket_1_1_web_socket_1a68061712183e36bb9a50aa0eec182470)`(string url)` | WebSocket constructor.
`public void ` [`Connect`](#class_hybrid_web_socket_1_1_web_socket_1a5b6b4e47c7e5a413015c702d9825734f)`()` | Open WebSocket connection.
`public void ` [`Close`](#class_hybrid_web_socket_1_1_web_socket_1ae9143496c90cc7021c0ca3ea40719ba2)`(` [`WebSocketCloseCode`](HybridWebSocket.md)` code, string reason)` | Close WebSocket connection with optional status code and reason.
`public void ` [`Send`](#class_hybrid_web_socket_1_1_web_socket_1aa826ba54ecf62a7df2cf50a0b93fd265)`(byte[] data)` | Send binary data over the socket.
`public ` [`WebSocketState`](HybridWebSocket.md)` ` [`GetState`](#class_hybrid_web_socket_1_1_web_socket_1a15c7ac02692c65d8f380a71a885d05dc)`()` | Return WebSocket connection state.
`protected ` [`WebSocketSharp.WebSocket`](WebSocketSharp--WebSocket.md)` ` [`ws`](#class_hybrid_web_socket_1_1_web_socket_1a20797a8cc1b055d1e89ac76539dea1b3) | The [WebSocketSharp](WebSocketSharp.md) instance.

## Members

##### `public ` [`WebSocket`](#class_hybrid_web_socket_1_1_web_socket_1a68061712183e36bb9a50aa0eec182470)`(string url)` 

WebSocket constructor.

#### Parameters
* `url` Valid WebSocket URL.

##### `public void ` [`Connect`](#class_hybrid_web_socket_1_1_web_socket_1a5b6b4e47c7e5a413015c702d9825734f)`()` 

Open WebSocket connection.

##### `public void ` [`Close`](#class_hybrid_web_socket_1_1_web_socket_1ae9143496c90cc7021c0ca3ea40719ba2)`(` [`WebSocketCloseCode`](HybridWebSocket.md)` code, string reason)` 

Close WebSocket connection with optional status code and reason.

#### Parameters
* `code` Close status code.

* `reason` Reason string.

##### `public void ` [`Send`](#class_hybrid_web_socket_1_1_web_socket_1aa826ba54ecf62a7df2cf50a0b93fd265)`(byte[] data)` 

Send binary data over the socket.

#### Parameters
* `data` Payload data.

##### `public ` [`WebSocketState`](HybridWebSocket.md)` ` [`GetState`](#class_hybrid_web_socket_1_1_web_socket_1a15c7ac02692c65d8f380a71a885d05dc)`()` 

Return WebSocket connection state.

#### Returns
The state.

##### `protected ` [`WebSocketSharp.WebSocket`](WebSocketSharp--WebSocket.md)` ` [`ws`](#class_hybrid_web_socket_1_1_web_socket_1a20797a8cc1b055d1e89ac76539dea1b3) 

The [WebSocketSharp](WebSocketSharp.md) instance.

