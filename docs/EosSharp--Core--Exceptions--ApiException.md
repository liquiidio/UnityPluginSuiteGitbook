# class `EosSharp::Core::Exceptions::ApiException` 

```
class EosSharp::Core::Exceptions::ApiException
  : public Exception
```

Generic Api exception.

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public int ` [`StatusCode`](#class_eos_sharp_1_1_core_1_1_exceptions_1_1_api_exception_1a5025d650f325c75a520675895ddb477d) | 
`public string ` [`Content`](#class_eos_sharp_1_1_core_1_1_exceptions_1_1_api_exception_1a6d1fb265b40351e94f79e0f749e5daf9) | 
`public ` [`ApiException`](#class_eos_sharp_1_1_core_1_1_exceptions_1_1_api_exception_1a00257a088b29ee23ca247c15a0245232)`()` | 
`public ` [`ApiException`](#class_eos_sharp_1_1_core_1_1_exceptions_1_1_api_exception_1a7a7e7bb7d013b0e990c1cb4d4e021a84)`(SerializationInfo info, StreamingContext context)` | 
`public override void ` [`GetObjectData`](#class_eos_sharp_1_1_core_1_1_exceptions_1_1_api_exception_1a414726cd81ae10ed0870e3307d1e76b7)`(SerializationInfo info, StreamingContext context)` | The function is called when the object is serialized

## Members

##### `public int ` [`StatusCode`](#class_eos_sharp_1_1_core_1_1_exceptions_1_1_api_exception_1a5025d650f325c75a520675895ddb477d) 

##### `public string ` [`Content`](#class_eos_sharp_1_1_core_1_1_exceptions_1_1_api_exception_1a6d1fb265b40351e94f79e0f749e5daf9) 

##### `public ` [`ApiException`](#class_eos_sharp_1_1_core_1_1_exceptions_1_1_api_exception_1a00257a088b29ee23ca247c15a0245232)`()` 

##### `public ` [`ApiException`](#class_eos_sharp_1_1_core_1_1_exceptions_1_1_api_exception_1a7a7e7bb7d013b0e990c1cb4d4e021a84)`(SerializationInfo info, StreamingContext context)` 

##### `public override void ` [`GetObjectData`](#class_eos_sharp_1_1_core_1_1_exceptions_1_1_api_exception_1a414726cd81ae10ed0870e3307d1e76b7)`(SerializationInfo info, StreamingContext context)` 

The function is called when the object is serialized

#### Parameters
* `SerializationInfo` This is a container for all the data that needs to be serialized.

* `StreamingContext` This is a structure that contains information about the source and destination of a given serialized stream, and provides an additional caller-defined context.

#### Returns
The status code and the content of the response.

