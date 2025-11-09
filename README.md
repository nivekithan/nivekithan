### Hi there 👋

I am Nivekithan S, a Backend Engineer currently working at [EPYC](https://www.linkedin.com/company/epyc/).

I write blogs at [nivekithan.com](https://nivekithan.com).

Connect with me at `nivekithan363@gmail.com` or on Twitter `https://twitter.com/nivekithanS`.

### Core Technologies

**Languages:** TypeScript, Go, Kotlin, JavaScript

**Backend & Infrastructure:** Node.js, Cloudflare Workers, Express.js, Hono, AWS (Batch, Lambda, S3)

**Databases:** PostgreSQL

**Frontend:** React, Next.js, React Router, Remix, Vite


### Work Experience

I am currently working as a Backend Engineer at [EPYC](https://www.linkedin.com/company/epyc/).

Here are the key projects I have delivered for various clients:

#### 1. Scheduling System

Implemented a scheduling system that allows users to book appointments with industry experts.

**Key Features:**
- Prevented double booking through proper concurrency handling
- Integrated with Razorpay to prevent duplicate payments and bookings for unavailable slots
- Enabled mentors to set custom availability schedules
- Synchronized with Google Calendar to prevent scheduling conflicts

**Tech Stack:** TypeScript, React (React Router v7), Cloudflare Workers, PostgreSQL

#### 2. Shopify Credits System for Airlines

Built a credits management system for airline companies to provide uniform purchase credits to their employees through a Shopify store.

**Key Features:**
- Handled all concurrency edge cases to ensure balances never go below zero
- Ensured accurate balance updates across refunds, cancellations, and returns
- Integrated with custom tax processing software for accurate sales tax deduction
- Provided comprehensive analytics dashboards for both vendors and airline companies

**Tech Stack:** TypeScript, React (Next.js), Cloudflare Workers, PostgreSQL

#### 3. Funding Application Platform

Developed a collaboration platform where founders can apply for funding, with an internal dashboard for investors to review applications.

**Key Features:**
- Reconciled applications across Algolia and multiple internal APIs
- Implemented duplicate detection and missing application handling
- Built a fault-tolerant system that maintains functionality with minimal degradation even when internal APIs are down

**Tech Stack:** TypeScript, React (React Router v7), Cloudflare Workers, PostgreSQL

#### Additional Achievements

In other projects, I have:

1. Designed and implemented a feature that sends 10,000+ Slack DM messages while respecting rate limits using Bull queue
2. Successfully transformed a monolithic backend into separate job and request services, significantly reducing memory and CPU usage while ensuring seamless operation during high job loads
3. Contributed to developing a payment gateway for an events system, enabling customers to seamlessly process transactions via Stripe
4. Contributed to migrating services from Digital Ocean to AWS, resulting in improved product performance
5. Created a CLI tool that initializes the development environment locally, reducing setup time from 2+ days to minutes for new hires
6. Orchestrated a gradual transition from JavaScript to JavaScript with JSDoc, reducing runtime errors and improving developer experience without compromising feature delivery timelines

### Featured Projects

Whenever I get free time, I like to work on projects to satisfy my curiosity about new technologies and understand their tradeoffs compared to current technologies.

## Levenshtein Automata

A Kotlin implementation of Levenshtein Automata for fast fuzzy string searching in large dictionaries. This project implements various optimizations described in the Schulz & Mihov paper, achieving 10,727 queries/second on a 370,000-word dictionary.

**Key Features:**
- Multiple implementation versions (v1-v7) showcasing progressive optimizations
- Precomputed DFA construction for maximum performance
- Trie-based dictionary for efficient prefix sharing
- Support for edit distances up to 9
- Comprehensive benchmarking suite
- 38% performance improvement over runtime construction at distance 3

- Github Repo: https://github.com/nivekithan/levenshtein-automata

## Go Raft

Implementation of the Raft consensus algorithm in Go with minimal mutex usage. To ensure correctness and safety, the implementation was formally verified using P-lang for model checking before coding.

**Key Features:**
- Raft consensus algorithm implementation in Go
- Minimal mutex usage for better performance
- Formally verified using P-lang model checking
- Based on the original Raft paper by Ongaro and Ousterhout

- Github Repo: https://github.com/nivekithan/go-raft
- P-lang Models: https://github.com/nivekithan/p-models
- Original Paper: https://raft.github.io/raft.pdf

## Protohackers Solutions (go-network)

Solutions for [Protohackers](https://protohackers.com/) network programming challenges implemented in Go. A series of increasingly complex TCP/UDP server implementations covering various networking concepts and custom protocol implementations.

**Problems Solved:**
- Line Reversal: Custom LRCP protocol implementation over UDP with acknowledgments and retransmission
- Speed Daemon: Speed camera and ticketing system with binary TCP protocol
- Mob in the Middle: TCP proxy with address rewriting
- Unusual Database Program: UDP key-value store
- Budget Chat: Multi-user chat room server
- Means to an End: Asset price tracking with binary protocol and SQLite
- Prime Time: JSON primality testing server

- Github Repo: https://github.com/nivekithan/go-network

## Tango Programming Language

A custom programming language with its own compiler and virtual machine, implemented in Go. Tango supports variable declarations, arithmetic and boolean operations, and includes a full compilation pipeline from lexer to bytecode execution.

**Key Features:**
- Complete compiler implementation (lexer, parser, AST, compiler, VM)
- Bytecode compilation and execution
- Interactive REPL for development
- Support for variables, arithmetic, and boolean operations
- Built entirely in Go

- Github Repo: https://github.com/nivekithan/tango

## Blender Render Farm

A serverless distributed rendering system for Blender animations using AWS Batch, S3, and Lambda. This project enables parallel frame rendering of Blender projects in the cloud, perfect for rendering complex animations faster by distributing frames across multiple Fargate containers.

**Key Features:**
- Parallel frame rendering using AWS Batch with Fargate
- Automatic frame consolidation into ZIP archives
- Lambda-triggered orchestration via S3 upload events
- Infrastructure as code using Pulumi
- Built with Go, Docker, AWS Batch, and S3

- Github Repo: https://github.com/nivekithan/blender-render-farm

## TypeScript Compiler

An educational compiler that converts a subset of TypeScript to native code using LLVM backend. This project demonstrates compiler design principles with comprehensive test coverage for all supported language features.

**Supported Features:**
- Variable declarations (const, let) with type annotations
- Unary and binary expressions
- Control flow (if/else if/else, while, do-while)
- Function declarations with typed parameters
- Comparison and logical operators
- Built with LLVM for native code generation

- Github Repo: https://github.com/nivekithan/compiler

### Other Projects

## Maailit

A temporary email service designed for developers who need to test email functionality, OTP verification, and password resets without cluttering their personal inboxes. Get instant access to temporary emails with real-time updates and AI-powered CTA detection.

**Key Features:**
- Instant email access at `yourslug@maailit.com`
- Real-time updates via WebSocket
- AI-powered extraction of verification codes and links using GPT-4o-mini
- Auto-cleanup after 15 minutes
- No registration required
- Built with Next.js 14, Cloudflare Workers, Durable Objects, and D1

- Live Version: https://maailit.com
- Github Repo: https://github.com/nivekithan/maailit

## Fireside Events

A real-time video broadcasting application built with WebRTC, Cloudflare Workers, and XState state machines. Experience multi-participant video calls with seamless screen sharing capabilities, powered by sophisticated state management.

**Key Features:**
- Real-time video broadcasting with multiple participants
- Screen sharing functionality
- XState v5 state machines for complex UI flows
- WebSocket-based signaling using Cloudflare Durable Objects
- Adaptive video states with pause/resume
- Built with React Router v7, Cloudflare Calls API, and Drizzle ORM

- Live Version: https://calls.nivekithan.com/
- State Machine Visualization: https://stately.ai/registry/editor/1f4bf00b-3305-47d0-8a41-6883662fc62b?machineId=f618d82b-9ff8-4384-a22d-80a650c9d620
- Github Repo: https://github.com/nivekithan/fireside-events

## Chat with JSON

A web application that lets you chat with your JSON files using natural language, powered by OpenAI's GPT-4. Upload a JSON file, ask questions about your data, and get AI-powered analysis with automatically generated and executed JavaScript code.

**Key Features:**
- Natural language queries for JSON data analysis
- Automatic JSON schema generation for better context
- Client-side processing - your data never leaves your browser
- Real-time chat interface with streaming responses
- Built with Remix, Vercel AI SDK, and deployed on Cloudflare Pages

- Live Version: https://chat-with-json.nivekithan.com
- Github Repo: https://github.com/nivekithan/chat-with-json

## pg-cluster

A Kubernetes operator for managing PostgreSQL database clusters with built-in backup, Point-in-Time Recovery (PITR), and easy database provisioning - designed for dynamic environments like PR preview deployments.

**Status:** Work in Progress

**Key Features (Planned):**
- PostgreSQL cluster management on Kubernetes
- Automated backups with pgBackRest integration
- Point-in-Time Recovery (PITR)
- On-demand database provisioning for PR previews
- Built with TypeScript, Effect-TS, Zod, and PostgreSQL 17

- Github Repo: https://github.com/nivekithan/pg-cluster

### Challenges & Learning

## Fly.io Distributed System Challenges

Doing a full-stack project is a huge time commitment. That's why I prefer to do challenges when I want to learn a particular concept with clearly defined requirements and constraints.

One of those challenges is [Fly.io Distributed System Challenges](https://fly.io/dist-sys/).

I have completed these challenges:

1. Echo - https://fly.io/dist-sys/1/
2. Unique ID Generation - https://fly.io/dist-sys/2/
3. Single Node Broadcast - https://fly.io/dist-sys/3a/
4. Multi Node Broadcast - https://fly.io/dist-sys/3b/
5. Fault-Tolerant Broadcast - https://fly.io/dist-sys/3c/
6. Efficient Broadcast - https://fly.io/dist-sys/3d/

You can check my solutions at [Solutions for fly.io challenges using Deno](https://github.com/nivekithan/deno-fly)

### Early Projects

## Path Finder

One of the first projects I did as a beginner. I was learning about path-finding algorithms and thought it would be fun to implement a visualizer for the algorithm.

- Live Site: https://path-finder-brown.vercel.app/
- Github Repo: https://github.com/nivekithan/path-finder

## Slatejs Devtools

`slate-js` is a library for creating rich text editors. When I was a beginner, I was working on creating a clone of Notion, which led me to `slate-js`. The Notion text editor is hugely complex, and whenever I ran into bugs while implementing those features using `slate-js`, it used to take me a long time to pin down the bug.

That's when I decided to build `slate-js-devtools` to make my debugging experience better.

- npm package: https://www.npmjs.com/package/slate-devtools
- Github Repo: https://github.com/nivekithan/slate-devtools
