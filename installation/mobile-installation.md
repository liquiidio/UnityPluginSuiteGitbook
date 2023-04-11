---
cover: ../.gitbook/assets/UNITY3DxWAX-1920x360_Devs_03.png
coverY: 0
---

# Mobile Installation

### **UniversalSDK**

The Mobile Installation and Configuration requires an additional third-party Package to be installed\
\- [https://assetstore.unity.com/packages/tools/integration/universal-sdk-204843](https://assetstore.unity.com/packages/tools/integration/universal-sdk-204843)\
\
The **UniversalSDK Package** allows the Application to make use of

* _**Chrome-Custom-Tabs**_ on Android (see [https://developer.chrome.com/docs/android/custom-tabs/](https://developer.chrome.com/docs/android/custom-tabs/) for further information)
* _**SFSafariViewController**_ on iOS ( see h[ttps://developer.apple.com/documentation/safariservices/sfsafariviewcontroller](https://developer.apple.com/documentation/safariservices/sfsafariviewcontroller) for further information)\


### Chrome-Custom-Tabs and the SFSafariViewController

Chrome-Custom-Tabs and the SFSafariViewController will allow the Application to Login to the Wax Cloud Wallet and Sign and Push Transactions/Acions in a secure environment while Cookies are shared between Custom-Tab/SafariViewController-Sessions and the local Browser, minimizing the Security-Risks while increasing the User-Experience.\
\
Apart from above mentioned benefits, the use of these native features allows the removal of specific issues coming with the use of WebViews&#x20;

* Cookie-Problems resulting in having to Login again and again
* no auto-signing
* disallowed user-agents within the WebView resulting in failing OAuth-Authenitcation
* banning of Applications from the AppStore or PlayStore because of usage of disallowed or unsupported user-agents
* banning of Applications from the AppStore or PlayStore because of heavy usage of WebViews (see iOS and Android Guidelines)

### Installation

* Download and install the UniversalSDK ([https://assetstore.unity.com/packages/tools/integration/universal-sdk-204843](https://assetstore.unity.com/packages/tools/integration/universal-sdk-204843)) from the AssetStore&#x20;
* **Follow the Installation-instructions provided in the UniversalSDK- Repository/Package **_**(The Setup is unfortunately not that easy but it's possible and works if it's done right)** We could try to explain the configuration here with our own words but we would never do as well as the author of the package_

_**NOTE!** Builds for other Targets (WebGL, Desktop etc.) will fail if the UniversalSDK is installed, therefore, it is recomended to create_ separate branches for your Mobile-Targets.
