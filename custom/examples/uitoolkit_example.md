# UIToolkit Example

1. In a Unity scene, add the UiToolkit authenticator handler prefab i.e. [UIToolkit](https://github.com/liquiidio/UniversalAuthenticatorLibrarySharp/blob/upm\_full/Src/UiToolkit/Prefabs/UnityUiToolkitUAL.prefab) .
2. Add the specific [authenticators](https://github.com/liquiidio/UniversalAuthenticatorLibrarySharp/tree/upm\_full/Src/Authenticators) that will be used e.g. [AnchorWallet](https://github.com/liquiidio/UniversalAuthenticatorLibrarySharp/tree/upm\_full/Src/Authenticators/Anchor/Prefabs) or [WAX Cloud Wallet](https://github.com/liquiidio/UniversalAuthenticatorLibrarySharp/tree/upm\_full/Src/Authenticators/WaxCloudWallet/Prefabs) as prefabs to the scene and specify them in the handler that was added in Step 1.
3. Create a new script inheriting from MonoBehaviour, add a public member of type `UnityUiToolkitUAL` and assign it in the editor.
4. In the Start-method, instantiate/initialize the respective handler prefab added above and add an action when the user login is successful.

**N.B. Ensure that you assign an event handler/callback for the login (** `UnityUiToolkitUAL.OnUserLogin += MyLoginCallback;`**) to get the `User` object. Click** [**here**](https://liquiidio.gitbook.io/unity-plugin-suite/v/universalauthenticatorlibrary/examples/example\_b) **for more information.**

#### UiToolkit

```csharp
   UnityUiToolkitUAL.OnUserLogin += UserLogin;
   await UnityCanvasUAL.Init();
```
