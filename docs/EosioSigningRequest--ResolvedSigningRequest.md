# class `EosioSigningRequest::ResolvedSigningRequest` 

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public readonly ` [`SigningRequest`](EosioSigningRequest--SigningRequest.md)` ` [`Request`](#class_eosio_signing_request_1_1_resolved_signing_request_1a4666af447650f0245e81089f8a749b5b) | 
`public readonly ` [`PermissionLevel`](EosSharp--Core--Api--v1--PermissionLevel.md)` ` [`Signer`](#class_eosio_signing_request_1_1_resolved_signing_request_1a0a4aac3f0767967dc5d8ba8db946abaa) | 
`public readonly ` [`Transaction`](EosSharp--Core--Api--v1--Transaction.md)` ` [`Transaction`](#class_eosio_signing_request_1_1_resolved_signing_request_1aca647c07a8262daff0e94acb66e91621) | 
`public readonly byte[] ` [`SerializedTransaction`](#class_eosio_signing_request_1_1_resolved_signing_request_1ab6cfe929c322a59f3360d9c195e72d06) | 
`public ` [`ResolvedSigningRequest`](#class_eosio_signing_request_1_1_resolved_signing_request_1a07c31983fda249e2ee6f801164a4e605)`(` [`SigningRequest`](EosioSigningRequest--SigningRequest.md)` request, ` [`PermissionLevel`](EosSharp--Core--Api--v1--PermissionLevel.md)` signer, ` [`Transaction`](EosSharp--Core--Api--v1--Transaction.md)` transaction, byte[] serializedTransaction)` | 
`public string ` [`GetTransactionId`](#class_eosio_signing_request_1_1_resolved_signing_request_1a94044203785090e906fc67365627a703)`()` | 
`public ` [`ResolvedCallback`](EosioSigningRequest--ResolvedCallback.md)` ` [`GetCallback`](#class_eosio_signing_request_1_1_resolved_signing_request_1ad126e303ff168defce630b0fb2dc2bb9)`(string[] signatures, int? blockNum)` | 
`public static async Task< ` [`ResolvedSigningRequest`](#class_eosio_signing_request_1_1_resolved_signing_request)` > ` [`FromPayload`](#class_eosio_signing_request_1_1_resolved_signing_request_1ab4f0cd7d51b327eb9592efd2c988226e)`(` [`CallbackPayload`](EosioSigningRequest--CallbackPayload.md)` payload, ` [`SigningRequestEncodingOptions`](EosioSigningRequest--SigningRequestEncodingOptions.md)` options, ` [`IAbiSerializationProvider`](EosSharp--Core--Providers.md)` abiSerializationProvider)` | Recreate a resolved request from a callback payload.

## Members

##### `public readonly ` [`SigningRequest`](EosioSigningRequest--SigningRequest.md)` ` [`Request`](#class_eosio_signing_request_1_1_resolved_signing_request_1a4666af447650f0245e81089f8a749b5b) 

##### `public readonly ` [`PermissionLevel`](EosSharp--Core--Api--v1--PermissionLevel.md)` ` [`Signer`](#class_eosio_signing_request_1_1_resolved_signing_request_1a0a4aac3f0767967dc5d8ba8db946abaa) 

##### `public readonly ` [`Transaction`](EosSharp--Core--Api--v1--Transaction.md)` ` [`Transaction`](#class_eosio_signing_request_1_1_resolved_signing_request_1aca647c07a8262daff0e94acb66e91621) 

##### `public readonly byte[] ` [`SerializedTransaction`](#class_eosio_signing_request_1_1_resolved_signing_request_1ab6cfe929c322a59f3360d9c195e72d06) 

##### `public ` [`ResolvedSigningRequest`](#class_eosio_signing_request_1_1_resolved_signing_request_1a07c31983fda249e2ee6f801164a4e605)`(` [`SigningRequest`](EosioSigningRequest--SigningRequest.md)` request, ` [`PermissionLevel`](EosSharp--Core--Api--v1--PermissionLevel.md)` signer, ` [`Transaction`](EosSharp--Core--Api--v1--Transaction.md)` transaction, byte[] serializedTransaction)` 

##### `public string ` [`GetTransactionId`](#class_eosio_signing_request_1_1_resolved_signing_request_1a94044203785090e906fc67365627a703)`()` 

##### `public ` [`ResolvedCallback`](EosioSigningRequest--ResolvedCallback.md)` ` [`GetCallback`](#class_eosio_signing_request_1_1_resolved_signing_request_1ad126e303ff168defce630b0fb2dc2bb9)`(string[] signatures, int? blockNum)` 

##### `public static async Task< ` [`ResolvedSigningRequest`](#class_eosio_signing_request_1_1_resolved_signing_request)` > ` [`FromPayload`](#class_eosio_signing_request_1_1_resolved_signing_request_1ab4f0cd7d51b327eb9592efd2c988226e)`(` [`CallbackPayload`](EosioSigningRequest--CallbackPayload.md)` payload, ` [`SigningRequestEncodingOptions`](EosioSigningRequest--SigningRequestEncodingOptions.md)` options, ` [`IAbiSerializationProvider`](EosSharp--Core--Providers.md)` abiSerializationProvider)` 

Recreate a resolved request from a callback payload.

