## class `AnchorLinkSharp::WebSocketWrapper` 

```
class AnchorLinkSharp::WebSocketWrapper
  : public MonoBehaviour
```

### Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public WebSocketState `[`State`](#class_anchor_link_sharp_1_1_web_socket_wrapper_1a966c24306ddaffe83224776895135d4b) | 
`public inline async Task `[`Create`](#class_anchor_link_sharp_1_1_web_socket_wrapper_1a86442c5776c9c701b69b9a1b89e2d331)`(string uri)` | Creates a new instance.
`public inline async Task `[`ConnectAsync`](#class_anchor_link_sharp_1_1_web_socket_wrapper_1a86bd3880fbaf34bd7945302f2ae8c34d)`()` | 
`public inline async Task `[`CloseAsync`](#class_anchor_link_sharp_1_1_web_socket_wrapper_1a60f282781ac602de720e4742a9dc376e)`()` | 
`public inline void `[`Clear`](#class_anchor_link_sharp_1_1_web_socket_wrapper_1aa71d36872f416feaa853788a7a7a7ef8)`()` | 
`private string `[`_uri`](#class_anchor_link_sharp_1_1_web_socket_wrapper_1a7ebc558df19b9e661a58ea51ee2aa499) | 
`private bool `[`_newRequest`](#class_anchor_link_sharp_1_1_web_socket_wrapper_1a60a6687fdd89a49fcb64541f433b94b9) | 
`private inline void `[`Update`](#class_anchor_link_sharp_1_1_web_socket_wrapper_1aec0783b5a136e042adcc47bae4fe5291)`()` | 
`private inline void `[`WebSocketOnOnError`](#class_anchor_link_sharp_1_1_web_socket_wrapper_1a2fee57c376761a906e3f2b3c6a9e74cd)`(string errormsg)` | 
`private inline void `[`WebSocketOnOpen`](#class_anchor_link_sharp_1_1_web_socket_wrapper_1ad2c18ea2e10ce78f71a17520f4a20606)`()` | 
`private inline void `[`WebSocketOnOnClose`](#class_anchor_link_sharp_1_1_web_socket_wrapper_1ae48ff1a243aa4dea6a13ab7ee6d9baa2)`(WebSocketCloseCode closeCode)` | 
`private inline void `[`WebSocketOnMessageReceived`](#class_anchor_link_sharp_1_1_web_socket_wrapper_1aa54325c796772820ef651bf820408886)`(byte[] data)` | 
`private inline async void `[`OnDisable`](#class_anchor_link_sharp_1_1_web_socket_wrapper_1a07442cbc23615cbf9ff556b3c144119c)`()` | 
`private inline async void `[`OnApplicationQuit`](#class_anchor_link_sharp_1_1_web_socket_wrapper_1ad62c6267dac9b36be1d8bec9370b3297)`()` | 

### Members

#### `public WebSocketState `[`State`](#class_anchor_link_sharp_1_1_web_socket_wrapper_1a966c24306ddaffe83224776895135d4b) 

#### `public inline async Task `[`Create`](#class_anchor_link_sharp_1_1_web_socket_wrapper_1a86442c5776c9c701b69b9a1b89e2d331)`(string uri)` 

Creates a new instance.

#### Parameters
* `uri` The URI of the WebSocket server.

#### Returns

#### `public inline async Task `[`ConnectAsync`](#class_anchor_link_sharp_1_1_web_socket_wrapper_1a86bd3880fbaf34bd7945302f2ae8c34d)`()` 

#### `public inline async Task `[`CloseAsync`](#class_anchor_link_sharp_1_1_web_socket_wrapper_1a60f282781ac602de720e4742a9dc376e)`()` 

#### `public inline void `[`Clear`](#class_anchor_link_sharp_1_1_web_socket_wrapper_1aa71d36872f416feaa853788a7a7a7ef8)`()` 

#### `private string `[`_uri`](#class_anchor_link_sharp_1_1_web_socket_wrapper_1a7ebc558df19b9e661a58ea51ee2aa499) 

#### `private bool `[`_newRequest`](#class_anchor_link_sharp_1_1_web_socket_wrapper_1a60a6687fdd89a49fcb64541f433b94b9) 

#### `private inline void `[`Update`](#class_anchor_link_sharp_1_1_web_socket_wrapper_1aec0783b5a136e042adcc47bae4fe5291)`()` 

#### `private inline void `[`WebSocketOnOnError`](#class_anchor_link_sharp_1_1_web_socket_wrapper_1a2fee57c376761a906e3f2b3c6a9e74cd)`(string errormsg)` 

#### `private inline void `[`WebSocketOnOpen`](#class_anchor_link_sharp_1_1_web_socket_wrapper_1ad2c18ea2e10ce78f71a17520f4a20606)`()` 

#### `private inline void `[`WebSocketOnOnClose`](#class_anchor_link_sharp_1_1_web_socket_wrapper_1ae48ff1a243aa4dea6a13ab7ee6d9baa2)`(WebSocketCloseCode closeCode)` 

#### `private inline void `[`WebSocketOnMessageReceived`](#class_anchor_link_sharp_1_1_web_socket_wrapper_1aa54325c796772820ef651bf820408886)`(byte[] data)` 

#### `private inline async void `[`OnDisable`](#class_anchor_link_sharp_1_1_web_socket_wrapper_1a07442cbc23615cbf9ff556b3c144119c)`()` 

#### `private inline async void `[`OnApplicationQuit`](#class_anchor_link_sharp_1_1_web_socket_wrapper_1ad62c6267dac9b36be1d8bec9370b3297)`()` 

