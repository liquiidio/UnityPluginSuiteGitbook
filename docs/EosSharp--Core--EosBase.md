# EosBase

Client wrapper to interact with eos blockchains.

## Summary

| Members                                                                                                                                                                                                                                                                                                                                                                               | Descriptions                                                                                |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------- |
| `private` [`EosConfigurator`](EosSharp--Core--EosConfigurator.md) `` [`EosConfig`](EosSharp--Core--EosBase.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_eos\_base\_1a610322e9d2996625cbc5b3ea4b8e8282)                                                                                                                                                                                     |                                                                                             |
| `private` [`EosApi`](EosSharp--Core--Api--v1--EosApi.md) `` [`Api`](EosSharp--Core--EosBase.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_eos\_base\_1a009709c7ea681d63e553e0757b6aad98)                                                                                                                                                                                                    |                                                                                             |
| `private` [`AbiSerializationProvider`](EosSharp--Core--Providers--AbiSerializationProvider.md) `` [`AbiSerializer`](EosSharp--Core--EosBase.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_eos\_base\_1acfb4be3fc5a3b9cf05ada59b13edc24f)                                                                                                                                                    |                                                                                             |
| `public` [`EosBase`](EosSharp--Core--EosBase.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_eos\_base\_1aecc38b4d372a32d1cf559121070ee1f4)`(` [`EosConfigurator`](EosSharp--Core--EosConfigurator.md)`config,` [`IHttpHandler`](EosSharp--Core--Interfaces.md) `httpHandler)`                                                                                                                | Client wrapper constructor.                                                                 |
| `public Task<` [`GetInfoResponse`](EosSharp--Core--Api--v1--GetInfoResponse.md)`>` [`GetInfo`](EosSharp--Core--EosBase.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_eos\_base\_1ab2524ac74c8d04f77b910017c0212990)`()`                                                                                                                                                                     | Query for blockchain information.                                                           |
| `public Task<` [`GetAccountResponse`](EosSharp--Core--Api--v1--GetAccountResponse.md)`>` [`GetAccount`](EosSharp--Core--EosBase.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_eos\_base\_1a36124e5736b861840a4dd2938bf5f316)`(string accountName)`                                                                                                                                          | Query for account information.                                                              |
| `public Task<` [`GetCodeResponse`](EosSharp--Core--Api--v1--GetCodeResponse.md)`>` [`GetCode`](EosSharp--Core--EosBase.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_eos\_base\_1a56a5565474e03177b58c6e5c2fbd3cf0)`(string accountName, bool codeAsWasm)`                                                                                                                                  | Query for smart contract detailed information.                                              |
| `public async Task<` [`Abi`](EosSharp--Core--Api--v1--Abi.md)`>` [`GetAbi`](EosSharp--Core--EosBase.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_eos\_base\_1a69f73da1f3f4f682df4ee5c282003f21)`(string accountName)`                                                                                                                                                                      | Query for smart contract abi detailed information.                                          |
| `public Task<` [`GetRawAbiResponse`](EosSharp--Core--Api--v1--GetRawAbiResponse.md)`>` [`GetRawAbi`](EosSharp--Core--EosBase.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_eos\_base\_1a02785a00fcc7152436e907c8a7a0bcd1)`(string accountName, string abiHash)`                                                                                                                             | Query for smart contract abi detailed information.                                          |
| `public Task<` [`GetRawCodeAndAbiResponse`](EosSharp--Core--Api--v1--GetRawCodeAndAbiResponse.md)`>` [`GetRawCodeAndAbi`](EosSharp--Core--EosBase.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_eos\_base\_1a3122939080875e53197ca4d050ba69ed)`(string accountName)`                                                                                                                        | Query for smart contract raw wasm and abi information.                                      |
| `public async Task< string >` [`AbiJsonToBin`](EosSharp--Core--EosBase.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_eos\_base\_1ac23b22d58818380f9326f31663263ac4)`(string code, string action, object data)`                                                                                                                                                                              | Transform action data to packed binary format.                                              |
| `public async Task< object >` [`AbiBinToJson`](EosSharp--Core--EosBase.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_eos\_base\_1a320437d8b70791ea043f2df7f2c53c03)`(string code, string action, string data)`                                                                                                                                                                              | Transform action data as packed binary format to object.                                    |
| `public async Task< List< string > >` [`GetRequiredKeys`](EosSharp--Core--EosBase.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_eos\_base\_1a165136927ecaf4c3c1e8d533f1ad306d)`(List< string > availableKeys,` [`Transaction`](EosSharp--Core--Api--v1--Transaction.md) `trx)`                                                                                                              | Calculate required keys to sign the given transaction.                                      |
| `public Task<` [`GetBlockResponse`](EosSharp--Core--Api--v1--GetBlockResponse.md)`>` [`GetBlock`](EosSharp--Core--EosBase.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_eos\_base\_1a120c6ca41fc30e7d451888062e6127fb)`(string blockNumOrId)`                                                                                                                                               | Query for blockchain block information.                                                     |
| `public Task<` [`GetBlockHeaderStateResponse`](EosSharp--Core--Api--v1--GetBlockHeaderStateResponse.md)`>` [`GetBlockHeaderState`](EosSharp--Core--EosBase.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_eos\_base\_1ab659874032737dabf3262f1ca2589785)`(string blockNumOrId)`                                                                                                              | Query block head state information.                                                         |
| `public async Task<` [`GetTableRowsResponse`](EosSharp--Core--Api--v1--GetTableRowsResponse.md)`< TRowType > >` [`GetTableRows< TRowType >`](EosSharp--Core--EosBase.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_eos\_base\_1a8e54b848c3d6b9de5531483dc9c7b7b3)`(` [`GetTableRowsRequest`](EosSharp--Core--Api--v1--GetTableRowsRequest.md) `request)`                                    | Query for blockchain smart contract table state information.                                |
| `public async Task<` [`GetTableRowsResponse`](EosSharp--Core--Api--v1--GetTableRowsResponse.md)`>` [`GetTableRows`](EosSharp--Core--EosBase.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_eos\_base\_1ae51f7c49f844a474176bfb25f07a1e30)`(` [`GetTableRowsRequest`](EosSharp--Core--Api--v1--GetTableRowsRequest.md) `request)`                                                             | Query for blockchain smart contract table state information.                                |
| `public async Task< List< string > >` [`GetCurrencyBalance`](EosSharp--Core--EosBase.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_eos\_base\_1a02335810374ecd58e5606cca40049186)`(string code, string account, string symbol)`                                                                                                                                                             | Query account balance for a given token.                                                    |
| `public async Task< Dictionary< string,` [`CurrencyStat`](EosSharp--Core--Api--v1--CurrencyStat.md)`> >` [`GetCurrencyStats`](EosSharp--Core--EosBase.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_eos\_base\_1a62d6b188acf6bbd2713e499ea00f2081)`(string code, string symbol)`                                                                                                            | Query token statistics.                                                                     |
| `public async Task<` [`GetProducersResponse`](EosSharp--Core--Api--v1--GetProducersResponse.md)`>` [`GetProducers`](EosSharp--Core--EosBase.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_eos\_base\_1aced3d6f82fe581da8eb783cf9bf7d267)`(` [`GetProducersRequest`](EosSharp--Core--Api--v1--GetProducersRequest.md) `request)`                                                             | Query producers information.                                                                |
| `public Task<` [`GetProducerScheduleResponse`](EosSharp--Core--Api--v1--GetProducerScheduleResponse.md)`>` [`GetProducerSchedule`](EosSharp--Core--EosBase.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_eos\_base\_1afcccbcb2c4f8c39ce89a081db39e372a)`()`                                                                                                                                 | Query producers schedule.                                                                   |
| `public async Task<` [`GetScheduledTransactionsResponse`](EosSharp--Core--Api--v1--GetScheduledTransactionsResponse.md)`>` [`GetScheduledTransactions`](EosSharp--Core--EosBase.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_eos\_base\_1a5865fc6d9540c5204af687cd6a4878f5)`(` [`GetScheduledTransactionsRequest`](EosSharp--Core--Api--v1--GetScheduledTransactionsRequest.md) `request)` | Query scheduled transactions.                                                               |
| `public async Task< string >` [`CreateTransaction`](EosSharp--Core--EosBase.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_eos\_base\_1acaabbb4670c2779fc9f009e50fdc4ad4)`(` [`Transaction`](EosSharp--Core--Api--v1--Transaction.md) `trx, List< string > requiredKeys)`                                                                                                                    | Creates a signed transaction using the signature provider and broadcasts it to the network. |
| `public async Task<` [`SignedTransaction`](EosSharp--Core--SignedTransaction.md)`>` [`SignTransaction`](EosSharp--Core--EosBase.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_eos\_base\_1acb01e94f7d13631730aa8e1bea115c1a)`(` [`Transaction`](EosSharp--Core--Api--v1--Transaction.md) `trx, List< string > requiredKeys)`                                                                | Creates a signed transaction using the signature provider.                                  |
| `public async Task< string >` [`BroadcastTransaction`](EosSharp--Core--EosBase.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_eos\_base\_1aeb354dd36b81b44501dfd198e5ec6316)`(` [`SignedTransaction`](EosSharp--Core--SignedTransaction.md) `strx)`                                                                                                                                          | Broadcast signed transaction to the network.                                                |
| `public Task<` [`GetActionsResponse`](EosSharp--Core--Api--v1--GetActionsResponse.md)`>` [`GetActions`](EosSharp--Core--EosBase.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_eos\_base\_1aa5ac98fd11b1554d9de72534e5860e31)`(string accountName, Int32 pos, Int32 offset)`                                                                                                                 | Query for account actions log.                                                              |
| `public Task<` [`GetTransactionResponse`](EosSharp--Core--Api--v1--GetTransactionResponse.md)`>` [`GetTransaction`](EosSharp--Core--EosBase.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_eos\_base\_1a719b040ac427c7cacd65ff67f66279f9)`(string transactionId, UInt32? blockNumberHint)`                                                                                                   | Query transaction information.                                                              |
| `public async Task< List< string > >` [`GetKeyAccounts`](EosSharp--Core--EosBase.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_eos\_base\_1a299509fb41993013eb49c38341e3cebc)`(string publicKey)`                                                                                                                                                                                           | Query public key accounts.                                                                  |
| `public async Task< List< string > >` [`GetControlledAccounts`](EosSharp--Core--EosBase.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_eos\_base\_1a8174c1396340fe8f56749fd0e1a67284)`(string accountName)`                                                                                                                                                                                  | Query controlled accounts by a given account.                                               |

## Members

**`private`** [**`EosConfigurator`**](EosSharp--Core--EosConfigurator.md) **``** [**`EosConfig`**](EosSharp--Core--EosBase.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_eos\_base\_1a610322e9d2996625cbc5b3ea4b8e8282)

**`private`** [**`EosApi`**](EosSharp--Core--Api--v1--EosApi.md) **``** [**`Api`**](EosSharp--Core--EosBase.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_eos\_base\_1a009709c7ea681d63e553e0757b6aad98)

**`private`** [**`AbiSerializationProvider`**](EosSharp--Core--Providers--AbiSerializationProvider.md) **``** [**`AbiSerializer`**](EosSharp--Core--EosBase.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_eos\_base\_1acfb4be3fc5a3b9cf05ada59b13edc24f)

**`public`** [**`EosBase`**](EosSharp--Core--EosBase.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_eos\_base\_1aecc38b4d372a32d1cf559121070ee1f4)**`(` ** [**`EosConfigurator`**](EosSharp--Core--EosConfigurator.md)**`config,` ** [**`IHttpHandler`**](EosSharp--Core--Interfaces.md) **`httpHandler)`**

Client wrapper constructor.

#### Parameters

* `config` Configures client parameters
* `httpHandler` Http handler implementation

**`public Task<`** [**`GetInfoResponse`**](EosSharp--Core--Api--v1--GetInfoResponse.md)**`>` ** [**`GetInfo`**](EosSharp--Core--EosBase.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_eos\_base\_1ab2524ac74c8d04f77b910017c0212990)**`()`**

Query for blockchain information.

#### Returns

Blockchain information

**`public Task<`** [**`GetAccountResponse`**](EosSharp--Core--Api--v1--GetAccountResponse.md)**`>` ** [**`GetAccount`**](EosSharp--Core--EosBase.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_eos\_base\_1a36124e5736b861840a4dd2938bf5f316)**`(string accountName)`**

Query for account information.

#### Parameters

* `accountName` account to query information

#### Returns

account information

**`public Task<`** [**`GetCodeResponse`**](EosSharp--Core--Api--v1--GetCodeResponse.md)**`>` ** [**`GetCode`**](EosSharp--Core--EosBase.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_eos\_base\_1a56a5565474e03177b58c6e5c2fbd3cf0)**`(string accountName, bool codeAsWasm)`**

Query for smart contract detailed information.

#### Parameters

* `accountName` smart contract account name
* `codeAsWasm` query code as wasm, wast otherwise

#### Returns

smart contract information

**`public async Task<`** [**`Abi`**](EosSharp--Core--Api--v1--Abi.md)**`>` ** [**`GetAbi`**](EosSharp--Core--EosBase.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_eos\_base\_1a69f73da1f3f4f682df4ee5c282003f21)**`(string accountName)`**

Query for smart contract abi detailed information.

#### Parameters

* `accountName` smart contract account name

#### Returns

**`public Task<`** [**`GetRawAbiResponse`**](EosSharp--Core--Api--v1--GetRawAbiResponse.md)**`>` ** [**`GetRawAbi`**](EosSharp--Core--EosBase.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_eos\_base\_1a02785a00fcc7152436e907c8a7a0bcd1)**`(string accountName, string abiHash)`**

Query for smart contract abi detailed information.

#### Parameters

* `accountName` smart contract account name
* `abiHash` TODO

#### Returns

smart contract abi information as Base64FcString

**`public Task<`** [**`GetRawCodeAndAbiResponse`**](EosSharp--Core--Api--v1--GetRawCodeAndAbiResponse.md)**`>` ** [**`GetRawCodeAndAbi`**](EosSharp--Core--EosBase.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_eos\_base\_1a3122939080875e53197ca4d050ba69ed)**`(string accountName)`**

Query for smart contract raw wasm and abi information.

#### Parameters

* `accountName` smart contract account name

#### Returns

smart contract wasm and abi information

**`public async Task< string >`** [**`AbiJsonToBin`**](EosSharp--Core--EosBase.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_eos\_base\_1ac23b22d58818380f9326f31663263ac4)**`(string code, string action, object data)`**

Transform action data to packed binary format.

#### Parameters

* `code` smart contract account name
* `action` action name
* `data` action

#### Returns

**`public async Task< object >`** [**`AbiBinToJson`**](EosSharp--Core--EosBase.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_eos\_base\_1a320437d8b70791ea043f2df7f2c53c03)**`(string code, string action, string data)`**

Transform action data as packed binary format to object.

#### Parameters

* `code`
* `action`
* `data`

#### Returns

**`public async Task< List< string > >`** [**`GetRequiredKeys`**](EosSharp--Core--EosBase.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_eos\_base\_1a165136927ecaf4c3c1e8d533f1ad306d)**`(List< string > availableKeys,`** [**`Transaction`**](EosSharp--Core--Api--v1--Transaction.md) **`trx)`**

Calculate required keys to sign the given transaction.

#### Parameters

* `availableKeys` available public keys list
* `trx` transaction requiring signatures

#### Returns

required public keys

**`public Task<`** [**`GetBlockResponse`**](EosSharp--Core--Api--v1--GetBlockResponse.md)**`>` ** [**`GetBlock`**](EosSharp--Core--EosBase.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_eos\_base\_1a120c6ca41fc30e7d451888062e6127fb)**`(string blockNumOrId)`**

Query for blockchain block information.

#### Parameters

* `blockNumOrId` block number or id to query information

#### Returns

block information

**`public Task<`** [**`GetBlockHeaderStateResponse`**](EosSharp--Core--Api--v1--GetBlockHeaderStateResponse.md)**`>` ** [**`GetBlockHeaderState`**](EosSharp--Core--EosBase.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_eos\_base\_1ab659874032737dabf3262f1ca2589785)**`(string blockNumOrId)`**

Query block head state information.

#### Parameters

* `blockNumOrId` block number or id

#### Returns

TODO

**`public async Task<`** [**`GetTableRowsResponse`**](EosSharp--Core--Api--v1--GetTableRowsResponse.md)**`< TRowType > >`** [**`GetTableRows< TRowType >`**](EosSharp--Core--EosBase.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_eos\_base\_1a8e54b848c3d6b9de5531483dc9c7b7b3)**`(` ** [**`GetTableRowsRequest`**](EosSharp--Core--Api--v1--GetTableRowsRequest.md) **`request)`**

Query for blockchain smart contract table state information.

#### Parameters

* `TRowType` Type used for each row

#### Parameters

* `request.Json` Request rows using json or raw format
* `request.Code` accountName of the contract to search for table rows
* `request.Scope` scope text segmenting the table set
* `request.Table` table name
* `request.TableKey` unused so far?
* `request.LowerBound` lower bound for the selected index value
* `request.UpperBound` upper bound for the selected index value
* `request.KeyType` Type of the index choosen, ex: i64
* `request.IndexPosition` 1 - primary(first), 2 - secondary index(in order defined by multi\_index), 3 - third index, etc

#### Returns

Rows and if is there More rows to be fetched

**`public async Task<`** [**`GetTableRowsResponse`**](EosSharp--Core--Api--v1--GetTableRowsResponse.md)**`>` ** [**`GetTableRows`**](EosSharp--Core--EosBase.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_eos\_base\_1ae51f7c49f844a474176bfb25f07a1e30)**`(` ** [**`GetTableRowsRequest`**](EosSharp--Core--Api--v1--GetTableRowsRequest.md) **`request)`**

Query for blockchain smart contract table state information.

#### Parameters

* `request.Json` Request rows using json or raw format
* `request.Code` accountName of the contract to search for table rows
* `request.Scope` scope text segmenting the table set
* `request.Table` table name
* `request.TableKey` unused so far?
* `request.LowerBound` lower bound for the selected index value
* `request.UpperBound` upper bound for the selected index value
* `request.KeyType` Type of the index choosen, ex: i64
* `request.IndexPosition` 1 - primary(first), 2 - secondary index(in order defined by multi\_index), 3 - third index, etc

#### Returns

Rows and if is there More rows to be fetched

**`public async Task< List< string > >`** [**`GetCurrencyBalance`**](EosSharp--Core--EosBase.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_eos\_base\_1a02335810374ecd58e5606cca40049186)**`(string code, string account, string symbol)`**

Query account balance for a given token.

#### Parameters

* `code` token smart contract account
* `account` account name to check
* `symbol` token symbol (optional)

#### Returns

token balances

**`public async Task< Dictionary< string,`** [**`CurrencyStat`**](EosSharp--Core--Api--v1--CurrencyStat.md)**`> >` ** [**`GetCurrencyStats`**](EosSharp--Core--EosBase.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_eos\_base\_1a62d6b188acf6bbd2713e499ea00f2081)**`(string code, string symbol)`**

Query token statistics.

#### Parameters

* `code` token smart contract account
* `symbol` token symbol (optional)

#### Returns

currencies statistics

**`public async Task<`** [**`GetProducersResponse`**](EosSharp--Core--Api--v1--GetProducersResponse.md)**`>` ** [**`GetProducers`**](EosSharp--Core--EosBase.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_eos\_base\_1aced3d6f82fe581da8eb783cf9bf7d267)**`(` ** [**`GetProducersRequest`**](EosSharp--Core--Api--v1--GetProducersRequest.md) **`request)`**

Query producers information.

#### Parameters

* `request.json` get list as json
* `request.lower_bound` lower bound for the selected index value
* `request.limit` limit the amount of results. Default 50

#### Returns

producers information

**`public Task<`** [**`GetProducerScheduleResponse`**](EosSharp--Core--Api--v1--GetProducerScheduleResponse.md)**`>` ** [**`GetProducerSchedule`**](EosSharp--Core--EosBase.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_eos\_base\_1afcccbcb2c4f8c39ce89a081db39e372a)**`()`**

Query producers schedule.

#### Returns

Active, pending and proposed schedule

**`public async Task<`** [**`GetScheduledTransactionsResponse`**](EosSharp--Core--Api--v1--GetScheduledTransactionsResponse.md)**`>` ** [**`GetScheduledTransactions`**](EosSharp--Core--EosBase.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_eos\_base\_1a5865fc6d9540c5204af687cd6a4878f5)**`(` ** [**`GetScheduledTransactionsRequest`**](EosSharp--Core--Api--v1--GetScheduledTransactionsRequest.md) **`request)`**

Query scheduled transactions.

#### Parameters

* `request.json` get list as json
* `request.lower_bound` lower bound for the selected index value
* `request.limit` limit the amount of results. Default 50

#### Returns

Scheduled transactions

**`public async Task< string >`** [**`CreateTransaction`**](EosSharp--Core--EosBase.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_eos\_base\_1acaabbb4670c2779fc9f009e50fdc4ad4)**`(` ** [**`Transaction`**](EosSharp--Core--Api--v1--Transaction.md) **`trx, List< string > requiredKeys)`**

Creates a signed transaction using the signature provider and broadcasts it to the network.

#### Parameters

* `trx` Transaction to send
* `requiredKeys` Override required keys to sign transaction

#### Returns

transaction id

**`public async Task<`** [**`SignedTransaction`**](EosSharp--Core--SignedTransaction.md)**`>` ** [**`SignTransaction`**](EosSharp--Core--EosBase.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_eos\_base\_1acb01e94f7d13631730aa8e1bea115c1a)**`(` ** [**`Transaction`**](EosSharp--Core--Api--v1--Transaction.md) **`trx, List< string > requiredKeys)`**

Creates a signed transaction using the signature provider.

#### Parameters

* `trx` Transaction to sign
* `requiredKeys` Override required keys to sign transaction

#### Returns

transaction id

**`public async Task< string >`** [**`BroadcastTransaction`**](EosSharp--Core--EosBase.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_eos\_base\_1aeb354dd36b81b44501dfd198e5ec6316)**`(` ** [**`SignedTransaction`**](EosSharp--Core--SignedTransaction.md) **`strx)`**

Broadcast signed transaction to the network.

#### Parameters

* `strx` Signed transaction to send

#### Returns

**`public Task<`** [**`GetActionsResponse`**](EosSharp--Core--Api--v1--GetActionsResponse.md)**`>` ** [**`GetActions`**](EosSharp--Core--EosBase.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_eos\_base\_1aa5ac98fd11b1554d9de72534e5860e31)**`(string accountName, Int32 pos, Int32 offset)`**

Query for account actions log.

#### Parameters

* `accountName` account to query information
* `pos` Absolute sequence positon -1 is the end/last action
* `offset` Number of actions relative to pos, negative numbers return \[pos-offset,pos), positive numbers return \[pos,pos+offset)

#### Returns

**`public Task<`** [**`GetTransactionResponse`**](EosSharp--Core--Api--v1--GetTransactionResponse.md)**`>` ** [**`GetTransaction`**](EosSharp--Core--EosBase.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_eos\_base\_1a719b040ac427c7cacd65ff67f66279f9)**`(string transactionId, UInt32? blockNumberHint)`**

Query transaction information.

#### Parameters

* `transactionId` transaction id

#### Returns

Transaction information

**`public async Task< List< string > >`** [**`GetKeyAccounts`**](EosSharp--Core--EosBase.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_eos\_base\_1a299509fb41993013eb49c38341e3cebc)**`(string publicKey)`**

Query public key accounts.

#### Parameters

* `publicKey` public key

#### Returns

account names

**`public async Task< List< string > >`** [**`GetControlledAccounts`**](EosSharp--Core--EosBase.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_eos\_base\_1a8174c1396340fe8f56749fd0e1a67284)**`(string accountName)`**

Query controlled accounts by a given account.

#### Parameters

* `accountName` account name to search

#### Returns

controlled account names
