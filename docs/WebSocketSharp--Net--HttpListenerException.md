# class `WebSocketSharp::Net::HttpListenerException` 

```
class WebSocketSharp::Net::HttpListenerException
  : public Win32Exception
```

The exception that is thrown when a HttpListener gets an error processing an HTTP request.

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public override int ` [`ErrorCode`](#class_web_socket_sharp_1_1_net_1_1_http_listener_exception_1abbbc717dde46b02e162defefd34101ae) | Gets the error code that identifies the error that occurred.
`public ` [`HttpListenerException`](#class_web_socket_sharp_1_1_net_1_1_http_listener_exception_1ad4a6bbe159375701b65e8368db40b9e3)`()` | Initializes a new instance of the HttpListenerException class.
`public ` [`HttpListenerException`](#class_web_socket_sharp_1_1_net_1_1_http_listener_exception_1a5a5354552ef501ac1c38b0f9547ac6f0)`(int errorCode)` | Initializes a new instance of the HttpListenerException class with the specified *errorCode* .
`public ` [`HttpListenerException`](#class_web_socket_sharp_1_1_net_1_1_http_listener_exception_1abd732423ec24215e04887f41e980a7a8)`(int errorCode, string message)` | Initializes a new instance of the HttpListenerException class with the specified *errorCode* and *message* .
`protected ` [`HttpListenerException`](#class_web_socket_sharp_1_1_net_1_1_http_listener_exception_1ad501f81ac71eb594663fa3a8a9149045)`(SerializationInfo serializationInfo, StreamingContext streamingContext)` | Initializes a new instance of the HttpListenerException class from the specified SerializationInfo and StreamingContext.

## Members

##### `public override int ` [`ErrorCode`](#class_web_socket_sharp_1_1_net_1_1_http_listener_exception_1abbbc717dde46b02e162defefd34101ae) 

Gets the error code that identifies the error that occurred.

An int that identifies the error.

##### `public ` [`HttpListenerException`](#class_web_socket_sharp_1_1_net_1_1_http_listener_exception_1ad4a6bbe159375701b65e8368db40b9e3)`()` 

Initializes a new instance of the HttpListenerException class.

##### `public ` [`HttpListenerException`](#class_web_socket_sharp_1_1_net_1_1_http_listener_exception_1a5a5354552ef501ac1c38b0f9547ac6f0)`(int errorCode)` 

Initializes a new instance of the HttpListenerException class with the specified *errorCode* .

#### Parameters
* `errorCode` An int that identifies the error.

##### `public ` [`HttpListenerException`](#class_web_socket_sharp_1_1_net_1_1_http_listener_exception_1abd732423ec24215e04887f41e980a7a8)`(int errorCode, string message)` 

Initializes a new instance of the HttpListenerException class with the specified *errorCode*  and *message* .

#### Parameters
* `errorCode` An int that identifies the error. 

* `message` A string that describes the error.

##### `protected ` [`HttpListenerException`](#class_web_socket_sharp_1_1_net_1_1_http_listener_exception_1ad501f81ac71eb594663fa3a8a9149045)`(SerializationInfo serializationInfo, StreamingContext streamingContext)` 

Initializes a new instance of the HttpListenerException class from the specified SerializationInfo and StreamingContext.

#### Parameters
* `serializationInfo` A SerializationInfo that contains the serialized object data. 

* `streamingContext` A StreamingContext that specifies the source for the deserialization.

