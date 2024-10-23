# Glossary <!-- omit in toc -->

![illustration](./imgs/img3.png)

## Table of Contents <!-- omit in toc -->

- [Core Concepts](#core-concepts)
  - [HMN (Human-Machine Network)](#hmn-human-machine-network)
- [Architecture Layers](#architecture-layers)
  - [Human Input Layer](#human-input-layer)
  - [Modular DAO Layer](#modular-dao-layer)
  - [Execution Layer](#execution-layer)
- [Technical Terms](#technical-terms)
  - [BFT (Byzantine Fault Tolerance)](#bft-byzantine-fault-tolerance)
  - [BLS12-381](#bls12-381)
  - [DAO (Decentralized Autonomous Organization)](#dao-decentralized-autonomous-organization)
  - [Groth16](#groth16)
  - [Liquid Democracy](#liquid-democracy)
  - [Pedersen Hash](#pedersen-hash)
  - [Quadratic Voting](#quadratic-voting)
  - [RISC Zero zkVM](#risc-zero-zkvm)
  - [SNARK (Succinct Non-interactive Argument of Knowledge)](#snark-succinct-non-interactive-argument-of-knowledge)
  - [SPADE Framework](#spade-framework)
  - [zkSync Era](#zksync-era)
  - [zkVM (Zero-Knowledge Virtual Machine)](#zkvm-zero-knowledge-virtual-machine)
- [Related Technologies](#related-technologies)
  - [Solidity](#solidity)
  - [Zero-Knowledge Proofs](#zero-knowledge-proofs)

## Core Concepts

### HMN (Human-Machine Network)

A system that operates through three abstraction layers to facilitate human-machine interaction and governance. The HMN
integrates human decision-making with autonomous AI agents, leveraging blockchain technology, zero-knowledge proofs,
and advanced voting mechanisms to create a decentralized, scalable, and privacy-preserving governance framework.

## Architecture Layers

### Human Input Layer

The foundational layer responsible for collecting human input such as governance proposals, ideas, and decisions. It
utilizes Succinct Non-interactive Arguments of Knowledge (SNARKs) to ensure data privacy and verifiable correctness.
This layer encodes human inputs into encrypted proof circuits, preserving confidentiality while allowing system
verification.

### Modular DAO Layer

The processing layer that integrates governance logic into decision-making workflows. It aggregates encrypted inputs
from the Human Input Layer, applies predefined governance rules, and generates executable commands for agents. This
layer employs smart contracts, consensus mechanisms, and advanced voting systems like liquid democracy and quadratic
voting to process decisions reflecting collective preferences.

### Execution Layer

The implementation layer where autonomous AI agents utilize Zero-Knowledge Virtual Machines (zkVMs) to execute
governance directives in a secure environment. These agents interpret tasks based on decisions recorded on-chain,
performing actions such as resource allocation, policy enforcement, and financial management while maintaining data
privacy and integrity.

## Technical Terms

### BFT (Byzantine Fault Tolerance)

A characteristic of a distributed system that allows it to continue operating correctly even when some nodes fail or
act maliciously. In the context of HMN, BFT ensures the reliability and security of the decision-making process across
the network of nodes.

### BLS12-381

An elliptic curve used for cryptographic operations, specifically in SNARK implementations. It provides a high level of
security while allowing for efficient computations, making it suitable for use in blockchain and zero-knowledge proof
systems.

### DAO (Decentralized Autonomous Organization)

A blockchain-based form of organization governed by smart contracts and community decisions. DAOs operate without
centralized leadership, using encoded rules and member voting to manage resources and make decisions. In HMN, the DAO
structure is enhanced with AI agents and advanced cryptographic techniques.

### Groth16

A specific zero-knowledge proof protocol used for creating succinct non-interactive arguments of knowledge. Groth16 is
known for its efficiency and small proof size, making it suitable for blockchain applications where minimizing data
storage and transmission is crucial.

### Liquid Democracy

A form of delegative democracy where participants can either vote directly on issues or delegate their voting power to
trusted representatives. This flexible system allows for more nuanced representation and engagement in the
decision-making process, potentially increasing participation and expertise in governance.

### Pedersen Hash

A cryptographic hash function used within zk-SNARK circuits for secure and efficient hashing. It provides the necessary
properties for use in zero-knowledge proofs while being computationally efficient, making it ideal for use in
blockchain and privacy-preserving applications.

### Quadratic Voting

A collective decision-making procedure where participants can express the intensity of their preferences. The cost of
votes increases quadratically, preventing large stakeholders from dominating decisions while allowing individuals to
concentrate their voting power on issues they care most about.

### RISC Zero zkVM

A specific implementation of a zero-knowledge virtual machine used in the execution layer of HMN. It allows for the
execution of arbitrary computations while generating proofs of correct execution, enabling secure and private
operation of autonomous agents.

### SNARK (Succinct Non-interactive Argument of Knowledge)

A form of zero-knowledge proof that allows one party to prove possession of certain information to another party
without revealing the information itself. SNARKs are crucial in HMN for ensuring data privacy while maintaining
verifiable correctness of inputs and operations.

### SPADE Framework

A development framework used for creating modular and composable autonomous agents. In HMN, SPADE facilitates the
design and implementation of AI agents that can interact with the blockchain, interpret governance decisions, and
execute tasks in alignment with the DAO's objectives.

### zkSync Era

An Ethereum Layer-2 solution optimized for scalability and low transaction fees with native zk-SNARK support. It
enables HMN to operate efficiently on the Ethereum network, providing the necessary infrastructure for secure and
scalable decentralized governance.

### zkVM (Zero-Knowledge Virtual Machine)

A virtual machine that can execute computations while maintaining data privacy through zero-knowledge proofs. In HMN,
zkVMs provide a secure environment for autonomous agents to execute governance directives without compromising
sensitive information.

## Related Technologies

### Solidity

The primary programming language used for implementing smart contracts in the Modular DAO Layer of HMN. Solidity
enables the creation of self-executing contracts with the business logic of the organization encoded on the Ethereum
blockchain.

### Zero-Knowledge Proofs

Cryptographic methods allowing one party to prove to another that a statement is true without revealing the underlying
information. In HMN, these proofs are fundamental to maintaining privacy while ensuring the integrity and correctness
of governance processes.
