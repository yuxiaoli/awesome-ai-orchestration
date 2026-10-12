# AI 编排精选项目

<a href="https://awesome.re"><img src="assets/badges/awesome-badge-official-flat2.svg" alt="Awesome" height="24" align="middle"></a>&ensp;<a href="https://awesome.re"><img src="assets/badges/awesome-badge-flat.svg" alt="Awesome (flat)" height="24" align="middle"></a>

[English](README.en.md) | **简体中文** | [繁體中文](README.zh-HK.md)

精选用于协调 AI 智能体、委派任务和执行智能体工作流的平台、框架及工作流引擎。

## 智能体协调与运行平台

通过共享工作空间和通信渠道，协调智能体运行、任务委派或智能体团队的平台。

- [Buzz](https://github.com/block/buzz) - 面向人类与 AI 智能体的工作空间，其 ACP 运行层负责分发频道事件、管理智能体进程池，并重启崩溃的智能体进程。
- [Multica](https://github.com/multica-ai/multica) - 可自行托管的工作空间，用于分配和协调编程智能体，支持由领队带领的团队、任务移交、执行日志及人工审核。
- [Omnigent](https://github.com/omnigent-ai/omnigent) - 面向编程智能体和自定义智能体的编排层，支持混合运行环境、主管智能体委派、共享会话和策略控制。
- [JiuwenSwarm](https://github.com/openJiuwen-ai/jiuwenswarm) - 多智能体系统，支持由领队主导的任务分解、依赖管理、团队并行执行和多阶段 SwarmFlow 工作流。

## 智能体框架

用于以代码构建 AI 编排的框架，涵盖智能体委派、团队协调和可组合的工作流控制。

- [Agno](https://github.com/agno-agi/agno) - Python 框架，用于协调智能体团队，并将智能体、团队和函数组合为支持共享状态与人工审批的工作流。
- [Pydantic AI](https://github.com/pydantic/pydantic-ai) - 具备类型支持的 Python 智能体框架，支持通过工具委派任务、以代码移交控制权、图式控制流和持久化工作流执行。
- [PraisonAI](https://github.com/MervinPraison/PraisonAI) - 用于构建多智能体工作流的框架，支持任务移交、路由、并行执行、循环，以及 Python 或 YAML 配置。

## 持久化工作流引擎

持久化保存 AI 工作流状态的引擎，用于协调智能体步骤、工具调用和审批，并支持故障恢复。

- [Conductor](https://github.com/conductor-oss/conductor) - 面向 AI 智能体的持久化工作流引擎，将大语言模型任务和 MCP 工具调用与分支、并行执行、人工审批及重试相结合。
