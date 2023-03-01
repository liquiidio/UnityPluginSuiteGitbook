# class `WebSocketSharp::WebSocket` 

```
class WebSocketSharp::WebSocket
  : public IDisposable
```

Implements the WebSocket interface.

This class provides a set of methods and properties for two-way communication using the WebSocket protocol. 

The WebSocket protocol is defined in RFC 6455

.

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`package ` [`CookieCollection`](WebSocketSharp--Net--CookieCollection.md)` ` [`CookieCollection`](#class_web_socket_sharp_1_1_web_socket_1a95ed1a6e4459712765a1d7442be37a34) | 
`package Func< ` [`WebSocketContext`](WebSocketSharp--Net--WebSockets--WebSocketContext.md)`, string > ` [`CustomHandshakeRequestChecker`](#class_web_socket_sharp_1_1_web_socket_1a023d8ecbd0def8e40a96e5f0278ba819) | 
`package bool ` [`HasMessage`](#class_web_socket_sharp_1_1_web_socket_1a638a23a29314b991b41df591520476a7) | 
`package bool ` [`IgnoreExtensions`](#class_web_socket_sharp_1_1_web_socket_1a5c0fcaaf94c0198e772892949edde5ff) | 
`package bool ` [`IsConnected`](#class_web_socket_sharp_1_1_web_socket_1abac0113ff571c017320394966a1ae6d5) | 
`public ` [`CompressionMethod`](WebSocketSharp.md)` ` [`Compression`](#class_web_socket_sharp_1_1_web_socket_1a043d2d1807559a16c975b0ac1fe59a9a) | Gets or sets the compression method used to compress a message.
`public IEnumerable< ` [`Cookie`](WebSocketSharp--Net--Cookie.md)` > ` [`Cookies`](#class_web_socket_sharp_1_1_web_socket_1a3f79caadcbe3007128dad4c04dc872b5) | Gets the HTTP cookies included in the handshake request/response.
`public ` [`NetworkCredential`](WebSocketSharp--Net--NetworkCredential.md)` ` [`Credentials`](#class_web_socket_sharp_1_1_web_socket_1a391a62443fa52b56a03c7266bfaaa9aa) | Gets the credentials for the HTTP authentication (Basic/Digest).
`public bool ` [`EmitOnPing`](#class_web_socket_sharp_1_1_web_socket_1ab33fc86f77c2cf3f8b102569d28a2e16) | Gets or sets a value indicating whether a OnMessage event is emitted when a ping is received.
`public bool ` [`EnableRedirection`](#class_web_socket_sharp_1_1_web_socket_1a3d77f6ddef4930f45522b87e8a77ab60) | Gets or sets a value indicating whether the URL redirection for the handshake request is allowed.
`public string ` [`Extensions`](#class_web_socket_sharp_1_1_web_socket_1aa5030055ce14a53aeeb8b22cf96c25c3) | Gets the extensions selected by server.
`public bool ` [`IsAlive`](#class_web_socket_sharp_1_1_web_socket_1a2bdb54e111b7cfeed1d46b5a7ef64dbf) | Gets a value indicating whether the connection is alive.
`public bool ` [`IsSecure`](#class_web_socket_sharp_1_1_web_socket_1adb59d1044fe46ad2ddd774ccbc267db1) | Gets a value indicating whether a secure connection is used.
`public ` [`Logger`](WebSocketSharp--Logger.md)` ` [`Log`](#class_web_socket_sharp_1_1_web_socket_1af2ed886ec3d2b2fd42fd0c5dad2f8cc5) | Gets the logging function.
`public string ` [`Origin`](#class_web_socket_sharp_1_1_web_socket_1aee0af9beab44b0ab2a52a2fb79ef9516) | Gets or sets the value of the HTTP Origin header to send with the handshake request.
`public string ` [`Protocol`](#class_web_socket_sharp_1_1_web_socket_1a0dda9c70e5a498baaa1cd780236ce1a1) | Gets the name of subprotocol selected by the server.
`public ` [`WebSocketState`](WebSocketSharp.md)` ` [`ReadyState`](#class_web_socket_sharp_1_1_web_socket_1a868359fe9c1d2fbe95b9ec16b6923d67) | Gets the current state of the connection.
`public ` [`ClientSslConfiguration`](WebSocketSharp--Net--ClientSslConfiguration.md)` ` [`SslConfiguration`](#class_web_socket_sharp_1_1_web_socket_1af416992ee8cb495df0367770ca3dc5e6) | Gets the configuration for secure connection.
`public Uri ` [`Url`](#class_web_socket_sharp_1_1_web_socket_1a8228cbbd65e3f8ccba81b3176ac491ed) | Gets the URL to which to connect.
`public TimeSpan ` [`WaitTime`](#class_web_socket_sharp_1_1_web_socket_1ae01f8dab993779eaa79c449c045db7a8) | Gets or sets the time to wait for the response to the ping or close.
`public ` [`WebSocket`](#class_web_socket_sharp_1_1_web_socket_1a6c3712dfa969a4484452cafda910f943)`(string url, params string[] protocols)` | Initializes a new instance of the WebSocket class with *url* and optionally *protocols* .
`public void ` [`Accept`](#class_web_socket_sharp_1_1_web_socket_1a82b975e44d6e24f21a11d81bfee91a84)`()` | Accepts the handshake request.
`public void ` [`AcceptAsync`](#class_web_socket_sharp_1_1_web_socket_1ad377eade00599c7fb198e3108f9f3495)`()` | Accepts the handshake request asynchronously.
`public void ` [`Close`](#class_web_socket_sharp_1_1_web_socket_1a7f7a3199c392465d0767c6506c1af5b4)`()` | Closes the connection.
`public void ` [`Close`](#class_web_socket_sharp_1_1_web_socket_1ac2b43498b7462ab9f931250a30fdae15)`(ushort code)` | Closes the connection with the specified code.
`public void ` [`Close`](#class_web_socket_sharp_1_1_web_socket_1a8cb3d7251e9310bc5e09879415a7da34)`(` [`CloseStatusCode`](WebSocketSharp.md)` code)` | Closes the connection with the specified code.
`public void ` [`Close`](#class_web_socket_sharp_1_1_web_socket_1a755fd8c332cdaf681536ca5ed7fa7fdb)`(ushort code, string reason)` | Closes the connection with the specified code and reason.
`public void ` [`Close`](#class_web_socket_sharp_1_1_web_socket_1ad2d11ea3a240649899dacd660c64100c)`(` [`CloseStatusCode`](WebSocketSharp.md)` code, string reason)` | Closes the connection with the specified code and reason.
`public void ` [`CloseAsync`](#class_web_socket_sharp_1_1_web_socket_1a9b146b83101efc75fe45964459e054ce)`()` | Closes the connection asynchronously.
`public void ` [`CloseAsync`](#class_web_socket_sharp_1_1_web_socket_1a6fa73542c436aa306414fc7f56337676)`(ushort code)` | Closes the connection asynchronously with the specified code.
`public void ` [`CloseAsync`](#class_web_socket_sharp_1_1_web_socket_1a3d4bd9254e100f158b7e8e8fe7e291ab)`(` [`CloseStatusCode`](WebSocketSharp.md)` code)` | Closes the connection asynchronously with the specified code.
`public void ` [`CloseAsync`](#class_web_socket_sharp_1_1_web_socket_1ae4f0b83a46dec1a0b30034b0e948d593)`(ushort code, string reason)` | Closes the connection asynchronously with the specified code and reason.
`public void ` [`CloseAsync`](#class_web_socket_sharp_1_1_web_socket_1acf084a4255d196ef3ad90420ccaea2f3)`(` [`CloseStatusCode`](WebSocketSharp.md)` code, string reason)` | Closes the connection asynchronously with the specified code and reason.
`public void ` [`Connect`](#class_web_socket_sharp_1_1_web_socket_1a5b6b4e47c7e5a413015c702d9825734f)`()` | Establishes a connection.
`public void ` [`ConnectAsync`](#class_web_socket_sharp_1_1_web_socket_1a2431b06e2ee33acae51e8a7894ee58fd)`()` | Establishes a connection asynchronously.
`public bool ` [`Ping`](#class_web_socket_sharp_1_1_web_socket_1a24ce3b6d0c9139e53e07089971dc864c)`()` | Sends a ping using the WebSocket connection.
`public bool ` [`Ping`](#class_web_socket_sharp_1_1_web_socket_1acb6bd2b66f507e81f91ee61e690d417c)`(string message)` | Sends a ping with *message* using the WebSocket connection.
`public void ` [`Send`](#class_web_socket_sharp_1_1_web_socket_1aa826ba54ecf62a7df2cf50a0b93fd265)`(byte[] data)` | Sends the specified data using the WebSocket connection.
`public void ` [`Send`](#class_web_socket_sharp_1_1_web_socket_1a32497e3fd2eb87d1d3051448c2dd1cb9)`(FileInfo fileInfo)` | Sends the specified file using the WebSocket connection.
`public void ` [`Send`](#class_web_socket_sharp_1_1_web_socket_1ac3549c8cf5f93b620c35c63c877ee896)`(string data)` | Sends the specified data using the WebSocket connection.
`public void ` [`Send`](#class_web_socket_sharp_1_1_web_socket_1aa98fdf5984aeb6dd44bdc7539a6a8fa0)`(Stream stream, int length)` | Sends the data from the specified stream using the WebSocket connection.
`public void ` [`SendAsync`](#class_web_socket_sharp_1_1_web_socket_1adc823b289d11ac4e6ac7744be0363a9d)`(byte[] data, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)`< bool > completed)` | Sends the specified data asynchronously using the WebSocket connection.
`public void ` [`SendAsync`](#class_web_socket_sharp_1_1_web_socket_1a4fbe47aee3ab33fc8c0a55388495608f)`(FileInfo fileInfo, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)`< bool > completed)` | Sends the specified file asynchronously using the WebSocket connection.
`public void ` [`SendAsync`](#class_web_socket_sharp_1_1_web_socket_1ae75cfc2f9c0c707bb4832bface2e1d48)`(string data, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)`< bool > completed)` | Sends the specified data asynchronously using the WebSocket connection.
`public void ` [`SendAsync`](#class_web_socket_sharp_1_1_web_socket_1aaef4fdb5c4b2e11d3f031c49241b7b51)`(Stream stream, int length, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)`< bool > completed)` | Sends the data from the specified stream asynchronously using the WebSocket connection.
`public void ` [`SetCookie`](#class_web_socket_sharp_1_1_web_socket_1aebf7816b302fd17dff92187e8ae2f27a)`(` [`Cookie`](WebSocketSharp--Net--Cookie.md)` cookie)` | Sets an HTTP cookie to send with the handshake request.
`public void ` [`SetCredentials`](#class_web_socket_sharp_1_1_web_socket_1ae6e3a8b053d753947db3c03c870b1405)`(string username, string password, bool preAuth)` | Sets the credentials for the HTTP authentication (Basic/Digest).
`public void ` [`SetProxy`](#class_web_socket_sharp_1_1_web_socket_1a1238de28fb663f2653de05812aaa89b3)`(string url, string username, string password)` | Sets the URL of the HTTP proxy server through which to connect and the credentials for the HTTP proxy authentication (Basic/Digest).
`private ` [`AuthenticationChallenge`](WebSocketSharp--Net--AuthenticationChallenge.md)` ` [`_authChallenge`](#class_web_socket_sharp_1_1_web_socket_1a106a7a79b7984ce1aadab37ad144076e) | 
`private string ` [`_base64Key`](#class_web_socket_sharp_1_1_web_socket_1a176b8baed7053aa466dc038791113e57) | 
`private bool ` [`_client`](#class_web_socket_sharp_1_1_web_socket_1a01b67b1dc268e5be557e1c101324f6d2) | 
`private ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)` ` [`_closeContext`](#class_web_socket_sharp_1_1_web_socket_1a03f9e37a2ad231b7523eb24f89df169e) | 
`private ` [`CompressionMethod`](WebSocketSharp.md)` ` [`_compression`](#class_web_socket_sharp_1_1_web_socket_1ad555ae5cd6fe8323472786ed031c998f) | 
`private ` [`WebSocketContext`](WebSocketSharp--Net--WebSockets--WebSocketContext.md)` ` [`_context`](#class_web_socket_sharp_1_1_web_socket_1a816ceeb71f3ec93039d6323396ba0da3) | 
`private ` [`CookieCollection`](WebSocketSharp--Net--CookieCollection.md)` ` [`_cookies`](#class_web_socket_sharp_1_1_web_socket_1ae2054e3379559490b8e8704754ae0eb0) | 
`private ` [`NetworkCredential`](WebSocketSharp--Net--NetworkCredential.md)` ` [`_credentials`](#class_web_socket_sharp_1_1_web_socket_1a407195013251672f90ff35301df110db) | 
`private bool ` [`_emitOnPing`](#class_web_socket_sharp_1_1_web_socket_1a76edee6035be0274acf14d5ce879a1e1) | 
`private bool ` [`_enableRedirection`](#class_web_socket_sharp_1_1_web_socket_1afd2de7b3765bd0450ee9d6c9c45ff636) | 
`private string ` [`_extensions`](#class_web_socket_sharp_1_1_web_socket_1a40021ce4cf931a6679907b82aa711726) | 
`private bool ` [`_extensionsRequested`](#class_web_socket_sharp_1_1_web_socket_1adf517f6c4c1f6c6b89337bc0db795869) | 
`private object ` [`_forMessageEventQueue`](#class_web_socket_sharp_1_1_web_socket_1a176a2da998f6e25c8207d692c960c2c4) | 
`private object ` [`_forPing`](#class_web_socket_sharp_1_1_web_socket_1ae6d7d8acfd68377508fc5a1597260728) | 
`private object ` [`_forSend`](#class_web_socket_sharp_1_1_web_socket_1a0070032c1f6a19cdd18897ecc7f4fa2e) | 
`private object ` [`_forState`](#class_web_socket_sharp_1_1_web_socket_1a99429982a354db10e5a37c22bf2b98c4) | 
`private MemoryStream ` [`_fragmentsBuffer`](#class_web_socket_sharp_1_1_web_socket_1acd379c10d911e0a1c7aa64e2c45ec96f) | 
`private bool ` [`_fragmentsCompressed`](#class_web_socket_sharp_1_1_web_socket_1ab4873eacb18f4c3fb45cdf43a29039b6) | 
`private ` [`Opcode`](WebSocketSharp.md)` ` [`_fragmentsOpcode`](#class_web_socket_sharp_1_1_web_socket_1a4b532bf7bd344319b9eaba6acfacd9b7) | 
`private Func< ` [`WebSocketContext`](WebSocketSharp--Net--WebSockets--WebSocketContext.md)`, string > ` [`_handshakeRequestChecker`](#class_web_socket_sharp_1_1_web_socket_1a6a51c8e83017953e513e70efd5c4ed92) | 
`private bool ` [`_ignoreExtensions`](#class_web_socket_sharp_1_1_web_socket_1aaa6b062ecf2c0e5631126d19e63232dc) | 
`private bool ` [`_inContinuation`](#class_web_socket_sharp_1_1_web_socket_1a5e156e843e0ac1bebc550840c265126b) | 
`private volatile bool ` [`_inMessage`](#class_web_socket_sharp_1_1_web_socket_1aa00f59420f5f3a2979676979c9528b16) | 
`private volatile ` [`Logger`](WebSocketSharp--Logger.md)` ` [`_logger`](#class_web_socket_sharp_1_1_web_socket_1aa9e8e1e5a50a812b6622c36b4c72537f) | 
`private ` [`Action](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)< [MessageEventArgs`](WebSocketSharp--MessageEventArgs.md)` > ` [`_message`](#class_web_socket_sharp_1_1_web_socket_1a0dd508694ae805621abe136374989fa7) | 
`private Queue< ` [`MessageEventArgs`](WebSocketSharp--MessageEventArgs.md)` > ` [`_messageEventQueue`](#class_web_socket_sharp_1_1_web_socket_1a3b9f66831321539f75180a0ecdc20c39) | 
`private uint ` [`_nonceCount`](#class_web_socket_sharp_1_1_web_socket_1a94db75d7371c21043430a471dffd3d45) | 
`private string ` [`_origin`](#class_web_socket_sharp_1_1_web_socket_1a103f18dc3009badb14b25480037f0815) | 
`private ManualResetEvent ` [`_pongReceived`](#class_web_socket_sharp_1_1_web_socket_1a8a0ca830ec222508948269f0accb4b35) | 
`private bool ` [`_preAuth`](#class_web_socket_sharp_1_1_web_socket_1ae8801eb7701de955da0880f490ad924c) | 
`private string ` [`_protocol`](#class_web_socket_sharp_1_1_web_socket_1ad984ec662a4971f019cea27a0fcb4c68) | 
`private string[] ` [`_protocols`](#class_web_socket_sharp_1_1_web_socket_1a735b0cbed8e1c0fc22269986c6a1f3dc) | 
`private bool ` [`_protocolsRequested`](#class_web_socket_sharp_1_1_web_socket_1a94a4ade7664db0d742981d37879e5d41) | 
`private ` [`NetworkCredential`](WebSocketSharp--Net--NetworkCredential.md)` ` [`_proxyCredentials`](#class_web_socket_sharp_1_1_web_socket_1ae1dc90d1c3e1c0acde13484633348eff) | 
`private Uri ` [`_proxyUri`](#class_web_socket_sharp_1_1_web_socket_1a578ddd6ba0a22637a03b4deb4b385615) | 
`private volatile ` [`WebSocketState`](WebSocketSharp.md)` ` [`_readyState`](#class_web_socket_sharp_1_1_web_socket_1aaee3f28c178c03d149781ee55c448e46) | 
`private ManualResetEvent ` [`_receivingExited`](#class_web_socket_sharp_1_1_web_socket_1a0cf5ded175f62b35b3a0d15cf367a007) | 
`private int ` [`_retryCountForConnect`](#class_web_socket_sharp_1_1_web_socket_1a17b6b1910ec88da03e62180c442165ea) | 
`private bool ` [`_secure`](#class_web_socket_sharp_1_1_web_socket_1a2f7b5b309c5830b8532939ca02946b44) | 
`private ` [`ClientSslConfiguration`](WebSocketSharp--Net--ClientSslConfiguration.md)` ` [`_sslConfig`](#class_web_socket_sharp_1_1_web_socket_1ab1e9b066883f0f8dd77aee498d23a40a) | 
`private Stream ` [`_stream`](#class_web_socket_sharp_1_1_web_socket_1ae5401654b26ad72d9da131e0a3db7eb8) | 
`private TcpClient ` [`_tcpClient`](#class_web_socket_sharp_1_1_web_socket_1a90eb17ad2d30dea9b36901e5dbb080dc) | 
`private Uri ` [`_uri`](#class_web_socket_sharp_1_1_web_socket_1a80518856549440f2fd5d4b4a681b4767) | 
`private TimeSpan ` [`_waitTime`](#class_web_socket_sharp_1_1_web_socket_1aff6d565013f5a1afe6d5b94ee07b5454) | 
`private bool ` [`accept`](#class_web_socket_sharp_1_1_web_socket_1a88a977a48a4980f337cf41e889a56afa)`()` | 
`private bool ` [`acceptHandshake`](#class_web_socket_sharp_1_1_web_socket_1ac91fd609727b087da8953534e1531c4e)`()` | 
`private bool ` [`canSet`](#class_web_socket_sharp_1_1_web_socket_1a729ea85bb2548e8a7b5f70f75159b133)`(out string message)` | 
`private bool ` [`checkHandshakeRequest`](#class_web_socket_sharp_1_1_web_socket_1a8d602a7c1ae13eec49b45639a4d06ee7)`(` [`WebSocketContext`](WebSocketSharp--Net--WebSockets--WebSocketContext.md)` context, out string message)` | 
`private bool ` [`checkHandshakeResponse`](#class_web_socket_sharp_1_1_web_socket_1a955b3a7bfabc569442026d0cc8d280cb)`(` [`HttpResponse`](WebSocketSharp--HttpResponse.md)` response, out string message)` | 
`private bool ` [`checkReceivedFrame`](#class_web_socket_sharp_1_1_web_socket_1ad124fa012efdd12ff3fb48dc891eb6f5)`(` [`WebSocketFrame`](WebSocketSharp--WebSocketFrame.md)` frame, out string message)` | 
`private void ` [`close`](#class_web_socket_sharp_1_1_web_socket_1a3bd770627ba58dc3a898d15908185552)`(ushort code, string reason)` | 
`private void ` [`close`](#class_web_socket_sharp_1_1_web_socket_1a87cc490498df87630b87d062f281f2bb)`(` [`PayloadData`](WebSocketSharp--PayloadData.md)` payloadData, bool send, bool receive, bool received)` | 
`private void ` [`closeAsync`](#class_web_socket_sharp_1_1_web_socket_1a2dbd9ef9f8949b8b01e6414f74708207)`(ushort code, string reason)` | 
`private void ` [`closeAsync`](#class_web_socket_sharp_1_1_web_socket_1a9485e8101259ccf8f872b1600030142e)`(` [`PayloadData`](WebSocketSharp--PayloadData.md)` payloadData, bool send, bool receive, bool received)` | 
`private bool ` [`closeHandshake`](#class_web_socket_sharp_1_1_web_socket_1aa39c91c8259cae1b13151dc6fda4d599)`(byte[] frameAsBytes, bool receive, bool received)` | 
`private bool ` [`closeHandshake`](#class_web_socket_sharp_1_1_web_socket_1a709b48d5b5323bf9b38f08c7f4ecf095)`(` [`PayloadData`](WebSocketSharp--PayloadData.md)` payloadData, bool send, bool receive, bool received)` | 
`private bool ` [`connect`](#class_web_socket_sharp_1_1_web_socket_1aa0a57e883c6c9fc19e62a609d967be9c)`()` | 
`private string ` [`createExtensions`](#class_web_socket_sharp_1_1_web_socket_1a8e484ded681920bfe82dcbbcaef37e9b)`()` | 
`private ` [`HttpResponse`](WebSocketSharp--HttpResponse.md)` ` [`createHandshakeFailureResponse`](#class_web_socket_sharp_1_1_web_socket_1a9a1984992a0f1cdc30732f64ce7d2ac4)`(` [`HttpStatusCode`](WebSocketSharp--Net.md)` code)` | 
`private ` [`HttpRequest`](WebSocketSharp--HttpRequest.md)` ` [`createHandshakeRequest`](#class_web_socket_sharp_1_1_web_socket_1a88f85a0265c260340479e0958827ab9b)`()` | 
`private ` [`HttpResponse`](WebSocketSharp--HttpResponse.md)` ` [`createHandshakeResponse`](#class_web_socket_sharp_1_1_web_socket_1a746282c95881c257af1abb03a6718dc8)`()` | 
`private bool ` [`customCheckHandshakeRequest`](#class_web_socket_sharp_1_1_web_socket_1a2561be3cf9e0366c9dfdda31daa5c09b)`(` [`WebSocketContext`](WebSocketSharp--Net--WebSockets--WebSocketContext.md)` context, out string message)` | 
`private ` [`MessageEventArgs`](WebSocketSharp--MessageEventArgs.md)` ` [`dequeueFromMessageEventQueue`](#class_web_socket_sharp_1_1_web_socket_1a3f7277570e5c47d04b26812bcb73fe9e)`()` | 
`private void ` [`doHandshake`](#class_web_socket_sharp_1_1_web_socket_1ad29764e5418e50470ad97ad22fb023f1)`()` | 
`private void ` [`enqueueToMessageEventQueue`](#class_web_socket_sharp_1_1_web_socket_1a1b62d31160cd60e000e690c32a469242)`(` [`MessageEventArgs`](WebSocketSharp--MessageEventArgs.md)` e)` | 
`private void ` [`error`](#class_web_socket_sharp_1_1_web_socket_1af4eb8e693d7e8d0c58b2a8edc2b54ac2)`(string message, Exception exception)` | 
`private void ` [`fatal`](#class_web_socket_sharp_1_1_web_socket_1aa318a7d65f90a4625a789480c16b7b0a)`(string message, Exception exception)` | 
`private void ` [`fatal`](#class_web_socket_sharp_1_1_web_socket_1a67a4cb57552a4c9c32ca808adaef7ea3)`(string message, ushort code)` | 
`private void ` [`fatal`](#class_web_socket_sharp_1_1_web_socket_1a7c0ffe110c51bbcb4eafd43ec01042e4)`(string message, ` [`CloseStatusCode`](WebSocketSharp.md)` code)` | 
`private ` [`ClientSslConfiguration`](WebSocketSharp--Net--ClientSslConfiguration.md)` ` [`getSslConfiguration`](#class_web_socket_sharp_1_1_web_socket_1acfae70861749a184f6e763974ec438e2)`()` | 
`private void ` [`init`](#class_web_socket_sharp_1_1_web_socket_1a02fd73d861ef2e4aabb38c0c9ff82947)`()` | 
`private void ` [`message`](#class_web_socket_sharp_1_1_web_socket_1a137d78a01e63d3b66d1b2ed0de0f4c4c)`()` | 
`private void ` [`messagec`](#class_web_socket_sharp_1_1_web_socket_1a7e35e38f50b6cb8157d8cbb829b853b7)`(` [`MessageEventArgs`](WebSocketSharp--MessageEventArgs.md)` e)` | 
`private void ` [`messages`](#class_web_socket_sharp_1_1_web_socket_1a83f52d3db2ef69f5bba3bc15f4ade975)`(` [`MessageEventArgs`](WebSocketSharp--MessageEventArgs.md)` e)` | 
`private void ` [`open`](#class_web_socket_sharp_1_1_web_socket_1a9e8555112049fc2b4945120b3c45f8ab)`()` | 
`private bool ` [`ping`](#class_web_socket_sharp_1_1_web_socket_1aa953583b1b6ba6cb36cb5c0a727ba8a1)`(byte[] data)` | 
`private bool ` [`processCloseFrame`](#class_web_socket_sharp_1_1_web_socket_1afa634ae55e6e2e73021d77dc6b10dd75)`(` [`WebSocketFrame`](WebSocketSharp--WebSocketFrame.md)` frame)` | 
`private void ` [`processCookies`](#class_web_socket_sharp_1_1_web_socket_1a898c7fad5d852c52cfc1b5c8866ea624)`(` [`CookieCollection`](WebSocketSharp--Net--CookieCollection.md)` cookies)` | 
`private bool ` [`processDataFrame`](#class_web_socket_sharp_1_1_web_socket_1ad849f6fd956a4fefdd9a8885316664ed)`(` [`WebSocketFrame`](WebSocketSharp--WebSocketFrame.md)` frame)` | 
`private bool ` [`processFragmentFrame`](#class_web_socket_sharp_1_1_web_socket_1aaa2af87494e4d4106a68eb72bea1d965)`(` [`WebSocketFrame`](WebSocketSharp--WebSocketFrame.md)` frame)` | 
`private bool ` [`processPingFrame`](#class_web_socket_sharp_1_1_web_socket_1a407805ce5d55a7bfc71fa90f69222096)`(` [`WebSocketFrame`](WebSocketSharp--WebSocketFrame.md)` frame)` | 
`private bool ` [`processPongFrame`](#class_web_socket_sharp_1_1_web_socket_1ab1da2b0eae1b7761364926e382e0d3d7)`(` [`WebSocketFrame`](WebSocketSharp--WebSocketFrame.md)` frame)` | 
`private bool ` [`processReceivedFrame`](#class_web_socket_sharp_1_1_web_socket_1a5bcbc0cb1b8b9089dfb454f9e5563e6d)`(` [`WebSocketFrame`](WebSocketSharp--WebSocketFrame.md)` frame)` | 
`private void ` [`processSecWebSocketExtensionsClientHeader`](#class_web_socket_sharp_1_1_web_socket_1a79041761a696299ce047c4726c5c8649)`(string value)` | 
`private void ` [`processSecWebSocketExtensionsServerHeader`](#class_web_socket_sharp_1_1_web_socket_1aa6595abb981503678a0b4f5c6211e265)`(string value)` | 
`private void ` [`processSecWebSocketProtocolClientHeader`](#class_web_socket_sharp_1_1_web_socket_1a69189464b89f8b9a2f7bc05134ae1a36)`(IEnumerable< string > values)` | 
`private bool ` [`processUnsupportedFrame`](#class_web_socket_sharp_1_1_web_socket_1a82829e6eed00af69e8ad5d0ad4e58729)`(` [`WebSocketFrame`](WebSocketSharp--WebSocketFrame.md)` frame)` | 
`private void ` [`refuseHandshake`](#class_web_socket_sharp_1_1_web_socket_1aca245c8e33ee3046974aa5c6da5dfed6)`(` [`CloseStatusCode`](WebSocketSharp.md)` code, string reason)` | 
`private void ` [`releaseClientResources`](#class_web_socket_sharp_1_1_web_socket_1a89420822ca5a6c0e6e277f084887f8f2)`()` | 
`private void ` [`releaseCommonResources`](#class_web_socket_sharp_1_1_web_socket_1afb84a74c6bb13348e097927e70a75d3a)`()` | 
`private void ` [`releaseResources`](#class_web_socket_sharp_1_1_web_socket_1a631d78806ec72c285cd1fff6f5afde13)`()` | 
`private void ` [`releaseServerResources`](#class_web_socket_sharp_1_1_web_socket_1a84f01e3854ad45bcdfdd42f5cae5d6d3)`()` | 
`private bool ` [`send`](#class_web_socket_sharp_1_1_web_socket_1a41de76e041a1b4576b0a8a9a097c0eb8)`(` [`Opcode`](WebSocketSharp.md)` opcode, Stream stream)` | 
`private bool ` [`send`](#class_web_socket_sharp_1_1_web_socket_1a691369ea736837730f027b4887442bb1)`(` [`Opcode`](WebSocketSharp.md)` opcode, Stream stream, bool compressed)` | 
`private bool ` [`send`](#class_web_socket_sharp_1_1_web_socket_1a920c2e763845fc66ef7ede0deebe75fb)`(` [`Fin`](WebSocketSharp.md)` fin, ` [`Opcode`](WebSocketSharp.md)` opcode, byte[] data, bool compressed)` | 
`private void ` [`sendAsync`](#class_web_socket_sharp_1_1_web_socket_1a51f0cf0eb7189687214e5b09f5b582c0)`(` [`Opcode`](WebSocketSharp.md)` opcode, Stream stream, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)`< bool > completed)` | 
`private bool ` [`sendBytes`](#class_web_socket_sharp_1_1_web_socket_1ac1625387556c92f6faf47f5f16e7452d)`(byte[] bytes)` | 
`private ` [`HttpResponse`](WebSocketSharp--HttpResponse.md)` ` [`sendHandshakeRequest`](#class_web_socket_sharp_1_1_web_socket_1ab7955004a263836896b00edbc1ba7fab)`()` | 
`private ` [`HttpResponse`](WebSocketSharp--HttpResponse.md)` ` [`sendHttpRequest`](#class_web_socket_sharp_1_1_web_socket_1aae7f1d804fe42999e049aee188879afd)`(` [`HttpRequest`](WebSocketSharp--HttpRequest.md)` request, int millisecondsTimeout)` | 
`private bool ` [`sendHttpResponse`](#class_web_socket_sharp_1_1_web_socket_1a7afb144fb354dc7a30380a333c2cb2e3)`(` [`HttpResponse`](WebSocketSharp--HttpResponse.md)` response)` | 
`private void ` [`sendProxyConnectRequest`](#class_web_socket_sharp_1_1_web_socket_1a0b5b763bb0c37f066880def4ad3ce055)`()` | 
`private void ` [`setClientStream`](#class_web_socket_sharp_1_1_web_socket_1aaad9c1417ba8e81afbc6aa8e96dd9b8d)`()` | 
`private void ` [`startReceiving`](#class_web_socket_sharp_1_1_web_socket_1a95e75d300547b71b3cc33d6e02f7a475)`()` | 
`private bool ` [`validateSecWebSocketAcceptHeader`](#class_web_socket_sharp_1_1_web_socket_1ad6b37153aa11b0eee2c043e080307f8a)`(string value)` | 
`private bool ` [`validateSecWebSocketExtensionsServerHeader`](#class_web_socket_sharp_1_1_web_socket_1ad64e160278d51e798829c12056e4e649)`(string value)` | 
`private bool ` [`validateSecWebSocketProtocolServerHeader`](#class_web_socket_sharp_1_1_web_socket_1aaa91a318e2a8072cc2a23174fb667b9f)`(string value)` | 
`private bool ` [`validateSecWebSocketVersionServerHeader`](#class_web_socket_sharp_1_1_web_socket_1a99626455e68da69b487658d1d0d5855f)`(string value)` | 
`private void IDisposable. ` [`Dispose`](#class_web_socket_sharp_1_1_web_socket_1a44dd5de4474284f22b70c3e0fbdc07f4)`()` | Closes the connection and releases all associated resources.
`private static static ` [`WebSocket`](#class_web_socket_sharp_1_1_web_socket_1a236bbe6b3b1d1d8ce39bccf7def48174)`()` | 
`private static bool ` [`checkProtocols`](#class_web_socket_sharp_1_1_web_socket_1a3de831cbb69869b04d305a8b507e171f)`(string[] protocols, out string message)` | 

## Members

##### `package ` [`CookieCollection`](WebSocketSharp--Net--CookieCollection.md)` ` [`CookieCollection`](#class_web_socket_sharp_1_1_web_socket_1a95ed1a6e4459712765a1d7442be37a34) 

##### `package Func< ` [`WebSocketContext`](WebSocketSharp--Net--WebSockets--WebSocketContext.md)`, string > ` [`CustomHandshakeRequestChecker`](#class_web_socket_sharp_1_1_web_socket_1a023d8ecbd0def8e40a96e5f0278ba819) 

##### `package bool ` [`HasMessage`](#class_web_socket_sharp_1_1_web_socket_1a638a23a29314b991b41df591520476a7) 

##### `package bool ` [`IgnoreExtensions`](#class_web_socket_sharp_1_1_web_socket_1a5c0fcaaf94c0198e772892949edde5ff) 

##### `package bool ` [`IsConnected`](#class_web_socket_sharp_1_1_web_socket_1abac0113ff571c017320394966a1ae6d5) 

##### `public ` [`CompressionMethod`](WebSocketSharp.md)` ` [`Compression`](#class_web_socket_sharp_1_1_web_socket_1a043d2d1807559a16c975b0ac1fe59a9a) 

Gets or sets the compression method used to compress a message.

The set operation does nothing if the connection has already been established or it is closing. 

One of the CompressionMethod enum values. 

It specifies the compression method used to compress a message. 

The default value is CompressionMethod.None. 

#### Exceptions
* `InvalidOperationException` The set operation is not available if this instance is not a client.

##### `public IEnumerable< ` [`Cookie`](WebSocketSharp--Net--Cookie.md)` > ` [`Cookies`](#class_web_socket_sharp_1_1_web_socket_1a3f79caadcbe3007128dad4c04dc872b5) 

Gets the HTTP cookies included in the handshake request/response.

An T:System.Collections.Generic.IEnumerable<WebSocketSharp.Net.Cookie> instance. 

It provides an enumerator which supports the iteration over the collection of the cookies.

##### `public ` [`NetworkCredential`](WebSocketSharp--Net--NetworkCredential.md)` ` [`Credentials`](#class_web_socket_sharp_1_1_web_socket_1a391a62443fa52b56a03c7266bfaaa9aa) 

Gets the credentials for the HTTP authentication (Basic/Digest).

A NetworkCredential that represents the credentials used to authenticate the client. 

The default value is `null`.

##### `public bool ` [`EmitOnPing`](#class_web_socket_sharp_1_1_web_socket_1ab33fc86f77c2cf3f8b102569d28a2e16) 

Gets or sets a value indicating whether a OnMessage event is emitted when a ping is received.

`true` if this instance emits a OnMessage event when receives a ping; otherwise, `false`. 

The default value is `false`.

##### `public bool ` [`EnableRedirection`](#class_web_socket_sharp_1_1_web_socket_1a3d77f6ddef4930f45522b87e8a77ab60) 

Gets or sets a value indicating whether the URL redirection for the handshake request is allowed.

The set operation does nothing if the connection has already been established or it is closing. 

`true` if this instance allows the URL redirection for the handshake request; otherwise, `false`. 

The default value is `false`. 

#### Exceptions
* `InvalidOperationException` The set operation is not available if this instance is not a client.

##### `public string ` [`Extensions`](#class_web_socket_sharp_1_1_web_socket_1aa5030055ce14a53aeeb8b22cf96c25c3) 

Gets the extensions selected by server.

A string that will be a list of the extensions negotiated between client and server, or an empty string if not specified or selected.

##### `public bool ` [`IsAlive`](#class_web_socket_sharp_1_1_web_socket_1a2bdb54e111b7cfeed1d46b5a7ef64dbf) 

Gets a value indicating whether the connection is alive.

The get operation returns the value by using a ping/pong if the current state of the connection is Open. 

`true` if the connection is alive; otherwise, `false`.

##### `public bool ` [`IsSecure`](#class_web_socket_sharp_1_1_web_socket_1adb59d1044fe46ad2ddd774ccbc267db1) 

Gets a value indicating whether a secure connection is used.

`true` if this instance uses a secure connection; otherwise, `false`.

##### `public ` [`Logger`](WebSocketSharp--Logger.md)` ` [`Log`](#class_web_socket_sharp_1_1_web_socket_1af2ed886ec3d2b2fd42fd0c5dad2f8cc5) 

Gets the logging function.

The default logging level is LogLevel.Error. 

A Logger that provides the logging function.

##### `public string ` [`Origin`](#class_web_socket_sharp_1_1_web_socket_1aee0af9beab44b0ab2a52a2fb79ef9516) 

Gets or sets the value of the HTTP Origin header to send with the handshake request.

The HTTP Origin header is defined in  Section 7 of RFC 6454

. 

This instance sends the Origin header if this property has any. 

The set operation does nothing if the connection has already been established or it is closing. 

A string that represents the value of the Origin header to send. 

The syntax is <scheme>://<host>[:<port>]. 

The default value is `null`. 

#### Exceptions
* `InvalidOperationException` The set operation is not available if this instance is not a client. 

* `ArgumentException` The value specified for a set operation is not an absolute URI string. 

-or- 

The value specified for a set operation includes the path segments.

##### `public string ` [`Protocol`](#class_web_socket_sharp_1_1_web_socket_1a0dda9c70e5a498baaa1cd780236ce1a1) 

Gets the name of subprotocol selected by the server.

A string that will be one of the names of subprotocols specified by client. 

An empty string if not specified or selected.

##### `public ` [`WebSocketState`](WebSocketSharp.md)` ` [`ReadyState`](#class_web_socket_sharp_1_1_web_socket_1a868359fe9c1d2fbe95b9ec16b6923d67) 

Gets the current state of the connection.

One of the WebSocketState enum values. 

It indicates the current state of the connection. 

The default value is WebSocketState.Connecting.

##### `public ` [`ClientSslConfiguration`](WebSocketSharp--Net--ClientSslConfiguration.md)` ` [`SslConfiguration`](#class_web_socket_sharp_1_1_web_socket_1af416992ee8cb495df0367770ca3dc5e6) 

Gets the configuration for secure connection.

This configuration will be referenced when attempts to connect, so it must be configured before any connect method is called. 

A ClientSslConfiguration that represents the configuration used to establish a secure connection. 

#### Exceptions
* `InvalidOperationException` This instance is not a client. 

This instance does not use a secure connection.

##### `public Uri ` [`Url`](#class_web_socket_sharp_1_1_web_socket_1a8228cbbd65e3f8ccba81b3176ac491ed) 

Gets the URL to which to connect.

A Uri that represents the URL to which to connect.

##### `public TimeSpan ` [`WaitTime`](#class_web_socket_sharp_1_1_web_socket_1ae01f8dab993779eaa79c449c045db7a8) 

Gets or sets the time to wait for the response to the ping or close.

The set operation does nothing if the connection has already been established or it is closing. 

A TimeSpan to wait for the response. 

The default value is the same as 5 seconds if this instance is a client. 

#### Exceptions
* `ArgumentOutOfRangeException` The value specified for a set operation is zero or less.

##### `public ` [`WebSocket`](#class_web_socket_sharp_1_1_web_socket_1a6c3712dfa969a4484452cafda910f943)`(string url, params string[] protocols)` 

Initializes a new instance of the WebSocket class with *url*  and optionally *protocols* .

#### Parameters
* `url` A string that specifies the URL to which to connect. 

The scheme of the URL must be ws or wss. 

The new instance uses a secure connection if the scheme is wss. 

* `protocols` An array of string that specifies the names of the subprotocols if necessary. 

Each value of the array must be a token defined in  RFC 2616

. 

#### Exceptions
* `ArgumentNullException` *url*  is `null`. 

* `ArgumentException` *url*  is an empty string. 

-or- 

*url*  is an invalid WebSocket URL string. 

-or- 

*protocols*  contains a value that is not a token. 

-or- 

*protocols*  contains a value twice.

##### `public void ` [`Accept`](#class_web_socket_sharp_1_1_web_socket_1a82b975e44d6e24f21a11d81bfee91a84)`()` 

Accepts the handshake request.

This method does nothing if the handshake request has already been accepted. 

#### Exceptions
* `InvalidOperationException` This instance is a client. 

-or- 

The close process is in progress. 

-or- 

The connection has already been closed.

##### `public void ` [`AcceptAsync`](#class_web_socket_sharp_1_1_web_socket_1ad377eade00599c7fb198e3108f9f3495)`()` 

Accepts the handshake request asynchronously.

This method does not wait for the accept process to be complete. 

This method does nothing if the handshake request has already been accepted. 

#### Exceptions
* `InvalidOperationException` This instance is a client. 

-or- 

The close process is in progress. 

-or- 

The connection has already been closed.

##### `public void ` [`Close`](#class_web_socket_sharp_1_1_web_socket_1a7f7a3199c392465d0767c6506c1af5b4)`()` 

Closes the connection.

This method does nothing if the current state of the connection is Closing or Closed.

##### `public void ` [`Close`](#class_web_socket_sharp_1_1_web_socket_1ac2b43498b7462ab9f931250a30fdae15)`(ushort code)` 

Closes the connection with the specified code.

This method does nothing if the current state of the connection is Closing or Closed. 

#### Parameters
* `code` A ushort that represents the status code indicating the reason for the close. 

The status codes are defined in  Section 7.4

of RFC 6455. 

#### Exceptions
* `ArgumentOutOfRangeException` *code*  is less than 1000 or greater than 4999. 

* `ArgumentException` *code*  is 1011 (server error). It cannot be used by clients. 

-or- 

*code*  is 1010 (mandatory extension). It cannot be used by servers.

##### `public void ` [`Close`](#class_web_socket_sharp_1_1_web_socket_1a8cb3d7251e9310bc5e09879415a7da34)`(` [`CloseStatusCode`](WebSocketSharp.md)` code)` 

Closes the connection with the specified code.

This method does nothing if the current state of the connection is Closing or Closed. 

#### Parameters
* `code` One of the CloseStatusCode enum values. 

It represents the status code indicating the reason for the close. 

#### Exceptions
* `ArgumentException` *code*  is CloseStatusCode.ServerError. It cannot be used by clients. 

-or- 

*code*  is CloseStatusCode.MandatoryExtension. It cannot be used by servers.

##### `public void ` [`Close`](#class_web_socket_sharp_1_1_web_socket_1a755fd8c332cdaf681536ca5ed7fa7fdb)`(ushort code, string reason)` 

Closes the connection with the specified code and reason.

This method does nothing if the current state of the connection is Closing or Closed. 

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

* `ArgumentException` *code*  is 1011 (server error). It cannot be used by clients. 

-or- 

*code*  is 1010 (mandatory extension). It cannot be used by servers. 

-or- 

*code*  is 1005 (no status) and there is reason. 

-or- 

*reason*  could not be UTF-8-encoded.

##### `public void ` [`Close`](#class_web_socket_sharp_1_1_web_socket_1ad2d11ea3a240649899dacd660c64100c)`(` [`CloseStatusCode`](WebSocketSharp.md)` code, string reason)` 

Closes the connection with the specified code and reason.

This method does nothing if the current state of the connection is Closing or Closed. 

#### Parameters
* `code` One of the CloseStatusCode enum values. 

It represents the status code indicating the reason for the close. 

* `reason` A string that represents the reason for the close. 

The size must be 123 bytes or less in UTF-8. 

#### Exceptions
* `ArgumentException` *code*  is CloseStatusCode.ServerError. It cannot be used by clients. 

-or- 

*code*  is CloseStatusCode.MandatoryExtension. It cannot be used by servers. 

-or- 

*code*  is CloseStatusCode.NoStatus and there is reason. 

-or- 

*reason*  could not be UTF-8-encoded. 

* `ArgumentOutOfRangeException` The size of *reason*  is greater than 123 bytes.

##### `public void ` [`CloseAsync`](#class_web_socket_sharp_1_1_web_socket_1a9b146b83101efc75fe45964459e054ce)`()` 

Closes the connection asynchronously.

This method does not wait for the close to be complete. 

This method does nothing if the current state of the connection is Closing or Closed.

##### `public void ` [`CloseAsync`](#class_web_socket_sharp_1_1_web_socket_1a6fa73542c436aa306414fc7f56337676)`(ushort code)` 

Closes the connection asynchronously with the specified code.

This method does not wait for the close to be complete. 

This method does nothing if the current state of the connection is Closing or Closed. 

#### Parameters
* `code` A ushort that represents the status code indicating the reason for the close. 

The status codes are defined in  Section 7.4

of RFC 6455. 

#### Exceptions
* `ArgumentOutOfRangeException` *code*  is less than 1000 or greater than 4999. 

* `ArgumentException` *code*  is 1011 (server error). It cannot be used by clients. 

-or- 

*code*  is 1010 (mandatory extension). It cannot be used by servers.

##### `public void ` [`CloseAsync`](#class_web_socket_sharp_1_1_web_socket_1a3d4bd9254e100f158b7e8e8fe7e291ab)`(` [`CloseStatusCode`](WebSocketSharp.md)` code)` 

Closes the connection asynchronously with the specified code.

This method does not wait for the close to be complete. 

This method does nothing if the current state of the connection is Closing or Closed. 

#### Parameters
* `code` One of the CloseStatusCode enum values. 

It represents the status code indicating the reason for the close. 

#### Exceptions
* `ArgumentException` *code*  is CloseStatusCode.ServerError. It cannot be used by clients. 

-or- 

*code*  is CloseStatusCode.MandatoryExtension. It cannot be used by servers.

##### `public void ` [`CloseAsync`](#class_web_socket_sharp_1_1_web_socket_1ae4f0b83a46dec1a0b30034b0e948d593)`(ushort code, string reason)` 

Closes the connection asynchronously with the specified code and reason.

This method does not wait for the close to be complete. 

This method does nothing if the current state of the connection is Closing or Closed. 

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

* `ArgumentException` *code*  is 1011 (server error). It cannot be used by clients. 

-or- 

*code*  is 1010 (mandatory extension). It cannot be used by servers. 

-or- 

*code*  is 1005 (no status) and there is reason. 

-or- 

*reason*  could not be UTF-8-encoded.

##### `public void ` [`CloseAsync`](#class_web_socket_sharp_1_1_web_socket_1acf084a4255d196ef3ad90420ccaea2f3)`(` [`CloseStatusCode`](WebSocketSharp.md)` code, string reason)` 

Closes the connection asynchronously with the specified code and reason.

This method does not wait for the close to be complete. 

This method does nothing if the current state of the connection is Closing or Closed. 

#### Parameters
* `code` One of the CloseStatusCode enum values. 

It represents the status code indicating the reason for the close. 

* `reason` A string that represents the reason for the close. 

The size must be 123 bytes or less in UTF-8. 

#### Exceptions
* `ArgumentException` *code*  is CloseStatusCode.ServerError. It cannot be used by clients. 

-or- 

*code*  is CloseStatusCode.MandatoryExtension. It cannot be used by servers. 

-or- 

*code*  is CloseStatusCode.NoStatus and there is reason. 

-or- 

*reason*  could not be UTF-8-encoded. 

* `ArgumentOutOfRangeException` The size of *reason*  is greater than 123 bytes.

##### `public void ` [`Connect`](#class_web_socket_sharp_1_1_web_socket_1a5b6b4e47c7e5a413015c702d9825734f)`()` 

Establishes a connection.

This method does nothing if the connection has already been established. 

#### Exceptions
* `InvalidOperationException` This instance is not a client. 

-or- 

The close process is in progress. 

-or- 

A series of reconnecting has failed.

##### `public void ` [`ConnectAsync`](#class_web_socket_sharp_1_1_web_socket_1a2431b06e2ee33acae51e8a7894ee58fd)`()` 

Establishes a connection asynchronously.

This method does not wait for the connect process to be complete. 

This method does nothing if the connection has already been established. 

#### Exceptions
* `InvalidOperationException` This instance is not a client. 

-or- 

The close process is in progress. 

-or- 

A series of reconnecting has failed.

##### `public bool ` [`Ping`](#class_web_socket_sharp_1_1_web_socket_1a24ce3b6d0c9139e53e07089971dc864c)`()` 

Sends a ping using the WebSocket connection.

#### Returns
`true` if the send has done with no error and a pong has been received within a time; otherwise, `false`.

##### `public bool ` [`Ping`](#class_web_socket_sharp_1_1_web_socket_1acb6bd2b66f507e81f91ee61e690d417c)`(string message)` 

Sends a ping with *message*  using the WebSocket connection.

#### Returns
`true` if the send has done with no error and a pong has been received within a time; otherwise, `false`. 

#### Parameters
* `message` A string that represents the message to send. 

The size must be 125 bytes or less in UTF-8. 

#### Exceptions
* `ArgumentException` *message*  could not be UTF-8-encoded. 

* `ArgumentOutOfRangeException` The size of *message*  is greater than 125 bytes.

##### `public void ` [`Send`](#class_web_socket_sharp_1_1_web_socket_1aa826ba54ecf62a7df2cf50a0b93fd265)`(byte[] data)` 

Sends the specified data using the WebSocket connection.

#### Parameters
* `data` An array of byte that represents the binary data to send. 

#### Exceptions
* `InvalidOperationException` The current state of the connection is not Open. 

* `ArgumentNullException` *data*  is `null`.

##### `public void ` [`Send`](#class_web_socket_sharp_1_1_web_socket_1a32497e3fd2eb87d1d3051448c2dd1cb9)`(FileInfo fileInfo)` 

Sends the specified file using the WebSocket connection.

#### Parameters
* `fileInfo` A FileInfo that specifies the file to send. 

The file is sent as the binary data. 

#### Exceptions
* `InvalidOperationException` The current state of the connection is not Open. 

* `ArgumentNullException` *fileInfo*  is `null`. 

* `ArgumentException` The file does not exist. 

-or- 

The file could not be opened.

##### `public void ` [`Send`](#class_web_socket_sharp_1_1_web_socket_1ac3549c8cf5f93b620c35c63c877ee896)`(string data)` 

Sends the specified data using the WebSocket connection.

#### Parameters
* `data` A string that represents the text data to send. 

#### Exceptions
* `InvalidOperationException` The current state of the connection is not Open. 

* `ArgumentNullException` *data*  is `null`. 

* `ArgumentException` *data*  could not be UTF-8-encoded.

##### `public void ` [`Send`](#class_web_socket_sharp_1_1_web_socket_1aa98fdf5984aeb6dd44bdc7539a6a8fa0)`(Stream stream, int length)` 

Sends the data from the specified stream using the WebSocket connection.

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

##### `public void ` [`SendAsync`](#class_web_socket_sharp_1_1_web_socket_1adc823b289d11ac4e6ac7744be0363a9d)`(byte[] data, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)`< bool > completed)` 

Sends the specified data asynchronously using the WebSocket connection.

This method does not wait for the send to be complete. 

#### Parameters
* `data` An array of byte that represents the binary data to send. 

* `completed` An `Action<bool>` delegate or `null` if not needed. 

The delegate invokes the method called when the send is complete. 

`true` is passed to the method if the send has done with no error; otherwise, `false`. 

#### Exceptions
* `InvalidOperationException` The current state of the connection is not Open. 

* `ArgumentNullException` *data*  is `null`.

##### `public void ` [`SendAsync`](#class_web_socket_sharp_1_1_web_socket_1a4fbe47aee3ab33fc8c0a55388495608f)`(FileInfo fileInfo, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)`< bool > completed)` 

Sends the specified file asynchronously using the WebSocket connection.

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

##### `public void ` [`SendAsync`](#class_web_socket_sharp_1_1_web_socket_1ae75cfc2f9c0c707bb4832bface2e1d48)`(string data, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)`< bool > completed)` 

Sends the specified data asynchronously using the WebSocket connection.

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

##### `public void ` [`SendAsync`](#class_web_socket_sharp_1_1_web_socket_1aaef4fdb5c4b2e11d3f031c49241b7b51)`(Stream stream, int length, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)`< bool > completed)` 

Sends the data from the specified stream asynchronously using the WebSocket connection.

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

##### `public void ` [`SetCookie`](#class_web_socket_sharp_1_1_web_socket_1aebf7816b302fd17dff92187e8ae2f27a)`(` [`Cookie`](WebSocketSharp--Net--Cookie.md)` cookie)` 

Sets an HTTP cookie to send with the handshake request.

This method does nothing if the connection has already been established or it is closing. 

#### Parameters
* `cookie` A Cookie that represents the cookie to send. 

#### Exceptions
* `InvalidOperationException` This instance is not a client. 

* `ArgumentNullException` *cookie*  is `null`.

##### `public void ` [`SetCredentials`](#class_web_socket_sharp_1_1_web_socket_1ae6e3a8b053d753947db3c03c870b1405)`(string username, string password, bool preAuth)` 

Sets the credentials for the HTTP authentication (Basic/Digest).

This method does nothing if the connection has already been established or it is closing. 

#### Parameters
* `username` A string that represents the username associated with the credentials. 

`null` or an empty string if initializes the credentials. 

* `password` A string that represents the password for the username associated with the credentials. 

`null` or an empty string if not necessary. 

* `preAuth` `true` if sends the credentials for the Basic authentication in advance with the first handshake request; otherwise, `false`. 

#### Exceptions
* `InvalidOperationException` This instance is not a client. 

* `ArgumentException` *username*  contains an invalid character. 

-or- 

*password*  contains an invalid character.

##### `public void ` [`SetProxy`](#class_web_socket_sharp_1_1_web_socket_1a1238de28fb663f2653de05812aaa89b3)`(string url, string username, string password)` 

Sets the URL of the HTTP proxy server through which to connect and the credentials for the HTTP proxy authentication (Basic/Digest).

This method does nothing if the connection has already been established or it is closing. 

#### Parameters
* `url` A string that represents the URL of the proxy server through which to connect. 

The syntax is [http://&lt;host&gt;](http://&lt;host&gt;)[:<port>]. 

`null` or an empty string if initializes the URL and the credentials. 

* `username` A string that represents the username associated with the credentials. 

`null` or an empty string if the credentials are not necessary. 

* `password` A string that represents the password for the username associated with the credentials. 

`null` or an empty string if not necessary. 

#### Exceptions
* `InvalidOperationException` This instance is not a client. 

* `ArgumentException` *url*  is not an absolute URI string. 

-or- 

The scheme of *url*  is not http. 

-or- 

*url*  includes the path segments. 

-or- 

*username*  contains an invalid character. 

-or- 

*password*  contains an invalid character.

##### `private ` [`AuthenticationChallenge`](WebSocketSharp--Net--AuthenticationChallenge.md)` ` [`_authChallenge`](#class_web_socket_sharp_1_1_web_socket_1a106a7a79b7984ce1aadab37ad144076e) 

##### `private string ` [`_base64Key`](#class_web_socket_sharp_1_1_web_socket_1a176b8baed7053aa466dc038791113e57) 

##### `private bool ` [`_client`](#class_web_socket_sharp_1_1_web_socket_1a01b67b1dc268e5be557e1c101324f6d2) 

##### `private ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)` ` [`_closeContext`](#class_web_socket_sharp_1_1_web_socket_1a03f9e37a2ad231b7523eb24f89df169e) 

##### `private ` [`CompressionMethod`](WebSocketSharp.md)` ` [`_compression`](#class_web_socket_sharp_1_1_web_socket_1ad555ae5cd6fe8323472786ed031c998f) 

##### `private ` [`WebSocketContext`](WebSocketSharp--Net--WebSockets--WebSocketContext.md)` ` [`_context`](#class_web_socket_sharp_1_1_web_socket_1a816ceeb71f3ec93039d6323396ba0da3) 

##### `private ` [`CookieCollection`](WebSocketSharp--Net--CookieCollection.md)` ` [`_cookies`](#class_web_socket_sharp_1_1_web_socket_1ae2054e3379559490b8e8704754ae0eb0) 

##### `private ` [`NetworkCredential`](WebSocketSharp--Net--NetworkCredential.md)` ` [`_credentials`](#class_web_socket_sharp_1_1_web_socket_1a407195013251672f90ff35301df110db) 

##### `private bool ` [`_emitOnPing`](#class_web_socket_sharp_1_1_web_socket_1a76edee6035be0274acf14d5ce879a1e1) 

##### `private bool ` [`_enableRedirection`](#class_web_socket_sharp_1_1_web_socket_1afd2de7b3765bd0450ee9d6c9c45ff636) 

##### `private string ` [`_extensions`](#class_web_socket_sharp_1_1_web_socket_1a40021ce4cf931a6679907b82aa711726) 

##### `private bool ` [`_extensionsRequested`](#class_web_socket_sharp_1_1_web_socket_1adf517f6c4c1f6c6b89337bc0db795869) 

##### `private object ` [`_forMessageEventQueue`](#class_web_socket_sharp_1_1_web_socket_1a176a2da998f6e25c8207d692c960c2c4) 

##### `private object ` [`_forPing`](#class_web_socket_sharp_1_1_web_socket_1ae6d7d8acfd68377508fc5a1597260728) 

##### `private object ` [`_forSend`](#class_web_socket_sharp_1_1_web_socket_1a0070032c1f6a19cdd18897ecc7f4fa2e) 

##### `private object ` [`_forState`](#class_web_socket_sharp_1_1_web_socket_1a99429982a354db10e5a37c22bf2b98c4) 

##### `private MemoryStream ` [`_fragmentsBuffer`](#class_web_socket_sharp_1_1_web_socket_1acd379c10d911e0a1c7aa64e2c45ec96f) 

##### `private bool ` [`_fragmentsCompressed`](#class_web_socket_sharp_1_1_web_socket_1ab4873eacb18f4c3fb45cdf43a29039b6) 

##### `private ` [`Opcode`](WebSocketSharp.md)` ` [`_fragmentsOpcode`](#class_web_socket_sharp_1_1_web_socket_1a4b532bf7bd344319b9eaba6acfacd9b7) 

##### `private Func< ` [`WebSocketContext`](WebSocketSharp--Net--WebSockets--WebSocketContext.md)`, string > ` [`_handshakeRequestChecker`](#class_web_socket_sharp_1_1_web_socket_1a6a51c8e83017953e513e70efd5c4ed92) 

##### `private bool ` [`_ignoreExtensions`](#class_web_socket_sharp_1_1_web_socket_1aaa6b062ecf2c0e5631126d19e63232dc) 

##### `private bool ` [`_inContinuation`](#class_web_socket_sharp_1_1_web_socket_1a5e156e843e0ac1bebc550840c265126b) 

##### `private volatile bool ` [`_inMessage`](#class_web_socket_sharp_1_1_web_socket_1aa00f59420f5f3a2979676979c9528b16) 

##### `private volatile ` [`Logger`](WebSocketSharp--Logger.md)` ` [`_logger`](#class_web_socket_sharp_1_1_web_socket_1aa9e8e1e5a50a812b6622c36b4c72537f) 

##### `private ` [`Action](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)< [MessageEventArgs`](WebSocketSharp--MessageEventArgs.md)` > ` [`_message`](#class_web_socket_sharp_1_1_web_socket_1a0dd508694ae805621abe136374989fa7) 

##### `private Queue< ` [`MessageEventArgs`](WebSocketSharp--MessageEventArgs.md)` > ` [`_messageEventQueue`](#class_web_socket_sharp_1_1_web_socket_1a3b9f66831321539f75180a0ecdc20c39) 

##### `private uint ` [`_nonceCount`](#class_web_socket_sharp_1_1_web_socket_1a94db75d7371c21043430a471dffd3d45) 

##### `private string ` [`_origin`](#class_web_socket_sharp_1_1_web_socket_1a103f18dc3009badb14b25480037f0815) 

##### `private ManualResetEvent ` [`_pongReceived`](#class_web_socket_sharp_1_1_web_socket_1a8a0ca830ec222508948269f0accb4b35) 

##### `private bool ` [`_preAuth`](#class_web_socket_sharp_1_1_web_socket_1ae8801eb7701de955da0880f490ad924c) 

##### `private string ` [`_protocol`](#class_web_socket_sharp_1_1_web_socket_1ad984ec662a4971f019cea27a0fcb4c68) 

##### `private string[] ` [`_protocols`](#class_web_socket_sharp_1_1_web_socket_1a735b0cbed8e1c0fc22269986c6a1f3dc) 

##### `private bool ` [`_protocolsRequested`](#class_web_socket_sharp_1_1_web_socket_1a94a4ade7664db0d742981d37879e5d41) 

##### `private ` [`NetworkCredential`](WebSocketSharp--Net--NetworkCredential.md)` ` [`_proxyCredentials`](#class_web_socket_sharp_1_1_web_socket_1ae1dc90d1c3e1c0acde13484633348eff) 

##### `private Uri ` [`_proxyUri`](#class_web_socket_sharp_1_1_web_socket_1a578ddd6ba0a22637a03b4deb4b385615) 

##### `private volatile ` [`WebSocketState`](WebSocketSharp.md)` ` [`_readyState`](#class_web_socket_sharp_1_1_web_socket_1aaee3f28c178c03d149781ee55c448e46) 

##### `private ManualResetEvent ` [`_receivingExited`](#class_web_socket_sharp_1_1_web_socket_1a0cf5ded175f62b35b3a0d15cf367a007) 

##### `private int ` [`_retryCountForConnect`](#class_web_socket_sharp_1_1_web_socket_1a17b6b1910ec88da03e62180c442165ea) 

##### `private bool ` [`_secure`](#class_web_socket_sharp_1_1_web_socket_1a2f7b5b309c5830b8532939ca02946b44) 

##### `private ` [`ClientSslConfiguration`](WebSocketSharp--Net--ClientSslConfiguration.md)` ` [`_sslConfig`](#class_web_socket_sharp_1_1_web_socket_1ab1e9b066883f0f8dd77aee498d23a40a) 

##### `private Stream ` [`_stream`](#class_web_socket_sharp_1_1_web_socket_1ae5401654b26ad72d9da131e0a3db7eb8) 

##### `private TcpClient ` [`_tcpClient`](#class_web_socket_sharp_1_1_web_socket_1a90eb17ad2d30dea9b36901e5dbb080dc) 

##### `private Uri ` [`_uri`](#class_web_socket_sharp_1_1_web_socket_1a80518856549440f2fd5d4b4a681b4767) 

##### `private TimeSpan ` [`_waitTime`](#class_web_socket_sharp_1_1_web_socket_1aff6d565013f5a1afe6d5b94ee07b5454) 

##### `private bool ` [`accept`](#class_web_socket_sharp_1_1_web_socket_1a88a977a48a4980f337cf41e889a56afa)`()` 

##### `private bool ` [`acceptHandshake`](#class_web_socket_sharp_1_1_web_socket_1ac91fd609727b087da8953534e1531c4e)`()` 

##### `private bool ` [`canSet`](#class_web_socket_sharp_1_1_web_socket_1a729ea85bb2548e8a7b5f70f75159b133)`(out string message)` 

##### `private bool ` [`checkHandshakeRequest`](#class_web_socket_sharp_1_1_web_socket_1a8d602a7c1ae13eec49b45639a4d06ee7)`(` [`WebSocketContext`](WebSocketSharp--Net--WebSockets--WebSocketContext.md)` context, out string message)` 

##### `private bool ` [`checkHandshakeResponse`](#class_web_socket_sharp_1_1_web_socket_1a955b3a7bfabc569442026d0cc8d280cb)`(` [`HttpResponse`](WebSocketSharp--HttpResponse.md)` response, out string message)` 

##### `private bool ` [`checkReceivedFrame`](#class_web_socket_sharp_1_1_web_socket_1ad124fa012efdd12ff3fb48dc891eb6f5)`(` [`WebSocketFrame`](WebSocketSharp--WebSocketFrame.md)` frame, out string message)` 

##### `private void ` [`close`](#class_web_socket_sharp_1_1_web_socket_1a3bd770627ba58dc3a898d15908185552)`(ushort code, string reason)` 

##### `private void ` [`close`](#class_web_socket_sharp_1_1_web_socket_1a87cc490498df87630b87d062f281f2bb)`(` [`PayloadData`](WebSocketSharp--PayloadData.md)` payloadData, bool send, bool receive, bool received)` 

##### `private void ` [`closeAsync`](#class_web_socket_sharp_1_1_web_socket_1a2dbd9ef9f8949b8b01e6414f74708207)`(ushort code, string reason)` 

##### `private void ` [`closeAsync`](#class_web_socket_sharp_1_1_web_socket_1a9485e8101259ccf8f872b1600030142e)`(` [`PayloadData`](WebSocketSharp--PayloadData.md)` payloadData, bool send, bool receive, bool received)` 

##### `private bool ` [`closeHandshake`](#class_web_socket_sharp_1_1_web_socket_1aa39c91c8259cae1b13151dc6fda4d599)`(byte[] frameAsBytes, bool receive, bool received)` 

##### `private bool ` [`closeHandshake`](#class_web_socket_sharp_1_1_web_socket_1a709b48d5b5323bf9b38f08c7f4ecf095)`(` [`PayloadData`](WebSocketSharp--PayloadData.md)` payloadData, bool send, bool receive, bool received)` 

##### `private bool ` [`connect`](#class_web_socket_sharp_1_1_web_socket_1aa0a57e883c6c9fc19e62a609d967be9c)`()` 

##### `private string ` [`createExtensions`](#class_web_socket_sharp_1_1_web_socket_1a8e484ded681920bfe82dcbbcaef37e9b)`()` 

##### `private ` [`HttpResponse`](WebSocketSharp--HttpResponse.md)` ` [`createHandshakeFailureResponse`](#class_web_socket_sharp_1_1_web_socket_1a9a1984992a0f1cdc30732f64ce7d2ac4)`(` [`HttpStatusCode`](WebSocketSharp--Net.md)` code)` 

##### `private ` [`HttpRequest`](WebSocketSharp--HttpRequest.md)` ` [`createHandshakeRequest`](#class_web_socket_sharp_1_1_web_socket_1a88f85a0265c260340479e0958827ab9b)`()` 

##### `private ` [`HttpResponse`](WebSocketSharp--HttpResponse.md)` ` [`createHandshakeResponse`](#class_web_socket_sharp_1_1_web_socket_1a746282c95881c257af1abb03a6718dc8)`()` 

##### `private bool ` [`customCheckHandshakeRequest`](#class_web_socket_sharp_1_1_web_socket_1a2561be3cf9e0366c9dfdda31daa5c09b)`(` [`WebSocketContext`](WebSocketSharp--Net--WebSockets--WebSocketContext.md)` context, out string message)` 

##### `private ` [`MessageEventArgs`](WebSocketSharp--MessageEventArgs.md)` ` [`dequeueFromMessageEventQueue`](#class_web_socket_sharp_1_1_web_socket_1a3f7277570e5c47d04b26812bcb73fe9e)`()` 

##### `private void ` [`doHandshake`](#class_web_socket_sharp_1_1_web_socket_1ad29764e5418e50470ad97ad22fb023f1)`()` 

##### `private void ` [`enqueueToMessageEventQueue`](#class_web_socket_sharp_1_1_web_socket_1a1b62d31160cd60e000e690c32a469242)`(` [`MessageEventArgs`](WebSocketSharp--MessageEventArgs.md)` e)` 

##### `private void ` [`error`](#class_web_socket_sharp_1_1_web_socket_1af4eb8e693d7e8d0c58b2a8edc2b54ac2)`(string message, Exception exception)` 

##### `private void ` [`fatal`](#class_web_socket_sharp_1_1_web_socket_1aa318a7d65f90a4625a789480c16b7b0a)`(string message, Exception exception)` 

##### `private void ` [`fatal`](#class_web_socket_sharp_1_1_web_socket_1a67a4cb57552a4c9c32ca808adaef7ea3)`(string message, ushort code)` 

##### `private void ` [`fatal`](#class_web_socket_sharp_1_1_web_socket_1a7c0ffe110c51bbcb4eafd43ec01042e4)`(string message, ` [`CloseStatusCode`](WebSocketSharp.md)` code)` 

##### `private ` [`ClientSslConfiguration`](WebSocketSharp--Net--ClientSslConfiguration.md)` ` [`getSslConfiguration`](#class_web_socket_sharp_1_1_web_socket_1acfae70861749a184f6e763974ec438e2)`()` 

##### `private void ` [`init`](#class_web_socket_sharp_1_1_web_socket_1a02fd73d861ef2e4aabb38c0c9ff82947)`()` 

##### `private void ` [`message`](#class_web_socket_sharp_1_1_web_socket_1a137d78a01e63d3b66d1b2ed0de0f4c4c)`()` 

##### `private void ` [`messagec`](#class_web_socket_sharp_1_1_web_socket_1a7e35e38f50b6cb8157d8cbb829b853b7)`(` [`MessageEventArgs`](WebSocketSharp--MessageEventArgs.md)` e)` 

##### `private void ` [`messages`](#class_web_socket_sharp_1_1_web_socket_1a83f52d3db2ef69f5bba3bc15f4ade975)`(` [`MessageEventArgs`](WebSocketSharp--MessageEventArgs.md)` e)` 

##### `private void ` [`open`](#class_web_socket_sharp_1_1_web_socket_1a9e8555112049fc2b4945120b3c45f8ab)`()` 

##### `private bool ` [`ping`](#class_web_socket_sharp_1_1_web_socket_1aa953583b1b6ba6cb36cb5c0a727ba8a1)`(byte[] data)` 

##### `private bool ` [`processCloseFrame`](#class_web_socket_sharp_1_1_web_socket_1afa634ae55e6e2e73021d77dc6b10dd75)`(` [`WebSocketFrame`](WebSocketSharp--WebSocketFrame.md)` frame)` 

##### `private void ` [`processCookies`](#class_web_socket_sharp_1_1_web_socket_1a898c7fad5d852c52cfc1b5c8866ea624)`(` [`CookieCollection`](WebSocketSharp--Net--CookieCollection.md)` cookies)` 

##### `private bool ` [`processDataFrame`](#class_web_socket_sharp_1_1_web_socket_1ad849f6fd956a4fefdd9a8885316664ed)`(` [`WebSocketFrame`](WebSocketSharp--WebSocketFrame.md)` frame)` 

##### `private bool ` [`processFragmentFrame`](#class_web_socket_sharp_1_1_web_socket_1aaa2af87494e4d4106a68eb72bea1d965)`(` [`WebSocketFrame`](WebSocketSharp--WebSocketFrame.md)` frame)` 

##### `private bool ` [`processPingFrame`](#class_web_socket_sharp_1_1_web_socket_1a407805ce5d55a7bfc71fa90f69222096)`(` [`WebSocketFrame`](WebSocketSharp--WebSocketFrame.md)` frame)` 

##### `private bool ` [`processPongFrame`](#class_web_socket_sharp_1_1_web_socket_1ab1da2b0eae1b7761364926e382e0d3d7)`(` [`WebSocketFrame`](WebSocketSharp--WebSocketFrame.md)` frame)` 

##### `private bool ` [`processReceivedFrame`](#class_web_socket_sharp_1_1_web_socket_1a5bcbc0cb1b8b9089dfb454f9e5563e6d)`(` [`WebSocketFrame`](WebSocketSharp--WebSocketFrame.md)` frame)` 

##### `private void ` [`processSecWebSocketExtensionsClientHeader`](#class_web_socket_sharp_1_1_web_socket_1a79041761a696299ce047c4726c5c8649)`(string value)` 

##### `private void ` [`processSecWebSocketExtensionsServerHeader`](#class_web_socket_sharp_1_1_web_socket_1aa6595abb981503678a0b4f5c6211e265)`(string value)` 

##### `private void ` [`processSecWebSocketProtocolClientHeader`](#class_web_socket_sharp_1_1_web_socket_1a69189464b89f8b9a2f7bc05134ae1a36)`(IEnumerable< string > values)` 

##### `private bool ` [`processUnsupportedFrame`](#class_web_socket_sharp_1_1_web_socket_1a82829e6eed00af69e8ad5d0ad4e58729)`(` [`WebSocketFrame`](WebSocketSharp--WebSocketFrame.md)` frame)` 

##### `private void ` [`refuseHandshake`](#class_web_socket_sharp_1_1_web_socket_1aca245c8e33ee3046974aa5c6da5dfed6)`(` [`CloseStatusCode`](WebSocketSharp.md)` code, string reason)` 

##### `private void ` [`releaseClientResources`](#class_web_socket_sharp_1_1_web_socket_1a89420822ca5a6c0e6e277f084887f8f2)`()` 

##### `private void ` [`releaseCommonResources`](#class_web_socket_sharp_1_1_web_socket_1afb84a74c6bb13348e097927e70a75d3a)`()` 

##### `private void ` [`releaseResources`](#class_web_socket_sharp_1_1_web_socket_1a631d78806ec72c285cd1fff6f5afde13)`()` 

##### `private void ` [`releaseServerResources`](#class_web_socket_sharp_1_1_web_socket_1a84f01e3854ad45bcdfdd42f5cae5d6d3)`()` 

##### `private bool ` [`send`](#class_web_socket_sharp_1_1_web_socket_1a41de76e041a1b4576b0a8a9a097c0eb8)`(` [`Opcode`](WebSocketSharp.md)` opcode, Stream stream)` 

##### `private bool ` [`send`](#class_web_socket_sharp_1_1_web_socket_1a691369ea736837730f027b4887442bb1)`(` [`Opcode`](WebSocketSharp.md)` opcode, Stream stream, bool compressed)` 

##### `private bool ` [`send`](#class_web_socket_sharp_1_1_web_socket_1a920c2e763845fc66ef7ede0deebe75fb)`(` [`Fin`](WebSocketSharp.md)` fin, ` [`Opcode`](WebSocketSharp.md)` opcode, byte[] data, bool compressed)` 

##### `private void ` [`sendAsync`](#class_web_socket_sharp_1_1_web_socket_1a51f0cf0eb7189687214e5b09f5b582c0)`(` [`Opcode`](WebSocketSharp.md)` opcode, Stream stream, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)`< bool > completed)` 

##### `private bool ` [`sendBytes`](#class_web_socket_sharp_1_1_web_socket_1ac1625387556c92f6faf47f5f16e7452d)`(byte[] bytes)` 

##### `private ` [`HttpResponse`](WebSocketSharp--HttpResponse.md)` ` [`sendHandshakeRequest`](#class_web_socket_sharp_1_1_web_socket_1ab7955004a263836896b00edbc1ba7fab)`()` 

##### `private ` [`HttpResponse`](WebSocketSharp--HttpResponse.md)` ` [`sendHttpRequest`](#class_web_socket_sharp_1_1_web_socket_1aae7f1d804fe42999e049aee188879afd)`(` [`HttpRequest`](WebSocketSharp--HttpRequest.md)` request, int millisecondsTimeout)` 

##### `private bool ` [`sendHttpResponse`](#class_web_socket_sharp_1_1_web_socket_1a7afb144fb354dc7a30380a333c2cb2e3)`(` [`HttpResponse`](WebSocketSharp--HttpResponse.md)` response)` 

##### `private void ` [`sendProxyConnectRequest`](#class_web_socket_sharp_1_1_web_socket_1a0b5b763bb0c37f066880def4ad3ce055)`()` 

##### `private void ` [`setClientStream`](#class_web_socket_sharp_1_1_web_socket_1aaad9c1417ba8e81afbc6aa8e96dd9b8d)`()` 

##### `private void ` [`startReceiving`](#class_web_socket_sharp_1_1_web_socket_1a95e75d300547b71b3cc33d6e02f7a475)`()` 

##### `private bool ` [`validateSecWebSocketAcceptHeader`](#class_web_socket_sharp_1_1_web_socket_1ad6b37153aa11b0eee2c043e080307f8a)`(string value)` 

##### `private bool ` [`validateSecWebSocketExtensionsServerHeader`](#class_web_socket_sharp_1_1_web_socket_1ad64e160278d51e798829c12056e4e649)`(string value)` 

##### `private bool ` [`validateSecWebSocketProtocolServerHeader`](#class_web_socket_sharp_1_1_web_socket_1aaa91a318e2a8072cc2a23174fb667b9f)`(string value)` 

##### `private bool ` [`validateSecWebSocketVersionServerHeader`](#class_web_socket_sharp_1_1_web_socket_1a99626455e68da69b487658d1d0d5855f)`(string value)` 

##### `private void IDisposable. ` [`Dispose`](#class_web_socket_sharp_1_1_web_socket_1a44dd5de4474284f22b70c3e0fbdc07f4)`()` 

Closes the connection and releases all associated resources.

This method closes the connection with close status 1001 (going away). 

And this method does nothing if the current state of the connection is Closing or Closed.

##### `private static static ` [`WebSocket`](#class_web_socket_sharp_1_1_web_socket_1a236bbe6b3b1d1d8ce39bccf7def48174)`()` 

##### `private static bool ` [`checkProtocols`](#class_web_socket_sharp_1_1_web_socket_1a3de831cbb69869b04d305a8b507e171f)`(string[] protocols, out string message)` 

