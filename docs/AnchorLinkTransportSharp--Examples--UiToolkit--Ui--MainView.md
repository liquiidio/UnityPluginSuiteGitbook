# class `AnchorLinkTransportSharp::Examples::UiToolkit::Ui::MainView` 

```
class AnchorLinkTransportSharp::Examples::UiToolkit::Ui::MainView
  : public ScreenBase
```

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public void ` [`OnBrowserClipboardPaste`](#class_anchor_link_transport_sharp_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_main_view_1a009752823a43afe0e10b9e91dfee8ae2)`(string pastedText)` | Called when ctrl + v is pressed in browser (webgl)
`private Button ` [`_changeToBidNameButton`](#class_anchor_link_transport_sharp_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_main_view_1ac7c73aa8fa9bfe4ba0d2e6d659a346ce) | Child-Controls
`private Button ` [`_changeToBuyRamButton`](#class_anchor_link_transport_sharp_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_main_view_1a0f24036b720fc6ca717c7ce2874022a7) | 
`private Button ` [`_changeToRestoreSessionButton`](#class_anchor_link_transport_sharp_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_main_view_1a0f31c2a8951edd6f46a5f5d3bd55303f) | 
`private Button ` [`_changeToSellRamButton`](#class_anchor_link_transport_sharp_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_main_view_1a21ffd5348d4a37dd3cd7d2dcd161fdcd) | 
`private Button ` [`_changeToTransferButton`](#class_anchor_link_transport_sharp_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_main_view_1a7ae01c8e220149d4ee6b19fa45e1959b) | 
`private Button ` [`_changeToVoteButton`](#class_anchor_link_transport_sharp_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_main_view_1aa85068f1b522b1ecf4a5f6ea864e2ceb) | 
`private Button ` [`_bidButton`](#class_anchor_link_transport_sharp_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_main_view_1a6880a0dad448008db46cba4774fd8f57) | 
`private Button ` [`_buyRamButton`](#class_anchor_link_transport_sharp_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_main_view_1a5089c8cda8e3bffd6151a37a6bef6082) | 
`private Button ` [`_transferTokenButton`](#class_anchor_link_transport_sharp_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_main_view_1ac6d6d0de392ca9d8f482e0cee2b81f7b) | 
`private Button ` [`_voteButton`](#class_anchor_link_transport_sharp_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_main_view_1afc09fb4200cf4d201876ac764a32372b) | 
`private Button ` [`_sellRamButton`](#class_anchor_link_transport_sharp_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_main_view_1a9a9142f62111d3191cede6029943c154) | 
`private Button ` [`_logoutButton`](#class_anchor_link_transport_sharp_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_main_view_1a447a79b3836e7bc65b7cc7b1572a3ae6) | 
`private TextField ` [`_toTextField`](#class_anchor_link_transport_sharp_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_main_view_1a2cc54f6a7b58fd65029cb0d5382fa1ae) | 
`private TextField ` [`_fromTextField`](#class_anchor_link_transport_sharp_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_main_view_1a871512e0e20d054224927791ed8741ed) | 
`private TextField ` [`_memoTextField`](#class_anchor_link_transport_sharp_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_main_view_1ab823d6fdae6298d9b476bdfacd2c64a3) | 
`private TextField ` [`_nameToBidTextField`](#class_anchor_link_transport_sharp_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_main_view_1a5d3cb99d7f5a4aee96b4c663d645d10b) | 
`private TextField ` [`_quantityTextField`](#class_anchor_link_transport_sharp_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_main_view_1a407de0db96b44e273044507ab078c7f1) | 
`private TextField ` [`_receiverAccountTextField`](#class_anchor_link_transport_sharp_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_main_view_1a578686eb753953fde8db1af3d2c58b4d) | 
`private TextField ` [`_userAccountTextField`](#class_anchor_link_transport_sharp_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_main_view_1a00ddd7a17c67b327dafcf5609d0c46b5) | 
`private TextField ` [`_sellRamAmountTextField`](#class_anchor_link_transport_sharp_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_main_view_1aee910684f9b5e60a25c15ab225d6634e) | 
`private TextField ` [`_amountToBuyTextField`](#class_anchor_link_transport_sharp_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_main_view_1a3b990681d5885ecc2b16f949a839b7e1) | 
`private TextField ` [`_amountWaxTextField`](#class_anchor_link_transport_sharp_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_main_view_1aa48ad1a6ef7f3fca4eaf0799599d5f4c) | 
`private TextField ` [`_bidAmountTextField`](#class_anchor_link_transport_sharp_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_main_view_1ab518c1e06df1bf6cd42a00dd98003ad8) | 
`private VisualElement ` [`_sellRamBox`](#class_anchor_link_transport_sharp_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_main_view_1a443512555902ec306c197fffd8994572) | 
`private VisualElement ` [`_transferTokenBox`](#class_anchor_link_transport_sharp_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_main_view_1ad230772cfc6da2fd9e5c3943015769e7) | 
`private VisualElement ` [`_bidNameBox`](#class_anchor_link_transport_sharp_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_main_view_1af0183409a7aca13640f533076c4e1f65) | 
`private VisualElement ` [`_buyRamBox`](#class_anchor_link_transport_sharp_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_main_view_1aaa9199bb06aa72126759e9c576a687ae) | 
`private VisualElement ` [`_voteBox`](#class_anchor_link_transport_sharp_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_main_view_1ab33985a9fb31c8e8c7423fa874e4f734) | 
`private Label ` [`_subtitleLabel`](#class_anchor_link_transport_sharp_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_main_view_1aeb62caba75bc09150d07bc04e7bf6742) | 
`private Label ` [`_loginTitleLabel`](#class_anchor_link_transport_sharp_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_main_view_1aa37a06ebec2e3dda8268b0a304373867) | 
`private Label ` [`_accountLabel`](#class_anchor_link_transport_sharp_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_main_view_1a3985401b5d20cc08776363a38095d411) | 
`private void ` [`Start`](#class_anchor_link_transport_sharp_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_main_view_1a07aaf1227e4d645f15e0a964f54ef291)`()` | 
`private void ` [`BindButtons`](#class_anchor_link_transport_sharp_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_main_view_1ac0a62408f7b64fe84a8a710e7119b60b)`()` | Assign UI toolkit interaction events.
`private void ` [`SetTransferAccountText`](#class_anchor_link_transport_sharp_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_main_view_1ab8d2fea12b0b68a71ac1900c411ad1de)`()` | Assign default values to the currency transfer window variables.
`private void ` [`SetSellRamText`](#class_anchor_link_transport_sharp_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_main_view_1a04df316e1b48502dc1a11dccf1741d14)`()` | Assign default values to the sell RAM transfer window variables.
`private void ` [`SetBuyRamText`](#class_anchor_link_transport_sharp_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_main_view_1abb62aae70d0490ae16485974f788ff80)`()` | Assign default values to the buy RAM transfer window variables.
`private void ` [`SetBidNameText`](#class_anchor_link_transport_sharp_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_main_view_1aea934c7204b2977c74d78b45cdc0c596)`()` | Assign default values to the bid window variables.

## Members

##### `public void ` [`OnBrowserClipboardPaste`](#class_anchor_link_transport_sharp_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_main_view_1a009752823a43afe0e10b9e91dfee8ae2)`(string pastedText)` 

Called when ctrl + v is pressed in browser (webgl)

#### Parameters
* `pastedText` The pasted text.

##### `private Button ` [`_changeToBidNameButton`](#class_anchor_link_transport_sharp_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_main_view_1ac7c73aa8fa9bfe4ba0d2e6d659a346ce) 

Child-Controls

##### `private Button ` [`_changeToBuyRamButton`](#class_anchor_link_transport_sharp_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_main_view_1a0f24036b720fc6ca717c7ce2874022a7) 

##### `private Button ` [`_changeToRestoreSessionButton`](#class_anchor_link_transport_sharp_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_main_view_1a0f31c2a8951edd6f46a5f5d3bd55303f) 

##### `private Button ` [`_changeToSellRamButton`](#class_anchor_link_transport_sharp_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_main_view_1a21ffd5348d4a37dd3cd7d2dcd161fdcd) 

##### `private Button ` [`_changeToTransferButton`](#class_anchor_link_transport_sharp_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_main_view_1a7ae01c8e220149d4ee6b19fa45e1959b) 

##### `private Button ` [`_changeToVoteButton`](#class_anchor_link_transport_sharp_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_main_view_1aa85068f1b522b1ecf4a5f6ea864e2ceb) 

##### `private Button ` [`_bidButton`](#class_anchor_link_transport_sharp_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_main_view_1a6880a0dad448008db46cba4774fd8f57) 

##### `private Button ` [`_buyRamButton`](#class_anchor_link_transport_sharp_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_main_view_1a5089c8cda8e3bffd6151a37a6bef6082) 

##### `private Button ` [`_transferTokenButton`](#class_anchor_link_transport_sharp_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_main_view_1ac6d6d0de392ca9d8f482e0cee2b81f7b) 

##### `private Button ` [`_voteButton`](#class_anchor_link_transport_sharp_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_main_view_1afc09fb4200cf4d201876ac764a32372b) 

##### `private Button ` [`_sellRamButton`](#class_anchor_link_transport_sharp_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_main_view_1a9a9142f62111d3191cede6029943c154) 

##### `private Button ` [`_logoutButton`](#class_anchor_link_transport_sharp_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_main_view_1a447a79b3836e7bc65b7cc7b1572a3ae6) 

##### `private TextField ` [`_toTextField`](#class_anchor_link_transport_sharp_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_main_view_1a2cc54f6a7b58fd65029cb0d5382fa1ae) 

##### `private TextField ` [`_fromTextField`](#class_anchor_link_transport_sharp_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_main_view_1a871512e0e20d054224927791ed8741ed) 

##### `private TextField ` [`_memoTextField`](#class_anchor_link_transport_sharp_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_main_view_1ab823d6fdae6298d9b476bdfacd2c64a3) 

##### `private TextField ` [`_nameToBidTextField`](#class_anchor_link_transport_sharp_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_main_view_1a5d3cb99d7f5a4aee96b4c663d645d10b) 

##### `private TextField ` [`_quantityTextField`](#class_anchor_link_transport_sharp_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_main_view_1a407de0db96b44e273044507ab078c7f1) 

##### `private TextField ` [`_receiverAccountTextField`](#class_anchor_link_transport_sharp_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_main_view_1a578686eb753953fde8db1af3d2c58b4d) 

##### `private TextField ` [`_userAccountTextField`](#class_anchor_link_transport_sharp_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_main_view_1a00ddd7a17c67b327dafcf5609d0c46b5) 

##### `private TextField ` [`_sellRamAmountTextField`](#class_anchor_link_transport_sharp_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_main_view_1aee910684f9b5e60a25c15ab225d6634e) 

##### `private TextField ` [`_amountToBuyTextField`](#class_anchor_link_transport_sharp_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_main_view_1a3b990681d5885ecc2b16f949a839b7e1) 

##### `private TextField ` [`_amountWaxTextField`](#class_anchor_link_transport_sharp_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_main_view_1aa48ad1a6ef7f3fca4eaf0799599d5f4c) 

##### `private TextField ` [`_bidAmountTextField`](#class_anchor_link_transport_sharp_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_main_view_1ab518c1e06df1bf6cd42a00dd98003ad8) 

##### `private VisualElement ` [`_sellRamBox`](#class_anchor_link_transport_sharp_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_main_view_1a443512555902ec306c197fffd8994572) 

##### `private VisualElement ` [`_transferTokenBox`](#class_anchor_link_transport_sharp_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_main_view_1ad230772cfc6da2fd9e5c3943015769e7) 

##### `private VisualElement ` [`_bidNameBox`](#class_anchor_link_transport_sharp_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_main_view_1af0183409a7aca13640f533076c4e1f65) 

##### `private VisualElement ` [`_buyRamBox`](#class_anchor_link_transport_sharp_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_main_view_1aaa9199bb06aa72126759e9c576a687ae) 

##### `private VisualElement ` [`_voteBox`](#class_anchor_link_transport_sharp_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_main_view_1ab33985a9fb31c8e8c7423fa874e4f734) 

##### `private Label ` [`_subtitleLabel`](#class_anchor_link_transport_sharp_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_main_view_1aeb62caba75bc09150d07bc04e7bf6742) 

##### `private Label ` [`_loginTitleLabel`](#class_anchor_link_transport_sharp_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_main_view_1aa37a06ebec2e3dda8268b0a304373867) 

##### `private Label ` [`_accountLabel`](#class_anchor_link_transport_sharp_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_main_view_1a3985401b5d20cc08776363a38095d411) 

##### `private void ` [`Start`](#class_anchor_link_transport_sharp_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_main_view_1a07aaf1227e4d645f15e0a964f54ef291)`()` 

##### `private void ` [`BindButtons`](#class_anchor_link_transport_sharp_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_main_view_1ac0a62408f7b64fe84a8a710e7119b60b)`()` 

Assign UI toolkit interaction events.

##### `private void ` [`SetTransferAccountText`](#class_anchor_link_transport_sharp_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_main_view_1ab8d2fea12b0b68a71ac1900c411ad1de)`()` 

Assign default values to the currency transfer window variables.

##### `private void ` [`SetSellRamText`](#class_anchor_link_transport_sharp_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_main_view_1a04df316e1b48502dc1a11dccf1741d14)`()` 

Assign default values to the sell RAM transfer window variables.

##### `private void ` [`SetBuyRamText`](#class_anchor_link_transport_sharp_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_main_view_1abb62aae70d0490ae16485974f788ff80)`()` 

Assign default values to the buy RAM transfer window variables.

##### `private void ` [`SetBidNameText`](#class_anchor_link_transport_sharp_1_1_examples_1_1_ui_toolkit_1_1_ui_1_1_main_view_1aea934c7204b2977c74d78b45cdc0c596)`()` 

Assign default values to the bid window variables.

