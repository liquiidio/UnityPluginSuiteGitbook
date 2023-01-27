# interface `AnchorLinkSharp::ILinkTransport` 

Protocol anchorLink transports need to implement. A transport is responsible for getting the request to the user, e.g. by opening request URIs or displaying QR codes.

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public ` [`ILinkStorage`](AnchorLinkSharp.md)` ` [`Storage`](AnchorLinkSharp.md) | Can be implemented if transport provides a storage as well.
`public void ` [`OnRequest`](AnchorLinkSharp.md)`(` [`SigningRequest`](EosioSigningRequest--SigningRequest.md)` request, ` [`Action`](#_anchor_example_panel_8cs_1a24e91c56095a0673d92c6eac6e069a3c)`< object > cancel)` | Present a signing request to the user.
`public void ` [`OnSuccess`](AnchorLinkSharp.md)`(` [`SigningRequest`](EosioSigningRequest--SigningRequest.md)` request, ` [`TransactResult`](AnchorLinkSharp--TransactResult.md)` result)` | Called if the request was successful.
`public void ` [`OnFailure`](AnchorLinkSharp.md)`(` [`SigningRequest`](EosioSigningRequest--SigningRequest.md)` request, Exception exception)` | Called if the request failed.
`public void ` [`OnSessionRequest`](AnchorLinkSharp.md)`(` [`LinkSession`](AnchorLinkSharp--LinkSession.md)` session, ` [`SigningRequest`](EosioSigningRequest--SigningRequest.md)` request, ` [`Action`](#_anchor_example_panel_8cs_1a24e91c56095a0673d92c6eac6e069a3c)`< object > cancel)` | Called when a session request is initiated.
`public Task< ` [`SigningRequest`](EosioSigningRequest--SigningRequest.md)` > ` [`Prepare`](AnchorLinkSharp.md)`(` [`SigningRequest`](EosioSigningRequest--SigningRequest.md)` request, ` [`LinkSession`](AnchorLinkSharp--LinkSession.md)` session)` | Can be implemented to modify request just after it has been created.
`public void ` [`ShowLoading`](AnchorLinkSharp.md)`()` | Called immediately when the transaction starts

## Members

##### `public ` [`ILinkStorage`](AnchorLinkSharp.md)` ` [`Storage`](AnchorLinkSharp.md) 

Can be implemented if transport provides a storage as well.

##### `public void ` [`OnRequest`](AnchorLinkSharp.md)`(` [`SigningRequest`](EosioSigningRequest--SigningRequest.md)` request, ` [`Action`](#_anchor_example_panel_8cs_1a24e91c56095a0673d92c6eac6e069a3c)`< object > cancel)` 

Present a signing request to the user. 
#### Parameters
* `request` The signing request. 

* `cancel` Can be called to abort the request.

##### `public void ` [`OnSuccess`](AnchorLinkSharp.md)`(` [`SigningRequest`](EosioSigningRequest--SigningRequest.md)` request, ` [`TransactResult`](AnchorLinkSharp--TransactResult.md)` result)` 

Called if the request was successful.

##### `public void ` [`OnFailure`](AnchorLinkSharp.md)`(` [`SigningRequest`](EosioSigningRequest--SigningRequest.md)` request, Exception exception)` 

Called if the request failed.

##### `public void ` [`OnSessionRequest`](AnchorLinkSharp.md)`(` [`LinkSession`](AnchorLinkSharp--LinkSession.md)` session, ` [`SigningRequest`](EosioSigningRequest--SigningRequest.md)` request, ` [`Action`](#_anchor_example_panel_8cs_1a24e91c56095a0673d92c6eac6e069a3c)`< object > cancel)` 

Called when a session request is initiated. 
#### Parameters
* `session` Session where the request originated. 

* `request` Signing request that will be sent over the session.

##### `public Task< ` [`SigningRequest`](EosioSigningRequest--SigningRequest.md)` > ` [`Prepare`](AnchorLinkSharp.md)`(` [`SigningRequest`](EosioSigningRequest--SigningRequest.md)` request, ` [`LinkSession`](AnchorLinkSharp--LinkSession.md)` session)` 

Can be implemented to modify request just after it has been created.

##### `public void ` [`ShowLoading`](AnchorLinkSharp.md)`()` 

Called immediately when the transaction starts

