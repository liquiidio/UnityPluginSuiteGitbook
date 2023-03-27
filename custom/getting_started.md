# Configuration

## Configuration

In order to interact with the Eos blockchain, you need to create a new instance of the **Eos** class with an **EosConfigurator**.

```csharp
Eos eos = new Eos(new EosConfigurator()
{    
    HttpEndpoint = "https://api.wax.liquidstudios.io", //WAX Mainnet
    ChainId = "1064487b3cd1a897ce03ae5b6a865651747e2e152090f99c1d19d44e01aea5a4",
    ExpireSeconds = 60,
    SignProvider = new DefaultSignProvider("myprivatekey")
});
```
