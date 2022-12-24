# class `EosSharp::Core::Helpers::SerializationHelper` 

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public static bool ` [`IsNegative`](#class_eos_sharp_1_1_core_1_1_helpers_1_1_serialization_helper_1aed216d2cdbe03794e7f6a3a2a960f410)`(byte[] bin)` | Is a big Number negative.
`public static void ` [`Negate`](#class_eos_sharp_1_1_core_1_1_helpers_1_1_serialization_helper_1a82488b4cffc57a54863e5c5bd310cd69)`(byte[] bin)` | Negate a big number.
`public static byte[] ` [`DecimalToBinary`](#class_eos_sharp_1_1_core_1_1_helpers_1_1_serialization_helper_1abe01ef075065ef4d39bed29632c49359)`(uint size, string s)` | Convert an unsigned decimal number as string to a big number.
`public static byte[] ` [`SignedDecimalToBinary`](#class_eos_sharp_1_1_core_1_1_helpers_1_1_serialization_helper_1a597b577fe75373ad8aa37d5d4b06e332)`(uint size, string s)` | Convert an signed decimal number as string to a big number.
`public static string ` [`BinaryToDecimal`](#class_eos_sharp_1_1_core_1_1_helpers_1_1_serialization_helper_1abe0ddafc71c19f66748646ea93fb72a9)`(byte[] bin, int minDigits)` | Convert big number to an unsigned decimal number.
`public static string ` [`SignedBinaryToDecimal`](#class_eos_sharp_1_1_core_1_1_helpers_1_1_serialization_helper_1a2241a7786a029417aa70b1f07dd397e0)`(byte[] bin, int minDigits)` | Convert big number to an signed decimal number.
`public static byte[] ` [`Base64FcStringToByteArray`](#class_eos_sharp_1_1_core_1_1_helpers_1_1_serialization_helper_1a68c3b58df5a309860ad42d469fbad1b6)`(string s)` | Convert base64 with fc prefix to byte array.
`public static byte ` [`CharToSymbol`](#class_eos_sharp_1_1_core_1_1_helpers_1_1_serialization_helper_1aee33a8596d4aa8b281720f975dd58d53)`(char c)` | Convert ascii char to symbol value.
`public static string ` [`SnakeCaseToPascalCase`](#class_eos_sharp_1_1_core_1_1_helpers_1_1_serialization_helper_1a54175f8aec9ed870844c1b0b04f111e9)`(string s)` | Convert snake case string to pascal case.
`public static string ` [`PascalCaseToSnakeCase`](#class_eos_sharp_1_1_core_1_1_helpers_1_1_serialization_helper_1add42c630befc38b3595d7b63b851b370)`(string s)` | Convert pascal case string to snake case.
`public static byte[] ` [`ObjectToByteArray`](#class_eos_sharp_1_1_core_1_1_helpers_1_1_serialization_helper_1af13e7e034aeaea3d5123c41d3b28f637)`(object obj)` | Serialize object to byte array.
`public static string ` [`ByteArrayToHexString`](#class_eos_sharp_1_1_core_1_1_helpers_1_1_serialization_helper_1af5a67e31714ea1aa43b27230fbd38350)`(byte[] ba)` | Encode byte array to hexadecimal string.
`public static byte[] ` [`HexStringToByteArray`](#class_eos_sharp_1_1_core_1_1_helpers_1_1_serialization_helper_1a7019135e4b14b81eb9374b42b523e665)`(string hex)` | Decode hexadecimal string to byte array.
`public static string ` [`ObjectToHexString`](#class_eos_sharp_1_1_core_1_1_helpers_1_1_serialization_helper_1a23ee6b5cba70acbfa79ffb73b7082af5)`(object obj)` | Serialize object to hexadecimal encoded string.
`public static byte[] ` [`Combine`](#class_eos_sharp_1_1_core_1_1_helpers_1_1_serialization_helper_1adfe42c165286a0731ee8c0f0e3671b54)`(IEnumerable< byte[]> arrays)` | Combina multiple arrays into one.
`public static UInt64 ` [`DateToTimePoint`](#class_eos_sharp_1_1_core_1_1_helpers_1_1_serialization_helper_1a74e3603c9aa91ab891b538e2da90a170)`(DateTime value)` | Convert DateTime to `time_point` (miliseconds since epoch)
`public static DateTime ` [`TimePointToDate`](#class_eos_sharp_1_1_core_1_1_helpers_1_1_serialization_helper_1a697260c623e80144bf94badcced78a3c)`(long ticks)` | Convert `time_point` (miliseconds since epoch) to DateTime.
`public static UInt32 ` [`DateToTimePointSec`](#class_eos_sharp_1_1_core_1_1_helpers_1_1_serialization_helper_1a7df0c2b0e92a1d00fc868f3bbd6986c7)`(DateTime value)` | Convert DateTime to `time_point_sec` (seconds since epoch)
`public static DateTime ` [`TimePointSecToDate`](#class_eos_sharp_1_1_core_1_1_helpers_1_1_serialization_helper_1a386e734156401132539b04b8432ee1e7)`(UInt32 secs)` | Convert `time_point_sec` (seconds since epoch) to DateTime.
`public static UInt32 ` [`DateToBlockTimestamp`](#class_eos_sharp_1_1_core_1_1_helpers_1_1_serialization_helper_1a2372ba341180b1e2f53128e75b543c86)`(DateTime value)` | Convert DateTime to `block_timestamp_type` (half-seconds since a different epoch)
`public static DateTime ` [`BlockTimestampToDate`](#class_eos_sharp_1_1_core_1_1_helpers_1_1_serialization_helper_1a004b7c9cc14fb75cfe80891c316f464d)`(UInt32 slot)` | Convert `block_timestamp_type` (half-seconds since a different epoch) to DateTime.
`public static UInt64 ` [`ConvertNameToLong`](#class_eos_sharp_1_1_core_1_1_helpers_1_1_serialization_helper_1a20bb129c87aa0f1b1e1be00d6a175556)`(string name)` | Convert Name into unsigned long.
`public static byte[] ` [`ConvertNameToBytes`](#class_eos_sharp_1_1_core_1_1_helpers_1_1_serialization_helper_1a70509f33a8c6f936a575d5d39af62a15)`(string name)` | Convert Name into bytes.
`public static string ` [`ReverseHex`](#class_eos_sharp_1_1_core_1_1_helpers_1_1_serialization_helper_1add51ded0a7538be5ff80038ac5df89fc)`(string h)` | 
`public static string ` [`ConvertULongToName`](#class_eos_sharp_1_1_core_1_1_helpers_1_1_serialization_helper_1aacf360f56c366a92fa182f6505192cae)`(ulong binary)` | Convert uint64_t into EOSIO name.

## Members

##### `public static bool ` [`IsNegative`](#class_eos_sharp_1_1_core_1_1_helpers_1_1_serialization_helper_1aed216d2cdbe03794e7f6a3a2a960f410)`(byte[] bin)` 

Is a big Number negative.

#### Parameters
* `bin` big number in byte array

#### Returns

##### `public static void ` [`Negate`](#class_eos_sharp_1_1_core_1_1_helpers_1_1_serialization_helper_1a82488b4cffc57a54863e5c5bd310cd69)`(byte[] bin)` 

Negate a big number.

#### Parameters
* `bin` big number in byte array

##### `public static byte[] ` [`DecimalToBinary`](#class_eos_sharp_1_1_core_1_1_helpers_1_1_serialization_helper_1abe01ef075065ef4d39bed29632c49359)`(uint size, string s)` 

Convert an unsigned decimal number as string to a big number.

#### Parameters
* `size` Size in bytes of the big number

* `s` decimal encoded as string

#### Returns

##### `public static byte[] ` [`SignedDecimalToBinary`](#class_eos_sharp_1_1_core_1_1_helpers_1_1_serialization_helper_1a597b577fe75373ad8aa37d5d4b06e332)`(uint size, string s)` 

Convert an signed decimal number as string to a big number.

#### Parameters
* `size` Size in bytes of the big number

* `s` decimal encoded as string

#### Returns

##### `public static string ` [`BinaryToDecimal`](#class_eos_sharp_1_1_core_1_1_helpers_1_1_serialization_helper_1abe0ddafc71c19f66748646ea93fb72a9)`(byte[] bin, int minDigits)` 

Convert big number to an unsigned decimal number.

#### Parameters
* `bin` big number as byte array

* `minDigits` 0-pad result to this many digits

#### Returns

##### `public static string ` [`SignedBinaryToDecimal`](#class_eos_sharp_1_1_core_1_1_helpers_1_1_serialization_helper_1a2241a7786a029417aa70b1f07dd397e0)`(byte[] bin, int minDigits)` 

Convert big number to an signed decimal number.

#### Parameters
* `bin` big number as byte array

* `minDigits` 0-pad result to this many digits

#### Returns

##### `public static byte[] ` [`Base64FcStringToByteArray`](#class_eos_sharp_1_1_core_1_1_helpers_1_1_serialization_helper_1a68c3b58df5a309860ad42d469fbad1b6)`(string s)` 

Convert base64 with fc prefix to byte array.

#### Parameters
* `s` string to convert

#### Returns

##### `public static byte ` [`CharToSymbol`](#class_eos_sharp_1_1_core_1_1_helpers_1_1_serialization_helper_1aee33a8596d4aa8b281720f975dd58d53)`(char c)` 

Convert ascii char to symbol value.

#### Parameters
* `c` 

#### Returns

##### `public static string ` [`SnakeCaseToPascalCase`](#class_eos_sharp_1_1_core_1_1_helpers_1_1_serialization_helper_1a54175f8aec9ed870844c1b0b04f111e9)`(string s)` 

Convert snake case string to pascal case.

#### Parameters
* `s` string to convert

#### Returns

##### `public static string ` [`PascalCaseToSnakeCase`](#class_eos_sharp_1_1_core_1_1_helpers_1_1_serialization_helper_1add42c630befc38b3595d7b63b851b370)`(string s)` 

Convert pascal case string to snake case.

#### Parameters
* `s` string to convert

#### Returns

##### `public static byte[] ` [`ObjectToByteArray`](#class_eos_sharp_1_1_core_1_1_helpers_1_1_serialization_helper_1af13e7e034aeaea3d5123c41d3b28f637)`(object obj)` 

Serialize object to byte array.

#### Parameters
* `obj` object to serialize

#### Returns

##### `public static string ` [`ByteArrayToHexString`](#class_eos_sharp_1_1_core_1_1_helpers_1_1_serialization_helper_1af5a67e31714ea1aa43b27230fbd38350)`(byte[] ba)` 

Encode byte array to hexadecimal string.

#### Parameters
* `ba` byte array to convert

#### Returns

##### `public static byte[] ` [`HexStringToByteArray`](#class_eos_sharp_1_1_core_1_1_helpers_1_1_serialization_helper_1a7019135e4b14b81eb9374b42b523e665)`(string hex)` 

Decode hexadecimal string to byte array.

#### Parameters
* `hex` 

#### Returns

##### `public static string ` [`ObjectToHexString`](#class_eos_sharp_1_1_core_1_1_helpers_1_1_serialization_helper_1a23ee6b5cba70acbfa79ffb73b7082af5)`(object obj)` 

Serialize object to hexadecimal encoded string.

#### Parameters
* `obj` 

#### Returns

##### `public static byte[] ` [`Combine`](#class_eos_sharp_1_1_core_1_1_helpers_1_1_serialization_helper_1adfe42c165286a0731ee8c0f0e3671b54)`(IEnumerable< byte[]> arrays)` 

Combina multiple arrays into one.

#### Parameters
* `arrays` 

#### Returns

##### `public static UInt64 ` [`DateToTimePoint`](#class_eos_sharp_1_1_core_1_1_helpers_1_1_serialization_helper_1a74e3603c9aa91ab891b538e2da90a170)`(DateTime value)` 

Convert DateTime to `time_point` (miliseconds since epoch)

#### Parameters
* `value` date to convert

#### Returns

##### `public static DateTime ` [`TimePointToDate`](#class_eos_sharp_1_1_core_1_1_helpers_1_1_serialization_helper_1a697260c623e80144bf94badcced78a3c)`(long ticks)` 

Convert `time_point` (miliseconds since epoch) to DateTime.

#### Parameters
* `ticks` time_point ticks to convert

#### Returns

##### `public static UInt32 ` [`DateToTimePointSec`](#class_eos_sharp_1_1_core_1_1_helpers_1_1_serialization_helper_1a7df0c2b0e92a1d00fc868f3bbd6986c7)`(DateTime value)` 

Convert DateTime to `time_point_sec` (seconds since epoch)

#### Parameters
* `value` date to convert

#### Returns

##### `public static DateTime ` [`TimePointSecToDate`](#class_eos_sharp_1_1_core_1_1_helpers_1_1_serialization_helper_1a386e734156401132539b04b8432ee1e7)`(UInt32 secs)` 

Convert `time_point_sec` (seconds since epoch) to DateTime.

#### Parameters
* `secs` time_point_sec to convert

#### Returns

##### `public static UInt32 ` [`DateToBlockTimestamp`](#class_eos_sharp_1_1_core_1_1_helpers_1_1_serialization_helper_1a2372ba341180b1e2f53128e75b543c86)`(DateTime value)` 

Convert DateTime to `block_timestamp_type` (half-seconds since a different epoch)

#### Parameters
* `value` date to convert

#### Returns

##### `public static DateTime ` [`BlockTimestampToDate`](#class_eos_sharp_1_1_core_1_1_helpers_1_1_serialization_helper_1a004b7c9cc14fb75cfe80891c316f464d)`(UInt32 slot)` 

Convert `block_timestamp_type` (half-seconds since a different epoch) to DateTime.

#### Parameters
* `slot` block_timestamp slot to convert

#### Returns

##### `public static UInt64 ` [`ConvertNameToLong`](#class_eos_sharp_1_1_core_1_1_helpers_1_1_serialization_helper_1a20bb129c87aa0f1b1e1be00d6a175556)`(string name)` 

Convert Name into unsigned long.

#### Parameters
* `name` 

#### Returns
Converted value

##### `public static byte[] ` [`ConvertNameToBytes`](#class_eos_sharp_1_1_core_1_1_helpers_1_1_serialization_helper_1a70509f33a8c6f936a575d5d39af62a15)`(string name)` 

Convert Name into bytes.

#### Parameters
* `name` 

#### Returns
Converted value bytes

##### `public static string ` [`ReverseHex`](#class_eos_sharp_1_1_core_1_1_helpers_1_1_serialization_helper_1add51ded0a7538be5ff80038ac5df89fc)`(string h)` 

##### `public static string ` [`ConvertULongToName`](#class_eos_sharp_1_1_core_1_1_helpers_1_1_serialization_helper_1aacf360f56c366a92fa182f6505192cae)`(ulong binary)` 

Convert uint64_t into EOSIO name.

#### Parameters
* `binary` 

#### Returns
EOSIO Name

