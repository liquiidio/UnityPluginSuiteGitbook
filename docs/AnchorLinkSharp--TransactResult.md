## class `AnchorLinkSharp::TransactResult` 

The result of a [[AnchorLink.transact]] call.

### Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`{property}  string[] `[`Signatures`](#class_anchor_link_sharp_1_1_transact_result_1a2611a812ef14c1f9c1f5040253017706) | The transaction signatures.
`{property}  byte[] `[`SerializedTransaction`](#class_anchor_link_sharp_1_1_transact_result_1aba3d8dc245a1e78ee0bb38a8d1a9bb68) | Serialized version of transaction.
`public SigningRequest `[`Request`](#class_anchor_link_sharp_1_1_transact_result_1a160ca56e72d0f7b9cd730bcc7055ad66) | The signing request that was sent.
`public CallbackPayload `[`Payload`](#class_anchor_link_sharp_1_1_transact_result_1a6f1ef57d50070a06b6712c335cf89ba4) | The callback payload.
`public PermissionLevel `[`Signer`](#class_anchor_link_sharp_1_1_transact_result_1a2faf2801a9dd6d1216b2be161b518068) | The signer authority.
`public Transaction `[`Transaction`](#class_anchor_link_sharp_1_1_transact_result_1af92c81fa5e0db1514333005d04e9d1d5) | The resulting transaction.
`public ProcessedTransaction `[`Processed`](#class_anchor_link_sharp_1_1_transact_result_1a685e844f3fc5a9206a25250f5e496dad) | Push transaction response from api node, only present if transaction was broadcast.

### Members

#### `{property}  string[] `[`Signatures`](#class_anchor_link_sharp_1_1_transact_result_1a2611a812ef14c1f9c1f5040253017706) 

The transaction signatures.

#### `{property}  byte[] `[`SerializedTransaction`](#class_anchor_link_sharp_1_1_transact_result_1aba3d8dc245a1e78ee0bb38a8d1a9bb68) 

Serialized version of transaction.

#### `public SigningRequest `[`Request`](#class_anchor_link_sharp_1_1_transact_result_1a160ca56e72d0f7b9cd730bcc7055ad66) 

The signing request that was sent.

#### `public CallbackPayload `[`Payload`](#class_anchor_link_sharp_1_1_transact_result_1a6f1ef57d50070a06b6712c335cf89ba4) 

The callback payload.

#### `public PermissionLevel `[`Signer`](#class_anchor_link_sharp_1_1_transact_result_1a2faf2801a9dd6d1216b2be161b518068) 

The signer authority.

#### `public Transaction `[`Transaction`](#class_anchor_link_sharp_1_1_transact_result_1af92c81fa5e0db1514333005d04e9d1d5) 

The resulting transaction.

#### `public ProcessedTransaction `[`Processed`](#class_anchor_link_sharp_1_1_transact_result_1a685e844f3fc5a9206a25250f5e496dad) 

Push transaction response from api node, only present if transaction was broadcast.

