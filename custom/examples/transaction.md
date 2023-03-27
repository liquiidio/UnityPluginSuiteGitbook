# Transact

To perform a generic transaction, do the following (ensure that you have a `User` member assigned as shown [here](https://liquiidio.gitbook.io/unity-plugin-suite/v/universalauthenticatorlibrary/examples/example\_b):

```csharp
public async Task Transact(EosSharp.Core.Api.v1.Action action)
{
    var transactResult = await User.SignTransaction(new []{ action });
}
```
