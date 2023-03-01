# class `HybridWebSocket::WebSocketHelpers` 

Various helpers to work mainly with enums and exceptions.

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public static ` [`WebSocketCloseCode`](HybridWebSocket.md)` ` [`ParseCloseCodeEnum`](#class_hybrid_web_socket_1_1_web_socket_helpers_1aa73f60b18c7ac01e89ded1f1f3503634)`(int closeCode)` | Safely parse close code enum from int value.
`public static ` [`WebSocketException`](HybridWebSocket--WebSocketException.md)` ` [`GetErrorMessageFromCode`](#class_hybrid_web_socket_1_1_web_socket_helpers_1aa5d0641c7842de83216a97e980c86acc)`(int errorCode, Exception inner)` | Return an exception instance based on int code.

## Members

##### `public static ` [`WebSocketCloseCode`](HybridWebSocket.md)` ` [`ParseCloseCodeEnum`](#class_hybrid_web_socket_1_1_web_socket_helpers_1aa73f60b18c7ac01e89ded1f1f3503634)`(int closeCode)` 

Safely parse close code enum from int value.

#### Returns
The close code enum.

#### Parameters
* `closeCode` Close code as int.

##### `public static ` [`WebSocketException`](HybridWebSocket--WebSocketException.md)` ` [`GetErrorMessageFromCode`](#class_hybrid_web_socket_1_1_web_socket_helpers_1aa5d0641c7842de83216a97e980c86acc)`(int errorCode, Exception inner)` 

Return an exception instance based on int code.

Used for resolving JSLIB errors to meaninfull messages.

#### Returns
Instance of an exception.

#### Parameters
* `errorCode` Error code.

* `inner` Inner exception

