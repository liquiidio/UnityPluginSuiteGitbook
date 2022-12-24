# class `EosSharp::Core::Providers::DefaultSignProvider` 

```
class EosSharp::Core::Providers::DefaultSignProvider
  : public ISignProvider
```

Signature provider default implementation that stores private keys in memory.

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public ` [`DefaultSignProvider`](#class_eos_sharp_1_1_core_1_1_providers_1_1_default_sign_provider_1a06070c9f4b3232bfce29d1d208518068)`(string privateKey)` | Create provider with single private key.
`public ` [`DefaultSignProvider`](#class_eos_sharp_1_1_core_1_1_providers_1_1_default_sign_provider_1ab491f05ee59d57e78077ed655b498575)`()` | 
`public ` [`DefaultSignProvider`](#class_eos_sharp_1_1_core_1_1_providers_1_1_default_sign_provider_1ad24474c259472487dc9af334f588d081)`(List< string > privateKeys)` | Create provider with list of private keys.
`public ` [`DefaultSignProvider`](#class_eos_sharp_1_1_core_1_1_providers_1_1_default_sign_provider_1a2e2e004fd9c1c841a46651d29851078c)`(Dictionary< string, string > encodedKeys)` | Create provider with dictionary of encoded key pairs.
`public ` [`DefaultSignProvider`](#class_eos_sharp_1_1_core_1_1_providers_1_1_default_sign_provider_1a4b8c84fad39f9dd53ec93d190f21915d)`(Dictionary< string, byte[]> keys)` | Create provider with dictionary of key pair with private key as byte array.
`public Task< IEnumerable< string > > ` [`GetAvailableKeys`](#class_eos_sharp_1_1_core_1_1_providers_1_1_default_sign_provider_1a89443935d11063ebf000f777ce4686ca)`()` | Get available public keys from signature provider.
`public Task< IEnumerable< string > > ` [`Sign`](#class_eos_sharp_1_1_core_1_1_providers_1_1_default_sign_provider_1aa672810df1c127e9eeb2695b87a474e5)`(string chainId, IEnumerable< string > requiredKeys, byte[] signBytes, IEnumerable< string > abiNames)` | Sign bytes using the signature provider.
`public string ` [`Sign`](#class_eos_sharp_1_1_core_1_1_providers_1_1_default_sign_provider_1a0fc9796423303a91abdb2dada5725241)`(string chainId, byte[] signBytes)` | Sign bytes using the signature provider.
`public Dictionary< string, string > ` [`Sign`](#class_eos_sharp_1_1_core_1_1_providers_1_1_default_sign_provider_1a79cf8d8e56daaf553c0f6f1579016ca6)`()` | 
`private readonly byte[] ` [`KeyTypeBytes`](#class_eos_sharp_1_1_core_1_1_providers_1_1_default_sign_provider_1a2cf57da14bca71b860e5d2508bb27f2e)`= Encoding.UTF8.GetBytes("K1")` | 
`private readonly Dictionary< string, byte[]> ` [`Keys`](#class_eos_sharp_1_1_core_1_1_providers_1_1_default_sign_provider_1a0a3a1162f8d774c5cb19af35b25c8743)`= new Dictionary<string, byte[]>()` | 

## Members

##### `public ` [`DefaultSignProvider`](#class_eos_sharp_1_1_core_1_1_providers_1_1_default_sign_provider_1a06070c9f4b3232bfce29d1d208518068)`(string privateKey)` 

Create provider with single private key.

#### Parameters
* `privateKey`

##### `public ` [`DefaultSignProvider`](#class_eos_sharp_1_1_core_1_1_providers_1_1_default_sign_provider_1ab491f05ee59d57e78077ed655b498575)`()` 

##### `public ` [`DefaultSignProvider`](#class_eos_sharp_1_1_core_1_1_providers_1_1_default_sign_provider_1ad24474c259472487dc9af334f588d081)`(List< string > privateKeys)` 

Create provider with list of private keys.

#### Parameters
* `privateKeys`

##### `public ` [`DefaultSignProvider`](#class_eos_sharp_1_1_core_1_1_providers_1_1_default_sign_provider_1a2e2e004fd9c1c841a46651d29851078c)`(Dictionary< string, string > encodedKeys)` 

Create provider with dictionary of encoded key pairs.

#### Parameters
* `encodedKeys`

##### `public ` [`DefaultSignProvider`](#class_eos_sharp_1_1_core_1_1_providers_1_1_default_sign_provider_1a4b8c84fad39f9dd53ec93d190f21915d)`(Dictionary< string, byte[]> keys)` 

Create provider with dictionary of key pair with private key as byte array.

#### Parameters
* `keys`

##### `public Task< IEnumerable< string > > ` [`GetAvailableKeys`](#class_eos_sharp_1_1_core_1_1_providers_1_1_default_sign_provider_1a89443935d11063ebf000f777ce4686ca)`()` 

Get available public keys from signature provider.

#### Returns
List of public keys

##### `public Task< IEnumerable< string > > ` [`Sign`](#class_eos_sharp_1_1_core_1_1_providers_1_1_default_sign_provider_1aa672810df1c127e9eeb2695b87a474e5)`(string chainId, IEnumerable< string > requiredKeys, byte[] signBytes, IEnumerable< string > abiNames)` 

Sign bytes using the signature provider.

#### Parameters
* `chainId` EOSIO Chain id

* `requiredKeys` required public keys for signing this bytes

* `signBytes` signature bytes

* `abiNames` abi contract names to get abi information from

#### Returns
List of signatures per required keys

##### `public string ` [`Sign`](#class_eos_sharp_1_1_core_1_1_providers_1_1_default_sign_provider_1a0fc9796423303a91abdb2dada5725241)`(string chainId, byte[] signBytes)` 

Sign bytes using the signature provider.

#### Parameters
* `key` key used for signing

* `signBytes` signature bytes

* `abiNames` abi contract names to get abi information from

#### Returns
List of signatures per required keys

##### `public Dictionary< string, string > ` [`Sign`](#class_eos_sharp_1_1_core_1_1_providers_1_1_default_sign_provider_1a79cf8d8e56daaf553c0f6f1579016ca6)`()` 

##### `private readonly byte[] ` [`KeyTypeBytes`](#class_eos_sharp_1_1_core_1_1_providers_1_1_default_sign_provider_1a2cf57da14bca71b860e5d2508bb27f2e)`= Encoding.UTF8.GetBytes("K1")` 

##### `private readonly Dictionary< string, byte[]> ` [`Keys`](#class_eos_sharp_1_1_core_1_1_providers_1_1_default_sign_provider_1a0a3a1162f8d774c5cb19af35b25c8743)`= new Dictionary<string, byte[]>()` 

