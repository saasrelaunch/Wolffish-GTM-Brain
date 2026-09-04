# Template, public tender response

Audience: an evaluation committee scoring against a published matrix, not a person being
persuaded. Channel: public tender, a year-two channel. Registration on the government procurement
platform must be complete before a relevant tender appears, never after.

## The mindset shift
A tender is scored, not read. Persuasive prose loses points that a plainly numbered response
collects. Answer in the order and the numbering of the tender document, even where the order makes
the argument worse.

## Structure
- **Compliance matrix first.** Every requirement, answered comply, partially comply or not comply.
  A partial answered honestly scores better than a comply that fails at clarification stage.
- **Technical response.** Per requirement, in the tender's own numbering, each capability carrying
  its status flag.
- **Local content.** The certificate, the score and the mechanism behind it. This is often worth
  more points than any technical differentiator.
- **Commercial response.** All three price lines, mapped onto the tender's own cost breakdown
  structure, with pass-through identified as customer-billed.
- **Evidence annexes.** The Compliance Evidence Pack sections that match the instruments named in
  the tender, plus the escrow deed and the service level terms.
- **Capacity statement.** Delivery capacity is four to six deployments a year. An overcommitted
  bid that is won is worse than a lost one.

## Fields to fill
- Tender reference and entity: [number, issuing entity, closing date]
- Instruments named in the tender: [list]
- Requirements we cannot meet: [list them, with the honest disposition]
- Partner, if bidding jointly: [name and the split]

## Go or no-go, decided before writing
Do not bid a tender whose requirements include a certification not held, a capacity beyond the
ceiling, or a scope outside the ladder. A no-bid costs a week. A bid won on a requirement that
cannot be met costs the entity relationship and, in a market this small, the next three.

Guardrail: every status flag from `../rules/feature-status.md`, every compliance claim in the
permitted form from `../rules/do-not-say.md`, every figure reconciled to
`../reference/pricing-model.md`. Run `../ops/QA-checklist.md`, then record the go or no-go call in
`../ops/decisions.md` whichever way it went.
