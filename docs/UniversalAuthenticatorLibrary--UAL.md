# class `UniversalAuthenticatorLibrary::UAL` 

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public ` [`Chain`](UniversalAuthenticatorLibrary--Chain.md)` ` [`Chains`](#class_universal_authenticator_library_1_1_u_a_l_1a45650146a22f4396f56ca700b1112fc4) | 
`public string ` [`AppName`](#class_universal_authenticator_library_1_1_u_a_l_1aedf62881f9930f223db4378cc841fb9e) | 
`public ` [`Authenticator`](UniversalAuthenticatorLibrary--Authenticator.md)` ` [`Authenticators`](#class_universal_authenticator_library_1_1_u_a_l_1a0489bf70b67398b6781bdc3640e253c8) | 
`public ` [`UAL`](#class_universal_authenticator_library_1_1_u_a_l_1aad8f03cb9f9c47d5e46a272a8bd28d5c)`(` [`Chain`](UniversalAuthenticatorLibrary--Chain.md)` chains, string appName, ` [`Authenticator`](UniversalAuthenticatorLibrary--Authenticator.md)` authenticators)` | #### Parameters
`public ` [`AuthenticatorResponse`](UniversalAuthenticatorLibrary--AuthenticatorResponse.md)` ` [`GetAuthenticators`](#class_universal_authenticator_library_1_1_u_a_l_1a32805bd7ec1f6b56890af4fd5a36f16d)`()` | Returns an object with a list of initialized Authenticators that returned true for shouldRender() as well as an authenticator that supports autoLogin

## Members

##### `public ` [`Chain`](UniversalAuthenticatorLibrary--Chain.md)` ` [`Chains`](#class_universal_authenticator_library_1_1_u_a_l_1a45650146a22f4396f56ca700b1112fc4) 

##### `public string ` [`AppName`](#class_universal_authenticator_library_1_1_u_a_l_1aedf62881f9930f223db4378cc841fb9e) 

##### `public ` [`Authenticator`](UniversalAuthenticatorLibrary--Authenticator.md)` ` [`Authenticators`](#class_universal_authenticator_library_1_1_u_a_l_1a0489bf70b67398b6781bdc3640e253c8) 

##### `public ` [`UAL`](#class_universal_authenticator_library_1_1_u_a_l_1aad8f03cb9f9c47d5e46a272a8bd28d5c)`(` [`Chain`](UniversalAuthenticatorLibrary--Chain.md)` chains, string appName, ` [`Authenticator`](UniversalAuthenticatorLibrary--Authenticator.md)` authenticators)` 

#### Parameters
* `chains` A list of chains the dapp supports.

* `appName` The name of the app using the authenticators

* `authenticators` A list of authenticator apps that the dapp supports.

##### `public ` [`AuthenticatorResponse`](UniversalAuthenticatorLibrary--AuthenticatorResponse.md)` ` [`GetAuthenticators`](#class_universal_authenticator_library_1_1_u_a_l_1a32805bd7ec1f6b56890af4fd5a36f16d)`()` 

Returns an object with a list of initialized Authenticators that returned true for shouldRender() as well as an authenticator that supports autoLogin

