<div align="center">

<img src="./portal-loader.svg" width="120" height="120" alt="Syntra Labs Logo" />

# Syntra Labs

**Interactive Coding Tutors, Distributed Systems Practice, and Developer Tools**

*Helping programmers build deep understanding rather than relying on auto-generated code.*

[![Organization: Syntra-Labs](https://img.shields.io/badge/organization-Syntra--Labs-blue.svg)](https://github.com/Syntra-Labs)
[![Roadmap: GitHub Issues](https://img.shields.io/badge/roadmap-github--issues-orange.svg)](https://github.com/Syntra-Labs/syntra-labs/issues)

</div>

---

## Overview

**Syntra Labs** builds open-source tools for developers who want to master systems programming, distributed systems, and software verification.

Instead of writing code for you, our tools are built to help you practice and understand hard engineering problems: distributed consensus, lock-free concurrency, memory management, and performance tuning.

---

## Core Focus Areas

All project milestones, ideas, and problem definitions are tracked in our **[GitHub Issues Tracker](https://github.com/Syntra-Labs/syntra-labs/issues)**.

### 1. A Tutor, Not an Autocomplete Bot
- **Build Real Understanding**: Copying AI-generated code leads to shallow understanding and subtle bugs. Syntra acts as a tutor that guides you to master core principles, edge cases, and performance tradeoffs.
- **Helpful Feedback**: The tutor asks guiding questions, points out unhandled errors, and gives targeted hints instead of simply writing the solution for you.

### 2. Real Systems Problem Sets
- Hands-on challenges covering practical computer science topics:
  - Distributed consensus and fault tolerance (Raft, Paxos, CRDTs under network chaos).
  - Formal methods and theorem proving (Lean 4, Hoare logic).
  - Cache-friendly data structures and memory layouts.
  - Custom memory allocators, lock-free queues, and runtime internals.

### 3. Realistic Test Environments
- **Real Network Conditions**: Tests are not just unit tests—they run in containers and simulated networks with real delays, partitions, and node crashes.
- **Thorough Verification**: Combines property-based fuzzing, automated test suites, and formal checks to ensure solutions work under stress.

### 4. Real-World Problems and Upstream Contributions
- **Extracted Problem Stubs**: We take real functions from open-source repositories and turn them into standalone exercises with test harnesses.
- **Contributing Back**: When an implementation passes all tests and beats the production baseline (lower CPU usage, fewer cache misses, lower latency), we help format a Pull Request to contribute the fix back.

### 5. Adaptive Problem Selection
- **Progress Tracking**: Tracks your comfort across topics (algorithms, concurrency, systems profiling) to suggest problems that match your current skill level.

---

## Repositories

| Repository | Description | Status |
| :--- | :--- | :--- |
| **[`tutor`](https://github.com/Syntra-Labs/tutor)** | Interactive problem runner and test harness for systems programming practice | Core Platform |
| **[`router`](https://github.com/Syntra-Labs/router)** | Fast C++ code search and data routing library | Core Library |
| **[`scribe`](https://github.com/Syntra-Labs/scribe)** | Fast local speech-to-text CLI for microphone recording | Tool |
| **[`synvim`](https://github.com/Syntra-Labs/synvim)** | Minimalist Neovim editor with voice input and fast search | Editor |
| **[`taskflow`](https://github.com/Syntra-Labs/taskflow)** | Task manager that tracks dependencies directly in code comments | Tool |
| **[`lawful`](https://github.com/Syntra-Labs/lawful)** | Fast C++ tensor and math library | Library |
| **[`uor-r4`](https://github.com/Syntra-Labs/uor-r4)** | Formal reasoning and mathematical logic research | Research |
| **[`prover`](https://github.com/Syntra-Labs/prover)** | Lean 4 theorem-proving experiment (archived) | Archived |
| **[`sphere-route`](https://github.com/Syntra-Labs/sphere-route)** | Interactive 3D globe where you steer paths using C++ in an in-browser Neovim editor | Interactive Demo |
| **[`tokenizer`](https://github.com/Syntra-Labs/tokenizer)** | Audio-based text tokenization experiment | Research |

---

## Contributing

We welcome systems programmers, researchers, and developers who care about building tools that help people learn and build better software.

- Check out our roadmap in [GitHub Issues](https://github.com/Syntra-Labs/syntra-labs/issues).
- Browse our repositories under the [Syntra-Labs Organization](https://github.com/Syntra-Labs).

<div align="center">
<sub>© 2026 Syntra Labs. Distributed under open source licenses.</sub>
</div>
