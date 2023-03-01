# class `WebSocketSharp::Net::HttpListenerPrefixCollection` 

```
class WebSocketSharp::Net::HttpListenerPrefixCollection
  : public ICollection< string >
```

Provides a collection used to store the URI prefixes for a instance of the HttpListener class.

The HttpListener instance responds to the request which has a requested URI that the prefixes most closely match.

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public int ` [`Count`](#class_web_socket_sharp_1_1_net_1_1_http_listener_prefix_collection_1aad462966ed963f892117056de1eba502) | Gets the number of prefixes in the collection.
`public bool ` [`IsReadOnly`](#class_web_socket_sharp_1_1_net_1_1_http_listener_prefix_collection_1ad1b02f19e753582b3c5f9ed71bb0318a) | Gets a value indicating whether the access to the collection is read-only.
`public bool ` [`IsSynchronized`](#class_web_socket_sharp_1_1_net_1_1_http_listener_prefix_collection_1a94b969d24485ca893c76b3323b3326f4) | Gets a value indicating whether the access to the collection is synchronized.
`public void ` [`Add`](#class_web_socket_sharp_1_1_net_1_1_http_listener_prefix_collection_1a03324ae52001555c74489cbf75e343d9)`(string uriPrefix)` | Adds the specified URI prefix to the collection.
`public void ` [`Clear`](#class_web_socket_sharp_1_1_net_1_1_http_listener_prefix_collection_1aa71d36872f416feaa853788a7a7a7ef8)`()` | Removes all URI prefixes from the collection.
`public bool ` [`Contains`](#class_web_socket_sharp_1_1_net_1_1_http_listener_prefix_collection_1a1e55c829396fa4e8613c8633e9a3acbd)`(string uriPrefix)` | Returns a value indicating whether the collection contains the specified URI prefix.
`public void ` [`CopyTo`](#class_web_socket_sharp_1_1_net_1_1_http_listener_prefix_collection_1a7c1cd4ff0e281185ae80a5e72280462e)`(string[] array, int offset)` | Copies the contents of the collection to the specified array of string.
`public IEnumerator< string > ` [`GetEnumerator`](#class_web_socket_sharp_1_1_net_1_1_http_listener_prefix_collection_1aa0a0ee79e0ff578fbd19069b2790ff73)`()` | Gets the enumerator that iterates through the collection.
`public bool ` [`Remove`](#class_web_socket_sharp_1_1_net_1_1_http_listener_prefix_collection_1ab8056f900a9a8a01f64efc133ecd4cf5)`(string uriPrefix)` | Removes the specified URI prefix from the collection.
`private ` [`HttpListener`](WebSocketSharp--Net--HttpListener.md)` ` [`_listener`](#class_web_socket_sharp_1_1_net_1_1_http_listener_prefix_collection_1ab5753944447cd49f99da3ec676f16769) | 
`private List< string > ` [`_prefixes`](#class_web_socket_sharp_1_1_net_1_1_http_listener_prefix_collection_1a79343bc0cf324b9dcf0e90afd10ebdc3) | 
`private IEnumerator IEnumerable. ` [`GetEnumerator`](#class_web_socket_sharp_1_1_net_1_1_http_listener_prefix_collection_1a7d819d2ba8ffadd29113c811ce043c9f)`()` | Gets the enumerator that iterates through the collection.

## Members

##### `public int ` [`Count`](#class_web_socket_sharp_1_1_net_1_1_http_listener_prefix_collection_1aad462966ed963f892117056de1eba502) 

Gets the number of prefixes in the collection.

An int that represents the number of prefixes.

##### `public bool ` [`IsReadOnly`](#class_web_socket_sharp_1_1_net_1_1_http_listener_prefix_collection_1ad1b02f19e753582b3c5f9ed71bb0318a) 

Gets a value indicating whether the access to the collection is read-only.

Always returns `false`.

##### `public bool ` [`IsSynchronized`](#class_web_socket_sharp_1_1_net_1_1_http_listener_prefix_collection_1a94b969d24485ca893c76b3323b3326f4) 

Gets a value indicating whether the access to the collection is synchronized.

Always returns `false`.

##### `public void ` [`Add`](#class_web_socket_sharp_1_1_net_1_1_http_listener_prefix_collection_1a03324ae52001555c74489cbf75e343d9)`(string uriPrefix)` 

Adds the specified URI prefix to the collection.

#### Parameters
* `uriPrefix` A string that specifies the URI prefix to add. 

It must be a well-formed URI prefix with http or https scheme, and must end with a '/'. 

#### Exceptions
* `ArgumentNullException` *uriPrefix*  is `null`. 

* `ArgumentException` *uriPrefix*  is invalid. 

* `ObjectDisposedException` The HttpListener instance associated with this collection is closed.

##### `public void ` [`Clear`](#class_web_socket_sharp_1_1_net_1_1_http_listener_prefix_collection_1aa71d36872f416feaa853788a7a7a7ef8)`()` 

Removes all URI prefixes from the collection.

#### Exceptions
* `ObjectDisposedException` The HttpListener instance associated with this collection is closed.

##### `public bool ` [`Contains`](#class_web_socket_sharp_1_1_net_1_1_http_listener_prefix_collection_1a1e55c829396fa4e8613c8633e9a3acbd)`(string uriPrefix)` 

Returns a value indicating whether the collection contains the specified URI prefix.

#### Returns
`true` if the collection contains the URI prefix; otherwise, `false`. 

#### Parameters
* `uriPrefix` A string that specifies the URI prefix to test. 

#### Exceptions
* `ArgumentNullException` *uriPrefix*  is `null`. 

* `ObjectDisposedException` The HttpListener instance associated with this collection is closed.

##### `public void ` [`CopyTo`](#class_web_socket_sharp_1_1_net_1_1_http_listener_prefix_collection_1a7c1cd4ff0e281185ae80a5e72280462e)`(string[] array, int offset)` 

Copies the contents of the collection to the specified array of string.

#### Parameters
* `array` An array of string that specifies the destination of the URI prefix strings copied from the collection. 

* `offset` An int that specifies the zero-based index in the array at which copying begins. 

#### Exceptions
* `ArgumentNullException` *array*  is `null`. 

* `ArgumentOutOfRangeException` *offset*  is less than zero. 

* `ArgumentException` The space from *offset*  to the end of *array*  is not enough to copy to. 

* `ObjectDisposedException` The HttpListener instance associated with this collection is closed.

##### `public IEnumerator< string > ` [`GetEnumerator`](#class_web_socket_sharp_1_1_net_1_1_http_listener_prefix_collection_1aa0a0ee79e0ff578fbd19069b2790ff73)`()` 

Gets the enumerator that iterates through the collection.

#### Returns
An T:System.Collections.Generic.IEnumerator<string> instance that can be used to iterate through the collection.

##### `public bool ` [`Remove`](#class_web_socket_sharp_1_1_net_1_1_http_listener_prefix_collection_1ab8056f900a9a8a01f64efc133ecd4cf5)`(string uriPrefix)` 

Removes the specified URI prefix from the collection.

#### Returns
`true` if the URI prefix is successfully removed; otherwise, `false`. 

#### Parameters
* `uriPrefix` A string that specifies the URI prefix to remove. 

#### Exceptions
* `ArgumentNullException` *uriPrefix*  is `null`. 

* `ObjectDisposedException` The HttpListener instance associated with this collection is closed.

##### `private ` [`HttpListener`](WebSocketSharp--Net--HttpListener.md)` ` [`_listener`](#class_web_socket_sharp_1_1_net_1_1_http_listener_prefix_collection_1ab5753944447cd49f99da3ec676f16769) 

##### `private List< string > ` [`_prefixes`](#class_web_socket_sharp_1_1_net_1_1_http_listener_prefix_collection_1a79343bc0cf324b9dcf0e90afd10ebdc3) 

##### `private IEnumerator IEnumerable. ` [`GetEnumerator`](#class_web_socket_sharp_1_1_net_1_1_http_listener_prefix_collection_1a7d819d2ba8ffadd29113c811ce043c9f)`()` 

Gets the enumerator that iterates through the collection.

#### Returns
An IEnumerator instance that can be used to iterate through the collection.

