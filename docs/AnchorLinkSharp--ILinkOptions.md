# interface `AnchorLinkSharp::ILinkOptions` 

Available options when creating a new [[AnchorLink]] instance.

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public ` [`ILinkTransport`](.github/workflows/documentation/md/AnchorLinkSharp.md#interface_anchor_link_sharp_1_1_i_link_transport)` ` [`Transport`](.github/workflows/documentation/md/AnchorLinkSharp.md#interface_anchor_link_sharp_1_1_i_link_options_1a30991ccc65e19ed1c427e915b451637b) | AnchorLink transport responsible for presenting signing requests to user, required.
`public string ` [`ChainId`](.github/workflows/documentation/md/AnchorLinkSharp.md#interface_anchor_link_sharp_1_1_i_link_options_1a4476ef8ec88d45c994accc6d8c4f0da3) | ChainID or esr chain name alias for which the anchorLink is valid. Defaults to EOS (aca376f206b8fc25a6ed44dbdc66547c36c6c33e3a119ffbeaef943642f0e906).
`public object ` [`Rpc`](.github/workflows/documentation/md/AnchorLinkSharp.md#interface_anchor_link_sharp_1_1_i_link_options_1a714dd6bb6ac64d2aa2a83fa16b291041) | URL to EOSIO node to communicate with or e EosApi instance. Defaults to [https://eos.greymass.com](https://eos.greymass.com)
`public string ` [`Service`](.github/workflows/documentation/md/AnchorLinkSharp.md#interface_anchor_link_sharp_1_1_i_link_options_1acb72e8546460cb1b9c63792240f4995a) | URL to anchorLink callback service. Defaults to [https://cb.anchor.link](https://cb.anchor.link).
`public ` [`ILinkStorage`](.github/workflows/documentation/md/AnchorLinkSharp.md#interface_anchor_link_sharp_1_1_i_link_storage)` ` [`Storage`](.github/workflows/documentation/md/AnchorLinkSharp.md#interface_anchor_link_sharp_1_1_i_link_options_1a3198c2558a95eb66553955ab4b579438) | Optional storage adapter that will be used to persist sessions if set. If not storage adapter is set but the given transport provides a storage, that will be used. Explicitly set this to `null` to force no storage.
`public IZlibProvider ` [`ZlibProvider`](.github/workflows/documentation/md/AnchorLinkSharp.md#interface_anchor_link_sharp_1_1_i_link_options_1a27585f060ac5d525b44f9078b53aa32a) | 

## Members

##### `public ` [`ILinkTransport`](.github/workflows/documentation/md/AnchorLinkSharp.md#interface_anchor_link_sharp_1_1_i_link_transport)` ` [`Transport`](.github/workflows/documentation/md/AnchorLinkSharp.md#interface_anchor_link_sharp_1_1_i_link_options_1a30991ccc65e19ed1c427e915b451637b) 

AnchorLink transport responsible for presenting signing requests to user, required.

##### `public string ` [`ChainId`](.github/workflows/documentation/md/AnchorLinkSharp.md#interface_anchor_link_sharp_1_1_i_link_options_1a4476ef8ec88d45c994accc6d8c4f0da3) 

ChainID or esr chain name alias for which the anchorLink is valid. Defaults to EOS (aca376f206b8fc25a6ed44dbdc66547c36c6c33e3a119ffbeaef943642f0e906).

##### `public object ` [`Rpc`](.github/workflows/documentation/md/AnchorLinkSharp.md#interface_anchor_link_sharp_1_1_i_link_options_1a714dd6bb6ac64d2aa2a83fa16b291041) 

URL to EOSIO node to communicate with or e EosApi instance. Defaults to [https://eos.greymass.com](https://eos.greymass.com)

##### `public string ` [`Service`](.github/workflows/documentation/md/AnchorLinkSharp.md#interface_anchor_link_sharp_1_1_i_link_options_1acb72e8546460cb1b9c63792240f4995a) 

URL to anchorLink callback service. Defaults to [https://cb.anchor.link](https://cb.anchor.link).

##### `public ` [`ILinkStorage`](.github/workflows/documentation/md/AnchorLinkSharp.md#interface_anchor_link_sharp_1_1_i_link_storage)` ` [`Storage`](.github/workflows/documentation/md/AnchorLinkSharp.md#interface_anchor_link_sharp_1_1_i_link_options_1a3198c2558a95eb66553955ab4b579438) 

Optional storage adapter that will be used to persist sessions if set. If not storage adapter is set but the given transport provides a storage, that will be used. Explicitly set this to `null` to force no storage.

##### `public IZlibProvider ` [`ZlibProvider`](.github/workflows/documentation/md/AnchorLinkSharp.md#interface_anchor_link_sharp_1_1_i_link_options_1a27585f060ac5d525b44f9078b53aa32a) 

