# class `UniversalAuthenticatorLibrary::Src::Authenticators::Anchor::AnchorAuthenticator` 

```
class UniversalAuthenticatorLibrary::Src::Authenticators::Anchor::AnchorAuthenticator
  : public Authenticator
```

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public UnityTransport ` [`Transport`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_anchor_1_1_anchor_authenticator_1a2cd2c7f38ebbbee4328a6ba1ccb9d01d) | 
`public ` [`AnchorAuthenticator`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_anchor_1_1_anchor_authenticator_1a1e84acd6ed8a8d2da17659c82e65eb43)`(` [`Chain`](UniversalAuthenticatorLibrary--Chain.md)` chain, ` [`UALOptions`](UniversalAuthenticatorLibrary--UALOptions.md)` options)` | 
`public virtual sealed override void ` [`Init`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_anchor_1_1_anchor_authenticator_1a6da445904a152cf0e0b4b10e33fffee3)`(` [`Chain`](UniversalAuthenticatorLibrary--Chain.md)` chain, ` [`UALOptions`](UniversalAuthenticatorLibrary--UALOptions.md)` options)` | 
`public virtual override async Task< ` [`User`](UniversalAuthenticatorLibrary--User.md)` > ` [`Login`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_anchor_1_1_anchor_authenticator_1a41728b37bee8ca54619143d2ffdad921)`(string accountName)` | 
`public virtual override async Task ` [`Logout`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_anchor_1_1_anchor_authenticator_1a1aa385a368572a569fbf9b3cc07b470c)`()` | 
`public virtual override bool ` [`ShouldAutoLogin`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_anchor_1_1_anchor_authenticator_1ac81e2aeafb5a64f62f6c20ca5c0350e6)`()` | 
`public virtual override bool ` [`ShouldRender`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_anchor_1_1_anchor_authenticator_1a32fcfca57912afc9dedb12cba37fed7b)`()` | 
`private AnchorLink ` [`_link`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_anchor_1_1_anchor_authenticator_1ab83a853dc8e03635061e08d6e0330778) | 
`private string ` [`_identifier`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_anchor_1_1_anchor_authenticator_1a1282b3920fb916d4229ac1ca0d9905fb) | 
`private ` [`AnchorUser`](UniversalAuthenticatorLibrary--Src--Authenticators--Anchor--AnchorUser.md)` ` [`_user`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_anchor_1_1_anchor_authenticator_1a5fd5ab910e503a6ac7c70a764a66ec49) | 

## Members

##### `public UnityTransport ` [`Transport`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_anchor_1_1_anchor_authenticator_1a2cd2c7f38ebbbee4328a6ba1ccb9d01d) 

##### `public ` [`AnchorAuthenticator`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_anchor_1_1_anchor_authenticator_1a1e84acd6ed8a8d2da17659c82e65eb43)`(` [`Chain`](UniversalAuthenticatorLibrary--Chain.md)` chain, ` [`UALOptions`](UniversalAuthenticatorLibrary--UALOptions.md)` options)` 

##### `public virtual sealed override void ` [`Init`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_anchor_1_1_anchor_authenticator_1a6da445904a152cf0e0b4b10e33fffee3)`(` [`Chain`](UniversalAuthenticatorLibrary--Chain.md)` chain, ` [`UALOptions`](UniversalAuthenticatorLibrary--UALOptions.md)` options)` 

##### `public virtual override async Task< ` [`User`](UniversalAuthenticatorLibrary--User.md)` > ` [`Login`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_anchor_1_1_anchor_authenticator_1a41728b37bee8ca54619143d2ffdad921)`(string accountName)` 

##### `public virtual override async Task ` [`Logout`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_anchor_1_1_anchor_authenticator_1a1aa385a368572a569fbf9b3cc07b470c)`()` 

##### `public virtual override bool ` [`ShouldAutoLogin`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_anchor_1_1_anchor_authenticator_1ac81e2aeafb5a64f62f6c20ca5c0350e6)`()` 

##### `public virtual override bool ` [`ShouldRender`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_anchor_1_1_anchor_authenticator_1a32fcfca57912afc9dedb12cba37fed7b)`()` 

##### `private AnchorLink ` [`_link`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_anchor_1_1_anchor_authenticator_1ab83a853dc8e03635061e08d6e0330778) 

##### `private string ` [`_identifier`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_anchor_1_1_anchor_authenticator_1a1282b3920fb916d4229ac1ca0d9905fb) 

##### `private ` [`AnchorUser`](UniversalAuthenticatorLibrary--Src--Authenticators--Anchor--AnchorUser.md)` ` [`_user`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_anchor_1_1_anchor_authenticator_1a5fd5ab910e503a6ac7c70a764a66ec49) 

