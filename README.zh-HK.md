# AI 編排精選項目

<a href="https://awesome.re"><img src="assets/badges/awesome-badge-official-flat2.svg" alt="Awesome" height="24" align="middle"></a>&ensp;<a href="https://awesome.re"><img src="assets/badges/awesome-badge-flat.svg" alt="Awesome (flat)" height="24" align="middle"></a>

[English](README.en.md) | [简体中文](README.zh-CN.md) | **繁體中文**

精選用於協調 AI 智能體、委派任務及執行智能體工作流程的平台、框架與工作流程引擎。

## 智能體協調與執行平台

透過共用工作空間及通訊渠道，協調智能體執行、任務委派或智能體團隊的平台。

- [Buzz](https://github.com/block/buzz) - 面向人類與 AI 智能體的工作空間，其 ACP 執行層負責分發頻道事件、管理智能體程序池，並重新啟動崩潰的智能體程序。
- [Multica](https://github.com/multica-ai/multica) - 可自行託管的工作空間，用於分配及協調程式編寫智能體，支援由領隊帶領的團隊、任務移交、執行記錄及人工審核。
- [Omnigent](https://github.com/omnigent-ai/omnigent) - 面向程式編寫智能體及自訂智能體的編排層，支援混合執行環境、主管智能體委派、共用工作階段及策略控制。
- [JiuwenSwarm](https://github.com/openJiuwen-ai/jiuwenswarm) - 多智能體系統，支援由領隊主導的任務分解、相依關係管理、團隊並行執行及多階段 SwarmFlow 工作流程。

## 智能體框架

用於以程式碼建構 AI 編排的框架，涵蓋智能體委派、團隊協調及可組合的工作流程控制。

- [Agno](https://github.com/agno-agi/agno) - Python 框架，用於協調智能體團隊，並將智能體、團隊及函式組合為支援共用狀態與人工審批的工作流程。
- [Pydantic AI](https://github.com/pydantic/pydantic-ai) - 具備型別支援的 Python 智能體框架，支援透過工具委派任務、以程式碼移交控制權、圖式控制流程及持久化工作流程執行。
- [PraisonAI](https://github.com/MervinPraison/PraisonAI) - 用於建構多智能體工作流程的框架，支援任務移交、路由、並行執行、迴圈，以及 Python 或 YAML 設定。

## 持久化工作流程引擎

持久化儲存 AI 工作流程狀態的引擎，用於協調智能體步驟、工具呼叫及審批，並支援故障復原。

- [Conductor](https://github.com/conductor-oss/conductor) - 面向 AI 智能體的持久化工作流程引擎，將大型語言模型任務及 MCP 工具呼叫與分支、並行執行、人工審批及重試結合。
