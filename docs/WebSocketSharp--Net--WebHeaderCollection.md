# class `WebSocketSharp::Net::WebHeaderCollection` 

```
class WebSocketSharp::Net::WebHeaderCollection
  : public NameValueCollection
  : public ISerializable
```

Provides a collection of the HTTP headers associated with a request or response.

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`package ` [`HttpHeaderType`](WebSocketSharp--Net.md)` ` [`State`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1a1e0580203f1062bb91d70dba9fec5003) | 
`public override string[] ` [`AllKeys`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1ab04b0dbb307ef11ef445a3195f48fd39) | Gets all header names in the collection.
`public override int ` [`Count`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1a9198bf6e7433159107917369117759d5) | Gets the number of headers in the collection.
`public string ` [`this[HttpRequestHeader header]`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1af8e56c64af8ffb4fb3043a92d7032846) | Gets or sets the specified request header.
`public string ` [`this[HttpResponseHeader header]`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1acb969ea1f9d6d92fe0948d7a03dc2034) | Gets or sets the specified response header.
`public override NameObjectCollectionBase.KeysCollection ` [`Keys`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1a9f43c6619b839bcd3e9174de299ea96c) | Gets a collection of header names in the collection.
`public ` [`WebHeaderCollection`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1aed173f1f7f02780eb5c44c7cce60bc72)`()` | Initializes a new instance of the WebHeaderCollection class.
`public void ` [`Add`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1a1b6c89758bce80c0abc77d58be0b4991)`(string header)` | Adds the specified header to the collection.
`public void ` [`Add`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1a6b61f8d689ce5868d2d595207a78046b)`(` [`HttpRequestHeader`](WebSocketSharp--Net.md)` header, string value)` | Adds the specified request header with the specified value to the collection.
`public void ` [`Add`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1a75bf5cdf1e6270e6c76eabed454a55b5)`(` [`HttpResponseHeader`](WebSocketSharp--Net.md)` header, string value)` | Adds the specified response header with the specified value to the collection.
`public override void ` [`Add`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1af8464d0a11372f13dee1ddda2b6578fa)`(string name, string value)` | Adds a header with the specified name and value to the collection.
`public override void ` [`Clear`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1a19f6e9e119005114268f68098f143906)`()` | Removes all headers from the collection.
`public override string ` [`Get`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1a6847b6cdc8b428247a46001710080607)`(int index)` | Get the value of the header at the specified index in the collection.
`public override string ` [`Get`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1aed2474b68bc4129e9dceda47e71d6330)`(string name)` | Get the value of the header with the specified name in the collection.
`public override IEnumerator ` [`GetEnumerator`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1a84aa5c7f8c07cbac14a7611a1c7b3b42)`()` | Gets the enumerator used to iterate through the collection.
`public override string ` [`GetKey`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1a5bd2a01f28f862773b3da82502bd71fc)`(int index)` | Get the name of the header at the specified index in the collection.
`public override string[] ` [`GetValues`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1a2d3b158932997b482e1bb8be23dc967b)`(int index)` | Get the values of the header at the specified index in the collection.
`public override string[] ` [`GetValues`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1a95b0dadb01d1549eaf85d5fad46886a7)`(string name)` | Get the values of the header with the specified name in the collection.
`public override void ` [`GetObjectData`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1a4cbc21245ff6badf7ef5f29bb3e8ee00)`(SerializationInfo serializationInfo, StreamingContext streamingContext)` | Populates a SerializationInfo instance with the data needed to serialize this instance.
`public override void ` [`OnDeserialization`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1a749cf4897a7a7f8c57f508d5dfe24cde)`(object sender)` | Implements the ISerializable interface and raises the deserialization event when the deserialization is complete.
`public void ` [`Remove`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1ae8a4296e6a8496c5fa5c8e30d74f2a12)`(` [`HttpRequestHeader`](WebSocketSharp--Net.md)` header)` | Removes the specified request header from the collection.
`public void ` [`Remove`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1aa938ba6784674f1eda92577ce05773a9)`(` [`HttpResponseHeader`](WebSocketSharp--Net.md)` header)` | Removes the specified response header from the collection.
`public override void ` [`Remove`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1a245d236c58be797c13ddbadb1066ab36)`(string name)` | Removes the specified header from the collection.
`public void ` [`Set`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1ab2ff9bcd1176fe7b64dd97920b2a5d6b)`(` [`HttpRequestHeader`](WebSocketSharp--Net.md)` header, string value)` | Sets the specified request header to the specified value.
`public void ` [`Set`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1a2f9d1beb43b66c386d2ea60ecc6d04e4)`(` [`HttpResponseHeader`](WebSocketSharp--Net.md)` header, string value)` | Sets the specified response header to the specified value.
`public override void ` [`Set`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1ad96bbd8e9c2b623a229fbda4f7be34ed)`(string name, string value)` | Sets the specified header to the specified value.
`public byte[] ` [`ToByteArray`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1a5e05025d8b0434ab88b76301915aff2b)`()` | Converts the current instance to an array of byte.
`public override string ` [`ToString`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1aa73e7c4dd1df5fd5fbf81c7764ee1533)`()` | Returns a string that represents the current instance.
`protected ` [`WebHeaderCollection`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1a8dc7537a74093c7175ec9a2bc5e1789c)`(SerializationInfo serializationInfo, StreamingContext streamingContext)` | Initializes a new instance of the WebHeaderCollection class from the specified instances of the SerializationInfo and StreamingContext classes.
`protected void ` [`AddWithoutValidate`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1a41f231d396b1afbbf1f4436bbd1795db)`(string headerName, string headerValue)` | Adds a header to the collection without checking if the header is on the restricted header list.
`private bool ` [`_internallyUsed`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1a0c5853d5c67ec4fae622dc69f8afd278) | 
`private ` [`HttpHeaderType`](WebSocketSharp--Net.md)` ` [`_state`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1a8f879a4c904d17af2f2e49ec4e1b1eec) | 
`private void ` [`add`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1a9c83d4ba40ac486d25cd826e927527c8)`(string name, string value, ` [`HttpHeaderType`](WebSocketSharp--Net.md)` headerType)` | 
`private void ` [`checkAllowed`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1ade88221efe2d03ccb2b57a77f491f9f6)`(` [`HttpHeaderType`](WebSocketSharp--Net.md)` headerType)` | 
`private void ` [`checkRestricted`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1af7e93bdea8a189e02636e0647774e9fa)`(string name, ` [`HttpHeaderType`](WebSocketSharp--Net.md)` headerType)` | 
`private void ` [`set`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1ac9f353605a5d6f48397fceec5198424a)`(string name, string value, ` [`HttpHeaderType`](WebSocketSharp--Net.md)` headerType)` | 
`private void ISerializable. ` [`GetObjectData`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1a4d5509ba69cde90836ddf369094242d0)`(SerializationInfo serializationInfo, StreamingContext streamingContext)` | Populates a SerializationInfo instance with the data needed to serialize this instance.
`public static bool ` [`IsRestricted`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1ace5529bba04cf7e45aab331d427488ac)`(string headerName)` | Determines whether the specified HTTP header can be set for the request.
`public static bool ` [`IsRestricted`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1a3dc6a9d7d76fac5b61c77f8013d2d410)`(string headerName, bool response)` | Determines whether the specified HTTP header can be set for the request or the response.
`private static static ` [`WebHeaderCollection`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1a3b255b650366edf41ab95bb4a2c722ea)`()` | 
`private static string ` [`checkName`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1a558a22486039034f9071679f3f90ff1e)`(string name, string paramName)` | 
`private static string ` [`checkValue`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1af963cc07d0e90f58287c9386fc74651f)`(string value, string paramName)` | 
`private static ` [`HttpHeaderInfo`](WebSocketSharp--Net--HttpHeaderInfo.md)` ` [`getHeaderInfo`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1a9e36bcd1f1285073d6b9ca67e36c2e93)`(string name)` | 
`private static string ` [`getHeaderName`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1a4774c5c9b5444c83544f7e5aac0965f5)`(string key)` | 
`private static ` [`HttpHeaderType`](WebSocketSharp--Net.md)` ` [`getHeaderType`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1ab3b83006594241d0ce970370e2f477a5)`(string name)` | 
`private static bool ` [`isMultiValue`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1ac02b46d520f9550e4081093cd7ea1a23)`(string name, bool response)` | 
`private static bool ` [`isRestricted`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1a744ff847a038ef93aacf7b7587f476db)`(string name, bool response)` | 

## Members

##### `package ` [`HttpHeaderType`](WebSocketSharp--Net.md)` ` [`State`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1a1e0580203f1062bb91d70dba9fec5003) 

##### `public override string[] ` [`AllKeys`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1ab04b0dbb307ef11ef445a3195f48fd39) 

Gets all header names in the collection.

An array of string that contains all header names in the collection.

##### `public override int ` [`Count`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1a9198bf6e7433159107917369117759d5) 

Gets the number of headers in the collection.

An int that represents the number of headers in the collection.

##### `public string ` [`this[HttpRequestHeader header]`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1af8e56c64af8ffb4fb3043a92d7032846) 

Gets or sets the specified request header.

A string that represents the value of the request header. 

#### Parameters
* `header` One of the HttpRequestHeader enum values. 

It specifies the request header to get or set. 

#### Exceptions
* `ArgumentException` *header*  is a restricted header. 

-or- 

*value*  contains an invalid character. 

* `ArgumentOutOfRangeException` The length of *value*  is greater than 65,535 characters. 

* `InvalidOperationException` This instance does not allow the request header.

##### `public string ` [`this[HttpResponseHeader header]`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1acb969ea1f9d6d92fe0948d7a03dc2034) 

Gets or sets the specified response header.

A string that represents the value of the response header. 

#### Parameters
* `header` One of the HttpResponseHeader enum values. 

It specifies the response header to get or set. 

#### Exceptions
* `ArgumentException` *header*  is a restricted header. 

-or- 

*value*  contains an invalid character. 

* `ArgumentOutOfRangeException` The length of *value*  is greater than 65,535 characters. 

* `InvalidOperationException` This instance does not allow the response header.

##### `public override NameObjectCollectionBase.KeysCollection ` [`Keys`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1a9f43c6619b839bcd3e9174de299ea96c) 

Gets a collection of header names in the collection.

A NameObjectCollectionBase.KeysCollection that contains all header names in the collection.

##### `public ` [`WebHeaderCollection`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1aed173f1f7f02780eb5c44c7cce60bc72)`()` 

Initializes a new instance of the WebHeaderCollection class.

##### `public void ` [`Add`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1a1b6c89758bce80c0abc77d58be0b4991)`(string header)` 

Adds the specified header to the collection.

#### Parameters
* `header` A string that specifies the header to add, with the name and value separated by a colon character (':'). 

#### Exceptions
* `ArgumentNullException` *header*  is `null`. 

* `ArgumentException` *header*  is an empty string. 

-or- 

*header*  does not contain a colon character. 

-or- 

The name part of *header*  is an empty string. 

-or- 

The name part of *header*  is a string of spaces. 

-or- 

The name part of *header*  contains an invalid character. 

-or- 

The value part of *header*  contains an invalid character. 

-or- 

*header*  is a restricted header. 

* `ArgumentOutOfRangeException` The length of the value part of *header*  is greater than 65,535 characters. 

* `InvalidOperationException` This instance does not allow the header.

##### `public void ` [`Add`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1a6b61f8d689ce5868d2d595207a78046b)`(` [`HttpRequestHeader`](WebSocketSharp--Net.md)` header, string value)` 

Adds the specified request header with the specified value to the collection.

#### Parameters
* `header` One of the HttpRequestHeader enum values. 

It specifies the request header to add. 

* `value` A string that specifies the value of the header to add. 

#### Exceptions
* `ArgumentException` *value*  contains an invalid character. 

-or- 

*header*  is a restricted header. 

* `ArgumentOutOfRangeException` The length of *value*  is greater than 65,535 characters. 

* `InvalidOperationException` This instance does not allow the request header.

##### `public void ` [`Add`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1a75bf5cdf1e6270e6c76eabed454a55b5)`(` [`HttpResponseHeader`](WebSocketSharp--Net.md)` header, string value)` 

Adds the specified response header with the specified value to the collection.

#### Parameters
* `header` One of the HttpResponseHeader enum values. 

It specifies the response header to add. 

* `value` A string that specifies the value of the header to add. 

#### Exceptions
* `ArgumentException` *value*  contains an invalid character. 

-or- 

*header*  is a restricted header. 

* `ArgumentOutOfRangeException` The length of *value*  is greater than 65,535 characters. 

* `InvalidOperationException` This instance does not allow the response header.

##### `public override void ` [`Add`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1af8464d0a11372f13dee1ddda2b6578fa)`(string name, string value)` 

Adds a header with the specified name and value to the collection.

#### Parameters
* `name` A string that specifies the name of the header to add. 

* `value` A string that specifies the value of the header to add. 

#### Exceptions
* `ArgumentNullException` *name*  is `null`. 

* `ArgumentException` *name*  is an empty string. 

-or- 

*name*  is a string of spaces. 

-or- 

*name*  contains an invalid character. 

-or- 

*value*  contains an invalid character. 

-or- 

*name*  is a restricted header name. 

* `ArgumentOutOfRangeException` The length of *value*  is greater than 65,535 characters. 

* `InvalidOperationException` This instance does not allow the header.

##### `public override void ` [`Clear`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1a19f6e9e119005114268f68098f143906)`()` 

Removes all headers from the collection.

##### `public override string ` [`Get`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1a6847b6cdc8b428247a46001710080607)`(int index)` 

Get the value of the header at the specified index in the collection.

#### Returns
A string that receives the value of the header. 

#### Parameters
* `index` An int that specifies the zero-based index of the header to find. 

#### Exceptions
* `ArgumentOutOfRangeException` *index*  is out of allowable range of indexes for the collection.

##### `public override string ` [`Get`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1aed2474b68bc4129e9dceda47e71d6330)`(string name)` 

Get the value of the header with the specified name in the collection.

#### Returns
A string that receives the value of the header. 

`null` if not found. 

#### Parameters
* `name` A string that specifies the name of the header to find.

##### `public override IEnumerator ` [`GetEnumerator`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1a84aa5c7f8c07cbac14a7611a1c7b3b42)`()` 

Gets the enumerator used to iterate through the collection.

#### Returns
An IEnumerator instance used to iterate through the collection.

##### `public override string ` [`GetKey`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1a5bd2a01f28f862773b3da82502bd71fc)`(int index)` 

Get the name of the header at the specified index in the collection.

#### Returns
A string that receives the name of the header. 

#### Parameters
* `index` An int that specifies the zero-based index of the header to find. 

#### Exceptions
* `ArgumentOutOfRangeException` *index*  is out of allowable range of indexes for the collection.

##### `public override string[] ` [`GetValues`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1a2d3b158932997b482e1bb8be23dc967b)`(int index)` 

Get the values of the header at the specified index in the collection.

#### Returns
An array of string that receives the values of the header. 

`null` if not present. 

#### Parameters
* `index` An int that specifies the zero-based index of the header to find. 

#### Exceptions
* `ArgumentOutOfRangeException` *index*  is out of allowable range of indexes for the collection.

##### `public override string[] ` [`GetValues`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1a95b0dadb01d1549eaf85d5fad46886a7)`(string name)` 

Get the values of the header with the specified name in the collection.

#### Returns
An array of string that receives the values of the header. 

`null` if not present. 

#### Parameters
* `name` A string that specifies the name of the header to find.

##### `public override void ` [`GetObjectData`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1a4cbc21245ff6badf7ef5f29bb3e8ee00)`(SerializationInfo serializationInfo, StreamingContext streamingContext)` 

Populates a SerializationInfo instance with the data needed to serialize this instance.

#### Parameters
* `serializationInfo` A SerializationInfo to populate with the data. 

* `streamingContext` A StreamingContext that specifies the destination for the serialization. 

#### Exceptions
* `ArgumentNullException` *serializationInfo*  is `null`.

##### `public override void ` [`OnDeserialization`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1a749cf4897a7a7f8c57f508d5dfe24cde)`(object sender)` 

Implements the ISerializable interface and raises the deserialization event when the deserialization is complete.

#### Parameters
* `sender` An object instance that represents the source of the deserialization event.

##### `public void ` [`Remove`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1ae8a4296e6a8496c5fa5c8e30d74f2a12)`(` [`HttpRequestHeader`](WebSocketSharp--Net.md)` header)` 

Removes the specified request header from the collection.

#### Parameters
* `header` One of the HttpRequestHeader enum values. 

It specifies the request header to remove. 

#### Exceptions
* `ArgumentException` *header*  is a restricted header. 

* `InvalidOperationException` This instance does not allow the request header.

##### `public void ` [`Remove`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1aa938ba6784674f1eda92577ce05773a9)`(` [`HttpResponseHeader`](WebSocketSharp--Net.md)` header)` 

Removes the specified response header from the collection.

#### Parameters
* `header` One of the HttpResponseHeader enum values. 

It specifies the response header to remove. 

#### Exceptions
* `ArgumentException` *header*  is a restricted header. 

* `InvalidOperationException` This instance does not allow the response header.

##### `public override void ` [`Remove`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1a245d236c58be797c13ddbadb1066ab36)`(string name)` 

Removes the specified header from the collection.

#### Parameters
* `name` A string that specifies the name of the header to remove. 

#### Exceptions
* `ArgumentNullException` *name*  is `null`. 

* `ArgumentException` *name*  is an empty string. 

-or- 

*name*  is a string of spaces. 

-or- 

*name*  contains an invalid character. 

-or- 

*name*  is a restricted header name. 

* `InvalidOperationException` This instance does not allow the header.

##### `public void ` [`Set`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1ab2ff9bcd1176fe7b64dd97920b2a5d6b)`(` [`HttpRequestHeader`](WebSocketSharp--Net.md)` header, string value)` 

Sets the specified request header to the specified value.

#### Parameters
* `header` One of the HttpRequestHeader enum values. 

It specifies the request header to set. 

* `value` A string that specifies the value of the request header to set. 

#### Exceptions
* `ArgumentException` *value*  contains an invalid character. 

-or- 

*header*  is a restricted header. 

* `ArgumentOutOfRangeException` The length of *value*  is greater than 65,535 characters. 

* `InvalidOperationException` This instance does not allow the request header.

##### `public void ` [`Set`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1a2f9d1beb43b66c386d2ea60ecc6d04e4)`(` [`HttpResponseHeader`](WebSocketSharp--Net.md)` header, string value)` 

Sets the specified response header to the specified value.

#### Parameters
* `header` One of the HttpResponseHeader enum values. 

It specifies the response header to set. 

* `value` A string that specifies the value of the response header to set. 

#### Exceptions
* `ArgumentException` *value*  contains an invalid character. 

-or- 

*header*  is a restricted header. 

* `ArgumentOutOfRangeException` The length of *value*  is greater than 65,535 characters. 

* `InvalidOperationException` This instance does not allow the response header.

##### `public override void ` [`Set`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1ad96bbd8e9c2b623a229fbda4f7be34ed)`(string name, string value)` 

Sets the specified header to the specified value.

#### Parameters
* `name` A string that specifies the name of the header to set. 

* `value` A string that specifies the value of the header to set. 

#### Exceptions
* `ArgumentNullException` *name*  is `null`. 

* `ArgumentException` *name*  is an empty string. 

-or- 

*name*  is a string of spaces. 

-or- 

*name*  contains an invalid character. 

-or- 

*value*  contains an invalid character. 

-or- 

*name*  is a restricted header name. 

* `ArgumentOutOfRangeException` The length of *value*  is greater than 65,535 characters. 

* `InvalidOperationException` This instance does not allow the header.

##### `public byte[] ` [`ToByteArray`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1a5e05025d8b0434ab88b76301915aff2b)`()` 

Converts the current instance to an array of byte.

#### Returns
An array of byte converted from a string that represents the current instance.

##### `public override string ` [`ToString`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1aa73e7c4dd1df5fd5fbf81c7764ee1533)`()` 

Returns a string that represents the current instance.

#### Returns
A string that represents all headers in the collection.

##### `protected ` [`WebHeaderCollection`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1a8dc7537a74093c7175ec9a2bc5e1789c)`(SerializationInfo serializationInfo, StreamingContext streamingContext)` 

Initializes a new instance of the WebHeaderCollection class from the specified instances of the SerializationInfo and StreamingContext classes.

#### Parameters
* `serializationInfo` A SerializationInfo that contains the serialized object data. 

* `streamingContext` A StreamingContext that specifies the source for the deserialization. 

#### Exceptions
* `ArgumentNullException` *serializationInfo*  is `null`. 

* `ArgumentException` An element with the specified name is not found in *serializationInfo* .

##### `protected void ` [`AddWithoutValidate`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1a41f231d396b1afbbf1f4436bbd1795db)`(string headerName, string headerValue)` 

Adds a header to the collection without checking if the header is on the restricted header list.

#### Parameters
* `headerName` A string that specifies the name of the header to add. 

* `headerValue` A string that specifies the value of the header to add. 

#### Exceptions
* `ArgumentNullException` *headerName*  is `null`. 

* `ArgumentException` *headerName*  is an empty string. 

-or- 

*headerName*  is a string of spaces. 

-or- 

*headerName*  contains an invalid character. 

-or- 

*headerValue*  contains an invalid character. 

* `ArgumentOutOfRangeException` The length of *headerValue*  is greater than 65,535 characters. 

* `InvalidOperationException` This instance does not allow the header.

##### `private bool ` [`_internallyUsed`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1a0c5853d5c67ec4fae622dc69f8afd278) 

##### `private ` [`HttpHeaderType`](WebSocketSharp--Net.md)` ` [`_state`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1a8f879a4c904d17af2f2e49ec4e1b1eec) 

##### `private void ` [`add`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1a9c83d4ba40ac486d25cd826e927527c8)`(string name, string value, ` [`HttpHeaderType`](WebSocketSharp--Net.md)` headerType)` 

##### `private void ` [`checkAllowed`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1ade88221efe2d03ccb2b57a77f491f9f6)`(` [`HttpHeaderType`](WebSocketSharp--Net.md)` headerType)` 

##### `private void ` [`checkRestricted`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1af7e93bdea8a189e02636e0647774e9fa)`(string name, ` [`HttpHeaderType`](WebSocketSharp--Net.md)` headerType)` 

##### `private void ` [`set`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1ac9f353605a5d6f48397fceec5198424a)`(string name, string value, ` [`HttpHeaderType`](WebSocketSharp--Net.md)` headerType)` 

##### `private void ISerializable. ` [`GetObjectData`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1a4d5509ba69cde90836ddf369094242d0)`(SerializationInfo serializationInfo, StreamingContext streamingContext)` 

Populates a SerializationInfo instance with the data needed to serialize this instance.

#### Parameters
* `serializationInfo` A SerializationInfo to populate with the data. 

* `streamingContext` A StreamingContext that specifies the destination for the serialization. 

#### Exceptions
* `ArgumentNullException` *serializationInfo*  is `null`.

##### `public static bool ` [`IsRestricted`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1ace5529bba04cf7e45aab331d427488ac)`(string headerName)` 

Determines whether the specified HTTP header can be set for the request.

#### Returns
`true` if the header cannot be set; otherwise, `false`. 

#### Parameters
* `headerName` A string that specifies the name of the header to test. 

#### Exceptions
* `ArgumentNullException` *headerName*  is `null`. 

* `ArgumentException` *headerName*  is an empty string. 

-or- 

*headerName*  is a string of spaces. 

-or- 

*headerName*  contains an invalid character.

##### `public static bool ` [`IsRestricted`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1a3dc6a9d7d76fac5b61c77f8013d2d410)`(string headerName, bool response)` 

Determines whether the specified HTTP header can be set for the request or the response.

#### Returns
`true` if the header cannot be set; otherwise, `false`. 

#### Parameters
* `headerName` A string that specifies the name of the header to test. 

* `response` A bool: `true` if the test is for the response; otherwise, `false`. 

#### Exceptions
* `ArgumentNullException` *headerName*  is `null`. 

* `ArgumentException` *headerName*  is an empty string. 

-or- 

*headerName*  is a string of spaces. 

-or- 

*headerName*  contains an invalid character.

##### `private static static ` [`WebHeaderCollection`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1a3b255b650366edf41ab95bb4a2c722ea)`()` 

##### `private static string ` [`checkName`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1a558a22486039034f9071679f3f90ff1e)`(string name, string paramName)` 

##### `private static string ` [`checkValue`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1af963cc07d0e90f58287c9386fc74651f)`(string value, string paramName)` 

##### `private static ` [`HttpHeaderInfo`](WebSocketSharp--Net--HttpHeaderInfo.md)` ` [`getHeaderInfo`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1a9e36bcd1f1285073d6b9ca67e36c2e93)`(string name)` 

##### `private static string ` [`getHeaderName`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1a4774c5c9b5444c83544f7e5aac0965f5)`(string key)` 

##### `private static ` [`HttpHeaderType`](WebSocketSharp--Net.md)` ` [`getHeaderType`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1ab3b83006594241d0ce970370e2f477a5)`(string name)` 

##### `private static bool ` [`isMultiValue`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1ac02b46d520f9550e4081093cd7ea1a23)`(string name, bool response)` 

##### `private static bool ` [`isRestricted`](#class_web_socket_sharp_1_1_net_1_1_web_header_collection_1a744ff847a038ef93aacf7b7587f476db)`(string name, bool response)` 

