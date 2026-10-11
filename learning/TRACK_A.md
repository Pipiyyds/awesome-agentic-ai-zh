# Track A — CLI Power User

先完成 [共同基础](PROJECT.md)，再按原路径 A1 → A2 → Stage 5 → A3 → Stage 8。CLI 是命令行入口，学习的是把目标委派成可验证任务并检查、复用结果。只用聊天界面不等于已经通过 CLI 文件操作验收。

| 节点 | 计划工时 | 原教材 |
| --- | ---: | --- |
| Track A / A1 | 3 h | [打开原章](../tracks/cli/A1-cli-intro.zh-Hans.md) |
| Track A / A2 | 4.5 h | [打开原章](../tracks/cli/A2-cli-workflow.zh-Hans.md) |
| Track A / Stage 5 核心 | 6 h | [打开原章](../stages/05-claude-code-ecosystem.zh-Hans.md) |
| Track A / A3 | 6 h | [打开原章](../tracks/cli/A3-cli-production.zh-Hans.md) |
| Track A / Stage 8 | 1.5 h | [打开原章](../stages/08-agent-interfaces.zh-Hans.md) |
| Track A / Capstone | 3 h | [打开原章](../CAPSTONE.zh-Hans.md) |

## 原练习与个人任务映射

- CLI-1/2 → A1-01；CLI-3/4 → A1-02。
- CLI-5 → A2-01；CLI-6 → A2-02；CLI-7/8 → A2-03。
- Stage 5 核心 5.1-5.4 → A5-01 至 A5-04；5.5-5.8 仅按需要选读。
- CLI-9/10/11/12 → A3-01/02/03/04。
- Stage 8 练习 1 → A8-01；个人周报验收 → AC-01/02。

每个任务的动作、时间和验收在 [TASKS.md](TASKS.md)。学完一个节点用原章自我检查与个人变式共同验收。

## 实战成果 v1

准备 5-10 条公开或自备材料。给 Agent 目标、数据范围、输出结构、引用规则、停止条件。先读取和计划，再生成草稿；检查来源和事实；换一批材料复跑，保存 prompt、输出、diff 和运行收据。

如果某 CLI 或 CI 缺少设备/账户/权限，记录 blocked，继续不依赖它的任务，不把读文档记成实作通过。

## 关键概念白话

| 概念 | 白话与用途 |
| --- | --- |
| Project Instructions | 当前项目的规则牌，告诉 Agent 可做范围和检查方法；不自动赋予权限。 |
| Skill | 重复任务的操作卡，说明什么时候用、怎么做和怎样检查；格式依宿主不同。 |
| Tool | 实际干活的函数或接口，例如读文件、查数据；不等于 Agent 自身。 |
| MCP | 让宿主与工具/资料服务沟通的协议，像约定接口的转接方式；不自动提供服务账号权限。 |
| Plugin | 把能力组合成可安装的包；具体打包结构随产品不同。 |
| Observability | 一次任务留下的收据和路线记录，帮助定位错误；有记录不代表结论正确。 |
