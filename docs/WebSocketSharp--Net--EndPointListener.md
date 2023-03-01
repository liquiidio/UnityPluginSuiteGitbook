# class `WebSocketSharp::Net::EndPointListener` 

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public IPAddress ` [`Address`](#class_web_socket_sharp_1_1_net_1_1_end_point_listener_1a71b78b11b2ca8123b86f6ba4f5ec4a19) | 
`public bool ` [`IsSecure`](#class_web_socket_sharp_1_1_net_1_1_end_point_listener_1adb59d1044fe46ad2ddd774ccbc267db1) | 
`public int ` [`Port`](#class_web_socket_sharp_1_1_net_1_1_end_point_listener_1a91b1a1342df7fe9e51fb5dfc4999dfe8) | 
`public ` [`ServerSslConfiguration`](WebSocketSharp--Net--ServerSslConfiguration.md)` ` [`SslConfiguration`](#class_web_socket_sharp_1_1_net_1_1_end_point_listener_1aa41bf1c36ef66f799331bb3ea0204ca9) | 
`public void ` [`AddPrefix`](#class_web_socket_sharp_1_1_net_1_1_end_point_listener_1a8e3e1b87077522fc590216644e8996f0)`(` [`HttpListenerPrefix`](WebSocketSharp--Net--HttpListenerPrefix.md)` prefix)` | 
`public void ` [`Close`](#class_web_socket_sharp_1_1_net_1_1_end_point_listener_1a7f7a3199c392465d0767c6506c1af5b4)`()` | 
`public void ` [`RemovePrefix`](#class_web_socket_sharp_1_1_net_1_1_end_point_listener_1a79c440205ab76aa16cc748568c1a1cd2)`(` [`HttpListenerPrefix`](WebSocketSharp--Net--HttpListenerPrefix.md)` prefix)` | 
`private List< ` [`HttpListenerPrefix`](WebSocketSharp--Net--HttpListenerPrefix.md)` > ` [`_all`](#class_web_socket_sharp_1_1_net_1_1_end_point_listener_1a46d12d50b6e8593623b7eff05d99232c) | 
`private IPEndPoint ` [`_endpoint`](#class_web_socket_sharp_1_1_net_1_1_end_point_listener_1a478dc17ebc4783c82947c00f2aab5c95) | 
`private List< ` [`HttpListenerPrefix`](WebSocketSharp--Net--HttpListenerPrefix.md)` > ` [`_prefixes`](#class_web_socket_sharp_1_1_net_1_1_end_point_listener_1a34784bf1aba451d21e010b9f5771873b) | 
`private bool ` [`_secure`](#class_web_socket_sharp_1_1_net_1_1_end_point_listener_1a2f7b5b309c5830b8532939ca02946b44) | 
`private Socket ` [`_socket`](#class_web_socket_sharp_1_1_net_1_1_end_point_listener_1a19c179c3753ee778675a7eb82548f554) | 
`private ` [`ServerSslConfiguration`](WebSocketSharp--Net--ServerSslConfiguration.md)` ` [`_sslConfig`](#class_web_socket_sharp_1_1_net_1_1_end_point_listener_1af4cb9aca2106370fa285c159de698e49) | 
`private List< ` [`HttpListenerPrefix`](WebSocketSharp--Net--HttpListenerPrefix.md)` > ` [`_unhandled`](#class_web_socket_sharp_1_1_net_1_1_end_point_listener_1a254038313a806eeccd7001304ffdcc97) | 
`private List< ` [`HttpConnection`](WebSocketSharp--Net--HttpConnection.md)` > ` [`_unregistered`](#class_web_socket_sharp_1_1_net_1_1_end_point_listener_1ac62a4900699d6da3f99e594f922a4d3f) | 
`private object ` [`_unregisteredSync`](#class_web_socket_sharp_1_1_net_1_1_end_point_listener_1a7d82a944c85c7a6cdf2049197195c0ea) | 
`private void ` [`clearConnections`](#class_web_socket_sharp_1_1_net_1_1_end_point_listener_1ab2e147bafa56b32ac4e1eca19c29d678)`()` | 
`private void ` [`leaveIfNoPrefix`](#class_web_socket_sharp_1_1_net_1_1_end_point_listener_1a35d52d3cdb9cadbbb1fd8a3d7c6d0ccb)`()` | 
`private static static ` [`EndPointListener`](#class_web_socket_sharp_1_1_net_1_1_end_point_listener_1aa29c3efda33dff0fa4637e79ea4e5520)`()` | 
`private static void ` [`addSpecial`](#class_web_socket_sharp_1_1_net_1_1_end_point_listener_1ad8f30164c09eefd97f53f3a77b9f92e7)`(List< ` [`HttpListenerPrefix`](WebSocketSharp--Net--HttpListenerPrefix.md)` > prefixes, ` [`HttpListenerPrefix`](WebSocketSharp--Net--HttpListenerPrefix.md)` prefix)` | 
`private static RSACryptoServiceProvider ` [`createRSAFromFile`](#class_web_socket_sharp_1_1_net_1_1_end_point_listener_1a868e91092222f3ed5ef4db7a70c38709)`(string path)` | 
`private static X509Certificate2 ` [`getCertificate`](#class_web_socket_sharp_1_1_net_1_1_end_point_listener_1a2e8de11603ed2f4dbb9b9e6e7357717b)`(int port, string folderPath, X509Certificate2 defaultCertificate)` | 
`private static void ` [`onAccept`](#class_web_socket_sharp_1_1_net_1_1_end_point_listener_1a3faea304e7ffa54c10b5161d15cf956e)`(IAsyncResult asyncResult)` | 
`private static void ` [`processAccepted`](#class_web_socket_sharp_1_1_net_1_1_end_point_listener_1a3973d28651bf8de03d89310834119b35)`(Socket socket, ` [`EndPointListener`](#class_web_socket_sharp_1_1_net_1_1_end_point_listener)` listener)` | 
`private static bool ` [`removeSpecial`](#class_web_socket_sharp_1_1_net_1_1_end_point_listener_1ac47955b0577d06a99df5b78353247aa8)`(List< ` [`HttpListenerPrefix`](WebSocketSharp--Net--HttpListenerPrefix.md)` > prefixes, ` [`HttpListenerPrefix`](WebSocketSharp--Net--HttpListenerPrefix.md)` prefix)` | 
`private static ` [`HttpListener`](WebSocketSharp--Net--HttpListener.md)` ` [`searchHttpListenerFromSpecial`](#class_web_socket_sharp_1_1_net_1_1_end_point_listener_1a715b0aab5e6ed2cde52b0271e1f649b7)`(string path, List< ` [`HttpListenerPrefix`](WebSocketSharp--Net--HttpListenerPrefix.md)` > prefixes)` | 

## Members

##### `public IPAddress ` [`Address`](#class_web_socket_sharp_1_1_net_1_1_end_point_listener_1a71b78b11b2ca8123b86f6ba4f5ec4a19) 

##### `public bool ` [`IsSecure`](#class_web_socket_sharp_1_1_net_1_1_end_point_listener_1adb59d1044fe46ad2ddd774ccbc267db1) 

##### `public int ` [`Port`](#class_web_socket_sharp_1_1_net_1_1_end_point_listener_1a91b1a1342df7fe9e51fb5dfc4999dfe8) 

##### `public ` [`ServerSslConfiguration`](WebSocketSharp--Net--ServerSslConfiguration.md)` ` [`SslConfiguration`](#class_web_socket_sharp_1_1_net_1_1_end_point_listener_1aa41bf1c36ef66f799331bb3ea0204ca9) 

##### `public void ` [`AddPrefix`](#class_web_socket_sharp_1_1_net_1_1_end_point_listener_1a8e3e1b87077522fc590216644e8996f0)`(` [`HttpListenerPrefix`](WebSocketSharp--Net--HttpListenerPrefix.md)` prefix)` 

##### `public void ` [`Close`](#class_web_socket_sharp_1_1_net_1_1_end_point_listener_1a7f7a3199c392465d0767c6506c1af5b4)`()` 

##### `public void ` [`RemovePrefix`](#class_web_socket_sharp_1_1_net_1_1_end_point_listener_1a79c440205ab76aa16cc748568c1a1cd2)`(` [`HttpListenerPrefix`](WebSocketSharp--Net--HttpListenerPrefix.md)` prefix)` 

##### `private List< ` [`HttpListenerPrefix`](WebSocketSharp--Net--HttpListenerPrefix.md)` > ` [`_all`](#class_web_socket_sharp_1_1_net_1_1_end_point_listener_1a46d12d50b6e8593623b7eff05d99232c) 

##### `private IPEndPoint ` [`_endpoint`](#class_web_socket_sharp_1_1_net_1_1_end_point_listener_1a478dc17ebc4783c82947c00f2aab5c95) 

##### `private List< ` [`HttpListenerPrefix`](WebSocketSharp--Net--HttpListenerPrefix.md)` > ` [`_prefixes`](#class_web_socket_sharp_1_1_net_1_1_end_point_listener_1a34784bf1aba451d21e010b9f5771873b) 

##### `private bool ` [`_secure`](#class_web_socket_sharp_1_1_net_1_1_end_point_listener_1a2f7b5b309c5830b8532939ca02946b44) 

##### `private Socket ` [`_socket`](#class_web_socket_sharp_1_1_net_1_1_end_point_listener_1a19c179c3753ee778675a7eb82548f554) 

##### `private ` [`ServerSslConfiguration`](WebSocketSharp--Net--ServerSslConfiguration.md)` ` [`_sslConfig`](#class_web_socket_sharp_1_1_net_1_1_end_point_listener_1af4cb9aca2106370fa285c159de698e49) 

##### `private List< ` [`HttpListenerPrefix`](WebSocketSharp--Net--HttpListenerPrefix.md)` > ` [`_unhandled`](#class_web_socket_sharp_1_1_net_1_1_end_point_listener_1a254038313a806eeccd7001304ffdcc97) 

##### `private List< ` [`HttpConnection`](WebSocketSharp--Net--HttpConnection.md)` > ` [`_unregistered`](#class_web_socket_sharp_1_1_net_1_1_end_point_listener_1ac62a4900699d6da3f99e594f922a4d3f) 

##### `private object ` [`_unregisteredSync`](#class_web_socket_sharp_1_1_net_1_1_end_point_listener_1a7d82a944c85c7a6cdf2049197195c0ea) 

##### `private void ` [`clearConnections`](#class_web_socket_sharp_1_1_net_1_1_end_point_listener_1ab2e147bafa56b32ac4e1eca19c29d678)`()` 

##### `private void ` [`leaveIfNoPrefix`](#class_web_socket_sharp_1_1_net_1_1_end_point_listener_1a35d52d3cdb9cadbbb1fd8a3d7c6d0ccb)`()` 

##### `private static static ` [`EndPointListener`](#class_web_socket_sharp_1_1_net_1_1_end_point_listener_1aa29c3efda33dff0fa4637e79ea4e5520)`()` 

##### `private static void ` [`addSpecial`](#class_web_socket_sharp_1_1_net_1_1_end_point_listener_1ad8f30164c09eefd97f53f3a77b9f92e7)`(List< ` [`HttpListenerPrefix`](WebSocketSharp--Net--HttpListenerPrefix.md)` > prefixes, ` [`HttpListenerPrefix`](WebSocketSharp--Net--HttpListenerPrefix.md)` prefix)` 

##### `private static RSACryptoServiceProvider ` [`createRSAFromFile`](#class_web_socket_sharp_1_1_net_1_1_end_point_listener_1a868e91092222f3ed5ef4db7a70c38709)`(string path)` 

##### `private static X509Certificate2 ` [`getCertificate`](#class_web_socket_sharp_1_1_net_1_1_end_point_listener_1a2e8de11603ed2f4dbb9b9e6e7357717b)`(int port, string folderPath, X509Certificate2 defaultCertificate)` 

##### `private static void ` [`onAccept`](#class_web_socket_sharp_1_1_net_1_1_end_point_listener_1a3faea304e7ffa54c10b5161d15cf956e)`(IAsyncResult asyncResult)` 

##### `private static void ` [`processAccepted`](#class_web_socket_sharp_1_1_net_1_1_end_point_listener_1a3973d28651bf8de03d89310834119b35)`(Socket socket, ` [`EndPointListener`](#class_web_socket_sharp_1_1_net_1_1_end_point_listener)` listener)` 

##### `private static bool ` [`removeSpecial`](#class_web_socket_sharp_1_1_net_1_1_end_point_listener_1ac47955b0577d06a99df5b78353247aa8)`(List< ` [`HttpListenerPrefix`](WebSocketSharp--Net--HttpListenerPrefix.md)` > prefixes, ` [`HttpListenerPrefix`](WebSocketSharp--Net--HttpListenerPrefix.md)` prefix)` 

##### `private static ` [`HttpListener`](WebSocketSharp--Net--HttpListener.md)` ` [`searchHttpListenerFromSpecial`](#class_web_socket_sharp_1_1_net_1_1_end_point_listener_1a715b0aab5e6ed2cde52b0271e1f649b7)`(string path, List< ` [`HttpListenerPrefix`](WebSocketSharp--Net--HttpListenerPrefix.md)` > prefixes)` 

