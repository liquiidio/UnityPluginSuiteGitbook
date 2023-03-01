# class `WebSocketSharp::Server::WebSocketServer` 

Provides a WebSocket protocol server.

This class can provide multiple WebSocket services.

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public System.Net.IPAddress ` [`Address`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1a42dec17b5716178801c81c25599ada7f) | Gets the IP address of the server.
`public bool ` [`AllowForwardedRequest`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1a0a862cec597988e7b8334dc282eebe92) | Gets or sets a value indicating whether the server accepts every handshake request without checking the request URI.
`public ` [`AuthenticationSchemes`](WebSocketSharp--Net.md)` ` [`AuthenticationSchemes`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1ab2f4176cabceeee69cb96c6d68ab5f05) | Gets or sets the scheme used to authenticate the clients.
`public bool ` [`IsListening`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1aa989b9618104958f4a259fa37fb939d8) | Gets a value indicating whether the server has started.
`public bool ` [`IsSecure`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1adb59d1044fe46ad2ddd774ccbc267db1) | Gets a value indicating whether secure connections are provided.
`public bool ` [`KeepClean`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1ad8b9e62479203719425166890ca196f6) | Gets or sets a value indicating whether the server cleans up the inactive sessions periodically.
`public ` [`Logger`](WebSocketSharp--Logger.md)` ` [`Log`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1af2ed886ec3d2b2fd42fd0c5dad2f8cc5) | Gets the logging function for the server.
`public int ` [`Port`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1a91b1a1342df7fe9e51fb5dfc4999dfe8) | Gets the port of the server.
`public string ` [`Realm`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1a52a674ec0b4dc0d9e94f9ff3c47c583a) | Gets or sets the realm used for authentication.
`public bool ` [`ReuseAddress`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1a923e721e9823564407e4d83b8a49fb9b) | Gets or sets a value indicating whether the server is allowed to be bound to an address that is already in use.
`public ` [`ServerSslConfiguration`](WebSocketSharp--Net--ServerSslConfiguration.md)` ` [`SslConfiguration`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1aa41bf1c36ef66f799331bb3ea0204ca9) | Gets the configuration for secure connection.
`public Func< IIdentity, ` [`NetworkCredential`](WebSocketSharp--Net--NetworkCredential.md)` > ` [`UserCredentialsFinder`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1acd9009b71f94aed4202e9e2fa19cc1d1) | Gets or sets the delegate used to find the credentials for an identity.
`public TimeSpan ` [`WaitTime`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1ae01f8dab993779eaa79c449c045db7a8) | Gets or sets the time to wait for the response to the WebSocket Ping or Close.
`public ` [`WebSocketServiceManager`](WebSocketSharp--Server--WebSocketServiceManager.md)` ` [`WebSocketServices`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1a224775f1dbbc2487c577806053764f68) | Gets the management function for the WebSocket services provided by the server.
`public ` [`WebSocketServer`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1ac530cc876c1f32a154a6c6a4b66851cd)`()` | Initializes a new instance of the WebSocketServer class.
`public ` [`WebSocketServer`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1a317b85aefc528c7e62c8b51d24a5e08a)`(int port)` | Initializes a new instance of the WebSocketServer class with the specified *port* .
`public ` [`WebSocketServer`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1a87afbd343306093640ed391f8083efcc)`(string url)` | Initializes a new instance of the WebSocketServer class with the specified *url* .
`public ` [`WebSocketServer`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1ab8275bebeb6b9102b0bf812a33610c30)`(int port, bool secure)` | Initializes a new instance of the WebSocketServer class with the specified *port* and *secure* .
`public ` [`WebSocketServer`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1afd603196a129fe80515fbb401509d202)`(System.Net.IPAddress address, int port)` | Initializes a new instance of the WebSocketServer class with the specified *address* and *port* .
`public ` [`WebSocketServer`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1a057afe05bcfb749b8ee5be3f9f6bee73)`(System.Net.IPAddress address, int port, bool secure)` | Initializes a new instance of the WebSocketServer class with the specified *address* , *port* , and *secure* .
`public void ` [`AddWebSocketService< TBehavior >`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1a755927557f8eb70227b2b084993fbeaf)`(string path, Func< TBehavior > creator)` | Adds a WebSocket service with the specified behavior, path, and delegate.
`public void ` [`AddWebSocketService< TBehaviorWithNew >`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1a5202fd649497479cdf216c483b68d9f7)`(string path)` | Adds a WebSocket service with the specified behavior and path.
`public void ` [`AddWebSocketService< TBehaviorWithNew >`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1a55ca1daeb59b639d48156e26f8d8ec06)`(string path, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)`< TBehaviorWithNew > initializer)` | Adds a WebSocket service with the specified behavior, path, and delegate.
`public bool ` [`RemoveWebSocketService`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1abf305a7e763e8c3dddd175993274fe50)`(string path)` | Removes a WebSocket service with the specified path.
`public void ` [`Start`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1a07aaf1227e4d645f15e0a964f54ef291)`()` | Starts receiving incoming handshake requests.
`public void ` [`Stop`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1a17a237457e57625296e6b24feb19c60a)`()` | Stops receiving incoming handshake requests.
`public void ` [`Stop`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1a701cfe4f1809ef684c7331dce15e8992)`(ushort code, string reason)` | Stops receiving incoming handshake requests and closes each connection with the specified code and reason.
`public void ` [`Stop`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1a069d2891d887dbaa888f84adf69e688c)`(` [`CloseStatusCode`](WebSocketSharp.md)` code, string reason)` | Stops receiving incoming handshake requests and closes each connection with the specified code and reason.
`private System.Net.IPAddress ` [`_address`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1ac2ee44bdb7b3f660c3a9cf04144c373a) | 
`private bool ` [`_allowForwardedRequest`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1ae72adaaab16bf632debb90dd6dae16f9) | 
`private ` [`AuthenticationSchemes`](WebSocketSharp--Net.md)` ` [`_authSchemes`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1ac2cfce2148d2f47655c0a1c4b048c07e) | 
`private bool ` [`_dnsStyle`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1a8f99d939bb49789b48acb0fdaa036eaa) | 
`private string ` [`_hostname`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1a4f28e1a261d44af6c3bbc9e5b8fa0683) | 
`private TcpListener ` [`_listener`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1a4fd3dc725bea8bf95a8841ed145d229b) | 
`private ` [`Logger`](WebSocketSharp--Logger.md)` ` [`_log`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1ab09157ab30052b0f1bf60fe26410d6ee) | 
`private int ` [`_port`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1a5cc37d2eb4f4e3fce88c482586cbe058) | 
`private string ` [`_realm`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1a7bc2b82b0e3f1b9f47f595918f1baa87) | 
`private string ` [`_realmInUse`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1a90a0e2c869ef5e6067928e7bf0234888) | 
`private Thread ` [`_receiveThread`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1a567bde8b1d4adcc2a3b4ed158dbe755a) | 
`private bool ` [`_reuseAddress`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1a60ce73ddecfd2200aa3a2b22feec4aed) | 
`private bool ` [`_secure`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1a2f7b5b309c5830b8532939ca02946b44) | 
`private ` [`WebSocketServiceManager`](WebSocketSharp--Server--WebSocketServiceManager.md)` ` [`_services`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1a47569c778ac707da606ea0028b42f0b0) | 
`private ` [`ServerSslConfiguration`](WebSocketSharp--Net--ServerSslConfiguration.md)` ` [`_sslConfig`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1af4cb9aca2106370fa285c159de698e49) | 
`private ` [`ServerSslConfiguration`](WebSocketSharp--Net--ServerSslConfiguration.md)` ` [`_sslConfigInUse`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1a0738248d74ac76ab03c13504526279d7) | 
`private volatile ` [`ServerState`](WebSocketSharp--Server.md)` ` [`_state`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1a0ef0deff6fe7732149d2bcd773a64f28) | 
`private object ` [`_sync`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1adbb069fcd0e2b452bc3342bc00739ed8) | 
`private Func< IIdentity, ` [`NetworkCredential`](WebSocketSharp--Net--NetworkCredential.md)` > ` [`_userCredFinder`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1add646c78b6352224b90bc76c70f4a2ae) | 
`private void ` [`abort`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1ac54f53dc342019e8db34f4aa581a5792)`()` | 
`private bool ` [`authenticateClient`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1aea3ce16fd2de0a569f238a599b5c5fd1)`(` [`TcpListenerWebSocketContext`](WebSocketSharp--Net--WebSockets--TcpListenerWebSocketContext.md)` context)` | 
`private bool ` [`canSet`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1a729ea85bb2548e8a7b5f70f75159b133)`(out string message)` | 
`private bool ` [`checkHostNameForRequest`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1a9e726505af1d172fbd969a6087e15f12)`(string name)` | 
`private string ` [`getRealm`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1a10ac965adeda4a6838004c665b046b09)`()` | 
`private ` [`ServerSslConfiguration`](WebSocketSharp--Net--ServerSslConfiguration.md)` ` [`getSslConfiguration`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1a406b51c54d80a996e6c1e7bcb50fe400)`()` | 
`private void ` [`init`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1a8142a8ba68ea30ebe7a768e3b65e7028)`(string hostname, System.Net.IPAddress address, int port, bool secure)` | 
`private void ` [`processRequest`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1a4146ace1d05f606cda17c11024fbbcbb)`(` [`TcpListenerWebSocketContext`](WebSocketSharp--Net--WebSockets--TcpListenerWebSocketContext.md)` context)` | 
`private void ` [`receiveRequest`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1aa74d80d71aa82435e1b49fa53bf4f613)`()` | 
`private void ` [`start`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1a27d9f4ee6425361774319f1d7923c4ed)`(` [`ServerSslConfiguration`](WebSocketSharp--Net--ServerSslConfiguration.md)` sslConfig)` | 
`private void ` [`startReceiving`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1a95e75d300547b71b3cc33d6e02f7a475)`()` | 
`private void ` [`stop`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1aecaba860bee0c6450a64303d3434fb5d)`(ushort code, string reason)` | 
`private void ` [`stopReceiving`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1a20283caf3d49d6d97189cde68aa6e727)`(int millisecondsTimeout)` | 
`private static static ` [`WebSocketServer`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1acad30243a86454edcb58f7b8728a87c8)`()` | 
`private static bool ` [`checkSslConfiguration`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1a66706eb1c92004c8812841c8e8ae8b0d)`(` [`ServerSslConfiguration`](WebSocketSharp--Net--ServerSslConfiguration.md)` configuration, out string message)` | 
`private static bool ` [`tryCreateUri`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1a101fd0c491f416bc1397f62f230b72ea)`(string uriString, out Uri result, out string message)` | 

## Members

##### `public System.Net.IPAddress ` [`Address`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1a42dec17b5716178801c81c25599ada7f) 

Gets the IP address of the server.

A System.Net.IPAddress that represents the local IP address on which to listen for incoming handshake requests.

##### `public bool ` [`AllowForwardedRequest`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1a0a862cec597988e7b8334dc282eebe92) 

Gets or sets a value indicating whether the server accepts every handshake request without checking the request URI.

The set operation does nothing if the server has already started or it is shutting down. 

`true` if the server accepts every handshake request without checking the request URI; otherwise, `false`. 

The default value is `false`.

##### `public ` [`AuthenticationSchemes`](WebSocketSharp--Net.md)` ` [`AuthenticationSchemes`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1ab2f4176cabceeee69cb96c6d68ab5f05) 

Gets or sets the scheme used to authenticate the clients.

The set operation does nothing if the server has already started or it is shutting down. 

One of the [WebSocketSharp.Net.AuthenticationSchemes](WebSocketSharp--Net.md) enum values. 

It represents the scheme used to authenticate the clients. 

The default value is WebSocketSharp.Net.AuthenticationSchemes.Anonymous.

##### `public bool ` [`IsListening`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1aa989b9618104958f4a259fa37fb939d8) 

Gets a value indicating whether the server has started.

`true` if the server has started; otherwise, `false`.

##### `public bool ` [`IsSecure`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1adb59d1044fe46ad2ddd774ccbc267db1) 

Gets a value indicating whether secure connections are provided.

`true` if this instance provides secure connections; otherwise, `false`.

##### `public bool ` [`KeepClean`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1ad8b9e62479203719425166890ca196f6) 

Gets or sets a value indicating whether the server cleans up the inactive sessions periodically.

The set operation does nothing if the server has already started or it is shutting down. 

`true` if the server cleans up the inactive sessions every 60 seconds; otherwise, `false`. 

The default value is `true`.

##### `public ` [`Logger`](WebSocketSharp--Logger.md)` ` [`Log`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1af2ed886ec3d2b2fd42fd0c5dad2f8cc5) 

Gets the logging function for the server.

The default logging level is LogLevel.Error. 

A Logger that provides the logging function.

##### `public int ` [`Port`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1a91b1a1342df7fe9e51fb5dfc4999dfe8) 

Gets the port of the server.

An int that represents the number of the port on which to listen for incoming handshake requests.

##### `public string ` [`Realm`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1a52a674ec0b4dc0d9e94f9ff3c47c583a) 

Gets or sets the realm used for authentication.

"SECRET AREA" is used as the realm if the value is `null` or an empty string. 

The set operation does nothing if the server has already started or it is shutting down. 

A string or `null` by default. 

That string represents the name of the realm.

##### `public bool ` [`ReuseAddress`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1a923e721e9823564407e4d83b8a49fb9b) 

Gets or sets a value indicating whether the server is allowed to be bound to an address that is already in use.

You should set this property to `true` if you would like to resolve to wait for socket in TIME_WAIT state. 

The set operation does nothing if the server has already started or it is shutting down. 

`true` if the server is allowed to be bound to an address that is already in use; otherwise, `false`. 

The default value is `false`.

##### `public ` [`ServerSslConfiguration`](WebSocketSharp--Net--ServerSslConfiguration.md)` ` [`SslConfiguration`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1aa41bf1c36ef66f799331bb3ea0204ca9) 

Gets the configuration for secure connection.

This configuration will be referenced when attempts to start, so it must be configured before the start method is called. 

A ServerSslConfiguration that represents the configuration used to provide secure connections. 

#### Exceptions
* `InvalidOperationException` This instance does not provide secure connections.

##### `public Func< IIdentity, ` [`NetworkCredential`](WebSocketSharp--Net--NetworkCredential.md)` > ` [`UserCredentialsFinder`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1acd9009b71f94aed4202e9e2fa19cc1d1) 

Gets or sets the delegate used to find the credentials for an identity.

No credentials are found if the method invoked by the delegate returns `null` or the value is `null`. 

The set operation does nothing if the server has already started or it is shutting down. 

A `Func<IIdentity, NetworkCredential>` delegate or `null` if not needed. 

That delegate invokes the method called for finding the credentials used to authenticate a client. 

The default value is `null`.

##### `public TimeSpan ` [`WaitTime`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1ae01f8dab993779eaa79c449c045db7a8) 

Gets or sets the time to wait for the response to the WebSocket Ping or Close.

The set operation does nothing if the server has already started or it is shutting down. 

A TimeSpan to wait for the response. 

The default value is the same as 1 second. 

#### Exceptions
* `ArgumentOutOfRangeException` The value specified for a set operation is zero or less.

##### `public ` [`WebSocketServiceManager`](WebSocketSharp--Server--WebSocketServiceManager.md)` ` [`WebSocketServices`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1a224775f1dbbc2487c577806053764f68) 

Gets the management function for the WebSocket services provided by the server.

A WebSocketServiceManager that manages the WebSocket services provided by the server.

##### `public ` [`WebSocketServer`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1ac530cc876c1f32a154a6c6a4b66851cd)`()` 

Initializes a new instance of the WebSocketServer class.

The new instance listens for incoming handshake requests on System.Net.IPAddress.Any and port 80.

##### `public ` [`WebSocketServer`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1a317b85aefc528c7e62c8b51d24a5e08a)`(int port)` 

Initializes a new instance of the WebSocketServer class with the specified *port* .

The new instance listens for incoming handshake requests on System.Net.IPAddress.Any and *port* . 

It provides secure connections if *port*  is 443. 

#### Parameters
* `port` An int that represents the number of the port on which to listen. 

#### Exceptions
* `ArgumentOutOfRangeException` *port*  is less than 1 or greater than 65535.

##### `public ` [`WebSocketServer`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1a87afbd343306093640ed391f8083efcc)`(string url)` 

Initializes a new instance of the WebSocketServer class with the specified *url* .

The new instance listens for incoming handshake requests on the IP address of the host of *url*  and the port of *url* . 

Either port 80 or 443 is used if *url*  includes no port. Port 443 is used if the scheme of *url*  is wss; otherwise, port 80 is used. 

The new instance provides secure connections if the scheme of *url*  is wss. 

#### Parameters
* `url` A string that represents the WebSocket URL of the server. 

#### Exceptions
* `ArgumentNullException` *url*  is `null`. 

* `ArgumentException` *url*  is an empty string. 

-or- 

*url*  is invalid.

##### `public ` [`WebSocketServer`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1ab8275bebeb6b9102b0bf812a33610c30)`(int port, bool secure)` 

Initializes a new instance of the WebSocketServer class with the specified *port*  and *secure* .

The new instance listens for incoming handshake requests on System.Net.IPAddress.Any and *port* . 

#### Parameters
* `port` An int that represents the number of the port on which to listen. 

* `secure` A bool: `true` if the new instance provides secure connections; otherwise, `false`. 

#### Exceptions
* `ArgumentOutOfRangeException` *port*  is less than 1 or greater than 65535.

##### `public ` [`WebSocketServer`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1afd603196a129fe80515fbb401509d202)`(System.Net.IPAddress address, int port)` 

Initializes a new instance of the WebSocketServer class with the specified *address*  and *port* .

The new instance listens for incoming handshake requests on *address*  and *port* . 

It provides secure connections if *port*  is 443. 

#### Parameters
* `address` A System.Net.IPAddress that represents the local IP address on which to listen. 

* `port` An int that represents the number of the port on which to listen. 

#### Exceptions
* `ArgumentNullException` *address*  is `null`. 

* `ArgumentException` *address*  is not a local IP address. 

* `ArgumentOutOfRangeException` *port*  is less than 1 or greater than 65535.

##### `public ` [`WebSocketServer`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1a057afe05bcfb749b8ee5be3f9f6bee73)`(System.Net.IPAddress address, int port, bool secure)` 

Initializes a new instance of the WebSocketServer class with the specified *address* , *port* , and *secure* .

The new instance listens for incoming handshake requests on *address*  and *port* . 

#### Parameters
* `address` A System.Net.IPAddress that represents the local IP address on which to listen. 

* `port` An int that represents the number of the port on which to listen. 

* `secure` A bool: `true` if the new instance provides secure connections; otherwise, `false`. 

#### Exceptions
* `ArgumentNullException` *address*  is `null`. 

* `ArgumentException` *address*  is not a local IP address. 

* `ArgumentOutOfRangeException` *port*  is less than 1 or greater than 65535.

##### `public void ` [`AddWebSocketService< TBehavior >`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1a755927557f8eb70227b2b084993fbeaf)`(string path, Func< TBehavior > creator)` 

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

##### `public void ` [`AddWebSocketService< TBehaviorWithNew >`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1a5202fd649497479cdf216c483b68d9f7)`(string path)` 

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

##### `public void ` [`AddWebSocketService< TBehaviorWithNew >`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1a55ca1daeb59b639d48156e26f8d8ec06)`(string path, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)`< TBehaviorWithNew > initializer)` 

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

##### `public bool ` [`RemoveWebSocketService`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1abf305a7e763e8c3dddd175993274fe50)`(string path)` 

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

##### `public void ` [`Start`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1a07aaf1227e4d645f15e0a964f54ef291)`()` 

Starts receiving incoming handshake requests.

This method does nothing if the server has already started or it is shutting down. 

#### Exceptions
* `InvalidOperationException` There is no server certificate for secure connection. 

-or- 

The underlying TcpListener has failed to start.

##### `public void ` [`Stop`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1a17a237457e57625296e6b24feb19c60a)`()` 

Stops receiving incoming handshake requests.

#### Exceptions
* `InvalidOperationException` The underlying TcpListener has failed to stop.

##### `public void ` [`Stop`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1a701cfe4f1809ef684c7331dce15e8992)`(ushort code, string reason)` 

Stops receiving incoming handshake requests and closes each connection with the specified code and reason.

#### Parameters
* `code` A ushort that represents the status code indicating the reason for the close. 

The status codes are defined in  Section 7.4

of RFC 6455. 

* `reason` A string that represents the reason for the close. 

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

* `InvalidOperationException` The underlying TcpListener has failed to stop.

##### `public void ` [`Stop`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1a069d2891d887dbaa888f84adf69e688c)`(` [`CloseStatusCode`](WebSocketSharp.md)` code, string reason)` 

Stops receiving incoming handshake requests and closes each connection with the specified code and reason.

#### Parameters
* `code` One of the CloseStatusCode enum values. 

It represents the status code indicating the reason for the close. 

* `reason` A string that represents the reason for the close. 

The size must be 123 bytes or less in UTF-8. 

#### Exceptions
* `ArgumentException` *code*  is CloseStatusCode.MandatoryExtension. 

-or- 

*code*  is CloseStatusCode.NoStatus and there is reason. 

-or- 

*reason*  could not be UTF-8-encoded. 

* `ArgumentOutOfRangeException` The size of *reason*  is greater than 123 bytes. 

* `InvalidOperationException` The underlying TcpListener has failed to stop.

##### `private System.Net.IPAddress ` [`_address`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1ac2ee44bdb7b3f660c3a9cf04144c373a) 

##### `private bool ` [`_allowForwardedRequest`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1ae72adaaab16bf632debb90dd6dae16f9) 

##### `private ` [`AuthenticationSchemes`](WebSocketSharp--Net.md)` ` [`_authSchemes`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1ac2cfce2148d2f47655c0a1c4b048c07e) 

##### `private bool ` [`_dnsStyle`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1a8f99d939bb49789b48acb0fdaa036eaa) 

##### `private string ` [`_hostname`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1a4f28e1a261d44af6c3bbc9e5b8fa0683) 

##### `private TcpListener ` [`_listener`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1a4fd3dc725bea8bf95a8841ed145d229b) 

##### `private ` [`Logger`](WebSocketSharp--Logger.md)` ` [`_log`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1ab09157ab30052b0f1bf60fe26410d6ee) 

##### `private int ` [`_port`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1a5cc37d2eb4f4e3fce88c482586cbe058) 

##### `private string ` [`_realm`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1a7bc2b82b0e3f1b9f47f595918f1baa87) 

##### `private string ` [`_realmInUse`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1a90a0e2c869ef5e6067928e7bf0234888) 

##### `private Thread ` [`_receiveThread`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1a567bde8b1d4adcc2a3b4ed158dbe755a) 

##### `private bool ` [`_reuseAddress`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1a60ce73ddecfd2200aa3a2b22feec4aed) 

##### `private bool ` [`_secure`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1a2f7b5b309c5830b8532939ca02946b44) 

##### `private ` [`WebSocketServiceManager`](WebSocketSharp--Server--WebSocketServiceManager.md)` ` [`_services`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1a47569c778ac707da606ea0028b42f0b0) 

##### `private ` [`ServerSslConfiguration`](WebSocketSharp--Net--ServerSslConfiguration.md)` ` [`_sslConfig`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1af4cb9aca2106370fa285c159de698e49) 

##### `private ` [`ServerSslConfiguration`](WebSocketSharp--Net--ServerSslConfiguration.md)` ` [`_sslConfigInUse`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1a0738248d74ac76ab03c13504526279d7) 

##### `private volatile ` [`ServerState`](WebSocketSharp--Server.md)` ` [`_state`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1a0ef0deff6fe7732149d2bcd773a64f28) 

##### `private object ` [`_sync`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1adbb069fcd0e2b452bc3342bc00739ed8) 

##### `private Func< IIdentity, ` [`NetworkCredential`](WebSocketSharp--Net--NetworkCredential.md)` > ` [`_userCredFinder`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1add646c78b6352224b90bc76c70f4a2ae) 

##### `private void ` [`abort`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1ac54f53dc342019e8db34f4aa581a5792)`()` 

##### `private bool ` [`authenticateClient`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1aea3ce16fd2de0a569f238a599b5c5fd1)`(` [`TcpListenerWebSocketContext`](WebSocketSharp--Net--WebSockets--TcpListenerWebSocketContext.md)` context)` 

##### `private bool ` [`canSet`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1a729ea85bb2548e8a7b5f70f75159b133)`(out string message)` 

##### `private bool ` [`checkHostNameForRequest`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1a9e726505af1d172fbd969a6087e15f12)`(string name)` 

##### `private string ` [`getRealm`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1a10ac965adeda4a6838004c665b046b09)`()` 

##### `private ` [`ServerSslConfiguration`](WebSocketSharp--Net--ServerSslConfiguration.md)` ` [`getSslConfiguration`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1a406b51c54d80a996e6c1e7bcb50fe400)`()` 

##### `private void ` [`init`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1a8142a8ba68ea30ebe7a768e3b65e7028)`(string hostname, System.Net.IPAddress address, int port, bool secure)` 

##### `private void ` [`processRequest`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1a4146ace1d05f606cda17c11024fbbcbb)`(` [`TcpListenerWebSocketContext`](WebSocketSharp--Net--WebSockets--TcpListenerWebSocketContext.md)` context)` 

##### `private void ` [`receiveRequest`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1aa74d80d71aa82435e1b49fa53bf4f613)`()` 

##### `private void ` [`start`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1a27d9f4ee6425361774319f1d7923c4ed)`(` [`ServerSslConfiguration`](WebSocketSharp--Net--ServerSslConfiguration.md)` sslConfig)` 

##### `private void ` [`startReceiving`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1a95e75d300547b71b3cc33d6e02f7a475)`()` 

##### `private void ` [`stop`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1aecaba860bee0c6450a64303d3434fb5d)`(ushort code, string reason)` 

##### `private void ` [`stopReceiving`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1a20283caf3d49d6d97189cde68aa6e727)`(int millisecondsTimeout)` 

##### `private static static ` [`WebSocketServer`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1acad30243a86454edcb58f7b8728a87c8)`()` 

##### `private static bool ` [`checkSslConfiguration`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1a66706eb1c92004c8812841c8e8ae8b0d)`(` [`ServerSslConfiguration`](WebSocketSharp--Net--ServerSslConfiguration.md)` configuration, out string message)` 

##### `private static bool ` [`tryCreateUri`](#class_web_socket_sharp_1_1_server_1_1_web_socket_server_1a101fd0c491f416bc1397f62f230b72ea)`(string uriString, out Uri result, out string message)` 

