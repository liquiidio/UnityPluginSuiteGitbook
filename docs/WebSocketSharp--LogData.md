# class `WebSocketSharp::LogData` 

Represents a log data used by the Logger class.

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public StackFrame ` [`Caller`](#class_web_socket_sharp_1_1_log_data_1a4a09325e4600aac70e41092e48487f0a) | Gets the information of the logging method caller.
`public DateTime ` [`Date`](#class_web_socket_sharp_1_1_log_data_1a9f6dd5f0a254ed27ca791fe4aa2c35cf) | Gets the date and time when the log data was created.
`public ` [`LogLevel`](WebSocketSharp.md)` ` [`Level`](#class_web_socket_sharp_1_1_log_data_1a261b732b1fd2e100a1745ccf5477e8fa) | Gets the logging level of the log data.
`public string ` [`Message`](#class_web_socket_sharp_1_1_log_data_1a40e8debace0cc6f4f7baa0fdd309c103) | Gets the message of the log data.
`public override string ` [`ToString`](#class_web_socket_sharp_1_1_log_data_1aa73e7c4dd1df5fd5fbf81c7764ee1533)`()` | Returns a string that represents the current LogData.
`private StackFrame ` [`_caller`](#class_web_socket_sharp_1_1_log_data_1a5955adea42f2a81ffdda82941d6c9f19) | 
`private DateTime ` [`_date`](#class_web_socket_sharp_1_1_log_data_1a7cc33070616df3caed09c5fdc7b41e7f) | 
`private ` [`LogLevel`](WebSocketSharp.md)` ` [`_level`](#class_web_socket_sharp_1_1_log_data_1ac8a6da946b34e252d8cf35820bb1adae) | 
`private string ` [`_message`](#class_web_socket_sharp_1_1_log_data_1ae0a8bbd5b0d900f0dbd444035a9a424c) | 

## Members

##### `public StackFrame ` [`Caller`](#class_web_socket_sharp_1_1_log_data_1a4a09325e4600aac70e41092e48487f0a) 

Gets the information of the logging method caller.

A StackFrame that provides the information of the logging method caller.

##### `public DateTime ` [`Date`](#class_web_socket_sharp_1_1_log_data_1a9f6dd5f0a254ed27ca791fe4aa2c35cf) 

Gets the date and time when the log data was created.

A DateTime that represents the date and time when the log data was created.

##### `public ` [`LogLevel`](WebSocketSharp.md)` ` [`Level`](#class_web_socket_sharp_1_1_log_data_1a261b732b1fd2e100a1745ccf5477e8fa) 

Gets the logging level of the log data.

One of the LogLevel enum values, indicates the logging level of the log data.

##### `public string ` [`Message`](#class_web_socket_sharp_1_1_log_data_1a40e8debace0cc6f4f7baa0fdd309c103) 

Gets the message of the log data.

A string that represents the message of the log data.

##### `public override string ` [`ToString`](#class_web_socket_sharp_1_1_log_data_1aa73e7c4dd1df5fd5fbf81c7764ee1533)`()` 

Returns a string that represents the current LogData.

#### Returns
A string that represents the current LogData.

##### `private StackFrame ` [`_caller`](#class_web_socket_sharp_1_1_log_data_1a5955adea42f2a81ffdda82941d6c9f19) 

##### `private DateTime ` [`_date`](#class_web_socket_sharp_1_1_log_data_1a7cc33070616df3caed09c5fdc7b41e7f) 

##### `private ` [`LogLevel`](WebSocketSharp.md)` ` [`_level`](#class_web_socket_sharp_1_1_log_data_1ac8a6da946b34e252d8cf35820bb1adae) 

##### `private string ` [`_message`](#class_web_socket_sharp_1_1_log_data_1ae0a8bbd5b0d900f0dbd444035a9a424c) 

