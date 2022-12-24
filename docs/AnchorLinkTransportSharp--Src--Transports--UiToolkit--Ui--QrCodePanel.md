# class `AnchorLinkTransportSharp::Src::Transports::UiToolkit::Ui::QrCodePanel` 

```
class AnchorLinkTransportSharp::Src::Transports::UiToolkit::Ui::QrCodePanel
  : public PanelBase
```

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`private readonly Vector3 ` [`_qrCurrentSize`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_ui_toolkit_1_1_ui_1_1_qr_code_panel_1a70dd0955f433a378cb45a9ac9d69206c)`= new Vector3(1, 1)` | 
`private ` [`SigningRequest`](EosioSigningRequest--SigningRequest.md)` ` [`_request`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_ui_toolkit_1_1_ui_1_1_qr_code_panel_1a10f6829816211e5c3488ee844917abae) | 
`private Button ` [`_launchAnchorButton`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_ui_toolkit_1_1_ui_1_1_qr_code_panel_1a41e2df165671e54dba913c63147cfc3e) | 
`private VisualElement ` [`_qrCodeBox`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_ui_toolkit_1_1_ui_1_1_qr_code_panel_1a9078712266dd2db3d05add33dba0aad2) | 
`private VisualElement ` [`_readyToCopy`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_ui_toolkit_1_1_ui_1_1_qr_code_panel_1a886b9d552e31ca1533ae6dd369bc7f3e) | 
`private VisualElement ` [`_alreadyCopied`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_ui_toolkit_1_1_ui_1_1_qr_code_panel_1a6db160a3309e5d0c6e1f80cacaad775e) | 
`private VisualElement ` [`_anchorFootnote`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_ui_toolkit_1_1_ui_1_1_qr_code_panel_1acd8cd37bfd8c6b60db6d56a812e5180f) | 
`private VisualElement ` [`_anchorLinkCopy`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_ui_toolkit_1_1_ui_1_1_qr_code_panel_1a2665408435b105bc877a2ba2376abe1a) | 
`private Label ` [`_subtitleLabel`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_ui_toolkit_1_1_ui_1_1_qr_code_panel_1aeb62caba75bc09150d07bc04e7bf6742) | 
`private Label ` [`_copyLabel`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_ui_toolkit_1_1_ui_1_1_qr_code_panel_1a8d7e5ae4de2ee6028b5ce25745b4dfae) | 
`private Label ` [`_downloadNowLabel`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_ui_toolkit_1_1_ui_1_1_qr_code_panel_1a20dc170757ab80a0678f904edd7693ac) | 
`private Label ` [`_linkedCopiedLabel`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_ui_toolkit_1_1_ui_1_1_qr_code_panel_1a493ba7fe5ab0624154d7851317a63b73) | 
`private Label ` [`_loginTitleLabel`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_ui_toolkit_1_1_ui_1_1_qr_code_panel_1aa37a06ebec2e3dda8268b0a304373867) | 
`private void ` [`Start`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_ui_toolkit_1_1_ui_1_1_qr_code_panel_1a07aaf1227e4d645f15e0a964f54ef291)`()` | 
`private void ` [`BindButtons`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_ui_toolkit_1_1_ui_1_1_qr_code_panel_1ac0a62408f7b64fe84a8a710e7119b60b)`()` | 
`private IEnumerator ` [`SetText`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_ui_toolkit_1_1_ui_1_1_qr_code_panel_1a05dae55364abc28ae3332f45d801b1e4)`(float counterDuration)` | 
`private Texture2D ` [`StringToQrCodeTexture2D`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_ui_toolkit_1_1_ui_1_1_qr_code_panel_1aaf7e564199136d7866f5ee711a6d7f04)`(string textForEncoding, int textureWidth, int textureHeight, Color32 baseColor, Color32 pixelColor)` | Call this to generate a QR code based on the parameters passed.
`private Color32[] ` [`StringEncoder`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_ui_toolkit_1_1_ui_1_1_qr_code_panel_1a49d96ac87b97c2e59de93e09af0d51cc)`(string textForEncoding, int width, int height, Color32 baseColor, Color32 pixelColor)` | 
`private void ` [`CopyToClipboard`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_ui_toolkit_1_1_ui_1_1_qr_code_panel_1a78826733039b0d0513d3a8d096c964c5)`(string targetString)` | Puts the passed string into the clipboard buffer to be pasted elsewhere.

## Members

##### `private readonly Vector3 ` [`_qrCurrentSize`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_ui_toolkit_1_1_ui_1_1_qr_code_panel_1a70dd0955f433a378cb45a9ac9d69206c)`= new Vector3(1, 1)` 

##### `private ` [`SigningRequest`](EosioSigningRequest--SigningRequest.md)` ` [`_request`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_ui_toolkit_1_1_ui_1_1_qr_code_panel_1a10f6829816211e5c3488ee844917abae) 

##### `private Button ` [`_launchAnchorButton`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_ui_toolkit_1_1_ui_1_1_qr_code_panel_1a41e2df165671e54dba913c63147cfc3e) 

##### `private VisualElement ` [`_qrCodeBox`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_ui_toolkit_1_1_ui_1_1_qr_code_panel_1a9078712266dd2db3d05add33dba0aad2) 

##### `private VisualElement ` [`_readyToCopy`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_ui_toolkit_1_1_ui_1_1_qr_code_panel_1a886b9d552e31ca1533ae6dd369bc7f3e) 

##### `private VisualElement ` [`_alreadyCopied`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_ui_toolkit_1_1_ui_1_1_qr_code_panel_1a6db160a3309e5d0c6e1f80cacaad775e) 

##### `private VisualElement ` [`_anchorFootnote`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_ui_toolkit_1_1_ui_1_1_qr_code_panel_1acd8cd37bfd8c6b60db6d56a812e5180f) 

##### `private VisualElement ` [`_anchorLinkCopy`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_ui_toolkit_1_1_ui_1_1_qr_code_panel_1a2665408435b105bc877a2ba2376abe1a) 

##### `private Label ` [`_subtitleLabel`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_ui_toolkit_1_1_ui_1_1_qr_code_panel_1aeb62caba75bc09150d07bc04e7bf6742) 

##### `private Label ` [`_copyLabel`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_ui_toolkit_1_1_ui_1_1_qr_code_panel_1a8d7e5ae4de2ee6028b5ce25745b4dfae) 

##### `private Label ` [`_downloadNowLabel`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_ui_toolkit_1_1_ui_1_1_qr_code_panel_1a20dc170757ab80a0678f904edd7693ac) 

##### `private Label ` [`_linkedCopiedLabel`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_ui_toolkit_1_1_ui_1_1_qr_code_panel_1a493ba7fe5ab0624154d7851317a63b73) 

##### `private Label ` [`_loginTitleLabel`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_ui_toolkit_1_1_ui_1_1_qr_code_panel_1aa37a06ebec2e3dda8268b0a304373867) 

##### `private void ` [`Start`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_ui_toolkit_1_1_ui_1_1_qr_code_panel_1a07aaf1227e4d645f15e0a964f54ef291)`()` 

##### `private void ` [`BindButtons`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_ui_toolkit_1_1_ui_1_1_qr_code_panel_1ac0a62408f7b64fe84a8a710e7119b60b)`()` 

##### `private IEnumerator ` [`SetText`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_ui_toolkit_1_1_ui_1_1_qr_code_panel_1a05dae55364abc28ae3332f45d801b1e4)`(float counterDuration)` 

##### `private Texture2D ` [`StringToQrCodeTexture2D`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_ui_toolkit_1_1_ui_1_1_qr_code_panel_1aaf7e564199136d7866f5ee711a6d7f04)`(string textForEncoding, int textureWidth, int textureHeight, Color32 baseColor, Color32 pixelColor)` 

Call this to generate a QR code based on the parameters passed.

#### Parameters
* `textForEncoding` The actual texture that will be encoded into a QRCode

* `textureWidth` How wide the new texture should be

* `textureHeight` How high the new texture should be

#### Returns

##### `private Color32[] ` [`StringEncoder`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_ui_toolkit_1_1_ui_1_1_qr_code_panel_1a49d96ac87b97c2e59de93e09af0d51cc)`(string textForEncoding, int width, int height, Color32 baseColor, Color32 pixelColor)` 

##### `private void ` [`CopyToClipboard`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_ui_toolkit_1_1_ui_1_1_qr_code_panel_1a78826733039b0d0513d3a8d096c964c5)`(string targetString)` 

Puts the passed string into the clipboard buffer to be pasted elsewhere.

#### Parameters
* `targetString` Text to be copied to the buffer

