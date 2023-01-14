# Transact

1. Transacting/Signing Transactions with the Wax Cloud Wallet Plugin is as simple as calling the Sign-Method on [the previously](https://liquiidio.gitbook.io/unity-plugin-suite/v/wcwunity/examples/example_a) initialized WaxCloudWalletPlugin-instance while passing a EosSharp Action Object.
2. To be able to perform a transaction, a user needs to [login](https://liquiidio.gitbook.io/unity-plugin-suite/v/wcwunity/examples/example_b) first. Once a user has been logged in, the Plugin will automatically use the the logged in user to sign transactions.
3. Once the Sign-Method is called (while a user has previously logged in and a valid Action Object has been passed) the user will automatically be prompted with the typical Wax Cloud Authentication and Signing-Scheme.
4. If "Auto-Signing" is enabled, transactions will be signed automatically.
5. Immediately a Transaction-Signing is successful, the OnTransactionSigned-Handler will be called (see the [Quick-Start](https://liquiidio.gitbook.io/unity-plugin-suite/v/wcwunity/examples/example_a) example)
6. If an error occurs, the OnError-Handler will be called (see the [Quick-Start] (https://liquiidio.gitbook.io/unity-plugin-suite/v/wcwunity/examples/example_a) example)

```csharp
public void Transact(EosSharp.Core.Api.v1.Action action)
{
	_waxCloudWalletPlugin.Sign(new[] { action });
}
```
