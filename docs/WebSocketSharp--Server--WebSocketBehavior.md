# class `WebSocketSharp::Server::WebSocketBehavior` 

```
class WebSocketSharp::Server::WebSocketBehavior
  : public IWebSocketSession
```

Exposes a set of methods and properties used to define the behavior of a WebSocket service provided by the WebSocketServer or HttpServer.

This class is an abstract class.

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`protected NameValueCollection ` [`Headers`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1a17b72b642f009151e61cda9a0e4696fd) | Gets the HTTP headers included in a WebSocket handshake request.
`protected ` [`Logger`](WebSocketSharp--Logger.md)` ` [`Log`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1af2ed886ec3d2b2fd42fd0c5dad2f8cc5) | Gets the logging function.
`protected NameValueCollection ` [`QueryString`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1ad1978eecc1cc95c4a628d1ee49c7772f) | Gets the query string included in a WebSocket handshake request.
`protected ` [`WebSocketSessionManager`](WebSocketSharp--Server--WebSocketSessionManager.md)` ` [`Sessions`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1a7f0f03b6c83528dbbf7e0ac483a59dd1) | Gets the management function for the sessions in the service.
`public ` [`WebSocketState`](WebSocketSharp.md)` ` [`ConnectionState`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1a9e5aac9610e64994dbfb49de2651c71a) | Gets the current state of the WebSocket connection for a session.
`public ` [`WebSocketContext`](WebSocketSharp--Net--WebSockets--WebSocketContext.md)` ` [`Context`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1a588dcc42dff8e6cf56b0808fe710a8e2) | Gets the information in a WebSocket handshake request to the service.
`public Func< ` [`CookieCollection](WebSocketSharp--Net--CookieCollection.md), [CookieCollection`](WebSocketSharp--Net--CookieCollection.md)`, bool > ` [`CookiesValidator`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1af274c695721e45b64f835c6e3aa59081) | Gets or sets the delegate used to validate the HTTP cookies included in a WebSocket handshake request to the service.
`public bool ` [`EmitOnPing`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1ab33fc86f77c2cf3f8b102569d28a2e16) | Gets or sets a value indicating whether the WebSocket instance for a session emits the message event when receives a ping.
`public string ` [`ID`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1acf1f7083c16b78285bb3372325cfdce4) | Gets the unique ID of a session.
`public bool ` [`IgnoreExtensions`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1a5c0fcaaf94c0198e772892949edde5ff) | Gets or sets a value indicating whether the service ignores the Sec-WebSocket-Extensions header included in a WebSocket handshake request.
`public Func< string, bool > ` [`OriginValidator`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1a776964d7ef755f39788fbb8a54d3665c) | Gets or sets the delegate used to validate the Origin header included in a WebSocket handshake request to the service.
`public string ` [`Protocol`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1a0dda9c70e5a498baaa1cd780236ce1a1) | Gets or sets the name of the WebSocket subprotocol for the service.
`public DateTime ` [`StartTime`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1ad8e7f82f173c976a2554bc06b2337f65) | Gets the time that a session has started.
`protected ` [`WebSocketBehavior`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1a283166ebafa10814c392e30735cb6ac9)`()` | Initializes a new instance of the WebSocketBehavior class.
`protected void ` [`Close`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1a7f7a3199c392465d0767c6506c1af5b4)`()` | Closes the WebSocket connection for a session.
`protected void ` [`Close`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1a755fd8c332cdaf681536ca5ed7fa7fdb)`(ushort code, string reason)` | Closes the WebSocket connection for a session with the specified code and reason.
`protected void ` [`Close`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1ad2d11ea3a240649899dacd660c64100c)`(` [`CloseStatusCode`](WebSocketSharp.md)` code, string reason)` | Closes the WebSocket connection for a session with the specified code and reason.
`protected void ` [`CloseAsync`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1a9b146b83101efc75fe45964459e054ce)`()` | Closes the WebSocket connection for a session asynchronously.
`protected void ` [`CloseAsync`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1ae4f0b83a46dec1a0b30034b0e948d593)`(ushort code, string reason)` | Closes the WebSocket connection for a session asynchronously with the specified code and reason.
`protected void ` [`CloseAsync`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1acf084a4255d196ef3ad90420ccaea2f3)`(` [`CloseStatusCode`](WebSocketSharp.md)` code, string reason)` | Closes the WebSocket connection for a session asynchronously with the specified code and reason.
`protected void ` [`Error`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1a34b18458600c03964982786f99537bab)`(string message, Exception exception)` | Calls the OnError method with the specified message.
`protected virtual void ` [`OnClose`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1a347e8f248b9f321cbe487c6367d88e0b)`(` [`CloseEventArgs`](WebSocketSharp--CloseEventArgs.md)` e)` | Called when the WebSocket connection for a session has been closed.
`protected virtual void ` [`OnError`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1ad4ff745115902e0a02b95b7bd3f80f01)`(` [`ErrorEventArgs`](WebSocketSharp--ErrorEventArgs.md)` e)` | Called when the WebSocket instance for a session gets an error.
`protected virtual void ` [`OnMessage`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1a6c5e03e397afe67cba301c63209f3a3e)`(` [`MessageEventArgs`](WebSocketSharp--MessageEventArgs.md)` e)` | Called when the WebSocket instance for a session receives a message.
`protected virtual void ` [`OnOpen`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1a9b2543e562be0b03ccd8017663408482)`()` | Called when the WebSocket connection for a session has been established.
`protected void ` [`Send`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1aa826ba54ecf62a7df2cf50a0b93fd265)`(byte[] data)` | Sends the specified data to a client using the WebSocket connection.
`protected void ` [`Send`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1a32497e3fd2eb87d1d3051448c2dd1cb9)`(FileInfo fileInfo)` | Sends the specified file to a client using the WebSocket connection.
`protected void ` [`Send`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1ac3549c8cf5f93b620c35c63c877ee896)`(string data)` | Sends the specified data to a client using the WebSocket connection.
`protected void ` [`Send`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1aa98fdf5984aeb6dd44bdc7539a6a8fa0)`(Stream stream, int length)` | Sends the data from the specified stream to a client using the WebSocket connection.
`protected void ` [`SendAsync`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1adc823b289d11ac4e6ac7744be0363a9d)`(byte[] data, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)`< bool > completed)` | Sends the specified data to a client asynchronously using the WebSocket connection.
`protected void ` [`SendAsync`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1a4fbe47aee3ab33fc8c0a55388495608f)`(FileInfo fileInfo, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)`< bool > completed)` | Sends the specified file to a client asynchronously using the WebSocket connection.
`protected void ` [`SendAsync`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1ae75cfc2f9c0c707bb4832bface2e1d48)`(string data, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)`< bool > completed)` | Sends the specified data to a client asynchronously using the WebSocket connection.
`protected void ` [`SendAsync`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1aaef4fdb5c4b2e11d3f031c49241b7b51)`(Stream stream, int length, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)`< bool > completed)` | Sends the data from the specified stream to a client asynchronously using the WebSocket connection.
`private ` [`WebSocketContext`](WebSocketSharp--Net--WebSockets--WebSocketContext.md)` ` [`_context`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1a816ceeb71f3ec93039d6323396ba0da3) | 
`private Func< ` [`CookieCollection](WebSocketSharp--Net--CookieCollection.md), [CookieCollection`](WebSocketSharp--Net--CookieCollection.md)`, bool > ` [`_cookiesValidator`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1ab0301a53dbe09700763f5f903eee192f) | 
`private bool ` [`_emitOnPing`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1a76edee6035be0274acf14d5ce879a1e1) | 
`private string ` [`_id`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1ab4e9506d9e58d1616d9ea66672f1dc4f) | 
`private bool ` [`_ignoreExtensions`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1aaa6b062ecf2c0e5631126d19e63232dc) | 
`private Func< string, bool > ` [`_originValidator`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1a9dfc1f4ad9323a54b26e6c98c1446c61) | 
`private string ` [`_protocol`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1ad984ec662a4971f019cea27a0fcb4c68) | 
`private ` [`WebSocketSessionManager`](WebSocketSharp--Server--WebSocketSessionManager.md)` ` [`_sessions`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1a2d355027aad9a7a26a1888fb960cfac4) | 
`private DateTime ` [`_startTime`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1af48c1159c5093858b8b788b91ddfd26c) | 
`private ` [`WebSocket`](WebSocketSharp--WebSocket.md)` ` [`_websocket`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1a6b4391ac74acffa01a6b60fe34ebca39) | 
`private string ` [`checkHandshakeRequest`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1a1dc3423f89003e539cde04c30f093ae6)`(` [`WebSocketContext`](WebSocketSharp--Net--WebSockets--WebSocketContext.md)` context)` | 
`private void ` [`onClose`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1a97b3b98ed2c0dd4ad2505d88a9de5166)`(object sender, ` [`CloseEventArgs`](WebSocketSharp--CloseEventArgs.md)` e)` | 
`private void ` [`onError`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1ad16600174c26dfebe07bfa371c85fdbf)`(object sender, ` [`ErrorEventArgs`](WebSocketSharp--ErrorEventArgs.md)` e)` | 
`private void ` [`onMessage`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1aaf5d1deb27a01c9204f77c5a80a2b865)`(object sender, ` [`MessageEventArgs`](WebSocketSharp--MessageEventArgs.md)` e)` | 
`private void ` [`onOpen`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1af3dff0a0e9c63c33458a6a18d303f9fd)`(object sender, EventArgs e)` | 

## Members

##### `protected NameValueCollection ` [`Headers`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1a17b72b642f009151e61cda9a0e4696fd) 

Gets the HTTP headers included in a WebSocket handshake request.

A NameValueCollection that contains the headers. 

`null` if the session has not started yet.

##### `protected ` [`Logger`](WebSocketSharp--Logger.md)` ` [`Log`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1af2ed886ec3d2b2fd42fd0c5dad2f8cc5) 

Gets the logging function.

A Logger that provides the logging function. 

`null` if the session has not started yet.

##### `protected NameValueCollection ` [`QueryString`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1ad1978eecc1cc95c4a628d1ee49c7772f) 

Gets the query string included in a WebSocket handshake request.

A NameValueCollection that contains the query parameters. 

An empty collection if not included. 

`null` if the session has not started yet.

##### `protected ` [`WebSocketSessionManager`](WebSocketSharp--Server--WebSocketSessionManager.md)` ` [`Sessions`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1a7f0f03b6c83528dbbf7e0ac483a59dd1) 

Gets the management function for the sessions in the service.

A WebSocketSessionManager that manages the sessions in the service. 

`null` if the session has not started yet.

##### `public ` [`WebSocketState`](WebSocketSharp.md)` ` [`ConnectionState`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1a9e5aac9610e64994dbfb49de2651c71a) 

Gets the current state of the WebSocket connection for a session.

One of the WebSocketState enum values. 

It indicates the current state of the connection. 

WebSocketState.Connecting if the session has not started yet.

##### `public ` [`WebSocketContext`](WebSocketSharp--Net--WebSockets--WebSocketContext.md)` ` [`Context`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1a588dcc42dff8e6cf56b0808fe710a8e2) 

Gets the information in a WebSocket handshake request to the service.

A WebSocketContext instance that provides the access to the information in the handshake request. 

`null` if the session has not started yet.

##### `public Func< ` [`CookieCollection](WebSocketSharp--Net--CookieCollection.md), [CookieCollection`](WebSocketSharp--Net--CookieCollection.md)`, bool > ` [`CookiesValidator`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1af274c695721e45b64f835c6e3aa59081) 

Gets or sets the delegate used to validate the HTTP cookies included in a WebSocket handshake request to the service.

A `Func<CookieCollection, CookieCollection, bool>` delegate or `null` if not needed. 

The delegate invokes the method called when the WebSocket instance for a session validates the handshake request. 

1st CookieCollection parameter passed to the method contains the cookies to validate if present. 

2nd CookieCollection parameter passed to the method receives the cookies to send to the client. 

The method must return `true` if the cookies are valid. 

The default value is `null`.

##### `public bool ` [`EmitOnPing`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1ab33fc86f77c2cf3f8b102569d28a2e16) 

Gets or sets a value indicating whether the WebSocket instance for a session emits the message event when receives a ping.

`true` if the WebSocket instance emits the message event when receives a ping; otherwise, `false`. 

The default value is `false`.

##### `public string ` [`ID`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1acf1f7083c16b78285bb3372325cfdce4) 

Gets the unique ID of a session.

A string that represents the unique ID of the session. 

`null` if the session has not started yet.

##### `public bool ` [`IgnoreExtensions`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1a5c0fcaaf94c0198e772892949edde5ff) 

Gets or sets a value indicating whether the service ignores the Sec-WebSocket-Extensions header included in a WebSocket handshake request.

`true` if the service ignores the extensions requested from a client; otherwise, `false`. 

The default value is `false`.

##### `public Func< string, bool > ` [`OriginValidator`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1a776964d7ef755f39788fbb8a54d3665c) 

Gets or sets the delegate used to validate the Origin header included in a WebSocket handshake request to the service.

A `Func<string, bool>` delegate or `null` if not needed. 

The delegate invokes the method called when the WebSocket instance for a session validates the handshake request. 

The string parameter passed to the method is the value of the Origin header or `null` if the header is not present. 

The method must return `true` if the header value is valid. 

The default value is `null`.

##### `public string ` [`Protocol`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1a0dda9c70e5a498baaa1cd780236ce1a1) 

Gets or sets the name of the WebSocket subprotocol for the service.

A string that represents the name of the subprotocol. 

The value specified for a set must be a token defined in  RFC 2616

. 

The default value is an empty string. 

#### Exceptions
* `InvalidOperationException` The set operation is not available if the session has already started. 

* `ArgumentException` The value specified for a set operation is not a token.

##### `public DateTime ` [`StartTime`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1ad8e7f82f173c976a2554bc06b2337f65) 

Gets the time that a session has started.

A DateTime that represents the time that the session has started. 

DateTime.MaxValue if the session has not started yet.

##### `protected ` [`WebSocketBehavior`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1a283166ebafa10814c392e30735cb6ac9)`()` 

Initializes a new instance of the WebSocketBehavior class.

##### `protected void ` [`Close`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1a7f7a3199c392465d0767c6506c1af5b4)`()` 

Closes the WebSocket connection for a session.

This method does nothing if the current state of the connection is Closing or Closed. 

#### Exceptions
* `InvalidOperationException` The session has not started yet.

##### `protected void ` [`Close`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1a755fd8c332cdaf681536ca5ed7fa7fdb)`(ushort code, string reason)` 

Closes the WebSocket connection for a session with the specified code and reason.

This method does nothing if the current state of the connection is Closing or Closed. 

#### Parameters
* `code` A ushort that represents the status code indicating the reason for the close. 

The status codes are defined in  Section 7.4

of RFC 6455. 

* `reason` A string that represents the reason for the close. 

The size must be 123 bytes or less in UTF-8. 

#### Exceptions
* `InvalidOperationException` The session has not started yet. 

* `ArgumentOutOfRangeException` *code*  is less than 1000 or greater than 4999. 

-or- 

The size of *reason*  is greater than 123 bytes. 

* `ArgumentException` *code*  is 1010 (mandatory extension). 

-or- 

*code*  is 1005 (no status) and there is reason. 

-or- 

*reason*  could not be UTF-8-encoded.

##### `protected void ` [`Close`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1ad2d11ea3a240649899dacd660c64100c)`(` [`CloseStatusCode`](WebSocketSharp.md)` code, string reason)` 

Closes the WebSocket connection for a session with the specified code and reason.

This method does nothing if the current state of the connection is Closing or Closed. 

#### Parameters
* `code` One of the CloseStatusCode enum values. 

It represents the status code indicating the reason for the close. 

* `reason` A string that represents the reason for the close. 

The size must be 123 bytes or less in UTF-8. 

#### Exceptions
* `InvalidOperationException` The session has not started yet. 

* `ArgumentOutOfRangeException` The size of *reason*  is greater than 123 bytes. 

* `ArgumentException` *code*  is CloseStatusCode.MandatoryExtension. 

-or- 

*code*  is CloseStatusCode.NoStatus and there is reason. 

-or- 

*reason*  could not be UTF-8-encoded.

##### `protected void ` [`CloseAsync`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1a9b146b83101efc75fe45964459e054ce)`()` 

Closes the WebSocket connection for a session asynchronously.

This method does not wait for the close to be complete. 

This method does nothing if the current state of the connection is Closing or Closed. 

#### Exceptions
* `InvalidOperationException` The session has not started yet.

##### `protected void ` [`CloseAsync`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1ae4f0b83a46dec1a0b30034b0e948d593)`(ushort code, string reason)` 

Closes the WebSocket connection for a session asynchronously with the specified code and reason.

This method does not wait for the close to be complete. 

This method does nothing if the current state of the connection is Closing or Closed. 

#### Parameters
* `code` A ushort that represents the status code indicating the reason for the close. 

The status codes are defined in  Section 7.4

of RFC 6455. 

* `reason` A string that represents the reason for the close. 

The size must be 123 bytes or less in UTF-8. 

#### Exceptions
* `InvalidOperationException` The session has not started yet. 

* `ArgumentOutOfRangeException` *code*  is less than 1000 or greater than 4999. 

-or- 

The size of *reason*  is greater than 123 bytes. 

* `ArgumentException` *code*  is 1010 (mandatory extension). 

-or- 

*code*  is 1005 (no status) and there is reason. 

-or- 

*reason*  could not be UTF-8-encoded.

##### `protected void ` [`CloseAsync`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1acf084a4255d196ef3ad90420ccaea2f3)`(` [`CloseStatusCode`](WebSocketSharp.md)` code, string reason)` 

Closes the WebSocket connection for a session asynchronously with the specified code and reason.

This method does not wait for the close to be complete. 

This method does nothing if the current state of the connection is Closing or Closed. 

#### Parameters
* `code` One of the CloseStatusCode enum values. 

It represents the status code indicating the reason for the close. 

* `reason` A string that represents the reason for the close. 

The size must be 123 bytes or less in UTF-8. 

#### Exceptions
* `InvalidOperationException` The session has not started yet. 

* `ArgumentException` *code*  is CloseStatusCode.MandatoryExtension. 

-or- 

*code*  is CloseStatusCode.NoStatus and there is reason. 

-or- 

*reason*  could not be UTF-8-encoded. 

* `ArgumentOutOfRangeException` The size of *reason*  is greater than 123 bytes.

##### `protected void ` [`Error`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1a34b18458600c03964982786f99537bab)`(string message, Exception exception)` 

Calls the OnError method with the specified message.

#### Parameters
* `message` A string that represents the error message. 

* `exception` An Exception instance that represents the cause of the error if present. 

#### Exceptions
* `ArgumentNullException` *message*  is `null`. 

* `ArgumentException` *message*  is an empty string.

##### `protected virtual void ` [`OnClose`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1a347e8f248b9f321cbe487c6367d88e0b)`(` [`CloseEventArgs`](WebSocketSharp--CloseEventArgs.md)` e)` 

Called when the WebSocket connection for a session has been closed.

#### Parameters
* `e` A CloseEventArgs that represents the event data passed from a WebSocket.OnClose event.

##### `protected virtual void ` [`OnError`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1ad4ff745115902e0a02b95b7bd3f80f01)`(` [`ErrorEventArgs`](WebSocketSharp--ErrorEventArgs.md)` e)` 

Called when the WebSocket instance for a session gets an error.

#### Parameters
* `e` A ErrorEventArgs that represents the event data passed from a WebSocket.OnError event.

##### `protected virtual void ` [`OnMessage`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1a6c5e03e397afe67cba301c63209f3a3e)`(` [`MessageEventArgs`](WebSocketSharp--MessageEventArgs.md)` e)` 

Called when the WebSocket instance for a session receives a message.

#### Parameters
* `e` A MessageEventArgs that represents the event data passed from a WebSocket.OnMessage event.

##### `protected virtual void ` [`OnOpen`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1a9b2543e562be0b03ccd8017663408482)`()` 

Called when the WebSocket connection for a session has been established.

##### `protected void ` [`Send`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1aa826ba54ecf62a7df2cf50a0b93fd265)`(byte[] data)` 

Sends the specified data to a client using the WebSocket connection.

#### Parameters
* `data` An array of byte that represents the binary data to send. 

#### Exceptions
* `InvalidOperationException` The current state of the connection is not Open. 

* `ArgumentNullException` *data*  is `null`.

##### `protected void ` [`Send`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1a32497e3fd2eb87d1d3051448c2dd1cb9)`(FileInfo fileInfo)` 

Sends the specified file to a client using the WebSocket connection.

#### Parameters
* `fileInfo` A FileInfo that specifies the file to send. 

The file is sent as the binary data. 

#### Exceptions
* `InvalidOperationException` The current state of the connection is not Open. 

* `ArgumentNullException` *fileInfo*  is `null`. 

* `ArgumentException` The file does not exist. 

-or- 

The file could not be opened.

##### `protected void ` [`Send`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1ac3549c8cf5f93b620c35c63c877ee896)`(string data)` 

Sends the specified data to a client using the WebSocket connection.

#### Parameters
* `data` A string that represents the text data to send. 

#### Exceptions
* `InvalidOperationException` The current state of the connection is not Open. 

* `ArgumentNullException` *data*  is `null`. 

* `ArgumentException` *data*  could not be UTF-8-encoded.

##### `protected void ` [`Send`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1aa98fdf5984aeb6dd44bdc7539a6a8fa0)`(Stream stream, int length)` 

Sends the data from the specified stream to a client using the WebSocket connection.

#### Parameters
* `stream` A Stream instance from which to read the data to send. 

The data is sent as the binary data. 

* `length` An int that specifies the number of bytes to send. 

#### Exceptions
* `InvalidOperationException` The current state of the connection is not Open. 

* `ArgumentNullException` *stream*  is `null`. 

* `ArgumentException` *stream*  cannot be read. 

-or- 

*length*  is less than 1. 

-or- 

No data could be read from *stream* .

##### `protected void ` [`SendAsync`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1adc823b289d11ac4e6ac7744be0363a9d)`(byte[] data, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)`< bool > completed)` 

Sends the specified data to a client asynchronously using the WebSocket connection.

This method does not wait for the send to be complete. 

#### Parameters
* `data` An array of byte that represents the binary data to send. 

* `completed` An `Action<bool>` delegate or `null` if not needed. 

The delegate invokes the method called when the send is complete. 

`true` is passed to the method if the send has done with no error; otherwise, `false`. 

#### Exceptions
* `InvalidOperationException` The current state of the connection is not Open. 

* `ArgumentNullException` *data*  is `null`.

##### `protected void ` [`SendAsync`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1a4fbe47aee3ab33fc8c0a55388495608f)`(FileInfo fileInfo, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)`< bool > completed)` 

Sends the specified file to a client asynchronously using the WebSocket connection.

This method does not wait for the send to be complete. 

#### Parameters
* `fileInfo` A FileInfo that specifies the file to send. 

The file is sent as the binary data. 

* `completed` An `Action<bool>` delegate or `null` if not needed. 

The delegate invokes the method called when the send is complete. 

`true` is passed to the method if the send has done with no error; otherwise, `false`. 

#### Exceptions
* `InvalidOperationException` The current state of the connection is not Open. 

* `ArgumentNullException` *fileInfo*  is `null`. 

* `ArgumentException` The file does not exist. 

-or- 

The file could not be opened.

##### `protected void ` [`SendAsync`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1ae75cfc2f9c0c707bb4832bface2e1d48)`(string data, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)`< bool > completed)` 

Sends the specified data to a client asynchronously using the WebSocket connection.

This method does not wait for the send to be complete. 

#### Parameters
* `data` A string that represents the text data to send. 

* `completed` An `Action<bool>` delegate or `null` if not needed. 

The delegate invokes the method called when the send is complete. 

`true` is passed to the method if the send has done with no error; otherwise, `false`. 

#### Exceptions
* `InvalidOperationException` The current state of the connection is not Open. 

* `ArgumentNullException` *data*  is `null`. 

* `ArgumentException` *data*  could not be UTF-8-encoded.

##### `protected void ` [`SendAsync`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1aaef4fdb5c4b2e11d3f031c49241b7b51)`(Stream stream, int length, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)`< bool > completed)` 

Sends the data from the specified stream to a client asynchronously using the WebSocket connection.

This method does not wait for the send to be complete. 

#### Parameters
* `stream` A Stream instance from which to read the data to send. 

The data is sent as the binary data. 

* `length` An int that specifies the number of bytes to send. 

* `completed` An `Action<bool>` delegate or `null` if not needed. 

The delegate invokes the method called when the send is complete. 

`true` is passed to the method if the send has done with no error; otherwise, `false`. 

#### Exceptions
* `InvalidOperationException` The current state of the connection is not Open. 

* `ArgumentNullException` *stream*  is `null`. 

* `ArgumentException` *stream*  cannot be read. 

-or- 

*length*  is less than 1. 

-or- 

No data could be read from *stream* .

##### `private ` [`WebSocketContext`](WebSocketSharp--Net--WebSockets--WebSocketContext.md)` ` [`_context`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1a816ceeb71f3ec93039d6323396ba0da3) 

##### `private Func< ` [`CookieCollection](WebSocketSharp--Net--CookieCollection.md), [CookieCollection`](WebSocketSharp--Net--CookieCollection.md)`, bool > ` [`_cookiesValidator`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1ab0301a53dbe09700763f5f903eee192f) 

##### `private bool ` [`_emitOnPing`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1a76edee6035be0274acf14d5ce879a1e1) 

##### `private string ` [`_id`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1ab4e9506d9e58d1616d9ea66672f1dc4f) 

##### `private bool ` [`_ignoreExtensions`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1aaa6b062ecf2c0e5631126d19e63232dc) 

##### `private Func< string, bool > ` [`_originValidator`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1a9dfc1f4ad9323a54b26e6c98c1446c61) 

##### `private string ` [`_protocol`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1ad984ec662a4971f019cea27a0fcb4c68) 

##### `private ` [`WebSocketSessionManager`](WebSocketSharp--Server--WebSocketSessionManager.md)` ` [`_sessions`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1a2d355027aad9a7a26a1888fb960cfac4) 

##### `private DateTime ` [`_startTime`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1af48c1159c5093858b8b788b91ddfd26c) 

##### `private ` [`WebSocket`](WebSocketSharp--WebSocket.md)` ` [`_websocket`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1a6b4391ac74acffa01a6b60fe34ebca39) 

##### `private string ` [`checkHandshakeRequest`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1a1dc3423f89003e539cde04c30f093ae6)`(` [`WebSocketContext`](WebSocketSharp--Net--WebSockets--WebSocketContext.md)` context)` 

##### `private void ` [`onClose`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1a97b3b98ed2c0dd4ad2505d88a9de5166)`(object sender, ` [`CloseEventArgs`](WebSocketSharp--CloseEventArgs.md)` e)` 

##### `private void ` [`onError`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1ad16600174c26dfebe07bfa371c85fdbf)`(object sender, ` [`ErrorEventArgs`](WebSocketSharp--ErrorEventArgs.md)` e)` 

##### `private void ` [`onMessage`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1aaf5d1deb27a01c9204f77c5a80a2b865)`(object sender, ` [`MessageEventArgs`](WebSocketSharp--MessageEventArgs.md)` e)` 

##### `private void ` [`onOpen`](#class_web_socket_sharp_1_1_server_1_1_web_socket_behavior_1af3dff0a0e9c63c33458a6a18d303f9fd)`(object sender, EventArgs e)` 

