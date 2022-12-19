# interface `AnchorLinkSharp::ILinkStorage` 

Interface storage adapters should implement.

LinkStorage adapters are responsible for persisting [[LinkSession]]'s and can optionally be passed to the [[AnchorLink]] constructor to auto-persist sessions.

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public Task `[`Write`](.github/workflows/documentation/md/AnchorLinkSharp.md#interface_anchor_link_sharp_1_1_i_link_storage_1a6a9c4db24bc4ca8b492930e3af6a2c34)`(string key, string data)` | Write string to storage at key. Should overwrite existing values without error.
`public Task< string > `[`Read`](.github/workflows/documentation/md/AnchorLinkSharp.md#interface_anchor_link_sharp_1_1_i_link_storage_1a4289dc0a9df40425bce9129ffa8ea8da)`(string key)` | Read key from storage. Should return `null` if key can not be found.
`public Task `[`Remove`](.github/workflows/documentation/md/AnchorLinkSharp.md#interface_anchor_link_sharp_1_1_i_link_storage_1aec4057c346c0b6ecff7bb12b6b08357c)`(string key)` | Delete key from storage. Should not error if deleting non-existing key.

## Members

### `public Task `[`Write`](.github/workflows/documentation/md/AnchorLinkSharp.md#interface_anchor_link_sharp_1_1_i_link_storage_1a6a9c4db24bc4ca8b492930e3af6a2c34)`(string key, string data)` 

Write string to storage at key. Should overwrite existing values without error.

### `public Task< string > `[`Read`](.github/workflows/documentation/md/AnchorLinkSharp.md#interface_anchor_link_sharp_1_1_i_link_storage_1a4289dc0a9df40425bce9129ffa8ea8da)`(string key)` 

Read key from storage. Should return `null` if key can not be found.

### `public Task `[`Remove`](.github/workflows/documentation/md/AnchorLinkSharp.md#interface_anchor_link_sharp_1_1_i_link_storage_1aec4057c346c0b6ecff7bb12b6b08357c)`(string key)` 

Delete key from storage. Should not error if deleting non-existing key.

