## 🚀 Welcome to Unicity

**Unicity** is a multi-layered developer platform designed for building, deploying, and orchestrating off-chain peer-to-peer applications. It offers a modular architecture with distinct layers, each serving a unique role in the decentralized stack:

### 🔷 Layer Overview

1. **Proof of Work Genesis**  
2. **BFT Consensus Layer**  
3. **SMT Aggregation / ZK Prover Layer**  
4. **Token State Transition Layer**  
5. **Agent Execution Layer**

---

### 1. ⚒️ Proof of Work Trust Anchor

Acts as the foundational trust layer, anchoring the entire system. New coins are mined and can be extracted for use in higher layers such as Agent Execution.  
A Bitcoin fork using the **RandomX** hash function and a **2-minute block time**.

- 🔗 [Unicity Alpha](https://github.com/unicitynetwork/alpha) (C++)

---

### 2. ⛓️ BFT Consensus Layer

Provides fast (1-second rounds) Byzantine Fault Tolerant consensus to anchor the Proof Aggregation Layer. It periodically commits state roots to the Proof of Work chain.

- 🔗 [eth-unicity-anchor](https://github.com/unicitynetwork/eth-unicity-anchor)  
- 🔗 [Unicity Core](https://github.com/unicitynetwork/unicity-core) (Golang)

---

### 3. 🌲 Proof Aggregation / Trustless SMT Layer

Implements Sparse Merkle Trees and Distributed Hash Trees with optional zero-knowledge proofs for non-deletion. Enables efficient, trust-minimized aggregation.

- 🔗 [Aggregators Net](https://github.com/unicitynetwork/aggregators_net) (TypeScript)  
- 🔗 [Prefix Hash Tree](https://github.com/unicitynetwork/prefix-hash-tree) (JavaScript)  
- 🔗 [ND-SMT](https://github.com/unicitynetwork/nd-smt) (Python / Circom)

---

### 4. 💱 Token State Transition Layer

Handles application-specific token state transitions with full SDK support for defining, validating, and applying rules.

- 🔗 [State Transition SDK](https://github.com/unicitynetwork/state-transition-sdk) (TypeScript)

---

### 5. 🤖 Agent Execution Layer

Enables off-chain execution of logic and stateful behavior via peer-to-peer agents. Currently in prototyping phase using **Yjs** and **Holepunch**.

- 🚧 *Coming Soon*




<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
