# class `WebSocketSharp::Server::WebSocketServiceHost` 

```
class WebSocketSharp::Server::WebSocketServiceHost
  : public WebSocketServiceHost
```

Exposes the methods and properties used to access the information in a WebSocket service provided by the WebSocketServer or HttpServer.

This class is an abstract class.

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`package ` [`ServerState`](WebSocketSharp--Server.md)` ` [`State`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_host_1a7867316717df3e603c59059f08137855) | 
`protected ` [`Logger`](WebSocketSharp--Logger.md)` ` [`Log`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_host_1af2ed886ec3d2b2fd42fd0c5dad2f8cc5) | Gets the logging function for the service.
`public bool ` [`KeepClean`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_host_1ad8b9e62479203719425166890ca196f6) | Gets or sets a value indicating whether the service cleans up the inactive sessions periodically.
`public string ` [`Path`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_host_1af331ba015acf9191899985a835008b9d) | Gets the path to the service.
`public ` [`WebSocketSessionManager`](WebSocketSharp--Server--WebSocketSessionManager.md)` ` [`Sessions`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_host_1a7f0f03b6c83528dbbf7e0ac483a59dd1) | Gets the management function for the sessions in the service.
`public abstract Type ` [`BehaviorType`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_host_1a816ae3eac2e91a775131f5ecfd262c25) | Gets the Type of the behavior of the service.
`public TimeSpan ` [`WaitTime`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_host_1ae01f8dab993779eaa79c449c045db7a8) | Gets or sets the time to wait for the response to the WebSocket Ping or Close.
`public override Type ` [`BehaviorType`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_host_1a2547d980354fb05459be3903b4b385c9) | 
`protected ` [`WebSocketServiceHost`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_host_1aa96617e485a3bed5e20ee428978a2f24)`(string path, ` [`Logger`](WebSocketSharp--Logger.md)` log)` | Initializes a new instance of the WebSocketServiceHost class with the specified *path* and *log* .
`protected abstract ` [`WebSocketBehavior`](WebSocketSharp--Server--WebSocketBehavior.md)` ` [`CreateSession`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_host_1a58f69ba44298867ed0acb7ed9e088c0a)`()` | Creates a new session for the service.
`protected override ` [`WebSocketBehavior`](WebSocketSharp--Server--WebSocketBehavior.md)` ` [`CreateSession`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_host_1abd19c990b6addae587ca76da68d48f29)`()` | 
`private ` [`Logger`](WebSocketSharp--Logger.md)` ` [`_log`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_host_1ab09157ab30052b0f1bf60fe26410d6ee) | 
`private string ` [`_path`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_host_1a301dbb9913055444022b6d007e61871d) | 
`private ` [`WebSocketSessionManager`](WebSocketSharp--Server--WebSocketSessionManager.md)` ` [`_sessions`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_host_1a2d355027aad9a7a26a1888fb960cfac4) | 
`private Func< TBehavior > ` [`_creator`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_host_1ae8b98eb5e1d1fe37b3d396a3b3cf0cb2) | 
`private Func< TBehavior > ` [`createCreator`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_host_1a85b1fcb53667ebdaa753eb91b1b1fcad)`(Func< TBehavior > creator, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)`< TBehavior > initializer)` | 

## Members

##### `package ` [`ServerState`](WebSocketSharp--Server.md)` ` [`State`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_host_1a7867316717df3e603c59059f08137855) 

##### `protected ` [`Logger`](WebSocketSharp--Logger.md)` ` [`Log`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_host_1af2ed886ec3d2b2fd42fd0c5dad2f8cc5) 

Gets the logging function for the service.

A Logger that provides the logging function.

##### `public bool ` [`KeepClean`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_host_1ad8b9e62479203719425166890ca196f6) 

Gets or sets a value indicating whether the service cleans up the inactive sessions periodically.

The set operation does nothing if the service has already started or it is shutting down. 

`true` if the service cleans up the inactive sessions every 60 seconds; otherwise, `false`.

##### `public string ` [`Path`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_host_1af331ba015acf9191899985a835008b9d) 

Gets the path to the service.

A string that represents the absolute path to the service.

##### `public ` [`WebSocketSessionManager`](WebSocketSharp--Server--WebSocketSessionManager.md)` ` [`Sessions`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_host_1a7f0f03b6c83528dbbf7e0ac483a59dd1) 

Gets the management function for the sessions in the service.

A WebSocketSessionManager that manages the sessions in the service.

##### `public abstract Type ` [`BehaviorType`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_host_1a816ae3eac2e91a775131f5ecfd262c25) 

Gets the Type of the behavior of the service.

A Type that represents the type of the behavior of the service.

##### `public TimeSpan ` [`WaitTime`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_host_1ae01f8dab993779eaa79c449c045db7a8) 

Gets or sets the time to wait for the response to the WebSocket Ping or Close.

The set operation does nothing if the service has already started or it is shutting down. 

A TimeSpan to wait for the response. 

#### Exceptions
* `ArgumentOutOfRangeException` The value specified for a set operation is zero or less.

##### `public override Type ` [`BehaviorType`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_host_1a2547d980354fb05459be3903b4b385c9) 

##### `protected ` [`WebSocketServiceHost`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_host_1aa96617e485a3bed5e20ee428978a2f24)`(string path, ` [`Logger`](WebSocketSharp--Logger.md)` log)` 

Initializes a new instance of the WebSocketServiceHost class with the specified *path*  and *log* .

#### Parameters
* `path` A string that represents the absolute path to the service. 

* `log` A Logger that represents the logging function for the service.

##### `protected abstract ` [`WebSocketBehavior`](WebSocketSharp--Server--WebSocketBehavior.md)` ` [`CreateSession`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_host_1a58f69ba44298867ed0acb7ed9e088c0a)`()` 

Creates a new session for the service.

#### Returns
A WebSocketBehavior instance that represents the new session.

##### `protected override ` [`WebSocketBehavior`](WebSocketSharp--Server--WebSocketBehavior.md)` ` [`CreateSession`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_host_1abd19c990b6addae587ca76da68d48f29)`()` 

##### `private ` [`Logger`](WebSocketSharp--Logger.md)` ` [`_log`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_host_1ab09157ab30052b0f1bf60fe26410d6ee) 

##### `private string ` [`_path`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_host_1a301dbb9913055444022b6d007e61871d) 

##### `private ` [`WebSocketSessionManager`](WebSocketSharp--Server--WebSocketSessionManager.md)` ` [`_sessions`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_host_1a2d355027aad9a7a26a1888fb960cfac4) 

##### `private Func< TBehavior > ` [`_creator`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_host_1ae8b98eb5e1d1fe37b3d396a3b3cf0cb2) 

##### `private Func< TBehavior > ` [`createCreator`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_host_1a85b1fcb53667ebdaa753eb91b1b1fcad)`(Func< TBehavior > creator, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)`< TBehavior > initializer)` 

