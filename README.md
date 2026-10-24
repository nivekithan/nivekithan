# Hi, I'm Nivekithan 👋

> Backend Engineer at [SARAL](https://www.linkedin.com/company/81731249/) | Building distributed systems, compilers, and everything in between

I'm passionate about **backend engineering**, **distributed systems**, and **systems programming**. When I'm not shipping production code, I'm probably implementing a consensus algorithm or building a programming language for fun.

**📍 Links:** [Blog](https://nivekithan.com) • [Email](mailto:nivekithan363@gmail.com) • [Twitter](https://twitter.com/nivekithanS) • [Resume](https://nive.fyi/resume)

---

## ⚡ Tech Stack

```
Languages            TypeScript · Go · Kotlin · JavaScript
Backend              Node.js · Cloudflare Workers · Hono · Express.js
Cloud & Infra        AWS (Batch, Lambda, S3) · Cloudflare · Pulumi
Databases            PostgreSQL
Frontend             React · Next.js · Remix · React Router · Vite
```


---

## 💼 Work Experience

**Backend Engineer** @ [EPYC](https://www.linkedin.com/company/epyc/) | *Aug 2022 - Feb 2026*

Delivering production systems for clients across scheduling, fintech, and funding platforms. Here's what I've built:

### Scheduling System

Built a robust appointment booking platform connecting users with industry experts.

**Highlights:**
- **Zero double bookings** through proper concurrency control
- Integrated Razorpay with duplicate payment prevention
- Google Calendar sync to avoid conflicts
- Custom mentor availability management

`TypeScript` `React Router v7` `Cloudflare Workers` `PostgreSQL`

### 💳 Shopify Credits System for Airlines

Enterprise credits management system for airline employee uniform purchases.

**Highlights:**
- **Balances never go negative** - handled every concurrency edge case
- Accurate accounting across refunds, cancellations, and returns
- Custom tax software integration for precise sales tax
- Analytics dashboards for vendors and airline management

`TypeScript` `Next.js` `Cloudflare Workers` `PostgreSQL`

### 🚀 Funding Application Platform

Collaboration platform connecting founders with investors.

**Highlights:**
- Application reconciliation across Algolia + multiple internal APIs
- **Fault-tolerant architecture** - graceful degradation when APIs fail
- Duplicate detection and missing application recovery

`TypeScript` `React Router v7` `Cloudflare Workers` `PostgreSQL`

### 🎯 Other Wins

- Built bulk Slack DM system sending **10,000+ messages** with rate limit handling (Bull queue)
- Decomposed monolith → microservices, **slashing memory/CPU usage** during high job loads
- Developed Stripe payment gateway for events platform
- Migrated services Digital Ocean → AWS, improving performance
- Created dev environment CLI: **setup time from 2+ days → minutes**
- Led JS → JSDoc migration: fewer runtime errors, zero delivery slowdown

---

## 🔨 Featured Projects

*I build things to understand how they work - from consensus algorithms to compilers.*

### [Levenshtein Automata](https://github.com/nivekithan/levenshtein-automata)

Fast fuzzy string search using finite automata - **10,727 queries/sec** on 370K-word dictionary.

```
Performance: 38% faster than runtime construction at distance 3
Approach:    Precomputed DFA + Trie-based dictionary
Language:    Kotlin
```

7 implementation versions (v1-v7) showing progressive optimizations from the Schulz & Mihov paper.

### [Go Raft](https://github.com/nivekithan/go-raft)

Raft consensus algorithm implementation with **formal verification** before a single line of code.

```
Verification: P-lang model checking
Approach:     Minimal mutex usage for performance
Language:     Go
```

**Links:** [P-lang Models](https://github.com/nivekithan/p-models) • [Original Paper](https://raft.github.io/raft.pdf)

### [Protohackers Solutions](https://github.com/nivekithan/go-network)

Network programming challenges: TCP/UDP servers, custom protocols, and everything low-level.

**7 Challenges Solved:**
- Custom LRCP protocol (UDP + acks + retransmission)
- Binary TCP protocol for speed cameras
- TCP proxy with address rewriting
- Multi-user chat server
- Asset tracking with binary protocol + SQLite
- And more...

`Go` `TCP/UDP` `Custom Protocols`

### [Tango Programming Language](https://github.com/nivekithan/tango)

Custom language with full compiler pipeline: **Lexer → Parser → AST → Compiler → VM**.

```
Features: Variables, arithmetic, boolean ops, REPL
Output:   Bytecode execution
Language: Go
```

### [Blender Render Farm](https://github.com/nivekithan/blender-render-farm)

Serverless distributed rendering: distribute animation frames across AWS Fargate containers.

```
Architecture: AWS Batch + Lambda + S3
Orchestration: S3 upload events → Lambda triggers
IaC:          Pulumi
```

Parallel rendering with automatic frame consolidation. `Go` `Docker` `AWS`

### [TypeScript Compiler](https://github.com/nivekithan/compiler)

TypeScript → Native code using LLVM. Educational compiler with full test coverage.

```
Supports: Variables, control flow, functions, operators
Backend:  LLVM
Output:   Native code
```

---

## 🚀 Live Projects

### [Maailit](https://maailit.com) • [GitHub](https://github.com/nivekithan/maailit)

Temporary email for developers - test OTPs, password resets, without inbox clutter.

**Features:** Real-time WebSocket updates • AI-powered code extraction (GPT-4o-mini) • 15-min auto-cleanup • Zero registration

`Next.js 14` `Cloudflare Workers` `Durable Objects` `D1`

### [Fireside Events](https://calls.nivekithan.com/) • [GitHub](https://github.com/nivekithan/fireside-events)

Real-time video broadcasting with **XState state machines** for complex UI flows.

**Features:** Multi-participant calls • Screen sharing • WebSocket signaling (Durable Objects) • [State machine visualization](https://stately.ai/registry/editor/1f4bf00b-3305-47d0-8a41-6883662fc62b?machineId=f618d82b-9ff8-4384-a22d-80a650c9d620)

`React Router v7` `WebRTC` `XState v5` `Cloudflare Calls API`

### [Chat with JSON](https://chat-with-json.nivekithan.com) • [GitHub](https://github.com/nivekithan/chat-with-json)

Query JSON files with natural language. **Your data never leaves your browser.**

**Features:** GPT-4 powered • Auto schema generation • Streaming responses • Client-side processing

`Remix` `Vercel AI SDK` `Cloudflare Pages`

### [pg-cluster](https://github.com/nivekithan/pg-cluster) *[WIP]*

Kubernetes operator for PostgreSQL clusters - backups, PITR, on-demand DB provisioning for PR previews.

`TypeScript` `Effect-TS` `Kubernetes` `PostgreSQL 17` `pgBackRest`

---

## 🎓 Learning Challenges

### [Fly.io Distributed Systems](https://fly.io/dist-sys/) • [My Solutions](https://github.com/nivekithan/deno-fly)

Completed 6 challenges: Echo • Unique ID Generation • Single/Multi-Node Broadcast • Fault-Tolerant Broadcast • Efficient Broadcast

*When I want to learn a concept deeply, I prefer challenges with clear constraints over building full projects.*

---

## 🌱 Early Projects

**[Path Finder](https://path-finder-brown.vercel.app/)** • [GitHub](https://github.com/nivekithan/path-finder)
Pathfinding algorithm visualizer - one of my first projects.

**[slate-devtools](https://www.npmjs.com/package/slate-devtools)** • [GitHub](https://github.com/nivekithan/slate-devtools)
Debugging tools for Slate.js rich text editor. Built while cloning Notion as a beginner.

---

<div align="center">

*Building systems, one abstraction at a time.*

**[nivekithan.com](https://nivekithan.com)** • **[nivekithan363@gmail.com](mailto:nivekithan363@gmail.com)** • **[@nivekithanS](https://twitter.com/nivekithanS)**

</div>
