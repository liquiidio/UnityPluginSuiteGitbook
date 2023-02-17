#### AnchorLink

## What is Anchor and AnchorLink

[Anchor](https://greymass.com/anchor) is a standalone blockchain Wallet and Authenticator available on most desktop and mobile platforms. It allows users to securely store their private keys and perform on-chain transactions requested by external applications. These external applications could be web apps, mobile apps, or games built with this plugin for the Unity platform.

Anchor utilizes the [anchor-link](https://github.com/greymass/anchor-link) SDK to send and receive [eosio-signing-request](https://github.com/greymass/eosio-signing-request) formatted message. All communication between the application and the user is encrypted and no private keys or other identifiable information (except for the on-chain account name) is trasmitted in this process. Other wallets built for Antelope-based blockchains can also adopt these protocols to allow their users an easy way to integrate into external applications.

## Availability

[Anchor](https://greymass.com/anchor) is available for Windows, macOS, Linux, iOS and Android. It is free to download and use. 

If users already have an account they can import it and use the app for free. Users can create or purchase accounts through any service. Anchor itself also offers paid account creation for users who do not have an account and are unsure how to create one. 

All SDKs related to Anchor are free and open source.

## Documentation

Additional documentation for the web-based integration of anchor-link can be found below, which may be of assistance when integrating the Unity-based SDKs.

- [https://github.com/greymass/anchor-link](https://github.com/greymass/anchor-link)
- [https://github.com/greymass/anchor-link-browser-transport](https://github.com/greymass/anchor-link-browser-transport)
- [https://github.com/greymass/eosio-signing-request](https://github.com/greymass/eosio-signing-request)

Web-based integration examples and demos can be found here:

- [https://github.com/greymass/unicove](https://github.com/greymass/unicove)
- [https://github.com/greymass/anchor-link-demo](https://github.com/greymass/anchor-link-demo)
- [https://github.com/greymass/anchor-link-demo-multipass](https://github.com/greymass/anchor-link-demo-multipass)
- [https://github.com/greymass/anchor-link-diagnostics](https://github.com/greymass/anchor-link-diagnostics)

# Greymass - The creators of Anchor

The team behind Anchor is [Greymass](https://www.greymass.com/), an imaginative team of developers and researchers who are paving the way to a better decentralized internet. Greymass created Anchor after identifying a need within the ecosystem for an easy to use and secure digital authenticator. Greymass is a 100% employee owned Canadian corporation responsible for the creation of a number of products besides Anchor, including:

- [Unicove](https://unicove.com), an open source web wallet interface designed to help users manage their accounts, tokens, and more.
- [Wharf](https://wharfkit.com), a software development kit for web developers building Antelope-based web applications.
- Roborovski, a scalable and fast blockchain solution providing transaction history.
- Fuel, a service which automatically provides network resources to users to help them more easily perform transactions.
- and much more...

All the open source products, services, and SDKSs Greymass has created over the years is [available on Github](https://github.com/greymass).

# The AnchorLink plugin for Unity3D, Standard .NET and C#

A native integration compatible with Unity3D and C# allowing users and developers to connect and communicate with the Anchor Wallet and ESR-based applications. The Anchor and ESR integration consists of multiple libraries for the ESR-Protocol, the Anchor-integration, Transports among others, which will be included via submodules while packaged and published as a single UnityPackage. 

{% embed url="https://github.com/liquiidio/AnchorLinkSharp" %}
Anchor Link Unity Plugin
{% endembed %}
