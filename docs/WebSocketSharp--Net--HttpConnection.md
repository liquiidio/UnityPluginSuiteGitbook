# class `WebSocketSharp::Net::HttpConnection` 

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public bool ` [`IsClosed`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1a26f01b589d00384406eb54173d4d7aca) | 
`public bool ` [`IsLocal`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1a0cf39c5047e171d9636886f431e7b185) | 
`public bool ` [`IsSecure`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1adb59d1044fe46ad2ddd774ccbc267db1) | 
`public IPEndPoint ` [`LocalEndPoint`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1a05807fb7d8cff57fb0c26f6d5f246287) | 
`public IPEndPoint ` [`RemoteEndPoint`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1a1c425bf92b1b37430af4ee10ba965480) | 
`public int ` [`Reuses`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1a46636316adfe4fa486d9707fbf85c91a) | 
`public Stream ` [`Stream`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1a389e58abbb7b2860d86cb6406557a12c) | 
`public void ` [`Close`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1a7f7a3199c392465d0767c6506c1af5b4)`()` | 
`public ` [`RequestStream`](WebSocketSharp--Net--RequestStream.md)` ` [`GetRequestStream`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1a1eb1600990c23052e23debd53e1705d1)`(long contentLength, bool chunked)` | 
`public ` [`ResponseStream`](WebSocketSharp--Net--ResponseStream.md)` ` [`GetResponseStream`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1a943ad761b89ffd656eaa7f5d7925f713)`()` | 
`private byte[] ` [`_buffer`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1afdf89bf39fd5e5e4b157398fbd2724e4) | 
`private ` [`HttpListenerContext`](WebSocketSharp--Net--HttpListenerContext.md)` ` [`_context`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1acce8d94df9e8bf7da6c2d6888e9f5391) | 
`private bool ` [`_contextRegistered`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1a9f88392b9c54d0ec1102d25b2b853adf) | 
`private StringBuilder ` [`_currentLine`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1ac7882fbf7c6a3ed2e141917d8ca77ca1) | 
`private ` [`InputState`](WebSocketSharp--Net.md)` ` [`_inputState`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1aed886a9195a625a814e8a1c507d0c425) | 
`private ` [`RequestStream`](WebSocketSharp--Net--RequestStream.md)` ` [`_inputStream`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1a3f1c452befedd4fee4054715752e6b3c) | 
`private ` [`HttpListener`](WebSocketSharp--Net--HttpListener.md)` ` [`_lastListener`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1a688897f487c945d4c8bf76382bbad969) | 
`private ` [`LineState`](WebSocketSharp--Net.md)` ` [`_lineState`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1a51c0f04eaa0c38581b82ee6250f9da08) | 
`private ` [`EndPointListener`](WebSocketSharp--Net--EndPointListener.md)` ` [`_listener`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1a7a4ee7cdcb58d41a690aa01fb2142bca) | 
`private EndPoint ` [`_localEndPoint`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1a3640132741deeb49ba0fda837dd1ea8d) | 
`private ` [`ResponseStream`](WebSocketSharp--Net--ResponseStream.md)` ` [`_outputStream`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1a5040da5db9a032349232b23e50e861c0) | 
`private int ` [`_position`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1ae8a4c9b3c903b1884e75302a77e41904) | 
`private EndPoint ` [`_remoteEndPoint`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1acf1fffc6901ee1797a1c9be9722690cd) | 
`private MemoryStream ` [`_requestBuffer`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1a9ebcdb3189e51feac6e1fc413ab2d470) | 
`private int ` [`_reuses`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1abbcaa9b19d23b14183f5b8632305ba9f) | 
`private bool ` [`_secure`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1a2f7b5b309c5830b8532939ca02946b44) | 
`private Socket ` [`_socket`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1a19c179c3753ee778675a7eb82548f554) | 
`private ` [`Stream`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1a389e58abbb7b2860d86cb6406557a12c)` ` [`_stream`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1ae5401654b26ad72d9da131e0a3db7eb8) | 
`private object ` [`_sync`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1adbb069fcd0e2b452bc3342bc00739ed8) | 
`private int ` [`_timeout`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1aa66a35e5edf58ce00047afcd1d4f455e) | 
`private Dictionary< int, bool > ` [`_timeoutCanceled`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1af6cfb5dcce6c090fc3d564bf469833a1) | 
`private Timer ` [`_timer`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1a56a939fe014990b98a18a1b720af281b) | 
`private void ` [`close`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1a5ae591df94fc66ccb85cbb6565368bca)`()` | 
`private void ` [`closeSocket`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1ad40053a8165967407f6018538233aea1)`()` | 
`private void ` [`disposeRequestBuffer`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1ab8bcc94dd778a3ac7c85e0ea99c900cb)`()` | 
`private void ` [`disposeStream`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1a860a55380e69b2fb895624c761b39548)`()` | 
`private void ` [`disposeTimer`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1a50713f33e3a9f12baadebe6cb0b96d23)`()` | 
`private void ` [`init`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1a578bdd2dfe5d3579f0426ea65368ce33)`(int timeout)` | 
`private bool ` [`processInput`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1a881c2a679fb43f6cef91d515d299b413)`(byte[] data, int length)` | 
`private string ` [`readLineFrom`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1a2599e47453b4d232220a5f5e50c484e2)`(byte[] buffer, int offset, int length, out int nread)` | 
`private void ` [`registerContext`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1a785477eb21f187f74360c552d020357c)`(` [`HttpListener`](WebSocketSharp--Net--HttpListener.md)` listener)` | 
`private void ` [`removeConnection`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1a02410805b02ad7003255c650db621691)`()` | 
`private void ` [`unregisterContext`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1ae412c9c7f282311a2733c44c4f0ced2f)`()` | 
`private static static ` [`HttpConnection`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1aa792ee4d65ee4e900b9c725a2e1dc964)`()` | 
`private static void ` [`onRead`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1a9f6b35d843f7ead819c1dc5c4ed82144)`(IAsyncResult asyncResult)` | 
`private static void ` [`onTimeout`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1ae9d47b8dcdf2d3f28c33a44ec6c45339)`(object state)` | 

## Members

##### `public bool ` [`IsClosed`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1a26f01b589d00384406eb54173d4d7aca) 

##### `public bool ` [`IsLocal`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1a0cf39c5047e171d9636886f431e7b185) 

##### `public bool ` [`IsSecure`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1adb59d1044fe46ad2ddd774ccbc267db1) 

##### `public IPEndPoint ` [`LocalEndPoint`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1a05807fb7d8cff57fb0c26f6d5f246287) 

##### `public IPEndPoint ` [`RemoteEndPoint`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1a1c425bf92b1b37430af4ee10ba965480) 

##### `public int ` [`Reuses`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1a46636316adfe4fa486d9707fbf85c91a) 

##### `public Stream ` [`Stream`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1a389e58abbb7b2860d86cb6406557a12c) 

##### `public void ` [`Close`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1a7f7a3199c392465d0767c6506c1af5b4)`()` 

##### `public ` [`RequestStream`](WebSocketSharp--Net--RequestStream.md)` ` [`GetRequestStream`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1a1eb1600990c23052e23debd53e1705d1)`(long contentLength, bool chunked)` 

##### `public ` [`ResponseStream`](WebSocketSharp--Net--ResponseStream.md)` ` [`GetResponseStream`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1a943ad761b89ffd656eaa7f5d7925f713)`()` 

##### `private byte[] ` [`_buffer`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1afdf89bf39fd5e5e4b157398fbd2724e4) 

##### `private ` [`HttpListenerContext`](WebSocketSharp--Net--HttpListenerContext.md)` ` [`_context`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1acce8d94df9e8bf7da6c2d6888e9f5391) 

##### `private bool ` [`_contextRegistered`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1a9f88392b9c54d0ec1102d25b2b853adf) 

##### `private StringBuilder ` [`_currentLine`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1ac7882fbf7c6a3ed2e141917d8ca77ca1) 

##### `private ` [`InputState`](WebSocketSharp--Net.md)` ` [`_inputState`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1aed886a9195a625a814e8a1c507d0c425) 

##### `private ` [`RequestStream`](WebSocketSharp--Net--RequestStream.md)` ` [`_inputStream`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1a3f1c452befedd4fee4054715752e6b3c) 

##### `private ` [`HttpListener`](WebSocketSharp--Net--HttpListener.md)` ` [`_lastListener`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1a688897f487c945d4c8bf76382bbad969) 

##### `private ` [`LineState`](WebSocketSharp--Net.md)` ` [`_lineState`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1a51c0f04eaa0c38581b82ee6250f9da08) 

##### `private ` [`EndPointListener`](WebSocketSharp--Net--EndPointListener.md)` ` [`_listener`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1a7a4ee7cdcb58d41a690aa01fb2142bca) 

##### `private EndPoint ` [`_localEndPoint`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1a3640132741deeb49ba0fda837dd1ea8d) 

##### `private ` [`ResponseStream`](WebSocketSharp--Net--ResponseStream.md)` ` [`_outputStream`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1a5040da5db9a032349232b23e50e861c0) 

##### `private int ` [`_position`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1ae8a4c9b3c903b1884e75302a77e41904) 

##### `private EndPoint ` [`_remoteEndPoint`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1acf1fffc6901ee1797a1c9be9722690cd) 

##### `private MemoryStream ` [`_requestBuffer`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1a9ebcdb3189e51feac6e1fc413ab2d470) 

##### `private int ` [`_reuses`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1abbcaa9b19d23b14183f5b8632305ba9f) 

##### `private bool ` [`_secure`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1a2f7b5b309c5830b8532939ca02946b44) 

##### `private Socket ` [`_socket`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1a19c179c3753ee778675a7eb82548f554) 

##### `private ` [`Stream`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1a389e58abbb7b2860d86cb6406557a12c)` ` [`_stream`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1ae5401654b26ad72d9da131e0a3db7eb8) 

##### `private object ` [`_sync`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1adbb069fcd0e2b452bc3342bc00739ed8) 

##### `private int ` [`_timeout`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1aa66a35e5edf58ce00047afcd1d4f455e) 

##### `private Dictionary< int, bool > ` [`_timeoutCanceled`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1af6cfb5dcce6c090fc3d564bf469833a1) 

##### `private Timer ` [`_timer`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1a56a939fe014990b98a18a1b720af281b) 

##### `private void ` [`close`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1a5ae591df94fc66ccb85cbb6565368bca)`()` 

##### `private void ` [`closeSocket`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1ad40053a8165967407f6018538233aea1)`()` 

##### `private void ` [`disposeRequestBuffer`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1ab8bcc94dd778a3ac7c85e0ea99c900cb)`()` 

##### `private void ` [`disposeStream`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1a860a55380e69b2fb895624c761b39548)`()` 

##### `private void ` [`disposeTimer`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1a50713f33e3a9f12baadebe6cb0b96d23)`()` 

##### `private void ` [`init`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1a578bdd2dfe5d3579f0426ea65368ce33)`(int timeout)` 

##### `private bool ` [`processInput`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1a881c2a679fb43f6cef91d515d299b413)`(byte[] data, int length)` 

##### `private string ` [`readLineFrom`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1a2599e47453b4d232220a5f5e50c484e2)`(byte[] buffer, int offset, int length, out int nread)` 

##### `private void ` [`registerContext`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1a785477eb21f187f74360c552d020357c)`(` [`HttpListener`](WebSocketSharp--Net--HttpListener.md)` listener)` 

##### `private void ` [`removeConnection`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1a02410805b02ad7003255c650db621691)`()` 

##### `private void ` [`unregisterContext`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1ae412c9c7f282311a2733c44c4f0ced2f)`()` 

##### `private static static ` [`HttpConnection`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1aa792ee4d65ee4e900b9c725a2e1dc964)`()` 

##### `private static void ` [`onRead`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1a9f6b35d843f7ead819c1dc5c4ed82144)`(IAsyncResult asyncResult)` 

##### `private static void ` [`onTimeout`](#class_web_socket_sharp_1_1_net_1_1_http_connection_1ae9d47b8dcdf2d3f28c33a44ec6c45339)`(object state)` 

