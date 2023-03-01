# class `AnchorLinkUnityTransportSharp::UnityTransport` 

```
class AnchorLinkUnityTransportSharp::UnityTransport
  : public ILinkTransport
```

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public ` [`ILinkStorage`](AnchorLinkSharp.md)` ` [`Storage`](#class_anchor_link_unity_transport_sharp_1_1_unity_transport_1a3198c2558a95eb66553955ab4b579438) | 
`public ` [`UnityTransport`](#class_anchor_link_unity_transport_sharp_1_1_unity_transport_1ac17cf84d27619a7170e46e363eee0412)`(` [`TransportOptions`](AnchorLinkUnityTransportSharp--TransportOptions.md)` options)` | 
`public void ` [`OnRequest`](#class_anchor_link_unity_transport_sharp_1_1_unity_transport_1af033a491264433deccf8f379377bf0de)`(` [`SigningRequest`](EosioSigningRequest--SigningRequest.md)` request, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)`< object > cancel)` | 
`public void ` [`OnSuccess`](#class_anchor_link_unity_transport_sharp_1_1_unity_transport_1ae42c87a32bf9bfaf937e577cecc1292a)`(` [`SigningRequest`](EosioSigningRequest--SigningRequest.md)` request, ` [`TransactResult`](AnchorLinkSharp--TransactResult.md)` result)` | 
`public void ` [`OnFailure`](#class_anchor_link_unity_transport_sharp_1_1_unity_transport_1a2881a07d943ba812c2ec609b33efd401)`(` [`SigningRequest`](EosioSigningRequest--SigningRequest.md)` request, Exception exception)` | 
`public void ` [`OnSessionRequest`](#class_anchor_link_unity_transport_sharp_1_1_unity_transport_1a29117d56b61602129466fa858b9810bd)`(` [`LinkSession`](AnchorLinkSharp--LinkSession.md)` session, ` [`SigningRequest`](EosioSigningRequest--SigningRequest.md)` request, object cancel)` | 
`public async Task< ` [`SigningRequest`](EosioSigningRequest--SigningRequest.md)` > ` [`Prepare`](#class_anchor_link_unity_transport_sharp_1_1_unity_transport_1a2ba24fa9a86412c68780ae3157322251)`(` [`SigningRequest`](EosioSigningRequest--SigningRequest.md)` request, ` [`LinkSession`](AnchorLinkSharp--LinkSession.md)` session)` | 
`public void ` [`ShowLoading`](#class_anchor_link_unity_transport_sharp_1_1_unity_transport_1a832760a5318046c0e28d3c99f9a71fa7)`()` | 
`private readonly bool ` [`_requestStatus`](#class_anchor_link_unity_transport_sharp_1_1_unity_transport_1aca210874d7d563cfc1475451b4e26ad1) | 
`private readonly bool ` [`_fuelEnabled`](#class_anchor_link_unity_transport_sharp_1_1_unity_transport_1a97134dea7e38960c1200ad5c5be50185) | 
`private ` [`SigningRequest`](EosioSigningRequest--SigningRequest.md)` ` [`_activeRequest`](#class_anchor_link_unity_transport_sharp_1_1_unity_transport_1a259fde2c0f9f930be8631c1d4427df9a) | 
`private object ` [`_activeCancel`](#class_anchor_link_unity_transport_sharp_1_1_unity_transport_1aa2a37657d0211f348462bcdc0f24fbe8) | 
`private Timer ` [`_countdownTimer`](#class_anchor_link_unity_transport_sharp_1_1_unity_transport_1aafa053c95a04c347610c7a13c85e7a8c) | 
`private Timer ` [`_closeTimer`](#class_anchor_link_unity_transport_sharp_1_1_unity_transport_1a390b89b7162c64f42454a99493adf94f) | 

## Members

##### `public ` [`ILinkStorage`](AnchorLinkSharp.md)` ` [`Storage`](#class_anchor_link_unity_transport_sharp_1_1_unity_transport_1a3198c2558a95eb66553955ab4b579438) 

##### `public ` [`UnityTransport`](#class_anchor_link_unity_transport_sharp_1_1_unity_transport_1ac17cf84d27619a7170e46e363eee0412)`(` [`TransportOptions`](AnchorLinkUnityTransportSharp--TransportOptions.md)` options)` 

##### `public void ` [`OnRequest`](#class_anchor_link_unity_transport_sharp_1_1_unity_transport_1af033a491264433deccf8f379377bf0de)`(` [`SigningRequest`](EosioSigningRequest--SigningRequest.md)` request, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)`< object > cancel)` 

##### `public void ` [`OnSuccess`](#class_anchor_link_unity_transport_sharp_1_1_unity_transport_1ae42c87a32bf9bfaf937e577cecc1292a)`(` [`SigningRequest`](EosioSigningRequest--SigningRequest.md)` request, ` [`TransactResult`](AnchorLinkSharp--TransactResult.md)` result)` 

##### `public void ` [`OnFailure`](#class_anchor_link_unity_transport_sharp_1_1_unity_transport_1a2881a07d943ba812c2ec609b33efd401)`(` [`SigningRequest`](EosioSigningRequest--SigningRequest.md)` request, Exception exception)` 

##### `public void ` [`OnSessionRequest`](#class_anchor_link_unity_transport_sharp_1_1_unity_transport_1a29117d56b61602129466fa858b9810bd)`(` [`LinkSession`](AnchorLinkSharp--LinkSession.md)` session, ` [`SigningRequest`](EosioSigningRequest--SigningRequest.md)` request, object cancel)` 

##### `public async Task< ` [`SigningRequest`](EosioSigningRequest--SigningRequest.md)` > ` [`Prepare`](#class_anchor_link_unity_transport_sharp_1_1_unity_transport_1a2ba24fa9a86412c68780ae3157322251)`(` [`SigningRequest`](EosioSigningRequest--SigningRequest.md)` request, ` [`LinkSession`](AnchorLinkSharp--LinkSession.md)` session)` 

##### `public void ` [`ShowLoading`](#class_anchor_link_unity_transport_sharp_1_1_unity_transport_1a832760a5318046c0e28d3c99f9a71fa7)`()` 

##### `private readonly bool ` [`_requestStatus`](#class_anchor_link_unity_transport_sharp_1_1_unity_transport_1aca210874d7d563cfc1475451b4e26ad1) 

##### `private readonly bool ` [`_fuelEnabled`](#class_anchor_link_unity_transport_sharp_1_1_unity_transport_1a97134dea7e38960c1200ad5c5be50185) 

##### `private ` [`SigningRequest`](EosioSigningRequest--SigningRequest.md)` ` [`_activeRequest`](#class_anchor_link_unity_transport_sharp_1_1_unity_transport_1a259fde2c0f9f930be8631c1d4427df9a) 

##### `private object ` [`_activeCancel`](#class_anchor_link_unity_transport_sharp_1_1_unity_transport_1aa2a37657d0211f348462bcdc0f24fbe8) 

##### `private Timer ` [`_countdownTimer`](#class_anchor_link_unity_transport_sharp_1_1_unity_transport_1aafa053c95a04c347610c7a13c85e7a8c) 

##### `private Timer ` [`_closeTimer`](#class_anchor_link_unity_transport_sharp_1_1_unity_transport_1a390b89b7162c64f42454a99493adf94f) 

