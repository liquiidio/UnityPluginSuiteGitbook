# class `AnchorLinkSharp::LinkUtils` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public static byte[] `[`AbiEncode`](#class_anchor_link_sharp_1_1_link_utils_1adab3b9354609878652e652f1f9fc620a)`(object value, string typeName)` | 
`public static TResultType `[`AbiDecode< TResultType >`](#class_anchor_link_sharp_1_1_link_utils_1a5952626941960f110b92a0a3438bae3b)`(byte[] bytes, string typeName, TResultType result)` | Helper to ABI decode data.
`public static byte[] `[`SealMessage`](#class_anchor_link_sharp_1_1_link_utils_1a538ddc29affee1a165387aab12338828)`(string message, string privateKey, string publicKey)` | Encrypt a message using AES and shared secret derived from given keys.
`public static string `[`NormalizePublicKey`](#class_anchor_link_sharp_1_1_link_utils_1af14e57b1b17d5e8c8bd1a14316c8356f)`(string key)` | Ensure public key is in new PUB_ format.
`public static bool `[`PublicKeyEqual`](#class_anchor_link_sharp_1_1_link_utils_1aee35594576cbcd989a3885af2d8f6afb)`(string keyA, string keyB)` | Return true if given public keys are equal.
`public static string `[`GeneratePrivateKey`](#class_anchor_link_sharp_1_1_link_utils_1a5b46dbec4572c7e31e33244880b89991)`()` | Generate a random private key. Uses browser crypto if available, otherwise falls back to slow eosjs-ecc.

## Members

### `public static byte[] `[`AbiEncode`](#class_anchor_link_sharp_1_1_link_utils_1adab3b9354609878652e652f1f9fc620a)`(object value, string typeName)` 

### `public static TResultType `[`AbiDecode< TResultType >`](#class_anchor_link_sharp_1_1_link_utils_1a5952626941960f110b92a0a3438bae3b)`(byte[] bytes, string typeName, TResultType result)` 

Helper to ABI decode data.

### `public static byte[] `[`SealMessage`](#class_anchor_link_sharp_1_1_link_utils_1a538ddc29affee1a165387aab12338828)`(string message, string privateKey, string publicKey)` 

Encrypt a message using AES and shared secret derived from given keys.

### `public static string `[`NormalizePublicKey`](#class_anchor_link_sharp_1_1_link_utils_1af14e57b1b17d5e8c8bd1a14316c8356f)`(string key)` 

Ensure public key is in new PUB_ format.

### `public static bool `[`PublicKeyEqual`](#class_anchor_link_sharp_1_1_link_utils_1aee35594576cbcd989a3885af2d8f6afb)`(string keyA, string keyB)` 

Return true if given public keys are equal.

### `public static string `[`GeneratePrivateKey`](#class_anchor_link_sharp_1_1_link_utils_1a5b46dbec4572c7e31e33244880b89991)`()` 

Generate a random private key. Uses browser crypto if available, otherwise falls back to slow eosjs-ecc.

