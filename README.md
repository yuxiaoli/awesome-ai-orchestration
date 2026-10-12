# Awesome AI Orchestration

<a href="https://awesome.re"><img src="assets/badges/awesome-badge-official-flat2.svg" alt="Awesome" height="24" align="middle"></a>&ensp;<a href="https://awesome.re"><img src="assets/badges/awesome-badge-flat.svg" alt="Awesome (flat)" height="24" align="middle"></a>

**English** | [简体中文](README.zh-CN.md) | [繁體中文](README.zh-HK.md)

A curated collection of platforms, frameworks, and workflow engines for coordinating AI agents, delegating tasks, and executing agent workflows.

## Agent coordination and runtime platforms

Platforms that coordinate agent runtimes, task delegation, or agent teams through shared workspaces and communication channels.

- [Buzz](https://github.com/block/buzz) - Workspace for humans and AI agents with an ACP harness that dispatches channel events, manages an agent process pool, and restarts crashed agents.
- [Multica](https://github.com/multica-ai/multica) - Self-hostable workspace for assigning and coordinating coding agents, with leader-led squads, task handoffs, execution logs, and human review.
- [Omnigent](https://github.com/omnigent-ai/omnigent) - Orchestration layer for coding agents and custom agents, supporting mixed runtimes, supervisor delegation, shared sessions, and policy controls.
- [JiuwenSwarm](https://github.com/openJiuwen-ai/jiuwenswarm) - Multi-agent system with leader-led task decomposition, dependency management, parallel team execution, and multistage SwarmFlow workflows.

## Agent frameworks

Frameworks for building AI orchestration in code, including agent delegation, team coordination, and composable workflow control.

- [Agno](https://github.com/agno-agi/agno) - Python framework for coordinating agent teams and composing agents, teams, and functions into workflows with shared state and human approval.
- [Pydantic AI](https://github.com/pydantic/pydantic-ai) - Typed Python agent framework supporting tool-based delegation, programmatic handoffs, graph-based control flow, and durable workflow execution.
- [PraisonAI](https://github.com/MervinPraison/PraisonAI) - Agent framework for building multi-agent workflows with task handoffs, routing, parallel execution, loops, and Python or YAML configuration.

## Durable workflow engines

Engines that persist AI workflow state and coordinate agent steps, tool calls, approvals, and recovery across failures.

- [Conductor](https://github.com/conductor-oss/conductor) - Durable workflow engine for AI agents, combining LLM tasks and MCP tool calls with branching, parallel execution, human approvals, and retries.
