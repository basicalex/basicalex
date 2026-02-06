
# Alex Basic

I build **terminal-first, agentic systems** and **human-centered solutions** that turn messy reality into usable interfaces: between people, data, and decisions.

**Current obsession:** making AI-assisted development **reproducible**, **stateful**, and **team-consistent**.

---

## ⚙️ Flagship: Agent Ops Cockpit (AOC)

**AOC** is a **Zellij-based terminal AI development workspace** that combines multi-agent coding, persistent project context, task execution, and memory — all inside one cockpit.

**Why it matters**
- Kills “AI session amnesia” with **durable, project-local state**
- Makes agent workflows **predictable across a team** (shared context = shared behavior)
- Keeps planning + execution tight with **task ⇄ PRD linkage**

**Core layers**
- `.aoc/context.md` — auto-generated project map + snapshot  
- `.aoc/memory.md` — append-only decision log (“why we did it”)  
- `.aoc/stm/` — short-term handoff buffer  
- `.taskmaster/tasks/tasks.json` — execution queue w/ deps + subtasks  
- `.taskmaster/docs/prds/` + `aocPrd` — per-task specs for quality + auditability

**Stack**
- Shell orchestration (`bin/`)
- Rust crates (`crates/`) for CLI/core/TUI/installer
- Zellij layouts (`zellij/`), Yazi integration (`yazi/`), docs (`docs/`)

**License**
- Open source under **Apache 2.0** (enterprise-friendly, patent grant, easy adoption).

---

## 🌍 The wider ecosystem (Intrface)

I’m building a set of systems that share one philosophy: **Designed for humans.**
A few threads you’ll see in my repos:

- **Civic engagement AI** — collecting public concerns, summarizing, categorizing, and supporting better municipal decisions
- **Extended Mind / HyperMind** — turning conversations into a structured, version-controlled knowledge system
- **AgroPulse** — satellite-first crop intelligence/monitoring (crop insights, anomaly detection, decision support)

---

## 🧠 How I work

- **Terminal-native** workflows (Zellij, CLI-first tools)
- **Contracts > vibes**: project state, style, and decisions written down where agents can read them
- **Multi-agent orchestration** with clear roles, bounded context, and repeatable operations
- Build fast, then **harden for reliability** (diagnostics, docs, predictable setup)

---

## 🧰 Tech I touch a lot

- **Rust / Shell / TypeScript**
- **Zellij**, **Yazi**, **pnpm**
- **Next.js**, **Payload**, **Convex**
- Agentic CLIs + model providers (Codex/Gemini/Claude/OpenCode workflows)

---

## 🤝 Collaborations & contributions

If you’re building:
- terminal-first dev tooling,
- agent orchestration systems,
- civic-tech / tourism platforms,
- or “stateful AI workflows” for teams…

…open an issue or PR. I like builders who ship.

---

## 📌 Pinned repos

Check the pinned section below for:
- **AOC (Agent Ops Cockpit)**
- agent workflows + automation experiments
- platform prototypes (Voyager / civic / knowledge systems)

---

<!-- Optional: GitHub widgets (uncomment if you want them)

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=YOUR_USERNAME&show_icons=true)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_USERNAME&layout=compact)

-->

<!-- Optional: Contact (add what you want public)
- Website: https://...
- X: https://...
- LinkedIn: https://...
-->
```

