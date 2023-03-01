# class `WebSocketSharp::Net::RequestStream` 

```
class WebSocketSharp::Net::RequestStream
  : public Stream
```

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public override bool ` [`CanRead`](#class_web_socket_sharp_1_1_net_1_1_request_stream_1ad722f13be7b117693e904035b7135f41) | 
`public override bool ` [`CanSeek`](#class_web_socket_sharp_1_1_net_1_1_request_stream_1a675dca5afdd0baef24cc22565586a862) | 
`public override bool ` [`CanWrite`](#class_web_socket_sharp_1_1_net_1_1_request_stream_1aff862cff6542f9483ca72f14f947b818) | 
`public override long ` [`Length`](#class_web_socket_sharp_1_1_net_1_1_request_stream_1a9fb344bf91f4a70b0b8c55de254a82a9) | 
`public override long ` [`Position`](#class_web_socket_sharp_1_1_net_1_1_request_stream_1aabfae0c1ad9dc9edd0dd69ce87b3281a) | 
`public override IAsyncResult ` [`BeginRead`](#class_web_socket_sharp_1_1_net_1_1_request_stream_1aa0ee0d6f27da4602ae9472eafef9b34e)`(byte[] buffer, int offset, int count, AsyncCallback callback, object state)` | 
`public override IAsyncResult ` [`BeginWrite`](#class_web_socket_sharp_1_1_net_1_1_request_stream_1a2a71bc58ffc661fc14381b76e392cad0)`(byte[] buffer, int offset, int count, AsyncCallback callback, object state)` | 
`public override void ` [`Close`](#class_web_socket_sharp_1_1_net_1_1_request_stream_1ab390fa8607d8d415cb28667bb2137bb5)`()` | 
`public override int ` [`EndRead`](#class_web_socket_sharp_1_1_net_1_1_request_stream_1a71be3895111be3dc6c1f136cde65f3b0)`(IAsyncResult asyncResult)` | 
`public override void ` [`EndWrite`](#class_web_socket_sharp_1_1_net_1_1_request_stream_1a1537aeaaf4ea251f01a3a474ab7d52dd)`(IAsyncResult asyncResult)` | 
`public override void ` [`Flush`](#class_web_socket_sharp_1_1_net_1_1_request_stream_1aa7fb788b182fe334800777f5e2882dcb)`()` | 
`public override int ` [`Read`](#class_web_socket_sharp_1_1_net_1_1_request_stream_1ac80b086ec9c49baeb2bc4a5f2c8f36db)`(byte[] buffer, int offset, int count)` | 
`public override long ` [`Seek`](#class_web_socket_sharp_1_1_net_1_1_request_stream_1a4d429be1fb6d7a7009dee7e9123cf592)`(long offset, SeekOrigin origin)` | 
`public override void ` [`SetLength`](#class_web_socket_sharp_1_1_net_1_1_request_stream_1a5b64e99bd560495589e696be3b2a6c9e)`(long value)` | 
`public override void ` [`Write`](#class_web_socket_sharp_1_1_net_1_1_request_stream_1ab7411151696464c81d02266936fbefaa)`(byte[] buffer, int offset, int count)` | 
`private long ` [`_bodyLeft`](#class_web_socket_sharp_1_1_net_1_1_request_stream_1abdddfce2752ce20e74500f98c23ca249) | 
`private byte[] ` [`_buffer`](#class_web_socket_sharp_1_1_net_1_1_request_stream_1afdf89bf39fd5e5e4b157398fbd2724e4) | 
`private int ` [`_count`](#class_web_socket_sharp_1_1_net_1_1_request_stream_1a83852750be9a651f15936176472dd5c0) | 
`private bool ` [`_disposed`](#class_web_socket_sharp_1_1_net_1_1_request_stream_1aa0695b8700eaefdf30302d9b2daf447b) | 
`private int ` [`_offset`](#class_web_socket_sharp_1_1_net_1_1_request_stream_1a53da2341ea4433867b68756f20019d5c) | 
`private Stream ` [`_stream`](#class_web_socket_sharp_1_1_net_1_1_request_stream_1ae5401654b26ad72d9da131e0a3db7eb8) | 
`private int ` [`fillFromBuffer`](#class_web_socket_sharp_1_1_net_1_1_request_stream_1a333764bb28508844de84af995c57e5f2)`(byte[] buffer, int offset, int count)` | 

## Members

##### `public override bool ` [`CanRead`](#class_web_socket_sharp_1_1_net_1_1_request_stream_1ad722f13be7b117693e904035b7135f41) 

##### `public override bool ` [`CanSeek`](#class_web_socket_sharp_1_1_net_1_1_request_stream_1a675dca5afdd0baef24cc22565586a862) 

##### `public override bool ` [`CanWrite`](#class_web_socket_sharp_1_1_net_1_1_request_stream_1aff862cff6542f9483ca72f14f947b818) 

##### `public override long ` [`Length`](#class_web_socket_sharp_1_1_net_1_1_request_stream_1a9fb344bf91f4a70b0b8c55de254a82a9) 

##### `public override long ` [`Position`](#class_web_socket_sharp_1_1_net_1_1_request_stream_1aabfae0c1ad9dc9edd0dd69ce87b3281a) 

##### `public override IAsyncResult ` [`BeginRead`](#class_web_socket_sharp_1_1_net_1_1_request_stream_1aa0ee0d6f27da4602ae9472eafef9b34e)`(byte[] buffer, int offset, int count, AsyncCallback callback, object state)` 

##### `public override IAsyncResult ` [`BeginWrite`](#class_web_socket_sharp_1_1_net_1_1_request_stream_1a2a71bc58ffc661fc14381b76e392cad0)`(byte[] buffer, int offset, int count, AsyncCallback callback, object state)` 

##### `public override void ` [`Close`](#class_web_socket_sharp_1_1_net_1_1_request_stream_1ab390fa8607d8d415cb28667bb2137bb5)`()` 

##### `public override int ` [`EndRead`](#class_web_socket_sharp_1_1_net_1_1_request_stream_1a71be3895111be3dc6c1f136cde65f3b0)`(IAsyncResult asyncResult)` 

##### `public override void ` [`EndWrite`](#class_web_socket_sharp_1_1_net_1_1_request_stream_1a1537aeaaf4ea251f01a3a474ab7d52dd)`(IAsyncResult asyncResult)` 

##### `public override void ` [`Flush`](#class_web_socket_sharp_1_1_net_1_1_request_stream_1aa7fb788b182fe334800777f5e2882dcb)`()` 

##### `public override int ` [`Read`](#class_web_socket_sharp_1_1_net_1_1_request_stream_1ac80b086ec9c49baeb2bc4a5f2c8f36db)`(byte[] buffer, int offset, int count)` 

##### `public override long ` [`Seek`](#class_web_socket_sharp_1_1_net_1_1_request_stream_1a4d429be1fb6d7a7009dee7e9123cf592)`(long offset, SeekOrigin origin)` 

##### `public override void ` [`SetLength`](#class_web_socket_sharp_1_1_net_1_1_request_stream_1a5b64e99bd560495589e696be3b2a6c9e)`(long value)` 

##### `public override void ` [`Write`](#class_web_socket_sharp_1_1_net_1_1_request_stream_1ab7411151696464c81d02266936fbefaa)`(byte[] buffer, int offset, int count)` 

##### `private long ` [`_bodyLeft`](#class_web_socket_sharp_1_1_net_1_1_request_stream_1abdddfce2752ce20e74500f98c23ca249) 

##### `private byte[] ` [`_buffer`](#class_web_socket_sharp_1_1_net_1_1_request_stream_1afdf89bf39fd5e5e4b157398fbd2724e4) 

##### `private int ` [`_count`](#class_web_socket_sharp_1_1_net_1_1_request_stream_1a83852750be9a651f15936176472dd5c0) 

##### `private bool ` [`_disposed`](#class_web_socket_sharp_1_1_net_1_1_request_stream_1aa0695b8700eaefdf30302d9b2daf447b) 

##### `private int ` [`_offset`](#class_web_socket_sharp_1_1_net_1_1_request_stream_1a53da2341ea4433867b68756f20019d5c) 

##### `private Stream ` [`_stream`](#class_web_socket_sharp_1_1_net_1_1_request_stream_1ae5401654b26ad72d9da131e0a3db7eb8) 

##### `private int ` [`fillFromBuffer`](#class_web_socket_sharp_1_1_net_1_1_request_stream_1a333764bb28508844de84af995c57e5f2)`(byte[] buffer, int offset, int count)` 

