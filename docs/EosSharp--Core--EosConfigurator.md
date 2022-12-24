# class `EosSharp::Core::EosConfigurator` 

Aggregates all properties to configure Eos client.

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public string ` [`HttpEndpoint`](#class_eos_sharp_1_1_core_1_1_eos_configurator_1a62f1f3c56291cefa77840b2ca2f20419) | http or https location of a nodeosd server providing a chain API.
`public string ` [`ChainId`](#class_eos_sharp_1_1_core_1_1_eos_configurator_1a4476ef8ec88d45c994accc6d8c4f0da3) | unique ID for the blockchain you're connecting to. If no ChainId is provided it will get from the get_info API call.
`public double ` [`ExpireSeconds`](#class_eos_sharp_1_1_core_1_1_eos_configurator_1a1de209d04ed6fa63c8e7b0f72e2fab54) | number of seconds before the transaction will expire. The time is based on the nodeosd's clock. An unexpired transaction that may have had an error is a liability until the expiration is reached, this time should be brief.
`public UInt32 ` [`blocksBehind`](#class_eos_sharp_1_1_core_1_1_eos_configurator_1a29e395da124d767fe65c693b692180ed) | How many blocks behind to use for TAPoS reference block.
`public ` [`ISignProvider`](EosSharp--Core--Interfaces.md)` ` [`SignProvider`](#class_eos_sharp_1_1_core_1_1_eos_configurator_1aa954fae2fc1b464d3a78a085bdf54a92) | signature implementation to handle available keys and signing transactions. Use the DefaultSignProvider with a privateKey to sign transactions inside the lib.

## Members

##### `public string ` [`HttpEndpoint`](#class_eos_sharp_1_1_core_1_1_eos_configurator_1a62f1f3c56291cefa77840b2ca2f20419) 

http or https location of a nodeosd server providing a chain API.

##### `public string ` [`ChainId`](#class_eos_sharp_1_1_core_1_1_eos_configurator_1a4476ef8ec88d45c994accc6d8c4f0da3) 

unique ID for the blockchain you're connecting to. If no ChainId is provided it will get from the get_info API call.

##### `public double ` [`ExpireSeconds`](#class_eos_sharp_1_1_core_1_1_eos_configurator_1a1de209d04ed6fa63c8e7b0f72e2fab54) 

number of seconds before the transaction will expire. The time is based on the nodeosd's clock. An unexpired transaction that may have had an error is a liability until the expiration is reached, this time should be brief.

##### `public UInt32 ` [`blocksBehind`](#class_eos_sharp_1_1_core_1_1_eos_configurator_1a29e395da124d767fe65c693b692180ed) 

How many blocks behind to use for TAPoS reference block.

##### `public ` [`ISignProvider`](EosSharp--Core--Interfaces.md)` ` [`SignProvider`](#class_eos_sharp_1_1_core_1_1_eos_configurator_1aa954fae2fc1b464d3a78a085bdf54a92) 

signature implementation to handle available keys and signing transactions. Use the DefaultSignProvider with a privateKey to sign transactions inside the lib.

