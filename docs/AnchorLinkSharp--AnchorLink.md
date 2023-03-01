# class `AnchorLinkSharp::AnchorLink` 

```
class AnchorLinkSharp::AnchorLink
  : public AbiSerializationProvider
```

Main class, also exposed as the default export of the library.

Example:

```cpp
import AnchorLink from 'anchor-anchorLink'
import ConsoleTransport from 'anchor-anchorLink-console-transport'

const anchorLink = new AnchorLink({
    transport: new ConsoleTransport()
})

const result = await anchorLink.transact({actions: myActions})
```

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public readonly ` [`ILinkTransport`](AnchorLinkSharp.md)` ` [`Transport`](#class_anchor_link_sharp_1_1_anchor_link_1aee5fc13a77160e6a524c6ad153299309) | The eosjs RPC instance used to communicate with the EOSIO node. Transport used to deliver requests to the user wallet.
`public readonly string ` [`ChainId`](#class_anchor_link_sharp_1_1_anchor_link_1a13b0e3b911976c623a64c2bd5da0f0d8) | EOSIO ChainID for which requests are valid.
`public readonly ` [`ILinkStorage`](AnchorLinkSharp.md)` ` [`Storage`](#class_anchor_link_sharp_1_1_anchor_link_1a54bdbcc79b07c68aa3dc1879abd64d43) | PlayerPrefsStorage adapter used to persist sessions.
`public ` [`AnchorLink`](#class_anchor_link_sharp_1_1_anchor_link_1aeaef1002a44d51caeea5ac9cbf3fcfc7)`(` [`ILinkOptions`](AnchorLinkSharp.md)` options)` | Create a new anchorLink instance.
`public async Task< ` [`Abi`](EosSharp--Core--Api--v1--Abi.md)` > ` [`GetAbi`](#class_anchor_link_sharp_1_1_anchor_link_1a9d9f8443e4fa6c3d5d5790567f0395f3)`(string account)` | Fetch the ABI for given account, cached.
`public string ` [`CreateCallbackUrl`](#class_anchor_link_sharp_1_1_anchor_link_1af3228312c13fbf438d8f2315ec47ec1d)`()` | Create a new unique buoy callback url.
`public async Task< ` [`SigningRequest`](EosioSigningRequest--SigningRequest.md)` > ` [`CreateRequest`](#class_anchor_link_sharp_1_1_anchor_link_1a7a825e1a392930afbde7725eec7297ff)`(` [`SigningRequestCreateArguments`](EosioSigningRequest--SigningRequestCreateArguments.md)` args, ` [`ILinkTransport`](AnchorLinkSharp.md)` transport)` | Create a SigningRequest instance configured for this anchorLink.
`public async Task< ` [`TransactResult`](AnchorLinkSharp--TransactResult.md)` > ` [`SendRequest`](#class_anchor_link_sharp_1_1_anchor_link_1a694674e4b7edcdf8c453232fa71cab9f)`(` [`SigningRequest`](EosioSigningRequest--SigningRequest.md)` request, ` [`ILinkTransport`](AnchorLinkSharp.md)` transport, bool broadcast)` | Send a SigningRequest instance using this anchorLink.
`public async Task< ` [`TransactResult`](AnchorLinkSharp--TransactResult.md)` > ` [`Transact`](#class_anchor_link_sharp_1_1_anchor_link_1a18a7e254c35f5c402f4bccf340fac893)`(` [`TransactArgs`](AnchorLinkSharp--TransactArgs.md)` args, ` [`TransactOptions`](AnchorLinkSharp--TransactOptions.md)` options, ` [`ILinkTransport`](AnchorLinkSharp.md)` transport)` | Sign and optionally broadcast a EOSIO transaction, action or actions.
`public async Task< ` [`IdentifyResult`](AnchorLinkSharp--IdentifyResult.md)` > ` [`Identify`](#class_anchor_link_sharp_1_1_anchor_link_1abcf7b8bbe7bcdcf28714aaf9f7ccbae6)`(` [`PermissionLevel`](EosSharp--Core--Api--v1--PermissionLevel.md)` requestPermission, object info)` | Send an identity request and verify the identity proof.
`public async Task< ` [`LoginResult`](AnchorLinkSharp--LoginResult.md)` > ` [`Login`](#class_anchor_link_sharp_1_1_anchor_link_1ab7be810b454e3488fe61cb53e6f9240c)`(string identifier)` | Login and create a persistent session.
`public async Task< ` [`LinkSession`](AnchorLinkSharp--LinkSession.md)` > ` [`RestoreSession`](#class_anchor_link_sharp_1_1_anchor_link_1a7cffa50a5f997a82e7b240c759429ae4)`(string identifier, ` [`PermissionLevel`](EosSharp--Core--Api--v1--PermissionLevel.md)` auth)` | Restore previous session, see [[AnchorLink.login]] to create a new session.
`public async Task< List< ` [`PermissionLevel`](EosSharp--Core--Api--v1--PermissionLevel.md)` > > ` [`ListSessions`](#class_anchor_link_sharp_1_1_anchor_link_1a26af270e04728d003f4413fe1fd09a6b)`(string identifier)` | List stored session auths for given identifier. The most recently used session is at the top (index 0).
`public async Task ` [`RemoveSession`](#class_anchor_link_sharp_1_1_anchor_link_1a0201a0d51fb824a07270e102192891cf)`(string identifier, ` [`PermissionLevel`](EosSharp--Core--Api--v1--PermissionLevel.md)` auth)` | Remove stored session for given identifier and auth.
`public async void ` [`ClearSessions`](#class_anchor_link_sharp_1_1_anchor_link_1a13e8a7c2fc690bff953766788d1c8507)`(string identifier)` | Remove all stored sessions for given identifier.
`public ` [`LinkSignatureProvider`](AnchorLinkSharp--LinkSignatureProvider.md)` ` [`MakeSignatureProvider`](#class_anchor_link_sharp_1_1_anchor_link_1a972262a195b3b8df071d75404acf03d8)`(string[] availableKeys, ` [`ILinkTransport`](AnchorLinkSharp.md)` transport)` | Create an eosjs compatible signature provider using this anchorLink.
`public Task< ` [`CallbackPayload`](EosioSigningRequest--CallbackPayload.md)` > ` [`WaitForCallback`](#class_anchor_link_sharp_1_1_anchor_link_1a3151832e764e7024f0a1b979e7ef664b)`(string url, CancellationTokenSource cts)` | Connect to a WebSocket channel and wait for a message.
`public void ` [`PollForCallback`](#class_anchor_link_sharp_1_1_anchor_link_1a6a32c2ea50075751354083b4919a43d0)`(string url, CancellationToken ctl)` | 
`private readonly string ` [`_serviceAddress`](#class_anchor_link_sharp_1_1_anchor_link_1af3111da0cd839afdaa039bb12e192a60) | 
`private readonly ` [`SigningRequestEncodingOptions`](EosioSigningRequest--SigningRequestEncodingOptions.md)` ` [`_requestOptions`](#class_anchor_link_sharp_1_1_anchor_link_1aa95d1275f898f38a9089ceb4c929942e) | 
`private readonly Dictionary< string, ` [`Abi`](EosSharp--Core--Api--v1--Abi.md)` > ` [`_abiCache`](#class_anchor_link_sharp_1_1_anchor_link_1a65fe607572bcc08a0a12c45ce4de6952)`= new Dictionary<string, >()` | 
`private readonly Dictionary< string, Task< ` [`GetAbiResponse`](EosSharp--Core--Api--v1--GetAbiResponse.md)` > > ` [`_pendingAbis`](#class_anchor_link_sharp_1_1_anchor_link_1a86e828352d049438a442b003467fb2f1)`= new Dictionary<string, Task<>>()` | 
`private async Task ` [`TouchSession`](#class_anchor_link_sharp_1_1_anchor_link_1a97ab13673964a3563c36bbe5a68b4e51)`(string identifier, ` [`PermissionLevel`](EosSharp--Core--Api--v1--PermissionLevel.md)` auth, bool remove)` | Makes sure session is in storage list of sessions and moves it to top (most recently used).
`private async Task ` [`StoreSession`](#class_anchor_link_sharp_1_1_anchor_link_1a9ab68f28433479ccb198256cc8f98ef2)`(string identifier, ` [`LinkSession`](AnchorLinkSharp--LinkSession.md)` session)` | Makes sure session is in storage list of sessions and moves it to top (most recently used).
`private string ` [`SessionKey`](#class_anchor_link_sharp_1_1_anchor_link_1a733533e1722e91beba57ea0c2d9b0400)`(string identifier, string suffix)` | Session storage key for identifier and suffix.

## Members

##### `public readonly ` [`ILinkTransport`](AnchorLinkSharp.md)` ` [`Transport`](#class_anchor_link_sharp_1_1_anchor_link_1aee5fc13a77160e6a524c6ad153299309) 

The eosjs RPC instance used to communicate with the EOSIO node. Transport used to deliver requests to the user wallet.

##### `public readonly string ` [`ChainId`](#class_anchor_link_sharp_1_1_anchor_link_1a13b0e3b911976c623a64c2bd5da0f0d8) 

EOSIO ChainID for which requests are valid.

##### `public readonly ` [`ILinkStorage`](AnchorLinkSharp.md)` ` [`Storage`](#class_anchor_link_sharp_1_1_anchor_link_1a54bdbcc79b07c68aa3dc1879abd64d43) 

PlayerPrefsStorage adapter used to persist sessions.

##### `public ` [`AnchorLink`](#class_anchor_link_sharp_1_1_anchor_link_1aeaef1002a44d51caeea5ac9cbf3fcfc7)`(` [`ILinkOptions`](AnchorLinkSharp.md)` options)` 

Create a new anchorLink instance.

##### `public async Task< ` [`Abi`](EosSharp--Core--Api--v1--Abi.md)` > ` [`GetAbi`](#class_anchor_link_sharp_1_1_anchor_link_1a9d9f8443e4fa6c3d5d5790567f0395f3)`(string account)` 

Fetch the ABI for given account, cached.

##### `public string ` [`CreateCallbackUrl`](#class_anchor_link_sharp_1_1_anchor_link_1af3228312c13fbf438d8f2315ec47ec1d)`()` 

Create a new unique buoy callback url.

##### `public async Task< ` [`SigningRequest`](EosioSigningRequest--SigningRequest.md)` > ` [`CreateRequest`](#class_anchor_link_sharp_1_1_anchor_link_1a7a825e1a392930afbde7725eec7297ff)`(` [`SigningRequestCreateArguments`](EosioSigningRequest--SigningRequestCreateArguments.md)` args, ` [`ILinkTransport`](AnchorLinkSharp.md)` transport)` 

Create a SigningRequest instance configured for this anchorLink.

##### `public async Task< ` [`TransactResult`](AnchorLinkSharp--TransactResult.md)` > ` [`SendRequest`](#class_anchor_link_sharp_1_1_anchor_link_1a694674e4b7edcdf8c453232fa71cab9f)`(` [`SigningRequest`](EosioSigningRequest--SigningRequest.md)` request, ` [`ILinkTransport`](AnchorLinkSharp.md)` transport, bool broadcast)` 

Send a SigningRequest instance using this anchorLink.

##### `public async Task< ` [`TransactResult`](AnchorLinkSharp--TransactResult.md)` > ` [`Transact`](#class_anchor_link_sharp_1_1_anchor_link_1a18a7e254c35f5c402f4bccf340fac893)`(` [`TransactArgs`](AnchorLinkSharp--TransactArgs.md)` args, ` [`TransactOptions`](AnchorLinkSharp--TransactOptions.md)` options, ` [`ILinkTransport`](AnchorLinkSharp.md)` transport)` 

Sign and optionally broadcast a EOSIO transaction, action or actions.

Example:

```cpp
var result = await myLink.transact({transaction: myTx})
```

#### Parameters
* `args` The action, actions or transaction to use. 

* `options` Options for this transact call. 

* `transport` Transport override, for internal use.

##### `public async Task< ` [`IdentifyResult`](AnchorLinkSharp--IdentifyResult.md)` > ` [`Identify`](#class_anchor_link_sharp_1_1_anchor_link_1abcf7b8bbe7bcdcf28714aaf9f7ccbae6)`(` [`PermissionLevel`](EosSharp--Core--Api--v1--PermissionLevel.md)` requestPermission, object info)` 

Send an identity request and verify the identity proof. 
#### Parameters
* `requestPermission` Optional request permission if the request is for a specific account or permission. 

* `info` Metadata to add to the request. 

This is for advanced use-cases, you probably want to use [[AnchorLink.login]] instead.

##### `public async Task< ` [`LoginResult`](AnchorLinkSharp--LoginResult.md)` > ` [`Login`](#class_anchor_link_sharp_1_1_anchor_link_1ab7be810b454e3488fe61cb53e6f9240c)`(string identifier)` 

Login and create a persistent session. 
#### Parameters
* `identifier` The session identifier, an EOSIO name (`[a-z1-5]{1,12}`). Should be set to the contract account if applicable.

##### `public async Task< ` [`LinkSession`](AnchorLinkSharp--LinkSession.md)` > ` [`RestoreSession`](#class_anchor_link_sharp_1_1_anchor_link_1a7cffa50a5f997a82e7b240c759429ae4)`(string identifier, ` [`PermissionLevel`](EosSharp--Core--Api--v1--PermissionLevel.md)` auth)` 

Restore previous session, see [[AnchorLink.login]] to create a new session. 
#### Parameters
* `identifier` The session identifier, should be same as what was used when creating the session with [[AnchorLink.login]]. 

* `auth` A specific session auth to restore, if omitted the most recently used session will be restored. 

#### Returns
A [[LinkSession]] instance or null if no session can be found. 

#### Exceptions
* `If` no [[LinkStorage]] adapter is configured or there was an error retrieving the session data.

##### `public async Task< List< ` [`PermissionLevel`](EosSharp--Core--Api--v1--PermissionLevel.md)` > > ` [`ListSessions`](#class_anchor_link_sharp_1_1_anchor_link_1a26af270e04728d003f4413fe1fd09a6b)`(string identifier)` 

List stored session auths for given identifier. The most recently used session is at the top (index 0). 
#### Exceptions
* `If` no [[LinkStorage]] adapter is configured or there was an error retrieving the session list.

##### `public async Task ` [`RemoveSession`](#class_anchor_link_sharp_1_1_anchor_link_1a0201a0d51fb824a07270e102192891cf)`(string identifier, ` [`PermissionLevel`](EosSharp--Core--Api--v1--PermissionLevel.md)` auth)` 

Remove stored session for given identifier and auth. 
#### Exceptions
* `If` no [[LinkStorage]] adapter is configured or there was an error removing the session data.

##### `public async void ` [`ClearSessions`](#class_anchor_link_sharp_1_1_anchor_link_1a13e8a7c2fc690bff953766788d1c8507)`(string identifier)` 

Remove all stored sessions for given identifier. 
#### Exceptions
* `If` no [[LinkStorage]] adapter is configured or there was an error removing the session data.

##### `public ` [`LinkSignatureProvider`](AnchorLinkSharp--LinkSignatureProvider.md)` ` [`MakeSignatureProvider`](#class_anchor_link_sharp_1_1_anchor_link_1a972262a195b3b8df071d75404acf03d8)`(string[] availableKeys, ` [`ILinkTransport`](AnchorLinkSharp.md)` transport)` 

Create an eosjs compatible signature provider using this anchorLink. 
#### Parameters
* `availableKeys` Keys the created provider will claim to be able to sign for. 

* `transport` (internal) Transport override for this call. 

We don't know what keys are available so those have to be provided, to avoid this use [[LinkSession.makeSignatureProvider]] instead. Sessions can be created with [[AnchorLink.login]].

##### `public Task< ` [`CallbackPayload`](EosioSigningRequest--CallbackPayload.md)` > ` [`WaitForCallback`](#class_anchor_link_sharp_1_1_anchor_link_1a3151832e764e7024f0a1b979e7ef664b)`(string url, CancellationTokenSource cts)` 

Connect to a WebSocket channel and wait for a message.

##### `public void ` [`PollForCallback`](#class_anchor_link_sharp_1_1_anchor_link_1a6a32c2ea50075751354083b4919a43d0)`(string url, CancellationToken ctl)` 

##### `private readonly string ` [`_serviceAddress`](#class_anchor_link_sharp_1_1_anchor_link_1af3111da0cd839afdaa039bb12e192a60) 

##### `private readonly ` [`SigningRequestEncodingOptions`](EosioSigningRequest--SigningRequestEncodingOptions.md)` ` [`_requestOptions`](#class_anchor_link_sharp_1_1_anchor_link_1aa95d1275f898f38a9089ceb4c929942e) 

##### `private readonly Dictionary< string, ` [`Abi`](EosSharp--Core--Api--v1--Abi.md)` > ` [`_abiCache`](#class_anchor_link_sharp_1_1_anchor_link_1a65fe607572bcc08a0a12c45ce4de6952)`= new Dictionary<string, >()` 

##### `private readonly Dictionary< string, Task< ` [`GetAbiResponse`](EosSharp--Core--Api--v1--GetAbiResponse.md)` > > ` [`_pendingAbis`](#class_anchor_link_sharp_1_1_anchor_link_1a86e828352d049438a442b003467fb2f1)`= new Dictionary<string, Task<>>()` 

##### `private async Task ` [`TouchSession`](#class_anchor_link_sharp_1_1_anchor_link_1a97ab13673964a3563c36bbe5a68b4e51)`(string identifier, ` [`PermissionLevel`](EosSharp--Core--Api--v1--PermissionLevel.md)` auth, bool remove)` 

Makes sure session is in storage list of sessions and moves it to top (most recently used).

##### `private async Task ` [`StoreSession`](#class_anchor_link_sharp_1_1_anchor_link_1a9ab68f28433479ccb198256cc8f98ef2)`(string identifier, ` [`LinkSession`](AnchorLinkSharp--LinkSession.md)` session)` 

Makes sure session is in storage list of sessions and moves it to top (most recently used).

##### `private string ` [`SessionKey`](#class_anchor_link_sharp_1_1_anchor_link_1a733533e1722e91beba57ea0c2d9b0400)`(string identifier, string suffix)` 

Session storage key for identifier and suffix.

