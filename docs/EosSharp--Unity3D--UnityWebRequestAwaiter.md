# class `EosSharp::Unity3D::UnityWebRequestAwaiter` 

```
class EosSharp::Unity3D::UnityWebRequestAwaiter
  : public INotifyCompletion
```

Class to implement async / awayt on a UnityWebRequest class.

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public bool ` [`IsCompleted`](#class_eos_sharp_1_1_unity3_d_1_1_unity_web_request_awaiter_1a56e67c316e46f622ba314b13c1a2a517) | 
`public ` [`UnityWebRequestAwaiter`](#class_eos_sharp_1_1_unity3_d_1_1_unity_web_request_awaiter_1aea5262d36a3bb836c3c85ab350aa48e2)`(UnityWebRequestAsyncOperation asyncOp)` | 
`public void ` [`GetResult`](#class_eos_sharp_1_1_unity3_d_1_1_unity_web_request_awaiter_1a46d168bac1ba28e57f8714d3ec38ea99)`()` | 
`public void ` [`OnCompleted`](#class_eos_sharp_1_1_unity3_d_1_1_unity_web_request_awaiter_1a9f75613527d1af50f55c6b0b1aa77e72)`(` [`Action`](#_abi_serialization_provider_8cs_1a24e91c56095a0673d92c6eac6e069a3c)` continuation)` | 
`private UnityWebRequestAsyncOperation ` [`asyncOp`](#class_eos_sharp_1_1_unity3_d_1_1_unity_web_request_awaiter_1a92e647278ab86a297da12eb56e7e3af4) | 
`private ` [`Action`](#_abi_serialization_provider_8cs_1a24e91c56095a0673d92c6eac6e069a3c)` ` [`continuation`](#class_eos_sharp_1_1_unity3_d_1_1_unity_web_request_awaiter_1aedc240dbeb849431f0c2f4424d9cd580) | 
`private void ` [`OnRequestCompleted`](#class_eos_sharp_1_1_unity3_d_1_1_unity_web_request_awaiter_1aced908de16a964914a723a1a3466cc75)`(AsyncOperation obj)` | 

## Members

##### `public bool ` [`IsCompleted`](#class_eos_sharp_1_1_unity3_d_1_1_unity_web_request_awaiter_1a56e67c316e46f622ba314b13c1a2a517) 

##### `public ` [`UnityWebRequestAwaiter`](#class_eos_sharp_1_1_unity3_d_1_1_unity_web_request_awaiter_1aea5262d36a3bb836c3c85ab350aa48e2)`(UnityWebRequestAsyncOperation asyncOp)` 

##### `public void ` [`GetResult`](#class_eos_sharp_1_1_unity3_d_1_1_unity_web_request_awaiter_1a46d168bac1ba28e57f8714d3ec38ea99)`()` 

##### `public void ` [`OnCompleted`](#class_eos_sharp_1_1_unity3_d_1_1_unity_web_request_awaiter_1a9f75613527d1af50f55c6b0b1aa77e72)`(` [`Action`](#_abi_serialization_provider_8cs_1a24e91c56095a0673d92c6eac6e069a3c)` continuation)` 

##### `private UnityWebRequestAsyncOperation ` [`asyncOp`](#class_eos_sharp_1_1_unity3_d_1_1_unity_web_request_awaiter_1a92e647278ab86a297da12eb56e7e3af4) 

##### `private ` [`Action`](#_abi_serialization_provider_8cs_1a24e91c56095a0673d92c6eac6e069a3c)` ` [`continuation`](#class_eos_sharp_1_1_unity3_d_1_1_unity_web_request_awaiter_1aedc240dbeb849431f0c2f4424d9cd580) 

##### `private void ` [`OnRequestCompleted`](#class_eos_sharp_1_1_unity3_d_1_1_unity_web_request_awaiter_1aced908de16a964914a723a1a3466cc75)`(AsyncOperation obj)` 

