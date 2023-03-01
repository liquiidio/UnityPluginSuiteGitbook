# class `WebSocketSharp::Ext` 

Provides a set of static methods for websocket-sharp.

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public static string ` [`GetDescription`](#class_web_socket_sharp_1_1_ext_1ab9cf4c5df2bcdab77d169c77f996b6fa)`(this ` [`HttpStatusCode`](WebSocketSharp--Net.md)` code)` | Gets the description of the specified HTTP status code.
`public static string ` [`GetStatusDescription`](#class_web_socket_sharp_1_1_ext_1a78f857c9d2cd8934a25932a5861cf505)`(this int code)` | Gets the description of the specified HTTP status code.
`public static bool ` [`IsCloseStatusCode`](#class_web_socket_sharp_1_1_ext_1a30f1a5c26062c76a0ca68d2d41bda2e2)`(this ushort value)` | Determines whether the specified ushort is in the range of the status code for the WebSocket connection close.
`public static bool ` [`IsEnclosedIn`](#class_web_socket_sharp_1_1_ext_1a3e6ec2281f6c6be292105765d953ca02)`(this string value, char c)` | Determines whether the specified string is enclosed in the specified character.
`public static bool ` [`IsHostOrder`](#class_web_socket_sharp_1_1_ext_1a87ed6fa881343fd5a7221096e374c173)`(this ` [`ByteOrder`](WebSocketSharp.md)` order)` | Determines whether the specified byte order is host (this computer architecture) byte order.
`public static bool ` [`IsLocal`](#class_web_socket_sharp_1_1_ext_1a46a397ba6a3b8d55824d94243a499f3f)`(this System.Net.IPAddress address)` | Determines whether the specified IP address is a local IP address.
`public static bool ` [`IsNullOrEmpty`](#class_web_socket_sharp_1_1_ext_1a8604d57ccce1e757f4772dc909f01086)`(this string value)` | Determines whether the specified string is `null` or an empty string.
`public static bool ` [`IsPredefinedScheme`](#class_web_socket_sharp_1_1_ext_1a5c05df80c3ea15de9da59ee1cc8b5b9e)`(this string value)` | Determines whether the specified string is a predefined scheme.
`public static bool ` [`MaybeUri`](#class_web_socket_sharp_1_1_ext_1a056449b1b82712baafa731bbf73c4077)`(this string value)` | Determines whether the specified string is a URI string.
`public static T[] ` [`SubArray< T >`](#class_web_socket_sharp_1_1_ext_1a8b308ba669b589d561f69aef4db09a6b)`(this T[] array, int startIndex, int length)` | Retrieves a sub-array from the specified array. A sub-array starts at the specified index in the array.
`public static T[] ` [`SubArray< T >`](#class_web_socket_sharp_1_1_ext_1a0a7ae84beda3d9638e6b96e12f47cdbd)`(this T[] array, long startIndex, long length)` | Retrieves a sub-array from the specified array. A sub-array starts at the specified index in the array.
`public static void ` [`Times`](#class_web_socket_sharp_1_1_ext_1ab170ebf318e09576d0a27af1523c66b7)`(this int n, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)` action)` | Executes the specified delegate *n* times.
`public static void ` [`Times`](#class_web_socket_sharp_1_1_ext_1a9c361b6e6120b605a0de1884da6c9451)`(this long n, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)` action)` | Executes the specified delegate *n* times.
`public static void ` [`Times`](#class_web_socket_sharp_1_1_ext_1a9d4e6f35b4fc06230beccd2b001b0f9d)`(this uint n, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)` action)` | Executes the specified delegate *n* times.
`public static void ` [`Times`](#class_web_socket_sharp_1_1_ext_1a7ba8aaaf134a8e4b8d03a6de1d14b1a8)`(this ulong n, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)` action)` | Executes the specified delegate *n* times.
`public static void ` [`Times`](#class_web_socket_sharp_1_1_ext_1a42fc1ec523a57117ac064639c8613a6f)`(this int n, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)`< int > action)` | Executes the specified delegate *n* times.
`public static void ` [`Times`](#class_web_socket_sharp_1_1_ext_1ad52dd34421d625470edfff7df0440e99)`(this long n, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)`< long > action)` | Executes the specified delegate *n* times.
`public static void ` [`Times`](#class_web_socket_sharp_1_1_ext_1a06faac195b1ed2c3546aa19a80be2ea7)`(this uint n, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)`< uint > action)` | Executes the specified delegate *n* times.
`public static void ` [`Times`](#class_web_socket_sharp_1_1_ext_1a989eb99783a2ab8e6f5c1d87ffcd76bd)`(this ulong n, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)`< ulong > action)` | Executes the specified delegate *n* times.
`public static T ` [`To< T >`](#class_web_socket_sharp_1_1_ext_1a678d3c2bd8ebf9fcdb71717b09f14625)`(this byte[] source, ` [`ByteOrder`](WebSocketSharp.md)` sourceOrder)` | Converts the specified byte array to the specified type value.
`public static byte[] ` [`ToByteArray< T >`](#class_web_socket_sharp_1_1_ext_1a8d8b2ceb186d1622fed7964fe9ebba3d)`(this T value, ` [`ByteOrder`](WebSocketSharp.md)` order)` | Converts the specified value to a byte array.
`public static byte[] ` [`ToHostOrder`](#class_web_socket_sharp_1_1_ext_1a6edf4e6e7e3eae9450243da28dd4ed96)`(this byte[] source, ` [`ByteOrder`](WebSocketSharp.md)` sourceOrder)` | Converts the order of elements in the specified byte array to host (this computer architecture) byte order.
`public static string ` [`ToString< T >`](#class_web_socket_sharp_1_1_ext_1ab1e5b8a65f818a514e22002469c9814a)`(this T[] array, string separator)` | Converts the specified array to a string.
`public static Uri ` [`ToUri`](#class_web_socket_sharp_1_1_ext_1ab7f3424773f904db9b7e689ed65d8c27)`(this string value)` | Converts the specified string to a Uri.
`public static void ` [`WriteContent`](#class_web_socket_sharp_1_1_ext_1a227eb824fbbda50cb284447437364456)`(this ` [`HttpListenerResponse`](WebSocketSharp--Net--HttpListenerResponse.md)` response, byte[] content)` | Sends the specified content data with the HTTP response.
`private static byte[] ` [`compress`](#class_web_socket_sharp_1_1_ext_1a591323d2a514de7f129da9b0a8c41f2a)`(this byte[] data)` | 
`private static MemoryStream ` [`compress`](#class_web_socket_sharp_1_1_ext_1ac35288dbed3a63ede58734526b50b2e4)`(this Stream stream)` | 
`private static byte[] ` [`compressToArray`](#class_web_socket_sharp_1_1_ext_1ae63c6b2a3072b16ece41dfe2ed955e0c)`(this Stream stream)` | 
`private static byte[] ` [`decompress`](#class_web_socket_sharp_1_1_ext_1a6781766bc699c503541d5e4e11dee3a5)`(this byte[] data)` | 
`private static MemoryStream ` [`decompress`](#class_web_socket_sharp_1_1_ext_1ae60f9706084fc10b4b56a409613e01c3)`(this Stream stream)` | 
`private static byte[] ` [`decompressToArray`](#class_web_socket_sharp_1_1_ext_1a41650c3d96ce109480809ff7115794f4)`(this Stream stream)` | 
`private static bool ` [`isHttpMethod`](#class_web_socket_sharp_1_1_ext_1abf46bf391a69c904dc6de0eb067f5f9c)`(this string value)` | 
`private static bool ` [`isHttpMethod10`](#class_web_socket_sharp_1_1_ext_1a80ecde5ced27fb7ad8f42cb22715111b)`(this string value)` | 

## Members

##### `public static string ` [`GetDescription`](#class_web_socket_sharp_1_1_ext_1ab9cf4c5df2bcdab77d169c77f996b6fa)`(this ` [`HttpStatusCode`](WebSocketSharp--Net.md)` code)` 

Gets the description of the specified HTTP status code.

#### Returns
A string that represents the description of the HTTP status code. 

#### Parameters
* `code` One of the [HttpStatusCode](WebSocketSharp--Net.md) enum values. 

It specifies the HTTP status code.

##### `public static string ` [`GetStatusDescription`](#class_web_socket_sharp_1_1_ext_1a78f857c9d2cd8934a25932a5861cf505)`(this int code)` 

Gets the description of the specified HTTP status code.

#### Returns
A string that represents the description of the HTTP status code. 

An empty string if the description is not present. 

#### Parameters
* `code` An int that specifies the HTTP status code.

##### `public static bool ` [`IsCloseStatusCode`](#class_web_socket_sharp_1_1_ext_1a30f1a5c26062c76a0ca68d2d41bda2e2)`(this ushort value)` 

Determines whether the specified ushort is in the range of the status code for the WebSocket connection close.

The ranges are the following: 

* 1000-2999: These numbers are reserved for definition by the WebSocket protocol.   

* 3000-3999: These numbers are reserved for use by libraries, frameworks, and applications.   

* 4000-4999: These numbers are reserved for private use.   

#### Returns
`true` if *value*  is in the range of the status code for the close; otherwise, `false`. 

#### Parameters
* `value` A ushort to test.

##### `public static bool ` [`IsEnclosedIn`](#class_web_socket_sharp_1_1_ext_1a3e6ec2281f6c6be292105765d953ca02)`(this string value, char c)` 

Determines whether the specified string is enclosed in the specified character.

#### Returns
`true` if *value*  is enclosed in *c* ; otherwise, `false`. 

#### Parameters
* `value` A string to test. 

* `c` A char to find.

##### `public static bool ` [`IsHostOrder`](#class_web_socket_sharp_1_1_ext_1a87ed6fa881343fd5a7221096e374c173)`(this ` [`ByteOrder`](WebSocketSharp.md)` order)` 

Determines whether the specified byte order is host (this computer architecture) byte order.

#### Returns
`true` if *order*  is host byte order; otherwise, `false`. 

#### Parameters
* `order` One of the ByteOrder enum values to test.

##### `public static bool ` [`IsLocal`](#class_web_socket_sharp_1_1_ext_1a46a397ba6a3b8d55824d94243a499f3f)`(this System.Net.IPAddress address)` 

Determines whether the specified IP address is a local IP address.

This local means NOT REMOTE for the current host. 

#### Returns
`true` if *address*  is a local IP address; otherwise, `false`. 

#### Parameters
* `address` A System.Net.IPAddress to test. 

#### Exceptions
* `ArgumentNullException` *address*  is `null`.

##### `public static bool ` [`IsNullOrEmpty`](#class_web_socket_sharp_1_1_ext_1a8604d57ccce1e757f4772dc909f01086)`(this string value)` 

Determines whether the specified string is `null` or an empty string.

#### Returns
`true` if *value*  is `null` or an empty string; otherwise, `false`. 

#### Parameters
* `value` A string to test.

##### `public static bool ` [`IsPredefinedScheme`](#class_web_socket_sharp_1_1_ext_1a5c05df80c3ea15de9da59ee1cc8b5b9e)`(this string value)` 

Determines whether the specified string is a predefined scheme.

#### Returns
`true` if *value*  is a predefined scheme; otherwise, `false`. 

#### Parameters
* `value` A string to test.

##### `public static bool ` [`MaybeUri`](#class_web_socket_sharp_1_1_ext_1a056449b1b82712baafa731bbf73c4077)`(this string value)` 

Determines whether the specified string is a URI string.

#### Returns
`true` if *value*  may be a URI string; otherwise, `false`. 

#### Parameters
* `value` A string to test.

##### `public static T[] ` [`SubArray< T >`](#class_web_socket_sharp_1_1_ext_1a8b308ba669b589d561f69aef4db09a6b)`(this T[] array, int startIndex, int length)` 

Retrieves a sub-array from the specified array. A sub-array starts at the specified index in the array.

#### Returns
An array of T that receives a sub-array. 

#### Parameters
* `array` An array of T from which to retrieve a sub-array. 

* `startIndex` An int that represents the zero-based index in the array at which retrieving starts. 

* `length` An int that represents the number of elements to retrieve. 

#### Parameters
* `T` The type of elements in the array. 

#### Exceptions
* `ArgumentNullException` *array*  is `null`. 

* `ArgumentOutOfRangeException` *startIndex*  is less than zero. 

-or- 

*startIndex*  is greater than the end of the array. 

-or- 

*length*  is less than zero. 

-or- 

*length*  is greater than the number of elements from *startIndex*  to the end of the array.

##### `public static T[] ` [`SubArray< T >`](#class_web_socket_sharp_1_1_ext_1a0a7ae84beda3d9638e6b96e12f47cdbd)`(this T[] array, long startIndex, long length)` 

Retrieves a sub-array from the specified array. A sub-array starts at the specified index in the array.

#### Returns
An array of T that receives a sub-array. 

#### Parameters
* `array` An array of T from which to retrieve a sub-array. 

* `startIndex` A long that represents the zero-based index in the array at which retrieving starts. 

* `length` A long that represents the number of elements to retrieve. 

#### Parameters
* `T` The type of elements in the array. 

#### Exceptions
* `ArgumentNullException` *array*  is `null`. 

* `ArgumentOutOfRangeException` *startIndex*  is less than zero. 

-or- 

*startIndex*  is greater than the end of the array. 

-or- 

*length*  is less than zero. 

-or- 

*length*  is greater than the number of elements from *startIndex*  to the end of the array.

##### `public static void ` [`Times`](#class_web_socket_sharp_1_1_ext_1ab170ebf318e09576d0a27af1523c66b7)`(this int n, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)` action)` 

Executes the specified delegate *n*  times.

#### Parameters
* `n` An int that specifies the number of times to execute. 

* `action` An Action delegate to execute.

##### `public static void ` [`Times`](#class_web_socket_sharp_1_1_ext_1a9c361b6e6120b605a0de1884da6c9451)`(this long n, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)` action)` 

Executes the specified delegate *n*  times.

#### Parameters
* `n` A long that specifies the number of times to execute. 

* `action` An Action delegate to execute.

##### `public static void ` [`Times`](#class_web_socket_sharp_1_1_ext_1a9d4e6f35b4fc06230beccd2b001b0f9d)`(this uint n, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)` action)` 

Executes the specified delegate *n*  times.

#### Parameters
* `n` A uint that specifies the number of times to execute. 

* `action` An Action delegate to execute.

##### `public static void ` [`Times`](#class_web_socket_sharp_1_1_ext_1a7ba8aaaf134a8e4b8d03a6de1d14b1a8)`(this ulong n, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)` action)` 

Executes the specified delegate *n*  times.

#### Parameters
* `n` A ulong that specifies the number of times to execute. 

* `action` An Action delegate to execute.

##### `public static void ` [`Times`](#class_web_socket_sharp_1_1_ext_1a42fc1ec523a57117ac064639c8613a6f)`(this int n, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)`< int > action)` 

Executes the specified delegate *n*  times.

#### Parameters
* `n` An int that specifies the number of times to execute. 

* `action` An `Action<int>` delegate to execute. 

The int parameter is the zero-based count of iteration.

##### `public static void ` [`Times`](#class_web_socket_sharp_1_1_ext_1ad52dd34421d625470edfff7df0440e99)`(this long n, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)`< long > action)` 

Executes the specified delegate *n*  times.

#### Parameters
* `n` A long that specifies the number of times to execute. 

* `action` An `Action<long>` delegate to execute. 

The long parameter is the zero-based count of iteration.

##### `public static void ` [`Times`](#class_web_socket_sharp_1_1_ext_1a06faac195b1ed2c3546aa19a80be2ea7)`(this uint n, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)`< uint > action)` 

Executes the specified delegate *n*  times.

#### Parameters
* `n` A uint that specifies the number of times to execute. 

* `action` An `Action<uint>` delegate to execute. 

The uint parameter is the zero-based count of iteration.

##### `public static void ` [`Times`](#class_web_socket_sharp_1_1_ext_1a989eb99783a2ab8e6f5c1d87ffcd76bd)`(this ulong n, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)`< ulong > action)` 

Executes the specified delegate *n*  times.

#### Parameters
* `n` A ulong that specifies the number of times to execute. 

* `action` An `Action<ulong>` delegate to execute. 

The ulong parameter is the zero-based count of iteration.

##### `public static T ` [`To< T >`](#class_web_socket_sharp_1_1_ext_1a678d3c2bd8ebf9fcdb71717b09f14625)`(this byte[] source, ` [`ByteOrder`](WebSocketSharp.md)` sourceOrder)` 

Converts the specified byte array to the specified type value.

#### Returns
A T converted from *source* . 

The default value of T if not converted. 

#### Parameters
* `source` An array of byte to convert. 

* `sourceOrder` One of the ByteOrder enum values. 

It specifies the byte order of *source* . 

#### Parameters
* `T` The type of the return. 

bool, char, double, float, int, long, short, uint, ulong, or ushort. 

#### Exceptions
* `ArgumentNullException` *source*  is `null`.

##### `public static byte[] ` [`ToByteArray< T >`](#class_web_socket_sharp_1_1_ext_1a8d8b2ceb186d1622fed7964fe9ebba3d)`(this T value, ` [`ByteOrder`](WebSocketSharp.md)` order)` 

Converts the specified value to a byte array.

#### Returns
An array of byte converted from *value* . 

#### Parameters
* `value` A T to convert. 

* `order` One of the ByteOrder enum values. 

It specifies the byte order of the return. 

#### Parameters
* `T` The type of *value* . 

bool, byte, char, double, float, int, long, short, uint, ulong, or ushort.

##### `public static byte[] ` [`ToHostOrder`](#class_web_socket_sharp_1_1_ext_1a6edf4e6e7e3eae9450243da28dd4ed96)`(this byte[] source, ` [`ByteOrder`](WebSocketSharp.md)` sourceOrder)` 

Converts the order of elements in the specified byte array to host (this computer architecture) byte order.

#### Returns
An array of byte converted from *source* . 

*source*  if the number of elements in it is less than 2 or *sourceOrder*  is same as host byte order. 

#### Parameters
* `source` An array of byte to convert. 

* `sourceOrder` One of the ByteOrder enum values. 

It specifies the order of elements in *source* . 

#### Exceptions
* `ArgumentNullException` *source*  is `null`.

##### `public static string ` [`ToString< T >`](#class_web_socket_sharp_1_1_ext_1ab1e5b8a65f818a514e22002469c9814a)`(this T[] array, string separator)` 

Converts the specified array to a string.

#### Returns
A string converted by concatenating each element of *array*  across *separator* . 

An empty string if *array*  is an empty array. 

#### Parameters
* `array` An array of T to convert. 

* `separator` A string used to separate each element of *array* . 

#### Parameters
* `T` The type of elements in *array* . 

#### Exceptions
* `ArgumentNullException` *array*  is `null`.

##### `public static Uri ` [`ToUri`](#class_web_socket_sharp_1_1_ext_1ab7f3424773f904db9b7e689ed65d8c27)`(this string value)` 

Converts the specified string to a Uri.

#### Returns
A Uri converted from *value* . 

`null` if the conversion has failed. 

#### Parameters
* `value` A string to convert.

##### `public static void ` [`WriteContent`](#class_web_socket_sharp_1_1_ext_1a227eb824fbbda50cb284447437364456)`(this ` [`HttpListenerResponse`](WebSocketSharp--Net--HttpListenerResponse.md)` response, byte[] content)` 

Sends the specified content data with the HTTP response.

#### Parameters
* `response` A HttpListenerResponse that represents the HTTP response used to send the content data. 

* `content` An array of byte that specifies the content data to send. 

#### Exceptions
* `ArgumentNullException` *response*  is `null`. 

-or- 

*content*  is `null`.

##### `private static byte[] ` [`compress`](#class_web_socket_sharp_1_1_ext_1a591323d2a514de7f129da9b0a8c41f2a)`(this byte[] data)` 

##### `private static MemoryStream ` [`compress`](#class_web_socket_sharp_1_1_ext_1ac35288dbed3a63ede58734526b50b2e4)`(this Stream stream)` 

##### `private static byte[] ` [`compressToArray`](#class_web_socket_sharp_1_1_ext_1ae63c6b2a3072b16ece41dfe2ed955e0c)`(this Stream stream)` 

##### `private static byte[] ` [`decompress`](#class_web_socket_sharp_1_1_ext_1a6781766bc699c503541d5e4e11dee3a5)`(this byte[] data)` 

##### `private static MemoryStream ` [`decompress`](#class_web_socket_sharp_1_1_ext_1ae60f9706084fc10b4b56a409613e01c3)`(this Stream stream)` 

##### `private static byte[] ` [`decompressToArray`](#class_web_socket_sharp_1_1_ext_1a41650c3d96ce109480809ff7115794f4)`(this Stream stream)` 

##### `private static bool ` [`isHttpMethod`](#class_web_socket_sharp_1_1_ext_1abf46bf391a69c904dc6de0eb067f5f9c)`(this string value)` 

##### `private static bool ` [`isHttpMethod10`](#class_web_socket_sharp_1_1_ext_1a80ecde5ced27fb7ad8f42cb22715111b)`(this string value)` 

