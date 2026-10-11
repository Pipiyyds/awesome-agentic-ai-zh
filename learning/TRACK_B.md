# Track B — Agent Builder

沿原主干：Stage 3 → 4 → 5 → 6 → 7 → 7.5 → 8。用已做的 Track A 周报任务贯穿：v2 手写 Loop，v3 Graph，v4 RAG，最后加 Eval/Trace/恢复。不要求先学完完整计算机专业知识，但必须能读、改和解释当前代码。

| 节点 | 计划工时 | 原教材 |
| --- | ---: | --- |
| Track B / Stage 3 | 12 h | [打开原章](../stages/03-tool-use-and-hello-agent.zh-Hans.md) |
| Track B / Stage 4 | 12 h | [打开原章](../stages/04-agent-frameworks.zh-Hans.md) |
| Track B / Stage 5 Builder 补读 | 6 h | [打开原章](../stages/05-claude-code-ecosystem.zh-Hans.md) |
| Track B / Stage 6 | 18 h | [打开原章](../stages/06-memory-rag.zh-Hans.md) |
| Track B / Stage 7 | 12 h | [打开原章](../stages/07-multi-agent-production.zh-Hans.md) |
| Track B / Stage 7.5 与 Stage 8 | 6 h | [打开原章](../stages/07.5-advanced-agentic-concepts.zh-Hans.md) |
| Track B / Capstone | 18 h | [打开原章](../CAPSTONE.zh-Hans.md) |

## 原练习与个人任务映射

- Stage 3 练习 1/2/3/4/5/6 → B3-01/02/03-04/05/06/07；B3-08 综合。
- Stage 4 练习 1/2/3/4/5 → B4-02/03/04-05/06/07；B4-01 选择，B4-08 综合。
- Stage 5 → B5-01 至 B5-04，复测基础，只补 Builder 的工具服务与组合能力。
- Stage 6 练习 1/2/3/4/5 → B6-02/03/04/06/08；其余为诊断、拒绝、评测和综合。
- Stage 7 四个核心 → B7-01 至 B7-08，拆成评测、记录、停止、批准、恢复、本地服务和回归。
- Stage 7.5 → B8-01；Stage 8 练习 2/3/4 → B8-02/03/04。
- 原 Track B Capstone → BC-01 至 BC-12，保持原 rubric，再加个人周报验收。

## 概念先用白话

| 概念 | 是什么、解决什么 |
| --- | --- |
| Function Calling | 模型提出要用哪个工具和什么参数，由程序校验并执行；模型说要调用不等于真的调用成功。 |
| Agent Loop | 做一步、看结果、再决定下一步的循环；必须能停止，失败不能无限重试。 |
| Workflow Graph | 预先画好的工作节点与分支图，规定条件、状态和下一步；框架是实现它的工具。 |
| RAG | 先找与问题有关的资料，再让模型依据它回答；拿到资料仍需核对是否支持结论。 |
| Memory | 跨任务保存允许保存的重要信息；不是把所有对话塞进上下文，需能更新和删除。 |
| Eval | 用固定案例和评分规则测效果，比较修改前后是否真的变好。 |
| Trace | 一次运行中各步骤与工具结果的记录，帮助定位哪个环节出错。 |
| Harness | 包住模型与循环的运行环境，实施权限、工具、记录、检查和停止。 |

## 框架选择

先手写最小 Loop；Stage 4 用同任务比较两个框架，只深入一个主选。根据你的实际语言、运行环境、任务状态和可用账户选择，不在本次假定哪个 SDK 已安装可运行。多 Agent 是有证据后再增加的选项。

## 可迁移的最后验收

你能独立换一个工具或一种数据输入，解释循环/图/检索的变化，并修好一个故意加入的小故障。最终保留案例 10 例至少 8 例满足质量要求，安全阻断全过。该阈值是个人教学目标；没有实际执行前所有项都保持未完成。
