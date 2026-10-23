# Changelog

All notable changes to this standalone edition of andrej-karpathy-skills are documented in this file.

## v1.1.0 — Standalone enhancements (2026-10-20)

- Converted the repository from a fork into a standalone edition with its own history, keeping full upstream credit.
- Added an "About This Standalone Edition" section to `README.md` with the upstream link, base-version provenance, and credit.
- Added `ENHANCEMENTS.md` documenting everything changed in this edition.
- Added `.github/dependabot.yml` for weekly GitHub Actions dependency updates.
- Added markdown linting automation (`.markdownlint.json` and the Markdown check workflow); the check was later scoped via `.markdownlint-cli2.yaml` so it covers this edition's own documentation instead of failing on upstream content.
- Added `.editorconfig` with standard editor settings (UTF-8, LF, 2-space indent).

## v1.0.0 — Upstream baseline (2026-10-20)

- Clean standalone baseline of [multica-ai/andrej-karpathy-skills](https://github.com/multica-ai/andrej-karpathy-skills) at upstream commit `2c606141936f1eeef17fa3043a72095b4765b9c2` (upstream HEAD dated 2026-04-20).
- Fork history severed; all files preserved as-is. No standalone licence file exists in the upstream tree (MIT is declared in the README License section and plugin metadata only).
