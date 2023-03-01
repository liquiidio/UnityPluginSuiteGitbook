# class `WebSocketSharp::Net::HttpListenerAsyncResult` 

```
class WebSocketSharp::Net::HttpListenerAsyncResult
  : public IAsyncResult
```

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`package bool ` [`EndCalled`](#class_web_socket_sharp_1_1_net_1_1_http_listener_async_result_1a20efd34034816e796039c920b6f11ba3) | 
`package bool ` [`InGet`](#class_web_socket_sharp_1_1_net_1_1_http_listener_async_result_1a389e762a0f3c73664f2f0826021cfbe0) | 
`public object ` [`AsyncState`](#class_web_socket_sharp_1_1_net_1_1_http_listener_async_result_1aacf53410c127126f0e57d24aebab1daf) | 
`public WaitHandle ` [`AsyncWaitHandle`](#class_web_socket_sharp_1_1_net_1_1_http_listener_async_result_1ab973b89edf31c20a1e2db85dfb3658fa) | 
`public bool ` [`CompletedSynchronously`](#class_web_socket_sharp_1_1_net_1_1_http_listener_async_result_1a42e092682fc9d867a8b3f3e1b0c50ffa) | 
`public bool ` [`IsCompleted`](#class_web_socket_sharp_1_1_net_1_1_http_listener_async_result_1a56e67c316e46f622ba314b13c1a2a517) | 
`private AsyncCallback ` [`_callback`](#class_web_socket_sharp_1_1_net_1_1_http_listener_async_result_1af78e6646b2b46f11a481d2ee6be679bc) | 
`private bool ` [`_completed`](#class_web_socket_sharp_1_1_net_1_1_http_listener_async_result_1ad730d4866e83fb6bd77b6776cb374148) | 
`private ` [`HttpListenerContext`](WebSocketSharp--Net--HttpListenerContext.md)` ` [`_context`](#class_web_socket_sharp_1_1_net_1_1_http_listener_async_result_1acce8d94df9e8bf7da6c2d6888e9f5391) | 
`private bool ` [`_endCalled`](#class_web_socket_sharp_1_1_net_1_1_http_listener_async_result_1a9ccc45be6aad87fa4d51df102fd38a64) | 
`private Exception ` [`_exception`](#class_web_socket_sharp_1_1_net_1_1_http_listener_async_result_1abcfe8ca61795cb92992dab20d4cb59f3) | 
`private bool ` [`_inGet`](#class_web_socket_sharp_1_1_net_1_1_http_listener_async_result_1ae76c04c5e11fe7d1bfcf2cec51995ef0) | 
`private object ` [`_state`](#class_web_socket_sharp_1_1_net_1_1_http_listener_async_result_1a683b078a1fa7a361ffb2e7dd7a9d2d2c) | 
`private object ` [`_sync`](#class_web_socket_sharp_1_1_net_1_1_http_listener_async_result_1adbb069fcd0e2b452bc3342bc00739ed8) | 
`private bool ` [`_syncCompleted`](#class_web_socket_sharp_1_1_net_1_1_http_listener_async_result_1ac1331d64c7541012dc9602be2ac1dc14) | 
`private ManualResetEvent ` [`_waitHandle`](#class_web_socket_sharp_1_1_net_1_1_http_listener_async_result_1ab6e395de0f001fd6942678eec45756a8) | 
`private static void ` [`complete`](#class_web_socket_sharp_1_1_net_1_1_http_listener_async_result_1a1f8c5d86a35d3e48644d1ddecbe31a66)`(` [`HttpListenerAsyncResult`](#class_web_socket_sharp_1_1_net_1_1_http_listener_async_result)` asyncResult)` | 

## Members

##### `package bool ` [`EndCalled`](#class_web_socket_sharp_1_1_net_1_1_http_listener_async_result_1a20efd34034816e796039c920b6f11ba3) 

##### `package bool ` [`InGet`](#class_web_socket_sharp_1_1_net_1_1_http_listener_async_result_1a389e762a0f3c73664f2f0826021cfbe0) 

##### `public object ` [`AsyncState`](#class_web_socket_sharp_1_1_net_1_1_http_listener_async_result_1aacf53410c127126f0e57d24aebab1daf) 

##### `public WaitHandle ` [`AsyncWaitHandle`](#class_web_socket_sharp_1_1_net_1_1_http_listener_async_result_1ab973b89edf31c20a1e2db85dfb3658fa) 

##### `public bool ` [`CompletedSynchronously`](#class_web_socket_sharp_1_1_net_1_1_http_listener_async_result_1a42e092682fc9d867a8b3f3e1b0c50ffa) 

##### `public bool ` [`IsCompleted`](#class_web_socket_sharp_1_1_net_1_1_http_listener_async_result_1a56e67c316e46f622ba314b13c1a2a517) 

##### `private AsyncCallback ` [`_callback`](#class_web_socket_sharp_1_1_net_1_1_http_listener_async_result_1af78e6646b2b46f11a481d2ee6be679bc) 

##### `private bool ` [`_completed`](#class_web_socket_sharp_1_1_net_1_1_http_listener_async_result_1ad730d4866e83fb6bd77b6776cb374148) 

##### `private ` [`HttpListenerContext`](WebSocketSharp--Net--HttpListenerContext.md)` ` [`_context`](#class_web_socket_sharp_1_1_net_1_1_http_listener_async_result_1acce8d94df9e8bf7da6c2d6888e9f5391) 

##### `private bool ` [`_endCalled`](#class_web_socket_sharp_1_1_net_1_1_http_listener_async_result_1a9ccc45be6aad87fa4d51df102fd38a64) 

##### `private Exception ` [`_exception`](#class_web_socket_sharp_1_1_net_1_1_http_listener_async_result_1abcfe8ca61795cb92992dab20d4cb59f3) 

##### `private bool ` [`_inGet`](#class_web_socket_sharp_1_1_net_1_1_http_listener_async_result_1ae76c04c5e11fe7d1bfcf2cec51995ef0) 

##### `private object ` [`_state`](#class_web_socket_sharp_1_1_net_1_1_http_listener_async_result_1a683b078a1fa7a361ffb2e7dd7a9d2d2c) 

##### `private object ` [`_sync`](#class_web_socket_sharp_1_1_net_1_1_http_listener_async_result_1adbb069fcd0e2b452bc3342bc00739ed8) 

##### `private bool ` [`_syncCompleted`](#class_web_socket_sharp_1_1_net_1_1_http_listener_async_result_1ac1331d64c7541012dc9602be2ac1dc14) 

##### `private ManualResetEvent ` [`_waitHandle`](#class_web_socket_sharp_1_1_net_1_1_http_listener_async_result_1ab6e395de0f001fd6942678eec45756a8) 

##### `private static void ` [`complete`](#class_web_socket_sharp_1_1_net_1_1_http_listener_async_result_1a1f8c5d86a35d3e48644d1ddecbe31a66)`(` [`HttpListenerAsyncResult`](#class_web_socket_sharp_1_1_net_1_1_http_listener_async_result)` asyncResult)` 

