# Reader's Guide — skills-anthropics (Anthropic's Agent Skills)

## What this project is

This is **Anthropic's official repository of Agent Skills for Claude**.
Skills are folders of instructions, scripts and resources that Claude loads
dynamically to get better at a specialised task in a repeatable way —
creating documents with your company's brand guidelines, analysing data with
your organisation's workflow, or automating a personal chore. This repo is
both a catalogue of production reference skills and the home of the format:
the `spec/` folder documents the Agent Skills standard, and `template/` is
the starting point for writing your own.

## How the content is organised

- `skills/` — **19 reference skills**, one folder each (every folder carries
  its `SKILL.md` plus any scripts/resources it needs):
  - **Documents & office:** `docx`, `pdf`, `pptx`, `xlsx`, `doc-coauthoring`.
  - **Design & creative:** `algorithmic-art`, `brand-guidelines`,
    `canvas-design`, `frontend-design`, `theme-factory`,
    `slack-gif-creator`.
  - **Building with Claude/agents:** `claude-api`, `mcp-builder`,
    `skill-creator`, `web-artifacts-builder`, `webapp-testing`.
  - **Workplace & guidance:** `academy-guide`, `discernment-nudge`,
    `internal-comms`.
- `spec/` — the Agent Skills specification: the format contract a skill
  folder must follow.
- `template/` — the official skill template to copy when authoring a new one.
- `.claude-plugin/` — plugin/marketplace packaging for installing the set
  into Claude Code.
- [`README.md`](README.md) — the overview: what skills are, links to the
  support articles and Anthropic's engineering write-up, and how the skills
  are installed and used.
- `THIRD_PARTY_NOTICES.md` — licensing notices for bundled third-party
  material (note the README's licence section: most skills are Apache-2.0,
  while the document skills — docx/pdf/pptx/xlsx — are source-available under
  Anthropic's terms).

## How to use it

1. Browse `skills/` for the task you want Claude to be good at and read its
   `SKILL.md` — that file is the skill.
2. Install skills via the `.claude-plugin` marketplace route described in the
   README (or copy a skill folder into your own setup).
3. Writing your own? Start from `template/`, follow `spec/`, and use the
   `skill-creator` skill to help you build it.

## About this standalone edition

This repository is a standalone edition of
[anthropics/skills](https://github.com/anthropics/skills), converted from a
fork into its own repository and enhanced in place (named skills-anthropics
because `skills` is used by the mattpocock/skills edition). See
[`ENHANCEMENTS.md`](ENHANCEMENTS.md) for what this edition adds and
[`CHANGELOG.md`](CHANGELOG.md) for its version history (v1.0.0 upstream
baseline, v1.1.0 enhancements). All original work belongs to Anthropic and
the upstream contributors.
