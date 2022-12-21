# class `AtomicMarketApiClient::Auctions::AuctionsApi` 

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public ` [`AuctionsDto`](AtomicMarketApiClient--Auctions--AuctionsDto.md)` ` [`Auctions`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_api_1a70929369a29816434cb7aa9f1fdccf6d)`()` | <br/><br/> It returns a list of auctions.
`public ` [`AuctionsDto`](AtomicMarketApiClient--Auctions--AuctionsDto.md)` ` [`Auctions`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_api_1aeaf2bbabe05b932fa38d1b79497c7043)`(` [`AuctionsUriParameterBuilder`](AtomicMarketApiClient--Auctions--AuctionsUriParameterBuilder.md)` uriParametersBuilder)` | It returns a list of auctions.
`public ` [`AuctionDto`](AtomicMarketApiClient--Auctions--AuctionDto.md)` ` [`Auction`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_api_1a75d59e4d934eedd845e155b6d817c20c)`(int id)` | This function will make a GET request to the Auction API and return the AuctionDto object
`public ` [`LogsDto`](AtomicMarketApiClient--LogsDto.md)` ` [`AuctionLogs`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_api_1a178c421fd59a002913bea678297638d1)`(int id)` | It gets the logs of an auction.
`public ` [`LogsDto`](AtomicMarketApiClient--LogsDto.md)` ` [`AuctionLogs`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_api_1a6f24b011e6579c0d001529b9947dbb0f)`(int id, ` [`AuctionsUriParameterBuilder`](AtomicMarketApiClient--Auctions--AuctionsUriParameterBuilder.md)` auctionsUriParametersBuilder)` | It gets the logs for an auction.
`private readonly string ` [`_requestUriBase`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_api_1a1854c4909a1013a684af16fb52e8a387) | 
`private Uri ` [`AuctionsUri`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_api_1ab42930e70b2df9b11371f9a5cff854e7)`()` | It returns a new Uri object that is the base request URI with the /auctions path appended to it.
`private Uri ` [`AuctionsUri`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_api_1a903e474e53b0416ec3e5a4e2d79ce7be)`(` [`IUriParameterBuilder`](AtomicMarketApiClient--Core.md)` uriParameterBuilder)` | It takes a `IUriParameterBuilder` and returns a `Uri` that is the base URI for the auctions endpoint with the parameters built by the `IUriParameterBuilder` appended to the end.
`private Uri ` [`AuctionUri`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_api_1ad7b1311a6988538438e4bd558e0a880e)`(int id)` | It returns a URI for the auction with the given ID.
`private Uri ` [`AuctionsLogsUri`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_api_1a85f4050f63ad9b1645e4d1adbadf436e)`(int id)` | It returns a `Uri` object that represents the URL for the auction logs endpoint
`private Uri ` [`AuctionsLogsUri`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_api_1a2e4a85fd8c17dec0515efe4bd683fa77)`(int id, ` [`IUriParameterBuilder`](AtomicMarketApiClient--Core.md)` uriParameterBuilder)` | It returns a URI for the auctions logs endpoint

## Members

##### `public ` [`AuctionsDto`](AtomicMarketApiClient--Auctions--AuctionsDto.md)` ` [`Auctions`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_api_1a70929369a29816434cb7aa9f1fdccf6d)`()` 

<br/>
 It returns a list of auctions.

<return> AuctionsDto </return> <br/>

##### `public ` [`AuctionsDto`](AtomicMarketApiClient--Auctions--AuctionsDto.md)` ` [`Auctions`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_api_1aeaf2bbabe05b932fa38d1b79497c7043)`(` [`AuctionsUriParameterBuilder`](AtomicMarketApiClient--Auctions--AuctionsUriParameterBuilder.md)` uriParametersBuilder)` 

It returns a list of auctions.

#### Parameters
* `AuctionsUriParameterBuilder` This is a class that contains all the parameters that can be passed to the API.

<return> AuctionsDto </return>

##### `public ` [`AuctionDto`](AtomicMarketApiClient--Auctions--AuctionDto.md)` ` [`Auction`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_api_1a75d59e4d934eedd845e155b6d817c20c)`(int id)` 

This function will make a GET request to the Auction API and return the AuctionDto object

#### Parameters
* `id` The id of the auction you want to retrieve

#### Returns
An AuctionDto object

##### `public ` [`LogsDto`](AtomicMarketApiClient--LogsDto.md)` ` [`AuctionLogs`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_api_1a178c421fd59a002913bea678297638d1)`(int id)` 

It gets the logs of an auction.

#### Parameters
* `id` The id of the auction you want to get the logs for.

#### Returns
A list of logs for the auction.

##### `public ` [`LogsDto`](AtomicMarketApiClient--LogsDto.md)` ` [`AuctionLogs`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_api_1a6f24b011e6579c0d001529b9947dbb0f)`(int id, ` [`AuctionsUriParameterBuilder`](AtomicMarketApiClient--Auctions--AuctionsUriParameterBuilder.md)` auctionsUriParametersBuilder)` 

It gets the logs for an auction.

#### Parameters
* `id` The id of the auction you want to get the logs for.

* `AuctionsUriParameterBuilder` This is a class that contains all the parameters that can be passed to the API.

#### Returns
A LogsDto object.

##### `private readonly string ` [`_requestUriBase`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_api_1a1854c4909a1013a684af16fb52e8a387) 

##### `private Uri ` [`AuctionsUri`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_api_1ab42930e70b2df9b11371f9a5cff854e7)`()` 

It returns a new Uri object that is the base request URI with the /auctions path appended to it.

##### `private Uri ` [`AuctionsUri`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_api_1a903e474e53b0416ec3e5a4e2d79ce7be)`(` [`IUriParameterBuilder`](AtomicMarketApiClient--Core.md)` uriParameterBuilder)` 

It takes a `IUriParameterBuilder` and returns a `Uri` that is the base URI for the auctions endpoint with the parameters built by the `IUriParameterBuilder` appended to the end.

#### Parameters
* `IUriParameterBuilder` This is an interface that is used to build the query string parameters for the request.

##### `private Uri ` [`AuctionUri`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_api_1ad7b1311a6988538438e4bd558e0a880e)`(int id)` 

It returns a URI for the auction with the given ID.

#### Parameters
* `id` The id of the auction you want to get.

##### `private Uri ` [`AuctionsLogsUri`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_api_1a85f4050f63ad9b1645e4d1adbadf436e)`(int id)` 

It returns a `Uri` object that represents the URL for the auction logs endpoint

#### Parameters
* `id` The id of the auction you want to get the logs for.

##### `private Uri ` [`AuctionsLogsUri`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_api_1a2e4a85fd8c17dec0515efe4bd683fa77)`(int id, ` [`IUriParameterBuilder`](AtomicMarketApiClient--Core.md)` uriParameterBuilder)` 

It returns a URI for the auctions logs endpoint

#### Parameters
* `id` The id of the auction you want to get the logs for.

* `IUriParameterBuilder` This is an interface that is used to build the query string parameters.

