# 🐍 BlackMamba Studio

Local-first creative engineering stack for **BlackMamba RECORDS / Iyari Gomez**.

## Mission

Build a reusable system for music, visuals, prompts, automation, repos, and local AI workflows.

The goal is simple:

> Use cloud AI only when it matters. Use local tools, saved prompts, scripts, and GitHub memory for everything repeatable.

## Core Stack

```txt
ChatGPT Atlas      = premium strategist / images / browser agent
Local AI           = daily drafting engine
GitHub             = memory backbone
Scripts            = automation layer
Prompts            = reusable creative fuel
```

## Modules

- `memory/` — reusable identity, workflow, and project context
- `prompts/` — song, cover-art, repo-review, and automation prompts
- `scripts/` — local CLI tools and automation helpers
- `outputs/` — generated local artifacts, ignored by git
- `logs/` — local runtime logs, ignored by git

## Operating Rule

Nothing random. Everything becomes a system.

## Quick Start

```bash
brew install ollama
ollama pull llama3.2:3b
ollama pull qwen2.5-coder:7b

mkdir -p ~/blackmamba-studio
cd ~/blackmamba-studio
```

Clone this repo:

```bash
git clone https://github.com/Blackmvmba88/Studio.git
cd Studio
```

Run the local command after installing the script:

```bash
./scripts/bm ask "what should I build next?"
```

## Philosophy

- Save reusable context.
- Convert repeated actions into commands.
- Keep personal/private data out of the public repo.
- Use local AI for drafts, lyrics, prompts, README files, and repo summaries.
- Use premium AI for hard reasoning, strategy, images, and browser automation.
