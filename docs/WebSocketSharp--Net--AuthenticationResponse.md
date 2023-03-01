# class `WebSocketSharp::Net::AuthenticationResponse` 

```
class WebSocketSharp::Net::AuthenticationResponse
  : public AuthenticationBase
```

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`package uint ` [`NonceCount`](#class_web_socket_sharp_1_1_net_1_1_authentication_response_1ac08baa15a781691aadf9175cbfeaa1cd) | 
`public string ` [`Cnonce`](#class_web_socket_sharp_1_1_net_1_1_authentication_response_1a3ebeaa58729032435f7c3728f75e8bc2) | 
`public string ` [`Nc`](#class_web_socket_sharp_1_1_net_1_1_authentication_response_1a6baf3edd7028c5b3a99f686c996d9f60) | 
`public string ` [`Password`](#class_web_socket_sharp_1_1_net_1_1_authentication_response_1a9c7aae3a8518d5efd22e991b5944e0d4) | 
`public string ` [`Response`](#class_web_socket_sharp_1_1_net_1_1_authentication_response_1afa13e95e50be44c9fffb3ce19f3bbd29) | 
`public string ` [`Uri`](#class_web_socket_sharp_1_1_net_1_1_authentication_response_1ab3fad9c5e5c69c7661a7c4e32df41c27) | 
`public string ` [`UserName`](#class_web_socket_sharp_1_1_net_1_1_authentication_response_1a6ec251e40abde6d9263485e1a237a82f) | 
`public IIdentity ` [`ToIdentity`](#class_web_socket_sharp_1_1_net_1_1_authentication_response_1a56b7c0d219f70750e92ef941d7e85f88)`()` | 
`private uint ` [`_nonceCount`](#class_web_socket_sharp_1_1_net_1_1_authentication_response_1a94db75d7371c21043430a471dffd3d45) | 
`private ` [`AuthenticationResponse`](#class_web_socket_sharp_1_1_net_1_1_authentication_response_1acb5a13402a9a50df23a9d56eaaf25293)`(` [`AuthenticationSchemes`](WebSocketSharp--Net.md)` scheme, NameValueCollection parameters)` | 
`private void ` [`initAsDigest`](#class_web_socket_sharp_1_1_net_1_1_authentication_response_1a1cd29723b05c2bcfda4b48fe80c11267)`()` | 
`private static string ` [`createA1`](#class_web_socket_sharp_1_1_net_1_1_authentication_response_1ae1365a35688c83feb9ee1abb4dad2f21)`(string username, string password, string realm)` | 
`private static string ` [`createA1`](#class_web_socket_sharp_1_1_net_1_1_authentication_response_1adf15fa444a5a46d44a6d6e589a43dedb)`(string username, string password, string realm, string nonce, string cnonce)` | 
`private static string ` [`createA2`](#class_web_socket_sharp_1_1_net_1_1_authentication_response_1abca39bbfd68be13efdddc23efff69a21)`(string method, string uri)` | 
`private static string ` [`createA2`](#class_web_socket_sharp_1_1_net_1_1_authentication_response_1af616e39852f7d9dd91ceb85ee2029ed3)`(string method, string uri, string entity)` | 
`private static string ` [`hash`](#class_web_socket_sharp_1_1_net_1_1_authentication_response_1a8e11bcfd95bfa82d626035f7e8b3d9fa)`(string value)` | 

## Members

##### `package uint ` [`NonceCount`](#class_web_socket_sharp_1_1_net_1_1_authentication_response_1ac08baa15a781691aadf9175cbfeaa1cd) 

##### `public string ` [`Cnonce`](#class_web_socket_sharp_1_1_net_1_1_authentication_response_1a3ebeaa58729032435f7c3728f75e8bc2) 

##### `public string ` [`Nc`](#class_web_socket_sharp_1_1_net_1_1_authentication_response_1a6baf3edd7028c5b3a99f686c996d9f60) 

##### `public string ` [`Password`](#class_web_socket_sharp_1_1_net_1_1_authentication_response_1a9c7aae3a8518d5efd22e991b5944e0d4) 

##### `public string ` [`Response`](#class_web_socket_sharp_1_1_net_1_1_authentication_response_1afa13e95e50be44c9fffb3ce19f3bbd29) 

##### `public string ` [`Uri`](#class_web_socket_sharp_1_1_net_1_1_authentication_response_1ab3fad9c5e5c69c7661a7c4e32df41c27) 

##### `public string ` [`UserName`](#class_web_socket_sharp_1_1_net_1_1_authentication_response_1a6ec251e40abde6d9263485e1a237a82f) 

##### `public IIdentity ` [`ToIdentity`](#class_web_socket_sharp_1_1_net_1_1_authentication_response_1a56b7c0d219f70750e92ef941d7e85f88)`()` 

##### `private uint ` [`_nonceCount`](#class_web_socket_sharp_1_1_net_1_1_authentication_response_1a94db75d7371c21043430a471dffd3d45) 

##### `private ` [`AuthenticationResponse`](#class_web_socket_sharp_1_1_net_1_1_authentication_response_1acb5a13402a9a50df23a9d56eaaf25293)`(` [`AuthenticationSchemes`](WebSocketSharp--Net.md)` scheme, NameValueCollection parameters)` 

##### `private void ` [`initAsDigest`](#class_web_socket_sharp_1_1_net_1_1_authentication_response_1a1cd29723b05c2bcfda4b48fe80c11267)`()` 

##### `private static string ` [`createA1`](#class_web_socket_sharp_1_1_net_1_1_authentication_response_1ae1365a35688c83feb9ee1abb4dad2f21)`(string username, string password, string realm)` 

##### `private static string ` [`createA1`](#class_web_socket_sharp_1_1_net_1_1_authentication_response_1adf15fa444a5a46d44a6d6e589a43dedb)`(string username, string password, string realm, string nonce, string cnonce)` 

##### `private static string ` [`createA2`](#class_web_socket_sharp_1_1_net_1_1_authentication_response_1abca39bbfd68be13efdddc23efff69a21)`(string method, string uri)` 

##### `private static string ` [`createA2`](#class_web_socket_sharp_1_1_net_1_1_authentication_response_1af616e39852f7d9dd91ceb85ee2029ed3)`(string method, string uri, string entity)` 

##### `private static string ` [`hash`](#class_web_socket_sharp_1_1_net_1_1_authentication_response_1a8e11bcfd95bfa82d626035f7e8b3d9fa)`(string value)` 

