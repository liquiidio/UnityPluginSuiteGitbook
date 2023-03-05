# bid name

1. The following example shows how a bid name Action can be created and passed to the Sign-Method.

```csharp
      async Task BidName(string nameToBid , string bidAmount )
      {
          //Create an action object
          var action = new EosSharp.Core.Api.v1.Action()
          {
              account = "eosio",
              name = "bidname",
              authorization = new List<PermissionLevel>() { _session.Auth },
              data = new Dictionary<string, object>
              {
                 { "newname", nameToBid },
                 { "bidder", UiToolkitExample.Account },
                 { "bid", bidAmount }
              }
          };
		
	  // Sign with the action object created
	  await LinkSession.Transact(new TransactArgs() { Action = action });
	}
```
