<div align="center">

# 💠 Web3OS

### *The Web3 Operating System for the Human Economy*

[![License: GPL-3.0](https://img.shields.io/badge/License-GPL--3.0-blue.svg)](LICENSE-GPL3)
[![Rust](https://img.shields.io/badge/Rust-000000?logo=rust&logoColor=white)](https://www.rust-lang.org/)
[![Substrate](https://img.shields.io/badge/Polkadot_SDK-E6007A?logo=polkadot&logoColor=white)](https://polkadot.network/)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)](https://www.typescriptlang.org/)

---

**Web3OS** is a modular, sovereign-first platform that combines blockchain infrastructure, AI-driven identity, and decentralized social & financial tools into a unified operating system — designed for citizens, not users.

</div>

---

## 🧬 Architecture

Web3OS follows a biological, cellular model. Each component is a living organ of a larger digital organism:

```
                         ┌──────────────────────────┐
                         │     💠 WEB3OS NEXUS       │
                         │   Orchestration & Wiki    │
                         └─────────┬────────────────┘
                                   │
              ┌────────────────────┼────────────────────┐
              │                    │                     │
    ┌─────────▼─────────┐  ┌──────▼───────┐  ┌─────────▼─────────┐
    │  ❤️ TOKFINNET      │  │ 🫁 STUDIO    │  │  🧩 CONNECTORS    │
    │  Layer 0           │  │ SDK & Tools  │  │  Shared Libraries │
    │  Blockchain Heart   │  │              │  │                   │
    └─────────┬─────────┘  └──────┬───────┘  └─────────┬─────────┘
              │                   │                     │
              └───────────────────┼─────────────────────┘
                                  │
         ┌────────────┬───────────┼───────────┬────────────┐
         │            │           │           │            │
    ┌────▼───┐  ┌─────▼──┐  ┌────▼───┐  ┌────▼───┐  ┌─────▼────┐
    │ Social │  │ OnAv3d │  │ Quipus │  │ Mesh   │  │ Ubi      │
    │ Suite  │  │        │  │        │  │ Mood   │  │ Arena    │
    └────────┘  └────────┘  └────────┘  └────────┘  └──────────┘
```

---

## ❤️ TokFinNet — The Heart

> **The Layer 0 Blockchain**

The economic foundation of Web3OS. A Substrate-based blockchain (Polkadot SDK) with EVM compatibility, providing the consensus, token primitives, and on-chain governance for the entire ecosystem.

| | |
|---|---|
| **Repo** | [`tokfinnet`](https://github.com/Web3os-Ecosystem/tokfinnet) |
| **Stack** | Rust · Polkadot SDK · Frontier (EVM) · BABE/GRANDPA Consensus |
| **Status** | 🟢 MVP |

---

## 🧩 WCN Connectors — The Nervous System

> **Shared Integration Libraries**

A unified library of connectors that abstracts external services (databases, AI, blockchain, monitoring, messaging) behind a consistent interface. Every application in the ecosystem consumes these connectors instead of building isolated integrations.

| | |
|---|---|
| **Repo** | [`wcn-connectors`](https://github.com/Web3os-Ecosystem/wcn-connectors) |
| **Stack** | Rust · Axum · TypeScript |
| **Connectors** | Ollama AI · PostgreSQL · Redis · TokFin RPC · Prometheus · Kubernetes |
| **Status** | 🚧 Dev |

---

## 🫁 Web3OS Studio — The Lungs

> **SDK & No-Code Creation Tools**

The developer and creator toolkit. Studio houses the engines that breathe life into the ecosystem: a **Token Engine** for no-code tokfacts generation nad assets verification, a **DAO Engine** for governance setup, and a **TokAgents** for AI tools to catalize human creativity and productivity.

| | |
|---|---|
| **Repo** | [`web3os-sdk`](https://github.com/Web3os-Ecosystem/web3os-studio) |
| **Stack** | Rust · TypeScript · React |
| **Status** | 🚧 Dev |

---

## 💠 Web3OS Nexus — The Brain

> **Orchestration Hub & Living Wiki**

The central nervous system. Nexus catalogues every entity in the ecosystem — from blockchain modules to citizen profiles — and serves as both a navigational wiki and the master data orchestration layer.

| | |
|---|---|
| **Repo** | [`web3os-nexus`](https://github.com/Web3os-Ecosystem/web3os-nexus) |
| **Stack** | Rust · Axum · Sled · HTML Templates |
| **Status** | 🚧 Dev |

---

## 💪 Applications

The functional organs — sovereign dApps that citizens interact with daily.

### 📱 Social Suite

> **Identity, Social Graph & Content Platform**

The citizen-facing social layer combining profile identity, messaging, content sharing (video, photos, stories, reels), microblogging, and community channels. Features sovereign content moderation and a built-in wallet.

| | |
|---|---|
| **Repo** | [`wcn-social-suite-mvp`](https://github.com/Web3os-Ecosystem/social-suite) |
| **Stack** | TypeScript · React · Vite · TailwindCSS |
| **Status** | 🟢 MVP |

---

### 🪪 OnAv3d

> **Onboarding, KYC & 3D Avatar Identity**

The digital identity gateway. Handles citizen onboarding with sovereign document verification (OCR), biometric liveness detection, KYC compliance, and AI-generated 3D avatars linked to unique `.wcn` domains. Includes NFC phygital card integration.

| | |
|---|---|
| **Repo** | [`wcn-onav3d`](https://github.com/Web3os-Ecosystem/onav3d) |
| **Stack** | Rust · Axum · PostgreSQL · Ollama |
| **Status** | 🚧 Dev |

---

### 🧘 MeshMood

> **AI Wellness Auto-Moderator**

A citizen-sovereign content filter and digital wellness engine. MeshMood lets each citizen define their own content consumption rules (Focus, Detox, Relax modes) and provides private wellness analytics — moderation is owned by the individual, not the platform.

| | |
|---|---|
| **Repo** | [`wcn-meshmood`](https://github.com/Web3os-Ecosystem/meshmood) |
| **Stack** | Rust |
| **Status** | 🚧 Dev |

---

### 💰 Quipus

> **Decentralized Exchange & Payment Gateway**

The financial DApp. A DEX infrastructure with jurisdictional compliance baked into smart contracts. Quipus implements a "Legal-to-Code" protocol that translates regulatory mandates (MiCA, FINMA) into on-chain rules, keeping financial operations segregated from the social layer.

| | |
|---|---|
| **Repo** | [`wcn-quipus`](https://github.com/Web3os-Ecosystem/quipus) |
| **Stack** | Rust · React · Smart Contracts · PostgreSQL |
| **Status** | 🚧 Dev |

---

### 🎮 UbiArena

> **Consensus Gamification**

A gamified arena where citizens participate in network validation and governance through game mechanics. Transforms blockchain consensus participation from technical complexity into engaging, accessible experiences.

| | |
|---|---|
| **Repo** | [`wcn-ubiarena`](https://github.com/Web3os-Ecosystem/wcn-ubiarena) |
| **Stack** | Rust · TypeScript · React |
| **Status** | 🚧 Dev |

---

## 🛠️ Tech Stack

| Layer | Technologies |
|-------|-------------|
| **Blockchain** | Polkadot SDK · Substrate · Frontier (EVM) · BABE/GRANDPA |
| **Backend** | Rust · Axum · Actix |
| **Frontend** | TypeScript · React · TailwindCSS · HTML5 |
| **AI** | Ollama · Mistral · Flux · LLaVA |
| **Database** | PostgreSQL · Redis · Sled |
| **Monitoring** | Prometheus · Grafana · Sentry |
| **Storage** | IPFS · Filecoin |
| **Orchestration** | Docker · Kubernetes |

---

## 📐 Design Principles

- **Sovereignty First** — Citizens own their data, keys, and content moderation rules
- **Biological Architecture** — Each module is an organ, not a microservice
- **Separation of Concerns** — Financial regulation is firewalled from social layers
- **Local-First AI** — Identity verification and moderation run on sovereign infrastructure
- **No Intermediaries** — Direct P2P interactions backed by blockchain consensus

---

## 🗺️ Roadmap

| Phase | Focus | Status |
|-------|-------|--------|
| **Phase 0** | TokFinNet blockchain + Economic Simulation | 🟢 Complete |
| **Phase 1** | Social Suite MVP + OnAv3d Identity | 🟡 In Progress |
| **Phase 2** | Quipus DEX + MeshMood Wellness | 🔵 Planned |
| **Phase 3** | UbiArena + Business Suite | ⚪ Future |

---

## 🏛️ Organization

**Web3OS Ecosystem** is structured as a federation of purpose-built entities:

- **Operations** — Legal, Marketing, Investor Relations, Ethics
- **Modules** — The technical repositories listed above
- **Citizens** — Sovereign user nodes with personal, professional, social, and organizational contexts

---

<div align="center">

**Built with 🦀 Rust & ❤️ for the Human Economy**

[Website](https://web3os.world) · [Documentation](https://docs.web3os.world) · [GitHub](https://github.com/Web3os-Ecosystem)

</div>
