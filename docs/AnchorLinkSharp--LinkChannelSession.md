# class `AnchorLinkSharp::LinkChannelSession` 

```
class AnchorLinkSharp::LinkChannelSession
  : public LinkSession
  : public ILinkTransport
```

AnchorLink session that pushes requests over a channel.

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public override ` [`AnchorLink`](AnchorLinkSharp--AnchorLink.md)` ` [`AnchorLink`](#class_anchor_link_sharp_1_1_link_channel_session_1a24b28f0dba3b13e8f4a0fdaaa43dc231) | 
`public override string ` [`Identifier`](#class_anchor_link_sharp_1_1_link_channel_session_1aa5310da6bb012937b796146745fc5ed0) | 
`public override string ` [`PublicKey`](#class_anchor_link_sharp_1_1_link_channel_session_1ac55c0d79f35bdf0aeb50116a70d7bf55) | 
`public override ` [`PermissionLevel`](EosSharp--Core--Api--v1--PermissionLevel.md)` ` [`Auth`](#class_anchor_link_sharp_1_1_link_channel_session_1a31159c68680d5628c3d9b5a17461e0c8) | 
`public override Dictionary< string, object > ` [`Metadata`](#class_anchor_link_sharp_1_1_link_channel_session_1a6019b38152dde21b18ba0a443e1a9343) | 
`public ` [`ILinkStorage`](AnchorLinkSharp.md)` ` [`Storage`](#class_anchor_link_sharp_1_1_link_channel_session_1a3198c2558a95eb66553955ab4b579438) | 
`public ` [`LinkChannelSession`](#class_anchor_link_sharp_1_1_link_channel_session_1a38b43400852a044907e80c9790f5a310)`(` [`AnchorLink`](AnchorLinkSharp--AnchorLink.md)` anchorLink, ` [`LinkChannelSessionData`](AnchorLinkSharp--LinkChannelSessionData.md)` data, Dictionary< string, object > metadata)` | 
`public void ` [`OnSuccess`](#class_anchor_link_sharp_1_1_link_channel_session_1ae42c87a32bf9bfaf937e577cecc1292a)`(` [`SigningRequest`](EosioSigningRequest--SigningRequest.md)` request, ` [`TransactResult`](AnchorLinkSharp--TransactResult.md)` result)` | 
`public void ` [`OnFailure`](#class_anchor_link_sharp_1_1_link_channel_session_1a2881a07d943ba812c2ec609b33efd401)`(` [`SigningRequest`](EosioSigningRequest--SigningRequest.md)` request, Exception exception)` | 
`public async void ` [`OnRequest`](#class_anchor_link_sharp_1_1_link_channel_session_1a2a447f06a5957b27add17fe4bd4992a1)`(` [`SigningRequest`](EosioSigningRequest--SigningRequest.md)` request, ` [`Action`](EosSharp--Core--Api--v1--Action.md)`< object > cancel)` | 
`public async Task< ` [`SigningRequest`](EosioSigningRequest--SigningRequest.md)` > ` [`Prepare`](#class_anchor_link_sharp_1_1_link_channel_session_1a2ba24fa9a86412c68780ae3157322251)`(` [`SigningRequest`](EosioSigningRequest--SigningRequest.md)` request, ` [`LinkSession`](AnchorLinkSharp--LinkSession.md)` session)` | 
`public void ` [`ShowLoading`](#class_anchor_link_sharp_1_1_link_channel_session_1a832760a5318046c0e28d3c99f9a71fa7)`()` | 
`public virtual override ` [`LinkSignatureProvider`](AnchorLinkSharp--LinkSignatureProvider.md)` ` [`MakeSignatureProvider`](#class_anchor_link_sharp_1_1_link_channel_session_1a58701db8173ae17a7f6dc5d10b5a07f2)`()` | 
`public virtual override async Task< ` [`TransactResult`](AnchorLinkSharp--TransactResult.md)` > ` [`Transact`](#class_anchor_link_sharp_1_1_link_channel_session_1a397043797e66dbe522d629d3f6d9c03c)`(` [`TransactArgs`](AnchorLinkSharp--TransactArgs.md)` args, ` [`TransactOptions`](AnchorLinkSharp--TransactOptions.md)` options)` | 
`public virtual override ` [`SerializedLinkSession`](AnchorLinkSharp--SerializedLinkSession.md)` ` [`Serialize`](#class_anchor_link_sharp_1_1_link_channel_session_1ae1257a731a7a371b5ea948a9aec66ebb)`()` | 
`public void ` [`OnSessionRequest`](#class_anchor_link_sharp_1_1_link_channel_session_1a29117d56b61602129466fa858b9810bd)`(` [`LinkSession`](AnchorLinkSharp--LinkSession.md)` session, ` [`SigningRequest`](EosioSigningRequest--SigningRequest.md)` request, object cancel)` | 
`private readonly Timer ` [`_timeoutTimer`](#class_anchor_link_sharp_1_1_link_channel_session_1aec27ec5582d418e91eded422e6b1eb04)`= new Timer()` | 
`private readonly ` [`ChannelInfo`](AnchorLinkSharp--ChannelInfo.md)` ` [`_channel`](#class_anchor_link_sharp_1_1_link_channel_session_1a4731b265f658311f52f7b90cca76ef00) | 
`private readonly int ` [`_timeout`](#class_anchor_link_sharp_1_1_link_channel_session_1a454e8b462819b572e30ebeb9f6ddbce0)`= 2 * 60 * 1000` | 
`private readonly Func< ` [`SigningRequest`](EosioSigningRequest--SigningRequest.md)`, byte[]> ` [`_encrypt`](#class_anchor_link_sharp_1_1_link_channel_session_1a34cbdc20b84287001f83b076061bf397) | 
`private readonly ` [`LinkChannelSessionData`](AnchorLinkSharp--LinkChannelSessionData.md)` ` [`_data`](#class_anchor_link_sharp_1_1_link_channel_session_1a55660cf814d6e480e886295f85bea33c) | 

## Members

##### `public override ` [`AnchorLink`](AnchorLinkSharp--AnchorLink.md)` ` [`AnchorLink`](#class_anchor_link_sharp_1_1_link_channel_session_1a24b28f0dba3b13e8f4a0fdaaa43dc231) 

##### `public override string ` [`Identifier`](#class_anchor_link_sharp_1_1_link_channel_session_1aa5310da6bb012937b796146745fc5ed0) 

##### `public override string ` [`PublicKey`](#class_anchor_link_sharp_1_1_link_channel_session_1ac55c0d79f35bdf0aeb50116a70d7bf55) 

##### `public override ` [`PermissionLevel`](EosSharp--Core--Api--v1--PermissionLevel.md)` ` [`Auth`](#class_anchor_link_sharp_1_1_link_channel_session_1a31159c68680d5628c3d9b5a17461e0c8) 

##### `public override Dictionary< string, object > ` [`Metadata`](#class_anchor_link_sharp_1_1_link_channel_session_1a6019b38152dde21b18ba0a443e1a9343) 

##### `public ` [`ILinkStorage`](AnchorLinkSharp.md)` ` [`Storage`](#class_anchor_link_sharp_1_1_link_channel_session_1a3198c2558a95eb66553955ab4b579438) 

##### `public ` [`LinkChannelSession`](#class_anchor_link_sharp_1_1_link_channel_session_1a38b43400852a044907e80c9790f5a310)`(` [`AnchorLink`](AnchorLinkSharp--AnchorLink.md)` anchorLink, ` [`LinkChannelSessionData`](AnchorLinkSharp--LinkChannelSessionData.md)` data, Dictionary< string, object > metadata)` 

##### `public void ` [`OnSuccess`](#class_anchor_link_sharp_1_1_link_channel_session_1ae42c87a32bf9bfaf937e577cecc1292a)`(` [`SigningRequest`](EosioSigningRequest--SigningRequest.md)` request, ` [`TransactResult`](AnchorLinkSharp--TransactResult.md)` result)` 

##### `public void ` [`OnFailure`](#class_anchor_link_sharp_1_1_link_channel_session_1a2881a07d943ba812c2ec609b33efd401)`(` [`SigningRequest`](EosioSigningRequest--SigningRequest.md)` request, Exception exception)` 

##### `public async void ` [`OnRequest`](#class_anchor_link_sharp_1_1_link_channel_session_1a2a447f06a5957b27add17fe4bd4992a1)`(` [`SigningRequest`](EosioSigningRequest--SigningRequest.md)` request, ` [`Action`](EosSharp--Core--Api--v1--Action.md)`< object > cancel)` 

##### `public async Task< ` [`SigningRequest`](EosioSigningRequest--SigningRequest.md)` > ` [`Prepare`](#class_anchor_link_sharp_1_1_link_channel_session_1a2ba24fa9a86412c68780ae3157322251)`(` [`SigningRequest`](EosioSigningRequest--SigningRequest.md)` request, ` [`LinkSession`](AnchorLinkSharp--LinkSession.md)` session)` 

##### `public void ` [`ShowLoading`](#class_anchor_link_sharp_1_1_link_channel_session_1a832760a5318046c0e28d3c99f9a71fa7)`()` 

##### `public virtual override ` [`LinkSignatureProvider`](AnchorLinkSharp--LinkSignatureProvider.md)` ` [`MakeSignatureProvider`](#class_anchor_link_sharp_1_1_link_channel_session_1a58701db8173ae17a7f6dc5d10b5a07f2)`()` 

##### `public virtual override async Task< ` [`TransactResult`](AnchorLinkSharp--TransactResult.md)` > ` [`Transact`](#class_anchor_link_sharp_1_1_link_channel_session_1a397043797e66dbe522d629d3f6d9c03c)`(` [`TransactArgs`](AnchorLinkSharp--TransactArgs.md)` args, ` [`TransactOptions`](AnchorLinkSharp--TransactOptions.md)` options)` 

##### `public virtual override ` [`SerializedLinkSession`](AnchorLinkSharp--SerializedLinkSession.md)` ` [`Serialize`](#class_anchor_link_sharp_1_1_link_channel_session_1ae1257a731a7a371b5ea948a9aec66ebb)`()` 

##### `public void ` [`OnSessionRequest`](#class_anchor_link_sharp_1_1_link_channel_session_1a29117d56b61602129466fa858b9810bd)`(` [`LinkSession`](AnchorLinkSharp--LinkSession.md)` session, ` [`SigningRequest`](EosioSigningRequest--SigningRequest.md)` request, object cancel)` 

##### `private readonly Timer ` [`_timeoutTimer`](#class_anchor_link_sharp_1_1_link_channel_session_1aec27ec5582d418e91eded422e6b1eb04)`= new Timer()` 

##### `private readonly ` [`ChannelInfo`](AnchorLinkSharp--ChannelInfo.md)` ` [`_channel`](#class_anchor_link_sharp_1_1_link_channel_session_1a4731b265f658311f52f7b90cca76ef00) 

##### `private readonly int ` [`_timeout`](#class_anchor_link_sharp_1_1_link_channel_session_1a454e8b462819b572e30ebeb9f6ddbce0)`= 2 * 60 * 1000` 

##### `private readonly Func< ` [`SigningRequest`](EosioSigningRequest--SigningRequest.md)`, byte[]> ` [`_encrypt`](#class_anchor_link_sharp_1_1_link_channel_session_1a34cbdc20b84287001f83b076061bf397) 

##### `private readonly ` [`LinkChannelSessionData`](AnchorLinkSharp--LinkChannelSessionData.md)` ` [`_data`](#class_anchor_link_sharp_1_1_link_channel_session_1a55660cf814d6e480e886295f85bea33c) 

