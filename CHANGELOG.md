# Changelog

All notable changes to this standalone edition of skills-anthropics (Anthropic's skills collection) are documented in this file.

## v1.1.0 — Standalone enhancements (2026-10-20)

- Converted the repository from a fork into a standalone edition with its own history, keeping full upstream credit. This edition is named **skills-anthropics** because the standalone name `skills` is already taken by the mattpocock/skills standalone edition; the upstream link is unchanged.
- Added an "About This Standalone Edition" section to `README.md` with the upstream link, base-version provenance, the skills-anthropics name note, and credit.
- Added `ENHANCEMENTS.md` documenting everything changed in this edition.
- Added `.github/dependabot.yml` for weekly GitHub Actions updates, plus pip updates for `skills/slack-gif-creator/requirements.txt` and `skills/mcp-builder/scripts/requirements.txt`.
- Added markdown linting automation (`.markdownlint.json` and the Markdown check workflow — this repository's first workflow, since upstream ships no GitHub Actions workflows); the check was later scoped via `.markdownlint-cli2.yaml` so it covers this edition's own documentation instead of failing on upstream content.
- Added `.editorconfig` with standard editor settings (UTF-8, LF, 2-space indent).
- Licence position recorded, not changed: there is no root licence file. Each skill ships its own `LICENSE.txt` — most are Apache License 2.0, but `skills/docx`, `skills/pdf`, `skills/pptx` and `skills/xlsx` carry Anthropic's source-available terms, as upstream's README itself states.

## v1.0.0 — Upstream baseline (2026-10-20)

- Clean standalone baseline of [anthropics/skills](https://github.com/anthropics/skills) at upstream commit `dbd4588f9e1033efb41dad4bef2f7947c8993d44` (upstream HEAD dated 2026-10-09).
- Fork history severed; all 445 files — including 54 canvas-design font files (.ttf), the theme-factory PDF and all per-skill `LICENSE.txt` files — preserved as-is.
