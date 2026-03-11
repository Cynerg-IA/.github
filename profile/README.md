<div align="center">

# Cynerg-IA

**One engineer. AI-augmented. Building lean software that does more with less.**

*Rust over bloat. Automation over headcount. Shipping over meetings.*

---

</div>

## The problem

The software industry has a weight problem. Screenshot tools ship as 200MB Electron apps. Note-taking needs a cloud subscription. Simple utilities demand frameworks, runtimes, and telemetry you never asked for.

We think that's broken.

---

## Layer 1 &mdash; XDR Snip

<table>
<tr>
<td width="120" align="center">
<br>
<a href="https://github.com/Cynerg-IA/xdr-snip">
<img src="https://img.shields.io/badge/XDR_Snip-000?style=for-the-badge&logo=rust&logoColor=white" />
</a>
</td>
<td>

**[XDR Snip](https://github.com/Cynerg-IA/xdr-snip)** &mdash; Screenshot tool for Windows 11. Freeze your screen, select a region, get a small JPEG. That's it.

- **~3MB** single executable. No installer. No runtime. No Electron.
- **Pure Rust.** Zero garbage collection, zero framework overhead.
- **HDR-aware.** Captures what you actually see, not a washed-out approximation.
- **Self-debugging.** Screenshots feed directly into AI prompts for visual QA &mdash; the tool tests itself.

Every screenshot tool on the market ships bloated, phones home, or both. XDR Snip does one thing, does it well, and weighs nothing.

</td>
</tr>
</table>

> XDR Snip is the first layer: proof that a useful desktop tool can be built in pure Rust, weigh almost nothing, and ship fast with AI-assisted development. It also serves as our visual QA pipeline &mdash; screenshots captured by the tool feed directly into Claude for autonomous UI validation. Since we implemented this loop, zero visual bugs have shipped.

---

## Layer 2 &mdash; Mission Control

<div align="center">

<br>

```
  One engineer. Multiple AI agents. Full autonomy.
```

<br>

</div>

**Mission Control** is our internal operations platform &mdash; and the real engine behind everything we ship. It's where AI stops being a copilot and becomes the workforce.

<div align="center">

| Metric | Number |
|--------|--------|
| **Commits on main** | 1,000+ |
| **Issues resolved** | 390+ |
| **Pull requests merged** | 400+ |
| **Time to build** | 11 days |
| **Engineers** | 1 |

</div>

### What it does

- **Autonomous agent orchestration.** Spawn AI agents that read issues, write code, create PRs, run CI, and merge &mdash; without human intervention.
- **Multi-agent coordination.** Opus orchestrators dispatch Sonnet builders in parallel. Agents work in isolated worktrees. No conflicts. No merge hell.
- **Self-healing pipelines.** Crashed agent? The system detects it, diagnoses the failure, and spawns a recovery agent. Automatically.
- **Real-time operations dashboard.** Token burn rates, deployment tracking, agent status, CI health &mdash; all in one place.
- **Built with its own tools.** Mission Control deploys itself through its own agent pipeline. The system improves the system.

### The stack

```
Backend:   Rust + Axum + SQLx + PostgreSQL 17
Frontend:  SolidJS + TypeScript + Vite
Daemon:    Rust service managing Claude Code agent lifecycles
CI/CD:     Gitea Actions, self-hosted runner, Docker deployment
Agents:    Claude Opus (orchestrator) + Claude Sonnet (builders)
```

> Mission Control is private. What you see here is the output: repositories built, tested, and deployed by autonomous agents coordinated through a platform that one person built in under two weeks.

---

## How we build

| Principle | Practice |
|-----------|----------|
| **Small footprint** | Rust, SolidJS (8KB runtime), Tauri. No Electron. No React. |
| **AI-native** | Humans architect decisions. AI writes, tests, and deploys. Agents manage the full cycle. |
| **Zero bloat** | Every dependency is justified. Every binary is measured. |
| **Ship daily** | CI/CD pipelines that deploy in minutes. No sprint ceremonies. No Jira. |
| **Verify everything** | Autonomous QA via Playwright + visual screenshot validation. CI green is not enough. |

<div align="center">

---

<img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" /> <img src="https://img.shields.io/badge/SolidJS-2c4f7c?style=flat-square&logo=solid&logoColor=white" /> <img src="https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white" /> <img src="https://img.shields.io/badge/Tauri-FFC131?style=flat-square&logo=tauri&logoColor=black" /> <img src="https://img.shields.io/badge/Claude-191919?style=flat-square&logo=anthropic&logoColor=white" />

**France** &middot; [cynerg-ia.com](https://cynerg-ia.com)

</div>
