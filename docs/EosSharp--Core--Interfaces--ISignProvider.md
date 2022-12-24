# interface `EosSharp::Core::Interfaces::ISignProvider` 

Signature provider Interface to delegate multiple signing implementations.

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public Task< IEnumerable< string > > ` [`GetAvailableKeys`](EosSharp--Core--Interfaces.md)`()` | Get available public keys from signature provider.
`public Task< IEnumerable< string > > ` [`Sign`](EosSharp--Core--Interfaces.md)`(string chainId, IEnumerable< string > requiredKeys, byte[] signBytes, IEnumerable< string > abiNames)` | Sign bytes using the signature provider.
`public string ` [`Sign`](EosSharp--Core--Interfaces.md)`(string chainId, byte[] signBytes)` | Sign bytes using the signature provider.
`public Dictionary< string, string > ` [`Sign`](EosSharp--Core--Interfaces.md)`()` | 

## Members

##### `public Task< IEnumerable< string > > ` [`GetAvailableKeys`](EosSharp--Core--Interfaces.md)`()` 

Get available public keys from signature provider.

#### Returns
List of public keys

##### `public Task< IEnumerable< string > > ` [`Sign`](EosSharp--Core--Interfaces.md)`(string chainId, IEnumerable< string > requiredKeys, byte[] signBytes, IEnumerable< string > abiNames)` 

Sign bytes using the signature provider.

#### Parameters
* `chainId` EOSIO Chain id

* `requiredKeys` required public keys for signing this bytes

* `signBytes` signature bytes

* `abiNames` abi contract names to get abi information from

#### Returns
List of signatures per required keys

##### `public string ` [`Sign`](EosSharp--Core--Interfaces.md)`(string chainId, byte[] signBytes)` 

Sign bytes using the signature provider.

#### Parameters
* `key` key used for signing

* `signBytes` signature bytes

#### Returns
List of signatures per required keys

##### `public Dictionary< string, string > ` [`Sign`](EosSharp--Core--Interfaces.md)`()` 

