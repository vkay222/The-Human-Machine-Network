# Technical Specifications <!-- omit in toc -->

## Table of Contents <!-- omit in toc -->

- [Overview](#overview)
  - [Architecture](#architecture)
  - [Workflow](#workflow)
- [Layers](#layers)
  - [1. Human Input Layer](#1-human-input-layer)
  - [2. Modular DAO Layer](#2-modular-dao-layer)
  - [3. Execution Layer](#3-execution-layer)

## Overview

The **Human-Machine Network (HMN)** operates through three abstraction layers:

1. **Human Input Layer**
2. **Modular DAO Layer**
3. **Execution Layer**

### Architecture

![HMN Architecture Diagram](docs/architecture_diagram.png)

### Workflow

The Human Input Layer collects human input (governance proposals, ideas, decisions etc.) using SNARKs to ensure data
privacy and verifiable correctness. This layer facilitates the encoding of human inputs into encrypted proof circuits.

The Modular DAO Layer processes these inputs autonomously to integrate governance logic into decision-making workflows,
operating with transparency by tallying human inputs and generating executable commands for agents. Within this layer,
agents reach consensus on what governance decisions to make through consensus mechanisms such as scalable multi-agent
Byzantine Fault Tolerance, and other algorithmic consensus mechanisms.

The Execution Layer leverages autonomous AI agents which utilize zkVMs to implement governance directives in a secure
execution environment once consensus has been reached on what decision to make. Agents could be tasked with financial
management, policy enforcement, resource allocation, and more.

Each layer plays a role in the governance process, ensuring that human inputs are effectively collected, processed, and
executed by agents in alignment with humans. The system employs granular privacy measures and utilizes modular,
composable agents for flexibility and scalability as the DAO evolves.

---

## Layers

### 1. Human Input Layer

**Purpose:**
Collect proposals, suggestions, and preferences from participants securely and privately using **Zero-Knowledge (ZK)** encryption.

**Process:**

- **Submission of Proposals and Preferences:**

  - Participants submit encrypted proposals and votes on-chain using **zkSync Era**, an Ethereum Layer-2 solution
  - optimized for scalability and low transaction fees.

- **Encryption and Verification:**
  - Inputs are transformed into encrypted proof circuits using **Succinct Non-interactive Arguments of\
    Knowledge (zk-SNARKs)**, specifically the **Groth16** protocol.

**Cryptographic Primitives:**

- **Elliptic Curve:** Utilizes **BLS12-381** for SNARK operations.
- **Hash Functions:** Employs **Pedersen Hash** within zk-SNARK circuits for secure and efficient hashing.

**Key Points:**

- **Encrypted Proposals and Votes:** Participants contribute ideas and preferences securely, protecting sensitive
- information at a fine-grained level.
- **Privacy Preservation:** zk-SNARKs keep inputs confidential while allowing system verification.
- **zkSync Era:** Provides scalability and low transaction fees with native zk-SNARK support.

---

### 2. Modular DAO Layer

**Purpose:**
Integrate governance logic into decision-making workflows, process encrypted inputs, and determine actions reflecting
the collective human will using consensus mechanisms.

**Process:**

- **Aggregation of Inputs:**

  - Collects encrypted proposals and votes from the Human Input Layer.

- **Governance Logic Application:**

  - **Smart Contracts:** Implemented in **Solidity**, defining governance logic, voting mechanisms, and verification processes.

- **Consensus Mechanisms:**

  - Validators reach consensus using hybrids of **Multi-Agent Scalable Byzantine Fault Tolerance (BFT)**.

- **Voting Mechanisms Applied:**

  - **Liquid Democracy:** Participants can delegate their voting power to trusted representatives, creating a dynamic
    and flexible network of representation.
  - **Quadratic Voting:** Allows participants to express the intensity of their preferences, with the cost of votes
    increasing quadratically to prevent dominance by large stakeholders.

- **Decision Processing:**

  - Aggregates inputs and applies governance logic to process votes and reach decisions reflecting collective preferences.

- **Recording Decisions:**
  - Decisions are recorded on-chain ensuring transparency, immutability, and accessibility for all participants.

**Key Points:**

- **Liquid Democracy and Quadratic Voting:** Capture both preference and intensity.
- **Consensus Among Validator Nodes:** Ensures decisions are secure and resistant to faults and malicious actors.
- **Automation and Trustlessness:** Solidity smart contracts enable automated and trustless governance operations.

---

### 3. Execution Layer

**Purpose:**
Execute governance directives using autonomous AI agents within secure environments, ensuring modularity and composability
for adaptability and scalability.

**Process:**

- **Reception of Directives:**

  - Agents retrieve tasks based on decisions recorded on-chain, interpreting executable commands from the Modular DAO Layer.

- **Autonomous Agents Execution:**

  - **Framework:** Agents are developed through the **SPADE** framework, allowing for modular and composable agent design.
  - **Capabilities:**
    - **Task Execution:** Perform tasks such as resource allocation, policy enforcement, financial management, and DAO initiatives.
    - **Blockchain Interaction:** Retrieve directives and submit execution proofs.

- **Secure Execution Environment:**
  - Agents execute tasks within **Zero-Knowledge Virtual Machines (zkVMs)**, specifically utilizing the **RISC Zero zkVM**
    implementation.

**Key Points:**

- **Autonomous AI Agents:** Ensure tasks are executed efficiently and securely.
- **zkVMs:** Provide a secure environment for task execution, maintaining data privacy and integrity.
