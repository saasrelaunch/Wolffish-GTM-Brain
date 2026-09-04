# Dashboard 04 — Ideal Customer Profile

**Wolffish Cloud · Kingdom of Saudi Arabia · v1.0 · 4 September 2026**
*Source skill Phase 4, step 4.1, with eleven Saudi-specific attributes added, an anti-ICP, and a named-account target map.*

---

## ⚠️ Standing caveats for this dashboard

**C1 — Not SaaS.** The ICP is not defined by "who would get value from the product." It is defined
by **who can absorb a four-layer purchase**: a device-level harness their endpoint security team
must approve, a control plane their CISO must configure, a services engagement that consumes six
to eight weeks of the founder's time, and a Saudi regulatory posture that only matters if they are
regulated. An organisation can want the product intensely and still fail three of those four
tests.

**C2 — No self-serve.** There is no bottom-up path in. Every ICP attribute is therefore a
*committee* attribute, and "has an accessible single decision authority" is weighted as heavily
here as any firmographic.

**C3 — The 200-seat floor is a hard qualification gate, not a preference.** Wolffish year-1
revenue from one customer is SAR 60,000 + (SAR 948 × seats), while deployment consumes the same
six to eight weeks of principal time regardless of seat count. Below roughly 200 seats the
engagement cannot repay the principal time at any point in the contract. **Both ICP levels below
enforce this floor and it is the single most consequential number on this page.**

**C4 — Saudi only.** Eleven attributes below (regulator, data classification exposure, ownership
structure, procurement route, Saudization band, Arabic-English workforce mix, in-Kingdom entity
status, budget-cycle alignment, decision authority, wasta path, and AI posture) exist only in
this market. Remove them and this dashboard becomes generic and useless.

**C5 — Offer metrics unreconciled.** The engagement model assumes the corrected offer stack in
`00-OFFER-METRICS-AUDIT.md`: the Agent Exposure and Spend Audit as a co-equal entry offer, the
Compliance Evidence Pack as embedded and free, and escrow pre-packaged. If the review call
rejects those corrections, the engagement model rows change.

---

## Step 4.1 — Two-level ICP

| Attribute | **ICP Level 1 — MVP to PMF stage** | **ICP Level 2 — Growth stage** |
|---|---|---|
| **Segment** | Saudi-owned, regulated or IP-sensitive mid-market enterprise with a document-heavy back office and a named information security function | Regulated large enterprise and government-adjacent entities, including PIF portfolio companies, giga-project subsidiaries and semi-government authorities |
| **Sub-industries** | Insurance and takaful · finance companies and mid-tier banks · private healthcare groups · law firms and professional services · engineering, EPC and industrial · family holding groups with a shared services centre | Tier-one banks · large insurers · PIF portfolio and giga-project entities (housing, tourism, industrial cities) · semi-government authorities · large healthcare networks · telecom and utilities · national logistics and ports |
| **Location** | Riyadh first. Eastern Province (Dammam, Khobar, Dhahran) second — industrial, energy-adjacent and unusually receptive to on-device and on-premise architectures. Jeddah third. | Riyadh overwhelmingly. Giga-project entities headquartered in Riyadh regardless of where the project sits. NEOM and Red Sea Global entities treated as Riyadh-decisioned. |
| **Revenue** | SAR 300m to SAR 2bn | SAR 2bn and above, or a government-allocated budget rather than revenue |
| **Team size** | **200 to 600 knowledge workers.** Total headcount often 500 to 3,000; the knowledge-worker subset is the seat count and is what must clear the floor. | **600 to 2,500 knowledge workers**, deployed in phases by business unit rather than all at once |
| **Business maturity** | Established ten years or more. Has an ERP, a CISO or Head of Information Security, and has already run at least one digital transformation programme. **Has run an AI pilot that has not reached production** — this is the single strongest maturity signal. | Mature, with a formal enterprise architecture function, an internal audit function, and an existing AI or data strategy document that names Vision 2030 |
| **Business model** | B2C or B2B services with heavy document, policy, claim, contract, case or drawing workflows. Value is created by knowledge workers reading, writing and deciding, not by machines running. | Same, at scale, plus a regulatory reporting obligation and a public accountability surface |
| **Regulator** *(KSA)* | SAMA (insurers, takaful operators, finance companies, banks) · CST · NCA where critical infrastructure applies · SDAIA and NDMO for all personal data · CBAHI and MoH for healthcare | All of the above, plus CCSPR obligations on public-sector data, NCA ECC as a mandated framework rather than a best practice, and internal audit committee oversight |
| **Data classification exposure** *(KSA)* | Holds data that NDMO classification puts above Public: customer records, claims, medical records, employment files, contracts. Has no documented SDAIA transfer basis for any AI tool currently in use. | Holds NDMO **Restricted or Secret** data. Under CCSPR, public-sector data may not leave the Kingdom for any purpose including caching, which disqualifies most of the competitive set outright. |
| **Ownership structure** *(KSA)* | Family-owned group, closely held private company, or a Tadawul-listed company with a concentrated founding shareholder. **Ownership concentration is a speed attribute:** when the owner or chairman decides, procurement executes rather than deliberates. | PIF portfolio, government-owned, or widely-held listed. Slower, larger, and requires a documented evaluation trail rather than a decision. |
| **Business model fit** | Buys software as capability, not as licence. Has previously paid for a custom build. | Buys through frame agreements, panels and tenders. Has a supplier registration process. |
| **Best engagement model** | **Founder-led direct.** Security call → free Agent Exposure and Spend Audit → live residency one-pager session → pilot cohort of ten seats for three weeks → deployment. No channel, no reseller, no RFP. | **Channel-assisted or Etimad-routed.** Either a Saudi SI or managed service provider fronts the commercial relationship with Wolffish as the platform, or the entity buys direct through Etimad with the Compliance Evidence Pack pre-loaded. Longer, larger, lower margin, higher reference value. |
| **Procurement route** *(KSA)* | Direct purchase order under the owner's or CEO's signature authority. Legal review of a SAR-denominated Saudi-jurisdiction contract. ZATCA e-invoice processed as routine. Rarely a tender. | Etimad tender, framework call-off, or subcontract under an SI's prime agreement. Bank guarantee may be required. Local content documentation expected even below the SAR 10m LCGPA threshold. |
| **Decision authority** *(KSA)* | **One accessible person can say yes**: CEO, Managing Director, or the owner. This is a hard qualification criterion, not a nice-to-have. | A committee with a documented mandate, plus an internal sponsor senior enough to sequence it |
| **Saudization band** *(KSA)* | Platinum or high Green under the 2026–2028 Nitaqat cycle. Actively hiring Saudi knowledge workers and therefore acutely interested in output per head. | Platinum. Has a published Saudization commitment and a workforce development narrative that AI productivity fits inside. |
| **Arabic–English workforce mix** *(KSA)* | 50 to 80 percent of knowledge workers operate primarily in Arabic. **This is a demand multiplier, not a localisation detail:** an English-only AI tool has effectively been deployed to half the company. | Similar, with the added factor that Arabic is often the language of the regulatory submission itself |
| **Existing AI posture** *(KSA)* | Has blocked or restricted a public AI tool on data-residency or security grounds, and knows staff use it anyway. Or has bought Copilot licences and seen weak adoption. Or has run a pilot with an SI that has not scaled. | Has an AI strategy document, a named AI or data leader, an allocated budget line, and at least one visible programme that has not yet produced measurable output |
| **Organisation challenges and pain points** | • A shadow AI estate nobody has inventoried, carrying data with no transfer basis<br>• Public AI tools blocked, leaving staff with nothing sanctioned and productive<br>• One or more internal systems — a bespoke admin tool, a legacy policy engine — that every integration project has refused to touch<br>• A stalled pilot that demonstrated value and could not reach production<br>• Knowledge work that scales only by hiring, under Saudization cost and availability pressure<br>• A CISO who cannot approve what is happening and cannot stop it either<br>• A CFO who has been asked to forecast AI spend and cannot | • All of the above, plus a formal regulatory obligation with an audit date attached<br>• An enterprise architecture function that will not approve a new vendor cloud<br>• Multiple business units running uncoordinated AI experiments<br>• Board-level pressure to show AI outcomes against a Vision 2030 narrative<br>• Procurement cycles long enough that vendors churn before award |
| **Why they should choose Wolffish** | Because their two blocking constraints — data cannot leave, and cost cannot be forecast — are the two things Wolffish is architecturally built around, and because the systems that actually run their business can be reached by an agent for the first time. Because the supplier is Saudi, invoices in SAR through ZATCA, contracts under Saudi law in Arabic, and answers NCA and PDPL questions live on the first call. | All of the above, plus: no RHQ barrier, favourable local-bidder treatment, CCSPR conformity by architecture, and a per-employee cost that survives a finance committee's forecast challenge at 2,000 seats as well as it does at 300. |
| **Strategic goals Wolffish serves** | Raise output per knowledge worker without headcount, under Saudization economics · sanction AI usage rather than police it · produce evidence a regulator will accept · reach production, not another pilot · demonstrate Vision 2030 digital progress with something staff actually use daily | Enterprise-wide AI capability with defensible governance · measurable productivity attributable to named business units · a documented sovereign posture for board and regulator · consolidation of scattered departmental AI spend into one forecastable line |
| **Triggers** | 1. CISO has just blocked or restricted a public AI tool<br>2. A surprising AI invoice has reached the CFO<br>3. An AI pilot has stalled between demo and production<br>4. A new CDO, CAIO or Head of Information Security has been appointed in the last two quarters<br>5. A SAMA, NCA or internal audit finding naming AI or third-party data handling<br>6. A direct competitor has publicly announced an AI programme<br>7. Attendance at LEAP, GAIN or Black Hat MEA<br>8. Q4 budget-setting for the following calendar year<br>9. An acquisition or new business unit creating an integration estate nobody owns<br>10. A PDPL enquiry, complaint or SDAIA decision in their sector | 1. A published AI or digital strategy with an unspent budget line<br>2. A board or audit-committee question about AI governance<br>3. An Etimad tender in an adjacent category signalling budget<br>4. A regulatory deadline with a named date<br>5. A giga-project entity standing up a new corporate function from zero<br>6. An SI partner bringing Wolffish into an existing account<br>7. Vision 2030 milestone reporting cycles |

---

## Anti-ICP — who to decline, and why declining matters more than usual

With a ceiling of four to six deployments in the first twelve months, **a wrong customer does not
cost a lost deal. It costs a quarter of the year's delivery capacity.** These are decline
criteria, and they should be applied on the first call.

| Disqualifier | Why | What to say |
|---|---|---|
| **Fewer than 200 knowledge workers** | The engagement cannot repay the principal time at any point in the contract. | "At your size the deployment fee dominates the economics and you would be paying for a custom build, not a platform. Come back to us when you cross two hundred." |
| **No named information security owner** | Without a CISO there is nobody for whom the core value proposition is the core value proposition, and the security call has no audience. | "Who owns information security here? If nobody does, our strongest argument has no one to make it to." |
| **No accessible decision authority** | A committee with no sponsor plus a two-person supplier equals an eighteen-month cycle and no close. | "Who can sign a two hundred and fifty thousand riyal commitment without a tender?" |
| **Fully English-speaking workforce** | Halves the Arabic-first advantage and moves the buyer closer to Copilot's home ground. | Not a hard decline. Reprioritise below Arabic-heavy accounts. |
| **No internal or legacy system of consequence** | Removes the `C2` integration advantage — the one competitors cannot answer — and reduces the deal to a harness comparison Wolffish does not win. | "If everything you run is standard SaaS, Copilot's connector catalogue may genuinely serve you better than we would." |
| **Pure engineering organisation** | Cursor and Claude Code are better and cheaper for developer-only work, and saying so builds more credibility than the deal is worth. | "For a room of only engineers, Claude Code or Cursor is a better answer than we are." |
| **Wants a proof of concept before the security call** | Inverts the motion, spends principal time before qualification, and converts a differentiated sale into a feature bake-off. | "We do the security call first. If the architecture is not a fit, a demo just wastes both our weeks." |
| **Central-government tender above SAR 1m with no route in** | Requires Etimad mechanics, possible bank guarantees and a maturity Wolffish does not have in year one. | Defer to ICP Level 2 and a channel partner. Do not chase alone. |
| **Requires frontier model quality on every call** | Wrong architecture. Wolffish runs open weights chosen for cost per token. | "That is a real requirement and we are the wrong shape for it." |

---

## Named target map — the twenty accounts

The capacity ceiling means this GTM needs **twenty correctly chosen accounts, not a funnel**.
Archetypes below are sized to the ICP; the example organisations are named as *illustrations of
the archetype from public information*, not as qualified prospects or as claims about their
current systems, vendors or intentions.

| # | Archetype | Approx. seats | Why it fits | Primary trigger to watch | Priority |
|---|---|---|---|---|---|
| 1 | **Mid-tier takaful and insurance operator** *(e.g. the Walaa, Malath, Salama, Al Rajhi Takaful tier)* | 300–700 | SAMA-regulated so vendor cloud needs prior approval; claims, underwriting and policy documents are the entire job; Arabic-heavy; PDPL-exposed customer data | SAMA cloud approval friction; a claims-automation initiative | **A** |
| 2 | **Large health insurer** *(e.g. the Tawuniya, Bupa Arabia tier)* | 800–2,000 | Same as above at scale, plus medical data with the highest classification sensitivity in the private sector | Audit finding on third-party data handling | A |
| 3 | **Private hospital group** *(e.g. the Mouwasat, Dr Sulaiman Al Habib, Saudi German tier)* | 400–1,200 knowledge workers within a much larger total headcount | Patient data cannot leave the Kingdom; enormous documentation load; strong Arabic requirement; CBAHI and MoH oversight | New CIO or digital health programme | A |
| 4 | **Mid-tier bank or SAMA-licensed finance company** *(e.g. the Bank Aljazira, Alinma, Nayifat, Emkan tier)* | 500–2,500 | SAMA CSF makes any vendor-cloud AI a formal approval project; document-heavy credit, compliance and collections work | SAMA outsourcing review; a competitor's AI launch | **A** |
| 5 | **Saudi law firm or professional services firm** | 200–500 | Privilege and client confidentiality make a vendor data path close to unacceptable; billable-hour economics make agent leverage directly monetisable | A client mandate requiring a confidentiality attestation | A |
| 6 | **Family holding group with a shared services centre** *(e.g. the Olayan, Al Muhaidib, Alesayi, Al Fozan tier)* | 250–800 across the group | Concentrated ownership means a fast yes; a shared services centre is a natural pilot cohort; multiple bespoke internal systems | Owner or chairman attends LEAP or GAIN | **A** |
| 7 | **Engineering, EPC or industrial group** *(e.g. the Alfanar, Zamil, Nesma tier)* | 300–900 | Drawings, specifications, tenders and contracts are the work product; strong IP sensitivity; Eastern Province receptiveness to on-premise | A large tender programme; an IP incident | B |
| 8 | **PIF portfolio corporate function** *(e.g. the Roshn, NHC, Diriyah, Qiddiya tier)* | 400–1,500 | Standing up corporate functions from zero, budget available, Vision 2030 mandate, NDMO-classified data | A new corporate function being built | B |
| 9 | **Semi-government authority or regulator support entity** | 300–1,000 | CCSPR forbids public-sector data leaving the Kingdom including for caching, which disqualifies most competitors outright | Budget statement in December; a digital mandate | B (Etimad route) |
| 10 | **Logistics, ports and supply chain operator** | 250–700 | Documentation-heavy operations, Arabic-first workforce, and a national-infrastructure sensitivity that engages NCA | A NEOM, Red Sea or port expansion programme | B |
| 11 | **Telecom or utility subsidiary** | 600–2,500 | Critical national infrastructure brings NCA ECC into scope; large Arabic knowledge-worker base | An NCA compliance cycle | C |
| 12 | **Saudi SI or managed service provider as a channel partner** *(e.g. the ejada, NourNet, SITE tier)* | n/a — channel | Brings frame agreements, local content credentials and Etimad access that Wolffish does not have | A tender they cannot answer alone | **A (channel)** |

**Build the list to twenty by instantiating archetypes 1, 4, 5 and 6 three to four times each,
and archetypes 2, 3, 7 and 12 twice.** Those four A-priority archetypes share the two attributes
that matter most: a concentrated decision authority that can say yes without a tender, and a
regulator that makes the competitive set structurally difficult.

**Sequencing note.** Archetype 12, the channel partner, is rated priority A despite generating no
direct revenue, because a single SI relationship converts ICP Level 2 from a category Wolffish
cannot serve in year one into one it can serve in year two. Pursue one, not several.

---

## Seat-count economics by archetype

Why the 200-seat floor is not negotiable, shown rather than asserted.

| Seats | Wolffish year 1 | Wolffish year 2+ | Principal weeks consumed in year 1 | Verdict |
|---|---|---|---|---|
| 100 | SAR 154,800 | SAR 94,800 | 6–8 plus support | **Decline.** Deployment is 39 percent of year-1 revenue and year 2 alone does not justify the slot. |
| 200 | SAR 249,600 | SAR 189,600 | 6–8 plus support | **Floor.** Acceptable only with a strong reference or expansion path. |
| 300 | SAR 344,400 | SAR 284,400 | 6–8 plus support | **Target.** The model works. |
| 500 | SAR 534,000 | SAR 474,000 | 8–10 plus support | **Ideal.** Same principal cost, twice the annuity. |
| 1,000 | SAR 1,008,000 | SAR 948,000 | 10–14, phased | **ICP Level 2.** Needs phased rollout and probably a channel partner. |

**The instruction this table produces:** at a fixed deployment cost in the only currency that is
scarce — principal weeks — **seat count is the only variable worth optimising in qualification.**
Two 500-seat customers are worth more than five 200-seat customers and cost less than half the
delivery capacity.
