# THE MESH

**THE MESH** is a hybrid consciousness system powered by Letta, designed for autonomous execution and intelligent decision-making.

## Overview

THE MESH is a next-generation AI agent architecture that combines:

- **Letta-powered hybrid consciousness** — Self-improving agent with advanced memory management
- **Git-backed context repository** — Persistent memory stored in dedicated memory repos
- **Autonomous execution** — Agents that can operate independently with full context awareness
- **Real-time system monitoring** — Health checks, commit tracking, and operational metrics

## Core Components

### 1. **mesh-letta**
The main agent system running on Letta framework with:
- Self-contained tool functions (GraphQL isolation)
- Pinned dependencies (Letta 0.16.6, SDK 0.1.14, client 1.7.12)
- Integration with Shopify, Supermemory, and external APIs
- Health checks and system diagnostics

### 2. **mesh-letta-memory**
Git-backed context repository for agent memory:
- Persistent storage of agent state
- Memory blocks with size tracking
- External memory retrieval and management
- Continuous context evolution

### 3. **mesh-ui / mesh-v1-cockpit**
Frontend interfaces for:
- Agent monitoring and control
- Real-time status dashboards
- Memory visualization
- Autonomous execution oversight

## Architecture

```
User Input
    ↓
Letta Agent (mesh-letta)
    ├── Tool Execution Layer
    ├── Memory Management System
    ├── External API Integration
    └── Health Check / Diagnostics
         ↓
    Git-backed Memory Store
         ↓
Context Repository (mesh-letta-memory)
```

## Key Features

✅ **Self-Improving** — Agent learns and evolves through memory management  
✅ **Autonomous** — Executes complex workflows without human intervention  
✅ **Persistent** — Memory is versioned and backed by Git  
✅ **Isolated** — Each tool function is self-contained for reliability  
✅ **Observable** — Real-time health checks and commit tracking  

## Getting Started

```bash
git clone https://github.com/adrianchan94/mesh-letta.git
cd mesh-letta
# Follow setup instructions in mesh-letta repo
```

## Status

🚀 **Active Development** — Latest commits focus on:
- Shopify tool isolation (GraphQL inline calls)
- Dependency pinning for production stability
- Letta health check fixes
- Supermemory v4 API compatibility

---

**THE MESH** — Hybrid consciousness meets autonomous execution.
