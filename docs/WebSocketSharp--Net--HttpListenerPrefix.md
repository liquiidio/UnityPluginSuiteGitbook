# class `WebSocketSharp::Net::HttpListenerPrefix` 

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public string ` [`Host`](#class_web_socket_sharp_1_1_net_1_1_http_listener_prefix_1abd5d02452d0753592d3ade6268727de8) | 
`public bool ` [`IsSecure`](#class_web_socket_sharp_1_1_net_1_1_http_listener_prefix_1adb59d1044fe46ad2ddd774ccbc267db1) | 
`public ` [`HttpListener`](WebSocketSharp--Net--HttpListener.md)` ` [`Listener`](#class_web_socket_sharp_1_1_net_1_1_http_listener_prefix_1a5f59445330f7cdaec56e697910f1a018) | 
`public string ` [`Original`](#class_web_socket_sharp_1_1_net_1_1_http_listener_prefix_1ac26babc4b12ea79cb094f2d22da27caf) | 
`public string ` [`Path`](#class_web_socket_sharp_1_1_net_1_1_http_listener_prefix_1af331ba015acf9191899985a835008b9d) | 
`public string ` [`Port`](#class_web_socket_sharp_1_1_net_1_1_http_listener_prefix_1a368389b3458f93beae404944c3bef5e2) | 
`public override bool ` [`Equals`](#class_web_socket_sharp_1_1_net_1_1_http_listener_prefix_1aadf763f0213fc2f3875230b06bb0b6cf)`(object obj)` | Determines whether the current instance is equal to the specified object instance.
`public override int ` [`GetHashCode`](#class_web_socket_sharp_1_1_net_1_1_http_listener_prefix_1a77e1afa2b6dee1ed3640da81d7407b42)`()` | Gets the hash code for the current instance.
`public override string ` [`ToString`](#class_web_socket_sharp_1_1_net_1_1_http_listener_prefix_1aa73e7c4dd1df5fd5fbf81c7764ee1533)`()` | 
`private string ` [`_host`](#class_web_socket_sharp_1_1_net_1_1_http_listener_prefix_1a71c81338569634cc59e668df36d3df04) | 
`private ` [`HttpListener`](WebSocketSharp--Net--HttpListener.md)` ` [`_listener`](#class_web_socket_sharp_1_1_net_1_1_http_listener_prefix_1ab5753944447cd49f99da3ec676f16769) | 
`private string ` [`_original`](#class_web_socket_sharp_1_1_net_1_1_http_listener_prefix_1a13d89b28edd0b79251119483492abbed) | 
`private string ` [`_path`](#class_web_socket_sharp_1_1_net_1_1_http_listener_prefix_1a301dbb9913055444022b6d007e61871d) | 
`private string ` [`_port`](#class_web_socket_sharp_1_1_net_1_1_http_listener_prefix_1a10678d523a188cddac879e8ed9f74230) | 
`private string ` [`_prefix`](#class_web_socket_sharp_1_1_net_1_1_http_listener_prefix_1aaa38b4ee3afbaa5755461bec16579d32) | 
`private bool ` [`_secure`](#class_web_socket_sharp_1_1_net_1_1_http_listener_prefix_1a2f7b5b309c5830b8532939ca02946b44) | 
`private void ` [`parse`](#class_web_socket_sharp_1_1_net_1_1_http_listener_prefix_1ab83f6fcd31e0d0bfd67da95809d9f56a)`(string uriPrefix)` | 
`public static void ` [`CheckPrefix`](#class_web_socket_sharp_1_1_net_1_1_http_listener_prefix_1ad04c35bd0fe63c4eeed36db0705c0da0)`(string uriPrefix)` | 

## Members

##### `public string ` [`Host`](#class_web_socket_sharp_1_1_net_1_1_http_listener_prefix_1abd5d02452d0753592d3ade6268727de8) 

##### `public bool ` [`IsSecure`](#class_web_socket_sharp_1_1_net_1_1_http_listener_prefix_1adb59d1044fe46ad2ddd774ccbc267db1) 

##### `public ` [`HttpListener`](WebSocketSharp--Net--HttpListener.md)` ` [`Listener`](#class_web_socket_sharp_1_1_net_1_1_http_listener_prefix_1a5f59445330f7cdaec56e697910f1a018) 

##### `public string ` [`Original`](#class_web_socket_sharp_1_1_net_1_1_http_listener_prefix_1ac26babc4b12ea79cb094f2d22da27caf) 

##### `public string ` [`Path`](#class_web_socket_sharp_1_1_net_1_1_http_listener_prefix_1af331ba015acf9191899985a835008b9d) 

##### `public string ` [`Port`](#class_web_socket_sharp_1_1_net_1_1_http_listener_prefix_1a368389b3458f93beae404944c3bef5e2) 

##### `public override bool ` [`Equals`](#class_web_socket_sharp_1_1_net_1_1_http_listener_prefix_1aadf763f0213fc2f3875230b06bb0b6cf)`(object obj)` 

Determines whether the current instance is equal to the specified object instance.

This method will be required to detect duplicates in any collection. 

#### Parameters
* `obj` An object instance to compare to the current instance. 

An reference to a HttpListenerPrefix instance. 

#### Returns
`true` if the current instance and *obj*  have the same URI prefix; otherwise, `false`.

##### `public override int ` [`GetHashCode`](#class_web_socket_sharp_1_1_net_1_1_http_listener_prefix_1a77e1afa2b6dee1ed3640da81d7407b42)`()` 

Gets the hash code for the current instance.

This method will be required to detect duplicates in any collection. 

#### Returns
An int that represents the hash code.

##### `public override string ` [`ToString`](#class_web_socket_sharp_1_1_net_1_1_http_listener_prefix_1aa73e7c4dd1df5fd5fbf81c7764ee1533)`()` 

##### `private string ` [`_host`](#class_web_socket_sharp_1_1_net_1_1_http_listener_prefix_1a71c81338569634cc59e668df36d3df04) 

##### `private ` [`HttpListener`](WebSocketSharp--Net--HttpListener.md)` ` [`_listener`](#class_web_socket_sharp_1_1_net_1_1_http_listener_prefix_1ab5753944447cd49f99da3ec676f16769) 

##### `private string ` [`_original`](#class_web_socket_sharp_1_1_net_1_1_http_listener_prefix_1a13d89b28edd0b79251119483492abbed) 

##### `private string ` [`_path`](#class_web_socket_sharp_1_1_net_1_1_http_listener_prefix_1a301dbb9913055444022b6d007e61871d) 

##### `private string ` [`_port`](#class_web_socket_sharp_1_1_net_1_1_http_listener_prefix_1a10678d523a188cddac879e8ed9f74230) 

##### `private string ` [`_prefix`](#class_web_socket_sharp_1_1_net_1_1_http_listener_prefix_1aaa38b4ee3afbaa5755461bec16579d32) 

##### `private bool ` [`_secure`](#class_web_socket_sharp_1_1_net_1_1_http_listener_prefix_1a2f7b5b309c5830b8532939ca02946b44) 

##### `private void ` [`parse`](#class_web_socket_sharp_1_1_net_1_1_http_listener_prefix_1ab83f6fcd31e0d0bfd67da95809d9f56a)`(string uriPrefix)` 

##### `public static void ` [`CheckPrefix`](#class_web_socket_sharp_1_1_net_1_1_http_listener_prefix_1ad04c35bd0fe63c4eeed36db0705c0da0)`(string uriPrefix)` 

