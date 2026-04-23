# Kael — blueprint

Public snapshot of a personal Claude Code AI-assistant architecture. Shared for anyone curious about how a self-hosted Claude Code agent can be wired end-to-end (memory, scheduling, voice, Discord, MCP, hooks, skills).

**This repo is documentation only.** No code, no tokens, no automation runs here. The actual system lives in a private vault; this repo mirrors only the design docs.

## Contents

| File | What it is | Read if you… |
|------|------------|---------------|
| [`BLUEPRINT.md`](./BLUEPRINT.md) | Step-by-step setup guide for replicating the system on a new Mac | …want to actually build your own |
| [`ARCHITECTURE.md`](./ARCHITECTURE.md) | Detailed reference: every component, every flow, every failure mode | …need depth on how specific pieces work or interact |

## What's intentionally NOT here

- The actual `~/KaelVault/` (contains personal notes, project history, and identifying information — stays private)
- Any secrets / API keys / OAuth tokens
- Hobby project repos or domain-specific pipelines
- Session transcripts or memory files

## Versioning

This repo is a periodic snapshot. When the architecture changes materially, the docs are regenerated from the private source of truth and pushed here. Git history tells you what changed when.

## License

The documentation here is for personal educational use — no explicit license. If you want to build your own agent from it, go ahead.
