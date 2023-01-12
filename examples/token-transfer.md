# Token Transfer

**Token Transfer**

1. Following Example shows how a Token Transfer Action could be created and passed to the Transact-Method using a Session.

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

            try
            {
                var transactResult = await mySession.Transact(new TransactArgs() { Action = action });
                Debug.Log($"Transaction broadcast! {transactResult.Processed}");

                waitCoroutine = StartCoroutine(SwitchPanels(Transport.currentPanel, CustomActionsPanel, 1.5f));

            }
            catch (Exception e)
            {
                Debug.Log(e);
                throw;
            }
        }
```
