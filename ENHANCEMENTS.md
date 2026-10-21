# Enhancements — Standalone Edition Changelog

Upstream: <https://github.com/anthropics/skills>
Maintainer of this edition: Syed Mujtaba Abbas (@mujtbabbas)

## Repository name

- Prepared as **skills-anthropics**, because the standalone name `skills`
  is already taken by the mattpocock/skills standalone edition. Final
  repository name is pending the owner's decision. The upstream link
  (<https://github.com/anthropics/skills>) is unchanged.

## v1.1.0 — Enhancement release (2026-10-20)

- Added "About This Standalone Edition" section to README.md with upstream
  link, base version provenance, the skills-anthropics name note, and credit.

- Added this changelog (ENHANCEMENTS.md).
- Added .github/dependabot.yml (weekly GitHub Actions updates, plus pip
  updates for skills/slack-gif-creator/requirements.txt and
  skills/mcp-builder/scripts/requirements.txt).

- Added .markdownlint.json and .github/workflows/markdown-check.yml
  (markdown linting automation for the skill documentation; upstream ships
  no GitHub Actions workflows, so this is the repo's first workflow).

- Added .editorconfig (standard editor settings: UTF-8, LF, 2-space indent).
- Licence position recorded, NOT changed: there is no root licence file.
  Each skill ships its own LICENSE.txt — most are Apache License 2.0, but
  skills/docx, skills/pdf, skills/pptx and skills/xlsx carry Anthropic's
  source-available terms ("© 2025 Anthropic, PBC", use governed by the
  user's agreement with Anthropic, with additional restrictions including
  limits on reproduction/retention), as upstream's README itself states.
  FLAG: DO NOT PUBLISH without the owner's explicit licence decision,
  especially for those four document skills.

## v1.0.0 — Baseline (2026-10-20)

- Clean standalone baseline of anthropics/skills at upstream commit
  dbd4588f9e1033efb41dad4bef2f7947c8993d44 (upstream HEAD dated 2026-10-09).

- Fork history severed; all 445 files — including 54 canvas-design font
  files (.ttf), the theme-factory PDF and all per-skill LICENSE.txt
  files — preserved as-is.
