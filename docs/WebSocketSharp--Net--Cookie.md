# class `WebSocketSharp::Net::Cookie` 

Provides a set of methods and properties used to manage an HTTP cookie.

This class refers to the following specifications: 

* Netscape specification

RFC 2109

RFC 2965

RFC 6265

This class cannot be inherited.

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`package bool ` [`ExactDomain`](#class_web_socket_sharp_1_1_net_1_1_cookie_1a37255f0ce87f696aa29ff6c0d057caf3) | 
`package int ` [`MaxAge`](#class_web_socket_sharp_1_1_net_1_1_cookie_1a13a3fe7c291fcb686fa0c1fd01230b8a) | 
`package int[] ` [`Ports`](#class_web_socket_sharp_1_1_net_1_1_cookie_1a066c5958f660936b80708d4454353bd7) | 
`package string ` [`SameSite`](#class_web_socket_sharp_1_1_net_1_1_cookie_1a5d2654fd103d15fa164b007b24cf041c) | 
`public string ` [`Comment`](#class_web_socket_sharp_1_1_net_1_1_cookie_1a71e9ec58ca153994beec51fb8a659dd7) | Gets the value of the Comment attribute of the cookie.
`public Uri ` [`CommentUri`](#class_web_socket_sharp_1_1_net_1_1_cookie_1a0f7e0293c2cb4b9b61e76a23b4a2ae88) | Gets the value of the CommentURL attribute of the cookie.
`public bool ` [`Discard`](#class_web_socket_sharp_1_1_net_1_1_cookie_1a5d3cab9edf8b7c2b19bd37301f5cf88c) | Gets a value indicating whether the client discards the cookie unconditionally when the client terminates.
`public string ` [`Domain`](#class_web_socket_sharp_1_1_net_1_1_cookie_1a72df16e5c55f3f510dbfdcba2d076baa) | Gets or sets the value of the Domain attribute of the cookie.
`public bool ` [`Expired`](#class_web_socket_sharp_1_1_net_1_1_cookie_1aba5dd9e8c9ac79260451b6a632afa8e7) | Gets or sets a value indicating whether the cookie has expired.
`public DateTime ` [`Expires`](#class_web_socket_sharp_1_1_net_1_1_cookie_1aa2691416481e7aa0eef54a1563b73912) | Gets or sets the value of the Expires attribute of the cookie.
`public bool ` [`HttpOnly`](#class_web_socket_sharp_1_1_net_1_1_cookie_1a660bff043d46641f3c60a81474e233fc) | Gets or sets a value indicating whether non-HTTP APIs can access the cookie.
`public string ` [`Name`](#class_web_socket_sharp_1_1_net_1_1_cookie_1a7ee9065718e6628dc7791b756fa6c0f9) | Gets or sets the name of the cookie.
`public string ` [`Path`](#class_web_socket_sharp_1_1_net_1_1_cookie_1af331ba015acf9191899985a835008b9d) | Gets or sets the value of the Path attribute of the cookie.
`public string ` [`Port`](#class_web_socket_sharp_1_1_net_1_1_cookie_1a368389b3458f93beae404944c3bef5e2) | Gets the value of the Port attribute of the cookie.
`public bool ` [`Secure`](#class_web_socket_sharp_1_1_net_1_1_cookie_1a5d366d19ccfb378d5de6635b6e14cbf5) | Gets or sets a value indicating whether the security level of the cookie is secure.
`public DateTime ` [`TimeStamp`](#class_web_socket_sharp_1_1_net_1_1_cookie_1a931e980ba3ac85bd305e2842d6425ceb) | Gets the time when the cookie was issued.
`public ` [`Cookie`](#class_web_socket_sharp_1_1_net_1_1_cookie_1a461d09aff0a65512c8b4597ddea2700a)`(string name, string value)` | Initializes a new instance of the Cookie class with the specified name and value.
`public ` [`Cookie`](#class_web_socket_sharp_1_1_net_1_1_cookie_1ad1f3232b7edd3c26d01e155da5e8de07)`(string name, string value, string path)` | Initializes a new instance of the Cookie class with the specified name, value, and path.
`public ` [`Cookie`](#class_web_socket_sharp_1_1_net_1_1_cookie_1ab76247ac0efaf33ee0f43ac35fa8c9a6)`(string name, string value, string path, string domain)` | Initializes a new instance of the Cookie class with the specified name, value, path, and domain.
`private string ` [`_comment`](#class_web_socket_sharp_1_1_net_1_1_cookie_1aceb0ed3ebbc5d83b29e48579103d6295) | 
`private Uri ` [`_commentUri`](#class_web_socket_sharp_1_1_net_1_1_cookie_1a840072fef8a4d22b86e216a7f20d08fe) | 
`private bool ` [`_discard`](#class_web_socket_sharp_1_1_net_1_1_cookie_1aa0c19f6621bd03a1f25bdd1738ed347d) | 
`private string ` [`_domain`](#class_web_socket_sharp_1_1_net_1_1_cookie_1a96681c0a2d3f9328e47233dac1d7d39e) | 
`private DateTime ` [`_expires`](#class_web_socket_sharp_1_1_net_1_1_cookie_1aa4086bbd26ac7e1cf5ff77bd3fbc6782) | 
`private bool ` [`_httpOnly`](#class_web_socket_sharp_1_1_net_1_1_cookie_1aa3c12792a92b01e83c817f5f0e6a60a2) | 
`private string ` [`_name`](#class_web_socket_sharp_1_1_net_1_1_cookie_1a92749b8d4b3ef0c4b1d2a4532db9032e) | 
`private string ` [`_path`](#class_web_socket_sharp_1_1_net_1_1_cookie_1a301dbb9913055444022b6d007e61871d) | 
`private string ` [`_port`](#class_web_socket_sharp_1_1_net_1_1_cookie_1a10678d523a188cddac879e8ed9f74230) | 
`private int[] ` [`_ports`](#class_web_socket_sharp_1_1_net_1_1_cookie_1aa8d296508ed642dc0c13be83c984f724) | 
`private string ` [`_sameSite`](#class_web_socket_sharp_1_1_net_1_1_cookie_1a5869cb0c3c1e80dbcf80858f21abec77) | 
`private bool ` [`_secure`](#class_web_socket_sharp_1_1_net_1_1_cookie_1a2f7b5b309c5830b8532939ca02946b44) | 
`private DateTime ` [`_timeStamp`](#class_web_socket_sharp_1_1_net_1_1_cookie_1ac7cbca9e371780eb91926dd6ec21b861) | 
`private string ` [`_value`](#class_web_socket_sharp_1_1_net_1_1_cookie_1a8bfdd9c00dcc86e43bc32af27290effd) | 
`private int ` [`_version`](#class_web_socket_sharp_1_1_net_1_1_cookie_1a5d970fae54e7cfeb30029c66caf3a351) | 
`private static static ` [`Cookie`](#class_web_socket_sharp_1_1_net_1_1_cookie_1a63d33bf5737762a6a4eb50151466a11d)`()` | 

## Members

##### `package bool ` [`ExactDomain`](#class_web_socket_sharp_1_1_net_1_1_cookie_1a37255f0ce87f696aa29ff6c0d057caf3) 

##### `package int ` [`MaxAge`](#class_web_socket_sharp_1_1_net_1_1_cookie_1a13a3fe7c291fcb686fa0c1fd01230b8a) 

##### `package int[] ` [`Ports`](#class_web_socket_sharp_1_1_net_1_1_cookie_1a066c5958f660936b80708d4454353bd7) 

##### `package string ` [`SameSite`](#class_web_socket_sharp_1_1_net_1_1_cookie_1a5d2654fd103d15fa164b007b24cf041c) 

##### `public string ` [`Comment`](#class_web_socket_sharp_1_1_net_1_1_cookie_1a71e9ec58ca153994beec51fb8a659dd7) 

Gets the value of the Comment attribute of the cookie.

A string that represents the comment to document intended use of the cookie. 

`null` if not present. 

The default value is `null`.

##### `public Uri ` [`CommentUri`](#class_web_socket_sharp_1_1_net_1_1_cookie_1a0f7e0293c2cb4b9b61e76a23b4a2ae88) 

Gets the value of the CommentURL attribute of the cookie.

A Uri that represents the URI that provides the comment to document intended use of the cookie. 

`null` if not present. 

The default value is `null`.

##### `public bool ` [`Discard`](#class_web_socket_sharp_1_1_net_1_1_cookie_1a5d3cab9edf8b7c2b19bd37301f5cf88c) 

Gets a value indicating whether the client discards the cookie unconditionally when the client terminates.

`true` if the client discards the cookie unconditionally when the client terminates; otherwise, `false`. 

The default value is `false`.

##### `public string ` [`Domain`](#class_web_socket_sharp_1_1_net_1_1_cookie_1a72df16e5c55f3f510dbfdcba2d076baa) 

Gets or sets the value of the Domain attribute of the cookie.

A string that represents the domain name that the cookie is valid for. 

An empty string if this attribute is not needed.

##### `public bool ` [`Expired`](#class_web_socket_sharp_1_1_net_1_1_cookie_1aba5dd9e8c9ac79260451b6a632afa8e7) 

Gets or sets a value indicating whether the cookie has expired.

`true` if the cookie has expired; otherwise, `false`. 

The default value is `false`.

##### `public DateTime ` [`Expires`](#class_web_socket_sharp_1_1_net_1_1_cookie_1aa2691416481e7aa0eef54a1563b73912) 

Gets or sets the value of the Expires attribute of the cookie.

A DateTime that represents the date and time that the cookie expires on. 

DateTime.MinValue if this attribute is not needed. 

The default value is DateTime.MinValue.

##### `public bool ` [`HttpOnly`](#class_web_socket_sharp_1_1_net_1_1_cookie_1a660bff043d46641f3c60a81474e233fc) 

Gets or sets a value indicating whether non-HTTP APIs can access the cookie.

`true` if non-HTTP APIs cannot access the cookie; otherwise, `false`. 

The default value is `false`.

##### `public string ` [`Name`](#class_web_socket_sharp_1_1_net_1_1_cookie_1a7ee9065718e6628dc7791b756fa6c0f9) 

Gets or sets the name of the cookie.

A string that represents the name of the cookie. 

The name must be a token defined in  RFC 2616

. 

#### Exceptions
* `ArgumentNullException` The value specified for a set operation is `null`. 

* `ArgumentException` The value specified for a set operation is an empty string. 

* or - 

The value specified for a set operation starts with a dollar sign. 

* or - 

The value specified for a set operation contains an invalid character.

##### `public string ` [`Path`](#class_web_socket_sharp_1_1_net_1_1_cookie_1af331ba015acf9191899985a835008b9d) 

Gets or sets the value of the Path attribute of the cookie.

A string that represents the subset of URI on the origin server that the cookie applies to.

##### `public string ` [`Port`](#class_web_socket_sharp_1_1_net_1_1_cookie_1a368389b3458f93beae404944c3bef5e2) 

Gets the value of the Port attribute of the cookie.

A string that represents the list of TCP ports that the cookie applies to. 

`null` if not present. 

The default value is `null`.

##### `public bool ` [`Secure`](#class_web_socket_sharp_1_1_net_1_1_cookie_1a5d366d19ccfb378d5de6635b6e14cbf5) 

Gets or sets a value indicating whether the security level of the cookie is secure.

When this property is `true`, the cookie may be included in the request only if the request is transmitted over HTTPS. 

`true` if the security level of the cookie is secure; otherwise, `false`. 

The default value is `false`.

##### `public DateTime ` [`TimeStamp`](#class_web_socket_sharp_1_1_net_1_1_cookie_1a931e980ba3ac85bd305e2842d6425ceb) 

Gets the time when the cookie was issued.

A DateTime that represents the time when the cookie was issued.

##### `public ` [`Cookie`](#class_web_socket_sharp_1_1_net_1_1_cookie_1a461d09aff0a65512c8b4597ddea2700a)`(string name, string value)` 

Initializes a new instance of the Cookie class with the specified name and value.

#### Parameters
* `name` A string that specifies the name of the cookie. 

The name must be a token defined in  RFC 2616

. 

* `value` A string that specifies the value of the cookie. 

#### Exceptions
* `ArgumentNullException` *name*  is `null`. 

* `ArgumentException` *name*  is an empty string. 

* or - 

*name*  starts with a dollar sign. 

* or - 

*name*  contains an invalid character. 

* or - 

*value*  is a string not enclosed in double quotes that contains an invalid character.

##### `public ` [`Cookie`](#class_web_socket_sharp_1_1_net_1_1_cookie_1ad1f3232b7edd3c26d01e155da5e8de07)`(string name, string value, string path)` 

Initializes a new instance of the Cookie class with the specified name, value, and path.

#### Parameters
* `name` A string that specifies the name of the cookie. 

The name must be a token defined in  RFC 2616

. 

* `value` A string that specifies the value of the cookie. 

* `path` A string that specifies the value of the Path attribute of the cookie. 

#### Exceptions
* `ArgumentNullException` *name*  is `null`. 

* `ArgumentException` *name*  is an empty string. 

* or - 

*name*  starts with a dollar sign. 

* or - 

*name*  contains an invalid character. 

* or - 

*value*  is a string not enclosed in double quotes that contains an invalid character.

##### `public ` [`Cookie`](#class_web_socket_sharp_1_1_net_1_1_cookie_1ab76247ac0efaf33ee0f43ac35fa8c9a6)`(string name, string value, string path, string domain)` 

Initializes a new instance of the Cookie class with the specified name, value, path, and domain.

#### Parameters
* `name` A string that specifies the name of the cookie. 

The name must be a token defined in  RFC 2616

. 

* `value` A string that specifies the value of the cookie. 

* `path` A string that specifies the value of the Path attribute of the cookie. 

* `domain` A string that specifies the value of the Domain attribute of the cookie. 

#### Exceptions
* `ArgumentNullException` *name*  is `null`. 

* `ArgumentException` *name*  is an empty string. 

* or - 

*name*  starts with a dollar sign. 

* or - 

*name*  contains an invalid character. 

* or - 

*value*  is a string not enclosed in double quotes that contains an invalid character.

##### `private string ` [`_comment`](#class_web_socket_sharp_1_1_net_1_1_cookie_1aceb0ed3ebbc5d83b29e48579103d6295) 

##### `private Uri ` [`_commentUri`](#class_web_socket_sharp_1_1_net_1_1_cookie_1a840072fef8a4d22b86e216a7f20d08fe) 

##### `private bool ` [`_discard`](#class_web_socket_sharp_1_1_net_1_1_cookie_1aa0c19f6621bd03a1f25bdd1738ed347d) 

##### `private string ` [`_domain`](#class_web_socket_sharp_1_1_net_1_1_cookie_1a96681c0a2d3f9328e47233dac1d7d39e) 

##### `private DateTime ` [`_expires`](#class_web_socket_sharp_1_1_net_1_1_cookie_1aa4086bbd26ac7e1cf5ff77bd3fbc6782) 

##### `private bool ` [`_httpOnly`](#class_web_socket_sharp_1_1_net_1_1_cookie_1aa3c12792a92b01e83c817f5f0e6a60a2) 

##### `private string ` [`_name`](#class_web_socket_sharp_1_1_net_1_1_cookie_1a92749b8d4b3ef0c4b1d2a4532db9032e) 

##### `private string ` [`_path`](#class_web_socket_sharp_1_1_net_1_1_cookie_1a301dbb9913055444022b6d007e61871d) 

##### `private string ` [`_port`](#class_web_socket_sharp_1_1_net_1_1_cookie_1a10678d523a188cddac879e8ed9f74230) 

##### `private int[] ` [`_ports`](#class_web_socket_sharp_1_1_net_1_1_cookie_1aa8d296508ed642dc0c13be83c984f724) 

##### `private string ` [`_sameSite`](#class_web_socket_sharp_1_1_net_1_1_cookie_1a5869cb0c3c1e80dbcf80858f21abec77) 

##### `private bool ` [`_secure`](#class_web_socket_sharp_1_1_net_1_1_cookie_1a2f7b5b309c5830b8532939ca02946b44) 

##### `private DateTime ` [`_timeStamp`](#class_web_socket_sharp_1_1_net_1_1_cookie_1ac7cbca9e371780eb91926dd6ec21b861) 

##### `private string ` [`_value`](#class_web_socket_sharp_1_1_net_1_1_cookie_1a8bfdd9c00dcc86e43bc32af27290effd) 

##### `private int ` [`_version`](#class_web_socket_sharp_1_1_net_1_1_cookie_1a5d970fae54e7cfeb30029c66caf3a351) 

##### `private static static ` [`Cookie`](#class_web_socket_sharp_1_1_net_1_1_cookie_1a63d33bf5737762a6a4eb50151466a11d)`()` 

