# class `EosioSigningRequest::SigningRequestCreateArguments` 

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public Action ` [`Action`](#class_eosio_signing_request_1_1_signing_request_create_arguments_1ac377793b12e6b1c3a4a087af2736db71) | Single action to create request with.
`public Action[] ` [`Actions`](#class_eosio_signing_request_1_1_signing_request_create_arguments_1a450c08d1f1cc5e400251b488172d7be8) | Multiple actions to create request with.
`public Transaction ` [`Transaction`](#class_eosio_signing_request_1_1_signing_request_create_arguments_1af92c81fa5e0db1514333005d04e9d1d5) | Full or partial transaction to create request with. If TAPoS info is omitted it will be filled in when resolving the request.
`public IdentityV2 ` [`Identity`](#class_eosio_signing_request_1_1_signing_request_create_arguments_1a2f44e5d64b7b947586378f15fbb0034c) | Create an identity request.
`public string ` [`ChainId`](#class_eosio_signing_request_1_1_signing_request_create_arguments_1a4476ef8ec88d45c994accc6d8c4f0da3) | Chain to use, defaults to EOS main-net if omitted.
`public bool? ` [`Broadcast`](#class_eosio_signing_request_1_1_signing_request_create_arguments_1a7c3cd88a3bae96e7019f32074bff6269) | Whether wallet should broadcast tx, defaults to true.
`public object ` [`Callback`](#class_eosio_signing_request_1_1_signing_request_create_arguments_1a931ed2d4c88be9086094e43c927fb532) | Optional callback URL the signer should hit after broadcasting or signing. Passing a string means background = false.
`public object ` [`Info`](#class_eosio_signing_request_1_1_signing_request_create_arguments_1a594a21f1bcb687d27d1e0be5200009e5) | Optional metadata to pass along with the request.

## Members

##### `public Action ` [`Action`](#class_eosio_signing_request_1_1_signing_request_create_arguments_1ac377793b12e6b1c3a4a087af2736db71) 

Single action to create request with.

##### `public Action[] ` [`Actions`](#class_eosio_signing_request_1_1_signing_request_create_arguments_1a450c08d1f1cc5e400251b488172d7be8) 

Multiple actions to create request with.

##### `public Transaction ` [`Transaction`](#class_eosio_signing_request_1_1_signing_request_create_arguments_1af92c81fa5e0db1514333005d04e9d1d5) 

Full or partial transaction to create request with. If TAPoS info is omitted it will be filled in when resolving the request.

##### `public IdentityV2 ` [`Identity`](#class_eosio_signing_request_1_1_signing_request_create_arguments_1a2f44e5d64b7b947586378f15fbb0034c) 

Create an identity request.

##### `public string ` [`ChainId`](#class_eosio_signing_request_1_1_signing_request_create_arguments_1a4476ef8ec88d45c994accc6d8c4f0da3) 

Chain to use, defaults to EOS main-net if omitted.

##### `public bool? ` [`Broadcast`](#class_eosio_signing_request_1_1_signing_request_create_arguments_1a7c3cd88a3bae96e7019f32074bff6269) 

Whether wallet should broadcast tx, defaults to true.

##### `public object ` [`Callback`](#class_eosio_signing_request_1_1_signing_request_create_arguments_1a931ed2d4c88be9086094e43c927fb532) 

Optional callback URL the signer should hit after broadcasting or signing. Passing a string means background = false.

##### `public object ` [`Info`](#class_eosio_signing_request_1_1_signing_request_create_arguments_1a594a21f1bcb687d27d1e0be5200009e5) 

Optional metadata to pass along with the request.

