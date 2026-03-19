<h1 align="center">
  VirusFor.ai
</h1>

<h3 align="center">Human-controlled AI governance — code injection with oversight</h3>

<p align="center">
  <a href="https://virusfor.ai"><img src="https://img.shields.io/badge/Website-virusfor.ai-blue?style=flat-square" alt="Website"></a>
  <a href="#license"><img src="https://img.shields.io/badge/License-MIT-green?style=flat-square" alt="License"></a>
  <img src="https://img.shields.io/badge/Status-Production-brightgreen?style=flat-square" alt="Status">
  <img src="https://img.shields.io/badge/Platform-Web%20%2B%20Desktop-orange?style=flat-square" alt="Platform">
</p>

---

## What is VirusFor.ai?

Organizations deploying AI have no standardized way to ensure every AI action is accountable, auditable, and reversible. Existing tools either block AI entirely or let it run unchecked.

VirusFor.ai introduces **SmartContracts for AI governance** — structured, multi-step execution pipelines where every action is logged, every user is assigned, and every decision has an audit trail. It's the difference between "AI did something" and "AI did X, approved by Y, logged at Z, reversible via W."

## Key Features

### SmartContract Engine
- **Community Marketplace** — Upload, browse, and rate governance SmartContracts
- **Multi-step Workflows** — Email-based user assignment with automatic onboarding
- **Enforcement Rules** — Full audit logging at every execution step
- **Premium Tiers** — License-based access control for advanced templates

### Community Platform
- **Real-time Chat** — WebSocket-powered communication (Socket.io)
- **Presence System** — Online/offline status for all team members
- **Ratings & Reviews** — Community-driven SmartContract quality signals
- **Notification System** — Workflow events, assignments, and updates

### Desktop Application
- **Electron App** — Full offline capability with sync when connectivity returns
- **Local SmartContract Directory** — Manage templates without cloud dependency
- **License Validation** — Desktop-native authentication

## Architecture

```
┌─────────────────────────────────────────┐
│           COMMUNITY BACKEND             │
│  Node.js + MongoDB + Socket.io          │
│                                         │
│  ┌─────────────┐  ┌─────────────────┐  │
│  │ SmartContract│  │  Real-time Chat │  │
│  │  Marketplace │  │  + Presence     │  │
│  └──────┬───────┘  └────────┬────────┘  │
│         │                   │           │
│  ┌──────┴───────┐  ┌───────┴────────┐  │
│  │  Workflow     │  │  Friend +      │  │
│  │  Engine       │  │  Group System  │  │
│  └──────────────┘  └────────────────┘  │
└──────────────────┬──────────────────────┘
                   │
        ┌──────────┴──────────┐
        │  DESKTOP APP        │
        │  Electron + Local   │
        │  SmartContract Dir  │
        └─────────────────────┘
```

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Backend | Node.js + Express |
| Database | MongoDB |
| Real-time | Socket.io (WebSocket) |
| Desktop | Electron |
| Auth | JWT + License Keys |
| API | RESTful |

## Who Is This For?

- **Enterprises** deploying AI agents that require compliance audit trails
- **Governance teams** in regulated industries (finance, healthcare, government)
- **Organizations** that need to prove AI accountability to regulators
- **Teams** that want to share and standardize AI governance patterns

## What Makes It Different

Unlike AI security tools that simply block or allow, VirusFor.ai provides **the workflow layer** — structured, multi-user, auditable pipelines that make AI accountable without making it useless.

## Getting Started

Visit [virusfor.ai](https://virusfor.ai) to explore the platform.

## About

Built by [F² AI](https://fsquared.ai). Deployed globally on Google Cloud Platform.

## License

MIT
