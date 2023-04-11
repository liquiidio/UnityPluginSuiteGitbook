# class `WaxCloudWalletPlugin` 

```
class WaxCloudWalletPlugin::MonoBehaviour
```

Main-class wrapping WAX Clout Wallet functionallity in a Unity MonoBehaviour

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public bool` `IsInitialized` | Boolean signaling if the plugin was initialized
`public bool` `IsLoggedIn` | Boolean signaling if a User is logged in
`public string` `Account` | String containing the AccountName of the logged-in User if a user is logged in
`public Action<WcwInitEvent>` `OnInit` | Event invoked when WaxJs was initialized
`public Action<WcwLoginEvent>` `OnLoggedIn` | Event invoked when a User successfully logged in
`public Action<WcwSignEvent>` `OnTransactionSigned` | Event invoked when a transaction was signed
`public Action<WcwLogoutEvent>` `OnLoggedIn` | Event invoked when a User logged out
`public Action<WcwErrorEvent>` `OnError` | Event invoked when an Error occured
`public Action<WcwCreateInfoEvent>` `OnInfoCreated` | Event invoked when CreateInfo was called successfully

## Members

##### `public bool IsInitialized `

Boolean signaling if the plugin was initialized

##### `public bool IsLoggedIn `

Boolean signaling if a User is logged in


##### `public string Account `

String containing the AccountName of the logged-in User if a user is logged in

## Events

##### `public Action<WcwInitEvent> OnInit` 

Event invoked when WaxJs was initialized

Example:

```cpp
_waxCloudWalletPlugin.OnInit += (initEvent) =>
{
    Debug.Log("WaxJs Initialized");
};
```

##### `public Action<WcwLoginEvent> OnLoggedIn`

Event invoked when a User successfully logged in

Example:

```cpp
_waxCloudWalletPlugin.OnLoggedIn += (loginEvent) =>
{
    Account = loginEvent.Account;
    Debug.Log($"{loginEvent.Account} Logged In");
};
```

##### `public Action<WcwSignEvent> OnTransactionSigned` 

Event invoked when a transaction was signed

Example:

```cpp
_waxCloudWalletPlugin.OnTransactionSigned += (signEvent) =>
{
    Debug.Log($"Transaction signed: {JsonConvert.SerializeObject(signEvent.Result)}");
};
```

##### `public Action<WcwLogoutEvent> OnLoggedIn` 

Event invoked when a User logged out

Example:

```cpp
_waxCloudWalletPlugin.OnLoggedIn += (loginEvent) =>
{
    Account = loginEvent.Account; // class-Level variable
    Debug.Log($"{loginEvent.Account} Logged In");
};
```

##### `public Action<WcwErrorEvent> OnError` 

Event invoked when an Error occured

Example:

```cpp
_waxCloudWalletPlugin.OnError += (errorEvent) =>
{
  Debug.Log($"An Error occured: {errorEvent.Message}");
};
```

##### `public Action<WcwCreateInfoEvent> OnInfoCreated` 

Event invoked when CreateInfo was called successfully

Example:

```cpp
_waxCloudWalletPlugin.OnInfoCreated += (infoCreatedEvent) =>
{
  Debug.Log($"CreateInfoResult: {JsonConvert.SerializeObject(infoCreatedEvent.Result)}");
};
```

## Methods

##### `public void InitializeWebGl(string rpcAddress, bool tryAutoLogin = true, string userAccount = null, string pubKeys = null, string apiSigner = null, string eosApiArgs = null, bool freeBandwidth = true, bool feeFallback = true, string verifyTx = null, string metricsUrl = null, bool returnTempAccounts = false)
            
Initialize the Cloud Wallet Plugin for WebGL, see [`WaxJs on Github`]([AnchorLinkSharp--IdentifyResult.md](https://github.com/worldwide-asset-exchange/waxjs)) for more information

Has no Effect on other Build-Targets.

RECOMMENDED Way to use this Plugin

Example:

```cpp
#if UNITY_WEBGL
   _waxCloudWalletPlugin.InitializeWebGl("https://wax.greymass.com");
#endif
```

#### Parameters
* `rpcAddress` The WAX public node API endpoint URL you wish to connect to. Required
 
* `tryAutoLogin` Always attempt to autologin when your dapp starts up. Default true
 
* `userAccount` User account to start up with. Optional
 
* `pubKeys` Public keys for the userAccount manually specified above. Optional.
 
* `apiSigner` Custom signing logic. Note that free bandwidth will not be provided to custom signers. Default Optional
 
* `eosApiArgs` Custom eosjs constructor arguments to use when instantiating eosjs. Optional
 
* `freeBandwidth` Request bandwidth management from WAX. Default true
 
* `feeFallback` Add wax fee action if user exhausted their own bandwidth, the free boost. Default true
 
* `verifyTx` IGNORED
 
* `metricsUrl` used by WAXIO to gather metrics about failed transaction, times it takes to load a transaction. Default Optional
 
* `returnTempAccounts` using this flag will return temporary accounts or accounts that have signed up for a cloud wallet but not paid the introduction fee to get a blockchain account created. When this is set to true, using the doLogin function will return blockchain account name that may not exist in the blockchain but it will also return an extra boolean flag called isTemp. If this flag is true it is a temporary account, it does not exist in the blockchain yet. If this constructor option is false then only accounts which have been activated and have a blockchain account will be returned.


##### `public void InitializeDesktop(uint localPort, string wcwSigningWebsiteUrl, bool hostLocalWebsite = true, string indexHtmlDataPath = null, string waxJsDataPath = null) 

Initialize the Cloud Wallet Plugin for use on Desktops (Windows, MAC, Linux)

Has no Effect on other Build-Targets. Useful for local debugging.

**USAGE NOT RECOMMENDED** in Production as it uses a local HttpListener and works with Localhost instead of a real domain while usage of a real domain is supported but comes with security risks

Example:

```cpp
#if UNTIY_ANDROID || UNITY_IOS
   _waxCloudWalletPlugin.InitializeDesktop(1234, "http://127.0.0.1:1234/index.html");
#endif
```

#### Parameters
* `localPort` The Port to be used in the HttpListener

* `wcwSigningWebsiteUrl` NOT RECOMMENDED. Allows the Usage of a website/domain instead of localhost, website needs to contain the custom methods from the custom index.html to make Callbacks to the UnityClient. Choosing this options comes with great security risks. Optional.

* `hostLocalWebsite` Default true - set to false if a website/domain should be used instead. Optional.

* `indexHtmlDataPath` Allows to provide a custom path to the index.html to be hosted via the HttpListener on the local device. Optional.

* `waxJsDataPath` Allows to provide a custom path to the waxjs.js-file to be hosted via the HttpListener on the local device. Optional.



##### `public void InitializeMobile(uint localPort, string wcwSigningWebsiteUrl, bool hostLocalWebsite = true, string indexHtmlString = null, string waxJsString = null)` 

Initialize the Cloud Wallet Plugin for Mobile (Android, iOS)

Has no Effect on other Build-Targets. Useful for local debugging and as temporary Solution until Wax Cloud Wallet updates for a better and more secure integration are implemented.

**USAGE NOT RECOMMENDED** in Production as it uses a local HttpListener and works with Localhost instead of a real domain while usage of a real domain is supported but comes with security risks

Uses *Android Chrome Custom Tabs* and *iOS SFSafariViewController* to visualize the Interaction with the WAX Cloud Wallet.

UniversalSDK ([`Github-Link`](https://github.com/coolishbee/universal-sdk-unity) [`Github-AssetStore-Link`](https://assetstore.unity.com/packages/tools/integration/universal-sdk-204843)) needs to be installed for Mobile support

Example:

```cpp
#if UNTIY_ANDROID || UNITY_IOS
    _waxCloudWalletPlugin.InitializeMobile(1234, "http://127.0.0.1:1234/index.html", true, indexHtmlString, waxJsString);
#endif
```

#### Parameters
* `localPort` The Port to be used in the HttpListener

* `wcwSigningWebsiteUrl` **NOT RECOMMENDED**. Allows the Usage of a website/domain instead of localhost, website needs to contain the custom methods from the custom index.html to make Callbacks to the UnityClient. Choosing this options comes with great security risks. Optional.

* `hostLocalWebsite` Default true - set to false if a website/domain should be used instead. Optional.

* `indexHtmlString` Allows to provide a custom index.html-file as string to be hosted via the HttpListener on the local device. Needs to be provided as string due to encryption and compression on Mobile Devices. Optional.

* `waxJsString` Allows to provide a custom waxjs.js-file as string to be hosted via the HttpListener on the local device. Needs to be provided as string due to encryption and compression on Mobile Devices. Optional.
