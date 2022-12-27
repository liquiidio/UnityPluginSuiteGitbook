# class `AnchorLinkTransportSharp::Src::Transports::Canvas::UnityCanvasTransport` 

```
class AnchorLinkTransportSharp::Src::Transports::Canvas::UnityCanvasTransport
  : public UnityTransport
```

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`private string ` [`CountdownText`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1aea35f1a5398bcdf185ebdeda7aae882d) | Property that updates the UI with the relevant time during countdown when assigned to.
`public ` [`UnityCanvasTransport`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a24308a36f68304db3677b33631cdb563)`(` [`TransportOptions`](AnchorLinkTransportSharp--Src--TransportOptions.md)` options)` | Transport constructor.
`public virtual override void ` [`ShowLoading`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1ad07a81fbeebbad741a68a3e9b3f310e7)`()` | Method is invoked when a request is made and user signing on the wallet is required.
`public virtual override void ` [`OnSuccess`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1ac36aa71aa9c9918667f60b2f046bbb4c)`(` [`SigningRequest`](EosioSigningRequest--SigningRequest.md)` request, ` [`TransactResult`](AnchorLinkSharp--TransactResult.md)` result)` | Method is invoked when a succesful signing request is completed.
`public virtual override void ` [`OnFailure`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1aad0b7848de702f685a2fc45a16474a6d)`(` [`SigningRequest`](EosioSigningRequest--SigningRequest.md)` request, Exception exception)` | Method is invoked when a signing request fails or is cancelled.
`public virtual override void ` [`DisplayRequest`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1aba60c11e2c8b926bea5109f4230a2a92)`(` [`SigningRequest`](EosioSigningRequest--SigningRequest.md)` request)` | Method is invoked when a request to sign or login is made and the QR code and link are generated and displayed.
`public void ` [`OnVersionButtonPressed`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1afdf2e2da9324eba7d3008e682495b72e)`()` | Executed when the version button is interacted with (on all panels)
`public void ` [`OnDownloadAnchorButtonPressed`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a4d1bb7a2d0f7966169727aea478c2421)`()` | Executed when download Anchor button is interacted with.
`public void ` [`OnLoginPanelCloseButtonPressed`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a900c2ebcf08d9ae995f8db8b11979679)`()` | Executed when the close button on the login panel is interacted with (on available panels)
`public void ` [`OnStaticQRCodeHolderTargetButtonPressed`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a7a4be886279d143eca46d39442a7a0fd)`(RectTransform resizableQRCodePanel)` | Executed when the QR code (in the ZOOMED OUT state) is interacted with.
`public void ` [`OnResizableQRCodeHolderTargetButtonPressed`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a1de68595c9f8c6d162aceb20a0447f1b)`(RectTransform resizableQRCodePanel)` | Executed when the QR code (in the ZOOMED IN state) is interacted with.
`public void ` [`OnQRHyperlinkButtonPressed`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a993a51c06ca2d700a1233eb49ac27c23)`()` | Executed when the hyperlink button containing the ESR link is interacted with.
`public void ` [`OnLaunchAnchorButtonPressed`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a350dca87a063285fc35d32c533f6bf7e)`()` | Executed when the launch Anchor button is interacted with (opens Anchor Wallet desktop if installed)
`public void ` [`OnCloseLoadingPanelButtonPressed`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a06b3899787c587ab99aba9b08fbb91e9)`()` | Executed when the close button on the loading panel is interacted with.
`public void ` [`OnCloseTimeoutPanelButtonPressed`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a7ca8ea8853bd69713db31b06d5c86d2f)`()` | Executed when the close button on the timeout panel is interacted with.
`public void ` [`OnSignManuallyButtonPressed`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a153e7838d682ad5bb59ebfff4352edfa)`()` | Executed whent he manually sign button is interacted with.
`public void ` [`OnCloseSignPanelButtonPressed`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1afa0820373b93a06e25f53b864c1a45ae)`()` | Executed when the close sign panel button is interacted with.
`public void ` [`OnCloseSuccessPanelButtonPressed`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1aea61bcc3a54d9b2cacdad4c2ab048b14)`()` | Executed when the close success panel button is interacted with.
`public void ` [`OnCloseFailurePanelButtonPressed`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a6fb08c47e732890db36d68e359de6fab)`()` | Executed when the failure panel button is interacted with.
`private Coroutine ` [`counterCoroutine`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a26fad57f840357a24b32a0498e4b2c1f)`= null` | Used to manage the countdown timer.
`private GameObject ` [`HyperlinkCopiedNotificationPanel`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a1e3cbb7c5d6339f3c84d1052a78b5442) | Confirmation panel for when the link has been successfully copied.
`private GameObject ` [`LoginSubpanel`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1ae8ca578b4a4359a5aa38ee0872bd5af1) | Primary panel for the login prompt.
`private GameObject ` [`ManuallySignSubpanel`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1aab689e6be20a2ccc15b19d19667d92ff) | Panel to show manual verification details (when the countdown reaches 0)
`private Button ` [`CloseLoginPanelButton`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1af6c67f2d1b60a53b011ab3c10c7282e3) | Button to close the login panel (and execute further code)
`private Button ` [`StaticQRCodeHolderTargetButton`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a2a05d00c858a488a747ba39c5303c72d) | Button which displays the ESR link QR code and doubles as a way to scale up the QR code.
`private Button ` [`ResizableQRCodeHolderTargetButton`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a81173e85b4c20e8df86da6cd661078f2) | Button which displays the ESR link QR code and doubles as a way to scale down the QR code.
`private Animator ` [`ResizableQRCode_Animator`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a8d98830293a91f83c08bf296cd1e3715) | Animator that transitions the QR code scale size.
`private Button ` [`HyperlinkCopyButton`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1acfd9f0561b9eb9b6b1c803baf140a573) | Button used to copy the current ESR link.
`private Button ` [`LaunchAnchorButton`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1abc0aa9b53c9680993ef19654912d316f) | Button used to open Anchor Wallet desktop.
`private TextMeshProUGUI ` [`CountdownTextGUI`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1aaeb7546c5473a5a32ce723ea98b47f78) | Countdown information in the SignPanel prompt.
`private void ` [`Awake`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1ae4b513cddd594f1c359e4f0a3e79a8c6)`()` | 
`private void ` [`SwitchToLightTheme`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a527d85a4d385f0bab922f3f4a79742e9)`()` | Toggle between the light and dark theme (default is dark)
`private IEnumerator ` [`ResizableQRCodePanelZoomOut`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a4cc88f26cf1b038d6107de4d5150fbf9)`(RectTransform resizableQRCodePanel)` | Method used to manage the zoom out mechanic.
`private IEnumerator ` [`ToggleHyperlinkCopyButton_Delayed`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a4f3c061a575b9b54bbf5914464142bba)`()` | Coroutine to display if the ESR hyperlink button is interacted with to show a success state and revert back to default state.
`private void ` [`StartTimer`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a66509b494102a5c28ba6c8be3eab7733)`()` | Begin the countdown timer to show how much time is left to authorize request.
`private IEnumerator ` [`CountdownTimer`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a3e130601b07e0937f46e074e8458c4ab)`(float counterDuration)` | Coroutine to manage the countdown timer and update the panel with remaining time.
`private void ` [`ClearAllLinks`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a8981b6f9df138f98010e86ccaf4ee188)`()` | Remove all links from the QR code to avoid double/wrong sign links/actions/transactions.

## Members

##### `private string ` [`CountdownText`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1aea35f1a5398bcdf185ebdeda7aae882d) 

Property that updates the UI with the relevant time during countdown when assigned to.

##### `public ` [`UnityCanvasTransport`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a24308a36f68304db3677b33631cdb563)`(` [`TransportOptions`](AnchorLinkTransportSharp--Src--TransportOptions.md)` options)` 

Transport constructor.

#### Parameters
* `options`

##### `public virtual override void ` [`ShowLoading`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1ad07a81fbeebbad741a68a3e9b3f310e7)`()` 

Method is invoked when a request is made and user signing on the wallet is required.

Refer to [https://github.com/greymass/anchor-link-browser-transport/blob/master/src/index.ts#L361](https://github.com/greymass/anchor-link-browser-transport/blob/master/src/index.ts#L361).

##### `public virtual override void ` [`OnSuccess`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1ac36aa71aa9c9918667f60b2f046bbb4c)`(` [`SigningRequest`](EosioSigningRequest--SigningRequest.md)` request, ` [`TransactResult`](AnchorLinkSharp--TransactResult.md)` result)` 

Method is invoked when a succesful signing request is completed.

Refer to [https://github.com/greymass/anchor-link-browser-transport/blob/master/src/index.ts#L680](https://github.com/greymass/anchor-link-browser-transport/blob/master/src/index.ts#L680).

#### Parameters
* `request` />

* `result`

##### `public virtual override void ` [`OnFailure`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1aad0b7848de702f685a2fc45a16474a6d)`(` [`SigningRequest`](EosioSigningRequest--SigningRequest.md)` request, Exception exception)` 

Method is invoked when a signing request fails or is cancelled.

Refer to [https://github.com/greymass/anchor-link-browser-transport/blob/master/src/index.ts#L698](https://github.com/greymass/anchor-link-browser-transport/blob/master/src/index.ts#L698).

#### Parameters
* `request` 
* `exception`

##### `public virtual override void ` [`DisplayRequest`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1aba60c11e2c8b926bea5109f4230a2a92)`(` [`SigningRequest`](EosioSigningRequest--SigningRequest.md)` request)` 

Method is invoked when a request to sign or login is made and the QR code and link are generated and displayed.

Refer to [https://github.com/greymass/anchor-link-browser-transport/blob/master/src/index.ts#L264](https://github.com/greymass/anchor-link-browser-transport/blob/master/src/index.ts#L264).

#### Parameters
* `request`

##### `public void ` [`OnVersionButtonPressed`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1afdf2e2da9324eba7d3008e682495b72e)`()` 

Executed when the version button is interacted with (on all panels)

##### `public void ` [`OnDownloadAnchorButtonPressed`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a4d1bb7a2d0f7966169727aea478c2421)`()` 

Executed when download Anchor button is interacted with.

##### `public void ` [`OnLoginPanelCloseButtonPressed`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a900c2ebcf08d9ae995f8db8b11979679)`()` 

Executed when the close button on the login panel is interacted with (on available panels)

##### `public void ` [`OnStaticQRCodeHolderTargetButtonPressed`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a7a4be886279d143eca46d39442a7a0fd)`(RectTransform resizableQRCodePanel)` 

Executed when the QR code (in the ZOOMED OUT state) is interacted with.

#### Parameters
* `resizableQRCodePanel` Similar QR panel with the animator component

##### `public void ` [`OnResizableQRCodeHolderTargetButtonPressed`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a1de68595c9f8c6d162aceb20a0447f1b)`(RectTransform resizableQRCodePanel)` 

Executed when the QR code (in the ZOOMED IN state) is interacted with.

#### Parameters
* `resizableQRCodePanel` QR Panel with the animator component

##### `public void ` [`OnQRHyperlinkButtonPressed`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a993a51c06ca2d700a1233eb49ac27c23)`()` 

Executed when the hyperlink button containing the ESR link is interacted with.

##### `public void ` [`OnLaunchAnchorButtonPressed`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a350dca87a063285fc35d32c533f6bf7e)`()` 

Executed when the launch Anchor button is interacted with (opens Anchor Wallet desktop if installed)

##### `public void ` [`OnCloseLoadingPanelButtonPressed`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a06b3899787c587ab99aba9b08fbb91e9)`()` 

Executed when the close button on the loading panel is interacted with.

##### `public void ` [`OnCloseTimeoutPanelButtonPressed`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a7ca8ea8853bd69713db31b06d5c86d2f)`()` 

Executed when the close button on the timeout panel is interacted with.

##### `public void ` [`OnSignManuallyButtonPressed`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a153e7838d682ad5bb59ebfff4352edfa)`()` 

Executed whent he manually sign button is interacted with.

##### `public void ` [`OnCloseSignPanelButtonPressed`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1afa0820373b93a06e25f53b864c1a45ae)`()` 

Executed when the close sign panel button is interacted with.

##### `public void ` [`OnCloseSuccessPanelButtonPressed`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1aea61bcc3a54d9b2cacdad4c2ab048b14)`()` 

Executed when the close success panel button is interacted with.

##### `public void ` [`OnCloseFailurePanelButtonPressed`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a6fb08c47e732890db36d68e359de6fab)`()` 

Executed when the failure panel button is interacted with.

##### `private Coroutine ` [`counterCoroutine`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a26fad57f840357a24b32a0498e4b2c1f)`= null` 

Used to manage the countdown timer.

##### `private GameObject ` [`HyperlinkCopiedNotificationPanel`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a1e3cbb7c5d6339f3c84d1052a78b5442) 

Confirmation panel for when the link has been successfully copied.

##### `private GameObject ` [`LoginSubpanel`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1ae8ca578b4a4359a5aa38ee0872bd5af1) 

Primary panel for the login prompt.

##### `private GameObject ` [`ManuallySignSubpanel`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1aab689e6be20a2ccc15b19d19667d92ff) 

Panel to show manual verification details (when the countdown reaches 0)

##### `private Button ` [`CloseLoginPanelButton`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1af6c67f2d1b60a53b011ab3c10c7282e3) 

Button to close the login panel (and execute further code)

##### `private Button ` [`StaticQRCodeHolderTargetButton`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a2a05d00c858a488a747ba39c5303c72d) 

Button which displays the ESR link QR code and doubles as a way to scale up the QR code.

##### `private Button ` [`ResizableQRCodeHolderTargetButton`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a81173e85b4c20e8df86da6cd661078f2) 

Button which displays the ESR link QR code and doubles as a way to scale down the QR code.

##### `private Animator ` [`ResizableQRCode_Animator`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a8d98830293a91f83c08bf296cd1e3715) 

Animator that transitions the QR code scale size.

##### `private Button ` [`HyperlinkCopyButton`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1acfd9f0561b9eb9b6b1c803baf140a573) 

Button used to copy the current ESR link.

##### `private Button ` [`LaunchAnchorButton`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1abc0aa9b53c9680993ef19654912d316f) 

Button used to open Anchor Wallet desktop.

##### `private TextMeshProUGUI ` [`CountdownTextGUI`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1aaeb7546c5473a5a32ce723ea98b47f78) 

Countdown information in the SignPanel prompt.

##### `private void ` [`Awake`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1ae4b513cddd594f1c359e4f0a3e79a8c6)`()` 

##### `private void ` [`SwitchToLightTheme`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a527d85a4d385f0bab922f3f4a79742e9)`()` 

Toggle between the light and dark theme (default is dark)

##### `private IEnumerator ` [`ResizableQRCodePanelZoomOut`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a4cc88f26cf1b038d6107de4d5150fbf9)`(RectTransform resizableQRCodePanel)` 

Method used to manage the zoom out mechanic.

#### Parameters
* `resizableQRCodePanel` QR Panel with the animator component

#### Returns

##### `private IEnumerator ` [`ToggleHyperlinkCopyButton_Delayed`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a4f3c061a575b9b54bbf5914464142bba)`()` 

Coroutine to display if the ESR hyperlink button is interacted with to show a success state and revert back to default state.

#### Returns

##### `private void ` [`StartTimer`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a66509b494102a5c28ba6c8be3eab7733)`()` 

Begin the countdown timer to show how much time is left to authorize request.

##### `private IEnumerator ` [`CountdownTimer`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a3e130601b07e0937f46e074e8458c4ab)`(float counterDuration)` 

Coroutine to manage the countdown timer and update the panel with remaining time.

#### Parameters
* `counterDuration` Starting time for the countdown timer

#### Returns

##### `private void ` [`ClearAllLinks`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a8981b6f9df138f98010e86ccaf4ee188)`()` 

Remove all links from the QR code to avoid double/wrong sign links/actions/transactions.

