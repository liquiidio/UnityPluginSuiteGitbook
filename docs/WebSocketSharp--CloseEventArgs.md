# class `WebSocketSharp::CloseEventArgs` 

```
class WebSocketSharp::CloseEventArgs
  : public EventArgs
```

Represents the event data for the WebSocket.OnClose event.

That event occurs when the WebSocket connection has been closed. 

If you would like to get the reason for the connection close, you should access the Code or Reason property.

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public ushort ` [`Code`](#class_web_socket_sharp_1_1_close_event_args_1a0ff7f8153f5f26ea4d0a03f397b22f26) | Gets the status code for the connection close.
`public string ` [`Reason`](#class_web_socket_sharp_1_1_close_event_args_1a5fd8157dac494c7c1d6a02d0c130edb6) | Gets the reason for the connection close.
`public bool ` [`WasClean`](#class_web_socket_sharp_1_1_close_event_args_1a188cf1cdada8880ad3ef1cfb82048a5c) | Gets a value indicating whether the connection has been closed cleanly.
`private bool ` [`_clean`](#class_web_socket_sharp_1_1_close_event_args_1ae30e3c68a89a0406fe709bd4a7718c03) | 
`private ` [`PayloadData`](WebSocketSharp--PayloadData.md)` ` [`_payloadData`](#class_web_socket_sharp_1_1_close_event_args_1aaf672d560272d42207991600d13b253f) | 

## Members

##### `public ushort ` [`Code`](#class_web_socket_sharp_1_1_close_event_args_1a0ff7f8153f5f26ea4d0a03f397b22f26) 

Gets the status code for the connection close.

A ushort that represents the status code for the connection close if present.

##### `public string ` [`Reason`](#class_web_socket_sharp_1_1_close_event_args_1a5fd8157dac494c7c1d6a02d0c130edb6) 

Gets the reason for the connection close.

A string that represents the reason for the connection close if present.

##### `public bool ` [`WasClean`](#class_web_socket_sharp_1_1_close_event_args_1a188cf1cdada8880ad3ef1cfb82048a5c) 

Gets a value indicating whether the connection has been closed cleanly.

`true` if the connection has been closed cleanly; otherwise, `false`.

##### `private bool ` [`_clean`](#class_web_socket_sharp_1_1_close_event_args_1ae30e3c68a89a0406fe709bd4a7718c03) 

##### `private ` [`PayloadData`](WebSocketSharp--PayloadData.md)` ` [`_payloadData`](#class_web_socket_sharp_1_1_close_event_args_1aaf672d560272d42207991600d13b253f) 

