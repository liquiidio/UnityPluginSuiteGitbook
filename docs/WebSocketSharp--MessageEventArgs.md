# class `WebSocketSharp::MessageEventArgs` 

```
class WebSocketSharp::MessageEventArgs
  : public EventArgs
```

Represents the event data for the WebSocket.OnMessage event.

That event occurs when the WebSocket receives a message or a ping if the WebSocket.EmitOnPing property is set to `true`. 

If you would like to get the message data, you should access the Data or RawData property.

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`package ` [`Opcode`](WebSocketSharp.md)` ` [`Opcode`](#class_web_socket_sharp_1_1_message_event_args_1a5f36c8d4334d62264583e3780665cace) | Gets the opcode for the message.
`public string ` [`Data`](#class_web_socket_sharp_1_1_message_event_args_1a0df039919c9cd4ab27611e3addb611c1) | Gets the message data as a string.
`public bool ` [`IsBinary`](#class_web_socket_sharp_1_1_message_event_args_1ac20ab8dd3673e3d34c24baedcb1ae05c) | Gets a value indicating whether the message type is binary.
`public bool ` [`IsPing`](#class_web_socket_sharp_1_1_message_event_args_1a5041039ae75897932439de503bcf6353) | Gets a value indicating whether the message type is ping.
`public bool ` [`IsText`](#class_web_socket_sharp_1_1_message_event_args_1ade87479ca45b0411f46103b5cd180594) | Gets a value indicating whether the message type is text.
`public byte[] ` [`RawData`](#class_web_socket_sharp_1_1_message_event_args_1a2734354c737bed6f59a60c9e5b59b4bf) | Gets the message data as an array of byte.
`private string ` [`_data`](#class_web_socket_sharp_1_1_message_event_args_1a1db10c6a9e09f46ef6f70004150c9f69) | 
`private bool ` [`_dataSet`](#class_web_socket_sharp_1_1_message_event_args_1a2ad7de5a05e587dccb185f0c2cbbfd4b) | 
`private ` [`Opcode`](WebSocketSharp.md)` ` [`_opcode`](#class_web_socket_sharp_1_1_message_event_args_1a894ffc3aeb669e6b542fb3f587307fa2) | 
`private byte[] ` [`_rawData`](#class_web_socket_sharp_1_1_message_event_args_1af09d23305f85b1ec41993f8592c4c67f) | 
`private void ` [`setData`](#class_web_socket_sharp_1_1_message_event_args_1a7432d9e5ee1087f766f00f2d83696a67)`()` | 

## Members

##### `package ` [`Opcode`](WebSocketSharp.md)` ` [`Opcode`](#class_web_socket_sharp_1_1_message_event_args_1a5f36c8d4334d62264583e3780665cace) 

Gets the opcode for the message.

MediaTypeNames.Text, Opcode.Binary, or Ping.

##### `public string ` [`Data`](#class_web_socket_sharp_1_1_message_event_args_1a0df039919c9cd4ab27611e3addb611c1) 

Gets the message data as a string.

A string that represents the message data if its type is text or ping and if decoding it to a string has successfully done; otherwise, `null`.

##### `public bool ` [`IsBinary`](#class_web_socket_sharp_1_1_message_event_args_1ac20ab8dd3673e3d34c24baedcb1ae05c) 

Gets a value indicating whether the message type is binary.

`true` if the message type is binary; otherwise, `false`.

##### `public bool ` [`IsPing`](#class_web_socket_sharp_1_1_message_event_args_1a5041039ae75897932439de503bcf6353) 

Gets a value indicating whether the message type is ping.

`true` if the message type is ping; otherwise, `false`.

##### `public bool ` [`IsText`](#class_web_socket_sharp_1_1_message_event_args_1ade87479ca45b0411f46103b5cd180594) 

Gets a value indicating whether the message type is text.

`true` if the message type is text; otherwise, `false`.

##### `public byte[] ` [`RawData`](#class_web_socket_sharp_1_1_message_event_args_1a2734354c737bed6f59a60c9e5b59b4bf) 

Gets the message data as an array of byte.

An array of byte that represents the message data.

##### `private string ` [`_data`](#class_web_socket_sharp_1_1_message_event_args_1a1db10c6a9e09f46ef6f70004150c9f69) 

##### `private bool ` [`_dataSet`](#class_web_socket_sharp_1_1_message_event_args_1a2ad7de5a05e587dccb185f0c2cbbfd4b) 

##### `private ` [`Opcode`](WebSocketSharp.md)` ` [`_opcode`](#class_web_socket_sharp_1_1_message_event_args_1a894ffc3aeb669e6b542fb3f587307fa2) 

##### `private byte[] ` [`_rawData`](#class_web_socket_sharp_1_1_message_event_args_1af09d23305f85b1ec41993f8592c4c67f) 

##### `private void ` [`setData`](#class_web_socket_sharp_1_1_message_event_args_1a7432d9e5ee1087f766f00f2d83696a67)`()` 

