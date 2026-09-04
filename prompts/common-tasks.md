# Prompt library, recurring Wolffish Cloud jobs

Filled, runnable prompts. Each assumes the agent has already read `../CLAUDE.md` and will load the
files the prompt names. Copy one, fill the square brackets, run it.

**There is no automated outreach sequencing in this go-to-market, so there are no sequencing
prompts. There is no volume cold email, so there are no cold email prompts. There is no paid
social, so there are no ad prompts.** That absence is the rule. If asked for one of the three,
decline, say why in one sentence, and offer the in-scope alternative from
`../reference/relationship-engine.md`.

## Write a founder post

"Write a bilingual founder post in the [instrument explainer / cost-shock note / deployment note /
refusal note] archetype for the [security officer / finance director] audience, on [the instrument
or number]. Follow `templates/founder-post.md` and match the voice in
`examples/founder-post-cloud-rules.md`. Arabic headline written natively, English subhead. Between
120 and 250 words. No product mention if this is an instrument explainer. Then QA against
`ops/QA-checklist.md`."

## Draft a warm introduction

"Draft both halves of a warm introduction following `templates/warm-introduction.md`: the private
ask to [sponsor], and the forwardable paragraph about [target, role, entity]. Match
`examples/forwardable-paragraph.md`. The paragraph stays under eighty words, carries no attachment
and no tracked link, and includes an explicit out for the sponsor. Check the calendar constraints
in `reference/customer-journey.md` before proposing a date."

## Prepare a security call

"Prepare the security call for [entity]. Load `templates/security-call.md`,
`reference/saudi-regulatory-file.md` for the instruments that govern this entity class, and
`rules/feature-status.md`. Give me the thirty-minute agenda, the architecture diagram brief to send
two days ahead, the two disqualifiers most likely to apply here, and the five questions this
security team is most likely to ask with the honest answer to each."

## Build a landed cost breakdown

"Build the landed cost breakdown for [seat count] seats at [entity], following
`templates/landed-cost-email.md` and matching `examples/landed-cost-email.md`. All three lines, the
pass-through marked as billed by their own providers at zero Wolffish margin, the assumptions block
separated so they can move it, and the note that figures exclude the fifteen percent value-added
tax. Reconcile every figure to `reference/pricing-model.md`. Include the honest price comparison
against [competitor] on landed cost on both sides, and say plainly if theirs is cheaper."

## Write a one-pager

"Write the bilingual one-page leave-behind for the [security officer / finance director] audience
following `templates/one-pager.md`, matching `examples/one-pager-security-officer.md`. Pull the
three pillars verbatim from `reference/value-proposition-icp1.md`. Every capability carries its
flag from `rules/feature-status.md` in the same sentence. Include the published disqualifier list.
One audience only. QA against `ops/QA-checklist.md`."

## Answer an objection

"Answer this objection: '[paste it verbatim]'. Audience is [role]. Ground the answer in
`reference/objection-handling.md` and match the concede-first structure in
`examples/objection-response-price.md`. Concede whatever part of it is true, in the first sentence.
Keep every capability flagged. If the honest answer is that a competitor is the better fit, say so."

## Position against a competitor

"Write positioning against [competitor] for a [security officer / finance director] at [entity
type], using `reference/competitor-battlecards.md`. Lead with the two vectors Wolffish owns. State
both sides on landed cost. Every superlative goes through `rules/do-not-say.md` and comes back
scoped or gets cut. If the competitor is the national champion, do not position against it at all,
neutralise in one sentence per the guardrail in `CLAUDE.md` and move on."

## Draft a Compliance Evidence Pack section

"Draft the [instrument] section of the Compliance Evidence Pack for an entity of class [bank /
government entity / listed company], following `templates/compliance-evidence-section.md` and
`reference/saudi-regulatory-file.md`. Cite the control numbers. State the mechanism, not the
intention. List the obligations that remain with the customer, and every control not yet met with
its status and expected date. Flag anything that needs Saudi counsel before external use."

## Prepare an event

"Prepare the three artefacts for [event, dates] following `templates/event-presence.md`: the
bilingual speaking abstract, the ninety-second stand conversation with its qualifying question and
its spoken disqualifier, and the same-week follow-up. Nothing flagged IN BUILD or ROADMAP may be
demonstrated. QA all three."

## Log a signal

"Log this in `ops/signal-log.md`: [paste the call note, objection, competitor move, or regulatory
change]. Keep the verbatim exactly as said, in the language it was said in. Classify the type,
assign a disposition using the thresholds in that file, and if it is a PATCH or an AMEND, route it
and tell me exactly which files change and in what order."

## Take a snapshot

"Build this period's snapshot in `snapshots/` from [paste the data]. Fill every section, diff the
capability section against `rules/feature-status.md`, and finish with what this changes, including
'no ledger change this period' if that is the honest answer."

## Audit the brain

"Run the audit script on this repo, then produce one real asset using only what is in the brain and
run it through `ops/QA-checklist.md`. Report anything the asset needed that the brain could not
supply, because that is the gap list."

## Refuse a request

"I have been asked to produce [the request]. Check it against the channel discipline in `CLAUDE.md`
and `reference/relationship-engine.md`. If it is one of the three refused channels, or it needs a
proof point outside the closed set, or it demonstrates an unshipped capability, decline in one
sentence, say why, and propose the in-scope alternative."
