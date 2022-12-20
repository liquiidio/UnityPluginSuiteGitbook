# class `AnchorLinkSharp::LinkSession` 

Type describing a anchorLink session that can create a eosjs compatible signature provider and transact for a specific auth.

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public abstract ` [`AnchorLink`](.github/workflows/documentation/md/AnchorLinkSharp--AnchorLink.md#class_anchor_link_sharp_1_1_anchor_link)` ` [`AnchorLink`](#class_anchor_link_sharp_1_1_link_session_1a2322154754500382ce52c50682fcf83d) | The underlying anchorLink instance used by the session.
`public abstract string ` [`Identifier`](#class_anchor_link_sharp_1_1_link_session_1a3e44d1bd1025981aab25479699e04c41) | App identifier that owns the session.
`public abstract string ` [`PublicKey`](#class_anchor_link_sharp_1_1_link_session_1a9092880216062f04702041399665a74d) | The public key the session can sign for.
`public abstract EosSharp.Core.Api.v1.PermissionLevel ` [`Auth`](#class_anchor_link_sharp_1_1_link_session_1a7424a61714b657c515f465a310fabc81) | The EOSIO auth (a.k.a. permission level) the session can sign for.
`public abstract Dictionary< string, object > ` [`Metadata`](#class_anchor_link_sharp_1_1_link_session_1a378bcbea14f9daadc8628853b844c2d4) | Arbitrary metadata that will be serialized with the session.
`public abstract LinkSignatureProvider ` [`MakeSignatureProvider`](#class_anchor_link_sharp_1_1_link_session_1afc8c4aabbaaa67518000b0c94aaff5c0)`()` | Creates a eosjs compatible signature provider that can sign for the session public key.
`public abstract Task< ` [`TransactResult`](.github/workflows/documentation/md/AnchorLinkSharp--TransactResult.md#class_anchor_link_sharp_1_1_transact_result)` > ` [`Transact`](#class_anchor_link_sharp_1_1_link_session_1a7d7f4df7098b04d6f399a7b4b861ee25)`(` [`TransactArgs`](.github/workflows/documentation/md/AnchorLinkSharp--TransactArgs.md#class_anchor_link_sharp_1_1_transact_args)` args, ` [`TransactOptions`](.github/workflows/documentation/md/AnchorLinkSharp--TransactOptions.md#class_anchor_link_sharp_1_1_transact_options)` options)` | Transact using this session. See [[AnchorLink.transact]].
`public abstract ` [`SerializedLinkSession`](.github/workflows/documentation/md/AnchorLinkSharp--SerializedLinkSession.md#class_anchor_link_sharp_1_1_serialized_link_session)` ` [`Serialize`](#class_anchor_link_sharp_1_1_link_session_1a04c6ca5dcf9567f3b194d7b53805c097)`()` | Returns a JSON-encodable object that can be used recreate the session.
`public async Task ` [`Remove`](#class_anchor_link_sharp_1_1_link_session_1a67092cd86472aa75e839abd38491001b)`()` | Convenience, remove this session from associated [[AnchorLink]] storage if set. Equivalent to:
`public static ` [`LinkSession`](#class_anchor_link_sharp_1_1_link_session)` ` [`Restore`](#class_anchor_link_sharp_1_1_link_session_1a28aa3da3ab90faebd8351909878959b6)`(` [`AnchorLink`](.github/workflows/documentation/md/AnchorLinkSharp--AnchorLink.md#class_anchor_link_sharp_1_1_anchor_link)` anchorLink, ` [`SerializedLinkSession`](.github/workflows/documentation/md/AnchorLinkSharp--SerializedLinkSession.md#class_anchor_link_sharp_1_1_serialized_link_session)` data)` | Restore a previously serialized session.

## Members

##### `public abstract ` [`AnchorLink`](.github/workflows/documentation/md/AnchorLinkSharp--AnchorLink.md#class_anchor_link_sharp_1_1_anchor_link)` ` [`AnchorLink`](#class_anchor_link_sharp_1_1_link_session_1a2322154754500382ce52c50682fcf83d) 

The underlying anchorLink instance used by the session.

##### `public abstract string ` [`Identifier`](#class_anchor_link_sharp_1_1_link_session_1a3e44d1bd1025981aab25479699e04c41) 

App identifier that owns the session.

##### `public abstract string ` [`PublicKey`](#class_anchor_link_sharp_1_1_link_session_1a9092880216062f04702041399665a74d) 

The public key the session can sign for.

##### `public abstract EosSharp.Core.Api.v1.PermissionLevel ` [`Auth`](#class_anchor_link_sharp_1_1_link_session_1a7424a61714b657c515f465a310fabc81) 

The EOSIO auth (a.k.a. permission level) the session can sign for.

##### `public abstract Dictionary< string, object > ` [`Metadata`](#class_anchor_link_sharp_1_1_link_session_1a378bcbea14f9daadc8628853b844c2d4) 

Arbitrary metadata that will be serialized with the session.

##### `public abstract LinkSignatureProvider ` [`MakeSignatureProvider`](#class_anchor_link_sharp_1_1_link_session_1afc8c4aabbaaa67518000b0c94aaff5c0)`()` 

Creates a eosjs compatible signature provider that can sign for the session public key.

##### `public abstract Task< ` [`TransactResult`](.github/workflows/documentation/md/AnchorLinkSharp--TransactResult.md#class_anchor_link_sharp_1_1_transact_result)` > ` [`Transact`](#class_anchor_link_sharp_1_1_link_session_1a7d7f4df7098b04d6f399a7b4b861ee25)`(` [`TransactArgs`](.github/workflows/documentation/md/AnchorLinkSharp--TransactArgs.md#class_anchor_link_sharp_1_1_transact_args)` args, ` [`TransactOptions`](.github/workflows/documentation/md/AnchorLinkSharp--TransactOptions.md#class_anchor_link_sharp_1_1_transact_options)` options)` 

Transact using this session. See [[AnchorLink.transact]].

##### `public abstract ` [`SerializedLinkSession`](.github/workflows/documentation/md/AnchorLinkSharp--SerializedLinkSession.md#class_anchor_link_sharp_1_1_serialized_link_session)` ` [`Serialize`](#class_anchor_link_sharp_1_1_link_session_1a04c6ca5dcf9567f3b194d7b53805c097)`()` 

Returns a JSON-encodable object that can be used recreate the session.

##### `public async Task ` [`Remove`](#class_anchor_link_sharp_1_1_link_session_1a67092cd86472aa75e839abd38491001b)`()` 

Convenience, remove this session from associated [[AnchorLink]] storage if set. Equivalent to: 
```cpp
session.anchorLink.removeSession(session.identifier, session.auth)
```

##### `public static ` [`LinkSession`](#class_anchor_link_sharp_1_1_link_session)` ` [`Restore`](#class_anchor_link_sharp_1_1_link_session_1a28aa3da3ab90faebd8351909878959b6)`(` [`AnchorLink`](.github/workflows/documentation/md/AnchorLinkSharp--AnchorLink.md#class_anchor_link_sharp_1_1_anchor_link)` anchorLink, ` [`SerializedLinkSession`](.github/workflows/documentation/md/AnchorLinkSharp--SerializedLinkSession.md#class_anchor_link_sharp_1_1_serialized_link_session)` data)` 

Restore a previously serialized session.

