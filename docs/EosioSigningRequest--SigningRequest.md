# class `EosioSigningRequest::SigningRequest` 

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public readonly byte ` [`Version`](#class_eosio_signing_request_1_1_signing_request_1a178611e8db5d33b13a2e718e3e7da89e)`= 2` | The signing request version.
`public readonly ` [`SigningRequestData`](EosioSigningRequest--SigningRequestData.md)` ` [`Data`](#class_eosio_signing_request_1_1_signing_request_1a4c1257e08422f73b49ebf53f39e0e05b) | The raw signing request data.
`public ` [`RequestSignature`](EosioSigningRequest--RequestSignature.md)` ` [`Signature`](#class_eosio_signing_request_1_1_signing_request_1a9b655cd0a8fcf8e9b7a3a427ad7c3697) | The request signature.
`public ` [`SigningRequest`](#class_eosio_signing_request_1_1_signing_request_1a500f6d90a374de68e9b27851a4dc3fe4)`(byte version, ` [`SigningRequestData`](EosioSigningRequest--SigningRequestData.md)` data, ` [`IZlibProvider`](EosioSigningRequest.md)` zlib, ` [`IAbiSerializationProvider`](EosSharp--Core--Providers.md)` abiSerializationProvider, ` [`RequestSignature`](EosioSigningRequest--RequestSignature.md)` signature)` | Create a new signing request. Normally not used directly, see the `create` and `from` class methods.
`public void ` [`Sign`](#class_eosio_signing_request_1_1_signing_request_1a0964c57b530756bde8afb67b2b0521de)`(` [`ISignProvider`](EosSharp--Core--Interfaces.md)` signatureProvider)` | Sign the request, mutating.
`public byte[] ` [`GetSignatureDigest`](#class_eosio_signing_request_1_1_signing_request_1a0bc2324062c309225c714cb4cdb7797f)`()` | Get the signature digest for this request.
`public void ` [`SetSignature`](#class_eosio_signing_request_1_1_signing_request_1ad42b845b56e72baa05967acde42e05ce)`(string signer, string signature)` | Set the signature data for this request, mutating.
`public void ` [`SetCallback`](#class_eosio_signing_request_1_1_signing_request_1a17b165d149d813362b8de328cde0fdd1)`(string url, bool background)` | Set the request callback, mutating.
`public void ` [`SetBroadcast`](#class_eosio_signing_request_1_1_signing_request_1a16d4f1eef9a879eaaac97ab49610ddc2)`(bool broadcast)` | Set broadcast flag.
`public string ` [`Encode`](#class_eosio_signing_request_1_1_signing_request_1a501ed55bc28053368690d6aa45c452a8)`(bool? compress, bool? slashes)` | 
`public byte[] ` [`GetData`](#class_eosio_signing_request_1_1_signing_request_1adbfc95617cc607e4e391f039973e21d0)`()` | Get the request data without header or signature.
`public byte[] ` [`GetSignatureData`](#class_eosio_signing_request_1_1_signing_request_1a5d9cf9d41b042911e96de12a9947f859)`()` | Get signature data, returns an empty array if request is not signed.
`public List< string > ` [`GetRequiredAbis`](#class_eosio_signing_request_1_1_signing_request_1a7b34185fe9fd822121fb22e49d8afd4d)`()` | ABI definitions required to resolve request.
`public bool ` [`RequiresTapos`](#class_eosio_signing_request_1_1_signing_request_1ae8a1fd251d474cfff3134e308cb27a50)`()` | Whether TaPoS values are required to resolve request.
`public async Task< Dictionary< string, ` [`EosSharp.Core.Api.v1.Abi`](EosSharp--Core--Api--v1--Abi.md)` > > ` [`FetchAbis`](#class_eosio_signing_request_1_1_signing_request_1a287135446ed75cec7993be0bf449f160)`(` [`IAbiSerializationProvider`](EosSharp--Core--Providers.md)` abiSerializationProvider)` | Resolve required ABI definitions.
`public ` [`Action`](EosSharp--Core--Api--v1--Action.md)` ` [`ResolveActions`](#class_eosio_signing_request_1_1_signing_request_1a43068a7abd40e9be516db811d7b02b84)`(Dictionary< string, ` [`Abi`](EosSharp--Core--Api--v1--Abi.md)` > abis, ` [`PermissionLevel`](EosSharp--Core--Api--v1--PermissionLevel.md)` signer)` | Decode raw actions actions to object representations.
`public ` [`Transaction`](EosSharp--Core--Api--v1--Transaction.md)` ` [`ResolveTransaction`](#class_eosio_signing_request_1_1_signing_request_1ab2dc137076b0d0433473e10ec3be598c)`(Dictionary< string, ` [`EosSharp.Core.Api.v1.Abi`](EosSharp--Core--Api--v1--Abi.md)` > abis, ` [`PermissionLevel`](EosSharp--Core--Api--v1--PermissionLevel.md)` signer, ` [`TransactionContext`](EosioSigningRequest--TransactionContext.md)` ctx)` | 
`public ` [`ResolvedSigningRequest`](EosioSigningRequest--ResolvedSigningRequest.md)` ` [`Resolve`](#class_eosio_signing_request_1_1_signing_request_1a54fcdfc703062b208ed48da7a19301db)`(Dictionary< string, ` [`EosSharp.Core.Api.v1.Abi`](EosSharp--Core--Api--v1--Abi.md)` > abis, ` [`PermissionLevel`](EosSharp--Core--Api--v1--PermissionLevel.md)` signer, ` [`TransactionContext`](EosioSigningRequest--TransactionContext.md)` ctx)` | 
`public string ` [`GetChainId`](#class_eosio_signing_request_1_1_signing_request_1adcc54fdf072893165ef0a596b27b783f)`()` | Get the id of the chain where this request is valid.
`public ` [`Action`](EosSharp--Core--Api--v1--Action.md)` ` [`GetRawActions`](#class_eosio_signing_request_1_1_signing_request_1ab95120e3b87a8f38277dc17dd0be31eb)`()` | Return the actions in this request with action data encoded.
`public ` [`Transaction`](EosSharp--Core--Api--v1--Transaction.md)` ` [`GetRawTransaction`](#class_eosio_signing_request_1_1_signing_request_1af1bc0253a1530079097b7aa56aac2c3f)`()` | Unresolved transaction.
`public bool ` [`IsIdentity`](#class_eosio_signing_request_1_1_signing_request_1a41c5fe4ef868e91de373ecd8406afbea)`()` | Whether the request is an identity request.
`public bool ` [`ShouldBroadcast`](#class_eosio_signing_request_1_1_signing_request_1a6b1c7dd6917b5792fea9cade44bff88a)`()` | Whether the request should be broadcast by signer.
`public string ` [`GetIdentity`](#class_eosio_signing_request_1_1_signing_request_1aab2aed888eac28bf4455416cfa34c2b5)`()` | Present if the request is an identity request and requests a specific account. This returns `nil` unless a specific identity has been requested, use `isIdentity` to check id requests.
`public string ` [`GetIdentityPermission`](#class_eosio_signing_request_1_1_signing_request_1aa8d9541f2f33e73a08f65378f1e145d1)`()` | Present if the request is an identity request and requests a specific permission. This returns `nil` unless a specific permission has been requested, use `isIdentity` to check id requests.
`public Dictionary< string, byte[]> ` [`GetRawInfo`](#class_eosio_signing_request_1_1_signing_request_1a62770679be2b9d855d0b706852e56bb4)`()` | Get raw info dict
`public T ` [`GetInfo< T >`](#class_eosio_signing_request_1_1_signing_request_1ab1a3ba7a2e63e8b6be80b162ca160b9e)`(string key, string abiSerializableType)` | Get metadata values as T
`public string ` [`GetInfo`](#class_eosio_signing_request_1_1_signing_request_1ab1de30af8e348351da8668f2a08d9200)`(string key, string abiSerializableType)` | Get metadata values as T
`public Dictionary< string, string > ` [`GetInfos`](#class_eosio_signing_request_1_1_signing_request_1aeb23e5f498a2d03b3d6120d5d96ca24d)`()` | Get metadata values as strings.
`public void ` [`SetInfoKey`](#class_eosio_signing_request_1_1_signing_request_1a8c412aea2aa69da0508663475cc38833)`(string key, object value, string abiSerializableType)` | Set a metadata key.
`public ` [`SigningRequest`](#class_eosio_signing_request_1_1_signing_request)` ` [`Clone`](#class_eosio_signing_request_1_1_signing_request_1a5411bdf3639011151bdf2d5e0be761b6)`()` | Return a deep copy of this request.
`public string ` [`GetIdentityScope`](#class_eosio_signing_request_1_1_signing_request_1aabcb8b43f0c38cecd51ea70677410d14)`()` | Present if the request is an identity request and requests a specific permission. This returns `nil` unless a specific permission has been requested, use `isIdentity` to check id requests.
`private readonly ` [`IZlibProvider`](EosioSigningRequest.md)` ` [`_zlib`](#class_eosio_signing_request_1_1_signing_request_1a2e35455830ca0af10574474af9c0ffff) | 
`private readonly ` [`IAbiSerializationProvider`](EosSharp--Core--Providers.md)` ` [`_abiSerializationProvider`](#class_eosio_signing_request_1_1_signing_request_1a064745c0037ea97c218e477403869873) | 
`private void ` [`ReplacePlaceholders`](#class_eosio_signing_request_1_1_signing_request_1a8c14820758c00550eda4bfedbc8b5526)`(Dictionary< string, object > dataDict, ` [`PermissionLevel`](EosSharp--Core--Api--v1--PermissionLevel.md)` signer)` | 
`public static async Task< ` [`SigningRequest`](#class_eosio_signing_request_1_1_signing_request)` > ` [`Create`](#class_eosio_signing_request_1_1_signing_request_1aa06051ac2db66f08f61ca08ac5fa3aa9)`(` [`SigningRequestCreateArguments`](EosioSigningRequest--SigningRequestCreateArguments.md)` args, ` [`SigningRequestEncodingOptions`](EosioSigningRequest--SigningRequestEncodingOptions.md)` options)` | Create a new signing request.
`public static async Task< ` [`SigningRequest`](#class_eosio_signing_request_1_1_signing_request)` > ` [`Identity`](#class_eosio_signing_request_1_1_signing_request_1af2dd68447583bca0c175b36fe1993346)`(` [`SigningRequestCreateIdentityArguments`](EosioSigningRequest--SigningRequestCreateIdentityArguments.md)` args, ` [`SigningRequestEncodingOptions`](EosioSigningRequest--SigningRequestEncodingOptions.md)` options)` | Creates an identity request.
`public static ` [`SigningRequest`](#class_eosio_signing_request_1_1_signing_request)` ` [`FromTransaction`](#class_eosio_signing_request_1_1_signing_request_1a8603a328faa2da09e07dbcc65472de42)`(object chainId, object serializedTransaction, ` [`SigningRequestEncodingOptions`](EosioSigningRequest--SigningRequestEncodingOptions.md)` options)` | Create a request from a chain id and serialized transaction.
`public static ` [`SigningRequest`](#class_eosio_signing_request_1_1_signing_request)` ` [`From`](#class_eosio_signing_request_1_1_signing_request_1a5c143a71e6d4cb0d06d4cd3f48424f85)`(string uri, ` [`SigningRequestEncodingOptions`](EosioSigningRequest--SigningRequestEncodingOptions.md)` options)` | Creates a signing request from encoded `esr:` uri string.
`public static ` [`SigningRequest`](#class_eosio_signing_request_1_1_signing_request)` ` [`FromData`](#class_eosio_signing_request_1_1_signing_request_1a16d778af8a2d8e7f495af24903fa7c19)`(byte[] data, ` [`SigningRequestEncodingOptions`](EosioSigningRequest--SigningRequestEncodingOptions.md)` options)` | 

## Members

##### `public readonly byte ` [`Version`](#class_eosio_signing_request_1_1_signing_request_1a178611e8db5d33b13a2e718e3e7da89e)`= 2` 

The signing request version.

##### `public readonly ` [`SigningRequestData`](EosioSigningRequest--SigningRequestData.md)` ` [`Data`](#class_eosio_signing_request_1_1_signing_request_1a4c1257e08422f73b49ebf53f39e0e05b) 

The raw signing request data.

##### `public ` [`RequestSignature`](EosioSigningRequest--RequestSignature.md)` ` [`Signature`](#class_eosio_signing_request_1_1_signing_request_1a9b655cd0a8fcf8e9b7a3a427ad7c3697) 

The request signature.

##### `public ` [`SigningRequest`](#class_eosio_signing_request_1_1_signing_request_1a500f6d90a374de68e9b27851a4dc3fe4)`(byte version, ` [`SigningRequestData`](EosioSigningRequest--SigningRequestData.md)` data, ` [`IZlibProvider`](EosioSigningRequest.md)` zlib, ` [`IAbiSerializationProvider`](EosSharp--Core--Providers.md)` abiSerializationProvider, ` [`RequestSignature`](EosioSigningRequest--RequestSignature.md)` signature)` 

Create a new signing request. Normally not used directly, see the `create` and `from` class methods.

##### `public void ` [`Sign`](#class_eosio_signing_request_1_1_signing_request_1a0964c57b530756bde8afb67b2b0521de)`(` [`ISignProvider`](EosSharp--Core--Interfaces.md)` signatureProvider)` 

Sign the request, mutating. 
#### Parameters
* `signatureProvider` The signature provider that provides a signature for the signer.

##### `public byte[] ` [`GetSignatureDigest`](#class_eosio_signing_request_1_1_signing_request_1a0bc2324062c309225c714cb4cdb7797f)`()` 

Get the signature digest for this request.

##### `public void ` [`SetSignature`](#class_eosio_signing_request_1_1_signing_request_1ad42b845b56e72baa05967acde42e05ce)`(string signer, string signature)` 

Set the signature data for this request, mutating. 
#### Parameters
* `signer` Account name of signer. 

* `signature` The signature string.

##### `public void ` [`SetCallback`](#class_eosio_signing_request_1_1_signing_request_1a17b165d149d813362b8de328cde0fdd1)`(string url, bool background)` 

Set the request callback, mutating. 
#### Parameters
* `url` Where the callback should be sent. 

* `background` Whether the callback should be sent in the background.

##### `public void ` [`SetBroadcast`](#class_eosio_signing_request_1_1_signing_request_1a16d4f1eef9a879eaaac97ab49610ddc2)`(bool broadcast)` 

Set broadcast flag. 
#### Parameters
* `broadcast` Whether the transaction should be broadcast by receiver.

##### `public string ` [`Encode`](#class_eosio_signing_request_1_1_signing_request_1a501ed55bc28053368690d6aa45c452a8)`(bool? compress, bool? slashes)` 

##### `public byte[] ` [`GetData`](#class_eosio_signing_request_1_1_signing_request_1adbfc95617cc607e4e391f039973e21d0)`()` 

Get the request data without header or signature.

##### `public byte[] ` [`GetSignatureData`](#class_eosio_signing_request_1_1_signing_request_1a5d9cf9d41b042911e96de12a9947f859)`()` 

Get signature data, returns an empty array if request is not signed.

##### `public List< string > ` [`GetRequiredAbis`](#class_eosio_signing_request_1_1_signing_request_1a7b34185fe9fd822121fb22e49d8afd4d)`()` 

ABI definitions required to resolve request.

##### `public bool ` [`RequiresTapos`](#class_eosio_signing_request_1_1_signing_request_1ae8a1fd251d474cfff3134e308cb27a50)`()` 

Whether TaPoS values are required to resolve request.

##### `public async Task< Dictionary< string, ` [`EosSharp.Core.Api.v1.Abi`](EosSharp--Core--Api--v1--Abi.md)` > > ` [`FetchAbis`](#class_eosio_signing_request_1_1_signing_request_1a287135446ed75cec7993be0bf449f160)`(` [`IAbiSerializationProvider`](EosSharp--Core--Providers.md)` abiSerializationProvider)` 

Resolve required ABI definitions.

##### `public ` [`Action`](EosSharp--Core--Api--v1--Action.md)` ` [`ResolveActions`](#class_eosio_signing_request_1_1_signing_request_1a43068a7abd40e9be516db811d7b02b84)`(Dictionary< string, ` [`Abi`](EosSharp--Core--Api--v1--Abi.md)` > abis, ` [`PermissionLevel`](EosSharp--Core--Api--v1--PermissionLevel.md)` signer)` 

Decode raw actions actions to object representations. 
#### Parameters
* `abis` ABI defenitions required to decode all actions. 

* `signer` Placeholders in actions will be resolved to signer if set.

##### `public ` [`Transaction`](EosSharp--Core--Api--v1--Transaction.md)` ` [`ResolveTransaction`](#class_eosio_signing_request_1_1_signing_request_1ab2dc137076b0d0433473e10ec3be598c)`(Dictionary< string, ` [`EosSharp.Core.Api.v1.Abi`](EosSharp--Core--Api--v1--Abi.md)` > abis, ` [`PermissionLevel`](EosSharp--Core--Api--v1--PermissionLevel.md)` signer, ` [`TransactionContext`](EosioSigningRequest--TransactionContext.md)` ctx)` 

##### `public ` [`ResolvedSigningRequest`](EosioSigningRequest--ResolvedSigningRequest.md)` ` [`Resolve`](#class_eosio_signing_request_1_1_signing_request_1a54fcdfc703062b208ed48da7a19301db)`(Dictionary< string, ` [`EosSharp.Core.Api.v1.Abi`](EosSharp--Core--Api--v1--Abi.md)` > abis, ` [`PermissionLevel`](EosSharp--Core--Api--v1--PermissionLevel.md)` signer, ` [`TransactionContext`](EosioSigningRequest--TransactionContext.md)` ctx)` 

##### `public string ` [`GetChainId`](#class_eosio_signing_request_1_1_signing_request_1adcc54fdf072893165ef0a596b27b783f)`()` 

Get the id of the chain where this request is valid. 
#### Returns
The 32-byte chain id as hex encoded string.

##### `public ` [`Action`](EosSharp--Core--Api--v1--Action.md)` ` [`GetRawActions`](#class_eosio_signing_request_1_1_signing_request_1ab95120e3b87a8f38277dc17dd0be31eb)`()` 

Return the actions in this request with action data encoded.

##### `public ` [`Transaction`](EosSharp--Core--Api--v1--Transaction.md)` ` [`GetRawTransaction`](#class_eosio_signing_request_1_1_signing_request_1af1bc0253a1530079097b7aa56aac2c3f)`()` 

Unresolved transaction.

##### `public bool ` [`IsIdentity`](#class_eosio_signing_request_1_1_signing_request_1a41c5fe4ef868e91de373ecd8406afbea)`()` 

Whether the request is an identity request.

##### `public bool ` [`ShouldBroadcast`](#class_eosio_signing_request_1_1_signing_request_1a6b1c7dd6917b5792fea9cade44bff88a)`()` 

Whether the request should be broadcast by signer.

##### `public string ` [`GetIdentity`](#class_eosio_signing_request_1_1_signing_request_1aab2aed888eac28bf4455416cfa34c2b5)`()` 

Present if the request is an identity request and requests a specific account. This returns `nil` unless a specific identity has been requested, use `isIdentity` to check id requests.

##### `public string ` [`GetIdentityPermission`](#class_eosio_signing_request_1_1_signing_request_1aa8d9541f2f33e73a08f65378f1e145d1)`()` 

Present if the request is an identity request and requests a specific permission. This returns `nil` unless a specific permission has been requested, use `isIdentity` to check id requests.

##### `public Dictionary< string, byte[]> ` [`GetRawInfo`](#class_eosio_signing_request_1_1_signing_request_1a62770679be2b9d855d0b706852e56bb4)`()` 

Get raw info dict

##### `public T ` [`GetInfo< T >`](#class_eosio_signing_request_1_1_signing_request_1ab1a3ba7a2e63e8b6be80b162ca160b9e)`(string key, string abiSerializableType)` 

Get metadata values as T

##### `public string ` [`GetInfo`](#class_eosio_signing_request_1_1_signing_request_1ab1de30af8e348351da8668f2a08d9200)`(string key, string abiSerializableType)` 

Get metadata values as T

##### `public Dictionary< string, string > ` [`GetInfos`](#class_eosio_signing_request_1_1_signing_request_1aeb23e5f498a2d03b3d6120d5d96ca24d)`()` 

Get metadata values as strings.

##### `public void ` [`SetInfoKey`](#class_eosio_signing_request_1_1_signing_request_1a8c412aea2aa69da0508663475cc38833)`(string key, object value, string abiSerializableType)` 

Set a metadata key.

##### `public ` [`SigningRequest`](#class_eosio_signing_request_1_1_signing_request)` ` [`Clone`](#class_eosio_signing_request_1_1_signing_request_1a5411bdf3639011151bdf2d5e0be761b6)`()` 

Return a deep copy of this request.

##### `public string ` [`GetIdentityScope`](#class_eosio_signing_request_1_1_signing_request_1aabcb8b43f0c38cecd51ea70677410d14)`()` 

Present if the request is an identity request and requests a specific permission. This returns `nil` unless a specific permission has been requested, use `isIdentity` to check id requests.

##### `private readonly ` [`IZlibProvider`](EosioSigningRequest.md)` ` [`_zlib`](#class_eosio_signing_request_1_1_signing_request_1a2e35455830ca0af10574474af9c0ffff) 

##### `private readonly ` [`IAbiSerializationProvider`](EosSharp--Core--Providers.md)` ` [`_abiSerializationProvider`](#class_eosio_signing_request_1_1_signing_request_1a064745c0037ea97c218e477403869873) 

##### `private void ` [`ReplacePlaceholders`](#class_eosio_signing_request_1_1_signing_request_1a8c14820758c00550eda4bfedbc8b5526)`(Dictionary< string, object > dataDict, ` [`PermissionLevel`](EosSharp--Core--Api--v1--PermissionLevel.md)` signer)` 

##### `public static async Task< ` [`SigningRequest`](#class_eosio_signing_request_1_1_signing_request)` > ` [`Create`](#class_eosio_signing_request_1_1_signing_request_1aa06051ac2db66f08f61ca08ac5fa3aa9)`(` [`SigningRequestCreateArguments`](EosioSigningRequest--SigningRequestCreateArguments.md)` args, ` [`SigningRequestEncodingOptions`](EosioSigningRequest--SigningRequestEncodingOptions.md)` options)` 

Create a new signing request.

##### `public static async Task< ` [`SigningRequest`](#class_eosio_signing_request_1_1_signing_request)` > ` [`Identity`](#class_eosio_signing_request_1_1_signing_request_1af2dd68447583bca0c175b36fe1993346)`(` [`SigningRequestCreateIdentityArguments`](EosioSigningRequest--SigningRequestCreateIdentityArguments.md)` args, ` [`SigningRequestEncodingOptions`](EosioSigningRequest--SigningRequestEncodingOptions.md)` options)` 

Creates an identity request.

##### `public static ` [`SigningRequest`](#class_eosio_signing_request_1_1_signing_request)` ` [`FromTransaction`](#class_eosio_signing_request_1_1_signing_request_1a8603a328faa2da09e07dbcc65472de42)`(object chainId, object serializedTransaction, ` [`SigningRequestEncodingOptions`](EosioSigningRequest--SigningRequestEncodingOptions.md)` options)` 

Create a request from a chain id and serialized transaction. 
#### Parameters
* `chainId` The chain id where the transaction is valid. 

* `serializedTransaction` The serialized transaction. 

* `options` Creation options.

##### `public static ` [`SigningRequest`](#class_eosio_signing_request_1_1_signing_request)` ` [`From`](#class_eosio_signing_request_1_1_signing_request_1a5c143a71e6d4cb0d06d4cd3f48424f85)`(string uri, ` [`SigningRequestEncodingOptions`](EosioSigningRequest--SigningRequestEncodingOptions.md)` options)` 

Creates a signing request from encoded `esr:` uri string.

##### `public static ` [`SigningRequest`](#class_eosio_signing_request_1_1_signing_request)` ` [`FromData`](#class_eosio_signing_request_1_1_signing_request_1a16d778af8a2d8e7f495af24903fa7c19)`(byte[] data, ` [`SigningRequestEncodingOptions`](EosioSigningRequest--SigningRequestEncodingOptions.md)` options)` 

