# class `AtomicMarketApiClient::Pricing::PricingUriParametersBuilder` 

```
class AtomicMarketApiClient::Pricing::PricingUriParametersBuilder
  : public IUriParameterBuilder
```

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public PricingUriParametersBuilder `[`WithSymbol`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_uri_parameters_builder_1a09ad8b6a8d73526f5a0fc20c76894819)`(string symbol)` | `WithSymbol` sets the `symbol` parameter
`public PricingUriParametersBuilder `[`WithBurned`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_uri_parameters_builder_1a4f7c02ab695e063599b873e235d5ce47)`(bool burned)` | `WithBurned` sets the `_burned` field to the value of the `burned` parameter
`public PricingUriParametersBuilder `[`WithCollectionName`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_uri_parameters_builder_1ade45698cd327201f24270ccede733cd3)`(string collectionName)` | `WithCollectionName` is a function that takes a string as a parameter and returns an `PricingUriParameterBuilder` object
`public PricingUriParametersBuilder `[`WithSchemaName`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_uri_parameters_builder_1a3728ef603ca60a309fe59e96213208b5)`(string schemaName)` | This function sets the schema name for the query
`public PricingUriParametersBuilder `[`WithTemplateId`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_uri_parameters_builder_1a56b890f7fa617e3ae6908264cb6fca6d)`(string templateId)` | `WithTemplateId` sets the `_templateId` variable to the value of the `templateId` parameter
`public PricingUriParametersBuilder `[`WithIsTransferable`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_uri_parameters_builder_1a6520a84e79a0e115c121cafc67cf6cf1)`(bool isTransferable)` | `WithIsTransferable` sets the `_isTransferable` field to the value of the `isTransferable` parameter
`public PricingUriParametersBuilder `[`WithIsBurnable`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_uri_parameters_builder_1a373cece648672a58d814966f3bc91b60)`(bool isBurnable)` | `WithIsTransferable` sets the `_isTransferable` field to the value of the `isTransferable` parameter
`public string `[`Build`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_uri_parameters_builder_1a933ab72b517a9c3879ef78b27a2483bf)`()` | It builds a query string based on the parameters that have been set.
`private string `[`_symbol`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_uri_parameters_builder_1a26c189f7d4c40f40f09ace24c4ccb945) | 
`private bool? `[`_burned`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_uri_parameters_builder_1a88325c0b6dc8cb4a570b2faaca18efa7) | 
`private string `[`_collectionName`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_uri_parameters_builder_1a10ec2fa990c6478bc519b1e57e1ab2aa) | 
`private string `[`_schemaName`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_uri_parameters_builder_1a2f9a887fd4dfcf60bfe4240a27085724) | 
`private string `[`_templateId`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_uri_parameters_builder_1a06f918051fc7b04615854510caa85934) | 
`private bool? `[`_isTransferable`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_uri_parameters_builder_1a44e26246620bd9d4efa97c195a356672) | 
`private bool? `[`_isBurnable`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_uri_parameters_builder_1a6020acf0c5cb6f447cfe5ba95579e74d) | 

## Members

##### `public PricingUriParametersBuilder `[`WithSymbol`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_uri_parameters_builder_1a09ad8b6a8d73526f5a0fc20c76894819)`(string symbol)` 

`WithSymbol` sets the `symbol` parameter

#### Parameters
* `symbol` Token symbols.

#### Returns
The PricingUriParameterBuilder object.

##### `public PricingUriParametersBuilder `[`WithBurned`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_uri_parameters_builder_1a4f7c02ab695e063599b873e235d5ce47)`(bool burned)` 

`WithBurned` sets the `_burned` field to the value of the `burned` parameter

#### Parameters
* `burned` It filters for burned assets.

#### Returns
The PricingUriParameterBuilder object.

##### `public PricingUriParametersBuilder `[`WithCollectionName`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_uri_parameters_builder_1ade45698cd327201f24270ccede733cd3)`(string collectionName)` 

`WithCollectionName` is a function that takes a string as a parameter and returns an `PricingUriParameterBuilder` object

#### Parameters
* `collectionName` The name of the collection you want to query.

#### Returns
The PricingUriParameterBuilder object.

##### `public PricingUriParametersBuilder `[`WithSchemaName`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_uri_parameters_builder_1a3728ef603ca60a309fe59e96213208b5)`(string schemaName)` 

This function sets the schema name for the query

#### Parameters
* `schemaName` The name of the schema to use.

#### Returns
The PricingUriParameterBuilder object.

##### `public PricingUriParametersBuilder `[`WithTemplateId`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_uri_parameters_builder_1a56b890f7fa617e3ae6908264cb6fca6d)`(string templateId)` 

`WithTemplateId` sets the `_templateId` variable to the value of the `templateId` parameter

#### Parameters
* `templateId` The templateId of the results to return.

#### Returns
The PricingUriParameterBuilder object.

##### `public PricingUriParametersBuilder `[`WithIsTransferable`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_uri_parameters_builder_1a6520a84e79a0e115c121cafc67cf6cf1)`(bool isTransferable)` 

`WithIsTransferable` sets the `_isTransferable` field to the value of the `isTransferable` parameter

#### Parameters
* `isTransferable` The isTransferable parameter filters results.

#### Returns
The PricingUriParameterBuilder object.

##### `public PricingUriParametersBuilder `[`WithIsBurnable`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_uri_parameters_builder_1a373cece648672a58d814966f3bc91b60)`(bool isBurnable)` 

`WithIsTransferable` sets the `_isTransferable` field to the value of the `isTransferable` parameter

#### Parameters
* `isTransferable` The isTransferable parameter filters for transferable assets.

#### Returns
The PricingUriParameterBuilder object.

##### `public string `[`Build`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_uri_parameters_builder_1a933ab72b517a9c3879ef78b27a2483bf)`()` 

It builds a query string based on the parameters that have been set.

#### Returns
A string that contains the parameters for the query.

##### `private string `[`_symbol`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_uri_parameters_builder_1a26c189f7d4c40f40f09ace24c4ccb945) 

##### `private bool? `[`_burned`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_uri_parameters_builder_1a88325c0b6dc8cb4a570b2faaca18efa7) 

##### `private string `[`_collectionName`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_uri_parameters_builder_1a10ec2fa990c6478bc519b1e57e1ab2aa) 

##### `private string `[`_schemaName`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_uri_parameters_builder_1a2f9a887fd4dfcf60bfe4240a27085724) 

##### `private string `[`_templateId`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_uri_parameters_builder_1a06f918051fc7b04615854510caa85934) 

##### `private bool? `[`_isTransferable`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_uri_parameters_builder_1a44e26246620bd9d4efa97c195a356672) 

##### `private bool? `[`_isBurnable`](#class_atomic_market_api_client_1_1_pricing_1_1_pricing_uri_parameters_builder_1a6020acf0c5cb6f447cfe5ba95579e74d) 

