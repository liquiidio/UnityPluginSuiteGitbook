**GetBlock** call
```csharp
var result = await eos.GetBlock("blockIdOrNumber");
```
Returns:
```csharp
class GetBlockResponse
{
    DateTime timestamp;
    string producer;
    UInt32 confirmed;
    string previous;
    string transaction_mroot;
    string action_mroot;
    UInt32 schedule_version;
    Schedule new_producers;
    List<Extension> block_extensions;
    List<Extension> header_extensions;
    string producer_signature;
    List<TransactionReceipt> transactions;
    string id;
    UInt32 block_num;
    UInt32 ref_block_prefix;
}
```
