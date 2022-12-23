# class `EosioSigningRequest::SigningRequestConstants` 

Static Class containing Constants used with the SigningRequest Package.

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public static bool ` [`IsIdentity`](#class_eosio_signing_request_1_1_signing_request_constants_1a1ffa929390cc3808305c1818e1a93b57)`(Action action)` | Checks if an action is an IdentityRequest.
`public static bool ` [`HasTapos`](#class_eosio_signing_request_1_1_signing_request_constants_1a27b46a905a4321f1a7a957167d82edd7)`(Transaction tx)` | Checks if an transaction has TAPOS (Transaction as Proof of Stake) properties set.
`public static KeyValuePair< string, object > ` [`VariantId`](#class_eosio_signing_request_1_1_signing_request_constants_1a456133560d18d3e4eb595aa2f07d1876)`(object chainId)` | Converts the chainId-Object to a KeyValuePair<string, object>.

## Members

##### `public static bool ` [`IsIdentity`](#class_eosio_signing_request_1_1_signing_request_constants_1a1ffa929390cc3808305c1818e1a93b57)`(Action action)` 

Checks if an action is an IdentityRequest.

#### Parameters
* `action` The action to be checked.

#### Returns
Returns true if the action passed is an IdentityRequest, returns false if not

##### `public static bool ` [`HasTapos`](#class_eosio_signing_request_1_1_signing_request_constants_1a27b46a905a4321f1a7a957167d82edd7)`(Transaction tx)` 

Checks if an transaction has TAPOS (Transaction as Proof of Stake) properties set.

#### Parameters
* `tx` The transaction to be checked.

#### Returns
Returns true if the transaction passed has TAPOS, returns false if not

##### `public static KeyValuePair< string, object > ` [`VariantId`](#class_eosio_signing_request_1_1_signing_request_constants_1a456133560d18d3e4eb595aa2f07d1876)`(object chainId)` 

Converts the chainId-Object to a KeyValuePair<string, object>.

#### Parameters
* `chainId` The chainId-Object to be converted, can either be of type string (Chain-Id or Chain-Name), ChainName-Enum, byte.

#### Returns
Returns a KeyValuePair<string, object> defining the variant-name and the object

