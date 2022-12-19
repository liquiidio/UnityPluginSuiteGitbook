# class `HyperionApiClient::Clients::HistoryClient` 

```
class HyperionApiClient::Clients::HistoryClient
  : public ClientExtensions
```

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public string `[`BaseUrl`](#class_hyperion_api_client_1_1_clients_1_1_history_client_1a5e5e1c3b42a6c7ab84f8aeca3c9e570c) | 
`public  `[`HistoryClient`](#class_hyperion_api_client_1_1_clients_1_1_history_client_1afb0bb1a0f3845eb1875cb41a202e6e7e)`(HttpClient httpClient)` | 
`public async Task< GetApiSnapshotResponse > `[`GetAbiSnapshotAsync`](#class_hyperion_api_client_1_1_clients_1_1_history_client_1acf64321b0c1cbee53fa031aba5d3125d)`(string contract, int? block, bool? fetch, CancellationToken cancellationToken) = default` | fetch abi at specific block
`public async Task< GetActionsResponse > `[`GetActionsAsync`](#class_hyperion_api_client_1_1_clients_1_1_history_client_1aa6d8280d420cbebbe276925cd762965d)`(int? limit, int? skip, string account, string track, string filter, `[`Sort`](.github/workflows/documentation/md/HyperionApiClient--Models.md#namespace_hyperion_api_client_1_1_models_1ab865d2a43d5c0a9363bf5112589ea852)`? sort, string after, string before, bool? simple, bool? hotOnly, bool? noBinary, bool? checkLib, CancellationToken cancellationToken) = default` | get root actions
`public async Task< GetDeltasResponse > `[`GetDeltasAsync`](#class_hyperion_api_client_1_1_clients_1_1_history_client_1a797cb65f1f8d94ef24c8038542e5de47)`(int? limit, int? skip, string code, string scope, string table, string payer, string after, string before, CancellationToken cancellationToken) = default` | get state deltas
`public async Task< GetScheduleResponse > `[`GetScheduleAsync`](#class_hyperion_api_client_1_1_clients_1_1_history_client_1a28d621db2dafdc7461bbfd8a6fa5b64b)`(string producer, string key, string after, string before, int? version, CancellationToken cancellationToken) = default` | get producer schedule by version
`public async Task< GetTransactionResponse > `[`GetTransactionAsync`](#class_hyperion_api_client_1_1_clients_1_1_history_client_1ae275f7865fb94efdbd55893b279f944d)`(string id, CancellationToken cancellationToken) = default` | get transaction by id
`public async Task< GetBlockResponse > `[`GetBlockAsync`](#class_hyperion_api_client_1_1_clients_1_1_history_client_1a9926e9c95e3de2101968520481bd0257)`(uint? blockNum, string blockId, CancellationToken cancellationToken) = default` | get block traces
`private readonly HttpClient `[`_httpClient`](#class_hyperion_api_client_1_1_clients_1_1_history_client_1ad46239d4d974eb6987f330cce204da62) | 

## Members

### `public string `[`BaseUrl`](#class_hyperion_api_client_1_1_clients_1_1_history_client_1a5e5e1c3b42a6c7ab84f8aeca3c9e570c) 

### `public  `[`HistoryClient`](#class_hyperion_api_client_1_1_clients_1_1_history_client_1afb0bb1a0f3845eb1875cb41a202e6e7e)`(HttpClient httpClient)` 

### `public async Task< GetApiSnapshotResponse > `[`GetAbiSnapshotAsync`](#class_hyperion_api_client_1_1_clients_1_1_history_client_1acf64321b0c1cbee53fa031aba5d3125d)`(string contract, int? block, bool? fetch, CancellationToken cancellationToken) = default` 

fetch abi at specific block

#### Parameters
* `cancellationToken` A cancellation token that can be used by other objects or threads to receive notice of cancellation.

#### Parameters
* `contract` contract account

* `block` target block

* `fetch` should fetch the ABI

#### Returns
Default Response

#### Exceptions
* `ApiException` A server side error occurred.

### `public async Task< GetActionsResponse > `[`GetActionsAsync`](#class_hyperion_api_client_1_1_clients_1_1_history_client_1aa6d8280d420cbebbe276925cd762965d)`(int? limit, int? skip, string account, string track, string filter, `[`Sort`](.github/workflows/documentation/md/HyperionApiClient--Models.md#namespace_hyperion_api_client_1_1_models_1ab865d2a43d5c0a9363bf5112589ea852)`? sort, string after, string before, bool? simple, bool? hotOnly, bool? noBinary, bool? checkLib, CancellationToken cancellationToken) = default` 

get root actions

#### Parameters
* `cancellationToken` A cancellation token that can be used by other objects or threads to receive notice of cancellation.

#### Parameters
* `limit` limit of [n] results per page

* `skip` skip [n] results

* `account` notified account

* `track` total results to track (count) [number or true]

* `filter` code:name filter

* `sort` sort direction

* `after` filter after specified date (ISO8601)

* `before` filter before specified date (ISO8601)

* `simple` simplified output mode

* `hotOnly` search only the latest hot index

* `noBinary` exclude large binary data

* `checkLib` perform reversibility check

#### Exceptions
* `ApiException` A server side error occurred.

### `public async Task< GetDeltasResponse > `[`GetDeltasAsync`](#class_hyperion_api_client_1_1_clients_1_1_history_client_1a797cb65f1f8d94ef24c8038542e5de47)`(int? limit, int? skip, string code, string scope, string table, string payer, string after, string before, CancellationToken cancellationToken) = default` 

get state deltas

#### Parameters
* `cancellationToken` A cancellation token that can be used by other objects or threads to receive notice of cancellation.

#### Parameters
* `limit` limit of [n] results per page

* `skip` skip [n] results

* `code` contract account

* `scope` table scope

* `table` table name

* `payer` payer account

* `after` filter after specified date (ISO8601)

* `before` filter before specified date (ISO8601)

#### Exceptions
* `ApiException` A server side error occurred.

### `public async Task< GetScheduleResponse > `[`GetScheduleAsync`](#class_hyperion_api_client_1_1_clients_1_1_history_client_1a28d621db2dafdc7461bbfd8a6fa5b64b)`(string producer, string key, string after, string before, int? version, CancellationToken cancellationToken) = default` 

get producer schedule by version

#### Parameters
* `cancellationToken` A cancellation token that can be used by other objects or threads to receive notice of cancellation.

#### Parameters
* `producer` search by producer

* `key` search by key

* `after` filter after specified date (ISO8601)

* `before` filter before specified date (ISO8601)

* `version` schedule version

#### Exceptions
* `ApiException` A server side error occurred.

### `public async Task< GetTransactionResponse > `[`GetTransactionAsync`](#class_hyperion_api_client_1_1_clients_1_1_history_client_1ae275f7865fb94efdbd55893b279f944d)`(string id, CancellationToken cancellationToken) = default` 

get transaction by id

#### Parameters
* `cancellationToken` A cancellation token that can be used by other objects or threads to receive notice of cancellation.

#### Parameters
* `id` transaction id

#### Returns
Default Response

#### Exceptions
* `ApiException` A server side error occurred.

### `public async Task< GetBlockResponse > `[`GetBlockAsync`](#class_hyperion_api_client_1_1_clients_1_1_history_client_1a9926e9c95e3de2101968520481bd0257)`(uint? blockNum, string blockId, CancellationToken cancellationToken) = default` 

get block traces

#### Parameters
* `cancellationToken` A cancellation token that can be used by other objects or threads to receive notice of cancellation.

#### Exceptions
* `ApiException` A server side error occurred.

### `private readonly HttpClient `[`_httpClient`](#class_hyperion_api_client_1_1_clients_1_1_history_client_1ad46239d4d974eb6987f330cce204da62) 

