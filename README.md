<div align="center">

# Hi, I'm mhkr9100 👋

### Building the personal AI layer between **your data, your desktop, and your agents**.

<p>
  <a href="https://github.com/mhkr9100?tab=repositories"><img src="https://img.shields.io/badge/Projects-Local--First%20AI-7c3aed?style=for-the-badge&logo=github&logoColor=white" alt="Projects" /></a>
  <a href="https://github.com/mhkr9100/UserMap"><img src="https://img.shields.io/badge/Flagship-UserMap-06b6d4?style=for-the-badge" alt="UserMap" /></a>
  <a href="https://github.com/mhkr9100/Screenmate"><img src="https://img.shields.io/badge/Automation-Screenmate-f59e0b?style=for-the-badge" alt="Screenmate" /></a>
</p>

<p>
  <em>Local-first AI systems · Agentic tools · Personal context infrastructure · Desktop automation</em>
</p>

</div>

---

## ⚡ The big idea

AI already knows a lot about the world. I am building the systems that help AI understand **you** — your context, your workflows, your decisions, and the tools you use every day.

My projects explore a more useful kind of AI:

- 🔒 **Private by default** — personal data stays close to the user
- 🧠 **Context-aware** — durable memory instead of disposable chat history
- 🖥️ **Able to act** — real desktop interaction, not just text generation
- 🧩 **Composable** — adapters, connectors, APIs, and automation workflows
- 🛠️ **Practical** — designed for actual work, not just demos

> **My direction:** turn local AI from a chatbot into a private, dependable operating layer for personal work.

---

## 🚀 Featured projects

### 🧠 [UserMap](https://github.com/mhkr9100/UserMap) · Personal Context OS

> **AI knows the world. UserMap helps AI know you.**

UserMap is a local-first personal context platform that ingests information from your tools, structures it into a personal knowledge graph, and makes it searchable, editable, and useful to agents.

**What makes it stand out:**

- 🔌 Pull connectors for Slack, Instagram, Facebook, and more
- 🔍 Full-text context retrieval with structured memory units
- 🗺️ MindMap, Tree, Flow Chart, and List views for exploring context
- 🤖 Prism Agent for classification, extraction, and knowledge structuring
- 🧠 Pattern-based memory categories: decisions, preferences, milestones, problems, and emotions
- 🔁 Deduplication, conflict detection, provenance, and lifecycle logs
- ⚙️ Push integrations for n8n, Make, and custom webhooks
- 🗄️ SQLite as the canonical source of truth with derived search/vector layers
- 🔒 No required cloud account, no telemetry, and local data ownership

**Stack:** `React` `Vite` `TypeScript` `Express` `SQLite` `FTS` `Chroma` `Webhooks`

---

### 🖥️ [Raman AI](https://github.com/mhkr9100/RamNAI) · Desktop AI Workspace

> **A private AI workspace that lives with the user.**

Raman AI is a desktop-first AI system built around real local execution, durable context, and personal workspaces instead of a hosted control plane.

**What it brings together:**

- 🪟 Electron desktop shell with renderer and IPC bridge
- 🧱 Local SQLite-backed persistence
- 🧠 Durable facts and internal context memory
- 🦙 Ollama-powered local runtime
- 📁 Filesystem workspace export
- ⏰ Scheduled tasks and council runs
- 🛠️ Ask, create, and work-surface flows
- 📦 Runtime adapters designed for extensibility

**Stack:** `TypeScript` `React` `Electron` `Node.js` `SQLite` `Ollama`

---

### 🤖 [Screenmate](https://github.com/mhkr9100/Screenmate) · Skills for AI Agents

> **Eyes, hands, and ears for agents operating real computers.**

Screenmate is a local Python toolkit that lets agents observe screens, control input, listen to OS events, and record workflows as portable skills that can be replayed later.

| Capability | What it does |
|---|---|
| 👁️ **Eyes** | Screen capture and visual change detection |
| 🖱️ **Hands** | Mouse, keyboard, hotkey, and text actuation |
| 👂 **Ears** | Global OS input hooks |
| 🎬 **Skills** | Record, save, and replay human workflows |

**Agent integrations include:** OpenClaw, Open Interpreter, Claude Desktop, Cursor, LangChain, and LangGraph.

The core design principle is simple: use structured input events whenever possible, and use vision as a targeted fallback. That keeps automation faster, more reliable, and cheaper than constant screen watching.

**Stack:** `Python` `mss` `imagehash` `pyautogui` `pynput` `MCP` `LangChain`

---

### 🧩 [RamN-AI](https://github.com/mhkr9100/RamN-AI) · Multi-Agent Orchestration

An earlier multi-agent workspace exploring specialized agents, model routing, dynamic workspaces, memory data, and orchestrated execution across different AI providers.

**Explored concepts:**

- Prism meta-agent orchestration
- Role-playing specialist agents
- OpenRouter and Hugging Face model routing
- Local workspaces and asynchronous workflows
- Knowledge ingestion from PDF, TXT, and DOCX data

---

## 🧭 How the projects connect

```text
                Personal context
                      │
                      ▼
       ┌─────────────────────────────┐
       │           UserMap            │
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

## 🛠️ Technology landscape

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

## 🔭 What I'm exploring next

- More reliable long-term personal memory and context retrieval
- Local model routing and runtime abstraction
- Agent workflows that can safely operate desktop applications
- Human-in-the-loop automation with inspectable actions
- Cross-device synchronization without surrendering data ownership
- Better standards for portable skills, memories, and agent tools

---

## 🌟 Find me in the work

If you are interested in **local AI, personal knowledge systems, desktop agents, privacy-first automation, or practical agent infrastructure**, start here:

- ⭐ [UserMap](https://github.com/mhkr9100/UserMap) — personal context and memory
- 🖥️ [Raman AI](https://github.com/mhkr9100/RamNAI) — local desktop AI workspace
- 🤖 [Screenmate](https://github.com/mhkr9100/Screenmate) — agent computer interaction
- 🧩 [RamN-AI](https://github.com/mhkr9100/RamN-AI) — multi-agent orchestration

<div align="center">

### Building toward AI that remembers, reasons, and acts — while keeping the user in control.

</div>
