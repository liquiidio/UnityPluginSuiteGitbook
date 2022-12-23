# class `AtomicAssetsApiClient::Accounts::AccountsApi` 

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public ` [`AccountsDto`](AtomicAssetsApiClient--Accounts--AccountsDto.md)` ` [`Accounts`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_api_1a3cb498f35499fd037a88b3b1e37c2163)`()` | It returns a list of accounts.
`public ` [`AccountsDto`](AtomicAssetsApiClient--Accounts--AccountsDto.md)` ` [`Accounts`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_api_1a21b62093a68ab5c18774ae77add176ff)`(` [`AccountsUriParameterBuilder`](AtomicAssetsApiClient--Accounts--AccountsUriParameterBuilder.md)` accountsUriParameterBuilder)` | It returns a list of accounts.
`public ` [`AccountDto`](AtomicAssetsApiClient--Accounts--AccountDto.md)` ` [`Account`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_api_1a5ac6ce36569f4531d3efc6976bd2d10d)`(string accountName)` | This function will return an AccountDto object if the API call is successful, otherwise it will throw an exception.
`public ` [`AccountCollectionDto`](AtomicAssetsApiClient--Accounts--AccountCollectionDto.md)` ` [`Collection`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_api_1ab3df414a63bbd8b27455e4dd5a3a3e93)`(string accountName, string collectionName)` | This function will return an AccountCollectionDto object if the request is successful.
`private readonly string ` [`_requestUriBase`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_api_1a1854c4909a1013a684af16fb52e8a387) | 
`private Uri ` [`AccountsUri`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_api_1a5e08d8ac1bf0710cd7d921b3102965bd)`()` | It returns a `Uri` object that represents the `/accounts` endpoint
`private Uri ` [`AccountsUri`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_api_1afca248f16f36e27bbfb8749031ed2b2b)`(` [`AccountsUriParameterBuilder`](AtomicAssetsApiClient--Accounts--AccountsUriParameterBuilder.md)` accountsUriParameterBuilder)` | It takes an `AccountsUriParameterBuilder` object and returns a `Uri` object.
`private Uri ` [`AccountUri`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_api_1ab2a03af57777e9423eee43615699a34f)`(string accountName)` | It returns a URI for a given account name
`private Uri ` [`AccountUri`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_api_1a8c7769f72a922e37fa8d228a46ac8762)`(string accountName, string collectionName)` | This function returns a URI for a given account name and collection name

## Members

##### `public ` [`AccountsDto`](AtomicAssetsApiClient--Accounts--AccountsDto.md)` ` [`Accounts`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_api_1a3cb498f35499fd037a88b3b1e37c2163)`()` 

It returns a list of accounts.

#### Returns
A list of accounts

##### `public ` [`AccountsDto`](AtomicAssetsApiClient--Accounts--AccountsDto.md)` ` [`Accounts`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_api_1a21b62093a68ab5c18774ae77add176ff)`(` [`AccountsUriParameterBuilder`](AtomicAssetsApiClient--Accounts--AccountsUriParameterBuilder.md)` accountsUriParameterBuilder)` 

It returns a list of accounts.

#### Parameters
* `AccountsUriParameterBuilder` This is a class that contains all the parameters that can be passed to the Accounts endpoint.

#### Returns
A list of accounts.

##### `public ` [`AccountDto`](AtomicAssetsApiClient--Accounts--AccountDto.md)` ` [`Account`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_api_1a5ac6ce36569f4531d3efc6976bd2d10d)`(string accountName)` 

This function will return an AccountDto object if the API call is successful, otherwise it will throw an exception.

#### Parameters
* `accountName` The name of the account you want to retrieve.

#### Returns
An AccountDto object

##### `public ` [`AccountCollectionDto`](AtomicAssetsApiClient--Accounts--AccountCollectionDto.md)` ` [`Collection`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_api_1ab3df414a63bbd8b27455e4dd5a3a3e93)`(string accountName, string collectionName)` 

This function will return an AccountCollectionDto object if the request is successful.

#### Parameters
* `accountName` The name of the account you want to retrieve.

* `collectionName` The name of the collection you want to retrieve.

#### Returns
An AccountCollectionDto object.

##### `private readonly string ` [`_requestUriBase`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_api_1a1854c4909a1013a684af16fb52e8a387) 

##### `private Uri ` [`AccountsUri`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_api_1a5e08d8ac1bf0710cd7d921b3102965bd)`()` 

It returns a `Uri` object that represents the `/accounts` endpoint

##### `private Uri ` [`AccountsUri`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_api_1afca248f16f36e27bbfb8749031ed2b2b)`(` [`AccountsUriParameterBuilder`](AtomicAssetsApiClient--Accounts--AccountsUriParameterBuilder.md)` accountsUriParameterBuilder)` 

It takes an `AccountsUriParameterBuilder` object and returns a `Uri` object.

#### Parameters
* `AccountsUriParameterBuilder` A class that builds the query string parameters for the accounts endpoint.

##### `private Uri ` [`AccountUri`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_api_1ab2a03af57777e9423eee43615699a34f)`(string accountName)` 

It returns a URI for a given account name

#### Parameters
* `accountName` The name of the account to be created.

##### `private Uri ` [`AccountUri`](#class_atomic_assets_api_client_1_1_accounts_1_1_accounts_api_1a8c7769f72a922e37fa8d228a46ac8762)`(string accountName, string collectionName)` 

This function returns a URI for a given account name and collection name

#### Parameters
* `accountName` The name of the account.

* `collectionName` The name of the collection you want to query.

