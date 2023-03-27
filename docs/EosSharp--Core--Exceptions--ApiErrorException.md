# ApiErrorException

```
class EosSharp::Core::Exceptions::ApiErrorException
  : public Exception
```

Wrapper exception for EOSIO api error.

## Summary

| Members                                                                                                                                                                                                                                                         | Descriptions |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ |
| `public int` [`code`](EosSharp--Core--Exceptions--ApiErrorException.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_exceptions\_1\_1\_api\_error\_exception\_1a45a5b7c00a796a23f01673cef1dbe0a9)                                                                        |              |
| `public string` [`message`](EosSharp--Core--Exceptions--ApiErrorException.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_exceptions\_1\_1\_api\_error\_exception\_1ae1ed0d7a6f352c7ee3ad978429822c6f)                                                                  |              |
| `public` [`ApiError`](EosSharp--Core--Exceptions--ApiError.md) `` [`error`](EosSharp--Core--Exceptions--ApiErrorException.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_exceptions\_1\_1\_api\_error\_exception\_1a63c6b67d0b89e363f1c70831c3372fa3)                  |              |
| `public` [`ApiErrorException`](EosSharp--Core--Exceptions--ApiErrorException.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_exceptions\_1\_1\_api\_error\_exception\_1aa7584896f0dc3199992e8a6b4101620c)`()`                                                           |              |
| `public` [`ApiErrorException`](EosSharp--Core--Exceptions--ApiErrorException.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_exceptions\_1\_1\_api\_error\_exception\_1a9523e8f3f6f9a6474b0c96b5bdf822dd)`(SerializationInfo info, StreamingContext context)`           |              |
| `public override void` [`GetObjectData`](EosSharp--Core--Exceptions--ApiErrorException.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_exceptions\_1\_1\_api\_error\_exception\_1a414726cd81ae10ed0870e3307d1e76b7)`(SerializationInfo info, StreamingContext context)` |              |

## Members

**`public int`** [**`code`**](EosSharp--Core--Exceptions--ApiErrorException.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_exceptions\_1\_1\_api\_error\_exception\_1a45a5b7c00a796a23f01673cef1dbe0a9)

**`public string`** [**`message`**](EosSharp--Core--Exceptions--ApiErrorException.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_exceptions\_1\_1\_api\_error\_exception\_1ae1ed0d7a6f352c7ee3ad978429822c6f)

**`public`** [**`ApiError`**](EosSharp--Core--Exceptions--ApiError.md) **``** [**`error`**](EosSharp--Core--Exceptions--ApiErrorException.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_exceptions\_1\_1\_api\_error\_exception\_1a63c6b67d0b89e363f1c70831c3372fa3)

**`public`** [**`ApiErrorException`**](EosSharp--Core--Exceptions--ApiErrorException.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_exceptions\_1\_1\_api\_error\_exception\_1aa7584896f0dc3199992e8a6b4101620c)**`()`**

**`public`** [**`ApiErrorException`**](EosSharp--Core--Exceptions--ApiErrorException.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_exceptions\_1\_1\_api\_error\_exception\_1a9523e8f3f6f9a6474b0c96b5bdf822dd)**`(SerializationInfo info, StreamingContext context)`**

**`public override void`** [**`GetObjectData`**](EosSharp--Core--Exceptions--ApiErrorException.md#class\_eos\_sharp\_1\_1\_core\_1\_1\_exceptions\_1\_1\_api\_error\_exception\_1a414726cd81ae10ed0870e3307d1e76b7)**`(SerializationInfo info, StreamingContext context)`**
