# class `EosioSigningRequest::Base64EncodingUtility` 

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public static string ` [`ToBase64UrlSafe`](#class_eosio_signing_request_1_1_base64_encoding_utility_1a404af4cf26ae2e3afeccdaebf34f6c2c)`(byte[] buffer)` | Encodes the binary to URL safe base64.
`public static byte[] ` [`FromBase64UrlSafe`](#class_eosio_signing_request_1_1_base64_encoding_utility_1ab90a252edaacdad882088ceb57c9a395)`(string base54Text)` | Decodes the URL safe base64 encoded string to binary.
`public static byte[] ` [`FromBase64FcString`](#class_eosio_signing_request_1_1_base64_encoding_utility_1a8c5e0e7968aa19605b556652086cdd18)`(string str)` | Convert a base64 encoded string with `fc` prefix to binary.

## Members

##### `public static string ` [`ToBase64UrlSafe`](#class_eosio_signing_request_1_1_base64_encoding_utility_1a404af4cf26ae2e3afeccdaebf34f6c2c)`(byte[] buffer)` 

Encodes the binary to URL safe base64.

#### Parameters
* `buffer` The binary to encode

#### Returns
Returns the URL safe base64 encoded string

##### `public static byte[] ` [`FromBase64UrlSafe`](#class_eosio_signing_request_1_1_base64_encoding_utility_1ab90a252edaacdad882088ceb57c9a395)`(string base54Text)` 

Decodes the URL safe base64 encoded string to binary.

#### Parameters
* `base54Text` The URL safe base64 string

#### Returns
Returns the decoded binary data

##### `public static byte[] ` [`FromBase64FcString`](#class_eosio_signing_request_1_1_base64_encoding_utility_1a8c5e0e7968aa19605b556652086cdd18)`(string str)` 

Convert a base64 encoded string with `fc` prefix to binary.

#### Parameters
* `str` The base64 encoded string with `fc` prefix

#### Returns
Returns the binary data

