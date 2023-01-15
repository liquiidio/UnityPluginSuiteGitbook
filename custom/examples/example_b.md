# Login

**Login**

1. Add a method calling the Login(identifier)-Method of the [previously instantiated AnchorLink](https://liquiidio.gitbook.io/unity-plugin-suite/v/anchorlink/examples/example_a).
2. When this method is called from your UI, the Transport will show and request the user to open AnchorWallet to log in.
3. After succesfully logging in, data about the account selected and additional session-data is returned to your application and is available for use within the session-variable returned.
4. Storing the session will allow you to to prompt the user with a Transaction-Request without the user having to log in again.

```csharp

internal LinkSession mySession;
internal async Task LoginAndStoreSession()
{
	try
	{
		var loginResult = await myLink.Login(Identifier);
		mySession = loginResult.Session;
		Debug.Log($"{mySession.Auth.actor} logged-in");
	}
	catch (Exception ex)
	{
		Debug.LogError(ex.Message);
	}
}
```
