# Login

**Login**

1. Logging in to the Wax Cloud Wallet Plugin is as simple as calling the Login-Method on [the previously](https://liquiidio.gitbook.io/unity-plugin-suite/v/wcwunity/examples/example_a) initialized WaxCloudWalletPlugin-instance.
2. Once Login() is called, the User will be prompted with the standard Wax Cloud Wallet Login prompt and is requested to follow the typical Login/Authentication-Scheme.

```csharp
public void Login()
{
	_waxCloudWalletPlugin.Login();
}
```
