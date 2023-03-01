# class `AtomicMarketApiClient::MarketPlaces::MarketPlacesApi` 

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public async Task< ` [`MarketplacesDto`](AtomicMarketApiClient--MarketPlaces--MarketplacesDto.md)` > ` [`Marketplaces`](#class_atomic_market_api_client_1_1_market_places_1_1_market_places_api_1a233c2ba04477c9d19cb659a7f6904651)`()` | This function will return a list of marketplaces that are available to the user.
`public async Task< ` [`MarketplaceDto`](AtomicMarketApiClient--MarketPlaces--MarketplaceDto.md)` > ` [`Marketplace`](#class_atomic_market_api_client_1_1_market_places_1_1_market_places_api_1aed12921c2adfe0070a11a52a6093a1ea)`(string name)` | This function will return a `MarketplaceDto` object from the API.
`private readonly string ` [`_requestUriBase`](#class_atomic_market_api_client_1_1_market_places_1_1_market_places_api_1a1854c4909a1013a684af16fb52e8a387) | 
`private readonly ` [`IHttpHandler`](AtomicMarketApiClient.md)` ` [`_httpHandler`](#class_atomic_market_api_client_1_1_market_places_1_1_market_places_api_1a278528cd3027ee0a4ca8e04964f99674) | 
`private Uri ` [`MarketplacesUri`](#class_atomic_market_api_client_1_1_market_places_1_1_market_places_api_1aa1317eb8215268be5c8093cee07c5f53)`()` | It returns a Uri object that represents the URL for the marketplaces endpoint.
`private Uri ` [`MarketplaceUri`](#class_atomic_market_api_client_1_1_market_places_1_1_market_places_api_1a397cdf4c3cb7b066c6dd41a453e88ec0)`(string name)` | It takes a string and returns a URI.

## Members

##### `public async Task< ` [`MarketplacesDto`](AtomicMarketApiClient--MarketPlaces--MarketplacesDto.md)` > ` [`Marketplaces`](#class_atomic_market_api_client_1_1_market_places_1_1_market_places_api_1a233c2ba04477c9d19cb659a7f6904651)`()` 

This function will return a list of marketplaces that are available to the user.

#### Returns
A list of marketplaces.

##### `public async Task< ` [`MarketplaceDto`](AtomicMarketApiClient--MarketPlaces--MarketplaceDto.md)` > ` [`Marketplace`](#class_atomic_market_api_client_1_1_market_places_1_1_market_places_api_1aed12921c2adfe0070a11a52a6093a1ea)`(string name)` 

This function will return a `MarketplaceDto` object from the API.

#### Parameters
* `name` The name of the marketplace you want to retrieve.

#### Returns
A MarketplaceDto object

##### `private readonly string ` [`_requestUriBase`](#class_atomic_market_api_client_1_1_market_places_1_1_market_places_api_1a1854c4909a1013a684af16fb52e8a387) 

##### `private readonly ` [`IHttpHandler`](AtomicMarketApiClient.md)` ` [`_httpHandler`](#class_atomic_market_api_client_1_1_market_places_1_1_market_places_api_1a278528cd3027ee0a4ca8e04964f99674) 

##### `private Uri ` [`MarketplacesUri`](#class_atomic_market_api_client_1_1_market_places_1_1_market_places_api_1aa1317eb8215268be5c8093cee07c5f53)`()` 

It returns a Uri object that represents the URL for the marketplaces endpoint.

##### `private Uri ` [`MarketplaceUri`](#class_atomic_market_api_client_1_1_market_places_1_1_market_places_api_1a397cdf4c3cb7b066c6dd41a453e88ec0)`(string name)` 

It takes a string and returns a URI.

#### Parameters
* `name` The name of the marketplace you want to retrieve.

