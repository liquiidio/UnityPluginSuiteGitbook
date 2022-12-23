# class `EosioSigningRequest::TransactionContext` 

Context used to resolve a transaction. Compatible with the JSON response from a `get_block` call.

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public DateTime? ` [`Timestamp`](#class_eosio_signing_request_1_1_transaction_context_1aa8c5beab2498cc5bf3959b37267b600d) | Timestamp expiration will be derived from.
`public uint? ` [`ExpireSeconds`](#class_eosio_signing_request_1_1_transaction_context_1aedae42d7d90e31877fea74c6b322b64b) | How many seconds in the future to set expiration when deriving from timestamp. Defaults to 60 seconds if unset.
`public ushort? ` [`BlockNum`](#class_eosio_signing_request_1_1_transaction_context_1a2cd70e91fcbdf6df846e35de645c4f7a) | Block number ref_block_num will be derived from.
`public ushort? ` [`RefBlockNum`](#class_eosio_signing_request_1_1_transaction_context_1a9a4684ffa5ca96ca1bde63ed0d763e9f) | Reference block number, takes precedence over block_num if both is set.
`public uint? ` [`RefBlockPrefix`](#class_eosio_signing_request_1_1_transaction_context_1aae7718bb5471334ee1e7c2503d45f6f4) | Reference block prefix.
`public DateTime? ` [`Expiration`](#class_eosio_signing_request_1_1_transaction_context_1a90d843c64f0de28b3dccc63f9f69d531) | Expiration timestamp, takes precedence over timestamp and expire_seconds if set.

## Members

##### `public DateTime? ` [`Timestamp`](#class_eosio_signing_request_1_1_transaction_context_1aa8c5beab2498cc5bf3959b37267b600d) 

Timestamp expiration will be derived from.

##### `public uint? ` [`ExpireSeconds`](#class_eosio_signing_request_1_1_transaction_context_1aedae42d7d90e31877fea74c6b322b64b) 

How many seconds in the future to set expiration when deriving from timestamp. Defaults to 60 seconds if unset.

##### `public ushort? ` [`BlockNum`](#class_eosio_signing_request_1_1_transaction_context_1a2cd70e91fcbdf6df846e35de645c4f7a) 

Block number ref_block_num will be derived from.

##### `public ushort? ` [`RefBlockNum`](#class_eosio_signing_request_1_1_transaction_context_1a9a4684ffa5ca96ca1bde63ed0d763e9f) 

Reference block number, takes precedence over block_num if both is set.

##### `public uint? ` [`RefBlockPrefix`](#class_eosio_signing_request_1_1_transaction_context_1aae7718bb5471334ee1e7c2503d45f6f4) 

Reference block prefix.

##### `public DateTime? ` [`Expiration`](#class_eosio_signing_request_1_1_transaction_context_1a90d843c64f0de28b3dccc63f9f69d531) 

Expiration timestamp, takes precedence over timestamp and expire_seconds if set.

