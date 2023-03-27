# Vote

1. The following example shows how a Vote Action can be created and passed to the Sign-Method of [the previously](https://liquiidio.gitbook.io/unity-plugin-suite/v/wcwunity/examples/example\_a) initialized WaxCloudWalletPlugin-Object.

```csharp
// vote using a session
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
		
      // Sign with the created action
      _waxCloudWalletPlugin.Sign(new[] { action });
}
```
