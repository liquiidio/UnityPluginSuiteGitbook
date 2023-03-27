# IAbiSerializationProvider

## Summary

| Members                                                                                                                                                                                                                       | Descriptions |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ |
| `public` [`EosApi`](EosSharp--Core--Api--v1--EosApi.md) `` [`Api`](EosSharp--Core--Providers.md)                                                                                                                              |              |
| `public Task<` [`Abi`](EosSharp--Core--Api--v1--Abi.md)`>` [`GetAbi`](EosSharp--Core--Providers.md)`(string account)`                                                                                                         |              |
| `public T` [`Deserialize< T >`](EosSharp--Core--Providers.md)`(byte[] rawVal, string abiSerializableType)`                                                                                                                    |              |
| `public byte[]` [`Serialize`](EosSharp--Core--Providers.md)`(object value, string abiSerializableType)`                                                                                                                       |              |
| `public byte[]` [`SerializeActionData`](EosSharp--Core--Providers.md)`(` [`Action`](EosSharp--Core--Api--v1--Action.md)`action,` [`Abi`](EosSharp--Core--Api--v1--Abi.md) `abi)`                                              |              |
| `public T` [`DeserializeStructData< T >`](EosSharp--Core--Providers.md)`(string signingRequestIdentityV3, byte[] array,` [`Abi`](EosSharp--Core--Api--v1--Abi.md) `abi, ref int readIndex)`                                   |              |
| `public byte[]` [`SerializeStructData`](EosSharp--Core--Providers.md)`(object data,` [`AbiStruct`](EosSharp--Core--Api--v1--AbiStruct.md)`type,` [`Abi`](EosSharp--Core--Api--v1--Abi.md) `abi)`                              |              |
| `public Dictionary< string, object >` [`DeserializeStructData`](EosSharp--Core--Providers.md)`(string name, string hex_data,` [`Abi`](EosSharp--Core--Api--v1--Abi.md) `abi)`                                                 |              |
| `public byte[]` [`SerializePackedTransaction`](EosSharp--Core--Providers.md)`(` [`Transaction`](EosSharp--Core--Api--v1--Transaction.md)`transaction, Dictionary< string,` [`Abi`](EosSharp--Core--Api--v1--Abi.md) `> abis)` |              |

## Members

**`public`** [**`EosApi`**](EosSharp--Core--Api--v1--EosApi.md) **``** [**`Api`**](EosSharp--Core--Providers.md)

**`public Task<`** [**`Abi`**](EosSharp--Core--Api--v1--Abi.md)**`>` ** [**`GetAbi`**](EosSharp--Core--Providers.md)**`(string account)`**

**`public T`** [**`Deserialize< T >`**](EosSharp--Core--Providers.md)**`(byte[] rawVal, string abiSerializableType)`**

**`public byte[]`** [**`Serialize`**](EosSharp--Core--Providers.md)**`(object value, string abiSerializableType)`**

**`public byte[]`** [**`SerializeActionData`**](EosSharp--Core--Providers.md)**`(` ** [**`Action`**](EosSharp--Core--Api--v1--Action.md)**`action,` ** [**`Abi`**](EosSharp--Core--Api--v1--Abi.md) **`abi)`**

**`public T`** [**`DeserializeStructData< T >`**](EosSharp--Core--Providers.md)**`(string signingRequestIdentityV3, byte[] array,`** [**`Abi`**](EosSharp--Core--Api--v1--Abi.md) **`abi, ref int readIndex)`**

**`public byte[]`** [**`SerializeStructData`**](EosSharp--Core--Providers.md)**`(object data,`** [**`AbiStruct`**](EosSharp--Core--Api--v1--AbiStruct.md)**`type,` ** [**`Abi`**](EosSharp--Core--Api--v1--Abi.md) **`abi)`**

**`public Dictionary< string, object >`** [**`DeserializeStructData`**](EosSharp--Core--Providers.md)**`(string name, string hex_data,`** [**`Abi`**](EosSharp--Core--Api--v1--Abi.md) **`abi)`**

**`public byte[]`** [**`SerializePackedTransaction`**](EosSharp--Core--Providers.md)**`(` ** [**`Transaction`**](EosSharp--Core--Api--v1--Transaction.md)**`transaction, Dictionary< string,` ** [**`Abi`**](EosSharp--Core--Api--v1--Abi.md) **`> abis)`**
