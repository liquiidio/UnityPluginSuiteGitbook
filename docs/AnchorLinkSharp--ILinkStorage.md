# interface `AnchorLinkSharp::ILinkStorage` 

Interface storage adapters should implement.

LinkStorage adapters are responsible for persisting [[LinkSession]]'s and can optionally be passed to the [[AnchorLink]] constructor to auto-persist sessions.

## Summary

 Members                                | Descriptions                                
----------------------------------------|---------------------------------------------
`public Task ` [`Write`](AnchorLinkSharp.md)`(string key, string data)` | Write string to storage at key. Should overwrite existing values without error.
`public Task< string > ` [`Read`](AnchorLinkSharp.md)`(string key)` | Read key from storage. Should return `null` if key can not be found.
`public Task ` [`Remove`](AnchorLinkSharp.md)`(string key)` | Delete key from storage. Should not error if deleting non-existing key.

## Members

##### `public Task ` [`Write`](AnchorLinkSharp.md)`(string key, string data)` 

Write string to storage at key. Should overwrite existing values without error.

##### `public Task< string > ` [`Read`](AnchorLinkSharp.md)`(string key)` 

Read key from storage. Should return `null` if key can not be found.

##### `public Task ` [`Remove`](AnchorLinkSharp.md)`(string key)` 

Delete key from storage. Should not error if deleting non-existing key.

