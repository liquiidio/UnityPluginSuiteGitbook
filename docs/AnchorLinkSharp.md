# namespace `AnchorLinkSharp` 

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`enum ` [`LinkErrorCode`](#namespace_anchor_link_sharp_1a92a85044068cecc9fbc18797e0626208)            | 
`class ` [`AnchorLink`](.github/workflows/documentation/md/AnchorLinkSharp--AnchorLink.md#class_anchor_link_sharp_1_1_anchor_link) | Main class
`class ` [`CancelException`](.github/workflows/documentation/md/AnchorLinkSharp--CancelException.md#class_anchor_link_sharp_1_1_cancel_exception) | Error that is thrown if a [[LinkTransport]] cancels a request.
`class ` [`ChannelInfo`](.github/workflows/documentation/md/AnchorLinkSharp--ChannelInfo.md#class_anchor_link_sharp_1_1_channel_info) | 
`class ` [`Defaults`](.github/workflows/documentation/md/AnchorLinkSharp--Defaults.md#class_anchor_link_sharp_1_1_defaults) | 
`class ` [`IdentifyResult`](.github/workflows/documentation/md/AnchorLinkSharp--IdentifyResult.md#class_anchor_link_sharp_1_1_identify_result) | The result of a [[AnchorLink.identify]] call.
`class ` [`IdentityException`](.github/workflows/documentation/md/AnchorLinkSharp--IdentityException.md#class_anchor_link_sharp_1_1_identity_exception) | Error that is thrown if an identity request fails to verify.
`class ` [`LinkAbiData`](.github/workflows/documentation/md/AnchorLinkSharp--LinkAbiData.md#class_anchor_link_sharp_1_1_link_abi_data) | 
`class ` [`LinkCallback`](.github/workflows/documentation/md/AnchorLinkSharp--LinkCallback.md#class_anchor_link_sharp_1_1_link_callback) | 
`class ` [`LinkChannelSession`](.github/workflows/documentation/md/AnchorLinkSharp--LinkChannelSession.md#class_anchor_link_sharp_1_1_link_channel_session) | AnchorLink session that pushes requests over a channel.
`class ` [`LinkChannelSessionData`](.github/workflows/documentation/md/AnchorLinkSharp--LinkChannelSessionData.md#class_anchor_link_sharp_1_1_link_channel_session_data) | 
`class ` [`LinkConstants`](.github/workflows/documentation/md/AnchorLinkSharp--LinkConstants.md#class_anchor_link_sharp_1_1_link_constants) | 
`class ` [`LinkCreate`](.github/workflows/documentation/md/AnchorLinkSharp--LinkCreate.md#class_anchor_link_sharp_1_1_link_create) | 
`class ` [`LinkException`](.github/workflows/documentation/md/AnchorLinkSharp--LinkException.md#class_anchor_link_sharp_1_1_link_exception) | Error codes. Accessible using the `code` property on errors thrown by [[AnchorLink]] and [[LinkSession]].
`class ` [`LinkFallbackSession`](.github/workflows/documentation/md/AnchorLinkSharp--LinkFallbackSession.md#class_anchor_link_sharp_1_1_link_fallback_session) | AnchorLink session that sends every request over the transport.
`class ` [`LinkFallbackSessionData`](.github/workflows/documentation/md/AnchorLinkSharp--LinkFallbackSessionData.md#class_anchor_link_sharp_1_1_link_fallback_session_data) | 
`class ` [`LinkInfo`](.github/workflows/documentation/md/AnchorLinkSharp--LinkInfo.md#class_anchor_link_sharp_1_1_link_info) | 
`class ` [`LinkOptions`](.github/workflows/documentation/md/AnchorLinkSharp--LinkOptions.md#class_anchor_link_sharp_1_1_link_options) | 
`class ` [`LinkSession`](.github/workflows/documentation/md/AnchorLinkSharp--LinkSession.md#class_anchor_link_sharp_1_1_link_session) | Type describing a anchorLink session that can create a eosjs compatible signature provider and transact for a specific auth.
`class ` [`LinkSessionDataBase`](.github/workflows/documentation/md/AnchorLinkSharp--LinkSessionDataBase.md#class_anchor_link_sharp_1_1_link_session_data_base) | 
`class ` [`LinkSessionDataConverter`](.github/workflows/documentation/md/AnchorLinkSharp--LinkSessionDataConverter.md#class_anchor_link_sharp_1_1_link_session_data_converter) | 
`class ` [`LinkSignatureProvider`](.github/workflows/documentation/md/AnchorLinkSharp--LinkSignatureProvider.md#class_anchor_link_sharp_1_1_link_signature_provider) | 
`class ` [`LinkSignatureProviderArgs`](.github/workflows/documentation/md/AnchorLinkSharp--LinkSignatureProviderArgs.md#class_anchor_link_sharp_1_1_link_signature_provider_args) | 
`class ` [`LinkUtils`](.github/workflows/documentation/md/AnchorLinkSharp--LinkUtils.md#class_anchor_link_sharp_1_1_link_utils) | 
`class ` [`LoginResult`](.github/workflows/documentation/md/AnchorLinkSharp--LoginResult.md#class_anchor_link_sharp_1_1_login_result) | The result of a [[AnchorLink.login]] call.
`class ` [`SealedMessage`](.github/workflows/documentation/md/AnchorLinkSharp--SealedMessage.md#class_anchor_link_sharp_1_1_sealed_message) | 
`class ` [`SerializedLinkSession`](.github/workflows/documentation/md/AnchorLinkSharp--SerializedLinkSession.md#class_anchor_link_sharp_1_1_serialized_link_session) | 
`class ` [`SessionException`](.github/workflows/documentation/md/AnchorLinkSharp--SessionException.md#class_anchor_link_sharp_1_1_session_exception) | Error originating from a [[LinkSession]].
`class ` [`TransactArgs`](.github/workflows/documentation/md/AnchorLinkSharp--TransactArgs.md#class_anchor_link_sharp_1_1_transact_args) | Payload accepted by the [[AnchorLink.transact]] method. Note that one of `action`, `actions` or `transaction` must be set.
`class ` [`TransactOptions`](.github/workflows/documentation/md/AnchorLinkSharp--TransactOptions.md#class_anchor_link_sharp_1_1_transact_options) | Options for the [[AnchorLink.transact]] method.
`class ` [`TransactResult`](.github/workflows/documentation/md/AnchorLinkSharp--TransactResult.md#class_anchor_link_sharp_1_1_transact_result) | The result of a [[AnchorLink.transact]] call.
`class ` [`WebSocketWrapper`](.github/workflows/documentation/md/AnchorLinkSharp--WebSocketWrapper.md#class_anchor_link_sharp_1_1_web_socket_wrapper) | 
`interface ` [`ILinkOptions`](#interface_anchor_link_sharp_1_1_i_link_options) | Available options when creating a new [[AnchorLink]] instance.
`interface ` [`ILinkStorage`](#interface_anchor_link_sharp_1_1_i_link_storage) | Interface storage adapters should implement.
`interface ` [`ILinkTransport`](#interface_anchor_link_sharp_1_1_i_link_transport) | Protocol anchorLink transports need to implement. A transport is responsible for getting the request to the user, e.g. by opening request URIs or displaying QR codes.

## Members

##### `enum ` [`LinkErrorCode`](#namespace_anchor_link_sharp_1a92a85044068cecc9fbc18797e0626208) 

