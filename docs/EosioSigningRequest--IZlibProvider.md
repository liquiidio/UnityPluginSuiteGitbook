# interface `EosioSigningRequest::IZlibProvider` 

Interface that should be implemented by zlib implementations.

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public byte[] ` [`DeflateRaw`](EosioSigningRequest.md)`(byte[] data)` | Deflate data w/o adding zlib header.
`public byte[] ` [`InflateRaw`](EosioSigningRequest.md)`(byte[] data)` | Inflate data w/o requiring zlib header.

## Members

##### `public byte[] ` [`DeflateRaw`](EosioSigningRequest.md)`(byte[] data)` 

Deflate data w/o adding zlib header.

##### `public byte[] ` [`InflateRaw`](EosioSigningRequest.md)`(byte[] data)` 

Inflate data w/o requiring zlib header.

