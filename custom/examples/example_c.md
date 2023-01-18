# Transfer tokens

To perform a transfer action, do the following (ensure that you have a `User` member assigned as shown [here](https://liquiidio.gitbook.io/unity-plugin-suite/v/universalauthenticatorlibrary/examples/example_b):

```csharp
   public async Task Transfer(string frmAcc, string toAcc, string qnty, string memo)
        {
            var action = new EosSharp.Core.Api.v1.Action
            {
                account = "eosio.token",
                name = "transfer",
                authorization = new List<PermissionLevel>
                {
                    new PermissionLevel()
                    {
                        actor =
                            "............1", // ............1 will be resolved to the signing accounts permission
                        permission =
                            "............2" // ............2 will be resolved to the signing accounts authority
                    }
                },

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
                await user.SignTransaction(new[] {action});
            }
            catch (Exception e)
            {
                Debug.Log(e);
                throw;
            }
        }
```
