# class `WebSocketSharp::Net::CookieCollection` 

```
class WebSocketSharp::Net::CookieCollection
  : public ICollection< Cookie >
```

Provides a collection of instances of the Cookie class.

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`package IList< ` [`Cookie`](WebSocketSharp--Net--Cookie.md)` > ` [`List`](#class_web_socket_sharp_1_1_net_1_1_cookie_collection_1a3df2a6166b38fc0ce267ccfe69b60a50) | 
`package IEnumerable< ` [`Cookie`](WebSocketSharp--Net--Cookie.md)` > ` [`Sorted`](#class_web_socket_sharp_1_1_net_1_1_cookie_collection_1adb679b50cd78ecc85bd88773f1ec5cf3) | 
`public int ` [`Count`](#class_web_socket_sharp_1_1_net_1_1_cookie_collection_1aad462966ed963f892117056de1eba502) | Gets the number of cookies in the collection.
`public bool ` [`IsReadOnly`](#class_web_socket_sharp_1_1_net_1_1_cookie_collection_1ad1b02f19e753582b3c5f9ed71bb0318a) | Gets a value indicating whether the collection is read-only.
`public bool ` [`IsSynchronized`](#class_web_socket_sharp_1_1_net_1_1_cookie_collection_1a94b969d24485ca893c76b3323b3326f4) | Gets a value indicating whether the access to the collection is thread safe.
`public ` [`Cookie`](WebSocketSharp--Net--Cookie.md)` ` [`this[int index]`](#class_web_socket_sharp_1_1_net_1_1_cookie_collection_1afe49b65c54e423279293acd3143278b5) | Gets the cookie at the specified index from the collection.
`public ` [`Cookie`](WebSocketSharp--Net--Cookie.md)` ` [`this[string name]`](#class_web_socket_sharp_1_1_net_1_1_cookie_collection_1a1cd2e8a6e8e821e5ed26a73dcde7b7e0) | Gets the cookie with the specified name from the collection.
`public object ` [`SyncRoot`](#class_web_socket_sharp_1_1_net_1_1_cookie_collection_1aede0ddd625f3f4969ddba51f6431bff1) | Gets an object used to synchronize access to the collection.
`public ` [`CookieCollection`](#class_web_socket_sharp_1_1_net_1_1_cookie_collection_1a8963df8e7614d9182d237998571e94c7)`()` | Initializes a new instance of the CookieCollection class.
`public void ` [`Add`](#class_web_socket_sharp_1_1_net_1_1_cookie_collection_1aefb1bd48e90b86e759282908dc47a29c)`(` [`Cookie`](WebSocketSharp--Net--Cookie.md)` cookie)` | Adds the specified cookie to the collection.
`public void ` [`Add`](#class_web_socket_sharp_1_1_net_1_1_cookie_collection_1a0d93e71904dd0d41d385b1763327cb6c)`(` [`CookieCollection`](#class_web_socket_sharp_1_1_net_1_1_cookie_collection)` cookies)` | Adds the specified cookies to the collection.
`public void ` [`Clear`](#class_web_socket_sharp_1_1_net_1_1_cookie_collection_1aa71d36872f416feaa853788a7a7a7ef8)`()` | Removes all cookies from the collection.
`public bool ` [`Contains`](#class_web_socket_sharp_1_1_net_1_1_cookie_collection_1a1980f6a1053b449f6dd42f92f83bb4b5)`(` [`Cookie`](WebSocketSharp--Net--Cookie.md)` cookie)` | Determines whether the collection contains the specified cookie.
`public void ` [`CopyTo`](#class_web_socket_sharp_1_1_net_1_1_cookie_collection_1aba6b502135948a837b5ea349481ca3d8)`(` [`Cookie`](WebSocketSharp--Net--Cookie.md)` array, int index)` | Copies the elements of the collection to the specified array, starting at the specified index.
`public IEnumerator< ` [`Cookie`](WebSocketSharp--Net--Cookie.md)` > ` [`GetEnumerator`](#class_web_socket_sharp_1_1_net_1_1_cookie_collection_1a367a2f12afaf56cb0919049bbeecf3a7)`()` | Gets the enumerator that iterates through the collection.
`public bool ` [`Remove`](#class_web_socket_sharp_1_1_net_1_1_cookie_collection_1a7a9efe20c2ec35fd1cae17e83614e510)`(` [`Cookie`](WebSocketSharp--Net--Cookie.md)` cookie)` | Removes the specified cookie from the collection.
`private ` [`List](#class_web_socket_sharp_1_1_net_1_1_cookie_collection_1a3df2a6166b38fc0ce267ccfe69b60a50)< [Cookie`](WebSocketSharp--Net--Cookie.md)` > ` [`_list`](#class_web_socket_sharp_1_1_net_1_1_cookie_collection_1a1e96abec2608ec3c681ec8d83dd8e822) | 
`private bool ` [`_readOnly`](#class_web_socket_sharp_1_1_net_1_1_cookie_collection_1a00cb751872aa86075f15e1bb68fdd29a) | 
`private object ` [`_sync`](#class_web_socket_sharp_1_1_net_1_1_cookie_collection_1adbb069fcd0e2b452bc3342bc00739ed8) | 
`private void ` [`add`](#class_web_socket_sharp_1_1_net_1_1_cookie_collection_1ad590465ff2b2ebd74fcf737ff21c4815)`(` [`Cookie`](WebSocketSharp--Net--Cookie.md)` cookie)` | 
`private int ` [`search`](#class_web_socket_sharp_1_1_net_1_1_cookie_collection_1ae7d79f2929cf6a6921f60709dea68985)`(` [`Cookie`](WebSocketSharp--Net--Cookie.md)` cookie)` | 
`private IEnumerator IEnumerable. ` [`GetEnumerator`](#class_web_socket_sharp_1_1_net_1_1_cookie_collection_1a7d819d2ba8ffadd29113c811ce043c9f)`()` | Gets the enumerator that iterates through the collection.
`private static int ` [`compareForSort`](#class_web_socket_sharp_1_1_net_1_1_cookie_collection_1aaac806c8b4147bf88962230e2b17bdb5)`(` [`Cookie`](WebSocketSharp--Net--Cookie.md)` x, ` [`Cookie`](WebSocketSharp--Net--Cookie.md)` y)` | 
`private static int ` [`compareForSorted`](#class_web_socket_sharp_1_1_net_1_1_cookie_collection_1ac3772282de104a7ae871dcf85bb1c1a5)`(` [`Cookie`](WebSocketSharp--Net--Cookie.md)` x, ` [`Cookie`](WebSocketSharp--Net--Cookie.md)` y)` | 
`private static ` [`CookieCollection`](#class_web_socket_sharp_1_1_net_1_1_cookie_collection)` ` [`parseRequest`](#class_web_socket_sharp_1_1_net_1_1_cookie_collection_1abc51d8190670684b7b3a83c0977a598b)`(string value)` | 
`private static ` [`CookieCollection`](#class_web_socket_sharp_1_1_net_1_1_cookie_collection)` ` [`parseResponse`](#class_web_socket_sharp_1_1_net_1_1_cookie_collection_1a8d74ddadbd23e80d75efa58d67d2a152)`(string value)` | 
`private static string ` [`urlDecode`](#class_web_socket_sharp_1_1_net_1_1_cookie_collection_1a8e0d21cf78494f1a9e1e3230cfe6dfbd)`(string s, Encoding encoding)` | 

## Members

##### `package IList< ` [`Cookie`](WebSocketSharp--Net--Cookie.md)` > ` [`List`](#class_web_socket_sharp_1_1_net_1_1_cookie_collection_1a3df2a6166b38fc0ce267ccfe69b60a50) 

##### `package IEnumerable< ` [`Cookie`](WebSocketSharp--Net--Cookie.md)` > ` [`Sorted`](#class_web_socket_sharp_1_1_net_1_1_cookie_collection_1adb679b50cd78ecc85bd88773f1ec5cf3) 

##### `public int ` [`Count`](#class_web_socket_sharp_1_1_net_1_1_cookie_collection_1aad462966ed963f892117056de1eba502) 

Gets the number of cookies in the collection.

An int that represents the number of cookies in the collection.

##### `public bool ` [`IsReadOnly`](#class_web_socket_sharp_1_1_net_1_1_cookie_collection_1ad1b02f19e753582b3c5f9ed71bb0318a) 

Gets a value indicating whether the collection is read-only.

`true` if the collection is read-only; otherwise, `false`. 

The default value is `false`.

##### `public bool ` [`IsSynchronized`](#class_web_socket_sharp_1_1_net_1_1_cookie_collection_1a94b969d24485ca893c76b3323b3326f4) 

Gets a value indicating whether the access to the collection is thread safe.

`true` if the access to the collection is thread safe; otherwise, `false`. 

The default value is `false`.

##### `public ` [`Cookie`](WebSocketSharp--Net--Cookie.md)` ` [`this[int index]`](#class_web_socket_sharp_1_1_net_1_1_cookie_collection_1afe49b65c54e423279293acd3143278b5) 

Gets the cookie at the specified index from the collection.

A Cookie at the specified index in the collection. 

#### Parameters
* `index` An int that specifies the zero-based index of the cookie to find. 

#### Exceptions
* `ArgumentOutOfRangeException` *index*  is out of allowable range for the collection.

##### `public ` [`Cookie`](WebSocketSharp--Net--Cookie.md)` ` [`this[string name]`](#class_web_socket_sharp_1_1_net_1_1_cookie_collection_1a1cd2e8a6e8e821e5ed26a73dcde7b7e0) 

Gets the cookie with the specified name from the collection.

A Cookie with the specified name in the collection. 

`null` if not found. 

#### Parameters
* `name` A string that specifies the name of the cookie to find. 

#### Exceptions
* `ArgumentNullException` *name*  is `null`.

##### `public object ` [`SyncRoot`](#class_web_socket_sharp_1_1_net_1_1_cookie_collection_1aede0ddd625f3f4969ddba51f6431bff1) 

Gets an object used to synchronize access to the collection.

An object used to synchronize access to the collection.

##### `public ` [`CookieCollection`](#class_web_socket_sharp_1_1_net_1_1_cookie_collection_1a8963df8e7614d9182d237998571e94c7)`()` 

Initializes a new instance of the CookieCollection class.

##### `public void ` [`Add`](#class_web_socket_sharp_1_1_net_1_1_cookie_collection_1aefb1bd48e90b86e759282908dc47a29c)`(` [`Cookie`](WebSocketSharp--Net--Cookie.md)` cookie)` 

Adds the specified cookie to the collection.

#### Parameters
* `cookie` A Cookie to add. 

#### Exceptions
* `InvalidOperationException` The collection is read-only. 

* `ArgumentNullException` *cookie*  is `null`.

##### `public void ` [`Add`](#class_web_socket_sharp_1_1_net_1_1_cookie_collection_1a0d93e71904dd0d41d385b1763327cb6c)`(` [`CookieCollection`](#class_web_socket_sharp_1_1_net_1_1_cookie_collection)` cookies)` 

Adds the specified cookies to the collection.

#### Parameters
* `cookies` A CookieCollection that contains the cookies to add. 

#### Exceptions
* `InvalidOperationException` The collection is read-only. 

* `ArgumentNullException` *cookies*  is `null`.

##### `public void ` [`Clear`](#class_web_socket_sharp_1_1_net_1_1_cookie_collection_1aa71d36872f416feaa853788a7a7a7ef8)`()` 

Removes all cookies from the collection.

#### Exceptions
* `InvalidOperationException` The collection is read-only.

##### `public bool ` [`Contains`](#class_web_socket_sharp_1_1_net_1_1_cookie_collection_1a1980f6a1053b449f6dd42f92f83bb4b5)`(` [`Cookie`](WebSocketSharp--Net--Cookie.md)` cookie)` 

Determines whether the collection contains the specified cookie.

#### Returns
`true` if the cookie is found in the collection; otherwise, `false`. 

#### Parameters
* `cookie` A Cookie to find. 

#### Exceptions
* `ArgumentNullException` *cookie*  is `null`.

##### `public void ` [`CopyTo`](#class_web_socket_sharp_1_1_net_1_1_cookie_collection_1aba6b502135948a837b5ea349481ca3d8)`(` [`Cookie`](WebSocketSharp--Net--Cookie.md)` array, int index)` 

Copies the elements of the collection to the specified array, starting at the specified index.

#### Parameters
* `array` An array of Cookie that specifies the destination of the elements copied from the collection. 

* `index` An int that specifies the zero-based index in the array at which copying starts. 

#### Exceptions
* `ArgumentNullException` *array*  is `null`. 

* `ArgumentOutOfRangeException` *index*  is less than zero. 

* `ArgumentException` The space from *index*  to the end of *array*  is not enough to copy to.

##### `public IEnumerator< ` [`Cookie`](WebSocketSharp--Net--Cookie.md)` > ` [`GetEnumerator`](#class_web_socket_sharp_1_1_net_1_1_cookie_collection_1a367a2f12afaf56cb0919049bbeecf3a7)`()` 

Gets the enumerator that iterates through the collection.

#### Returns
An T:System.Collections.Generic.IEnumerator<Cookie> instance that can be used to iterate through the collection.

##### `public bool ` [`Remove`](#class_web_socket_sharp_1_1_net_1_1_cookie_collection_1a7a9efe20c2ec35fd1cae17e83614e510)`(` [`Cookie`](WebSocketSharp--Net--Cookie.md)` cookie)` 

Removes the specified cookie from the collection.

#### Returns
`true` if the cookie is successfully removed; otherwise, `false`. 

`false` if the cookie is not found in the collection. 

#### Parameters
* `cookie` A Cookie to remove. 

#### Exceptions
* `InvalidOperationException` The collection is read-only. 

* `ArgumentNullException` *cookie*  is `null`.

##### `private ` [`List](#class_web_socket_sharp_1_1_net_1_1_cookie_collection_1a3df2a6166b38fc0ce267ccfe69b60a50)< [Cookie`](WebSocketSharp--Net--Cookie.md)` > ` [`_list`](#class_web_socket_sharp_1_1_net_1_1_cookie_collection_1a1e96abec2608ec3c681ec8d83dd8e822) 

##### `private bool ` [`_readOnly`](#class_web_socket_sharp_1_1_net_1_1_cookie_collection_1a00cb751872aa86075f15e1bb68fdd29a) 

##### `private object ` [`_sync`](#class_web_socket_sharp_1_1_net_1_1_cookie_collection_1adbb069fcd0e2b452bc3342bc00739ed8) 

##### `private void ` [`add`](#class_web_socket_sharp_1_1_net_1_1_cookie_collection_1ad590465ff2b2ebd74fcf737ff21c4815)`(` [`Cookie`](WebSocketSharp--Net--Cookie.md)` cookie)` 

##### `private int ` [`search`](#class_web_socket_sharp_1_1_net_1_1_cookie_collection_1ae7d79f2929cf6a6921f60709dea68985)`(` [`Cookie`](WebSocketSharp--Net--Cookie.md)` cookie)` 

##### `private IEnumerator IEnumerable. ` [`GetEnumerator`](#class_web_socket_sharp_1_1_net_1_1_cookie_collection_1a7d819d2ba8ffadd29113c811ce043c9f)`()` 

Gets the enumerator that iterates through the collection.

#### Returns
An IEnumerator instance that can be used to iterate through the collection.

##### `private static int ` [`compareForSort`](#class_web_socket_sharp_1_1_net_1_1_cookie_collection_1aaac806c8b4147bf88962230e2b17bdb5)`(` [`Cookie`](WebSocketSharp--Net--Cookie.md)` x, ` [`Cookie`](WebSocketSharp--Net--Cookie.md)` y)` 

##### `private static int ` [`compareForSorted`](#class_web_socket_sharp_1_1_net_1_1_cookie_collection_1ac3772282de104a7ae871dcf85bb1c1a5)`(` [`Cookie`](WebSocketSharp--Net--Cookie.md)` x, ` [`Cookie`](WebSocketSharp--Net--Cookie.md)` y)` 

##### `private static ` [`CookieCollection`](#class_web_socket_sharp_1_1_net_1_1_cookie_collection)` ` [`parseRequest`](#class_web_socket_sharp_1_1_net_1_1_cookie_collection_1abc51d8190670684b7b3a83c0977a598b)`(string value)` 

##### `private static ` [`CookieCollection`](#class_web_socket_sharp_1_1_net_1_1_cookie_collection)` ` [`parseResponse`](#class_web_socket_sharp_1_1_net_1_1_cookie_collection_1a8d74ddadbd23e80d75efa58d67d2a152)`(string value)` 

##### `private static string ` [`urlDecode`](#class_web_socket_sharp_1_1_net_1_1_cookie_collection_1a8e0d21cf78494f1a9e1e3230cfe6dfbd)`(string s, Encoding encoding)` 

