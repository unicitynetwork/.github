## 🚀 Welcome to Unicity - The Autonomous Agentic Internet

**Unicity** is the first blockchain platform designed for the **Autonomous Agentic Internet** - a new digital paradigm where AI agents, not just humans, are the primary economic actors. 

In this new era, agents require more than just payment rails; they need a verifiable, trustless environment to execute complex logic, manage state, and interact with the world. Unicity solves the scalability and privacy bottlenecks of traditional blockchains by shifting **all execution off-chain**, leaving the blockchain to serve as a pure trust anchor. 

Get started with [**Unicity AgentSphere**](https://sphere.unicity.network/) - a multifunctional Web3 platform with integrated crypto wallet, specialized AI agents, and P2P functionality.

### Why Unicity?
* **Off-Chain Execution**: the agent logic runs entirely off-chain, ensuring unlimited scalability and privacy.
* **On-Chain Security**: the blockchain anchors state transitions, preventing double-spending and ensuring finality without executing the logic itself.
* **Verifiable Agents**: the Agent Execution Layer provides a framework for verifiable, Turing-complete computations, allowing agents to act autonomously with cryptographic proofs of validity.

### Resources

#### Documentation & Papers
* 📄 **[Whitepaper](https://github.com/unicitynetwork/whitepaper/releases/download/latest/Unicity.pdf)**
* 📘 **[Technical Yellowpaper](https://github.com/unicitynetwork/unicity-yellowpaper-tex/releases/download/latest/unicity-yellowpaper.pdf)**, **[ZK Bluepaper](https://github.com/unicitynetwork/aggr-layer-paper/releases/download/latest/aggregation-layer.pdf)**
* 🎓 **[Unicity Execution Model](https://github.com/unicitynetwork/execution-model-tex/releases/download/latest/unicity-execution-layer.pdf)**, **[Unicity Programming: Predicates and Atomic Swaps](https://github.com/unicitynetwork/unicity-predicates-tex/releases/download/latest/unicity-predicates.pdf)** (formal papers with security proofs)
* ❓ **[Unicity FAQ](https://docs.google.com/document/d/1cQ2Zom5zfk5HXj0fRlysYDarj245fIqO4sPfDYPCcTc/)**
* 📖 **[Glossary](https://docs.google.com/document/d/1-6kmf5SqxGuQJGbtJ7wzUnBM7p8N8WsFgtFNH2x384A/)**
* 👾 **[Ask Viktor](https://sphere.unicity.network/#/agents/ai)** (chatbot with Unicity knowledge)

#### Tools & Ecosystem
* 🌅 **[Official Website](https://www.unicity.ai/)**
* ✨ **[Unicity AgentSphere](https://sphere.unicity.network/)**
* 🔍 **[Block Explorer](https://unicity.network/)**
* 👛 **[Web Wallet](https://unicitynetwork.github.io/webwallet/)**
* 🛠️ **[Start Building (Sphere SDK)](https://github.com/unicity-sphere/sphere-sdk)**
* 🛠️ **[Start Building (JS SDK)](https://github.com/unicitynetwork/state-transition-sdk)**
* 📊 **[Pitch Deck](https://unicity-aai-61djl4q.gamma.site/)**

#### Community
* 🐦 **[Follow us on X (@unicity_labs)](https://x.com/unicity_labs)**
* 📺 **[Subscribe to our YouTube channel](https://www.youtube.com/@unicity-labs)**
* 📖 **[Join Unicity Discord](https://discord.gg/PGzNZT5uVp)**

## 🏗️ Modular Architecture

Main Unicity components designed to power the agent economy:

### 1. ⚒️ Proof of Work
The foundational trust layer anchoring the entire system.
* **Role**: Provides immutable security and prevents history rewriting.
* **Tech**: A Bitcoin fork using the RandomX PoW function.
* **Key Repo**: [`unicity-pow`](https://github.com/unicitynetwork/unicity-pow)

### 2. ⛓️ BFT Consensus
Provides fast, Byzantine Fault Tolerant consensus to anchor the aggregation layer.
* **Role**: Commits state roots with fast 1-second finality.
* **Tech**: Custom BFT implementation (Golang).
* **Key Repo**: [`bft-core`](https://github.com/unicitynetwork/bft-core)

### 3. 🌲 Proof Aggregation
Implements Trustless Sparse Merkle Trees (SMT) and Distributed Hash Trees (DHT).
* **Role**: Enables efficient, trust-minimized aggregation of off-chain states.
* **Tech**: Proofs for non-deletion and efficient state commitments.
* **Key Repo**: [`aggregator-go`](https://github.com/unicitynetwork/aggregator-go)

### 4. 💱 State Transition SDKs
A framework for managing assets off-chain with on-chain security guarantees.
* **Role**: Tokens are managed, stored, and transferred off-chain. Only cryptographic commitments are published on-chain to prevent double-spending.
* **Key Repos**: [`TypeScript`](https://github.com/unicitynetwork/state-transition-sdk) | [`Java`](https://github.com/unicitynetwork/java-state-transition-sdk) | [`Rust (Experimental)`](https://github.com/unicitynetwork/rust-state-transition-sdk)

### 5. 🤖 Unicity Orchestrator
The runtime for the Autonomous Agentic Internet. 
* **Role**: A knowledge graph-based orchestrator for Model Context Protocol (MCP) services with advanced tool discovery and symbolic reasoning capabilities (Unicity Orchestrator).
* **Capabilities**: Agnostic verifiable discovery, addressing, communication, storage, and execution environments for AI agents.
* **Key Repo**: [`Unicity Orchestrator`](https://github.com/unicitynetwork/unicity-orchestrator)

### 6. ✨ Unicity AgentSphere
A multifunctional Web3 platform with integrated crypto wallet, specialized AI agents and P2P functionality.
* **Role**: Unicity AgentSphere is a modern decentralized application built on the concept of agents — specialized AI interfaces for various activities: sports betting, gaming, merchandise shopping, P2P crypto trading, trivia, direct messaging, AI assistance, etc.
* **Key Repos**: [`AgentSphere`](https://github.com/unicity-sphere/sphere) | [`Sphere SDK`](https://github.com/unicity-sphere/sphere-sdk)

---

## 🚀 Get Started

### How to Start Mining in 5 minutes 
1. Generate a wallet and mining address with Unicity Web Wallet here: https://unicitynetwork.github.io/webwallet/
2. Download the binary or build the miner client from source here https://github.com/unicitynetwork/alpha-miner
3. Follow the [instructions how to connect to a mining pool](https://github.com/unicitynetwork/alpha-miner?tab=readme-ov-file#pool-mining-stratum).

### For Developers
Building on Unicity means building for the future of AI commerce. Start by exploring our SDKs:

* **State Transition SDK**: [TypeScript](https://github.com/unicitynetwork/state-transition-sdk) | [Java](https://github.com/unicitynetwork/java-state-transition-sdk) | [Rust (Experimental)](https://github.com/unicitynetwork/rust-state-transition-sdk)
* [Sphere SDK](https://github.com/unicity-sphere/sphere-sdk)

## Support

### Getting Help
- **GitHub Issues**: [Report bugs and request features](https://github.com/unicitynetwork/.github/issues)
 

<p align="center">
  Built for the <b>Agentic Future</b>. <br>
  © 2026 Unicity Labs.
</p>
