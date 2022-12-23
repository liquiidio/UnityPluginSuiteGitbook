# class `EosioSigningRequest::CallbackPayload` 

The callback payload sent to background callbacks.

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public string ` [`Sig`](#class_eosio_signing_request_1_1_callback_payload_1a47b44c970581e07458a3f12ad5838d03) | The first signature.
`public string ` [`Tx`](#class_eosio_signing_request_1_1_callback_payload_1a3eac2934f8c4a44bd3523e4d4e6b930c) | Transaction ID as HEX-encoded string.
`public string ` [`Bn`](#class_eosio_signing_request_1_1_callback_payload_1a677288245b7e39128166243c79feec89) | Block number hint (only present if transaction was broadcast).
`public string ` [`Sa`](#class_eosio_signing_request_1_1_callback_payload_1a0a1dab9d8fac6ccf38f9464bc925d0ec) | Signer authority, aka account name.
`public string ` [`Sp`](#class_eosio_signing_request_1_1_callback_payload_1a86efdd189cc5e55a31df4027c1647e98) | Signer permission, e.g. "active".
`public string ` [`Rbn`](#class_eosio_signing_request_1_1_callback_payload_1a187bb4a0a85109d2b37c267d20b1a54a) | Reference block num used when resolving request.
`public string ` [`Rid`](#class_eosio_signing_request_1_1_callback_payload_1a11408a290dc14ccebf59db5d71d9a589) | Reference block id used when resolving request.
`public string ` [`Req`](#class_eosio_signing_request_1_1_callback_payload_1acc7d3ac967ac87b1ff94ee86c85b231f) | The originating signing request packed as a uri string.
`public string ` [`Ex`](#class_eosio_signing_request_1_1_callback_payload_1af90f4977c077d7a5e5c9caaa4e32f7c8) | Expiration time used when resolving request.
`public Dictionary< string, string > ` [`Data`](#class_eosio_signing_request_1_1_callback_payload_1a0b1a02c2487bb0cf63e07057200af41b) | All signatures 0-indexed as `sig0`, `sig1`, etc.

## Members

##### `public string ` [`Sig`](#class_eosio_signing_request_1_1_callback_payload_1a47b44c970581e07458a3f12ad5838d03) 

The first signature.

##### `public string ` [`Tx`](#class_eosio_signing_request_1_1_callback_payload_1a3eac2934f8c4a44bd3523e4d4e6b930c) 

Transaction ID as HEX-encoded string.

##### `public string ` [`Bn`](#class_eosio_signing_request_1_1_callback_payload_1a677288245b7e39128166243c79feec89) 

Block number hint (only present if transaction was broadcast).

##### `public string ` [`Sa`](#class_eosio_signing_request_1_1_callback_payload_1a0a1dab9d8fac6ccf38f9464bc925d0ec) 

Signer authority, aka account name.

##### `public string ` [`Sp`](#class_eosio_signing_request_1_1_callback_payload_1a86efdd189cc5e55a31df4027c1647e98) 

Signer permission, e.g. "active".

##### `public string ` [`Rbn`](#class_eosio_signing_request_1_1_callback_payload_1a187bb4a0a85109d2b37c267d20b1a54a) 

Reference block num used when resolving request.

##### `public string ` [`Rid`](#class_eosio_signing_request_1_1_callback_payload_1a11408a290dc14ccebf59db5d71d9a589) 

Reference block id used when resolving request.

##### `public string ` [`Req`](#class_eosio_signing_request_1_1_callback_payload_1acc7d3ac967ac87b1ff94ee86c85b231f) 

The originating signing request packed as a uri string.

##### `public string ` [`Ex`](#class_eosio_signing_request_1_1_callback_payload_1af90f4977c077d7a5e5c9caaa4e32f7c8) 

Expiration time used when resolving request.

##### `public Dictionary< string, string > ` [`Data`](#class_eosio_signing_request_1_1_callback_payload_1a0b1a02c2487bb0cf63e07057200af41b) 

All signatures 0-indexed as `sig0`, `sig1`, etc.

