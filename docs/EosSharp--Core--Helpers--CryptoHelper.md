# CryptoHelper

Helper class with crypto functions.

## Summary

| Members                                                                                                                                                                                                                                                                  | Descriptions                                                                                                         |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------- |
| `class` [`KeyPair`](EosSharp--Core--Helpers--CryptoHelper--KeyPair.md)                                                                                                                                                                                                   | KeyPair with a private and public key.                                                                               |
| `public static` [`KeyPair`](EosSharp--Core--Helpers--CryptoHelper--KeyPair.md) `` [`GenerateKeyPair`](EosSharp--Core--Helpers--CryptoHelper.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_helpers\_1\_1\_crypto\_helper\_1a9a68d315f6c31a00fec9a00c4e71ee24)`(string keyType)` | Generate a new key pair based on a key type.                                                                         |
| `public static byte[]` [`GetPrivateKeyBytesWithoutCheckSum`](EosSharp--Core--Helpers--CryptoHelper.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_helpers\_1\_1\_crypto\_helper\_1a38b2473eed75c06c4c734e27e26122d9)`(string privateKey)`                                       | Get private key bytes without is checksum.                                                                           |
| `public static string` [`PubKeyBytesToString`](EosSharp--Core--Helpers--CryptoHelper.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_helpers\_1\_1\_crypto\_helper\_1ac7162460e9b5ea41250d70eb6a2f7cd9)`(byte[] keyBytes, string keyType, string prefix)`                        | Convert byte array to encoded public key string.                                                                     |
| `public static string` [`PrivKeyBytesToString`](EosSharp--Core--Helpers--CryptoHelper.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_helpers\_1\_1\_crypto\_helper\_1af0e4e0cb3164ad3a83c341697e3d123b)`(byte[] keyBytes, string keyType, string prefix)`                       | Convert byte array to encoded private key string.                                                                    |
| `public static string` [`SignBytesToString`](EosSharp--Core--Helpers--CryptoHelper.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_helpers\_1\_1\_crypto\_helper\_1ac58343e52bf95582164813067793be5e)`(byte[] signBytes, string keyType, string prefix)`                         | Convert byte array to encoded signature string.                                                                      |
| `public static byte[]` [`PubKeyStringToBytes`](EosSharp--Core--Helpers--CryptoHelper.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_helpers\_1\_1\_crypto\_helper\_1ab91ebf83b16a9f194f1ee48dbad32cef)`(string key, string prefix)`                                             | Convert encoded public key to byte array.                                                                            |
| `public static byte[]` [`PrivKeyStringToBytes`](EosSharp--Core--Helpers--CryptoHelper.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_helpers\_1\_1\_crypto\_helper\_1a17e8e76f38936b1b688770994c8f5d06)`(string key)`                                                           | Convert encoded public key to byte array.                                                                            |
| `public static byte[]` [`SignStringToBytes`](EosSharp--Core--Helpers--CryptoHelper.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_helpers\_1\_1\_crypto\_helper\_1ae91273855d47fc7eb2e1f8bed64b562b)`(string sign)`                                                             | Convert encoded signature to byte array.                                                                             |
| `public static byte[]` [`StringToKey`](EosSharp--Core--Helpers--CryptoHelper.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_helpers\_1\_1\_crypto\_helper\_1ae466d4c3676f9acca9a7eba9d7e9787d)`(string key, int size, string keyType)`                                          | Convert Pub/Priv key or signature to byte array.                                                                     |
| `public static string` [`KeyToString`](EosSharp--Core--Helpers--CryptoHelper.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_helpers\_1\_1\_crypto\_helper\_1a8193bcf373a57404f18551ccacc7f402)`(byte[] key, string keyType, string prefix)`                                     | Convert key byte array to encoded generic key.                                                                       |
| `public static byte[]` [`AesEncrypt`](EosSharp--Core--Helpers--CryptoHelper.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_helpers\_1\_1\_crypto\_helper\_1a112e473d779be9458041d39132fa7a89)`(byte[] keyBytes, string plainText)`                                              | It takes a 32 byte key and a 16 byte IV, and uses them to encrypt a string                                           |
| `public static string` [`AesDecrypt`](EosSharp--Core--Helpers--CryptoHelper.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_helpers\_1\_1\_crypto\_helper\_1adc4e9315d0cc011bd7de23fcb4e2a3ef)`(byte[] keyBytes, byte[] cipherText)`                                             | It decrypts the ciphertext using the keyBytes.                                                                       |
| `public static byte[]` [`EncryptStringToBytes_Aes`](EosSharp--Core--Helpers--CryptoHelper.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_helpers\_1\_1\_crypto\_helper\_1a83795232cf502459362028ddaea4c897)`(string plainText, byte[] Key, byte[] IV)`                          | It takes a string, a key, and an IV, and returns an encrypted byte array.                                            |
| `public static string` [`DecryptStringFromBytes_Aes`](EosSharp--Core--Helpers--CryptoHelper.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_helpers\_1\_1\_crypto\_helper\_1ad41398e0f35f226aaa7e9ea014ece67b)`(byte[] cipherText, byte[] Key, byte[] IV)`                       | It takes a byte array of ciphertext, a byte array of key, and a byte array of IV, and returns a string of plaintext. |

## Members

**`class`** [**`KeyPair`**](EosSharp--Core--Helpers--CryptoHelper--KeyPair.md)

KeyPair with a private and public key.

**`public static`** [**`KeyPair`**](EosSharp--Core--Helpers--CryptoHelper--KeyPair.md) **``** [**`GenerateKeyPair`**](EosSharp--Core--Helpers--CryptoHelper.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_helpers\_1\_1\_crypto\_helper\_1a9a68d315f6c31a00fec9a00c4e71ee24)**`(string keyType)`**

Generate a new key pair based on a key type.

#### Parameters

* `keyType` Optional key type. (sha256x2, R1)

#### Returns

key pair

**`public static byte[]`** [**`GetPrivateKeyBytesWithoutCheckSum`**](EosSharp--Core--Helpers--CryptoHelper.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_helpers\_1\_1\_crypto\_helper\_1a38b2473eed75c06c4c734e27e26122d9)**`(string privateKey)`**

Get private key bytes without is checksum.

#### Parameters

* `privateKey` private key

#### Returns

byte array

**`public static string`** [**`PubKeyBytesToString`**](EosSharp--Core--Helpers--CryptoHelper.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_helpers\_1\_1\_crypto\_helper\_1ac7162460e9b5ea41250d70eb6a2f7cd9)**`(byte[] keyBytes, string keyType, string prefix)`**

Convert byte array to encoded public key string.

#### Parameters

* `keyBytes` public key bytes
* `keyType` Optional key type. (sha256x2, R1, K1)
* `prefix` Optional prefix to public key

#### Returns

encoded public key

**`public static string`** [**`PrivKeyBytesToString`**](EosSharp--Core--Helpers--CryptoHelper.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_helpers\_1\_1\_crypto\_helper\_1af0e4e0cb3164ad3a83c341697e3d123b)**`(byte[] keyBytes, string keyType, string prefix)`**

Convert byte array to encoded private key string.

#### Parameters

* `keyBytes` public key bytes
* `keyType` Optional key type. (sha256x2, R1, K1)
* `prefix` Optional prefix to public key

#### Returns

encoded private key

**`public static string`** [**`SignBytesToString`**](EosSharp--Core--Helpers--CryptoHelper.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_helpers\_1\_1\_crypto\_helper\_1ac58343e52bf95582164813067793be5e)**`(byte[] signBytes, string keyType, string prefix)`**

Convert byte array to encoded signature string.

#### Parameters

* `signBytes` signature bytes
* `keyType` Optional key type. (sha256x2, R1, K1)
* `prefix` Optional prefix to public key

#### Returns

encoded signature

**`public static byte[]`** [**`PubKeyStringToBytes`**](EosSharp--Core--Helpers--CryptoHelper.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_helpers\_1\_1\_crypto\_helper\_1ab91ebf83b16a9f194f1ee48dbad32cef)**`(string key, string prefix)`**

Convert encoded public key to byte array.

#### Parameters

* `key` encoded public key
* `prefix` Optional prefix on key

#### Returns

public key bytes

**`public static byte[]`** [**`PrivKeyStringToBytes`**](EosSharp--Core--Helpers--CryptoHelper.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_helpers\_1\_1\_crypto\_helper\_1a17e8e76f38936b1b688770994c8f5d06)**`(string key)`**

Convert encoded public key to byte array.

#### Parameters

* `key` encoded public key
* `prefix` Optional prefix on key

#### Returns

public key bytes

**`public static byte[]`** [**`SignStringToBytes`**](EosSharp--Core--Helpers--CryptoHelper.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_helpers\_1\_1\_crypto\_helper\_1ae91273855d47fc7eb2e1f8bed64b562b)**`(string sign)`**

Convert encoded signature to byte array.

#### Parameters

* `sign` encoded signature

#### Returns

signature bytes

**`public static byte[]`** [**`StringToKey`**](EosSharp--Core--Helpers--CryptoHelper.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_helpers\_1\_1\_crypto\_helper\_1ae466d4c3676f9acca9a7eba9d7e9787d)**`(string key, int size, string keyType)`**

Convert Pub/Priv key or signature to byte array.

#### Parameters

* `key` generic key
* `size` Key size
* `keyType` Optional key type. (sha256x2, R1, K1)

#### Returns

key bytes

**`public static string`** [**`KeyToString`**](EosSharp--Core--Helpers--CryptoHelper.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_helpers\_1\_1\_crypto\_helper\_1a8193bcf373a57404f18551ccacc7f402)**`(byte[] key, string keyType, string prefix)`**

Convert key byte array to encoded generic key.

#### Parameters

* `key` key byte array
* `keyType` Key type. (sha256x2, R1, K1)
* `prefix` Optional prefix

#### Returns

**`public static byte[]`** [**`AesEncrypt`**](EosSharp--Core--Helpers--CryptoHelper.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_helpers\_1\_1\_crypto\_helper\_1a112e473d779be9458041d39132fa7a89)**`(byte[] keyBytes, string plainText)`**

It takes a 32 byte key and a 16 byte IV, and uses them to encrypt a string

#### Parameters

* `keyBytes` The key used to encrypt the data.
* `plainText` The text to be encrypted.

#### Returns

The encrypted text.

**`public static string`** [**`AesDecrypt`**](EosSharp--Core--Helpers--CryptoHelper.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_helpers\_1\_1\_crypto\_helper\_1adc4e9315d0cc011bd7de23fcb4e2a3ef)**`(byte[] keyBytes, byte[] cipherText)`**

It decrypts the ciphertext using the keyBytes.

#### Parameters

* `keyBytes` The key used to encrypt the data.
* `cipherText` The encrypted text

#### Returns

The decrypted string.

**`public static byte[]`** [**`EncryptStringToBytes_Aes`**](EosSharp--Core--Helpers--CryptoHelper.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_helpers\_1\_1\_crypto\_helper\_1a83795232cf502459362028ddaea4c897)**`(string plainText, byte[] Key, byte[] IV)`**

It takes a string, a key, and an IV, and returns an encrypted byte array.

#### Parameters

* `plainText` The text to be encrypted.
* `Key` The key used to encrypt the data.
* `IV` The initialization vector is a random number that is used to encrypt the first block of text in the data. This number is then used in the decryption of the data.

#### Returns

The encrypted bytes from the memory stream.

**`public static string`** [**`DecryptStringFromBytes_Aes`**](EosSharp--Core--Helpers--CryptoHelper.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_helpers\_1\_1\_crypto\_helper\_1ad41398e0f35f226aaa7e9ea014ece67b)**`(byte[] cipherText, byte[] Key, byte[] IV)`**

It takes a byte array of ciphertext, a byte array of key, and a byte array of IV, and returns a string of plaintext.

#### Parameters

* `cipherText` The encrypted string.
* `Key` The key used to encrypt the data.
* `IV` The initialization vector. This is a random string of bytes that is used to initialize the encryption algorithm. It is used to ensure that the same plaintext will not always produce the same ciphertext.

#### Returns

The decrypted string.
