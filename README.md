# Hi, I'm Qianyu (Jiahua Wang)

**AI Product & Systems Engineer** · Hong Kong (`UTC+8 · SGT-Aligned / Remote or On-site`)

[![AI Portfolio](https://img.shields.io/badge/AI_Portfolio-ssrqy.cn%2Fwork-4f46e5?style=flat-square)](https://ssrqy.cn/work/)
[![Digital Twin](https://img.shields.io/badge/Interactive_AI_Twin-ssrqy.cn-7c3aed?style=flat-square)](https://ssrqy.cn/)
[![Resume PDF](https://img.shields.io/badge/1--Page_Resume-PDF-0f766e?style=flat-square)](https://ssrqy.cn/resume/Qianyu-Resume-EN.pdf)
[![Email](https://img.shields.io/badge/Email-qy20040625%40gmail.com-374151?style=flat-square)](mailto:qy20040625@gmail.com)

---

### Core Architectural Principle

I design and ship **Compound AI systems** built around a clean separation of authority:

- **Stateless Reasoning Engine:** LLMs handle semantic synthesis, intent routing, and natural interaction—never holding authoritative state, clock truth, or financial arithmetic.
- **Deterministic Tooling & Externalized State Layer:** Code, SQLite/IndexedDB schemas, BigInt ledgers, identity locks, and permission gates own every number, stable ID, and boundary check.
- **Progressive Context Disclosure:** Two-pass directory-first retrieval keeps prompts lean (`<=70%` budget) and avoids blind vector stuffing.
- **Context Governance (`AGENTS.md`):** Multi-agent sessions share durable workspace protocols, three-file topic knowledge bases (`manual.md` / `README.md` / `notes.md`), and automated hygiene verification.

---

### Shipped Systems & Open Source

| Project | Scope & Status | Key Architecture | Links |
|---|---|---|---|
| **Ta (祂)** | `2026 · Live Production v2.0.1` *(Private Repo · Android + Web PWA)* | 2-stage catalog recall (`<=70%` cap), 4-subject memory ownership + human edit locks, era-aware tool guard + Prompt Cache prefixing, zero-copy ZIP & SSE archive pipeline | [Live Web App](https://ssrqy.cn/ta/app/) · [Case Study](https://ssrqy.cn/work/#ta) |
| **AI Ops Workbench** | `2026 · Production v1.5.0` *(Private Repo · Electron + SQLite v22)* | Hard LLM/tool decoupling with integer-cent BigInt commission ledger, DeepSeek-Harness 3-role memory isolation, read-only HIL drafting, 3-way Lark (Feishu) sync, **374 regression tests** | [Architecture](https://ssrqy.cn/work/#workbench) |
| **Qianyu QQ Agent** | `2026 · Open Source v0.3.14` *(Python + pywebview + C#)* | Stateless DeepSeek-compatible API wrapper with per-account externalized memory, local doc search, and cleanly decoupled open-source distribution | [Repository](https://github.com/qy70/qianyu) |
| **Agent Context Governance** | `2026 · Open Source Starter` *(Markdown + Node.js ESM)* | Reusable `AGENTS.md` multi-agent protocol, 3-file persistent topic KB template, and zero-dependency workspace hygiene checker | [Repository](https://github.com/qy70/agent-context-governance) |
| **Directory-First Retrieval** | `2026 · Open Source Reference` *(Node.js ESM · zero deps · 20 tests)* | Lightweight catalog first, model selects groups, deterministic budgeted fetch second; resident layer and `70%` budget cap with truncation reports | [Repository](https://github.com/qy70/directory-first-retrieval) |
| **Integer-Cent Ledger** | `2026 · Open Source Library` *(Node.js ESM · BigInt · 32 tests)* | Integer-cent tiered commissions, policy snapshots, cross-month recalculation, clawback debt entries and a SHA-256 hash-chained audit trail | [Repository](https://github.com/qy70/integer-cent-ledger) |
| **AI Portfolio Source** | `2026 · Open Source Site` *(Vanilla JS · EN/ZH · light/dark)* | Zero-dependency static portfolio with native SVG architecture diagrams and lightbox gallery | [Repository](https://github.com/qy70/ssrqy-work-portfolio) · [Live](https://ssrqy.cn/work/) |

---

### Multi-Agent Workflow & Engineering Stack

- **Multi-Agent Orchestration:** Antigravity, Codex, DeepSeek-Harness, Grokbot, WorkBuddy
- **Languages & Runtimes:** JavaScript / TypeScript (Node.js, Electron, PWA), Python
- **Data & Verification:** SQLite / IndexedDB, SQL, SSE Streaming, Lark (Feishu) Sync APIs, Headless Chrome CDP Automated QA
- **Collaboration:** `UTC+8` (Zero time difference with Singapore SGT) · Async written technical collaboration in English & Chinese
