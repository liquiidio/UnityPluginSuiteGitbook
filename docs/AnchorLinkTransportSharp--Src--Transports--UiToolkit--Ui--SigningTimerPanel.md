# class `AnchorLinkTransportSharp::Src::Transports::UiToolkit::Ui::SigningTimerPanel` 

```
class AnchorLinkTransportSharp::Src::Transports::UiToolkit::Ui::SigningTimerPanel
  : public PanelBase
```

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`package string ` [`CountdownText`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_ui_toolkit_1_1_ui_1_1_signing_timer_panel_1aea35f1a5398bcdf185ebdeda7aae882d) | 
`private Label ` [`_signManualLabel`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_ui_toolkit_1_1_ui_1_1_signing_timer_panel_1a849c373c577d3e85a70077ff57708f52) | Child-Controls
`private Label ` [`_singingTimerLabel`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_ui_toolkit_1_1_ui_1_1_signing_timer_panel_1a586cea763f4e54d4a8b588e79ad89ba6) | 
`private Coroutine ` [`_counterCoroutine`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_ui_toolkit_1_1_ui_1_1_signing_timer_panel_1a8d9ab4ca92bf90c3108e1bf97c61952e) | 
`private void ` [`Start`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_ui_toolkit_1_1_ui_1_1_signing_timer_panel_1a07aaf1227e4d645f15e0a964f54ef291)`()` | 
`private void ` [`BindButtons`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_ui_toolkit_1_1_ui_1_1_signing_timer_panel_1ac0a62408f7b64fe84a8a710e7119b60b)`()` | Assign UI toolkit interaction events.
`private IEnumerator ` [`ScheduleTimer`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_ui_toolkit_1_1_ui_1_1_signing_timer_panel_1a304b94c240d8dd1e11359c9d4babecb0)`(float counterDuration)` | Countdown coroutine that exits after timer reaches zero.

## Members

##### `package string ` [`CountdownText`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_ui_toolkit_1_1_ui_1_1_signing_timer_panel_1aea35f1a5398bcdf185ebdeda7aae882d) 

##### `private Label ` [`_signManualLabel`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_ui_toolkit_1_1_ui_1_1_signing_timer_panel_1a849c373c577d3e85a70077ff57708f52) 

Child-Controls

##### `private Label ` [`_singingTimerLabel`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_ui_toolkit_1_1_ui_1_1_signing_timer_panel_1a586cea763f4e54d4a8b588e79ad89ba6) 

##### `private Coroutine ` [`_counterCoroutine`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_ui_toolkit_1_1_ui_1_1_signing_timer_panel_1a8d9ab4ca92bf90c3108e1bf97c61952e) 

##### `private void ` [`Start`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_ui_toolkit_1_1_ui_1_1_signing_timer_panel_1a07aaf1227e4d645f15e0a964f54ef291)`()` 

##### `private void ` [`BindButtons`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_ui_toolkit_1_1_ui_1_1_signing_timer_panel_1ac0a62408f7b64fe84a8a710e7119b60b)`()` 

Assign UI toolkit interaction events.

##### `private IEnumerator ` [`ScheduleTimer`](#class_anchor_link_transport_sharp_1_1_src_1_1_transports_1_1_ui_toolkit_1_1_ui_1_1_signing_timer_panel_1a304b94c240d8dd1e11359c9d4babecb0)`(float counterDuration)` 

Countdown coroutine that exits after timer reaches zero.

#### Parameters
* `counterDuration` 

#### Returns

