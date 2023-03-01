# class `WebSocketSharp::Net::NetworkCredential` 

Provides the credentials for the password-based authentication.

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public string ` [`Domain`](#class_web_socket_sharp_1_1_net_1_1_network_credential_1a72df16e5c55f3f510dbfdcba2d076baa) | Gets the domain associated with the credentials.
`public string ` [`Password`](#class_web_socket_sharp_1_1_net_1_1_network_credential_1a9c7aae3a8518d5efd22e991b5944e0d4) | Gets the password for the username associated with the credentials.
`public string[] ` [`Roles`](#class_web_socket_sharp_1_1_net_1_1_network_credential_1a4d174983ce061f363fcfa5abdb5ae9dc) | Gets the roles associated with the credentials.
`public string ` [`Username`](#class_web_socket_sharp_1_1_net_1_1_network_credential_1acc7e2f953f8dbfceb1c5a3834b78e3f7) | Gets the username associated with the credentials.
`public ` [`NetworkCredential`](#class_web_socket_sharp_1_1_net_1_1_network_credential_1a7a9fab29ad455309535762cd6fb573ae)`(string username, string password)` | Initializes a new instance of the NetworkCredential class with the specified *username* and *password* .
`public ` [`NetworkCredential`](#class_web_socket_sharp_1_1_net_1_1_network_credential_1a15fd5caa710a1873d3a745677e040dab)`(string username, string password, string domain, params string[] roles)` | Initializes a new instance of the NetworkCredential class with the specified *username* , *password* , *domain* and *roles* .
`private string ` [`_domain`](#class_web_socket_sharp_1_1_net_1_1_network_credential_1a96681c0a2d3f9328e47233dac1d7d39e) | 
`private string ` [`_password`](#class_web_socket_sharp_1_1_net_1_1_network_credential_1af8aecf42d3f813730ae6e97b44bb7fc8) | 
`private string[] ` [`_roles`](#class_web_socket_sharp_1_1_net_1_1_network_credential_1a0de5a0cff5863d9b9c1d1f34a43eea8d) | 
`private string ` [`_username`](#class_web_socket_sharp_1_1_net_1_1_network_credential_1a9a670661561d489590daca1c6454eefe) | 
`private static static ` [`NetworkCredential`](#class_web_socket_sharp_1_1_net_1_1_network_credential_1a0512fe8e27b5ff20a99108486e0cdb07)`()` | 

## Members

##### `public string ` [`Domain`](#class_web_socket_sharp_1_1_net_1_1_network_credential_1a72df16e5c55f3f510dbfdcba2d076baa) 

Gets the domain associated with the credentials.

This property returns an empty string if the domain was initialized with `null`. 

A string that represents the domain name to which the username belongs.

##### `public string ` [`Password`](#class_web_socket_sharp_1_1_net_1_1_network_credential_1a9c7aae3a8518d5efd22e991b5944e0d4) 

Gets the password for the username associated with the credentials.

This property returns an empty string if the password was initialized with `null`. 

A string that represents the password.

##### `public string[] ` [`Roles`](#class_web_socket_sharp_1_1_net_1_1_network_credential_1a4d174983ce061f363fcfa5abdb5ae9dc) 

Gets the roles associated with the credentials.

This property returns an empty array if the roles were initialized with `null`. 

An array of string that represents the role names to which the username belongs.

##### `public string ` [`Username`](#class_web_socket_sharp_1_1_net_1_1_network_credential_1acc7e2f953f8dbfceb1c5a3834b78e3f7) 

Gets the username associated with the credentials.

A string that represents the username.

##### `public ` [`NetworkCredential`](#class_web_socket_sharp_1_1_net_1_1_network_credential_1a7a9fab29ad455309535762cd6fb573ae)`(string username, string password)` 

Initializes a new instance of the NetworkCredential class with the specified *username*  and *password* .

#### Parameters
* `username` A string that represents the username associated with the credentials. 

* `password` A string that represents the password for the username associated with the credentials. 

#### Exceptions
* `ArgumentNullException` *username*  is `null`. 

* `ArgumentException` *username*  is empty.

##### `public ` [`NetworkCredential`](#class_web_socket_sharp_1_1_net_1_1_network_credential_1a15fd5caa710a1873d3a745677e040dab)`(string username, string password, string domain, params string[] roles)` 

Initializes a new instance of the NetworkCredential class with the specified *username* , *password* , *domain*  and *roles* .

#### Parameters
* `username` A string that represents the username associated with the credentials. 

* `password` A string that represents the password for the username associated with the credentials. 

* `domain` A string that represents the domain associated with the credentials. 

* `roles` An array of string that represents the roles associated with the credentials if any. 

#### Exceptions
* `ArgumentNullException` *username*  is `null`. 

* `ArgumentException` *username*  is empty.

##### `private string ` [`_domain`](#class_web_socket_sharp_1_1_net_1_1_network_credential_1a96681c0a2d3f9328e47233dac1d7d39e) 

##### `private string ` [`_password`](#class_web_socket_sharp_1_1_net_1_1_network_credential_1af8aecf42d3f813730ae6e97b44bb7fc8) 

##### `private string[] ` [`_roles`](#class_web_socket_sharp_1_1_net_1_1_network_credential_1a0de5a0cff5863d9b9c1d1f34a43eea8d) 

##### `private string ` [`_username`](#class_web_socket_sharp_1_1_net_1_1_network_credential_1a9a670661561d489590daca1c6454eefe) 

##### `private static static ` [`NetworkCredential`](#class_web_socket_sharp_1_1_net_1_1_network_credential_1a0512fe8e27b5ff20a99108486e0cdb07)`()` 

