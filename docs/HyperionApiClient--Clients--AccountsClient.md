# class `HyperionApiClient::Clients::AccountsClient` 

```
class HyperionApiClient::Clients::AccountsClient
  : public ClientExtensions
```

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public string `[`BaseUrl`](#class_hyperion_api_client_1_1_clients_1_1_accounts_client_1a5e5e1c3b42a6c7ab84f8aeca3c9e570c) | 
`public  `[`AccountsClient`](#class_hyperion_api_client_1_1_clients_1_1_accounts_client_1a9ac22a9cdfa1aee84aca6f92790cadfb)`(HttpClient httpClient)` | 
`public async Task< GetCreatedAccountsResponse > `[`GetCreatedAccountsAsync`](#class_hyperion_api_client_1_1_clients_1_1_accounts_client_1a635c3eab451507a0d8e5a4bb8ed90072)`(string account, int? limit, int? skip, CancellationToken cancellationToken) = default` | get created accounts
`public async Task< GetCreatorResponse > `[`GetCreatorAsync`](#class_hyperion_api_client_1_1_clients_1_1_accounts_client_1a69b6295546037d1b1719172b91babdb0)`(string account, CancellationToken cancellationToken) = default` | get account creator
`public async Task< GetAccountResponse > `[`GetAccountAsync`](#class_hyperion_api_client_1_1_clients_1_1_accounts_client_1a8f28c769216fc1f7240aa7cdf9a6c64a)`(string account, int? limit, int? skip, CancellationToken cancellationToken) = default` | get account summary
`public async Task< GetKeyAccountsWithPermissionsResponse > `[`GetKeyAccountsAsync`](#class_hyperion_api_client_1_1_clients_1_1_accounts_client_1ac9561611402f182b3998a5e3abe24d6e)`(string publicKey, int? limit, int? skip, bool? details, CancellationToken cancellationToken) = default` | get accounts by public key
`public async Task< GetLinksResponse > `[`GetLinksAsync`](#class_hyperion_api_client_1_1_clients_1_1_accounts_client_1ae3e355d0616ba13263433540c59cf76b)`(string account, string code, string action, string permission, CancellationToken cancellationToken) = default` | get permission links
`public async Task< GetTokensResponse > `[`GetTokensAsync`](#class_hyperion_api_client_1_1_clients_1_1_accounts_client_1a9ff3161c00ddb34dcec834b2b36f9646)`(string account, int? limit, int? skip, CancellationToken cancellationToken) = default` | get all tokens
`public async Task< GetControlledAccountsResponse > `[`GetControlledAccountsAsync`](#class_hyperion_api_client_1_1_clients_1_1_accounts_client_1a69664f91962a139c1b146714d202ce9a)`(string controllingAccount, CancellationToken cancellationToken) = default` | get controlled accounts by controlling accounts
`private readonly HttpClient `[`_httpClient`](#class_hyperion_api_client_1_1_clients_1_1_accounts_client_1ad46239d4d974eb6987f330cce204da62) | 

## Members

### `public string `[`BaseUrl`](#class_hyperion_api_client_1_1_clients_1_1_accounts_client_1a5e5e1c3b42a6c7ab84f8aeca3c9e570c) 

### `public  `[`AccountsClient`](#class_hyperion_api_client_1_1_clients_1_1_accounts_client_1a9ac22a9cdfa1aee84aca6f92790cadfb)`(HttpClient httpClient)` 

### `public async Task< GetCreatedAccountsResponse > `[`GetCreatedAccountsAsync`](#class_hyperion_api_client_1_1_clients_1_1_accounts_client_1a635c3eab451507a0d8e5a4bb8ed90072)`(string account, int? limit, int? skip, CancellationToken cancellationToken) = default` 

get created accounts

#### Parameters
* `cancellationToken` A cancellation token that can be used by other objects or threads to receive notice of cancellation.

#### Parameters
* `account` creator account

* `limit` limit of [n] results per page

* `skip` skip [n] results

#### Exceptions
* `ApiException` A server side error occurred.

### `public async Task< GetCreatorResponse > `[`GetCreatorAsync`](#class_hyperion_api_client_1_1_clients_1_1_accounts_client_1a69b6295546037d1b1719172b91babdb0)`(string account, CancellationToken cancellationToken) = default` 

get account creator

#### Parameters
* `cancellationToken` A cancellation token that can be used by other objects or threads to receive notice of cancellation.

#### Parameters
* `account` created account

#### Exceptions
* `ApiException` A server side error occurred.

### `public async Task< GetAccountResponse > `[`GetAccountAsync`](#class_hyperion_api_client_1_1_clients_1_1_accounts_client_1a8f28c769216fc1f7240aa7cdf9a6c64a)`(string account, int? limit, int? skip, CancellationToken cancellationToken) = default` 

get account summary

#### Parameters
* `cancellationToken` A cancellation token that can be used by other objects or threads to receive notice of cancellation.

#### Parameters
* `account` account name

* `limit` limit of [n] results per page

* `skip` skip [n] results

#### Exceptions
* `ApiException` A server side error occurred.

### `public async Task< GetKeyAccountsWithPermissionsResponse > `[`GetKeyAccountsAsync`](#class_hyperion_api_client_1_1_clients_1_1_accounts_client_1ac9561611402f182b3998a5e3abe24d6e)`(string publicKey, int? limit, int? skip, bool? details, CancellationToken cancellationToken) = default` 

get accounts by public key

#### Parameters
* `cancellationToken` A cancellation token that can be used by other objects or threads to receive notice of cancellation.

#### Parameters
* `public_key` public key

* `limit` limit of [n] results per page

* `skip` skip [n] results

* `details` include permission details

#### Exceptions
* `ApiException` A server side error occurred.

### `public async Task< GetLinksResponse > `[`GetLinksAsync`](#class_hyperion_api_client_1_1_clients_1_1_accounts_client_1ae3e355d0616ba13263433540c59cf76b)`(string account, string code, string action, string permission, CancellationToken cancellationToken) = default` 

get permission links

#### Parameters
* `cancellationToken` A cancellation token that can be used by other objects or threads to receive notice of cancellation.

#### Parameters
* `account` account name

* `code` contract name

* `action` method name

* `permission` permission name

#### Exceptions
* `ApiException` A server side error occurred.

### `public async Task< GetTokensResponse > `[`GetTokensAsync`](#class_hyperion_api_client_1_1_clients_1_1_accounts_client_1a9ff3161c00ddb34dcec834b2b36f9646)`(string account, int? limit, int? skip, CancellationToken cancellationToken) = default` 

get all tokens

#### Parameters
* `cancellationToken` A cancellation token that can be used by other objects or threads to receive notice of cancellation.

#### Parameters
* `account` account name

* `limit` limit of [n] results per page

* `skip` skip [n] results

#### Returns
Default Response

#### Exceptions
* `ApiException` A server side error occurred.

### `public async Task< GetControlledAccountsResponse > `[`GetControlledAccountsAsync`](#class_hyperion_api_client_1_1_clients_1_1_accounts_client_1a69664f91962a139c1b146714d202ce9a)`(string controllingAccount, CancellationToken cancellationToken) = default` 

get controlled accounts by controlling accounts

#### Parameters
* `cancellationToken` A cancellation token that can be used by other objects or threads to receive notice of cancellation.

#### Exceptions
* `ApiException` A server side error occurred.

### `private readonly HttpClient `[`_httpClient`](#class_hyperion_api_client_1_1_clients_1_1_accounts_client_1ad46239d4d974eb6987f330cce204da62) 

