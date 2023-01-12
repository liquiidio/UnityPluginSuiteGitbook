# Transact

**Transact**

1. Transacting/Signing Transactions with the Wax Cloud Wallet Plugin is as simple as calling the Sign-Method on the previously initialized WaxCloudWalletPlugin-instance while passing a EosSharp Action Object.
2. To be able to Transact, a User needs to Login first (see Login Example). Once a User has been Logged in, the Plugin will automatically use the the logged-in User to sign Transactions.
3. Once Sign()-Method is called (while a user has previously logged in and while passing a valid Action Object) the User will automatically be prompted with the typical Wax Cloud Authentication and Signing-Flow.
4. If Auto-Signing is enabled, Transactions will be signed automatically.
5. On Successfull Transaction-Signing, the OnTransactionSigned-Handler will be called (see the Quick-Start Example)
6. If an Error occurs, the OnError-Handler will called (see the Quick-Start Example)

```csharp
public void Transact(EosSharp.Core.Api.v1.Action action)
{
	_waxCloudWalletPlugin.Sign(new[] { action });
}
```
