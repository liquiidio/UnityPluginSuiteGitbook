# class `WebSocketSharp::Server::WebSocketServiceManager` 

Provides the management function for the WebSocket services.

This class manages the WebSocket services provided by the WebSocketServer or HttpServer.

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public int ` [`Count`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_manager_1aad462966ed963f892117056de1eba502) | Gets the number of the WebSocket services.
`public IEnumerable< ` [`WebSocketServiceHost`](WebSocketSharp--Server--WebSocketServiceHost.md)` > ` [`Hosts`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_manager_1a68caad9ece82726e7e4542206cf36e9d) | Gets the host instances for the WebSocket services.
`public ` [`WebSocketServiceHost`](WebSocketSharp--Server--WebSocketServiceHost.md)` ` [`this[string path]`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_manager_1a24d89d8d853109c397b9ab36a1892feb) | Gets the host instance for a WebSocket service with the specified path.
`public bool ` [`KeepClean`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_manager_1ad8b9e62479203719425166890ca196f6) | Gets or sets a value indicating whether the inactive sessions in the WebSocket services are cleaned up periodically.
`public IEnumerable< string > ` [`Paths`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_manager_1abe5ff82cf1f2bd9ecf20bc02fd357c81) | Gets the paths for the WebSocket services.
`public int ` [`SessionCount`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_manager_1a5eb54ca651b9a44306251528eb170f86) | Gets the total number of the sessions in the WebSocket services.
`public TimeSpan ` [`WaitTime`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_manager_1ae01f8dab993779eaa79c449c045db7a8) | Gets or sets the time to wait for the response to the WebSocket Ping or Close.
`public void ` [`AddService< TBehavior >`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_manager_1aaa2045e5611c8fe2a701254c3b6151c4)`(string path, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)`< TBehavior > initializer)` | Adds a WebSocket service with the specified behavior, path, and delegate.
`public void ` [`Broadcast`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_manager_1ac59ca4e4646d0cf396ecabdf4a3bf991)`(byte[] data)` | Sends *data* to every client in the WebSocket services.
`public void ` [`Broadcast`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_manager_1aac21e8f8a4bb1d2c60b8870498ba3624)`(string data)` | Sends *data* to every client in the WebSocket services.
`public void ` [`BroadcastAsync`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_manager_1aaa7e0e4b6e9e58fa843ee7c87f05d4af)`(byte[] data, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)` completed)` | Sends *data* asynchronously to every client in the WebSocket services.
`public void ` [`BroadcastAsync`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_manager_1a8012e57f77b3bce959c8678deeae7c58)`(string data, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)` completed)` | Sends *data* asynchronously to every client in the WebSocket services.
`public void ` [`BroadcastAsync`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_manager_1a9dd7b98e046613e6911fadfb337d393e)`(Stream stream, int length, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)` completed)` | Sends the data from *stream* asynchronously to every client in the WebSocket services.
`public Dictionary< string, Dictionary< string, bool > > ` [`Broadping`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_manager_1a009cd2182bf3b56e1852c605977161df)`()` | Sends a ping to every client in the WebSocket services.
`public Dictionary< string, Dictionary< string, bool > > ` [`Broadping`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_manager_1a7fe2b5d1da9804b872d182c3ec06cba5)`(string message)` | Sends a ping with *message* to every client in the WebSocket services.
`public void ` [`Clear`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_manager_1aa71d36872f416feaa853788a7a7a7ef8)`()` | Removes all WebSocket services managed by the manager.
`public bool ` [`RemoveService`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_manager_1a15a732c71b9da8a2f3eee5c879bc75ed)`(string path)` | Removes a WebSocket service with the specified path.
`public bool ` [`TryGetServiceHost`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_manager_1a368b766068596e8ed6ccec3d4cf35b10)`(string path, out ` [`WebSocketServiceHost`](WebSocketSharp--Server--WebSocketServiceHost.md)` host)` | Tries to get the host instance for a WebSocket service with the specified path.
`private volatile bool ` [`_clean`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_manager_1a12dfa42d0f87fc871d5d85bcd1627aeb) | 
`private Dictionary< string, ` [`WebSocketServiceHost`](WebSocketSharp--Server--WebSocketServiceHost.md)` > ` [`_hosts`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_manager_1a660f1855366bf97c45f830a24abb4282) | 
`private ` [`Logger`](WebSocketSharp--Logger.md)` ` [`_log`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_manager_1ab09157ab30052b0f1bf60fe26410d6ee) | 
`private volatile ` [`ServerState`](WebSocketSharp--Server.md)` ` [`_state`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_manager_1a0ef0deff6fe7732149d2bcd773a64f28) | 
`private object ` [`_sync`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_manager_1adbb069fcd0e2b452bc3342bc00739ed8) | 
`private TimeSpan ` [`_waitTime`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_manager_1aff6d565013f5a1afe6d5b94ee07b5454) | 
`private void ` [`broadcast`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_manager_1a24675ceb7f198a2aababe824eccb7e73)`(` [`Opcode`](WebSocketSharp.md)` opcode, byte[] data, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)` completed)` | 
`private void ` [`broadcast`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_manager_1a8ecd32e2431afbe6044b3400bd5c430f)`(` [`Opcode`](WebSocketSharp.md)` opcode, Stream stream, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)` completed)` | 
`private void ` [`broadcastAsync`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_manager_1ac9014e9eaa1e94b08ac4e21a7ee2393e)`(` [`Opcode`](WebSocketSharp.md)` opcode, byte[] data, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)` completed)` | 
`private void ` [`broadcastAsync`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_manager_1a45bd88460c7605fafea44ba473d3ab55)`(` [`Opcode`](WebSocketSharp.md)` opcode, Stream stream, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)` completed)` | 
`private Dictionary< string, Dictionary< string, bool > > ` [`broadping`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_manager_1a5cc1564299d60f488e841facfc2bbb62)`(byte[] frameAsBytes, TimeSpan timeout)` | 
`private bool ` [`canSet`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_manager_1a729ea85bb2548e8a7b5f70f75159b133)`(out string message)` | 

## Members

##### `public int ` [`Count`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_manager_1aad462966ed963f892117056de1eba502) 

Gets the number of the WebSocket services.

An int that represents the number of the services.

##### `public IEnumerable< ` [`WebSocketServiceHost`](WebSocketSharp--Server--WebSocketServiceHost.md)` > ` [`Hosts`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_manager_1a68caad9ece82726e7e4542206cf36e9d) 

Gets the host instances for the WebSocket services.

An `IEnumerable<WebSocketServiceHost>` instance. 

It provides an enumerator which supports the iteration over the collection of the host instances.

##### `public ` [`WebSocketServiceHost`](WebSocketSharp--Server--WebSocketServiceHost.md)` ` [`this[string path]`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_manager_1a24d89d8d853109c397b9ab36a1892feb) 

Gets the host instance for a WebSocket service with the specified path.

A WebSocketServiceHost instance or `null` if not found. 

The host instance provides the function to access the information in the service. 

#### Parameters
* `path` A string that represents an absolute path to the service to find. 

/ is trimmed from the end of the string if present. 

#### Exceptions
* `ArgumentNullException` *path*  is `null`. 

* `ArgumentException` *path*  is empty. 

-or- 

*path*  is not an absolute path. 

-or- 

*path*  includes either or both query and fragment components.

##### `public bool ` [`KeepClean`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_manager_1ad8b9e62479203719425166890ca196f6) 

Gets or sets a value indicating whether the inactive sessions in the WebSocket services are cleaned up periodically.

The set operation does nothing if the server has already started or it is shutting down. 

`true` if the inactive sessions are cleaned up every 60 seconds; otherwise, `false`.

##### `public IEnumerable< string > ` [`Paths`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_manager_1abe5ff82cf1f2bd9ecf20bc02fd357c81) 

Gets the paths for the WebSocket services.

An `IEnumerable<string>` instance. 

It provides an enumerator which supports the iteration over the collection of the paths.

##### `public int ` [`SessionCount`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_manager_1a5eb54ca651b9a44306251528eb170f86) 

Gets the total number of the sessions in the WebSocket services.

An int that represents the total number of the sessions in the services.

##### `public TimeSpan ` [`WaitTime`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_manager_1ae01f8dab993779eaa79c449c045db7a8) 

Gets or sets the time to wait for the response to the WebSocket Ping or Close.

The set operation does nothing if the server has already started or it is shutting down. 

A TimeSpan to wait for the response. 

#### Exceptions
* `ArgumentOutOfRangeException` The value specified for a set operation is zero or less.

##### `public void ` [`AddService< TBehavior >`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_manager_1aaa2045e5611c8fe2a701254c3b6151c4)`(string path, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)`< TBehavior > initializer)` 

Adds a WebSocket service with the specified behavior, path, and delegate.

#### Parameters
* `path` A string that represents an absolute path to the service to add. 

/ is trimmed from the end of the string if present. 

* `initializer` An `Action<TBehavior>` delegate or `null` if not needed. 

The delegate invokes the method called when initializing a new session instance for the service. 

#### Parameters
* `TBehavior` The type of the behavior for the service. 

It must inherit the WebSocketBehavior class. 

And also, it must have a public parameterless constructor. 

#### Exceptions
* `ArgumentNullException` *path*  is `null`. 

* `ArgumentException` *path*  is empty. 

-or- 

*path*  is not an absolute path. 

-or- 

*path*  includes either or both query and fragment components. 

-or- 

*path*  is already in use.

##### `public void ` [`Broadcast`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_manager_1ac59ca4e4646d0cf396ecabdf4a3bf991)`(byte[] data)` 

Sends *data*  to every client in the WebSocket services.

#### Parameters
* `data` An array of byte that represents the binary data to send. 

#### Exceptions
* `InvalidOperationException` The current state of the manager is not Start. 

* `ArgumentNullException` *data*  is `null`.

##### `public void ` [`Broadcast`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_manager_1aac21e8f8a4bb1d2c60b8870498ba3624)`(string data)` 

Sends *data*  to every client in the WebSocket services.

#### Parameters
* `data` A string that represents the text data to send. 

#### Exceptions
* `InvalidOperationException` The current state of the manager is not Start. 

* `ArgumentNullException` *data*  is `null`. 

* `ArgumentException` *data*  could not be UTF-8-encoded.

##### `public void ` [`BroadcastAsync`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_manager_1aaa7e0e4b6e9e58fa843ee7c87f05d4af)`(byte[] data, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)` completed)` 

Sends *data*  asynchronously to every client in the WebSocket services.

This method does not wait for the send to be complete. 

#### Parameters
* `data` An array of byte that represents the binary data to send. 

* `completed` An Action delegate or `null` if not needed. 

The delegate invokes the method called when the send is complete. 

#### Exceptions
* `InvalidOperationException` The current state of the manager is not Start. 

* `ArgumentNullException` *data*  is `null`.

##### `public void ` [`BroadcastAsync`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_manager_1a8012e57f77b3bce959c8678deeae7c58)`(string data, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)` completed)` 

Sends *data*  asynchronously to every client in the WebSocket services.

This method does not wait for the send to be complete. 

#### Parameters
* `data` A string that represents the text data to send. 

* `completed` An Action delegate or `null` if not needed. 

The delegate invokes the method called when the send is complete. 

#### Exceptions
* `InvalidOperationException` The current state of the manager is not Start. 

* `ArgumentNullException` *data*  is `null`. 

* `ArgumentException` *data*  could not be UTF-8-encoded.

##### `public void ` [`BroadcastAsync`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_manager_1a9dd7b98e046613e6911fadfb337d393e)`(Stream stream, int length, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)` completed)` 

Sends the data from *stream*  asynchronously to every client in the WebSocket services.

The data is sent as the binary data. 

This method does not wait for the send to be complete. 

#### Parameters
* `stream` A Stream instance from which to read the data to send. 

* `length` An int that specifies the number of bytes to send. 

* `completed` An Action delegate or `null` if not needed. 

The delegate invokes the method called when the send is complete. 

#### Exceptions
* `InvalidOperationException` The current state of the manager is not Start. 

* `ArgumentNullException` *stream*  is `null`. 

* `ArgumentException` *stream*  cannot be read. 

-or- 

*length*  is less than 1. 

-or- 

No data could be read from *stream* .

##### `public Dictionary< string, Dictionary< string, bool > > ` [`Broadping`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_manager_1a009cd2182bf3b56e1852c605977161df)`()` 

Sends a ping to every client in the WebSocket services.

#### Returns
A `Dictionary<string, Dictionary<string, bool>>`. 

It represents a collection of pairs of a service path and another collection of pairs of a session ID and a value indicating whether a pong has been received from the client within a time. 

#### Exceptions
* `InvalidOperationException` The current state of the manager is not Start.

##### `public Dictionary< string, Dictionary< string, bool > > ` [`Broadping`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_manager_1a7fe2b5d1da9804b872d182c3ec06cba5)`(string message)` 

Sends a ping with *message*  to every client in the WebSocket services.

#### Returns
A `Dictionary<string, Dictionary<string, bool>>`. 

It represents a collection of pairs of a service path and another collection of pairs of a session ID and a value indicating whether a pong has been received from the client within a time. 

#### Parameters
* `message` A string that represents the message to send. 

The size must be 125 bytes or less in UTF-8. 

#### Exceptions
* `InvalidOperationException` The current state of the manager is not Start. 

* `ArgumentException` *message*  could not be UTF-8-encoded. 

* `ArgumentOutOfRangeException` The size of *message*  is greater than 125 bytes.

##### `public void ` [`Clear`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_manager_1aa71d36872f416feaa853788a7a7a7ef8)`()` 

Removes all WebSocket services managed by the manager.

A service is stopped with close status 1001 (going away) if it has already started.

##### `public bool ` [`RemoveService`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_manager_1a15a732c71b9da8a2f3eee5c879bc75ed)`(string path)` 

Removes a WebSocket service with the specified path.

The service is stopped with close status 1001 (going away) if it has already started. 

#### Returns
`true` if the service is successfully found and removed; otherwise, `false`. 

#### Parameters
* `path` A string that represents an absolute path to the service to remove. 

/ is trimmed from the end of the string if present. 

#### Exceptions
* `ArgumentNullException` *path*  is `null`. 

* `ArgumentException` *path*  is empty. 

-or- 

*path*  is not an absolute path. 

-or- 

*path*  includes either or both query and fragment components.

##### `public bool ` [`TryGetServiceHost`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_manager_1a368b766068596e8ed6ccec3d4cf35b10)`(string path, out ` [`WebSocketServiceHost`](WebSocketSharp--Server--WebSocketServiceHost.md)` host)` 

Tries to get the host instance for a WebSocket service with the specified path.

#### Returns
`true` if the service is successfully found; otherwise, `false`. 

#### Parameters
* `path` A string that represents an absolute path to the service to find. 

/ is trimmed from the end of the string if present. 

* `host` When this method returns, a WebSocketServiceHost instance or `null` if not found. 

The host instance provides the function to access the information in the service. 

#### Exceptions
* `ArgumentNullException` *path*  is `null`. 

* `ArgumentException` *path*  is empty. 

-or- 

*path*  is not an absolute path. 

-or- 

*path*  includes either or both query and fragment components.

##### `private volatile bool ` [`_clean`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_manager_1a12dfa42d0f87fc871d5d85bcd1627aeb) 

##### `private Dictionary< string, ` [`WebSocketServiceHost`](WebSocketSharp--Server--WebSocketServiceHost.md)` > ` [`_hosts`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_manager_1a660f1855366bf97c45f830a24abb4282) 

##### `private ` [`Logger`](WebSocketSharp--Logger.md)` ` [`_log`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_manager_1ab09157ab30052b0f1bf60fe26410d6ee) 

##### `private volatile ` [`ServerState`](WebSocketSharp--Server.md)` ` [`_state`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_manager_1a0ef0deff6fe7732149d2bcd773a64f28) 

##### `private object ` [`_sync`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_manager_1adbb069fcd0e2b452bc3342bc00739ed8) 

##### `private TimeSpan ` [`_waitTime`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_manager_1aff6d565013f5a1afe6d5b94ee07b5454) 

##### `private void ` [`broadcast`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_manager_1a24675ceb7f198a2aababe824eccb7e73)`(` [`Opcode`](WebSocketSharp.md)` opcode, byte[] data, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)` completed)` 

##### `private void ` [`broadcast`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_manager_1a8ecd32e2431afbe6044b3400bd5c430f)`(` [`Opcode`](WebSocketSharp.md)` opcode, Stream stream, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)` completed)` 

##### `private void ` [`broadcastAsync`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_manager_1ac9014e9eaa1e94b08ac4e21a7ee2393e)`(` [`Opcode`](WebSocketSharp.md)` opcode, byte[] data, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)` completed)` 

##### `private void ` [`broadcastAsync`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_manager_1a45bd88460c7605fafea44ba473d3ab55)`(` [`Opcode`](WebSocketSharp.md)` opcode, Stream stream, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)` completed)` 

##### `private Dictionary< string, Dictionary< string, bool > > ` [`broadping`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_manager_1a5cc1564299d60f488e841facfc2bbb62)`(byte[] frameAsBytes, TimeSpan timeout)` 

##### `private bool ` [`canSet`](#class_web_socket_sharp_1_1_server_1_1_web_socket_service_manager_1a729ea85bb2548e8a7b5f70f75159b133)`(out string message)` 

