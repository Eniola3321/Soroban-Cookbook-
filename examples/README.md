# Soroban Examples Index

A collection of Soroban smart contract examples organized by complexity and use case.

## 📂 Category Overview

### [Basics](./basics/)
Beginner-friendly examples that introduce core Soroban concepts one at a time.
- Hello World, Storage, Auth, Events, Errors, Types, Validation

### [Intermediate](./intermediate/)
Common patterns and more complex contract interactions.
- Multi-sig, Cross-contract calls, Custom types, Advanced storage

### [Advanced](./advanced/)
Complex systems and architectural patterns.
- Timelocks, Multi-party auth, Proxy patterns, Upgradeability

### [DeFi](./defi/)
Financial application examples and protocols.
- Automated Market Makers (AMMs), Lending, Staking, Yield farming

### [NFTs](./nfts/)
Non-fungible token implementations and patterns.
- Minting, Transfers, Metadata, Royalties

### [Governance](./governance/)
DAO and voting system examples.
- Voting, Proposals, Multi-sig governance

### [Tokens](./tokens/)
Token standards and custom token implementations.
- SEP-41, Custom tokens, Wrapper tokens

---

#### 🚀 Getting Started

To run any of these examples:

```bash
# Navigate to an example (relative to repo root)
cd examples/basics/01-hello-world

# Run tests
cargo test
```

# Build WASM
cargo build --target wasm32-unknown-unknown --release
```

## 🛠️ Requirements

- [Rust](https://www.rust-lang.org/tools/install) (stable, 1.74+)
- `wasm32-unknown-unknown` target
- [Soroban / Stellar CLI](https://developers.stellar.org/docs/tools/developer-tools/cli)
