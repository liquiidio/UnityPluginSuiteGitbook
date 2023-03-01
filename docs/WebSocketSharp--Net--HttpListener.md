# class `WebSocketSharp::Net::HttpListener` 

```
class WebSocketSharp::Net::HttpListener
  : public IDisposable
```

Provides a simple, programmatically controlled HTTP listener.

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`package bool ` [`IsDisposed`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1ab96a71c70205ed1aa4af692ee7f35403) | 
`package bool ` [`ReuseAddress`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1a923e721e9823564407e4d83b8a49fb9b) | 
`public ` [`AuthenticationSchemes`](WebSocketSharp--Net.md)` ` [`AuthenticationSchemes`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1ab2f4176cabceeee69cb96c6d68ab5f05) | Gets or sets the scheme used to authenticate the clients.
`public Func< ` [`HttpListenerRequest](WebSocketSharp--Net--HttpListenerRequest.md), [AuthenticationSchemes`](WebSocketSharp--Net.md)` > ` [`AuthenticationSchemeSelector`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1af6eaeee559b38c8c524cbc06e8ec6232) | Gets or sets the delegate called to select the scheme used to authenticate the clients.
`public string ` [`CertificateFolderPath`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1abc2f63e7ede69b59b8e6ef25869145d5) | Gets or sets the path to the folder in which stores the certificate files used to authenticate the server on the secure connection.
`public bool ` [`IgnoreWriteExceptions`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1aa16e1537c56cc89c560f4c0be96263b0) | Gets or sets a value indicating whether the listener returns exceptions that occur when sending the response to the client.
`public bool ` [`IsListening`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1aa989b9618104958f4a259fa37fb939d8) | Gets a value indicating whether the listener has been started.
`public bool ` [`IsSupported`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1a25e3c2c0333e001d5887b8549960d97d) | Gets a value indicating whether the listener can be used with the current operating system.
`public ` [`Logger`](WebSocketSharp--Logger.md)` ` [`Log`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1af2ed886ec3d2b2fd42fd0c5dad2f8cc5) | Gets the logging functions.
`public ` [`HttpListenerPrefixCollection`](WebSocketSharp--Net--HttpListenerPrefixCollection.md)` ` [`Prefixes`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1ab1c80e2a715f1bc832b7ab6d90774f42) | Gets the URI prefixes handled by the listener.
`public string ` [`Realm`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1a52a674ec0b4dc0d9e94f9ff3c47c583a) | Gets or sets the name of the realm associated with the listener.
`public ` [`ServerSslConfiguration`](WebSocketSharp--Net--ServerSslConfiguration.md)` ` [`SslConfiguration`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1aa41bf1c36ef66f799331bb3ea0204ca9) | Gets or sets the SSL configuration used to authenticate the server and optionally the client for secure connection.
`public bool ` [`UnsafeConnectionNtlmAuthentication`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1aa2238ae56a0f27532704a5b85d045e25) | Gets or sets a value indicating whether, when NTLM authentication is used, the authentication information of first request is used to authenticate additional requests on the same connection.
`public Func< IIdentity, ` [`NetworkCredential`](WebSocketSharp--Net--NetworkCredential.md)` > ` [`UserCredentialsFinder`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1acd9009b71f94aed4202e9e2fa19cc1d1) | Gets or sets the delegate called to find the credentials for an identity used to authenticate a client.
`public ` [`HttpListener`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1ac3e7570badee6dbd180eb3e428ac57f1)`()` | Initializes a new instance of the HttpListener class.
`public void ` [`Abort`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1a12b9283f52eaf7610afe4b04fbca2ff0)`()` | Shuts down the listener immediately.
`public IAsyncResult ` [`BeginGetContext`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1a023bc9d06972faaf48bfbfd86d532bf0)`(AsyncCallback callback, Object state)` | Begins getting an incoming request asynchronously.
`public void ` [`Close`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1a7f7a3199c392465d0767c6506c1af5b4)`()` | Shuts down the listener.
`public ` [`HttpListenerContext`](WebSocketSharp--Net--HttpListenerContext.md)` ` [`EndGetContext`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1a5658742d6d2009adebc0efa96747dd08)`(IAsyncResult asyncResult)` | Ends an asynchronous operation to get an incoming request.
`public ` [`HttpListenerContext`](WebSocketSharp--Net--HttpListenerContext.md)` ` [`GetContext`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1a84ef6c2f87fc0851891c2e2ab9e43430)`()` | Gets an incoming request.
`public void ` [`Start`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1a07aaf1227e4d645f15e0a964f54ef291)`()` | Starts receiving incoming requests.
`public void ` [`Stop`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1a17a237457e57625296e6b24feb19c60a)`()` | Stops receiving incoming requests.
`private ` [`AuthenticationSchemes`](WebSocketSharp--Net.md)` ` [`_authSchemes`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1ac2cfce2148d2f47655c0a1c4b048c07e) | 
`private Func< ` [`HttpListenerRequest](WebSocketSharp--Net--HttpListenerRequest.md), [AuthenticationSchemes`](WebSocketSharp--Net.md)` > ` [`_authSchemeSelector`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1ae347a57717f3450131827af52f8bd391) | 
`private string ` [`_certFolderPath`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1ab629f6b98d73781678e6233be5f6aa35) | 
`private Dictionary< ` [`HttpConnection](WebSocketSharp--Net--HttpConnection.md), [HttpConnection`](WebSocketSharp--Net--HttpConnection.md)` > ` [`_connections`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1a08dab1e1a4ffb24111729120b65f4f79) | 
`private object ` [`_connectionsSync`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1a7e72e3355f1a90b1b9de44c59e015789) | 
`private List< ` [`HttpListenerContext`](WebSocketSharp--Net--HttpListenerContext.md)` > ` [`_ctxQueue`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1a2ce83548a56554c90e7ba772cbd7224b) | 
`private object ` [`_ctxQueueSync`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1ad7d9a67000bdc328623b83ea1eed7d7a) | 
`private Dictionary< ` [`HttpListenerContext](WebSocketSharp--Net--HttpListenerContext.md), [HttpListenerContext`](WebSocketSharp--Net--HttpListenerContext.md)` > ` [`_ctxRegistry`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1ab36fb215befff864ed883121e969703e) | 
`private object ` [`_ctxRegistrySync`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1ade53f9d63842f320b6d018132ce9f790) | 
`private bool ` [`_disposed`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1aa0695b8700eaefdf30302d9b2daf447b) | 
`private bool ` [`_ignoreWriteExceptions`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1a667228ad2045d1bee40e60a72c095972) | 
`private volatile bool ` [`_listening`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1a38e02c1986fb0191b1e70340104b22bb) | 
`private ` [`Logger`](WebSocketSharp--Logger.md)` ` [`_logger`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1ab6e74ad12d98b2369e94b3cb10299a20) | 
`private ` [`HttpListenerPrefixCollection`](WebSocketSharp--Net--HttpListenerPrefixCollection.md)` ` [`_prefixes`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1a9cd682108f9448a2f425c153faddf3e0) | 
`private string ` [`_realm`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1a7bc2b82b0e3f1b9f47f595918f1baa87) | 
`private bool ` [`_reuseAddress`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1a60ce73ddecfd2200aa3a2b22feec4aed) | 
`private ` [`ServerSslConfiguration`](WebSocketSharp--Net--ServerSslConfiguration.md)` ` [`_sslConfig`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1af4cb9aca2106370fa285c159de698e49) | 
`private Func< IIdentity, ` [`NetworkCredential`](WebSocketSharp--Net--NetworkCredential.md)` > ` [`_userCredFinder`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1add646c78b6352224b90bc76c70f4a2ae) | 
`private List< ` [`HttpListenerAsyncResult`](WebSocketSharp--Net--HttpListenerAsyncResult.md)` > ` [`_waitQueue`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1a975b6e277f9e483fabbb8dda761e5def) | 
`private object ` [`_waitQueueSync`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1aed87b638df254f920a629898e3a973fd) | 
`private void ` [`cleanupConnections`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1ac6fa91d4c9285129ed9c05de9bc2754a)`()` | 
`private void ` [`cleanupContextQueue`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1af2260ae6f266eb9dc394b3f48c160e3e)`(bool sendServiceUnavailable)` | 
`private void ` [`cleanupContextRegistry`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1a533e62192b465bb3f8bed28697ca9f35)`()` | 
`private void ` [`cleanupWaitQueue`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1ade84a476cba7cb95587d763ef36d53a6)`(Exception exception)` | 
`private void ` [`close`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1ac55aa072031a68a49d85a2d72496ab80)`(bool force)` | 
`private ` [`HttpListenerAsyncResult`](WebSocketSharp--Net--HttpListenerAsyncResult.md)` ` [`getAsyncResultFromQueue`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1a55f6711dcf81409d6a1dae95634bb046)`()` | 
`private ` [`HttpListenerContext`](WebSocketSharp--Net--HttpListenerContext.md)` ` [`getContextFromQueue`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1ad15e5a24393fe208a2ea35e4ed3aed0d)`()` | 
`private void IDisposable. ` [`Dispose`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1a44dd5de4474284f22b70c3e0fbdc07f4)`()` | Releases all resources used by the listener.
`private static static ` [`HttpListener`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1a4b5af2a84aef081f430f14b46ef37d99)`()` | 

## Members

##### `package bool ` [`IsDisposed`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1ab96a71c70205ed1aa4af692ee7f35403) 

##### `package bool ` [`ReuseAddress`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1a923e721e9823564407e4d83b8a49fb9b) 

##### `public ` [`AuthenticationSchemes`](WebSocketSharp--Net.md)` ` [`AuthenticationSchemes`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1ab2f4176cabceeee69cb96c6d68ab5f05) 

Gets or sets the scheme used to authenticate the clients.

One of the [WebSocketSharp.Net.AuthenticationSchemes](WebSocketSharp--Net.md) enum values, represents the scheme used to authenticate the clients. The default value is WebSocketSharp.Net.AuthenticationSchemes.Anonymous. 

#### Exceptions
* `ObjectDisposedException` This listener has been closed.

##### `public Func< ` [`HttpListenerRequest](WebSocketSharp--Net--HttpListenerRequest.md), [AuthenticationSchemes`](WebSocketSharp--Net.md)` > ` [`AuthenticationSchemeSelector`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1af6eaeee559b38c8c524cbc06e8ec6232) 

Gets or sets the delegate called to select the scheme used to authenticate the clients.

If you set this property, the listener uses the authentication scheme selected by the delegate for each request. Or if you don't set, the listener uses the value of the HttpListener.AuthenticationSchemes property as the authentication scheme for all requests. 

A `Func<HttpListenerRequest, AuthenticationSchemes>` delegate that references the method used to select an authentication scheme. The default value is `null`. 

#### Exceptions
* `ObjectDisposedException` This listener has been closed.

##### `public string ` [`CertificateFolderPath`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1abc2f63e7ede69b59b8e6ef25869145d5) 

Gets or sets the path to the folder in which stores the certificate files used to authenticate the server on the secure connection.

This property represents the path to the folder in which stores the certificate files associated with each port number of added URI prefixes. A set of the certificate files is a pair of the `'port number'.cer` (DER) and `'port number'.key` (DER, RSA Private Key). 

If this property is `null` or empty, the result of `System.Environment.GetFolderPath (Environment.SpecialFolder.ApplicationData)` is used as the default path. 

A string that represents the path to the folder in which stores the certificate files. The default value is `null`. 

#### Exceptions
* `ObjectDisposedException` This listener has been closed.

##### `public bool ` [`IgnoreWriteExceptions`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1aa16e1537c56cc89c560f4c0be96263b0) 

Gets or sets a value indicating whether the listener returns exceptions that occur when sending the response to the client.

`true` if the listener shouldn't return those exceptions; otherwise, `false`. The default value is `false`. 

#### Exceptions
* `ObjectDisposedException` This listener has been closed.

##### `public bool ` [`IsListening`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1aa989b9618104958f4a259fa37fb939d8) 

Gets a value indicating whether the listener has been started.

`true` if the listener has been started; otherwise, `false`.

##### `public bool ` [`IsSupported`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1a25e3c2c0333e001d5887b8549960d97d) 

Gets a value indicating whether the listener can be used with the current operating system.

`true`.

##### `public ` [`Logger`](WebSocketSharp--Logger.md)` ` [`Log`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1af2ed886ec3d2b2fd42fd0c5dad2f8cc5) 

Gets the logging functions.

The default logging level is LogLevel.Error. If you would like to change it, you should set the `Log.Level` property to any of the LogLevel enum values. 

A Logger that provides the logging functions.

##### `public ` [`HttpListenerPrefixCollection`](WebSocketSharp--Net--HttpListenerPrefixCollection.md)` ` [`Prefixes`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1ab1c80e2a715f1bc832b7ab6d90774f42) 

Gets the URI prefixes handled by the listener.

A HttpListenerPrefixCollection that contains the URI prefixes. 

#### Exceptions
* `ObjectDisposedException` This listener has been closed.

##### `public string ` [`Realm`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1a52a674ec0b4dc0d9e94f9ff3c47c583a) 

Gets or sets the name of the realm associated with the listener.

If this property is `null` or empty, `"SECRET AREA"` will be used as the name of the realm. 

A string that represents the name of the realm. The default value is `null`. 

#### Exceptions
* `ObjectDisposedException` This listener has been closed.

##### `public ` [`ServerSslConfiguration`](WebSocketSharp--Net--ServerSslConfiguration.md)` ` [`SslConfiguration`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1aa41bf1c36ef66f799331bb3ea0204ca9) 

Gets or sets the SSL configuration used to authenticate the server and optionally the client for secure connection.

A ServerSslConfiguration that represents the configuration used to authenticate the server and optionally the client for secure connection. 

#### Exceptions
* `ObjectDisposedException` This listener has been closed.

##### `public bool ` [`UnsafeConnectionNtlmAuthentication`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1aa2238ae56a0f27532704a5b85d045e25) 

Gets or sets a value indicating whether, when NTLM authentication is used, the authentication information of first request is used to authenticate additional requests on the same connection.

This property isn't currently supported and always throws a NotSupportedException. 

`true` if the authentication information of first request is used; otherwise, `false`. 

#### Exceptions
* `NotSupportedException` Any use of this property.

##### `public Func< IIdentity, ` [`NetworkCredential`](WebSocketSharp--Net--NetworkCredential.md)` > ` [`UserCredentialsFinder`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1acd9009b71f94aed4202e9e2fa19cc1d1) 

Gets or sets the delegate called to find the credentials for an identity used to authenticate a client.

A `Func<IIdentity, NetworkCredential>` delegate that references the method used to find the credentials. The default value is `null`. 

#### Exceptions
* `ObjectDisposedException` This listener has been closed.

##### `public ` [`HttpListener`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1ac3e7570badee6dbd180eb3e428ac57f1)`()` 

Initializes a new instance of the HttpListener class.

##### `public void ` [`Abort`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1a12b9283f52eaf7610afe4b04fbca2ff0)`()` 

Shuts down the listener immediately.

##### `public IAsyncResult ` [`BeginGetContext`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1a023bc9d06972faaf48bfbfd86d532bf0)`(AsyncCallback callback, Object state)` 

Begins getting an incoming request asynchronously.

This asynchronous operation must be completed by calling the `EndGetContext` method. Typically, the method is invoked by the *callback*  delegate. 

#### Returns
An IAsyncResult that represents the status of the asynchronous operation. 

#### Parameters
* `callback` An AsyncCallback delegate that references the method to invoke when the asynchronous operation completes. 

* `state` An object that represents a user defined object to pass to the *callback*  delegate. 

#### Exceptions
* `InvalidOperationException` This listener has no URI prefix on which listens. 

-or- 

This listener hasn't been started, or is currently stopped. 

* `ObjectDisposedException` This listener has been closed.

##### `public void ` [`Close`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1a7f7a3199c392465d0767c6506c1af5b4)`()` 

Shuts down the listener.

##### `public ` [`HttpListenerContext`](WebSocketSharp--Net--HttpListenerContext.md)` ` [`EndGetContext`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1a5658742d6d2009adebc0efa96747dd08)`(IAsyncResult asyncResult)` 

Ends an asynchronous operation to get an incoming request.

This method completes an asynchronous operation started by calling the `BeginGetContext` method. 

#### Returns
A HttpListenerContext that represents a request. 

#### Parameters
* `asyncResult` An IAsyncResult obtained by calling the `BeginGetContext` method. 

#### Exceptions
* `ArgumentNullException` *asyncResult*  is `null`. 

* `ArgumentException` *asyncResult*  wasn't obtained by calling the `BeginGetContext` method. 

* `InvalidOperationException` This method was already called for the specified *asyncResult* . 

* `ObjectDisposedException` This listener has been closed.

##### `public ` [`HttpListenerContext`](WebSocketSharp--Net--HttpListenerContext.md)` ` [`GetContext`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1a84ef6c2f87fc0851891c2e2ab9e43430)`()` 

Gets an incoming request.

This method waits for an incoming request, and returns when a request is received. 

#### Returns
A HttpListenerContext that represents a request. 

#### Exceptions
* `InvalidOperationException` This listener has no URI prefix on which listens. 

-or- 

This listener hasn't been started, or is currently stopped. 

* `ObjectDisposedException` This listener has been closed.

##### `public void ` [`Start`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1a07aaf1227e4d645f15e0a964f54ef291)`()` 

Starts receiving incoming requests.

#### Exceptions
* `ObjectDisposedException` This listener has been closed.

##### `public void ` [`Stop`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1a17a237457e57625296e6b24feb19c60a)`()` 

Stops receiving incoming requests.

#### Exceptions
* `ObjectDisposedException` This listener has been closed.

##### `private ` [`AuthenticationSchemes`](WebSocketSharp--Net.md)` ` [`_authSchemes`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1ac2cfce2148d2f47655c0a1c4b048c07e) 

##### `private Func< ` [`HttpListenerRequest](WebSocketSharp--Net--HttpListenerRequest.md), [AuthenticationSchemes`](WebSocketSharp--Net.md)` > ` [`_authSchemeSelector`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1ae347a57717f3450131827af52f8bd391) 

##### `private string ` [`_certFolderPath`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1ab629f6b98d73781678e6233be5f6aa35) 

##### `private Dictionary< ` [`HttpConnection](WebSocketSharp--Net--HttpConnection.md), [HttpConnection`](WebSocketSharp--Net--HttpConnection.md)` > ` [`_connections`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1a08dab1e1a4ffb24111729120b65f4f79) 

##### `private object ` [`_connectionsSync`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1a7e72e3355f1a90b1b9de44c59e015789) 

##### `private List< ` [`HttpListenerContext`](WebSocketSharp--Net--HttpListenerContext.md)` > ` [`_ctxQueue`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1a2ce83548a56554c90e7ba772cbd7224b) 

##### `private object ` [`_ctxQueueSync`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1ad7d9a67000bdc328623b83ea1eed7d7a) 

##### `private Dictionary< ` [`HttpListenerContext](WebSocketSharp--Net--HttpListenerContext.md), [HttpListenerContext`](WebSocketSharp--Net--HttpListenerContext.md)` > ` [`_ctxRegistry`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1ab36fb215befff864ed883121e969703e) 

##### `private object ` [`_ctxRegistrySync`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1ade53f9d63842f320b6d018132ce9f790) 

##### `private bool ` [`_disposed`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1aa0695b8700eaefdf30302d9b2daf447b) 

##### `private bool ` [`_ignoreWriteExceptions`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1a667228ad2045d1bee40e60a72c095972) 

##### `private volatile bool ` [`_listening`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1a38e02c1986fb0191b1e70340104b22bb) 

##### `private ` [`Logger`](WebSocketSharp--Logger.md)` ` [`_logger`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1ab6e74ad12d98b2369e94b3cb10299a20) 

##### `private ` [`HttpListenerPrefixCollection`](WebSocketSharp--Net--HttpListenerPrefixCollection.md)` ` [`_prefixes`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1a9cd682108f9448a2f425c153faddf3e0) 

##### `private string ` [`_realm`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1a7bc2b82b0e3f1b9f47f595918f1baa87) 

##### `private bool ` [`_reuseAddress`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1a60ce73ddecfd2200aa3a2b22feec4aed) 

##### `private ` [`ServerSslConfiguration`](WebSocketSharp--Net--ServerSslConfiguration.md)` ` [`_sslConfig`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1af4cb9aca2106370fa285c159de698e49) 

##### `private Func< IIdentity, ` [`NetworkCredential`](WebSocketSharp--Net--NetworkCredential.md)` > ` [`_userCredFinder`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1add646c78b6352224b90bc76c70f4a2ae) 

##### `private List< ` [`HttpListenerAsyncResult`](WebSocketSharp--Net--HttpListenerAsyncResult.md)` > ` [`_waitQueue`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1a975b6e277f9e483fabbb8dda761e5def) 

##### `private object ` [`_waitQueueSync`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1aed87b638df254f920a629898e3a973fd) 

##### `private void ` [`cleanupConnections`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1ac6fa91d4c9285129ed9c05de9bc2754a)`()` 

##### `private void ` [`cleanupContextQueue`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1af2260ae6f266eb9dc394b3f48c160e3e)`(bool sendServiceUnavailable)` 

##### `private void ` [`cleanupContextRegistry`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1a533e62192b465bb3f8bed28697ca9f35)`()` 

##### `private void ` [`cleanupWaitQueue`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1ade84a476cba7cb95587d763ef36d53a6)`(Exception exception)` 

##### `private void ` [`close`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1ac55aa072031a68a49d85a2d72496ab80)`(bool force)` 

##### `private ` [`HttpListenerAsyncResult`](WebSocketSharp--Net--HttpListenerAsyncResult.md)` ` [`getAsyncResultFromQueue`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1a55f6711dcf81409d6a1dae95634bb046)`()` 

##### `private ` [`HttpListenerContext`](WebSocketSharp--Net--HttpListenerContext.md)` ` [`getContextFromQueue`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1ad15e5a24393fe208a2ea35e4ed3aed0d)`()` 

##### `private void IDisposable. ` [`Dispose`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1a44dd5de4474284f22b70c3e0fbdc07f4)`()` 

Releases all resources used by the listener.

##### `private static static ` [`HttpListener`](#class_web_socket_sharp_1_1_net_1_1_http_listener_1a4b5af2a84aef081f430f14b46ef37d99)`()` 

