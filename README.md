<h1 align="center">Dzithendo Mathegu</h1>

<p align="center">
  <b>Software engineer in fintech · founder of <a href="https://z10-labs.github.io">z10 labs</a> · building TutorSpaces</b><br>
  <sub>Cape Town, South Africa</sub>
</p>

<p align="center">
  <a href="https://z10-labs.github.io"><img alt="z10 labs" src="https://img.shields.io/badge/z10_labs-research_→_products-C5FF3D?style=flat-square&labelColor=0E0F12"></a>
  <a href="https://github.com/z10-labs"><img alt="GitHub org" src="https://img.shields.io/badge/github-z10--labs-f2f3f5?style=flat-square&logo=github&labelColor=0E0F12"></a>
</p>

---

> **An AI agent starts every session with amnesia.**
> Git records what changed. The code records what is. Nothing records what was *rejected*, and why.
> I build the layer that fixes that, and I build real products on top of it to prove it holds.

## What I'm working on

**By day** I'm a software engineer at a fintech company, building scalable, reliable systems where correctness isn't optional: payments, event-driven services, and the domain models that keep money honest.

**[z10 labs](https://z10-labs.github.io)** is my lab for infrastructure that makes AI coding agents trustworthy on real teams: memory, review, and orchestration. Every idea starts as research, gets tested against a harness, and ships with its data, failed runs included.

**TutorSpaces** is the proving ground: a production platform for independent tutors (scheduling, sessions, invoicing, assessments), built as a Next.js 15 frontend over a NestJS modular monolith. It's developed with agents in the loop, including *Sfiso*, an autonomous QA agent that tests every change end to end. If a z10 idea doesn't survive TutorSpaces, it doesn't ship.

## The lab

| Track | Project | What it is |
|:--|:--|:--|
| 🧠 **Memory** | [**hippomem**](https://github.com/z10-labs/hippomem) | A team's engineering memory for coding agents: the decisions behind the software, and the options rejected. |
| | [hippocampus-research](https://github.com/z10-labs/hippocampus-research) · [validation](https://github.com/z10-labs/hippocampus-validation) | The evidence. 13-feature system built by agents with cold context; source-file reads fell from **13/21 → 0/21** using the decision index alone. |
| | [teach-ai](https://github.com/z10-labs/teach-ai) | Learner memory for tutoring: events and transcripts become an evidence-backed model of each student. |
| 🔍 **Review** | [**sentinel**](https://github.com/z10-labs/sentinel) | AI PR reviewer as a GitHub App: AWS Lambda + SQS + Claude. |
| | [iqiniso](https://github.com/z10-labs/iqiniso) | *"Truth"* in isiZulu: an AI walkthrough of every changed file before you approve. |
| | [watchman](https://github.com/z10-labs/watchman) | Strategic-alignment review: does this PR move the product where we decided it should go? |
| ⚙️ **Agent tooling** | [**whetstone**](https://github.com/z10-labs/whetstone) | An agentic dev environment: launch Claude agent runs, group them into sessions, capture everything as structured events. |
| | [helm](https://github.com/z10-labs/helm) | Reasoning-agent orchestrator: teams of agents that gate artifacts, spending effort in proportion to risk. |
| | [rami](https://github.com/z10-labs/rami) | A background second brain that tracks tasks, decisions and follow-ups across every Claude Code session. |
| | [deploy-monitor](https://github.com/z10-labs/deploy-monitor) · [plugins](https://github.com/z10-labs/plugins) | Verifies production deploys, traces failures to the PR, opens guarded fix PRs. Published in the z10 plugin marketplace. |
| | [revie](https://github.com/z10-labs/revie) | Portable HTML/CSS prototyping for agents: versioned ops, not snapshots. |

## How I build

- **Decisions are artifacts.** Written down, reviewed in PRs, and readable by the next human *or* agent.
- **Publish the evidence.** Claims ship with the harness, the logs and the sample size. n=1 is labelled n=1.
- **Spend effort in proportion to risk.** Agents gate their own output; humans approve what matters.
- **Boring architecture, sharp edges.** Modular monoliths, clear domain boundaries, money in integer cents.

## Toolbox

<p>
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white">
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">
  <img alt="Go" src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white">
  <img alt="Java" src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white">
  <img alt="Next.js" src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white">
  <img alt="NestJS" src="https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white">
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white">
  <img alt="AWS" src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white">
  <img alt="Vercel" src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white">
  <img alt="Electron" src="https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white">
  <img alt="Claude Agent SDK" src="https://img.shields.io/badge/Claude_Agent_SDK-D97757?style=flat-square&logo=anthropic&logoColor=white">
  <img alt="MCP" src="https://img.shields.io/badge/MCP-0E0F12?style=flat-square&logo=modelcontextprotocol&logoColor=white">
</p>

<sub>Background in computer science and electrical engineering at UCT. My course notes are public: <a href="https://github.com/Dzithendo31/software-engineering-notes-csc-3-uct">software engineering</a>, <a href="https://github.com/Dzithendo31/machine-learning-notes-csc-uct">machine learning</a>, <a href="https://github.com/Dzithendo31/cplus-plus-notes-csc-uct">C++</a>.</sub>

---

<p align="center">
  <sub>Met me at a conference? Start at <a href="https://z10-labs.github.io"><b>z10-labs.github.io</b></a>, then open an issue on anything that looks wrong. That's the fastest way to talk to me.</sub>
</p>
