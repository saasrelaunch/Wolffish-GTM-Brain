# Adapters, one door per tool

The brain is the truth. Everything here is a pointer of about twenty lines that says where to look
and when. **No adapter carries strategy, a claim or a status.** The moment one does, it starts
drifting, and a stale guardrail is worse than none because it still carries authority.

One deliberate exception: `portable-control-layer.md`, which carries content because a chat model
cannot follow a pointer. It is dated in its own header and regenerated whenever a ledger changes.

## Install

Each file below is copied into the repository or configuration where that tool reads. Every one of
them assumes the brain is checked out at `~/gtm/Wolffish-GTM-Brain`. If it lives somewhere else,
change that path in the copy you install, not here.

| Tool | File here | Install as |
|---|---|---|
| Claude Code, Claude apps | `../CLAUDE.md` | Already in place at the repository root |
| Codex, Zed, Jules, opencode | `AGENTS.block.md` | Merge into `AGENTS.md` in the consuming repository |
| Cursor | `cursor.mdc` | `.cursor/rules/wolffish-gtm.mdc` |
| Windsurf | `windsurf.md` | `.windsurf/rules/wolffish-gtm.md` |
| GitHub Copilot | `copilot-instructions.md` | `.github/copilot-instructions.md` |
| Gemini | `GEMINI.md` | Repository root of the consuming project |
| Any chat model, no file access | `portable-control-layer.md` | Pasted into the system prompt or the first message |

Files ending `.block.md` merge into a file the project already has. Keep the markers:

```
<!-- gtm-brain:begin -->
<!-- gtm-brain:end -->
```

Replace what sits between them on an update, append the block when the markers are absent, and
never edit inside them by hand.

## Why this folder exists at all

The founder writes in one tool, an engineer edits product strings in another, an agency works in a
third, and the landing page gets rewritten one evening in a chat window with no file access. If the
guardrails load in only one of those, the other three ship copy the brain would have refused. The
person on the tool nobody wired up is not being careless. They were never given the rules.

## Keeping them honest

The tool list is assumed rather than confirmed, which is an open item in `../ops/decisions.md`.
Confirm it, delete the adapters nobody runs, and record the answer. An adapter for a tool nobody
uses goes stale unnoticed, which is the same failure in a different direction.

Adapters are checked on the ledger cycle in `../ops/review-cadence.md`, and every one of them is
listed in `../ops/asset-index.md` with where it is installed and who runs that tool.
