# class `EosSharp::Core::Providers::AbiSerializationProvider` 

```
class EosSharp::Core::Providers::AbiSerializationProvider
  : public IAbiSerializationProvider
```

Serialize / deserialize transaction and fields using a Abi schema [https://developers.eos.io/eosio-home/docs/the-abi](https://developers.eos.io/eosio-home/docs/the-abi).

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public ` [`EosApi`](EosSharp--Core--Api--v1--EosApi.md)` ` [`Api`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a009709c7ea681d63e553e0757b6aad98) | 
`private Dictionary< string, ` [`Action`](EosSharp--Core--Api--v1--Action.md)`< MemoryStream, object > > ` [`TypeWriters`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1ad72e48be739d27c26ec88108dfdb1713) | 
`private Dictionary< string, ` [`ReaderDelegate`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a4b3954f690a83d221f051fe4d247a4a0)` > ` [`TypeReaders`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1adb945b19d93c43c4eccdc2efef7ec324) | 
`public ` [`AbiSerializationProvider`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1af0d04280ca397c9363633c7a655d1695)`(` [`EosApi`](EosSharp--Core--Api--v1--EosApi.md)` api)` | Construct abi serialization provided using EOS api.
`public ` [`AbiSerializationProvider`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a805412f077abcf0d2626bb71cf23dc5f)`()` | Construct abi serialization provided using EOS api.
`public async Task< byte[]> ` [`SerializePackedTransaction`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1ae944dc519928285ea32284ae481f50fc)`(` [`Transaction`](EosSharp--Core--Api--v1--Transaction.md)` trx)` | Serialize transaction to packed asynchronously.
`public byte[] ` [`SerializePackedTransaction`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a7968963f584623dab8955de8834acd7d)`(` [`Transaction`](EosSharp--Core--Api--v1--Transaction.md)` trx, Dictionary< string, ` [`Abi`](EosSharp--Core--Api--v1--Abi.md)` > abiMap)` | Serialize transaction to packed asynchronously.
`public async Task< ` [`Transaction`](EosSharp--Core--Api--v1--Transaction.md)` > ` [`DeserializePackedTransaction`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1ac4ce5b52ffdaa36eb384a06401d2f82d)`(string packtrx)` | Deserialize packed transaction asynchronously.
`public ` [`Abi`](EosSharp--Core--Api--v1--Abi.md)` ` [`DeserializePackedAbi`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a6948af6d8990d23201ae14e5b409cec7)`(string packabi)` | Deserialize packed abi.
`public byte[] ` [`SerializeActionData`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a5a00cc0aadcd8879b9ccf727f1abd984)`(` [`Core.Api.v1.Action`](EosSharp--Core--Api--v1--Action.md)` action, ` [`Abi`](EosSharp--Core--Api--v1--Abi.md)` abi)` | Serialize action to packed action data.
`public Dictionary< string, object > ` [`DeserializeStructData`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1adc2b5d436f61b8a9e7d2c0616d271d97)`(string structType, string dataHex, ` [`Abi`](EosSharp--Core--Api--v1--Abi.md)` abi)` | Deserialize structure data as "Dictionary<string, object>".
`public TStructData ` [`DeserializeStructData< TStructData >`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a137dd5d729b376a227684470c3d1cd2f)`(string structType, string dataHex, ` [`Abi`](EosSharp--Core--Api--v1--Abi.md)` abi)` | Deserialize structure data with generic TStructData type.
`public TStructData ` [`DeserializeStructData< TStructData >`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a0404206bd05c769a42c4c99b523d0883)`(string structType, string dataHex, ` [`Abi`](EosSharp--Core--Api--v1--Abi.md)` abi, ref int readIndex)` | Deserialize structure data with generic TStructData type.
`public TStructData ` [`DeserializeStructData< TStructData >`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a4ea655b57432fb074988eff99b37d0f3)`(string structType, byte[] data, ` [`Abi`](EosSharp--Core--Api--v1--Abi.md)` abi, ref int readIndex)` | Deserialize structure data with generic TStructData type.
`public Task< ` [`Abi`](EosSharp--Core--Api--v1--Abi.md)` ` [`GetTransactionAbis`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a7fe66e434fd86de9cc82a954bdd00542)`(` [`Transaction`](EosSharp--Core--Api--v1--Transaction.md)` trx)` | Get abi schemas used in transaction.
`public async Task< ` [`Abi`](EosSharp--Core--Api--v1--Abi.md)` > ` [`GetAbi`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a69f73da1f3f4f682df4ee5c282003f21)`(string accountName)` | Get abi schema by contract account name.
`public T ` [`DeserializeType< T >`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a6214712319846732baf10935978c1382)`(string dataHex)` | Deserialize type by encoded string data.
`public T ` [`DeserializeType< T >`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1ae3f8d0ec6c9e0eb2765303665154401d)`(byte[] data)` | Deserialize type by binary data.
`public T ` [`DeserializeType< T >`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a734fbdbc4cf0cf937e10847b0f2c856d)`(byte[] data, ref int readIndex)` | Deserialize type by binary data, ref readIndex.
`public byte[] ` [`SerializeTypeData`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a7a038ce7a360d4bee05fe0bcfe358a40)`(string typeName, object value, ` [`Abi`](EosSharp--Core--Api--v1--Abi.md)` abi)` | 
`public byte[] ` [`SerializeTypeData`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1aecd19937fe2efda921d0d0ab0d87d8f0)`(object value, ` [`AbiType`](EosSharp--Core--Api--v1--AbiType.md)` abiType, ` [`Abi`](EosSharp--Core--Api--v1--Abi.md)` abi)` | 
`public byte[] ` [`SerializeStructData`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1ae6a64445634dc494ca52a4aa0504de79)`(object value, ` [`AbiStruct`](EosSharp--Core--Api--v1--AbiStruct.md)` abiStruct, ` [`Abi`](EosSharp--Core--Api--v1--Abi.md)` abi)` | 
`public byte[] ` [`Serialize`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a2919381e8f0160aa4bbb440bd951a183)`(object value, string type)` | #### Parameters
`public T ` [`Deserialize< T >`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a445d5a518f2460cc3c78e0c15a1178fc)`(byte[] value, string type)` | #### Parameters
`private delegate object ` [`ReaderDelegate`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a4b3954f690a83d221f051fe4d247a4a0)`(byte[] data, ref int readIndex)` | 
`private void ` [`WriteAction`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a2dc17caf4d9afd08f568f90e2f13fed4)`(MemoryStream ms, ` [`Core.Api.v1.Action`](EosSharp--Core--Api--v1--Action.md)` action, ` [`Abi`](EosSharp--Core--Api--v1--Abi.md)` abi)` | 
`private void ` [`WriteAbiType`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a65ee5b7e5ba6a7082749f344a7723ac2)`(MemoryStream ms, object value, string type, ` [`Abi`](EosSharp--Core--Api--v1--Abi.md)` abi, bool isBinaryExtensionAllowed)` | 
`private void ` [`WriteAbiStruct`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1aeeaf1ed5ed0acc6ee46eef2aa8fa23c3)`(MemoryStream ms, object value, ` [`AbiStruct`](EosSharp--Core--Api--v1--AbiStruct.md)` abiStruct, ` [`Abi`](EosSharp--Core--Api--v1--Abi.md)` abi)` | 
`private void ` [`WriteAbiVariant`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1aa651b30cdc2c2e746562966d99b03dd1)`(MemoryStream ms, object value, ` [`Variant`](EosSharp--Core--Api--v1--Variant.md)` abiVariant, ` [`Abi`](EosSharp--Core--Api--v1--Abi.md)` abi, bool isBinaryExtensionAllowed)` | 
`private string ` [`UnwrapTypeDef`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a7caecee67f7b0cbaad9b5ba0122ee6b6)`(` [`Abi`](EosSharp--Core--Api--v1--Abi.md)` abi, string type)` | 
`private TSerializer ` [`GetTypeSerializerAndCache< TSerializer >`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1acde66cc5d0608f2f43d256eb3935733c)`(string type, Dictionary< string, TSerializer > typeSerializers, ` [`Abi`](EosSharp--Core--Api--v1--Abi.md)` abi)` | 
`private object ` [`ReadByte`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a2ff2df961188ce3d979d1e43989862ee)`(byte[] data, ref int readIndex)` | 
`private object ` [`ReadInt16`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a3658c1e7fe7ce6c1002edc6423a04d30)`(byte[] data, ref int readIndex)` | 
`private object ` [`ReadUint16`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1ade830f38c5731de2144516c31830251b)`(byte[] data, ref int readIndex)` | 
`private object ` [`ReadInt32`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a47afd1fe8db18e28626cdd60d89be58a)`(byte[] data, ref int readIndex)` | 
`private object ` [`ReadUint32`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a9d7c602465b5395b7a97bf107ebc0a0c)`(byte[] data, ref int readIndex)` | 
`private object ` [`ReadInt64`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a60b19c35acd5ff0a453293998827d5fa)`(byte[] data, ref int readIndex)` | 
`private object ` [`ReadUint64`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1ae30ad2ace4f45a2badf9547d5c2a8918)`(byte[] data, ref int readIndex)` | 
`private object ` [`ReadInt128`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a40e114af8e1f3c564e8f571eac86a4c9)`(byte[] data, ref int readIndex)` | 
`private object ` [`ReadUInt128`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a68e5d46ee3ca9ce4c04bd16880f14827)`(byte[] data, ref int readIndex)` | 
`private object ` [`ReadVarUint32`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a8be1ae6600cbb4be8badead26f2f13ef)`(byte[] data, ref int readIndex)` | 
`private object ` [`ReadVarInt32`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a91a86c0094d21136140f6257976b9bfe)`(byte[] data, ref int readIndex)` | 
`private object ` [`ReadFloat32`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1aabf4f0e640040f15a84b953f9ce8a464)`(byte[] data, ref int readIndex)` | 
`private object ` [`ReadFloat64`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1ad836aaf6d1152105b58b2f8a08934146)`(byte[] data, ref int readIndex)` | 
`private object ` [`ReadFloat128`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1abbdbb07cd7979e2d4a55fbe2f4e3be45)`(byte[] data, ref int readIndex)` | 
`private object ` [`ReadBytes`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a8591ec9d0fc15d49f24e848808a66ec8)`(byte[] data, ref int readIndex)` | 
`private object ` [`ReadBool`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1af283e12657b51056cf3394f78e286c0e)`(byte[] data, ref int readIndex)` | 
`private object ` [`ReadString`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a595054f9bcfb8bba3c54e72f87e5fd58)`(byte[] data, ref int readIndex)` | 
`private object ` [`ReadName`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a1aac1787932d1d0ae98965d519d117ee)`(byte[] data, ref int readIndex)` | 
`private object ` [`ReadAsset`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a8a5e22a045cfc442263190f426806917)`(byte[] data, ref int readIndex)` | 
`private object ` [`ReadTimePoint`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a781f3224bc811b68bc58e97c2b6c81d7)`(byte[] data, ref int readIndex)` | 
`private object ` [`ReadTimePointSec`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a5122f2a85f9980f812695938943a3675)`(byte[] data, ref int readIndex)` | 
`private object ` [`ReadBlockTimestampType`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a698266f23bc0e3da9cc06a2bbe3a090e)`(byte[] data, ref int readIndex)` | 
`private object ` [`ReadSymbolString`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1ab14dbdd7edcf1996bb9554a84f4cf1ed)`(byte[] data, ref int readIndex)` | 
`private object ` [`ReadSymbolCode`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a35344d35e5fb5d7709f007538cf7c662)`(byte[] data, ref int readIndex)` | 
`private object ` [`ReadChecksum160`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1ae06abe1842ffbdcef0cbf80681097f14)`(byte[] data, ref int readIndex)` | 
`private object ` [`ReadChecksum256`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a1b7c48682c5c649525d00d28d1b76821)`(byte[] data, ref int readIndex)` | 
`private object ` [`ReadChecksum512`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a9de19d94dbca45fcfb70075df8bcf846)`(byte[] data, ref int readIndex)` | 
`private object ` [`ReadPublicKey`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1ae73eeae318405b767a6855cff1602be7)`(byte[] data, ref int readIndex)` | 
`private object ` [`ReadPrivateKey`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a601f7efedb1cb7d8eab919fce24c42d8)`(byte[] data, ref int readIndex)` | 
`private object ` [`ReadSignature`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a4b734e85bc13f916533756b3ae9c4f20)`(byte[] data, ref int readIndex)` | 
`private object ` [`ReadExtendedAsset`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1ade520f813d88798d5a111c7d7dcad153)`(byte[] data, ref int readIndex)` | 
`private object ` [`ReadSymbol`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a8c81cd219cc06e19f281f7a21ea4eae9)`(byte[] data, ref int readIndex)` | 
`private object ` [`ReadPermissionLevel`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a6339e349c3024ac27be6c4eed2159dfe)`(byte[] data, ref int readIndex)` | 
`private object ` [`ReadActionHeader`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a43608d7e411608ebf1f1a1fb8d4e34da)`(byte[] data, ref int readIndex)` | 
`private object ` [`ReadAction`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1aaaa5b21e1509e9504866cccbfffd09e8)`(byte[] data, ` [`Core.Api.v1.Action`](EosSharp--Core--Api--v1--Action.md)` action, ` [`Abi`](EosSharp--Core--Api--v1--Abi.md)` abi, ref int readIndex)` | 
`private List< ` [`AbiAction`](EosSharp--Core--Api--v1--AbiAction.md)` > ` [`ReadAbiActionList`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1ac4778b50805d60ef54c2269d6ac1b772)`(byte[] data, ref int readIndex)` | 
`private List< ` [`AbiTable`](EosSharp--Core--Api--v1--AbiTable.md)` > ` [`ReadAbiTableList`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a5736a47dc7ff41a3d3a77a504b1fd4e6)`(byte[] data, ref int readIndex)` | 
`private object ` [`ReadAbiType`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a6faf90017940947dea2e8ae4000c3a1f)`(byte[] data, string type, ` [`Abi`](EosSharp--Core--Api--v1--Abi.md)` abi, ref int readIndex, bool isBinaryExtensionAllowed)` | 
`private object ` [`ReadAbiStruct`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a95bb30b914b07d30c84214b3e498f051)`(byte[] data, ` [`AbiStruct`](EosSharp--Core--Api--v1--AbiStruct.md)` abiStruct, ` [`Abi`](EosSharp--Core--Api--v1--Abi.md)` abi, ref int readIndex)` | 
`private T ` [`ReadAbiStruct< T >`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a0681400d7e93e83a3084de1a6fe79c15)`(byte[] data, ` [`AbiStruct`](EosSharp--Core--Api--v1--AbiStruct.md)` abiStruct, ` [`Abi`](EosSharp--Core--Api--v1--Abi.md)` abi, ref int readIndex)` | 
`private object ` [`ReadAbiVariant`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1ab35833687f73e065a7976792895e51b6)`(byte[] data, ` [`Variant`](EosSharp--Core--Api--v1--Variant.md)` abiVariant, ` [`Abi`](EosSharp--Core--Api--v1--Abi.md)` abi, ref int readIndex, bool isBinaryExtensionAllowed)` | 
`private T ` [`ReadType< T >`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a829b75036e6602374e7e62527a40b15e)`(byte[] data, ref int readIndex)` | 
`private object ` [`ReadType`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a34b3e24d76087773ad62e0cbb1630747)`(byte[] data, Type objectType, ref int readIndex)` | 
`private IList ` [`ReadCollectionType`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a015ddefedac263d549a4b2349b3cf109)`(byte[] data, Type objectType, ref int readIndex)` | 
`private string ` [`FindObjectFieldName`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a2d6cd85fbf7e73f1b876f4191540fd08)`(string name, System.Collections.IDictionary value)` | 
`private string ` [`FindObjectFieldName`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1acff2d9c02fc03578d2ae5c543a5b0902)`(string name, Type objectType)` | 
`private string ` [`FindObjectPropertyName`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a1a0cf7c04a981643145baa2795139f2e)`(string name, Type objectType)` | 
`private static void ` [`WriteByte`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a98447ea14d96cb85b652c02766e8d79f)`(MemoryStream ms, object value)` | 
`private static void ` [`WriteInt16`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1ae4c5da5e57be6e64589cf69de7cb8cd4)`(MemoryStream ms, object value)` | 
`private static void ` [`WriteUint16`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1abd9efbed1ac6dee12170badbc5950b9c)`(MemoryStream ms, object value)` | 
`private static void ` [`WriteUint32`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a74a6e3e9e48d20b632dfcba78333f6ca)`(MemoryStream ms, object value)` | 
`private static void ` [`WriteInt32`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1ab5c111271fb17742cd6fd2ef429a284d)`(MemoryStream ms, object value)` | 
`private static void ` [`WriteInt64`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a8410b9c5fc7a58a941968f86509c2961)`(MemoryStream ms, object value)` | 
`private static void ` [`WriteUint64`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a367e9f819f6804ea3982b23e3bcbc5ee)`(MemoryStream ms, object value)` | 
`private static void ` [`WriteInt128`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a796727d8b2843b34a6fe792d3fe93a6a)`(MemoryStream ms, object value)` | 
`private static void ` [`WriteUInt128`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a9b276b60d4cc48ef6301ece0c8d90c9a)`(MemoryStream ms, object value)` | 
`private static void ` [`WriteVarUint32`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a208f9dd45b0ee01d654c84e4980e2809)`(MemoryStream ms, object value)` | 
`private static void ` [`WriteVarInt32`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1ae33fffaff6a330cd4dff6cc3f6513e55)`(MemoryStream ms, object value)` | 
`private static void ` [`WriteFloat32`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a49d90bfb3eb47dbb426aa8dfe08ae126)`(MemoryStream ms, object value)` | 
`private static void ` [`WriteFloat64`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1ac85bc3fb761d52831963394d2f1f91bb)`(MemoryStream ms, object value)` | 
`private static void ` [`WriteFloat128`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1adf7f25e762f45ecfcbd97ddfa3a0c1a7)`(MemoryStream ms, object value)` | 
`private static void ` [`WriteBytes`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1ad72ea08bb8748a3bea4a718aa82e8adc)`(MemoryStream ms, object value)` | 
`private static void ` [`WriteBool`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a6622d6ac04c8e080794ce8b6027624b0)`(MemoryStream ms, object value)` | 
`private static void ` [`WriteString`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1ae433868ab474fc2a0581803659a3b926)`(MemoryStream ms, object value)` | 
`private static void ` [`WriteName`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a196f4ea05193116a2ce2c694ea146e48)`(MemoryStream ms, object value)` | 
`private static void ` [`WriteAsset`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1ac14eb16ed289ad285e3a480fcf3d0760)`(MemoryStream ms, object value)` | 
`private static void ` [`WriteTimePoint`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1adce708c6a0b143b151e66e8204232438)`(MemoryStream ms, object value)` | 
`private static void ` [`WriteTimePointSec`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a5302ac328fbee11f2d8281d585bbe565)`(MemoryStream ms, object value)` | 
`private static void ` [`WriteBlockTimestampType`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1aa5a81aa38518b43bc71a547d5d34b804)`(MemoryStream ms, object value)` | 
`private static void ` [`WriteSymbolString`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1aeff63c156dc3e36cab9a9d92baeb13c9)`(MemoryStream ms, object value)` | 
`private static void ` [`WriteSymbolCode`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1ac0666b688641a89f7aa17a97940b99ce)`(MemoryStream ms, object value)` | 
`private static void ` [`WriteChecksum160`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a2d8d35ec286d033eb713a8c45a56fad0)`(MemoryStream ms, object value)` | 
`private static void ` [`WriteChecksum256`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a8d172b1caef7300265304198d51a95bc)`(MemoryStream ms, object value)` | 
`private static void ` [`WriteChecksum512`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a4338460dbf502f9de373c8f64a04a4d7)`(MemoryStream ms, object value)` | 
`private static void ` [`WritePublicKey`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a78700a83727ced7a5ad0228f71dc56ba)`(MemoryStream ms, object value)` | 
`private static void ` [`WritePrivateKey`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1adcaf3b4a7146faee779afa16883f11a4)`(MemoryStream ms, object value)` | 
`private static void ` [`WriteSignature`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a331954f48d4ccec15aa71824c381f352)`(MemoryStream ms, object value)` | 
`private static void ` [`WriteExtendedAsset`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a333167e4f0883dc1992af84eed2410c0)`(MemoryStream ms, object value)` | 
`private static void ` [`WriteSymbol`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1ae19d79262e4e90381b4fcb285e930ceb)`(MemoryStream ms, object value)` | 
`private static void ` [`WriteExtension`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a9091bef018f54f6bfd9f145bac3247d3)`(MemoryStream ms, ` [`Core.Api.v1.Extension`](EosSharp--Core--Api--v1--Extension.md)` extension)` | 
`private static void ` [`WritePermissionLevel`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a0e33c9db1bc86b092fe1b1b16e77a27e)`(MemoryStream ms, ` [`PermissionLevel`](EosSharp--Core--Api--v1--PermissionLevel.md)` perm)` | 
`private static bool ` [`IsCollection`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a1356c19770154cfdafed70aa00787c59)`(Type type)` | 
`private static bool ` [`IsOptional`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a3bf0514b336adb0b8146cce5f763b0e9)`(Type type)` | 
`private static Type ` [`GetFirstGenericType`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a2045c72f23017b7322d4289b508e3eb5)`(Type type)` | 
`private static bool ` [`IsPrimitive`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a672adb55da26c616b649e664a2a1565c)`(Type type)` | 
`private static string ` [`GetNormalizedReaderName`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1ad593c365a0ac5edff13d6dbfcdf829d1)`(Type type, IEnumerable< Attribute > customAttributes)` | 

## Members

##### `public ` [`EosApi`](EosSharp--Core--Api--v1--EosApi.md)` ` [`Api`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a009709c7ea681d63e553e0757b6aad98) 

##### `private Dictionary< string, ` [`Action`](EosSharp--Core--Api--v1--Action.md)`< MemoryStream, object > > ` [`TypeWriters`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1ad72e48be739d27c26ec88108dfdb1713) 

##### `private Dictionary< string, ` [`ReaderDelegate`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a4b3954f690a83d221f051fe4d247a4a0)` > ` [`TypeReaders`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1adb945b19d93c43c4eccdc2efef7ec324) 

##### `public ` [`AbiSerializationProvider`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1af0d04280ca397c9363633c7a655d1695)`(` [`EosApi`](EosSharp--Core--Api--v1--EosApi.md)` api)` 

Construct abi serialization provided using EOS api.

#### Parameters
* `api`

##### `public ` [`AbiSerializationProvider`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a805412f077abcf0d2626bb71cf23dc5f)`()` 

Construct abi serialization provided using EOS api.

#### Parameters
* `api`

##### `public async Task< byte[]> ` [`SerializePackedTransaction`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1ae944dc519928285ea32284ae481f50fc)`(` [`Transaction`](EosSharp--Core--Api--v1--Transaction.md)` trx)` 

Serialize transaction to packed asynchronously.

#### Parameters
* `trx` transaction to pack

#### Returns

##### `public byte[] ` [`SerializePackedTransaction`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a7968963f584623dab8955de8834acd7d)`(` [`Transaction`](EosSharp--Core--Api--v1--Transaction.md)` trx, Dictionary< string, ` [`Abi`](EosSharp--Core--Api--v1--Abi.md)` > abiMap)` 

Serialize transaction to packed asynchronously.

#### Parameters
* `trx` transaction to pack

#### Returns

##### `public async Task< ` [`Transaction`](EosSharp--Core--Api--v1--Transaction.md)` > ` [`DeserializePackedTransaction`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1ac4ce5b52ffdaa36eb384a06401d2f82d)`(string packtrx)` 

Deserialize packed transaction asynchronously.

#### Parameters
* `packtrx` hex encoded strinh with packed transaction

#### Returns

##### `public ` [`Abi`](EosSharp--Core--Api--v1--Abi.md)` ` [`DeserializePackedAbi`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a6948af6d8990d23201ae14e5b409cec7)`(string packabi)` 

Deserialize packed abi.

#### Parameters
* `packabi` string encoded abi

#### Returns

##### `public byte[] ` [`SerializeActionData`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a5a00cc0aadcd8879b9ccf727f1abd984)`(` [`Core.Api.v1.Action`](EosSharp--Core--Api--v1--Action.md)` action, ` [`Abi`](EosSharp--Core--Api--v1--Abi.md)` abi)` 

Serialize action to packed action data.

#### Parameters
* `action` action to pack

* `abi` abi schema to look action structure

#### Returns

##### `public Dictionary< string, object > ` [`DeserializeStructData`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1adc2b5d436f61b8a9e7d2c0616d271d97)`(string structType, string dataHex, ` [`Abi`](EosSharp--Core--Api--v1--Abi.md)` abi)` 

Deserialize structure data as "Dictionary<string, object>".

#### Parameters
* `structType` struct type in abi

* `dataHex` data to deserialize

* `abi` abi schema to look for struct type

#### Returns

##### `public TStructData ` [`DeserializeStructData< TStructData >`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a137dd5d729b376a227684470c3d1cd2f)`(string structType, string dataHex, ` [`Abi`](EosSharp--Core--Api--v1--Abi.md)` abi)` 

Deserialize structure data with generic TStructData type.

#### Parameters
* `TStructData` deserialization struct data type

#### Parameters
* `structType` struct type in abi

* `dataHex` data to deserialize

* `abi` abi schema to look for struct type

#### Returns

##### `public TStructData ` [`DeserializeStructData< TStructData >`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a0404206bd05c769a42c4c99b523d0883)`(string structType, string dataHex, ` [`Abi`](EosSharp--Core--Api--v1--Abi.md)` abi, ref int readIndex)` 

Deserialize structure data with generic TStructData type.

#### Parameters
* `TStructData` deserialization struct data type

#### Parameters
* `structType` struct type in abi

* `dataHex` data to deserialize

* `abi` abi schema to look for struct type

* `readIndex` 

#### Returns

##### `public TStructData ` [`DeserializeStructData< TStructData >`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a4ea655b57432fb074988eff99b37d0f3)`(string structType, byte[] data, ` [`Abi`](EosSharp--Core--Api--v1--Abi.md)` abi, ref int readIndex)` 

Deserialize structure data with generic TStructData type.

#### Parameters
* `TStructData` deserialization struct data type

#### Parameters
* `structType` struct type in abi

* `data` data to deserialize

* `abi` abi schema to look for struct type

* `readIndex` 

#### Returns

##### `public Task< ` [`Abi`](EosSharp--Core--Api--v1--Abi.md)` ` [`GetTransactionAbis`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a7fe66e434fd86de9cc82a954bdd00542)`(` [`Transaction`](EosSharp--Core--Api--v1--Transaction.md)` trx)` 

Get abi schemas used in transaction.

#### Parameters
* `trx` 

#### Returns

##### `public async Task< ` [`Abi`](EosSharp--Core--Api--v1--Abi.md)` > ` [`GetAbi`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a69f73da1f3f4f682df4ee5c282003f21)`(string accountName)` 

Get abi schema by contract account name.

#### Parameters
* `accountName` account name

#### Returns

##### `public T ` [`DeserializeType< T >`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a6214712319846732baf10935978c1382)`(string dataHex)` 

Deserialize type by encoded string data.

#### Parameters
* `T` 

#### Parameters
* `dataHex` 

#### Returns

##### `public T ` [`DeserializeType< T >`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1ae3f8d0ec6c9e0eb2765303665154401d)`(byte[] data)` 

Deserialize type by binary data.

#### Parameters
* `T` 

#### Parameters
* `data` 

#### Returns

##### `public T ` [`DeserializeType< T >`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a734fbdbc4cf0cf937e10847b0f2c856d)`(byte[] data, ref int readIndex)` 

Deserialize type by binary data, ref readIndex.

#### Parameters
* `T` 

#### Parameters
* `data` 
* `readIndex` 

#### Returns

##### `public byte[] ` [`SerializeTypeData`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a7a038ce7a360d4bee05fe0bcfe358a40)`(string typeName, object value, ` [`Abi`](EosSharp--Core--Api--v1--Abi.md)` abi)` 

##### `public byte[] ` [`SerializeTypeData`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1aecd19937fe2efda921d0d0ab0d87d8f0)`(object value, ` [`AbiType`](EosSharp--Core--Api--v1--AbiType.md)` abiType, ` [`Abi`](EosSharp--Core--Api--v1--Abi.md)` abi)` 

##### `public byte[] ` [`SerializeStructData`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1ae6a64445634dc494ca52a4aa0504de79)`(object value, ` [`AbiStruct`](EosSharp--Core--Api--v1--AbiStruct.md)` abiStruct, ` [`Abi`](EosSharp--Core--Api--v1--Abi.md)` abi)` 

##### `public byte[] ` [`Serialize`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a2919381e8f0160aa4bbb440bd951a183)`(object value, string type)` 

#### Parameters
* `action` action to pack

* `abi` abi schema to look action structure

#### Returns

##### `public T ` [`Deserialize< T >`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a445d5a518f2460cc3c78e0c15a1178fc)`(byte[] value, string type)` 

#### Parameters
* `action` action to pack

* `abi` abi schema to look action structure

#### Returns

##### `private delegate object ` [`ReaderDelegate`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a4b3954f690a83d221f051fe4d247a4a0)`(byte[] data, ref int readIndex)` 

##### `private void ` [`WriteAction`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a2dc17caf4d9afd08f568f90e2f13fed4)`(MemoryStream ms, ` [`Core.Api.v1.Action`](EosSharp--Core--Api--v1--Action.md)` action, ` [`Abi`](EosSharp--Core--Api--v1--Abi.md)` abi)` 

##### `private void ` [`WriteAbiType`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a65ee5b7e5ba6a7082749f344a7723ac2)`(MemoryStream ms, object value, string type, ` [`Abi`](EosSharp--Core--Api--v1--Abi.md)` abi, bool isBinaryExtensionAllowed)` 

##### `private void ` [`WriteAbiStruct`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1aeeaf1ed5ed0acc6ee46eef2aa8fa23c3)`(MemoryStream ms, object value, ` [`AbiStruct`](EosSharp--Core--Api--v1--AbiStruct.md)` abiStruct, ` [`Abi`](EosSharp--Core--Api--v1--Abi.md)` abi)` 

##### `private void ` [`WriteAbiVariant`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1aa651b30cdc2c2e746562966d99b03dd1)`(MemoryStream ms, object value, ` [`Variant`](EosSharp--Core--Api--v1--Variant.md)` abiVariant, ` [`Abi`](EosSharp--Core--Api--v1--Abi.md)` abi, bool isBinaryExtensionAllowed)` 

##### `private string ` [`UnwrapTypeDef`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a7caecee67f7b0cbaad9b5ba0122ee6b6)`(` [`Abi`](EosSharp--Core--Api--v1--Abi.md)` abi, string type)` 

##### `private TSerializer ` [`GetTypeSerializerAndCache< TSerializer >`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1acde66cc5d0608f2f43d256eb3935733c)`(string type, Dictionary< string, TSerializer > typeSerializers, ` [`Abi`](EosSharp--Core--Api--v1--Abi.md)` abi)` 

##### `private object ` [`ReadByte`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a2ff2df961188ce3d979d1e43989862ee)`(byte[] data, ref int readIndex)` 

##### `private object ` [`ReadInt16`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a3658c1e7fe7ce6c1002edc6423a04d30)`(byte[] data, ref int readIndex)` 

##### `private object ` [`ReadUint16`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1ade830f38c5731de2144516c31830251b)`(byte[] data, ref int readIndex)` 

##### `private object ` [`ReadInt32`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a47afd1fe8db18e28626cdd60d89be58a)`(byte[] data, ref int readIndex)` 

##### `private object ` [`ReadUint32`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a9d7c602465b5395b7a97bf107ebc0a0c)`(byte[] data, ref int readIndex)` 

##### `private object ` [`ReadInt64`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a60b19c35acd5ff0a453293998827d5fa)`(byte[] data, ref int readIndex)` 

##### `private object ` [`ReadUint64`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1ae30ad2ace4f45a2badf9547d5c2a8918)`(byte[] data, ref int readIndex)` 

##### `private object ` [`ReadInt128`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a40e114af8e1f3c564e8f571eac86a4c9)`(byte[] data, ref int readIndex)` 

##### `private object ` [`ReadUInt128`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a68e5d46ee3ca9ce4c04bd16880f14827)`(byte[] data, ref int readIndex)` 

##### `private object ` [`ReadVarUint32`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a8be1ae6600cbb4be8badead26f2f13ef)`(byte[] data, ref int readIndex)` 

##### `private object ` [`ReadVarInt32`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a91a86c0094d21136140f6257976b9bfe)`(byte[] data, ref int readIndex)` 

##### `private object ` [`ReadFloat32`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1aabf4f0e640040f15a84b953f9ce8a464)`(byte[] data, ref int readIndex)` 

##### `private object ` [`ReadFloat64`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1ad836aaf6d1152105b58b2f8a08934146)`(byte[] data, ref int readIndex)` 

##### `private object ` [`ReadFloat128`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1abbdbb07cd7979e2d4a55fbe2f4e3be45)`(byte[] data, ref int readIndex)` 

##### `private object ` [`ReadBytes`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a8591ec9d0fc15d49f24e848808a66ec8)`(byte[] data, ref int readIndex)` 

##### `private object ` [`ReadBool`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1af283e12657b51056cf3394f78e286c0e)`(byte[] data, ref int readIndex)` 

##### `private object ` [`ReadString`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a595054f9bcfb8bba3c54e72f87e5fd58)`(byte[] data, ref int readIndex)` 

##### `private object ` [`ReadName`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a1aac1787932d1d0ae98965d519d117ee)`(byte[] data, ref int readIndex)` 

##### `private object ` [`ReadAsset`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a8a5e22a045cfc442263190f426806917)`(byte[] data, ref int readIndex)` 

##### `private object ` [`ReadTimePoint`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a781f3224bc811b68bc58e97c2b6c81d7)`(byte[] data, ref int readIndex)` 

##### `private object ` [`ReadTimePointSec`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a5122f2a85f9980f812695938943a3675)`(byte[] data, ref int readIndex)` 

##### `private object ` [`ReadBlockTimestampType`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a698266f23bc0e3da9cc06a2bbe3a090e)`(byte[] data, ref int readIndex)` 

##### `private object ` [`ReadSymbolString`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1ab14dbdd7edcf1996bb9554a84f4cf1ed)`(byte[] data, ref int readIndex)` 

##### `private object ` [`ReadSymbolCode`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a35344d35e5fb5d7709f007538cf7c662)`(byte[] data, ref int readIndex)` 

##### `private object ` [`ReadChecksum160`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1ae06abe1842ffbdcef0cbf80681097f14)`(byte[] data, ref int readIndex)` 

##### `private object ` [`ReadChecksum256`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a1b7c48682c5c649525d00d28d1b76821)`(byte[] data, ref int readIndex)` 

##### `private object ` [`ReadChecksum512`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a9de19d94dbca45fcfb70075df8bcf846)`(byte[] data, ref int readIndex)` 

##### `private object ` [`ReadPublicKey`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1ae73eeae318405b767a6855cff1602be7)`(byte[] data, ref int readIndex)` 

##### `private object ` [`ReadPrivateKey`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a601f7efedb1cb7d8eab919fce24c42d8)`(byte[] data, ref int readIndex)` 

##### `private object ` [`ReadSignature`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a4b734e85bc13f916533756b3ae9c4f20)`(byte[] data, ref int readIndex)` 

##### `private object ` [`ReadExtendedAsset`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1ade520f813d88798d5a111c7d7dcad153)`(byte[] data, ref int readIndex)` 

##### `private object ` [`ReadSymbol`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a8c81cd219cc06e19f281f7a21ea4eae9)`(byte[] data, ref int readIndex)` 

##### `private object ` [`ReadPermissionLevel`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a6339e349c3024ac27be6c4eed2159dfe)`(byte[] data, ref int readIndex)` 

##### `private object ` [`ReadActionHeader`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a43608d7e411608ebf1f1a1fb8d4e34da)`(byte[] data, ref int readIndex)` 

##### `private object ` [`ReadAction`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1aaaa5b21e1509e9504866cccbfffd09e8)`(byte[] data, ` [`Core.Api.v1.Action`](EosSharp--Core--Api--v1--Action.md)` action, ` [`Abi`](EosSharp--Core--Api--v1--Abi.md)` abi, ref int readIndex)` 

##### `private List< ` [`AbiAction`](EosSharp--Core--Api--v1--AbiAction.md)` > ` [`ReadAbiActionList`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1ac4778b50805d60ef54c2269d6ac1b772)`(byte[] data, ref int readIndex)` 

##### `private List< ` [`AbiTable`](EosSharp--Core--Api--v1--AbiTable.md)` > ` [`ReadAbiTableList`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a5736a47dc7ff41a3d3a77a504b1fd4e6)`(byte[] data, ref int readIndex)` 

##### `private object ` [`ReadAbiType`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a6faf90017940947dea2e8ae4000c3a1f)`(byte[] data, string type, ` [`Abi`](EosSharp--Core--Api--v1--Abi.md)` abi, ref int readIndex, bool isBinaryExtensionAllowed)` 

##### `private object ` [`ReadAbiStruct`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a95bb30b914b07d30c84214b3e498f051)`(byte[] data, ` [`AbiStruct`](EosSharp--Core--Api--v1--AbiStruct.md)` abiStruct, ` [`Abi`](EosSharp--Core--Api--v1--Abi.md)` abi, ref int readIndex)` 

##### `private T ` [`ReadAbiStruct< T >`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a0681400d7e93e83a3084de1a6fe79c15)`(byte[] data, ` [`AbiStruct`](EosSharp--Core--Api--v1--AbiStruct.md)` abiStruct, ` [`Abi`](EosSharp--Core--Api--v1--Abi.md)` abi, ref int readIndex)` 

##### `private object ` [`ReadAbiVariant`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1ab35833687f73e065a7976792895e51b6)`(byte[] data, ` [`Variant`](EosSharp--Core--Api--v1--Variant.md)` abiVariant, ` [`Abi`](EosSharp--Core--Api--v1--Abi.md)` abi, ref int readIndex, bool isBinaryExtensionAllowed)` 

##### `private T ` [`ReadType< T >`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a829b75036e6602374e7e62527a40b15e)`(byte[] data, ref int readIndex)` 

##### `private object ` [`ReadType`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a34b3e24d76087773ad62e0cbb1630747)`(byte[] data, Type objectType, ref int readIndex)` 

##### `private IList ` [`ReadCollectionType`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a015ddefedac263d549a4b2349b3cf109)`(byte[] data, Type objectType, ref int readIndex)` 

##### `private string ` [`FindObjectFieldName`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a2d6cd85fbf7e73f1b876f4191540fd08)`(string name, System.Collections.IDictionary value)` 

##### `private string ` [`FindObjectFieldName`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1acff2d9c02fc03578d2ae5c543a5b0902)`(string name, Type objectType)` 

##### `private string ` [`FindObjectPropertyName`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a1a0cf7c04a981643145baa2795139f2e)`(string name, Type objectType)` 

##### `private static void ` [`WriteByte`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a98447ea14d96cb85b652c02766e8d79f)`(MemoryStream ms, object value)` 

##### `private static void ` [`WriteInt16`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1ae4c5da5e57be6e64589cf69de7cb8cd4)`(MemoryStream ms, object value)` 

##### `private static void ` [`WriteUint16`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1abd9efbed1ac6dee12170badbc5950b9c)`(MemoryStream ms, object value)` 

##### `private static void ` [`WriteUint32`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a74a6e3e9e48d20b632dfcba78333f6ca)`(MemoryStream ms, object value)` 

##### `private static void ` [`WriteInt32`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1ab5c111271fb17742cd6fd2ef429a284d)`(MemoryStream ms, object value)` 

##### `private static void ` [`WriteInt64`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a8410b9c5fc7a58a941968f86509c2961)`(MemoryStream ms, object value)` 

##### `private static void ` [`WriteUint64`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a367e9f819f6804ea3982b23e3bcbc5ee)`(MemoryStream ms, object value)` 

##### `private static void ` [`WriteInt128`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a796727d8b2843b34a6fe792d3fe93a6a)`(MemoryStream ms, object value)` 

##### `private static void ` [`WriteUInt128`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a9b276b60d4cc48ef6301ece0c8d90c9a)`(MemoryStream ms, object value)` 

##### `private static void ` [`WriteVarUint32`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a208f9dd45b0ee01d654c84e4980e2809)`(MemoryStream ms, object value)` 

##### `private static void ` [`WriteVarInt32`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1ae33fffaff6a330cd4dff6cc3f6513e55)`(MemoryStream ms, object value)` 

##### `private static void ` [`WriteFloat32`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a49d90bfb3eb47dbb426aa8dfe08ae126)`(MemoryStream ms, object value)` 

##### `private static void ` [`WriteFloat64`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1ac85bc3fb761d52831963394d2f1f91bb)`(MemoryStream ms, object value)` 

##### `private static void ` [`WriteFloat128`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1adf7f25e762f45ecfcbd97ddfa3a0c1a7)`(MemoryStream ms, object value)` 

##### `private static void ` [`WriteBytes`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1ad72ea08bb8748a3bea4a718aa82e8adc)`(MemoryStream ms, object value)` 

##### `private static void ` [`WriteBool`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a6622d6ac04c8e080794ce8b6027624b0)`(MemoryStream ms, object value)` 

##### `private static void ` [`WriteString`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1ae433868ab474fc2a0581803659a3b926)`(MemoryStream ms, object value)` 

##### `private static void ` [`WriteName`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a196f4ea05193116a2ce2c694ea146e48)`(MemoryStream ms, object value)` 

##### `private static void ` [`WriteAsset`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1ac14eb16ed289ad285e3a480fcf3d0760)`(MemoryStream ms, object value)` 

##### `private static void ` [`WriteTimePoint`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1adce708c6a0b143b151e66e8204232438)`(MemoryStream ms, object value)` 

##### `private static void ` [`WriteTimePointSec`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a5302ac328fbee11f2d8281d585bbe565)`(MemoryStream ms, object value)` 

##### `private static void ` [`WriteBlockTimestampType`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1aa5a81aa38518b43bc71a547d5d34b804)`(MemoryStream ms, object value)` 

##### `private static void ` [`WriteSymbolString`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1aeff63c156dc3e36cab9a9d92baeb13c9)`(MemoryStream ms, object value)` 

##### `private static void ` [`WriteSymbolCode`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1ac0666b688641a89f7aa17a97940b99ce)`(MemoryStream ms, object value)` 

##### `private static void ` [`WriteChecksum160`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a2d8d35ec286d033eb713a8c45a56fad0)`(MemoryStream ms, object value)` 

##### `private static void ` [`WriteChecksum256`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a8d172b1caef7300265304198d51a95bc)`(MemoryStream ms, object value)` 

##### `private static void ` [`WriteChecksum512`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a4338460dbf502f9de373c8f64a04a4d7)`(MemoryStream ms, object value)` 

##### `private static void ` [`WritePublicKey`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a78700a83727ced7a5ad0228f71dc56ba)`(MemoryStream ms, object value)` 

##### `private static void ` [`WritePrivateKey`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1adcaf3b4a7146faee779afa16883f11a4)`(MemoryStream ms, object value)` 

##### `private static void ` [`WriteSignature`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a331954f48d4ccec15aa71824c381f352)`(MemoryStream ms, object value)` 

##### `private static void ` [`WriteExtendedAsset`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a333167e4f0883dc1992af84eed2410c0)`(MemoryStream ms, object value)` 

##### `private static void ` [`WriteSymbol`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1ae19d79262e4e90381b4fcb285e930ceb)`(MemoryStream ms, object value)` 

##### `private static void ` [`WriteExtension`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a9091bef018f54f6bfd9f145bac3247d3)`(MemoryStream ms, ` [`Core.Api.v1.Extension`](EosSharp--Core--Api--v1--Extension.md)` extension)` 

##### `private static void ` [`WritePermissionLevel`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a0e33c9db1bc86b092fe1b1b16e77a27e)`(MemoryStream ms, ` [`PermissionLevel`](EosSharp--Core--Api--v1--PermissionLevel.md)` perm)` 

##### `private static bool ` [`IsCollection`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a1356c19770154cfdafed70aa00787c59)`(Type type)` 

##### `private static bool ` [`IsOptional`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a3bf0514b336adb0b8146cce5f763b0e9)`(Type type)` 

##### `private static Type ` [`GetFirstGenericType`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a2045c72f23017b7322d4289b508e3eb5)`(Type type)` 

##### `private static bool ` [`IsPrimitive`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1a672adb55da26c616b649e664a2a1565c)`(Type type)` 

##### `private static string ` [`GetNormalizedReaderName`](#class_eos_sharp_1_1_core_1_1_providers_1_1_abi_serialization_provider_1ad593c365a0ac5edff13d6dbfcdf829d1)`(Type type, IEnumerable< Attribute > customAttributes)` 

