### Hi there 👋

I am Nivekithan S, I am fullstack developer currently working in [Magic](https://www.linkedin.com/company/usemagic) in the role Product Engineer (Backend).

Connect with me at `nivekithan363@gmail.com` or at twitter `https://twitter.com/nivekithanS`

### Work Experience

I am working as Product Engineer at [Magic](https://www.linkedin.com/compay/usemagic). Some of my notable achievements include

1. Designed and implemented a feature that sends more than 10,000 slack DM messages while also respecting the slack ratelimit using bull queue
2. Created a Chatbot using `NextJs`, `supabase (Postgres)`, `openai` and `langchain` in typescript `language` which when deployed increases customer interaction and reduces customer support.
3. Successfully transformed monolithic backend into separate job and request services, significantly reducing memory and CPU usage. This ensured seamless operation during high job loads.
4. Contributed to the development of a payment gateway for the events system, empowering our customers to seamlessly utilize Stripe for event-related transactions.
5. Worked on setting up Prometheus, Loki, Grafanna for our frontend and backend service while also making minimal changes to our codebase so that we can continuously develop our product.
6. Contributed to migrating our service from Digital Ocean to AWS leading to improved performance of our product
7. Took ownership and created a `cli` tool that initializes our development environment locally after one of our new hires took more than two days to setup the development environment locally.
8. Took ownership and orchestrated a gradual transition of our product's codebase from Javascript to Javascript with `JsDoc` leading to less runtime errors and better DX without compromising development timelines for ongoing features.

### Projects

Whenever I get free time, I like to work on projects to satisfy my curiosity about new technologies and understand their tradeoff compared to current technologies.


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

## Blender Render Farm

A serverless distributed rendering system for Blender animations using AWS Batch, S3, and Lambda. This project enables parallel frame rendering of Blender projects in the cloud, perfect for rendering complex animations faster by distributing frames across multiple Fargate containers.

**Key Features:**
- Parallel frame rendering using AWS Batch with Fargate
- Automatic frame consolidation into ZIP archives
- Lambda-triggered orchestration via S3 upload events
- Infrastructure as code using Pulumi
- Built with Go, Docker, AWS Batch, and S3

- Github Repo: https://github.com/nivekithan/blender-render-farm


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


## Cartoon Generator

An AI-powered political cartoon generator that creates simple black and white cartoons based on user-provided topics. Uses GPT-4 for prompt enhancement and Flux 1.1 Pro for high-quality image generation.

**Key Features:**
- Generate political cartoons from text prompts
- AI-powered prompt enhancement using GPT-4o
- High-quality image generation using Replicate's Flux 1.1 Pro
- Gallery view of generated cartoons
- Built with React, Vite, Hono, Cloudflare Workers, D1, and R2

- Live Version: https://cartoon-gen.nivekithan.com/
- Github Repo: https://github.com/nivekithan/cartoon_gen

## Screenshot Page

A free tool to take screenshots of any website using Cloudflare's Browser Rendering API. Supports multiple device types (mobile, tablet, desktop) and full-page screenshots with fast and reliable rendering.

**Key Features:**
- Screenshot any publicly accessible website
- Multiple device type support
- Full page screenshot option
- Built with Remix, Cloudflare Pages, Workers, and R2
- Fast rendering using Cloudflare Browser API

- Live Version: https://screenshot.nivekithan.com/
- Github Repo: https://github.com/nivekithan/screenshot-page

## Path Finder

It is one of the first projects I did as a beginner, I was learning about path-finding algorithms and I thought how fun it will be if I implemented a visualizer for the algorithm.

- Live Site: https://path-finder-brown.vercel.app/
- Github Repo: https://github.com/nivekithan/path-finder

## Slatejs Devtools

`slate-js` is a library for creating a rich text editor. When I was a beginner I was working on creating a clone of notion, which lead me to `slate-js`. Notion text editor is hugely complex. Whenever I run into bugs while implementing those features using `slate-js` it used to take me a long time to pin down the bug.

That's when I decided to build `slate-js-devtools` to make my debugging experience better.

- npm package: https://www.npmjs.com/package/slate-devtools
- Github Repo: https://github.com/nivekithan/slate-devtools

### Fly.io Distributed System Challenges

Doing a full-stack project is a huge time commitment. That's I prefer to do challenges when I want to learn a particular concept with clearly defined requirements and constraints.

One of those challenges is [Fly.io Distributed system challenges](https://fly.io/dist-sys/)

Till now I have completed these challenges

1. Echo - https://fly.io/dist-sys/1/
2. Unqiue Id generateion - https://fly.io/dist-sys/2/
3. Single Node Broadcast - https://fly.io/dist-sys/3a/
4. Multi Node Broadcast - https://fly.io/dist-sys/3b/
5. Fault-Tolerant Broadcast - https://fly.io/dist-sys/3c/
6. Efficiency Broadcast - https://fly.io/dist-sys/3d/

You can check my solutions at [Solution for fly.io challenge using deno](https://github.com/nivekithan/deno-fly)


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

## Low Code Builder

A visual, node-based low-code builder for creating API endpoints through an intuitive drag-and-drop interface. Build API workflows visually and compile them into deployable Cloudflare Workers with production-ready code.

**Key Features:**
- Visual API design using a node-based editor
- API Request, Response, and If/Else condition nodes
- Automatic graph layout with Dagre and ELK
- Real-time autosave
- Code generation that compiles visual workflows into JavaScript
- Built with Electron, React Flow, tRPC, and TypeScript

- Github Repo: https://github.com/nivekithan/low-code-builder
