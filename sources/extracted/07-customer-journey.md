# Dashboard 07 — Customer Journey Funnel

**Wolffish Cloud · Kingdom of Saudi Arabia · v1.0 · 4 September 2026**
*Source skill Phase 7, step 7.1. Seven stages rebuilt for the Saudi enterprise motion, with stage durations mapped to the Saudi selling calendar.*

---

## ⚠️ Standing caveats for this dashboard

**C1 — Not SaaS.** The funnel has **no product-led stage**. There is no signup, no activation, no
PQL and no expansion-by-upgrade. Where a source-skill KPI assumed one, it is marked
`n/a — not a self-serve product` rather than invented. Stage 4 is a **paid pilot cohort inside the
customer's perimeter**, which is a delivery event consuming principal time, not a trial.

**C2 — No self-serve.** Conversion between every stage requires a human meeting. The funnel's
throughput is therefore bounded by founder calendar, not by traffic. Volume KPIs are deliberately
small and are correct at that size.

**C3 — The pass-through line is introduced at stage 3, unprompted.** A CFO who discovers it at
stage 4 will reopen stage 3.

**C4 — Saudi only.** Two structural changes from the source template. First, **the security call
moves from stage 3 to stage 2** — the CISO is engaged before the economic buyer, which inverts the
standard Western sequence and is the single most important process decision in this suite.
Second, **stage durations are given in the Saudi selling calendar**, in which roughly four months
of the year are not sellable. A twelve-month plan that assumes twelve selling months will miss by
about forty percent.

**C5 — Offer metrics unreconciled.** Stage 3 assumes escrow is pre-packaged rather than negotiated
(Finding 3) and that the Compliance Evidence Pack is embedded and free (Finding 6). Stage 6
assumes the capability allowance exists (Finding 1). If any of those are rejected on the review
call, the stage durations lengthen materially.

---

## Step 7.1 — Full funnel

| Funnel stage | Buyer mindset and trigger | Key questions they ask | Wolffish touch-points and assets (channel) | Internal goal / KPI | State after stage | Function |
|---|---|---|---|---|---|---|
| **1 · Problem awareness**<br>*2 to 8 weeks* | *"I know our people use ChatGPT. I do not know what they put in it, and I could not tell the auditor if asked."*<br><br>**Triggers:** a blocked tool · a surprising AI invoice · a stalled pilot · a new CISO or CDO · an audit finding · a competitor's announcement · GAIN or Black Hat attendance | • How much of our data has left the Kingdom?<br>• Do we have a transfer basis for any of it?<br>• What will AI cost us next year?<br>• Why did our pilot not scale? | • **Kingdom AI Exposure Scorecard** (ScoreApp, bilingual, QR at events)<br>• **Landed Cost Calculator** (web, forwardable)<br>• Founder's LinkedIn and X posts on PDPL, CCSPR and agent cost economics, in Arabic and English<br>• **GAIN, 15–17 Sep 2026** and **Black Hat MEA, 1–3 Dec 2026** — booth conversations and speaking slots<br>• Sector WhatsApp groups, via the sponsor, never cold | • 150 scorecard completions per quarter<br>• 40 percent of completions from ICP-matching organisations<br>• 12 qualified conversations per quarter<br>• `n/a — not a self-serve product`: signups, activation rate | The buyer has a number they did not have, and an uncomfortable one. They know their exposure is unmeasured and their forecast is missing. They do not yet know Wolffish is the answer. | Marketing |
| **2 · Solution discovery**<br>**and the security call**<br>*2 to 4 weeks* | *"I need to see whether this is architecturally real or another vendor promising residency."*<br><br>**Trigger:** a scorecard result above the threshold, or a warm introduction from the relationship sponsor | • Where exactly does our data go?<br>• What can the agent touch on an employee's machine?<br>• Who approves a sensitive action?<br>• Do you hold any of our credentials?<br>• What happens if you disappear? | • **Discovery and Security Call**, 30 minutes, founder-led, **with the security team in the room** — this is the pivotal asset in the entire funnel<br>• Residency architecture diagram, sent before the call<br>• Audit log schema<br>• Approval-gate configuration reference<br>• Escrow summary, pre-packaged, offered before it is asked for | • 60 percent of qualified conversations reach a security call<br>• 70 percent of security calls proceed to a diagnostic<br>• **Honest-decline rate above 15 percent** — a call that never says no is a call nobody believes<br>• Time from first contact to security call under 14 days | The CISO has either disqualified Wolffish, which is a good outcome delivered cheaply, or **has become the internal champion**. In the Kingdom the gatekeeper turned sponsor is worth more than any other conversion in this funnel. | Sales, founder-led |
| **3 · Vendor evaluation**<br>*4 to 10 weeks* | *"I believe the architecture. Now prove the economics, prove you can reach our systems, and give me something I can take to procurement."*<br><br>**Trigger:** the CISO asks to bring in the CFO or the CIO | • What is the real all-in cost per employee?<br>• Can you integrate with the system nobody will touch?<br>• Why not HUMAIN?<br>• Why not our integrator?<br>• Could we build this ourselves?<br>• Will our Arabic-speaking staff use it? | • **Agent Exposure and Spend Audit**, one week, founder-led, free, delivered live to CISO and CFO together<br>• **Residency One-Pager built live** — 90 minutes, the agent runs on the customer's own policy documents on their machine<br>• Three-line landed cost breakdown at their headcount, **pass-through volunteered**<br>• **Compliance Evidence Pack** — NCA ECC and CCC mapping, NDMO classification, PDPL architecture note, SAMA CSF annex where applicable<br>• Integration feasibility note on their named internal system<br>• Draft contract, Arabic and English, Saudi jurisdiction, plus CR, ZATCA registration and a sample e-invoice | • 50 percent of diagnostics reach a pilot proposal<br>• Audit delivered within 7 working days of scope agreement<br>• Compliance pack requires zero net-new work after the first build<br>• Integration feasibility answered inside 5 days<br>• Seat count confirmed above the **200-seat floor** before proposal | The buying committee is assembled and each member has been given the argument built for their chair. Procurement has a complete pack rather than a request. The "why not HUMAIN" and "why not our integrator" questions have been answered once, on the record. | Sales |
| **4 · Pilot cohort and purchase decision**<br>*6 to 12 weeks* | *"Show me ten of my own people using it on real work, then I will sign for the company."*<br><br>**Trigger:** the decision maker asks what a pilot would look like | • Which ten people, doing which workflow?<br>• What does success look like at week three?<br>• What does this cost if we stop?<br>• Who signs, and against which budget line? | • **Pilot Cohort Sprint** — 10 seats, 3 weeks, one named workflow, in their perimeter, on their inference account<br>• Cohort scope document agreed before start<br>• Baseline time measurement on the named workflow, taken before<br>• Week-3 pilot report with attributable numbers<br>• Arabic-first one-page onboarding for the cohort<br>• Deployment scope ladder and statement of work<br>• Pre-packaged escrow deed with named agent | • 70 percent of pilots convert to deployment<br>• 80 percent of the cohort still using the agent daily at week 3<br>• Measured improvement on the named workflow, stated as a number<br>• Contract signed within 6 weeks of pilot completion<br>• `n/a — not a self-serve product`: trial-to-paid conversion, free-tier upgrade rate | Signed. SAR 60,000 at signature, twelve-month term, quarterly in advance. **The customer has consumed a delivery slot: one of four to six available in the year.** | Sales into Delivery |
| **5 · Value realisation**<br>*6 to 8 weeks build, then 12 weeks* | *"We committed. Now make this real before anyone loses interest."*<br><br>**Trigger:** contract signature and the go-live payment milestone | • Is our internal system actually reachable?<br>• Are the Arabic-speaking teams using it?<br>• Is the quota holding?<br>• Can we produce an audit answer if asked today? | • Scoping, 1 to 2 weeks, on site<br>• Build, 3 to 6 weeks, with weekly demonstrations<br>• Pilot cohort expanded to first business unit<br>• Arabic-first enablement session per function<br>• Quota configuration workshop with finance<br>• First audit-query walkthrough with the CISO<br>• 99.5 percent uptime, P1 within four hours | • Go-live within 8 weeks of signature<br>• 60 percent of licensed seats active weekly by week 12<br>• At least 2 internal systems reachable by an agent at go-live<br>• Landed cost per employee within 10 percent of forecast<br>• CISO able to answer a sample audit query from their own store within one day | The platform is in production, not in pilot. The CISO has produced a real audit answer. The CFO has seen the first quarter's actual landed cost against the forecast. The reference conversation becomes possible. | Delivery, founder-led |
| **6 · Expansion and advocacy**<br>*Months 4 to 12* | *"This works for claims. What about underwriting, legal and procurement?"*<br><br>**Trigger:** a second department asks for access | • Can we add another business unit?<br>• Can the agent reach system number three?<br>• What does another 200 seats cost?<br>• Will you speak to our peers? | • Quarterly capability review against the **capability allowance**<br>• Seat expansion pricing, pre-agreed at deployment<br>• New integration scoping inside the quarter<br>• Named public reference and a quotable sentence<br>• CISO-to-CISO reference call<br>• Anonymised deployment write-up<br>• Joint session at GAIN or Black Hat MEA the following year | • Seats grow 40 percent by month 12<br>• At least 2 new capabilities shipped within the allowance<br>• 1 referenceable peer introduction per customer<br>• 1 CISO-to-CISO call per quarter<br>• **Capability allowance consumption tracked and reported** — the Finding 1 control | Account is expanding, the reference base exists, and peer introductions are arriving. **In a market this relationship-dense, this stage produces more qualified pipeline than all of stage 1.** | Delivery and Marketing |
| **7 · Renewal and loyalty**<br>*Month 10 to 12, then annually* | *"Is this still the right architecture, and is the number still the number?"*<br><br>**Trigger:** the twelve-month term approaching, and the Q4 budget cycle | • Did the cost hold against forecast?<br>• Is the model still the right one?<br>• What did we get for the capability allowance?<br>• Should we expand to the whole company? | • Annual landed-cost review against original forecast<br>• Model refresh proposal — switching to a better open weight is a configuration change<br>• Capability allowance report for the year<br>• Multi-year term with price protection<br>• Renewal timed to land **before the December budget statement**, not after | • 90 percent logo retention<br>• 120 percent net revenue retention through seat expansion<br>• Renewal agreed before the Q4 budget cycle closes<br>• Zero escrow invocations, stated in every subsequent security call<br>• `n/a — not a self-serve product`: churn-by-non-renewal-of-credit-card | Multi-year, expanded, and referenceable. The customer is now a channel: their CISO is in the same WhatsApp groups as the next four prospects. | Delivery and Product |

---

## Stage durations against the Saudi selling calendar

Total realistic cycle from first contact to signature: **16 to 34 weeks.** Add six to eight weeks
to go-live. **But calendar weeks are not selling weeks in the Kingdom.**

| Period | Selling status | Practical instruction |
|---|---|---|
| **Sep–Dec 2026** | **Live window, ~14 weeks.** GAIN (15–17 Sep), Black Hat MEA (1–3 Dec), and the budget cycle that culminates in the December budget statement. | This is where the year is won. Everything in stages 1 to 3 should be compressed into it. |
| **Jan – early Feb 2027** | **Second window, ~5 weeks.** New fiscal-year budget released. | Close what stage 4 started in Q4. |
| **8 Feb – 8 Mar 2027 (Ramadan)** | **Not sellable.** Statutory 6-hour working day. | Relationship work only, often in evening hours. **Do not forecast a close here.** Use the period for delivery, content and the Compliance Evidence Pack. |
| **9–12 Mar 2027 (Eid al-Fitr)** | **Dead.** | Nothing. |
| **Mar–May 2027** | **Third window, ~6 weeks**, truncated by Eid al-Adha in late May. | New pipeline generation for the following Q4. |
| **Jun–Aug 2027** | **Not sellable.** Executive travel, Riyadh empties. | Build and deliver. This is when deployments should run. |

**Consequence for forecasting:** roughly **25 sellable weeks in a twelve-month period**, not 48.
A four-to-six-deployment year is therefore not conservative. It is what 25 selling weeks and a
16-to-34-week cycle actually produce, and the deployment capacity ceiling and the calendar ceiling
happen to land in the same place, which is a coincidence worth noticing but not relying on.

---

## Key journey insights

### Critical success factors

1. **The security call must come before the economic conversation.** In every other market the
   sequence is buyer first, security later. Here, the CISO holds a real veto, and in
   SAMA-regulated entities a formal one, so engaging them first converts the largest risk in the
   funnel into its most credible internal advocate. This single re-ordering is the highest-leverage
   process decision in the suite.
2. **The relationship sponsor must be mapped before any outreach.** A deal that arrives through a
   trusted introduction starts at trust and negotiates price. A deal that arrives cold starts at
   suspicion and spends two quarters negotiating trust, if it survives at all.
3. **Every artefact ships bilingual, with Arabic primary in Arabic-first rooms.** Making the
   Arabic-first claim in an English-only document is a self-inflicted contradiction the buyer
   will notice.
4. **The honest decline is a conversion instrument.** Declining above fifteen percent of security
   calls is a target, not an accident. In a network where CISOs talk to each other constantly, the
   vendor who said "we are not a fit" is the one who gets called next time.

### Primary journey blockers

1. **"Why not HUMAIN?"** — arrives at stage 3 in almost every deal. Unanswered it is fatal;
   answered in one sentence with model portability it disappears. It must be pre-empted in the
   security call, not defended in the evaluation.
2. **Two-person supplier risk** — surfaces at stage 3 with procurement and legal, and again at
   stage 7 with internal audit. Pre-packaged escrow with a named agent converts it from an open
   risk into a signed clause. Negotiated escrow makes it the longest pole in the deal.
3. **The internal build proposal** — appears at stage 3, usually after Wolffish leaves the room,
   proposed by an ambitious head of digital. It is defeated by pricing the maintenance headcount
   honestly and by asking what the open-source stack produces when the NCA reviewer asks for
   attributed action-level audit and enforced quotas.
4. **Fiscal-year timing** — a deal that reaches stage 4 in February waits for the following
   January. The budget statement lands in early December and the fiscal year is the calendar year,
   so a deal that has not reached stage 3 by October is a next-year deal, and should be managed as
   one rather than forecast as this year's.

### Acceleration opportunities

1. **Run stage 3 during GAIN and Black Hat MEA rather than around them.** Both events put the
   CISO, the CIO and often the decision maker in the same building for three days. A security
   call, a live residency session and a CFO conversation can compress from six weeks to three days.
   **GAIN is 11 days away as of this document's date.**
2. **Convert stage 6 into stage 1 for the next account.** A CISO-to-CISO reference call in a market
   this relationship-dense produces better-qualified pipeline than any amount of content. Budget it
   as a marketing channel, because it is one.
3. **Build the Compliance Evidence Pack once and reuse it entirely.** It is the largest single
   time cost in the first deal and near-zero in every subsequent one, which means the second
   deal's stage 3 is materially shorter than the first's. Front-load it deliberately.
4. **Time renewals and expansions to land before the December budget statement.** A seat expansion
   proposed in November enters next year's budget. The same proposal in January competes with an
   allocated one.
