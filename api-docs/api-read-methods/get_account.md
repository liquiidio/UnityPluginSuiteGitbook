# GetAccount

**GetAccount**\
****Returns an object containing various details about a specific account on the blockchain.



```csharp
var result = await eos.GetAccount("myaccountname");
```

Returns:

```csharp
class GetAccountResponse
{
    string account_name;
    UInt32 head_block_num;
    DateTime head_block_time;
    bool privileged;
    DateTime last_code_update;
    DateTime created;
    Int64 ram_quota;
    Int64 net_weight;
    Int64 cpu_weight; 
    Resource net_limit; 
    Resource cpu_limit;
    UInt64 ram_usage;
    List<Permission> permissions;
    RefundRequest refund_request;
    SelfDelegatedBandwidth self_delegated_bandwidth;
    TotalResources total_resources;
    VoterInfo voter_info;
}
```
