# class `HyperionApiClient::Clients::ChainClient` 

```
class HyperionApiClient::Clients::ChainClient
  : public ClientExtensions
```

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public string ` [`BaseUrl`](#class_hyperion_api_client_1_1_clients_1_1_chain_client_1a5e5e1c3b42a6c7ab84f8aeca3c9e570c) | 
`public ` [`ChainClient`](#class_hyperion_api_client_1_1_clients_1_1_chain_client_1a1401b58497cd035ce78c721013739d27)`(` [`IHttpHandler`](HyperionApiClient.md)` httpHandler)` | 
`public async Task ` [`AbiBinToJsonAsync`](#class_hyperion_api_client_1_1_clients_1_1_chain_client_1acb50a40d1dd0c1e5824c3f57ca195b67)`(string code, string action, string binargs, CancellationToken cancellationToken) = default` | Returns an object containing rows from the specified table.
`public async Task ` [`AbiJsonToBinAsync`](#class_hyperion_api_client_1_1_clients_1_1_chain_client_1a044ae7153bf015634e5b86c42d246b07)`(string binargs, CancellationToken cancellationToken) = default` | Convert JSON object to binary.
`public async Task< GetAbiResponse > ` [`GetAbiAsync`](#class_hyperion_api_client_1_1_clients_1_1_chain_client_1ad107c0f016fc2e5fd05799b278f09cf1)`(string accountName, CancellationToken cancellationToken) = default` | Retrieves the ABI for a contract based on its account name.
`public async Task< GetAccountResponse2 > ` [`GetAccountAsync`](#class_hyperion_api_client_1_1_clients_1_1_chain_client_1a0fa96318dd11589bb50fbdf55c66d8a8)`(string accountName, CancellationToken cancellationToken) = default` | Returns an object containing various details about a specific account on the blockchain.
`public async Task< GetActivatedProtocolFeaturesResponse > ` [`GetActivatedProtocolFeaturesAsync`](#class_hyperion_api_client_1_1_clients_1_1_chain_client_1ad9bef63d48487cd4dc533aa9702ed073)`(int? lowerBound, int? upperBound, int? limit, bool? searchByBlockNum, bool? reverse, CancellationToken cancellationToken) = default` | Retreives the activated protocol features for producer node.
`public async Task< GetBlockResponse2 > ` [`GetBlockAsync`](#class_hyperion_api_client_1_1_clients_1_1_chain_client_1abaa94a0282bcd676d33be4e8cf66b65a)`(string blockNumOrId, CancellationToken cancellationToken) = default` | Returns an object containing various details about a specific block on the blockchain.
`public async Task< GetBlockHeaderStateResponse > ` [`GetBlockHeaderStateAsync`](#class_hyperion_api_client_1_1_clients_1_1_chain_client_1af5181f82fe64a091c2fc976b5af4d0e2)`(string blockNumOrId, CancellationToken cancellationToken) = default` | Retrieves the block header state.
`public async Task< GetCodeResponse > ` [`GetCodeAsync`](#class_hyperion_api_client_1_1_clients_1_1_chain_client_1afe6f7ad664e43b5dad77102de4298bb2)`(string accountName, bool codeAsWasm, CancellationToken cancellationToken) = default` | Retrieves contract code.
`public async Task< List< string > > ` [`GetCurrencyBalanceAsync`](#class_hyperion_api_client_1_1_clients_1_1_chain_client_1ac25d45a1be18bac89fe8190600694d46)`(string code, string account, string symbol, CancellationToken cancellationToken) = default` | Retrieves the current balance.
`public async Task< string > ` [`GetCurrencyStatsAsync`](#class_hyperion_api_client_1_1_clients_1_1_chain_client_1ae33129ab398ac3494fb6d2a9f3e8cc8f)`(string code, string symbol, CancellationToken cancellationToken) = default` | Retrieves currency stats.
`public async Task< GetInfoResponse > ` [`GetInfoAsync`](#class_hyperion_api_client_1_1_clients_1_1_chain_client_1a6ee36abef4a7ae6c3574e9ec9bae5236)`(CancellationToken cancellationToken) = default` | Returns an object containing various details about the blockchain.
`public async Task< GetProducersResponse > ` [`GetProducersAsync`](#class_hyperion_api_client_1_1_clients_1_1_chain_client_1ae0dedd1c6f6323a14500b621f1bafab3)`(string limit, string lowerBound, bool? json, CancellationToken cancellationToken) = default` | Retrieves producers list.
`public async Task ` [`GetRawAbiAsync`](#class_hyperion_api_client_1_1_clients_1_1_chain_client_1a337a315a3b3a89c1cf4aa6abf74ac89a)`(string accountName, CancellationToken cancellationToken) = default` | Retrieves raw ABI for a contract based on account name.
`public async Task ` [`GetRawCodeAndAbiAsync`](#class_hyperion_api_client_1_1_clients_1_1_chain_client_1a53af3ffe2b660041d548f503a31714f1)`(string accountName, CancellationToken cancellationToken) = default` | Retrieves raw code and ABI for a contract based on account name.
`public async Task ` [`GetScheduledTransactionAsync`](#class_hyperion_api_client_1_1_clients_1_1_chain_client_1a363bd691602cb4c92708d8b1a330bcbb)`(string lowerBound, int? limit, bool? json, CancellationToken cancellationToken) = default` | Retrieves the scheduled transaction.
`public async Task< GetTableByScopeResponse > ` [`GetTableByScopeAsync`](#class_hyperion_api_client_1_1_clients_1_1_chain_client_1acb27517727e54b0f9829e7117fad7fc7)`(string code, string table, string lowerBound, string upperBound, int? limit, bool? reverse, CancellationToken cancellationToken) = default` | Retrieves table scope.
`public async Task ` [`GetTableRowsAsync`](#class_hyperion_api_client_1_1_clients_1_1_chain_client_1a3519bf9a98468f2c9c36d70f3efd0894)`(string code, string table, string scope, string indexPosition, string keyType, string encodeType, string upperBound, string lowerBound, CancellationToken cancellationToken) = default` | Returns an object containing rows from the specified table.
`public async Task ` [`PushTransactionAsync`](#class_hyperion_api_client_1_1_clients_1_1_chain_client_1a0b0ff0b3db671ccb82da9fafb785ac2c)`(object body, CancellationToken cancellationToken) = default` | This method expects a transaction in JSON format and will attempt to apply it to the blockchain.
`public async Task ` [`PushTransactionsAsync`](#class_hyperion_api_client_1_1_clients_1_1_chain_client_1a98fa20d9d7836386416367425809d428)`(IEnumerable< object > body, CancellationToken cancellationToken) = default` | This method expects a transaction in JSON format and will attempt to apply it to the blockchain.
`public async Task ` [`SendTransactionAsync`](#class_hyperion_api_client_1_1_clients_1_1_chain_client_1a06bd3fddbf5d37b9718c982a841c7cc1)`(object body, CancellationToken cancellationToken) = default` | This method expects a transaction in JSON format and will attempt to apply it to the blockchain.
`private readonly ` [`IHttpHandler`](HyperionApiClient.md)` ` [`_httpHandler`](#class_hyperion_api_client_1_1_clients_1_1_chain_client_1a278528cd3027ee0a4ca8e04964f99674) | 

## Members

##### `public string ` [`BaseUrl`](#class_hyperion_api_client_1_1_clients_1_1_chain_client_1a5e5e1c3b42a6c7ab84f8aeca3c9e570c) 

##### `public ` [`ChainClient`](#class_hyperion_api_client_1_1_clients_1_1_chain_client_1a1401b58497cd035ce78c721013739d27)`(` [`IHttpHandler`](HyperionApiClient.md)` httpHandler)` 

##### `public async Task ` [`AbiBinToJsonAsync`](#class_hyperion_api_client_1_1_clients_1_1_chain_client_1acb50a40d1dd0c1e5824c3f57ca195b67)`(string code, string action, string binargs, CancellationToken cancellationToken) = default` 

Returns an object containing rows from the specified table.

#### Parameters
* `cancellationToken` A cancellation token that can be used by other objects or threads to receive notice of cancellation.

#### Returns
Default Response

#### Exceptions
* `ApiException` A server side error occurred.

##### `public async Task ` [`AbiJsonToBinAsync`](#class_hyperion_api_client_1_1_clients_1_1_chain_client_1a044ae7153bf015634e5b86c42d246b07)`(string binargs, CancellationToken cancellationToken) = default` 

Convert JSON object to binary.

#### Parameters
* `cancellationToken` A cancellation token that can be used by other objects or threads to receive notice of cancellation.

#### Returns
Default Response

#### Exceptions
* `ApiException` A server side error occurred.

##### `public async Task< GetAbiResponse > ` [`GetAbiAsync`](#class_hyperion_api_client_1_1_clients_1_1_chain_client_1ad107c0f016fc2e5fd05799b278f09cf1)`(string accountName, CancellationToken cancellationToken) = default` 

Retrieves the ABI for a contract based on its account name.

#### Parameters
* `cancellationToken` A cancellation token that can be used by other objects or threads to receive notice of cancellation.

#### Returns
Default Response

#### Exceptions
* `ApiException` A server side error occurred.

##### `public async Task< GetAccountResponse2 > ` [`GetAccountAsync`](#class_hyperion_api_client_1_1_clients_1_1_chain_client_1a0fa96318dd11589bb50fbdf55c66d8a8)`(string accountName, CancellationToken cancellationToken) = default` 

Returns an object containing various details about a specific account on the blockchain.

#### Parameters
* `cancellationToken` A cancellation token that can be used by other objects or threads to receive notice of cancellation.

#### Returns
Default Response

#### Exceptions
* `ApiException` A server side error occurred.

##### `public async Task< GetActivatedProtocolFeaturesResponse > ` [`GetActivatedProtocolFeaturesAsync`](#class_hyperion_api_client_1_1_clients_1_1_chain_client_1ad9bef63d48487cd4dc533aa9702ed073)`(int? lowerBound, int? upperBound, int? limit, bool? searchByBlockNum, bool? reverse, CancellationToken cancellationToken) = default` 

Retreives the activated protocol features for producer node.

#### Parameters
* `cancellationToken` A cancellation token that can be used by other objects or threads to receive notice of cancellation.

#### Parameters
* `lower_bound` Lower bound

* `upper_bound` Upper bound

* `limit` The limit, default is 10

* `search_by_block_num` Flag to indicate it is has to search by block number

* `reverse` Flag to indicate it has to search in reverse

#### Returns
Default Response

#### Exceptions
* `ApiException` A server side error occurred.

##### `public async Task< GetBlockResponse2 > ` [`GetBlockAsync`](#class_hyperion_api_client_1_1_clients_1_1_chain_client_1abaa94a0282bcd676d33be4e8cf66b65a)`(string blockNumOrId, CancellationToken cancellationToken) = default` 

Returns an object containing various details about a specific block on the blockchain.

#### Parameters
* `cancellationToken` A cancellation token that can be used by other objects or threads to receive notice of cancellation.

#### Parameters
* `block_num_or_id` Provide a `block number` or a `block id`

#### Returns
Default Response

#### Exceptions
* `ApiException` A server side error occurred.

##### `public async Task< GetBlockHeaderStateResponse > ` [`GetBlockHeaderStateAsync`](#class_hyperion_api_client_1_1_clients_1_1_chain_client_1af5181f82fe64a091c2fc976b5af4d0e2)`(string blockNumOrId, CancellationToken cancellationToken) = default` 

Retrieves the block header state.

#### Parameters
* `cancellationToken` A cancellation token that can be used by other objects or threads to receive notice of cancellation.

#### Parameters
* `blockNumOrId` Provide a block_number or a block_id

#### Returns
Default Response

#### Exceptions
* `ApiException` A server side error occurred.

##### `public async Task< GetCodeResponse > ` [`GetCodeAsync`](#class_hyperion_api_client_1_1_clients_1_1_chain_client_1afe6f7ad664e43b5dad77102de4298bb2)`(string accountName, bool codeAsWasm, CancellationToken cancellationToken) = default` 

Retrieves contract code.

#### Parameters
* `cancellationToken` A cancellation token that can be used by other objects or threads to receive notice of cancellation.

#### Parameters
* `code_as_wasm` This must be 1 (true)

#### Returns
Default Response

#### Exceptions
* `ApiException` A server side error occurred.

##### `public async Task< List< string > > ` [`GetCurrencyBalanceAsync`](#class_hyperion_api_client_1_1_clients_1_1_chain_client_1ac25d45a1be18bac89fe8190600694d46)`(string code, string account, string symbol, CancellationToken cancellationToken) = default` 

Retrieves the current balance.

#### Parameters
* `cancellationToken` A cancellation token that can be used by other objects or threads to receive notice of cancellation.

#### Parameters
* `symbol` A symbol composed of capital letters between 1-7.

#### Returns
Default Response

#### Exceptions
* `ApiException` A server side error occurred.

##### `public async Task< string > ` [`GetCurrencyStatsAsync`](#class_hyperion_api_client_1_1_clients_1_1_chain_client_1ae33129ab398ac3494fb6d2a9f3e8cc8f)`(string code, string symbol, CancellationToken cancellationToken) = default` 

Retrieves currency stats.

#### Parameters
* `cancellationToken` A cancellation token that can be used by other objects or threads to receive notice of cancellation.

#### Parameters
* `code` contract name

* `symbol` token symbol

#### Returns
Default Response

#### Exceptions
* `ApiException` A server side error occurred.

##### `public async Task< GetInfoResponse > ` [`GetInfoAsync`](#class_hyperion_api_client_1_1_clients_1_1_chain_client_1a6ee36abef4a7ae6c3574e9ec9bae5236)`(CancellationToken cancellationToken) = default` 

Returns an object containing various details about the blockchain.

#### Parameters
* `cancellationToken` A cancellation token that can be used by other objects or threads to receive notice of cancellation.

#### Returns
Default Response

#### Exceptions
* `ApiException` A server side error occurred.

##### `public async Task< GetProducersResponse > ` [`GetProducersAsync`](#class_hyperion_api_client_1_1_clients_1_1_chain_client_1ae0dedd1c6f6323a14500b621f1bafab3)`(string limit, string lowerBound, bool? json, CancellationToken cancellationToken) = default` 

Retrieves producers list.

#### Parameters
* `cancellationToken` A cancellation token that can be used by other objects or threads to receive notice of cancellation.

#### Parameters
* `limit` total number of producers to retrieve

* `lower_bound` In conjunction with limit can be used to paginate through the results. For example, limit=10 and lower_bound=10 would be page 2

* `json` return result in JSON format

#### Returns
Default Response

#### Exceptions
* `ApiException` A server side error occurred.

##### `public async Task ` [`GetRawAbiAsync`](#class_hyperion_api_client_1_1_clients_1_1_chain_client_1a337a315a3b3a89c1cf4aa6abf74ac89a)`(string accountName, CancellationToken cancellationToken) = default` 

Retrieves raw ABI for a contract based on account name.

#### Parameters
* `cancellationToken` A cancellation token that can be used by other objects or threads to receive notice of cancellation.

#### Returns
Default Response

#### Exceptions
* `ApiException` A server side error occurred.

##### `public async Task ` [`GetRawCodeAndAbiAsync`](#class_hyperion_api_client_1_1_clients_1_1_chain_client_1a53af3ffe2b660041d548f503a31714f1)`(string accountName, CancellationToken cancellationToken) = default` 

Retrieves raw code and ABI for a contract based on account name.

#### Parameters
* `cancellationToken` A cancellation token that can be used by other objects or threads to receive notice of cancellation.

#### Returns
Default Response

#### Exceptions
* `ApiException` A server side error occurred.

##### `public async Task ` [`GetScheduledTransactionAsync`](#class_hyperion_api_client_1_1_clients_1_1_chain_client_1a363bd691602cb4c92708d8b1a330bcbb)`(string lowerBound, int? limit, bool? json, CancellationToken cancellationToken) = default` 

Retrieves the scheduled transaction.

#### Parameters
* `cancellationToken` A cancellation token that can be used by other objects or threads to receive notice of cancellation.

#### Parameters
* `lower_bound` Date/time string in the format YYYY-MM-DDTHH:MM:SS.sss

* `limit` The maximum number of transactions to return

* `json` true/false whether the packed transaction is converted to json

#### Returns
Default Response

#### Exceptions
* `ApiException` A server side error occurred.

##### `public async Task< GetTableByScopeResponse > ` [`GetTableByScopeAsync`](#class_hyperion_api_client_1_1_clients_1_1_chain_client_1acb27517727e54b0f9829e7117fad7fc7)`(string code, string table, string lowerBound, string upperBound, int? limit, bool? reverse, CancellationToken cancellationToken) = default` 

Retrieves table scope.

#### Parameters
* `cancellationToken` A cancellation token that can be used by other objects or threads to receive notice of cancellation.

#### Parameters
* `code` `name` of the contract to return table data for

* `table` Filter results by table

* `lower_bound` Filters results to return the first element that is not less than provided value in set

* `upper_bound` Filters results to return the first element that is greater than provided value in set

* `limit` Limit number of results returned.

* `reverse` Reverse the order of returned results

#### Returns
Default Response

#### Exceptions
* `ApiException` A server side error occurred.

##### `public async Task ` [`GetTableRowsAsync`](#class_hyperion_api_client_1_1_clients_1_1_chain_client_1a3519bf9a98468f2c9c36d70f3efd0894)`(string code, string table, string scope, string indexPosition, string keyType, string encodeType, string upperBound, string lowerBound, CancellationToken cancellationToken) = default` 

Returns an object containing rows from the specified table.

#### Parameters
* `cancellationToken` A cancellation token that can be used by other objects or threads to receive notice of cancellation.

#### Parameters
* `code` The name of the smart contract that controls the provided table

* `table` The name of the table to query

* `scope` The account to which this data belongs

* `index_position` Position of the index used, accepted parameters `primary`, `secondary`, `tertiary`, `fourth`, `fifth`, `sixth`, `seventh`, `eighth`, `ninth` , `tenth`

* `key_type` Type of key specified by index_position (for example - `uint64_t` or `name`)

#### Returns
Default Response

#### Exceptions
* `ApiException` A server side error occurred.

##### `public async Task ` [`PushTransactionAsync`](#class_hyperion_api_client_1_1_clients_1_1_chain_client_1a0b0ff0b3db671ccb82da9fafb785ac2c)`(object body, CancellationToken cancellationToken) = default` 

This method expects a transaction in JSON format and will attempt to apply it to the blockchain.

#### Parameters
* `cancellationToken` A cancellation token that can be used by other objects or threads to receive notice of cancellation.

#### Returns
Default Response

#### Exceptions
* `ApiException` A server side error occurred.

##### `public async Task ` [`PushTransactionsAsync`](#class_hyperion_api_client_1_1_clients_1_1_chain_client_1a98fa20d9d7836386416367425809d428)`(IEnumerable< object > body, CancellationToken cancellationToken) = default` 

This method expects a transaction in JSON format and will attempt to apply it to the blockchain.

#### Parameters
* `cancellationToken` A cancellation token that can be used by other objects or threads to receive notice of cancellation.

#### Returns
Default Response

#### Exceptions
* `ApiException` A server side error occurred.

##### `public async Task ` [`SendTransactionAsync`](#class_hyperion_api_client_1_1_clients_1_1_chain_client_1a06bd3fddbf5d37b9718c982a841c7cc1)`(object body, CancellationToken cancellationToken) = default` 

This method expects a transaction in JSON format and will attempt to apply it to the blockchain.

#### Parameters
* `cancellationToken` A cancellation token that can be used by other objects or threads to receive notice of cancellation.

#### Returns
Default Response

#### Exceptions
* `ApiException` A server side error occurred.

##### `private readonly ` [`IHttpHandler`](HyperionApiClient.md)` ` [`_httpHandler`](#class_hyperion_api_client_1_1_clients_1_1_chain_client_1a278528cd3027ee0a4ca8e04964f99674) 

