# Manage CPU/NET

1. The following example shows how to stake CPU/NET Action and pass the created action to the Sign-Method of [the previously](https://liquiidio.gitbook.io/unity-plugin-suite/v/wcwunity/examples/example\_a) initialized WaxCloudWalletPlugin-Object.

<pre class="language-csharp"><code class="lang-csharp">// Stake CPU/NET using a session
async Task Stake(string amountToStakeCPU, string amountToStakeNET  )
{
    //Create an action object
    var action = new EosSharp.Core.Api.v1.Action()
    {
      account = "eosio",
      name = "delegatebw",
      authorization = new List&#x3C;PermissionLevel>() { UiToolkitExample.LinkSession.Auth  },
      data = new Dictionary&#x3C;string, object>
      {
              { "from", "............1" },
              { "receiver", "............1" },
    		      { "stake_cpu_quantity", amountToStakeCPU },
    		      { "stake_net_quantity", amountToStakeNET },
      }
    };
		
    // Sign with the action created
<strong>    _waxCloudWalletPlugin.Sign(new[] { action });
</strong>}
</code></pre>
