# Reader's Guide — andrej-karpathy-skills

## What this project is

A single set of **guidelines that make AI coding assistants behave better**,
distilled from Andrej Karpathy's observations on LLM coding pitfalls — models
making silent assumptions, overcomplicating code, and making orthogonal edits
they do not understand. The fix is four principles, shipped as ready-to-drop-in
instruction files:

1. **Think Before Coding** — state assumptions, surface tradeoffs, ask when
   confused.
2. **Simplicity First** — minimum code that solves the problem, nothing
   speculative.
3. **Surgical Changes** — touch only what you must; clean up only your own
   mess.
4. **Goal-Driven Execution** — work toward tests and verifiable success
   criteria.

## How the content is organised

- [`CLAUDE.md`](CLAUDE.md) — **the main deliverable**: the full guidelines in
  Claude Code format. Most readers only need this file.
- [`CURSOR.md`](CURSOR.md) — the same guidelines adapted for Cursor users.
- `skills/karpathy-guidelines/` — the guidelines packaged as a reusable skill.
- `.claude-plugin/` and `.cursor/` — plugin packaging metadata for the
  respective tools.
- [`EXAMPLES.md`](EXAMPLES.md) — worked examples showing the principles
  applied (and violated).
- [`README.md`](README.md) — the problem statements and the principles in
  detail; [`README.zh.md`](README.zh.md) is the Simplified Chinese edition.

## How to use it

1. Read the README's **The Problems** and **The Four Principles in Detail**
   sections to understand *why* each rule exists.
2. Copy `CLAUDE.md` into your own project (or follow the plugin/skill route
   via the packaged folders) so your assistant inherits the guidelines.
3. Skim `EXAMPLES.md` when a rule feels abstract — it shows the behaviour
   difference concretely.

## About this standalone edition

This repository is a standalone edition of
[multica-ai/andrej-karpathy-skills](https://github.com/multica-ai/andrej-karpathy-skills),
converted from a fork into its own repository and enhanced in place. See
[`ENHANCEMENTS.md`](ENHANCEMENTS.md) for what this edition adds and
[`CHANGELOG.md`](CHANGELOG.md) for its version history (v1.0.0 upstream
baseline, v1.1.0 enhancements). All original work belongs to the upstream
contributors; licence MIT as declared upstream.
