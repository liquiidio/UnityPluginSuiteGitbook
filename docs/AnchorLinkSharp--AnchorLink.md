# class `AnchorLinkSharp::AnchorLink` 

```
class AnchorLinkSharp::AnchorLink
  : public AbiSerializationProvider
```

Main class

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public readonly ` [`ILinkTransport`](.github/workflows/documentation/md/AnchorLinkSharp.md#interface_anchor_link_sharp_1_1_i_link_transport)` ` [`Transport`](#class_anchor_link_sharp_1_1_anchor_link_1aee5fc13a77160e6a524c6ad153299309) | Transport used to deliver requests to the user wallet.
`public readonly string ` [`ChainId`](#class_anchor_link_sharp_1_1_anchor_link_1a13b0e3b911976c623a64c2bd5da0f0d8) | EOSIO ChainID for which requests are valid.
`public readonly ` [`ILinkStorage`](.github/workflows/documentation/md/AnchorLinkSharp.md#interface_anchor_link_sharp_1_1_i_link_storage)` ` [`Storage`](#class_anchor_link_sharp_1_1_anchor_link_1a54bdbcc79b07c68aa3dc1879abd64d43) | PlayerPrefsStorage adapter used to persist sessions.
`public ` [`AnchorLink`](#class_anchor_link_sharp_1_1_anchor_link_1aeaef1002a44d51caeea5ac9cbf3fcfc7)`(` [`ILinkOptions`](.github/workflows/documentation/md/AnchorLinkSharp.md#interface_anchor_link_sharp_1_1_i_link_options)` options)` | Create a new anchorLink instance.
`public async Task< Abi > ` [`GetAbi`](#class_anchor_link_sharp_1_1_anchor_link_1a9d9f8443e4fa6c3d5d5790567f0395f3)`(string account)` | Fetch the ABI for given account, cached.
`public string ` [`CreateCallbackUrl`](#class_anchor_link_sharp_1_1_anchor_link_1af3228312c13fbf438d8f2315ec47ec1d)`()` | Create a new unique buoy callback url.
`public async Task< SigningRequest > ` [`CreateRequest`](#class_anchor_link_sharp_1_1_anchor_link_1a7a825e1a392930afbde7725eec7297ff)`(SigningRequestCreateArguments args, ` [`ILinkTransport`](.github/workflows/documentation/md/AnchorLinkSharp.md#interface_anchor_link_sharp_1_1_i_link_transport)` transport)` | Create a SigningRequest instance configured for this anchorLink.
`public async Task< ` [`TransactResult`](.github/workflows/documentation/md/AnchorLinkSharp--TransactResult.md#class_anchor_link_sharp_1_1_transact_result)` > ` [`SendRequest`](#class_anchor_link_sharp_1_1_anchor_link_1a694674e4b7edcdf8c453232fa71cab9f)`(SigningRequest request, ` [`ILinkTransport`](.github/workflows/documentation/md/AnchorLinkSharp.md#interface_anchor_link_sharp_1_1_i_link_transport)` transport, bool broadcast)` | Send a SigningRequest instance using this anchorLink.
`public async Task< ` [`TransactResult`](.github/workflows/documentation/md/AnchorLinkSharp--TransactResult.md#class_anchor_link_sharp_1_1_transact_result)` > ` [`Transact`](#class_anchor_link_sharp_1_1_anchor_link_1a18a7e254c35f5c402f4bccf340fac893)`(` [`TransactArgs`](.github/workflows/documentation/md/AnchorLinkSharp--TransactArgs.md#class_anchor_link_sharp_1_1_transact_args)` args, ` [`TransactOptions`](.github/workflows/documentation/md/AnchorLinkSharp--TransactOptions.md#class_anchor_link_sharp_1_1_transact_options)` options, ` [`ILinkTransport`](.github/workflows/documentation/md/AnchorLinkSharp.md#interface_anchor_link_sharp_1_1_i_link_transport)` transport)` | Sign and optionally broadcast a EOSIO transaction, action or actions.
`public async Task< ` [`IdentifyResult`](.github/workflows/documentation/md/AnchorLinkSharp--IdentifyResult.md#class_anchor_link_sharp_1_1_identify_result)` > ` [`Identify`](#class_anchor_link_sharp_1_1_anchor_link_1abcf7b8bbe7bcdcf28714aaf9f7ccbae6)`(PermissionLevel requestPermission, object info)` | Send an identity request and verify the identity proof.
`public async Task< ` [`LoginResult`](.github/workflows/documentation/md/AnchorLinkSharp--LoginResult.md#class_anchor_link_sharp_1_1_login_result)` > ` [`Login`](#class_anchor_link_sharp_1_1_anchor_link_1ab7be810b454e3488fe61cb53e6f9240c)`(string identifier)` | Login and create a persistent session.
`public async Task< ` [`LinkSession`](.github/workflows/documentation/md/AnchorLinkSharp--LinkSession.md#class_anchor_link_sharp_1_1_link_session)` > ` [`RestoreSession`](#class_anchor_link_sharp_1_1_anchor_link_1a7cffa50a5f997a82e7b240c759429ae4)`(string identifier, PermissionLevel auth)` | Restore previous session, see [[AnchorLink.login]] to create a new session.
`public async Task< List< PermissionLevel > > ` [`ListSessions`](#class_anchor_link_sharp_1_1_anchor_link_1a26af270e04728d003f4413fe1fd09a6b)`(string identifier)` | List stored session auths for given identifier. The most recently used session is at the top (index 0).
`public async Task ` [`RemoveSession`](#class_anchor_link_sharp_1_1_anchor_link_1a0201a0d51fb824a07270e102192891cf)`(string identifier, PermissionLevel auth)` | Remove stored session for given identifier and auth.
`public async void ` [`ClearSessions`](#class_anchor_link_sharp_1_1_anchor_link_1a13e8a7c2fc690bff953766788d1c8507)`(string identifier)` | Remove all stored sessions for given identifier.
`public LinkSignatureProvider ` [`MakeSignatureProvider`](#class_anchor_link_sharp_1_1_anchor_link_1a972262a195b3b8df071d75404acf03d8)`(string[] availableKeys, ` [`ILinkTransport`](.github/workflows/documentation/md/AnchorLinkSharp.md#interface_anchor_link_sharp_1_1_i_link_transport)` transport)` | Create an eosjs compatible signature provider using this anchorLink.
`public async Task< CallbackPayload > ` [`WaitForCallback`](#class_anchor_link_sharp_1_1_anchor_link_1adc00a445712a67d7ae7f6e94aa0facdb)`(string url)` | Connect to a WebSocket channel and wait for a message.
`public async Task ` [`PollForCallback`](#class_anchor_link_sharp_1_1_anchor_link_1aab81c9f8580485999fb50b0b92b57297)`(string url)` | 
`private readonly string ` [`_serviceAddress`](#class_anchor_link_sharp_1_1_anchor_link_1af3111da0cd839afdaa039bb12e192a60) | 
`private readonly SigningRequestEncodingOptions ` [`_requestOptions`](#class_anchor_link_sharp_1_1_anchor_link_1aa95d1275f898f38a9089ceb4c929942e) | 
`private readonly Dictionary< string, Abi > ` [`_abiCache`](#class_anchor_link_sharp_1_1_anchor_link_1a65fe607572bcc08a0a12c45ce4de6952)`= new Dictionary<string, Abi>()` | 
`private readonly Dictionary< string, Task< GetAbiResponse > > ` [`_pendingAbis`](#class_anchor_link_sharp_1_1_anchor_link_1a86e828352d049438a442b003467fb2f1)`= new Dictionary<string, Task<GetAbiResponse>>()` | 
`private WebSocketWrapper ` [`_socket`](#class_anchor_link_sharp_1_1_anchor_link_1aa91178ae68686e701a8db0ba9aa4e0b2) | 
`private async Task ` [`TouchSession`](#class_anchor_link_sharp_1_1_anchor_link_1a97ab13673964a3563c36bbe5a68b4e51)`(string identifier, PermissionLevel auth, bool remove)` | Makes sure session is in storage list of sessions and moves it to top (most recently used).
`private async Task ` [`StoreSession`](#class_anchor_link_sharp_1_1_anchor_link_1a9ab68f28433479ccb198256cc8f98ef2)`(string identifier, ` [`LinkSession`](.github/workflows/documentation/md/AnchorLinkSharp--LinkSession.md#class_anchor_link_sharp_1_1_link_session)` session)` | Makes sure session is in storage list of sessions and moves it to top (most recently used).
`private string ` [`SessionKey`](#class_anchor_link_sharp_1_1_anchor_link_1a41d11cf2b1f6e0f5c6cc5b5a2c2236ae)`(string identifier, string[] suffixes)` | Session storage key for identifier and suffix.

## Members

##### `public readonly ` [`ILinkTransport`](.github/workflows/documentation/md/AnchorLinkSharp.md#interface_anchor_link_sharp_1_1_i_link_transport)` ` [`Transport`](#class_anchor_link_sharp_1_1_anchor_link_1aee5fc13a77160e6a524c6ad153299309) 

Transport used to deliver requests to the user wallet.

##### `public readonly string ` [`ChainId`](#class_anchor_link_sharp_1_1_anchor_link_1a13b0e3b911976c623a64c2bd5da0f0d8) 

EOSIO ChainID for which requests are valid.

##### `public readonly ` [`ILinkStorage`](.github/workflows/documentation/md/AnchorLinkSharp.md#interface_anchor_link_sharp_1_1_i_link_storage)` ` [`Storage`](#class_anchor_link_sharp_1_1_anchor_link_1a54bdbcc79b07c68aa3dc1879abd64d43) 

PlayerPrefsStorage adapter used to persist sessions.

##### `public ` [`AnchorLink`](#class_anchor_link_sharp_1_1_anchor_link_1aeaef1002a44d51caeea5ac9cbf3fcfc7)`(` [`ILinkOptions`](.github/workflows/documentation/md/AnchorLinkSharp.md#interface_anchor_link_sharp_1_1_i_link_options)` options)` 

Create a new anchorLink instance.

##### `public async Task< Abi > ` [`GetAbi`](#class_anchor_link_sharp_1_1_anchor_link_1a9d9f8443e4fa6c3d5d5790567f0395f3)`(string account)` 

Fetch the ABI for given account, cached.

##### `public string ` [`CreateCallbackUrl`](#class_anchor_link_sharp_1_1_anchor_link_1af3228312c13fbf438d8f2315ec47ec1d)`()` 

Create a new unique buoy callback url.

##### `public async Task< SigningRequest > ` [`CreateRequest`](#class_anchor_link_sharp_1_1_anchor_link_1a7a825e1a392930afbde7725eec7297ff)`(SigningRequestCreateArguments args, ` [`ILinkTransport`](.github/workflows/documentation/md/AnchorLinkSharp.md#interface_anchor_link_sharp_1_1_i_link_transport)` transport)` 

Create a SigningRequest instance configured for this anchorLink.

##### `public async Task< ` [`TransactResult`](.github/workflows/documentation/md/AnchorLinkSharp--TransactResult.md#class_anchor_link_sharp_1_1_transact_result)` > ` [`SendRequest`](#class_anchor_link_sharp_1_1_anchor_link_1a694674e4b7edcdf8c453232fa71cab9f)`(SigningRequest request, ` [`ILinkTransport`](.github/workflows/documentation/md/AnchorLinkSharp.md#interface_anchor_link_sharp_1_1_i_link_transport)` transport, bool broadcast)` 

Send a SigningRequest instance using this anchorLink.

##### `public async Task< ` [`TransactResult`](.github/workflows/documentation/md/AnchorLinkSharp--TransactResult.md#class_anchor_link_sharp_1_1_transact_result)` > ` [`Transact`](#class_anchor_link_sharp_1_1_anchor_link_1a18a7e254c35f5c402f4bccf340fac893)`(` [`TransactArgs`](.github/workflows/documentation/md/AnchorLinkSharp--TransactArgs.md#class_anchor_link_sharp_1_1_transact_args)` args, ` [`TransactOptions`](.github/workflows/documentation/md/AnchorLinkSharp--TransactOptions.md#class_anchor_link_sharp_1_1_transact_options)` options, ` [`ILinkTransport`](.github/workflows/documentation/md/AnchorLinkSharp.md#interface_anchor_link_sharp_1_1_i_link_transport)` transport)` 

Sign and optionally broadcast a EOSIO transaction, action or actions.

Example:

```cpp
var result = await myLink.transact({transaction: myTx})
```

#### Parameters
* `args` The action, actions or transaction to use. 

* `options` Options for this transact call. 

* `transport` Transport override, for internal use.

##### `public async Task< ` [`IdentifyResult`](.github/workflows/documentation/md/AnchorLinkSharp--IdentifyResult.md#class_anchor_link_sharp_1_1_identify_result)` > ` [`Identify`](#class_anchor_link_sharp_1_1_anchor_link_1abcf7b8bbe7bcdcf28714aaf9f7ccbae6)`(PermissionLevel requestPermission, object info)` 

Send an identity request and verify the identity proof. 
#### Parameters
* `requestPermission` Optional request permission if the request is for a specific account or permission. 

* `info` Metadata to add to the request. 

This is for advanced use-cases, you probably want to use [[AnchorLink.login]] instead.

##### `public async Task< ` [`LoginResult`](.github/workflows/documentation/md/AnchorLinkSharp--LoginResult.md#class_anchor_link_sharp_1_1_login_result)` > ` [`Login`](#class_anchor_link_sharp_1_1_anchor_link_1ab7be810b454e3488fe61cb53e6f9240c)`(string identifier)` 

Login and create a persistent session. 
#### Parameters
* `identifier` The session identifier, an EOSIO name (`[a-z1-5]{1,12}`). Should be set to the contract account if applicable.

##### `public async Task< ` [`LinkSession`](.github/workflows/documentation/md/AnchorLinkSharp--LinkSession.md#class_anchor_link_sharp_1_1_link_session)` > ` [`RestoreSession`](#class_anchor_link_sharp_1_1_anchor_link_1a7cffa50a5f997a82e7b240c759429ae4)`(string identifier, PermissionLevel auth)` 

Restore previous session, see [[AnchorLink.login]] to create a new session. 
#### Parameters
* `identifier` The session identifier, should be same as what was used when creating the session with [[AnchorLink.login]]. 

* `auth` A specific session auth to restore, if omitted the most recently used session will be restored. 

#### Returns
A [[LinkSession]] instance or null if no session can be found. 

#### Exceptions
* `If` no [[LinkStorage]] adapter is configured or there was an error retrieving the session data.

##### `public async Task< List< PermissionLevel > > ` [`ListSessions`](#class_anchor_link_sharp_1_1_anchor_link_1a26af270e04728d003f4413fe1fd09a6b)`(string identifier)` 

List stored session auths for given identifier. The most recently used session is at the top (index 0). 
#### Exceptions
* `If` no [[LinkStorage]] adapter is configured or there was an error retrieving the session list.

##### `public async Task ` [`RemoveSession`](#class_anchor_link_sharp_1_1_anchor_link_1a0201a0d51fb824a07270e102192891cf)`(string identifier, PermissionLevel auth)` 

Remove stored session for given identifier and auth. 
#### Exceptions
* `If` no [[LinkStorage]] adapter is configured or there was an error removing the session data.

##### `public async void ` [`ClearSessions`](#class_anchor_link_sharp_1_1_anchor_link_1a13e8a7c2fc690bff953766788d1c8507)`(string identifier)` 

Remove all stored sessions for given identifier. 
#### Exceptions
* `If` no [[LinkStorage]] adapter is configured or there was an error removing the session data.

##### `public LinkSignatureProvider ` [`MakeSignatureProvider`](#class_anchor_link_sharp_1_1_anchor_link_1a972262a195b3b8df071d75404acf03d8)`(string[] availableKeys, ` [`ILinkTransport`](.github/workflows/documentation/md/AnchorLinkSharp.md#interface_anchor_link_sharp_1_1_i_link_transport)` transport)` 

Create an eosjs compatible signature provider using this anchorLink. 
#### Parameters
* `availableKeys` Keys the created provider will claim to be able to sign for. 

* `transport` (internal) Transport override for this call. 

We don't know what keys are available so those have to be provided, to avoid this use [[LinkSession.makeSignatureProvider]] instead. Sessions can be created with [[AnchorLink.login]].

##### `public async Task< CallbackPayload > ` [`WaitForCallback`](#class_anchor_link_sharp_1_1_anchor_link_1adc00a445712a67d7ae7f6e94aa0facdb)`(string url)` 

Connect to a WebSocket channel and wait for a message.

##### `public async Task ` [`PollForCallback`](#class_anchor_link_sharp_1_1_anchor_link_1aab81c9f8580485999fb50b0b92b57297)`(string url)` 

##### `private readonly string ` [`_serviceAddress`](#class_anchor_link_sharp_1_1_anchor_link_1af3111da0cd839afdaa039bb12e192a60) 

##### `private readonly SigningRequestEncodingOptions ` [`_requestOptions`](#class_anchor_link_sharp_1_1_anchor_link_1aa95d1275f898f38a9089ceb4c929942e) 

##### `private readonly Dictionary< string, Abi > ` [`_abiCache`](#class_anchor_link_sharp_1_1_anchor_link_1a65fe607572bcc08a0a12c45ce4de6952)`= new Dictionary<string, Abi>()` 

##### `private readonly Dictionary< string, Task< GetAbiResponse > > ` [`_pendingAbis`](#class_anchor_link_sharp_1_1_anchor_link_1a86e828352d049438a442b003467fb2f1)`= new Dictionary<string, Task<GetAbiResponse>>()` 

##### `private WebSocketWrapper ` [`_socket`](#class_anchor_link_sharp_1_1_anchor_link_1aa91178ae68686e701a8db0ba9aa4e0b2) 

##### `private async Task ` [`TouchSession`](#class_anchor_link_sharp_1_1_anchor_link_1a97ab13673964a3563c36bbe5a68b4e51)`(string identifier, PermissionLevel auth, bool remove)` 

Makes sure session is in storage list of sessions and moves it to top (most recently used).

##### `private async Task ` [`StoreSession`](#class_anchor_link_sharp_1_1_anchor_link_1a9ab68f28433479ccb198256cc8f98ef2)`(string identifier, ` [`LinkSession`](.github/workflows/documentation/md/AnchorLinkSharp--LinkSession.md#class_anchor_link_sharp_1_1_link_session)` session)` 

Makes sure session is in storage list of sessions and moves it to top (most recently used).

##### `private string ` [`SessionKey`](#class_anchor_link_sharp_1_1_anchor_link_1a41d11cf2b1f6e0f5c6cc5b5a2c2236ae)`(string identifier, string[] suffixes)` 

Session storage key for identifier and suffix.

