# class `AtomicAssetsApiClient::Collections::CollectionsApi` 

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public async Task< ` [`CollectionsDto`](AtomicAssetsApiClient--Collections--CollectionsDto.md)` > ` [`Collections`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_api_1aded62930010a85157e50373773a6cace)`()` | It returns a list of all the collections in the database.
`public async Task< ` [`CollectionsDto`](AtomicAssetsApiClient--Collections--CollectionsDto.md)` > ` [`Collections`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_api_1aaded815ecdafbfc5a187d855118b9f80)`(` [`CollectionsUriParameterBuilder`](AtomicAssetsApiClient--Collections--CollectionsUriParameterBuilder.md)` collectionsUriParameterBuilder)` | It takes a `CollectionsUriParameterBuilder` object as a parameter, builds an `HttpRequestMessage` object, sends it to the API, and returns a `CollectionsDto` object.
`public async Task< ` [`CollectionDto`](AtomicAssetsApiClient--Collections--CollectionDto.md)` > ` [`Collection`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_api_1a3fa79176e5989a427376b0d805bfef37)`(string collectionName)` | This function will return a collection object from the API.
`public async Task< ` [`StatsDto`](AtomicAssetsApiClient--StatsDto.md)` > ` [`CollectionStats`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_api_1a98eb61d8ce2f790d07357280fd693a89)`(string collectionName)` | This function will return a StatsDto object that contains the stats for the collection specified in the collectionName parameter.
`public async Task< ` [`LogsDto`](AtomicAssetsApiClient--LogsDto.md)` > ` [`CollectionLogs`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_api_1a12ddcb9a0840ea6985174036b424a9b0)`(string collectionName)` | This function will return a list of logs for a given collection.
`public async Task< ` [`LogsDto`](AtomicAssetsApiClient--LogsDto.md)` > ` [`CollectionLogs`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_api_1a3d0f8dc31cb0576e4560c8d11817aba1)`(string collectionName, ` [`CollectionsUriParameterBuilder`](AtomicAssetsApiClient--Collections--CollectionsUriParameterBuilder.md)` collectionsUriParameterBuilder)` | This function returns a list of logs for a given collection.
`private readonly string ` [`_requestUriBase`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_api_1a1854c4909a1013a684af16fb52e8a387) | 
`private readonly ` [`IHttpHandler`](AtomicAssetsApiClient.md)` ` [`_httpHander`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_api_1a9d6aefe5d22f75d6325426f4e58efe7a) | 
`private Uri ` [`CollectionsUri`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_api_1a07e4028b75613f3c27b168e278447f34)`()` | It returns a Uri object that represents the URL for the collections endpoint.
`private Uri ` [`CollectionsUri`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_api_1a1e26b6852994d59587b8fa84fafaac3d)`(` [`CollectionsUriParameterBuilder`](AtomicAssetsApiClient--Collections--CollectionsUriParameterBuilder.md)` collectionsUriParameterBuilder)` | It takes a `CollectionsUriParameterBuilder` object as a parameter and returns a `Uri` object.
`private Uri ` [`CollectionUri`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_api_1aff56cb901f7ea42535fe8f007c9d4ae4)`(string collectionName)` | Given a collection name, return a Uri object that represents the collection's endpoint.
`private Uri ` [`CollectionStatsUri`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_api_1a7937ea6f21a012bd204d562b6291b5dd)`(string collectionName)` | It returns a URI that points to the stats endpoint for a given collection.
`private Uri ` [`CollectionLogsUri`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_api_1a877ce097f0c95c800d21e40f42434e06)`(string collectionName)` | It returns a URI for the collection logs endpoint.
`private Uri ` [`CollectionLogsUri`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_api_1a7f81992d78f135234ecb827d51d8ce0f)`(string collectionName, ` [`CollectionsUriParameterBuilder`](AtomicAssetsApiClient--Collections--CollectionsUriParameterBuilder.md)` collectionsUriParameterBuilder)` | It returns a Uri object that represents the URL for the collection logs endpoint.

## Members

##### `public async Task< ` [`CollectionsDto`](AtomicAssetsApiClient--Collections--CollectionsDto.md)` > ` [`Collections`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_api_1aded62930010a85157e50373773a6cace)`()` 

It returns a list of all the collections in the database.

#### Returns
A list of collections

##### `public async Task< ` [`CollectionsDto`](AtomicAssetsApiClient--Collections--CollectionsDto.md)` > ` [`Collections`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_api_1aaded815ecdafbfc5a187d855118b9f80)`(` [`CollectionsUriParameterBuilder`](AtomicAssetsApiClient--Collections--CollectionsUriParameterBuilder.md)` collectionsUriParameterBuilder)` 

It takes a `CollectionsUriParameterBuilder` object as a parameter, builds an `HttpRequestMessage` object, sends it to the API, and returns a `CollectionsDto` object.

#### Parameters
* `CollectionsUriParameterBuilder` This is a class that contains all the parameters that can be passed to the API.

#### Returns
A collection of collections.

##### `public async Task< ` [`CollectionDto`](AtomicAssetsApiClient--Collections--CollectionDto.md)` > ` [`Collection`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_api_1a3fa79176e5989a427376b0d805bfef37)`(string collectionName)` 

This function will return a collection object from the API.

#### Parameters
* `collectionName` The name of the collection you want to retrieve.

#### Returns
A collection of documents.

##### `public async Task< ` [`StatsDto`](AtomicAssetsApiClient--StatsDto.md)` > ` [`CollectionStats`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_api_1a98eb61d8ce2f790d07357280fd693a89)`(string collectionName)` 

This function will return a StatsDto object that contains the stats for the collection specified in the collectionName parameter.

#### Parameters
* `collectionName` The name of the collection you want to get stats for.

#### Returns
A StatsDto object

##### `public async Task< ` [`LogsDto`](AtomicAssetsApiClient--LogsDto.md)` > ` [`CollectionLogs`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_api_1a12ddcb9a0840ea6985174036b424a9b0)`(string collectionName)` 

This function will return a list of logs for a given collection.

#### Parameters
* `collectionName` The name of the collection you want to get the logs for.

#### Returns
A LogsDto object

##### `public async Task< ` [`LogsDto`](AtomicAssetsApiClient--LogsDto.md)` > ` [`CollectionLogs`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_api_1a3d0f8dc31cb0576e4560c8d11817aba1)`(string collectionName, ` [`CollectionsUriParameterBuilder`](AtomicAssetsApiClient--Collections--CollectionsUriParameterBuilder.md)` collectionsUriParameterBuilder)` 

This function returns a list of logs for a given collection.

#### Parameters
* `collectionName` The name of the collection you want to get the logs for.

* `CollectionsUriParameterBuilder` This is a class that allows you to build the query string parameters for the request.

#### Returns
A LogsDto object

##### `private readonly string ` [`_requestUriBase`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_api_1a1854c4909a1013a684af16fb52e8a387) 

##### `private readonly ` [`IHttpHandler`](AtomicAssetsApiClient.md)` ` [`_httpHander`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_api_1a9d6aefe5d22f75d6325426f4e58efe7a) 

##### `private Uri ` [`CollectionsUri`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_api_1a07e4028b75613f3c27b168e278447f34)`()` 

It returns a Uri object that represents the URL for the collections endpoint.

##### `private Uri ` [`CollectionsUri`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_api_1a1e26b6852994d59587b8fa84fafaac3d)`(` [`CollectionsUriParameterBuilder`](AtomicAssetsApiClient--Collections--CollectionsUriParameterBuilder.md)` collectionsUriParameterBuilder)` 

It takes a `CollectionsUriParameterBuilder` object as a parameter and returns a `Uri` object.

#### Parameters
* `CollectionsUriParameterBuilder` A class that builds the query string parameters for the collections endpoint.

##### `private Uri ` [`CollectionUri`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_api_1aff56cb901f7ea42535fe8f007c9d4ae4)`(string collectionName)` 

Given a collection name, return a Uri object that represents the collection's endpoint.

#### Parameters
* `collectionName` The name of the collection you want to query.

##### `private Uri ` [`CollectionStatsUri`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_api_1a7937ea6f21a012bd204d562b6291b5dd)`(string collectionName)` 

It returns a URI that points to the stats endpoint for a given collection.

#### Parameters
* `collectionName` The name of the collection you want to get stats for.

##### `private Uri ` [`CollectionLogsUri`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_api_1a877ce097f0c95c800d21e40f42434e06)`(string collectionName)` 

It returns a URI for the collection logs endpoint.

#### Parameters
* `collectionName` The name of the collection you want to get the logs for.

##### `private Uri ` [`CollectionLogsUri`](#class_atomic_assets_api_client_1_1_collections_1_1_collections_api_1a7f81992d78f135234ecb827d51d8ce0f)`(string collectionName, ` [`CollectionsUriParameterBuilder`](AtomicAssetsApiClient--Collections--CollectionsUriParameterBuilder.md)` collectionsUriParameterBuilder)` 

It returns a Uri object that represents the URL for the collection logs endpoint.

#### Parameters
* `collectionName` The name of the collection you want to get the logs for.

* `CollectionsUriParameterBuilder` This is a class that builds the query parameters for the request.

