# class `WebSocketSharp::Net::CookieException` 

```
class WebSocketSharp::Net::CookieException
  : public FormatException
  : public ISerializable
```

The exception that is thrown when a Cookie gets an error.

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public ` [`CookieException`](#class_web_socket_sharp_1_1_net_1_1_cookie_exception_1aba6c21e2c57586859e4a3ac1c739a9e5)`()` | Initializes a new instance of the CookieException class.
`public override void ` [`GetObjectData`](#class_web_socket_sharp_1_1_net_1_1_cookie_exception_1a4cbc21245ff6badf7ef5f29bb3e8ee00)`(SerializationInfo serializationInfo, StreamingContext streamingContext)` | Populates the specified SerializationInfo instance with the data needed to serialize the current instance.
`protected ` [`CookieException`](#class_web_socket_sharp_1_1_net_1_1_cookie_exception_1aa89ac608a85d148c4b01b6ce7862cba3)`(SerializationInfo serializationInfo, StreamingContext streamingContext)` | Initializes a new instance of the CookieException class with the serialized data.
`private void ISerializable. ` [`GetObjectData`](#class_web_socket_sharp_1_1_net_1_1_cookie_exception_1a4d5509ba69cde90836ddf369094242d0)`(SerializationInfo serializationInfo, StreamingContext streamingContext)` | Populates the specified SerializationInfo instance with the data needed to serialize the current instance.

## Members

##### `public ` [`CookieException`](#class_web_socket_sharp_1_1_net_1_1_cookie_exception_1aba6c21e2c57586859e4a3ac1c739a9e5)`()` 

Initializes a new instance of the CookieException class.

##### `public override void ` [`GetObjectData`](#class_web_socket_sharp_1_1_net_1_1_cookie_exception_1a4cbc21245ff6badf7ef5f29bb3e8ee00)`(SerializationInfo serializationInfo, StreamingContext streamingContext)` 

Populates the specified SerializationInfo instance with the data needed to serialize the current instance.

#### Parameters
* `serializationInfo` A SerializationInfo that holds the serialized object data. 

* `streamingContext` A StreamingContext that specifies the destination for the serialization. 

#### Exceptions
* `ArgumentNullException` *serializationInfo*  is `null`.

##### `protected ` [`CookieException`](#class_web_socket_sharp_1_1_net_1_1_cookie_exception_1aa89ac608a85d148c4b01b6ce7862cba3)`(SerializationInfo serializationInfo, StreamingContext streamingContext)` 

Initializes a new instance of the CookieException class with the serialized data.

#### Parameters
* `serializationInfo` A SerializationInfo that holds the serialized object data. 

* `streamingContext` A StreamingContext that specifies the source for the deserialization. 

#### Exceptions
* `ArgumentNullException` *serializationInfo*  is `null`.

##### `private void ISerializable. ` [`GetObjectData`](#class_web_socket_sharp_1_1_net_1_1_cookie_exception_1a4d5509ba69cde90836ddf369094242d0)`(SerializationInfo serializationInfo, StreamingContext streamingContext)` 

Populates the specified SerializationInfo instance with the data needed to serialize the current instance.

#### Parameters
* `serializationInfo` A SerializationInfo that holds the serialized object data. 

* `streamingContext` A StreamingContext that specifies the destination for the serialization. 

#### Exceptions
* `ArgumentNullException` *serializationInfo*  is `null`.

