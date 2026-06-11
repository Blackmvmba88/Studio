# 🗺️ BlackMamba Studio Roadmap

## Phase 0 — First Brick

Goal: create the repo backbone.

- [x] README
- [x] Roadmap
- [ ] Memory files
- [ ] Prompt files
- [ ] Local `bm` CLI
- [ ] Install instructions

## Phase 1 — Local AI Core

Goal: run daily creative/code tasks locally.

- Install Ollama
- Pull base models:
  - `llama3.2:3b` for fast drafts
  - `qwen2.5-coder:7b` for code/repo work
- Add script wrapper for model selection
- Add local context loading from `memory/*.md`

## Phase 2 — Creative Pipeline

Goal: make music/visual workflows repeatable.

- Song lyric prompt
- Cover-art prompt
- Metadata prompt
- Pinterest caption prompt
- DistroKid checklist
- SoundCloud upload checklist

## Phase 3 — Repo Brain

Goal: make engineering projects easier to continue.

- Repo analyzer command
- README generator
- Next-commits planner
- Risk scanner
- Test command suggester

## Phase 4 — Automation Layer

Goal: reduce manual repetition.

- File watchers
- Batch prompt generation
- Pinterest queue helper
- Metadata CSV generator
- Local SQLite memory

## Phase 5 — Studio OS

Goal: turn this into a true local operating layer.

- `bm ingest`
- `bm ask`
- `bm song`
- `bm cover`
- `bm repo`
- `bm distro`
- `bm pinterest`

## Golden Rule

Build small. Commit often. Automate what repeats.
