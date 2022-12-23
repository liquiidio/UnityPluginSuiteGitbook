# class `AnchorLinkTransportSharp::Src::StorageProviders::JsonLocalStorage` 

```
class AnchorLinkTransportSharp::Src::StorageProviders::JsonLocalStorage
  : public ILinkStorage
```

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public ` [`JsonLocalStorage`](#class_anchor_link_transport_sharp_1_1_src_1_1_storage_providers_1_1_json_local_storage_1acd422b563c06c6d247964d7bd7bf236f)`(string prefix)` | 
`public async Task ` [`Write`](#class_anchor_link_transport_sharp_1_1_src_1_1_storage_providers_1_1_json_local_storage_1a85339ebaba72bf321ec33c93ea34d759)`(string key, string data)` | 
`public async Task< string > ` [`Read`](#class_anchor_link_transport_sharp_1_1_src_1_1_storage_providers_1_1_json_local_storage_1a9d488de7ef25a3a8925f1de15b54f721)`(string key)` | 
`public async Task ` [`Remove`](#class_anchor_link_transport_sharp_1_1_src_1_1_storage_providers_1_1_json_local_storage_1a40a452f5353cf5697b8b7fbb94b6dbfb)`(string key)` | 
`private readonly string ` [`_filePath`](#class_anchor_link_transport_sharp_1_1_src_1_1_storage_providers_1_1_json_local_storage_1a9c5d4672eaa53fe0315d5cb3931a64bf) | 
`private async Task< Dictionary< string, string > > ` [`ReadStorage`](#class_anchor_link_transport_sharp_1_1_src_1_1_storage_providers_1_1_json_local_storage_1a793b4e74661a9c64e49de7fdca4be414)`()` | 
`private async Task ` [`WriteStorage`](#class_anchor_link_transport_sharp_1_1_src_1_1_storage_providers_1_1_json_local_storage_1ae97c9bab0ea59906a16f80fcb7112a4a)`(Dictionary< string, string > storage)` | 

## Members

##### `public ` [`JsonLocalStorage`](#class_anchor_link_transport_sharp_1_1_src_1_1_storage_providers_1_1_json_local_storage_1acd422b563c06c6d247964d7bd7bf236f)`(string prefix)` 

##### `public async Task ` [`Write`](#class_anchor_link_transport_sharp_1_1_src_1_1_storage_providers_1_1_json_local_storage_1a85339ebaba72bf321ec33c93ea34d759)`(string key, string data)` 

##### `public async Task< string > ` [`Read`](#class_anchor_link_transport_sharp_1_1_src_1_1_storage_providers_1_1_json_local_storage_1a9d488de7ef25a3a8925f1de15b54f721)`(string key)` 

##### `public async Task ` [`Remove`](#class_anchor_link_transport_sharp_1_1_src_1_1_storage_providers_1_1_json_local_storage_1a40a452f5353cf5697b8b7fbb94b6dbfb)`(string key)` 

##### `private readonly string ` [`_filePath`](#class_anchor_link_transport_sharp_1_1_src_1_1_storage_providers_1_1_json_local_storage_1a9c5d4672eaa53fe0315d5cb3931a64bf) 

##### `private async Task< Dictionary< string, string > > ` [`ReadStorage`](#class_anchor_link_transport_sharp_1_1_src_1_1_storage_providers_1_1_json_local_storage_1a793b4e74661a9c64e49de7fdca4be414)`()` 

##### `private async Task ` [`WriteStorage`](#class_anchor_link_transport_sharp_1_1_src_1_1_storage_providers_1_1_json_local_storage_1ae97c9bab0ea59906a16f80fcb7112a4a)`(Dictionary< string, string > storage)` 

