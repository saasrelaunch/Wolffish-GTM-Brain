# Dashboard 01 — Product Feature Matrix

**Wolffish Cloud · Kingdom of Saudi Arabia · v1.0 · 4 September 2026**
*Source skill Phase 1, steps 1.2 through 1.7, adapted.*

---

## ⚠️ Standing caveats for this dashboard

**C1 — Not SaaS.** Every feature below carries a **Layer** tag: **A** agentic harness (runs on the
employee's machine), **B** platform control plane, **C** cloud service and engagement, **D** Saudi
regulatory and commercial fit. Demand and competitiveness mean different things in each layer and
**scores must not be averaged across layers**. Layer D has no equivalent in the source skill and is
scored on market structure, not on product capability.

**C2 — No self-serve.** No feature here is reachable by a free tier or a trial. Every one of them
arrives through a SAR 60,000 deployment. "Adoption" is a rollout, not an activation curve.

**C3 — Two of three price lines are not Wolffish revenue.** Nothing in this matrix should be read
as a feature the customer is paying SAR 79 for in isolation. The seat buys Layers A and B; the
SAR 60,000 buys Layer C; Layer D is free and is the reason the deal is allowed to exist.

**C4 — Saudi only.** Demand scores are calibrated against a Saudi regulated mid-market enterprise
of 200 to 600 knowledge workers. The same features scored against a US buyer would move by a wide
margin, most obviously across Layer D, where several would fall to zero.

**C5 — Offer metrics are self-rated and unreconciled.** Features `B1`, `B6` and `C8` absorb the
Ali-block "AI Agent Spend Governance Platform" and "Agent Spend Diagnostic" rows, per
`00-OFFER-METRICS-AUDIT.md` Finding 6. Feature `C3` carries the uncapped-cost defect in Finding 1
and is scored on the corrected, allowance-bounded version of the offer, not the sheet version.

---

## Step 1.2 — Demand and competitiveness

**Demand scale:** Wanted by one · Wanted by some · Wanted by most · Wanted by every client
**Competitiveness scale:** Commodity, should be free · Most vendors can · A few others can · Only we can

Competitors assessed: Microsoft 365 Copilot + Azure AI Foundry · OpenAI ChatGPT Enterprise ·
Anthropic Claude Enterprise + Claude Code · HUMAIN · Saudi SI custom build (ejada, Elm, Solutions
by stc, SITE) · Cursor + GitHub Copilot · DIY open-source in-house stack.

### Layer A — Agentic harness

| ID | Feature | Demand | Competitiveness |
|---|---|---|---|
| A1 | Persistent per-employee agent running on the employee's own machine | Wanted by every client | A few others can |
| A2 | Real file-system read and write on the device, scoped per role | Wanted by most | A few others can |
| A3 | Shell and command execution under per-role scopes | Wanted by some | A few others can |
| A4 | Multi-step autonomous execution: plan, run, read output, iterate | Wanted by most | Most vendors can |
| A5 | Approval gates on sensitive actions, human in the loop | Wanted by every client | A few others can |
| A6 | Local context ingestion — the employee's own files, never uploaded | Wanted by most | A few others can |
| A7 | Arabic-first agent: RTL interface, Arabic prompting and output, Arabic document handling, Hijri dates | Wanted by every client | A few others can |
| A8 | Model portability — any open-weight model on any zero-retention endpoint, switchable in a week | Wanted by some | A few others can |
| A9 | Conversational chat over company documents (RAG assistant) | Wanted by every client | Commodity, should be free |
| A10 | Prompt library and template gallery | Wanted by one | Most vendors can |
| A11 | Native mobile application for the agent | Wanted by some | Commodity, should be free ⚑ |

### Layer B — Platform and control plane

| ID | Feature | Demand | Competitiveness |
|---|---|---|---|
| B1 | Hard token quota per user, per team, per period — an enforced cap, not an alert | Wanted by most | A few others can |
| B2 | Action-level audit log in the customer's own store, attributed to employee and timestamp | Wanted by every client | A few others can |
| B3 | Kill switch, per user and global | Wanted by most | Most vendors can |
| B4 | SSO, directory sync and offboarding — the agent leaves when the employee does | Wanted by every client | Commodity, should be free |
| B5 | Admin console with per-role and per-agent permission scopes | Wanted by every client | Most vendors can |
| B6 | Spend visibility by team and by task | Wanted by most | A few others can |
| B7 | Zero vendor-side data path — no route exists for a prompt, file or output to reach Wolffish | Wanted by most | **Only we can** |
| B8 | Branded single-tenant deployment, no shared instance | Wanted by some | A few others can |
| B9 | Usage analytics: message counts, active users, adoption curves | Wanted by some | Commodity, should be free ⚑ |

### Layer C — Cloud service and engagement

| ID | Feature | Demand | Competitiveness |
|---|---|---|---|
| C1 | Deployment engineering: 1–2 weeks scoping, 3–6 weeks build, pilot cohort before company rollout | Wanted by every client | A few others can |
| C2 | First-class custom integrations into internal services, databases, bespoke admin and legacy systems | Wanted by most | **Only we can** |
| C3 | Ongoing capability development after go-live, inside the seat fee, bounded by a quarterly allowance | Wanted by every client | A few others can |
| C4 | 99.5 percent uptime SLA, P1 response within four hours, unlimited bug fixes | Wanted by every client | Most vendors can |
| C5 | Source access and escrow | Wanted by some | A few others can |
| C6 | Founder-engineer delivery — the person who wrote the platform designs the deployment | Wanted by some | **Only we can, network or track record** |
| C7 | Discovery and security call — straight answers to the CISO before anyone spends | Wanted by every client | A few others can |
| C8 | Agent Exposure and Spend Diagnostic — a one-week read of residency exposure and cost trajectory | Wanted by most | A few others can |

### Layer D — Saudi regulatory and commercial fit

| ID | Feature | Demand | Competitiveness |
|---|---|---|---|
| D1 | Saudi legal entity, SAR contract, ZATCA-compliant e-invoice, Saudi jurisdiction, Arabic contracting | Wanted by every client | A few others can |
| D2 | PDPL by architecture — personal data never crosses the border, so no SDAIA transfer mechanism is needed | Wanted by most | **Only we can** |
| D3 | NCA ECC and CCC control mapping plus NDMO data-classification evidence pack | Wanted by most | A few others can |
| D4 | SAMA CSF outsourcing and cloud-approval support pack for financial institutions | Wanted by some | A few others can |
| D5 | CCSPR conformity — no public-sector data leaves the Kingdom, caching and redundancy included | Wanted by some | **Only we can** |
| D6 | In-Kingdom Sunday-to-Thursday support hours and Arabic documentation | Wanted by every client | Most vendors can |
| D7 | No RHQ barrier; favourable local-bidder treatment in government procurement | Wanted by some | A few others can |
| D8 | ALLaM and HUMAIN in-Kingdom inference endpoints supported as model options | Wanted by some | A few others can |

⚑ = corrected during Step 1.5 validation. See below.

---

## Step 1.3 — Scatter plot scoring

Demand and competitiveness scored -20 to +20, with a definitive decimal distribution.
Demand is measured against the ICP defined in Dashboard 04: a Saudi regulated or IP-sensitive
enterprise with 200 to 600 knowledge workers. Competitiveness is measured against the seven-way
competitive set in `00-RESEARCH-DOSSIER.md` Part 2, **as it exists in the Kingdom**, not globally.

| ID | Feature | Layer | Demand score | Competitiveness score |
|---|---|---|---|---|
| A1 | Persistent per-employee agent on the employee's own machine | A | +17.4 | +6.8 |
| A2 | Real file-system read and write on the device | A | +12.6 | +9.6 |
| A3 | Shell and command execution under per-role scopes | A | -6.8 | +11.4 |
| A4 | Multi-step autonomous execution | A | +15.8 | -4.2 |
| A5 | Approval gates on sensitive actions | A | +14.9 | +8.9 |
| A6 | Local context ingestion, never uploaded | A | +13.5 | +10.7 |
| A7 | Arabic-first agent interface and output | A | +16.8 | +7.2 |
| A8 | Model portability across zero-retention endpoints | A | -3.4 | +15.3 |
| A9 | Conversational chat over company documents | A | +11.7 | -15.9 |
| A10 | Prompt library and template gallery | A | -10.8 | -17.3 |
| A11 | Native mobile application | A | -8.9 | -8.2 |
| B1 | Hard token quota, enforced cap | B | +14.7 | +14.1 |
| B2 | Action-level audit log in the customer's own store | B | +17.9 | +12.3 |
| B3 | Kill switch, per user and global | B | +11.2 | -2.8 |
| B4 | SSO, directory sync, offboarding | B | +18.3 | -13.7 |
| B5 | Admin console with per-role and per-agent scopes | B | +16.4 | -1.9 |
| B6 | Spend visibility by team and by task | B | +13.1 | +9.8 |
| B7 | Zero vendor-side data path | B | +15.6 | +19.2 |
| B8 | Branded single-tenant deployment | B | -2.7 | +12.7 |
| B9 | Usage analytics dashboard | B | -5.6 | -13.4 |
| C1 | Deployment engineering with pilot cohort | C | +17.1 | +11.8 |
| C2 | First-class custom integrations into internal systems | C | +16.9 | +18.4 |
| C3 | Ongoing capability development inside the seat fee | C | +15.3 | +15.7 |
| C4 | 99.5 percent SLA, P1 in four hours | C | +14.8 | -6.4 |
| C5 | Source access and escrow | C | -1.6 | +13.9 |
| C6 | Founder-engineer delivery | C | -4.9 | +17.6 |
| C7 | Discovery and security call | C | +16.2 | +8.4 |
| C8 | Agent Exposure and Spend Diagnostic | C | +12.4 | +7.9 |
| D1 | Saudi entity, SAR contract, ZATCA e-invoice, Arabic contracting | D | +18.7 | +9.3 |
| D2 | PDPL by architecture, no cross-border transfer | D | +17.6 | +19.6 |
| D3 | NCA ECC and CCC mapping, NDMO classification pack | D | +15.1 | +12.6 |
| D4 | SAMA CSF outsourcing and cloud-approval pack | D | +4.7 | +14.8 |
| D5 | CCSPR conformity for public-sector data | D | -7.3 | +18.1 |
| D6 | In-Kingdom support hours and Arabic documentation | D | +13.8 | -3.7 |
| D7 | No RHQ barrier, favourable local-bidder treatment | D | -8.6 | +15.2 |
| D8 | ALLaM and HUMAIN endpoints supported | D | -5.2 | +16.4 |

---

## Step 1.4 — Quadrant assignment

```
                          HIGH COMPETITIVENESS (+20)
                                    |
        QUADRANT 2                  |                 QUADRANT 1
      "Differentiators"             |               "Hero Features"
    Low demand, high advantage      |          High demand, high advantage
    A3 A8 B8 C5 C6 D5 D7 D8         |   A1 A2 A5 A6 A7 B1 B2 B6 B7
                                    |   C1 C2 C3 C7 C8 D1 D2 D3 D4
 LOW DEMAND -----------------------+----------------------- HIGH DEMAND
   (-20)                            |                          (+20)
        QUADRANT 3                  |                 QUADRANT 4
       "Commodities"                |               "Table Stakes"
    Low demand, low advantage       |          High demand, low advantage
    A10 A11 B9                      |   A4 A9 B3 B4 B5 C4 D6
                                    |
                          LOW COMPETITIVENESS (-20)
```

| Feature | Quadrant | Rationale |
|---|---|---|
| A1 Persistent per-employee agent on the machine | **Q1 Hero** | The category-defining claim. Everyone wants an agent; almost nobody puts one on the device with real permissions. |
| A2 File-system read and write on the device | **Q1 Hero** | The thing that makes A1 real rather than rhetorical. Claude Code and Cursor do it for a repository; Wolffish does it for a job. |
| A5 Approval gates on sensitive actions | **Q1 Hero** | The only reason a Saudi CISO will permit A2 and A3 at all. This feature is what converts a risk into a control. |
| A6 Local context ingestion, never uploaded | **Q1 Hero** | Structurally impossible for a vendor-cloud product to match, and directly answers the PDPL question. |
| A7 Arabic-first agent | **Q1 Hero** | HUMAIN leads on Arabic model quality; nobody leads on an Arabic-first *agent* with permissions. Genuine open ground. |
| B1 Hard token quota, enforced | **Q1 Hero** | The reversal of the dominant 2026 enterprise complaint. Anthropic shipped spend controls in July 2026, which validates demand and narrows the lead — treat as a two-year window, not a permanent moat. |
| B2 Action-level audit in the customer's own store | **Q1 Hero** | Copilot's own reviewers name auditing as a gap. Ownership of the log, not just its existence, is the differentiator. |
| B6 Spend visibility by team and task | **Q1 Hero** | Absorbs the Ali-block governance offer. Strong with the CFO, weak alone — it sells the diagnostic, not the platform. |
| B7 Zero vendor-side data path | **Q1 Hero** | The strongest single claim in the product, and the one competitors cannot answer without changing architecture. |
| C1 Deployment with pilot cohort | **Q1 Hero** | In a market that has run pilots and stalled at scale, arriving with a rollout method rather than a licence is the differentiator. |
| C2 First-class custom integrations | **Q1 Hero** | The gap the price tables cannot show. A connector reads your CRM; this writes to your bespoke admin tool. |
| C3 Ongoing capability development in the seat | **Q1 Hero** | Beats the SI on economics and the vendor on responsiveness. **Scored on the allowance-bounded version only** — see Finding 1. |
| C7 Discovery and security call | **Q1 Hero** | The entry offer. Under-rated in the source sheet; corrected here. |
| C8 Agent Exposure and Spend Diagnostic | **Q1 Hero** | The demand driver. See Step 1.6. |
| D1 Saudi entity, SAR contract, ZATCA e-invoice | **Q1 Hero** | Highest raw demand score in the matrix, and almost never articulated as a feature. Procurement's silent preference. |
| D2 PDPL by architecture | **Q1 Hero** | Highest combined score. SDAIA has published no adequacy list, so every competitor's transfer story is an argument and Wolffish's is an absence. |
| D3 NCA and NDMO evidence pack | **Q1 Hero** | Turns the CISO from a gatekeeper into a co-author of the business case. |
| D4 SAMA CSF pack | **Q1 Hero, marginal** | Demand is bimodal: near +18 inside financial services, near -12 outside. Blended to +4.7. **Treat as segment-specific, not general.** |
| A3 Shell and command execution | **Q2 Differentiator** | Buyers do not ask for this and are often frightened of it. Introduce it only after A5 has been established, never before. |
| A8 Model portability | **Q2 Differentiator** | Nobody asks. Everybody values it once vendor lock-in is named. A sales-conversation asset, not a demand generator. |
| B8 Branded single-tenant deployment | **Q2 Differentiator** | Low pull, real closing value with brand-conscious Saudi groups and family holdings. |
| C5 Source access and escrow | **Q2 Differentiator** | Removes a blocker rather than creating a want. Pre-package it, do not negotiate it. See Finding 3. |
| C6 Founder-engineer delivery | **Q2 Differentiator** | The strongest thing about the company and one buyers never request. Some read it as bus-factor risk, which escrow must answer. |
| D5 CCSPR conformity | **Q2 Differentiator** | Near-zero demand from private buyers, decisive for government-adjacent ones. Segment-gated. |
| D7 No RHQ barrier | **Q2 Differentiator** | Invisible until a competitor is disqualified by it. Then it is the whole deal. |
| D8 ALLaM and HUMAIN endpoints supported | **Q2 Differentiator** | Nobody asks for it. It exists to neutralise the single hardest objection in the Kingdom. See Dashboard 02. |
| A4 Multi-step autonomous execution | **Q4 Table stakes** | High demand, commoditising quarterly. Claim it, never lead with it. |
| A9 Chat over company documents | **Q4 Table stakes** | What buyers *think* they are buying. Free everywhere. Must be present, must not be the pitch. |
| B3 Kill switch | **Q4 Table stakes** | Expected. Its absence loses; its presence wins nothing. |
| B4 SSO, directory, offboarding | **Q4 Table stakes** | Highest table-stakes demand in the matrix. Absent, the deal dies at the identity review. |
| B5 Admin console with role scopes | **Q4 Table stakes** | Expected. Depth of scoping is where any advantage sits, not existence. |
| C4 SLA, P1 in four hours | **Q4 Table stakes** | Every SI offers it. Meaningful only because a two-person vendor offering it is unusual. |
| D6 In-Kingdom support and Arabic docs | **Q4 Table stakes** | **In Saudi Arabia this is table stakes, not a differentiator.** Every local SI has it. Rating it as an advantage is the most common mistake a foreign-authored GTM makes about this market. |
| A10 Prompt library | **Q3 Commodity** | Build only if a customer asks by name. Do not put it in a deck. |
| A11 Native mobile app | **Q3 Commodity** | Structurally awkward — the agent's value comes from executing on a machine with files and a shell. Say so plainly rather than roadmapping it. |
| B9 Usage analytics dashboard | **Q3 Commodity** | Message counts and active users are vanity. B6, spend by team and task, is the version that matters. |

---

## Step 1.5 — Entry validation

Rules applied:
1. If **Wanted by some** → exclude **Most vendors can do this**
2. If **Wanted by every client** → exclude **Only we can**
3. If **Wanted by one** → exclude **Commodity, should be free**

### Violations found and corrected

| ID | Original rating | Violation | Correction | Reasoning |
|---|---|---|---|---|
| **B9** Usage analytics | Wanted by some + Most vendors can | Rule 1 | → **Commodity, should be free** | If it is genuinely available from most vendors and only some clients want it, its true position is commodity. Correcting it moves B9 from a false Q2 to its real Q3 home and removes a feature from the deck that should never have been in one. |
| **A11** Mobile app | Wanted by some + Most vendors can | Rule 1 | → **Commodity, should be free** | Same logic. The correction is more useful than it looks: it turns "mobile is on the roadmap" into "mobile is not what this product is," which is the honest and stronger answer. |
| **D2** PDPL by architecture | *First instinct:* Wanted by every client + Only we can | Rule 2 | → **split into two claims** | See below. This is the most important validation outcome in the matrix. |
| **A10** Prompt library | *First instinct:* Wanted by one + Commodity, should be free | Rule 3 | → **Wanted by one + Most vendors can** | A prompt library is not free in the sense that it costs nothing to build; it is free in the sense that everybody ships one. "Most vendors can" is the accurate cell. |

### The D2 resolution, and where the rule breaks

Rule 2 exists to stop a team convincing itself that a universally demanded capability is
uniquely theirs. In Saudi Arabia the rule produces a false negative, because a **regulatory
constraint can be simultaneously universal and structurally unique** — every buyer needs a
cross-border answer, and only an architecture with no vendor-side data path gives one without a
transfer mechanism.

Rather than override the rule, the claim was split, which is both compliant and more precise:

| Split claim | Demand | Competitiveness | Where it lands |
|---|---|---|---|
| **"Data residency compliance in the Kingdom"** | Wanted by every client | A few others can | Q4 Table stakes. Microsoft, Oracle, Google and the SIs can all say this contractually. It wins nothing. |
| **"No cross-border transfer is possible, so no SDAIA transfer mechanism is required"** (`D2`) | Wanted by most | Only we can | Q1 Hero. This is the claim that survives a CISO's cross-examination. |

**Sales consequence, and it is a large one:** never say *"we are data-resident."* Every competitor
says that. Say *"there is no mechanism by which your data could leave, so you do not need a
transfer basis for it."* The first is a promise. The second is an architecture.

### Consistency checks passed

- No feature rated **Wanted by every client** also carries **Only we can** after correction.
- All four **Only we can** ratings (`B7`, `C2`, `C6`, `D5`) sit at **Wanted by most or some**, as the rules require.
- Layer D contains no **Commodity** ratings, which is correct: market structure is not a commodity, though it is invisible until tested.
- Layer A now contains three of the four commodity or table-stakes-negative ratings, which is the honest picture — **the harness layer is where Wolffish is least defensible and it is commoditising fastest.** Positioning must not rest there.

---

## Step 1.6 — Demand driver

**The Agent Exposure and Spend Audit.**

A one-week, founder-led read of an organisation's existing AI usage that produces two numbers no
Saudi executive can currently obtain, and that no competing product can fix.

| Attribute | Description |
|---|---|
| **What it is** | A one-week diagnostic across the organisation's sanctioned and unsanctioned AI usage. Output is a two-page brief: a **residency exposure map** and a **twelve-month cost trajectory**, both attributable by department. Delivered by the founder, not a template. |
| **Immediate value** | The CISO receives a shadow-AI inventory — which tools are in use, by which departments, carrying which data classes — that they have almost certainly been asked for and cannot presently produce. The CFO receives a forecast of AI spend twelve months out at observed adoption growth, expressed as landed cost per employee per month. Both are artefacts they are already accountable for. Both are useful whether or not Wolffish is ever bought. |
| **How it helps in problem identification** | It converts two abstractions into instrumented facts. "Some people probably paste customer data into ChatGPT" becomes "fourteen employees in Collections and Underwriting, carrying data your NDMO classification marks Confidential, with no SDAIA transfer basis on file." "AI is getting expensive" becomes "SAR 61 per employee per month today, SAR 240 by Q3 next year on current growth, unbudgeted." |
| **How it exposes the need for Wolffish** | Both findings are **structurally unfixable inside a vendor-cloud AI product**, and the audit says so without needing to sell. You cannot resolve cross-border exposure by buying a better ChatGPT tier, because the data path is the product. You cannot resolve cost trajectory on a metered plan, because the meter is the business model. The only two fixes that exist are **execution inside the perimeter** and **a hard enforced quota** — which is the definition of Wolffish. The audit does not argue for Wolffish. It describes a shape, and Wolffish is the only thing that fits it. |
| **ICP fit** | Ideal for ICP Level 1 (Dashboard 04): a Saudi regulated or IP-sensitive enterprise, 200 to 600 knowledge workers, with a named CISO and a CFO who has already seen one surprising AI invoice. Requires no procurement event to accept, which is exactly why it works in a market where procurement is the slowest gate. |
| **Leverage for conversion** | The audit's own deliverable is the business case for the deployment. The residency map becomes the risk section; the cost trajectory becomes the ROI baseline in Dashboard 09; the department breakdown becomes the pilot-cohort scope. Nothing has to be re-gathered. The proposal writes itself out of the diagnostic, and the customer has already agreed to the inputs. |
| **Top-of-funnel use case** | Offered free to a named target account as the reason for the first meeting, and delivered as a **self-assessment scorecard** at scale (Lead Magnet Specification). At GAIN and Black Hat MEA it is the booth conversation: *"Do you know how much of your data left the Kingdom this month, and what your AI bill looks like in twelve months? We will tell you in a week, free."* |

**Why this and not something else.** The two alternatives considered were a free pilot cohort
(too expensive against a four-to-six-deployment annual capacity ceiling, and it consumes the
principal before qualification) and an Arabic agent demo (impressive, but it demonstrates a
capability rather than revealing a problem, and it invites a feature comparison Wolffish does not
want in meeting one). The audit is the only option that satisfies both source-skill rules
simultaneously: it delivers standalone value, and the problem it uncovers has exactly one
category of solution.

---

## Step 1.7 — Demand driver variants

Positioned on two sliding scales: **perceived value and impact** (low to high) and **ease of
delivery** (hard to easy). The delivery-type taxonomy follows the source skill.

| # | Variant | Perceived value | Ease of delivery | Delivery type | Description | TOFU use case |
|---|---|---|---|---|---|---|
| 1 | **Kingdom AI Exposure Scorecard** | Medium | Easy | Self-assessment scorecard (ScoreApp) | 12 questions, 4 minutes, produces a Residency Exposure Score and a Cost Forecast Band with an Arabic and English result page benchmarked against Saudi peers. Full specification in `10-lead-magnet-spec.md`. | The scale play. GAIN and Black Hat MEA booth QR, LinkedIn, WhatsApp forward, partner newsletters. Only variant that works without founder time. |
| 2 | **Landed Cost Calculator** | Medium | Easy | Light tool | Public single-page calculator. Headcount and usage profile in; landed SAR per employee per month out, across Wolffish, ChatGPT Enterprise, Claude Enterprise and an SI build, with the three-line breakdown shown. | Pure top-of-funnel and a link that survives being forwarded to a CFO. Also the highest-utility artefact for a channel partner to send on Wolffish's behalf. |
| 3 | **Shadow AI Sweep** | Medium-high | Medium | Light tool plus async review | A structured questionnaire completed by IT plus a review of SaaS spend and egress logs, returned as a one-page exposure map. No live founder day required. | The second touch after the scorecard for accounts that scored high. Converts a score into a named list of departments. |
| 4 | **Agent Exposure and Spend Audit** | **High** | **Hard** | Service, white glove | The flagship, above. One week, founder-led, two-page brief, presented live to CISO and CFO together. | Reserved for the roughly twenty named target accounts in Dashboard 04. This is where principal time is deliberately spent. |
| 5 | **Residency One-Pager, built live** | High | Medium | Value using the software itself | A 90-minute working session in which the Wolffish agent runs against the customer's own policy and classification documents, on their machine, and produces their NCA ECC and PDPL mapping in front of them. The demo and the deliverable are the same artefact. | The strongest meeting-two asset. Proves A1, A2, A6, A7 and D3 simultaneously, and produces something the CISO keeps regardless of outcome. |
| 6 | **Pilot Cohort Sprint** | **Very high** | **Hard** | Service, white glove | Ten seats, three weeks, one real workflow, in the customer's perimeter, on their inference account. | **Not top of funnel.** Listed for completeness and explicitly reclassified as a bottom-of-funnel closing instrument in Dashboard 07 stage 4. Offering it early burns the capacity ceiling on unqualified accounts. |

### Variant strategy

Run **1 and 2 always** — they cost no principal time and they are the only two that scale against
a four-to-six-deployment capacity ceiling. Run **4 selectively**, against named accounts only,
and treat each one as consuming a week that could have been deployment. Run **5 as the standard
second meeting** once a security call has happened. Run **3** as the bridge for accounts that
scored high on 1 but do not yet justify 4. **Never lead with 6.**

**The governing constraint, restated:** Wolffish can deploy four to six customers in the next
twelve months (`00-OFFER-METRICS-AUDIT.md`, Finding 4). The demand driver's job is therefore not
to generate volume. It is to make the *right twenty accounts* raise their hand, and to give the
founder a reason to be in the room with a CISO and a CFO at the same time, holding a document
they asked for.
