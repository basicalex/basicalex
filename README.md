<!-- ===================== HERO ===================== -->

<div align="center">

# Alex Basic

<div align="center">
  <a href="https://git.io/typing-svg">
    <img
      src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=1500&pause=1000&color=AFFF00&background=0B0F1A&center=false&vCenter=false&width=600&lines=%24+build.+harden.+ship.;%3E+automation%3A+enabled;%3E+reliability%3A+enforced;%3E+system+ready."
      alt="Typing SVG"
    />
  </a>
</div>

<p>
  <img alt="Rust" src="https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white" />
  <img alt="Shell" src="https://img.shields.io/badge/Shell-121011?style=for-the-badge&logo=gnu-bash&logoColor=white" />
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-1e293b?style=for-the-badge&logo=typescript&logoColor=white" />
  <img alt="Linux" src="https://img.shields.io/badge/Linux-111827?style=for-the-badge&logo=linux&logoColor=white" />
</p>

<p>
I build <b>terminal-first, agentic systems</b> and <b>human-centered solutions</b> that turn messy reality into usable interfaces: between people, data, and decisions.
</p>

<p>
<b>Current obsession:</b> making AI-assisted development <b>reproducible</b>, <b>stateful</b>, and <b>team-consistent</b>.
</p>

</div>

---

## ⚙️ Flagship: Agent Ops Cockpit (AOC)

**AOC** is a **Zellij-based terminal AI development workspace** that combines multi-agent coding, persistent project context, task execution, and memory — all inside one cockpit.

### Why it matters
- Kills “AI session amnesia” with **durable, project-local state**
- Makes agent workflows **predictable across a team** (shared context = shared behavior)
- Keeps planning + execution tight with **task ⇄ PRD linkage**

### Core architecture (repo-local, agent-readable)

```mermaid
flowchart TB
  A[Developer] --> Z[Zellij Cockpit]

  subgraph RepoLocal["Repo-local state"]
    C[.aoc/context.md]
    M[.aoc/memory.md]
    S[.aoc/stm/]
    T[.taskmaster/tasks/tasks.json]
    P[.taskmaster/docs/prds/]
  end

  Z --> C
  Z --> M
  Z --> S
  Z --> T
  T --> P

  Z --> AG[Agent CLIs]
  AG --> X[Codex]
  AG --> Y[Gemini]
  AG --> W[Claude]
  AG --> V[OpenCode]
