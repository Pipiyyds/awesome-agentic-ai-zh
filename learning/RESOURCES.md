# 按任务找资料

原地图是主要方针；下面是当前必要入口与候选辅助资料。链接已读取/打开不等于代码已验证可运行。每次进入实作才核查官方版本、设备、权限和具体安装命令。

| 对应节点 | 优先级 | 资源 | 只看什么 / 用途 | 核查范围 |
| --- | --- | --- | --- | --- |
| F0 | 必读 | [原地图基础与 setup](https://github.com/WenyuChiou/awesome-agentic-ai-zh/blob/83775cf3cdef26717a4e40d8928de57ae869b8d7/stages/00-foundations.zh-Hans.md) | Python/API/JSON/Git 最小项目 | 2026-10-08 已读取原章 |
| F0 | 辅助查阅 | [Python 官方中文教程](https://docs.python.org/zh-cn/3/tutorial/) | 先看控制流、函数、字典、JSON、异常和 venv；零编程基础用逐步示例进入 | 2026-10-08 已打开；官方提醒预期有编程概念 |
| F0 | 辅助查阅 | [Pro Git 中文](https://git-scm.com/book/zh/v2) | 先看起步、commit、diff、撤销，按当前任务查阅 | 2026-10-08 已打开 |
| F1/F2 | 必读 | [原地图 LLM/Prompt](https://github.com/WenyuChiou/awesome-agentic-ai-zh/blob/83775cf3cdef26717a4e40d8928de57ae869b8d7/stages/01-llm-basics.zh-Hans.md) | 模型调用、Token、Context，再用固定样例比较提示 | 2026-10-08 已读取；具体模型与费率运行前复核 |
| A1/A2 | 必读 | [原地图 CLI 入口与流程](https://github.com/WenyuChiou/awesome-agentic-ai-zh/blob/83775cf3cdef26717a4e40d8928de57ae869b8d7/tracks/cli/A1-cli-intro.zh-Hans.md) | CLI-1 至 CLI-8 与前置检查 | 2026-10-08 已读取 |
| A1/A5 | 备选官方 | [Claude Code 概览](https://code.claude.com/docs/en/overview) | 选该 CLI 时才看安装、运行和操作入口 | 2026-10-08 已打开；未安装/测试 |
| A5/B5 | 必读辅助 | [MCP 官方介绍](https://modelcontextprotocol.io/docs/getting-started/intro) | 理解 host/client/server/tool 和协议边界 | 2026-10-08 已打开，跳转当前版本 |
| B3-B7 | 补系统讲解 | [Datawhale Hello-Agents](https://github.com/datawhalechina/hello-agents) | 缺完整解释时按当前主题找章，不先整本刷完 | 2026-10-08 已打开仓库，未逐章通读 |
| B4/B8 | 概念辅助 | [Anthropic Building effective agents](https://www.anthropic.com/engineering/building-effective-agents) | 比较固定 workflow 与动态 Agent，以及何时增加复杂度 | 2026-10-08 已打开；文章有当前工具变化提示 |
| B4 | 主框架候选 | [LangGraph 官方概览](https://docs.langchain.com/oss/python/langgraph/overview) | 确需状态/分支/恢复时按该框架主线实作 | 2026-10-08 已打开；未安装/测试 |
| B4 | 框架对照候选 | [OpenAI Agents SDK 官方仓库](https://github.com/openai/openai-agents-python) | 以同任务比较工具、handoff 与 trace；不同时深入多套框架 | 2026-10-08 已打开；未安装/测试 |
| A3/B7 | 原章入口 | [受限工具、CI 与运行记录](https://github.com/WenyuChiou/awesome-agentic-ai-zh/blob/83775cf3cdef26717a4e40d8928de57ae869b8d7/tracks/cli/A3-cli-production.zh-Hans.md) | 具体 Action 版本、权限和计费在做 CLI-10 时核实 | 2026-10-08 已读取 |
| B6 | 必读 | [原地图 RAG 与 Memory](https://github.com/WenyuChiou/awesome-agentic-ai-zh/blob/83775cf3cdef26717a4e40d8928de57ae869b8d7/stages/06-memory-rag.zh-Hans.md) | Embedding、向量库、Chunking、完整 RAG、偏好记忆 | 2026-10-08 已读取 |
| B7 | 必读 | [原地图生产工程](https://github.com/WenyuChiou/awesome-agentic-ai-zh/blob/83775cf3cdef26717a4e40d8928de57ae869b8d7/stages/07-multi-agent-production.zh-Hans.md) | 开发集/保留集、Eval、Trace、停止、批准和恢复 | 2026-10-08 已读取 |
| A8/B8 | 必读 | [原地图 Agent 操作界面](https://github.com/WenyuChiou/awesome-agentic-ai-zh/blob/83775cf3cdef26717a4e40d8928de57ae869b8d7/stages/08-agent-interfaces.zh-Hans.md) | API/CLI/Browser/Computer Use 的选择与边界 | 2026-10-08 已读取 |
| AC/BC | 必读 | [原作者 Capstone rubric](https://github.com/WenyuChiou/awesome-agentic-ai-zh/blob/83775cf3cdef26717a4e40d8928de57ae869b8d7/CAPSTONE.zh-Hans.md) | 保留原评分，再加个人周报验收 | 2026-10-08 已读取 |

## 原仓库完整入口

- [简体资源清单](../RESOURCES.zh-Hans.md)
- [零基础设置](../resources/setup-guide.zh-Hans.md)
- [核心名词表](../resources/glossary.zh-Hans.md)
- [可运行例子](../examples/README.zh-Hans.md)
- [练习方法](../docs/HOW_TO_USE.md)

## 全部外链索引

RESOURCE_INDEX.json 从主线和资源页提取原始 URL，并保留出现文件。它是搜索索引，未对每条外链逐一 live 验证。你只需打开当前节点的 1-2 份补充，不必刷完整资源库。外链内容没有离线下载。

## 参与方与费用怎么判断

| 参与方 | 提供什么 | 谁付费 / 得到什么 | 当前选择原则 |
| --- | --- | --- | --- |
| 原教材维护者 | 路线、说明、示例、资源整理 | 原仓库 MIT 开放；付出维护时间 | 主线采用，保留出处 |
| 模型/API 服务商 | 推理与模型调用 | 用户可能按订阅或 usage 付费 | 看实际模型、usage 与当前官方费率 |
| CLI/框架/插件 | 任务宿主、组合工具、开发抽象 | 工具许可与模型费用分开，服务条款各异 | 一个主入口，不因目录推荐就默认安全/免费 |
| 数据/账户服务 | 资料、导出、认证、接口 | 可能有独立订阅或 API 权限 | 先确认能取到数据与允许范围 |
| 你 | 目标、材料、人工判断与验收 | 承担时间、费用与最终结果风险 | 把成本、日志、范围、停止证据放进成果 |
