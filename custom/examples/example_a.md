# Quick Start

**Quick Start**

1. Create a new Script inheriting from MonoBehaviour
2. Add a Member of Type WaxCloudWalletPlugin as well as a string to store the Name of the Logged in User
3. Create the Start-Method and instantiate/initialize the CloudWalletPlugin as follows 4. Instantiate the WaxCloudWalletPlugin as seen below 5. Assign the EventHandlers/Callbacks allowing the CloudWalletPlugin to notify your Script about events and related Data 6. Initialize the CloudWalletPlugin. This will start the communication with the Browser and create the binding between your local script and the wax-js running in the Browser.

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
