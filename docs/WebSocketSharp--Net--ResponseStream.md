# class `WebSocketSharp::Net::ResponseStream` 

```
class WebSocketSharp::Net::ResponseStream
  : public Stream
```

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public override bool ` [`CanRead`](#class_web_socket_sharp_1_1_net_1_1_response_stream_1ad722f13be7b117693e904035b7135f41) | 
`public override bool ` [`CanSeek`](#class_web_socket_sharp_1_1_net_1_1_response_stream_1a675dca5afdd0baef24cc22565586a862) | 
`public override bool ` [`CanWrite`](#class_web_socket_sharp_1_1_net_1_1_response_stream_1aff862cff6542f9483ca72f14f947b818) | 
`public override long ` [`Length`](#class_web_socket_sharp_1_1_net_1_1_response_stream_1a9fb344bf91f4a70b0b8c55de254a82a9) | 
`public override long ` [`Position`](#class_web_socket_sharp_1_1_net_1_1_response_stream_1aabfae0c1ad9dc9edd0dd69ce87b3281a) | 
`public override IAsyncResult ` [`BeginRead`](#class_web_socket_sharp_1_1_net_1_1_response_stream_1aa0ee0d6f27da4602ae9472eafef9b34e)`(byte[] buffer, int offset, int count, AsyncCallback callback, object state)` | 
`public override IAsyncResult ` [`BeginWrite`](#class_web_socket_sharp_1_1_net_1_1_response_stream_1a2a71bc58ffc661fc14381b76e392cad0)`(byte[] buffer, int offset, int count, AsyncCallback callback, object state)` | 
`public override void ` [`Close`](#class_web_socket_sharp_1_1_net_1_1_response_stream_1ab390fa8607d8d415cb28667bb2137bb5)`()` | 
`public override int ` [`EndRead`](#class_web_socket_sharp_1_1_net_1_1_response_stream_1a71be3895111be3dc6c1f136cde65f3b0)`(IAsyncResult asyncResult)` | 
`public override void ` [`EndWrite`](#class_web_socket_sharp_1_1_net_1_1_response_stream_1a1537aeaaf4ea251f01a3a474ab7d52dd)`(IAsyncResult asyncResult)` | 
`public override void ` [`Flush`](#class_web_socket_sharp_1_1_net_1_1_response_stream_1aa7fb788b182fe334800777f5e2882dcb)`()` | 
`public override int ` [`Read`](#class_web_socket_sharp_1_1_net_1_1_response_stream_1ac80b086ec9c49baeb2bc4a5f2c8f36db)`(byte[] buffer, int offset, int count)` | 
`public override long ` [`Seek`](#class_web_socket_sharp_1_1_net_1_1_response_stream_1a4d429be1fb6d7a7009dee7e9123cf592)`(long offset, SeekOrigin origin)` | 
`public override void ` [`SetLength`](#class_web_socket_sharp_1_1_net_1_1_response_stream_1a5b64e99bd560495589e696be3b2a6c9e)`(long value)` | 
`public override void ` [`Write`](#class_web_socket_sharp_1_1_net_1_1_response_stream_1ab7411151696464c81d02266936fbefaa)`(byte[] buffer, int offset, int count)` | 
`protected override void ` [`Dispose`](#class_web_socket_sharp_1_1_net_1_1_response_stream_1a849c3c7f8d08104f0cdb46bee9fe6389)`(bool disposing)` | 
`private MemoryStream ` [`_bodyBuffer`](#class_web_socket_sharp_1_1_net_1_1_response_stream_1a90dfc93d2d73b8bd2717b2c44d605771) | 
`private bool ` [`_disposed`](#class_web_socket_sharp_1_1_net_1_1_response_stream_1aa0695b8700eaefdf30302d9b2daf447b) | 
`private Stream ` [`_innerStream`](#class_web_socket_sharp_1_1_net_1_1_response_stream_1a7bdb1eb36e7f6a6398dccf098774c800) | 
`private ` [`HttpListenerResponse`](WebSocketSharp--Net--HttpListenerResponse.md)` ` [`_response`](#class_web_socket_sharp_1_1_net_1_1_response_stream_1a3801a43a4ae7736589bbba4556e24c11) | 
`private bool ` [`_sendChunked`](#class_web_socket_sharp_1_1_net_1_1_response_stream_1a9f01324db2b61d8e6841a4a9649ce792) | 
`private ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)`< byte[], int, int > ` [`_write`](#class_web_socket_sharp_1_1_net_1_1_response_stream_1acda779816ed096d13b69e5a65d9da379) | 
`private ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)`< byte[], int, int > ` [`_writeBody`](#class_web_socket_sharp_1_1_net_1_1_response_stream_1a4d828e43ef72fed0d0414c28c4f24c3f) | 
`private ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)`< byte[], int, int > ` [`_writeChunked`](#class_web_socket_sharp_1_1_net_1_1_response_stream_1ab5e2689b6cc2eda43c0f49e1006f56cd) | 
`private bool ` [`flush`](#class_web_socket_sharp_1_1_net_1_1_response_stream_1a1242e770280594a10c5d479903dae656)`(bool closing)` | 
`private void ` [`flushBody`](#class_web_socket_sharp_1_1_net_1_1_response_stream_1ac2d867d8d41908ecfbb9c17b2a4efd4c)`(bool closing)` | 
`private bool ` [`flushHeaders`](#class_web_socket_sharp_1_1_net_1_1_response_stream_1a05af3f8deb4cd371719dfb080d11a1af)`()` | 
`private void ` [`writeChunked`](#class_web_socket_sharp_1_1_net_1_1_response_stream_1a1a9dc5c183e47904d9bcbfc6816bb2ac)`(byte[] buffer, int offset, int count)` | 
`private void ` [`writeChunkedWithoutThrowingException`](#class_web_socket_sharp_1_1_net_1_1_response_stream_1a9973aab6cd174de01ec8bf3dafae4c90)`(byte[] buffer, int offset, int count)` | 
`private void ` [`writeWithoutThrowingException`](#class_web_socket_sharp_1_1_net_1_1_response_stream_1a82f3217fcf8420468b0d33c57510e444)`(byte[] buffer, int offset, int count)` | 
`private static static ` [`ResponseStream`](#class_web_socket_sharp_1_1_net_1_1_response_stream_1ac6be9a1b6d9041e15b3edf5b323d18a8)`()` | 
`private static byte[] ` [`getChunkSizeBytes`](#class_web_socket_sharp_1_1_net_1_1_response_stream_1a05f421636a976b96645624bc513f8588)`(int size)` | 

## Members

##### `public override bool ` [`CanRead`](#class_web_socket_sharp_1_1_net_1_1_response_stream_1ad722f13be7b117693e904035b7135f41) 

##### `public override bool ` [`CanSeek`](#class_web_socket_sharp_1_1_net_1_1_response_stream_1a675dca5afdd0baef24cc22565586a862) 

##### `public override bool ` [`CanWrite`](#class_web_socket_sharp_1_1_net_1_1_response_stream_1aff862cff6542f9483ca72f14f947b818) 

##### `public override long ` [`Length`](#class_web_socket_sharp_1_1_net_1_1_response_stream_1a9fb344bf91f4a70b0b8c55de254a82a9) 

##### `public override long ` [`Position`](#class_web_socket_sharp_1_1_net_1_1_response_stream_1aabfae0c1ad9dc9edd0dd69ce87b3281a) 

##### `public override IAsyncResult ` [`BeginRead`](#class_web_socket_sharp_1_1_net_1_1_response_stream_1aa0ee0d6f27da4602ae9472eafef9b34e)`(byte[] buffer, int offset, int count, AsyncCallback callback, object state)` 

##### `public override IAsyncResult ` [`BeginWrite`](#class_web_socket_sharp_1_1_net_1_1_response_stream_1a2a71bc58ffc661fc14381b76e392cad0)`(byte[] buffer, int offset, int count, AsyncCallback callback, object state)` 

##### `public override void ` [`Close`](#class_web_socket_sharp_1_1_net_1_1_response_stream_1ab390fa8607d8d415cb28667bb2137bb5)`()` 

##### `public override int ` [`EndRead`](#class_web_socket_sharp_1_1_net_1_1_response_stream_1a71be3895111be3dc6c1f136cde65f3b0)`(IAsyncResult asyncResult)` 

##### `public override void ` [`EndWrite`](#class_web_socket_sharp_1_1_net_1_1_response_stream_1a1537aeaaf4ea251f01a3a474ab7d52dd)`(IAsyncResult asyncResult)` 

##### `public override void ` [`Flush`](#class_web_socket_sharp_1_1_net_1_1_response_stream_1aa7fb788b182fe334800777f5e2882dcb)`()` 

##### `public override int ` [`Read`](#class_web_socket_sharp_1_1_net_1_1_response_stream_1ac80b086ec9c49baeb2bc4a5f2c8f36db)`(byte[] buffer, int offset, int count)` 

##### `public override long ` [`Seek`](#class_web_socket_sharp_1_1_net_1_1_response_stream_1a4d429be1fb6d7a7009dee7e9123cf592)`(long offset, SeekOrigin origin)` 

##### `public override void ` [`SetLength`](#class_web_socket_sharp_1_1_net_1_1_response_stream_1a5b64e99bd560495589e696be3b2a6c9e)`(long value)` 

##### `public override void ` [`Write`](#class_web_socket_sharp_1_1_net_1_1_response_stream_1ab7411151696464c81d02266936fbefaa)`(byte[] buffer, int offset, int count)` 

##### `protected override void ` [`Dispose`](#class_web_socket_sharp_1_1_net_1_1_response_stream_1a849c3c7f8d08104f0cdb46bee9fe6389)`(bool disposing)` 

##### `private MemoryStream ` [`_bodyBuffer`](#class_web_socket_sharp_1_1_net_1_1_response_stream_1a90dfc93d2d73b8bd2717b2c44d605771) 

##### `private bool ` [`_disposed`](#class_web_socket_sharp_1_1_net_1_1_response_stream_1aa0695b8700eaefdf30302d9b2daf447b) 

##### `private Stream ` [`_innerStream`](#class_web_socket_sharp_1_1_net_1_1_response_stream_1a7bdb1eb36e7f6a6398dccf098774c800) 

##### `private ` [`HttpListenerResponse`](WebSocketSharp--Net--HttpListenerResponse.md)` ` [`_response`](#class_web_socket_sharp_1_1_net_1_1_response_stream_1a3801a43a4ae7736589bbba4556e24c11) 

##### `private bool ` [`_sendChunked`](#class_web_socket_sharp_1_1_net_1_1_response_stream_1a9f01324db2b61d8e6841a4a9649ce792) 

##### `private ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)`< byte[], int, int > ` [`_write`](#class_web_socket_sharp_1_1_net_1_1_response_stream_1acda779816ed096d13b69e5a65d9da379) 

##### `private ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)`< byte[], int, int > ` [`_writeBody`](#class_web_socket_sharp_1_1_net_1_1_response_stream_1a4d828e43ef72fed0d0414c28c4f24c3f) 

##### `private ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)`< byte[], int, int > ` [`_writeChunked`](#class_web_socket_sharp_1_1_net_1_1_response_stream_1ab5e2689b6cc2eda43c0f49e1006f56cd) 

##### `private bool ` [`flush`](#class_web_socket_sharp_1_1_net_1_1_response_stream_1a1242e770280594a10c5d479903dae656)`(bool closing)` 

##### `private void ` [`flushBody`](#class_web_socket_sharp_1_1_net_1_1_response_stream_1ac2d867d8d41908ecfbb9c17b2a4efd4c)`(bool closing)` 

##### `private bool ` [`flushHeaders`](#class_web_socket_sharp_1_1_net_1_1_response_stream_1a05af3f8deb4cd371719dfb080d11a1af)`()` 

##### `private void ` [`writeChunked`](#class_web_socket_sharp_1_1_net_1_1_response_stream_1a1a9dc5c183e47904d9bcbfc6816bb2ac)`(byte[] buffer, int offset, int count)` 

##### `private void ` [`writeChunkedWithoutThrowingException`](#class_web_socket_sharp_1_1_net_1_1_response_stream_1a9973aab6cd174de01ec8bf3dafae4c90)`(byte[] buffer, int offset, int count)` 

##### `private void ` [`writeWithoutThrowingException`](#class_web_socket_sharp_1_1_net_1_1_response_stream_1a82f3217fcf8420468b0d33c57510e444)`(byte[] buffer, int offset, int count)` 

##### `private static static ` [`ResponseStream`](#class_web_socket_sharp_1_1_net_1_1_response_stream_1ac6be9a1b6d9041e15b3edf5b323d18a8)`()` 

##### `private static byte[] ` [`getChunkSizeBytes`](#class_web_socket_sharp_1_1_net_1_1_response_stream_1a05f421636a976b96645624bc513f8588)`(int size)` 

