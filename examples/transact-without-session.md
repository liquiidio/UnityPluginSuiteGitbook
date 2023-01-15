# Transact (without Session)

1. To make a transaction without a session, create a method and pass an EosSharp Action-Object to it.
2. Call `await AnchorLink.Transact(new TransactArgs(){Action = action)` to attempt the transaction.
3. When this method is called from your UI or another script, the Transport will show a prompt and request the user to open AnchorWallet to log in and then sign a transaction containing the Action passed.

```csharp
internal async Task TransactWithoutSession(EosSharp.Core.Api.v1.Action action)
{
	var transactResult = await myLink.Transact(new TransactArgs() { Action = action });
	Debug.Log($"Transaction broadcast! {transactResult.Processed}");
}
```
