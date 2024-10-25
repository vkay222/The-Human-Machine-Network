# Glossary <!-- omit in toc -->

## Table of Contents <!-- omit in toc -->

- [Core Concepts](#core-concepts)
- [Architecture Layers](#architecture-layers)
- [Technical Terms](#technical-terms)
- [AI and Agent Concepts](#ai-and-agent-concepts)
- [Blockchain and Tokenomics](#blockchain-and-tokenomics)
- [Governance and Decision-Making](#governance-and-decision-making)
- [Related Technologies](#related-technologies)

---

## Core Concepts

### HMN (Human-Machine Network)

A system that operates through three abstraction layers to facilitate human-machine interaction and governance. The HMN
integrates human decision-making with autonomous AI agents, leveraging blockchain technology, zero-knowledge proofs,
and advanced voting mechanisms to create a decentralized, scalable, and privacy-preserving governance framework.

### Polycentric Governance Levels

A hierarchical structure of governance domains within the HMN, ranging from individual to global levels, including
various interpersonal associations. This structure allows for nuanced decision-making and ensures that topics and
proposals are addressed at the appropriate scale.

## Architecture Layers

### Human Input Layer

The foundational layer responsible for collecting human input such as governance proposals, ideas, and decisions. It
utilizes Succinct Non-interactive Arguments of Knowledge (SNARKs) to ensure data privacy and verifiable correctness.

### Modular DAO Layer

The processing layer that integrates governance logic into decision-making workflows. It aggregates encrypted inputs
from the Human Input Layer, applies predefined governance rules, and generates executable commands for agents.

### Execution Layer

The implementation layer where autonomous AI agents utilize Zero-Knowledge Virtual Machines (zkVMs) to execute
governance directives in a secure environment.

## Technical Terms

### BFT (Byzantine Fault Tolerance)

A characteristic of a distributed system that allows it to continue operating correctly even when some nodes fail or
act maliciously.

### SNARK (Succinct Non-interactive Argument of Knowledge)

A form of zero-knowledge proof that allows one party to prove possession of certain information to another party
without revealing the information itself.

### zkVM (Zero-Knowledge Virtual Machine)

A virtual machine that can execute computations while maintaining data privacy through zero-knowledge proofs.

### Mirror Objects

On-chain representations of off-chain AI resources (models, data, computation) in the HMN, inspired by the Talus network.

### Consensus Gadget

A component in the Autonolas framework that implements a protocol allowing a set of agents to reach agreement on one or
more variables.

### ABCI (Application BlockChain Interface)

An interface that defines the boundary between the consensus engine and the state machine in blockchain applications.

## AI and Agent Concepts

### AI Agent Collectives

Structured groups of specialized AI agents that collaborate on complex tasks, enhancing the system's problem-solving capabilities.

### Aggregator Agents

Specialized agents responsible for coordinating workflows and managing budgets within AI Agent Collectives.

### Evaluator Agents

Dedicated agents for assessing collective performance and generating Proofs of Contribution.

### Optimizer Agents

Specialized agents focused on improving collective composition and producing Proofs of Collaboration.

### Proof of Contribution

A verifiable certificate that ensures the authenticity and integrity of the evaluation process for AI agents.

### Proof of Collaboration

An on-chain record of a Collective's membership optimization process, ensuring its authenticity and integrity.

### Swarm Intelligence

A collective behavior of decentralized, self-organized systems, natural or artificial, applied to AI agent collectives
for efficient problem-solving.

### Personal AI Agents

Intelligent assistants that represent individual users' interests and participate in governance processes within the HMN.

### Topic Board

A dynamic system for submitting, prioritizing, and managing governance topics in the HMN.

### Reputation System

A multi-dimensional scoring system that reflects users' expertise and contributions within the HMN.

### Member Agents

Specialized agents within AI Agent Collectives that focus on specific tasks or areas of expertise.

## Blockchain and Tokenomics

### IBC (Inter-Blockchain Communication)

A protocol that enables communication and asset transfer between different blockchain networks.

### Protocol-Owned Services (PoSe)

Services owned and operated by the protocol itself, with profits contributing to the protocol treasury.

### Protocol-Owned Liquidity (PoL)

Liquidity owned by the protocol, which can be deployed to generate returns or invest in protocol-owned services.

### Bonding Mechanism

A process where users provide liquidity in exchange for protocol tokens at a discount, contributing to protocol-owned liquidity.

### veToken Model

A token model where users lock tokens for extended periods to gain voting rights and other benefits, encouraging
long-term alignment with the protocol.

### HMNX

The native token of the Human-Machine Network, used for voting, staking, rewards, and accessing network resources.

### Dynamic Resource Allocation

Market-driven pricing for computational resources and AI services within the HMN.

## Governance and Decision-Making

### Liquid Democracy

A form of delegative democracy where participants can either vote directly on issues or delegate their voting power to
trusted representatives.

### Quadratic Voting

A collective decision-making procedure where participants can express the intensity of their preferences, with the cost
of votes increasing quadratically.

### Futarchy

A governance system that uses prediction markets to select policies based on their forecasted outcomes.

## Related Technologies

### Solidity

The primary programming language used for implementing smart contracts in Ethereum-based blockchains.

### Zero-Knowledge Proofs

Cryptographic methods allowing one party to prove to another that a statement is true without revealing the underlying information.

### Move

A programming language developed by Facebook for writing safe smart contracts, used in the Sui blockchain.

### Tendermint

A Byzantine Fault Tolerant (BFT) consensus engine that can be used as a basis for blockchain applications.

### IPFS (InterPlanetary File System)

A protocol and peer-to-peer network for storing and sharing data in a distributed file system.

### Filecoin

A decentralized storage network that turns cloud storage into an algorithmic market, enabling the creation of a
decentralized alternative to centralized cloud storage providers.

### Arweave

A decentralized storage network that aims to offer permanent data storage through a novel consensus mechanism called
Proof of Access.

### zkSync Era

An Ethereum Layer-2 scaling solution that uses zero-knowledge proofs to increase throughput and reduce gas fees while
maintaining the security of the Ethereum mainnet.

### Chainlink

A decentralized oracle network that provides real-world data to smart contracts on the blockchain, enabling them to
interact with off-chain systems.

### Optimistic Rollups

A Layer-2 scaling solution for Ethereum that assumes transactions are valid by default and only runs computation, via a
fraud proof, in the event of a challenge.

### DAG (Directed Acyclic Graph)

A data structure used in some blockchain systems as an alternative to the traditional blockchain, allowing for
potentially higher scalability and faster transaction confirmation times.

### Plasma

A framework for building scalable applications on Ethereum using child chains, which process transactions off the main
Ethereum chain but derive security from it.

### State Channels

A scaling solution that allows participants to conduct multiple transactions off-chain while only submitting two on-chain
transactions to the Ethereum network.

### Sharding

A scaling technique that partitions a blockchain network into smaller parts called shards, allowing for parallel
transaction processing and increased throughput.

### Polkadot

A multi-chain network that allows for interoperability between different blockchain networks, facilitating the transfer
of any type of data or asset across chains.

### Cosmos

An ecosystem of blockchains that can scale and interoperate with each other, aiming to solve problems of scalability,
usability, and interoperability in blockchain.

### The Graph

A decentralized protocol for indexing and querying blockchain data, making it easier for developers to build and deploy
decentralized applications.

### Ceramic Network

A decentralized data network that allows for the creation of tamper-proof and time-stamped streams of data, enabling
developers to build decentralized applications with rich, dynamic data.
