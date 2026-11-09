# Product Labs

围绕具体 AI 产品与工具持续整理的公开研究记录。一个研究对象一个目录，共用同一套结构。

本仓只存**研究过程**。研究成品（可对外的结论、可浏览的资料）升格为子站，并登记在 [chenjin.io](https://chenjin.io) 的项目注册表里。

## 研究对象

| 目录 | 对象 | 当前记录 |
|---|---|---|
| [labs/corespeed/](labs/corespeed/README.md) | [CoreSpeed](https://corespeed.io/) | 1 条实测：Similarweb 抓取工具对照 |
| [labs/ego-lite/](labs/ego-lite/README.md) | Ego Lite 浏览器 / `ego-browser` | 1 条：安装版本指南与初步观察 |
| [labs/model-launch/](labs/model-launch/README.md) | AI 模型发布与传播 | 1 份研究框架，尚无事件研究 |

三者均为独立维护，与所研究产品的官方无隶属关系。

## 共同结构

每个对象目录下固定四个子目录：

| 目录 | 内容 |
|---|---|
| `research/` | 产品、市场、增长与使用场景调研 |
| `monitoring/` | 更新与持续观察 |
| `experiments/` | 实测步骤、结果、费用与限制 |
| `resources/` | 可追溯的资料与来源 |

## 记录规则

- 每条记录注明日期与依据。
- 区分**厂商说法**、**实际观察**与**待验证问题**三类陈述，不混写。
- 公开仓库不收录私人交流、凭据或未获授权的内部资料。

## 升格路径

当一个对象积累到结论站得住、且外部读者能用时：

1. 建独立子站（先例：`claude-fable5.chenjin.io`）。
2. 在 chenjin.io 的 `src/content/projects.ts` 注册一条，`kind` 记为独立子页。
3. 本仓保留研究过程，不重复搬运成品。

## 合并记录

2026-11-09 由 `corespeed-lab`、`ego-lite-lab`、`model-launch-lab` 三个独立仓库合并而来。内容逐文件保留，来源提交见 [MIGRATION-2026-11-09.md](MIGRATION-2026-11-09.md)。
