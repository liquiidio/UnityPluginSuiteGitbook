# GetInfo

**GetInfo**\
****Returns an object containing various details about the blockchain.



```csharp
var result = await eos.GetInfo();
```

Returns:

```csharp
class GetInfoResponse 
{ 
    string server_version;
    string chain_id;
    UInt32 head_block_num;
    UInt32 last_irreversible_block_num;
    string last_irreversible_block_id;
    string head_block_id;
    DateTime head_block_time;
    string head_block_producer;
    string virtual_block_cpu_limit;
    string virtual_block_net_limit;
    string block_cpu_limit;
    string block_net_limit;
}
```
