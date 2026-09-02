# Hi, I'm justpassingByte

<div align="center">

### Full-Stack Engineer | Next.js • NestJS • PostgreSQL • Redis • Agentic AI

*Product-driven engineer architecting high-trust marketplaces, multi-gateway payment engines, distributed task queues, and agentic AI systems.*

[![GitHub](https://img.shields.io/badge/GitHub-justpassingByte-181717?style=for-the-badge&logo=github)](https://github.com/justpassingByte)
[![Facebook](https://img.shields.io/badge/Facebook-Leoz666-1877F2?style=for-the-badge&logo=facebook&logoColor=white)](https://facebook.com/Leoz666)
[![Discord](https://img.shields.io/badge/Discord-ngusitink-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.com/users/ngusitink)

</div>

---

## About Me & Career Aspirations

- **Current Focus:** Full-Stack Engineering at **Trustbase** (Digital Products & Freelance Marketplace).
- **Core Stack:** Next.js (Frontend), NestJS (Backend), PostgreSQL & Redis (Data, Caching, Locking & Queues).
- **AI-Native Engineering:** Designing structured software workflows with **Agentic Systems** — orchestrating subagent delegations, custom agent skills, domain rules, tool calling, and MCP for requirements modeling, refactoring, and code verification.
- **Career Growth & Philosophy:** 
  Driven by curiosity and a commitment to engineering excellence. I am actively looking to contribute within **high-standard, collaborative engineering teams** where I can execute fast while refining habits around rigorous code reviews, distributed system design, and production reliability.

---

## System Design & Architecture Highlights

Key engineering patterns and production challenges I tackle across real-world systems:

- **State-Driven Architectures (FSM):**  
  Model complex domain lifecycles (Order, Escrow, Dispute resolution) using Finite State Machines to enforce deterministic state transitions and eliminate race conditions under concurrent workloads.

- **Concurrency Control & Financial Data Integrity:**  
  Enforce pessimistic locking (`SELECT ... FOR UPDATE`) combined with Redis distributed locks to prevent double-spending, inventory overselling, and balance inconsistency under concurrent transactions.

- **Modular Payment Engines & Cashflow Integrity:**  
  Architect modular payment gateways using the Factory and Adapter patterns for seamless multi-provider expansion, integrated with webhook idempotency keys to prevent duplicate transactions and automate revenue reconciliation.

- **Asynchronous Task Processing & Event Queues (BullMQ / Redis):**  
  Decouple resource-intensive operations (escrow settlement, receipt generation, webhook dispatches) into background job queues with exponential backoff retries and Dead Letter Queues (DLQ).

- **Secure Digital Asset Delivery (Presigned S3 URLs):**  
  Design direct cloud-storage upload/download pipelines with short-lived presigned URLs and cryptographic signatures, eliminating I/O bottlenecks on backend servers while securing digital property.

- **Authentication & Multi-Tier Access Control:**  
  Implement robust JWT authentication with refresh token rotation, multi-device session management, and multi-tier role-based access control (RBAC).

- **Testing, Quality & Production Observability:**  
  Write comprehensive Unit and Integration tests (Vitest, Testcontainers) for critical business logic and state transitions; incorporate structured logging with Correlation IDs for end-to-end request tracing.

---

## Agentic AI Workflows & Code Review

Treating AI not as a stochastic code generator, but as a structured, deterministic workflow:

- **Hierarchical Subagent Orchestration:** Break complex business problems into scoped subtasks and orchestrate concurrent background agent delegations.
- **Context-Aware Rules & Domain Skills:** Establish system rules and specialized skills that enforce codebase patterns, typing standards, and architectural boundaries.
- **Automated Verification & Code Review:** Utilize continuous AI-assisted review pipelines to inspect logic boundaries, test cases, and edge scenarios prior to merge.

---

## Featured Products & Ecosystems

### RobinHUD
**Transforming raw notes into high-dimensional strategic signals & exploit intelligence**

Converts unstructured, noisy poker observations into multidimensional tactical signals (position, street, board texture, stack depth, opponent tendencies). Combines RAG retrieval with LLM reasoning to identify behavioral leaks and produce precise exploit recommendations.

- **Stack:** Next.js, React, TypeScript, Node.js, RAG Retrieval, LLM Integration

---

### Testictour
**Empowering grassroots esports communities with daily competitive arenas & seamless rewards**

Centralizes the competitive tournament lifecycle: automated bracket management, cybercafe venue coordination, and real-time prize distribution. Creates accessible competitive environments for gamers while generating sustainable O2O revenue streams for venue operators.

- **Stack:** Next.js, Node.js, PostgreSQL, Bracket Engine, Leaderboard & Reward Logic

---

### ChayFood
**Harmonizing personal nutrition metrics with farm-to-table traceability**

Digitalizes healthy living through personalized nutrition calculation engines tailored to individual health metrics, connected directly to farm-to-table supply chains from organic agricultural partners.

- **Stack:** Next.js, NestJS, PostgreSQL, Redis, Data Modeling, Nutrition Metric Engine

---

### Trustbase
**Multi-vendor digital products & freelance marketplace**

Multi-vendor marketplace platform connecting digital creators and freelancers with clients globally through transparent transactions, role-based workflows, and secure cashflow escrow mechanics.

- **Stack:** Next.js, NestJS, PostgreSQL, Redis, BullMQ, Multi-Vendor Architecture, Payment Adapters

---

### Netsla
**Next-generation cybercafe ecosystem & community engagement hub**

Transforms traditional computer rental facilities into connected community hubs through workstation telemetry, member management, loyalty reward engines, and localized tournament operations.

- **Stack:** Next.js, React, Dashboard UX, Loyalty Engine

---

### Topic2Test
**Context-rich AI quiz engine & structured knowledge extraction**

Transforms raw documents and domain literature into structured, multi-choice question banks complete with reasoning explanations and multi-tier difficulty classifications via RAG and structured JSON outputs.

- **Stack:** Next.js, Node.js, RAG Retrieval, Structured JSON Output

---

### DealSniper
**Contextual shopping intelligence & automated price arbitrage**

Intelligent in-browser shopping assistant that evaluates product values, identifies optimal deals, and streamlines purchasing decisions directly within the shopping context.

- **Stack:** React, Next.js, Extension Architecture, Product Design

---

## Tech Stack & Tooling

### Core Backend & Frontend
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

### System Design & Concurrency Patterns
![State Machine](https://img.shields.io/badge/State_Machine_(FSM)-8B5CF6?style=for-the-badge&logo=diagramsdotnet&logoColor=white)
![Pessimistic Locking](https://img.shields.io/badge/DB_Locks_&_Transactions-0F766E?style=for-the-badge&logo=databricks&logoColor=white)
![Payment Factory](https://img.shields.io/badge/Payment_Factory_%26_Adapters-22C55E?style=for-the-badge&logo=cashapp&logoColor=white)
![BullMQ](https://img.shields.io/badge/BullMQ_&_Queues-CC3534?style=for-the-badge&logo=redis&logoColor=white)
![Cron Jobs](https://img.shields.io/badge/Cron_Jobs_%26_Workers-F59E0B?style=for-the-badge&logo=clockify&logoColor=white)
![JWT Auth](https://img.shields.io/badge/JWT_&_Refresh_Tokens-111827?style=for-the-badge&logo=jsonwebtokens&logoColor=white)
![Presigned S3](https://img.shields.io/badge/Presigned_URLs_(S3)-569A31?style=for-the-badge&logo=amazons3&logoColor=white)
![RBAC](https://img.shields.io/badge/RBAC_Auth-6366F1?style=for-the-badge&logo=auth0&logoColor=white)

### Testing & Observability
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white)
![Structured Logging](https://img.shields.io/badge/Correlation_Tracing-4B5563?style=for-the-badge&logo=sentry&logoColor=white)

### Agentic AI & Modern Tooling
![Subagents](https://img.shields.io/badge/Subagents_&_Delegations-7C3AED?style=for-the-badge&logo=probot&logoColor=white)
![Agent Skills](https://img.shields.io/badge/Agent_Skills_&_Rules-0EA5E9?style=for-the-badge&logo=codewars&logoColor=white)
![MCP](https://img.shields.io/badge/MCP_Architecture-374151?style=for-the-badge&logo=protocolsdotio&logoColor=white)
![Tool Calling](https://img.shields.io/badge/Tool_Calling_&_Plugins-10B981?style=for-the-badge&logo=octopusdeploy&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![DeepSeek DSH](https://img.shields.io/badge/DeepSeek_DSH-0066FF?style=for-the-badge&logo=deepseek&logoColor=white)
![Antigravity CLI](https://img.shields.io/badge/Antigravity_CLI-4285F4?style=for-the-badge&logo=google&logoColor=white)
![OpenAI Codex](https://img.shields.io/badge/Codex-111827?style=for-the-badge&logo=openai&logoColor=white)

### Server, DevOps & CI/CD
![PM2](https://img.shields.io/badge/PM2-2B037A?style=for-the-badge&logo=pm2&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![CI/CD](https://img.shields.io/badge/CI%2FCD_(GitHub_Actions)-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux_Server-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

---

## Engineering Mindset

```txt
System Integrity > Quick Fixes
Design clean transaction lifecycles, structured data contracts, and secure session boundaries.

Agentic Workflows > Raw Prompts
AI becomes a superpower when tools, domain skills, subagent delegations, and rules are systematically engineered.

Rigorous Code Review > Assumption-Driven Coding
Continuous learning and peer reviews build resilient, production-ready software.

Real-World Impact > Vanity Code
Great software completes the operational loop — from database records to real-world businesses.
```

---

## Contribution Activity

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/justpassingByte/justpassingByte/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/justpassingByte/justpassingByte/output/github-contribution-grid-snake.svg">
  <img alt="GitHub Contribution Snake Animation" src="https://raw.githubusercontent.com/justpassingByte/justpassingByte/output/github-contribution-grid-snake-dark.svg" width="100%">
</picture>

---

<div align="center">

### Let's build scalable systems and meaningful products.

</div>