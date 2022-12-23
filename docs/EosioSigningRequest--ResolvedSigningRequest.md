# class `EosioSigningRequest::ResolvedSigningRequest` 

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public readonly SigningRequest ` [`Request`](#class_eosio_signing_request_1_1_resolved_signing_request_1a4666af447650f0245e81089f8a749b5b) | The resolved SigningRequest.
`public readonly PermissionLevel ` [`Signer`](#class_eosio_signing_request_1_1_resolved_signing_request_1a0a4aac3f0767967dc5d8ba8db946abaa) | The signer Permission of the resolved SigningRequest.
`public readonly Transaction ` [`Transaction`](#class_eosio_signing_request_1_1_resolved_signing_request_1aca647c07a8262daff0e94acb66e91621) | The transaction of the resolved SigningRequest.
`public readonly byte[] ` [`SerializedTransaction`](#class_eosio_signing_request_1_1_resolved_signing_request_1ab6cfe929c322a59f3360d9c195e72d06) | 
`public ` [`ResolvedSigningRequest`](#class_eosio_signing_request_1_1_resolved_signing_request_1a07c31983fda249e2ee6f801164a4e605)`(SigningRequest request, PermissionLevel signer, Transaction transaction, byte[] serializedTransaction)` | 
`public string ` [`GetTransactionId`](#class_eosio_signing_request_1_1_resolved_signing_request_1a94044203785090e906fc67365627a703)`()` | Computes the transactionId of the transaction of the resolved Requestt and returns it as Hex-string.
`public ` [`ResolvedCallback`](EosioSigningRequest--ResolvedCallback.md)` ` [`GetCallback`](#class_eosio_signing_request_1_1_resolved_signing_request_1ad126e303ff168defce630b0fb2dc2bb9)`(string[] signatures, int? blockNum)` | Resolves a Callback.
`public static async Task< ResolvedSigningRequest > ` [`FromPayload`](#class_eosio_signing_request_1_1_resolved_signing_request_1ab4f0cd7d51b327eb9592efd2c988226e)`(` [`CallbackPayload`](EosioSigningRequest--CallbackPayload.md)` payload, SigningRequestEncodingOptions options, IAbiSerializationProvider abiSerializationProvider)` | Recreate a resolved request from a callback payload.

## Members

##### `public readonly SigningRequest ` [`Request`](#class_eosio_signing_request_1_1_resolved_signing_request_1a4666af447650f0245e81089f8a749b5b) 

The resolved SigningRequest.

##### `public readonly PermissionLevel ` [`Signer`](#class_eosio_signing_request_1_1_resolved_signing_request_1a0a4aac3f0767967dc5d8ba8db946abaa) 

The signer Permission of the resolved SigningRequest.

##### `public readonly Transaction ` [`Transaction`](#class_eosio_signing_request_1_1_resolved_signing_request_1aca647c07a8262daff0e94acb66e91621) 

The transaction of the resolved SigningRequest.

##### `public readonly byte[] ` [`SerializedTransaction`](#class_eosio_signing_request_1_1_resolved_signing_request_1ab6cfe929c322a59f3360d9c195e72d06) 

##### `public ` [`ResolvedSigningRequest`](#class_eosio_signing_request_1_1_resolved_signing_request_1a07c31983fda249e2ee6f801164a4e605)`(SigningRequest request, PermissionLevel signer, Transaction transaction, byte[] serializedTransaction)` 

##### `public string ` [`GetTransactionId`](#class_eosio_signing_request_1_1_resolved_signing_request_1a94044203785090e906fc67365627a703)`()` 

Computes the transactionId of the transaction of the resolved Requestt and returns it as Hex-string.

#### Returns
the transactionId

##### `public ` [`ResolvedCallback`](EosioSigningRequest--ResolvedCallback.md)` ` [`GetCallback`](#class_eosio_signing_request_1_1_resolved_signing_request_1ad126e303ff168defce630b0fb2dc2bb9)`(string[] signatures, int? blockNum)` 

Resolves a Callback.

#### Parameters
* `signatures` Signature applied to payload and callback-url

* `blockNum` Blocknum applied to payload and callback-url

#### Returns
ResolvedCallback-Object containing payload, url and metadata

##### `public static async Task< ResolvedSigningRequest > ` [`FromPayload`](#class_eosio_signing_request_1_1_resolved_signing_request_1ab4f0cd7d51b327eb9592efd2c988226e)`(` [`CallbackPayload`](EosioSigningRequest--CallbackPayload.md)` payload, SigningRequestEncodingOptions options, IAbiSerializationProvider abiSerializationProvider)` 

Recreate a resolved request from a callback payload.

