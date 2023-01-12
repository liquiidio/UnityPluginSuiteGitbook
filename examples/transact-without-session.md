# Transact (without Session)

**Transact (without Session)**

1. To transact without a Session, create a Method and pass a EosSharp Action-Object to it.
2. Call await AnchorLink.Transact(new TransactArgs(){Action = action); to transact.
3. When this Method is called from your UI or other Code, the Transport will show and Ask the User to Open Anchor to Login and afterwards to Sign a Transaction containing the Action passed.

```csharp
internal async Task TransactWithoutSession(EosSharp.Core.Api.v1.Action action)
{
	var transactResult = await myLink.Transact(new TransactArgs() { Action = action });
	Debug.Log($"Transaction broadcast! {transactResult.Processed}");
}
```
