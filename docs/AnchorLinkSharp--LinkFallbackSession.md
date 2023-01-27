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
`public override ` [`AnchorLink`](AnchorLinkSharp--AnchorLink.md)` ` [`AnchorLink`](#class_anchor_link_sharp_1_1_link_fallback_session_1a24b28f0dba3b13e8f4a0fdaaa43dc231) | 
`public override string ` [`Identifier`](#class_anchor_link_sharp_1_1_link_fallback_session_1aa5310da6bb012937b796146745fc5ed0) | 
`public override string ` [`PublicKey`](#class_anchor_link_sharp_1_1_link_fallback_session_1ac55c0d79f35bdf0aeb50116a70d7bf55) | 
`public override PermissionLevel ` [`Auth`](#class_anchor_link_sharp_1_1_link_fallback_session_1a31159c68680d5628c3d9b5a17461e0c8) | 
`public override Dictionary< string, object > ` [`Metadata`](#class_anchor_link_sharp_1_1_link_fallback_session_1a6019b38152dde21b18ba0a443e1a9343) | 
`public ` [`ILinkStorage`](AnchorLinkSharp.md)` ` [`Storage`](#class_anchor_link_sharp_1_1_link_fallback_session_1a3198c2558a95eb66553955ab4b579438) | 
`public ` [`LinkFallbackSession`](#class_anchor_link_sharp_1_1_link_fallback_session_1a017464201706c37a504d26995f8ab669)`(` [`AnchorLink`](AnchorLinkSharp--AnchorLink.md)` anchorLink, ` [`LinkFallbackSessionData`](AnchorLinkSharp--LinkFallbackSessionData.md)` data, Dictionary< string, object > metadata)` | 
`public void ` [`OnSuccess`](#class_anchor_link_sharp_1_1_link_fallback_session_1ae42c87a32bf9bfaf937e577cecc1292a)`(` [`SigningRequest`](EosioSigningRequest--SigningRequest.md)` request, ` [`TransactResult`](AnchorLinkSharp--TransactResult.md)` result)` | 
`public void ` [`OnFailure`](#class_anchor_link_sharp_1_1_link_fallback_session_1a2881a07d943ba812c2ec609b33efd401)`(` [`SigningRequest`](EosioSigningRequest--SigningRequest.md)` request, Exception exception)` | 
`public void ` [`OnRequest`](#class_anchor_link_sharp_1_1_link_fallback_session_1af033a491264433deccf8f379377bf0de)`(` [`SigningRequest`](EosioSigningRequest--SigningRequest.md)` request, ` [`Action`](#_anchor_example_panel_8cs_1a24e91c56095a0673d92c6eac6e069a3c)`< object > cancel)` | 
`public Task< ` [`SigningRequest`](EosioSigningRequest--SigningRequest.md)` > ` [`Prepare`](#class_anchor_link_sharp_1_1_link_fallback_session_1a4cf59f297378d8bf8b50556182625565)`(` [`SigningRequest`](EosioSigningRequest--SigningRequest.md)` request, ` [`LinkSession`](AnchorLinkSharp--LinkSession.md)` session)` | 
`public void ` [`ShowLoading`](#class_anchor_link_sharp_1_1_link_fallback_session_1a832760a5318046c0e28d3c99f9a71fa7)`()` | 
`public virtual override ` [`LinkSignatureProvider`](AnchorLinkSharp--LinkSignatureProvider.md)` ` [`MakeSignatureProvider`](#class_anchor_link_sharp_1_1_link_fallback_session_1a58701db8173ae17a7f6dc5d10b5a07f2)`()` | 
`public virtual override async Task< ` [`TransactResult`](AnchorLinkSharp--TransactResult.md)` > ` [`Transact`](#class_anchor_link_sharp_1_1_link_fallback_session_1a0203c2a04ea5cf737cb4fc846b2f1822)`(` [`TransactArgs`](AnchorLinkSharp--TransactArgs.md)` args, ` [`TransactOptions`](AnchorLinkSharp--TransactOptions.md)` options)` | 
`public virtual override ` [`SerializedLinkSession`](AnchorLinkSharp--SerializedLinkSession.md)` ` [`Serialize`](#class_anchor_link_sharp_1_1_link_fallback_session_1ae1257a731a7a371b5ea948a9aec66ebb)`()` | 
`public void ` [`OnSessionRequest`](#class_anchor_link_sharp_1_1_link_fallback_session_1ab43ebe78aa7d484d52f5d1f80e8a0e74)`(` [`LinkSession`](AnchorLinkSharp--LinkSession.md)` session, ` [`SigningRequest`](EosioSigningRequest--SigningRequest.md)` request, ` [`Action`](#_anchor_example_panel_8cs_1a24e91c56095a0673d92c6eac6e069a3c)`< object > cancel)` | 
`private readonly ` [`LinkFallbackSessionData`](AnchorLinkSharp--LinkFallbackSessionData.md)` ` [`_data`](#class_anchor_link_sharp_1_1_link_fallback_session_1a285c682789cc6f896d09a76909bc881b) | 

## Members

##### `public override ` [`AnchorLink`](AnchorLinkSharp--AnchorLink.md)` ` [`AnchorLink`](#class_anchor_link_sharp_1_1_link_fallback_session_1a24b28f0dba3b13e8f4a0fdaaa43dc231) 

##### `public override string ` [`Identifier`](#class_anchor_link_sharp_1_1_link_fallback_session_1aa5310da6bb012937b796146745fc5ed0) 

##### `public override string ` [`PublicKey`](#class_anchor_link_sharp_1_1_link_fallback_session_1ac55c0d79f35bdf0aeb50116a70d7bf55) 

##### `public override PermissionLevel ` [`Auth`](#class_anchor_link_sharp_1_1_link_fallback_session_1a31159c68680d5628c3d9b5a17461e0c8) 

##### `public override Dictionary< string, object > ` [`Metadata`](#class_anchor_link_sharp_1_1_link_fallback_session_1a6019b38152dde21b18ba0a443e1a9343) 

##### `public ` [`ILinkStorage`](AnchorLinkSharp.md)` ` [`Storage`](#class_anchor_link_sharp_1_1_link_fallback_session_1a3198c2558a95eb66553955ab4b579438) 

##### `public ` [`LinkFallbackSession`](#class_anchor_link_sharp_1_1_link_fallback_session_1a017464201706c37a504d26995f8ab669)`(` [`AnchorLink`](AnchorLinkSharp--AnchorLink.md)` anchorLink, ` [`LinkFallbackSessionData`](AnchorLinkSharp--LinkFallbackSessionData.md)` data, Dictionary< string, object > metadata)` 

##### `public void ` [`OnSuccess`](#class_anchor_link_sharp_1_1_link_fallback_session_1ae42c87a32bf9bfaf937e577cecc1292a)`(` [`SigningRequest`](EosioSigningRequest--SigningRequest.md)` request, ` [`TransactResult`](AnchorLinkSharp--TransactResult.md)` result)` 

##### `public void ` [`OnFailure`](#class_anchor_link_sharp_1_1_link_fallback_session_1a2881a07d943ba812c2ec609b33efd401)`(` [`SigningRequest`](EosioSigningRequest--SigningRequest.md)` request, Exception exception)` 

##### `public void ` [`OnRequest`](#class_anchor_link_sharp_1_1_link_fallback_session_1af033a491264433deccf8f379377bf0de)`(` [`SigningRequest`](EosioSigningRequest--SigningRequest.md)` request, ` [`Action`](#_anchor_example_panel_8cs_1a24e91c56095a0673d92c6eac6e069a3c)`< object > cancel)` 

##### `public Task< ` [`SigningRequest`](EosioSigningRequest--SigningRequest.md)` > ` [`Prepare`](#class_anchor_link_sharp_1_1_link_fallback_session_1a4cf59f297378d8bf8b50556182625565)`(` [`SigningRequest`](EosioSigningRequest--SigningRequest.md)` request, ` [`LinkSession`](AnchorLinkSharp--LinkSession.md)` session)` 

##### `public void ` [`ShowLoading`](#class_anchor_link_sharp_1_1_link_fallback_session_1a832760a5318046c0e28d3c99f9a71fa7)`()` 

##### `public virtual override ` [`LinkSignatureProvider`](AnchorLinkSharp--LinkSignatureProvider.md)` ` [`MakeSignatureProvider`](#class_anchor_link_sharp_1_1_link_fallback_session_1a58701db8173ae17a7f6dc5d10b5a07f2)`()` 

##### `public virtual override async Task< ` [`TransactResult`](AnchorLinkSharp--TransactResult.md)` > ` [`Transact`](#class_anchor_link_sharp_1_1_link_fallback_session_1a0203c2a04ea5cf737cb4fc846b2f1822)`(` [`TransactArgs`](AnchorLinkSharp--TransactArgs.md)` args, ` [`TransactOptions`](AnchorLinkSharp--TransactOptions.md)` options)` 

##### `public virtual override ` [`SerializedLinkSession`](AnchorLinkSharp--SerializedLinkSession.md)` ` [`Serialize`](#class_anchor_link_sharp_1_1_link_fallback_session_1ae1257a731a7a371b5ea948a9aec66ebb)`()` 

##### `public void ` [`OnSessionRequest`](#class_anchor_link_sharp_1_1_link_fallback_session_1ab43ebe78aa7d484d52f5d1f80e8a0e74)`(` [`LinkSession`](AnchorLinkSharp--LinkSession.md)` session, ` [`SigningRequest`](EosioSigningRequest--SigningRequest.md)` request, ` [`Action`](#_anchor_example_panel_8cs_1a24e91c56095a0673d92c6eac6e069a3c)`< object > cancel)` 

##### `private readonly ` [`LinkFallbackSessionData`](AnchorLinkSharp--LinkFallbackSessionData.md)` ` [`_data`](#class_anchor_link_sharp_1_1_link_fallback_session_1a285c682789cc6f896d09a76909bc881b) 

