# class `WebSocketSharp::Server::HttpRequestEventArgs` 

```
class WebSocketSharp::Server::HttpRequestEventArgs
  : public EventArgs
```

Represents the event data for the HTTP request events of the HttpServer.

An HTTP request event occurs when the HttpServer receives an HTTP request. 

You should access the Request property if you would like to get the request data sent from a client. 

And you should access the Response property if you would like to get the response data to return to the client.

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public ` [`HttpListenerRequest`](WebSocketSharp--Net--HttpListenerRequest.md)` ` [`Request`](#class_web_socket_sharp_1_1_server_1_1_http_request_event_args_1a0f2368ed8a6de977e8c6ceba56420c8a) | Gets the request data sent from a client.
`public ` [`HttpListenerResponse`](WebSocketSharp--Net--HttpListenerResponse.md)` ` [`Response`](#class_web_socket_sharp_1_1_server_1_1_http_request_event_args_1a6e691750661f8d2066e59078e0e3078d) | Gets the response data to return to the client.
`public IPrincipal ` [`User`](#class_web_socket_sharp_1_1_server_1_1_http_request_event_args_1adf66d13cfa13babb9d8dba518c5413a3) | Gets the information for the client.
`public byte[] ` [`ReadFile`](#class_web_socket_sharp_1_1_server_1_1_http_request_event_args_1a3a7a86e293388f22b9be1b8ea537bb22)`(string path)` | Reads the specified file from the document folder of the HttpServer.
`public bool ` [`TryReadFile`](#class_web_socket_sharp_1_1_server_1_1_http_request_event_args_1a0166e86c45156ff217edd1cfabec409e)`(string path, out byte[] contents)` | Tries to read the specified file from the document folder of the HttpServer.
`private ` [`HttpListenerContext`](WebSocketSharp--Net--HttpListenerContext.md)` ` [`_context`](#class_web_socket_sharp_1_1_server_1_1_http_request_event_args_1acce8d94df9e8bf7da6c2d6888e9f5391) | 
`private string ` [`_docRootPath`](#class_web_socket_sharp_1_1_server_1_1_http_request_event_args_1a5d44ed0d3ffdceebe6c80c84608deb02) | 
`private string ` [`createFilePath`](#class_web_socket_sharp_1_1_server_1_1_http_request_event_args_1a3f45464cd0ec94df224210340bb572ea)`(string childPath)` | 
`private static bool ` [`tryReadFile`](#class_web_socket_sharp_1_1_server_1_1_http_request_event_args_1a6c58e5473f2351f98dafa0026857cb59)`(string path, out byte[] contents)` | 

## Members

##### `public ` [`HttpListenerRequest`](WebSocketSharp--Net--HttpListenerRequest.md)` ` [`Request`](#class_web_socket_sharp_1_1_server_1_1_http_request_event_args_1a0f2368ed8a6de977e8c6ceba56420c8a) 

Gets the request data sent from a client.

A HttpListenerRequest that provides the methods and properties for the request data.

##### `public ` [`HttpListenerResponse`](WebSocketSharp--Net--HttpListenerResponse.md)` ` [`Response`](#class_web_socket_sharp_1_1_server_1_1_http_request_event_args_1a6e691750661f8d2066e59078e0e3078d) 

Gets the response data to return to the client.

A HttpListenerResponse that provides the methods and properties for the response data.

##### `public IPrincipal ` [`User`](#class_web_socket_sharp_1_1_server_1_1_http_request_event_args_1adf66d13cfa13babb9d8dba518c5413a3) 

Gets the information for the client.

A IPrincipal instance or `null` if not authenticated. 

That instance describes the identity, authentication scheme, and security roles for the client.

##### `public byte[] ` [`ReadFile`](#class_web_socket_sharp_1_1_server_1_1_http_request_event_args_1a3a7a86e293388f22b9be1b8ea537bb22)`(string path)` 

Reads the specified file from the document folder of the HttpServer.

#### Returns
An array of byte or `null` if it fails. 

That array receives the contents of the file. 

#### Parameters
* `path` A string that represents a virtual path to find the file from the document folder. 

#### Exceptions
* `ArgumentNullException` *path*  is `null`. 

* `ArgumentException` *path*  is an empty string. 

-or- 

*path*  contains "..".

##### `public bool ` [`TryReadFile`](#class_web_socket_sharp_1_1_server_1_1_http_request_event_args_1a0166e86c45156ff217edd1cfabec409e)`(string path, out byte[] contents)` 

Tries to read the specified file from the document folder of the HttpServer.

#### Returns
`true` if it succeeds to read; otherwise, `false`. 

#### Parameters
* `path` A string that represents a virtual path to find the file from the document folder. 

* `contents` When this method returns, an array of byte or `null` if it fails. 

That array receives the contents of the file. 

#### Exceptions
* `ArgumentNullException` *path*  is `null`. 

* `ArgumentException` *path*  is an empty string. 

-or- 

*path*  contains "..".

##### `private ` [`HttpListenerContext`](WebSocketSharp--Net--HttpListenerContext.md)` ` [`_context`](#class_web_socket_sharp_1_1_server_1_1_http_request_event_args_1acce8d94df9e8bf7da6c2d6888e9f5391) 

##### `private string ` [`_docRootPath`](#class_web_socket_sharp_1_1_server_1_1_http_request_event_args_1a5d44ed0d3ffdceebe6c80c84608deb02) 

##### `private string ` [`createFilePath`](#class_web_socket_sharp_1_1_server_1_1_http_request_event_args_1a3f45464cd0ec94df224210340bb572ea)`(string childPath)` 

##### `private static bool ` [`tryReadFile`](#class_web_socket_sharp_1_1_server_1_1_http_request_event_args_1a6c58e5473f2351f98dafa0026857cb59)`(string path, out byte[] contents)` 

