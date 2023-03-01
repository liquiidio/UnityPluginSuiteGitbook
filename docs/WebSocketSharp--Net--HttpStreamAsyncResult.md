# class `WebSocketSharp::Net::HttpStreamAsyncResult` 

```
class WebSocketSharp::Net::HttpStreamAsyncResult
  : public IAsyncResult
```

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`package byte[] ` [`Buffer`](#class_web_socket_sharp_1_1_net_1_1_http_stream_async_result_1aa7d0001a7d84f7541ba6552012858437) | 
`package int ` [`Count`](#class_web_socket_sharp_1_1_net_1_1_http_stream_async_result_1aad462966ed963f892117056de1eba502) | 
`package Exception ` [`Exception`](#class_web_socket_sharp_1_1_net_1_1_http_stream_async_result_1a75f456e07534eb091bd4c71b194ec90e) | 
`package bool ` [`HasException`](#class_web_socket_sharp_1_1_net_1_1_http_stream_async_result_1a38bc83562886fe3551bd7f9bbc51551e) | 
`package int ` [`Offset`](#class_web_socket_sharp_1_1_net_1_1_http_stream_async_result_1a03e24f0a881e07cbe69ecd4db34a2323) | 
`package int ` [`SyncRead`](#class_web_socket_sharp_1_1_net_1_1_http_stream_async_result_1a8394dfee5af4281e926df97aea20125b) | 
`public object ` [`AsyncState`](#class_web_socket_sharp_1_1_net_1_1_http_stream_async_result_1aacf53410c127126f0e57d24aebab1daf) | 
`public WaitHandle ` [`AsyncWaitHandle`](#class_web_socket_sharp_1_1_net_1_1_http_stream_async_result_1ab973b89edf31c20a1e2db85dfb3658fa) | 
`public bool ` [`CompletedSynchronously`](#class_web_socket_sharp_1_1_net_1_1_http_stream_async_result_1a42e092682fc9d867a8b3f3e1b0c50ffa) | 
`public bool ` [`IsCompleted`](#class_web_socket_sharp_1_1_net_1_1_http_stream_async_result_1a56e67c316e46f622ba314b13c1a2a517) | 
`private byte[] ` [`_buffer`](#class_web_socket_sharp_1_1_net_1_1_http_stream_async_result_1afdf89bf39fd5e5e4b157398fbd2724e4) | 
`private AsyncCallback ` [`_callback`](#class_web_socket_sharp_1_1_net_1_1_http_stream_async_result_1af78e6646b2b46f11a481d2ee6be679bc) | 
`private bool ` [`_completed`](#class_web_socket_sharp_1_1_net_1_1_http_stream_async_result_1ad730d4866e83fb6bd77b6776cb374148) | 
`private int ` [`_count`](#class_web_socket_sharp_1_1_net_1_1_http_stream_async_result_1a83852750be9a651f15936176472dd5c0) | 
`private ` [`Exception`](#class_web_socket_sharp_1_1_net_1_1_http_stream_async_result_1a75f456e07534eb091bd4c71b194ec90e)` ` [`_exception`](#class_web_socket_sharp_1_1_net_1_1_http_stream_async_result_1abcfe8ca61795cb92992dab20d4cb59f3) | 
`private int ` [`_offset`](#class_web_socket_sharp_1_1_net_1_1_http_stream_async_result_1a53da2341ea4433867b68756f20019d5c) | 
`private object ` [`_state`](#class_web_socket_sharp_1_1_net_1_1_http_stream_async_result_1a683b078a1fa7a361ffb2e7dd7a9d2d2c) | 
`private object ` [`_sync`](#class_web_socket_sharp_1_1_net_1_1_http_stream_async_result_1adbb069fcd0e2b452bc3342bc00739ed8) | 
`private int ` [`_syncRead`](#class_web_socket_sharp_1_1_net_1_1_http_stream_async_result_1a1676ff7f2337dee7a9558623dba3aaf7) | 
`private ManualResetEvent ` [`_waitHandle`](#class_web_socket_sharp_1_1_net_1_1_http_stream_async_result_1ab6e395de0f001fd6942678eec45756a8) | 

## Members

##### `package byte[] ` [`Buffer`](#class_web_socket_sharp_1_1_net_1_1_http_stream_async_result_1aa7d0001a7d84f7541ba6552012858437) 

##### `package int ` [`Count`](#class_web_socket_sharp_1_1_net_1_1_http_stream_async_result_1aad462966ed963f892117056de1eba502) 

##### `package Exception ` [`Exception`](#class_web_socket_sharp_1_1_net_1_1_http_stream_async_result_1a75f456e07534eb091bd4c71b194ec90e) 

##### `package bool ` [`HasException`](#class_web_socket_sharp_1_1_net_1_1_http_stream_async_result_1a38bc83562886fe3551bd7f9bbc51551e) 

##### `package int ` [`Offset`](#class_web_socket_sharp_1_1_net_1_1_http_stream_async_result_1a03e24f0a881e07cbe69ecd4db34a2323) 

##### `package int ` [`SyncRead`](#class_web_socket_sharp_1_1_net_1_1_http_stream_async_result_1a8394dfee5af4281e926df97aea20125b) 

##### `public object ` [`AsyncState`](#class_web_socket_sharp_1_1_net_1_1_http_stream_async_result_1aacf53410c127126f0e57d24aebab1daf) 

##### `public WaitHandle ` [`AsyncWaitHandle`](#class_web_socket_sharp_1_1_net_1_1_http_stream_async_result_1ab973b89edf31c20a1e2db85dfb3658fa) 

##### `public bool ` [`CompletedSynchronously`](#class_web_socket_sharp_1_1_net_1_1_http_stream_async_result_1a42e092682fc9d867a8b3f3e1b0c50ffa) 

##### `public bool ` [`IsCompleted`](#class_web_socket_sharp_1_1_net_1_1_http_stream_async_result_1a56e67c316e46f622ba314b13c1a2a517) 

##### `private byte[] ` [`_buffer`](#class_web_socket_sharp_1_1_net_1_1_http_stream_async_result_1afdf89bf39fd5e5e4b157398fbd2724e4) 

##### `private AsyncCallback ` [`_callback`](#class_web_socket_sharp_1_1_net_1_1_http_stream_async_result_1af78e6646b2b46f11a481d2ee6be679bc) 

##### `private bool ` [`_completed`](#class_web_socket_sharp_1_1_net_1_1_http_stream_async_result_1ad730d4866e83fb6bd77b6776cb374148) 

##### `private int ` [`_count`](#class_web_socket_sharp_1_1_net_1_1_http_stream_async_result_1a83852750be9a651f15936176472dd5c0) 

##### `private ` [`Exception`](#class_web_socket_sharp_1_1_net_1_1_http_stream_async_result_1a75f456e07534eb091bd4c71b194ec90e)` ` [`_exception`](#class_web_socket_sharp_1_1_net_1_1_http_stream_async_result_1abcfe8ca61795cb92992dab20d4cb59f3) 

##### `private int ` [`_offset`](#class_web_socket_sharp_1_1_net_1_1_http_stream_async_result_1a53da2341ea4433867b68756f20019d5c) 

##### `private object ` [`_state`](#class_web_socket_sharp_1_1_net_1_1_http_stream_async_result_1a683b078a1fa7a361ffb2e7dd7a9d2d2c) 

##### `private object ` [`_sync`](#class_web_socket_sharp_1_1_net_1_1_http_stream_async_result_1adbb069fcd0e2b452bc3342bc00739ed8) 

##### `private int ` [`_syncRead`](#class_web_socket_sharp_1_1_net_1_1_http_stream_async_result_1a1676ff7f2337dee7a9558623dba3aaf7) 

##### `private ManualResetEvent ` [`_waitHandle`](#class_web_socket_sharp_1_1_net_1_1_http_stream_async_result_1ab6e395de0f001fd6942678eec45756a8) 

