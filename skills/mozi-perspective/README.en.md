# Mozi · Upstream Skill

[中文](README.md) | [English](README.en.md)

Attributed upstream module from [nuwa-skills/mozi-skill](https://github.com/nuwa-skills/mozi-skill). Original authorship and [MIT license](LICENSE) are retained. See [SOURCE.json](SOURCE.json) for provenance.

## Installation

This skill follows the open [Agent Skills](https://agentskills.io/) standard and can run in any skills-compatible AI agent runtime, including Claude Code, Codex, Cursor, OpenClaw, Hermes Agent, CodeBuddy, Workbuddy, Gemini CLI, OpenCode, and the broader ecosystem of 50+ runtimes.

### 1. One command

```bash
npx skills add jiushiaaa/Philosophy-Skills --skill mozi-perspective
```

The [Skills CLI](https://github.com/vercel-labs/skills) can detect supported agents. To select one, append `-a codex`, `-a claude-code`, or `-a cursor`; append `-g` for a global installation. Runtime support describes the standard and installer ecosystem, not a claim that we tested every runtime.

### 2. Manual installation

Clone this repository, then copy the selected folder under `skills/` into your runtime's skill directory, preserving `SKILL.md` and its relative reference paths. Name the installed folder `mozi-perspective` to match its metadata. Common locations include `~/.agents/skills/` (Codex), `~/.claude/skills/` (Claude Code), and `~/.cursor/skills/` (Cursor); consult your runtime's current documentation.

```bash
git clone https://github.com/jiushiaaa/Philosophy-Skills.git
```

### 3. Use as reference

If automatic skill loading is unavailable, provide `SKILL.md` together with the referenced files needed for your question. Research notes remain in their source languages; README and usage guides are bilingual.

[Usage / 使用](USAGE.md) · [Upstream / 原始来源](https://github.com/nuwa-skills/mozi-skill) · [Provenance / 来源记录](SOURCE.json)

## More skills

Explore more thinkers and writers in the [Philosophy Skills collection](https://github.com/jiushiaaa/Philosophy-Skills).
