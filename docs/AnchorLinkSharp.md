# namespace `AnchorLinkSharp` 

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`enum ` [`LinkErrorCode`](#namespace_anchor_link_sharp_1a92a85044068cecc9fbc18797e0626208)            | 
`class ` [`AnchorLink`](AnchorLinkSharp--AnchorLink.md) | Main class
`class ` [`CancelException`](AnchorLinkSharp--CancelException.md) | Error that is thrown if a [[LinkTransport]] cancels a request.
`class ` [`ChannelInfo`](AnchorLinkSharp--ChannelInfo.md) | 
`class ` [`Defaults`](AnchorLinkSharp--Defaults.md) | 
`class ` [`IdentifyResult`](AnchorLinkSharp--IdentifyResult.md) | The result of a [[AnchorLink.identify]] call.
`class ` [`IdentityException`](AnchorLinkSharp--IdentityException.md) | Error that is thrown if an identity request fails to verify.
`class ` [`LinkAbiData`](AnchorLinkSharp--LinkAbiData.md) | 
`class ` [`LinkCallback`](AnchorLinkSharp--LinkCallback.md) | 
`class ` [`LinkChannelSession`](AnchorLinkSharp--LinkChannelSession.md) | AnchorLink session that pushes requests over a channel.
`class ` [`LinkChannelSessionData`](AnchorLinkSharp--LinkChannelSessionData.md) | 
`class ` [`LinkConstants`](AnchorLinkSharp--LinkConstants.md) | 
`class ` [`LinkCreate`](AnchorLinkSharp--LinkCreate.md) | 
`class ` [`LinkException`](AnchorLinkSharp--LinkException.md) | Error codes. Accessible using the `code` property on errors thrown by [[AnchorLink]] and [[LinkSession]].
`class ` [`LinkFallbackSession`](AnchorLinkSharp--LinkFallbackSession.md) | AnchorLink session that sends every request over the transport.
`class ` [`LinkFallbackSessionData`](AnchorLinkSharp--LinkFallbackSessionData.md) | 
`class ` [`LinkInfo`](AnchorLinkSharp--LinkInfo.md) | 
`class ` [`LinkOptions`](AnchorLinkSharp--LinkOptions.md) | 
`class ` [`LinkSession`](AnchorLinkSharp--LinkSession.md) | Type describing a anchorLink session that can create a eosjs compatible signature provider and transact for a specific auth.
`class ` [`LinkSessionDataBase`](AnchorLinkSharp--LinkSessionDataBase.md) | 
`class ` [`LinkSessionDataConverter`](AnchorLinkSharp--LinkSessionDataConverter.md) | 
`class ` [`LinkSignatureProvider`](AnchorLinkSharp--LinkSignatureProvider.md) | 
`class ` [`LinkSignatureProviderArgs`](AnchorLinkSharp--LinkSignatureProviderArgs.md) | 
`class ` [`LinkUtils`](AnchorLinkSharp--LinkUtils.md) | 
`class ` [`LoginResult`](AnchorLinkSharp--LoginResult.md) | The result of a [[AnchorLink.login]] call.
`class ` [`SealedMessage`](AnchorLinkSharp--SealedMessage.md) | 
`class ` [`SerializedLinkSession`](AnchorLinkSharp--SerializedLinkSession.md) | 
`class ` [`SessionException`](AnchorLinkSharp--SessionException.md) | Error originating from a [[LinkSession]].
`class ` [`TransactArgs`](AnchorLinkSharp--TransactArgs.md) | Payload accepted by the [[AnchorLink.transact]] method. Note that one of `action`, `actions` or `transaction` must be set.
`class ` [`TransactOptions`](AnchorLinkSharp--TransactOptions.md) | Options for the [[AnchorLink.transact]] method.
`class ` [`TransactResult`](AnchorLinkSharp--TransactResult.md) | The result of a [[AnchorLink.transact]] call.
`class ` [`WebSocketWrapper`](AnchorLinkSharp--WebSocketWrapper.md) | 
`interface ` [`ILinkOptions`](#interface_anchor_link_sharp_1_1_i_link_options) | Available options when creating a new [[AnchorLink]] instance.
`interface ` [`ILinkStorage`](#interface_anchor_link_sharp_1_1_i_link_storage) | Interface storage adapters should implement.
`interface ` [`ILinkTransport`](#interface_anchor_link_sharp_1_1_i_link_transport) | Protocol anchorLink transports need to implement. A transport is responsible for getting the request to the user, e.g. by opening request URIs or displaying QR codes.

## Members

##### `enum ` [`LinkErrorCode`](#namespace_anchor_link_sharp_1a92a85044068cecc9fbc18797e0626208) 

