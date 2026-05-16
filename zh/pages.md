# Reading Index - Chinese

Source PDF: `The modern biblia.pdf`
Generated Markdown: `The modern biblia.md`
Observed page count: 92
Text extraction quality: Clean extraction observed

Use this index to jump from a question to the generated Markdown line ranges.
Line numbers refer to the generated Markdown file in this same folder.

## Topic Shortcuts

| Topic | PDF pages | Markdown page sections |
| --- | ---: | --- |
| Modern AI workflow | 1-12 | 1-12 |
| Subagents and delegation | 13-23 | 13-23 |
| SDD and support structure | 24-35 | 24-35 |
| GitHub, AGENTS.md, and prompt files | 36-49 | 36-49 |
| Prompt and harness engineering | 50-78 | 50-78 |
| Volume 06: complete repository scaffolding | 79-92 | 79-92 |
| Verification and closure | 67-78, 91-92 | 67-78, 91-92 |

## Page Map

| PDF page | Markdown lines | Page cue |
| ---: | ---: | --- |
| 1 | 18-31 | 现代人工智能 |
| 2 | 32-52 | 总目录 |
| 3 | 53-60 | 卷 01 |
| 4 | 61-95 | 核心理念 |
| 5 | 96-146 | 意图: |
| 6 | 147-169 | 没有这个最小单元，模型会用假设补洞。有时它会猜对；在真实系统里，它也会因为遵循看似合理但不属于项目的逻 |
| 7 | 170-202 | 目标: |
| 8 | 203-263 | 工件 |
| 9 | 264-297 | 2. Typecheck、lint 和 build。 |
| 10 | 298-329 | 1. 初版 AGENTS.md 。 |
| 11 | 330-375 | 常见反模式 |
| 12 | 376-385 | 结语 |
| 13 | 386-393 | 卷 02 |
| 14 | 394-430 | 本卷用途 |
| 15 | 431-468 | Explorer 与 worker |
| 16 | 469-503 | 通用规则很简单：explorer 用于降低不确定性，worker 用于执行已理解任务。 |
| 17 | 504-539 | 文件 ownership |
| 18 | 540-574 | 执行并行 |
| 19 | 575-608 | 3. ownership 模糊 |
| 20 | 609-642 | 边界清晰的实现任务 |
| 21 | 643-678 | 测试映射 |
| 22 | 679-715 | 没有超出 scope 的改动。 |
| 23 | 716-732 | 你必须重新解读他们返回的全部内容； |
| 24 | 733-740 | 卷 03 |
| 25 | 741-777 | SDD（Specification-Driven Development）是一种工作方式：规范不是装饰性文档，也不是孤立笔记，而是开发流程 |
| 26 | 778-821 | 推荐目录 |
| 27 | 822-859 | 期望内容： |
| 28 | 860-897 | 背景； |
| 29 | 898-935 | 坏 task 会写“把 feature 做完”；好 task 会写“在 endpoint Y 增加字段 X 的校验，并用集成测试覆盖”。 |
| 30 | 936-969 | 出现了哪些缺陷； |
| 31 | 970-1001 | 7. 评估 |
| 32 | 1002-1031 | ADR |
| 33 | 1032-1063 | Runbook |
| 34 | 1064-1098 | 反模式 |
| 35 | 1099-1119 | 仓库可在不依赖口头记忆的情况下重建上下文。 |
| 36 | 1120-1129 | 卷 04 |
| 37 | 1130-1181 | 为什么需要这一卷 |
| 38 | 1182-1231 | 推荐结构 |
| 39 | 1232-1251 | 并非所有项目从第一天起都需要全部内容。但应先建立这套心智架构。MVP 可以先从 AGENTS.md 、 |
| 40 | 1252-1288 | # AGENTS.md |
| 41 | 1289-1318 | 可按以下方式理解： |
| 42 | 1319-1347 | --- |
| 43 | 1348-1386 | --- |
| 44 | 1387-1423 | --- |
| 45 | 1424-1457 | 2. 目标。 |
| 46 | 1458-1500 | name: Safe PR Reviewer |
| 47 | 1501-1536 | 3. 使用哪些权限。 |
| 48 | 1537-1583 | 常见错误 |
| 49 | 1584-1595 | 注：在 2026-05-08 校验这些来源时，Copilot 的 prompt files 仍被标注为 public preview，因此在企业内将其设为刚 |
| 50 | 1596-1604 | 卷 05 |
| 51 | 1605-1642 | 一个有用实验与一个可靠系统之间的差别，不只是写出一个好 prompt。孤立的 prompt 可以解决单点任务，但严肃 |
| 52 | 1643-1670 | 示例： |
| 53 | 1671-1702 | 固定返回： |
| 54 | 1703-1739 | 干净输入； |
| 55 | 1740-1771 | { |
| 56 | 1772-1812 | 可能的目录结构 |
| 57 | 1813-1852 | Evals 与 rubrics：超越“我觉得不错” |
| 58 | 1853-1889 | Regression tests：别把原本可用的能力弄坏 |
| 59 | 1890-1923 | 输入输出校验； |
| 60 | 1924-1962 | policy 决策； |
| 61 | 1963-2000 | 伪代码 |
| 62 | 2001-2036 | 3. 不看回归就不要宣布成功。 |
| 63 | 2037-2059 | 发布变更前运行 regression tests； |
| 64 | 2060-2102 | 实践规则 |
| 65 | 2103-2145 | Golden tests：固定预期行为 |
| 66 | 2146-2196 | 报告； |
| 67 | 2197-2241 | init.sh 作为健康合同 |
| 68 | 2242-2281 | 如果团队主要在 Windows 上工作，可以提供等价的 `init.ps1` 或 `node scripts/init.mjs`。重点是必须有一个记录在案、可重复、退出码清楚的收尾 |
| 69 | 2282-2329 | Hooks 和 workflows 作为 guardrails |
| 70 | 2330-2370 | Harness-SDD Checklist |
| 71 | 2371-2415 | 1 = 部分满足 |
| 72 | 2416-2455 | 人工：适合质量、清晰度、说服力、实用性和对齐度的细微判断。 |
| 73 | 2456-2493 | 基本原则 |
| 74 | 2494-2537 | 日期和时间； |
| 75 | 2538-2585 | 1. 加载 persistent instructions |
| 76 | 2586-2625 | 运行 harness； |
| 77 | 2626-2662 | 如果这些答案分散在各处，系统仍然过度依赖人的记忆。 |
| 78 | 2663-2676 | 设计简单且可重复的 rubric。 |
| 79 | 2677-2686 | VOLUME 06 |
| 80 | 2687-2737 | 本卷用一个完整案例收尾。这个示例的截止日期是 2026-05-15。它不是为了展示装饰性 mockup，而是一个功能性 scaffolding：人可以复制、调整，并把它作为带 AI |
| 81 | 2738-2791 | traces/ |
| 82 | 2792-2843 | "eval": "node harness/run-eval.mjs", |
| 83 | 2844-2895 | npm test \|\| exit 1 |
| 84 | 2896-2950 | .toSorted((a, b) => b.updated_at.localeCompare(a.updated_at)) |
| 85 | 2951-2997 | console.error(error.message); |
| 86 | 2998-3049 | scripts/validate-sdd.mjs |
| 87 | 3050-3094 | ## Non-goals |
| 88 | 3095-3144 | SDD: spec |
| 89 | 3145-3198 | \| R2 \| T2, T4 \| `recent respects --limit` \| `npm test` \| |
| 90 | 3199-3252 | --- |
| 91 | 3253-3303 | on: |
| 92 | 3304-3310 | 如果一个人能够打开 repo、阅读规则、理解合同、执行验证，并在不依赖一段已经丢失的对话的情况下继续工作，那么系统就已经开始成熟。 |

## Volume 06

Volume 06 is present on pages 79-92 and contains the complete `agentic-notes` scaffolding: repository tree, README, package scripts, AGENTS.md, init.sh, CLI/store code, tests, SDD validation, harness fixtures/evals, reusable prompts, GitHub Actions, progress files, and final closure guidance.
