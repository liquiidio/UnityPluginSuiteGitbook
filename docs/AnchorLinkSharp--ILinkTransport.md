# interface `AnchorLinkSharp::ILinkTransport` 

Protocol anchorLink transports need to implement. A transport is responsible for getting the request to the user, e.g. by opening request URIs or displaying QR codes.

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public ` [`ILinkStorage`](.github/workflows/documentation/md/AnchorLinkSharp.md#interface_anchor_link_sharp_1_1_i_link_storage)` ` [`Storage`](.github/workflows/documentation/md/AnchorLinkSharp.md#interface_anchor_link_sharp_1_1_i_link_transport_1a3198c2558a95eb66553955ab4b579438) | Can be implemented if transport provides a storage as well.
`public void ` [`OnRequest`](.github/workflows/documentation/md/AnchorLinkSharp.md#interface_anchor_link_sharp_1_1_i_link_transport_1af033a491264433deccf8f379377bf0de)`(SigningRequest request, Action< object > cancel)` | Present a signing request to the user.
`public void ` [`OnSuccess`](.github/workflows/documentation/md/AnchorLinkSharp.md#interface_anchor_link_sharp_1_1_i_link_transport_1ae42c87a32bf9bfaf937e577cecc1292a)`(SigningRequest request, ` [`TransactResult`](.github/workflows/documentation/md/AnchorLinkSharp--TransactResult.md#class_anchor_link_sharp_1_1_transact_result)` result)` | Called if the request was successful.
`public void ` [`OnFailure`](.github/workflows/documentation/md/AnchorLinkSharp.md#interface_anchor_link_sharp_1_1_i_link_transport_1a2881a07d943ba812c2ec609b33efd401)`(SigningRequest request, Exception exception)` | Called if the request failed.
`public void ` [`OnSessionRequest`](.github/workflows/documentation/md/AnchorLinkSharp.md#interface_anchor_link_sharp_1_1_i_link_transport_1ab43ebe78aa7d484d52f5d1f80e8a0e74)`(` [`LinkSession`](.github/workflows/documentation/md/AnchorLinkSharp--LinkSession.md#class_anchor_link_sharp_1_1_link_session)` session, SigningRequest request, Action< object > cancel)` | Called when a session request is initiated.
`public Task< SigningRequest > ` [`Prepare`](.github/workflows/documentation/md/AnchorLinkSharp.md#interface_anchor_link_sharp_1_1_i_link_transport_1a4cf59f297378d8bf8b50556182625565)`(SigningRequest request, ` [`LinkSession`](.github/workflows/documentation/md/AnchorLinkSharp--LinkSession.md#class_anchor_link_sharp_1_1_link_session)` session)` | Can be implemented to modify request just after it has been created.
`public void ` [`ShowLoading`](.github/workflows/documentation/md/AnchorLinkSharp.md#interface_anchor_link_sharp_1_1_i_link_transport_1a832760a5318046c0e28d3c99f9a71fa7)`()` | Called immediately when the transaction starts

## Members

##### `public ` [`ILinkStorage`](.github/workflows/documentation/md/AnchorLinkSharp.md#interface_anchor_link_sharp_1_1_i_link_storage)` ` [`Storage`](.github/workflows/documentation/md/AnchorLinkSharp.md#interface_anchor_link_sharp_1_1_i_link_transport_1a3198c2558a95eb66553955ab4b579438) 

Can be implemented if transport provides a storage as well.

##### `public void ` [`OnRequest`](.github/workflows/documentation/md/AnchorLinkSharp.md#interface_anchor_link_sharp_1_1_i_link_transport_1af033a491264433deccf8f379377bf0de)`(SigningRequest request, Action< object > cancel)` 

Present a signing request to the user. 
#### Parameters
* `request` The signing request. 

* `cancel` Can be called to abort the request.

##### `public void ` [`OnSuccess`](.github/workflows/documentation/md/AnchorLinkSharp.md#interface_anchor_link_sharp_1_1_i_link_transport_1ae42c87a32bf9bfaf937e577cecc1292a)`(SigningRequest request, ` [`TransactResult`](.github/workflows/documentation/md/AnchorLinkSharp--TransactResult.md#class_anchor_link_sharp_1_1_transact_result)` result)` 

Called if the request was successful.

##### `public void ` [`OnFailure`](.github/workflows/documentation/md/AnchorLinkSharp.md#interface_anchor_link_sharp_1_1_i_link_transport_1a2881a07d943ba812c2ec609b33efd401)`(SigningRequest request, Exception exception)` 

Called if the request failed.

##### `public void ` [`OnSessionRequest`](.github/workflows/documentation/md/AnchorLinkSharp.md#interface_anchor_link_sharp_1_1_i_link_transport_1ab43ebe78aa7d484d52f5d1f80e8a0e74)`(` [`LinkSession`](.github/workflows/documentation/md/AnchorLinkSharp--LinkSession.md#class_anchor_link_sharp_1_1_link_session)` session, SigningRequest request, Action< object > cancel)` 

Called when a session request is initiated. 
#### Parameters
* `session` Session where the request originated. 

* `request` Signing request that will be sent over the session.

##### `public Task< SigningRequest > ` [`Prepare`](.github/workflows/documentation/md/AnchorLinkSharp.md#interface_anchor_link_sharp_1_1_i_link_transport_1a4cf59f297378d8bf8b50556182625565)`(SigningRequest request, ` [`LinkSession`](.github/workflows/documentation/md/AnchorLinkSharp--LinkSession.md#class_anchor_link_sharp_1_1_link_session)` session)` 

Can be implemented to modify request just after it has been created.

##### `public void ` [`ShowLoading`](.github/workflows/documentation/md/AnchorLinkSharp.md#interface_anchor_link_sharp_1_1_i_link_transport_1a832760a5318046c0e28d3c99f9a71fa7)`()` 

Called immediately when the transaction starts

