# class `AnchorLinkTransportSharp::Src::Transports::Canvas::UnityCanvasTransport` 

```
class AnchorLinkTransportSharp::Src::Transports::Canvas::UnityCanvasTransport
  : public UnityTransport
```

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`private string ` [`CountdownText`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1aea35f1a5398bcdf185ebdeda7aae882d) | 
`public ` [`UnityCanvasTransport`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a24308a36f68304db3677b33631cdb563)`(TransportOptions options)` | 
`public override void ` [`ShowLoading`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1ad07a81fbeebbad741a68a3e9b3f310e7)`()` | 
`public override void ` [`OnSuccess`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1ac36aa71aa9c9918667f60b2f046bbb4c)`(SigningRequest request, ` [`TransactResult`](AnchorLinkSharp--TransactResult.md)` result)` | 
`public override void ` [`OnFailure`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1aad0b7848de702f685a2fc45a16474a6d)`(SigningRequest request, Exception exception)` | 
`public override void ` [`DisplayRequest`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1aba60c11e2c8b926bea5109f4230a2a92)`(SigningRequest request)` | 
`public void ` [`OnVersionButtonPressed`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1afdf2e2da9324eba7d3008e682495b72e)`()` | 
`public void ` [`OnDownloadAnchorButtonPressed`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a4d1bb7a2d0f7966169727aea478c2421)`()` | 
`public void ` [`OnLoginPanelCloseButtonPressed`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a900c2ebcf08d9ae995f8db8b11979679)`()` | 
`public void ` [`OnStaticQRCodeHolderTargetButtonPressed`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a7a4be886279d143eca46d39442a7a0fd)`(RectTransform resizableQRCodePanel)` | 
`public void ` [`OnResizableQRCodeHolderTargetButtonPressed`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a1de68595c9f8c6d162aceb20a0447f1b)`(RectTransform resizableQRCodePanel)` | 
`public void ` [`OnQRHyperlinkButtonPressed`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a993a51c06ca2d700a1233eb49ac27c23)`()` | 
`public void ` [`OnLaunchAnchorButtonPressed`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a350dca87a063285fc35d32c533f6bf7e)`()` | 
`public void ` [`OnCloseLoadingPanelButtonPressed`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a06b3899787c587ab99aba9b08fbb91e9)`()` | 
`public void ` [`OnCloseTimeoutPanelButtonPressed`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a7ca8ea8853bd69713db31b06d5c86d2f)`()` | 
`public void ` [`OnSignManuallyButtonPressed`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a153e7838d682ad5bb59ebfff4352edfa)`()` | 
`public void ` [`OnCloseSignPanelButtonPressed`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1afa0820373b93a06e25f53b864c1a45ae)`()` | 
`public void ` [`OnCloseSuccessPanelButtonPressed`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1aea61bcc3a54d9b2cacdad4c2ab048b14)`()` | 
`public void ` [`OnCloseFailurePanelButtonPressed`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a6fb08c47e732890db36d68e359de6fab)`()` | 
`private Coroutine ` [`counterCoroutine`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a26fad57f840357a24b32a0498e4b2c1f)`= null` | 
`private GameObject ` [`HyperlinkCopiedNotificationPanel`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a1e3cbb7c5d6339f3c84d1052a78b5442) | Confirmation panel for when the link has been successfully copied.
`private GameObject ` [`LoginSubpanel`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1ae8ca578b4a4359a5aa38ee0872bd5af1) | 
`private GameObject ` [`ManuallySignSubpanel`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1aab689e6be20a2ccc15b19d19667d92ff) | 
`private Button ` [`CloseLoginPanelButton`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1af6c67f2d1b60a53b011ab3c10c7282e3) | 
`private Button ` [`StaticQRCodeHolderTargetButton`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a2a05d00c858a488a747ba39c5303c72d) | 
`private Button ` [`ResizableQRCodeHolderTargetButton`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a81173e85b4c20e8df86da6cd661078f2) | 
`private Animator ` [`ResizableQRCode_Animator`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a8d98830293a91f83c08bf296cd1e3715) | 
`private Button ` [`HyperlinkCopyButton`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1acfd9f0561b9eb9b6b1c803baf140a573) | 
`private Button ` [`LaunchAnchorButton`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1abc0aa9b53c9680993ef19654912d316f) | 
`private TextMeshProUGUI ` [`CountdownTextGUI`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1aaeb7546c5473a5a32ce723ea98b47f78) | 
`private void ` [`Awake`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1ae4b513cddd594f1c359e4f0a3e79a8c6)`()` | 
`private void ` [`SwitchToLightTheme`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a527d85a4d385f0bab922f3f4a79742e9)`()` | Toggle between the light and dark theme (default is dark)
`private IEnumerator ` [`ResizableQRCodePanelZoomOut`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a4cc88f26cf1b038d6107de4d5150fbf9)`(RectTransform resizableQRCodePanel)` | 
`private IEnumerator ` [`ToggleHyperlinkCopyButton_Delayed`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a4f3c061a575b9b54bbf5914464142bba)`()` | 
`private void ` [`StartTimer`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a66509b494102a5c28ba6c8be3eab7733)`()` | 
`private IEnumerator ` [`CountdownTimer`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a3e130601b07e0937f46e074e8458c4ab)`(float counterDuration)` | 
`private void ` [`ClearAllLinks`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a8981b6f9df138f98010e86ccaf4ee188)`()` | 

## Members

##### `private string ` [`CountdownText`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1aea35f1a5398bcdf185ebdeda7aae882d) 

##### `public ` [`UnityCanvasTransport`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a24308a36f68304db3677b33631cdb563)`(TransportOptions options)` 

##### `public override void ` [`ShowLoading`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1ad07a81fbeebbad741a68a3e9b3f310e7)`()` 

##### `public override void ` [`OnSuccess`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1ac36aa71aa9c9918667f60b2f046bbb4c)`(SigningRequest request, ` [`TransactResult`](AnchorLinkSharp--TransactResult.md)` result)` 

##### `public override void ` [`OnFailure`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1aad0b7848de702f685a2fc45a16474a6d)`(SigningRequest request, Exception exception)` 

##### `public override void ` [`DisplayRequest`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1aba60c11e2c8b926bea5109f4230a2a92)`(SigningRequest request)` 

##### `public void ` [`OnVersionButtonPressed`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1afdf2e2da9324eba7d3008e682495b72e)`()` 

##### `public void ` [`OnDownloadAnchorButtonPressed`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a4d1bb7a2d0f7966169727aea478c2421)`()` 

##### `public void ` [`OnLoginPanelCloseButtonPressed`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a900c2ebcf08d9ae995f8db8b11979679)`()` 

##### `public void ` [`OnStaticQRCodeHolderTargetButtonPressed`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a7a4be886279d143eca46d39442a7a0fd)`(RectTransform resizableQRCodePanel)` 

##### `public void ` [`OnResizableQRCodeHolderTargetButtonPressed`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a1de68595c9f8c6d162aceb20a0447f1b)`(RectTransform resizableQRCodePanel)` 

##### `public void ` [`OnQRHyperlinkButtonPressed`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a993a51c06ca2d700a1233eb49ac27c23)`()` 

##### `public void ` [`OnLaunchAnchorButtonPressed`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a350dca87a063285fc35d32c533f6bf7e)`()` 

##### `public void ` [`OnCloseLoadingPanelButtonPressed`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a06b3899787c587ab99aba9b08fbb91e9)`()` 

##### `public void ` [`OnCloseTimeoutPanelButtonPressed`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a7ca8ea8853bd69713db31b06d5c86d2f)`()` 

##### `public void ` [`OnSignManuallyButtonPressed`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a153e7838d682ad5bb59ebfff4352edfa)`()` 

##### `public void ` [`OnCloseSignPanelButtonPressed`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1afa0820373b93a06e25f53b864c1a45ae)`()` 

##### `public void ` [`OnCloseSuccessPanelButtonPressed`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1aea61bcc3a54d9b2cacdad4c2ab048b14)`()` 

##### `public void ` [`OnCloseFailurePanelButtonPressed`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a6fb08c47e732890db36d68e359de6fab)`()` 

##### `private Coroutine ` [`counterCoroutine`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a26fad57f840357a24b32a0498e4b2c1f)`= null` 

##### `private GameObject ` [`HyperlinkCopiedNotificationPanel`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a1e3cbb7c5d6339f3c84d1052a78b5442) 

Confirmation panel for when the link has been successfully copied.

##### `private GameObject ` [`LoginSubpanel`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1ae8ca578b4a4359a5aa38ee0872bd5af1) 

##### `private GameObject ` [`ManuallySignSubpanel`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1aab689e6be20a2ccc15b19d19667d92ff) 

##### `private Button ` [`CloseLoginPanelButton`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1af6c67f2d1b60a53b011ab3c10c7282e3) 

##### `private Button ` [`StaticQRCodeHolderTargetButton`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a2a05d00c858a488a747ba39c5303c72d) 

##### `private Button ` [`ResizableQRCodeHolderTargetButton`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a81173e85b4c20e8df86da6cd661078f2) 

##### `private Animator ` [`ResizableQRCode_Animator`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a8d98830293a91f83c08bf296cd1e3715) 

##### `private Button ` [`HyperlinkCopyButton`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1acfd9f0561b9eb9b6b1c803baf140a573) 

##### `private Button ` [`LaunchAnchorButton`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1abc0aa9b53c9680993ef19654912d316f) 

##### `private TextMeshProUGUI ` [`CountdownTextGUI`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1aaeb7546c5473a5a32ce723ea98b47f78) 

##### `private void ` [`Awake`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1ae4b513cddd594f1c359e4f0a3e79a8c6)`()` 

##### `private void ` [`SwitchToLightTheme`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a527d85a4d385f0bab922f3f4a79742e9)`()` 

Toggle between the light and dark theme (default is dark)

##### `private IEnumerator ` [`ResizableQRCodePanelZoomOut`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a4cc88f26cf1b038d6107de4d5150fbf9)`(RectTransform resizableQRCodePanel)` 

##### `private IEnumerator ` [`ToggleHyperlinkCopyButton_Delayed`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a4f3c061a575b9b54bbf5914464142bba)`()` 

##### `private void ` [`StartTimer`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a66509b494102a5c28ba6c8be3eab7733)`()` 

##### `private IEnumerator ` [`CountdownTimer`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a3e130601b07e0937f46e074e8458c4ab)`(float counterDuration)` 

##### `private void ` [`ClearAllLinks`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_canvas_1_1_unity_canvas_transport_1a8981b6f9df138f98010e86ccaf4ee188)`()` 

