<div align="center">

<img src="./portal-loader.svg" width="120" height="120" alt="Syntra Labs Logo" />

# Syntra Labs

**Cognitive Tutors, Distributed Verification, and Clean-Room Systems Research**

*Empowering human mastery over passive code generation.*

[![Organization: Syntra-Labs](https://img.shields.io/badge/organization-Syntra--Labs-blue.svg)](https://github.com/Syntra-Labs)
[![Architecture: Future Plans](https://img.shields.io/badge/roadmap-future--plans-orange.svg)](FUTURE_PLANS.md)

</div>

---

## Overview

**Syntra Labs** is an open-source systems and research laboratory building tools at the intersection of developer cognitive augmentation, distributed systems, and formal methods.

While the modern AI landscape is focused on autonomous coding agents that write code on behalf of developers, Syntra Labs pursues a fundamentally different vision: **Cognitive Tutors and Research Arenas**. We build environments where engineers solve genuine systems and research challenges, prove invariants, spin up distributed clusters, and crowdsource real-world production software optimization through clean-room contract slicing.

---

## Core Pillars & Future Plans

For our complete architectural specification and multi-phase roadmap, read **[FUTURE_PLANS.md](FUTURE_PLANS.md)**.

### 1. Coding Tutor, Rather than Coding Agent
- **Active Synthesis over Passive Generation**: Generative agents produce epistemic debt and shallow understanding. Syntra operates as a Socratic mentor and rigorous evaluator that guides developers to master foundational principles, edge-case invariants, and algorithmic tradeoffs.
- **Dialectic Evaluation**: The tutor asks probing questions, points out unhandled failure modes, and offers targeted hints rather than writing solutions for the user.

### 2. Research & Experimentation via Problem-Set Solving
- Complex theoretical computer science and systems engineering structured as inquiry-driven problem sets:
  - Distributed consensus & fault tolerance (Raft, Paxos, CRDTs under network chaos).
  - Formal methods & interactive theorem proving (Lean 4, Hoare logic, SMT).
  - High-performance systems & cache-conscious data structures.
  - Custom allocators, lock-free concurrency, and kernel/runtime internals.

### 3. Distributed Execution & Integrated Verification
- **Real-World Topologies**: Challenges are not in-memory script exercises—they spin up ephemeral container clusters, microVMs, and simulated networks with dynamic fault injection (delays, partitions, node crashes).
- **Multi-Tier Verification**: Combines property-based fuzzing, deterministic test oracles, and formal proof checkers to guarantee correctness under real-world conditions.

### 4. Clean-Room Real-World Slicing & Production Optimization
- **Opaque Interface Boundaries**: Users can tackle real-world problems from existing production software without seeing existing implementations or surrounding code. They receive only the strict type signature and behavioral contract.
- **Production Upstream Pipeline**: If a user's implementation passes all verification suites and demonstrates superior performance (lower CPU cycles, fewer cache misses, reduced memory allocations, better tail latency) compared to the current production baseline, the system can automatically propose an upstream Pull Request to update production code.

### 5. Adaptive Cognitive Routing
- **Skill Graph & Knowledge Tracing**: Continuous evaluation of user proficiency across algorithmic depth, concurrency modeling, invariant reasoning, and profiling intuition.
- **Frontier Guidance**: Challenges are sequenced dynamically to keep learners in their optimal Zone of Proximal Development based on their explicit goals.

---

## Ecosystem Repositories

| Repository | Description | Status |
| :--- | :--- | :--- |
| **[`tutor`](https://github.com/Syntra-Labs/tutor)** | Socratic systems problem runner (LeetVim-style), native test runner, and `lgcc` contract slicer & linter | Core Platform |
| **[`router`](https://github.com/Syntra-Labs/router)** | High-throughput geometric manifold substrate (`manifold.cpp`) and hybrid search engine (BM25 + FZF) | Substrate |
| **[`scribe`](https://github.com/Syntra-Labs/scribe)** | Minimalist microphone voice recording and Whisper transcription CLI (`youtube` pipeline branched) | Active Tooling |
| **[`synvim`](https://github.com/Syntra-Labs/synvim)** | Sovereign minimalist Neovim editor with voice input and instant symbol navigation | Active Editor |
| **[`lawful`](https://github.com/Syntra-Labs/lawful)** | High-performance C++ tensor library and mathematical primitives | Core Substrate |
| **[`uor-r4`](https://github.com/Syntra-Labs/uor-r4)** | Research fork of `UOR-Foundation/uor-r4`: universal order & resonance formal systems | Active Research |
| **[`prover`](https://github.com/Syntra-Labs/prover)** | Neurosymbolic theorem-proving framework and live Lean 4 compiler verification loop | Active Research |

---

## Contributing & Collaboration

We welcome systems researchers, formal methods practitioners, and developers passionate about building tools that foster human understanding.

- Read our detailed vision in **[FUTURE_PLANS.md](FUTURE_PLANS.md)**.
- Explore our repositories under the [Syntra-Labs Organization](https://github.com/Syntra-Labs).

<div align="center">
<sub>© 2026 Syntra Labs. Distributed under open research licenses.</sub>
</div>
