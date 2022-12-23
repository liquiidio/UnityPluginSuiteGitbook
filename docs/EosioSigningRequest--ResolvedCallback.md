# class `EosioSigningRequest::ResolvedCallback` 

Context used to resolve a callback. Compatible with the JSON response from a `push_transaction` call.

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public string ` [`Url`](#class_eosio_signing_request_1_1_resolved_callback_1a9619cd3b7a409d3733877feef572732d) | The URL to hit.
`public bool ` [`Background`](#class_eosio_signing_request_1_1_resolved_callback_1a1257345277af35dad6e3b0292889ea5e) | Whether to run the request in the background. For a https url this means POST in the background instead of a GET redirect.
`public ` [`CallbackPayload`](EosioSigningRequest--CallbackPayload.md)` ` [`Payload`](#class_eosio_signing_request_1_1_resolved_callback_1a6f1ef57d50070a06b6712c335cf89ba4) | The callback payload as a object that should be encoded to JSON and POSTed to background callbacks.

## Members

##### `public string ` [`Url`](#class_eosio_signing_request_1_1_resolved_callback_1a9619cd3b7a409d3733877feef572732d) 

The URL to hit.

##### `public bool ` [`Background`](#class_eosio_signing_request_1_1_resolved_callback_1a1257345277af35dad6e3b0292889ea5e) 

Whether to run the request in the background. For a https url this means POST in the background instead of a GET redirect.

##### `public ` [`CallbackPayload`](EosioSigningRequest--CallbackPayload.md)` ` [`Payload`](#class_eosio_signing_request_1_1_resolved_callback_1a6f1ef57d50070a06b6712c335cf89ba4) 

The callback payload as a object that should be encoded to JSON and POSTed to background callbacks.

