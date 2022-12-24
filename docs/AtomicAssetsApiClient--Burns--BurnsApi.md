# class `AtomicAssetsApiClient::Burns::BurnsApi` 

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public ` [`BurnsDto`](AtomicAssetsApiClient--Burns--BurnsDto.md)` ` [`Burns`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_api_1a2e4454210656355fc68d2fd454cf75ad)`()` | This function will make a GET request to the Burns endpoint and return the response as a BurnsDto object.
`public ` [`BurnsDto`](AtomicAssetsApiClient--Burns--BurnsDto.md)` ` [`Burns`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_api_1a7f8383ecd99252b57d68ee3fe1372aac)`(` [`BurnsUriParameterBuilder`](AtomicAssetsApiClient--Burns--BurnsUriParameterBuilder.md)` burnsUriParameterBuilder)` | This function will return a BurnsDto object if the API call is successful. Otherwise, it will throw an exception.
`public ` [`BurnDto`](AtomicAssetsApiClient--Burns--BurnDto.md)` ` [`Account`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_api_1a477590800625fbc1d4087ee8aec5350b)`(string accountName)` | It returns the burn amount for a given account.
`private readonly string ` [`_requestUriBase`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_api_1a1854c4909a1013a684af16fb52e8a387) | 
`private Uri ` [`BurnsUri`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_api_1ab7e0279e9f4a23c75ec9cd452b1cec78)`()` | This function returns a Uri object that represents the Burns endpoint
`private Uri ` [`BurnsUri`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_api_1a72a4a0af9ef4fa0f42ca09627055ca9e)`(` [`BurnsUriParameterBuilder`](AtomicAssetsApiClient--Burns--BurnsUriParameterBuilder.md)` burnsUriParameterBuilder)` | It takes a BurnsUriParameterBuilder object and returns a Uri object.
`private Uri ` [`BurnUri`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_api_1a4b9fa036cab638a320616ffc440c6eb3)`(string accountName)` | This function returns a URI that can be used to burn a specific account

## Members

##### `public ` [`BurnsDto`](AtomicAssetsApiClient--Burns--BurnsDto.md)` ` [`Burns`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_api_1a2e4454210656355fc68d2fd454cf75ad)`()` 

This function will make a GET request to the Burns endpoint and return the response as a BurnsDto object.

#### Returns
BurnsDto

##### `public ` [`BurnsDto`](AtomicAssetsApiClient--Burns--BurnsDto.md)` ` [`Burns`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_api_1a7f8383ecd99252b57d68ee3fe1372aac)`(` [`BurnsUriParameterBuilder`](AtomicAssetsApiClient--Burns--BurnsUriParameterBuilder.md)` burnsUriParameterBuilder)` 

This function will return a BurnsDto object if the API call is successful. Otherwise, it will throw an exception.

#### Parameters
* `BurnsUriParameterBuilder` This is a class that contains all the parameters that can be passed to the API.

#### Returns
A BurnsDto object.

##### `public ` [`BurnDto`](AtomicAssetsApiClient--Burns--BurnDto.md)` ` [`Account`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_api_1a477590800625fbc1d4087ee8aec5350b)`(string accountName)` 

It returns the burn amount for a given account.

#### Parameters
* `accountName` The name of the account to burn

#### Returns
A BurnDto object

##### `private readonly string ` [`_requestUriBase`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_api_1a1854c4909a1013a684af16fb52e8a387) 

##### `private Uri ` [`BurnsUri`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_api_1ab7e0279e9f4a23c75ec9cd452b1cec78)`()` 

This function returns a Uri object that represents the Burns endpoint

##### `private Uri ` [`BurnsUri`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_api_1a72a4a0af9ef4fa0f42ca09627055ca9e)`(` [`BurnsUriParameterBuilder`](AtomicAssetsApiClient--Burns--BurnsUriParameterBuilder.md)` burnsUriParameterBuilder)` 

It takes a BurnsUriParameterBuilder object and returns a Uri object.

#### Parameters
* `BurnsUriParameterBuilder` A class that builds the query string parameters for the URI.

##### `private Uri ` [`BurnUri`](#class_atomic_assets_api_client_1_1_burns_1_1_burns_api_1a4b9fa036cab638a320616ffc440c6eb3)`(string accountName)` 

This function returns a URI that can be used to burn a specific account

#### Parameters
* `accountName` The name of the account to burn.

