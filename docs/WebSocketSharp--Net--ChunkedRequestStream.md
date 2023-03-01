# class `WebSocketSharp::Net::ChunkedRequestStream` 

```
class WebSocketSharp::Net::ChunkedRequestStream
  : public RequestStream
```

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`package ` [`ChunkStream`](WebSocketSharp--Net--ChunkStream.md)` ` [`Decoder`](#class_web_socket_sharp_1_1_net_1_1_chunked_request_stream_1a83583c23124196ef5e0bd0d564898506) | 
`public override IAsyncResult ` [`BeginRead`](#class_web_socket_sharp_1_1_net_1_1_chunked_request_stream_1aa0ee0d6f27da4602ae9472eafef9b34e)`(byte[] buffer, int offset, int count, AsyncCallback callback, object state)` | 
`public override void ` [`Close`](#class_web_socket_sharp_1_1_net_1_1_chunked_request_stream_1ab390fa8607d8d415cb28667bb2137bb5)`()` | 
`public override int ` [`EndRead`](#class_web_socket_sharp_1_1_net_1_1_chunked_request_stream_1a71be3895111be3dc6c1f136cde65f3b0)`(IAsyncResult asyncResult)` | 
`public override int ` [`Read`](#class_web_socket_sharp_1_1_net_1_1_chunked_request_stream_1ac80b086ec9c49baeb2bc4a5f2c8f36db)`(byte[] buffer, int offset, int count)` | 
`private ` [`HttpListenerContext`](WebSocketSharp--Net--HttpListenerContext.md)` ` [`_context`](#class_web_socket_sharp_1_1_net_1_1_chunked_request_stream_1acce8d94df9e8bf7da6c2d6888e9f5391) | 
`private ` [`ChunkStream`](WebSocketSharp--Net--ChunkStream.md)` ` [`_decoder`](#class_web_socket_sharp_1_1_net_1_1_chunked_request_stream_1afda7141c6aa80eb6dc8590c525967dc5) | 
`private bool ` [`_disposed`](#class_web_socket_sharp_1_1_net_1_1_chunked_request_stream_1aa0695b8700eaefdf30302d9b2daf447b) | 
`private bool ` [`_noMoreData`](#class_web_socket_sharp_1_1_net_1_1_chunked_request_stream_1a5c16121f5fc4bfdb3f266d3532bfaa9c) | 
`private void ` [`onRead`](#class_web_socket_sharp_1_1_net_1_1_chunked_request_stream_1aba01ae09836359f57fb849555057cc69)`(IAsyncResult asyncResult)` | 

## Members

##### `package ` [`ChunkStream`](WebSocketSharp--Net--ChunkStream.md)` ` [`Decoder`](#class_web_socket_sharp_1_1_net_1_1_chunked_request_stream_1a83583c23124196ef5e0bd0d564898506) 

##### `public override IAsyncResult ` [`BeginRead`](#class_web_socket_sharp_1_1_net_1_1_chunked_request_stream_1aa0ee0d6f27da4602ae9472eafef9b34e)`(byte[] buffer, int offset, int count, AsyncCallback callback, object state)` 

##### `public override void ` [`Close`](#class_web_socket_sharp_1_1_net_1_1_chunked_request_stream_1ab390fa8607d8d415cb28667bb2137bb5)`()` 

##### `public override int ` [`EndRead`](#class_web_socket_sharp_1_1_net_1_1_chunked_request_stream_1a71be3895111be3dc6c1f136cde65f3b0)`(IAsyncResult asyncResult)` 

##### `public override int ` [`Read`](#class_web_socket_sharp_1_1_net_1_1_chunked_request_stream_1ac80b086ec9c49baeb2bc4a5f2c8f36db)`(byte[] buffer, int offset, int count)` 

##### `private ` [`HttpListenerContext`](WebSocketSharp--Net--HttpListenerContext.md)` ` [`_context`](#class_web_socket_sharp_1_1_net_1_1_chunked_request_stream_1acce8d94df9e8bf7da6c2d6888e9f5391) 

##### `private ` [`ChunkStream`](WebSocketSharp--Net--ChunkStream.md)` ` [`_decoder`](#class_web_socket_sharp_1_1_net_1_1_chunked_request_stream_1afda7141c6aa80eb6dc8590c525967dc5) 

##### `private bool ` [`_disposed`](#class_web_socket_sharp_1_1_net_1_1_chunked_request_stream_1aa0695b8700eaefdf30302d9b2daf447b) 

##### `private bool ` [`_noMoreData`](#class_web_socket_sharp_1_1_net_1_1_chunked_request_stream_1a5c16121f5fc4bfdb3f266d3532bfaa9c) 

##### `private void ` [`onRead`](#class_web_socket_sharp_1_1_net_1_1_chunked_request_stream_1aba01ae09836359f57fb849555057cc69)`(IAsyncResult asyncResult)` 

