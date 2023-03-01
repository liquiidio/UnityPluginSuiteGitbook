# class `AnchorLinkSharp::WebSocketWrapper` 

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public WebSocketState ` [`State`](#class_anchor_link_sharp_1_1_web_socket_wrapper_1a966c24306ddaffe83224776895135d4b) | 
`public ` [`WebSocketWrapper`](#class_anchor_link_sharp_1_1_web_socket_wrapper)` ` [`Connect`](#class_anchor_link_sharp_1_1_web_socket_wrapper_1a685fe2391fd8db666828b323207df232)`()` | Connects to the WebSocket server.
`public void ` [`SendMessage`](#class_anchor_link_sharp_1_1_web_socket_wrapper_1a92dca680c62360c29da6980d9a622179)`(string message)` | Send a message to the WebSocket server.
`public async Task ` [`ConnectAsync`](#class_anchor_link_sharp_1_1_web_socket_wrapper_1a86bd3880fbaf34bd7945302f2ae8c34d)`()` | 
`public async Task ` [`ConnectAsync`](#class_anchor_link_sharp_1_1_web_socket_wrapper_1a7fa650ba674d361ff90f08ba20f8c5b0)`(CancellationToken cts)` | 
`public async Task ` [`CloseAsync`](#class_anchor_link_sharp_1_1_web_socket_wrapper_1aef23671d9ac826feac12e827928df001)`(WebSocketCloseStatus closeStatus, string statusDescription, CancellationToken clt) = default` | 
`protected ` [`WebSocketWrapper`](#class_anchor_link_sharp_1_1_web_socket_wrapper_1ab7556e1ee8352871126230d9ad5310da)`(string uri)` | 
`private readonly ClientWebSocket ` [`_ws`](#class_anchor_link_sharp_1_1_web_socket_wrapper_1a0077728dcd210864ec15bb6f56df9397) | 
`private readonly Uri ` [`_uri`](#class_anchor_link_sharp_1_1_web_socket_wrapper_1adc5dbdbb8e36afb4cdcfd681b7d22a5e) | 
`private readonly CancellationTokenSource ` [`_cancellationTokenSource`](#class_anchor_link_sharp_1_1_web_socket_wrapper_1a7497c35e8b85c6d0820a9e9800ca8da6)`= new CancellationTokenSource()` | 
`private readonly CancellationToken ` [`_cancellationToken`](#class_anchor_link_sharp_1_1_web_socket_wrapper_1ae75f89cd3db480a08927706bf42509b3) | 
`private async void ` [`SendMessageAsync`](#class_anchor_link_sharp_1_1_web_socket_wrapper_1a414b7797f81f24b83912f5ddd7f33e2a)`(string message)` | 
`private async void ` [`StartListen`](#class_anchor_link_sharp_1_1_web_socket_wrapper_1a1b8970fc1ba94268efe3be921f1798d8)`()` | 
`public static ` [`WebSocketWrapper`](#class_anchor_link_sharp_1_1_web_socket_wrapper)` ` [`Create`](#class_anchor_link_sharp_1_1_web_socket_wrapper_1a5d6a17bcf371d6b967d7cd51a523b601)`(string uri)` | Creates a new instance.

## Members

##### `public WebSocketState ` [`State`](#class_anchor_link_sharp_1_1_web_socket_wrapper_1a966c24306ddaffe83224776895135d4b) 

##### `public ` [`WebSocketWrapper`](#class_anchor_link_sharp_1_1_web_socket_wrapper)` ` [`Connect`](#class_anchor_link_sharp_1_1_web_socket_wrapper_1a685fe2391fd8db666828b323207df232)`()` 

Connects to the WebSocket server.

#### Returns

##### `public void ` [`SendMessage`](#class_anchor_link_sharp_1_1_web_socket_wrapper_1a92dca680c62360c29da6980d9a622179)`(string message)` 

Send a message to the WebSocket server.

#### Parameters
* `message` The message to send

##### `public async Task ` [`ConnectAsync`](#class_anchor_link_sharp_1_1_web_socket_wrapper_1a86bd3880fbaf34bd7945302f2ae8c34d)`()` 

##### `public async Task ` [`ConnectAsync`](#class_anchor_link_sharp_1_1_web_socket_wrapper_1a7fa650ba674d361ff90f08ba20f8c5b0)`(CancellationToken cts)` 

##### `public async Task ` [`CloseAsync`](#class_anchor_link_sharp_1_1_web_socket_wrapper_1aef23671d9ac826feac12e827928df001)`(WebSocketCloseStatus closeStatus, string statusDescription, CancellationToken clt) = default` 

##### `protected ` [`WebSocketWrapper`](#class_anchor_link_sharp_1_1_web_socket_wrapper_1ab7556e1ee8352871126230d9ad5310da)`(string uri)` 

##### `private readonly ClientWebSocket ` [`_ws`](#class_anchor_link_sharp_1_1_web_socket_wrapper_1a0077728dcd210864ec15bb6f56df9397) 

##### `private readonly Uri ` [`_uri`](#class_anchor_link_sharp_1_1_web_socket_wrapper_1adc5dbdbb8e36afb4cdcfd681b7d22a5e) 

##### `private readonly CancellationTokenSource ` [`_cancellationTokenSource`](#class_anchor_link_sharp_1_1_web_socket_wrapper_1a7497c35e8b85c6d0820a9e9800ca8da6)`= new CancellationTokenSource()` 

##### `private readonly CancellationToken ` [`_cancellationToken`](#class_anchor_link_sharp_1_1_web_socket_wrapper_1ae75f89cd3db480a08927706bf42509b3) 

##### `private async void ` [`SendMessageAsync`](#class_anchor_link_sharp_1_1_web_socket_wrapper_1a414b7797f81f24b83912f5ddd7f33e2a)`(string message)` 

##### `private async void ` [`StartListen`](#class_anchor_link_sharp_1_1_web_socket_wrapper_1a1b8970fc1ba94268efe3be921f1798d8)`()` 

##### `public static ` [`WebSocketWrapper`](#class_anchor_link_sharp_1_1_web_socket_wrapper)` ` [`Create`](#class_anchor_link_sharp_1_1_web_socket_wrapper_1a5d6a17bcf371d6b967d7cd51a523b601)`(string uri)` 

Creates a new instance.

#### Parameters
* `uri` The URI of the WebSocket server.

#### Returns

