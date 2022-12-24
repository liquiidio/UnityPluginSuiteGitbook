# class `UniversalAuthenticatorLibrary::Src::Authenticators::WaxCloudWallet::WaxCloudWalletAuthenticator` 

```
class UniversalAuthenticatorLibrary::Src::Authenticators::WaxCloudWallet::WaxCloudWalletAuthenticator
  : public Authenticator
```

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public ` [`WaxCloudWalletConfig`](UniversalAuthenticatorLibrary--Src--Authenticators--WaxCloudWallet--WaxCloudWalletConfig.md)` ` [`WaxCloudWalletConfig`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_wax_cloud_wallet_1_1_wax_cloud_wallet_authenticator_1a562cd0d5cfc81e2ae7ae181b08849064) | 
`public ` [`WaxCloudWalletAuthenticator`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_wax_cloud_wallet_1_1_wax_cloud_wallet_authenticator_1a1fb40c21768f82d28de079b0b16d86e0)`(` [`Chain`](UniversalAuthenticatorLibrary--Chain.md)` chain, ` [`UALOptions`](UniversalAuthenticatorLibrary--UALOptions.md)` options)` | 
`public virtual sealed override void ` [`Init`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_wax_cloud_wallet_1_1_wax_cloud_wallet_authenticator_1a6da445904a152cf0e0b4b10e33fffee3)`(` [`Chain`](UniversalAuthenticatorLibrary--Chain.md)` chain, ` [`UALOptions`](UniversalAuthenticatorLibrary--UALOptions.md)` options)` | 
`public virtual override async Task< ` [`User`](UniversalAuthenticatorLibrary--User.md)` > ` [`Login`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_wax_cloud_wallet_1_1_wax_cloud_wallet_authenticator_1a41728b37bee8ca54619143d2ffdad921)`(string accountName)` | 
`public virtual override async Task ` [`Logout`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_wax_cloud_wallet_1_1_wax_cloud_wallet_authenticator_1a1aa385a368572a569fbf9b3cc07b470c)`()` | 
`public virtual override bool ` [`ShouldAutoLogin`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_wax_cloud_wallet_1_1_wax_cloud_wallet_authenticator_1ac81e2aeafb5a64f62f6c20ca5c0350e6)`()` | 
`public virtual override bool ` [`ShouldRender`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_wax_cloud_wallet_1_1_wax_cloud_wallet_authenticator_1a32fcfca57912afc9dedb12cba37fed7b)`()` | 
`private WaxCloudWalletPlugin ` [`_waxCloudWalletPlugin`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_wax_cloud_wallet_1_1_wax_cloud_wallet_authenticator_1a61000a73dfb6e41eb8485936be3e984e) | 
`private ` [`WaxCloudWalletUser`](UniversalAuthenticatorLibrary--Src--Authenticators--WaxCloudWallet--WaxCloudWalletUser.md)` ` [`_user`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_wax_cloud_wallet_1_1_wax_cloud_wallet_authenticator_1a1e8ff1af61b3a4ffeb3f9db1ddfc7d5e) | 

## Members

##### `public ` [`WaxCloudWalletConfig`](UniversalAuthenticatorLibrary--Src--Authenticators--WaxCloudWallet--WaxCloudWalletConfig.md)` ` [`WaxCloudWalletConfig`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_wax_cloud_wallet_1_1_wax_cloud_wallet_authenticator_1a562cd0d5cfc81e2ae7ae181b08849064) 

##### `public ` [`WaxCloudWalletAuthenticator`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_wax_cloud_wallet_1_1_wax_cloud_wallet_authenticator_1a1fb40c21768f82d28de079b0b16d86e0)`(` [`Chain`](UniversalAuthenticatorLibrary--Chain.md)` chain, ` [`UALOptions`](UniversalAuthenticatorLibrary--UALOptions.md)` options)` 

##### `public virtual sealed override void ` [`Init`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_wax_cloud_wallet_1_1_wax_cloud_wallet_authenticator_1a6da445904a152cf0e0b4b10e33fffee3)`(` [`Chain`](UniversalAuthenticatorLibrary--Chain.md)` chain, ` [`UALOptions`](UniversalAuthenticatorLibrary--UALOptions.md)` options)` 

##### `public virtual override async Task< ` [`User`](UniversalAuthenticatorLibrary--User.md)` > ` [`Login`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_wax_cloud_wallet_1_1_wax_cloud_wallet_authenticator_1a41728b37bee8ca54619143d2ffdad921)`(string accountName)` 

##### `public virtual override async Task ` [`Logout`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_wax_cloud_wallet_1_1_wax_cloud_wallet_authenticator_1a1aa385a368572a569fbf9b3cc07b470c)`()` 

##### `public virtual override bool ` [`ShouldAutoLogin`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_wax_cloud_wallet_1_1_wax_cloud_wallet_authenticator_1ac81e2aeafb5a64f62f6c20ca5c0350e6)`()` 

##### `public virtual override bool ` [`ShouldRender`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_wax_cloud_wallet_1_1_wax_cloud_wallet_authenticator_1a32fcfca57912afc9dedb12cba37fed7b)`()` 

##### `private WaxCloudWalletPlugin ` [`_waxCloudWalletPlugin`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_wax_cloud_wallet_1_1_wax_cloud_wallet_authenticator_1a61000a73dfb6e41eb8485936be3e984e) 

##### `private ` [`WaxCloudWalletUser`](UniversalAuthenticatorLibrary--Src--Authenticators--WaxCloudWallet--WaxCloudWalletUser.md)` ` [`_user`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_wax_cloud_wallet_1_1_wax_cloud_wallet_authenticator_1a1e8ff1af61b3a4ffeb3f9db1ddfc7d5e) 

