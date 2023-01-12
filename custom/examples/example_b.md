# Login

**Login**

1. Add a method calling the Login(identifier)-Method of the previously instantiated AnchorLink.
2. When this Method is called from your UI, the Transport will show and Ask the User to Open Anchor to Login.
3. After succesfull Login, data about the Account selected and additional session-data is returned your Application, available for use within the session-variable returned.
4. Storing the Session will allow you to to promt the User with a Transact-Request without the user having to Login again.

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
