# Hi, I'm Adrian 👋

[![English](https://img.shields.io/badge/Lang-English-2b7489?style=flat-square)](README.md)&nbsp;[![中文](https://img.shields.io/badge/语言-简体中文-d54a35?style=flat-square)](README-zh.md)

I build practical AI agent tooling — multi-agent systems, personal AI workflows, and the context layer that ties them together. What I care about most is reliability: getting agents to produce work you can actually trust and verify.

## Public work

- **[challenge-plans](https://github.com/hiadrianchen/challenge-plans)** — a multi-agent tool that adversarially reviews a plan or spec *before* you execute it, surfacing weak assumptions, missing evidence, and handoff risks. Runs locally on the coding CLIs you're already logged into (Claude Code, Codex) with no API keys. It's where a lot of my thinking about reliable multi-agent systems turned into something you can actually run.

## What I'm into

- **Multi-agent systems that don't fool themselves** — cross-family verification, evidence over headcount, guarding against false consensus and premature hand-off.
- **Personal AI operating systems** — turning notes, tasks, content, and long-running work into files, queues, and memory that survive beyond one chat.
- **Durable agent context** — versioned memory and shared-context patterns that let agents resume work without re-discovering the basics.
- **Knowledge ingestion** — pipelines that turn scattered inputs (articles, videos, repos, notes) into something searchable and reusable.

Some experiments stay private because they depend on personal context. I pull pieces out into public tools when they're general enough to stand on their own — challenge-plans was the first.

## How I work

I care about the parts that decide whether an agent system is usable twice: a clear source of truth, recoverable long-running tasks, privacy boundaries, and human review gates. My rough split:

- scripts handle extraction, cleaning, and validation;
- agents handle judgment, synthesis, and recovery;
- humans keep the final call.

## Links

- GitHub: [@hiadrianchen](https://github.com/hiadrianchen)
- Open to issues, sharp reviews, and small collaborations around challenge-plans.
