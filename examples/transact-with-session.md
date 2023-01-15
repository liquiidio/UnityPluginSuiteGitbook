# Transact (with Session)

1. To transact with a session, create a method and pass an EosSharp Action-Object to it.
2. Call the method `await LinkSession.Transact(new TransactArgs(){Action = action)` to attempt the transaction.
3. When this method is called from your UI or other another script, the Transport will display a prompt and ask the user to sign the transaction containing the Action passed (without requiring the user to log in again).

```csharp
internal async Task TransactWithoutSession(EosSharp.Core.Api.v1.Action action)
{
	var transactResult = await mySession.Transact(new TransactArgs() { Action = action });
	Debug.Log($"Transaction broadcast! {transactResult.Processed}");
}
```
