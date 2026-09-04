# Standing Caveats — read before any dashboard in this suite

**Version 1.0 · 4 September 2026 · Wolffish Cloud · Kingdom of Saudi Arabia only**

This block is reproduced verbatim at the head of every one of the nine dashboards, the lead
magnet specification and the walkthrough deck. It is not boilerplate. Four of the five caveats
change what the numbers in those dashboards mean, and the fifth changes who is allowed to use
them.

---

## C1 — This is not SaaS. It is three products with three different economies.

The source GTM skill assumes a single B2B SaaS artefact: one product, one price, one funnel,
one set of feature economics. Wolffish is not that. It is three stacked layers, and a "feature"
behaves completely differently depending on which layer it sits in. Every feature, benefit,
score and price in this suite is tagged to a layer, and the layer tag is load-bearing.

| Layer | What it is | Who it wins over | Economic behaviour | Commoditisation risk |
|---|---|---|---|---|
| **A · Agentic harness** | The runtime on the employee's own machine. File and shell permissions, approval gates, multi-step execution, model portability. | The employee, then the engineering manager | Marginal cost is tokens, not compute. Adding agent work adds tokens, not servers. | **High.** Claude Code, Cursor, OpenHands and Copilot CLI are converging on the same capability set every quarter. |
| **B · Platform / control plane** | Quotas, audit store, kill switch, SSO and offboarding, per-role and per-agent scopes, admin console, branded deployment. | The CISO and the CFO | Near-zero marginal cost per seat. This is the SAR 79. | **Medium.** Anthropic shipped Enterprise spend controls in July 2026. Vendors are closing this gap, but only inside their own cloud. |
| **C · Cloud service / engagement** | Deployment engineering, first-class integrations into the customer's own systems, ongoing capability development, SLA, escrow. | Procurement, legal, and the business owner of the internal system | Priced once at SAR 60,000 but consumes principal time indefinitely. This is the capacity ceiling of the whole company. | **Low.** Does not commoditise. Also does not scale. |

A fourth layer exists that the source skill has no concept of at all:

| Layer | What it is | Why it is separated |
|---|---|---|
| **D · Saudi regulatory and commercial fit** | Saudi CR and SAR invoicing, ZATCA e-invoicing, PDPL no-transfer-by-architecture, NCA ECC and CCC evidence, SAMA outsourcing pack, NDMO classification mapping, Arabic contracting, ALLaM and HUMAIN endpoint support. | These are not product features and they are not services. They are **market-structural advantages that a foreign vendor cannot buy in under two years**, and in Saudi Arabia they close deals that the product alone would lose. Scoring them inside Layer A or B understates them by a factor of about three. |

**Consequence for every dashboard:** do not average a score across layers. A feature that is
"commodity" in Layer A can be the reason a Layer D deal closes. Read the layer column first.

---

## C2 — There is no self-serve motion, no free tier, and no trial-to-paid conversion.

SAR 60,000 at signature, a twelve-month term, and quarterly prepay make this a committee
purchase from the first meeting. The source skill's default pricing architecture
(Decoy / Hero / Anchor, a free entry tier at 10 to 20 percent of customers, expansion by
self-serve upgrade) does not apply and has been replaced throughout with a
**deployment-scope ladder plus in-account seat expansion**.

Anywhere a source-skill template asked for a trial funnel, an activation metric, a PQL, or an
MRR self-serve number, that cell has been re-derived rather than filled in. Where a metric
genuinely cannot exist in this model, it is marked `n/a — not a self-serve product`, never
guessed.

---

## C3 — Two of the three price lines are not Wolffish revenue.

Landed cost per employee is SAR 124 to 184 per month. Wolffish revenue is SAR 79 of it.
The remaining SAR 45 to 55 (DeepInfra inference plus relay, sync, audit-store and object
storage) is billed by the customer's own providers, directly to the customer, and never passes
through Wolffish at any margin.

- **Never model the pass-through line as revenue.** It is a positioning asset and a
  procurement-friction reducer, not income.
- **Never drop it from a competitor comparison.** Quoting SAR 79 against a ChatGPT Enterprise
  seat is a false comparison that a competent CFO will catch in the first meeting, and it
  costs more credibility than the number gains.
- Every price comparison in this suite is stated as **landed cost**, both sides.

Practical arithmetic that follows from this and drives the whole ICP:

> Wolffish year-1 revenue from one customer = SAR 60,000 + (SAR 948 × seats).
> Deployment consumes six to eight weeks of principal time regardless of seat count.
> **Below roughly 200 seats the engagement is a services business wearing a product's clothes.**
> Qualification floor is 200 seats. Target band is 300 to 600.

---

## C4 — Saudi Arabia only. This suite does not travel.

Every ICP, persona, channel, price point, asset, objection and KPI here is scoped to the
Kingdom. That is a deliberate constraint, not an omission.

- The source skill's three external research steps lean on G2, Capterra, Trustpilot and Product
  Hunt. Those corpora carry **almost no Saudi buyer signal**. They were used here only to
  extract global product-quality themes (what people love and hate about the competing
  products as products). Every Saudi-specific claim in this suite is sourced instead to Saudi
  regulation, Saudi procurement rule, or Saudi market reporting, and is cited in
  `00-RESEARCH-DOSSIER.md`.
- The source skill's default channel set (HeyReach LinkedIn automation, Instantly cold email,
  LinkedIn Ads) is close to the **worst available channel mix for Saudi enterprise**. It has
  been replaced, not supplemented. See Dashboard 08.
- Do not export this GTM to the wider GCC, to Egypt, or globally without re-running Phases 2,
  4, 7 and 8 from scratch. Phases 1, 3, 6 and 9 largely survive a move to the UAE. Phases 4, 5,
  7 and 8 do not.

---

## C5 — The Service and Offer Matrix is self-rated, split-sourced, and internally inconsistent.

`Service_Offer_Matrix_Wolffish.xlsx` contains two blocks of ratings by two different people who
have described **two different companies**.

- The **Younes block** (founder) describes a company that deploys a custom agent platform
  inside a customer's perimeter. This matches the September 2026 pricing document.
- The **Ali block** is labelled in the sheet itself as "first-pass read from the engagement
  brief, not a live product audit, to be corrected with Younes on the review call." It
  describes an **AI agent spend-governance company** — an offer that does not appear in the
  pricing document at all, at any price, in any tier.

This suite treats the Younes block as **the sold product** and the Ali block as a **candidate
adjacent offer, flagged and held separate, not merged**. Four specific rating cells are
challenged in `00-OFFER-METRICS-AUDIT.md`, including one — Ongoing Capability Development
rated "Free, diagnostic or door opener" — that is the single largest hidden margin risk in the
business model.

**Nothing downstream in this suite should be treated as validated until the Younes and Ali
blocks are reconciled on a review call.** Where a dashboard depends on an unreconciled cell,
it says so inline.

---

*Younes Alturkey · Founder & Engineer, Wolffish · younes@wolffi.sh · +966 53 865 4514 · wolffi.sh/cloud*
