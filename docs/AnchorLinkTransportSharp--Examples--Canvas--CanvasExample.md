# class `AnchorLinkTransportSharp::Examples::Canvas::CanvasExample` 

```
class AnchorLinkTransportSharp::Examples::Canvas::CanvasExample
  : public MonoBehaviour
```

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public async void ` [`StartSession`](#class_anchor_link_transport_sharp_1_1_examples_1_1_canvas_1_1_canvas_example_1a21a21c71ee0ace02fd3160e2837634eb)`()` | Initialize a new session.
`public async void ` [`RestoreASession`](#class_anchor_link_transport_sharp_1_1_examples_1_1_canvas_1_1_canvas_example_1afea5a36560e6fcb1b0678f39a5c15b7a)`()` | Call from UI button.
`public async void ` [`DoLogout`](#class_anchor_link_transport_sharp_1_1_examples_1_1_canvas_1_1_canvas_example_1a50120f60083f3b65162d886528fbe29c)`()` | Call from UI button.
`public void ` [`ShowTargetPanel`](#class_anchor_link_transport_sharp_1_1_examples_1_1_canvas_1_1_canvas_example_1aa07ec4761b8644ff9aeaf15c3872dcdd)`(GameObject targetPanel)` | Use this to toggle on a new rect (or a gameobject) in the canvas.
`public async void ` [`TryTransferTokens`](#class_anchor_link_transport_sharp_1_1_examples_1_1_canvas_1_1_canvas_example_1a6438f85911eb313073eca6ec1cc2d3fb)`(GameObject TransferDetailsPanel)` | Gather data from the custom transfer UI panel.
`private UnityCanvasTransport ` [`Transport`](#class_anchor_link_transport_sharp_1_1_examples_1_1_canvas_1_1_canvas_example_1a6fb478943c7a1f823ab22bfa7b15f015) | Assign UnityTransport through the Editor.
`private GameObject ` [`CustomActionsPanel`](#class_anchor_link_transport_sharp_1_1_examples_1_1_canvas_1_1_canvas_example_1a6fff9e3e3300f7c0960ddcaccef1ffbd) | 
`private GameObject ` [`CustomTransferPanel`](#class_anchor_link_transport_sharp_1_1_examples_1_1_canvas_1_1_canvas_example_1a4596cbd6121197c94bd4e0d4109deecc) | 
`private Button ` [`LoginButton`](#class_anchor_link_transport_sharp_1_1_examples_1_1_canvas_1_1_canvas_example_1a14ce573f076bdd94dc78abf946718885) | 
`private Button ` [`RestoreSessionButton`](#class_anchor_link_transport_sharp_1_1_examples_1_1_canvas_1_1_canvas_example_1aa3122a5c822deeb2e84a04f637936d42) | 
`private Button ` [`TransferButton`](#class_anchor_link_transport_sharp_1_1_examples_1_1_canvas_1_1_canvas_example_1ac372f612d7aed4ac8a1b4a3349f3eeba) | 
`private Button ` [`LogoutButton`](#class_anchor_link_transport_sharp_1_1_examples_1_1_canvas_1_1_canvas_example_1ad2f6ad4809aaadcd5a7884c5bf69acd9) | 
`private Coroutine ` [`waitCoroutine`](#class_anchor_link_transport_sharp_1_1_examples_1_1_canvas_1_1_canvas_example_1acaf3524519c2960c79f6a7d20e97d9aa) | 
`private ` [`AnchorLink`](AnchorLinkSharp--AnchorLink.md)` ` [`_link`](#class_anchor_link_transport_sharp_1_1_examples_1_1_canvas_1_1_canvas_example_1ab83a853dc8e03635061e08d6e0330778) | initialize the link
`private ` [`LinkSession`](AnchorLinkSharp--LinkSession.md)` ` [`_session`](#class_anchor_link_transport_sharp_1_1_examples_1_1_canvas_1_1_canvas_example_1a028dc4f27d9ba73226782f611d3ac6b4) | the session instance, either restored using link.restoreSession() or created with link.login()
`private void ` [`Start`](#class_anchor_link_transport_sharp_1_1_examples_1_1_canvas_1_1_canvas_example_1a07aaf1227e4d645f15e0a964f54ef291)`()` | 
`private async Task ` [`Login`](#class_anchor_link_transport_sharp_1_1_examples_1_1_canvas_1_1_canvas_example_1a1e2c964859fcad3068b0e8c497dfc595)`()` | Login and store session if sucessful.
`private async Task ` [`RestoreSession`](#class_anchor_link_transport_sharp_1_1_examples_1_1_canvas_1_1_canvas_example_1adadc720358152fd54c27c3b46e0e9e3f)`()` | Tries to restore session, called when document is loaded.
`private async Task ` [`Logout`](#class_anchor_link_transport_sharp_1_1_examples_1_1_canvas_1_1_canvas_example_1a6cb278c915d3dc67fc4a4539ee1418ef)`()` | Logout and remove session from storage.
`private void ` [`DidLogin`](#class_anchor_link_transport_sharp_1_1_examples_1_1_canvas_1_1_canvas_example_1a44c32017daaa3807a8938a368b707ac1)`()` | Called when session was restored or created.
`private async Task ` [`Transfer`](#class_anchor_link_transport_sharp_1_1_examples_1_1_canvas_1_1_canvas_example_1a25397506d3153a001f7a7fa954d7b1f1)`(string frmAcc, string toAcc, string qnty, string memo)` | Transfer tokens using a session.
`private IEnumerator ` [`SwitchPanels`](#class_anchor_link_transport_sharp_1_1_examples_1_1_canvas_1_1_canvas_example_1a906a251a06dfd177e4d81bbf1645c2c1)`(GameObject fromPanel, GameObject toPanel, float SecondsToWait)` | 

## Members

##### `public async void ` [`StartSession`](#class_anchor_link_transport_sharp_1_1_examples_1_1_canvas_1_1_canvas_example_1a21a21c71ee0ace02fd3160e2837634eb)`()` 

Initialize a new session.

##### `public async void ` [`RestoreASession`](#class_anchor_link_transport_sharp_1_1_examples_1_1_canvas_1_1_canvas_example_1afea5a36560e6fcb1b0678f39a5c15b7a)`()` 

Call from UI button.

##### `public async void ` [`DoLogout`](#class_anchor_link_transport_sharp_1_1_examples_1_1_canvas_1_1_canvas_example_1a50120f60083f3b65162d886528fbe29c)`()` 

Call from UI button.

##### `public void ` [`ShowTargetPanel`](#class_anchor_link_transport_sharp_1_1_examples_1_1_canvas_1_1_canvas_example_1aa07ec4761b8644ff9aeaf15c3872dcdd)`(GameObject targetPanel)` 

Use this to toggle on a new rect (or a gameobject) in the canvas.

#### Parameters
* `targetPanel`

##### `public async void ` [`TryTransferTokens`](#class_anchor_link_transport_sharp_1_1_examples_1_1_canvas_1_1_canvas_example_1a6438f85911eb313073eca6ec1cc2d3fb)`(GameObject TransferDetailsPanel)` 

Gather data from the custom transfer UI panel.

#### Parameters
* `TransferDetailsPanel`

##### `private UnityCanvasTransport ` [`Transport`](#class_anchor_link_transport_sharp_1_1_examples_1_1_canvas_1_1_canvas_example_1a6fb478943c7a1f823ab22bfa7b15f015) 

Assign UnityTransport through the Editor.

##### `private GameObject ` [`CustomActionsPanel`](#class_anchor_link_transport_sharp_1_1_examples_1_1_canvas_1_1_canvas_example_1a6fff9e3e3300f7c0960ddcaccef1ffbd) 

##### `private GameObject ` [`CustomTransferPanel`](#class_anchor_link_transport_sharp_1_1_examples_1_1_canvas_1_1_canvas_example_1a4596cbd6121197c94bd4e0d4109deecc) 

##### `private Button ` [`LoginButton`](#class_anchor_link_transport_sharp_1_1_examples_1_1_canvas_1_1_canvas_example_1a14ce573f076bdd94dc78abf946718885) 

##### `private Button ` [`RestoreSessionButton`](#class_anchor_link_transport_sharp_1_1_examples_1_1_canvas_1_1_canvas_example_1aa3122a5c822deeb2e84a04f637936d42) 

##### `private Button ` [`TransferButton`](#class_anchor_link_transport_sharp_1_1_examples_1_1_canvas_1_1_canvas_example_1ac372f612d7aed4ac8a1b4a3349f3eeba) 

##### `private Button ` [`LogoutButton`](#class_anchor_link_transport_sharp_1_1_examples_1_1_canvas_1_1_canvas_example_1ad2f6ad4809aaadcd5a7884c5bf69acd9) 

##### `private Coroutine ` [`waitCoroutine`](#class_anchor_link_transport_sharp_1_1_examples_1_1_canvas_1_1_canvas_example_1acaf3524519c2960c79f6a7d20e97d9aa) 

##### `private ` [`AnchorLink`](AnchorLinkSharp--AnchorLink.md)` ` [`_link`](#class_anchor_link_transport_sharp_1_1_examples_1_1_canvas_1_1_canvas_example_1ab83a853dc8e03635061e08d6e0330778) 

initialize the link

##### `private ` [`LinkSession`](AnchorLinkSharp--LinkSession.md)` ` [`_session`](#class_anchor_link_transport_sharp_1_1_examples_1_1_canvas_1_1_canvas_example_1a028dc4f27d9ba73226782f611d3ac6b4) 

the session instance, either restored using link.restoreSession() or created with link.login()

##### `private void ` [`Start`](#class_anchor_link_transport_sharp_1_1_examples_1_1_canvas_1_1_canvas_example_1a07aaf1227e4d645f15e0a964f54ef291)`()` 

##### `private async Task ` [`Login`](#class_anchor_link_transport_sharp_1_1_examples_1_1_canvas_1_1_canvas_example_1a1e2c964859fcad3068b0e8c497dfc595)`()` 

Login and store session if sucessful.

#### Returns

##### `private async Task ` [`RestoreSession`](#class_anchor_link_transport_sharp_1_1_examples_1_1_canvas_1_1_canvas_example_1adadc720358152fd54c27c3b46e0e9e3f)`()` 

Tries to restore session, called when document is loaded.

#### Returns

##### `private async Task ` [`Logout`](#class_anchor_link_transport_sharp_1_1_examples_1_1_canvas_1_1_canvas_example_1a6cb278c915d3dc67fc4a4539ee1418ef)`()` 

Logout and remove session from storage.

#### Returns

##### `private void ` [`DidLogin`](#class_anchor_link_transport_sharp_1_1_examples_1_1_canvas_1_1_canvas_example_1a44c32017daaa3807a8938a368b707ac1)`()` 

Called when session was restored or created.

##### `private async Task ` [`Transfer`](#class_anchor_link_transport_sharp_1_1_examples_1_1_canvas_1_1_canvas_example_1a25397506d3153a001f7a7fa954d7b1f1)`(string frmAcc, string toAcc, string qnty, string memo)` 

Transfer tokens using a session.

#### Parameters
* `frmAcc` 
* `toAcc` 
* `qnty` 
* `memo` 

#### Returns

##### `private IEnumerator ` [`SwitchPanels`](#class_anchor_link_transport_sharp_1_1_examples_1_1_canvas_1_1_canvas_example_1a906a251a06dfd177e4d81bbf1645c2c1)`(GameObject fromPanel, GameObject toPanel, float SecondsToWait)` 

