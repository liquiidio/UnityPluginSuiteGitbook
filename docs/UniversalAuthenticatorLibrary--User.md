# class `UniversalAuthenticatorLibrary::User` 

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public abstract Task< ` [`SignTransactionResponse`](UniversalAuthenticatorLibrary--SignTransactionResponse.md)` > ` [`SignTransaction`](#class_universal_authenticator_library_1_1_user_1a8474a94475897ca28fb2b4aedf5fbe56)`(Transaction transaction, ` [`SignTransactionConfig`](UniversalAuthenticatorLibrary--SignTransactionConfig.md)` config)` | #### Parameters
`public abstract Task< ` [`SignTransactionResponse`](UniversalAuthenticatorLibrary--SignTransactionResponse.md)` > ` [`SignTransaction`](#class_universal_authenticator_library_1_1_user_1a4effd9f8beb08d2e389b60d843f1c474)`(` [`Action`](#_u_a_l_example_panel_8cs_1a24e91c56095a0673d92c6eac6e069a3c)` actions, ` [`SignTransactionConfig`](UniversalAuthenticatorLibrary--SignTransactionConfig.md)` config)` | #### Parameters
`public abstract Task< string > ` [`GetAccountName`](#class_universal_authenticator_library_1_1_user_1a775e8b40319a1310ecb5ccceeb4e09a1)`()` | 
`public abstract Task< string > ` [`GetChainId`](#class_universal_authenticator_library_1_1_user_1a63e9252267067459a97776310f6fb204)`()` | 
`public abstract Task< string > ` [`GetKeys`](#class_universal_authenticator_library_1_1_user_1a0910a057b7d4fb7a9331da132dbcaa08)`()` | 
`public abstract string ` [`GetWalletType`](#class_universal_authenticator_library_1_1_user_1a3280674ce658a5ce896a647576e9ae5e)`()` | 
`protected string ` [`BuildRpcEndpoint`](#class_universal_authenticator_library_1_1_user_1a9ef43a56d7223542b72cbdf6fe15b5e7)`(` [`RpcEndpoint`](UniversalAuthenticatorLibrary--RpcEndpoint.md)` endPoint)` | 

## Members

##### `public abstract Task< ` [`SignTransactionResponse`](UniversalAuthenticatorLibrary--SignTransactionResponse.md)` > ` [`SignTransaction`](#class_universal_authenticator_library_1_1_user_1a8474a94475897ca28fb2b4aedf5fbe56)`(Transaction transaction, ` [`SignTransactionConfig`](UniversalAuthenticatorLibrary--SignTransactionConfig.md)` config)` 

#### Parameters
* `transaction` The transaction to be signed (a object that matches the RpcAPI structure).

##### `public abstract Task< ` [`SignTransactionResponse`](UniversalAuthenticatorLibrary--SignTransactionResponse.md)` > ` [`SignTransaction`](#class_universal_authenticator_library_1_1_user_1a4effd9f8beb08d2e389b60d843f1c474)`(` [`Action`](#_u_a_l_example_panel_8cs_1a24e91c56095a0673d92c6eac6e069a3c)` actions, ` [`SignTransactionConfig`](UniversalAuthenticatorLibrary--SignTransactionConfig.md)` config)` 

#### Parameters
* `actions` The actions to be included into the transaction to be signed (a object that matches the RpcAPI structure).

##### `public abstract Task< string > ` [`GetAccountName`](#class_universal_authenticator_library_1_1_user_1a775e8b40319a1310ecb5ccceeb4e09a1)`()` 

##### `public abstract Task< string > ` [`GetChainId`](#class_universal_authenticator_library_1_1_user_1a63e9252267067459a97776310f6fb204)`()` 

##### `public abstract Task< string > ` [`GetKeys`](#class_universal_authenticator_library_1_1_user_1a0910a057b7d4fb7a9331da132dbcaa08)`()` 

##### `public abstract string ` [`GetWalletType`](#class_universal_authenticator_library_1_1_user_1a3280674ce658a5ce896a647576e9ae5e)`()` 

##### `protected string ` [`BuildRpcEndpoint`](#class_universal_authenticator_library_1_1_user_1a9ef43a56d7223542b72cbdf6fe15b5e7)`(` [`RpcEndpoint`](UniversalAuthenticatorLibrary--RpcEndpoint.md)` endPoint)` 

