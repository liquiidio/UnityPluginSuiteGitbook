# class `AtomicMarketApiClient::Stats::StatsApi` 

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public async Task< ` [`CollectionsDto`](AtomicMarketApiClient--Stats--CollectionsDto.md)` > ` [`Collections`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1aded62930010a85157e50373773a6cace)`()` | This function will return a list of all collections in the database.
`public async Task< ` [`CollectionsDto`](AtomicMarketApiClient--Stats--CollectionsDto.md)` > ` [`Collections`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1aefd673a2b4f24941e0b0d92b8a20eceb)`(` [`StatsUriParameterBuilder`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md)` uriParameterBuilder)` | This function will return a `CollectionsDto` object that contains a list of `CollectionDto` objects.
`public async Task< ` [`CollectionDto`](AtomicMarketApiClient--Stats--CollectionDto.md)` > ` [`Collection`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1a8159b96fa830b83793fd21e5d147a854)`(string collectionName, ` [`StatsUriParameterBuilder`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md)` uriParameterBuilder)` | This function will return a `CollectionDto` object that contains the collection's name, the number of documents in the collection, the number of documents that have been deleted, the number of documents that are new (i.e. have not been persisted to disk), the number of documents that have been updated, the number of documents that have been replaced, the number of documents that have been removed, the number of documents that have been inserted, the number of documents that have been ignored, the number of documents that have been updated, the number of documents that have been replaced, the number of documents that have been removed, the number of documents that have been inserted, the number of documents that have been ignored, the number of documents that have been updated, the number of documents that have been replaced, the number of documents that have been removed, the number of documents that have been inserted, the number of documents that have been ignored, the number of documents that have been.
`public async Task< ` [`AccountsDto`](AtomicMarketApiClient--Stats--AccountsDto.md)` > ` [`Accounts`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1aea06c946a7e9ab7bdc8905119ecc63c0)`()` | This function will return a list of accounts for the current user.
`public async Task< ` [`AccountsDto`](AtomicMarketApiClient--Stats--AccountsDto.md)` > ` [`Accounts`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1af21e19d7edbd5c4a893fe75f3673387c)`(` [`StatsUriParameterBuilder`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md)` uriParameterBuilder)` | This function will return a list of accounts that match the criteria specified in the `uriParameterBuilder` parameter.
`public async Task< ` [`AccountDto`](AtomicMarketApiClient--Stats--AccountDto.md)` > ` [`Account`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1a77a0ea72456795262f5b4babf550a59e)`(string accountName, ` [`StatsUriParameterBuilder`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md)` uriParameterBuilder)` | This function will return an AccountDto object that contains the account information for the account name passed in.
`public async Task< ` [`SchemaDto`](AtomicMarketApiClient--Stats--SchemaDto.md)` > ` [`Schema`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1a548a9f75a5eca30ae1fe8480e2729b53)`(string collectionName)` | This function will return the schema for the specified collection.
`public async Task< ` [`SchemaDto`](AtomicMarketApiClient--Stats--SchemaDto.md)` > ` [`Schema`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1a0f802b475aa169804755488bc179ad29)`(string collectionName, ` [`StatsUriParameterBuilder`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md)` uriParameterBuilder)` | This function returns a schema for a given collection.
`public async Task< ` [`GraphDto`](AtomicMarketApiClient--Stats--GraphDto.md)` > ` [`Graph`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1a52cbbad919bb7888635e527c53a0adaa)`()` | This function will return a `GraphDto` object that contains the graph data.
`public async Task< ` [`SalesDto`](AtomicMarketApiClient--Stats--SalesDto.md)` > ` [`Sales`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1ac812e90e195c900bf42740aa1b8b4e43)`()` | The function sends a GET request to the API and returns the response as a SalesDto object.
`private readonly string ` [`_requestUriBase`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1a1854c4909a1013a684af16fb52e8a387) | 
`private readonly ` [`IHttpHandler`](AtomicMarketApiClient.md)` ` [`_httpHandler`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1a278528cd3027ee0a4ca8e04964f99674) | 
`private Uri ` [`CollectionsUri`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1a07e4028b75613f3c27b168e278447f34)`()` | It returns a URI that points to the collections endpoint of the stats API.
`private Uri ` [`CollectionsUri`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1a1ba975c33a750ebb181aa7743ca05563)`(` [`IUriParameterBuilder`](AtomicMarketApiClient.md)` uriParameterBuilder)` | It returns a URI for the collections endpoint
`private Uri ` [`CollectionUri`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1ae6ee87506dcf31f5710562e4299a93eb)`(string collectionName, ` [`IUriParameterBuilder`](AtomicMarketApiClient.md)` uriParameterBuilder)` | It returns a URI for the collection stats endpoint
`private Uri ` [`AccountsUri`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1a5e08d8ac1bf0710cd7d921b3102965bd)`()` | It returns a `Uri` object that represents the URL for the `/stats/accounts` endpoint.
`private Uri ` [`AccountsUri`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1ac1ca638b8fc8e71629788fd15de02e4b)`(` [`IUriParameterBuilder`](AtomicMarketApiClient.md)` uriParameterBuilder)` | It returns a URI for the `/stats/accounts` endpoint
`private Uri ` [`AccountUri`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1ad9c8103b60a0464ea2f44f87d684982e)`(string accountName, ` [`IUriParameterBuilder`](AtomicMarketApiClient.md)` uriParameterBuilder)` | It returns a URI for the account stats endpoint
`private Uri ` [`SchemasUri`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1a5c09b26c062c3f79bd9197188be9338e)`(string collectionName)` | It returns a URI for the schemas endpoint.
`private Uri ` [`SchemasUri`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1a2882b19df8fea482117a7ef079dea621)`(string collectionName, ` [`IUriParameterBuilder`](AtomicMarketApiClient.md)` uriParameterBuilder)` | It returns a URI for the `/stats/schemas/{collectionName}` endpoint
`private Uri ` [`GraphUri`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1a34c6ee73578f1d1fcfccf4e7bbb870a9)`()` | It returns a new Uri object that is the base request URI with the /stats/graph path appended to it.
`private Uri ` [`SalesUri`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1a40df74fdccb558ba58338c9fdff8c5cb)`()` | It returns a new Uri object that is the base request Uri with the `/stats/sales` path appended to it.

## Members

##### `public async Task< ` [`CollectionsDto`](AtomicMarketApiClient--Stats--CollectionsDto.md)` > ` [`Collections`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1aded62930010a85157e50373773a6cace)`()` 

This function will return a list of all collections in the database.

#### Returns
A list of collections

##### `public async Task< ` [`CollectionsDto`](AtomicMarketApiClient--Stats--CollectionsDto.md)` > ` [`Collections`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1aefd673a2b4f24941e0b0d92b8a20eceb)`(` [`StatsUriParameterBuilder`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md)` uriParameterBuilder)` 

This function will return a `CollectionsDto` object that contains a list of `CollectionDto` objects.

#### Parameters
* `StatsUriParameterBuilder` This is a class that contains all the parameters that can be passed to the API.

#### Returns
A CollectionsDto object.

##### `public async Task< ` [`CollectionDto`](AtomicMarketApiClient--Stats--CollectionDto.md)` > ` [`Collection`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1a8159b96fa830b83793fd21e5d147a854)`(string collectionName, ` [`StatsUriParameterBuilder`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md)` uriParameterBuilder)` 

This function will return a `CollectionDto` object that contains the collection's name, the number of documents in the collection, the number of documents that have been deleted, the number of documents that are new (i.e. have not been persisted to disk), the number of documents that have been updated, the number of documents that have been replaced, the number of documents that have been removed, the number of documents that have been inserted, the number of documents that have been ignored, the number of documents that have been updated, the number of documents that have been replaced, the number of documents that have been removed, the number of documents that have been inserted, the number of documents that have been ignored, the number of documents that have been updated, the number of documents that have been replaced, the number of documents that have been removed, the number of documents that have been inserted, the number of documents that have been ignored, the number of documents that have been.

#### Parameters
* `collectionName` The name of the collection you want to get stats for.

* `StatsUriParameterBuilder` This is a class that allows you to build the query string parameters for the API call.

#### Returns
A collection of documents.

##### `public async Task< ` [`AccountsDto`](AtomicMarketApiClient--Stats--AccountsDto.md)` > ` [`Accounts`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1aea06c946a7e9ab7bdc8905119ecc63c0)`()` 

This function will return a list of accounts for the current user.

#### Returns
A list of accounts

##### `public async Task< ` [`AccountsDto`](AtomicMarketApiClient--Stats--AccountsDto.md)` > ` [`Accounts`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1af21e19d7edbd5c4a893fe75f3673387c)`(` [`StatsUriParameterBuilder`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md)` uriParameterBuilder)` 

This function will return a list of accounts that match the criteria specified in the `uriParameterBuilder` parameter.

#### Parameters
* `StatsUriParameterBuilder` This is a class that contains all the parameters that can be passed to the API.

#### Returns
A list of accounts.

##### `public async Task< ` [`AccountDto`](AtomicMarketApiClient--Stats--AccountDto.md)` > ` [`Account`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1a77a0ea72456795262f5b4babf550a59e)`(string accountName, ` [`StatsUriParameterBuilder`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md)` uriParameterBuilder)` 

This function will return an AccountDto object that contains the account information for the account name passed in.

#### Parameters
* `accountName` The name of the account you want to get information about.

* `StatsUriParameterBuilder` This is a class that allows you to build the query string parameters for the API call.

#### Returns
An AccountDto object.

##### `public async Task< ` [`SchemaDto`](AtomicMarketApiClient--Stats--SchemaDto.md)` > ` [`Schema`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1a548a9f75a5eca30ae1fe8480e2729b53)`(string collectionName)` 

This function will return the schema for the specified collection.

#### Parameters
* `collectionName` The name of the collection you want to get the schema for.

#### Returns
A SchemaDto object

##### `public async Task< ` [`SchemaDto`](AtomicMarketApiClient--Stats--SchemaDto.md)` > ` [`Schema`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1a0f802b475aa169804755488bc179ad29)`(string collectionName, ` [`StatsUriParameterBuilder`](AtomicMarketApiClient--Stats--StatsUriParameterBuilder.md)` uriParameterBuilder)` 

This function returns a schema for a given collection.

#### Parameters
* `collectionName` The name of the collection you want to get the schema for.

* `StatsUriParameterBuilder` This is a class that contains all the parameters that can be passed to the API.

#### Returns
A SchemaDto object.

##### `public async Task< ` [`GraphDto`](AtomicMarketApiClient--Stats--GraphDto.md)` > ` [`Graph`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1a52cbbad919bb7888635e527c53a0adaa)`()` 

This function will return a `GraphDto` object that contains the graph data.

#### Returns
A GraphDto object

##### `public async Task< ` [`SalesDto`](AtomicMarketApiClient--Stats--SalesDto.md)` > ` [`Sales`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1ac812e90e195c900bf42740aa1b8b4e43)`()` 

The function sends a GET request to the API and returns the response as a SalesDto object.

#### Returns
A SalesDto object

##### `private readonly string ` [`_requestUriBase`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1a1854c4909a1013a684af16fb52e8a387) 

##### `private readonly ` [`IHttpHandler`](AtomicMarketApiClient.md)` ` [`_httpHandler`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1a278528cd3027ee0a4ca8e04964f99674) 

##### `private Uri ` [`CollectionsUri`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1a07e4028b75613f3c27b168e278447f34)`()` 

It returns a URI that points to the collections endpoint of the stats API.

##### `private Uri ` [`CollectionsUri`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1a1ba975c33a750ebb181aa7743ca05563)`(` [`IUriParameterBuilder`](AtomicMarketApiClient.md)` uriParameterBuilder)` 

It returns a URI for the collections endpoint

#### Parameters
* `IUriParameterBuilder` This is a class that is used to build the query string parameters for the request.

##### `private Uri ` [`CollectionUri`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1ae6ee87506dcf31f5710562e4299a93eb)`(string collectionName, ` [`IUriParameterBuilder`](AtomicMarketApiClient.md)` uriParameterBuilder)` 

It returns a URI for the collection stats endpoint

#### Parameters
* `collectionName` The name of the collection you want to get stats for.

* `IUriParameterBuilder` This is an interface that is used to build the query string parameters for the request.

##### `private Uri ` [`AccountsUri`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1a5e08d8ac1bf0710cd7d921b3102965bd)`()` 

It returns a `Uri` object that represents the URL for the `/stats/accounts` endpoint.

##### `private Uri ` [`AccountsUri`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1ac1ca638b8fc8e71629788fd15de02e4b)`(` [`IUriParameterBuilder`](AtomicMarketApiClient.md)` uriParameterBuilder)` 

It returns a URI for the `/stats/accounts` endpoint

#### Parameters
* `IUriParameterBuilder` This is a class that will build the query string parameters for the request.

##### `private Uri ` [`AccountUri`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1ad9c8103b60a0464ea2f44f87d684982e)`(string accountName, ` [`IUriParameterBuilder`](AtomicMarketApiClient.md)` uriParameterBuilder)` 

It returns a URI for the account stats endpoint

#### Parameters
* `accountName` The name of the account you want to get stats for.

* `IUriParameterBuilder` This is an interface that is used to build the query string parameters for the request.

##### `private Uri ` [`SchemasUri`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1a5c09b26c062c3f79bd9197188be9338e)`(string collectionName)` 

It returns a URI for the schemas endpoint.

#### Parameters
* `collectionName` The name of the collection you want to get the stats for.

##### `private Uri ` [`SchemasUri`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1a2882b19df8fea482117a7ef079dea621)`(string collectionName, ` [`IUriParameterBuilder`](AtomicMarketApiClient.md)` uriParameterBuilder)` 

It returns a URI for the `/stats/schemas/{collectionName}` endpoint

#### Parameters
* `collectionName` The name of the collection you want to get the schema for.

* `IUriParameterBuilder` This is a class that is used to build the query string parameters for the request.

##### `private Uri ` [`GraphUri`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1a34c6ee73578f1d1fcfccf4e7bbb870a9)`()` 

It returns a new Uri object that is the base request URI with the /stats/graph path appended to it.

##### `private Uri ` [`SalesUri`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1a40df74fdccb558ba58338c9fdff8c5cb)`()` 

It returns a new Uri object that is the base request Uri with the `/stats/sales` path appended to it.

