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
`public async void ` [`TryTransferTokens`](#class_universal_authenticator_library_1_1_examples_1_1_canvas_1_1_u_a_l_canvas_example_1a6438f85911eb313073eca6ec1cc2d3fb)`(GameObject TransferDetailsPanel)` | Gather data from the custom transfer UI panel.
`private ` [`User`](UniversalAuthenticatorLibrary--User.md)` ` [`user`](#class_universal_authenticator_library_1_1_examples_1_1_canvas_1_1_u_a_l_canvas_example_1a7ffd636d88d39d8b4366d5423d352b0b) | 
`private void ` [`Start`](#class_universal_authenticator_library_1_1_examples_1_1_canvas_1_1_u_a_l_canvas_example_1a07aaf1227e4d645f15e0a964f54ef291)`()` | 
`private void ` [`BindButtons`](#class_universal_authenticator_library_1_1_examples_1_1_canvas_1_1_u_a_l_canvas_example_1ac0a62408f7b64fe84a8a710e7119b60b)`()` | 
`private void ` [`ReturnToAuthenticatorSelection`](#class_universal_authenticator_library_1_1_examples_1_1_canvas_1_1_u_a_l_canvas_example_1a673d166cf5d64fbd7c0da1f932ec3f0a)`()` | 
`private void ` [`UserLogin`](#class_universal_authenticator_library_1_1_examples_1_1_canvas_1_1_u_a_l_canvas_example_1a163bfe7d532dad50f4c6a6be0179d2ab)`(` [`User`](UniversalAuthenticatorLibrary--User.md)` _user)` | 
`private async Task ` [`Transfer`](#class_universal_authenticator_library_1_1_examples_1_1_canvas_1_1_u_a_l_canvas_example_1a25397506d3153a001f7a7fa954d7b1f1)`(string frmAcc, string toAcc, string qnty, string memo)` | 

## Members

##### `public ` [`UnityCanvasUAL`](UniversalAuthenticatorLibrary--Src--Canvas--UnityCanvasUAL.md)` ` [`UnityCanvasUAL`](#class_universal_authenticator_library_1_1_examples_1_1_canvas_1_1_u_a_l_canvas_example_1a80913e8bd8a266d2b35aac9812c7caf7) 

##### `public GameObject ` [`TransactionPanel`](#class_universal_authenticator_library_1_1_examples_1_1_canvas_1_1_u_a_l_canvas_example_1a40c2058d3f65a869398ba6d24828071b) 

##### `public async void ` [`TryTransferTokens`](#class_universal_authenticator_library_1_1_examples_1_1_canvas_1_1_u_a_l_canvas_example_1a6438f85911eb313073eca6ec1cc2d3fb)`(GameObject TransferDetailsPanel)` 

Gather data from the custom transfer UI panel.

#### Parameters
* `TransferDetailsPanel`

##### `private ` [`User`](UniversalAuthenticatorLibrary--User.md)` ` [`user`](#class_universal_authenticator_library_1_1_examples_1_1_canvas_1_1_u_a_l_canvas_example_1a7ffd636d88d39d8b4366d5423d352b0b) 

##### `private void ` [`Start`](#class_universal_authenticator_library_1_1_examples_1_1_canvas_1_1_u_a_l_canvas_example_1a07aaf1227e4d645f15e0a964f54ef291)`()` 

##### `private void ` [`BindButtons`](#class_universal_authenticator_library_1_1_examples_1_1_canvas_1_1_u_a_l_canvas_example_1ac0a62408f7b64fe84a8a710e7119b60b)`()` 

##### `private void ` [`ReturnToAuthenticatorSelection`](#class_universal_authenticator_library_1_1_examples_1_1_canvas_1_1_u_a_l_canvas_example_1a673d166cf5d64fbd7c0da1f932ec3f0a)`()` 

##### `private void ` [`UserLogin`](#class_universal_authenticator_library_1_1_examples_1_1_canvas_1_1_u_a_l_canvas_example_1a163bfe7d532dad50f4c6a6be0179d2ab)`(` [`User`](UniversalAuthenticatorLibrary--User.md)` _user)` 

##### `private async Task ` [`Transfer`](#class_universal_authenticator_library_1_1_examples_1_1_canvas_1_1_u_a_l_canvas_example_1a25397506d3153a001f7a7fa954d7b1f1)`(string frmAcc, string toAcc, string qnty, string memo)` 

