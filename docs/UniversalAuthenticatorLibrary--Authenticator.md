# class `UniversalAuthenticatorLibrary::Authenticator` 

```
class UniversalAuthenticatorLibrary::Authenticator
  : public MonoBehaviour
```

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public ` [`Authenticator`](#class_universal_authenticator_library_1_1_authenticator_1ab23c9931185b7d2ed1df846304565bc0)`(` [`Chain`](UniversalAuthenticatorLibrary--Chain.md)` chain, ` [`UALOptions`](UniversalAuthenticatorLibrary--UALOptions.md)` options)` | 
`public virtual void ` [`Init`](#class_universal_authenticator_library_1_1_authenticator_1ad02d0bc6712c0142357ea28c901b540f)`(` [`Chain`](UniversalAuthenticatorLibrary--Chain.md)` chain, ` [`UALOptions`](UniversalAuthenticatorLibrary--UALOptions.md)` options)` | 
`public ` [`ButtonStyle`](UniversalAuthenticatorLibrary--ButtonStyle.md)` ` [`GetStyle`](#class_universal_authenticator_library_1_1_authenticator_1a04a22cff21dcd15b98988b0fe7969afc)`()` | Returns the style of the Button that will be rendered.
`public virtual bool ` [`ShouldRender`](#class_universal_authenticator_library_1_1_authenticator_1a96f5bfb6c43d5aca41afa153d45848a7)`()` | 
`public virtual bool ` [`ShouldAutoLogin`](#class_universal_authenticator_library_1_1_authenticator_1aa6e79d162791d7d72273fc93d99388dd)`()` | Returns whether or not the dapp should attempt to auto login with the Authenticator app. Auto login will only occur when there is only one Authenticator that returns shouldRender() true and shouldAutoLogin() true.
`public uint ` [`ShouldInvalidateAfter`](#class_universal_authenticator_library_1_1_authenticator_1a5af01a96359ca8f539098eef54da4519)`()` | Returns the amount of seconds after the authentication will be invalid for logging in on new browser sessions. Setting this value to zero will cause users to re-attempt authentication on every new browser session. Please note that the invalidate time will be saved client-side and should not be relied on for security.
`public virtual Task< ` [`User`](UniversalAuthenticatorLibrary--User.md)` > ` [`Login`](#class_universal_authenticator_library_1_1_authenticator_1a2a72d1cb495b8c2ef24da6b411a6c4f6)`(string accountName)` | **
`public virtual Task ` [`Logout`](#class_universal_authenticator_library_1_1_authenticator_1a8a97cbd434878195ddb345d3ecc5c6d3)`()` | Logs the user out of the dapp. This will be strongly dependent on each Authenticator app's patterns.
`private uint ` [`defaultInvalidateAfter`](#class_universal_authenticator_library_1_1_authenticator_1a816cf04c4c384c9c4ee110302a57912c)`= 604800` | Default value for shouldInvalidateAfter(), 1 week in seconds
`private ` [`ButtonStyle`](UniversalAuthenticatorLibrary--ButtonStyle.md)` ` [`ButtonStyle`](#class_universal_authenticator_library_1_1_authenticator_1a412d693877e4cb5f89501d2539b8b858) | 
`private ` [`Chain`](UniversalAuthenticatorLibrary--Chain.md)` ` [`Chain`](#class_universal_authenticator_library_1_1_authenticator_1ac5ae30619ab2ecd485d62c4a67082190) | 
`private ` [`UALOptions`](UniversalAuthenticatorLibrary--UALOptions.md)` ` [`Options`](#class_universal_authenticator_library_1_1_authenticator_1a225bcd4e4908f06b1dfadbb0c04821c2) | 

## Members

##### `public ` [`Authenticator`](#class_universal_authenticator_library_1_1_authenticator_1ab23c9931185b7d2ed1df846304565bc0)`(` [`Chain`](UniversalAuthenticatorLibrary--Chain.md)` chain, ` [`UALOptions`](UniversalAuthenticatorLibrary--UALOptions.md)` options)` 

##### `public virtual void ` [`Init`](#class_universal_authenticator_library_1_1_authenticator_1ad02d0bc6712c0142357ea28c901b540f)`(` [`Chain`](UniversalAuthenticatorLibrary--Chain.md)` chain, ` [`UALOptions`](UniversalAuthenticatorLibrary--UALOptions.md)` options)` 

##### `public ` [`ButtonStyle`](UniversalAuthenticatorLibrary--ButtonStyle.md)` ` [`GetStyle`](#class_universal_authenticator_library_1_1_authenticator_1a04a22cff21dcd15b98988b0fe7969afc)`()` 

Returns the style of the Button that will be rendered.

##### `public virtual bool ` [`ShouldRender`](#class_universal_authenticator_library_1_1_authenticator_1a96f5bfb6c43d5aca41afa153d45848a7)`()` 

##### `public virtual bool ` [`ShouldAutoLogin`](#class_universal_authenticator_library_1_1_authenticator_1aa6e79d162791d7d72273fc93d99388dd)`()` 

Returns whether or not the dapp should attempt to auto login with the Authenticator app. Auto login will only occur when there is only one Authenticator that returns shouldRender() true and shouldAutoLogin() true.

##### `public uint ` [`ShouldInvalidateAfter`](#class_universal_authenticator_library_1_1_authenticator_1a5af01a96359ca8f539098eef54da4519)`()` 

Returns the amount of seconds after the authentication will be invalid for logging in on new browser sessions. Setting this value to zero will cause users to re-attempt authentication on every new browser session. Please note that the invalidate time will be saved client-side and should not be relied on for security.

##### `public virtual Task< ` [`User`](UniversalAuthenticatorLibrary--User.md)` > ` [`Login`](#class_universal_authenticator_library_1_1_authenticator_1a2a72d1cb495b8c2ef24da6b411a6c4f6)`(string accountName)` 

**

##### `public virtual Task ` [`Logout`](#class_universal_authenticator_library_1_1_authenticator_1a8a97cbd434878195ddb345d3ecc5c6d3)`()` 

Logs the user out of the dapp. This will be strongly dependent on each Authenticator app's patterns.

##### `private uint ` [`defaultInvalidateAfter`](#class_universal_authenticator_library_1_1_authenticator_1a816cf04c4c384c9c4ee110302a57912c)`= 604800` 

Default value for shouldInvalidateAfter(), 1 week in seconds

##### `private ` [`ButtonStyle`](UniversalAuthenticatorLibrary--ButtonStyle.md)` ` [`ButtonStyle`](#class_universal_authenticator_library_1_1_authenticator_1a412d693877e4cb5f89501d2539b8b858) 

##### `private ` [`Chain`](UniversalAuthenticatorLibrary--Chain.md)` ` [`Chain`](#class_universal_authenticator_library_1_1_authenticator_1ac5ae30619ab2ecd485d62c4a67082190) 

##### `private ` [`UALOptions`](UniversalAuthenticatorLibrary--UALOptions.md)` ` [`Options`](#class_universal_authenticator_library_1_1_authenticator_1a225bcd4e4908f06b1dfadbb0c04821c2) 

