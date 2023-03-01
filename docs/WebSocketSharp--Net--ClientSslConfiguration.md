# class `WebSocketSharp::Net::ClientSslConfiguration` 

Stores the parameters for the SslStream used by clients.

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public bool ` [`CheckCertificateRevocation`](#class_web_socket_sharp_1_1_net_1_1_client_ssl_configuration_1a822614b06d5a57c453296ea927014078) | Gets or sets a value indicating whether the certificate revocation list is checked during authentication.
`public X509CertificateCollection ` [`ClientCertificates`](#class_web_socket_sharp_1_1_net_1_1_client_ssl_configuration_1a1d6373fc055f4cda350d8975d23d7e1a) | Gets or sets the collection of client certificates from which to select one to supply to the server.
`public LocalCertificateSelectionCallback ` [`ClientCertificateSelectionCallback`](#class_web_socket_sharp_1_1_net_1_1_client_ssl_configuration_1a2a5b6ff61ad90da29f8eec2d0fde3a8f) | Gets or sets the callback used to select the certificate to supply to the server.
`public SslProtocols ` [`EnabledSslProtocols`](#class_web_socket_sharp_1_1_net_1_1_client_ssl_configuration_1a733bdf2e8032d228e86f45e92e3e2964) | Gets or sets the protocols used for authentication.
`public RemoteCertificateValidationCallback ` [`ServerCertificateValidationCallback`](#class_web_socket_sharp_1_1_net_1_1_client_ssl_configuration_1a7653e91cf420ea989c983cfbe634464b) | Gets or sets the callback used to validate the certificate supplied by the server.
`public string ` [`TargetHost`](#class_web_socket_sharp_1_1_net_1_1_client_ssl_configuration_1a04fcd8c2d870ef53644c08f9e5cf7a97) | Gets or sets the target host server name.
`public ` [`ClientSslConfiguration`](#class_web_socket_sharp_1_1_net_1_1_client_ssl_configuration_1a163d3ca4573a204e5323bd0ece4f89f9)`(string targetHost)` | Initializes a new instance of the ClientSslConfiguration class with the specified target host server name.
`public ` [`ClientSslConfiguration`](#class_web_socket_sharp_1_1_net_1_1_client_ssl_configuration_1aa0409adc6b234737e9b199d036a78413)`(` [`ClientSslConfiguration`](#class_web_socket_sharp_1_1_net_1_1_client_ssl_configuration)` configuration)` | Initializes a new instance of the ClientSslConfiguration class that stores the parameters copied from the specified configuration.
`private bool ` [`_checkCertRevocation`](#class_web_socket_sharp_1_1_net_1_1_client_ssl_configuration_1a62b9540bea0de155bc686405dc335ab9) | 
`private LocalCertificateSelectionCallback ` [`_clientCertSelectionCallback`](#class_web_socket_sharp_1_1_net_1_1_client_ssl_configuration_1ac075f325c80e78bef2b98518b8c54590) | 
`private X509CertificateCollection ` [`_clientCerts`](#class_web_socket_sharp_1_1_net_1_1_client_ssl_configuration_1a7643bf4ef5d17e1bf7a73d1f386b9253) | 
`private SslProtocols ` [`_enabledSslProtocols`](#class_web_socket_sharp_1_1_net_1_1_client_ssl_configuration_1ab8e239926aabbf74357cf27c253cdf32) | 
`private RemoteCertificateValidationCallback ` [`_serverCertValidationCallback`](#class_web_socket_sharp_1_1_net_1_1_client_ssl_configuration_1adaf9e5e074ecb1187f6a791f24c4117a) | 
`private string ` [`_targetHost`](#class_web_socket_sharp_1_1_net_1_1_client_ssl_configuration_1a3f1fe09e81ad9abdeecbddbb03c49f4e) | 
`private static X509Certificate ` [`defaultSelectClientCertificate`](#class_web_socket_sharp_1_1_net_1_1_client_ssl_configuration_1a1d0ada86335b020e9cc002e9cf579f10)`(object sender, string targetHost, X509CertificateCollection clientCertificates, X509Certificate serverCertificate, string[] acceptableIssuers)` | 
`private static bool ` [`defaultValidateServerCertificate`](#class_web_socket_sharp_1_1_net_1_1_client_ssl_configuration_1ab664cb0dd3ed1cf6500fc54acf539cbc)`(object sender, X509Certificate certificate, X509Chain chain, SslPolicyErrors sslPolicyErrors)` | 

## Members

##### `public bool ` [`CheckCertificateRevocation`](#class_web_socket_sharp_1_1_net_1_1_client_ssl_configuration_1a822614b06d5a57c453296ea927014078) 

Gets or sets a value indicating whether the certificate revocation list is checked during authentication.

`true` if the certificate revocation list is checked during authentication; otherwise, `false`. 

The default value is `false`.

##### `public X509CertificateCollection ` [`ClientCertificates`](#class_web_socket_sharp_1_1_net_1_1_client_ssl_configuration_1a1d6373fc055f4cda350d8975d23d7e1a) 

Gets or sets the collection of client certificates from which to select one to supply to the server.

A X509CertificateCollection or `null`. 

The collection contains client certificates from which to select. 

The default value is `null`.

##### `public LocalCertificateSelectionCallback ` [`ClientCertificateSelectionCallback`](#class_web_socket_sharp_1_1_net_1_1_client_ssl_configuration_1a2a5b6ff61ad90da29f8eec2d0fde3a8f) 

Gets or sets the callback used to select the certificate to supply to the server.

No certificate is supplied if the callback returns `null`. 

A LocalCertificateSelectionCallback delegate that invokes the method called for selecting the certificate. 

The default value is a delegate that invokes a method that only returns `null`.

##### `public SslProtocols ` [`EnabledSslProtocols`](#class_web_socket_sharp_1_1_net_1_1_client_ssl_configuration_1a733bdf2e8032d228e86f45e92e3e2964) 

Gets or sets the protocols used for authentication.

Any of the SslProtocols enum values. 

It represents the protocols used for authentication. 

The default value is SslProtocols.None.

##### `public RemoteCertificateValidationCallback ` [`ServerCertificateValidationCallback`](#class_web_socket_sharp_1_1_net_1_1_client_ssl_configuration_1a7653e91cf420ea989c983cfbe634464b) 

Gets or sets the callback used to validate the certificate supplied by the server.

The certificate is valid if the callback returns `true`. 

A RemoteCertificateValidationCallback delegate that invokes the method called for validating the certificate. 

The default value is a delegate that invokes a method that only returns `true`.

##### `public string ` [`TargetHost`](#class_web_socket_sharp_1_1_net_1_1_client_ssl_configuration_1a04fcd8c2d870ef53644c08f9e5cf7a97) 

Gets or sets the target host server name.

A string that represents the name of the server that will share a secure connection with a client. 

#### Exceptions
* `ArgumentNullException` The value specified for a set operation is `null`. 

* `ArgumentException` The value specified for a set operation is an empty string.

##### `public ` [`ClientSslConfiguration`](#class_web_socket_sharp_1_1_net_1_1_client_ssl_configuration_1a163d3ca4573a204e5323bd0ece4f89f9)`(string targetHost)` 

Initializes a new instance of the ClientSslConfiguration class with the specified target host server name.

#### Parameters
* `targetHost` A string that specifies the target host server name. 

#### Exceptions
* `ArgumentNullException` *targetHost*  is `null`. 

* `ArgumentException` *targetHost*  is an empty string.

##### `public ` [`ClientSslConfiguration`](#class_web_socket_sharp_1_1_net_1_1_client_ssl_configuration_1aa0409adc6b234737e9b199d036a78413)`(` [`ClientSslConfiguration`](#class_web_socket_sharp_1_1_net_1_1_client_ssl_configuration)` configuration)` 

Initializes a new instance of the ClientSslConfiguration class that stores the parameters copied from the specified configuration.

#### Parameters
* `configuration` A ClientSslConfiguration from which to copy. 

#### Exceptions
* `ArgumentNullException` *configuration*  is `null`.

##### `private bool ` [`_checkCertRevocation`](#class_web_socket_sharp_1_1_net_1_1_client_ssl_configuration_1a62b9540bea0de155bc686405dc335ab9) 

##### `private LocalCertificateSelectionCallback ` [`_clientCertSelectionCallback`](#class_web_socket_sharp_1_1_net_1_1_client_ssl_configuration_1ac075f325c80e78bef2b98518b8c54590) 

##### `private X509CertificateCollection ` [`_clientCerts`](#class_web_socket_sharp_1_1_net_1_1_client_ssl_configuration_1a7643bf4ef5d17e1bf7a73d1f386b9253) 

##### `private SslProtocols ` [`_enabledSslProtocols`](#class_web_socket_sharp_1_1_net_1_1_client_ssl_configuration_1ab8e239926aabbf74357cf27c253cdf32) 

##### `private RemoteCertificateValidationCallback ` [`_serverCertValidationCallback`](#class_web_socket_sharp_1_1_net_1_1_client_ssl_configuration_1adaf9e5e074ecb1187f6a791f24c4117a) 

##### `private string ` [`_targetHost`](#class_web_socket_sharp_1_1_net_1_1_client_ssl_configuration_1a3f1fe09e81ad9abdeecbddbb03c49f4e) 

##### `private static X509Certificate ` [`defaultSelectClientCertificate`](#class_web_socket_sharp_1_1_net_1_1_client_ssl_configuration_1a1d0ada86335b020e9cc002e9cf579f10)`(object sender, string targetHost, X509CertificateCollection clientCertificates, X509Certificate serverCertificate, string[] acceptableIssuers)` 

##### `private static bool ` [`defaultValidateServerCertificate`](#class_web_socket_sharp_1_1_net_1_1_client_ssl_configuration_1ab664cb0dd3ed1cf6500fc54acf539cbc)`(object sender, X509Certificate certificate, X509Chain chain, SslPolicyErrors sslPolicyErrors)` 

