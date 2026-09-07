# Use cases, what the founder actually does with this repository

Twelve jobs this brain does in daily operation. Each names the trigger, the files to load, the
output, and what it saves. They are ordered by how often they come up, not by importance.

Read this alongside [operating-rhythm.md](operating-rhythm.md), which sets when each one happens,
and [integration-map.md](integration-map.md), which sets where the output lands.

---

## 1. Write the weekly bilingual post

**Trigger.** Sunday, or whenever a regulatory instrument or a public cost fact appears.

**Load.** `templates/founder-post.md`, `reference/relationship-engine.md` for the archetype,
`reference/saudi-regulatory-file.md` or the claim ledger for the anchor fact,
`examples/founder-post-cloud-rules.md` for the voice.

**Output.** One post, Arabic headline and English subhead, 120 to 250 words, one archetype, ending
without a call to action six times out of eight.

**What it saves.** Twenty minutes instead of two hours. The archetype, the audience, the anchor and
the voice are all decided before the first sentence, so the work is the thinking rather than the
framing.

**Why it matters more than the time saved.** This channel is about fifteen percent of pipeline on
its own and it is what makes the other thirty percent, the warm introduction, possible at all. A
sponsor checks the founder's writing before agreeing to introduce.

---

## 2. Prepare a security call

**Trigger.** An introduction landed and a call is booked. This is the pivotal moment in the funnel.

**Load.** `templates/security-call.md`, `reference/saudi-regulatory-file.md` for the instruments
that govern that entity class, `rules/feature-status.md`, `reference/buying-committee.md`.

**Output.** The thirty-minute agenda, the architecture diagram brief to send two days ahead, the
two disqualifiers to say out loud, and the five questions this security team is most likely to ask
with the honest answer to each.

**What it saves.** A repeated call. A security call held without the security team in the room, or
held after the commercial conversation, gets re-run from the start, and the second run is slower
than the first would have been.

---

## 3. Answer an objection in writing

**Trigger.** A price objection, a two-person-company objection, a certification question, or a
comparison with the incumbent.

**Load.** `reference/objection-handling.md`, `examples/objection-response-price.md` for the
concede-first structure, `rules/do-not-say.md`.

**Output.** A written answer that concedes the true part in the first sentence, moves the
comparison rather than disputing an accurate number, and offers the competitor where the competitor
is genuinely the better fit.

**What it saves.** The credibility that gets spent by an answer which opens defensively. In a market
of about twenty accounts whose buyers talk to each other, that credibility is the scarcest asset the
company holds.

---

## 4. Produce the landed cost breakdown

**Trigger.** A finance director who was not in the room asks what it costs, or a proposal is due.

**Load.** `templates/landed-cost-email.md`, `reference/pricing-model.md`,
`examples/landed-cost-email.md`.

**Output.** All three lines, the pass-through named as customer-billed at zero margin, a separated
assumptions block the reader can move, the landed total, and the honest comparison.

**What it saves.** The single most expensive avoidable mistake in this go-to-market, which is
quoting the seat price alone. It understates spend by about a third, and the finance director who
finds that later discounts every other number the company has given them.

---

## 5. Ask for a warm introduction

**Trigger.** A named account on the twenty-account list has a credible sponsor.

**Load.** `templates/warm-introduction.md`, `examples/forwardable-paragraph.md`,
`reference/customer-journey.md` for the calendar constraints.

**Output.** Two documents. The private ask to the sponsor, with an explicit out. The forwardable
paragraph, under eighty words, no attachment and no tracked link.

**What it saves.** The introduction that never gets made because only the second half was written,
and the sponsor relationship that gets spent by a tracked link inside a personal favour.

---

## 6. Decide whether a signal changes anything

**Trigger.** A customer said something surprising. A competitor moved. A deal was lost.

**Load.** `ops/signal-log.md` and the thresholds in it, `ops/decisions.md`.

**Output.** A logged verbatim, a type, a disposition, and if it is a PATCH or an AMEND, the routed
file list in the right order.

**What it saves.** Two opposite failures at once. A brain that amends on every conversation has no
memory and flip-flops on the last thing it heard. A brain that never amends is a static document
that quietly stops being true. The thresholds are what sit between them.

---

## 7. Stop an agent overclaiming

**Trigger.** Any agent, in any tool, is about to write something a customer will read.

**Load.** Automatic. `CLAUDE.md` or the adapter for that tool names the four rules files, and
`ops/QA-checklist.md` is the gate before returning.

**Output.** Copy with every capability flagged, no proof point outside the closed set, no
unscoped superlative, no certification claim, and no invented customer.

**What it saves.** A claim that reaches a regulated buyer and cannot be defended. There is no
reference customer, so the failure mode here is not exaggeration, it is fabrication, and it is the
kind a security officer checks.

---

## 8. Prepare an event

**Trigger.** One of the two fixed dates that carry the year, with an abstract deadline months ahead.

**Load.** `templates/event-presence.md`, `reference/marketing-campaigns.md` for the build sequence,
`rules/feature-status.md` for the demonstration ban.

**Output.** The bilingual speaking abstract, the ninety-second stand conversation with its
qualifying question and its spoken disqualifier, and the same-week follow-up.

**What it saves.** The event that produces business cards and no conversations, and the follow-up
that never gets sent because it was not written before the event started.

---

## 9. Decide whether to bid a tender

**Trigger.** A tender appears on the government procurement platform, from year two.

**Load.** `templates/tender-response.md`, `rules/feature-status.md`,
`reference/saudi-regulatory-file.md` for the local content section.

**Output.** A go or no-go call, recorded in `ops/decisions.md` whichever way it goes, and if it is
a go, a response written in the tender's own numbering with a compliance matrix answered honestly.

**What it saves.** A no-bid costs a week. A bid won on a requirement that cannot be met costs the
entity relationship and, in a market this small, the next three.

---

## 10. Onboard a contractor, an agency or a first hire

**Trigger.** Somebody new has to produce work that sounds like this company.

**Load.** Hand them this README, `docs/use-cases.md`, and the master context. That is the
onboarding.

**Output.** Somebody producing on-voice, claim-safe work in their first week rather than their
second month.

**What it saves.** The review cycle where the founder rewrites everything, which is the real cost of
onboarding in a two-person company and the reason most contractors are not worth hiring.

---

## 11. Work in a chat window with no file access

**Trigger.** The founder is rewriting the landing page one evening in ChatGPT, Grok or Gemini.

**Load.** Paste `adapters/portable-control-layer.md`.

**Output.** Draft copy inside the same guardrails as anything produced in Claude Code, from a model
that cannot see a single file in this repository.

**What it saves.** The failure this whole portability layer exists to prevent. The guardrails that
load in one tool and not the others are not guardrails, they are a false sense of one.

---

## 12. Hand the whole go-to-market to somebody else

**Trigger.** An investor, an advisor, a partner or an acquirer asks how this company goes to market.

**Load.** The repository.

**Output.** A complete, dated, internally consistent go-to-market with its open questions named
rather than hidden, its conflicts logged, and its reasoning attached to every decision.

**What it saves.** The version of that conversation where strategy lives in one person's head and
has to be reconstructed out loud, differently each time.

---

## What this brain deliberately does not do

It does not produce for paid social. That is refused, with the reasoning in
`reference/relationship-engine.md`, because unlike the two primary outbound channels it returns no
named contact that can then be worked.

Instantly and HeyReach are the two primary channels and they have their own prompts. What the brain
still refuses inside them is any automated first touch into a Dream 100 account, and any merge tag
beyond first name and company.

It does not invent a proof point. Where a fact is missing the honest output is a gap, not a
plausible number.

It does not answer the five open questions in `ops/decisions.md`. Recording them as open is the
correct behaviour. An invented answer becomes a rule, and a wrong rule propagates into every asset
produced after it.
