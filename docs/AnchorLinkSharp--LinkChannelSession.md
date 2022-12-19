# class `AnchorLinkSharp::LinkChannelSession` 

```
class AnchorLinkSharp::LinkChannelSession
  : public LinkSession
  : public ILinkTransport
```

AnchorLink session that pushes requests over a channel.

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public override `[`AnchorLink`](.github/workflows/documentation/md/AnchorLinkSharp--AnchorLink.md#class_anchor_link_sharp_1_1_anchor_link)` `[`AnchorLink`](#class_anchor_link_sharp_1_1_link_channel_session_1a24b28f0dba3b13e8f4a0fdaaa43dc231) | 
`public override string `[`Identifier`](#class_anchor_link_sharp_1_1_link_channel_session_1aa5310da6bb012937b796146745fc5ed0) | 
`public override string `[`PublicKey`](#class_anchor_link_sharp_1_1_link_channel_session_1ac55c0d79f35bdf0aeb50116a70d7bf55) | 
`public override PermissionLevel `[`Auth`](#class_anchor_link_sharp_1_1_link_channel_session_1a31159c68680d5628c3d9b5a17461e0c8) | 
`public override Dictionary< string, object > `[`Metadata`](#class_anchor_link_sharp_1_1_link_channel_session_1a6019b38152dde21b18ba0a443e1a9343) | 
`public `[`ILinkStorage`](.github/workflows/documentation/md/AnchorLinkSharp.md#interface_anchor_link_sharp_1_1_i_link_storage)` `[`Storage`](#class_anchor_link_sharp_1_1_link_channel_session_1a3198c2558a95eb66553955ab4b579438) | 
`public  `[`LinkChannelSession`](#class_anchor_link_sharp_1_1_link_channel_session_1a38b43400852a044907e80c9790f5a310)`(`[`AnchorLink`](.github/workflows/documentation/md/AnchorLinkSharp--AnchorLink.md#class_anchor_link_sharp_1_1_anchor_link)` anchorLink, `[`LinkChannelSessionData`](.github/workflows/documentation/md/AnchorLinkSharp--LinkChannelSessionData.md#class_anchor_link_sharp_1_1_link_channel_session_data)` data, Dictionary< string, object > metadata)` | 
`public void `[`OnSuccess`](#class_anchor_link_sharp_1_1_link_channel_session_1ae42c87a32bf9bfaf937e577cecc1292a)`(SigningRequest request, `[`TransactResult`](.github/workflows/documentation/md/AnchorLinkSharp--TransactResult.md#class_anchor_link_sharp_1_1_transact_result)` result)` | 
`public void `[`OnFailure`](#class_anchor_link_sharp_1_1_link_channel_session_1a2881a07d943ba812c2ec609b33efd401)`(SigningRequest request, Exception exception)` | 
`public async void `[`OnRequest`](#class_anchor_link_sharp_1_1_link_channel_session_1a2a447f06a5957b27add17fe4bd4992a1)`(SigningRequest request, Action< object > cancel)` | 
`public async Task< SigningRequest > `[`Prepare`](#class_anchor_link_sharp_1_1_link_channel_session_1a2ba24fa9a86412c68780ae3157322251)`(SigningRequest request, `[`LinkSession`](.github/workflows/documentation/md/AnchorLinkSharp--LinkSession.md#class_anchor_link_sharp_1_1_link_session)` session)` | 
`public void `[`ShowLoading`](#class_anchor_link_sharp_1_1_link_channel_session_1a832760a5318046c0e28d3c99f9a71fa7)`()` | 
`public virtual override LinkSignatureProvider `[`MakeSignatureProvider`](#class_anchor_link_sharp_1_1_link_channel_session_1a58701db8173ae17a7f6dc5d10b5a07f2)`()` | 
`public virtual override async Task< `[`TransactResult`](.github/workflows/documentation/md/AnchorLinkSharp--TransactResult.md#class_anchor_link_sharp_1_1_transact_result)` > `[`Transact`](#class_anchor_link_sharp_1_1_link_channel_session_1a397043797e66dbe522d629d3f6d9c03c)`(`[`TransactArgs`](.github/workflows/documentation/md/AnchorLinkSharp--TransactArgs.md#class_anchor_link_sharp_1_1_transact_args)` args, `[`TransactOptions`](.github/workflows/documentation/md/AnchorLinkSharp--TransactOptions.md#class_anchor_link_sharp_1_1_transact_options)` options)` | 
`public virtual override `[`SerializedLinkSession`](.github/workflows/documentation/md/AnchorLinkSharp--SerializedLinkSession.md#class_anchor_link_sharp_1_1_serialized_link_session)` `[`Serialize`](#class_anchor_link_sharp_1_1_link_channel_session_1ae1257a731a7a371b5ea948a9aec66ebb)`()` | 
`public void `[`OnSessionRequest`](#class_anchor_link_sharp_1_1_link_channel_session_1ab43ebe78aa7d484d52f5d1f80e8a0e74)`(`[`LinkSession`](.github/workflows/documentation/md/AnchorLinkSharp--LinkSession.md#class_anchor_link_sharp_1_1_link_session)` session, SigningRequest request, Action< object > cancel)` | 
`private readonly Timer `[`_timeoutTimer`](#class_anchor_link_sharp_1_1_link_channel_session_1aec27ec5582d418e91eded422e6b1eb04) | 
`private readonly `[`ChannelInfo`](.github/workflows/documentation/md/AnchorLinkSharp--ChannelInfo.md#class_anchor_link_sharp_1_1_channel_info)` `[`_channel`](#class_anchor_link_sharp_1_1_link_channel_session_1a4731b265f658311f52f7b90cca76ef00) | 
`private readonly int `[`_timeout`](#class_anchor_link_sharp_1_1_link_channel_session_1a454e8b462819b572e30ebeb9f6ddbce0) | 
`private readonly Func< SigningRequest, byte[]> `[`_encrypt`](#class_anchor_link_sharp_1_1_link_channel_session_1a34cbdc20b84287001f83b076061bf397) | 
`private readonly `[`LinkChannelSessionData`](.github/workflows/documentation/md/AnchorLinkSharp--LinkChannelSessionData.md#class_anchor_link_sharp_1_1_link_channel_session_data)` `[`_data`](#class_anchor_link_sharp_1_1_link_channel_session_1a55660cf814d6e480e886295f85bea33c) | 

## Members

### `public override `[`AnchorLink`](.github/workflows/documentation/md/AnchorLinkSharp--AnchorLink.md#class_anchor_link_sharp_1_1_anchor_link)` `[`AnchorLink`](#class_anchor_link_sharp_1_1_link_channel_session_1a24b28f0dba3b13e8f4a0fdaaa43dc231) 

### `public override string `[`Identifier`](#class_anchor_link_sharp_1_1_link_channel_session_1aa5310da6bb012937b796146745fc5ed0) 

### `public override string `[`PublicKey`](#class_anchor_link_sharp_1_1_link_channel_session_1ac55c0d79f35bdf0aeb50116a70d7bf55) 

### `public override PermissionLevel `[`Auth`](#class_anchor_link_sharp_1_1_link_channel_session_1a31159c68680d5628c3d9b5a17461e0c8) 

### `public override Dictionary< string, object > `[`Metadata`](#class_anchor_link_sharp_1_1_link_channel_session_1a6019b38152dde21b18ba0a443e1a9343) 

### `public `[`ILinkStorage`](.github/workflows/documentation/md/AnchorLinkSharp.md#interface_anchor_link_sharp_1_1_i_link_storage)` `[`Storage`](#class_anchor_link_sharp_1_1_link_channel_session_1a3198c2558a95eb66553955ab4b579438) 

### `public  `[`LinkChannelSession`](#class_anchor_link_sharp_1_1_link_channel_session_1a38b43400852a044907e80c9790f5a310)`(`[`AnchorLink`](.github/workflows/documentation/md/AnchorLinkSharp--AnchorLink.md#class_anchor_link_sharp_1_1_anchor_link)` anchorLink, `[`LinkChannelSessionData`](.github/workflows/documentation/md/AnchorLinkSharp--LinkChannelSessionData.md#class_anchor_link_sharp_1_1_link_channel_session_data)` data, Dictionary< string, object > metadata)` 

### `public void `[`OnSuccess`](#class_anchor_link_sharp_1_1_link_channel_session_1ae42c87a32bf9bfaf937e577cecc1292a)`(SigningRequest request, `[`TransactResult`](.github/workflows/documentation/md/AnchorLinkSharp--TransactResult.md#class_anchor_link_sharp_1_1_transact_result)` result)` 

### `public void `[`OnFailure`](#class_anchor_link_sharp_1_1_link_channel_session_1a2881a07d943ba812c2ec609b33efd401)`(SigningRequest request, Exception exception)` 

### `public async void `[`OnRequest`](#class_anchor_link_sharp_1_1_link_channel_session_1a2a447f06a5957b27add17fe4bd4992a1)`(SigningRequest request, Action< object > cancel)` 

### `public async Task< SigningRequest > `[`Prepare`](#class_anchor_link_sharp_1_1_link_channel_session_1a2ba24fa9a86412c68780ae3157322251)`(SigningRequest request, `[`LinkSession`](.github/workflows/documentation/md/AnchorLinkSharp--LinkSession.md#class_anchor_link_sharp_1_1_link_session)` session)` 

### `public void `[`ShowLoading`](#class_anchor_link_sharp_1_1_link_channel_session_1a832760a5318046c0e28d3c99f9a71fa7)`()` 

### `public virtual override LinkSignatureProvider `[`MakeSignatureProvider`](#class_anchor_link_sharp_1_1_link_channel_session_1a58701db8173ae17a7f6dc5d10b5a07f2)`()` 

### `public virtual override async Task< `[`TransactResult`](.github/workflows/documentation/md/AnchorLinkSharp--TransactResult.md#class_anchor_link_sharp_1_1_transact_result)` > `[`Transact`](#class_anchor_link_sharp_1_1_link_channel_session_1a397043797e66dbe522d629d3f6d9c03c)`(`[`TransactArgs`](.github/workflows/documentation/md/AnchorLinkSharp--TransactArgs.md#class_anchor_link_sharp_1_1_transact_args)` args, `[`TransactOptions`](.github/workflows/documentation/md/AnchorLinkSharp--TransactOptions.md#class_anchor_link_sharp_1_1_transact_options)` options)` 

### `public virtual override `[`SerializedLinkSession`](.github/workflows/documentation/md/AnchorLinkSharp--SerializedLinkSession.md#class_anchor_link_sharp_1_1_serialized_link_session)` `[`Serialize`](#class_anchor_link_sharp_1_1_link_channel_session_1ae1257a731a7a371b5ea948a9aec66ebb)`()` 

### `public void `[`OnSessionRequest`](#class_anchor_link_sharp_1_1_link_channel_session_1ab43ebe78aa7d484d52f5d1f80e8a0e74)`(`[`LinkSession`](.github/workflows/documentation/md/AnchorLinkSharp--LinkSession.md#class_anchor_link_sharp_1_1_link_session)` session, SigningRequest request, Action< object > cancel)` 

### `private readonly Timer `[`_timeoutTimer`](#class_anchor_link_sharp_1_1_link_channel_session_1aec27ec5582d418e91eded422e6b1eb04) 

### `private readonly `[`ChannelInfo`](.github/workflows/documentation/md/AnchorLinkSharp--ChannelInfo.md#class_anchor_link_sharp_1_1_channel_info)` `[`_channel`](#class_anchor_link_sharp_1_1_link_channel_session_1a4731b265f658311f52f7b90cca76ef00) 

### `private readonly int `[`_timeout`](#class_anchor_link_sharp_1_1_link_channel_session_1a454e8b462819b572e30ebeb9f6ddbce0) 

### `private readonly Func< SigningRequest, byte[]> `[`_encrypt`](#class_anchor_link_sharp_1_1_link_channel_session_1a34cbdc20b84287001f83b076061bf397) 

### `private readonly `[`LinkChannelSessionData`](.github/workflows/documentation/md/AnchorLinkSharp--LinkChannelSessionData.md#class_anchor_link_sharp_1_1_link_channel_session_data)` `[`_data`](#class_anchor_link_sharp_1_1_link_channel_session_1a55660cf814d6e480e886295f85bea33c) 

