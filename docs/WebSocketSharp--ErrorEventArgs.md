# class `WebSocketSharp::ErrorEventArgs` 

```
class WebSocketSharp::ErrorEventArgs
  : public EventArgs
```

Represents the event data for the WebSocket.OnError event.

That event occurs when the WebSocket gets an error. 

If you would like to get the error message, you should access the ErrorEventArgs.Message property. 

And if the error is due to an exception, you can get it by accessing the ErrorEventArgs.Exception property.

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public Exception ` [`Exception`](#class_web_socket_sharp_1_1_error_event_args_1a75f456e07534eb091bd4c71b194ec90e) | Gets the exception that caused the error.
`public string ` [`Message`](#class_web_socket_sharp_1_1_error_event_args_1a40e8debace0cc6f4f7baa0fdd309c103) | Gets the error message.
`private ` [`Exception`](#class_web_socket_sharp_1_1_error_event_args_1a75f456e07534eb091bd4c71b194ec90e)` ` [`_exception`](#class_web_socket_sharp_1_1_error_event_args_1abcfe8ca61795cb92992dab20d4cb59f3) | 
`private string ` [`_message`](#class_web_socket_sharp_1_1_error_event_args_1ae0a8bbd5b0d900f0dbd444035a9a424c) | 

## Members

##### `public Exception ` [`Exception`](#class_web_socket_sharp_1_1_error_event_args_1a75f456e07534eb091bd4c71b194ec90e) 

Gets the exception that caused the error.

An System.Exception instance that represents the cause of the error if it is due to an exception; otherwise, `null`.

##### `public string ` [`Message`](#class_web_socket_sharp_1_1_error_event_args_1a40e8debace0cc6f4f7baa0fdd309c103) 

Gets the error message.

A string that represents the error message.

##### `private ` [`Exception`](#class_web_socket_sharp_1_1_error_event_args_1a75f456e07534eb091bd4c71b194ec90e)` ` [`_exception`](#class_web_socket_sharp_1_1_error_event_args_1abcfe8ca61795cb92992dab20d4cb59f3) 

##### `private string ` [`_message`](#class_web_socket_sharp_1_1_error_event_args_1ae0a8bbd5b0d900f0dbd444035a9a424c) 

