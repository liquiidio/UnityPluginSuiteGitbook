# class `UniversalAuthenticatorLibrary::Examples::Canvas::UALCanvasExample` 

```
class UniversalAuthenticatorLibrary::Examples::Canvas::UALCanvasExample
  : public MonoBehaviour
```

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public ` [`UnityCanvasUAL`](UniversalAuthenticatorLibrary--Src--Canvas--UnityCanvasUAL.md)` ` [`UnityCanvasUAL`](#class_universal_authenticator_library_1_1_examples_1_1_canvas_1_1_u_a_l_canvas_example_1a80913e8bd8a266d2b35aac9812c7caf7) | 
`public GameObject ` [`TransactionPanel`](#class_universal_authenticator_library_1_1_examples_1_1_canvas_1_1_u_a_l_canvas_example_1a40c2058d3f65a869398ba6d24828071b) | 
`public void ` [`OnBrowserClipboardPaste`](#class_universal_authenticator_library_1_1_examples_1_1_canvas_1_1_u_a_l_canvas_example_1a009752823a43afe0e10b9e91dfee8ae2)`(string pastedText)` | Called when ctrl + v is pressed in browser (webgl)
`public async void ` [`TryTransferTokens`](#class_universal_authenticator_library_1_1_examples_1_1_canvas_1_1_u_a_l_canvas_example_1a6438f85911eb313073eca6ec1cc2d3fb)`(GameObject TransferDetailsPanel)` | Gather data from the custom transfer UI panel.
`private ` [`User`](UniversalAuthenticatorLibrary--User.md)` ` [`user`](#class_universal_authenticator_library_1_1_examples_1_1_canvas_1_1_u_a_l_canvas_example_1a7ffd636d88d39d8b4366d5423d352b0b) | 
`private EventSystem ` [`_canvasEventSystem`](#class_universal_authenticator_library_1_1_examples_1_1_canvas_1_1_u_a_l_canvas_example_1acc92c1097922093b8ddd19f150619efa) | 
`private async void ` [`Start`](#class_universal_authenticator_library_1_1_examples_1_1_canvas_1_1_u_a_l_canvas_example_1a5957aa0d15061f2c6b7145cca4139d83)`()` | 
`private void ` [`BindButtons`](#class_universal_authenticator_library_1_1_examples_1_1_canvas_1_1_u_a_l_canvas_example_1ac0a62408f7b64fe84a8a710e7119b60b)`()` | 
`private void ` [`ReturnToAuthenticatorSelection`](#class_universal_authenticator_library_1_1_examples_1_1_canvas_1_1_u_a_l_canvas_example_1a673d166cf5d64fbd7c0da1f932ec3f0a)`()` | 
`private void ` [`Update`](#class_universal_authenticator_library_1_1_examples_1_1_canvas_1_1_u_a_l_canvas_example_1aec0783b5a136e042adcc47bae4fe5291)`()` | 
`private void ` [`UserLogin`](#class_universal_authenticator_library_1_1_examples_1_1_canvas_1_1_u_a_l_canvas_example_1a163bfe7d532dad50f4c6a6be0179d2ab)`(` [`User`](UniversalAuthenticatorLibrary--User.md)` _user)` | 
`private async Task ` [`Transfer`](#class_universal_authenticator_library_1_1_examples_1_1_canvas_1_1_u_a_l_canvas_example_1a25397506d3153a001f7a7fa954d7b1f1)`(string frmAcc, string toAcc, string qnty, string memo)` | 

## Members

##### `public ` [`UnityCanvasUAL`](UniversalAuthenticatorLibrary--Src--Canvas--UnityCanvasUAL.md)` ` [`UnityCanvasUAL`](#class_universal_authenticator_library_1_1_examples_1_1_canvas_1_1_u_a_l_canvas_example_1a80913e8bd8a266d2b35aac9812c7caf7) 

##### `public GameObject ` [`TransactionPanel`](#class_universal_authenticator_library_1_1_examples_1_1_canvas_1_1_u_a_l_canvas_example_1a40c2058d3f65a869398ba6d24828071b) 

##### `public void ` [`OnBrowserClipboardPaste`](#class_universal_authenticator_library_1_1_examples_1_1_canvas_1_1_u_a_l_canvas_example_1a009752823a43afe0e10b9e91dfee8ae2)`(string pastedText)` 

Called when ctrl + v is pressed in browser (webgl)

#### Parameters
* `pastedText` The pasted text.

##### `public async void ` [`TryTransferTokens`](#class_universal_authenticator_library_1_1_examples_1_1_canvas_1_1_u_a_l_canvas_example_1a6438f85911eb313073eca6ec1cc2d3fb)`(GameObject TransferDetailsPanel)` 

Gather data from the custom transfer UI panel.

#### Parameters
* `TransferDetailsPanel`

##### `private ` [`User`](UniversalAuthenticatorLibrary--User.md)` ` [`user`](#class_universal_authenticator_library_1_1_examples_1_1_canvas_1_1_u_a_l_canvas_example_1a7ffd636d88d39d8b4366d5423d352b0b) 

##### `private EventSystem ` [`_canvasEventSystem`](#class_universal_authenticator_library_1_1_examples_1_1_canvas_1_1_u_a_l_canvas_example_1acc92c1097922093b8ddd19f150619efa) 

##### `private async void ` [`Start`](#class_universal_authenticator_library_1_1_examples_1_1_canvas_1_1_u_a_l_canvas_example_1a5957aa0d15061f2c6b7145cca4139d83)`()` 

##### `private void ` [`BindButtons`](#class_universal_authenticator_library_1_1_examples_1_1_canvas_1_1_u_a_l_canvas_example_1ac0a62408f7b64fe84a8a710e7119b60b)`()` 

##### `private void ` [`ReturnToAuthenticatorSelection`](#class_universal_authenticator_library_1_1_examples_1_1_canvas_1_1_u_a_l_canvas_example_1a673d166cf5d64fbd7c0da1f932ec3f0a)`()` 

##### `private void ` [`Update`](#class_universal_authenticator_library_1_1_examples_1_1_canvas_1_1_u_a_l_canvas_example_1aec0783b5a136e042adcc47bae4fe5291)`()` 

##### `private void ` [`UserLogin`](#class_universal_authenticator_library_1_1_examples_1_1_canvas_1_1_u_a_l_canvas_example_1a163bfe7d532dad50f4c6a6be0179d2ab)`(` [`User`](UniversalAuthenticatorLibrary--User.md)` _user)` 

##### `private async Task ` [`Transfer`](#class_universal_authenticator_library_1_1_examples_1_1_canvas_1_1_u_a_l_canvas_example_1a25397506d3153a001f7a7fa954d7b1f1)`(string frmAcc, string toAcc, string qnty, string memo)` 

