# Dashboard 09 — Pricing and Packaging

**Wolffish Cloud · Kingdom of Saudi Arabia · v1.0 · 4 September 2026**
*Source skill Phase 9, steps 9.1 to 9.3. **The Decoy-Hero-Anchor tier structure has been replaced**, for the reasons below.*

---

## ⚠️ Standing caveats for this dashboard

**C1 — Not SaaS.** Pricing has **three lines across three layers**, not one price with four tiers.
The deployment fee buys Layer C, the seat buys Layers A and B, and Layer D is free and is the
reason the deal is legal. A tier table that collapses these into "Starter / Pro / Enterprise"
would misdescribe the product to the one person most likely to check.

**C2 — No self-serve, and the tier model is therefore discarded.**

> The source skill prescribes a four-tier Decoy-Hero-Anchor ladder with a free or low entry tier
> taking 10 to 20 percent of customers, a hero tier taking 60 to 80 percent, and expansion by
> self-serve upgrade. **None of that is applicable and none of it is filled in below.** Wolffish
> has no free tier, no self-serve upgrade path, and a customer count in the single digits, so a
> distribution target expressed as a percentage of customers is meaningless at n=5. The structure
> is replaced with a **deployment scope ladder plus in-account seat expansion**, which is what the
> business actually sells.

**C3 — Two of three lines are not Wolffish revenue, and every table here separates them.** The
pass-through line is shown because hiding it loses CFOs, and is excluded from every revenue
figure because including it would be false.

**C4 — Saudi only.** All figures in SAR. **All prices are stated exclusive of 15 percent Saudi
VAT**, which must appear on every quotation and every ZATCA e-invoice. Payment terms, invoicing
mechanics and the negotiation posture below are specific to Saudi enterprise practice and do not
transfer.

**C5 — Offer metrics unreconciled, and this dashboard is where that bites hardest.** Two
structural corrections from `00-OFFER-METRICS-AUDIT.md` are implemented here and **neither exists
in the current commercial documents**: the **deployment scope ladder** (Finding 4) and the
**capability allowance** that bounds ongoing capability development (Finding 1). Until both are
agreed and contracted, the business is selling an uncapped senior-engineering commitment against a
fixed recurring price. **This is the most urgent open action in the entire suite.**

---

## Step 9.1 — Value metric selection

| Denominator | Correlation to value | Scalability | Ease of measurement | Score |
|---|---|---|---|---|
| **/employee seat** | **High.** Value accrues per person who gets an agent. A knowledge worker with an agent is worth roughly the same to any employer, so the metric tracks value without needing to measure it. | **High.** Zero marginal cost per additional seat on Wolffish's side. Expansion is a line-item change. | **High.** Directory count. Auditable, undisputable, already how the customer thinks about headcount. | **9.2** |
| /provisioned seat, distinct from active user | Medium. Provisioned but unused seats are revenue without value, which produces exactly the resentment that kills a renewal. | High | High | 6.4 |
| **/token or /usage** | **Low, and negatively correlated in practice.** A poorly engineered agent consumes more tokens for the same outcome. Charging on tokens rewards inefficiency and penalises the adoption you want. | High | High | **2.8** |
| /outcome — per claim processed, per contract reviewed, per document produced | **Very high.** Perfectly aligned with value. | **Low.** Requires per-customer instrumentation, an agreed attribution model, and a trust relationship Wolffish does not have with customer one. | **Low.** Attribution disputes at renewal are near-certain. | 5.6 |
| /capability or /integration | Medium. Correlates with Wolffish's cost, not with the customer's value. | **Low.** Each capability consumes principal time, which is the scarcest resource in the company. | High | 4.1 |
| /deployment, one-time | High for Layer C specifically. Does not recur, so it cannot be the primary metric. | Low — bounded by principal capacity | High | 6.9 *(correct as a secondary, one-time metric)* |

### Recommendation

- **Primary value metric: the employee seat, at SAR 79 per month, flat.**
- **Secondary metric: the deployment scope tier, one-time**, replacing the current flat SAR 60,000.
- **Capacity selector, not a meter: the token quota tier** — Standard, High or Unmetered. **This is
  a selection of how much the customer spends with their own inference provider. It does not
  change what they pay Wolffish.**
- **Explicitly rejected: usage-based pricing of any form.**

**Why usage pricing is rejected on strategic rather than economic grounds.** It would be the
easiest revenue in the business and it would destroy the company's positioning in a single quarter.
Vector V4 in Dashboard 02 — *forecastable cost per employee* — is one of only two vectors Wolffish
leads, and its entire credibility rests on Wolffish taking **no margin on inference at all**. The
moment a token generates Wolffish revenue, the interests that make the pitch believable are
inverted, and a competent CFO will spot it. **The absence of a meter is the product.**

**Why the seat price does not rise with the quota tier.** A customer on the High quota consumes
SAR 90 of their own inference instead of SAR 30. They pay Wolffish SAR 79 either way. Charging
more for a bigger quota would reintroduce, in miniature, the exact dynamic the company exists to
argue against — and it would be visible in the first pricing conversation. The marginal platform
cost of a higher-throughput seat is real but small, and it is worth absorbing to keep the claim
clean.

---

## Step 9.2 — Packaging

### Line 1 — Deployment scope ladder *(new; implements Finding 4)*

The current flat SAR 60,000 charges the same for a two-integration deployment into a clean
Microsoft Entra estate as for a six-integration deployment across three legal entities with a
SAMA approval process attached. Since deployment consumes the company's only non-scalable
resource, that is a structural mispricing.

| Tier | Price (SAR, ex-VAT) | Seats | First-class integrations | Duration | Includes | Who it is for |
|---|---|---|---|---|---|---|
| **Pilot Deployment** | **25,000** | 10 to 25 | 1 | 3 weeks | One business unit, one named workflow, standard identity, no production rollout. **Credited in full against a Standard or Complex deployment fee if converted within 90 days.** | An account that needs proof before a company commitment. **A paid pilot, never a free one** — a free pilot spends principal capacity on an unqualified account and destroys the price anchor in a market where buyers compare notes. |
| **Standard Deployment** | **60,000** | 200 to 600 | Up to 3 | 6 to 8 weeks | Scoping, custom build, branded deployment, standard identity integration, pilot cohort, company rollout, Compliance Evidence Pack | The ICP Level 1 default. Unchanged from the current price, deliberately: it is a land fee, not margin. |
| **Complex Deployment** | **95,000 to 150,000** | 600+ | 4 or more | 10 to 14 weeks | Everything in Standard, plus multi-entity or multi-jurisdiction scope, non-standard identity or network, segregated or air-gapped segments, SAMA or NCA approval support, phased rollout across business units | ICP Level 2, regulated financial institutions, giga-project entities, group deployments |

**The ladder is a qualification instrument as much as a pricing one.** An account that resists the
Complex tier while describing a Complex environment is telling you their budget and their
seriousness before you have spent six weeks finding out.

### Line 2 — Platform seat

| Item | Price | Billing | Notes |
|---|---|---|---|
| **Wolffish Cloud platform seat** | **SAR 79 per employee per month, ex-VAT** | Quarterly in advance, 12-month minimum term | Flat at every volume. Includes the agent, sync, audit, admin console, SLA, maintenance and the capability allowance. |
| Minimum contracted seats | **200** | — | Implements the qualification floor in caveat C3. Below 200, decline (Dashboard 04). |
| Volume banding | **None** | — | See below. |
| Term concession | 24-month term: seat price protected at SAR 79 for the full term. 36-month: protected, with the deployment fee reduced by 10 percent. | — | **Concede on term, never on seat price.** |

**Why there is no volume discount, and what to concede instead.** Saudi enterprise negotiation
expects movement, and refusing all movement reads as inflexible. But a volume discount on the seat
rewards a larger customer for something that costs Wolffish nothing extra, and it converts "the
price is the price" — a genuine differentiator against a market of quote-only vendors publishing
no numbers at all — into "the price is negotiable," which is what everyone else offers. **Concede
on term length, on deployment scope inclusions, and on quota tier support. Hold the seat.** Above
1,000 seats, if a band becomes unavoidable, structure it as a **retrospective rebate on achieved
seat count**, not as a lower list price, so the published number survives.

### Line 3 — Pass-through, billed by the customer's own providers

| Item | Approximate cost | Billed by | Wolffish margin |
|---|---|---|---|
| Inference — open weights on a zero-retention endpoint | ~SAR 30 per seat per month at Standard quota (100M input, 8M output) · ~SAR 90 at High (300M, 25M) | The customer's own inference account | **Zero. Never resold.** |
| Infrastructure — relay, sync, audit store, object storage. No GPUs. | ~SAR 15 to 25 per seat per month | The customer's own cloud account | **Zero.** |

### Landed cost, the only number that should ever be quoted

| Seats | Deployment (yr 1) | Wolffish seats / yr | Customer inference | Customer infra | **Landed yr 1** | **Per seat / mo** | **Landed yr 2+** | **Per seat / mo** |
|---|---|---|---|---|---|---|---|---|
| 200 | 60,000 | 189,600 | 72,000 | 52,800 | **374,400** | **SAR 156** | **314,400** | **SAR 131** |
| 300 | 60,000 | 284,400 | 108,000 | 72,000 | **524,400** | **SAR 146** | **464,400** | **SAR 129** |
| 500 | 60,000 | 474,000 | 180,000 | 90,000 | **804,000** | **SAR 134** | **744,000** | **SAR 124** |
| 1,000 | 95,000 *(Complex)* | 948,000 | 360,000 | 168,000 | **1,571,000** | **SAR 131** | **1,476,000** | **SAR 123** |

*The 1,000-seat row applies the new Complex tier and extrapolates the published infrastructure
band; the 200 to 500 rows are as published in the Wolffish pricing document.*

### Expansion levers

| # | Lever | Wolffish revenue? | Notes |
|---|---|---|---|
| 1 | **Seat expansion by business unit** | **Yes — this is the growth model.** | Deployment is a one-time land fee; the seat line is the entire annuity. Target 40 percent seat growth by month 12 (Dashboard 07 stage 6). |
| 2 | Quota tier upgrade, Standard to High | **No.** | Increases the customer's own inference spend, not Wolffish's revenue. **It is an adoption signal, and the best leading indicator of renewal in the business.** Track it as a health metric, never as a revenue forecast. |
| 3 | Integrations beyond the capability allowance | Yes, as scoped change orders | The pressure valve that makes the allowance bounded rather than uncapped. |
| 4 | Second deployment for another group entity | Yes, a second deployment fee | Common in Saudi family holdings and PIF portfolios, where sister companies are separate legal entities with separate CRs. |
| 5 | Complex-tier upgrade at renewal | Yes | When scope has grown past what Standard covers. |
| 6 | ~~Managed Optimization Retainer~~ | — | **Recommended: do not sell.** Competes for the same principal hours as the capability allowance. See Finding 6. |

### The capability allowance *(new; implements Finding 1 — the most urgent item in this suite)*

| Tier | Included per quarter | Effort ceiling per capability | Beyond the allowance |
|---|---|---|---|
| Standard deployment | **2 scoped capabilities** | 5 working days each | Scoped change order at SAR 12,000 to 25,000 per capability, quoted before work starts |
| Complex deployment | **3 scoped capabilities** | 5 working days each | As above |

**Sales language, which must not change even though the commercial reality has:** *"New agent
capabilities keep shipping after go-live. When a team needs the agent to reach another internal
system, it gets scoped and shipped inside the quarter, and it does not generate a new invoice."*
That sentence stays true under the allowance, because the allowance covers the volume a real
customer actually consumes. What changes is that the exposure now has a ceiling.

**Unbounded, the arithmetic fails:** four customers each requesting one meaningful integration per
quarter at two principal weeks each consumes a full principal year, leaving nobody to sell or to
deploy. Bounded at two capabilities per quarter with a five-day ceiling, the same four customers
consume roughly sixteen principal weeks a year, which is sustainable and leaves the deployment
capacity intact.

### Saudi commercial mechanics

| Item | Position | Why it matters here |
|---|---|---|
| **VAT** | 15 percent, added, itemised on every quotation and ZATCA e-invoice | A quotation without explicit VAT treatment gets returned by Saudi procurement. |
| **Invoicing** | ZATCA-compliant e-invoice, SAR-denominated, from a Saudi CR holder | Processed as routine. A USD invoice from a foreign entity is an exception requiring extra internal treatment, which is a quiet, real advantage over OpenAI, Anthropic and Cursor. |
| **Payment terms** | Quarterly in advance | Genuinely favourable to Wolffish in a market where 60 to 120-day terms are common. **Expect this to be negotiated, and defend it** — it is working capital for a two-person company. Trade term length for payment timing, not the reverse. |
| **Deployment fee split** | 50 percent at signature, 50 percent at go-live | Standard and defensible. Resist a shift to 100 percent on go-live, which transfers all delivery risk to Wolffish. |
| **Contract** | Arabic and English, Saudi jurisdiction, Saudi governing law | Removes the foreign-jurisdiction objection entirely and shortens legal review. |
| **Bank guarantee** | Not required for ICP Level 1. Anticipate for Etimad tenders in year two. | A performance bond requirement can be a hard blocker for a small company. Check before bidding. |
| **Local content statement** | Prepared and current | LCGPA weighting on IT services begins 1 April 2027 for tenders at or above SAR 10m, extending to SAR 5m from 1 January 2028. Below Wolffish's current deal sizes, but several large private buyers apply their own preferences. |
| **Currency** | SAR, pegged at 3.75 to the USD | No FX exposure for the customer, unlike every foreign competitor. Say so. |

---

## Step 9.3 — ROI anchoring

### Anchor 1 — Cost of the problem

| Problem scenario | Cost without a solution | Annual Wolffish landed cost, 300 seats yr 2+ | ROI multiple |
|---|---|---|---|
| **A PDPL finding involving customer personal data** — SDAIA issued 48 enforcement decisions in the year to early 2026 | **SAR 5,000,000** per breach, doubling on repeat, plus remediation and reputational cost | SAR 464,400 | **10.8x** |
| **An unbudgeted AI cost overrun** on the 2026 pattern — Uber exhausted its full-year budget by April; 78 percent of IT leaders hit by surprise charges | **~SAR 550,000** at 300 seats *(modelled Claude Code rollout of SAR 851,850 against a budgeted SAR 300,000)* | SAR 464,400 | **1.2x in the first year of avoidance alone** |
| **A stalled AI pilot** — internal effort plus an SI engagement that never reaches production | **SAR 400,000 to 900,000** *(modelled)* | SAR 464,400 | **1.5x**, and the Wolffish spend produces a production system rather than a lesson |
| **Scaling knowledge work by hiring** under Saudization cost and availability pressure | **~SAR 200,000** per fully loaded knowledge worker per year *(modelled)* | SAR 464,400 | Whole-company platform costs the equivalent of **2.3 hires** |
| **A SAMA outsourcing or cloud approval that fails or stalls** | Two to three quarters of programme delay, plus sunk vendor and internal cost | SAR 464,400 | Not quantified. **The architecture removes the approval question rather than answering it**, which is the point. |

### Anchor 2 — Alternative comparison, 300 seats, year 2 onward

| Alternative | Their annual cost | Wolffish landed | Saving | Notes |
|---|---|---|---|---|
| ChatGPT Enterprise | SAR 904,500 | SAR 464,400 | **49 percent** | And no agents, no Saudi residency, no Saudi entity |
| Claude Enterprise with Claude Code | SAR 851,850 | SAR 464,400 | **45 percent** | Metered. The gap widens with adoption. |
| Claude Enterprise, heavy autonomous agents | SAR 2,544,750 | SAR 464,400 | **82 percent** | This is the Uber scenario, priced |
| Microsoft 365 Copilot at USD 30 per seat | ~SAR 405,000 seats only | SAR 464,400 | **Wolffish costs more** | **State this plainly.** Copilot is cheaper and it is a different product: no device execution, no enforced quota, no customer-owned audit log, no custom integration. Compare capability, not price, and say so first. |
| Saudi SI custom build | ~SAR 1,200,000 yr 1, ~SAR 650,000 yr 2+ *(modelled: build, then maintenance plus change orders)* | SAR 524,400 / SAR 464,400 | **~56 percent / ~29 percent** | And the gap compounds, because every new capability is a new quote |
| DIY open-source in-house | ~SAR 580,000 *(modelled: 2 engineers at SAR 200,000 plus inference and infrastructure)* | SAR 464,400 | **20 percent** | **The honest comparison, and the one to make.** The saving is modest; the difference is that the DIY stack produces no enforced quota, no attributed action-level audit, no approval gates, no offboarding and no SLA. Argue governance, not price. |
| Status quo — shadow AI | SAR 0 visible | SAR 464,400 | Negative on paper | Unbounded and uninventoried regulatory exposure. This is what the free Exposure Audit is for. |

*Competitor figures are modelled from published rates, reported bands and independent analyses,
converted at SAR 3.75 to the USD, and carry the estimate caveats in the Wolffish pricing document.
Vendor seat prices are negotiated and move with volume and term. The Wolffish figures are the only
fixed numbers in this table, because they are Wolffish's own.*

### Anchor 3 — Breakeven

The strongest arithmetic Wolffish has, and the one most consistently left out of the pitch.

| Plan | Annual landed cost (300 seats, yr 2+) | Value needed to break even | Typical knowledge-worker value base | **Productivity gain required** | Payback at a 5 percent measured gain |
|---|---|---|---|---|---|
| Wolffish Cloud, 300 seats | **SAR 464,400** | SAR 464,400 of recovered capacity | 300 knowledge workers × ~SAR 200,000 fully loaded = **SAR 60,000,000** | **0.77 percent** | **~57 days** |
| Wolffish Cloud, 500 seats | SAR 744,000 | SAR 744,000 | 500 × SAR 200,000 = SAR 100,000,000 | **0.74 percent** | ~54 days |
| Wolffish Cloud, 200 seats | SAR 314,400 | SAR 314,400 | 200 × SAR 200,000 = SAR 40,000,000 | **0.79 percent** | ~58 days |

**The sentence this table produces, and it should be said in every CFO meeting:**

> **Your agent platform pays for itself if it makes your knowledge workers less than one percent
> more productive. Microsoft's own users report twenty to forty percent reductions in
> administrative task time, from a product that only drafts. We are asking you to believe in
> nought point eight.**

*Knowledge-worker fully loaded cost of SAR 200,000 is modelled and should be replaced with the
customer's own figure during the Exposure and Spend Audit. Using their number instead of a modelled
one roughly doubles the persuasive force of this table and costs nothing.*

### "One avoided X pays for Y years" calculator

| One avoided event | Value | Wolffish-only cost, 300 seats yr 2+ (SAR 284,400) | Landed cost, 300 seats yr 2+ (SAR 464,400) |
|---|---|---|---|
| **One PDPL enforcement decision** | SAR 5,000,000 | **17.6 years** | **10.8 years** |
| One unbudgeted AI overrun on the 2026 pattern | SAR 550,000 | 1.9 years | 1.2 years |
| One stalled AI pilot | SAR 700,000 *(modelled)* | 2.5 years | 1.5 years |
| One avoided knowledge-worker hire | SAR 200,000 *(modelled)* | 0.7 years | 0.4 years |
| One quarter of programme delay from a failed cloud approval | SAR 300,000 *(modelled)* | 1.1 years | 0.6 years |

**The headline message:**

> **One PDPL finding costs SAR 5 million. Running an agent platform for three hundred employees,
> everything included, costs SAR 464,400 a year. One avoided finding pays for ten years of the
> whole company having agents.**

**And the discipline that makes it credible:** deliver this line only after the residency
architecture has been walked through, never before. Delivered first it sounds like fear selling.
Delivered after the CISO has traced the diagram with a finger, it is arithmetic.
