# Codex Brief — Phase 1

## Mission

Turn **BlackMamba Studio** into a usable local-first CLI system that supports creative, repo, and prompt workflows around ChatGPT Atlas, GitHub memory, and local AI tools.

## Context

This repo is the operating base for BlackMamba RECORDS / Iyari Gomez.

The stack is:

```txt
ChatGPT Atlas = command vision / internet eyes / high-leverage execution
Local AI      = offline helper / drafts / experiments / fallback engine
GitHub        = memory backbone
Scripts       = automation layer
Prompts       = reusable creative fuel
```

## Phase 1 Tasks

1. Improve `scripts/bm` so it behaves like a clean CLI.
2. Add clear install instructions for macOS with Homebrew and Ollama.
3. Add a `repo-review` workflow that can scan local repo files and summarize next commits.
4. Add safe defaults and helpful errors when dependencies are missing.
5. Keep all private data, secrets, generated media, logs, and large files out of git.
6. Update README usage examples.
7. Add basic validation commands.

## Acceptance Criteria

- `./scripts/bm help` works.
- `./scripts/bm ask "..."` gives a useful response when Ollama is installed.
- `./scripts/bm song "..."` drafts complete lyrics.
- `./scripts/bm prompt "..."` generates cover-art prompts.
- `./scripts/bm repo ./path` scans common source files and returns engineering notes.
- The repo remains public-safe.
- README explains setup and command usage.
- `.gitignore` protects generated files and secrets.

## Guardrails

- Do not commit API keys, tokens, credentials, personal private data, or generated media.
- Do not add heavyweight dependencies unless justified.
- Prefer Bash/Python standard library first.
- Keep commands simple and runnable on macOS.
- Every change should improve repeatability.

## Suggested PR Title

`Phase 1: harden local CLI and Codex-ready workflow`

## Suggested PR Summary

- Improved local CLI behavior
- Added installation and usage docs
- Added repo-review prompt
- Added public-safe ignore rules
- Prepared BlackMamba Studio for iterative Codex execution
