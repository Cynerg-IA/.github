<div align="center">

# Cynerg-IA

**One engineer. AI-augmented. Building lean software that does more with less.**

*Rust over bloat. Automation over headcount. Shipping over meetings.*

---

</div>

## The problem

The software industry has a weight problem. Screenshot tools ship as 200MB Electron apps. Invoicing needs a cloud subscription. Simple utilities demand frameworks, runtimes, and telemetry you never asked for.

We think that's broken. So we build differently.

---

## What we've built

<div align="center">

| | Metric | |
|---|--------|---|
| **69,600+** | lines of production code | Rust + TypeScript + SQL |
| **816** | commits on main | in 13 days |
| **178** | releases shipped | continuous delivery |
| **400+** | pull requests merged | AI-authored, human-verified |
| **1** | engineer | augmented by autonomous AI agents |

</div>

---

## Projects

### Mission Control &mdash; AI Agent Orchestration Platform

The engine behind everything we ship. Not a copilot. A workforce.

One engineer dispatches autonomous AI agents that read issues, write code, create PRs, run CI, verify deployments, and merge &mdash; without human intervention. The system improves itself through its own pipeline.

**Key capabilities:**
- **Multi-agent orchestration** &mdash; Opus orchestrators dispatch Sonnet builders in parallel, working in isolated git worktrees
- **Self-healing pipelines** &mdash; crashed agents are detected, diagnosed, and recovered automatically
- **Sub-agent awareness** &mdash; watchdog tracks nested agent hierarchies, prevents false-positive kills
- **Deploy verification** &mdash; CI green is not enough; agents verify live behavior before closing issues
- **Real-time dashboard** &mdash; token burn rates, agent status, deployment tracking, KPIs

```
Backend:   Rust (Axum + SQLx) .......... 18,700 LOC across 164 files
Frontend:  SolidJS + TypeScript ........ 49,200 LOC across 175 files
Database:  PostgreSQL 17 ............... 58 migrations
CI/CD:     Gitea Actions, self-hosted runner, Docker
Agents:    Claude Opus (orchestrator) + Claude Sonnet (builders)
```

> Mission Control is private. What you see in our public repos is the output: code written, tested, and deployed by autonomous agents coordinated through this platform.

---

### XDR Snip &mdash; Screenshot Tool for Windows

<table>
<tr>
<td width="120" align="center">
<br>
<a href="https://github.com/Cynerg-IA/xdr-snip">
<img src="https://img.shields.io/badge/XDR_Snip-000?style=for-the-badge&logo=rust&logoColor=white" />
</a>
</td>
<td>

**[XDR Snip](https://github.com/Cynerg-IA/xdr-snip)** &mdash; Freeze your screen, select a region, get a small WebP. That's it.

- **~3MB** single executable. No installer. No runtime. No Electron.
- **Pure Rust.** Zero garbage collection, zero framework overhead.
- **HDR-aware.** Captures what you actually see, not a washed-out approximation.
- **Visual QA pipeline.** Screenshots feed directly into AI agents for autonomous UI validation.

</td>
</tr>
</table>

---

### Meridian &mdash; Business OS *(in development)*

Desktop-first invoicing and accounting for French micro-entrepreneurs. Tauri + Rust + SolidJS + PostgreSQL. Offline-first, NF 525 compliant, designed to replace cloud SaaS with a self-hosted alternative that costs nothing to run.

---

## How we build

<div align="center">

| Principle | In practice |
|-----------|-------------|
| **AI-native development** | Humans architect. AI agents write, test, deploy, and verify. Full autonomy from issue to merge. |
| **Small footprint** | Rust, SolidJS (8KB runtime), Tauri. No Electron. No React. Every dependency justified. |
| **Ship continuously** | 178 releases in 13 days. CI/CD pipelines that build, test, and deploy in minutes. |
| **Verify everything** | Agents verify live deployments, not just CI status. Playwright + visual QA. "It compiles" is not "it works." |
| **Self-hosted first** | Gitea, PostgreSQL, Docker, self-hosted CI runners. Data stays where it belongs. |
| **Security by default** | OWASP Top 10 baseline. Zero trust. Parameterized SQL only. Defense in depth. |

</div>

---

## The Cynerg-IA Way

Our operating philosophy is codified in **10 strategic playbooks** covering decisions, architecture, security, quality, project management, business structure, infrastructure, risk, AI operations, and financial discipline &mdash; plus **6 cross-cutting principles** and **50+ deep-dive articles**.

Every agent we spawn, every PR we merge, every system we deploy follows these principles. They're not aspirational. They're enforced by CI gates, hooks, and automated verification.

<div align="center">

`X1` Earned Trust &middot; `X2` Project Hierarchy &middot; `X3` Systems Over Discipline &middot; `X4` Assumption Is Not Knowledge &middot; `X5` Output Is Not Outcome &middot; `X6` Verification Is Not Optional

</div>

---

<div align="center">

<img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" /> <img src="https://img.shields.io/badge/SolidJS-2c4f7c?style=flat-square&logo=solid&logoColor=white" /> <img src="https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white" /> <img src="https://img.shields.io/badge/Tauri-FFC131?style=flat-square&logo=tauri&logoColor=black" /> <img src="https://img.shields.io/badge/Claude-191919?style=flat-square&logo=anthropic&logoColor=white" /> <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" /> <img src="https://img.shields.io/badge/Gitea-609926?style=flat-square&logo=gitea&logoColor=white" />

**France** &middot; [cynerg-ia.com](https://cynerg-ia.com)

</div>
