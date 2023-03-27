### Usage

#### Configuration

In order to interact with the Eos blockchain, you need to create a new instance of the **Eos** class with an **EosConfigurator**.

```csharp
Eos eos = new Eos(new EosConfigurator()
{    
    HttpEndpoint = "https://nodes.eos42.io", //Mainnet
    ChainId = "aca376f206b8fc25a6ed44dbdc66547c36c6c33e3a119ffbeaef943642f0e906",
    ExpireSeconds = 60,
    SignProvider = new DefaultSignProvider("myprivatekey")
});
```
