# class `AnchorLinkTransportSharp::Src::UnityTransport` 

```
class AnchorLinkTransportSharp::Src::UnityTransport
  : public MonoBehaviour
  : public ILinkTransport
```

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public ` [`ILinkStorage`](AnchorLinkSharp.md)` ` [`Storage`](#class_anchor_link_transport_sharp_1_1_src_1_1_unity_transport_1a3198c2558a95eb66553955ab4b579438) | The Storage used for sessions and metadata.
`public ` [`UnityTransport`](#class_anchor_link_transport_sharp_1_1_src_1_1_unity_transport_1ac17cf84d27619a7170e46e363eee0412)`(TransportOptions options)` | 
`public void ` [`OnRequest`](#class_anchor_link_transport_sharp_1_1_src_1_1_unity_transport_1af033a491264433deccf8f379377bf0de)`(SigningRequest request, Action< object > cancel)` | 
`public void ` [`OnSessionRequest`](#class_anchor_link_transport_sharp_1_1_src_1_1_unity_transport_1ab43ebe78aa7d484d52f5d1f80e8a0e74)`(` [`LinkSession`](AnchorLinkSharp--LinkSession.md)` session, SigningRequest request, Action< object > cancel)` | 
`public async Task< SigningRequest > ` [`Prepare`](#class_anchor_link_transport_sharp_1_1_src_1_1_unity_transport_1a2ba24fa9a86412c68780ae3157322251)`(SigningRequest request, ` [`LinkSession`](AnchorLinkSharp--LinkSession.md)` session)` | 
`public void ` [`CopyToClipboard`](#class_anchor_link_transport_sharp_1_1_src_1_1_unity_transport_1a78826733039b0d0513d3a8d096c964c5)`(string targetString)` | Puts the passed string into the clipboard buffer to be pasted elsewhere.
`public Texture2D ` [`StringToQRCodeTexture2D`](#class_anchor_link_transport_sharp_1_1_src_1_1_unity_transport_1aacd85aff186fa6642a396d97be396fba)`(string textForEncoding, int textureWidth, int textureHeight, Color32 baseColor, Color32 pixelColor)` | Call this to generate a QR code based on the parameters passed.
`public abstract void ` [`ShowLoading`](#class_anchor_link_transport_sharp_1_1_src_1_1_unity_transport_1af418b15dece32a4e64c2eecf5ad5d395)`()` | Method is invoked when a request is made and user signing on the wallet is required.
`public abstract void ` [`OnSuccess`](#class_anchor_link_transport_sharp_1_1_src_1_1_unity_transport_1a21b85c67f69efaeeb2fcc52bcbb75d8f)`(SigningRequest request, ` [`TransactResult`](AnchorLinkSharp--TransactResult.md)` result)` | Method is invoked when a succesful signing request is completed.
`public abstract void ` [`OnFailure`](#class_anchor_link_transport_sharp_1_1_src_1_1_unity_transport_1ad51f12d8e0f841020c19b45b7554a8b0)`(SigningRequest request, Exception exception)` | Method is invoked when a signing request fails or is cancelled.
`public abstract void ` [`DisplayRequest`](#class_anchor_link_transport_sharp_1_1_src_1_1_unity_transport_1a768e8851a4d14b2454161b925e5efc16)`(SigningRequest request)` | Method is invoked when a request to sign or login is made and the QR code and link are generated and displayed.
`private readonly bool ` [`_requestStatus`](#class_anchor_link_transport_sharp_1_1_src_1_1_unity_transport_1aca210874d7d563cfc1475451b4e26ad1) | The Status of the current Request.
`private SigningRequest ` [`_activeRequest`](#class_anchor_link_transport_sharp_1_1_src_1_1_unity_transport_1a259fde2c0f9f930be8631c1d4427df9a) | The current active Request.
`private Action< object > ` [`_activeCancel`](#class_anchor_link_transport_sharp_1_1_src_1_1_unity_transport_1a0c4229d810ba5ac013493dd663c0b6f5) | The activeCancel Delegate (invoked when a Request is cancelled)
`private Color32[] ` [`StringEncoder`](#class_anchor_link_transport_sharp_1_1_src_1_1_unity_transport_1af25c30c32b47c2b50192173b1133ed01)`(string textForEncoding, int width, int height)` | 

## Members

##### `public ` [`ILinkStorage`](AnchorLinkSharp.md)` ` [`Storage`](#class_anchor_link_transport_sharp_1_1_src_1_1_unity_transport_1a3198c2558a95eb66553955ab4b579438) 

The Storage used for sessions and metadata.

##### `public ` [`UnityTransport`](#class_anchor_link_transport_sharp_1_1_src_1_1_unity_transport_1ac17cf84d27619a7170e46e363eee0412)`(TransportOptions options)` 

##### `public void ` [`OnRequest`](#class_anchor_link_transport_sharp_1_1_src_1_1_unity_transport_1af033a491264433deccf8f379377bf0de)`(SigningRequest request, Action< object > cancel)` 

##### `public void ` [`OnSessionRequest`](#class_anchor_link_transport_sharp_1_1_src_1_1_unity_transport_1ab43ebe78aa7d484d52f5d1f80e8a0e74)`(` [`LinkSession`](AnchorLinkSharp--LinkSession.md)` session, SigningRequest request, Action< object > cancel)` 

##### `public async Task< SigningRequest > ` [`Prepare`](#class_anchor_link_transport_sharp_1_1_src_1_1_unity_transport_1a2ba24fa9a86412c68780ae3157322251)`(SigningRequest request, ` [`LinkSession`](AnchorLinkSharp--LinkSession.md)` session)` 

##### `public void ` [`CopyToClipboard`](#class_anchor_link_transport_sharp_1_1_src_1_1_unity_transport_1a78826733039b0d0513d3a8d096c964c5)`(string targetString)` 

Puts the passed string into the clipboard buffer to be pasted elsewhere.

#### Parameters
* `targetString` Text to be copied to the buffer

##### `public Texture2D ` [`StringToQRCodeTexture2D`](#class_anchor_link_transport_sharp_1_1_src_1_1_unity_transport_1aacd85aff186fa6642a396d97be396fba)`(string textForEncoding, int textureWidth, int textureHeight, Color32 baseColor, Color32 pixelColor)` 

Call this to generate a QR code based on the parameters passed.

#### Parameters
* `textForEncoding` The actual texture that will be encoded into a QRCode

* `textureWidth` How wide the new texture should be

* `textureHeight` How high the new texture should be

#### Returns

##### `public abstract void ` [`ShowLoading`](#class_anchor_link_transport_sharp_1_1_src_1_1_unity_transport_1af418b15dece32a4e64c2eecf5ad5d395)`()` 

Method is invoked when a request is made and user signing on the wallet is required.

##### `public abstract void ` [`OnSuccess`](#class_anchor_link_transport_sharp_1_1_src_1_1_unity_transport_1a21b85c67f69efaeeb2fcc52bcbb75d8f)`(SigningRequest request, ` [`TransactResult`](AnchorLinkSharp--TransactResult.md)` result)` 

Method is invoked when a succesful signing request is completed.

#### Parameters
* `request` 
* `result`

##### `public abstract void ` [`OnFailure`](#class_anchor_link_transport_sharp_1_1_src_1_1_unity_transport_1ad51f12d8e0f841020c19b45b7554a8b0)`(SigningRequest request, Exception exception)` 

Method is invoked when a signing request fails or is cancelled.

#### Parameters
* `request` 
* `exception`

##### `public abstract void ` [`DisplayRequest`](#class_anchor_link_transport_sharp_1_1_src_1_1_unity_transport_1a768e8851a4d14b2454161b925e5efc16)`(SigningRequest request)` 

Method is invoked when a request to sign or login is made and the QR code and link are generated and displayed.

#### Parameters
* `request`

##### `private readonly bool ` [`_requestStatus`](#class_anchor_link_transport_sharp_1_1_src_1_1_unity_transport_1aca210874d7d563cfc1475451b4e26ad1) 

The Status of the current Request.

##### `private SigningRequest ` [`_activeRequest`](#class_anchor_link_transport_sharp_1_1_src_1_1_unity_transport_1a259fde2c0f9f930be8631c1d4427df9a) 

The current active Request.

##### `private Action< object > ` [`_activeCancel`](#class_anchor_link_transport_sharp_1_1_src_1_1_unity_transport_1a0c4229d810ba5ac013493dd663c0b6f5) 

The activeCancel Delegate (invoked when a Request is cancelled)

##### `private Color32[] ` [`StringEncoder`](#class_anchor_link_transport_sharp_1_1_src_1_1_unity_transport_1af25c30c32b47c2b50192173b1133ed01)`(string textForEncoding, int width, int height)` 

