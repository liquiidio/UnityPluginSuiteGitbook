### Getting an Offer

```csharp

async Task GetOffer(string offerId)
{

    // Initialize the v1 offers API
    var api = AtomicMarketApiFactory.Version1.OffersApi;

    // Call the offers endpoint passing the offerId as an input
    var sales = await api.Offer(offerId);

    // Access different informations about the offer using the Data property in the result
    Console.WriteLine(sales.Data.SenderName);
}

 ```
