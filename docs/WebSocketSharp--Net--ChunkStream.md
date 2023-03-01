# class `WebSocketSharp::Net::ChunkStream` 

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`package ` [`WebHeaderCollection`](WebSocketSharp--Net--WebHeaderCollection.md)` ` [`Headers`](#class_web_socket_sharp_1_1_net_1_1_chunk_stream_1a8b3c309de61f38e225a156f3b6cd5242) | 
`public int ` [`ChunkLeft`](#class_web_socket_sharp_1_1_net_1_1_chunk_stream_1a68fe86060ebd5c60450b6ae86f8cf78a) | 
`public bool ` [`WantMore`](#class_web_socket_sharp_1_1_net_1_1_chunk_stream_1a97070d2e62af99e94c8d24280c1ed0d9) | 
`public ` [`ChunkStream`](#class_web_socket_sharp_1_1_net_1_1_chunk_stream_1af3f679518509c19d8c18f4b3a0d22b92)`(` [`WebHeaderCollection`](WebSocketSharp--Net--WebHeaderCollection.md)` headers)` | 
`public ` [`ChunkStream`](#class_web_socket_sharp_1_1_net_1_1_chunk_stream_1a478f6998877c11c022a72c46920bcc2b)`(byte[] buffer, int offset, int count, ` [`WebHeaderCollection`](WebSocketSharp--Net--WebHeaderCollection.md)` headers)` | 
`public int ` [`Read`](#class_web_socket_sharp_1_1_net_1_1_chunk_stream_1a8808dd9eda395da311795796ebbd37df)`(byte[] buffer, int offset, int count)` | 
`public void ` [`Write`](#class_web_socket_sharp_1_1_net_1_1_chunk_stream_1ade37cde1242c3645f807cfe8c8344717)`(byte[] buffer, int offset, int count)` | 
`private int ` [`_chunkRead`](#class_web_socket_sharp_1_1_net_1_1_chunk_stream_1a869cd563523b37dfc1d2e59877aba927) | 
`private int ` [`_chunkSize`](#class_web_socket_sharp_1_1_net_1_1_chunk_stream_1a1d4ad3cc86d1a360997162354751f287) | 
`private List< ` [`Chunk`](WebSocketSharp--Net--Chunk.md)` > ` [`_chunks`](#class_web_socket_sharp_1_1_net_1_1_chunk_stream_1a382b8f2f0930b6c8844c811c7c6a2116) | 
`private bool ` [`_gotIt`](#class_web_socket_sharp_1_1_net_1_1_chunk_stream_1a74ea05034b8831c320bf6d41d8282b61) | 
`private ` [`WebHeaderCollection`](WebSocketSharp--Net--WebHeaderCollection.md)` ` [`_headers`](#class_web_socket_sharp_1_1_net_1_1_chunk_stream_1a6540483f7f73f46c6c5b52bbbed7ecd1) | 
`private StringBuilder ` [`_saved`](#class_web_socket_sharp_1_1_net_1_1_chunk_stream_1a2a2bcb33917bee31cc59a1bd9df4254b) | 
`private bool ` [`_sawCr`](#class_web_socket_sharp_1_1_net_1_1_chunk_stream_1a280e8c8fed99a9f94ae7a2cf91ae9f3a) | 
`private ` [`InputChunkState`](WebSocketSharp--Net.md)` ` [`_state`](#class_web_socket_sharp_1_1_net_1_1_chunk_stream_1a3d2203a6de6f9bbe0577f13eb9c3a9f1) | 
`private int ` [`_trailerState`](#class_web_socket_sharp_1_1_net_1_1_chunk_stream_1a3f991aac7b3327b9008a26ea87dc285f) | 
`private int ` [`read`](#class_web_socket_sharp_1_1_net_1_1_chunk_stream_1add98e3d068cdc3e42a70f8889aef9aac)`(byte[] buffer, int offset, int count)` | 
`private ` [`InputChunkState`](WebSocketSharp--Net.md)` ` [`seekCrLf`](#class_web_socket_sharp_1_1_net_1_1_chunk_stream_1a7a5120402830581dd61960cbefca723f)`(byte[] buffer, ref int offset, int length)` | 
`private ` [`InputChunkState`](WebSocketSharp--Net.md)` ` [`setChunkSize`](#class_web_socket_sharp_1_1_net_1_1_chunk_stream_1a739a436d670668d639e2dbf93f8a594d)`(byte[] buffer, ref int offset, int length)` | 
`private ` [`InputChunkState`](WebSocketSharp--Net.md)` ` [`setTrailer`](#class_web_socket_sharp_1_1_net_1_1_chunk_stream_1af31e38538a2552ccf8b0f1518ba2ac88)`(byte[] buffer, ref int offset, int length)` | 
`private void ` [`write`](#class_web_socket_sharp_1_1_net_1_1_chunk_stream_1a48741da1a1d4ec262e0d653a31a4a77d)`(byte[] buffer, ref int offset, int length)` | 
`private ` [`InputChunkState`](WebSocketSharp--Net.md)` ` [`writeData`](#class_web_socket_sharp_1_1_net_1_1_chunk_stream_1a2393ba9bef35a2c295ea53b297be7575)`(byte[] buffer, ref int offset, int length)` | 
`private static string ` [`removeChunkExtension`](#class_web_socket_sharp_1_1_net_1_1_chunk_stream_1a5363484ada3083b1a27a2c07a926a65e)`(string value)` | 
`private static void ` [`throwProtocolViolation`](#class_web_socket_sharp_1_1_net_1_1_chunk_stream_1a6d673d6fcc25c7a52c312f5eccba2aac)`(string message)` | 

## Members

##### `package ` [`WebHeaderCollection`](WebSocketSharp--Net--WebHeaderCollection.md)` ` [`Headers`](#class_web_socket_sharp_1_1_net_1_1_chunk_stream_1a8b3c309de61f38e225a156f3b6cd5242) 

##### `public int ` [`ChunkLeft`](#class_web_socket_sharp_1_1_net_1_1_chunk_stream_1a68fe86060ebd5c60450b6ae86f8cf78a) 

##### `public bool ` [`WantMore`](#class_web_socket_sharp_1_1_net_1_1_chunk_stream_1a97070d2e62af99e94c8d24280c1ed0d9) 

##### `public ` [`ChunkStream`](#class_web_socket_sharp_1_1_net_1_1_chunk_stream_1af3f679518509c19d8c18f4b3a0d22b92)`(` [`WebHeaderCollection`](WebSocketSharp--Net--WebHeaderCollection.md)` headers)` 

##### `public ` [`ChunkStream`](#class_web_socket_sharp_1_1_net_1_1_chunk_stream_1a478f6998877c11c022a72c46920bcc2b)`(byte[] buffer, int offset, int count, ` [`WebHeaderCollection`](WebSocketSharp--Net--WebHeaderCollection.md)` headers)` 

##### `public int ` [`Read`](#class_web_socket_sharp_1_1_net_1_1_chunk_stream_1a8808dd9eda395da311795796ebbd37df)`(byte[] buffer, int offset, int count)` 

##### `public void ` [`Write`](#class_web_socket_sharp_1_1_net_1_1_chunk_stream_1ade37cde1242c3645f807cfe8c8344717)`(byte[] buffer, int offset, int count)` 

##### `private int ` [`_chunkRead`](#class_web_socket_sharp_1_1_net_1_1_chunk_stream_1a869cd563523b37dfc1d2e59877aba927) 

##### `private int ` [`_chunkSize`](#class_web_socket_sharp_1_1_net_1_1_chunk_stream_1a1d4ad3cc86d1a360997162354751f287) 

##### `private List< ` [`Chunk`](WebSocketSharp--Net--Chunk.md)` > ` [`_chunks`](#class_web_socket_sharp_1_1_net_1_1_chunk_stream_1a382b8f2f0930b6c8844c811c7c6a2116) 

##### `private bool ` [`_gotIt`](#class_web_socket_sharp_1_1_net_1_1_chunk_stream_1a74ea05034b8831c320bf6d41d8282b61) 

##### `private ` [`WebHeaderCollection`](WebSocketSharp--Net--WebHeaderCollection.md)` ` [`_headers`](#class_web_socket_sharp_1_1_net_1_1_chunk_stream_1a6540483f7f73f46c6c5b52bbbed7ecd1) 

##### `private StringBuilder ` [`_saved`](#class_web_socket_sharp_1_1_net_1_1_chunk_stream_1a2a2bcb33917bee31cc59a1bd9df4254b) 

##### `private bool ` [`_sawCr`](#class_web_socket_sharp_1_1_net_1_1_chunk_stream_1a280e8c8fed99a9f94ae7a2cf91ae9f3a) 

##### `private ` [`InputChunkState`](WebSocketSharp--Net.md)` ` [`_state`](#class_web_socket_sharp_1_1_net_1_1_chunk_stream_1a3d2203a6de6f9bbe0577f13eb9c3a9f1) 

##### `private int ` [`_trailerState`](#class_web_socket_sharp_1_1_net_1_1_chunk_stream_1a3f991aac7b3327b9008a26ea87dc285f) 

##### `private int ` [`read`](#class_web_socket_sharp_1_1_net_1_1_chunk_stream_1add98e3d068cdc3e42a70f8889aef9aac)`(byte[] buffer, int offset, int count)` 

##### `private ` [`InputChunkState`](WebSocketSharp--Net.md)` ` [`seekCrLf`](#class_web_socket_sharp_1_1_net_1_1_chunk_stream_1a7a5120402830581dd61960cbefca723f)`(byte[] buffer, ref int offset, int length)` 

##### `private ` [`InputChunkState`](WebSocketSharp--Net.md)` ` [`setChunkSize`](#class_web_socket_sharp_1_1_net_1_1_chunk_stream_1a739a436d670668d639e2dbf93f8a594d)`(byte[] buffer, ref int offset, int length)` 

##### `private ` [`InputChunkState`](WebSocketSharp--Net.md)` ` [`setTrailer`](#class_web_socket_sharp_1_1_net_1_1_chunk_stream_1af31e38538a2552ccf8b0f1518ba2ac88)`(byte[] buffer, ref int offset, int length)` 

##### `private void ` [`write`](#class_web_socket_sharp_1_1_net_1_1_chunk_stream_1a48741da1a1d4ec262e0d653a31a4a77d)`(byte[] buffer, ref int offset, int length)` 

##### `private ` [`InputChunkState`](WebSocketSharp--Net.md)` ` [`writeData`](#class_web_socket_sharp_1_1_net_1_1_chunk_stream_1a2393ba9bef35a2c295ea53b297be7575)`(byte[] buffer, ref int offset, int length)` 

##### `private static string ` [`removeChunkExtension`](#class_web_socket_sharp_1_1_net_1_1_chunk_stream_1a5363484ada3083b1a27a2c07a926a65e)`(string value)` 

##### `private static void ` [`throwProtocolViolation`](#class_web_socket_sharp_1_1_net_1_1_chunk_stream_1a6d673d6fcc25c7a52c312f5eccba2aac)`(string message)` 

