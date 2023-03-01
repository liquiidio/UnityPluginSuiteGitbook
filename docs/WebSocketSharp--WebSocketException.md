# class `WebSocketSharp::WebSocketException` 

```
class WebSocketSharp::WebSocketException
  : public Exception
```

The exception that is thrown when a fatal error occurs in the WebSocket communication.

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public ` [`CloseStatusCode`](WebSocketSharp.md)` ` [`Code`](#class_web_socket_sharp_1_1_web_socket_exception_1af3fa6b6d685a8e14771041a3f01eb2e1) | Gets the status code indicating the cause of the exception.
`private ` [`CloseStatusCode`](WebSocketSharp.md)` ` [`_code`](#class_web_socket_sharp_1_1_web_socket_exception_1a019a885a66a2cf098abbc9c15114f5db) | 

## Members

##### `public ` [`CloseStatusCode`](WebSocketSharp.md)` ` [`Code`](#class_web_socket_sharp_1_1_web_socket_exception_1af3fa6b6d685a8e14771041a3f01eb2e1) 

Gets the status code indicating the cause of the exception.

One of the CloseStatusCode enum values that represents the status code indicating the cause of the exception.

##### `private ` [`CloseStatusCode`](WebSocketSharp.md)` ` [`_code`](#class_web_socket_sharp_1_1_web_socket_exception_1a019a885a66a2cf098abbc9c15114f5db) 

