# class `EosioSigningRequest::SigningRequestEncodingOptions` 

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public ` [`IZlibProvider`](EosioSigningRequest.md)` ` [`Zlib`](#class_eosio_signing_request_1_1_signing_request_encoding_options_1a3e0b98a7386e4ba7d41b4e372bf29c41) | Optional zlib, if provided the request will be compressed when encoding.
`public IAbiSerializationProvider ` [`AbiSerializationProvider`](#class_eosio_signing_request_1_1_signing_request_encoding_options_1abd9a1d1fc2896aa0f42f6413b6c5e59e) | Abi provider, required if the arguments contain un-encoded actions.
`public ISignProvider ` [`SignatureProvider`](#class_eosio_signing_request_1_1_signing_request_encoding_options_1aee547ad0c0284393549b3c14bc870f65) | Optional signature provider, will be used to create a request signature if provided.

## Members

##### `public ` [`IZlibProvider`](EosioSigningRequest.md)` ` [`Zlib`](#class_eosio_signing_request_1_1_signing_request_encoding_options_1a3e0b98a7386e4ba7d41b4e372bf29c41) 

Optional zlib, if provided the request will be compressed when encoding.

##### `public IAbiSerializationProvider ` [`AbiSerializationProvider`](#class_eosio_signing_request_1_1_signing_request_encoding_options_1abd9a1d1fc2896aa0f42f6413b6c5e59e) 

Abi provider, required if the arguments contain un-encoded actions.

##### `public ISignProvider ` [`SignatureProvider`](#class_eosio_signing_request_1_1_signing_request_encoding_options_1aee547ad0c0284393549b3c14bc870f65) 

Optional signature provider, will be used to create a request signature if provided.

