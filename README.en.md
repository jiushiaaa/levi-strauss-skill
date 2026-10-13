<h1 align="center">levi-strauss.skill</h1>

<p align="center">列维-斯特劳斯 · Claude Lévi-Strauss</p>

[中文](README.md) · **English**

<blockquote>
<p align="center">“The barbarian is, first of all, the person who believes in barbarism.”<br>— Claude Lévi-Strauss · <a href="https://ecg-humanite.fr/humanite/textes/levi-strauss-race-histoire">Race and History</a></p>
</blockquote>

[![MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Agent Skills](https://img.shields.io/badge/Agent_Skills-Standard-blue.svg)](https://agentskills.io/) [![Made with nvwa-skill](https://img.shields.io/badge/Made_with-nvwa--skill-orange.svg)](https://github.com/alchaincyf/nuwa-skill)

**A thinking skill for structural relations, cultural comparison, and recombination: compare how narratives organize relations and question the measures and standpoints used to rank cultures.**

---

## Examples

Illustrative applications written for this README; these are not quotations from the philosopher or transcripts of a live run.

### 1. Two myths both feature a snake. Do they mean the same thing?

> Compare what the snake opposes or transforms and how variants alter those relations. A shared object does not establish shared meaning, and structural similarity alone does not demonstrate historical transmission.

### 2. Does slower technological change make an entire society inferior?

> Specify the measure and standpoint, then examine other forms of accumulated activity. A real difference on one measure need not be denied, but it does not by itself rank an entire people.

## What is distilled

| Method | What it helps examine |
|---|---|
| Relational comparison | Compare relations and variants rather than matching isolated symbols. |
| Available materials | Trace inherited uses, constraints, and recombinations. |
| Measures and standpoints | Distinguish specific differences from unsupported rankings of entire cultures. |

These are selected, source-grounded methods, not a claim to cover the complete works. See [SKILL.md](SKILL.md) and [extraction notes](EXTRACTION.md) for scope and reasoning.

## Installation

This skill follows the open [Agent Skills](https://agentskills.io/) standard and can run in any skills-compatible AI agent runtime, including Claude Code, Codex, Cursor, OpenClaw, Hermes Agent, CodeBuddy, Workbuddy, Gemini CLI, OpenCode, and the broader ecosystem of 50+ runtimes.

### 1. One command

```bash
npx skills add jiushiaaa/levi-strauss-skill
```

The [Skills CLI](https://github.com/vercel-labs/skills) can detect supported agents. To select one, append `-a codex`, `-a claude-code`, or `-a cursor`; append `-g` for a global installation. Runtime support describes the standard and installer ecosystem, not a claim that we tested every runtime.

### 2. Manual installation

Clone this repository, then copy the complete folder into your runtime's skill directory, preserving `SKILL.md` and its relative reference paths. Name the installed folder `levi-strauss-perspective` to match its metadata. Common locations include `~/.agents/skills/` (Codex), `~/.claude/skills/` (Claude Code), and `~/.cursor/skills/` (Cursor); consult your runtime's current documentation.

```bash
git clone https://github.com/jiushiaaa/levi-strauss-skill.git
```

### 3. Use as reference

If automatic skill loading is unavailable, provide `SKILL.md` together with the referenced files needed for your question. Research notes remain in their source languages; README and usage guides are bilingual.

## Usage

- **Neutral analysis (default):** “Use Claude Lévi-Strauss’s ideas to analyze this question. Distinguish source claims from contemporary applications.”
- **Persona expression (optional):** explicitly request “persona expression mode.” It is an acknowledged simulation, not a statement by the philosopher.

Fiction work uses the ideas while leaving narrative voice to the writing task. See the bilingual [usage guide](USAGE.md).

## Research sources

The Structural Study of Myth; selections from chapter I of The Savage Mind, Race and History, and Tristes Tropiques.

- [Source catalogue and reading ranges](source-catalog.md)
- [Method extraction and evidence](EXTRACTION.md)
- Opening quotation: <a href="https://ecg-humanite.fr/humanite/textes/levi-strauss-race-histoire">Race and History</a>, 1952, chapter 3. English wording is translated where the source is not English; Chinese quotations are repository translations.

## Repository structure

Main files:

```text
├── SKILL.md  # Skill entry point and analysis methods
├── README.md / README.en.md  # Chinese and English introduction
├── USAGE.md  # Bilingual usage guide
├── EXTRACTION.md  # Method extraction and evidence
├── references/  # Research notes and optional expression mode
└── LICENSE  # MIT license
```

## Built with

Built with [nvwa-skill](https://github.com/alchaincyf/nuwa-skill).

Original project material is [MIT licensed](LICENSE); quoted works and translations retain their separate rights. See [source notices](ATTRIBUTION.md).

## More skills

Explore more thinkers and writers in the [Philosophy Skills collection](https://github.com/jiushiaaa/Philosophy-Skills).
