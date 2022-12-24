# class `AnchorLinkSharp::LinkException` 

```
class AnchorLinkSharp::LinkException
  : public Exception
```

Error codes. Accessible using the `code` property on errors thrown by [[AnchorLink]] and [[LinkSession]].

* `E_DELIVERY`: Unable to request message to wallet.

* `E_TIMEOUT`: Request was delivered but user/wallet didn't respond in time.

* `E_CANCEL`: The [[LinkTransport]] canceled the request.

* `E_IDENTITY`: Identity proof failed to verify.

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public ` [`LinkErrorCode`](AnchorLinkSharp.md)` ` [`Code`](#class_anchor_link_sharp_1_1_link_exception_1ac439edf1a8b44fc129d679671e87645f) | 
`protected ` [`LinkException`](#class_anchor_link_sharp_1_1_link_exception_1aa1a6e1d171100385ce40667757946a8d)`(string reason)` | 

## Members

##### `public ` [`LinkErrorCode`](AnchorLinkSharp.md)` ` [`Code`](#class_anchor_link_sharp_1_1_link_exception_1ac439edf1a8b44fc129d679671e87645f) 

##### `protected ` [`LinkException`](#class_anchor_link_sharp_1_1_link_exception_1aa1a6e1d171100385ce40667757946a8d)`(string reason)` 

