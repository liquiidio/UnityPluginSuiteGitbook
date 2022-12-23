# class `EosioSigningRequest::TransactionHeader` 

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public DateTime? ` [`Expiration`](#class_eosio_signing_request_1_1_transaction_header_1a90d843c64f0de28b3dccc63f9f69d531) | The time at which a transaction expires.
`public ushort? ` [`RefBlockNum`](#class_eosio_signing_request_1_1_transaction_header_1a9a4684ffa5ca96ca1bde63ed0d763e9f) | Specifies a block num in the last 2^16 blocks.
`public uint? ` [`RefBlockPrefix`](#class_eosio_signing_request_1_1_transaction_header_1aae7718bb5471334ee1e7c2503d45f6f4) | specifies the lower 32 bits of the blockid at get_ref_blocknum
`public uint? ` [`MaxNetUsageWords`](#class_eosio_signing_request_1_1_transaction_header_1aa89040c3c91ec4766e05163ed9824cb5) | Upper limit on total network bandwidth (in 8 byte words) billed for this transaction.
`public byte? ` [`MaxCpuUsageMs`](#class_eosio_signing_request_1_1_transaction_header_1ab5cd6164108a4759f559af0d11695dee) | Upper limit on the total CPU time billed for this transaction.
`public uint? ` [`DelaySec`](#class_eosio_signing_request_1_1_transaction_header_1a1ac2358c3cdbcc918797a51916437f97) | Number of seconds to delay this transaction for during which it may be canceled.

## Members

##### `public DateTime? ` [`Expiration`](#class_eosio_signing_request_1_1_transaction_header_1a90d843c64f0de28b3dccc63f9f69d531) 

The time at which a transaction expires.

##### `public ushort? ` [`RefBlockNum`](#class_eosio_signing_request_1_1_transaction_header_1a9a4684ffa5ca96ca1bde63ed0d763e9f) 

Specifies a block num in the last 2^16 blocks.

##### `public uint? ` [`RefBlockPrefix`](#class_eosio_signing_request_1_1_transaction_header_1aae7718bb5471334ee1e7c2503d45f6f4) 

specifies the lower 32 bits of the blockid at get_ref_blocknum

##### `public uint? ` [`MaxNetUsageWords`](#class_eosio_signing_request_1_1_transaction_header_1aa89040c3c91ec4766e05163ed9824cb5) 

Upper limit on total network bandwidth (in 8 byte words) billed for this transaction.

##### `public byte? ` [`MaxCpuUsageMs`](#class_eosio_signing_request_1_1_transaction_header_1ab5cd6164108a4759f559af0d11695dee) 

Upper limit on the total CPU time billed for this transaction.

##### `public uint? ` [`DelaySec`](#class_eosio_signing_request_1_1_transaction_header_1a1ac2358c3cdbcc918797a51916437f97) 

Number of seconds to delay this transaction for during which it may be canceled.

