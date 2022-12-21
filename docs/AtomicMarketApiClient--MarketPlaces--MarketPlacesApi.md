# class `AtomicMarketApiClient::MarketPlaces::MarketPlacesApi` 

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public ` [`MarketplacesDto`](AtomicMarketApiClient--MarketPlaces--MarketplacesDto.md)` ` [`Marketplaces`](#class_atomic_market_api_client_1_1_market_places_1_1_market_places_api_1a78a67d170323ad260b2051102c66d267)`()` | This function will return a list of marketplaces that are available to the user.
`public ` [`MarketplaceDto`](AtomicMarketApiClient--MarketPlaces--MarketplaceDto.md)` ` [`Marketplace`](#class_atomic_market_api_client_1_1_market_places_1_1_market_places_api_1a0cd5d4e88fd64208a1d543de10f14acb)`(string name)` | This function will return a `MarketplaceDto` object from the API.
`private readonly string ` [`_requestUriBase`](#class_atomic_market_api_client_1_1_market_places_1_1_market_places_api_1a1854c4909a1013a684af16fb52e8a387) | 
`private Uri ` [`MarketplacesUri`](#class_atomic_market_api_client_1_1_market_places_1_1_market_places_api_1aa1317eb8215268be5c8093cee07c5f53)`()` | It returns a Uri object that represents the URL for the marketplaces endpoint.
`private Uri ` [`MarketplaceUri`](#class_atomic_market_api_client_1_1_market_places_1_1_market_places_api_1a397cdf4c3cb7b066c6dd41a453e88ec0)`(string name)` | It takes a string and returns a URI.

## Members

##### `public ` [`MarketplacesDto`](AtomicMarketApiClient--MarketPlaces--MarketplacesDto.md)` ` [`Marketplaces`](#class_atomic_market_api_client_1_1_market_places_1_1_market_places_api_1a78a67d170323ad260b2051102c66d267)`()` 

This function will return a list of marketplaces that are available to the user.

#### Returns
A list of marketplaces.

##### `public ` [`MarketplaceDto`](AtomicMarketApiClient--MarketPlaces--MarketplaceDto.md)` ` [`Marketplace`](#class_atomic_market_api_client_1_1_market_places_1_1_market_places_api_1a0cd5d4e88fd64208a1d543de10f14acb)`(string name)` 

This function will return a `MarketplaceDto` object from the API.

#### Parameters
* `name` The name of the marketplace you want to retrieve.

#### Returns
A MarketplaceDto object

##### `private readonly string ` [`_requestUriBase`](#class_atomic_market_api_client_1_1_market_places_1_1_market_places_api_1a1854c4909a1013a684af16fb52e8a387) 

##### `private Uri ` [`MarketplacesUri`](#class_atomic_market_api_client_1_1_market_places_1_1_market_places_api_1aa1317eb8215268be5c8093cee07c5f53)`()` 

It returns a Uri object that represents the URL for the marketplaces endpoint.

##### `private Uri ` [`MarketplaceUri`](#class_atomic_market_api_client_1_1_market_places_1_1_market_places_api_1a397cdf4c3cb7b066c6dd41a453e88ec0)`(string name)` 

It takes a string and returns a URI.

#### Parameters
* `name` The name of the marketplace you want to retrieve.

