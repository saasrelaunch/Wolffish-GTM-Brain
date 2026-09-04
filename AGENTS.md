# Wolffish Cloud GTM, agent entry point

Cross-tool entry file. Codex, Cursor, Zed, opencode, Jules and most newer agents read `AGENTS.md`,
so this is the widest door into this brain. Identical in intent to `CLAUDE.md`. **If the two
differ, `CLAUDE.md` wins.**

Working in a tool that reads neither, or in a chat window with no file access? See `adapters/`.

## Start here
1. `context/Wolffish_GTM_Master_Context.md`, the full go-to-market. Source of truth.
2. `rules/writing-rules.md`, house writing rules and the bilingual rule.
3. `rules/do-not-say.md`, claim hygiene and the safe replacement for each ban.
4. `rules/feature-status.md`, shipped versus partial versus in build versus roadmap.
5. `rules/glossary.md`, canonical vocabulary.
6. `reference/relationship-engine.md`, load for any channel task. It is the channel engine.

## What is being sold
Four layers at once: an agentic harness on the employee's own machine, a platform control plane, a
cloud service delivered by engineers, and a Saudi regulatory and commercial fit. Not software with
a signup. Delivery capacity is four to six deployments a year against about twenty named accounts.

## Channel discipline
In: events and physical presence, warm introduction and the sponsor network, founder organic
writing in Arabic and English, messaging apps after an introduction, partner co-sell, the owned
site and scorecard, and public tender from year two.

Out, refused: automated outreach sequencing, volume cold email, paid social. Decline, say why in
one sentence, offer the in-scope alternative.

## Audiences, never blended
- **ICP 1**, Saudi-owned regulated enterprises of 200 to 600 knowledge workers, sold founder-led.
- **ICP 2**, larger regulated institutions, reached through partners.

Pick one before writing a word. The sentence that reassures a security officer alarms a finance
director, and the reverse.

## Non-negotiables
- Kingdom of Saudi Arabia only.
- No proof point outside the closed set in `ops/copy-bank.md`. There is no reference customer.
- Every capability carries its status flag in the same sentence.
- Landed cost on both sides. Never the SAR 79 seat against a competitor seat price.
- Never position against HUMAIN. Neutralise in one sentence.
- Nothing flagged IN BUILD or ROADMAP is demonstrated.
- The phrase "no new invoice" does not appear in writing.
- Data residency and the absence of a vendor-side data path are different claims. Only the second
  is ours.

## Before shipping
Run `ops/QA-checklist.md`. Templates in `templates/`, approved voice in `examples/`, filled prompts
in `prompts/common-tasks.md`.

## Compounding
New market input goes to `ops/signal-log.md`. Rule changes follow the amendment procedure in order:
ledger, master context, decision log, copy, then regenerate
`adapters/portable-control-layer.md`.
