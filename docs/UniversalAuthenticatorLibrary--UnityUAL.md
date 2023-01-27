# class `UniversalAuthenticatorLibrary::UnityUAL` 

```
class UniversalAuthenticatorLibrary::UnityUAL
  : public MonoBehaviour
```

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public bool ` [`IsAutologin`](#class_universal_authenticator_library_1_1_unity_u_a_l_1abd51b3c200ab5b64815eba7203156f30) | 
`public ` [`Authenticator`](UniversalAuthenticatorLibrary--Authenticator.md)` ` [`ActiveAuthenticator`](#class_universal_authenticator_library_1_1_unity_u_a_l_1ac1bcd85c15c9365f17835e7222ff1502) | 
`public ` [`Chain`](UniversalAuthenticatorLibrary--Chain.md)` ` [`Chain`](#class_universal_authenticator_library_1_1_unity_u_a_l_1ac5ae30619ab2ecd485d62c4a67082190) | 
`public ` [`UALOptions`](UniversalAuthenticatorLibrary--UALOptions.md)` ` [`UalOptions`](#class_universal_authenticator_library_1_1_unity_u_a_l_1a4f4de2df5d9187ce1613ac8072ca0306) | 
`public List< ` [`Authenticator`](UniversalAuthenticatorLibrary--Authenticator.md)` > ` [`Authenticators`](#class_universal_authenticator_library_1_1_unity_u_a_l_1ae557c481fa8c3e51dde178910f0a96cf) | 
`public ` [`Action](#_u_a_l_example_panel_8cs_1a24e91c56095a0673d92c6eac6e069a3c)< [User`](UniversalAuthenticatorLibrary--User.md)` > ` [`OnUserLogin`](#class_universal_authenticator_library_1_1_unity_u_a_l_1a300ad3fd0063bb50f08edc2efe28f920) | 
`public ` [`UnityUAL`](#class_universal_authenticator_library_1_1_unity_u_a_l_1ae8aa6187c4f35b82bea55b52df9dcef9)`(` [`Chain`](UniversalAuthenticatorLibrary--Chain.md)` chain, ` [`UALOptions`](UniversalAuthenticatorLibrary--UALOptions.md)` ualOptions, List< ` [`Authenticator`](UniversalAuthenticatorLibrary--Authenticator.md)` > authenticators)` | #### Parameters
`public ` [`AuthenticatorResponse`](UniversalAuthenticatorLibrary--AuthenticatorResponse.md)` ` [`GetAuthenticators`](#class_universal_authenticator_library_1_1_unity_u_a_l_1a32805bd7ec1f6b56890af4fd5a36f16d)`()` | Returns an object with a list of initialized Authenticators that returned true for shouldRender() as well as an authenticator that supports autoLogin
`public async Task ` [`Init`](#class_universal_authenticator_library_1_1_unity_u_a_l_1ad2211bc8cfc2d8c4fe5784b6917e6520)`()` | Initializes UAL: If a renderConfig was provided and no autologin authenticator is returned it will render the Auth Button and relevant DOM elements.
`protected abstract void ` [`CreateUalPanel`](#class_universal_authenticator_library_1_1_unity_u_a_l_1a177c1252275603108b9be9c60dee2a91)`(` [`Authenticator`](UniversalAuthenticatorLibrary--Authenticator.md)` authenticators)` | 
`private async Task ` [`AttemptSessionLogin`](#class_universal_authenticator_library_1_1_unity_u_a_l_1afb8edc1e3cd649805dfbe54e6fd79688)`(` [`Authenticator`](UniversalAuthenticatorLibrary--Authenticator.md)` availableAuthenticators)` | 
`private void ` [`ClearStorageKeys`](#class_universal_authenticator_library_1_1_unity_u_a_l_1a74bf10f219ebfa5a39edf8809bf774d2)`()` | 

## Members

##### `public bool ` [`IsAutologin`](#class_universal_authenticator_library_1_1_unity_u_a_l_1abd51b3c200ab5b64815eba7203156f30) 

##### `public ` [`Authenticator`](UniversalAuthenticatorLibrary--Authenticator.md)` ` [`ActiveAuthenticator`](#class_universal_authenticator_library_1_1_unity_u_a_l_1ac1bcd85c15c9365f17835e7222ff1502) 

##### `public ` [`Chain`](UniversalAuthenticatorLibrary--Chain.md)` ` [`Chain`](#class_universal_authenticator_library_1_1_unity_u_a_l_1ac5ae30619ab2ecd485d62c4a67082190) 

##### `public ` [`UALOptions`](UniversalAuthenticatorLibrary--UALOptions.md)` ` [`UalOptions`](#class_universal_authenticator_library_1_1_unity_u_a_l_1a4f4de2df5d9187ce1613ac8072ca0306) 

##### `public List< ` [`Authenticator`](UniversalAuthenticatorLibrary--Authenticator.md)` > ` [`Authenticators`](#class_universal_authenticator_library_1_1_unity_u_a_l_1ae557c481fa8c3e51dde178910f0a96cf) 

##### `public ` [`Action](#_u_a_l_example_panel_8cs_1a24e91c56095a0673d92c6eac6e069a3c)< [User`](UniversalAuthenticatorLibrary--User.md)` > ` [`OnUserLogin`](#class_universal_authenticator_library_1_1_unity_u_a_l_1a300ad3fd0063bb50f08edc2efe28f920) 

##### `public ` [`UnityUAL`](#class_universal_authenticator_library_1_1_unity_u_a_l_1ae8aa6187c4f35b82bea55b52df9dcef9)`(` [`Chain`](UniversalAuthenticatorLibrary--Chain.md)` chain, ` [`UALOptions`](UniversalAuthenticatorLibrary--UALOptions.md)` ualOptions, List< ` [`Authenticator`](UniversalAuthenticatorLibrary--Authenticator.md)` > authenticators)` 

#### Parameters
* `chains` A list of chains the dapp supports.

* `appName` The name of the app using the authenticators

* `authenticators` A list of authenticator apps that the dapp supports.

##### `public ` [`AuthenticatorResponse`](UniversalAuthenticatorLibrary--AuthenticatorResponse.md)` ` [`GetAuthenticators`](#class_universal_authenticator_library_1_1_unity_u_a_l_1a32805bd7ec1f6b56890af4fd5a36f16d)`()` 

Returns an object with a list of initialized Authenticators that returned true for shouldRender() as well as an authenticator that supports autoLogin

##### `public async Task ` [`Init`](#class_universal_authenticator_library_1_1_unity_u_a_l_1ad2211bc8cfc2d8c4fe5784b6917e6520)`()` 

Initializes UAL: If a renderConfig was provided and no autologin authenticator is returned it will render the Auth Button and relevant DOM elements.

##### `protected abstract void ` [`CreateUalPanel`](#class_universal_authenticator_library_1_1_unity_u_a_l_1a177c1252275603108b9be9c60dee2a91)`(` [`Authenticator`](UniversalAuthenticatorLibrary--Authenticator.md)` authenticators)` 

##### `private async Task ` [`AttemptSessionLogin`](#class_universal_authenticator_library_1_1_unity_u_a_l_1afb8edc1e3cd649805dfbe54e6fd79688)`(` [`Authenticator`](UniversalAuthenticatorLibrary--Authenticator.md)` availableAuthenticators)` 

##### `private void ` [`ClearStorageKeys`](#class_universal_authenticator_library_1_1_unity_u_a_l_1a74bf10f219ebfa5a39edf8809bf774d2)`()` 

