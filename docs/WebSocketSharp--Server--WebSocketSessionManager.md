# class `WebSocketSharp::Server::WebSocketSessionManager` 

Provides the management function for the sessions in a WebSocket service.

This class manages the sessions in a WebSocket service provided by the WebSocketServer or HttpServer.

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`package ` [`ServerState`](WebSocketSharp--Server.md)` ` [`State`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1a7867316717df3e603c59059f08137855) | 
`public IEnumerable< string > ` [`ActiveIDs`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1a962077e793d1bd2af32c5fd80cad20ed) | Gets the IDs for the active sessions in the WebSocket service.
`public int ` [`Count`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1aad462966ed963f892117056de1eba502) | Gets the number of the sessions in the WebSocket service.
`public IEnumerable< string > ` [`IDs`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1a181ab180fd94c1824fde73e871231e63) | Gets the IDs for the sessions in the WebSocket service.
`public IEnumerable< string > ` [`InactiveIDs`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1a0bfae768bd1e09175ce93fc78a76ebdb) | Gets the IDs for the inactive sessions in the WebSocket service.
`public ` [`IWebSocketSession`](WebSocketSharp--Server.md)` ` [`this[string id]`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1a05c310078fc6a246a6101554849a4238) | Gets the session instance with *id* .
`public bool ` [`KeepClean`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1ad8b9e62479203719425166890ca196f6) | Gets or sets a value indicating whether the inactive sessions in the WebSocket service are cleaned up periodically.
`public IEnumerable< ` [`IWebSocketSession`](WebSocketSharp--Server.md)` > ` [`Sessions`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1a1c16d52f1138953fa3eb326e5b8bbd7e) | Gets the session instances in the WebSocket service.
`public TimeSpan ` [`WaitTime`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1ae01f8dab993779eaa79c449c045db7a8) | Gets or sets the time to wait for the response to the WebSocket Ping or Close.
`public void ` [`Broadcast`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1ac59ca4e4646d0cf396ecabdf4a3bf991)`(byte[] data)` | Sends *data* to every client in the WebSocket service.
`public void ` [`Broadcast`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1aac21e8f8a4bb1d2c60b8870498ba3624)`(string data)` | Sends *data* to every client in the WebSocket service.
`public void ` [`Broadcast`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1a84163486a79ba85df6d1b70f42fd1303)`(Stream stream, int length)` | Sends the data from *stream* to every client in the WebSocket service.
`public void ` [`BroadcastAsync`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1aaa7e0e4b6e9e58fa843ee7c87f05d4af)`(byte[] data, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)` completed)` | Sends *data* asynchronously to every client in the WebSocket service.
`public void ` [`BroadcastAsync`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1a8012e57f77b3bce959c8678deeae7c58)`(string data, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)` completed)` | Sends *data* asynchronously to every client in the WebSocket service.
`public void ` [`BroadcastAsync`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1a9dd7b98e046613e6911fadfb337d393e)`(Stream stream, int length, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)` completed)` | Sends the data from *stream* asynchronously to every client in the WebSocket service.
`public Dictionary< string, bool > ` [`Broadping`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1aa4dbe93d2d8c8024efaf742dcc6151f7)`()` | Sends a ping to every client in the WebSocket service.
`public Dictionary< string, bool > ` [`Broadping`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1a6f38ac18a87bdc91c29448e2be2018a8)`(string message)` | Sends a ping with *message* to every client in the WebSocket service.
`public void ` [`CloseSession`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1a7f2d797dcddf8c6a27093550fe97ff1f)`(string id)` | Closes the specified session.
`public void ` [`CloseSession`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1a4b34c43603f82e5b116e8ae843d88025)`(string id, ushort code, string reason)` | Closes the specified session with *code* and *reason* .
`public void ` [`CloseSession`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1a5692e1609c2bae980d0baed58660d584)`(string id, ` [`CloseStatusCode`](WebSocketSharp.md)` code, string reason)` | Closes the specified session with *code* and *reason* .
`public bool ` [`PingTo`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1aa53f1ff2e1be8f054564c5917fd4a7a8)`(string id)` | Sends a ping to the client using the specified session.
`public bool ` [`PingTo`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1a02a6cbe48406b083254d3ffd2f68447c)`(string message, string id)` | Sends a ping with *message* to the client using the specified session.
`public void ` [`SendTo`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1a7fc48dc5bf3042d80f42b5b8518c6a77)`(byte[] data, string id)` | Sends *data* to the client using the specified session.
`public void ` [`SendTo`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1ad4dedaf27b37bd9bb41f2cfdfcaec9aa)`(string data, string id)` | Sends *data* to the client using the specified session.
`public void ` [`SendTo`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1a96fd7ef837298749cc6731b3e1829364)`(Stream stream, int length, string id)` | Sends the data from *stream* to the client using the specified session.
`public void ` [`SendToAsync`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1a91ad85c95ed380ba98cd40928166d6d9)`(byte[] data, string id, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)`< bool > completed)` | Sends *data* asynchronously to the client using the specified session.
`public void ` [`SendToAsync`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1abee1ed00d68277a9da783d11986055ec)`(string data, string id, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)`< bool > completed)` | Sends *data* asynchronously to the client using the specified session.
`public void ` [`SendToAsync`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1ae001532c5574ee3504aabf6e81d76226)`(Stream stream, int length, string id, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)`< bool > completed)` | Sends the data from *stream* asynchronously to the client using the specified session.
`public void ` [`Sweep`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1a948f644fec100a1ad661e30ff9f4a314)`()` | Cleans up the inactive sessions in the WebSocket service.
`public bool ` [`TryGetSession`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1a521e17c6054dac38c184e024237c587b)`(string id, out ` [`IWebSocketSession`](WebSocketSharp--Server.md)` session)` | Tries to get the session instance with *id* .
`private volatile bool ` [`_clean`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1a12dfa42d0f87fc871d5d85bcd1627aeb) | 
`private object ` [`_forSweep`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1a1c5101c9930ee22b59aa4854441aa009) | 
`private ` [`Logger`](WebSocketSharp--Logger.md)` ` [`_log`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1ab09157ab30052b0f1bf60fe26410d6ee) | 
`private Dictionary< string, ` [`IWebSocketSession`](WebSocketSharp--Server.md)` > ` [`_sessions`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1a3cd368b7e987d74a1342c3f5b25ab2d4) | 
`private volatile ` [`ServerState`](WebSocketSharp--Server.md)` ` [`_state`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1a0ef0deff6fe7732149d2bcd773a64f28) | 
`private volatile bool ` [`_sweeping`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1a06c33a07f6959f37b3fb6e89ce28dd83) | 
`private System.Timers.Timer ` [`_sweepTimer`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1a1ac7edcca3acf15bffc7489f29d2d627) | 
`private object ` [`_sync`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1adbb069fcd0e2b452bc3342bc00739ed8) | 
`private TimeSpan ` [`_waitTime`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1aff6d565013f5a1afe6d5b94ee07b5454) | 
`private void ` [`broadcast`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1a24675ceb7f198a2aababe824eccb7e73)`(` [`Opcode`](WebSocketSharp.md)` opcode, byte[] data, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)` completed)` | 
`private void ` [`broadcast`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1a8ecd32e2431afbe6044b3400bd5c430f)`(` [`Opcode`](WebSocketSharp.md)` opcode, Stream stream, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)` completed)` | 
`private void ` [`broadcastAsync`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1ac9014e9eaa1e94b08ac4e21a7ee2393e)`(` [`Opcode`](WebSocketSharp.md)` opcode, byte[] data, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)` completed)` | 
`private void ` [`broadcastAsync`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1a45bd88460c7605fafea44ba473d3ab55)`(` [`Opcode`](WebSocketSharp.md)` opcode, Stream stream, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)` completed)` | 
`private Dictionary< string, bool > ` [`broadping`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1a6d5265d35df0d418775c8e615b660d20)`(byte[] frameAsBytes)` | 
`private bool ` [`canSet`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1a729ea85bb2548e8a7b5f70f75159b133)`(out string message)` | 
`private void ` [`setSweepTimer`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1a2ffb610419cf5eafce04a46e65d55204)`(double interval)` | 
`private void ` [`stop`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1a75dfa06184262c39a381d228ece12524)`(` [`PayloadData`](WebSocketSharp--PayloadData.md)` payloadData, bool send)` | 
`private bool ` [`tryGetSession`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1a657a98b961e7583fbb2244451ba46128)`(string id, out ` [`IWebSocketSession`](WebSocketSharp--Server.md)` session)` | 
`private static string ` [`createID`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1a7f9aacb66fc97c47e3c46351303468d5)`()` | 

## Members

##### `package ` [`ServerState`](WebSocketSharp--Server.md)` ` [`State`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1a7867316717df3e603c59059f08137855) 

##### `public IEnumerable< string > ` [`ActiveIDs`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1a962077e793d1bd2af32c5fd80cad20ed) 

Gets the IDs for the active sessions in the WebSocket service.

An `IEnumerable<string>` instance. 

It provides an enumerator which supports the iteration over the collection of the IDs for the active sessions.

##### `public int ` [`Count`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1aad462966ed963f892117056de1eba502) 

Gets the number of the sessions in the WebSocket service.

An int that represents the number of the sessions.

##### `public IEnumerable< string > ` [`IDs`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1a181ab180fd94c1824fde73e871231e63) 

Gets the IDs for the sessions in the WebSocket service.

An `IEnumerable<string>` instance. 

It provides an enumerator which supports the iteration over the collection of the IDs for the sessions.

##### `public IEnumerable< string > ` [`InactiveIDs`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1a0bfae768bd1e09175ce93fc78a76ebdb) 

Gets the IDs for the inactive sessions in the WebSocket service.

An `IEnumerable<string>` instance. 

It provides an enumerator which supports the iteration over the collection of the IDs for the inactive sessions.

##### `public ` [`IWebSocketSession`](WebSocketSharp--Server.md)` ` [`this[string id]`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1a05c310078fc6a246a6101554849a4238) 

Gets the session instance with *id* .

A IWebSocketSession instance or `null` if not found. 

The session instance provides the function to access the information in the session. 

#### Parameters
* `id` A string that represents the ID of the session to find. 

#### Exceptions
* `ArgumentNullException` *id*  is `null`. 

* `ArgumentException` *id*  is an empty string.

##### `public bool ` [`KeepClean`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1ad8b9e62479203719425166890ca196f6) 

Gets or sets a value indicating whether the inactive sessions in the WebSocket service are cleaned up periodically.

The set operation does nothing if the service has already started or it is shutting down. 

`true` if the inactive sessions are cleaned up every 60 seconds; otherwise, `false`.

##### `public IEnumerable< ` [`IWebSocketSession`](WebSocketSharp--Server.md)` > ` [`Sessions`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1a1c16d52f1138953fa3eb326e5b8bbd7e) 

Gets the session instances in the WebSocket service.

An `IEnumerable<IWebSocketSession>` instance. 

It provides an enumerator which supports the iteration over the collection of the session instances.

##### `public TimeSpan ` [`WaitTime`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1ae01f8dab993779eaa79c449c045db7a8) 

Gets or sets the time to wait for the response to the WebSocket Ping or Close.

The set operation does nothing if the service has already started or it is shutting down. 

A TimeSpan to wait for the response. 

#### Exceptions
* `ArgumentOutOfRangeException` The value specified for a set operation is zero or less.

##### `public void ` [`Broadcast`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1ac59ca4e4646d0cf396ecabdf4a3bf991)`(byte[] data)` 

Sends *data*  to every client in the WebSocket service.

#### Parameters
* `data` An array of byte that represents the binary data to send. 

#### Exceptions
* `InvalidOperationException` The current state of the manager is not Start. 

* `ArgumentNullException` *data*  is `null`.

##### `public void ` [`Broadcast`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1aac21e8f8a4bb1d2c60b8870498ba3624)`(string data)` 

Sends *data*  to every client in the WebSocket service.

#### Parameters
* `data` A string that represents the text data to send. 

#### Exceptions
* `InvalidOperationException` The current state of the manager is not Start. 

* `ArgumentNullException` *data*  is `null`. 

* `ArgumentException` *data*  could not be UTF-8-encoded.

##### `public void ` [`Broadcast`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1a84163486a79ba85df6d1b70f42fd1303)`(Stream stream, int length)` 

Sends the data from *stream*  to every client in the WebSocket service.

The data is sent as the binary data. 

#### Parameters
* `stream` A Stream instance from which to read the data to send. 

* `length` An int that specifies the number of bytes to send. 

#### Exceptions
* `InvalidOperationException` The current state of the manager is not Start. 

* `ArgumentNullException` *stream*  is `null`. 

* `ArgumentException` *stream*  cannot be read. 

-or- 

*length*  is less than 1. 

-or- 

No data could be read from *stream* .

##### `public void ` [`BroadcastAsync`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1aaa7e0e4b6e9e58fa843ee7c87f05d4af)`(byte[] data, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)` completed)` 

Sends *data*  asynchronously to every client in the WebSocket service.

This method does not wait for the send to be complete. 

#### Parameters
* `data` An array of byte that represents the binary data to send. 

* `completed` An Action delegate or `null` if not needed. 

The delegate invokes the method called when the send is complete. 

#### Exceptions
* `InvalidOperationException` The current state of the manager is not Start. 

* `ArgumentNullException` *data*  is `null`.

##### `public void ` [`BroadcastAsync`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1a8012e57f77b3bce959c8678deeae7c58)`(string data, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)` completed)` 

Sends *data*  asynchronously to every client in the WebSocket service.

This method does not wait for the send to be complete. 

#### Parameters
* `data` A string that represents the text data to send. 

* `completed` An Action delegate or `null` if not needed. 

The delegate invokes the method called when the send is complete. 

#### Exceptions
* `InvalidOperationException` The current state of the manager is not Start. 

* `ArgumentNullException` *data*  is `null`. 

* `ArgumentException` *data*  could not be UTF-8-encoded.

##### `public void ` [`BroadcastAsync`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1a9dd7b98e046613e6911fadfb337d393e)`(Stream stream, int length, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)` completed)` 

Sends the data from *stream*  asynchronously to every client in the WebSocket service.

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

##### `public Dictionary< string, bool > ` [`Broadping`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1aa4dbe93d2d8c8024efaf742dcc6151f7)`()` 

Sends a ping to every client in the WebSocket service.

#### Returns
A `Dictionary<string, bool>`. 

It represents a collection of pairs of a session ID and a value indicating whether a pong has been received from the client within a time. 

#### Exceptions
* `InvalidOperationException` The current state of the manager is not Start.

##### `public Dictionary< string, bool > ` [`Broadping`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1a6f38ac18a87bdc91c29448e2be2018a8)`(string message)` 

Sends a ping with *message*  to every client in the WebSocket service.

#### Returns
A `Dictionary<string, bool>`. 

It represents a collection of pairs of a session ID and a value indicating whether a pong has been received from the client within a time. 

#### Parameters
* `message` A string that represents the message to send. 

The size must be 125 bytes or less in UTF-8. 

#### Exceptions
* `InvalidOperationException` The current state of the manager is not Start. 

* `ArgumentException` *message*  could not be UTF-8-encoded. 

* `ArgumentOutOfRangeException` The size of *message*  is greater than 125 bytes.

##### `public void ` [`CloseSession`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1a7f2d797dcddf8c6a27093550fe97ff1f)`(string id)` 

Closes the specified session.

#### Parameters
* `id` A string that represents the ID of the session to close. 

#### Exceptions
* `ArgumentNullException` *id*  is `null`. 

* `ArgumentException` *id*  is an empty string. 

* `InvalidOperationException` The session could not be found.

##### `public void ` [`CloseSession`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1a4b34c43603f82e5b116e8ae843d88025)`(string id, ushort code, string reason)` 

Closes the specified session with *code*  and *reason* .

#### Parameters
* `id` A string that represents the ID of the session to close. 

* `code` A ushort that represents the status code indicating the reason for the close. 

The status codes are defined in  Section 7.4

of RFC 6455. 

* `reason` A string that represents the reason for the close. 

The size must be 123 bytes or less in UTF-8. 

#### Exceptions
* `ArgumentNullException` *id*  is `null`. 

* `ArgumentException` *id*  is an empty string. 

-or- 

*code*  is 1010 (mandatory extension). 

-or- 

*code*  is 1005 (no status) and there is *reason* . 

-or- 

*reason*  could not be UTF-8-encoded. 

* `InvalidOperationException` The session could not be found. 

* `ArgumentOutOfRangeException` *code*  is less than 1000 or greater than 4999. 

-or- 

The size of *reason*  is greater than 123 bytes.

##### `public void ` [`CloseSession`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1a5692e1609c2bae980d0baed58660d584)`(string id, ` [`CloseStatusCode`](WebSocketSharp.md)` code, string reason)` 

Closes the specified session with *code*  and *reason* .

#### Parameters
* `id` A string that represents the ID of the session to close. 

* `code` One of the CloseStatusCode enum values. 

It represents the status code indicating the reason for the close. 

* `reason` A string that represents the reason for the close. 

The size must be 123 bytes or less in UTF-8. 

#### Exceptions
* `ArgumentNullException` *id*  is `null`. 

* `ArgumentException` *id*  is an empty string. 

-or- 

*code*  is CloseStatusCode.MandatoryExtension. 

-or- 

*code*  is CloseStatusCode.NoStatus and there is *reason* . 

-or- 

*reason*  could not be UTF-8-encoded. 

* `InvalidOperationException` The session could not be found. 

* `ArgumentOutOfRangeException` The size of *reason*  is greater than 123 bytes.

##### `public bool ` [`PingTo`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1aa53f1ff2e1be8f054564c5917fd4a7a8)`(string id)` 

Sends a ping to the client using the specified session.

#### Returns
`true` if the send has done with no error and a pong has been received from the client within a time; otherwise, `false`. 

#### Parameters
* `id` A string that represents the ID of the session. 

#### Exceptions
* `ArgumentNullException` *id*  is `null`. 

* `ArgumentException` *id*  is an empty string. 

* `InvalidOperationException` The session could not be found.

##### `public bool ` [`PingTo`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1a02a6cbe48406b083254d3ffd2f68447c)`(string message, string id)` 

Sends a ping with *message*  to the client using the specified session.

#### Returns
`true` if the send has done with no error and a pong has been received from the client within a time; otherwise, `false`. 

#### Parameters
* `message` A string that represents the message to send. 

The size must be 125 bytes or less in UTF-8. 

* `id` A string that represents the ID of the session. 

#### Exceptions
* `ArgumentNullException` *id*  is `null`. 

* `ArgumentException` *id*  is an empty string. 

-or- 

*message*  could not be UTF-8-encoded. 

* `InvalidOperationException` The session could not be found. 

* `ArgumentOutOfRangeException` The size of *message*  is greater than 125 bytes.

##### `public void ` [`SendTo`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1a7fc48dc5bf3042d80f42b5b8518c6a77)`(byte[] data, string id)` 

Sends *data*  to the client using the specified session.

#### Parameters
* `data` An array of byte that represents the binary data to send. 

* `id` A string that represents the ID of the session. 

#### Exceptions
* `ArgumentNullException` *id*  is `null`. 

-or- 

*data*  is `null`. 

* `ArgumentException` *id*  is an empty string. 

* `InvalidOperationException` The session could not be found. 

-or- 

The current state of the WebSocket connection is not Open.

##### `public void ` [`SendTo`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1ad4dedaf27b37bd9bb41f2cfdfcaec9aa)`(string data, string id)` 

Sends *data*  to the client using the specified session.

#### Parameters
* `data` A string that represents the text data to send. 

* `id` A string that represents the ID of the session. 

#### Exceptions
* `ArgumentNullException` *id*  is `null`. 

-or- 

*data*  is `null`. 

* `ArgumentException` *id*  is an empty string. 

-or- 

*data*  could not be UTF-8-encoded. 

* `InvalidOperationException` The session could not be found. 

-or- 

The current state of the WebSocket connection is not Open.

##### `public void ` [`SendTo`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1a96fd7ef837298749cc6731b3e1829364)`(Stream stream, int length, string id)` 

Sends the data from *stream*  to the client using the specified session.

The data is sent as the binary data. 

#### Parameters
* `stream` A Stream instance from which to read the data to send. 

* `length` An int that specifies the number of bytes to send. 

* `id` A string that represents the ID of the session. 

#### Exceptions
* `ArgumentNullException` *id*  is `null`. 

-or- 

*stream*  is `null`. 

* `ArgumentException` *id*  is an empty string. 

-or- 

*stream*  cannot be read. 

-or- 

*length*  is less than 1. 

-or- 

No data could be read from *stream* . 

* `InvalidOperationException` The session could not be found. 

-or- 

The current state of the WebSocket connection is not Open.

##### `public void ` [`SendToAsync`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1a91ad85c95ed380ba98cd40928166d6d9)`(byte[] data, string id, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)`< bool > completed)` 

Sends *data*  asynchronously to the client using the specified session.

This method does not wait for the send to be complete. 

#### Parameters
* `data` An array of byte that represents the binary data to send. 

* `id` A string that represents the ID of the session. 

* `completed` An `Action<bool>` delegate or `null` if not needed. 

The delegate invokes the method called when the send is complete. 

`true` is passed to the method if the send has done with no error; otherwise, `false`. 

#### Exceptions
* `ArgumentNullException` *id*  is `null`. 

-or- 

*data*  is `null`. 

* `ArgumentException` *id*  is an empty string. 

* `InvalidOperationException` The session could not be found. 

-or- 

The current state of the WebSocket connection is not Open.

##### `public void ` [`SendToAsync`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1abee1ed00d68277a9da783d11986055ec)`(string data, string id, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)`< bool > completed)` 

Sends *data*  asynchronously to the client using the specified session.

This method does not wait for the send to be complete. 

#### Parameters
* `data` A string that represents the text data to send. 

* `id` A string that represents the ID of the session. 

* `completed` An `Action<bool>` delegate or `null` if not needed. 

The delegate invokes the method called when the send is complete. 

`true` is passed to the method if the send has done with no error; otherwise, `false`. 

#### Exceptions
* `ArgumentNullException` *id*  is `null`. 

-or- 

*data*  is `null`. 

* `ArgumentException` *id*  is an empty string. 

-or- 

*data*  could not be UTF-8-encoded. 

* `InvalidOperationException` The session could not be found. 

-or- 

The current state of the WebSocket connection is not Open.

##### `public void ` [`SendToAsync`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1ae001532c5574ee3504aabf6e81d76226)`(Stream stream, int length, string id, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)`< bool > completed)` 

Sends the data from *stream*  asynchronously to the client using the specified session.

The data is sent as the binary data. 

This method does not wait for the send to be complete. 

#### Parameters
* `stream` A Stream instance from which to read the data to send. 

* `length` An int that specifies the number of bytes to send. 

* `id` A string that represents the ID of the session. 

* `completed` An `Action<bool>` delegate or `null` if not needed. 

The delegate invokes the method called when the send is complete. 

`true` is passed to the method if the send has done with no error; otherwise, `false`. 

#### Exceptions
* `ArgumentNullException` *id*  is `null`. 

-or- 

*stream*  is `null`. 

* `ArgumentException` *id*  is an empty string. 

-or- 

*stream*  cannot be read. 

-or- 

*length*  is less than 1. 

-or- 

No data could be read from *stream* . 

* `InvalidOperationException` The session could not be found. 

-or- 

The current state of the WebSocket connection is not Open.

##### `public void ` [`Sweep`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1a948f644fec100a1ad661e30ff9f4a314)`()` 

Cleans up the inactive sessions in the WebSocket service.

##### `public bool ` [`TryGetSession`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1a521e17c6054dac38c184e024237c587b)`(string id, out ` [`IWebSocketSession`](WebSocketSharp--Server.md)` session)` 

Tries to get the session instance with *id* .

#### Returns
`true` if the session is successfully found; otherwise, `false`. 

#### Parameters
* `id` A string that represents the ID of the session to find. 

* `session` When this method returns, a IWebSocketSession instance or `null` if not found. 

The session instance provides the function to access the information in the session. 

#### Exceptions
* `ArgumentNullException` *id*  is `null`. 

* `ArgumentException` *id*  is an empty string.

##### `private volatile bool ` [`_clean`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1a12dfa42d0f87fc871d5d85bcd1627aeb) 

##### `private object ` [`_forSweep`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1a1c5101c9930ee22b59aa4854441aa009) 

##### `private ` [`Logger`](WebSocketSharp--Logger.md)` ` [`_log`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1ab09157ab30052b0f1bf60fe26410d6ee) 

##### `private Dictionary< string, ` [`IWebSocketSession`](WebSocketSharp--Server.md)` > ` [`_sessions`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1a3cd368b7e987d74a1342c3f5b25ab2d4) 

##### `private volatile ` [`ServerState`](WebSocketSharp--Server.md)` ` [`_state`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1a0ef0deff6fe7732149d2bcd773a64f28) 

##### `private volatile bool ` [`_sweeping`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1a06c33a07f6959f37b3fb6e89ce28dd83) 

##### `private System.Timers.Timer ` [`_sweepTimer`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1a1ac7edcca3acf15bffc7489f29d2d627) 

##### `private object ` [`_sync`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1adbb069fcd0e2b452bc3342bc00739ed8) 

##### `private TimeSpan ` [`_waitTime`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1aff6d565013f5a1afe6d5b94ee07b5454) 

##### `private void ` [`broadcast`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1a24675ceb7f198a2aababe824eccb7e73)`(` [`Opcode`](WebSocketSharp.md)` opcode, byte[] data, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)` completed)` 

##### `private void ` [`broadcast`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1a8ecd32e2431afbe6044b3400bd5c430f)`(` [`Opcode`](WebSocketSharp.md)` opcode, Stream stream, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)` completed)` 

##### `private void ` [`broadcastAsync`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1ac9014e9eaa1e94b08ac4e21a7ee2393e)`(` [`Opcode`](WebSocketSharp.md)` opcode, byte[] data, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)` completed)` 

##### `private void ` [`broadcastAsync`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1a45bd88460c7605fafea44ba473d3ab55)`(` [`Opcode`](WebSocketSharp.md)` opcode, Stream stream, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)` completed)` 

##### `private Dictionary< string, bool > ` [`broadping`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1a6d5265d35df0d418775c8e615b660d20)`(byte[] frameAsBytes)` 

##### `private bool ` [`canSet`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1a729ea85bb2548e8a7b5f70f75159b133)`(out string message)` 

##### `private void ` [`setSweepTimer`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1a2ffb610419cf5eafce04a46e65d55204)`(double interval)` 

##### `private void ` [`stop`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1a75dfa06184262c39a381d228ece12524)`(` [`PayloadData`](WebSocketSharp--PayloadData.md)` payloadData, bool send)` 

##### `private bool ` [`tryGetSession`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1a657a98b961e7583fbb2244451ba46128)`(string id, out ` [`IWebSocketSession`](WebSocketSharp--Server.md)` session)` 

##### `private static string ` [`createID`](#class_web_socket_sharp_1_1_server_1_1_web_socket_session_manager_1a7f9aacb66fc97c47e3c46351303468d5)`()` 

