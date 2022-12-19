# class `HyperionApiClient::Models::ApiException` 

```
class HyperionApiClient::Models::ApiException
  : public Exception
  : public ApiException
```

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public int `[`StatusCode`](#class_hyperion_api_client_1_1_models_1_1_api_exception_1a5025d650f325c75a520675895ddb477d) | 
`public string `[`Response`](#class_hyperion_api_client_1_1_models_1_1_api_exception_1afa13e95e50be44c9fffb3ce19f3bbd29) | 
`public IReadOnlyDictionary< string, IEnumerable< string > > `[`Headers`](#class_hyperion_api_client_1_1_models_1_1_api_exception_1a6ab586e208648591377a90cca8d0e94b) | 
`public TResult `[`Result`](#class_hyperion_api_client_1_1_models_1_1_api_exception_1acc84a574c5f877b0428fe7926c700f27) | 
`public  `[`ApiException`](#class_hyperion_api_client_1_1_models_1_1_api_exception_1a756c8ce5337c2c8b42c8c524d1aa546d)`(string message, int statusCode, string response, IReadOnlyDictionary< string, IEnumerable< string > > headers, Exception innerException)` | 
`public override string `[`ToString`](#class_hyperion_api_client_1_1_models_1_1_api_exception_1aa73e7c4dd1df5fd5fbf81c7764ee1533)`()` | 
`public  `[`ApiException`](#class_hyperion_api_client_1_1_models_1_1_api_exception_1ac1cdb3f3f8060ab6e59a50fe1042a40e)`(string message, int statusCode, string response, IReadOnlyDictionary< string, IEnumerable< string > > headers, TResult result, Exception innerException)` | 

## Members

### `public int `[`StatusCode`](#class_hyperion_api_client_1_1_models_1_1_api_exception_1a5025d650f325c75a520675895ddb477d) 

### `public string `[`Response`](#class_hyperion_api_client_1_1_models_1_1_api_exception_1afa13e95e50be44c9fffb3ce19f3bbd29) 

### `public IReadOnlyDictionary< string, IEnumerable< string > > `[`Headers`](#class_hyperion_api_client_1_1_models_1_1_api_exception_1a6ab586e208648591377a90cca8d0e94b) 

### `public TResult `[`Result`](#class_hyperion_api_client_1_1_models_1_1_api_exception_1acc84a574c5f877b0428fe7926c700f27) 

### `public  `[`ApiException`](#class_hyperion_api_client_1_1_models_1_1_api_exception_1a756c8ce5337c2c8b42c8c524d1aa546d)`(string message, int statusCode, string response, IReadOnlyDictionary< string, IEnumerable< string > > headers, Exception innerException)` 

### `public override string `[`ToString`](#class_hyperion_api_client_1_1_models_1_1_api_exception_1aa73e7c4dd1df5fd5fbf81c7764ee1533)`()` 

### `public  `[`ApiException`](#class_hyperion_api_client_1_1_models_1_1_api_exception_1ac1cdb3f3f8060ab6e59a50fe1042a40e)`(string message, int statusCode, string response, IReadOnlyDictionary< string, IEnumerable< string > > headers, TResult result, Exception innerException)` 

