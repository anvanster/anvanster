## Andrey Vasilevsky

I build the infrastructure AI coding agents need to work on real codebases — structured code
understanding, persistent memory, context economy, and architectural constraint. Twenty years in
enterprise infrastructure; currently a validation engineer working on VMware and Linux network
driver certification.

### Projects

| Project | What it does |
| --- | --- |
| **[CodeGraph](https://github.com/codegraph-ai/CodeGraph)** | Semantic graph of your codebase — functions, classes, imports, call chains — exposed as 42 MCP tools across 38 languages. One Rust binary serving MCP and LSP; VS Code extension, JetBrains plugin, npm package, GitHub Action. |
| **[Tempera](https://github.com/anvanster/tempera)** | Episodic memory for coding agents. Captures sessions as episodes, retrieves them by semantic search, and uses reinforcement learning to surface what actually helped. |
| **[Smelt](https://github.com/anvanster/smelt-svc)** | Semantic version control over Git. Record the intent, get a semantic delta — functions changed, breaking signatures, dependency impact — validated against architectural rules before commit. |
| **[Crucible](https://github.com/anvanster/crucible)** | Architecture validation for AI-generated code. Checks implementations against a machine-readable system definition to catch drift before it lands. |
| **[Compressor](https://github.com/anvanster/compressor)** | Token reduction for Copilot agent mode. Compressed reads, searches, and outlines as Language Model Tools, with recoverable expansion markers and a local savings ledger. |

All Rust unless noted. Apache-2.0.

### Security research

- **[CVE-2026-50163](https://github.com/oras-project/oras-go/security/advisories/GHSA-fxhp-mv3v-67qp)** (High) — link-following path traversal in `oras-go` tar extraction. CNCF ORAS project; fixed in 2.6.2.
- **[CVE-2026-47699](https://github.com/confidential-containers/guest-components/security/advisories/GHSA-84rc-2q4r-45pc)** — escaping hardlink during OCI image unpacking in Confidential Containers `image_rs`; fixed in 0.20.0.
- Microsoft Security Response Center — bounty awarded, researcher recognition Q2 2026.

### Elsewhere

[CodeGraph](https://codegraph.astudioplus.com) · [LinkedIn](https://www.linkedin.com/in/andreyvasilevsky) · [dev.to](https://dev.to/anvanster)

English · Russian · Hebrew
