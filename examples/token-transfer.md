# Token Transfer

1. The following example shows how a Token Transfer Action can be created and passed to the Sign-Method of [the previously](https://liquiidio.gitbook.io/unity-plugin-suite/v/wcwunity/examples/example_a) initialized WaxCloudWalletPlugin-Object.

```csharp
   // transfer tokens using a session
      private async Task Transfer(string frmAcc, string toAcc, string qnty, string memo)
      {
          var action = new EosSharp.Core.Api.v1.Action()
          {
              account = "eosio.token",
              name = "transfer",
              authorization = new List<PermissionLevel>() { _session.Auth },
              data = new Dictionary<string, object>
              {
                  {"from", frmAcc},
                  {"to", toAcc},
                  {"quantity", qnty},
                  {"memo", memo}
              }
          };
		
	  // Sign 
	 _waxCloudWalletPlugin.Sign(new[] { action });
	}
```
