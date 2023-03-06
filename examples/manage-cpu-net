   // manage CPU/NET using a session
      async Task Stake(List<string> producers)
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
