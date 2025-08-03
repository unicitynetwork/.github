## 🚀 Welcome to Unicity

Welcome to **Unicity**, the first blockchain platform in which all execution is off-chain. Assets are minted off-chain, transfers happen off-chain and smart contracts or "agents" execute off-chain, and the blockchain is reduced to an infrastructure that (by enforcement of non-forking) prevents double spending of off-chain assets. 

All blockchain designs Bitcoin, Ethereum, L1s L2s, rollups, sidechains etc. have followed the same core design principle for the last 17 years. There is a an append-only shared ledger of assets with computation happening sequentially on assets in the same shared statespace, leading inevitably to competition for resources. Unicity is a fundamental redesign. All assets exist off-chain, and each asset is its own ledger with only aggregate state transitions recorded on-chain. This architectural shift unlocks off-chain computation giving orders of magnitude higher throughput and massively reduced friction for users, developers and agents.

### How to Start Mining in 5 minutes 
Generate a wallet and mining address in one click using the offline wallet here https://unicitynetwork.github.io/offlinewallet/
Download the binary or build the miner client from source here https://github.com/unicitynetwork/alpha-miner
Follow the instructions in alpha-miner to connect to a mining pool.

### Resources 
whitepaper here: https://github.com/unicitynetwork/whitepaper/releases/tag/latest

ZK bluepaper here: https://github.com/unicitynetwork/aggr-layer-paper/releases/tag/latest

block explorer here:  https://www.unicity.network/

Discord link here: https://discord.gg/PGzNZT5uVp

start building on Unicity with its [State Transition SDK](https://github.com/unicitynetwork/state-transition-sdk). 

see the tech in action by playing Quake running in a Unicity agent here https://quake.unicity.network/

The Unicity platform offers a modular architecture with distinct layers, each serving a unique role in the decentralized stack:


### 1. ⚒️ Proof of Work

Acts as the foundational trust layer, anchoring the entire system. New coins are mined and can be extracted for use in higher layers such as Agent Execution. A Bitcoin fork using the **RandomX** hash function and a **2-minute block time**.

- 🔗 [Unicity Alpha](https://github.com/unicitynetwork/alpha) (full node implementation, C++)
- 🔗 [Alpha-miner](https://github.com/unicitynetwork/alpha-miner) (mining software for mining Unicity's native Alpha)
- 🔗 [Block explorer](https://www.unicity.network/)

---

### 2. ⛓️ BFT Consensus

Provides fast (1-second rounds) Byzantine Fault Tolerant consensus to anchor the Proof Aggregation Layer. It periodically commits state roots to the Proof of Work chain.

- 🔗 [eth-unicity-anchor](https://github.com/unicitynetwork/eth-unicity-anchor)  
- 🔗 [Unicity Core](https://github.com/unicitynetwork/unicity-core) (Golang)

---

### 3. 🌲 Proof Aggregation / Trustless SMT

Implements Sparse Merkle Trees and Distributed Hash Trees with optional zero-knowledge proofs for non-deletion. Enables efficient, trust-minimized aggregation.

- 🔗 [Aggregators Net](https://github.com/unicitynetwork/aggregators_net) (TypeScript)  
- 🔗 [Prefix Hash Tree](https://github.com/unicitynetwork/prefix-hash-tree) (JavaScript)  
- 🔗 [ND-SMT](https://github.com/unicitynetwork/nd-smt) (Python / Circom)

---

### 4. 💱 State Transition

Start building on Unicity with the **State Transition SDK** - for managing assets on the Unicity Protocol, supporting off-chain state with on-chain security guarantees. The State Transition SDK is a TypeScript library that provides an off-chain token transaction framework. Tokens are managed, stored, and transferred off-chain with only cryptographic commitments published on-chain, ensuring privacy while preventing double-spending through single-spend proofs.

- 🔗 [State Transition SDK](https://github.com/unicitynetwork/state-transition-sdk) (TypeScript)

---

### 5. 🤖 Agent Execution

Agent SDK provides a framework for the development, deployment and composability of verifiable off-chain Turing-complete computations. The SDK delivers APIs facilitating agnostic verifiable discovery, addressing, communication, storage and execution environment. Currently in prototyping phase using **Yjs** and **Holepunch**.

- 🚧 *Coming Soon*

---

## 🗺️ Roadmap
### H1 2025
- PoW/BFT/Aggregation layers
- State Transition SDK
- Mining pools

### H2 2025 📋
- Agent SDK
- Developer subscriptions
- SMT sharding
- Cross-chain bridges
- Client side ZK

## 🤝 Community & Support

### Getting Help
- **GitHub Issues**: [Report bugs and request features](https://github.com/unicitynetwork/.github/issues)

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
