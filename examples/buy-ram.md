# Buy ram

1. The following example shows how a buy Ram Action can be created and passed to the Sign-Method of [the previously](https://liquiidio.gitbook.io/unity-plugin-suite/v/wcwunity/examples/example_a) initialized WaxCloudWalletPlugin-Object.

```csharp
   // buy ram using a session
      private async Task BuyRam(string amountToBuy, string receiverAccount  )
      {
          var action = new EosSharp.Core.Api.v1.Action()
          {
              account = "eosio",
              name = "buyram",
              authorization = new List<PermissionLevel>() { _session.Auth },
              data = new Dictionary<string, object>
              {
                      { "payer", "............1" },
                      { "quant", amountToBuyTex },
                      { "receiver", receiverAccount }
              }
          };
		
	  // Sign 
	 var transactResult = await LinkSession.Transact(new TransactArgs() { Action = action });
	}
```
