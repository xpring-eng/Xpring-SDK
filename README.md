

*Read this in other languages: [日本](README-ja.md).*

# Introduction
Xpring SDK is a set of libraries and services designed to make interaction with protocols from Xpring easy and intuitive. Xpring SDK works consistently across languages and platforms to create a cohesive development experience, regardless of the language, platform, or environment you are building your app in.

## Protocol Support

Xpring SDK integrates with the following protocols:
- [XRP Ledger](https://xrpl.org): The XRP Ledger is a decentralized cryptographic ledger, powered by a network of peer-to-peer servers.
- [PayID](https://payid.org): A better way for your users to send and receive payments.
- [Interledger Protocol](https://interledger.org): An open protocol suite for sending payments across different ledgers.

### Libraries

Xpring SDK provides commonly used functionality for the XRP Ledger, PayID and Interledger Protocol (ILP). Functionality and programming paradigms are common across all libraries in Xpring SDK.

Xpring SDK provides the following features when used with the XRP Ledger protocol:
- Wallet generation and derivation (Seed-based or HD Wallet-based)
- Address validation
- Account balance retrieval
- Sending XRP payments
- Transaction Status
- Payment History

Xpring SDK provides the following features when used with Interledger protocols:
- Sending payments
- Checking account balance

Xpring SDK is available in the following languages:
- Java: [Xpring4j](https://github.com/xpring-eng/xpring4j)
- Swift: [XpringKit](https://github.com/xpring-eng/xpringkit)
- JavaScript: [Xpring-JS](https://github.com/xpring-eng/xpring-js)

### Remote Node

Xpring SDK connects to a remote [rippled node](https://github.com/ripple/rippled) or [Interledger node](https://github.com/xpring-eng/hermes-ilp).

Xpring recommends users of the SDK run their own nodes. However, Xpring recognizes that users may want to rapidly prototype without running their own infrastructure. As a result, we run the following public nodes which users can connect to:


```
# rippled
## Mainnet
main.xrp.xpring.io:50051         # Outside of a browser
https://envoy.main.xrp.xpring.io # Inside of a browser

## Testnet
test.xrp.xpring.io:50051         # Outside of a browser
https://envoy.test.xrp.xpring.io # Inside of a browser

# ILP
## Testnet
hermes-envoy-test.xpring.io
```

## Roadmap

Over time Xpring will work with the community, developers, and partners to expand the feature set to fulfill the needs of apps in the ecosystem. Xpring will also expand support to more languages and platforms in the near future.

If you have a use case or feature request not fulfilled by Xpring SDK, feel free to ask over at the [Xpring Forum](https://forum.xpring.io).
