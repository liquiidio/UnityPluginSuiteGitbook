# class `AtomicMarketApiClient::Stats::StatsApi` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public CollectionsDto `[`Collections`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1a99d55526cbe148310bd140c1ea21e97a)`()` | This function will return a list of all collections in the database
`public CollectionsDto `[`Collections`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1a9ee68cbabd519bdbf0a5e5becb6adfb8)`(StatsUriParameterBuilder uriParameterBuilder)` | This function will return a `CollectionsDto` object that contains a list of `CollectionDto`<br/><br/>objects
`public CollectionDto `[`Collection`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1a94744e7cb4182c866d42d10bb5d4441c)`(string collectionName, StatsUriParameterBuilder uriParameterBuilder)` | This function will return a `CollectionDto` object that contains the collection's name, the number <br/><br/>of documents in the collection, the number of documents that have been deleted, the number of documents that are new (i.e. have not been persisted to disk), the number of documents that have been updated, the number of documents that have been replaced, the number of documents that have been removed, the number of documents that have been inserted, the number of documents that have been ignored, the number of documents that have been updated, the number of documents that have been replaced, the number of documents that have been removed, the number of documents that have been inserted, the number of documents that have been ignored, the number of documents that have been updated, the number of documents that have been replaced, the number of documents that have been removed, the number of documents that have been inserted, the number of documents that have been ignored, the number of documents that have been
`public AccountsDto `[`Accounts`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1a3cb498f35499fd037a88b3b1e37c2163)`()` | This function will return a list of accounts for the current user
`public AccountsDto `[`Accounts`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1a1aee62547caf2696855c3d18ef8d2be2)`(StatsUriParameterBuilder uriParameterBuilder)` | This function will return a list of accounts that match the criteria specified in the <br/><br/>`uriParameterBuilder` parameter
`public AccountDto `[`Account`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1a117e7abeab8e57b9439a62a124270b71)`(string accountName, StatsUriParameterBuilder uriParameterBuilder)` | This function will return an AccountDto object that contains the account information for the <br/><br/>account name passed in
`public SchemaDto `[`Schema`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1a010d66ee9d420f333f5bc096cfb02122)`(string collectionName)` | This function will return the schema for the specified collection
`public SchemaDto `[`Schema`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1abd9aa3a18365cf538bf0729a41e109e4)`(string collectionName, StatsUriParameterBuilder uriParameterBuilder)` | This function returns a schema for a given collection
`public GraphDto `[`Graph`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1a3750a373cd4414c35877b0742bc335e7)`()` | This function will return a `GraphDto` object that contains the graph data
`public SalesDto `[`Sales`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1aa0e37cd4086cddc4ba41ff9855d83b9b)`()` | The function sends a GET request to the API and returns the response as a SalesDto object
`private readonly string `[`_requestUriBase`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1a1854c4909a1013a684af16fb52e8a387) | 
`private Uri `[`CollectionsUri`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1a07e4028b75613f3c27b168e278447f34)`()` | 
`private Uri `[`CollectionsUri`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1a1ba975c33a750ebb181aa7743ca05563)`(IUriParameterBuilder uriParameterBuilder)` | 
`private Uri `[`CollectionUri`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1ae6ee87506dcf31f5710562e4299a93eb)`(string collectionName, IUriParameterBuilder uriParameterBuilder)` | 
`private Uri `[`AccountsUri`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1a5e08d8ac1bf0710cd7d921b3102965bd)`()` | 
`private Uri `[`AccountsUri`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1ac1ca638b8fc8e71629788fd15de02e4b)`(IUriParameterBuilder uriParameterBuilder)` | 
`private Uri `[`AccountUri`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1ad9c8103b60a0464ea2f44f87d684982e)`(string accountName, IUriParameterBuilder uriParameterBuilder)` | 
`private Uri `[`SchemasUri`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1a5c09b26c062c3f79bd9197188be9338e)`(string collectionName)` | 
`private Uri `[`SchemasUri`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1a2882b19df8fea482117a7ef079dea621)`(string collectionName, IUriParameterBuilder uriParameterBuilder)` | 
`private Uri `[`GraphUri`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1a34c6ee73578f1d1fcfccf4e7bbb870a9)`()` | 
`private Uri `[`SalesUri`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1a40df74fdccb558ba58338c9fdff8c5cb)`()` | 

## Members

### `public CollectionsDto `[`Collections`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1a99d55526cbe148310bd140c1ea21e97a)`()` 

This function will return a list of all collections in the database

#### Returns
A list of collections

### `public CollectionsDto `[`Collections`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1a9ee68cbabd519bdbf0a5e5becb6adfb8)`(StatsUriParameterBuilder uriParameterBuilder)` 

This function will return a `CollectionsDto` object that contains a list of `CollectionDto`

objects

#### Parameters
* `StatsUriParameterBuilder` This is a class that contains all the parameters that can be passed to the API.

#### Returns
A CollectionsDto object.

### `public CollectionDto `[`Collection`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1a94744e7cb4182c866d42d10bb5d4441c)`(string collectionName, StatsUriParameterBuilder uriParameterBuilder)` 

This function will return a `CollectionDto` object that contains the collection's name, the number 

of documents in the collection, the number of documents that have been deleted, the number of documents that are new (i.e. have not been persisted to disk), the number of documents that have been updated, the number of documents that have been replaced, the number of documents that have been removed, the number of documents that have been inserted, the number of documents that have been ignored, the number of documents that have been updated, the number of documents that have been replaced, the number of documents that have been removed, the number of documents that have been inserted, the number of documents that have been ignored, the number of documents that have been updated, the number of documents that have been replaced, the number of documents that have been removed, the number of documents that have been inserted, the number of documents that have been ignored, the number of documents that have been

#### Parameters
* `collectionName` The name of the collection you want to get stats for.

* `StatsUriParameterBuilder` This is a class that allows you to build the query string parameters for the API call.

#### Returns
A collection of documents.

### `public AccountsDto `[`Accounts`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1a3cb498f35499fd037a88b3b1e37c2163)`()` 

This function will return a list of accounts for the current user

#### Returns
A list of accounts

### `public AccountsDto `[`Accounts`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1a1aee62547caf2696855c3d18ef8d2be2)`(StatsUriParameterBuilder uriParameterBuilder)` 

This function will return a list of accounts that match the criteria specified in the 

`uriParameterBuilder` parameter

#### Parameters
* `StatsUriParameterBuilder` This is a class that contains all the parameters that can be passed to the API.

#### Returns
A list of accounts.

### `public AccountDto `[`Account`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1a117e7abeab8e57b9439a62a124270b71)`(string accountName, StatsUriParameterBuilder uriParameterBuilder)` 

This function will return an AccountDto object that contains the account information for the 

account name passed in

#### Parameters
* `accountName` The name of the account you want to get information about.

* `StatsUriParameterBuilder` This is a class that allows you to build the query string parameters for the API call.

#### Returns
An AccountDto object.

### `public SchemaDto `[`Schema`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1a010d66ee9d420f333f5bc096cfb02122)`(string collectionName)` 

This function will return the schema for the specified collection

#### Parameters
* `collectionName` The name of the collection you want to get the schema for.

#### Returns
A SchemaDto object

### `public SchemaDto `[`Schema`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1abd9aa3a18365cf538bf0729a41e109e4)`(string collectionName, StatsUriParameterBuilder uriParameterBuilder)` 

This function returns a schema for a given collection

#### Parameters
* `collectionName` The name of the collection you want to get the schema for.

* `StatsUriParameterBuilder` This is a class that contains all the parameters that can be passed to the API.

#### Returns
A SchemaDto object.

### `public GraphDto `[`Graph`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1a3750a373cd4414c35877b0742bc335e7)`()` 

This function will return a `GraphDto` object that contains the graph data

#### Returns
A GraphDto object

### `public SalesDto `[`Sales`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1aa0e37cd4086cddc4ba41ff9855d83b9b)`()` 

The function sends a GET request to the API and returns the response as a SalesDto object

#### Returns
A SalesDto object

### `private readonly string `[`_requestUriBase`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1a1854c4909a1013a684af16fb52e8a387) 

### `private Uri `[`CollectionsUri`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1a07e4028b75613f3c27b168e278447f34)`()` 

### `private Uri `[`CollectionsUri`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1a1ba975c33a750ebb181aa7743ca05563)`(IUriParameterBuilder uriParameterBuilder)` 

### `private Uri `[`CollectionUri`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1ae6ee87506dcf31f5710562e4299a93eb)`(string collectionName, IUriParameterBuilder uriParameterBuilder)` 

### `private Uri `[`AccountsUri`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1a5e08d8ac1bf0710cd7d921b3102965bd)`()` 

### `private Uri `[`AccountsUri`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1ac1ca638b8fc8e71629788fd15de02e4b)`(IUriParameterBuilder uriParameterBuilder)` 

### `private Uri `[`AccountUri`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1ad9c8103b60a0464ea2f44f87d684982e)`(string accountName, IUriParameterBuilder uriParameterBuilder)` 

### `private Uri `[`SchemasUri`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1a5c09b26c062c3f79bd9197188be9338e)`(string collectionName)` 

### `private Uri `[`SchemasUri`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1a2882b19df8fea482117a7ef079dea621)`(string collectionName, IUriParameterBuilder uriParameterBuilder)` 

### `private Uri `[`GraphUri`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1a34c6ee73578f1d1fcfccf4e7bbb870a9)`()` 

### `private Uri `[`SalesUri`](#class_atomic_market_api_client_1_1_stats_1_1_stats_api_1a40df74fdccb558ba58338c9fdff8c5cb)`()` 

