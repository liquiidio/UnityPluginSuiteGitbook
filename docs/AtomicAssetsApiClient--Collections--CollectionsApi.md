## class `AtomicAssetsApiClient::Collections::CollectionsApi` 

### Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public CollectionsDto `[`Collections`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_api_1a99d55526cbe148310bd140c1ea21e97a)`()` | It returns a list of all the collections in the database.
`public CollectionsDto `[`Collections`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_api_1a91e42b46049a909a59bec675cf5781c4)`(CollectionsUriParameterBuilder collectionsUriParameterBuilder)` | It takes a `CollectionsUriParameterBuilder` object as a parameter, builds an `HttpRequestMessage` object, sends it to the API, and returns a `CollectionsDto` object.
`public CollectionDto `[`Collection`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_api_1ae19d5cdb32cdec1b8fb41d58da4fa66f)`(string collectionName)` | This function will return a collection object from the API.
`public StatsDto `[`CollectionStats`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_api_1aaa047ee05af9518ee76cd7c56d17d35b)`(string collectionName)` | This function will return a StatsDto object that contains the stats for the collection specified in the collectionName parameter.
`public LogsDto `[`CollectionLogs`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_api_1ae459db65d80a896ba3ca50df6099e51c)`(string collectionName)` | This function will return a list of logs for a given collection.
`public LogsDto `[`CollectionLogs`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_api_1ab837b276acda594ee59a32bbcfa3899b)`(string collectionName, CollectionsUriParameterBuilder collectionsUriParameterBuilder)` | This function returns a list of logs for a given collection.
`private readonly string `[`_requestUriBase`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_api_1a1854c4909a1013a684af16fb52e8a387) | 
`private Uri `[`CollectionsUri`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_api_1a07e4028b75613f3c27b168e278447f34)`()` | 
`private Uri `[`CollectionsUri`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_api_1a1e26b6852994d59587b8fa84fafaac3d)`(CollectionsUriParameterBuilder collectionsUriParameterBuilder)` | 
`private Uri `[`CollectionUri`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_api_1aff56cb901f7ea42535fe8f007c9d4ae4)`(string collectionName)` | 
`private Uri `[`CollectionStatsUri`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_api_1a7937ea6f21a012bd204d562b6291b5dd)`(string collectionName)` | 
`private Uri `[`CollectionLogsUri`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_api_1a877ce097f0c95c800d21e40f42434e06)`(string collectionName)` | 
`private Uri `[`CollectionLogsUri`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_api_1a7f81992d78f135234ecb827d51d8ce0f)`(string collectionName, CollectionsUriParameterBuilder collectionsUriParameterBuilder)` | 

### Members

#### `public CollectionsDto `[`Collections`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_api_1a99d55526cbe148310bd140c1ea21e97a)`()` 

It returns a list of all the collections in the database.

#### Returns
A list of collections

#### `public CollectionsDto `[`Collections`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_api_1a91e42b46049a909a59bec675cf5781c4)`(CollectionsUriParameterBuilder collectionsUriParameterBuilder)` 

It takes a `CollectionsUriParameterBuilder` object as a parameter, builds an `HttpRequestMessage` object, sends it to the API, and returns a `CollectionsDto` object.

#### Parameters
* `CollectionsUriParameterBuilder` This is a class that contains all the parameters that can be passed to the API.

#### Returns
A collection of collections.

#### `public CollectionDto `[`Collection`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_api_1ae19d5cdb32cdec1b8fb41d58da4fa66f)`(string collectionName)` 

This function will return a collection object from the API.

#### Parameters
* `collectionName` The name of the collection you want to retrieve.

#### Returns
A collection of documents.

#### `public StatsDto `[`CollectionStats`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_api_1aaa047ee05af9518ee76cd7c56d17d35b)`(string collectionName)` 

This function will return a StatsDto object that contains the stats for the collection specified in the collectionName parameter.

#### Parameters
* `collectionName` The name of the collection you want to get stats for.

#### Returns
A StatsDto object

#### `public LogsDto `[`CollectionLogs`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_api_1ae459db65d80a896ba3ca50df6099e51c)`(string collectionName)` 

This function will return a list of logs for a given collection.

#### Parameters
* `collectionName` The name of the collection you want to get the logs for.

#### Returns
A LogsDto object

#### `public LogsDto `[`CollectionLogs`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_api_1ab837b276acda594ee59a32bbcfa3899b)`(string collectionName, CollectionsUriParameterBuilder collectionsUriParameterBuilder)` 

This function returns a list of logs for a given collection.

#### Parameters
* `collectionName` The name of the collection you want to get the logs for.

* `CollectionsUriParameterBuilder` This is a class that allows you to build the query string parameters for the request.

#### Returns
A LogsDto object

#### `private readonly string `[`_requestUriBase`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_api_1a1854c4909a1013a684af16fb52e8a387) 

#### `private Uri `[`CollectionsUri`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_api_1a07e4028b75613f3c27b168e278447f34)`()` 

#### `private Uri `[`CollectionsUri`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_api_1a1e26b6852994d59587b8fa84fafaac3d)`(CollectionsUriParameterBuilder collectionsUriParameterBuilder)` 

#### `private Uri `[`CollectionUri`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_api_1aff56cb901f7ea42535fe8f007c9d4ae4)`(string collectionName)` 

#### `private Uri `[`CollectionStatsUri`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_api_1a7937ea6f21a012bd204d562b6291b5dd)`(string collectionName)` 

#### `private Uri `[`CollectionLogsUri`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_api_1a877ce097f0c95c800d21e40f42434e06)`(string collectionName)` 

#### `private Uri `[`CollectionLogsUri`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_api_1a7f81992d78f135234ecb827d51d8ce0f)`(string collectionName, CollectionsUriParameterBuilder collectionsUriParameterBuilder)` 

