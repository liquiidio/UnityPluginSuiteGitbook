# class `AnchorLinkTransportSharp::Src::Transports::UiToolkit::UnityUiToolkitTransport` 

```
class AnchorLinkTransportSharp::Src::Transports::UiToolkit::UnityUiToolkitTransport
  : public UnityTransport
```

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public ` [`UnityUiToolkitTransport`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_ui_toolkit_1_1_unity_ui_toolkit_transport_1a468667ee5507db327c6467647b9d2804)`(` [`TransportOptions`](AnchorLinkTransportSharp--Src--TransportOptions.md)` options)` | Transport constructor.
`public virtual override void ` [`ShowLoading`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_ui_toolkit_1_1_unity_ui_toolkit_transport_1ad07a81fbeebbad741a68a3e9b3f310e7)`()` | Method is invoked when a request is made and user signing on the wallet is required.
`public virtual override void ` [`OnSuccess`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_ui_toolkit_1_1_unity_ui_toolkit_transport_1ac36aa71aa9c9918667f60b2f046bbb4c)`(` [`SigningRequest`](EosioSigningRequest--SigningRequest.md)` request, ` [`TransactResult`](AnchorLinkSharp--TransactResult.md)` result)` | Method is invoked when a succesful signing request is completed.
`public virtual override void ` [`OnFailure`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_ui_toolkit_1_1_unity_ui_toolkit_transport_1aad0b7848de702f685a2fc45a16474a6d)`(` [`SigningRequest`](EosioSigningRequest--SigningRequest.md)` request, Exception exception)` | Method is invoked when a signing request fails or is cancelled.
`public virtual override void ` [`DisplayRequest`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_ui_toolkit_1_1_unity_ui_toolkit_transport_1aba60c11e2c8b926bea5109f4230a2a92)`(` [`SigningRequest`](EosioSigningRequest--SigningRequest.md)` request)` | Method is invoked when a request to sign or login is made and the QR code and link are generated and displayed.
`private void ` [`CheckTheme`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_ui_toolkit_1_1_unity_ui_toolkit_transport_1a7bd8080ab3f19f9ace4cd6b317930bae)`()` | check which theme to use (light and dark)

## Members

##### `public ` [`UnityUiToolkitTransport`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_ui_toolkit_1_1_unity_ui_toolkit_transport_1a468667ee5507db327c6467647b9d2804)`(` [`TransportOptions`](AnchorLinkTransportSharp--Src--TransportOptions.md)` options)` 

Transport constructor.

#### Parameters
* `options`

##### `public virtual override void ` [`ShowLoading`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_ui_toolkit_1_1_unity_ui_toolkit_transport_1ad07a81fbeebbad741a68a3e9b3f310e7)`()` 

Method is invoked when a request is made and user signing on the wallet is required.

Refer to [https://github.com/greymass/anchor-link-browser-transport/blob/master/src/index.ts#L361](https://github.com/greymass/anchor-link-browser-transport/blob/master/src/index.ts#L361).

##### `public virtual override void ` [`OnSuccess`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_ui_toolkit_1_1_unity_ui_toolkit_transport_1ac36aa71aa9c9918667f60b2f046bbb4c)`(` [`SigningRequest`](EosioSigningRequest--SigningRequest.md)` request, ` [`TransactResult`](AnchorLinkSharp--TransactResult.md)` result)` 

Method is invoked when a succesful signing request is completed.

Refer to [https://github.com/greymass/anchor-link-browser-transport/blob/master/src/index.ts#L680](https://github.com/greymass/anchor-link-browser-transport/blob/master/src/index.ts#L680).

#### Parameters
* `request` />

* `result`

##### `public virtual override void ` [`OnFailure`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_ui_toolkit_1_1_unity_ui_toolkit_transport_1aad0b7848de702f685a2fc45a16474a6d)`(` [`SigningRequest`](EosioSigningRequest--SigningRequest.md)` request, Exception exception)` 

Method is invoked when a signing request fails or is cancelled.

Refer to [https://github.com/greymass/anchor-link-browser-transport/blob/master/src/index.ts#L698](https://github.com/greymass/anchor-link-browser-transport/blob/master/src/index.ts#L698).

#### Parameters
* `request` 
* `exception`

##### `public virtual override void ` [`DisplayRequest`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_ui_toolkit_1_1_unity_ui_toolkit_transport_1aba60c11e2c8b926bea5109f4230a2a92)`(` [`SigningRequest`](EosioSigningRequest--SigningRequest.md)` request)` 

Method is invoked when a request to sign or login is made and the QR code and link are generated and displayed.

Refer to [https://github.com/greymass/anchor-link-browser-transport/blob/master/src/index.ts#L264](https://github.com/greymass/anchor-link-browser-transport/blob/master/src/index.ts#L264).

#### Parameters
* `request`

##### `private void ` [`CheckTheme`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_ui_toolkit_1_1_unity_ui_toolkit_transport_1a7bd8080ab3f19f9ace4cd6b317930bae)`()` 

check which theme to use (light and dark)

