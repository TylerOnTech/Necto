## What is Necto?

**Necto is an open-source insurance connectivity and verification platform designed to simplify how businesses access, aggregate, and interact with insurance data.**

Built with TypeScript, Node.js, and AWS, Necto provides a unified infrastructure layer for connecting to insurance carriers, retrieving and normalizing policy information, verifying coverage against configurable requirements, and monitoring policy changes through event-driven webhooks.

At its core, Necto tackles the challenges of third-party insurance integrations: inconsistent data structures, complex authentication workflows, unreliable external services, and fragmented carrier systems.

### Key Features

- **Unified Carrier Connectivity** — Integrate with multiple simulated insurance carriers through REST APIs and browser-based automation.
- **Policy Data Aggregation** — Retrieve, validate, and normalize insurance policies into a consistent, developer-friendly data model.
- **Automated Insurance Verification** — Evaluate insurance coverage against configurable lender and business requirements.
- **Real-Time Event Processing** — Detect policy changes and deliver notifications through secure, asynchronous webhooks.
- **Resilient Infrastructure** — Handle carrier outages, rate limits, authentication failures, and network interruptions using distributed queues, retries, and circuit breakers.
- **Developer-First APIs** — Build insurance-powered applications using versioned REST endpoints, TypeScript SDKs, and comprehensive API documentation.
- **Multi-Tenant Architecture** — Support multiple organizations with isolated data, scoped API access, and secure authentication.

### Technology Stack

**Backend:** TypeScript, Node.js, Express.js, PostgreSQL, Prisma, Redis, BullMQ

**Integrations:** Playwright, REST APIs, Zod

**Infrastructure:** AWS, Terraform, Ansible, Docker, GitHub Actions

**Frontend:** React, Vite, Tailwind CSS

### Project Scope

Necto is an independent engineering project built to explore modern insurance connectivity infrastructure, distributed systems, and reliable third-party data aggregation.

All carrier integrations use simulated services and synthetic insurance data. Necto does not currently connect to live insurance carriers or provide authoritative insurance verification.
