---
cover: ../.gitbook/assets/UNITY3DxWAX-1920x360_Devs_03.png
coverY: 0
---

# Bid Name

1. The following example shows how a bid name Action can be created and passed to the Sign-Method of [the previously](https://liquiidio.gitbook.io/unity-plugin-suite/v/wcwunity/examples/example\_a) initialized WaxCloudWalletPlugin-Object.

<pre class="language-csharp"><code class="lang-csharp">// bid name using a session
async Task BidName(string nameToBid , string bidAmount )
{
<strong>    //Create an action object
</strong>    var action = new EosSharp.Core.Api.v1.Action()
    {
      account = "eosio",
      name = "bidname",
      authorization = new List&#x3C;PermissionLevel>() { _session.Auth },
      data = new Dictionary&#x3C;string, object>
      {
         { "newname", nameToBid },
         { "bidder", UiToolkitExample.Account },
         { "bid", bidAmount }
      }
    };
		
<strong>    // Sign with the action created
</strong><strong>    _waxCloudWalletPlugin.Sign(new[] { action });
</strong>}
</code></pre>
