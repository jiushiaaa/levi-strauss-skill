<h1 align="center">levi-strauss.skill</h1>

<p align="center">列维-斯特劳斯 · Claude Lévi-Strauss</p>

**中文** · [English](README.en.md)

<blockquote>
<p align="center">“野蛮人，首先是相信野蛮之分的人。”<br>— 列维-斯特劳斯 · <a href="https://ecg-humanite.fr/humanite/textes/levi-strauss-race-histoire">《种族与历史》</a></p>
</blockquote>

[![MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Agent Skills](https://img.shields.io/badge/Agent_Skills-Standard-blue.svg)](https://agentskills.io/) [![Made with nvwa-skill](https://img.shields.io/badge/Made_with-nvwa--skill-orange.svg)](https://github.com/alchaincyf/nuwa-skill)

**将结构关系、文化比较与有限材料的组合整理为思想分析 Skill，让 AI 比较故事如何组织关系，并反问评价文化时所用的尺度与观察位置。**

---

## 效果示例

以下为说明用法而编写的示例，展示分析思路；不是哲学家原话或实测对话记录。

### 1. 两个神话都有蛇，是否说明它们表达同一个意思？

> 先看蛇在各自叙事中与谁对立、促成什么转换，以及不同版本怎样改变这些关系。相同物件不足以证明同义；结构相似也不能单独证明历史传播。

### 2. 一个社会技术发展慢，是不是整体更落后？

> 先说明指标和观察位置，再比较该社会在其他活动中的积累。某项技术确实较少不必被否认，但不能不经论证就把局部差异扩成整个人群的等级。

## 蒸馏了什么

| 思想方法 | 能帮助分析什么 |
|---|---|
| 关系比较 | 比较行动关系与变体，而不只寻找相同符号。 |
| 有限材料 | 追踪既有材料的用途、约束与重新组合。 |
| 尺度与位置 | 区分局部指标差异和无依据的整体文化等级。 |

这些方法来自已定位的原作选段，不代表全集蒸馏。具体依据与适用范围见 [SKILL.md](SKILL.md) 和 [提炼说明](EXTRACTION.md)。

## 安装

本 skill 基于开放的 [Agent Skills](https://agentskills.io/) 协议，可在任何 skills-compatible 的 AI agent runtime 中运行（Claude Code、Codex、Cursor、OpenClaw、Hermes Agent、CodeBuddy、Workbuddy、Gemini CLI、OpenCode 等 50+ runtime）。

### 方式一：一行命令

```bash
npx skills add jiushiaaa/levi-strauss-skill
```

[Skills CLI](https://github.com/vercel-labs/skills) 可检测受支持的 agent；指定 runtime 时添加 `-a codex`、`-a claude-code` 或 `-a cursor`，全局安装添加 `-g`。这里说明协议与安装器的兼容生态，不代表本项目逐一实测了全部 runtime。

### 方式二：手动安装

克隆仓库后，将完整目录放入 runtime 的 skills 目录，保留 `SKILL.md` 及相对引用。安装目录命名为 `levi-strauss-perspective`，与入口元数据一致。常见路径为 Codex 的 `~/.agents/skills/`、Claude Code 的 `~/.claude/skills/`、Cursor 的 `~/.cursor/skills/`；以所用 runtime 当前文档为准。

```bash
git clone https://github.com/jiushiaaa/levi-strauss-skill.git
```

### 方式三：作为参考资料

不支持自动加载时，可把 `SKILL.md` 连同当前问题需要的引用文件交给 agent。README 与使用说明提供中英双语，研究底稿保留原语言。

## 使用方式

- **中性思想模式（默认）：**“用列维-斯特劳斯的思想分析这个问题，区分原作观点与当代应用。”
- **人物表达模式（可选）：**明确提出“开启人物表达模式”。这是注明性质的模拟，不是作者本人发言。

文游创作默认只取思想，文风另行决定。详见 [双语使用说明](USAGE.md)。

## 调研来源

〈神话的结构研究〉；《野性的思维》第一章选段；《种族与历史》及《忧郁的热带》选段。

- [原作来源、版本与实际阅读范围](source-catalog.md)
- [方法提炼与证据](EXTRACTION.md)
- 开篇名言出处：<a href="https://ecg-humanite.fr/humanite/textes/levi-strauss-race-histoire">《种族与历史》</a>，1952 年，第三章。中文引文为本仓库译文；非英语原作的英文引文亦为本仓库译文。

## 仓库结构

主要文件：

```text
├── SKILL.md  # Skill 入口与分析方法
├── README.md / README.en.md  # 中英文介绍
├── USAGE.md  # 双语使用说明
├── EXTRACTION.md  # 方法提炼与证据
├── references/  # 研究笔记与可选人物表达模式
└── LICENSE  # MIT 许可
```

## 构建工具

使用 [nvwa-skill](https://github.com/alchaincyf/nuwa-skill) 构建。

项目原创材料采用 [MIT](LICENSE)，所引原著与译本保留各自权利。详见 [来源说明](ATTRIBUTION.md)。

## 更多 Skill

更多人物 Skill 请查看 [Philosophy Skills 合集](https://github.com/jiushiaaa/Philosophy-Skills)。
