
# Awesome NEAR [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list by NEARCatalog of awesome frameworks, libraries, software, and resources on NEAR.

<img src="https://user-images.githubusercontent.com/46699230/155927021-1567bbfc-f870-4ce0-a7e0-1d227a64563c.svg" width="150">

## Contents:

- [Categories](#categories)
    - [Smart Contract SDK 🔧](#smart-contract-sdk-)
    - [Wallets & Frontend Libs 💼](#wallets--frontend-libs-)
    - [Tools & SDKs 🛠️](#tools--sdks-)
    - [DeFi 💰](#defi-)
    - [Chain Abstraction 🔄](#chain-abstraction-)
    - [AI 🧠](#ai-)
    - [Validators / RPCs 🔍](#validators--rpcs-)
    - [Decetralized Storage 📦](#decetralized-storage-)
    - [Indexer 📊](#indexer-)
    - [NFT 🖼️](#nft-)
    - [DAO & Social platforms 🏛️](#dao--social-platforms-)
    - [Oracle 🔮](#oracle-)
    - [Linkdrop 🔗](#linkdrop-)
    - [Payment 💳](#payment-)
    - [Game Frameworks 🎮](#game-frameworks-)
    - [Resources & Tutorials 📚](#-resources--tutorials)
- [Contribute](#contribute)


## Categories


#### Smart Contract SDK 🔧

- [near-sdk-rs](https://github.com/near/near-sdk-rs)
- [near-sdk-js](https://github.com/near/near-sdk-js)


#### Wallets & Frontend Libs 💼

- [Intear Wallet](https://github.com/INTEARnear/wallet) - An open-source NEAR wallet.  
- [My NEAR Wallet](https://github.com/mynearwallet/my-near-wallet) - Web wallet for NEAR Protocol which stores keys in browser's localStorage
- [near-contract-helper](https://github.com/near/near-contract-helper) - Micro-service used by NEAR Wallet to store & send recovery methods

- [NEAR wallet Selector](https://github.com/near/wallet-selector) - This is a wallet selector modal that allows users to interact with NEAR dApps with a selection of available wallets.
- [HOT Wallet Connector](https://github.com/AZbang/hot-connector) - An easily upgradeable, secure and lightweight wallet connector for the NEAR blockchain
- [near-kit](https://github.com/r-near/near-kit) - TypeScript library for interacting with NEAR Protocol - simple, type-safe, and intuitive
- [NEAR Mobile Wallet](https://github.com/Peersyst/near-mobile-wallet) - Opensource repo of NEAR Mobile - the on-the-go solution for all things NEAR Protocol. 

- [fastintear](https://github.com/elliotBraem/fastintear) - Simple, intuitive JavaScript library for interacting with the NEAR Protocol blockchain
- [near-sign-verify](https://github.com/elliotBraem/near-sign-verify) - Create and validate NEP-413 signed messages for API authentication.
- [better-near-auth](https://github.com/elliotBraem/better-near-auth) - Sign in with NEAR (SIWN) plugin for Better Auth

- [near-api-js](https://github.com/near/near-api-js)
- [near-api-go](https://github.com/aurora-is-near/near-api-go)
- [near-api-py](https://github.com/near/near-api-py)
- [near-api-swift](https://github.com/near/near-api-swift)


#### Tools & SDKs 🛠️

- [NEAR CLI](https://github.com/near/near-cli-rs) - NEAR CLI is your human-friendly companion that helps to interact with NEAR Protocol from command line.
- [NEAR Explorer List](https://explorer.near.org/)
- [inindexer](https://github.com/INTEARnear/inindexer) - A framework for indexers in Rust.  
- [Near TGI](https://github.com/INTEARnear/Tear/tree/main/near-tgi) - Port of near-cli-rs to Telegram.  
- [inevents-websocket-client](https://github.com/INTEARnear/inevents) - WebSocket client library for inevents WebSocket API (Rust, TypeScript).  
- [near-min-api](https://github.com/INTEARnear/wallet/tree/main/near-min-api) - Portable Rust crate for interacting with RPC, works on WASM.  
- [NEAR Core Contracts]() - Core contracts: reference staking pool, lockup, voting, whitelist, multisig.

- [py-near](https://github.com/pvolnov/py-near) - Python high-level framework for NEAR Protocol

- [near-workspaces-rs](https://github.com/near/workspaces-rs) - Write tests once, run them both on NEAR TestNet and a controlled NEAR Sandbox local environment via Rust
- [near-workspaces-js](https://github.com/near/workspaces-js) - Write tests once, run them both on NEAR TestNet and a controlled NEAR Sandbox local environment via JS

- [NEAR Devportal toolbox](https://dev.near.org/tools?tab=ft) - Quickly create Fungible Token, NFT, Linkdrop, or DAO contracts through a simple web UI. 
- [NEAR Protocol TypeScript RPC Client](https://github.com/near/near-jsonrpc-client-ts) - An automated, type-safe TypeScript client for NEAR Protocol's JSON-RPC API, generated from the official OpenAPI specification.

#### DeFi 💰

- [Rhea Finance DEX](https://github.com/ref-finance/ref-contracts)
- [Lending contract](https://github.com/NearDeFi/burrowland)

- [Meta Pool](https://github.com/Meta-Pool/liquid-staking-contract) - a LST protocol on NEAR
- [rNEAR from Rhea Finance](https://github.com/ref-finance/rnear-contract) - a LST protocol on NEAR
- [LiNEAR Protocol](https://github.com/linear-protocol) - a LST protocol on NEAR
- [DEX Aggregator API](https://docs.intear.tech/docs/dex-aggregator/) - The Intear DEX Aggregator provides optimal trading routes across multiple decentralized exchanges on the NEAR blockchain, ensuring users get the best prices with minimal slippage.

#### Chain Abstraction 🔄

- [chainsig.js](https://github.com/NearDeFi/chainsig.js) - A TypeScript library for handling multi-chain transactions and signatures using MPC (Multi-Party Computation).
- [NEAR-Intents](https://github.com/near/intents) - Set of contracts for the NEAR Intents project

- [Omni Bridge Docs](https://docs.near.org/chain-abstraction/omnibridge/overview) - The Omni Bridge is a multi-chain asset bridge that facilitates secure and efficient asset transfers between different blockchain networks
- [Omni Bridge TypeScript SDK](https://github.com/Near-One/bridge-sdk-js) - TypeScript SDK for seamless cross-chain token transfers using the Omni Bridge protocol
- [Omni Bridge Rust SDK](https://github.com/Near-One/bridge-sdk-rs) - Rust SDK for seamless cross-chain token transfers using the Omni Bridge protocol
- [btc-light-client-contract](https://github.com/Near-One/btc-light-client-contract) - Bitcoin light client implementation for Near Protocol
- [RainBow Bridge](https://github.com/Near-One/rainbow-bridge) - 🌈🌈🌈 NEAR <> Ethereum Decentralized Bridge


#### AI 🧠

- [Shade Agents Docs](https://docs.near.org/ai/shade-agents/introduction) - The Shade Agent Framework allows developers to build decentralized and trustless AI agents that control accounts and assets across multiple blockchains.
- [Shade Agent Template](https://github.com/NearDeFi/shade-agent-template)
- [Shade Agent JS CLI](https://github.com/NearDeFi/shade-agent-js)

- [NEAR AI Docs](https://docs.near.ai/)
- [NEAR AI](https://github.com/nearai/nearai)
- [private-ml-sdk](https://github.com/nearai/private-ml-sdk)
- [near-mcp](https://github.com/nearai/near-mcp) - An MCP server for the NEAR blockchain
- [aitp](https://github.com/nearai/aitp) - AITP: Agent Interaction & Transaction Protocol
- [smart-contract-example](https://github.com/nearai/smart-contract-example) - Smart Contract with Autonomous AI Execution
- [nearai_langchain](https://github.com/nearai/nearai_langchain) - NearAI integration for LangChain

- [Bitte Staking Agent](https://github.com/INTEARnear/token-agent) - AI agent for staking, unstaking, seeing your staking information. 
- [Awesome Bitte](https://github.com/BitteProtocol/awesome-bitte) - List of Awesome Resources built on top of Bitte Protocol

- [AI Oracles](https://github.com/INTEARnear/oracle/tree/main/crates) - GPT-4o centralized, GPT-4o through Reclaim Protocol, Near AI inference oracles.  
- [AI Moderator](https://github.com/INTEARnear/Tear/tree/main/ai-moderator) - Telegram Bot that has an AI Moderation feature.  


#### Validators / RPCs 🔍

- [Introduction](https://docs.near.org/docs/develop/node/intro/what-is-a-node)
- [Run a Validator Node](https://near-nodes.io/validator/compile-and-run-a-node) 
- [Running NEAR node, Step2step guide by LearnNEARClub](https://learnnear.club/how-to-run-a-near-validator-node/)

#### Decetralized Storage 📦

- [Use Decentralized Storage Solutions with NEAR](https://docs.near.org/docs/concepts/storage-solutions)

#### Indexer 📊

- [NEAR Data Server by FASTNEAR](https://github.com/fastnear/neardata-server) - Serves historical NEAR data with some caching
- [NEAR Indexer](https://github.com/near/near-indexer-for-explorer)
- [The Graph](https://thegraph.com/docs/en/supported-networks/near)
- [intear-events](https://docs.intear.tech/docs/events-api/) - Realtime HTTP + WebSocket API framework with 25+ built-in events.
- [inindexer](https://github.com/INTEARnear/inindexer) - A framework for indexers in Rust	
- [price-indexer](https://github.com/INTEARnear/price-indexer) - Indexes prices of (almost) all tokens, adds new tokens automatically


#### NFT 🖼️

- [NFT example](https://github.com/near-examples/NFT)
- [Paras NFT Marketplace Codebase](https://github.com/ParasHQ/paras-marketplace-contract) - An Open source NFT Marketplace 
- [Mintbase Codebase](https://github.com/Mintbase/mintbase-core) - An Open source NFT Marketplace
- [TenK](https://github.com/TENK-DAO/tenk) - Template for making a NFT contract with a raffle of tokens

#### DAO & Social platforms 🏛️

- [SputnikDAO](https://github.com/near-daos/sputnik-dao-contract)
- [Nearn](https://github.com/NEAR-DevHub/nearn) - An open source platform connecting crypto founders with elite talent to create bounties, and accelerate project completion
- [SHITZU Apes](https://github.com/Shitzu-Apes) - Opensource repos of Shitzu - the memecoin community building NEAR apps & infras  

#### Oracle 🔮

- [NEAR Oracles](https://docs.near.org/primitives/oracles)
- [price-oracle](https://github.com/NearDeFi/price-oracle) - Basic implementation of a price oracle for a set of trusted parties
- [Intear Oracle](https://github.com/INTEARnear/oracle) - Decentralized data marketplace that uses Yielded Execution	


#### Linkdrop 🔗

- [NEAR Linkdrop](https://github.com/near/near-linkdrop)
- [Linkdrop Campaign](https://github.com/NEAR-labs/contracts.near-linkdrop)
- [NFT Linkdrop](https://github.com/web3gamesofficial/web3games-near-nftdrop)
- [Linkdrop Proxy](https://github.com/near-apps/linkdrop-proxy)

#### Payment 💳

- [Tearpay](https://github.com/INTEARnear/TearPay) -  accept crypto payments on 12+ blockchains, and receive the payments automatically converted to USDC on NEAR.


#### Game Frameworks 🎮

- [unity](https://github.com/metaseed-project/metaseed-unity-toolkit)
- [godot](https://github.com/svntax/godot-near-sdk)


#### 📚 Resources & Tutorials

- [How to Run Localnet/Devnet on NEAR Protocol 🦀](https://t.me/NEARDevHub/522) - Want to test smart contracts without touching mainnet? This step-by-step guide shows you how to set up your own localnet/devnet for NEAR — fast, private, and 100% free.

- [Hackathon Resources](https://devhub.near.page/devhub.near/widget/app?page=blogv2&id=hackathon-resources-for-redacted-lsy0pp&community=developer-dao)

- [NEARCatalog](https://nearcatalog.xyz/) - Explorer NEAR Projects

- [near-protocol-reward](https://github.com/near-horizon/near-protocol-rewards) - Build. Ship. Get Rewarded. A transparent, on-chain rewards program for NEAR builders. Where activity and impact earn you real incentives.

- [NEAR Dev Newsletter](https://dev.near.org/newsletter) - This is NEAR Dev NEWS — your weekly scoop on ecosystem updates, dev tools, freelance gigs, and events around the NEAR Protocol. Let’s dive in.

- [NEARWEEK Newsletter](https://nearweek.com/) - a weekly newsletter covering everything within the NEAR PROTOCOL ecosystem.

- [NEAR Opensource Contract List](https://docs.near.org/smart-contracts/contracts-list) - a collection of open-source contracts from various projects deployed on NEAR like reference staking pool, lockup, voting, whitelist, multisig and many mores.

## Contribute

Contributions are always welcome! xoxoxo! 

This is the source repo for https://NEARCatalog.xyz/awesome-near.
