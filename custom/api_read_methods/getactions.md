- **GetActions** call
    * accountName - accountName to get actions history
    * pos - a absolute sequence positon -1 is the end/last action
    * offset - the number of actions relative to pos, negative numbers return [pos-offset,pos), positive numbers return [pos,pos+offset)

```csharp
var result = await eos.GetActions("myaccountname", 0, 10);
```

Returns:

```csharp
class GetActionsResponse
{
    List<GlobalAction> actions;
    UInt32 last_irreversible_block;
    bool time_limit_exceeded_error;
}
```
