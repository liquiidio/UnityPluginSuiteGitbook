# AccountsApi

## Summary

| Members                                                                                                                                                                                                                                                   | Descriptions                                                                                                        |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------- |
| `public AccountsDto` [`Accounts`](AtomicAssetsApiClient--Accounts--AccountsApi.md#class\_atomic\_assets\_api\_client\_1\_1\_accounts\_1\_1\_accounts\_api\_1a3cb498f35499fd037a88b3b1e37c2163)`()`                                                        | It returns a list of accounts.                                                                                      |
| `public AccountsDto` [`Accounts`](AtomicAssetsApiClient--Accounts--AccountsApi.md#class\_atomic\_assets\_api\_client\_1\_1\_accounts\_1\_1\_accounts\_api\_1a21b62093a68ab5c18774ae77add176ff)`(AccountsUriParameterBuilder accountsUriParameterBuilder)` | It returns a list of accounts.                                                                                      |
| `public AccountDto` [`Account`](AtomicAssetsApiClient--Accounts--AccountsApi.md#class\_atomic\_assets\_api\_client\_1\_1\_accounts\_1\_1\_accounts\_api\_1a5ac6ce36569f4531d3efc6976bd2d10d)`(string accountName)`                                        | This function will return an AccountDto object if the API call is successful, otherwise it will throw an exception. |
| `public AccountCollectionDto` [`Collection`](AtomicAssetsApiClient--Accounts--AccountsApi.md#class\_atomic\_assets\_api\_client\_1\_1\_accounts\_1\_1\_accounts\_api\_1ab3df414a63bbd8b27455e4dd5a3a3e93)`(string accountName, string collectionName)`    | This function will return an AccountCollectionDto object if the request is successful.                              |
| `private readonly string` [`_requestUriBase`](AtomicAssetsApiClient--Accounts--AccountsApi.md#class\_atomic\_assets\_api\_client\_1\_1\_accounts\_1\_1\_accounts\_api\_1a1854c4909a1013a684af16fb52e8a387)                                                |                                                                                                                     |
| `private Uri` [`AccountsUri`](AtomicAssetsApiClient--Accounts--AccountsApi.md#class\_atomic\_assets\_api\_client\_1\_1\_accounts\_1\_1\_accounts\_api\_1a5e08d8ac1bf0710cd7d921b3102965bd)`()`                                                            |                                                                                                                     |
| `private Uri` [`AccountsUri`](AtomicAssetsApiClient--Accounts--AccountsApi.md#class\_atomic\_assets\_api\_client\_1\_1\_accounts\_1\_1\_accounts\_api\_1afca248f16f36e27bbfb8749031ed2b2b)`(AccountsUriParameterBuilder accountsUriParameterBuilder)`     |                                                                                                                     |
| `private Uri` [`AccountUri`](AtomicAssetsApiClient--Accounts--AccountsApi.md#class\_atomic\_assets\_api\_client\_1\_1\_accounts\_1\_1\_accounts\_api\_1ab2a03af57777e9423eee43615699a34f)`(string accountName)`                                           |                                                                                                                     |
| `private Uri` [`AccountUri`](AtomicAssetsApiClient--Accounts--AccountsApi.md#class\_atomic\_assets\_api\_client\_1\_1\_accounts\_1\_1\_accounts\_api\_1a8c7769f72a922e37fa8d228a46ac8762)`(string accountName, string collectionName)`                    |                                                                                                                     |

## Members

### `public AccountsDto` [`Accounts`](AtomicAssetsApiClient--Accounts--AccountsApi.md#class\_atomic\_assets\_api\_client\_1\_1\_accounts\_1\_1\_accounts\_api\_1a3cb498f35499fd037a88b3b1e37c2163)`()`

It returns a list of accounts.

#### Returns

A list of accounts

##### `public AccountsDto` [`Accounts`](AtomicAssetsApiClient--Accounts--AccountsApi.md#class\_atomic\_assets\_api\_client\_1\_1\_accounts\_1\_1\_accounts\_api\_1a21b62093a68ab5c18774ae77add176ff)`(AccountsUriParameterBuilder accountsUriParameterBuilder)`

It returns a list of accounts.

#### Parameters

* `AccountsUriParameterBuilder` This is a class that contains all the parameters that can be passed to the Accounts endpoint.

#### Returns

A list of accounts.

### `public AccountDto` [`Account`](AtomicAssetsApiClient--Accounts--AccountsApi.md#class\_atomic\_assets\_api\_client\_1\_1\_accounts\_1\_1\_accounts\_api\_1a5ac6ce36569f4531d3efc6976bd2d10d)`(string accountName)`

This function will return an AccountDto object if the API call is successful, otherwise it will throw an exception.

#### Parameters

* `accountName` The name of the account you want to retrieve.

#### Returns

An AccountDto object

### `public AccountCollectionDto` [`Collection`](AtomicAssetsApiClient--Accounts--AccountsApi.md#class\_atomic\_assets\_api\_client\_1\_1\_accounts\_1\_1\_accounts\_api\_1ab3df414a63bbd8b27455e4dd5a3a3e93)`(string accountName, string collectionName)`

This function will return an AccountCollectionDto object if the request is successful.

#### Parameters

* `accountName` The name of the account you want to retrieve.
* `collectionName` The name of the collection you want to retrieve.

#### Returns

An AccountCollectionDto object.

### `private readonly string` [`_requestUriBase`](AtomicAssetsApiClient--Accounts--AccountsApi.md#class\_atomic\_assets\_api\_client\_1\_1\_accounts\_1\_1\_accounts\_api\_1a1854c4909a1013a684af16fb52e8a387)

### `private Uri` [`AccountsUri`](AtomicAssetsApiClient--Accounts--AccountsApi.md#class\_atomic\_assets\_api\_client\_1\_1\_accounts\_1\_1\_accounts\_api\_1a5e08d8ac1bf0710cd7d921b3102965bd)`()`

### `private Uri` [`AccountsUri`](AtomicAssetsApiClient--Accounts--AccountsApi.md#class\_atomic\_assets\_api\_client\_1\_1\_accounts\_1\_1\_accounts\_api\_1afca248f16f36e27bbfb8749031ed2b2b)`(AccountsUriParameterBuilder accountsUriParameterBuilder)`

### `private Uri` [`AccountUri`](AtomicAssetsApiClient--Accounts--AccountsApi.md#class\_atomic\_assets\_api\_client\_1\_1\_accounts\_1\_1\_accounts\_api\_1ab2a03af57777e9423eee43615699a34f)`(string accountName)`

### `private Uri` [`AccountUri`](AtomicAssetsApiClient--Accounts--AccountsApi.md#class\_atomic\_assets\_api\_client\_1\_1\_accounts\_1\_1\_accounts\_api\_1a8c7769f72a922e37fa8d228a46ac8762)`(string accountName, string collectionName)`
