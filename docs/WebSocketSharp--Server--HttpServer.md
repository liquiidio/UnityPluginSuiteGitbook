# class `WebSocketSharp::Server::HttpServer` 

Provides a simple HTTP server that allows to accept WebSocket handshake requests.

This class can provide multiple WebSocket services.

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public System.Net.IPAddress ` [`Address`](#class_web_socket_sharp_1_1_server_1_1_http_server_1a42dec17b5716178801c81c25599ada7f) | Gets the IP address of the server.
`public ` [`AuthenticationSchemes`](WebSocketSharp--Net.md)` ` [`AuthenticationSchemes`](#class_web_socket_sharp_1_1_server_1_1_http_server_1ab2f4176cabceeee69cb96c6d68ab5f05) | Gets or sets the scheme used to authenticate the clients.
`public string ` [`DocumentRootPath`](#class_web_socket_sharp_1_1_server_1_1_http_server_1a26caef77dbd79698a2c9d468423540ce) | Gets or sets the path to the document folder of the server.
`public bool ` [`IsListening`](#class_web_socket_sharp_1_1_server_1_1_http_server_1aa989b9618104958f4a259fa37fb939d8) | Gets a value indicating whether the server has started.
`public bool ` [`IsSecure`](#class_web_socket_sharp_1_1_server_1_1_http_server_1adb59d1044fe46ad2ddd774ccbc267db1) | Gets a value indicating whether secure connections are provided.
`public bool ` [`KeepClean`](#class_web_socket_sharp_1_1_server_1_1_http_server_1ad8b9e62479203719425166890ca196f6) | Gets or sets a value indicating whether the server cleans up the inactive sessions periodically.
`public ` [`Logger`](WebSocketSharp--Logger.md)` ` [`Log`](#class_web_socket_sharp_1_1_server_1_1_http_server_1af2ed886ec3d2b2fd42fd0c5dad2f8cc5) | Gets the logging function for the server.
`public int ` [`Port`](#class_web_socket_sharp_1_1_server_1_1_http_server_1a91b1a1342df7fe9e51fb5dfc4999dfe8) | Gets the port of the server.
`public string ` [`Realm`](#class_web_socket_sharp_1_1_server_1_1_http_server_1a52a674ec0b4dc0d9e94f9ff3c47c583a) | Gets or sets the realm used for authentication.
`public bool ` [`ReuseAddress`](#class_web_socket_sharp_1_1_server_1_1_http_server_1a923e721e9823564407e4d83b8a49fb9b) | Gets or sets a value indicating whether the server is allowed to be bound to an address that is already in use.
`public ` [`ServerSslConfiguration`](WebSocketSharp--Net--ServerSslConfiguration.md)` ` [`SslConfiguration`](#class_web_socket_sharp_1_1_server_1_1_http_server_1aa41bf1c36ef66f799331bb3ea0204ca9) | Gets the configuration for secure connection.
`public Func< IIdentity, ` [`NetworkCredential`](WebSocketSharp--Net--NetworkCredential.md)` > ` [`UserCredentialsFinder`](#class_web_socket_sharp_1_1_server_1_1_http_server_1acd9009b71f94aed4202e9e2fa19cc1d1) | Gets or sets the delegate used to find the credentials for an identity.
`public TimeSpan ` [`WaitTime`](#class_web_socket_sharp_1_1_server_1_1_http_server_1ae01f8dab993779eaa79c449c045db7a8) | Gets or sets the time to wait for the response to the WebSocket Ping or Close.
`public ` [`WebSocketServiceManager`](WebSocketSharp--Server--WebSocketServiceManager.md)` ` [`WebSocketServices`](#class_web_socket_sharp_1_1_server_1_1_http_server_1a224775f1dbbc2487c577806053764f68) | Gets the management function for the WebSocket services provided by the server.
`public ` [`HttpServer`](#class_web_socket_sharp_1_1_server_1_1_http_server_1ae3a207f1d3c0c12d1455b67ae2288200)`()` | Initializes a new instance of the HttpServer class.
`public ` [`HttpServer`](#class_web_socket_sharp_1_1_server_1_1_http_server_1a5f85abf7da4b63687de2118fede29062)`(int port)` | Initializes a new instance of the HttpServer class with the specified *port* .
`public ` [`HttpServer`](#class_web_socket_sharp_1_1_server_1_1_http_server_1a6ebf184dfa0a2895d282e74a1d93799c)`(string url)` | Initializes a new instance of the HttpServer class with the specified *url* .
`public ` [`HttpServer`](#class_web_socket_sharp_1_1_server_1_1_http_server_1ad467ceb85a60f1bf27913a228181e0e2)`(int port, bool secure)` | Initializes a new instance of the HttpServer class with the specified *port* and *secure* .
`public ` [`HttpServer`](#class_web_socket_sharp_1_1_server_1_1_http_server_1a90f7abd52258f8f853cb669ddb374a71)`(System.Net.IPAddress address, int port)` | Initializes a new instance of the HttpServer class with the specified *address* and *port* .
`public ` [`HttpServer`](#class_web_socket_sharp_1_1_server_1_1_http_server_1a0161d2b83a8d7e206711d6196ec2acda)`(System.Net.IPAddress address, int port, bool secure)` | Initializes a new instance of the HttpServer class with the specified *address* , *port* , and *secure* .
`public void ` [`AddWebSocketService< TBehavior >`](#class_web_socket_sharp_1_1_server_1_1_http_server_1a755927557f8eb70227b2b084993fbeaf)`(string path, Func< TBehavior > creator)` | Adds a WebSocket service with the specified behavior, path, and delegate.
`public void ` [`AddWebSocketService< TBehaviorWithNew >`](#class_web_socket_sharp_1_1_server_1_1_http_server_1a5202fd649497479cdf216c483b68d9f7)`(string path)` | Adds a WebSocket service with the specified behavior and path.
`public void ` [`AddWebSocketService< TBehaviorWithNew >`](#class_web_socket_sharp_1_1_server_1_1_http_server_1a55ca1daeb59b639d48156e26f8d8ec06)`(string path, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)`< TBehaviorWithNew > initializer)` | Adds a WebSocket service with the specified behavior, path, and delegate.
`public byte[] ` [`GetFile`](#class_web_socket_sharp_1_1_server_1_1_http_server_1a28cdb1e7f214464d536c2be63a2f5871)`(string path)` | Gets the contents of the specified file from the document folder of the server.
`public bool ` [`RemoveWebSocketService`](#class_web_socket_sharp_1_1_server_1_1_http_server_1abf305a7e763e8c3dddd175993274fe50)`(string path)` | Removes a WebSocket service with the specified path.
`public void ` [`Start`](#class_web_socket_sharp_1_1_server_1_1_http_server_1a07aaf1227e4d645f15e0a964f54ef291)`()` | Starts receiving incoming requests.
`public void ` [`Stop`](#class_web_socket_sharp_1_1_server_1_1_http_server_1a17a237457e57625296e6b24feb19c60a)`()` | Stops receiving incoming requests.
`public void ` [`Stop`](#class_web_socket_sharp_1_1_server_1_1_http_server_1a701cfe4f1809ef684c7331dce15e8992)`(ushort code, string reason)` | Stops receiving incoming requests and closes each connection.
`public void ` [`Stop`](#class_web_socket_sharp_1_1_server_1_1_http_server_1a069d2891d887dbaa888f84adf69e688c)`(` [`CloseStatusCode`](WebSocketSharp.md)` code, string reason)` | Stops receiving incoming requests and closes each connection.
`private System.Net.IPAddress ` [`_address`](#class_web_socket_sharp_1_1_server_1_1_http_server_1ac2ee44bdb7b3f660c3a9cf04144c373a) | 
`private string ` [`_docRootPath`](#class_web_socket_sharp_1_1_server_1_1_http_server_1a5d44ed0d3ffdceebe6c80c84608deb02) | 
`private string ` [`_hostname`](#class_web_socket_sharp_1_1_server_1_1_http_server_1a4f28e1a261d44af6c3bbc9e5b8fa0683) | 
`private ` [`HttpListener`](WebSocketSharp--Net--HttpListener.md)` ` [`_listener`](#class_web_socket_sharp_1_1_server_1_1_http_server_1ab5753944447cd49f99da3ec676f16769) | 
`private ` [`Logger`](WebSocketSharp--Logger.md)` ` [`_log`](#class_web_socket_sharp_1_1_server_1_1_http_server_1ab09157ab30052b0f1bf60fe26410d6ee) | 
`private int ` [`_port`](#class_web_socket_sharp_1_1_server_1_1_http_server_1a5cc37d2eb4f4e3fce88c482586cbe058) | 
`private Thread ` [`_receiveThread`](#class_web_socket_sharp_1_1_server_1_1_http_server_1a567bde8b1d4adcc2a3b4ed158dbe755a) | 
`private bool ` [`_secure`](#class_web_socket_sharp_1_1_server_1_1_http_server_1a2f7b5b309c5830b8532939ca02946b44) | 
`private ` [`WebSocketServiceManager`](WebSocketSharp--Server--WebSocketServiceManager.md)` ` [`_services`](#class_web_socket_sharp_1_1_server_1_1_http_server_1a47569c778ac707da606ea0028b42f0b0) | 
`private volatile ` [`ServerState`](WebSocketSharp--Server.md)` ` [`_state`](#class_web_socket_sharp_1_1_server_1_1_http_server_1a0ef0deff6fe7732149d2bcd773a64f28) | 
`private object ` [`_sync`](#class_web_socket_sharp_1_1_server_1_1_http_server_1adbb069fcd0e2b452bc3342bc00739ed8) | 
`private void ` [`abort`](#class_web_socket_sharp_1_1_server_1_1_http_server_1ac54f53dc342019e8db34f4aa581a5792)`()` | 
`private bool ` [`canSet`](#class_web_socket_sharp_1_1_server_1_1_http_server_1a729ea85bb2548e8a7b5f70f75159b133)`(out string message)` | 
`private bool ` [`checkCertificate`](#class_web_socket_sharp_1_1_server_1_1_http_server_1acea234fdd273a9f437b7b64e075550fb)`(out string message)` | 
`private string ` [`createFilePath`](#class_web_socket_sharp_1_1_server_1_1_http_server_1a3f45464cd0ec94df224210340bb572ea)`(string childPath)` | 
`private void ` [`init`](#class_web_socket_sharp_1_1_server_1_1_http_server_1a8142a8ba68ea30ebe7a768e3b65e7028)`(string hostname, System.Net.IPAddress address, int port, bool secure)` | 
`private void ` [`processRequest`](#class_web_socket_sharp_1_1_server_1_1_http_server_1ae84ee8a2d68ba3199903d57cb231a56b)`(` [`HttpListenerContext`](WebSocketSharp--Net--HttpListenerContext.md)` context)` | 
`private void ` [`processRequest`](#class_web_socket_sharp_1_1_server_1_1_http_server_1a41815f8d0f22d261bf4ed6262748d0cb)`(` [`HttpListenerWebSocketContext`](WebSocketSharp--Net--WebSockets--HttpListenerWebSocketContext.md)` context)` | 
`private void ` [`receiveRequest`](#class_web_socket_sharp_1_1_server_1_1_http_server_1aa74d80d71aa82435e1b49fa53bf4f613)`()` | 
`private void ` [`start`](#class_web_socket_sharp_1_1_server_1_1_http_server_1a60de64d75454385b23995437f1d72669)`()` | 
`private void ` [`startReceiving`](#class_web_socket_sharp_1_1_server_1_1_http_server_1a95e75d300547b71b3cc33d6e02f7a475)`()` | 
`private void ` [`stop`](#class_web_socket_sharp_1_1_server_1_1_http_server_1aecaba860bee0c6450a64303d3434fb5d)`(ushort code, string reason)` | 
`private void ` [`stopReceiving`](#class_web_socket_sharp_1_1_server_1_1_http_server_1a20283caf3d49d6d97189cde68aa6e727)`(int millisecondsTimeout)` | 
`private static ` [`HttpListener`](WebSocketSharp--Net--HttpListener.md)` ` [`createListener`](#class_web_socket_sharp_1_1_server_1_1_http_server_1ac479a2fccf6ded03858621c76e41807c)`(string hostname, int port, bool secure)` | 
`private static bool ` [`tryCreateUri`](#class_web_socket_sharp_1_1_server_1_1_http_server_1a101fd0c491f416bc1397f62f230b72ea)`(string uriString, out Uri result, out string message)` | 

## Members

##### `public System.Net.IPAddress ` [`Address`](#class_web_socket_sharp_1_1_server_1_1_http_server_1a42dec17b5716178801c81c25599ada7f) 

Gets the IP address of the server.

A System.Net.IPAddress that represents the local IP address on which to listen for incoming requests.

##### `public ` [`AuthenticationSchemes`](WebSocketSharp--Net.md)` ` [`AuthenticationSchemes`](#class_web_socket_sharp_1_1_server_1_1_http_server_1ab2f4176cabceeee69cb96c6d68ab5f05) 

Gets or sets the scheme used to authenticate the clients.

The set operation does nothing if the server has already started or it is shutting down. 

One of the [WebSocketSharp.Net.AuthenticationSchemes](WebSocketSharp--Net.md) enum values. 

It represents the scheme used to authenticate the clients. 

The default value is WebSocketSharp.Net.AuthenticationSchemes.Anonymous.

##### `public string ` [`DocumentRootPath`](#class_web_socket_sharp_1_1_server_1_1_http_server_1a26caef77dbd79698a2c9d468423540ce) 

Gets or sets the path to the document folder of the server.

'/' or '\' is trimmed from the end of the value if any. 

The set operation does nothing if the server has already started or it is shutting down. 

A string that represents a path to the folder from which to find the requested file. 

The default value is "./Public". 

#### Exceptions
* `ArgumentNullException` The value specified for a set operation is `null`. 

* `ArgumentException` The value specified for a set operation is an empty string. 

-or- 

The value specified for a set operation is an invalid path string. 

-or- 

The value specified for a set operation is an absolute root.

##### `public bool ` [`IsListening`](#class_web_socket_sharp_1_1_server_1_1_http_server_1aa989b9618104958f4a259fa37fb939d8) 

Gets a value indicating whether the server has started.

`true` if the server has started; otherwise, `false`.

##### `public bool ` [`IsSecure`](#class_web_socket_sharp_1_1_server_1_1_http_server_1adb59d1044fe46ad2ddd774ccbc267db1) 

Gets a value indicating whether secure connections are provided.

`true` if this instance provides secure connections; otherwise, `false`.

##### `public bool ` [`KeepClean`](#class_web_socket_sharp_1_1_server_1_1_http_server_1ad8b9e62479203719425166890ca196f6) 

Gets or sets a value indicating whether the server cleans up the inactive sessions periodically.

The set operation does nothing if the server has already started or it is shutting down. 

`true` if the server cleans up the inactive sessions every 60 seconds; otherwise, `false`. 

The default value is `true`.

##### `public ` [`Logger`](WebSocketSharp--Logger.md)` ` [`Log`](#class_web_socket_sharp_1_1_server_1_1_http_server_1af2ed886ec3d2b2fd42fd0c5dad2f8cc5) 

Gets the logging function for the server.

The default logging level is LogLevel.Error. 

A Logger that provides the logging function.

##### `public int ` [`Port`](#class_web_socket_sharp_1_1_server_1_1_http_server_1a91b1a1342df7fe9e51fb5dfc4999dfe8) 

Gets the port of the server.

An int that represents the number of the port on which to listen for incoming requests.

##### `public string ` [`Realm`](#class_web_socket_sharp_1_1_server_1_1_http_server_1a52a674ec0b4dc0d9e94f9ff3c47c583a) 

Gets or sets the realm used for authentication.

"SECRET AREA" is used as the realm if the value is `null` or an empty string. 

The set operation does nothing if the server has already started or it is shutting down. 

A string or `null` by default. 

That string represents the name of the realm.

##### `public bool ` [`ReuseAddress`](#class_web_socket_sharp_1_1_server_1_1_http_server_1a923e721e9823564407e4d83b8a49fb9b) 

Gets or sets a value indicating whether the server is allowed to be bound to an address that is already in use.

You should set this property to `true` if you would like to resolve to wait for socket in TIME_WAIT state. 

The set operation does nothing if the server has already started or it is shutting down. 

`true` if the server is allowed to be bound to an address that is already in use; otherwise, `false`. 

The default value is `false`.

##### `public ` [`ServerSslConfiguration`](WebSocketSharp--Net--ServerSslConfiguration.md)` ` [`SslConfiguration`](#class_web_socket_sharp_1_1_server_1_1_http_server_1aa41bf1c36ef66f799331bb3ea0204ca9) 

Gets the configuration for secure connection.

This configuration will be referenced when attempts to start, so it must be configured before the start method is called. 

A ServerSslConfiguration that represents the configuration used to provide secure connections. 

#### Exceptions
* `InvalidOperationException` This instance does not provide secure connections.

##### `public Func< IIdentity, ` [`NetworkCredential`](WebSocketSharp--Net--NetworkCredential.md)` > ` [`UserCredentialsFinder`](#class_web_socket_sharp_1_1_server_1_1_http_server_1acd9009b71f94aed4202e9e2fa19cc1d1) 

Gets or sets the delegate used to find the credentials for an identity.

No credentials are found if the method invoked by the delegate returns `null` or the value is `null`. 

The set operation does nothing if the server has already started or it is shutting down. 

A `Func<IIdentity, NetworkCredential>` delegate or `null` if not needed. 

That delegate invokes the method called for finding the credentials used to authenticate a client. 

The default value is `null`.

##### `public TimeSpan ` [`WaitTime`](#class_web_socket_sharp_1_1_server_1_1_http_server_1ae01f8dab993779eaa79c449c045db7a8) 

Gets or sets the time to wait for the response to the WebSocket Ping or Close.

The set operation does nothing if the server has already started or it is shutting down. 

A TimeSpan to wait for the response. 

The default value is the same as 1 second. 

#### Exceptions
* `ArgumentOutOfRangeException` The value specified for a set operation is zero or less.

##### `public ` [`WebSocketServiceManager`](WebSocketSharp--Server--WebSocketServiceManager.md)` ` [`WebSocketServices`](#class_web_socket_sharp_1_1_server_1_1_http_server_1a224775f1dbbc2487c577806053764f68) 

Gets the management function for the WebSocket services provided by the server.

A WebSocketServiceManager that manages the WebSocket services provided by the server.

##### `public ` [`HttpServer`](#class_web_socket_sharp_1_1_server_1_1_http_server_1ae3a207f1d3c0c12d1455b67ae2288200)`()` 

Initializes a new instance of the HttpServer class.

The new instance listens for incoming requests on System.Net.IPAddress.Any and port 80.

##### `public ` [`HttpServer`](#class_web_socket_sharp_1_1_server_1_1_http_server_1a5f85abf7da4b63687de2118fede29062)`(int port)` 

Initializes a new instance of the HttpServer class with the specified *port* .

The new instance listens for incoming requests on System.Net.IPAddress.Any and *port* . 

It provides secure connections if *port*  is 443. 

#### Parameters
* `port` An int that represents the number of the port on which to listen. 

#### Exceptions
* `ArgumentOutOfRangeException` *port*  is less than 1 or greater than 65535.

##### `public ` [`HttpServer`](#class_web_socket_sharp_1_1_server_1_1_http_server_1a6ebf184dfa0a2895d282e74a1d93799c)`(string url)` 

Initializes a new instance of the HttpServer class with the specified *url* .

The new instance listens for incoming requests on the IP address of the host of *url*  and the port of *url* . 

Either port 80 or 443 is used if *url*  includes no port. Port 443 is used if the scheme of *url*  is https; otherwise, port 80 is used. 

The new instance provides secure connections if the scheme of *url*  is https. 

#### Parameters
* `url` A string that represents the HTTP URL of the server. 

#### Exceptions
* `ArgumentNullException` *url*  is `null`. 

* `ArgumentException` *url*  is empty. 

-or- 

*url*  is invalid.

##### `public ` [`HttpServer`](#class_web_socket_sharp_1_1_server_1_1_http_server_1ad467ceb85a60f1bf27913a228181e0e2)`(int port, bool secure)` 

Initializes a new instance of the HttpServer class with the specified *port*  and *secure* .

The new instance listens for incoming requests on System.Net.IPAddress.Any and *port* . 

#### Parameters
* `port` An int that represents the number of the port on which to listen. 

* `secure` A bool: `true` if the new instance provides secure connections; otherwise, `false`. 

#### Exceptions
* `ArgumentOutOfRangeException` *port*  is less than 1 or greater than 65535.

##### `public ` [`HttpServer`](#class_web_socket_sharp_1_1_server_1_1_http_server_1a90f7abd52258f8f853cb669ddb374a71)`(System.Net.IPAddress address, int port)` 

Initializes a new instance of the HttpServer class with the specified *address*  and *port* .

The new instance listens for incoming requests on *address*  and *port* . 

It provides secure connections if *port*  is 443. 

#### Parameters
* `address` A System.Net.IPAddress that represents the local IP address on which to listen. 

* `port` An int that represents the number of the port on which to listen. 

#### Exceptions
* `ArgumentNullException` *address*  is `null`. 

* `ArgumentException` *address*  is not a local IP address. 

* `ArgumentOutOfRangeException` *port*  is less than 1 or greater than 65535.

##### `public ` [`HttpServer`](#class_web_socket_sharp_1_1_server_1_1_http_server_1a0161d2b83a8d7e206711d6196ec2acda)`(System.Net.IPAddress address, int port, bool secure)` 

Initializes a new instance of the HttpServer class with the specified *address* , *port* , and *secure* .

The new instance listens for incoming requests on *address*  and *port* . 

#### Parameters
* `address` A System.Net.IPAddress that represents the local IP address on which to listen. 

* `port` An int that represents the number of the port on which to listen. 

* `secure` A bool: `true` if the new instance provides secure connections; otherwise, `false`. 

#### Exceptions
* `ArgumentNullException` *address*  is `null`. 

* `ArgumentException` *address*  is not a local IP address. 

* `ArgumentOutOfRangeException` *port*  is less than 1 or greater than 65535.

##### `public void ` [`AddWebSocketService< TBehavior >`](#class_web_socket_sharp_1_1_server_1_1_http_server_1a755927557f8eb70227b2b084993fbeaf)`(string path, Func< TBehavior > creator)` 

Adds a WebSocket service with the specified behavior, path, and delegate.

#### Parameters
* `path` A string that represents an absolute path to the service to add. 

/ is trimmed from the end of the string if present. 

* `creator` A `Func<TBehavior>` delegate. 

It invokes the method called when creating a new session instance for the service. 

The method must create a new instance of the specified behavior class and return it. 

#### Parameters
* `TBehavior` The type of the behavior for the service. 

It must inherit the WebSocketBehavior class. 

#### Exceptions
* `ArgumentNullException` *path*  is `null`. 

-or- 

*creator*  is `null`. 

* `ArgumentException` *path*  is an empty string. 

-or- 

*path*  is not an absolute path. 

-or- 

*path*  includes either or both query and fragment components. 

-or- 

*path*  is already in use.

##### `public void ` [`AddWebSocketService< TBehaviorWithNew >`](#class_web_socket_sharp_1_1_server_1_1_http_server_1a5202fd649497479cdf216c483b68d9f7)`(string path)` 

Adds a WebSocket service with the specified behavior and path.

#### Parameters
* `path` A string that represents an absolute path to the service to add. 

/ is trimmed from the end of the string if present. 

#### Parameters
* `TBehaviorWithNew` The type of the behavior for the service. 

It must inherit the WebSocketBehavior class. 

And also, it must have a public parameterless constructor. 

#### Exceptions
* `ArgumentNullException` *path*  is `null`. 

* `ArgumentException` *path*  is an empty string. 

-or- 

*path*  is not an absolute path. 

-or- 

*path*  includes either or both query and fragment components. 

-or- 

*path*  is already in use.

##### `public void ` [`AddWebSocketService< TBehaviorWithNew >`](#class_web_socket_sharp_1_1_server_1_1_http_server_1a55ca1daeb59b639d48156e26f8d8ec06)`(string path, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)`< TBehaviorWithNew > initializer)` 

Adds a WebSocket service with the specified behavior, path, and delegate.

#### Parameters
* `path` A string that represents an absolute path to the service to add. 

/ is trimmed from the end of the string if present. 

* `initializer` An `Action<TBehaviorWithNew>` delegate or `null` if not needed. 

The delegate invokes the method called when initializing a new session instance for the service. 

#### Parameters
* `TBehaviorWithNew` The type of the behavior for the service. 

It must inherit the WebSocketBehavior class. 

And also, it must have a public parameterless constructor. 

#### Exceptions
* `ArgumentNullException` *path*  is `null`. 

* `ArgumentException` *path*  is an empty string. 

-or- 

*path*  is not an absolute path. 

-or- 

*path*  includes either or both query and fragment components. 

-or- 

*path*  is already in use.

##### `public byte[] ` [`GetFile`](#class_web_socket_sharp_1_1_server_1_1_http_server_1a28cdb1e7f214464d536c2be63a2f5871)`(string path)` 

Gets the contents of the specified file from the document folder of the server.

#### Returns
An array of byte or `null` if it fails. 

That array represents the contents of the file. 

#### Parameters
* `path` A string that represents a virtual path to find the file from the document folder. 

#### Exceptions
* `ArgumentNullException` *path*  is `null`. 

* `ArgumentException` *path*  is an empty string. 

-or- 

*path*  contains "..".

##### `public bool ` [`RemoveWebSocketService`](#class_web_socket_sharp_1_1_server_1_1_http_server_1abf305a7e763e8c3dddd175993274fe50)`(string path)` 

Removes a WebSocket service with the specified path.

The service is stopped with close status 1001 (going away) if it has already started. 

#### Returns
`true` if the service is successfully found and removed; otherwise, `false`. 

#### Parameters
* `path` A string that represents an absolute path to the service to remove. 

/ is trimmed from the end of the string if present. 

#### Exceptions
* `ArgumentNullException` *path*  is `null`. 

* `ArgumentException` *path*  is an empty string. 

-or- 

*path*  is not an absolute path. 

-or- 

*path*  includes either or both query and fragment components.

##### `public void ` [`Start`](#class_web_socket_sharp_1_1_server_1_1_http_server_1a07aaf1227e4d645f15e0a964f54ef291)`()` 

Starts receiving incoming requests.

This method does nothing if the server has already started or it is shutting down. 

#### Exceptions
* `InvalidOperationException` There is no server certificate for secure connection. 

-or- 

The underlying HttpListener has failed to start.

##### `public void ` [`Stop`](#class_web_socket_sharp_1_1_server_1_1_http_server_1a17a237457e57625296e6b24feb19c60a)`()` 

Stops receiving incoming requests.

##### `public void ` [`Stop`](#class_web_socket_sharp_1_1_server_1_1_http_server_1a701cfe4f1809ef684c7331dce15e8992)`(ushort code, string reason)` 

Stops receiving incoming requests and closes each connection.

#### Parameters
* `code` A ushort that represents the status code indicating the reason for the WebSocket connection close. 

The status codes are defined in  Section 7.4

of RFC 6455. 

* `reason` A string that represents the reason for the WebSocket connection close. 

The size must be 123 bytes or less in UTF-8. 

#### Exceptions
* `ArgumentOutOfRangeException` *code*  is less than 1000 or greater than 4999. 

-or- 

The size of *reason*  is greater than 123 bytes. 

* `ArgumentException` *code*  is 1010 (mandatory extension). 

-or- 

*code*  is 1005 (no status) and there is reason. 

-or- 

*reason*  could not be UTF-8-encoded.

##### `public void ` [`Stop`](#class_web_socket_sharp_1_1_server_1_1_http_server_1a069d2891d887dbaa888f84adf69e688c)`(` [`CloseStatusCode`](WebSocketSharp.md)` code, string reason)` 

Stops receiving incoming requests and closes each connection.

#### Parameters
* `code` One of the CloseStatusCode enum values. 

It represents the status code indicating the reason for the WebSocket connection close. 

* `reason` A string that represents the reason for the WebSocket connection close. 

The size must be 123 bytes or less in UTF-8. 

#### Exceptions
* `ArgumentOutOfRangeException` The size of *reason*  is greater than 123 bytes. 

* `ArgumentException` *code*  is CloseStatusCode.MandatoryExtension. 

-or- 

*code*  is CloseStatusCode.NoStatus and there is reason. 

-or- 

*reason*  could not be UTF-8-encoded.

##### `private System.Net.IPAddress ` [`_address`](#class_web_socket_sharp_1_1_server_1_1_http_server_1ac2ee44bdb7b3f660c3a9cf04144c373a) 

##### `private string ` [`_docRootPath`](#class_web_socket_sharp_1_1_server_1_1_http_server_1a5d44ed0d3ffdceebe6c80c84608deb02) 

##### `private string ` [`_hostname`](#class_web_socket_sharp_1_1_server_1_1_http_server_1a4f28e1a261d44af6c3bbc9e5b8fa0683) 

##### `private ` [`HttpListener`](WebSocketSharp--Net--HttpListener.md)` ` [`_listener`](#class_web_socket_sharp_1_1_server_1_1_http_server_1ab5753944447cd49f99da3ec676f16769) 

##### `private ` [`Logger`](WebSocketSharp--Logger.md)` ` [`_log`](#class_web_socket_sharp_1_1_server_1_1_http_server_1ab09157ab30052b0f1bf60fe26410d6ee) 

##### `private int ` [`_port`](#class_web_socket_sharp_1_1_server_1_1_http_server_1a5cc37d2eb4f4e3fce88c482586cbe058) 

##### `private Thread ` [`_receiveThread`](#class_web_socket_sharp_1_1_server_1_1_http_server_1a567bde8b1d4adcc2a3b4ed158dbe755a) 

##### `private bool ` [`_secure`](#class_web_socket_sharp_1_1_server_1_1_http_server_1a2f7b5b309c5830b8532939ca02946b44) 

##### `private ` [`WebSocketServiceManager`](WebSocketSharp--Server--WebSocketServiceManager.md)` ` [`_services`](#class_web_socket_sharp_1_1_server_1_1_http_server_1a47569c778ac707da606ea0028b42f0b0) 

##### `private volatile ` [`ServerState`](WebSocketSharp--Server.md)` ` [`_state`](#class_web_socket_sharp_1_1_server_1_1_http_server_1a0ef0deff6fe7732149d2bcd773a64f28) 

##### `private object ` [`_sync`](#class_web_socket_sharp_1_1_server_1_1_http_server_1adbb069fcd0e2b452bc3342bc00739ed8) 

##### `private void ` [`abort`](#class_web_socket_sharp_1_1_server_1_1_http_server_1ac54f53dc342019e8db34f4aa581a5792)`()` 

##### `private bool ` [`canSet`](#class_web_socket_sharp_1_1_server_1_1_http_server_1a729ea85bb2548e8a7b5f70f75159b133)`(out string message)` 

##### `private bool ` [`checkCertificate`](#class_web_socket_sharp_1_1_server_1_1_http_server_1acea234fdd273a9f437b7b64e075550fb)`(out string message)` 

##### `private string ` [`createFilePath`](#class_web_socket_sharp_1_1_server_1_1_http_server_1a3f45464cd0ec94df224210340bb572ea)`(string childPath)` 

##### `private void ` [`init`](#class_web_socket_sharp_1_1_server_1_1_http_server_1a8142a8ba68ea30ebe7a768e3b65e7028)`(string hostname, System.Net.IPAddress address, int port, bool secure)` 

##### `private void ` [`processRequest`](#class_web_socket_sharp_1_1_server_1_1_http_server_1ae84ee8a2d68ba3199903d57cb231a56b)`(` [`HttpListenerContext`](WebSocketSharp--Net--HttpListenerContext.md)` context)` 

##### `private void ` [`processRequest`](#class_web_socket_sharp_1_1_server_1_1_http_server_1a41815f8d0f22d261bf4ed6262748d0cb)`(` [`HttpListenerWebSocketContext`](WebSocketSharp--Net--WebSockets--HttpListenerWebSocketContext.md)` context)` 

##### `private void ` [`receiveRequest`](#class_web_socket_sharp_1_1_server_1_1_http_server_1aa74d80d71aa82435e1b49fa53bf4f613)`()` 

##### `private void ` [`start`](#class_web_socket_sharp_1_1_server_1_1_http_server_1a60de64d75454385b23995437f1d72669)`()` 

##### `private void ` [`startReceiving`](#class_web_socket_sharp_1_1_server_1_1_http_server_1a95e75d300547b71b3cc33d6e02f7a475)`()` 

##### `private void ` [`stop`](#class_web_socket_sharp_1_1_server_1_1_http_server_1aecaba860bee0c6450a64303d3434fb5d)`(ushort code, string reason)` 

##### `private void ` [`stopReceiving`](#class_web_socket_sharp_1_1_server_1_1_http_server_1a20283caf3d49d6d97189cde68aa6e727)`(int millisecondsTimeout)` 

##### `private static ` [`HttpListener`](WebSocketSharp--Net--HttpListener.md)` ` [`createListener`](#class_web_socket_sharp_1_1_server_1_1_http_server_1ac479a2fccf6ded03858621c76e41807c)`(string hostname, int port, bool secure)` 

##### `private static bool ` [`tryCreateUri`](#class_web_socket_sharp_1_1_server_1_1_http_server_1a101fd0c491f416bc1397f62f230b72ea)`(string uriString, out Uri result, out string message)` 

