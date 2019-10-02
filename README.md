# Introduction
Xpring SDK is a set of libraries and services designed to make interaction with Xpring easy and intuitive. Xpring SDK works consistently across languages and platforms to create a cohesive development experience, regardless of the language, platform, or environment you are building your app in. 

## Architecture
The development experience is comprised of two components: 
- A set of language-specific client-side libraries
- A server-side component that handles requests from the client-side libraries and proxies them to an XRP node

### Client-Side Libraries
Xpring SDK provides the most commonly used functionality on the XRP Ledger. Functionality and programming paradigms are common across all libraries in Xpring SDK. 

Xpring SDK provides the following features:
- Wallet generation and derivation (Seed-based or HD Wallet-based)
- Address validation
- Account balance retrieval
- Sending XRP payments

Xpring SDK is available in the following languages:
- Java: [Xpring4j](https://github.com/xpring-eng/xpring4j)
- Swift: [XpringKit](https://github.com/xpring-eng/xpringkit)
- JavaScript: [Xpring-JS](https://github.com/xpring-eng/xpring-js) 

### Server-Side Component
The server-side component sends client-side requests to an XRP Node. 

To get developers started right away, Xpring currently provides the server side component as a hosted service, which proxies requests from client side libraries to an XRP Node. Developers can reach the endpoint here: `grpc.xpring.tech:80`

Xpring is working on building a zero-config way for XRP node users to deploy and use the adapter as an open-source component of [rippled](https://github.com/ripple/rippled). Watch this space!

## Roadmap

Over time Xpring will work with the community, developers, and partners to expand the feature set to fulfill the needs of apps in the ecosystem. Xpring will also expand support to more languages and platforms in the near future. 
