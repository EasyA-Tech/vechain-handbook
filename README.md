# The VeChain Handbook

Welcome. This is EasyA's legendary handbook. If you want to learn VeChain like a legend, then you're in the right place.

# Purpose

This handbook serves as a guide to the VeChain ecosystem, geared towards those just joining for the first time. It isn't just a beginners' handbook; it's a legendary handbook. Even if you've already immersed yourself in the ecosystem, you'll find tons of helpful tidbits around here!

# The EasyA App

Of course, the best place to start is always the [EasyA](https://www.easya.io) app! Download it here for the fastest and most fun way to learn about VeChain. Download it directly right [here](https://links.easya.io/links/gotoapp)!

## Table of Contents

- [Introduction](#introduction)
- [Getting Started](#getting-started)
- [Core Concepts](#core-concepts)
- [Development Tools](#development-tools)
- [Smart Contracts](#smart-contracts)
- [VeChain Network](#vechain-network)
- [Ecosystem Projects](#ecosystem-projects)
- [Resources](#resources)
- [Handy Code Snippets](#handy-code-snippets)
- [Contributing](#contributing)

## Introduction

What is VeChain:

- [VeChain Official Website](https://www.vechain.org/) - The go-to place for all things VeChain, including the latest news and developments.

## Getting Started

The no-fluff starter:

- [VeChain Sync](https://env.vechain.org/#sync) - A desktop application that connects you to the VeChain blockchain.
- [VeChain Insights](https://insights.vechain.org/) - A platform for viewing real-time statistics and information about the VeChain network.

## Core Concepts

Explanation of fundamental concepts in the VeChain ecosystem:

- [VeChain's Dual-Token Model](https://www.vechain.org/vechainthor-is-live/) - Learn about VET and VTHO, the two tokens that power the VeChain ecosystem.
- [Proof of Authority](https://www.vechain.org/sustainability/) - Understand VeChain's consensus mechanism that balances decentralization with efficiency.

## Development Tools

Key tools and environments for VeChain:

- [VeChain Thor](https://github.com/vechain/thor) - The official VeChain Thor blockchain client.
- [Connex](https://github.com/vechain/connex) - The standard interface to connect dApps with VeChain blockchain and users.

## Smart Contracts

How to write and deploy smart contracts on VeChain:

- [VeChain Developer Documentation](https://docs.vechain.org/) - Comprehensive guide for developing on VeChain.
- [VeChain Studio](https://studio.vechain.org/) - Browser-based IDE for writing, testing, and deploying VeChain smart contracts.

## VeChain Network

Going into the network level:

- [VeChain Stats](https://vechainstats.com/) - Real-time statistics and information about the VeChain network.
- [VeChain Explorer](https://explore.vechain.org/) - Official block explorer for the VeChain network.

## Ecosystem Projects

Cool projects built on VeChain:

- [VeChain ToolChain](https://www.vechain.com/product/toolchain) - VeChain's Blockchain-as-a-Service (BaaS) platform.
- [VeriArti](https://www.veriart.io/) - NFT platform built on VeChain.
- [VIMworld](https://vimworld.com/) - A blockchain-based collectibles platform on VeChain.

## Resources

Extra stuff:

- [VeChain Blog](https://www.vechain.org/blog/) - Official blog with updates and insights into VeChain and its ecosystem.
- [VeChain Foundation Twitter](https://twitter.com/vechainofficial) - Stay updated with the latest news and announcements.

## Handy Code Snippets

Get a taste of VeChain development with these code snippets:

### Connecting to VeChain Thor

```javascript
const { Framework } = require('@vechain/connex-framework');
const { Driver, SimpleNet } = require('@vechain/connex-driver');

const net = new SimpleNet('https://sync-testnet.vechain.org');
const driver = await Driver.connect(net);
const connex = new Framework(driver);

console.log('Connected to VeChain Thor:', connex.thor.genesis.id);
```

### Creating a new account

```javascript
const { createAccount } = require('@vechain/thor-devkit');

const account = createAccount();
console.log('New account address:', account.address);
console.log('Private key:', account.privateKey);
```

These examples showcase:
1. How to connect to the VeChain Thor network.
2. How to create a new VeChain account.

## Contributing

We welcome contributions to make this handbook even more legendary! Here's how you can contribute:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/amazing-addition`)
3. Make your changes
4. Commit your changes (`git commit -am 'Add some amazing feature'`)
5. Push to the branch (`git push origin feature/amazing-addition`)
6. Create a new Pull Request

Please ensure your contributions align with our code of conduct and contribution guidelines.

## Credit/Inspiration

This handbook was inspired by the famous awesome lists by sindresorhus and the Awesome VeChain list. We need awesome lists for Web3 ecosystems, with more of a hacker's guide to how they work. This is the answer to that need.
