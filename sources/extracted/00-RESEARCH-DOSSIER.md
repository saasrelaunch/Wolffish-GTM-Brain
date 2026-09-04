# Research Dossier — Steps 1.1, 2.1 and 2.7 executed in-session, plus the Saudi market file

**Version 1.0 · 4 September 2026**

The source skill marks three steps as "user executes externally" using Perplexity, Browse AI and
manual G2 reading. All three were executed inside this session against live sources on
4 September 2026. This file is the evidence base every downstream dashboard draws on. Where a
number is modelled rather than sourced, it says so.

## ⚠️ Standing caveats for this dossier

**C1 — Not SaaS.** Competitors are researched as four different kinds of thing a Saudi buyer
chooses between in one meeting: a bundled productivity assistant, frontier chat and agent clouds,
a sovereign infrastructure and model platform, a services build, a developer tool, and free
software plus internal effort. They are not category peers and are not researched as if they were.

**C2 — No self-serve.** Where a competitor's real advantage is bottom-up adoption that bypasses
procurement, that is recorded as a genuine advantage rather than discounted, because Wolffish
structurally cannot answer it.

**C3 — Landed cost, both sides.** Every competitor cost figure in Part 1.4 and Part 2 is stated on
the same basis as Wolffish's, including the customer's own inference and infrastructure.

**C4 — Saudi only, and it governs the whole method.** The source skill's three external research
steps lean on G2, Capterra, Trustpilot and Product Hunt, which carry almost no Saudi buyer signal.
Those corpora were used **only** for global product-quality themes. Every Saudi-specific claim in
this dossier is sourced instead to a Saudi regulatory instrument, a Saudi procurement rule, or
Saudi market reporting, and is listed at the end.

**C5 — Offer metrics unreconciled.** Wolffish's own position throughout is assessed against the
corrected offer stack in `00-OFFER-METRICS-AUDIT.md`, not against the raw Service and Offer Matrix.

---

# PART 1 — The Saudi regulatory and commercial file

This part has no equivalent in the source skill. In the Kingdom it outranks the product
comparison, because it decides which vendors are *permitted* before it decides which are *best*.

## 1.1 The data rules, and why they are an architecture argument rather than a policy argument

| Instrument | Regulator | What it actually requires | What it does to a vendor-cloud AI deal |
|---|---|---|---|
| **PDPL** (Royal Decree M/19, grace period ended 14 Sep 2024) | SDAIA | Personal data may leave the Kingdom only to an adequacy-listed country or under SDAIA-approved transfer mechanisms. **SDAIA has not published an adequacy list.** Fines to SAR 5m per breach, doubling on repeat. SDAIA issued 48 enforcement decisions in the year to early 2026. | Every prompt containing a customer name, an employee record or a patient identifier becomes a cross-border transfer question. The buyer's DPO must build and defend a transfer mechanism for a US vendor. |
| **NDMO National Data Governance policies** (data classification: Top Secret, Secret, Restricted/Confidential, Public) | SDAIA / NDMO | Classification drives storage location, encryption, access control, retention and **whether the dataset may leave the Kingdom at all**. Data-localisation authority moved here from NCA CCC in the 2024 revision. | Any dataset classified above Public needs a documented location argument. "The vendor contractually commits to residency" is a weaker artefact than "the data physically never moved." |
| **NCA ECC-2:2024 and CCC-2:2024** | National Cybersecurity Authority | Applies to government entities, their companies, and private-sector owners or operators of critical national infrastructure. CCC-1:2020's in-Kingdom delivery subcontrols were deleted in the 2024 revision and the localisation authority moved to NDMO. | The CISO still has to evidence controls over a third party that executes code against company data. An architecture with no vendor-side data path shortens that evidence pack dramatically. |
| **CST Cloud Computing Regulatory Framework / CCSPR** | Communications, Space & Technology Commission | CSPs register in four categories (Qualification, A, B, C) against customer-data levels 1 to 4. **Public-sector data may not be transferred outside the Kingdom for any purpose, permanently or temporarily, including caching or redundancy**, unless expressly allowed. | This is close to fatal for a foreign multi-tenant AI cloud selling to government or semi-government, because caching alone breaches it. |
| **SAMA Cyber Security Framework** | Saudi Central Bank | Prior SAMA approval is required **before using cloud services or signing the contract**, hybrid and public, **not conditioned on materiality**. Cloud is to be used in-Kingdom "in principle"; anything outside needs explicit SAMA approval. Material outsourcing needs SAMA non-objection under CSF 3.4.2.3(a). | For every bank, finance company, insurer and takaful operator in the Kingdom, a vendor-cloud AI rollout is a formal regulator-approval project measured in quarters. |

**The single most important derived fact in this whole dossier:** in Saudi Arabia the difference
between *contractual* residency and *architectural* residency is not a marketing nuance. It is
the difference between a compliance artefact the buyer has to defend and one they can simply
point at. Wolffish's SAR 79 seat is, from the CISO's chair, partly a purchase of a shorter
compliance argument.

## 1.2 The procurement rules, and the structural advantage of being Saudi

| Rule | Effect | Bearing on Wolffish |
|---|---|---|
| **RHQ programme** — since 1 Jan 2024 a foreign company without a MISA-licensed regional headquarters in the Kingdom cannot be awarded a central-government or state-entity contract above **SAR 1m**. 780+ companies held RHQ status by Q1 2026. | Bars most foreign AI vendors from the government and state-entity tier unless they have stood up a Riyadh RHQ with 15 FTE and three C-suite executives. | Wolffish is a Saudi entity. The barrier does not apply. Competitors selling direct from the US do not clear it. |
| **Local bidder price preference** — foreign bidders generally need to be materially cheaper than the nearest local competitor to win a government tender. | Systematically disadvantages a foreign-invoiced bid against a Saudi-invoiced one at comparable price. | Wolffish is on the favoured side of this by construction. |
| **LCGPA local-content weighting on IT services** — from **1 April 2027** for tenders at or above **SAR 10m**, extending to **SAR 5m from 1 January 2028**. Local-content weighting in financial evaluation must be **not less than 30 percent**. | Does not bind Wolffish deals directly, which land at SAR 250k to 800k. But it signals the direction of travel and it hurts foreign vendors chasing the large integrated AI programmes. | Use as a narrative accelerant with government-adjacent buyers, not as a claim about your own deal. |
| **Etimad** (portal.etimad.sa) — the unified Ministry of Finance platform for government tendering, contracting, payment and guarantees. | Any public-sector sale routes here. Registration, bid mechanics and the unwritten evaluation rhythm are a discipline of their own. | Treated in Dashboard 08 as a distinct channel with its own asset set, not as "outbound". |
| **ZATCA e-invoicing (Fatoora)** | Saudi buyers process a ZATCA-compliant SAR e-invoice from a Saudi CR holder as routine. A USD invoice from a foreign entity is an exception requiring extra treatment. | A quiet, real, rarely-articulated advantage. Named explicitly in the value proposition. |
| **Nitaqat / Saudization, 2026 to 2028 cycle** — technology employers face roughly 25 to 35 percent Saudi workforce thresholds by size; 30 percent Saudi nationals required across 46 accredited engineering professions for firms with five or more accredited engineers by 30 June 2026; profession-level quotas expanded to 269 roles; Yellow tier eliminated; credit tied to Qiwa digital contracts. | Constrains Wolffish's own delivery hiring as it scales past a handful of engineers. Also gives buyers a reason to prefer a Saudi supplier. | Appears in Dashboard 09 as a scaling constraint on the deployment business, and in Dashboard 04 as a buyer-side motivator. |

## 1.3 The demand file

| Signal | Figure | Source class |
|---|---|---|
| Saudi enterprises deploying industry-specific AI | **81 percent** | SAP KSA survey, Nov 2025 |
| Saudi organisations reporting AI initiatives meeting or exceeding expectations | **91 percent** (50 exceeding, 41 meeting) | SAP / YouGov, 260 chief IT decision-makers, Jun 2026 |
| Saudi respondents who participated in an AI pilot that delivered value | **71 percent** vs 66 percent globally | PwC Middle East |
| Saudi organisations prioritising AI investment strategically and enterprise-wide | **59 percent** | SAP / YouGov, Jun 2026 |
| Business-sector AI adoption, all sizes | **27.6 percent** (2024); ICT sector highest at 52.8, finance and insurance 44.7, education 42.1 | GASTAT |
| Middle East AI adoption vs global average | **75 percent**, above global | PwC |
| Tech investment announced at LEAP 2026 | circa **USD 15bn**, including a USD 1.2bn AI data-centre expansion | LEAP 2026 reporting |
| Saudi FY2026 state budget | **SAR 1,313bn** expenditure, SAR 1,147bn revenue, approved by Council of Ministers 2 Dec 2025 | Ministry of Finance |

**Reading:** the Saudi market is past the "why AI" conversation and into the "why *this* AI, and
will the regulator and the CFO both sign it" conversation. That is precisely the conversation
Wolffish is built to win, and precisely the one a generic feature-led GTM would waste its budget
trying to start again from awareness.

## 1.4 The cost-shock file — the strongest single narrative available to Wolffish in 2026

| Event | Detail |
|---|---|
| IT leaders hit with unexpected consumption-pricing charges in 2026 | **78 percent** |
| CIOs naming AI cost forecasting as their top deployment challenge | **90 percent** |
| Uber | Exhausted its **full 2026 AI budget by April** after deploying Claude Code across thousands of engineers |
| Microsoft | Cancelled most internal Claude Code licences and redirected engineers to GitHub Copilot CLI |
| Single reported enterprise | **USD 500m in one month** after enabling AI access without usage caps |
| Structural cause | An agentic coding task can consume on the order of **1,000x** the tokens of a single-turn query |
| Vendor response | Anthropic shipped Claude Enterprise spend controls in July 2026 — an admission that the problem is real, and a signal that the Layer B gap is closing inside vendor clouds |

## 1.5 The Saudi calendar — the thing a generic GTM will get most wrong

| Window | Status | Note |
|---|---|---|
| **LEAP 2026** | **31 Aug – 3 Sep 2026. Just closed, one day before this dossier.** RECC Malham, 200,000+ attendees, 1,800+ brands. Moved from its historic February slot. | Post-event follow-up window is open **right now** and closes fast. |
| **GAIN / Global AI Summit 2026** | **15–17 Sep 2026**, KAICC Riyadh, organised by SDAIA. **Eleven days out.** | The single highest-density room of Saudi AI decision-makers and regulators in the year. |
| **Black Hat MEA 2026** | **1–3 Dec 2026**, Riyadh, 14,000+ visitors, global and Saudi CISOs. | The CISO channel. Wolffish's buyer, in one hall. |
| **Saudi National Day** | 23 Sep | Short holiday. |
| **Budget cycle** | Pre-budget statement circa end Sep; Council of Ministers approval and final statement early Dec; fiscal year = calendar year. | **Oct to Dec is when next-year budget lines are argued.** Miss it and the money is allocated. |
| **Ramadan 1448** | circa **8 Feb – 8 Mar 2027**. Private-sector Muslim employees work a statutory maximum of **6 hours per day / 36 per week**. | Deals do not close. Discovery and relationship work continues, often better, in evening majlis hours. |
| **Eid al-Fitr 1448** | circa **9–12 Mar 2027**, four-day private-sector holiday | Dead zone. |
| **Eid al-Adha / Hajj** | circa late May 2027 | Dead zone. |
| **Summer** | Jul–Aug | Executive travel. Riyadh empties. Effectively a second dead zone. |

**Derived selling calendar for the next twelve months:**

- **Sep–Dec 2026 — the live window.** GAIN, budget season, Black Hat MEA. This is where the
  year is won. Roughly fourteen selling weeks.
- **Jan – early Feb 2027 — second window.** New budget released, pre-Ramadan urgency.
  Roughly five weeks.
- **Feb–Mar 2027 — Ramadan and Eid.** Relationship-building only. Do not forecast closes.
- **Apr–May 2027 — third window**, truncated by Eid al-Adha. Roughly six weeks.
- **Jun–Aug 2027 — summer.** Delivery and build, not selling.

A GTM plan that assumes twelve even months of pipeline in Saudi Arabia is wrong by roughly
forty percent of the year.

## 1.6 The infrastructure file

| Provider | Saudi region status as at Jul–Sep 2026 |
|---|---|
| Google Cloud | **Live** — Dammam (me-central2), sold through CNTXT as exclusive reseller for KSA-billed customers |
| Oracle | **Live** — Jeddah (me-jeddah-1, since 2020) and Riyadh (me-riyadh-1, since Oct 2024) |
| Huawei Cloud | **Live** — Riyadh |
| Alibaba Cloud (SCCC, JV with stc) | **Live** — Riyadh (me-central-1) |
| Tencent Cloud | **Live** — Riyadh |
| Microsoft Azure | **Announced, Q4 2026**, Saudi Arabia East, Eastern Province, three availability zones |
| AWS | USD 5.3bn committed Mar 2024, targeted 2026, **not launched as at Jul 2026** |

**Reading:** Wolffish's infrastructure line (relay, sync, audit store, object storage, no GPUs)
can sit on a live in-Kingdom region today on four different providers. Microsoft's Saudi region
arriving in Q4 2026 is the clock on the "Copilot cannot be resident here" argument, and that
argument should not be leaned on as a primary differentiator past Q1 2027. The durable arguments
are **no vendor-side data path at all** and **execution on the employee's own device** — neither
of which a Microsoft region changes.

---

# PART 2 — Step 1.1 and 2.1: the competitor file

Seven competitors, selected for who actually appears on a Saudi enterprise shortlist for
"give every employee an agent", not for who ranks in a global SaaS category.

## C1 · Microsoft 365 Copilot + Azure AI Foundry — *the incumbent*

- **Tagline in market:** the AI assistant built into the tools your company already runs on.
- **Why it is on every Saudi shortlist:** Microsoft has a full Saudi entity, existing enterprise
  agreements with nearly every large Saudi organisation, an Azure Saudi region landing Q4 2026,
  and a long-term ALLaM collaboration with HUMAIN announced in 2026. It is the default, and the
  default wins by not being evaluated.
- **Strengths from reviews:** 88 percent satisfaction across 847 reviews; reported 20 to 40
  percent reductions in administrative task time; unmatched breadth of integration across
  Microsoft 365; strong at summarisation and retrieval.
- **Weaknesses from reviews:** USD 30 per user per month described as high for the value
  delivered; imprecise generated scripts requiring validation; inaccurate output on
  summarisation, grammar and Excel formulas; complex spreadsheet analysis is weak; **lack of
  transparency and auditing features**; cannot search email or Teams messages on specific
  prompts; 10,240-character input ceiling; compatibility problems with non-Microsoft tools and
  custom SharePoint modules; 80 percent of tenants found misconfigured in one security-review
  vendor's sample.
- **Wolffish read:** Copilot is a *chat assistant inside documents*. It does not execute
  multi-step work with file and command permissions on the employee's machine, it does not reach
  an undocumented internal admin tool, and its auditing is the thing reviewers complain about.
  Do not fight it on ecosystem. Fight it on **what the agent is allowed to actually do**, and on
  **auditability**, which is its own users' stated complaint.

## C2 · OpenAI ChatGPT Enterprise / ChatGPT Work — *the brand*

- **Strengths:** SOC 2, end-to-end encryption, SSO/SAML, SCIM, IP allowlists, domain
  verification, custom roles, exportable usage and compliance logs; expanded native connectors
  (Salesforce, ServiceNow, enterprise RDBs, vector DBs); mature app ecosystem; ChatGPT Work
  adds connectors, long-horizon autonomy, artifact production and agentic browsing; hybrid and
  dedicated-instance deployment modes since early 2026.
- **Weaknesses:** quote-only pricing with a reported ~150-seat minimum and annual prepay;
  credits-based flexible pricing layered on Enterprise since April 2026 for heavy model use;
  outputs still require validation on technical, legal and financial decisions; documented
  vulnerabilities in third-party integrations and misconfigured custom GPTs with external API
  access; and, decisively for this market, **organisations with strict on-premises or air-gap
  requirements are advised to consider private model hosting or specialist vendors instead**.
- **Saudi position:** data residency is offered in Europe, UK, US, Canada, Japan, South Korea,
  Singapore, India, Australia and the UAE. **Saudi Arabia is not on that list.** The Saudi path
  runs through the HUMAIN and Groq deployment of OpenAI open models in-Kingdom, which is a
  different product from ChatGPT Enterprise.
- **Wolffish read:** OpenAI's own guidance points air-gapped and on-premises buyers at
  specialist vendors. In Saudi Arabia, under CCSPR and SAMA, a large share of the addressable
  buyer base *is* that buyer. Quote it.

## C3 · Anthropic Claude Enterprise + Claude Code — *the capability leader, and the cautionary tale*

- **Strengths:** frontier reasoning; Claude Code is the reference agentic coding harness;
  seat price cut to USD 20 technical and USD 10 business in 2026.
- **Weaknesses:** **zero bundled tokens** — every token in Claude, Claude Code and Cowork bills
  at API rates. Anthropic's own documentation puts the average Claude Code developer at USD 6
  per day, 90 percent under USD 12, autonomous agent workflows at USD 25 to 50, extreme users
  above USD 300. Uber burned its entire 2026 AI budget by April. Microsoft cancelled most
  internal Claude Code licences. Anthropic shipped Enterprise spend controls in July 2026 in
  response.
- **Wolffish read:** this is the most useful competitor Wolffish has, because the failure mode
  is public, documented, and CFO-legible. Do not attack the model quality; concede it. Attack
  the **invoice shape**. The line that lands: *on a metered plan, finance ends up rationing
  exactly the behaviour that creates the value.*

## C4 · HUMAIN — *the sovereign incumbent, and the hardest objection in the Kingdom*

- **What it is:** PIF-established (May 2025), with Aramco taking a significant minority stake.
  Gigawatt-scale data centres, the ALLaM Arabic frontier model, HUMAIN ONE and HUMAIN Chat, a
  HUMAIN OS agentic layer, partnerships across NVIDIA, AMD, AWS, Qualcomm, xAI, Groq and
  Microsoft, and, with Turing (Mar 2026), an enterprise AI agent marketplace. Microsoft is
  bringing ALLaM to its global platform. OpenAI open models are deployed in-Kingdom via HUMAIN
  and Groq.
- **Strengths:** unassailable sovereign legitimacy, national mandate, capital, Arabic-first
  model, in-Kingdom hosting, and the ability to be the safe political answer.
- **Weaknesses:** it is **infrastructure, models and a marketplace**, not a deployed harness on
  an individual employee's laptop wired into that company's own undocumented admin tool. It is
  a platform to build on, not a finished per-employee agent programme. Enterprise engagement is
  correspondingly large-programme shaped.
- **Wolffish read — and this is the most important competitive decision in this suite:**
  **do not compete with HUMAIN on sovereignty. You will lose, and you should.** Wolffish's model
  portability means ALLaM on a HUMAIN or Groq in-Kingdom endpoint is a *supported inference
  option*. Convert the biggest threat into a configuration line. The sentence is:
  *"If you want the national model, we run on it. Wolffish is the layer that puts it on every
  employee's machine with permissions, quotas and an audit log you own."*

## C5 · Saudi systems integrator custom build — *ejada, Elm, Solutions by stc, SITE* — *the real competitor in most deals*

- **What it is:** the composite alternative of "our SI will build it for us." ejada has 25+
  years in MEA and an exclusive partnership with Dyna.Ai for production AI agents across Saudi
  call centres. Elm is Tadawul-listed and PIF-owned with deep government e-services and
  published GenAI deployment case studies. Solutions by stc serves 25,000+ clients across 35
  Saudi cities. Center3 supplies the data-centre substrate.
- **Strengths:** existing master agreements, local content credentials, Arabic delivery teams,
  relationships that predate the buyer's current CIO, government track record, and the ability
  to absorb a project into an existing frame agreement without a new vendor onboarding.
- **Weaknesses:** time and materials economics — the customer pays for every capability, forever;
  no product to inherit improvements from; the harness is rebuilt per client; SI staff churn;
  and the delivered thing is usually a chat interface over a RAG index rather than an agent with
  file and command permissions.
- **Wolffish read:** this is where most Wolffish deals will actually be won or lost, not against
  OpenAI. The argument is **product economics versus project economics**: a fixed SAR 79 seat
  with ongoing capability development included, against an SI day rate that reappears every time
  a team wants a new integration. Escrow and source access neutralise the "but they are big and
  you are small" objection.

## C6 · Cursor + GitHub Copilot — *the developer wedge*

- **Strengths:** genuinely loved by engineers; fastest adoption path; bottom-up.
- **Weaknesses:** repo-scoped, developer-only, and metered. GitHub introduced pooled AI credits
  with overage billing in June 2026. Cursor bills usage on heavy features above the seat.
  Neither is a company-wide programme and neither touches the finance, legal, HR or operations
  desk.
- **Wolffish read:** not a displacement target. It is a **beachhead signal**. A company already
  paying for Cursor has proven agentic budget, an engineering champion, and a CFO who has
  already seen one metered AI invoice. Prospect on it.

## C7 · DIY open-source in-house stack — *the invisible competitor that kills deals quietly*

- **What it is:** OpenWebUI or LibreChat as the front end, vLLM or a ZDR API for inference,
  n8n or LangGraph for orchestration, OpenHands or an equivalent MIT-licensed coding agent,
  Onyx for search over the knowledge base. All free. All self-hostable. All in-perimeter.
- **Strengths:** zero licence cost; complete sovereignty; a smart internal team can demo
  something in a fortnight; and it is exactly what an ambitious Saudi head of digital will
  propose in the meeting *after* Wolffish's pitch.
- **Weaknesses:** no quota enforcement, no action-level audit attributed to an employee, no
  approval gates, no offboarding, no SLA, no roadmap, and a permanent internal maintenance
  burden that shows up as two to four salaried engineers. It is a demo, not a controlled
  programme, and it fails the first NCA or SAMA review it meets.
- **Wolffish read:** never dismiss it. Price it honestly — two mid-level Saudi engineers fully
  loaded is materially more per year than a 300-seat Wolffish deployment — and then move the
  argument to the artefacts a regulator asks for, which the DIY stack does not produce.

---

# PART 3 — Step 2.7: review-derived themes

The source skill asks for the top three positive themes from 4 and 5-star reviews and the top
three negative themes from 1 to 3-star reviews per competitor, with frequency counts. Verbatim
G2 frequency counts are not retrievable in-session and **no frequency numbers are invented
here**. What follows is the theme extraction with a qualitative frequency band and the evidence
class behind it. Frequency bands: **Dominant** (the headline theme in most summaries),
**Recurrent** (appears across multiple independent summaries), **Noted** (appears, but not
consistently).

| Competitor | Loved — themes from favourable reviews | Band | Disliked or wished for — themes from critical reviews | Band |
|---|---|---|---|---|
| **Microsoft 365 Copilot** | Integration breadth across M365; measurable admin time savings of 20–40 percent; strong summarisation and retrieval | Dominant / Recurrent / Recurrent | Price-to-value at USD 30 per seat; **transparency and auditing gaps**; inaccurate output on formulas, grammar and summarisation; cannot search mail or Teams on prompt; input length ceiling; poor fit with non-Microsoft and custom tooling | Dominant / **Recurrent** / Recurrent |
| **ChatGPT Enterprise** | Admin and compliance control surface; connector and app breadth; agentic autonomy in ChatGPT Work | Dominant / Recurrent / Noted | Quote-only pricing with seat minimum and annual prepay; credits layered on top since Apr 2026; integration and custom-GPT security exposure; **explicitly not the right answer for on-premises or air-gapped buyers** | Dominant / Recurrent / **Recurrent** |
| **Claude Enterprise / Claude Code** | Frontier reasoning quality; the reference agentic coding experience; low seat price | Dominant / Dominant / Noted | **Unforecastable metered cost** — the dominant theme of 2026 across enterprise commentary; zero bundled tokens; budget exhaustion at named enterprises; finance rationing usage | **Dominant** / Dominant / Recurrent |
| **Cursor / GitHub Copilot** | Developer affection; speed of adoption; low friction | Dominant / Dominant / Recurrent | Metered overage above the seat; repo-scoped, developer-only; no company-wide governance story | Recurrent / Dominant / Recurrent |
| **HUMAIN** | Sovereign legitimacy; Arabic-first model quality; national scale and capital | Dominant / Dominant / Dominant | Platform-and-infrastructure shaped rather than per-employee-programme shaped; large-programme engagement model; agent marketplace still maturing | Recurrent / Recurrent / Noted |
| **Saudi SI custom build** | Relationship depth; local content and delivery; existing frame agreements | Dominant / Dominant / Recurrent | Time-and-materials economics that never end; rebuilt per client; typically a RAG chat interface rather than a permissioned agent | Dominant / Recurrent / Recurrent |
| **DIY open-source stack** | Zero licence cost; total control; fast to demo | Dominant / Dominant / Recurrent | No quota enforcement, no attributed audit, no approval gates, no offboarding, no SLA; permanent internal maintenance load; fails formal regulatory review | Dominant / Dominant / Recurrent |

**Vector derivation.** Per the skill's rule, the first two positioning vectors come from what
competitors are loved for, and the remaining vectors are the reversal of what they are
criticised for. Applied here that yields:

1. *Frontier Model Capability* — they lead (Anthropic, OpenAI)
2. *Ecosystem Breadth and Enterprise Familiarity* — they lead (Microsoft)
3. *Sovereign Legitimacy and National Mandate* — they lead (HUMAIN). **A fifth vector added
   against the skill's four-vector template, because in the Kingdom this vector decides deals
   and omitting it would produce a positioning map that flatters Wolffish and loses in the room.**
4. *Forecastable Cost per Employee* — reversal of the dominant Claude and Copilot complaint.
   Wolffish leads.
5. *In-Perimeter Execution and Custom System Reach* — reversal of the residency, auditing and
   connector-menu complaints. Wolffish leads.

---

## Source list

Regulation and procurement: NCA CCC and ECC; SDAIA PDPL and the Aug 2024 Transfer Regulation;
SDAIA NDMO National Data Governance Interim Regulations; CST Cloud Computing Regulatory
Framework and CCSPR; SAMA Cyber Security Framework and Rules on Outsourcing; MISA RHQ programme;
LCGPA local-content announcements via SPA; Etimad; MHRSD Nitaqat 2026–2028 cycle; ZATCA Fatoora.

Market: SAP KSA Business AI surveys (Nov 2025, Jun 2026); PwC Middle East AI maturity; GASTAT AI
adoption; Saudi Ministry of Finance FY2026 Budget Statement; LEAP 2026, GAIN 2026 and Black Hat
MEA 2026 event reporting; Saudi cloud-region availability reporting.

Competitors: OpenAI product, pricing, data-residency and admin-control documentation; Anthropic
pricing and Claude Code usage documentation; Microsoft 365 Copilot review aggregation across G2,
Capterra, TrustRadius, Gartner Peer Insights and SelectHub; 2026 enterprise AI cost reporting
including the Uber and Microsoft Claude Code accounts; HUMAIN, ALLaM, Microsoft-HUMAIN and
HUMAIN-Turing announcements; ejada, Elm, Solutions by stc and Center3 company material;
self-hosted and open-source agent platform surveys.

Wolffish primary: `Wolffish-Business-Model-Pricing-and-Value-Prop.md` (Sept 2026) and
`Service_Offer_Matrix_Wolffish.xlsx`, both in this repository.
