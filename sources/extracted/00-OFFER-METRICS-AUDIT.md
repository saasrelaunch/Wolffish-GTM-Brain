# Offer Metrics Audit — reading the Service & Offer Matrix carefully

**Version 1.0 · 4 September 2026 · Source: `Service_Offer_Matrix_Wolffish.xlsx`, sheet "Service Matrix"**

## ⚠️ Standing caveats for this audit

**C1 — Not SaaS.** Each corrected row is tagged to the layer it sells: harness, platform, service,
or Saudi regulatory fit. Two of the six findings exist only because a service layer and a
regulatory layer are being priced as if they were product features.

**C2 — No self-serve.** "Entry offer" throughout this file means a **free diagnostic that starts a
committee conversation**, never a self-serve funnel step. Both entry offers in the corrected matrix
are founder-delivered.

**C3 — Two of three price lines are not Wolffish revenue.** Every ticket size here is Wolffish
revenue only. The pass-through line appears nowhere in this file, and no finding should be read as
a claim about the customer's landed cost.

**C4 — Saudi only.** Two corrections exist purely because of Saudi market structure: the Compliance
Evidence Pack (recast from a paid service to an embedded free deliverable, because charging to
clear the buyer's own regulator signals that clearing it is optional), and pre-packaged escrow.
Neither correction would be made for a US or European market.

**C5 — This file is the reconciliation.** It is the prerequisite for trusting anything downstream,
and its own conclusions are unvalidated until the review call. Six open actions are listed at the
end.

---

## Finding 0 — The two blocks describe two different companies

| | Younes block (founder) | Ali block (SaaS Relaunch first-pass) |
|---|---|---|
| Implied category | A **deployed agent platform inside the customer's perimeter** | An **AI agent spend-governance vendor** |
| Rows | Discovery & Security Call · Cloud Deployment · Platform Seat · Ongoing Capability Development · Source Access & Escrow | Agent Spend Governance Platform · Agent Spend Diagnostic · Governance Policy & Guardrail Design · Managed Optimization Retainer · Enterprise Rollout & Procurement Support |
| Supported by the Sept 2026 pricing document? | **Yes, exactly.** Three price lines, the deployment, the seat, ongoing engineering, the SLA, escrow. | **No.** Not one of these five appears in the pricing document at any price, in any tier, under any name. |
| Sheet's own status note | none | *"First-pass read from the engagement brief, not a live product audit. To be corrected with Younes on the review call."* |

**Resolution used throughout this suite.** The Younes block is treated as **the sold product**.
The Ali block is treated as a **candidate adjacent offer**, held separate and flagged, not merged.

**Why this matters more than it looks.** Cost control is real and it is one of Wolffish's two
strongest arguments (see Dashboard 02, vector V4). But it is *reason four of eight* in the
pricing document, not the category. Category is decided by what the buyer thinks they are
buying, and the two readings put Wolffish in two different rooms:

- *Agent spend governance* puts Wolffish in the FinOps room, against Vantage, CloudZero, Finout
  and every observability vendor adding an AI-cost module, selling to a FinOps lead, with a
  ceiling set by "how much are we overspending."
- *Deployed agent platform inside your perimeter* puts Wolffish in the CISO and CEO room,
  against Microsoft, HUMAIN and the SI, selling a per-employee capability programme, with a
  ceiling set by headcount.

The second room is larger, harder to enter, and the only one where SAR 79 per employee per month
is a rational price. **The Ali framing would, if adopted, reprice the company downward by roughly
an order of magnitude.** It should be captured as a *wedge offer inside* the platform story, not
as the story. Dashboard 01 carries the surviving Ali rows in exactly that role.

---

## Finding 1 — "Ongoing Capability Development" is misrated, and it is the largest hidden margin risk in the model

| Column | Sheet value | Audit verdict |
|---|---|---|
| Client Demand | Wanted by most | Understated. The pricing document sells it as an inclusion; anyone who buys the platform will use it. **Should be: Wanted by every client.** |
| Competitive Differentiation | A few others can | Correct, arguably generous to competitors. |
| Delivery Effort | **Heavy, senior-led custom** | Correct, and this is the problem. |
| Sales Motion | Fast and simple, under 30 days, 1 decision maker | Correct — but only because **it is not a sale at all.** |
| Ticket Size | **Free, diagnostic or door opener** | **Wrong by construction.** |
| Funnel Role | Anchor, retention | Correct. |

**The defect.** The pricing document commits to *"ongoing engineering for new capabilities as
you need them"* and the matrix's own outcome text promises delivery *"inside the quarter"* with
*"no new invoice"* — bundled into the SAR 79 seat. So the Ticket Size cell is not "free as a
door opener." It is **unbounded senior engineering time, sold at a fixed per-seat price, with a
quarterly delivery commitment and no cap.**

Rating it green as a free door opener hides the exposure. Rating it correctly makes it visible:

> **Ongoing Capability Development is an uncapped cost of goods sold attached to a fixed-price
> recurring line, delivered by the single scarcest resource in the company.**

**Worked exposure.** At 300 seats a customer pays SAR 284,400 per year. If that customer's teams
request one meaningful new integration per quarter and each consumes two principal weeks, the
commitment consumes eight principal weeks a year — roughly the same principal time as an entire
new SAR 60,000 deployment. Across four such customers it consumes a full principal year, and
there is no principal left to sell with.

**Recommended correction, carried into Dashboard 09:**
- Restate as **Ticket Size = embedded in seat (non-billable)**, Funnel Role = Anchor, retention.
- Define the inclusion contractually: a **capability allowance** — for example two scoped
  capabilities per quarter per deployment, each under a stated effort ceiling — with anything
  beyond it quoted as a scoped change order.
- Keep the *feeling* of "it does not generate a new invoice," which is a genuine differentiator
  against the SI, while bounding the liability. The allowance framing preserves the sales line
  and removes the open-ended exposure.

---

## Finding 2 — "Discovery & Security Call" is under-rated on differentiation

Sheet reads Competitive Differentiation = **"Most others can."** True of the *activity*. False of
the *execution*.

What is actually on offer is the founder-engineer who wrote the platform, answering a Saudi
CISO's NCA, NDMO, PDPL and SAMA architecture questions live, in the first meeting, without a
pre-sales engineer, a legal review, or an escalation — and saying no if it is not a fit. Almost
nobody in this market can do that. Microsoft sends an account team. OpenAI and Anthropic send a
form. The SI sends a solution architect who will come back to you.

**Correction: A few others can.** This matters because Discovery & Security Call is the **only
entry offer in the Younes block**, and the entry offer's job is to create the asymmetry the rest
of the funnel spends. Under-rating it leads directly to under-investing in it — and Dashboard 08
makes it the single most produced-for asset in the library.

---

## Finding 3 — "Source Access & Escrow" lengthens the cycle it exists to shorten

Sheet reads: Ticket Size = Low, Sales Motion = **"Long and complex, 6 months plus, procurement
and legal"**, Funnel Role = Credibility play.

That is an honest and correct self-assessment, and it describes a trap. Escrow exists to remove
the single-vendor-risk objection. But if it is *negotiated* rather than *presented*, it adds a
procurement-and-legal cycle to a deal that would otherwise close faster, and the mechanism
intended to unblock the deal becomes its longest pole.

**Correction:** pre-package it. A standing escrow arrangement with a named agent, a
pre-drafted trilateral deed, and the release conditions already written, presented as a
data-room artefact at the security call rather than opened as a negotiation at contract stage.
Sales Motion then drops from "6 months plus" to a document the buyer's counsel reviews in
parallel. Carried into Dashboard 07 (stage 3) and Dashboard 08.

---

## Finding 4 — "Wolffish Cloud Deployment" at Ticket Size = Mid is the binding constraint on the company

Sheet reads: Delivery Effort = **Bespoke, principal time throughout**, Ticket Size = **Mid**
(SAR 60,000), Sales Motion = Complex 3 to 6 months committee.

SAR 60,000 buys six to eight weeks of the founder's engineering time end to end. That is not a
mid ticket; it is a below-market principal engagement priced as a land fee. Which may well be
the right *strategic* choice — it lowers the barrier to the first deployment and the seat line
is where the money is — but it must be recognised for what it is:

> **Deployment is not a revenue line. It is a paid pilot that consumes the company's only
> non-scalable resource, and it sets the hard ceiling on customer count.**

**Capacity arithmetic.** One principal, six to eight weeks per deployment, plus selling, support
and ongoing capability work: realistically **four to six deployments in the first twelve months**,
not more. That single number reshapes the entire GTM, and it is the reason Dashboard 04 targets
roughly twenty named accounts rather than a demand-generation funnel, and Dashboard 08 spends on
depth per account rather than reach.

**Recommended corrections, carried into Dashboard 09:**
- Restate Ticket Size as **Mid, strategically underpriced — land fee, not margin.**
- Introduce a **deployment scope ladder** (Pilot / Standard / Complex) so that a genuinely
  complex integration estate is not absorbed at the same SAR 60,000.
- Enforce the **200-seat qualification floor** derived in caveat C3. Below it, the engagement
  cannot repay the principal time at any point in the contract.

---

## Finding 5 — "Platform Seat" Delivery Effort is optimistic in year one

Sheet reads Delivery Effort = **"Templated but customized."** That is the correct steady-state
answer and the wrong first-three-customers answer. Until the deployment pattern has been run
three or four times across different Saudi identity, network and data-classification
environments, seat delivery is closer to heavy and senior-led, and the template is being written
as it is used.

**Correction: heavy and senior-led for deployments one to three, templated but customised from
four onward.** Carried into Dashboard 09 as an explicit gross-margin ramp rather than a flat
assumption.

---

## Finding 6 — Two Ali rows survive as wedge offers; three do not survive as standalone products

| Ali row | Verdict | Where it lands in this suite |
|---|---|---|
| **Agent Spend Diagnostic** | **Survives, and is valuable.** A one-week read that shows a CFO exactly which agents and workflows drive the AI bill is a near-perfect Saudi entry offer: fast, free or low-cost, single decision maker, and it *creates* the problem Wolffish solves. | Promoted to a **co-equal entry offer** alongside the Discovery & Security Call, and it is the basis of the Phase 1 demand driver and the ScoreApp lead magnet. |
| **Enterprise Rollout & Procurement Support** | **Survives as an included capability, not a product.** In Saudi Arabia, answering security, residency and procurement questions in a documented pack is not an upsell — it is the price of being allowed to bid at all, under SAMA, CST and NCA. Rated "Very high, mandate level" ticket in the sheet; in reality it should be **embedded and free**, because charging for it signals that clearing the buyer's own regulator is optional. | Becomes the **Compliance Evidence Pack**, a Dashboard 08 asset produced once and reused, and a stage-3 gate in Dashboard 07. |
| **AI Agent Spend Governance Platform** | **Does not survive as a separate product.** Its capabilities — spend visibility by team and task, hard budget caps enforced automatically — are already Layer B of Wolffish Cloud (`B1` quota, `B6` spend visibility). Selling them separately splits the story and halves the price. | Folded into Layer B features `B1` and `B6` in Dashboard 01. |
| **Governance Policy & Guardrail Design** | **Does not survive as a product.** Configuring budget limits, approval thresholds and auto-throttles to a client's decision structure is deployment work, and the pricing document already sells it inside the SAR 60,000. | Folded into deployment scope in Dashboard 09. |
| **Managed Optimization Retainer** | **Does not survive, and is actively hazardous.** Rated Ticket Size = Low, Delivery = templated but customised, Sales Motion = fast. It is a low-price recurring line that competes for the same principal hours as Ongoing Capability Development, which is already uncapped and already bundled. Adding a second, cheaper claim on the same scarce resource makes the Finding 1 exposure worse. | **Recommended: do not sell.** If retained at all, it must be staffed by someone other than the principal. |

---

## Corrected matrix — the version this suite runs on

| Service / Offer | Layer | Client Demand | Competitive Differentiation | Delivery Effort | Sales Motion | Ticket Size | Funnel Role | Change from sheet |
|---|---|---|---|---|---|---|---|---|
| Discovery & Security Call | C + D | Wanted by every client | **A few others can** | Productized, runs off a template | Fast and simple, <30 days, 1 DM | Free, door opener | Entry offer, door opener | Differentiation raised (F2) |
| Agent Spend Diagnostic | C + B | Wanted by most | **A few others can** | Productized, runs off a template | Fast and simple, <30 days, 1 DM | Free, door opener | Entry offer, door opener | Promoted from Ali block; differentiation raised (F6) |
| Wolffish Cloud Deployment, SAR 60,000 | C | Wanted by every client | A few others can | Bespoke, principal time throughout | Complex, 3–6 months, committee | **Mid — land fee, not margin** | **Core revenue driver + capacity ceiling** | Reframed (F4); scope ladder added |
| Wolffish Cloud Platform Seat, SAR 79 | A + B | Wanted by every client | A few others can | **Heavy senior-led for #1–3, then templated** | Complex, 3–6 months, committee | High | Core revenue driver | Effort ramp added (F5) |
| Ongoing Capability Development | C | **Wanted by every client** | A few others can | Heavy, senior-led custom | n/a — not separately sold | **Embedded in seat, non-billable, capped by allowance** | Anchor, retention | **Repriced and bounded (F1)** |
| Compliance Evidence Pack (NCA / PDPL / SAMA / NDMO) | D | Wanted by every client | **Only we can, by architecture** | Productized after first build | Runs inside the main cycle | Embedded, free | **Deal-clearing gate** | Recast from Ali's "Enterprise Rollout & Procurement Support" (F6) |
| Source Access & Escrow | C + D | Wanted by most | A few others can | Productized, runs off a template | **Parallel document review, pre-packaged** | Low | Credibility play, not for margin | Pre-packaged to shorten cycle (F3) |
| ~~Managed Optimization Retainer~~ | — | — | — | — | — | — | **Recommended: do not sell** | Competes for principal hours (F6) |

---

## Open actions for the review call

1. Confirm or reject the Younes framing as the category. **This is the decision everything else hangs on.**
2. Agree the capability allowance that bounds Finding 1, in writing, before the next contract.
3. Approve the deployment scope ladder and the 200-seat qualification floor.
4. Approve pre-packaged escrow and appoint the escrow agent.
5. Decide whether the Agent Spend Diagnostic ships as a free founder-led read, a ScoreApp
   self-assessment, or both. Dashboard 01 and the lead magnet spec assume **both**.
6. Kill or restaff the Managed Optimization Retainer.
