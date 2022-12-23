# interface `AnchorLinkSharp::ILinkOptions` 

Available options when creating a new [[AnchorLink]] instance.

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public ` [`ILinkTransport`](AnchorLinkSharp.md)` ` [`Transport`](AnchorLinkSharp.md) | AnchorLink transport responsible for presenting signing requests to user, required.
`public string ` [`ChainId`](AnchorLinkSharp.md) | ChainID or esr chain name alias for which the anchorLink is valid. Defaults to EOS (aca376f206b8fc25a6ed44dbdc66547c36c6c33e3a119ffbeaef943642f0e906).
`public object ` [`Rpc`](AnchorLinkSharp.md) | URL to EOSIO node to communicate with or e EosApi instance. Defaults to [https://eos.greymass.com](https://eos.greymass.com)
`public string ` [`Service`](AnchorLinkSharp.md) | URL to anchorLink callback service. Defaults to [https://cb.anchor.link](https://cb.anchor.link).
`public ` [`ILinkStorage`](AnchorLinkSharp.md)` ` [`Storage`](AnchorLinkSharp.md) | Optional storage adapter that will be used to persist sessions if set. If not storage adapter is set but the given transport provides a storage, that will be used. Explicitly set this to `null` to force no storage.
`public ` [`IZlibProvider`](EosioSigningRequest.md)` ` [`ZlibProvider`](AnchorLinkSharp.md) | 

## Members

##### `public ` [`ILinkTransport`](AnchorLinkSharp.md)` ` [`Transport`](AnchorLinkSharp.md) 

AnchorLink transport responsible for presenting signing requests to user, required.

##### `public string ` [`ChainId`](AnchorLinkSharp.md) 

ChainID or esr chain name alias for which the anchorLink is valid. Defaults to EOS (aca376f206b8fc25a6ed44dbdc66547c36c6c33e3a119ffbeaef943642f0e906).

##### `public object ` [`Rpc`](AnchorLinkSharp.md) 

URL to EOSIO node to communicate with or e EosApi instance. Defaults to [https://eos.greymass.com](https://eos.greymass.com)

##### `public string ` [`Service`](AnchorLinkSharp.md) 

URL to anchorLink callback service. Defaults to [https://cb.anchor.link](https://cb.anchor.link).

##### `public ` [`ILinkStorage`](AnchorLinkSharp.md)` ` [`Storage`](AnchorLinkSharp.md) 

Optional storage adapter that will be used to persist sessions if set. If not storage adapter is set but the given transport provides a storage, that will be used. Explicitly set this to `null` to force no storage.

##### `public ` [`IZlibProvider`](EosioSigningRequest.md)` ` [`ZlibProvider`](AnchorLinkSharp.md) 

