# Desktop Installation

Please note that the **USAGE OF THIS PLUGIN ON DESKTOP IS NOT RECOMMENDED** as it uses a local HttpListener and works with localhost instead of a real domain or a real domain with an insecure html-script. Both comes with security risks.



## Configuration

### Component and Events

Add the CloudWalletPlugin-Component to your Script and assign EventHandlers to the individual Events.

```csharp
public void Start()
{
    // Instantiate the WaxCloudWalletPlugin
    _cloudWalletPlugin = new GameObject(nameof(CloudWalletPlugin)).AddComponent<CloudWalletPlugin>();

    // Assign Event-Handlers/Callbacks
    _cloudWalletPlugin.OnLoggedIn += (loginEvent) =>
    {
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

    ... see below ...

}
```



### Initialization

#### Initialization of the CloudWalletPlugin for Desktop-Builds or the use within the Unity Editor

\
The following Examples show different ways to initialize the Plugin for Desktop

#### Local Website hosted from Resources Folder

```csharp
_cloudWalletPlugin.InitializeDesktop(
    // The port the local HttpListener listenes to receive callbacks
    localPort: 1234,
    // the url for the locally hosted index.html interacting with waxjs.js
    cloudWalletSigningWebsiteUrl: "http://127.0.0.1:1234/index.html", 
    // default true, if set to true, loads waxjs.js and index.html 
    // from the local machine and serves them via localhost
    hostLocalWebsite: true
);
```

Initialization while using a locally hosted Website and the index.html and waxjs.js files loaded from the Resources-Folder.\
\
**Important!** \
\- using this in Release Builds and for purposes outside Development is not recommended as it comes with security-risks.&#x20;

\- You need to copy the CloudWallet-Folder containing waxjs.txt (yes, it's txt-file) and index.html from the CloudWalletPackage to your Resources-Folder.

\- With this example the local port needs to match the port used in the cloudWalletSigningWebsiteUrl as it's hosted via the same HttpListener.

\- https is not supported as Unity does not allow to provide a certificate for a HttpListener (which wouldn't work with localhost anyways).

#### Local Website hosted from custom Pathes

```
_cloudWalletPlugin.InitializeDesktop(
    // The port the local HttpListener listenes to receive callbacks
    localPort: 1234,
    // the url for the locally hosted index.html interacting with waxjs.js
    cloudWalletSigningWebsiteUrl: "http://127.0.0.1:1234/index.html", 
    // default true, if set to true, loads waxjs.js and index.html 
    // from the local machine and serves them via localhost
    hostLocalWebsite: true,
    // path to the index.html file
    indexHtmlDataPath: $"{Application.dataPath}\\index.html",
    // path to the waxjs.js file
    waxJsDataPath: $"{Application.dataPath}\\waxjs.js"
);
```

Initialization while using a locally hosted Website while the index.html and waxjs.js files are loaded from a custom path specified by the developer.

**Important!**&#x20;

\- using this in Release Builds and for purposes outside Development is not recommended as it comes with security-risks.&#x20;

\- Text Assets stored outside the Resources Folder will not be included in builds, you need to manually add them to your Build-Output while defining a correct path.



#### Hosted Website (not local)

```
_cloudWalletPlugin.InitializeDesktop(
    // The port the local HttpListener listenes to receive callbacks
    localPort: 1234,
    // the url for the locally hosted index.html interacting with waxjs.js
    cloudWalletSigningWebsiteUrl: "http://mycoolproject.com/index.html", 
    // default true, if set to false opens the Website 
    hostLocalWebsite: false
);
```

**Important!**&#x20;

\- using this in Release Builds and for purposes outside Development is not recommended as it comes with security-risks.&#x20;

\- custom paths will be ignored&#x20;

\- https is not allowed as the local HttpListener can't be a SSL-protected and SSL-protected websites can't communicate with non-SSL-protected HttpListeners

\- the index.html needs to contain the custom javascript-eventlistener you can find in the custom index.html provided [here ](https://github.com/liquiidio/CloudWalletUnity/blob/bbb2c993837ad9da9b956e263126fb9514f7834c/Assets/index.html#L20)and in the upm-package.&#x20;

### Troubleshooting

#### Pop-Ups

Some Browsers block Pop-Ups by default, if you don't see the CloudWallet signing Window popping up when the Browser opens you might need to allow Pop-Ups for the Url you choose in your initialization-call.

#### Debug-Mode

The index.html provided allows to switch between debug and release-mode. Changing the default value (false) to true results in prompts/messageboxes containing helpful information shown when interacting with the CloudWallet. See [here](https://github.com/liquiidio/CloudWalletUnity/blob/upm/Assets/index.html#L18)
