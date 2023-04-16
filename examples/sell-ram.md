---
cover: ../.gitbook/assets/UNITY3DxWAX-1920x360_Devs_03.png
coverY: 0
---

# Sell Ram

1. The following example shows how a Sell Ram Action can be created and passed to the Sign-Method of [the previously](https://liquiidio.gitbook.io/unity-plugin-suite/v/wcwunity/examples/example\_a) initialized CloudWalletPlugin-Object.

```csharp
// sell ram using a session
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
    _cloudWalletPlugin.Sign(new[] { action });
}
```
