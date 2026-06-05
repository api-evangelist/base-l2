# Base (base-l2)

Base is Coinbase's Ethereum Layer 2 network built on the OP Stack and part of the Optimism Superchain. It exposes a standard Ethereum JSON-RPC interface for smart contracts and dApps, plus higher-level developer surfaces including Base Account (Smart Wallet, Sub Accounts, passkeys, paymaster-sponsored transactions), OnchainKit React components, Mini Apps, the canonical Bridge to Ethereum, and a Solana cross- chain bridge. Block exploration is available through BaseScan and Blockscout.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/base-l2/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/base-l2/refs/heads/main/apis.yml)

## Tags

- Layer 2
- Ethereum
- OP Stack
- Superchain
- JSON-RPC
- Smart Wallet
- Bridge

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-23

## APIs

### Base Mainnet JSON-RPC

Standard Ethereum JSON-RPC endpoint for Base Mainnet (chain ID 8453). Supports eth_*, net_*, web3_*, and Optimism-specific extensions for fee estimation and L1 messaging. The public endpoint is rate-limited and not recommended for production; teams typically front it with Alchemy, QuickNode, Infura, Coinbase Developer Platform, or self-hosted op-geth + op-node.

- **Human URL:** [https://docs.base.org/chain/network-information](https://docs.base.org/chain/network-information)
- **Base URL:** `https://mainnet.base.org`

#### Tags

- JSON-RPC
- Mainnet
- EVM

#### Properties

- [Documentation](https://docs.base.org/chain/network-information)
- [Postman Collection](collections/base-l2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/base-l2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Base Sepolia JSON-RPC

Public JSON-RPC endpoint for the Base Sepolia testnet (chain ID 84532) used for development, contract deployment, and integration testing.

- **Human URL:** [https://docs.base.org/chain/network-information](https://docs.base.org/chain/network-information)
- **Base URL:** `https://sepolia.base.org`

#### Tags

- JSON-RPC
- Testnet
- Sepolia

#### Properties

- [Documentation](https://docs.base.org/chain/network-information)
- [Postman Collection](collections/base-l2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/base-l2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Base Flashblocks RPC

Pre-confirmation JSON-RPC endpoint exposing Flashblocks — sub-block streams of ordered transactions that allow apps to react to pending state with sub-second latency.

- **Human URL:** [https://docs.base.org/chain/flashblocks](https://docs.base.org/chain/flashblocks)
- **Base URL:** `https://mainnet-preconf.base.org`

#### Tags

- Flashblocks
- Pre-Confirmation
- JSON-RPC

#### Properties

- [Documentation](https://docs.base.org/chain/flashblocks)
- [Postman Collection](collections/base-l2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/base-l2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Base Bridge

Canonical cross-chain bridge between Ethereum L1 and Base L2 for depositing and withdrawing ETH and ERC-20 tokens, secured by the OP Stack bridge contracts.

- **Human URL:** [https://bridge.base.org](https://bridge.base.org)
- **Base URL:** `https://bridge.base.org`

#### Tags

- Bridge
- L1
- L2
- Canonical

#### Properties

- [Documentation](https://docs.base.org/chain/bridges-mainnet)
- [App](https://bridge.base.org)
- [Postman Collection](collections/base-l2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/base-l2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Base / Solana Bridge

Cross-chain bridge enabling asset transfers between Base and Solana, integrated into the Base ecosystem app surface.

- **Human URL:** [https://docs.base.org/chain/base-solana-bridge](https://docs.base.org/chain/base-solana-bridge)
- **Base URL:** `https://docs.base.org/chain/base-solana-bridge`

#### Tags

- Bridge
- Solana
- Cross-Chain

#### Properties

- [Documentation](https://docs.base.org/chain/base-solana-bridge)
- [Postman Collection](collections/base-l2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/base-l2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Base Account / Smart Wallet

Base Account (formerly Coinbase Smart Wallet) is an ERC-4337 smart contract wallet with passkey sign-in, sub-accounts, session keys, sponsored transactions via paymaster, and SDK + React component integrations.

- **Human URL:** [https://docs.base.org/base-account](https://docs.base.org/base-account)
- **Base URL:** `https://docs.base.org/base-account`

#### Tags

- Smart Wallet
- Account Abstraction
- ERC-4337
- Passkeys

#### Properties

- [Documentation](https://docs.base.org/base-account)
- [Website](https://www.smartwallet.dev)
- [Postman Collection](collections/base-l2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/base-l2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### OnchainKit

React component library and TypeScript SDK (@coinbase/onchainkit) for building onchain apps on Base — wallet, identity, transaction, swap, checkout, fund, and NFT components with built-in Smart Wallet and Mini App support.

- **Human URL:** [https://docs.base.org/onchainkit](https://docs.base.org/onchainkit)
- **Base URL:** `https://www.npmjs.com/package/@coinbase/onchainkit`

#### Tags

- SDK
- React
- Components
- Onchain

#### Properties

- [Documentation](https://docs.base.org/onchainkit)
- [Repository](https://github.com/coinbase/onchainkit)
- [Postman Collection](collections/base-l2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/base-l2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### BaseScan Block Explorer

Etherscan-family block explorer for Base Mainnet and Sepolia with a public contract / transaction / address API.

- **Human URL:** [https://basescan.org](https://basescan.org)
- **Base URL:** `https://api.basescan.org/api`

#### Tags

- Block Explorer
- API
- BaseScan

#### Properties

- [Documentation](https://docs.basescan.org)
- [Website](https://basescan.org)
- [Postman Collection](collections/base-l2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/base-l2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Base Blockscout Block Explorer

Blockscout-powered open-source block explorer for Base with REST and GraphQL APIs.

- **Human URL:** [https://base.blockscout.com](https://base.blockscout.com)
- **Base URL:** `https://base.blockscout.com/api`

#### Tags

- Block Explorer
- Blockscout
- API

#### Properties

- [Website](https://base.blockscout.com)
- [Postman Collection](collections/base-l2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/base-l2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.base.org)
- [Documentation](https://docs.base.org)
- [Git Hub](https://github.com/base-org)
- [GitHub Organization](https://github.com/base)
- [Status](https://status.base.org)
- [Bridge](https://bridge.base.org)
- [Ecosystem](https://www.base.org/ecosystem)
- [Twitter](https://x.com/base)
- [Discord](https://discord.gg/buildonbase)
- [Blog](https://base.mirror.xyz)
- [L L Ms Txt](https://docs.base.org/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
