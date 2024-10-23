# The Human-Machine Network (HMN) <!-- omit in toc -->

![illustration](docs/imgs/img1.png)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Documentation](https://img.shields.io/badge/docs-latest-blue.svg)](docs/README.md)
[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg)](CODE_OF_CONDUCT.md)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![Conventional Commits](https://img.shields.io/badge/Conventional%20Commits-1.0.0-yellow.svg)](https://conventionalcommits.org)
[![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)](http://commitizen.github.io/cz-cli)

## Table of Contents <!-- omit in toc -->

- [Abstract](#abstract)
- [The HMN in Two Sentences](#the-hmn-in-two-sentences)
- [Overview](#overview)
  - [Architecture](#architecture)
  - [Workflow](#workflow)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [IDE Setup](#ide-setup)
- [Technical Specifications](#technical-specifications)
- [Real-World Example](#real-world-example)
- [Glossary](#glossary)

---

## Abstract

Governance systems face issues with bureaucratic inertia, privacy concerns, and the concentration of power amongst a few
decision-makers. We describe the **Human-Machine Network (HMN)**, a framework for a new paradigm of decentralized governance
facilitating human-machine collaboration within Decentralized Autonomous Organizations (DAOs). The HMN orchestrates the
interaction between human inputs and a network of autonomous AI agents who execute governance directives. This framework
proposes efficiency, reduces cooperative dilemmas through game-theoretic value alignment, and addresses privacy concerns
facilitated by advancements in Zero-Knowledge Proofs (ZKPs), including Succinct Non-Interactive Arguments of Knowledge
(SNARKs) and Zero-Knowledge Virtual Machines (zkVMs). Scalability challenges inherent to voting are addressed through liquid
democracy and quadratic voting, along with consensus mechanisms amongst agents to execute decisions on the collective human
will. The systems described possess the potential to redefine traditional bureaucracies and enable parallel societies, whilst
orchestrating consensus across vast numbers of participants. This Human-Machine collaboration is brought about in a
decentralized, scalable, efficient, and privacy-preserving manner.

**Key Words:** Decentralized Autonomous Organizations, Zero-Knowledge Proofs, Succinct-Interactive Arguments of Knowledge,
Zero-Knowledge Virtual Machines, Multi-Agent Systems, Byzantine Fault Tolerance, Distributed Systems, Consensus Mechanisms,
Network States, Game Theory, Quadratic Voting, Liquid Democracy

---

## The HMN in Two Sentences

The HMN is a framework for a new paradigm of decentralized governance that integrates autonomous AI agents, ZK-encryption,
scalable voting, game theory, and consensus mechanisms within DAOs. This system may underpin future parallel societies
or network states.

---

## Overview

The **Human-Machine Network (HMN)** operates through three abstraction layers:

1. **Human Input Layer**
2. **Modular DAO Layer**
3. **Execution Layer**

### Architecture

<!-- TODO: Add architecture diagram -->

![HMN Architecture Diagram](docs/architecture_diagram.png)

### Workflow

1. **Human Input Layer:** Collects governance proposals and decisions using SNARKs for data privacy and correctness.
2. This layer facilitates the encoding of inputs into encrypted proof circuits.
3. **Modular DAO Layer:** Processes inputs, applies governance logic, and provides executable commands for agents.
4. **Execution Layer:** Utilizes autonomous AI agents and zkVMs to implement governance directives securely.

---

## Getting Started

These instructions will help you set up the HMN project on your local machine for development and testing purposes.

### Prerequisites

- [Git](https://git-scm.com/downloads)
- [Node.js](https://nodejs.org/) (v14 or higher)
- [Hardhat](https://hardhat.org/) for smart contract development

### Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/yourusername/Human-Machine-Network.git
   cd Human-Machine-Network
   ```

### IDE Setup

For VS Code and Cursor users:

1. Open the workspace file:

   ```bash
   code app.code-workspace
   ```

This workspace configuration includes:

- Recommended extensions for development
- Consistent code formatting settings
- File associations and exclusions
- Spell checking configuration

The workspace ensures all developers have the same development experience and code quality tools.

Recommended Extensions:

- Code Spell Checker
- Better Comments
- Todo Tree
- Markdown All in One
- Prettier

---

## Technical Specifications

For detailed technical architecture and implementation details, see our [Technical Specifications](docs/Technical_Specifications.md).

## Real-World Example

For a comprehensive example of HMN implementation in practice, see our [Real-World Example](docs/Real_World_Example.md).

## Glossary

For definitions of key terms and concepts used in this project, please refer to our [Glossary](.github/GLOSSARY.md).
