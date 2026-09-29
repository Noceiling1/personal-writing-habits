# 个人写作习惯与研究偏好

> 一套面向论文阅读、学术写作、研究交流与汇报材料的个人偏好 skill。

[![Skill](https://img.shields.io/badge/Skill-personal--writing--habits-blue)](SKILL.md)

## 项目简介

这是西电研究生 **Noceiling1** 持续整理和维护的个人写作与研究交流规范。它将长期使用中形成的表达习惯、论文阅读方法、研究分析原则和汇报材料工作流沉淀为可复用的 Markdown 文档，供 AI 助手在相关任务中参考。

项目重点不是提供一套固定模板，而是明确以下问题：

- 如何根据任务选择合适的处理方式
- 如何让文字直接、清楚，并服务于真实观点
- 如何区分作者主张、实验支持、合理推断和未知信息
- 如何把论文方法、实验结果和研究价值讲清楚
- 如何根据交付物调整详略，而不是机械套用统一格式

## 适用场景

- 论文阅读、精读、方法解释与批判性分析
- 论文正文、摘要、相关工作、翻译与润色
- 审稿式修改与论文论证检查
- 研究笔记、组会笔记与批量汇报整理
- 课堂报告、幻灯片内容组织与演讲稿
- 概念解释、方法调研、研究方向分类与代表工作梳理

## 核心偏好

- **先明确任务和边界**：区分论文阅读、正式写作、报告汇报和研究分析，不把不同任务混在一起。
- **表达直接、简洁**：避免套话、迂回立论、实质性重复和不必要的术语堆砌。
- **重视论证关系**：每句话都应提供观点、证据、机制、差异或必要的过渡。
- **保持独立判断**：不为了迎合用户而放弃有依据的判断，也不为了显得批判而堆砌低收益意见。
- **严格匹配证据**：不把摘要中的主张自动写成已证实结论，不将推断或未知信息伪装成原文事实。
- **说明机制而非罗列模块**：解释输入、处理、输出、下游关系和设计理由，明确最终由谁作出决策。
- **区分阶段和条件**：分清训练与推理、离线与在线、仿真与真实环境，并说明收益、代价和适用范围。
- **用户要求优先**：用户指定的格式、范围、文件和交付物优先于默认偏好。

## 项目结构

```text
personal-writing-habits/
├── README.md                                  # 项目说明
├── SKILL.md                                   # 技能入口、任务路由与共同偏好
├── agents/
│   └── openai.yaml                            # 代理配置
└── references/
    ├── paper-reading.md                       # 论文阅读与精读方法
    ├── paper-writing.md                       # 论文写作、审阅、翻译与摘要
    ├── reports-and-notes.md                   # 研究笔记、课堂报告与演讲稿
    ├── research-explanations.md               # 概念解释、方法调研与边界判断
    └── group-meeting-notes/                   # 组会汇报与批量整理模块
        ├── workflow.md                        # 组会笔记工作流
        ├── style-guide.md                     # 组会材料风格与详略规则
        ├── note-templates.md                  # 组会笔记模板
        └── batch-workflow.md                  # 批量汇报整理流程
```

## 文档索引

| 任务 | 首选文档 |
| --- | --- |
| 选择任务模块、查看共同原则 | [`SKILL.md`](SKILL.md) |
| 快速了解、精读、方法解释、复现分析 | [`references/paper-reading.md`](references/paper-reading.md) |
| 论文正文、相关工作、翻译、润色、摘要、审稿式修改 | [`references/paper-writing.md`](references/paper-writing.md) |
| 研究笔记、课堂报告、幻灯片、演讲稿 | [`references/reports-and-notes.md`](references/reports-and-notes.md) |
| 概念解释、方法调研、方向分类、成熟度判断 | [`references/research-explanations.md`](references/research-explanations.md) |
| 单篇或多篇组会汇报笔记 | [`references/group-meeting-notes/workflow.md`](references/group-meeting-notes/workflow.md) |
| 组会材料的表达风格与详略 | [`references/group-meeting-notes/style-guide.md`](references/group-meeting-notes/style-guide.md) |
| 组会笔记模板 | [`references/group-meeting-notes/note-templates.md`](references/group-meeting-notes/note-templates.md) |
| 批量整理组会材料 | [`references/group-meeting-notes/batch-workflow.md`](references/group-meeting-notes/batch-workflow.md) |

## 使用方式

1. 先阅读 [`SKILL.md`](SKILL.md)，识别当前任务和对应模块。
2. 只加载本次任务相关的参考文档，避免将不同交付物的规则混用。
3. 用户的明确要求优先于默认偏好，已确定的结构直接沿用。
4. 输出前核对事实、数字、引用、图表、链接和文件覆盖范围。
5. 区分长期习惯与单次任务限制，不把某次报告的时长、选题或排除项固化为通用规则。

### 按交付物选择模块

- **最终交付是论文正文**：以 `paper-writing.md` 为主，使用专家写作尺度。
- **最终交付是论文阅读分析**：以 `paper-reading.md` 为主，重点检查主张、证据、机制和适用条件。
- **最终交付是组会笔记**：以 `group-meeting-notes/workflow.md` 为主，必要时读取其风格、模板和批量流程。
- **最终交付是课堂报告或演讲稿**：使用 `reports-and-notes.md`，根据实际幻灯片、页序和时长组织内容。
- **任务包含概念解释或方向调研**：补充 `research-explanations.md`，明确分类依据和证据边界。

## 维护原则

- 共同偏好集中维护在 [`SKILL.md`](SKILL.md)。
- 具体任务流程维护在 `references/` 下的对应文档中。
- 新增规则应与已有内容合并，避免重复或互相冲突。
- 只有明确属于长期习惯的内容才进入项目，不将一次性要求写成通用规则。
- 阅读规则中的批判性检查不直接照搬到正式论文正文中。

## 项目状态

- **主要维护者**：Noceiling1
- **项目性质**：西电研究生个人偏好 skill
- **维护状态**：持续更新中
- **项目地址**：<https://github.com/Noceiling1/personal-writing-habits>
