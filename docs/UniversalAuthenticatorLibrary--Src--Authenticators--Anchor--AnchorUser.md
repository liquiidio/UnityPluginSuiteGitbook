# class `UniversalAuthenticatorLibrary::Src::Authenticators::Anchor::AnchorUser` 

```
class UniversalAuthenticatorLibrary::Src::Authenticators::Anchor::AnchorUser
  : public User
```

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public LinkSession ` [`Session`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_anchor_1_1_anchor_user_1a14ef31455c6bbcc06398fa9eb58b5bf1) | 
`public ` [`AnchorUser`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_anchor_1_1_anchor_user_1aa11278b0b8a1f7ed4511317ecfee7a18)`(LinkSession session)` | 
`public virtual override async Task< string > ` [`GetAccountName`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_anchor_1_1_anchor_user_1a185072920e957d470d3766f877f164c0)`()` | 
`public virtual override async Task< string > ` [`GetChainId`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_anchor_1_1_anchor_user_1a4840a163daf66e9848b715d037911fa7)`()` | 
`public virtual override async Task< string > ` [`GetKeys`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_anchor_1_1_anchor_user_1a22ebe61b245e5a0fffb7106a956a2379)`()` | 
`public virtual override string ` [`GetWalletType`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_anchor_1_1_anchor_user_1ad0515ac540e384b6202be982c31796f4)`()` | 
`public virtual override async Task< ` [`SignTransactionResponse`](UniversalAuthenticatorLibrary--SignTransactionResponse.md)` > ` [`SignTransaction`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_anchor_1_1_anchor_user_1a68c7afa9823b07f565a4c413cf5f3f7c)`(Transaction transaction, ` [`SignTransactionConfig`](UniversalAuthenticatorLibrary--SignTransactionConfig.md)` config)` | 
`public virtual override async Task< ` [`SignTransactionResponse`](UniversalAuthenticatorLibrary--SignTransactionResponse.md)` > ` [`SignTransaction`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_anchor_1_1_anchor_user_1a97bc9e6a3795e8eac4b18cd534a19188)`(` [`Action`](#_example_main_view_8cs_1a24e91c56095a0673d92c6eac6e069a3c)` actions, ` [`SignTransactionConfig`](UniversalAuthenticatorLibrary--SignTransactionConfig.md)` config)` | 
`private async Task< ` [`SignTransactionResponse`](UniversalAuthenticatorLibrary--SignTransactionResponse.md)` > ` [`Transact`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_anchor_1_1_anchor_user_1af02144a31edc9b53218e5d9ccadcd43e)`(` [`Action`](#_example_main_view_8cs_1a24e91c56095a0673d92c6eac6e069a3c)` action, ` [`Action`](#_example_main_view_8cs_1a24e91c56095a0673d92c6eac6e069a3c)` actions, Transaction transaction)` | 

## Members

##### `public LinkSession ` [`Session`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_anchor_1_1_anchor_user_1a14ef31455c6bbcc06398fa9eb58b5bf1) 

##### `public ` [`AnchorUser`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_anchor_1_1_anchor_user_1aa11278b0b8a1f7ed4511317ecfee7a18)`(LinkSession session)` 

##### `public virtual override async Task< string > ` [`GetAccountName`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_anchor_1_1_anchor_user_1a185072920e957d470d3766f877f164c0)`()` 

##### `public virtual override async Task< string > ` [`GetChainId`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_anchor_1_1_anchor_user_1a4840a163daf66e9848b715d037911fa7)`()` 

##### `public virtual override async Task< string > ` [`GetKeys`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_anchor_1_1_anchor_user_1a22ebe61b245e5a0fffb7106a956a2379)`()` 

##### `public virtual override string ` [`GetWalletType`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_anchor_1_1_anchor_user_1ad0515ac540e384b6202be982c31796f4)`()` 

##### `public virtual override async Task< ` [`SignTransactionResponse`](UniversalAuthenticatorLibrary--SignTransactionResponse.md)` > ` [`SignTransaction`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_anchor_1_1_anchor_user_1a68c7afa9823b07f565a4c413cf5f3f7c)`(Transaction transaction, ` [`SignTransactionConfig`](UniversalAuthenticatorLibrary--SignTransactionConfig.md)` config)` 

##### `public virtual override async Task< ` [`SignTransactionResponse`](UniversalAuthenticatorLibrary--SignTransactionResponse.md)` > ` [`SignTransaction`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_anchor_1_1_anchor_user_1a97bc9e6a3795e8eac4b18cd534a19188)`(` [`Action`](#_example_main_view_8cs_1a24e91c56095a0673d92c6eac6e069a3c)` actions, ` [`SignTransactionConfig`](UniversalAuthenticatorLibrary--SignTransactionConfig.md)` config)` 

##### `private async Task< ` [`SignTransactionResponse`](UniversalAuthenticatorLibrary--SignTransactionResponse.md)` > ` [`Transact`](#class_universal_authenticator_library_1_1_src_1_1_authenticators_1_1_anchor_1_1_anchor_user_1af02144a31edc9b53218e5d9ccadcd43e)`(` [`Action`](#_example_main_view_8cs_1a24e91c56095a0673d92c6eac6e069a3c)` action, ` [`Action`](#_example_main_view_8cs_1a24e91c56095a0673d92c6eac6e069a3c)` actions, Transaction transaction)` 

