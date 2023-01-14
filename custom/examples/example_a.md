# Quick Start

1. Create a new script inheriting from MonoBehaviour
2. Add a member of type WaxCloudWalletPlugin as well as a string to store the name of the user that is logged in.
3. In the Start-method, instantiate/initialize the CloudWalletPlugin.
4. Assign the EventHandlers/Callbacks allowing the CloudWalletPlugin to notify your Script about events and related Data 
5. Initialize the CloudWalletPlugin. This will start the communication with the Browser and create the binding between your local script and the wax-js running in the Browser.

```csharp
private WaxCloudWalletPlugin _waxCloudWalletPlugin;
public string Account { get; private set; }

public void Start()
{
	// Instantiate the WaxCloudWalletPlugin
	_waxCloudWalletPlugin = new GameObject(nameof(WaxCloudWalletPlugin)).AddComponent<WaxCloudWalletPlugin>();

	// Assign Event-Handlers/Callbacks
	_waxCloudWalletPlugin.OnLoggedIn += (loginEvent) =>
	{
		Account = loginEvent.Account;
		Debug.Log($"{loginEvent.Account} Logged In");
	};

	_waxCloudWalletPlugin.OnError += (errorEvent) =>
	{
		Debug.Log($"Error: {errorEvent.Message}");
	};

	_waxCloudWalletPlugin.OnTransactionSigned += (signEvent) =>
	{
		Debug.Log($"Transaction signed: {JsonConvert.SerializeObject(signEvent.Result)}");
	};
	
	// Inititalize the WebGl binding while passign the RPC-Endpoint of your Choice
	_waxCloudWalletPlugin.InitializeWebGl("https://wax.greymass.com");
}
```
