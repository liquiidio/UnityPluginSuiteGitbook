---
cover: ../../.gitbook/assets/UNITY3DxWAX-1920x360_Devs_03.png
coverY: 0
---

# Quick Start

1. Create a new script inheriting from MonoBehaviour
2. Add a member of type CloudWalletPlugin as well as a string to store the name of the user that is logged in.
3. In the Start-method, instantiate/initialize the CloudWalletPlugin.
4. Assign the EventHandlers/Callbacks allowing the CloudWalletPlugin to notify your Script about events and related Data
5. Initialize the CloudWalletPlugin. This will start the communication with the Browser and create the binding between your local script and the wax-js running in the Browser.

```csharp
private CloudWalletPlugin _cloudWalletPlugin;
public string Account { get; private set; }

public void Start()
{
	// Instantiate the WaxCloudWalletPlugin
	_cloudWalletPlugin= new GameObject(nameof(CloudWalletPlugin )).AddComponent<CloudWalletPlugin >();
	
	// Assign Event-Handlers/Callbacks
	_cloudWalletPlugin.OnLoggedIn += (loginEvent) =>
	{
		Account = loginEvent.Account;
		Debug.Log($"{loginEvent.Account} Logged In");
	};
	
	_cloudWalletPlugin.OnError += (errorEvent) =>
	{
		Debug.Log($"Error: {errorEvent.Message}");
	};
	
	_cloudWalletPlugin.OnTransactionSigned += (signEvent) =>
	{
		Debug.Log($"Transaction signed: {JsonConvert.SerializeObject(signEvent.Result)}");
	};
	
	// Inititalize the WebGl binding while passign the RPC-Endpoint of your Choice
	_cloudWalletPlugin.InitializeWebGl("https://wax.greymass.com");
	// NOTE! For other Build Targets you will need to call the related initialize Methods 
	// allowing to provide the necessary parameters needed for Mobile or Desktop-Builds
}
```
