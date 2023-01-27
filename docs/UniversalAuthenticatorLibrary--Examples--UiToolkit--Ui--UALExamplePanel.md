# class `UniversalAuthenticatorLibrary::Examples::UiToolkit::Ui::UALExamplePanel` 

```
class UniversalAuthenticatorLibrary::Examples::UiToolkit::Ui::UALExamplePanel
  : public ScreenBase
```

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public async void ` [`Rebind`](#class_universal_authenticator_library_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_u_a_l_example_panel_1ab378c14625c2a991edc88100c89561f6)`(` [`User`](UniversalAuthenticatorLibrary--User.md)` user)` | 
`public void ` [`OnBrowserClipboardPaste`](#class_universal_authenticator_library_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_u_a_l_example_panel_1a009752823a43afe0e10b9e91dfee8ae2)`(string pastedText)` | Called when ctrl + v is pressed in browser (webgl)
`private Button ` [`_changeToBidNameButton`](#class_universal_authenticator_library_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_u_a_l_example_panel_1ac7c73aa8fa9bfe4ba0d2e6d659a346ce) | Child-Controls
`private Button ` [`_changeToBuyRamButton`](#class_universal_authenticator_library_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_u_a_l_example_panel_1a0f24036b720fc6ca717c7ce2874022a7) | 
`private Button ` [`_changeToSellRamButton`](#class_universal_authenticator_library_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_u_a_l_example_panel_1a21ffd5348d4a37dd3cd7d2dcd161fdcd) | 
`private Button ` [`_changeToTransferButton`](#class_universal_authenticator_library_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_u_a_l_example_panel_1a7ae01c8e220149d4ee6b19fa45e1959b) | 
`private Button ` [`_changeToVoteButton`](#class_universal_authenticator_library_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_u_a_l_example_panel_1aa85068f1b522b1ecf4a5f6ea864e2ceb) | 
`private Button ` [`_bidButton`](#class_universal_authenticator_library_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_u_a_l_example_panel_1a6880a0dad448008db46cba4774fd8f57) | 
`private Button ` [`_buyRamButton`](#class_universal_authenticator_library_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_u_a_l_example_panel_1a5089c8cda8e3bffd6151a37a6bef6082) | 
`private Button ` [`_transferTokenButton`](#class_universal_authenticator_library_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_u_a_l_example_panel_1ac6d6d0de392ca9d8f482e0cee2b81f7b) | 
`private Button ` [`_voteButton`](#class_universal_authenticator_library_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_u_a_l_example_panel_1afc09fb4200cf4d201876ac764a32372b) | 
`private Button ` [`_sellRamButton`](#class_universal_authenticator_library_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_u_a_l_example_panel_1a9a9142f62111d3191cede6029943c154) | 
`private Button ` [`_logoutButton`](#class_universal_authenticator_library_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_u_a_l_example_panel_1a447a79b3836e7bc65b7cc7b1572a3ae6) | 
`private VisualElement ` [`_sellRamBox`](#class_universal_authenticator_library_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_u_a_l_example_panel_1a443512555902ec306c197fffd8994572) | 
`private VisualElement ` [`_transferTokenBox`](#class_universal_authenticator_library_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_u_a_l_example_panel_1ad230772cfc6da2fd9e5c3943015769e7) | 
`private VisualElement ` [`_bidNameBox`](#class_universal_authenticator_library_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_u_a_l_example_panel_1af0183409a7aca13640f533076c4e1f65) | 
`private VisualElement ` [`_buyRamBox`](#class_universal_authenticator_library_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_u_a_l_example_panel_1aaa9199bb06aa72126759e9c576a687ae) | 
`private VisualElement ` [`_voteBox`](#class_universal_authenticator_library_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_u_a_l_example_panel_1ab33985a9fb31c8e8c7423fa874e4f734) | 
`private Label ` [`_accountLabel`](#class_universal_authenticator_library_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_u_a_l_example_panel_1a3985401b5d20cc08776363a38095d411) | 
`private ` [`User`](UniversalAuthenticatorLibrary--User.md)` ` [`_user`](#class_universal_authenticator_library_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_u_a_l_example_panel_1a0e4623cfba2f709f9712c50e474b8722) | 
`private void ` [`Start`](#class_universal_authenticator_library_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_u_a_l_example_panel_1a07aaf1227e4d645f15e0a964f54ef291)`()` | 
`private void ` [`BindButtons`](#class_universal_authenticator_library_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_u_a_l_example_panel_1ac0a62408f7b64fe84a8a710e7119b60b)`()` | 
`private void ` [`SetTransferAccountText`](#class_universal_authenticator_library_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_u_a_l_example_panel_1ab8d2fea12b0b68a71ac1900c411ad1de)`()` | 
`private void ` [`SetSellRamText`](#class_universal_authenticator_library_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_u_a_l_example_panel_1a04df316e1b48502dc1a11dccf1741d14)`()` | 
`private void ` [`SetBuyRamText`](#class_universal_authenticator_library_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_u_a_l_example_panel_1abb62aae70d0490ae16485974f788ff80)`()` | 
`private void ` [`SetBidNameText`](#class_universal_authenticator_library_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_u_a_l_example_panel_1aea934c7204b2977c74d78b45cdc0c596)`()` | 
`public static void ` [`MultiExampleClipboardPaste`](#class_universal_authenticator_library_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_u_a_l_example_panel_1a21d6386abd2ee0bb933d9a54d743c01f)`(string pastedText)` | Called when ctrl + v is pressed in browser for the PluginSuiteMultiExample Scene (webgl)

## Members

##### `public async void ` [`Rebind`](#class_universal_authenticator_library_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_u_a_l_example_panel_1ab378c14625c2a991edc88100c89561f6)`(` [`User`](UniversalAuthenticatorLibrary--User.md)` user)` 

##### `public void ` [`OnBrowserClipboardPaste`](#class_universal_authenticator_library_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_u_a_l_example_panel_1a009752823a43afe0e10b9e91dfee8ae2)`(string pastedText)` 

Called when ctrl + v is pressed in browser (webgl)

#### Parameters
* `pastedText` The pasted text.

##### `private Button ` [`_changeToBidNameButton`](#class_universal_authenticator_library_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_u_a_l_example_panel_1ac7c73aa8fa9bfe4ba0d2e6d659a346ce) 

Child-Controls

##### `private Button ` [`_changeToBuyRamButton`](#class_universal_authenticator_library_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_u_a_l_example_panel_1a0f24036b720fc6ca717c7ce2874022a7) 

##### `private Button ` [`_changeToSellRamButton`](#class_universal_authenticator_library_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_u_a_l_example_panel_1a21ffd5348d4a37dd3cd7d2dcd161fdcd) 

##### `private Button ` [`_changeToTransferButton`](#class_universal_authenticator_library_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_u_a_l_example_panel_1a7ae01c8e220149d4ee6b19fa45e1959b) 

##### `private Button ` [`_changeToVoteButton`](#class_universal_authenticator_library_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_u_a_l_example_panel_1aa85068f1b522b1ecf4a5f6ea864e2ceb) 

##### `private Button ` [`_bidButton`](#class_universal_authenticator_library_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_u_a_l_example_panel_1a6880a0dad448008db46cba4774fd8f57) 

##### `private Button ` [`_buyRamButton`](#class_universal_authenticator_library_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_u_a_l_example_panel_1a5089c8cda8e3bffd6151a37a6bef6082) 

##### `private Button ` [`_transferTokenButton`](#class_universal_authenticator_library_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_u_a_l_example_panel_1ac6d6d0de392ca9d8f482e0cee2b81f7b) 

##### `private Button ` [`_voteButton`](#class_universal_authenticator_library_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_u_a_l_example_panel_1afc09fb4200cf4d201876ac764a32372b) 

##### `private Button ` [`_sellRamButton`](#class_universal_authenticator_library_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_u_a_l_example_panel_1a9a9142f62111d3191cede6029943c154) 

##### `private Button ` [`_logoutButton`](#class_universal_authenticator_library_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_u_a_l_example_panel_1a447a79b3836e7bc65b7cc7b1572a3ae6) 

##### `private VisualElement ` [`_sellRamBox`](#class_universal_authenticator_library_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_u_a_l_example_panel_1a443512555902ec306c197fffd8994572) 

##### `private VisualElement ` [`_transferTokenBox`](#class_universal_authenticator_library_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_u_a_l_example_panel_1ad230772cfc6da2fd9e5c3943015769e7) 

##### `private VisualElement ` [`_bidNameBox`](#class_universal_authenticator_library_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_u_a_l_example_panel_1af0183409a7aca13640f533076c4e1f65) 

##### `private VisualElement ` [`_buyRamBox`](#class_universal_authenticator_library_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_u_a_l_example_panel_1aaa9199bb06aa72126759e9c576a687ae) 

##### `private VisualElement ` [`_voteBox`](#class_universal_authenticator_library_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_u_a_l_example_panel_1ab33985a9fb31c8e8c7423fa874e4f734) 

##### `private Label ` [`_accountLabel`](#class_universal_authenticator_library_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_u_a_l_example_panel_1a3985401b5d20cc08776363a38095d411) 

##### `private ` [`User`](UniversalAuthenticatorLibrary--User.md)` ` [`_user`](#class_universal_authenticator_library_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_u_a_l_example_panel_1a0e4623cfba2f709f9712c50e474b8722) 

##### `private void ` [`Start`](#class_universal_authenticator_library_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_u_a_l_example_panel_1a07aaf1227e4d645f15e0a964f54ef291)`()` 

##### `private void ` [`BindButtons`](#class_universal_authenticator_library_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_u_a_l_example_panel_1ac0a62408f7b64fe84a8a710e7119b60b)`()` 

##### `private void ` [`SetTransferAccountText`](#class_universal_authenticator_library_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_u_a_l_example_panel_1ab8d2fea12b0b68a71ac1900c411ad1de)`()` 

##### `private void ` [`SetSellRamText`](#class_universal_authenticator_library_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_u_a_l_example_panel_1a04df316e1b48502dc1a11dccf1741d14)`()` 

##### `private void ` [`SetBuyRamText`](#class_universal_authenticator_library_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_u_a_l_example_panel_1abb62aae70d0490ae16485974f788ff80)`()` 

##### `private void ` [`SetBidNameText`](#class_universal_authenticator_library_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_u_a_l_example_panel_1aea934c7204b2977c74d78b45cdc0c596)`()` 

##### `public static void ` [`MultiExampleClipboardPaste`](#class_universal_authenticator_library_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_u_a_l_example_panel_1a21d6386abd2ee0bb933d9a54d743c01f)`(string pastedText)` 

Called when ctrl + v is pressed in browser for the PluginSuiteMultiExample Scene (webgl)

#### Parameters
* `pastedText` The pasted text.

