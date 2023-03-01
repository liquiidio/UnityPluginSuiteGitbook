# class `WebSocketSharp::Logger` 

Provides a set of methods and properties for logging.

If you output a log with lower than the value of the Logger.Level property, it cannot be outputted. 

The default output action writes a log to the standard output stream and the log file if the Logger.File property has a valid path to it. 

If you would like to use the custom output action, you should set the Logger.Output property to any `Action<LogData, string>` delegate.

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public string ` [`File`](#class_web_socket_sharp_1_1_logger_1a61b3286023daa81d7a68da1bbd3b6bdb) | Gets or sets the current path to the log file.
`public ` [`LogLevel`](WebSocketSharp.md)` ` [`Level`](#class_web_socket_sharp_1_1_logger_1a261b732b1fd2e100a1745ccf5477e8fa) | Gets or sets the current logging level.
`public ` [`Action](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)< [LogData`](WebSocketSharp--LogData.md)`, string > ` [`Output`](#class_web_socket_sharp_1_1_logger_1aabe4abbba70118025b2761a23229674f) | Gets or sets the current output action used to output a log.
`public ` [`Logger`](#class_web_socket_sharp_1_1_logger_1a4fac0c9f6ee2dce6abd726264b9195f7)`()` | Initializes a new instance of the Logger class.
`public ` [`Logger`](#class_web_socket_sharp_1_1_logger_1afb4a40a114f6b7d89c8a517550acca4c)`(` [`LogLevel`](WebSocketSharp.md)` level)` | Initializes a new instance of the Logger class with the specified logging *level* .
`public ` [`Logger`](#class_web_socket_sharp_1_1_logger_1a73e02f4281cbcea91ec349c022a02006)`(` [`LogLevel`](WebSocketSharp.md)` level, string file, ` [`Action](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)< [LogData`](WebSocketSharp--LogData.md)`, string > output)` | Initializes a new instance of the Logger class with the specified logging *level* , path to the log *file* , and *output* action.
`public void ` [`Debug`](#class_web_socket_sharp_1_1_logger_1ad53b6a03d6e0d46e89be828d0c5dd53f)`(string message)` | Outputs *message* as a log with LogLevel.Debug.
`public void ` [`Error`](#class_web_socket_sharp_1_1_logger_1ace6b9df8609d512f6e90f00214a935d0)`(string message)` | Outputs *message* as a log with LogLevel.Error.
`public void ` [`Fatal`](#class_web_socket_sharp_1_1_logger_1af11d2b7baf68a19319e811642de41ef6)`(string message)` | Outputs *message* as a log with LogLevel.Fatal.
`public void ` [`Info`](#class_web_socket_sharp_1_1_logger_1af8b6272be88a9fe7f64161d01813f218)`(string message)` | Outputs *message* as a log with LogLevel.Info.
`public void ` [`Trace`](#class_web_socket_sharp_1_1_logger_1aae01c16226e703fd8d5956de6c524755)`(string message)` | Outputs *message* as a log with LogLevel.Trace.
`public void ` [`Warn`](#class_web_socket_sharp_1_1_logger_1aa19290e7e5352347a2bb60378595b767)`(string message)` | Outputs *message* as a log with LogLevel.Warn.
`private volatile string ` [`_file`](#class_web_socket_sharp_1_1_logger_1a3b4460eec76cda348bc02312f30e4c35) | 
`private volatile ` [`LogLevel`](WebSocketSharp.md)` ` [`_level`](#class_web_socket_sharp_1_1_logger_1abb525228e950037f5111fc65ca84cc91) | 
`private ` [`Action](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)< [LogData`](WebSocketSharp--LogData.md)`, string > ` [`_output`](#class_web_socket_sharp_1_1_logger_1a28ff5b017f454ac2db8cc89af5fed73a) | 
`private object ` [`_sync`](#class_web_socket_sharp_1_1_logger_1adbb069fcd0e2b452bc3342bc00739ed8) | 
`private void ` [`output`](#class_web_socket_sharp_1_1_logger_1a1d23c324ac2cc182e07e19e2a84be467)`(string message, ` [`LogLevel`](WebSocketSharp.md)` level)` | 
`private static void ` [`defaultOutput`](#class_web_socket_sharp_1_1_logger_1a4fece87f430fe2c7f0e81b571aef1925)`(` [`LogData`](WebSocketSharp--LogData.md)` data, string path)` | 
`private static void ` [`writeToFile`](#class_web_socket_sharp_1_1_logger_1a9c516a044e348aeb3b13cf95849b3776)`(string value, string path)` | 

## Members

##### `public string ` [`File`](#class_web_socket_sharp_1_1_logger_1a61b3286023daa81d7a68da1bbd3b6bdb) 

Gets or sets the current path to the log file.

A string that represents the current path to the log file if any.

##### `public ` [`LogLevel`](WebSocketSharp.md)` ` [`Level`](#class_web_socket_sharp_1_1_logger_1a261b732b1fd2e100a1745ccf5477e8fa) 

Gets or sets the current logging level.

A log with lower than the value of this property cannot be outputted. 

One of the LogLevel enum values, specifies the current logging level.

##### `public ` [`Action](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)< [LogData`](WebSocketSharp--LogData.md)`, string > ` [`Output`](#class_web_socket_sharp_1_1_logger_1aabe4abbba70118025b2761a23229674f) 

Gets or sets the current output action used to output a log.

An `Action<LogData, string>` delegate that references the method(s) used to output a log. A string parameter passed to this delegate is the value of the Logger.File property. 

If the value to set is `null`, the current output action is changed to the default output action.

##### `public ` [`Logger`](#class_web_socket_sharp_1_1_logger_1a4fac0c9f6ee2dce6abd726264b9195f7)`()` 

Initializes a new instance of the Logger class.

This constructor initializes the current logging level with LogLevel.Error.

##### `public ` [`Logger`](#class_web_socket_sharp_1_1_logger_1afb4a40a114f6b7d89c8a517550acca4c)`(` [`LogLevel`](WebSocketSharp.md)` level)` 

Initializes a new instance of the Logger class with the specified logging *level* .

#### Parameters
* `level` One of the LogLevel enum values.

##### `public ` [`Logger`](#class_web_socket_sharp_1_1_logger_1a73e02f4281cbcea91ec349c022a02006)`(` [`LogLevel`](WebSocketSharp.md)` level, string file, ` [`Action](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)< [LogData`](WebSocketSharp--LogData.md)`, string > output)` 

Initializes a new instance of the Logger class with the specified logging *level* , path to the log *file* , and *output*  action.

#### Parameters
* `level` One of the LogLevel enum values. 

* `file` A string that represents the path to the log file. 

* `output` An `Action<LogData, string>` delegate that references the method(s) used to output a log. A string parameter passed to this delegate is *file* .

##### `public void ` [`Debug`](#class_web_socket_sharp_1_1_logger_1ad53b6a03d6e0d46e89be828d0c5dd53f)`(string message)` 

Outputs *message*  as a log with LogLevel.Debug.

If the current logging level is higher than LogLevel.Debug, this method doesn't output *message*  as a log. 

#### Parameters
* `message` A string that represents the message to output as a log.

##### `public void ` [`Error`](#class_web_socket_sharp_1_1_logger_1ace6b9df8609d512f6e90f00214a935d0)`(string message)` 

Outputs *message*  as a log with LogLevel.Error.

If the current logging level is higher than LogLevel.Error, this method doesn't output *message*  as a log. 

#### Parameters
* `message` A string that represents the message to output as a log.

##### `public void ` [`Fatal`](#class_web_socket_sharp_1_1_logger_1af11d2b7baf68a19319e811642de41ef6)`(string message)` 

Outputs *message*  as a log with LogLevel.Fatal.

#### Parameters
* `message` A string that represents the message to output as a log.

##### `public void ` [`Info`](#class_web_socket_sharp_1_1_logger_1af8b6272be88a9fe7f64161d01813f218)`(string message)` 

Outputs *message*  as a log with LogLevel.Info.

If the current logging level is higher than LogLevel.Info, this method doesn't output *message*  as a log. 

#### Parameters
* `message` A string that represents the message to output as a log.

##### `public void ` [`Trace`](#class_web_socket_sharp_1_1_logger_1aae01c16226e703fd8d5956de6c524755)`(string message)` 

Outputs *message*  as a log with LogLevel.Trace.

If the current logging level is higher than LogLevel.Trace, this method doesn't output *message*  as a log. 

#### Parameters
* `message` A string that represents the message to output as a log.

##### `public void ` [`Warn`](#class_web_socket_sharp_1_1_logger_1aa19290e7e5352347a2bb60378595b767)`(string message)` 

Outputs *message*  as a log with LogLevel.Warn.

If the current logging level is higher than LogLevel.Warn, this method doesn't output *message*  as a log. 

#### Parameters
* `message` A string that represents the message to output as a log.

##### `private volatile string ` [`_file`](#class_web_socket_sharp_1_1_logger_1a3b4460eec76cda348bc02312f30e4c35) 

##### `private volatile ` [`LogLevel`](WebSocketSharp.md)` ` [`_level`](#class_web_socket_sharp_1_1_logger_1abb525228e950037f5111fc65ca84cc91) 

##### `private ` [`Action](#_unit_test1_8cs_1a24e91c56095a0673d92c6eac6e069a3c)< [LogData`](WebSocketSharp--LogData.md)`, string > ` [`_output`](#class_web_socket_sharp_1_1_logger_1a28ff5b017f454ac2db8cc89af5fed73a) 

##### `private object ` [`_sync`](#class_web_socket_sharp_1_1_logger_1adbb069fcd0e2b452bc3342bc00739ed8) 

##### `private void ` [`output`](#class_web_socket_sharp_1_1_logger_1a1d23c324ac2cc182e07e19e2a84be467)`(string message, ` [`LogLevel`](WebSocketSharp.md)` level)` 

##### `private static void ` [`defaultOutput`](#class_web_socket_sharp_1_1_logger_1a4fece87f430fe2c7f0e81b571aef1925)`(` [`LogData`](WebSocketSharp--LogData.md)` data, string path)` 

##### `private static void ` [`writeToFile`](#class_web_socket_sharp_1_1_logger_1a9c516a044e348aeb3b13cf95849b3776)`(string value, string path)` 

