# Stake CPU/NET

1. The following example shows how to stake CPU/NET Action is created and passed to the Sign-Method.

```csharp
   // Stake CPU/NET using a session
      async Task Stake(string amountToStakeCPU, string amountToStakeNET  )
      {
          //Create an action object
          var action = new EosSharp.Core.Api.v1.Action()
          {
              account = "eosio",
              name = "delegatebw",
              authorization = new List<PermissionLevel>() { _session.Auth },
              data = new Dictionary<string, object>
              {
                      { "from", "............1" },
                      { "receiver", "............1" },
		      { "stake_cpu_quantity", amountToStakeCPU },
		      { "stake_net_quantity", amountToStakeNET },
              }
          };
		
	  // Sign with the action created
	var transactResult = await LinkSession.Transact(new TransactArgs() { Action = action });
	}
```
