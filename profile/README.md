## 🚀🚀🚀 Welcome to Unicity 🚀🚀🚀


Unicity is a mult-layered developer platform for building, deploying and orchestrating off-chain crypto agents. 

	
						1. Proof of Work Trust Anchor
						2. BFT Consensus Layer 
						3. Proof Aggregation Layer
						4. State Transition Layer 
						5. Agent Execution Layer
						6. Agent Orchestration Layer


### Proof of Work Trust Anchor ###
Anchors the second layer and provides new coins through mining which can then be extracted and used off-chain in the Agent layers. Fork of Bitcoin with RandomX hash function, 2 min block times. Written in C++
https://github.com/unicitynetwork/alpha


### BFT Consensus Layer ###
Chained Hotstuff implementation of BFT Consensus. Anchors the Proof Aggregation Layer with one second rounds. Periodically publishes state root in Proof of Work layer. Written in Golang
https://github.com/unicitynetwork/unicity-core
https://github.com/unicitynetwork/unicity-go-base

### BFT Proof Aggregation Layer/ Trustless SMT Accumulator ###
Proof Aggregation Layer: Distributed Hash Tree and Spase Merkle Tree implementations with and without with ZK Proof of non-deletion 


https://github.com/unicitynetwork/prefix-hash-tree
Data structures for prefix hash tree. Written in JavaScript

https://github.com/unicitynetwork/aggregators_net
API for communication between aggregator layer and agent layer. Written in javascript

https://github.com/unicitynetwork/nd-smt
SMT with Compact non-deletion proof. Written in Python/Circom


### State Transition Layer ###

Implementation of agent state transitions. A transaction flow runtime facilitates and verifies an agent transition from a state to another one according to application-specific rules. In order to perform a state transition, one has to provide to the runtime current state and the input (for instance, signature to unlock a given state, address representing the destination state and all sorts of auxiliary data needed to authorize transition to the new state).

https://github.com/unicitynetwork/tx-flow-engine
written in Javascript


###Agent Execution Layer ###
Under development

###Agent Orchestration Layer ###
Under development 






<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
