# class `WebSocketSharp::Net::HttpUtility` 

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public static string ` [`HtmlAttributeEncode`](#class_web_socket_sharp_1_1_net_1_1_http_utility_1a3728dede3cc64575852bac21ce9db896)`(string s)` | 
`public static void ` [`HtmlAttributeEncode`](#class_web_socket_sharp_1_1_net_1_1_http_utility_1a873eb85b3c4b0149777337023a42f85e)`(string s, TextWriter output)` | 
`public static string ` [`HtmlDecode`](#class_web_socket_sharp_1_1_net_1_1_http_utility_1aad7440f78ed2901fb53972bdff82ace1)`(string s)` | 
`public static void ` [`HtmlDecode`](#class_web_socket_sharp_1_1_net_1_1_http_utility_1a1aa5db543c6053c5330c4ee00d88fbc8)`(string s, TextWriter output)` | 
`public static string ` [`HtmlEncode`](#class_web_socket_sharp_1_1_net_1_1_http_utility_1a5e344be444526170180b838dd153a4de)`(string s)` | 
`public static void ` [`HtmlEncode`](#class_web_socket_sharp_1_1_net_1_1_http_utility_1af53e573676d616b40d8b7df9de50592a)`(string s, TextWriter output)` | 
`public static string ` [`UrlDecode`](#class_web_socket_sharp_1_1_net_1_1_http_utility_1a1b17656c8e6c08aceebf84b65bb1d17a)`(string s)` | 
`public static string ` [`UrlDecode`](#class_web_socket_sharp_1_1_net_1_1_http_utility_1a23b6d9b1efd8d21486ed413a36a185c7)`(byte[] bytes, Encoding encoding)` | 
`public static string ` [`UrlDecode`](#class_web_socket_sharp_1_1_net_1_1_http_utility_1a83bebf4cdc0b70ac10e5a4a91f7d8b5f)`(string s, Encoding encoding)` | 
`public static string ` [`UrlDecode`](#class_web_socket_sharp_1_1_net_1_1_http_utility_1a99542e536c64e9e9183dd17ff4a496b3)`(byte[] bytes, int offset, int count, Encoding encoding)` | 
`public static byte[] ` [`UrlDecodeToBytes`](#class_web_socket_sharp_1_1_net_1_1_http_utility_1ad9573c957f3d16d0f6b8c9749b17f34a)`(byte[] bytes)` | 
`public static byte[] ` [`UrlDecodeToBytes`](#class_web_socket_sharp_1_1_net_1_1_http_utility_1a7d46b159b55039ae0dcf0f23b93dff84)`(string s)` | 
`public static byte[] ` [`UrlDecodeToBytes`](#class_web_socket_sharp_1_1_net_1_1_http_utility_1a0df9395aab5bdadf6f8a7ff6214c75f0)`(byte[] bytes, int offset, int count)` | 
`public static string ` [`UrlEncode`](#class_web_socket_sharp_1_1_net_1_1_http_utility_1a412868f07c67ed0dd91f7283d3bf77b6)`(byte[] bytes)` | 
`public static string ` [`UrlEncode`](#class_web_socket_sharp_1_1_net_1_1_http_utility_1a89e690ee900451d052cb839af44e6995)`(string s)` | 
`public static string ` [`UrlEncode`](#class_web_socket_sharp_1_1_net_1_1_http_utility_1a3661850fd047751b48d4e69a315807ce)`(string s, Encoding encoding)` | 
`public static string ` [`UrlEncode`](#class_web_socket_sharp_1_1_net_1_1_http_utility_1a3e6d7721dd897cb8b549b107f9169e9f)`(byte[] bytes, int offset, int count)` | 
`public static byte[] ` [`UrlEncodeToBytes`](#class_web_socket_sharp_1_1_net_1_1_http_utility_1a72861694ecc07eb0d352ea2f69dc6fc2)`(byte[] bytes)` | 
`public static byte[] ` [`UrlEncodeToBytes`](#class_web_socket_sharp_1_1_net_1_1_http_utility_1a7b66810e9b246fed6fe0d5d218431bf0)`(string s)` | 
`public static byte[] ` [`UrlEncodeToBytes`](#class_web_socket_sharp_1_1_net_1_1_http_utility_1a83c4c208eb000df36bf7c488c1732b03)`(string s, Encoding encoding)` | 
`public static byte[] ` [`UrlEncodeToBytes`](#class_web_socket_sharp_1_1_net_1_1_http_utility_1ab3098862f6e53c823ee9132d22e7ad3b)`(byte[] bytes, int offset, int count)` | 
`private static static ` [`HttpUtility`](#class_web_socket_sharp_1_1_net_1_1_http_utility_1a29c07a6ff39c947c0dcdc5dc53708086)`()` | 
`private static Dictionary< string, char > ` [`getEntities`](#class_web_socket_sharp_1_1_net_1_1_http_utility_1a107ff2ff68dce5d5e83bdad2df32f18b)`()` | 
`private static int ` [`getNumber`](#class_web_socket_sharp_1_1_net_1_1_http_utility_1a0c6d5b49d95f8400f056a43ef29bcccc)`(char c)` | 
`private static int ` [`getNumber`](#class_web_socket_sharp_1_1_net_1_1_http_utility_1ae48b26d3b36f68da7c11b19452918a8e)`(byte[] bytes, int offset, int count)` | 
`private static int ` [`getNumber`](#class_web_socket_sharp_1_1_net_1_1_http_utility_1ab27cddcf17dfa1c075fd9268d4659102)`(string s, int offset, int count)` | 
`private static string ` [`htmlDecode`](#class_web_socket_sharp_1_1_net_1_1_http_utility_1a0de9f109fc824766b20bd583cb177df6)`(string s)` | 
`private static string ` [`htmlEncode`](#class_web_socket_sharp_1_1_net_1_1_http_utility_1a4959a8c2042382b1bb6994177481a914)`(string s, bool minimal)` | Converts the specified string to an HTML-encoded string.
`private static void ` [`initEntities`](#class_web_socket_sharp_1_1_net_1_1_http_utility_1acbe0f0fd38e0c8a91c7b03051de08c96)`()` | Initializes the _entities field.
`private static bool ` [`isAlphabet`](#class_web_socket_sharp_1_1_net_1_1_http_utility_1a1c401d56f2aa6283fc8b268e94e74b99)`(char c)` | 
`private static bool ` [`isNumeric`](#class_web_socket_sharp_1_1_net_1_1_http_utility_1a2d3b7a46d527687d292551ed9252602f)`(char c)` | 
`private static bool ` [`isUnreserved`](#class_web_socket_sharp_1_1_net_1_1_http_utility_1aa40eaecb681056dd81a865d82cb78108)`(char c)` | 
`private static bool ` [`isUnreservedInRfc2396`](#class_web_socket_sharp_1_1_net_1_1_http_utility_1ae94c8305d88dec43eb0fc1b2e9b05e5b)`(char c)` | 
`private static bool ` [`isUnreservedInRfc3986`](#class_web_socket_sharp_1_1_net_1_1_http_utility_1a8affd0a965f93ae922e90947f5fa9d97)`(char c)` | 
`private static byte[] ` [`urlDecodeToBytes`](#class_web_socket_sharp_1_1_net_1_1_http_utility_1a630e4ef2eb70ed546cd0d406a1d0af3a)`(byte[] bytes, int offset, int count)` | 
`private static void ` [`urlEncode`](#class_web_socket_sharp_1_1_net_1_1_http_utility_1afec046e8080786c3cc1ed54ff77697d9)`(byte b, Stream output)` | 
`private static byte[] ` [`urlEncodeToBytes`](#class_web_socket_sharp_1_1_net_1_1_http_utility_1ac0043ca6cc0fd5b2120d2063558a9ffe)`(byte[] bytes, int offset, int count)` | 

## Members

##### `public static string ` [`HtmlAttributeEncode`](#class_web_socket_sharp_1_1_net_1_1_http_utility_1a3728dede3cc64575852bac21ce9db896)`(string s)` 

##### `public static void ` [`HtmlAttributeEncode`](#class_web_socket_sharp_1_1_net_1_1_http_utility_1a873eb85b3c4b0149777337023a42f85e)`(string s, TextWriter output)` 

##### `public static string ` [`HtmlDecode`](#class_web_socket_sharp_1_1_net_1_1_http_utility_1aad7440f78ed2901fb53972bdff82ace1)`(string s)` 

##### `public static void ` [`HtmlDecode`](#class_web_socket_sharp_1_1_net_1_1_http_utility_1a1aa5db543c6053c5330c4ee00d88fbc8)`(string s, TextWriter output)` 

##### `public static string ` [`HtmlEncode`](#class_web_socket_sharp_1_1_net_1_1_http_utility_1a5e344be444526170180b838dd153a4de)`(string s)` 

##### `public static void ` [`HtmlEncode`](#class_web_socket_sharp_1_1_net_1_1_http_utility_1af53e573676d616b40d8b7df9de50592a)`(string s, TextWriter output)` 

##### `public static string ` [`UrlDecode`](#class_web_socket_sharp_1_1_net_1_1_http_utility_1a1b17656c8e6c08aceebf84b65bb1d17a)`(string s)` 

##### `public static string ` [`UrlDecode`](#class_web_socket_sharp_1_1_net_1_1_http_utility_1a23b6d9b1efd8d21486ed413a36a185c7)`(byte[] bytes, Encoding encoding)` 

##### `public static string ` [`UrlDecode`](#class_web_socket_sharp_1_1_net_1_1_http_utility_1a83bebf4cdc0b70ac10e5a4a91f7d8b5f)`(string s, Encoding encoding)` 

##### `public static string ` [`UrlDecode`](#class_web_socket_sharp_1_1_net_1_1_http_utility_1a99542e536c64e9e9183dd17ff4a496b3)`(byte[] bytes, int offset, int count, Encoding encoding)` 

##### `public static byte[] ` [`UrlDecodeToBytes`](#class_web_socket_sharp_1_1_net_1_1_http_utility_1ad9573c957f3d16d0f6b8c9749b17f34a)`(byte[] bytes)` 

##### `public static byte[] ` [`UrlDecodeToBytes`](#class_web_socket_sharp_1_1_net_1_1_http_utility_1a7d46b159b55039ae0dcf0f23b93dff84)`(string s)` 

##### `public static byte[] ` [`UrlDecodeToBytes`](#class_web_socket_sharp_1_1_net_1_1_http_utility_1a0df9395aab5bdadf6f8a7ff6214c75f0)`(byte[] bytes, int offset, int count)` 

##### `public static string ` [`UrlEncode`](#class_web_socket_sharp_1_1_net_1_1_http_utility_1a412868f07c67ed0dd91f7283d3bf77b6)`(byte[] bytes)` 

##### `public static string ` [`UrlEncode`](#class_web_socket_sharp_1_1_net_1_1_http_utility_1a89e690ee900451d052cb839af44e6995)`(string s)` 

##### `public static string ` [`UrlEncode`](#class_web_socket_sharp_1_1_net_1_1_http_utility_1a3661850fd047751b48d4e69a315807ce)`(string s, Encoding encoding)` 

##### `public static string ` [`UrlEncode`](#class_web_socket_sharp_1_1_net_1_1_http_utility_1a3e6d7721dd897cb8b549b107f9169e9f)`(byte[] bytes, int offset, int count)` 

##### `public static byte[] ` [`UrlEncodeToBytes`](#class_web_socket_sharp_1_1_net_1_1_http_utility_1a72861694ecc07eb0d352ea2f69dc6fc2)`(byte[] bytes)` 

##### `public static byte[] ` [`UrlEncodeToBytes`](#class_web_socket_sharp_1_1_net_1_1_http_utility_1a7b66810e9b246fed6fe0d5d218431bf0)`(string s)` 

##### `public static byte[] ` [`UrlEncodeToBytes`](#class_web_socket_sharp_1_1_net_1_1_http_utility_1a83c4c208eb000df36bf7c488c1732b03)`(string s, Encoding encoding)` 

##### `public static byte[] ` [`UrlEncodeToBytes`](#class_web_socket_sharp_1_1_net_1_1_http_utility_1ab3098862f6e53c823ee9132d22e7ad3b)`(byte[] bytes, int offset, int count)` 

##### `private static static ` [`HttpUtility`](#class_web_socket_sharp_1_1_net_1_1_http_utility_1a29c07a6ff39c947c0dcdc5dc53708086)`()` 

##### `private static Dictionary< string, char > ` [`getEntities`](#class_web_socket_sharp_1_1_net_1_1_http_utility_1a107ff2ff68dce5d5e83bdad2df32f18b)`()` 

##### `private static int ` [`getNumber`](#class_web_socket_sharp_1_1_net_1_1_http_utility_1a0c6d5b49d95f8400f056a43ef29bcccc)`(char c)` 

##### `private static int ` [`getNumber`](#class_web_socket_sharp_1_1_net_1_1_http_utility_1ae48b26d3b36f68da7c11b19452918a8e)`(byte[] bytes, int offset, int count)` 

##### `private static int ` [`getNumber`](#class_web_socket_sharp_1_1_net_1_1_http_utility_1ab27cddcf17dfa1c075fd9268d4659102)`(string s, int offset, int count)` 

##### `private static string ` [`htmlDecode`](#class_web_socket_sharp_1_1_net_1_1_http_utility_1a0de9f109fc824766b20bd583cb177df6)`(string s)` 

##### `private static string ` [`htmlEncode`](#class_web_socket_sharp_1_1_net_1_1_http_utility_1a4959a8c2042382b1bb6994177481a914)`(string s, bool minimal)` 

Converts the specified string to an HTML-encoded string.

This method starts encoding with a NCR from the character code 160 but does not stop at the character code 255. 

One reason is the unicode characters &#65308; and &#65310; that look like < and >. 

#### Returns
A string that represents an encoded string. 

#### Parameters
* `s` A string to encode. 

* `minimal` A bool: `true` if encodes without a NCR; otherwise, `false`.

##### `private static void ` [`initEntities`](#class_web_socket_sharp_1_1_net_1_1_http_utility_1acbe0f0fd38e0c8a91c7b03051de08c96)`()` 

Initializes the _entities field.

This method builds a dictionary of HTML character entity references. This dictionary comes from the HTML 4.01 W3C recommendation.

##### `private static bool ` [`isAlphabet`](#class_web_socket_sharp_1_1_net_1_1_http_utility_1a1c401d56f2aa6283fc8b268e94e74b99)`(char c)` 

##### `private static bool ` [`isNumeric`](#class_web_socket_sharp_1_1_net_1_1_http_utility_1a2d3b7a46d527687d292551ed9252602f)`(char c)` 

##### `private static bool ` [`isUnreserved`](#class_web_socket_sharp_1_1_net_1_1_http_utility_1aa40eaecb681056dd81a865d82cb78108)`(char c)` 

##### `private static bool ` [`isUnreservedInRfc2396`](#class_web_socket_sharp_1_1_net_1_1_http_utility_1ae94c8305d88dec43eb0fc1b2e9b05e5b)`(char c)` 

##### `private static bool ` [`isUnreservedInRfc3986`](#class_web_socket_sharp_1_1_net_1_1_http_utility_1a8affd0a965f93ae922e90947f5fa9d97)`(char c)` 

##### `private static byte[] ` [`urlDecodeToBytes`](#class_web_socket_sharp_1_1_net_1_1_http_utility_1a630e4ef2eb70ed546cd0d406a1d0af3a)`(byte[] bytes, int offset, int count)` 

##### `private static void ` [`urlEncode`](#class_web_socket_sharp_1_1_net_1_1_http_utility_1afec046e8080786c3cc1ed54ff77697d9)`(byte b, Stream output)` 

##### `private static byte[] ` [`urlEncodeToBytes`](#class_web_socket_sharp_1_1_net_1_1_http_utility_1ac0043ca6cc0fd5b2120d2063558a9ffe)`(byte[] bytes, int offset, int count)` 

