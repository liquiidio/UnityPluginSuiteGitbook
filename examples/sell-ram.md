# Sell ram

1. The following example shows how a Sell Ram Action can be created and passed to the Sign-Method.

```csharp
      async Task SellRam(string sellRamAmount )
      {
          //Create an action object
          var action = new EosSharp.Core.Api.v1.Action()
          {
              account = "eosio",
              name = "sellram",
              authorization = new List<PermissionLevel>() { _session.Auth },
              data = new Dictionary<string, object>
              {
                  { "account", "............1" },
                  { "bytes", sellRamAmount }
              }
          };
		
	  // Sign with the action created
	  var transactResult = await LinkSession.Transact(new TransactArgs() { Action = action });
	}
```
