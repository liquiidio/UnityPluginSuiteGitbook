# class `WebSocketSharp::Net::ServerSslConfiguration` 

Stores the parameters for the SslStream used by servers.

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public bool ` [`CheckCertificateRevocation`](#class_web_socket_sharp_1_1_net_1_1_server_ssl_configuration_1a822614b06d5a57c453296ea927014078) | Gets or sets a value indicating whether the certificate revocation list is checked during authentication.
`public bool ` [`ClientCertificateRequired`](#class_web_socket_sharp_1_1_net_1_1_server_ssl_configuration_1abe27a80b0a46997da031d3a4afc75725) | Gets or sets a value indicating whether the client is asked for a certificate for authentication.
`public RemoteCertificateValidationCallback ` [`ClientCertificateValidationCallback`](#class_web_socket_sharp_1_1_net_1_1_server_ssl_configuration_1adb6dadafe4b6dc47bc70a672fadd07cb) | Gets or sets the callback used to validate the certificate supplied by the client.
`public SslProtocols ` [`EnabledSslProtocols`](#class_web_socket_sharp_1_1_net_1_1_server_ssl_configuration_1a733bdf2e8032d228e86f45e92e3e2964) | Gets or sets the protocols used for authentication.
`public X509Certificate2 ` [`ServerCertificate`](#class_web_socket_sharp_1_1_net_1_1_server_ssl_configuration_1a96e44534cbc84876b4ae3b0ea6435095) | Gets or sets the certificate used to authenticate the server.
`public ` [`ServerSslConfiguration`](#class_web_socket_sharp_1_1_net_1_1_server_ssl_configuration_1a009316a79d3bfe5cd7bd4a53e9fbf62f)`()` | Initializes a new instance of the ServerSslConfiguration class.
`public ` [`ServerSslConfiguration`](#class_web_socket_sharp_1_1_net_1_1_server_ssl_configuration_1aac4c462e5b6ef44cda51e7b8800c8c36)`(` [`ServerSslConfiguration`](#class_web_socket_sharp_1_1_net_1_1_server_ssl_configuration)` configuration)` | Initializes a new instance of the ServerSslConfiguration class that stores the parameters copied from the specified configuration.
`private bool ` [`_checkCertRevocation`](#class_web_socket_sharp_1_1_net_1_1_server_ssl_configuration_1a62b9540bea0de155bc686405dc335ab9) | 
`private bool ` [`_clientCertRequired`](#class_web_socket_sharp_1_1_net_1_1_server_ssl_configuration_1ac1c1ef544161354a6e05b603130847c3) | 
`private RemoteCertificateValidationCallback ` [`_clientCertValidationCallback`](#class_web_socket_sharp_1_1_net_1_1_server_ssl_configuration_1abbbf3e5b8521b7c8c732f3431f8c5364) | 
`private SslProtocols ` [`_enabledSslProtocols`](#class_web_socket_sharp_1_1_net_1_1_server_ssl_configuration_1ab8e239926aabbf74357cf27c253cdf32) | 
`private X509Certificate2 ` [`_serverCert`](#class_web_socket_sharp_1_1_net_1_1_server_ssl_configuration_1ab208bb0068bd97b9dcdcdaeb15760d59) | 
`private static bool ` [`defaultValidateClientCertificate`](#class_web_socket_sharp_1_1_net_1_1_server_ssl_configuration_1ad02155b153d485550130f6490de4955d)`(object sender, X509Certificate certificate, X509Chain chain, SslPolicyErrors sslPolicyErrors)` | 

## Members

##### `public bool ` [`CheckCertificateRevocation`](#class_web_socket_sharp_1_1_net_1_1_server_ssl_configuration_1a822614b06d5a57c453296ea927014078) 

Gets or sets a value indicating whether the certificate revocation list is checked during authentication.

`true` if the certificate revocation list is checked during authentication; otherwise, `false`. 

The default value is `false`.

##### `public bool ` [`ClientCertificateRequired`](#class_web_socket_sharp_1_1_net_1_1_server_ssl_configuration_1abe27a80b0a46997da031d3a4afc75725) 

Gets or sets a value indicating whether the client is asked for a certificate for authentication.

`true` if the client is asked for a certificate for authentication; otherwise, `false`. 

The default value is `false`.

##### `public RemoteCertificateValidationCallback ` [`ClientCertificateValidationCallback`](#class_web_socket_sharp_1_1_net_1_1_server_ssl_configuration_1adb6dadafe4b6dc47bc70a672fadd07cb) 

Gets or sets the callback used to validate the certificate supplied by the client.

The certificate is valid if the callback returns `true`. 

A RemoteCertificateValidationCallback delegate that invokes the method called for validating the certificate. 

The default value is a delegate that invokes a method that only returns `true`.

##### `public SslProtocols ` [`EnabledSslProtocols`](#class_web_socket_sharp_1_1_net_1_1_server_ssl_configuration_1a733bdf2e8032d228e86f45e92e3e2964) 

Gets or sets the protocols used for authentication.

Any of the SslProtocols enum values. 

It represents the protocols used for authentication. 

The default value is SslProtocols.None.

##### `public X509Certificate2 ` [`ServerCertificate`](#class_web_socket_sharp_1_1_net_1_1_server_ssl_configuration_1a96e44534cbc84876b4ae3b0ea6435095) 

Gets or sets the certificate used to authenticate the server.

A X509Certificate2 or `null`. 

The certificate represents an X.509 certificate. 

The default value is `null`.

##### `public ` [`ServerSslConfiguration`](#class_web_socket_sharp_1_1_net_1_1_server_ssl_configuration_1a009316a79d3bfe5cd7bd4a53e9fbf62f)`()` 

Initializes a new instance of the ServerSslConfiguration class.

##### `public ` [`ServerSslConfiguration`](#class_web_socket_sharp_1_1_net_1_1_server_ssl_configuration_1aac4c462e5b6ef44cda51e7b8800c8c36)`(` [`ServerSslConfiguration`](#class_web_socket_sharp_1_1_net_1_1_server_ssl_configuration)` configuration)` 

Initializes a new instance of the ServerSslConfiguration class that stores the parameters copied from the specified configuration.

#### Parameters
* `configuration` A ServerSslConfiguration from which to copy. 

#### Exceptions
* `ArgumentNullException` *configuration*  is `null`.

##### `private bool ` [`_checkCertRevocation`](#class_web_socket_sharp_1_1_net_1_1_server_ssl_configuration_1a62b9540bea0de155bc686405dc335ab9) 

##### `private bool ` [`_clientCertRequired`](#class_web_socket_sharp_1_1_net_1_1_server_ssl_configuration_1ac1c1ef544161354a6e05b603130847c3) 

##### `private RemoteCertificateValidationCallback ` [`_clientCertValidationCallback`](#class_web_socket_sharp_1_1_net_1_1_server_ssl_configuration_1abbbf3e5b8521b7c8c732f3431f8c5364) 

##### `private SslProtocols ` [`_enabledSslProtocols`](#class_web_socket_sharp_1_1_net_1_1_server_ssl_configuration_1ab8e239926aabbf74357cf27c253cdf32) 

##### `private X509Certificate2 ` [`_serverCert`](#class_web_socket_sharp_1_1_net_1_1_server_ssl_configuration_1ab208bb0068bd97b9dcdcdaeb15760d59) 

##### `private static bool ` [`defaultValidateClientCertificate`](#class_web_socket_sharp_1_1_net_1_1_server_ssl_configuration_1ad02155b153d485550130f6490de4955d)`(object sender, X509Certificate certificate, X509Chain chain, SslPolicyErrors sslPolicyErrors)` 

