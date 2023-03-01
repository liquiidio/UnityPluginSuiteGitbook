# class `EosSharp::Core::Api::v1::EosApi` 

EosApi defines api methods to interface with a http handler.

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public ` [`EosConfigurator`](EosSharp--Core--EosConfigurator.md)` ` [`Config`](#class_eos_sharp_1_1_core_1_1_api_1_1v1_1_1_eos_api_1a73d93752ba0913bd0ba08fa38f22e139) | 
`public ` [`IHttpHandler`](EosSharp--Core--Interfaces.md)` ` [`HttpHandler`](#class_eos_sharp_1_1_core_1_1_api_1_1v1_1_1_eos_api_1a0537f3a2de8d9e5c8f63b26097166035) | 
`public ` [`EosApi`](#class_eos_sharp_1_1_core_1_1_api_1_1v1_1_1_eos_api_1a7f5d4f11154b164d0da01b00caa5f0de)`(` [`EosConfigurator`](EosSharp--Core--EosConfigurator.md)` config, ` [`IHttpHandler`](EosSharp--Core--Interfaces.md)` httpHandler)` | Eos Client api constructor.
`public async Task< ` [`GetInfoResponse`](EosSharp--Core--Api--v1--GetInfoResponse.md)` > ` [`GetInfo`](#class_eos_sharp_1_1_core_1_1_api_1_1v1_1_1_eos_api_1af0e21395e7b1c2f61935db977797d35b)`()` | 
`public async Task< ` [`GetAccountResponse`](EosSharp--Core--Api--v1--GetAccountResponse.md)` > ` [`GetAccount`](#class_eos_sharp_1_1_core_1_1_api_1_1v1_1_1_eos_api_1acd3fdcea1a7daabdc1ed6b45f9f97dbc)`(` [`GetAccountRequest`](EosSharp--Core--Api--v1--GetAccountRequest.md)` data)` | 
`public async Task< ` [`GetCodeResponse`](EosSharp--Core--Api--v1--GetCodeResponse.md)` > ` [`GetCode`](#class_eos_sharp_1_1_core_1_1_api_1_1v1_1_1_eos_api_1af74a8aac1fcce920e55fbcbf45710d7c)`(` [`GetCodeRequest`](EosSharp--Core--Api--v1--GetCodeRequest.md)` data, bool reload)` | 
`public async Task< ` [`GetAbiResponse`](EosSharp--Core--Api--v1--GetAbiResponse.md)` > ` [`GetAbi`](#class_eos_sharp_1_1_core_1_1_api_1_1v1_1_1_eos_api_1a3f33976b9bfae847e4beaca65aa9e0af)`(` [`GetAbiRequest`](EosSharp--Core--Api--v1--GetAbiRequest.md)` data, bool reload)` | 
`public async Task< ` [`GetRawCodeAndAbiResponse`](EosSharp--Core--Api--v1--GetRawCodeAndAbiResponse.md)` > ` [`GetRawCodeAndAbi`](#class_eos_sharp_1_1_core_1_1_api_1_1v1_1_1_eos_api_1a5807323e21428631a3cbb6aa339b9804)`(` [`GetRawCodeAndAbiRequest`](EosSharp--Core--Api--v1--GetRawCodeAndAbiRequest.md)` data, bool reload)` | 
`public async Task< ` [`GetRawAbiResponse`](EosSharp--Core--Api--v1--GetRawAbiResponse.md)` > ` [`GetRawAbi`](#class_eos_sharp_1_1_core_1_1_api_1_1v1_1_1_eos_api_1ad4fb20685de828ba81139a45aaa53d33)`(` [`GetRawAbiRequest`](EosSharp--Core--Api--v1--GetRawAbiRequest.md)` data, bool reload)` | 
`public async Task< ` [`AbiJsonToBinResponse`](EosSharp--Core--Api--v1--AbiJsonToBinResponse.md)` > ` [`AbiJsonToBin`](#class_eos_sharp_1_1_core_1_1_api_1_1v1_1_1_eos_api_1ab92d3b1a8603ba482f1f8ea60f7b4688)`(` [`AbiJsonToBinRequest`](EosSharp--Core--Api--v1--AbiJsonToBinRequest.md)` data)` | 
`public async Task< ` [`AbiBinToJsonResponse`](EosSharp--Core--Api--v1--AbiBinToJsonResponse.md)` > ` [`AbiBinToJson`](#class_eos_sharp_1_1_core_1_1_api_1_1v1_1_1_eos_api_1ad4308519bfb2c301cc82e1b212089568)`(` [`AbiBinToJsonRequest`](EosSharp--Core--Api--v1--AbiBinToJsonRequest.md)` data)` | 
`public async Task< ` [`GetRequiredKeysResponse`](EosSharp--Core--Api--v1--GetRequiredKeysResponse.md)` > ` [`GetRequiredKeys`](#class_eos_sharp_1_1_core_1_1_api_1_1v1_1_1_eos_api_1a11dc3338074c0bd2ca5b88fef4565c93)`(` [`GetRequiredKeysRequest`](EosSharp--Core--Api--v1--GetRequiredKeysRequest.md)` data)` | 
`public async Task< ` [`GetBlockResponse`](EosSharp--Core--Api--v1--GetBlockResponse.md)` > ` [`GetBlock`](#class_eos_sharp_1_1_core_1_1_api_1_1v1_1_1_eos_api_1a7eff7bcaac3ac227b0314307aec3778d)`(` [`GetBlockRequest`](EosSharp--Core--Api--v1--GetBlockRequest.md)` data)` | 
`public async Task< ` [`GetBlockInfoResponse`](EosSharp--Core--Api--v1--GetBlockInfoResponse.md)` > ` [`GetBlockInfo`](#class_eos_sharp_1_1_core_1_1_api_1_1v1_1_1_eos_api_1addf198ad0a7ae88ed0f117899448b589)`(` [`GetBlockInfoRequest`](EosSharp--Core--Api--v1--GetBlockInfoRequest.md)` data)` | 
`public async Task< ` [`GetBlockHeaderStateResponse`](EosSharp--Core--Api--v1--GetBlockHeaderStateResponse.md)` > ` [`GetBlockHeaderState`](#class_eos_sharp_1_1_core_1_1_api_1_1v1_1_1_eos_api_1a109ec89808dfbb56819597f203763883)`(` [`GetBlockHeaderStateRequest`](EosSharp--Core--Api--v1--GetBlockHeaderStateRequest.md)` data)` | 
`public async Task< ` [`GetTableRowsResponse`](EosSharp--Core--Api--v1--GetTableRowsResponse.md)`< TRowType > > ` [`GetTableRows< TRowType >`](#class_eos_sharp_1_1_core_1_1_api_1_1v1_1_1_eos_api_1ac3731451ee399d489c2df016144d4a20)`(` [`GetTableRowsRequest`](EosSharp--Core--Api--v1--GetTableRowsRequest.md)` data)` | 
`public async Task< ` [`GetTableRowsResponse`](EosSharp--Core--Api--v1--GetTableRowsResponse.md)` > ` [`GetTableRows`](#class_eos_sharp_1_1_core_1_1_api_1_1v1_1_1_eos_api_1a158d36598f3a45b50c45a63b8bd9dc8f)`(` [`GetTableRowsRequest`](EosSharp--Core--Api--v1--GetTableRowsRequest.md)` data)` | 
`public async Task< ` [`GetTableByScopeResponse`](EosSharp--Core--Api--v1--GetTableByScopeResponse.md)` > ` [`GetTableByScope`](#class_eos_sharp_1_1_core_1_1_api_1_1v1_1_1_eos_api_1ab756a6a61e5aa4db17ea205ce3585544)`(` [`GetTableByScopeRequest`](EosSharp--Core--Api--v1--GetTableByScopeRequest.md)` data)` | 
`public async Task< ` [`GetCurrencyBalanceResponse`](EosSharp--Core--Api--v1--GetCurrencyBalanceResponse.md)` > ` [`GetCurrencyBalance`](#class_eos_sharp_1_1_core_1_1_api_1_1v1_1_1_eos_api_1ab7f2ca7c74ae3e8c8bfeeed85f06c615)`(` [`GetCurrencyBalanceRequest`](EosSharp--Core--Api--v1--GetCurrencyBalanceRequest.md)` data)` | 
`public async Task< ` [`GetCurrencyStatsResponse`](EosSharp--Core--Api--v1--GetCurrencyStatsResponse.md)` > ` [`GetCurrencyStats`](#class_eos_sharp_1_1_core_1_1_api_1_1v1_1_1_eos_api_1acb566d816620cc69afd9675b504419d8)`(` [`GetCurrencyStatsRequest`](EosSharp--Core--Api--v1--GetCurrencyStatsRequest.md)` data)` | 
`public async Task< ` [`GetProducersResponse`](EosSharp--Core--Api--v1--GetProducersResponse.md)` > ` [`GetProducers`](#class_eos_sharp_1_1_core_1_1_api_1_1v1_1_1_eos_api_1aea74888d90d7124d259c47341b0eb633)`(` [`GetProducersRequest`](EosSharp--Core--Api--v1--GetProducersRequest.md)` data)` | 
`public async Task< ` [`GetProducerScheduleResponse`](EosSharp--Core--Api--v1--GetProducerScheduleResponse.md)` > ` [`GetProducerSchedule`](#class_eos_sharp_1_1_core_1_1_api_1_1v1_1_1_eos_api_1a8c3b1a90414ddc0353b64ac7ee28bf71)`()` | 
`public async Task< ` [`GetScheduledTransactionsResponse`](EosSharp--Core--Api--v1--GetScheduledTransactionsResponse.md)` > ` [`GetScheduledTransactions`](#class_eos_sharp_1_1_core_1_1_api_1_1v1_1_1_eos_api_1aaac2e504289862995eec77850379d27a)`(` [`GetScheduledTransactionsRequest`](EosSharp--Core--Api--v1--GetScheduledTransactionsRequest.md)` data)` | 
`public async Task< ` [`PushTransactionResponse`](EosSharp--Core--Api--v1--PushTransactionResponse.md)` > ` [`PushTransaction`](#class_eos_sharp_1_1_core_1_1_api_1_1v1_1_1_eos_api_1a8856275b3ab41729f67dc981c1893b73)`(` [`PushTransactionRequest`](EosSharp--Core--Api--v1--PushTransactionRequest.md)` data)` | 
`public async Task< ` [`GetActivatedProtocolFeaturesResponse`](EosSharp--Core--Api--v1--GetActivatedProtocolFeaturesResponse.md)` > ` [`GetActivatedProtocolFeatures`](#class_eos_sharp_1_1_core_1_1_api_1_1v1_1_1_eos_api_1abc40225ad6d76fd6d296675cc70f726d)`(` [`GetActivatedProtocolFeaturesRequest`](EosSharp--Core--Api--v1--GetActivatedProtocolFeaturesRequest.md)` data)` | 
`public async Task< ` [`GetAccountsByAuthorizersResponse`](EosSharp--Core--Api--v1--GetAccountsByAuthorizersResponse.md)` > ` [`GetAccountsByAuthorizers`](#class_eos_sharp_1_1_core_1_1_api_1_1v1_1_1_eos_api_1a0e74084cbe432a3d0c2117b91a106809)`(` [`GetAccountsByAuthorizersRequest`](EosSharp--Core--Api--v1--GetAccountsByAuthorizersRequest.md)` data)` | 

## Members

##### `public ` [`EosConfigurator`](EosSharp--Core--EosConfigurator.md)` ` [`Config`](#class_eos_sharp_1_1_core_1_1_api_1_1v1_1_1_eos_api_1a73d93752ba0913bd0ba08fa38f22e139) 

##### `public ` [`IHttpHandler`](EosSharp--Core--Interfaces.md)` ` [`HttpHandler`](#class_eos_sharp_1_1_core_1_1_api_1_1v1_1_1_eos_api_1a0537f3a2de8d9e5c8f63b26097166035) 

##### `public ` [`EosApi`](#class_eos_sharp_1_1_core_1_1_api_1_1v1_1_1_eos_api_1a7f5d4f11154b164d0da01b00caa5f0de)`(` [`EosConfigurator`](EosSharp--Core--EosConfigurator.md)` config, ` [`IHttpHandler`](EosSharp--Core--Interfaces.md)` httpHandler)` 

Eos Client api constructor.

#### Parameters
* `config` Configures client parameters

* `httpHandler` Http handler implementation

##### `public async Task< ` [`GetInfoResponse`](EosSharp--Core--Api--v1--GetInfoResponse.md)` > ` [`GetInfo`](#class_eos_sharp_1_1_core_1_1_api_1_1v1_1_1_eos_api_1af0e21395e7b1c2f61935db977797d35b)`()` 

##### `public async Task< ` [`GetAccountResponse`](EosSharp--Core--Api--v1--GetAccountResponse.md)` > ` [`GetAccount`](#class_eos_sharp_1_1_core_1_1_api_1_1v1_1_1_eos_api_1acd3fdcea1a7daabdc1ed6b45f9f97dbc)`(` [`GetAccountRequest`](EosSharp--Core--Api--v1--GetAccountRequest.md)` data)` 

##### `public async Task< ` [`GetCodeResponse`](EosSharp--Core--Api--v1--GetCodeResponse.md)` > ` [`GetCode`](#class_eos_sharp_1_1_core_1_1_api_1_1v1_1_1_eos_api_1af74a8aac1fcce920e55fbcbf45710d7c)`(` [`GetCodeRequest`](EosSharp--Core--Api--v1--GetCodeRequest.md)` data, bool reload)` 

##### `public async Task< ` [`GetAbiResponse`](EosSharp--Core--Api--v1--GetAbiResponse.md)` > ` [`GetAbi`](#class_eos_sharp_1_1_core_1_1_api_1_1v1_1_1_eos_api_1a3f33976b9bfae847e4beaca65aa9e0af)`(` [`GetAbiRequest`](EosSharp--Core--Api--v1--GetAbiRequest.md)` data, bool reload)` 

##### `public async Task< ` [`GetRawCodeAndAbiResponse`](EosSharp--Core--Api--v1--GetRawCodeAndAbiResponse.md)` > ` [`GetRawCodeAndAbi`](#class_eos_sharp_1_1_core_1_1_api_1_1v1_1_1_eos_api_1a5807323e21428631a3cbb6aa339b9804)`(` [`GetRawCodeAndAbiRequest`](EosSharp--Core--Api--v1--GetRawCodeAndAbiRequest.md)` data, bool reload)` 

##### `public async Task< ` [`GetRawAbiResponse`](EosSharp--Core--Api--v1--GetRawAbiResponse.md)` > ` [`GetRawAbi`](#class_eos_sharp_1_1_core_1_1_api_1_1v1_1_1_eos_api_1ad4fb20685de828ba81139a45aaa53d33)`(` [`GetRawAbiRequest`](EosSharp--Core--Api--v1--GetRawAbiRequest.md)` data, bool reload)` 

##### `public async Task< ` [`AbiJsonToBinResponse`](EosSharp--Core--Api--v1--AbiJsonToBinResponse.md)` > ` [`AbiJsonToBin`](#class_eos_sharp_1_1_core_1_1_api_1_1v1_1_1_eos_api_1ab92d3b1a8603ba482f1f8ea60f7b4688)`(` [`AbiJsonToBinRequest`](EosSharp--Core--Api--v1--AbiJsonToBinRequest.md)` data)` 

##### `public async Task< ` [`AbiBinToJsonResponse`](EosSharp--Core--Api--v1--AbiBinToJsonResponse.md)` > ` [`AbiBinToJson`](#class_eos_sharp_1_1_core_1_1_api_1_1v1_1_1_eos_api_1ad4308519bfb2c301cc82e1b212089568)`(` [`AbiBinToJsonRequest`](EosSharp--Core--Api--v1--AbiBinToJsonRequest.md)` data)` 

##### `public async Task< ` [`GetRequiredKeysResponse`](EosSharp--Core--Api--v1--GetRequiredKeysResponse.md)` > ` [`GetRequiredKeys`](#class_eos_sharp_1_1_core_1_1_api_1_1v1_1_1_eos_api_1a11dc3338074c0bd2ca5b88fef4565c93)`(` [`GetRequiredKeysRequest`](EosSharp--Core--Api--v1--GetRequiredKeysRequest.md)` data)` 

##### `public async Task< ` [`GetBlockResponse`](EosSharp--Core--Api--v1--GetBlockResponse.md)` > ` [`GetBlock`](#class_eos_sharp_1_1_core_1_1_api_1_1v1_1_1_eos_api_1a7eff7bcaac3ac227b0314307aec3778d)`(` [`GetBlockRequest`](EosSharp--Core--Api--v1--GetBlockRequest.md)` data)` 

##### `public async Task< ` [`GetBlockInfoResponse`](EosSharp--Core--Api--v1--GetBlockInfoResponse.md)` > ` [`GetBlockInfo`](#class_eos_sharp_1_1_core_1_1_api_1_1v1_1_1_eos_api_1addf198ad0a7ae88ed0f117899448b589)`(` [`GetBlockInfoRequest`](EosSharp--Core--Api--v1--GetBlockInfoRequest.md)` data)` 

##### `public async Task< ` [`GetBlockHeaderStateResponse`](EosSharp--Core--Api--v1--GetBlockHeaderStateResponse.md)` > ` [`GetBlockHeaderState`](#class_eos_sharp_1_1_core_1_1_api_1_1v1_1_1_eos_api_1a109ec89808dfbb56819597f203763883)`(` [`GetBlockHeaderStateRequest`](EosSharp--Core--Api--v1--GetBlockHeaderStateRequest.md)` data)` 

##### `public async Task< ` [`GetTableRowsResponse`](EosSharp--Core--Api--v1--GetTableRowsResponse.md)`< TRowType > > ` [`GetTableRows< TRowType >`](#class_eos_sharp_1_1_core_1_1_api_1_1v1_1_1_eos_api_1ac3731451ee399d489c2df016144d4a20)`(` [`GetTableRowsRequest`](EosSharp--Core--Api--v1--GetTableRowsRequest.md)` data)` 

##### `public async Task< ` [`GetTableRowsResponse`](EosSharp--Core--Api--v1--GetTableRowsResponse.md)` > ` [`GetTableRows`](#class_eos_sharp_1_1_core_1_1_api_1_1v1_1_1_eos_api_1a158d36598f3a45b50c45a63b8bd9dc8f)`(` [`GetTableRowsRequest`](EosSharp--Core--Api--v1--GetTableRowsRequest.md)` data)` 

##### `public async Task< ` [`GetTableByScopeResponse`](EosSharp--Core--Api--v1--GetTableByScopeResponse.md)` > ` [`GetTableByScope`](#class_eos_sharp_1_1_core_1_1_api_1_1v1_1_1_eos_api_1ab756a6a61e5aa4db17ea205ce3585544)`(` [`GetTableByScopeRequest`](EosSharp--Core--Api--v1--GetTableByScopeRequest.md)` data)` 

##### `public async Task< ` [`GetCurrencyBalanceResponse`](EosSharp--Core--Api--v1--GetCurrencyBalanceResponse.md)` > ` [`GetCurrencyBalance`](#class_eos_sharp_1_1_core_1_1_api_1_1v1_1_1_eos_api_1ab7f2ca7c74ae3e8c8bfeeed85f06c615)`(` [`GetCurrencyBalanceRequest`](EosSharp--Core--Api--v1--GetCurrencyBalanceRequest.md)` data)` 

##### `public async Task< ` [`GetCurrencyStatsResponse`](EosSharp--Core--Api--v1--GetCurrencyStatsResponse.md)` > ` [`GetCurrencyStats`](#class_eos_sharp_1_1_core_1_1_api_1_1v1_1_1_eos_api_1acb566d816620cc69afd9675b504419d8)`(` [`GetCurrencyStatsRequest`](EosSharp--Core--Api--v1--GetCurrencyStatsRequest.md)` data)` 

##### `public async Task< ` [`GetProducersResponse`](EosSharp--Core--Api--v1--GetProducersResponse.md)` > ` [`GetProducers`](#class_eos_sharp_1_1_core_1_1_api_1_1v1_1_1_eos_api_1aea74888d90d7124d259c47341b0eb633)`(` [`GetProducersRequest`](EosSharp--Core--Api--v1--GetProducersRequest.md)` data)` 

##### `public async Task< ` [`GetProducerScheduleResponse`](EosSharp--Core--Api--v1--GetProducerScheduleResponse.md)` > ` [`GetProducerSchedule`](#class_eos_sharp_1_1_core_1_1_api_1_1v1_1_1_eos_api_1a8c3b1a90414ddc0353b64ac7ee28bf71)`()` 

##### `public async Task< ` [`GetScheduledTransactionsResponse`](EosSharp--Core--Api--v1--GetScheduledTransactionsResponse.md)` > ` [`GetScheduledTransactions`](#class_eos_sharp_1_1_core_1_1_api_1_1v1_1_1_eos_api_1aaac2e504289862995eec77850379d27a)`(` [`GetScheduledTransactionsRequest`](EosSharp--Core--Api--v1--GetScheduledTransactionsRequest.md)` data)` 

##### `public async Task< ` [`PushTransactionResponse`](EosSharp--Core--Api--v1--PushTransactionResponse.md)` > ` [`PushTransaction`](#class_eos_sharp_1_1_core_1_1_api_1_1v1_1_1_eos_api_1a8856275b3ab41729f67dc981c1893b73)`(` [`PushTransactionRequest`](EosSharp--Core--Api--v1--PushTransactionRequest.md)` data)` 

##### `public async Task< ` [`GetActivatedProtocolFeaturesResponse`](EosSharp--Core--Api--v1--GetActivatedProtocolFeaturesResponse.md)` > ` [`GetActivatedProtocolFeatures`](#class_eos_sharp_1_1_core_1_1_api_1_1v1_1_1_eos_api_1abc40225ad6d76fd6d296675cc70f726d)`(` [`GetActivatedProtocolFeaturesRequest`](EosSharp--Core--Api--v1--GetActivatedProtocolFeaturesRequest.md)` data)` 

##### `public async Task< ` [`GetAccountsByAuthorizersResponse`](EosSharp--Core--Api--v1--GetAccountsByAuthorizersResponse.md)` > ` [`GetAccountsByAuthorizers`](#class_eos_sharp_1_1_core_1_1_api_1_1v1_1_1_eos_api_1a0e74084cbe432a3d0c2117b91a106809)`(` [`GetAccountsByAuthorizersRequest`](EosSharp--Core--Api--v1--GetAccountsByAuthorizersRequest.md)` data)` 

