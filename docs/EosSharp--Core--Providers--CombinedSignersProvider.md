# class `EosSharp::Core::Providers::CombinedSignersProvider` 

```
class EosSharp::Core::Providers::CombinedSignersProvider
  : public ISignProvider
```

Signature provider that combine multiple signature providers to complete all the signatures for a transaction.

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`private List< ` [`ISignProvider`](EosSharp--Core--Interfaces.md)` > ` [`Signers`](#class_eos_sharp_1_1_core_1_1_providers_1_1_combined_signers_provider_1ae8aaf996c9db766477f2dc50ae603abd) | 
`public ` [`CombinedSignersProvider`](#class_eos_sharp_1_1_core_1_1_providers_1_1_combined_signers_provider_1a6627f4273acabc945dec7a90fbe25c6f)`(List< ` [`ISignProvider`](EosSharp--Core--Interfaces.md)` > signers)` | Creates the provider with a list of signature providers.
`public async Task< IEnumerable< string > > ` [`GetAvailableKeys`](#class_eos_sharp_1_1_core_1_1_providers_1_1_combined_signers_provider_1abc854ac1910c72b068bb1de7b01494cf)`()` | Get available public keys from the list of signature providers.
`public async Task< IEnumerable< string > > ` [`Sign`](#class_eos_sharp_1_1_core_1_1_providers_1_1_combined_signers_provider_1adb0929d2b1d32c1bcf325e15fc8b86f0)`(string chainId, IEnumerable< string > requiredKeys, byte[] signBytes, IEnumerable< string > abiNames)` | Sign bytes using the list of signature providers.
`public string ` [`Sign`](#class_eos_sharp_1_1_core_1_1_providers_1_1_combined_signers_provider_1a0fc9796423303a91abdb2dada5725241)`(string chainId, byte[] signBytes)` | 
`public Dictionary< string, string > ` [`Sign`](#class_eos_sharp_1_1_core_1_1_providers_1_1_combined_signers_provider_1a79cf8d8e56daaf553c0f6f1579016ca6)`()` | 

## Members

##### `private List< ` [`ISignProvider`](EosSharp--Core--Interfaces.md)` > ` [`Signers`](#class_eos_sharp_1_1_core_1_1_providers_1_1_combined_signers_provider_1ae8aaf996c9db766477f2dc50ae603abd) 

##### `public ` [`CombinedSignersProvider`](#class_eos_sharp_1_1_core_1_1_providers_1_1_combined_signers_provider_1a6627f4273acabc945dec7a90fbe25c6f)`(List< ` [`ISignProvider`](EosSharp--Core--Interfaces.md)` > signers)` 

Creates the provider with a list of signature providers.

#### Parameters
* `signers`

##### `public async Task< IEnumerable< string > > ` [`GetAvailableKeys`](#class_eos_sharp_1_1_core_1_1_providers_1_1_combined_signers_provider_1abc854ac1910c72b068bb1de7b01494cf)`()` 

Get available public keys from the list of signature providers.

#### Returns
List of public keys

##### `public async Task< IEnumerable< string > > ` [`Sign`](#class_eos_sharp_1_1_core_1_1_providers_1_1_combined_signers_provider_1adb0929d2b1d32c1bcf325e15fc8b86f0)`(string chainId, IEnumerable< string > requiredKeys, byte[] signBytes, IEnumerable< string > abiNames)` 

Sign bytes using the list of signature providers.

#### Parameters
* `chainId` EOSIO Chain id

* `requiredKeys` required public keys for signing this bytes

* `signBytes` signature bytes

* `abiNames` abi contract names to get abi information from

#### Returns
List of signatures per required keys

##### `public string ` [`Sign`](#class_eos_sharp_1_1_core_1_1_providers_1_1_combined_signers_provider_1a0fc9796423303a91abdb2dada5725241)`(string chainId, byte[] signBytes)` 

##### `public Dictionary< string, string > ` [`Sign`](#class_eos_sharp_1_1_core_1_1_providers_1_1_combined_signers_provider_1a79cf8d8e56daaf553c0f6f1579016ca6)`()` 

