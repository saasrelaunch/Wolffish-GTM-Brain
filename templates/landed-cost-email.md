# Template, landed cost breakdown

Audience: the finance director, who was not in the room. Channel: owned and follow-up. This is the
document that survives being forwarded without you, so it must answer the questions you would have
answered in person.

## The rule this template exists to enforce
Wolffish publishes three price lines and a competitor usually publishes one. Quoting the seat fee
alone against a competitor seat price hides roughly a third of the cost and a competent finance
director will find it, at which point the credibility of every other number is gone. Every cost
communication carries all three lines and the words landed cost.

## Structure
- **One line of context.** Who asked, or who this was prepared for.
- **The three lines, as a table.** Platform and deployment, seats, and pass-through inference and
  infrastructure, with the pass-through explicitly marked as billed by the customer's own providers
  at zero Wolffish margin.
- **The assumptions block.** Seat count, period, usage assumption, and the model or endpoint
  assumed. Every number that moves lives here, so the reader can move it.
- **The landed total,** stated once, with the note that it excludes the fifteen percent
  value-added tax.
- **The comparison, if one is requested.** Both sides on landed cost. If the competitor's landed
  cost cannot be computed from public information, say so rather than estimating it.
- **What is not included.** Anything outside the deployment scope ladder, named.

## Fields to fill
- Seat count and period: [number, months]
- Usage assumption: [the basis, stated so it can be challenged]
- Endpoint or model assumed: [name, and whether it is the sovereign in-Kingdom option]
- Scope ladder rung: [which one, and what sits outside it]

## What may never appear here
No pass-through figure described as revenue.
No discount invented on the spot. Pricing is published and fixed.
No promise of unbounded ongoing capability development. The capability allowance is proposed and
not contracted, so the phrase no new invoice must not appear.

Guardrail: figures reconcile to `../reference/pricing-model.md`, claims to
`../rules/do-not-say.md`, and the draft goes through `../ops/QA-checklist.md` before sending,
because this document gets forwarded to people who never speak to you.
