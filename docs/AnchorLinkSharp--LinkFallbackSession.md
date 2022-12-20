# class `AnchorLinkSharp::LinkFallbackSession` 

```
class AnchorLinkSharp::LinkFallbackSession
  : public LinkSession
  : public ILinkTransport
```

AnchorLink session that sends every request over the transport.

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public override ` [`AnchorLink`](.github/workflows/documentation/md/AnchorLinkSharp--AnchorLink.md#class_anchor_link_sharp_1_1_anchor_link)` ` [`AnchorLink`](#class_anchor_link_sharp_1_1_link_fallback_session_1a24b28f0dba3b13e8f4a0fdaaa43dc231) | 
`public override string ` [`Identifier`](#class_anchor_link_sharp_1_1_link_fallback_session_1aa5310da6bb012937b796146745fc5ed0) | 
`public override string ` [`PublicKey`](#class_anchor_link_sharp_1_1_link_fallback_session_1ac55c0d79f35bdf0aeb50116a70d7bf55) | 
`public override PermissionLevel ` [`Auth`](#class_anchor_link_sharp_1_1_link_fallback_session_1a31159c68680d5628c3d9b5a17461e0c8) | 
`public override Dictionary< string, object > ` [`Metadata`](#class_anchor_link_sharp_1_1_link_fallback_session_1a6019b38152dde21b18ba0a443e1a9343) | 
`public ` [`ILinkStorage`](.github/workflows/documentation/md/AnchorLinkSharp.md#interface_anchor_link_sharp_1_1_i_link_storage)` ` [`Storage`](#class_anchor_link_sharp_1_1_link_fallback_session_1a3198c2558a95eb66553955ab4b579438) | 
`public ` [`LinkFallbackSession`](#class_anchor_link_sharp_1_1_link_fallback_session_1a017464201706c37a504d26995f8ab669)`(` [`AnchorLink`](.github/workflows/documentation/md/AnchorLinkSharp--AnchorLink.md#class_anchor_link_sharp_1_1_anchor_link)` anchorLink, ` [`LinkFallbackSessionData`](.github/workflows/documentation/md/AnchorLinkSharp--LinkFallbackSessionData.md#class_anchor_link_sharp_1_1_link_fallback_session_data)` data, Dictionary< string, object > metadata)` | 
`public void ` [`OnSuccess`](#class_anchor_link_sharp_1_1_link_fallback_session_1ae42c87a32bf9bfaf937e577cecc1292a)`(SigningRequest request, ` [`TransactResult`](.github/workflows/documentation/md/AnchorLinkSharp--TransactResult.md#class_anchor_link_sharp_1_1_transact_result)` result)` | 
`public void ` [`OnFailure`](#class_anchor_link_sharp_1_1_link_fallback_session_1a2881a07d943ba812c2ec609b33efd401)`(SigningRequest request, Exception exception)` | 
`public void ` [`OnRequest`](#class_anchor_link_sharp_1_1_link_fallback_session_1af033a491264433deccf8f379377bf0de)`(SigningRequest request, Action< object > cancel)` | 
`public Task< SigningRequest > ` [`Prepare`](#class_anchor_link_sharp_1_1_link_fallback_session_1a4cf59f297378d8bf8b50556182625565)`(SigningRequest request, ` [`LinkSession`](.github/workflows/documentation/md/AnchorLinkSharp--LinkSession.md#class_anchor_link_sharp_1_1_link_session)` session)` | 
`public void ` [`ShowLoading`](#class_anchor_link_sharp_1_1_link_fallback_session_1a832760a5318046c0e28d3c99f9a71fa7)`()` | 
`public virtual override LinkSignatureProvider ` [`MakeSignatureProvider`](#class_anchor_link_sharp_1_1_link_fallback_session_1a58701db8173ae17a7f6dc5d10b5a07f2)`()` | 
`public virtual override async Task< ` [`TransactResult`](.github/workflows/documentation/md/AnchorLinkSharp--TransactResult.md#class_anchor_link_sharp_1_1_transact_result)` > ` [`Transact`](#class_anchor_link_sharp_1_1_link_fallback_session_1a0203c2a04ea5cf737cb4fc846b2f1822)`(` [`TransactArgs`](.github/workflows/documentation/md/AnchorLinkSharp--TransactArgs.md#class_anchor_link_sharp_1_1_transact_args)` args, ` [`TransactOptions`](.github/workflows/documentation/md/AnchorLinkSharp--TransactOptions.md#class_anchor_link_sharp_1_1_transact_options)` options)` | 
`public virtual override ` [`SerializedLinkSession`](.github/workflows/documentation/md/AnchorLinkSharp--SerializedLinkSession.md#class_anchor_link_sharp_1_1_serialized_link_session)` ` [`Serialize`](#class_anchor_link_sharp_1_1_link_fallback_session_1ae1257a731a7a371b5ea948a9aec66ebb)`()` | 
`public void ` [`OnSessionRequest`](#class_anchor_link_sharp_1_1_link_fallback_session_1ab43ebe78aa7d484d52f5d1f80e8a0e74)`(` [`LinkSession`](.github/workflows/documentation/md/AnchorLinkSharp--LinkSession.md#class_anchor_link_sharp_1_1_link_session)` session, SigningRequest request, Action< object > cancel)` | 
`private readonly ` [`LinkFallbackSessionData`](.github/workflows/documentation/md/AnchorLinkSharp--LinkFallbackSessionData.md#class_anchor_link_sharp_1_1_link_fallback_session_data)` ` [`_data`](#class_anchor_link_sharp_1_1_link_fallback_session_1a285c682789cc6f896d09a76909bc881b) | 

## Members

##### `public override ` [`AnchorLink`](.github/workflows/documentation/md/AnchorLinkSharp--AnchorLink.md#class_anchor_link_sharp_1_1_anchor_link)` ` [`AnchorLink`](#class_anchor_link_sharp_1_1_link_fallback_session_1a24b28f0dba3b13e8f4a0fdaaa43dc231) 

##### `public override string ` [`Identifier`](#class_anchor_link_sharp_1_1_link_fallback_session_1aa5310da6bb012937b796146745fc5ed0) 

##### `public override string ` [`PublicKey`](#class_anchor_link_sharp_1_1_link_fallback_session_1ac55c0d79f35bdf0aeb50116a70d7bf55) 

##### `public override PermissionLevel ` [`Auth`](#class_anchor_link_sharp_1_1_link_fallback_session_1a31159c68680d5628c3d9b5a17461e0c8) 

##### `public override Dictionary< string, object > ` [`Metadata`](#class_anchor_link_sharp_1_1_link_fallback_session_1a6019b38152dde21b18ba0a443e1a9343) 

##### `public ` [`ILinkStorage`](.github/workflows/documentation/md/AnchorLinkSharp.md#interface_anchor_link_sharp_1_1_i_link_storage)` ` [`Storage`](#class_anchor_link_sharp_1_1_link_fallback_session_1a3198c2558a95eb66553955ab4b579438) 

##### `public ` [`LinkFallbackSession`](#class_anchor_link_sharp_1_1_link_fallback_session_1a017464201706c37a504d26995f8ab669)`(` [`AnchorLink`](.github/workflows/documentation/md/AnchorLinkSharp--AnchorLink.md#class_anchor_link_sharp_1_1_anchor_link)` anchorLink, ` [`LinkFallbackSessionData`](.github/workflows/documentation/md/AnchorLinkSharp--LinkFallbackSessionData.md#class_anchor_link_sharp_1_1_link_fallback_session_data)` data, Dictionary< string, object > metadata)` 

##### `public void ` [`OnSuccess`](#class_anchor_link_sharp_1_1_link_fallback_session_1ae42c87a32bf9bfaf937e577cecc1292a)`(SigningRequest request, ` [`TransactResult`](.github/workflows/documentation/md/AnchorLinkSharp--TransactResult.md#class_anchor_link_sharp_1_1_transact_result)` result)` 

##### `public void ` [`OnFailure`](#class_anchor_link_sharp_1_1_link_fallback_session_1a2881a07d943ba812c2ec609b33efd401)`(SigningRequest request, Exception exception)` 

##### `public void ` [`OnRequest`](#class_anchor_link_sharp_1_1_link_fallback_session_1af033a491264433deccf8f379377bf0de)`(SigningRequest request, Action< object > cancel)` 

##### `public Task< SigningRequest > ` [`Prepare`](#class_anchor_link_sharp_1_1_link_fallback_session_1a4cf59f297378d8bf8b50556182625565)`(SigningRequest request, ` [`LinkSession`](.github/workflows/documentation/md/AnchorLinkSharp--LinkSession.md#class_anchor_link_sharp_1_1_link_session)` session)` 

##### `public void ` [`ShowLoading`](#class_anchor_link_sharp_1_1_link_fallback_session_1a832760a5318046c0e28d3c99f9a71fa7)`()` 

##### `public virtual override LinkSignatureProvider ` [`MakeSignatureProvider`](#class_anchor_link_sharp_1_1_link_fallback_session_1a58701db8173ae17a7f6dc5d10b5a07f2)`()` 

##### `public virtual override async Task< ` [`TransactResult`](.github/workflows/documentation/md/AnchorLinkSharp--TransactResult.md#class_anchor_link_sharp_1_1_transact_result)` > ` [`Transact`](#class_anchor_link_sharp_1_1_link_fallback_session_1a0203c2a04ea5cf737cb4fc846b2f1822)`(` [`TransactArgs`](.github/workflows/documentation/md/AnchorLinkSharp--TransactArgs.md#class_anchor_link_sharp_1_1_transact_args)` args, ` [`TransactOptions`](.github/workflows/documentation/md/AnchorLinkSharp--TransactOptions.md#class_anchor_link_sharp_1_1_transact_options)` options)` 

##### `public virtual override ` [`SerializedLinkSession`](.github/workflows/documentation/md/AnchorLinkSharp--SerializedLinkSession.md#class_anchor_link_sharp_1_1_serialized_link_session)` ` [`Serialize`](#class_anchor_link_sharp_1_1_link_fallback_session_1ae1257a731a7a371b5ea948a9aec66ebb)`()` 

##### `public void ` [`OnSessionRequest`](#class_anchor_link_sharp_1_1_link_fallback_session_1ab43ebe78aa7d484d52f5d1f80e8a0e74)`(` [`LinkSession`](.github/workflows/documentation/md/AnchorLinkSharp--LinkSession.md#class_anchor_link_sharp_1_1_link_session)` session, SigningRequest request, Action< object > cancel)` 

##### `private readonly ` [`LinkFallbackSessionData`](.github/workflows/documentation/md/AnchorLinkSharp--LinkFallbackSessionData.md#class_anchor_link_sharp_1_1_link_fallback_session_data)` ` [`_data`](#class_anchor_link_sharp_1_1_link_fallback_session_1a285c682789cc6f896d09a76909bc881b) 

