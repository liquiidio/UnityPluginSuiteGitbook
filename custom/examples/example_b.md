#### Custom SignProvider

Is also possible to implement your own **ISignProvider** to customize how the signatures and key handling is done.

Example:

```csharp
/// <summary>
/// Signature provider implementation that uses a private server to hold keys
/// </summary>
class SuperSecretSignProvider : ISignProvider
{
   /// <summary>
   /// Get available public keys from signature provider server
   /// </summary>
   /// <returns>List of public keys</returns>
   public async Task<IEnumerable<string>> GetAvailableKeys()
   {
        var result = await HttpHelper.GetJsonAsync<SecretResponse>("https://supersecretserver.com/get_available_keys");
        return result.Keys;
   }
   
   /// <summary>
   /// Sign bytes using the signature provider server
   /// </summary>
   /// <param name="chainId">EOSIO Chain id</param>
   /// <param name="requiredKeys">required public keys for signing this bytes</param>
   /// <param name="signBytes">signature bytes</param>
   /// <param name="abiNames">abi contract names to get abi information from</param>
   /// <returns>List of signatures per required keys</returns>
   public async Task<IEnumerable<string>> Sign(string chainId, List<string> requiredKeys, byte[] signBytes)
   {
        var result = await HttpHelper.PostJsonAsync<SecretSignResponse>("https://supersecretserver.com/sign", new SecretRequest {
            chainId = chainId,
            RequiredKeys = requiredKeys,
            Data = signBytes
        });
        return result.Signatures;
   }
}

// create new Eos client instance using your custom signature provider
Eos eos = new Eos(new EosConfigurator()
{
    SignProvider = new SuperSecretSignProvider(),
    HttpEndpoint = "https://nodes.eos42.io", //Mainnet
    ChainId = "aca376f206b8fc25a6ed44dbdc66547c36c6c33e3a119ffbeaef943642f0e906"
});
```
