# class `WebSocketSharp::WebSocketFrame` 

```
class WebSocketSharp::WebSocketFrame
  : public IEnumerable< byte >
```

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`package ulong ` [`ExactPayloadLength`](#class_web_socket_sharp_1_1_web_socket_frame_1a2597913e0e1e8b96beb716c392a03099) | 
`package int ` [`ExtendedPayloadLengthWidth`](#class_web_socket_sharp_1_1_web_socket_frame_1a0ca3b781feae89746926ac1055fb33b8) | 
`public byte[] ` [`ExtendedPayloadLength`](#class_web_socket_sharp_1_1_web_socket_frame_1a0f005a6b65b0c8d254bb14ded64465b8) | 
`public ` [`Fin`](WebSocketSharp.md)` ` [`Fin`](#class_web_socket_sharp_1_1_web_socket_frame_1aad7391ca40d3dfba7f7030b860eb0d78) | 
`public bool ` [`IsBinary`](#class_web_socket_sharp_1_1_web_socket_frame_1ac20ab8dd3673e3d34c24baedcb1ae05c) | 
`public bool ` [`IsClose`](#class_web_socket_sharp_1_1_web_socket_frame_1a653e0a550a2919ea86865271dc962e4f) | 
`public bool ` [`IsCompressed`](#class_web_socket_sharp_1_1_web_socket_frame_1a65c59e7e1354d5cba0194556939974b7) | 
`public bool ` [`IsContinuation`](#class_web_socket_sharp_1_1_web_socket_frame_1acfd9e8139ed77683241ff76b2d6d2b1f) | 
`public bool ` [`IsControl`](#class_web_socket_sharp_1_1_web_socket_frame_1a88852e0121e370f84734c16f9e1e6589) | 
`public bool ` [`IsData`](#class_web_socket_sharp_1_1_web_socket_frame_1ae6b244f234b78e3305b6690a93377c3f) | 
`public bool ` [`IsFinal`](#class_web_socket_sharp_1_1_web_socket_frame_1a696e673333201e973b485e6e4bc7d99d) | 
`public bool ` [`IsFragment`](#class_web_socket_sharp_1_1_web_socket_frame_1aaa4c9f4adf84745f454e57aebe8b82db) | 
`public bool ` [`IsMasked`](#class_web_socket_sharp_1_1_web_socket_frame_1a0b1ed268426b88af4835cf3d6b080c83) | 
`public bool ` [`IsPing`](#class_web_socket_sharp_1_1_web_socket_frame_1a5041039ae75897932439de503bcf6353) | 
`public bool ` [`IsPong`](#class_web_socket_sharp_1_1_web_socket_frame_1a1173adedaf47d88f3a816a18a9d0824a) | 
`public bool ` [`IsText`](#class_web_socket_sharp_1_1_web_socket_frame_1ade87479ca45b0411f46103b5cd180594) | 
`public ulong ` [`Length`](#class_web_socket_sharp_1_1_web_socket_frame_1af57d54d7e52c68ff922dc602e92e877e) | 
`public ` [`Mask`](WebSocketSharp.md)` ` [`Mask`](#class_web_socket_sharp_1_1_web_socket_frame_1a5ba15efee03bee8428a0dad81b8a90fe) | 
`public byte[] ` [`MaskingKey`](#class_web_socket_sharp_1_1_web_socket_frame_1a3d14215020cedbb4e3d94ebf67095615) | 
`public ` [`Opcode`](WebSocketSharp.md)` ` [`Opcode`](#class_web_socket_sharp_1_1_web_socket_frame_1a5f36c8d4334d62264583e3780665cace) | 
`public ` [`PayloadData`](WebSocketSharp--PayloadData.md)` ` [`PayloadData`](#class_web_socket_sharp_1_1_web_socket_frame_1ae1a41ca4d73c55d93b165f43213f970e) | 
`public byte ` [`PayloadLength`](#class_web_socket_sharp_1_1_web_socket_frame_1a5ecbcf07e817d62fba3dea1aef41a509) | 
`public ` [`Rsv`](WebSocketSharp.md)` ` [`Rsv1`](#class_web_socket_sharp_1_1_web_socket_frame_1a46679985ca7dff680ef5687103ff7ce1) | 
`public ` [`Rsv`](WebSocketSharp.md)` ` [`Rsv2`](#class_web_socket_sharp_1_1_web_socket_frame_1a8ddbc19b1d4a756ad00cb8fedcae9804) | 
`public ` [`Rsv`](WebSocketSharp.md)` ` [`Rsv3`](#class_web_socket_sharp_1_1_web_socket_frame_1af4a17ccb76c6cd446ad8ac485ec9bdd9) | 
`public IEnumerator< byte > ` [`GetEnumerator`](#class_web_socket_sharp_1_1_web_socket_frame_1a6b87250fa032ce4914ca2c127aabec89)`()` | 
`public void ` [`Print`](#class_web_socket_sharp_1_1_web_socket_frame_1a60d8fce2ea4cf1a44f2387163fa5dba3)`(bool dumped)` | 
`public string ` [`PrintToString`](#class_web_socket_sharp_1_1_web_socket_frame_1a0f05954feb40baacf6846ae0e4f01598)`(bool dumped)` | 
`public byte[] ` [`ToArray`](#class_web_socket_sharp_1_1_web_socket_frame_1a32a13bca0d50bf570b8d20c6a77e913a)`()` | 
`public override string ` [`ToString`](#class_web_socket_sharp_1_1_web_socket_frame_1aa73e7c4dd1df5fd5fbf81c7764ee1533)`()` | 
`private byte[] ` [`_extPayloadLength`](#class_web_socket_sharp_1_1_web_socket_frame_1ac7e8f98b5c3950fcb803adc8e1aa5a9e) | 
`private ` [`Fin`](WebSocketSharp.md)` ` [`_fin`](#class_web_socket_sharp_1_1_web_socket_frame_1ab47724e4b7af9a1170e98dfab4d8ac41) | 
`private ` [`Mask`](WebSocketSharp.md)` ` [`_mask`](#class_web_socket_sharp_1_1_web_socket_frame_1a966a535d8ce0f3e0a4f64e36cbe1a569) | 
`private byte[] ` [`_maskingKey`](#class_web_socket_sharp_1_1_web_socket_frame_1adb98cfa743b1552edcbc338985d835bb) | 
`private ` [`Opcode`](WebSocketSharp.md)` ` [`_opcode`](#class_web_socket_sharp_1_1_web_socket_frame_1a894ffc3aeb669e6b542fb3f587307fa2) | 
`private ` [`PayloadData`](WebSocketSharp--PayloadData.md)` ` [`_payloadData`](#class_web_socket_sharp_1_1_web_socket_frame_1aaf672d560272d42207991600d13b253f) | 
`private byte ` [`_payloadLength`](#class_web_socket_sharp_1_1_web_socket_frame_1aa7a51728065dac3c6568c1600a026c12) | 
`private ` [`Rsv`](WebSocketSharp.md)` ` [`_rsv1`](#class_web_socket_sharp_1_1_web_socket_frame_1aa525c4f131ee107b3f86dc221923f981) | 
`private ` [`Rsv`](WebSocketSharp.md)` ` [`_rsv2`](#class_web_socket_sharp_1_1_web_socket_frame_1aa92d0ed00b8aaf89a3e56ba4ab0db661) | 
`private ` [`Rsv`](WebSocketSharp.md)` ` [`_rsv3`](#class_web_socket_sharp_1_1_web_socket_frame_1a0c655dddbc7d91acebd57325e08e9131) | 
`private ` [`WebSocketFrame`](#class_web_socket_sharp_1_1_web_socket_frame_1a05565ce3706200e5c2644a6a6d22071c)`()` | 
`private IEnumerator IEnumerable. ` [`GetEnumerator`](#class_web_socket_sharp_1_1_web_socket_frame_1a7d819d2ba8ffadd29113c811ce043c9f)`()` | 
`private static static ` [`WebSocketFrame`](#class_web_socket_sharp_1_1_web_socket_frame_1ad13589cc43f25f16fd42b22f8ffc9099)`()` | 
`private static byte[] ` [`createMaskingKey`](#class_web_socket_sharp_1_1_web_socket_frame_1a205ce3a0dbe69cbb56df82346c69d17b)`()` | 
`private static string ` [`dump`](#class_web_socket_sharp_1_1_web_socket_frame_1a2fd825b593d9cc66428d28363e844a36)`(` [`WebSocketFrame`](#class_web_socket_sharp_1_1_web_socket_frame)` frame)` | 
`private static string ` [`print`](#class_web_socket_sharp_1_1_web_socket_frame_1a2f953c8875b97c99b210bbbef0d4e565)`(` [`WebSocketFrame`](#class_web_socket_sharp_1_1_web_socket_frame)` frame)` | 
`private static ` [`WebSocketFrame`](#class_web_socket_sharp_1_1_web_socket_frame)` ` [`processHeader`](#class_web_socket_sharp_1_1_web_socket_frame_1ae7a0b18e1ffdeb855fc8be1a703bfc78)`(byte[] header)` | 
`private static ` [`WebSocketFrame`](#class_web_socket_sharp_1_1_web_socket_frame)` ` [`readExtendedPayloadLength`](#class_web_socket_sharp_1_1_web_socket_frame_1af07e68523389d16cbcea99ac72ac2167)`(Stream stream, ` [`WebSocketFrame`](#class_web_socket_sharp_1_1_web_socket_frame)` frame)` | 
`private static void ` [`readExtendedPayloadLengthAsync`](#class_web_socket_sharp_1_1_web_socket_frame_1aedbeb5a64f4f47d9b193f005362111ac)`(Stream stream, ` [`WebSocketFrame`](#class_web_socket_sharp_1_1_web_socket_frame)` frame, ` [`Action](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)< [WebSocketFrame`](#class_web_socket_sharp_1_1_web_socket_frame)` > completed, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)`< Exception > error)` | 
`private static ` [`WebSocketFrame`](#class_web_socket_sharp_1_1_web_socket_frame)` ` [`readHeader`](#class_web_socket_sharp_1_1_web_socket_frame_1ac9e4355f388866f76a176b39f725fac4)`(Stream stream)` | 
`private static void ` [`readHeaderAsync`](#class_web_socket_sharp_1_1_web_socket_frame_1a7196f7d6b98264934f10d9cb1af24fab)`(Stream stream, ` [`Action](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)< [WebSocketFrame`](#class_web_socket_sharp_1_1_web_socket_frame)` > completed, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)`< Exception > error)` | 
`private static ` [`WebSocketFrame`](#class_web_socket_sharp_1_1_web_socket_frame)` ` [`readMaskingKey`](#class_web_socket_sharp_1_1_web_socket_frame_1a47b113698ef7c8616c804d1774f5c53f)`(Stream stream, ` [`WebSocketFrame`](#class_web_socket_sharp_1_1_web_socket_frame)` frame)` | 
`private static void ` [`readMaskingKeyAsync`](#class_web_socket_sharp_1_1_web_socket_frame_1a112fdff861afa0f3809daf47f1cf7f00)`(Stream stream, ` [`WebSocketFrame`](#class_web_socket_sharp_1_1_web_socket_frame)` frame, ` [`Action](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)< [WebSocketFrame`](#class_web_socket_sharp_1_1_web_socket_frame)` > completed, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)`< Exception > error)` | 
`private static ` [`WebSocketFrame`](#class_web_socket_sharp_1_1_web_socket_frame)` ` [`readPayloadData`](#class_web_socket_sharp_1_1_web_socket_frame_1ad25a8da89ad4a18144d68371b6a7fcdb)`(Stream stream, ` [`WebSocketFrame`](#class_web_socket_sharp_1_1_web_socket_frame)` frame)` | 
`private static void ` [`readPayloadDataAsync`](#class_web_socket_sharp_1_1_web_socket_frame_1a811894fbf238dff285c12447b0a798be)`(Stream stream, ` [`WebSocketFrame`](#class_web_socket_sharp_1_1_web_socket_frame)` frame, ` [`Action](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)< [WebSocketFrame`](#class_web_socket_sharp_1_1_web_socket_frame)` > completed, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)`< Exception > error)` | 
`private static string ` [`utf8Decode`](#class_web_socket_sharp_1_1_web_socket_frame_1a0f4a28f4963ea3799cb2b32af0dd0370)`(byte[] bytes)` | 

## Members

##### `package ulong ` [`ExactPayloadLength`](#class_web_socket_sharp_1_1_web_socket_frame_1a2597913e0e1e8b96beb716c392a03099) 

##### `package int ` [`ExtendedPayloadLengthWidth`](#class_web_socket_sharp_1_1_web_socket_frame_1a0ca3b781feae89746926ac1055fb33b8) 

##### `public byte[] ` [`ExtendedPayloadLength`](#class_web_socket_sharp_1_1_web_socket_frame_1a0f005a6b65b0c8d254bb14ded64465b8) 

##### `public ` [`Fin`](WebSocketSharp.md)` ` [`Fin`](#class_web_socket_sharp_1_1_web_socket_frame_1aad7391ca40d3dfba7f7030b860eb0d78) 

##### `public bool ` [`IsBinary`](#class_web_socket_sharp_1_1_web_socket_frame_1ac20ab8dd3673e3d34c24baedcb1ae05c) 

##### `public bool ` [`IsClose`](#class_web_socket_sharp_1_1_web_socket_frame_1a653e0a550a2919ea86865271dc962e4f) 

##### `public bool ` [`IsCompressed`](#class_web_socket_sharp_1_1_web_socket_frame_1a65c59e7e1354d5cba0194556939974b7) 

##### `public bool ` [`IsContinuation`](#class_web_socket_sharp_1_1_web_socket_frame_1acfd9e8139ed77683241ff76b2d6d2b1f) 

##### `public bool ` [`IsControl`](#class_web_socket_sharp_1_1_web_socket_frame_1a88852e0121e370f84734c16f9e1e6589) 

##### `public bool ` [`IsData`](#class_web_socket_sharp_1_1_web_socket_frame_1ae6b244f234b78e3305b6690a93377c3f) 

##### `public bool ` [`IsFinal`](#class_web_socket_sharp_1_1_web_socket_frame_1a696e673333201e973b485e6e4bc7d99d) 

##### `public bool ` [`IsFragment`](#class_web_socket_sharp_1_1_web_socket_frame_1aaa4c9f4adf84745f454e57aebe8b82db) 

##### `public bool ` [`IsMasked`](#class_web_socket_sharp_1_1_web_socket_frame_1a0b1ed268426b88af4835cf3d6b080c83) 

##### `public bool ` [`IsPing`](#class_web_socket_sharp_1_1_web_socket_frame_1a5041039ae75897932439de503bcf6353) 

##### `public bool ` [`IsPong`](#class_web_socket_sharp_1_1_web_socket_frame_1a1173adedaf47d88f3a816a18a9d0824a) 

##### `public bool ` [`IsText`](#class_web_socket_sharp_1_1_web_socket_frame_1ade87479ca45b0411f46103b5cd180594) 

##### `public ulong ` [`Length`](#class_web_socket_sharp_1_1_web_socket_frame_1af57d54d7e52c68ff922dc602e92e877e) 

##### `public ` [`Mask`](WebSocketSharp.md)` ` [`Mask`](#class_web_socket_sharp_1_1_web_socket_frame_1a5ba15efee03bee8428a0dad81b8a90fe) 

##### `public byte[] ` [`MaskingKey`](#class_web_socket_sharp_1_1_web_socket_frame_1a3d14215020cedbb4e3d94ebf67095615) 

##### `public ` [`Opcode`](WebSocketSharp.md)` ` [`Opcode`](#class_web_socket_sharp_1_1_web_socket_frame_1a5f36c8d4334d62264583e3780665cace) 

##### `public ` [`PayloadData`](WebSocketSharp--PayloadData.md)` ` [`PayloadData`](#class_web_socket_sharp_1_1_web_socket_frame_1ae1a41ca4d73c55d93b165f43213f970e) 

##### `public byte ` [`PayloadLength`](#class_web_socket_sharp_1_1_web_socket_frame_1a5ecbcf07e817d62fba3dea1aef41a509) 

##### `public ` [`Rsv`](WebSocketSharp.md)` ` [`Rsv1`](#class_web_socket_sharp_1_1_web_socket_frame_1a46679985ca7dff680ef5687103ff7ce1) 

##### `public ` [`Rsv`](WebSocketSharp.md)` ` [`Rsv2`](#class_web_socket_sharp_1_1_web_socket_frame_1a8ddbc19b1d4a756ad00cb8fedcae9804) 

##### `public ` [`Rsv`](WebSocketSharp.md)` ` [`Rsv3`](#class_web_socket_sharp_1_1_web_socket_frame_1af4a17ccb76c6cd446ad8ac485ec9bdd9) 

##### `public IEnumerator< byte > ` [`GetEnumerator`](#class_web_socket_sharp_1_1_web_socket_frame_1a6b87250fa032ce4914ca2c127aabec89)`()` 

##### `public void ` [`Print`](#class_web_socket_sharp_1_1_web_socket_frame_1a60d8fce2ea4cf1a44f2387163fa5dba3)`(bool dumped)` 

##### `public string ` [`PrintToString`](#class_web_socket_sharp_1_1_web_socket_frame_1a0f05954feb40baacf6846ae0e4f01598)`(bool dumped)` 

##### `public byte[] ` [`ToArray`](#class_web_socket_sharp_1_1_web_socket_frame_1a32a13bca0d50bf570b8d20c6a77e913a)`()` 

##### `public override string ` [`ToString`](#class_web_socket_sharp_1_1_web_socket_frame_1aa73e7c4dd1df5fd5fbf81c7764ee1533)`()` 

##### `private byte[] ` [`_extPayloadLength`](#class_web_socket_sharp_1_1_web_socket_frame_1ac7e8f98b5c3950fcb803adc8e1aa5a9e) 

##### `private ` [`Fin`](WebSocketSharp.md)` ` [`_fin`](#class_web_socket_sharp_1_1_web_socket_frame_1ab47724e4b7af9a1170e98dfab4d8ac41) 

##### `private ` [`Mask`](WebSocketSharp.md)` ` [`_mask`](#class_web_socket_sharp_1_1_web_socket_frame_1a966a535d8ce0f3e0a4f64e36cbe1a569) 

##### `private byte[] ` [`_maskingKey`](#class_web_socket_sharp_1_1_web_socket_frame_1adb98cfa743b1552edcbc338985d835bb) 

##### `private ` [`Opcode`](WebSocketSharp.md)` ` [`_opcode`](#class_web_socket_sharp_1_1_web_socket_frame_1a894ffc3aeb669e6b542fb3f587307fa2) 

##### `private ` [`PayloadData`](WebSocketSharp--PayloadData.md)` ` [`_payloadData`](#class_web_socket_sharp_1_1_web_socket_frame_1aaf672d560272d42207991600d13b253f) 

##### `private byte ` [`_payloadLength`](#class_web_socket_sharp_1_1_web_socket_frame_1aa7a51728065dac3c6568c1600a026c12) 

##### `private ` [`Rsv`](WebSocketSharp.md)` ` [`_rsv1`](#class_web_socket_sharp_1_1_web_socket_frame_1aa525c4f131ee107b3f86dc221923f981) 

##### `private ` [`Rsv`](WebSocketSharp.md)` ` [`_rsv2`](#class_web_socket_sharp_1_1_web_socket_frame_1aa92d0ed00b8aaf89a3e56ba4ab0db661) 

##### `private ` [`Rsv`](WebSocketSharp.md)` ` [`_rsv3`](#class_web_socket_sharp_1_1_web_socket_frame_1a0c655dddbc7d91acebd57325e08e9131) 

##### `private ` [`WebSocketFrame`](#class_web_socket_sharp_1_1_web_socket_frame_1a05565ce3706200e5c2644a6a6d22071c)`()` 

##### `private IEnumerator IEnumerable. ` [`GetEnumerator`](#class_web_socket_sharp_1_1_web_socket_frame_1a7d819d2ba8ffadd29113c811ce043c9f)`()` 

##### `private static static ` [`WebSocketFrame`](#class_web_socket_sharp_1_1_web_socket_frame_1ad13589cc43f25f16fd42b22f8ffc9099)`()` 

##### `private static byte[] ` [`createMaskingKey`](#class_web_socket_sharp_1_1_web_socket_frame_1a205ce3a0dbe69cbb56df82346c69d17b)`()` 

##### `private static string ` [`dump`](#class_web_socket_sharp_1_1_web_socket_frame_1a2fd825b593d9cc66428d28363e844a36)`(` [`WebSocketFrame`](#class_web_socket_sharp_1_1_web_socket_frame)` frame)` 

##### `private static string ` [`print`](#class_web_socket_sharp_1_1_web_socket_frame_1a2f953c8875b97c99b210bbbef0d4e565)`(` [`WebSocketFrame`](#class_web_socket_sharp_1_1_web_socket_frame)` frame)` 

##### `private static ` [`WebSocketFrame`](#class_web_socket_sharp_1_1_web_socket_frame)` ` [`processHeader`](#class_web_socket_sharp_1_1_web_socket_frame_1ae7a0b18e1ffdeb855fc8be1a703bfc78)`(byte[] header)` 

##### `private static ` [`WebSocketFrame`](#class_web_socket_sharp_1_1_web_socket_frame)` ` [`readExtendedPayloadLength`](#class_web_socket_sharp_1_1_web_socket_frame_1af07e68523389d16cbcea99ac72ac2167)`(Stream stream, ` [`WebSocketFrame`](#class_web_socket_sharp_1_1_web_socket_frame)` frame)` 

##### `private static void ` [`readExtendedPayloadLengthAsync`](#class_web_socket_sharp_1_1_web_socket_frame_1aedbeb5a64f4f47d9b193f005362111ac)`(Stream stream, ` [`WebSocketFrame`](#class_web_socket_sharp_1_1_web_socket_frame)` frame, ` [`Action](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)< [WebSocketFrame`](#class_web_socket_sharp_1_1_web_socket_frame)` > completed, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)`< Exception > error)` 

##### `private static ` [`WebSocketFrame`](#class_web_socket_sharp_1_1_web_socket_frame)` ` [`readHeader`](#class_web_socket_sharp_1_1_web_socket_frame_1ac9e4355f388866f76a176b39f725fac4)`(Stream stream)` 

##### `private static void ` [`readHeaderAsync`](#class_web_socket_sharp_1_1_web_socket_frame_1a7196f7d6b98264934f10d9cb1af24fab)`(Stream stream, ` [`Action](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)< [WebSocketFrame`](#class_web_socket_sharp_1_1_web_socket_frame)` > completed, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)`< Exception > error)` 

##### `private static ` [`WebSocketFrame`](#class_web_socket_sharp_1_1_web_socket_frame)` ` [`readMaskingKey`](#class_web_socket_sharp_1_1_web_socket_frame_1a47b113698ef7c8616c804d1774f5c53f)`(Stream stream, ` [`WebSocketFrame`](#class_web_socket_sharp_1_1_web_socket_frame)` frame)` 

##### `private static void ` [`readMaskingKeyAsync`](#class_web_socket_sharp_1_1_web_socket_frame_1a112fdff861afa0f3809daf47f1cf7f00)`(Stream stream, ` [`WebSocketFrame`](#class_web_socket_sharp_1_1_web_socket_frame)` frame, ` [`Action](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)< [WebSocketFrame`](#class_web_socket_sharp_1_1_web_socket_frame)` > completed, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)`< Exception > error)` 

##### `private static ` [`WebSocketFrame`](#class_web_socket_sharp_1_1_web_socket_frame)` ` [`readPayloadData`](#class_web_socket_sharp_1_1_web_socket_frame_1ad25a8da89ad4a18144d68371b6a7fcdb)`(Stream stream, ` [`WebSocketFrame`](#class_web_socket_sharp_1_1_web_socket_frame)` frame)` 

##### `private static void ` [`readPayloadDataAsync`](#class_web_socket_sharp_1_1_web_socket_frame_1a811894fbf238dff285c12447b0a798be)`(Stream stream, ` [`WebSocketFrame`](#class_web_socket_sharp_1_1_web_socket_frame)` frame, ` [`Action](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)< [WebSocketFrame`](#class_web_socket_sharp_1_1_web_socket_frame)` > completed, ` [`Action`](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)`< Exception > error)` 

##### `private static string ` [`utf8Decode`](#class_web_socket_sharp_1_1_web_socket_frame_1a0f4a28f4963ea3799cb2b32af0dd0370)`(byte[] bytes)` 

