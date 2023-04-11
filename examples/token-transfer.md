---
cover: ../.gitbook/assets/UNITY3DxWAX-1920x360_Devs_03.png
coverY: 0
---

# Token Transfer

1. The following example shows how a Token Transfer Action can be created and passed to the Sign-Method of [the previously](https://liquiidio.gitbook.io/unity-plugin-suite/v/wcwunity/examples/example\_a) initialized WaxCloudWalletPlugin-Object.

<pre class="language-csharp"><code class="lang-csharp">// transfer tokens using a session
private async Task Transfer(string frmAcc, string toAcc, string qnty, string memo)
{
    var action = new EosSharp.Core.Api.v1.Action()
    {
      account = "eosio.token",
      name = "transfer",
      authorization = new List&#x3C;PermissionLevel>() { _session.Auth },
      data = new Dictionary&#x3C;string, object>
      {
          {"from", frmAcc},
          {"to", toAcc},
          {"quantity", qnty},
          {"memo", memo}
      }
    };
		
    // Sign 
<strong>    _waxCloudWalletPlugin.Sign(new[] { action });
</strong>}
</code></pre>
