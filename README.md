# Toolbox

收集我觉得有用的工具、提示词、工作流和可复用的 skills。 — Jiang Wu

## 收藏目录

| 名称 | 用途 | 收录方式 |
| --- | --- | --- |
| [ICLR · Search Self-Play 配图提示词](prompts/iclr-search-self-play.md) | 搜索自博弈、验证门控和共享策略更新 | 原始长截图与文字版 |
| [Writing Science · Joshua Schimel](tools/writing-science.md) | 科研写作参考书 | PDF 原文件与来源说明 |
| [paper2anything](tools/paper2anything.md) | 把论文转成 slides、海报、项目主页和传播材料 | 上游项目收藏 |
| [开发提效小 tips · LofiSu](tools/lofi-development-tips.md) | 开发工具、AI / Prompt 工作流、UI 组件和求职资源 | Markdown 原文快照与主题索引 |
| [论文写作模板 · 彭思达](tools/peng-sida-research-notes.md) | 论文写作流程、各章节模板、图表与投稿前自审 | 原文入口与来源说明 |
| [Learning Research · 彭思达](tools/learning-research.md) | 科研入门、选题与实验、论文写作和学术报告 | 上游仓库快照 |
| [Research-Paper-Writing-Skills · Master-cai](skills/Research-Paper-Writing-Skills/README_zh.md) | 论文结构、段落衔接、章节写作和投稿前自审 | 完整上游仓库快照，含 skill、说明与许可证 |
| [AAAI 分层技能挖掘配图提示词](prompts/aaai-skill-mining.md) | 参考图驱动的手绘学术流程图 | 原始截图与文字版 |
| [ICML 多模块框架图提示词](prompts/icml-system-diagram.md) | 多模块论文系统示意图的构图与视觉要求 | 原始长截图与文字版 |
| [ICLR · EventBridge-RL 配图提示词](prompts/iclr-eventbridge-rl.md) | 不确定性门控与双时间尺度想象 | 原始长截图与文字版 |
| [NeurIPS · SCOPE 配图提示词](prompts/neurips-scope.md) | 预算感知的多模态推理与世界模型想象 | 原始长截图与文字版 |

## Tools

- [Writing Science · Joshua Schimel](tools/writing-science.md) · [PDF 原文件](resources/books/Writing_Science.pdf)
- [paper2anything](tools/paper2anything.md) · [上游仓库](https://github.com/QuZhan51496/paper2anything) · [中文说明](https://github.com/QuZhan51496/paper2anything/blob/main/README.zh-CN.md)
- [开发提效小 tips · LofiSu](tools/lofi-development-tips.md) · [Markdown 原文副本](tools/lofi-development-tips.original.md) · [上游原文](https://github.com/LofiSu/LofiSu/blob/main/%E5%BC%80%E5%8F%91%E6%8F%90%E6%95%88%E5%B0%8Ftips.md)
- [论文写作模板 · 彭思达](tools/peng-sida-research-notes.md) · [Notion 原文](https://pengsida.notion.site/c1a22465a0fa4b15a12985223916048e)
- [Learning Research · 彭思达](tools/learning-research.md) · [完整仓库快照](resources/pengsida-learning-research/README.md) · [上游仓库](https://github.com/pengsida/learning_research)

每个工具单独记一页：它解决什么问题、什么时候值得用，以及原始链接。收藏与实际使用经验会分别记录。

## Prompts

[论文配图提示词目录](prompts/README.md)：保存原始截图和可复制的提示词，方便以后制作论文示意图时查找。

- [ICLR · Search Self-Play 配图](prompts/iclr-search-self-play.md)
- [AAAI 分层技能挖掘配图](prompts/aaai-skill-mining.md)
- [ICML 多模块框架图](prompts/icml-system-diagram.md)
- [ICLR · EventBridge-RL 配图](prompts/iclr-eventbridge-rl.md)
- [NeurIPS · SCOPE 配图](prompts/neurips-scope.md)

## Skills

### Research-Paper-Writing-Skills · Master-cai

面向 ML / CV / NLP 论文写作，重点是清楚讲出论文故事、保持段落逻辑连贯，并让论断与实验依据对应。

- **项目**：[上游仓库](https://github.com/Master-cai/Research-Paper-Writing-Skills) · [中文说明](skills/Research-Paper-Writing-Skills/README_zh.md) · [MIT 许可证](skills/Research-Paper-Writing-Skills/LICENSE)
- **入口**：[SKILL.md](skills/Research-Paper-Writing-Skills/research-paper-writing/SKILL.md)
- **章节指南**：[Abstract](skills/Research-Paper-Writing-Skills/research-paper-writing/references/abstract.md) · [Introduction](skills/Research-Paper-Writing-Skills/research-paper-writing/references/introduction.md) · [Related Work](skills/Research-Paper-Writing-Skills/research-paper-writing/references/related-work.md) · [Method](skills/Research-Paper-Writing-Skills/research-paper-writing/references/method.md) · [Experiments](skills/Research-Paper-Writing-Skills/research-paper-writing/references/experiments.md) · [Conclusion](skills/Research-Paper-Writing-Skills/research-paper-writing/references/conclusion.md)
- **投稿前自审**：[Paper Review](skills/Research-Paper-Writing-Skills/research-paper-writing/references/paper-review.md)
- **写作示例**：[Example Bank](skills/Research-Paper-Writing-Skills/research-paper-writing/references/examples/index.md)
- **知识来源**：据上游说明，主要来自彭思达老师的[公开学习笔记](https://pengsida.notion.site/c1a22465a0fa4b15a12985223916048e)与[原始仓库](https://github.com/pengsida/learning_research)，由 Master-cai 整理、结构化适配并封装为 Skills。
- **使用与来源**：[Skills 说明](skills/README.md)

## 继续添加

- 新工具：复制 [条目模板](tools/_template.md)，放到 `tools/`，再加入上方目录。
- 新 skill：把完整技能目录或上游仓库快照放到 `skills/<name>/`，保留 `SKILL.md`、引用文件、来源说明与许可证，再加入目录。
- 新提示词：文字条目放到 `prompts/`，参考截图放到 `assets/prompts/`，保留来源信息。
- 用过之后：在对应条目补充自己的使用场景和体验。

外部项目保留原始链接、作者和许可证信息；本仓库中的示例或引用资料保留其原有归属。
