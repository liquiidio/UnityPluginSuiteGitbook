# Transact (with Session)

**Transact (with Session)**

1. To transact without a Session, create a Method and pass a EosSharp Action-Object to it.
2. Call await LinkSession.Transact(new TransactArgs(){Action = action); to transact.
3. When this Method is called from your UI or other Code, the Transport will show and Ask the User to Sign a Transaction containing the Action passed (without requiring the User to Login again).

```csharp
internal async Task TransactWithoutSession(EosSharp.Core.Api.v1.Action action)
{
	var transactResult = await mySession.Transact(new TransactArgs() { Action = action });
	Debug.Log($"Transaction broadcast! {transactResult.Processed}");
}
```
