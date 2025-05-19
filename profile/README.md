## 🚀🚀🚀 Welcome to Unicity 🚀🚀🚀


Unicity is a multi-layered developer platform for building, deploying and orchestrating off-chain P2P applications. Layers:

					1. Proof of Work Geneis 
					2. BFT Consensus Layer 
					3. ZK Prover Layer
					4. Token Operations Layer 
					5. Agent Execution Layer
				
 
1. **Proof of Work Trust Anchor**: Anchors the second layer and provides new coins through mining which can then be extracted and used off-chain in the Agent layers. Fork of Bitcoin with RandomX hash function, 2 min block times. Written in C++.
    - [Unicity Alpha](https://github.com/unicitynetwork/alpha)
2. **BFT Consensus Layer**: Anchors the Proof Aggregation Layer with one-second rounds. Periodically publishes state root in Proof of Work layer. Written in Golang.
    - [eth-unicity-anchor](https://github.com/unicitynetwork/eth-unicity-anchor)
    - [Unicity Core](https://github.com/unicitynetwork/unicity-core)
    - [Unicity Go Base](https://github.com/unicitynetwork/unicity-go-base)
4. **Proof Aggregation Layer/ Trustless SMT Accumulator**: Distributed Hash Tree and Sparse Merkle Tree implementations with and without ZK Proof of non-deletion. 
    - [Prefix Hash Tree](https://github.com/unicitynetwork/prefix-hash-tree) (JavaScript)
    - [Aggregators Net](https://github.com/unicitynetwork/aggregators_net) (JavaScript)
    - [ND-SMT](https://github.com/unicitynetwork/nd-smt) (Python/Circom)
5. **Token Operations Layer**: Implementation of agent state transitions. A transaction flow runtime facilitates and verifies an agent transition from one state to another according to application-specific rules.
    - [Transaction Flow Engine](https://github.com/unicitynetwork/tx-flow-engine) (JavaScript)
6. **Agent Execution Layer**: Prototyping using yjs, holepunch








<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
