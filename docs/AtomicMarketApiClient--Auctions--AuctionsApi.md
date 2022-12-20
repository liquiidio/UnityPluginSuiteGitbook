# class `AtomicMarketApiClient::Auctions::AuctionsApi` 

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public ` [`AuctionsDto`](.github/workflows/documentation/md/AtomicMarketApiClient--Auctions--AuctionsDto.md#class_atomic_market_api_client_1_1_auctions_1_1_auctions_dto)` ` [`Auctions`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_api_1a70929369a29816434cb7aa9f1fdccf6d)`()` | <br/><br/> It returns a list of auctions.
`public ` [`AuctionsDto`](.github/workflows/documentation/md/AtomicMarketApiClient--Auctions--AuctionsDto.md#class_atomic_market_api_client_1_1_auctions_1_1_auctions_dto)` ` [`Auctions`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_api_1aeaf2bbabe05b932fa38d1b79497c7043)`(` [`AuctionsUriParameterBuilder`](.github/workflows/documentation/md/AtomicMarketApiClient--Auctions--AuctionsUriParameterBuilder.md#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder)` uriParametersBuilder)` | It returns a list of auctions.
`public ` [`AuctionDto`](.github/workflows/documentation/md/AtomicMarketApiClient--Auctions--AuctionDto.md#class_atomic_market_api_client_1_1_auctions_1_1_auction_dto)` ` [`Auction`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_api_1a75d59e4d934eedd845e155b6d817c20c)`(int id)` | 
`public ` [`LogsDto`](.github/workflows/documentation/md/AtomicMarketApiClient--LogsDto.md#class_atomic_market_api_client_1_1_logs_dto)` ` [`AuctionLogs`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_api_1a178c421fd59a002913bea678297638d1)`(int id)` | 
`public ` [`LogsDto`](.github/workflows/documentation/md/AtomicMarketApiClient--LogsDto.md#class_atomic_market_api_client_1_1_logs_dto)` ` [`AuctionLogs`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_api_1a6f24b011e6579c0d001529b9947dbb0f)`(int id, ` [`AuctionsUriParameterBuilder`](.github/workflows/documentation/md/AtomicMarketApiClient--Auctions--AuctionsUriParameterBuilder.md#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder)` auctionsUriParametersBuilder)` | 
`private readonly string ` [`_requestUriBase`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_api_1a1854c4909a1013a684af16fb52e8a387) | 
`private Uri ` [`AuctionsUri`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_api_1ab42930e70b2df9b11371f9a5cff854e7)`()` | 
`private Uri ` [`AuctionsUri`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_api_1a903e474e53b0416ec3e5a4e2d79ce7be)`(` [`IUriParameterBuilder`](.github/workflows/documentation/md/AtomicMarketApiClient--Core.md#interface_atomic_market_api_client_1_1_core_1_1_i_uri_parameter_builder)` uriParameterBuilder)` | 
`private Uri ` [`AuctionUri`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_api_1ad7b1311a6988538438e4bd558e0a880e)`(int id)` | 
`private Uri ` [`AuctionsLogsUri`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_api_1a85f4050f63ad9b1645e4d1adbadf436e)`(int id)` | 
`private Uri ` [`AuctionsLogsUri`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_api_1a2e4a85fd8c17dec0515efe4bd683fa77)`(int id, ` [`IUriParameterBuilder`](.github/workflows/documentation/md/AtomicMarketApiClient--Core.md#interface_atomic_market_api_client_1_1_core_1_1_i_uri_parameter_builder)` uriParameterBuilder)` | 

## Members

##### `public ` [`AuctionsDto`](.github/workflows/documentation/md/AtomicMarketApiClient--Auctions--AuctionsDto.md#class_atomic_market_api_client_1_1_auctions_1_1_auctions_dto)` ` [`Auctions`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_api_1a70929369a29816434cb7aa9f1fdccf6d)`()` 

<br/>
 It returns a list of auctions.

<return> AuctionsDto </return> <br/>

##### `public ` [`AuctionsDto`](.github/workflows/documentation/md/AtomicMarketApiClient--Auctions--AuctionsDto.md#class_atomic_market_api_client_1_1_auctions_1_1_auctions_dto)` ` [`Auctions`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_api_1aeaf2bbabe05b932fa38d1b79497c7043)`(` [`AuctionsUriParameterBuilder`](.github/workflows/documentation/md/AtomicMarketApiClient--Auctions--AuctionsUriParameterBuilder.md#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder)` uriParametersBuilder)` 

It returns a list of auctions.

#### Parameters
* `AuctionsUriParameterBuilder` This is a class that contains all the parameters that can be passed to the API.

<return> AuctionsDto </return>

##### `public ` [`AuctionDto`](.github/workflows/documentation/md/AtomicMarketApiClient--Auctions--AuctionDto.md#class_atomic_market_api_client_1_1_auctions_1_1_auction_dto)` ` [`Auction`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_api_1a75d59e4d934eedd845e155b6d817c20c)`(int id)` 

##### `public ` [`LogsDto`](.github/workflows/documentation/md/AtomicMarketApiClient--LogsDto.md#class_atomic_market_api_client_1_1_logs_dto)` ` [`AuctionLogs`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_api_1a178c421fd59a002913bea678297638d1)`(int id)` 

##### `public ` [`LogsDto`](.github/workflows/documentation/md/AtomicMarketApiClient--LogsDto.md#class_atomic_market_api_client_1_1_logs_dto)` ` [`AuctionLogs`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_api_1a6f24b011e6579c0d001529b9947dbb0f)`(int id, ` [`AuctionsUriParameterBuilder`](.github/workflows/documentation/md/AtomicMarketApiClient--Auctions--AuctionsUriParameterBuilder.md#class_atomic_market_api_client_1_1_auctions_1_1_auctions_uri_parameter_builder)` auctionsUriParametersBuilder)` 

##### `private readonly string ` [`_requestUriBase`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_api_1a1854c4909a1013a684af16fb52e8a387) 

##### `private Uri ` [`AuctionsUri`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_api_1ab42930e70b2df9b11371f9a5cff854e7)`()` 

##### `private Uri ` [`AuctionsUri`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_api_1a903e474e53b0416ec3e5a4e2d79ce7be)`(` [`IUriParameterBuilder`](.github/workflows/documentation/md/AtomicMarketApiClient--Core.md#interface_atomic_market_api_client_1_1_core_1_1_i_uri_parameter_builder)` uriParameterBuilder)` 

##### `private Uri ` [`AuctionUri`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_api_1ad7b1311a6988538438e4bd558e0a880e)`(int id)` 

##### `private Uri ` [`AuctionsLogsUri`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_api_1a85f4050f63ad9b1645e4d1adbadf436e)`(int id)` 

##### `private Uri ` [`AuctionsLogsUri`](#class_atomic_market_api_client_1_1_auctions_1_1_auctions_api_1a2e4a85fd8c17dec0515efe4bd683fa77)`(int id, ` [`IUriParameterBuilder`](.github/workflows/documentation/md/AtomicMarketApiClient--Core.md#interface_atomic_market_api_client_1_1_core_1_1_i_uri_parameter_builder)` uriParameterBuilder)` 

