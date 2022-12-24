# class `UniversalAuthenticatorLibrary::Src::Authenticators::WaxCloudWallet::WaxCloudWalletUser` 

```
class UniversalAuthenticatorLibrary::Src::Authenticators::WaxCloudWallet::WaxCloudWalletUser
  : public User
```

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public string ` [`AccountName`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_wax_cloud_wallet_1_1_wax_cloud_wallet_user_1a635084e524fbb2366267e7f5ddc82780) | 
`public ` [`WaxCloudWalletUser`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_wax_cloud_wallet_1_1_wax_cloud_wallet_user_1ab3f7b1b44d812fd8c5e08889be952455)`(string accountName, WaxCloudWalletPlugin waxCloudWalletPlugin)` | 
`public virtual override async Task< string > ` [`GetAccountName`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_wax_cloud_wallet_1_1_wax_cloud_wallet_user_1a185072920e957d470d3766f877f164c0)`()` | 
`public virtual override async Task< string > ` [`GetChainId`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_wax_cloud_wallet_1_1_wax_cloud_wallet_user_1a4840a163daf66e9848b715d037911fa7)`()` | 
`public virtual override async Task< string > ` [`GetKeys`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_wax_cloud_wallet_1_1_wax_cloud_wallet_user_1a22ebe61b245e5a0fffb7106a956a2379)`()` | 
`public virtual override string ` [`GetWalletType`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_wax_cloud_wallet_1_1_wax_cloud_wallet_user_1ad0515ac540e384b6202be982c31796f4)`()` | 
`public virtual override async Task< ` [`SignTransactionResponse`](UniversalAuthenticatorLibrary--SignTransactionResponse.md)` > ` [`SignTransaction`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_wax_cloud_wallet_1_1_wax_cloud_wallet_user_1a68c7afa9823b07f565a4c413cf5f3f7c)`(Transaction transaction, ` [`SignTransactionConfig`](UniversalAuthenticatorLibrary--SignTransactionConfig.md)` config)` | 
`public virtual override async Task< ` [`SignTransactionResponse`](UniversalAuthenticatorLibrary--SignTransactionResponse.md)` > ` [`SignTransaction`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_wax_cloud_wallet_1_1_wax_cloud_wallet_user_1a97bc9e6a3795e8eac4b18cd534a19188)`(` [`Action`](#_example_main_view_8cs_1a24e91c56095a0673d92c6eac6e069a3c)` actions, ` [`SignTransactionConfig`](UniversalAuthenticatorLibrary--SignTransactionConfig.md)` config)` | 
`private WaxCloudWalletPlugin ` [`_waxCloudWalletPlugin`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_wax_cloud_wallet_1_1_wax_cloud_wallet_user_1a61000a73dfb6e41eb8485936be3e984e) | 
`private WcwSignEvent ` [`_wcwSignEvent`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_wax_cloud_wallet_1_1_wax_cloud_wallet_user_1ab1568884cf7ba14a8b8665fcb2881bbe) | 
`private WcwErrorEvent ` [`_wcwErrorEvent`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_wax_cloud_wallet_1_1_wax_cloud_wallet_user_1a06095cf337b4679c22e52ab72c1eb5ec) | 
`private EosApi ` [`_api`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_wax_cloud_wallet_1_1_wax_cloud_wallet_user_1a02bd81e0b511c6f2a9517ba9832b6fac) | 
`private async Task< ` [`SignTransactionResponse`](UniversalAuthenticatorLibrary--SignTransactionResponse.md)` > ` [`WaitForEvent`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_wax_cloud_wallet_1_1_wax_cloud_wallet_user_1a638746597fb65f36eef03af3fd46d7b1)`()` | 

## Members

##### `public string ` [`AccountName`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_wax_cloud_wallet_1_1_wax_cloud_wallet_user_1a635084e524fbb2366267e7f5ddc82780) 

##### `public ` [`WaxCloudWalletUser`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_wax_cloud_wallet_1_1_wax_cloud_wallet_user_1ab3f7b1b44d812fd8c5e08889be952455)`(string accountName, WaxCloudWalletPlugin waxCloudWalletPlugin)` 

##### `public virtual override async Task< string > ` [`GetAccountName`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_wax_cloud_wallet_1_1_wax_cloud_wallet_user_1a185072920e957d470d3766f877f164c0)`()` 

##### `public virtual override async Task< string > ` [`GetChainId`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_wax_cloud_wallet_1_1_wax_cloud_wallet_user_1a4840a163daf66e9848b715d037911fa7)`()` 

##### `public virtual override async Task< string > ` [`GetKeys`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_wax_cloud_wallet_1_1_wax_cloud_wallet_user_1a22ebe61b245e5a0fffb7106a956a2379)`()` 

##### `public virtual override string ` [`GetWalletType`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_wax_cloud_wallet_1_1_wax_cloud_wallet_user_1ad0515ac540e384b6202be982c31796f4)`()` 

##### `public virtual override async Task< ` [`SignTransactionResponse`](UniversalAuthenticatorLibrary--SignTransactionResponse.md)` > ` [`SignTransaction`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_wax_cloud_wallet_1_1_wax_cloud_wallet_user_1a68c7afa9823b07f565a4c413cf5f3f7c)`(Transaction transaction, ` [`SignTransactionConfig`](UniversalAuthenticatorLibrary--SignTransactionConfig.md)` config)` 

##### `public virtual override async Task< ` [`SignTransactionResponse`](UniversalAuthenticatorLibrary--SignTransactionResponse.md)` > ` [`SignTransaction`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_wax_cloud_wallet_1_1_wax_cloud_wallet_user_1a97bc9e6a3795e8eac4b18cd534a19188)`(` [`Action`](#_example_main_view_8cs_1a24e91c56095a0673d92c6eac6e069a3c)` actions, ` [`SignTransactionConfig`](UniversalAuthenticatorLibrary--SignTransactionConfig.md)` config)` 

##### `private WaxCloudWalletPlugin ` [`_waxCloudWalletPlugin`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_wax_cloud_wallet_1_1_wax_cloud_wallet_user_1a61000a73dfb6e41eb8485936be3e984e) 

##### `private WcwSignEvent ` [`_wcwSignEvent`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_wax_cloud_wallet_1_1_wax_cloud_wallet_user_1ab1568884cf7ba14a8b8665fcb2881bbe) 

##### `private WcwErrorEvent ` [`_wcwErrorEvent`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_wax_cloud_wallet_1_1_wax_cloud_wallet_user_1a06095cf337b4679c22e52ab72c1eb5ec) 

##### `private EosApi ` [`_api`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_wax_cloud_wallet_1_1_wax_cloud_wallet_user_1a02bd81e0b511c6f2a9517ba9832b6fac) 

##### `private async Task< ` [`SignTransactionResponse`](UniversalAuthenticatorLibrary--SignTransactionResponse.md)` > ` [`WaitForEvent`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_wax_cloud_wallet_1_1_wax_cloud_wallet_user_1a638746597fb65f36eef03af3fd46d7b1)`()` 

