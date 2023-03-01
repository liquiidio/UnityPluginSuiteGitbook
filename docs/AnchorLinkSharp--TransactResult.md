# class `AnchorLinkSharp::TransactResult` 

The result of a [[AnchorLink.transact]] call.

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public string[] ` [`Signatures`](#class_anchor_link_sharp_1_1_transact_result_1a2611a812ef14c1f9c1f5040253017706) | The transaction signatures.
`public byte[] ` [`SerializedTransaction`](#class_anchor_link_sharp_1_1_transact_result_1aba3d8dc245a1e78ee0bb38a8d1a9bb68) | Serialized version of transaction.
`public ` [`SigningRequest`](EosioSigningRequest--SigningRequest.md)` ` [`Request`](#class_anchor_link_sharp_1_1_transact_result_1a160ca56e72d0f7b9cd730bcc7055ad66) | The signing request that was sent.
`public ` [`CallbackPayload`](EosioSigningRequest--CallbackPayload.md)` ` [`Payload`](#class_anchor_link_sharp_1_1_transact_result_1a6f1ef57d50070a06b6712c335cf89ba4) | The callback payload.
`public ` [`PermissionLevel`](EosSharp--Core--Api--v1--PermissionLevel.md)` ` [`Signer`](#class_anchor_link_sharp_1_1_transact_result_1a2faf2801a9dd6d1216b2be161b518068) | The signer authority.
`public ` [`Transaction`](EosSharp--Core--Api--v1--Transaction.md)` ` [`Transaction`](#class_anchor_link_sharp_1_1_transact_result_1af92c81fa5e0db1514333005d04e9d1d5) | The resulting transaction.
`public object ` [`Processed`](#class_anchor_link_sharp_1_1_transact_result_1a95d32e8fdc933dd3428d5b5a82c86191) | Push transaction response from api node, only present if transaction was broadcast.

## Members

##### `public string[] ` [`Signatures`](#class_anchor_link_sharp_1_1_transact_result_1a2611a812ef14c1f9c1f5040253017706) 

The transaction signatures.

##### `public byte[] ` [`SerializedTransaction`](#class_anchor_link_sharp_1_1_transact_result_1aba3d8dc245a1e78ee0bb38a8d1a9bb68) 

Serialized version of transaction.

##### `public ` [`SigningRequest`](EosioSigningRequest--SigningRequest.md)` ` [`Request`](#class_anchor_link_sharp_1_1_transact_result_1a160ca56e72d0f7b9cd730bcc7055ad66) 

The signing request that was sent.

##### `public ` [`CallbackPayload`](EosioSigningRequest--CallbackPayload.md)` ` [`Payload`](#class_anchor_link_sharp_1_1_transact_result_1a6f1ef57d50070a06b6712c335cf89ba4) 

The callback payload.

##### `public ` [`PermissionLevel`](EosSharp--Core--Api--v1--PermissionLevel.md)` ` [`Signer`](#class_anchor_link_sharp_1_1_transact_result_1a2faf2801a9dd6d1216b2be161b518068) 

The signer authority.

##### `public ` [`Transaction`](EosSharp--Core--Api--v1--Transaction.md)` ` [`Transaction`](#class_anchor_link_sharp_1_1_transact_result_1af92c81fa5e0db1514333005d04e9d1d5) 

The resulting transaction.

##### `public object ` [`Processed`](#class_anchor_link_sharp_1_1_transact_result_1a95d32e8fdc933dd3428d5b5a82c86191) 

Push transaction response from api node, only present if transaction was broadcast.

