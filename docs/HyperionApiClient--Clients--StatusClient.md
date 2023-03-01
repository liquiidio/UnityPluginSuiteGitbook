# class `HyperionApiClient::Clients::StatusClient` 

```
class HyperionApiClient::Clients::StatusClient
  : public ClientExtensions
```

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public string ` [`BaseUrl`](#class_hyperion_api_client_1_1_clients_1_1_status_client_1a5e5e1c3b42a6c7ab84f8aeca3c9e570c) | 
`public ` [`StatusClient`](#class_hyperion_api_client_1_1_clients_1_1_status_client_1adad3c3f6f99bbb6f9761a4630d49df44)`(` [`IHttpHandler`](HyperionApiClient.md)` httpHandler)` | 
`public async Task< GetHealthResponse > ` [`HealthAsync`](#class_hyperion_api_client_1_1_clients_1_1_status_client_1a66a30b023ce8e396579381d59e17d308)`(CancellationToken cancellationToken) = default` | API Service Health Report.
`private readonly ` [`IHttpHandler`](HyperionApiClient.md)` ` [`_httpHandler`](#class_hyperion_api_client_1_1_clients_1_1_status_client_1a278528cd3027ee0a4ca8e04964f99674) | 

## Members

##### `public string ` [`BaseUrl`](#class_hyperion_api_client_1_1_clients_1_1_status_client_1a5e5e1c3b42a6c7ab84f8aeca3c9e570c) 

##### `public ` [`StatusClient`](#class_hyperion_api_client_1_1_clients_1_1_status_client_1adad3c3f6f99bbb6f9761a4630d49df44)`(` [`IHttpHandler`](HyperionApiClient.md)` httpHandler)` 

##### `public async Task< GetHealthResponse > ` [`HealthAsync`](#class_hyperion_api_client_1_1_clients_1_1_status_client_1a66a30b023ce8e396579381d59e17d308)`(CancellationToken cancellationToken) = default` 

API Service Health Report.

#### Parameters
* `cancellationToken` A cancellation token that can be used by other objects or threads to receive notice of cancellation.

#### Returns
Default Response

#### Exceptions
* `ApiException` A server side error occurred.

##### `private readonly ` [`IHttpHandler`](HyperionApiClient.md)` ` [`_httpHandler`](#class_hyperion_api_client_1_1_clients_1_1_status_client_1a278528cd3027ee0a4ca8e04964f99674) 

