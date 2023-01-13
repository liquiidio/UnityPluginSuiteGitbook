**GetTableRows** call
* Json
* Code - accountName of the contract to search for table rows
* Scope - scope text segmenting the table set
* Table - table name 
* TableKey - unused so far?
* LowerBound - lower bound for the selected index value
* UpperBound - upper bound for the selected index value
* KeyType - Type of the index choosen, ex: i64
* Limit
* IndexPosition - 1 - primary (first), 2 - secondary index (in order defined by multi_index), 3 - third index, etc
* EncodeType - dec, hex
* Reverse - reverse result order
* ShowPayer - show ram payer

```csharp
var result = await eos.GetTableRows(new GetTableRowsRequest() {
    json = true,
    code = "eosio.token",
    scope = "EOS",
    table = "stat"
});
```

Returns:

```csharp
class GetTableRowsResponse
{
    List<object> rows
    bool?        more
}
```

Using generic type

```csharp
/*JsonProperty helps map the fields from the api*/
public class Stat
{
    public string issuer { get; set; }
    public string max_supply { get; set; }
    public string supply { get; set; }
}

var result = await Eos.GetTableRows<Stat>(new GetTableRowsRequest()
{
    json = true,
    code = "eosio.token",
    scope = "EOS",
    table = "stat"
});
```

Returns:

```csharp
class GetTableRowsResponse<Stat>
{
    List<Stat> rows
    bool?      more
}
```
