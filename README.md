# Isaac Phillips
**Principal Systems Architect**

I design high-performance, local-first systems. Currently focused on **ApexPlanner**, a hermetic context engine for AI-assisted engineering that prioritizes deterministic state over cloud-based heuristics.

### Current Project: [ApexPlanner](https://github.com/IsaacP-lab/ApexPlanner-Public)
A Rust-backed MCP server designed to eliminate "Context Rot" in large-scale TypeScript architectures.

* **D5 Performance Budgets:** < 100ms p95 cold boot; < 30MB warm RSS.
* **Data Sovereignty:** Implements a Hermetic IP Boundary (HIPB) to prevent proprietary source-code leakage.
* **Integrity:** Uses BLAKE3-normalized AST hashing for cryptographic drift detection.

### Technical Governance (Proof of Work)
I do not prioritize "lines of code." I prioritize the integrity of the architecture. My work is documented through rigorous Architecture Decision Records (ADRs) to ensure every technical trade-off is auditable.

* **[ADR Register]**: Foundational decisions on SQLite state management and BLAKE3 normalization.
* **[Governance Standard]**: R1–R8 protocols for Human-in-the-loop (HITL) AI verification.
* **[Benchmarks]**: Comparative analysis of local file-scanning vs. remote semantic search.

### Toolkit
**Systems:** Rust (Async/Tokio), SQLite (WAL-mode), C (FFI)  
**Infrastructure:** MCP (Model Context Protocol), Tauri, JSON-RPC  
**Foundations:** AST Normalization, Context Engineering, Local-First Architecture

---
[LinkedIn](https://www.linkedin.com/in/isaac-phillips-apexsystems) | [Contact](isaacp@pbrlocksmith.com)
