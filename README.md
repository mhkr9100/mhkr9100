<div align="center">

# Hi, I'm Hemanth Kumar 👋

### Building the personal AI layer between **your data, your desktop, and your agents**.

<p>
  <a href="https://github.com/mhkr9100?tab=repositories"><img src="https://img.shields.io/badge/Projects-Local--First%20AI-7c3aed?style=for-the-badge&logo=github&logoColor=white" alt="Projects" /></a>
  <a href="https://github.com/mhkr9100/UserMap2"><img src="https://img.shields.io/badge/Flagship-UserMap2-06b6d4?style=for-the-badge" alt="UserMap2" /></a>
  <a href="https://github.com/mhkr9100/Screenmate"><img src="https://img.shields.io/badge/Automation-Screenmate-f59e0b?style=for-the-badge" alt="Screenmate" /></a>
</p>

<p>
  <em>Local-first AI systems · Agentic tools · Personal context infrastructure · Desktop automation</em>
</p>

<p>
  <strong>Contact:</strong>
  <a href="https://www.linkedin.com/in/hemanth-k-r-m-673b0b334/">LinkedIn</a> ·
  <a href="https://github.com/mhkr9100">GitHub Profile</a>
</p>

</div>

---

## The big idea

- I am not just trying to be a coder; I am an innovator who notices practical problems and gaps.
- I build local-first AI systems to optimize workflows, solve real friction, and fill missing layers.
- The goal is useful software that helps AI remember, reason, and act while users stay in control.

---

## Featured projects

### [UserMap2](https://github.com/mhkr9100/UserMap2) · Personal Context OS

> AI knows the world. UserMap2 helps AI know you.

Why this started: general AI has public knowledge, but not personal context. UserMap2 is built to close that gap with a local-first personal context layer.

What it provides (as documented in the repository README):

- Local-first personal context ingestion and search
- Prism Agent classification and knowledge structuring pipeline
- Data Studio MindMap with visual CRUD exploration
- Lifecycle logs timeline across connector, Prism, and user actions
- Pull connectors and push connectors (n8n, Make, webhooks)
- Structured Prism memory units with category-aware retrieval
- Deduplication and conflict handling in the memory pipeline
- SQLite canonical storage with FTS, with derived semantic/vector layers

Status: Phase 5 feature set documented in repository README.
Demo: see repository README.

**Stack:** `React` `Vite` `TypeScript` `Express` `SQLite` `FTS` `Chroma` `Webhooks`

---

### [Raman AI](https://github.com/mhkr9100/RamNAI) · Desktop AI Workspace (current)

> A private AI workspace that lives with the user.

Why this started: AI workspaces often depend on hosted control planes. Raman AI focuses on a desktop-first, local workspace with durable context and execution close to the user.

Raman AI is the current project. **RamN-AI** is the predecessor exploration that informed this direction.

Current foundation (as documented in Raman AI README):

- Electron desktop shell with renderer and IPC bridge
- Local profile flow and SQLite-backed persistence
- Filesystem workspace export
- Local Ollama runtime adapter
- Ask/create flows, scheduled tasks, and council runs
- Internal context memory and durable facts

Status: Current foundation documented in repository README.
Demo: see repository README.

**Stack:** `TypeScript` `React` `Electron` `Node.js` `SQLite` `Ollama`

---

### [Screenmate](https://github.com/mhkr9100/Screenmate) · Skills for AI Agents

> Eyes, hands, and ears for agents operating real computers.

Why this started: many "AI on desktop" demos rebuild the same primitives. Screenmate factors those primitives into a reusable local toolkit.

| Capability | What it does |
|---|---|
| Eyes | Screen capture and visual change detection |
| Hands | Mouse, keyboard, hotkey, and text actuation |
| Ears | Global OS input hooks |
| Skills | Record, save, and replay human workflows |

Agent integrations include OpenClaw, Open Interpreter, Claude Desktop, Cursor, LangChain, and LangGraph.

Status: Local Python package with documented CLI/Python usage and adapter integrations.
Demo: see repository README.

**Stack:** `Python` `mss` `imagehash` `pyautogui` `pynput` `MCP` `LangChain`

---

## How the projects connect

```text
                Personal context
                      │
                      ▼
       ┌─────────────────────────────┐
       │          UserMap2            │
       │  memory · knowledge · data   │
       └──────────────┬──────────────┘
                      │
                      ▼
       ┌─────────────────────────────┐
       │          Raman AI            │
       │  local runtime · workspace   │
       │  tasks · durable context     │
       └──────────────┬──────────────┘
                      │
                      ▼
       ┌─────────────────────────────┐
       │          Screenmate          │
       │  observe · act · automate    │
       │  recordable desktop skills   │
       └─────────────────────────────┘
```

Together, these projects point toward a personal AI stack with three layers:

1. **Remember** — capture and structure personal context.
2. **Think** — reason over local context and coordinate agents.
3. **Act** — operate tools and complete real workflows.

---

## Technology landscape

<p>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white" alt="Electron" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white" alt="SQLite" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white" alt="Ollama" />
  <img src="https://img.shields.io/badge/MCP-7C3AED?style=flat-square&logoColor=white" alt="MCP" />
  <img src="https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white" alt="n8n" />
</p>

---

## What I'm exploring next

- More reliable long-term personal memory and context retrieval
- Local model routing and runtime abstraction
- Agent workflows that can safely operate desktop applications
- Human-in-the-loop automation with inspectable actions
- Cross-device synchronization without surrendering data ownership
- Better standards for portable skills, memories, and agent tools

<div align="center">

### Building toward AI that remembers, reasons, and acts — while keeping the user in control.

</div>
