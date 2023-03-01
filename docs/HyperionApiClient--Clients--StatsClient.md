# class `HyperionApiClient::Clients::StatsClient` 

```
class HyperionApiClient::Clients::StatsClient
  : public ClientExtensions
```

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public string ` [`BaseUrl`](#class_hyperion_api_client_1_1_clients_1_1_stats_client_1a5e5e1c3b42a6c7ab84f8aeca3c9e570c) | 
`public ` [`StatsClient`](#class_hyperion_api_client_1_1_clients_1_1_stats_client_1a7e7916892bc06fc0ef9fca9d04f15552)`(` [`IHttpHandler`](HyperionApiClient.md)` httpHandler)` | 
`public async Task< GetActionUsageResponse > ` [`GetActionUsageAsync`](#class_hyperion_api_client_1_1_clients_1_1_stats_client_1afdf2c1723afa8ffa992e21ce74b3fdb7)`(string period, string endDate, bool? uniqueActors, CancellationToken cancellationToken) = default` | get action and transaction stats for a given period
`public async Task< GetMissedBlocksResponse > ` [`GetMissedBlocksAsync`](#class_hyperion_api_client_1_1_clients_1_1_stats_client_1ab662ce58fd786d0ee405c686f471a5e3)`(string producer, string after, string before, int? minBlocks, CancellationToken cancellationToken) = default` | get missed blocks
`public async Task< GetResourceUsageResponse > ` [`GetResourceUsageAsync`](#class_hyperion_api_client_1_1_clients_1_1_stats_client_1a5b1e6532ea145738b08f16289eebf6ef)`(string code, string action, CancellationToken cancellationToken) = default` | get resource usage stats for a specific action
`private readonly ` [`IHttpHandler`](HyperionApiClient.md)` ` [`_httpHandler`](#class_hyperion_api_client_1_1_clients_1_1_stats_client_1a278528cd3027ee0a4ca8e04964f99674) | 

## Members

##### `public string ` [`BaseUrl`](#class_hyperion_api_client_1_1_clients_1_1_stats_client_1a5e5e1c3b42a6c7ab84f8aeca3c9e570c) 

##### `public ` [`StatsClient`](#class_hyperion_api_client_1_1_clients_1_1_stats_client_1a7e7916892bc06fc0ef9fca9d04f15552)`(` [`IHttpHandler`](HyperionApiClient.md)` httpHandler)` 

##### `public async Task< GetActionUsageResponse > ` [`GetActionUsageAsync`](#class_hyperion_api_client_1_1_clients_1_1_stats_client_1afdf2c1723afa8ffa992e21ce74b3fdb7)`(string period, string endDate, bool? uniqueActors, CancellationToken cancellationToken) = default` 

get action and transaction stats for a given period

#### Parameters
* `cancellationToken` A cancellation token that can be used by other objects or threads to receive notice of cancellation.

#### Parameters
* `period` analysis period

* `end_date` final date

* `unique_actors` compute unique actors

#### Returns
Default Response

#### Exceptions
* `ApiException` A server side error occurred.

##### `public async Task< GetMissedBlocksResponse > ` [`GetMissedBlocksAsync`](#class_hyperion_api_client_1_1_clients_1_1_stats_client_1ab662ce58fd786d0ee405c686f471a5e3)`(string producer, string after, string before, int? minBlocks, CancellationToken cancellationToken) = default` 

get missed blocks

#### Parameters
* `cancellationToken` A cancellation token that can be used by other objects or threads to receive notice of cancellation.

#### Parameters
* `producer` filter by producer

* `after` filter after specified date (ISO8601)

* `before` filter before specified date (ISO8601)

* `min_blocks` min. blocks threshold

#### Exceptions
* `ApiException` A server side error occurred.

##### `public async Task< GetResourceUsageResponse > ` [`GetResourceUsageAsync`](#class_hyperion_api_client_1_1_clients_1_1_stats_client_1a5b1e6532ea145738b08f16289eebf6ef)`(string code, string action, CancellationToken cancellationToken) = default` 

get resource usage stats for a specific action

#### Parameters
* `cancellationToken` A cancellation token that can be used by other objects or threads to receive notice of cancellation.

#### Parameters
* `code` contract

* `action` action name

#### Returns
Default Response

#### Exceptions
* `ApiException` A server side error occurred.

##### `private readonly ` [`IHttpHandler`](HyperionApiClient.md)` ` [`_httpHandler`](#class_hyperion_api_client_1_1_clients_1_1_stats_client_1a278528cd3027ee0a4ca8e04964f99674) 

