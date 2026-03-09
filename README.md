# Google Fonts Central Hub

Central coordination repository for [Google Fonts](https://fonts.google.com/) work by [@felipesanches](https://github.com/felipesanches).

## What is this?

This repo serves as a starting point and coordination hub for AI-assisted contributions to the Google Fonts ecosystem. It contains:

- **CLAUDE.md** — Instructions and strict policies that govern how the AI agent (Claude Code) operates on behalf of @felipesanches across all related repositories
- **AGENTS.md** — Workflow documentation for the [beads](https://github.com/jwalsh/beads) issue tracking system used for task coordination
- **.beads/** — Local issue tracker data (exported as JSONL) for planning and tracking work

## Related Repositories

| Repository | Description |
|------------|-------------|
| [google/fonts](https://github.com/google/fonts) | Main Google Fonts repo (font binaries, metadata) |
| [fonttools/fontspector](https://github.com/fonttools/fontspector) | Rust-based font QA tool (fontbakery port) |
| [googlefonts/gftools](https://github.com/googlefonts/gftools) | Google Fonts CLI toolkit (build, fix, validate fonts) |
| [felipesanches/gfonts_agents](https://github.com/felipesanches/gfonts_agents) | Dashboard & investigation reports for GF source metadata |

## How it works

All work sessions start here. The AI agent reads `CLAUDE.md` for policies and constraints, checks the beads tracker for available work, and coordinates across the related repositories. Every public-facing post made by the agent includes a disclaimer noting it was AI-generated without human review.

Key policies enforced (see `CLAUDE.md` for full details):

- AI-generated content disclaimer on all public posts
- PRs never submitted without explicit human approval
- PRs never merged by the agent (human maintainers only)
- No force-pushing — additional commits for PR follow-ups
- Build and tests must pass before any PR submission
- HTTPS URL upgrades verified before committing
- All code, comments, and docs in English

## Transparency

This repository is intentionally public to provide full transparency into how AI-assisted contributions are coordinated. The policies, issue tracker, and agent instructions are all visible for review by maintainers and the community.
