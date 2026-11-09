# 合并记录 2026-11-09

## 决定

三个研究对象仓库合并为 `product-labs`，每个对象一个目录，共用同一套 `research / monitoring / experiments / resources` 结构。

动机：三个仓由同一动作（研究一个产品）产生，生命周期一致，且共用同一套脚手架。按「一研究对象一仓库」的做法，第四个产品会再长出第四个仓库。

## 来源映射

| 原仓库 | 已审查提交 | 目标位置 | 保留内容 |
|---|---|---|---|
| `ChenJinCloud/corespeed-lab` | `026b36ac9aeed1fe07cf609db98b3c4f72da8869` | `labs/corespeed/` | README、research/monitoring/experiments/resources 全部文件 |
| `ChenJinCloud/ego-lite-lab` | `51c28d03ed80fa7a6077070f5a37a2d4cd7cbde2` | `labs/ego-lite/` | 同上 |
| `ChenJinCloud/model-launch-lab` | `3801b1025a446d32244790d4bcce0c7e32eb6ab8` | `labs/model-launch/` | 同上，另含 LICENSE |

合并前 19 个文件，合并后 19 个文件，逐文件保留，无内容改写。各对象目录内原有的脚手架 README 保持原样（三份内容因产品名不同而互不相同，未做归一化）。

## 安全与删除门禁

原仓库只有在以下全部成立后才可删除：

- 目标文件已提交并推送；
- 合并后文件数与原仓合计一致；
- 未引入凭据、私人记录、个人绝对路径或生成产物。

## 删除状态

已于 2026-11-09 完成。合并提交 `28667d6` 推送至 `main` 后，远端确认 21 个文件（19 个原内容 + README + 本记录），三个原仓库随即永久删除；后续 API 检查三个原路径均返回 `404 Not Found`。
