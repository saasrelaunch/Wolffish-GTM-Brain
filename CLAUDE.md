# Wolffish Cloud GTM, agent entry point

This repository is the Wolffish Cloud go-to-market. You are an agent working inside it. Read this
file, then follow its pointers. Do not improvise strategy that is already settled here.

## Read before any customer-facing output
1. `context/Wolffish_GTM_Master_Context.md`, the full strategy, ICP, positioning, messaging,
   funnels and campaigns. Source of truth. Section 15 answers most single-fact lookups.
2. `rules/writing-rules.md`, how every word is written, including the bilingual rule.
3. `rules/do-not-say.md`, the claims that must never be made and their safe replacements.
4. `rules/feature-status.md`, shipped versus partial versus in build. Check before describing any
   capability, every time.
5. `rules/glossary.md`, the canonical vocabulary and the one distinction that must never blur.

## This is not a software funnel
Wolffish Cloud is four things at once: an agentic harness that runs on the employee's machine, a
platform control plane, a cloud service delivered by engineers, and a Saudi regulatory and
commercial fit. Anything written as though it were a self-serve product is wrong at the root.

Delivery capacity is four to six deployments in twelve months against about twenty named accounts.
Volume marketing is out of scope by arithmetic, not by preference.

**The two primary channels are Instantly for cold email and HeyReach for LinkedIn outreach**, and
together they carry about fifty-five percent of expected qualified pipeline. Supporting them:
events and physical presence, warm introduction and the sponsor network, founder organic writing in
Arabic and English, messaging apps after a reply, partner co-sell, the owned site and scorecard, and
public tender from year two. For any channel work load `reference/relationship-engine.md` first.

**Non-negotiable inside the two primary channels.** Sunday to Thursday sending, never Friday,
paused for Ramadan. No merge tag beyond first name and company, and every Arabic name
transliteration verified. Sending domains separate from the primary domain. **The Dream 100 is on a
permanent suppression list in both tools** and is opened only by introduction.

**Refused outright: paid social.** If asked, decline, give the one-sentence reason, and offer the
outbound sequences instead.

## Pick the audience first
Two audiences with separate value propositions. Never blended in one asset.
- **ICP 1**, Saudi-owned regulated enterprises of 200 to 600 knowledge workers, founder-led.
  `reference/value-proposition-icp1.md`.
- **ICP 2**, the larger regulated institutions reached through partners.
  `reference/value-proposition-icp2.md`.

## Non-negotiables
- **Kingdom of Saudi Arabia only.** Refuse to produce for the wider Gulf, Egypt or globally, and
  say why.
- **No proof point outside the closed set in `ops/copy-bank.md`.** There is no reference customer.
  Any logo, quote, metric, case study or customer count is fabrication.
- **Every capability carries its status flag in the same sentence.** Not in a footnote.
- **Landed cost on both sides, always.** Never quote the SAR 79 seat against a competitor seat
  price. That hides about a third of the cost.
- **Never position against HUMAIN.** Neutralise in one sentence, then move on.
- **Nothing unshipped is demonstrated.** No demo, recording or narrated walkthrough of anything
  flagged IN BUILD or ROADMAP.
- **The phrase "no new invoice" does not appear in writing.** The capability allowance is proposed
  and not contracted.
- **Residency and the absence of a data path are different claims.** Wolffish makes the second.

## Before you ship
Run `ops/QA-checklist.md` against the draft. Templates are in `templates/`, the approved voice
reference is in `examples/`, and filled prompts for recurring jobs are in `prompts/common-tasks.md`.

## When something changes
New input from a lead, customer, partner, competitor or regulator goes to `ops/signal-log.md`
first. If it changes a rule, follow the amendment procedure in order: the ledger in `rules/`, then
`context/`, then `ops/decisions.md`, then the copy, then `adapters/portable-control-layer.md`.
Never the other way around.

If this file and `AGENTS.md` ever disagree, this file wins.
