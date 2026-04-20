# Kael — blueprint

Public snapshot of the Kael AI-assistant architecture running on Miro's Mac mini. Shared here for Miro's family (specifically his father, who's exploring whether to set up a similar system) and anyone else curious about how a personal Claude Code agent can be wired end-to-end.

**This repo is documentation only.** No code, no tokens, no automation runs here. The actual Kael lives in a private vault; this repo mirrors only the design docs.

## Contents

| File | What it is | Read if you… |
|------|------------|---------------|
| [`architecture-diagram-sk.html`](./architecture-diagram-sk.html) | Single-page visual diagram (Slovak labels) — the big picture | …want to understand the shape of the system in one glance |
| [`BLUEPRINT.md`](./BLUEPRINT.md) | Step-by-step setup guide for replicating the system on a new Mac | …want to actually build your own Kael |
| [`ARCHITECTURE.md`](./ARCHITECTURE.md) | Detailed reference: every component, every flow, every failure mode | …need depth on how specific pieces work or interact |

## Rendering the diagram

`architecture-diagram-sk.html` is a standalone HTML file — you can open it directly in a browser. For a quick online view without cloning, use the GitHub raw viewer via one of these proxies:

- **Pretty:** `https://htmlpreview.github.io/?https://github.com/MaoTanx/kael-blueprint/blob/main/architecture-diagram-sk.html`
- **Alternative:** `https://raw.githack.com/MaoTanx/kael-blueprint/main/architecture-diagram-sk.html`

Or — if GitHub Pages is enabled for the repo — open: `https://maotanx.github.io/kael-blueprint/architecture-diagram-sk.html`

## Language

The diagram is in Slovak (the reader is Miro's Slovak-speaking father). The two Markdown docs are in English, since that's what Claude Code works in and most of the tooling references are English-native. If you need a Slovak version of one of the markdown docs, ping Miro.

## What's intentionally NOT here

- The actual `~/KaelVault/` (contains personal notes, project history, people, music — stays private)
- Any secrets / API keys / OAuth tokens
- The `music-taste-profile` / `dota-spectate` / other project repos
- The session transcripts or memory files

If you're Miro's dad and want access to anything above, ask him directly.

## Versioning

This repo is a periodic snapshot. When the architecture changes materially, Miro regenerates the diagram + markdown docs and commits here. Git history tells you what changed when.

## License

The documentation here is for personal educational use — no explicit license. If you want to build your own Kael from it, go ahead; if you want to fork/redistribute publicly, ask Miro first.
