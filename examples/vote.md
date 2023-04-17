---
cover: ../.gitbook/assets/UNITY3DxWAX-1920x360_Devs_03.png
coverY: 0
---

# Vote

1. The following example shows how a vote Action can be created and passed to the vote-Method using a session.

```csharp
      async Task Vote(List<string> producers)
      {
          //Create an action object
          var action = new EosSharp.Core.Api.v1.Action()
          {
              account = "eosio",
              name = "voteproducer",
              authorization = new List<PermissionLevel>() { _session.Auth },
              data = new Dictionary<string, object>
              {
                  { "voter", "............1" },
                  { "proxy", "coredevproxy" },
                  { "producers", producers.ToArray() }
              }
          };
		
	  // Sign with an action created.
	   _anchorLink.Transact(new TransactArgs() { Action = action }).ContinueWith(transactTask =>
          {
                Debug.Log($"Thank you {transactTask.Result.Signer.actor}");
          });
	}
```
