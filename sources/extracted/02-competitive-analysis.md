# Dashboard 02 — Competitive Market Analysis

**Wolffish Cloud · Kingdom of Saudi Arabia · v1.0 · 4 September 2026**
*Source skill Phase 2, steps 2.2 through 2.16, adapted. Research inputs in `00-RESEARCH-DOSSIER.md`.*

---

## ⚠️ Standing caveats for this dashboard

**C1 — Not SaaS.** The competitive set is not a category peer group. It is **four different kinds
of thing** that a Saudi buyer chooses between in one meeting: a bundled productivity assistant
(Microsoft), a frontier chat and agent cloud (OpenAI, Anthropic), a sovereign infrastructure and
model platform (HUMAIN), a services build (the SIs), a developer tool (Cursor and Copilot), and
free software plus internal effort (DIY). Comparing them on a single feature grid is only valid
because the *buyer* compares them that way, and every score below is a score of how each option
looks **from that buyer's chair**, not of engineering merit.

**C2 — No self-serve.** Competitors with a self-serve motion (Cursor, ChatGPT) can win a team
before procurement notices. Wolffish structurally cannot. Every competitive comparison here
assumes a committee, and where a competitor's advantage *is* bottom-up adoption, that is scored as
a real advantage, not dismissed.

**C3 — Landed cost, both sides.** Every price comparison in this dashboard is stated as landed
cost including the customer's own inference and infrastructure. Quoting SAR 79 against a
competitor's full seat price is a false comparison and is not made anywhere in this suite.

**C4 — Saudi only.** Competitive positions here are **as they exist in the Kingdom in September
2026**. Three of them have a shelf life: Microsoft's Saudi Arabia East region lands in Q4 2026;
AWS's region is committed but unlaunched; OpenAI has no Saudi data residency today but is
expanding the list. **The residency argument is a two-to-four-quarter window. The
no-vendor-data-path and on-device-execution arguments are not.** Positioning is built on the
second pair, deliberately.

**C5 — Offer metrics unreconciled.** Wolffish's own column is scored against the corrected offer
in `00-OFFER-METRICS-AUDIT.md`, not the raw Service and Offer Matrix. In particular, the
"ongoing capability development at no new invoice" advantage is scored on the allowance-bounded
version. Scored on the unbounded sheet version it would be higher, and undeliverable.

---

## Step 2.2 — Competitor summary

| Attribute | **Wolffish Cloud** | Microsoft 365 Copilot | OpenAI ChatGPT Enterprise | Anthropic Claude Enterprise |
|---|---|---|---|---|
| Website | wolffi.sh/cloud | microsoft.com/microsoft-365/copilot | openai.com/enterprise | anthropic.com/enterprise |
| Tagline | Your own agent platform, inside your own perimeter | The AI assistant for work, in the apps you already use | ChatGPT for your whole company | Claude for the enterprise, built for safety |
| Sub tag | One persistent agent per employee, on their machine, with permissions you set | Grounded in your Microsoft 365 data | Enterprise-grade security, privacy and control | Frontier intelligence with enterprise controls |
| Description | A custom-built agent platform deployed inside the customer's own infrastructure. Agents run on employee devices with real file and command permissions. Inference goes to a zero-retention endpoint on the customer's own account. Wolffish never receives customer data. SAR 60,000 deployment, SAR 79 per seat per month, inference and infrastructure billed direct to the customer. | A generative assistant embedded across Word, Excel, Outlook, Teams and SharePoint, grounded in Microsoft Graph, extended by Copilot Studio agents and Azure AI Foundry. Sold on existing enterprise agreements. Saudi Arabia East region announced for Q4 2026. | A multi-tenant enterprise workspace over frontier models with SSO, SCIM, IP allowlists, compliance export, a connector catalogue and, since 2026, ChatGPT Work with long-horizon autonomy and agentic browsing. Quote-only, reported ~150-seat minimum, annual prepay. | Frontier models plus Claude Code, sold as a low seat price with **zero bundled tokens**. All consumption billed at API rates. Enterprise spend controls shipped July 2026. |
| Strengths | No vendor-side data path at all. Agent executes on the device. Hard enforced quotas. Audit log in the customer's own store. Custom integration into bespoke and legacy systems. Saudi entity, SAR contracting, ZATCA invoicing, Arabic-first. Model-portable, including ALLaM. Founder-engineer delivery. Source access and escrow. | Ubiquity and incumbency. Existing agreements with nearly every large Saudi organisation. 88 percent satisfaction across 847 reviews. Reported 20 to 40 percent admin time savings. Integration breadth nothing else matches. Saudi entity and a Saudi cloud region landing Q4 2026. HUMAIN and ALLaM collaboration. | Brand recognition that shortens every internal conversation. Serious admin surface: SSO/SAML, SCIM, domain verification, IP allowlists, custom roles, compliance export. Broad connector catalogue. Hybrid and dedicated-instance modes since early 2026. | Best-in-class reasoning. Claude Code is the reference agentic coding harness. Very low seat price. Genuine engineering affection. |
| Weaknesses | Two-person company against trillion-dollar incumbents. No brand. No reference customers yet. Capacity ceiling of four to six deployments a year. Harness layer commoditising quarterly. Founder is the single point of delivery. | Chat inside documents, not an agent with device permissions. **Auditing and transparency named as a gap by its own reviewers.** Output accuracy complaints on formulas, grammar and summarisation. 10,240-character input ceiling. Weak with non-Microsoft and custom tooling. USD 30 per seat widely called high for the value. 80 percent of tenants found misconfigured in one security-review sample. | **No Saudi data residency.** Residency is live in the EU, UK, US, Canada, Japan, Korea, Singapore, India, Australia and the UAE — not the Kingdom. Quote-only with a seat floor that penalises sub-150-seat buyers. Credits layered on Enterprise since April 2026. Documented third-party integration and custom-GPT exposure. **OpenAI's own guidance points on-premises and air-gapped buyers at specialist vendors.** | **Cost is unforecastable by design.** Zero bundled tokens. Anthropic's own figures: USD 6 per developer-day average, USD 25 to 50 for autonomous workflows, over USD 300 at the extreme. Uber exhausted its 2026 AI budget by April. Microsoft cancelled most internal Claude Code licences. No Saudi entity, no Saudi residency, no Arabic-first product. |

| Attribute | HUMAIN | Saudi SI custom build (ejada · Elm · Solutions by stc · SITE) | Cursor + GitHub Copilot | DIY open-source in-house stack |
|---|---|---|---|---|
| Website | humain.ai | ejada.com · elm.sa · solutions.com.sa | cursor.com · github.com/features/copilot | openwebui.com · vllm.ai · openhands.dev |
| Tagline | Saudi Arabia's national AI champion | Your digital transformation partner in the Kingdom | The AI code editor / your AI pair programmer | Own the whole stack |
| Sub tag | Full-stack AI, from data centres to ALLaM to agents | 25 years delivering for Saudi enterprise and government | Built to make you extraordinarily productive | No licence, no vendor, no limits |
| Description | PIF-established May 2025 with Aramco holding a significant minority stake. Gigawatt-scale in-Kingdom data centres, the ALLaM Arabic frontier model, HUMAIN ONE and HUMAIN Chat, a HUMAIN OS agentic layer, and an enterprise AI agent marketplace with Turing. Partnerships spanning NVIDIA, AMD, AWS, Qualcomm, xAI, Groq and Microsoft. | The composite "our integrator will build it" alternative. Existing master agreements, Arabic delivery teams, government track record, local content credentials. ejada has an exclusive Dyna.Ai partnership for production call-centre agents; Elm is Tadawul-listed and PIF-owned with published GenAI case studies; Solutions by stc serves 25,000+ clients across 35 Saudi cities. | Repo-scoped developer agents. GitHub introduced pooled AI credits with overage billing in June 2026; Cursor bills usage on heavy features above the seat. | OpenWebUI or LibreChat over vLLM or a zero-retention API, orchestrated with n8n or LangGraph, coding agents from OpenHands, search from Onyx. All free, all self-hostable, all in-perimeter. |
| Strengths | Unassailable sovereign legitimacy and national mandate. Capital at a scale no one can match. ALLaM's Arabic quality. In-Kingdom hosting by definition. The politically safe answer for any government-adjacent buyer. Microsoft is taking ALLaM to its global platform. | Relationships that predate the buyer's current CIO. Existing frame agreements that avoid a new vendor onboarding entirely. Local content and Saudization credentials. Arabic delivery. Government references. Scale and balance sheet. | Real developer love and the fastest adoption path in the building. Bottom-up, no committee required. Proven agentic value that softens the ground for a company-wide programme. | Zero licence cost. Total sovereignty. A capable internal team can demo something in a fortnight. Exactly what an ambitious head of digital will propose in the meeting after Wolffish's pitch. |
| Weaknesses | Infrastructure, models and a marketplace — **not a deployed per-employee harness wired into one company's undocumented admin tool**. Large-programme engagement shape. Agent marketplace still maturing. Not a fit for a 300-person insurer that wants agents on desks next quarter. | **Time-and-materials economics that never end** — every new capability is a new quote, forever. No product to inherit improvements from. The harness is rebuilt per client. Staff churn. What is usually delivered is a chat interface over a RAG index, not an agent with file and command permissions. | Repo-scoped and developer-only. Touches no finance, legal, HR or operations desk. Metered above the seat. No company-wide governance story. Not a programme. | No enforced quota, no attributed action-level audit, no approval gates, no offboarding, no SLA, no roadmap. Two to four salaried engineers of permanent maintenance that never appears in the business case. **Fails the first NCA or SAMA review it meets.** |

---

## Step 2.3 — Core offering vectors, one word per bullet

- **Wolffish:** · perimeter · agent · quota · integration · audit · Saudi ·
- **Microsoft:** · ubiquity · documents · grounding · ecosystem · incumbency ·
- **OpenAI:** · frontier · brand · connectors · workspace · autonomy ·
- **Anthropic:** · reasoning · coding · safety · metered · developers ·
- **HUMAIN:** · sovereignty · compute · Arabic · national · scale ·
- **Saudi SI:** · relationships · delivery · localisation · projects · references ·
- **Cursor / Copilot:** · developers · speed · repository · adoption · seat ·
- **DIY stack:** · free · control · assembly · maintenance · improvisation ·

---

## Step 2.4 — Target audiences

| Company | Target audience #1 | Target audience #2 |
|---|---|---|
| **Wolffish** | Saudi regulated or IP-sensitive enterprises, 200 to 600 knowledge workers, whose CISO has already blocked a public AI tool on residency grounds | Saudi government-adjacent and PIF-portfolio entities holding NDMO-classified data that cannot leave the Kingdom under CCSPR |
| Microsoft | Existing Microsoft 365 E3 and E5 estates of any size, sold through the incumbent account team | Saudi public sector and large enterprise, via the Q4 2026 Saudi region and the HUMAIN and ALLaM collaboration |
| OpenAI | Mid-market and enterprise knowledge-work organisations of 150 seats and above, globally | Developer and technical teams via Codex, and now agentic knowledge work via ChatGPT Work |
| Anthropic | Engineering organisations adopting agentic coding at scale | Enterprises prioritising model safety and reasoning quality over cost predictability |
| HUMAIN | Saudi government, PIF portfolio companies and national-scale programmes | Global enterprises and developers wanting Arabic-first models and in-Kingdom compute |
| Saudi SI | Saudi government entities buying through Etimad and existing frame agreements | Large Saudi enterprises with an existing integrator relationship and an internal build preference |
| Cursor / Copilot | Individual software engineers, then their engineering managers | Engineering leadership standardising a per-developer tool |
| DIY stack | Technically ambitious internal platform and digital teams | Cost-constrained or sovereignty-constrained organisations with in-house capability and time |

---

## Step 2.5 — Value propositions by engagement level

Value proposition defined as what the product offers at its core, per level, in three to four words.

| Company | VP #1 — User level | VP #2 — Manager level | VP #3 — Decision maker level |
|---|---|---|---|
| **Wolffish** | An agent that acts | Work you can approve | Nothing leaves the building |
| Microsoft | Drafts in your apps | Faster team output | One vendor, one bill |
| OpenAI | The best assistant | Company-wide capability | Enterprise controls, known brand |
| Anthropic | The smartest model | Engineering throughput | Frontier quality, safety first |
| HUMAIN | Arabic that understands you | National-grade AI capacity | Sovereign by mandate |
| Saudi SI | Built for our process | Delivered by people we know | A partner, not a licence |
| Cursor / Copilot | Code much faster | Shipping velocity | Cheap per developer |
| DIY stack | Whatever we build | Total flexibility | No licence, no vendor |

---

## Step 2.6 — Feature extraction, as each company describes it

**Wolffish Cloud** — persistent per-employee agent on the employee's machine · file and command
permissions, gated · approval gates on sensitive operations · custom-built first-class
integrations to internal services, databases, bespoke admin and legacy systems · hard token quota
per user, team and period · action-level audit attributed to employee and timestamp, in the
customer's own store · kill switch per user and globally · SSO, directory and offboarding ·
per-role and per-agent scopes · branded single-tenant deployment · any open-weight model on any
zero-retention endpoint · inference on the customer's own account · deployment in one to two
weeks scoping and three to six weeks build with a pilot cohort · 99.5 percent uptime, P1 in four
hours, unlimited bug fixes · ongoing capability engineering · source access and escrow ·
Arabic-first interface and agents · data residency by architecture.

**Microsoft 365 Copilot** — Copilot in Word, Excel, PowerPoint, Outlook, Teams, Loop and OneNote ·
Microsoft Graph grounding · Copilot Chat · Copilot Studio custom agents · Copilot Pages · agent
mode in Office apps · Researcher and Analyst reasoning agents · Purview and Entra governance ·
Azure AI Foundry model catalogue · Saudi Arabia East region (Q4 2026) · ALLaM on the Microsoft
platform via HUMAIN.

**OpenAI ChatGPT Enterprise / Work** — GPT frontier models · unlimited higher-speed access ·
extended context · Advanced Data Analysis · connectors to Salesforce, ServiceNow, enterprise
relational and vector databases · custom GPTs and an app marketplace · Codex · agentic browsing ·
long-horizon autonomy · artifact production · admin console with custom roles · SSO/SAML, SCIM,
domain verification, IP allowlists · compliance and usage log export · SOC 2 · data residency in
ten territories, **not Saudi Arabia** · hybrid and dedicated-instance deployment.

**Anthropic Claude Enterprise** — frontier Claude models · Claude Code · Cowork · large context ·
projects and shared knowledge · SSO and SCIM · audit logs · admin spend limits and Enterprise
spend controls (July 2026) · MCP connectors · zero bundled tokens, all usage at API rates.

**HUMAIN** — ALLaM Arabic frontier model · HUMAIN ONE · HUMAIN Chat · HUMAIN OS agentic layer ·
gigawatt-scale in-Kingdom data centres · enterprise AI agent marketplace with Turing · model
evaluation, fine-tuning and reasoning services · partner silicon and cloud across NVIDIA, AMD,
AWS, Qualcomm, xAI and Groq · OpenAI open models deployed in-Kingdom with Groq.

**Saudi SI custom build** — bespoke RAG and knowledge assistants · call-centre and service agents
(ejada with Dyna.Ai) · digital government and identity services (Elm) · cloud, connectivity,
cybersecurity and systems integration (Solutions by stc) · in-Kingdom data centres (Center3) ·
managed services · local content and Saudization credentials · Etimad and frame-agreement access.

**Cursor + GitHub Copilot** — inline completion · agent mode · codebase-wide context · repository
scope · pull-request and review automation · Copilot CLI · pooled AI credits with overage
(June 2026) · usage billing on heavy features above the seat.

**DIY open-source stack** — OpenWebUI or LibreChat front end · vLLM or a zero-retention API ·
n8n or LangGraph orchestration · OpenHands coding agents · Onyx enterprise search · self-hosting
on any in-Kingdom region · no licence cost.

---

## Step 2.8 — Positioning vectors

**Deliberate deviation from the source skill.** The template specifies four vectors, two where
competitors lead and two derived from reversing their criticisms. **Five are used here.** The
added vector is *Sovereign Legitimacy and National Mandate*, and it is added because in the
Kingdom it decides deals. Omitting it would produce a map on which Wolffish looks stronger than
it is and then loses in a room where the question *"why not HUMAIN?"* is asked and unanswered.
A positioning map that flatters is worse than no map.

**Vectors 1 and 2** derive from what competitors are genuinely loved for.
**Vector 3** is Saudi-specific and competitor-led.
**Vectors 4 and 5** are the reversal of the dominant criticisms in the 2026 record: unforecastable
metered cost, and the combination of contractual-only residency, weak auditing and connector
menus that cannot reach internal systems.

| Positioning vector | **Wolffish** | Microsoft | OpenAI | Anthropic | HUMAIN | Saudi SI | Cursor/Copilot | DIY |
|---|---|---|---|---|---|---|---|---|
| **V1 · Frontier model capability** | 5.2 | 8.4 | 9.1 | **9.6** | 7.3 | 5.8 | 8.9 | 6.4 |
| **V2 · Ecosystem breadth and enterprise familiarity** | 2.6 | **9.7** | 8.2 | 6.9 | 6.1 | 7.8 | 5.4 | 3.2 |
| **V3 · Sovereign legitimacy and national mandate** | 6.8 | 5.9 | 3.4 | 2.7 | **9.8** | 8.6 | 1.9 | 7.1 |
| **V4 · Forecastable cost per employee** | **9.4** | 6.7 | 4.2 | 2.1 | 4.8 | 3.6 | 3.1 | 5.9 |
| **V5 · In-perimeter execution and custom system reach** | **9.6** | 3.8 | 2.9 | 4.3 | 5.2 | 7.4 | 3.7 | 6.8 |

### Reading the map honestly

- **Wolffish loses V1 and V2 and should stop trying to win them.** A 5.2 on model capability is
  correct — Wolffish runs open weights chosen for cost per token, not for benchmark position, and
  that is a deliberate trade. A 2.6 on ecosystem breadth is correct and will not improve. Any
  slide that argues these is a slide that invites the comparison Wolffish loses.
- **V3 is the vector Wolffish must neutralise rather than win.** 6.8 against HUMAIN's 9.8 is not
  a gap to close. It is a gap to make irrelevant, by making ALLaM on a HUMAIN or Groq in-Kingdom
  endpoint a supported inference option (feature `D8`). *"If you want the national model, we run
  on it"* converts the hardest objection in the Kingdom into a configuration line.
- **V4 and V5 are where Wolffish is not merely ahead but structurally ahead**, because closing
  either would require a competitor to abandon their own architecture or their own revenue model.
  Anthropic's July 2026 spend controls narrow V4 inside their cloud but cannot make the meter go
  away. Microsoft's Saudi region improves residency but does not put an agent on the employee's
  machine with file and shell permissions.
- **The nearest competitor on the two vectors that matter is the Saudi SI** — 3.6 and 7.4 — not
  any of the AI vendors. That is the single most consequential line in this dashboard, and
  Dashboard 03 and Dashboard 07 are built on it.

---

## Step 2.9 — Consolidated feature list

Merged to eighteen non-overlapping capabilities with no duplication across the eight products.

1. Agent executes on the employee's own device with file and command permissions
2. Multi-step autonomous task execution
3. Chat and retrieval over company documents
4. Approval gates and human-in-the-loop on sensitive actions
5. Arabic-first interface, prompting and document handling
6. Enforced hard spend or token cap, not alerting
7. Action-level audit log owned and stored by the customer
8. SSO, directory sync and automated offboarding
9. Custom integration into internal, bespoke and legacy systems
10. Model choice and portability across providers
11. In-perimeter deployment with no vendor-side data path
12. In-Kingdom data residency
13. Saudi legal entity, SAR contracting and ZATCA e-invoicing
14. Regulatory evidence pack: NCA ECC and CCC, NDMO, SAMA, CCSPR
15. Fixed, forecastable cost per employee
16. Vendor-independent continuity: source access or escrow
17. Deployment engineering and pilot rollout method included
18. Ongoing capability development without a new invoice

---

## Step 2.10 — Feature presence

**Deviation noted:** a third symbol, **◐ partial**, is used alongside ✓ and ✗. A binary grid would
have forced several genuinely partial positions into false claims in Wolffish's favour, which is
the failure mode this dashboard exists to prevent.

| # | Capability | **Wolffish** | MSFT | OpenAI | Anthropic | HUMAIN | Saudi SI | Cursor/Cop | DIY |
|---|---|---|---|---|---|---|---|---|---|
| 1 | Agent on the employee's device, file and command permissions | ✓ | ✗ | ◐ | ✓ | ✗ | ✗ | ◐ | ✓ |
| 2 | Multi-step autonomous execution | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ |
| 3 | Chat and retrieval over company documents | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✗ | ✓ |
| 4 | Approval gates on sensitive actions | ✓ | ✗ | ✗ | ◐ | ✗ | ✗ | ✗ | ✗ |
| 5 | Arabic-first interface and document handling | ✓ | ◐ | ◐ | ◐ | ✓ | ✓ | ✗ | ✗ |
| 6 | Enforced hard spend or token cap | ✓ | ✗ | ✗ | ◐ | ✗ | ✗ | ✗ | ✗ |
| 7 | Action-level audit log owned by the customer | ✓ | ✗ | ✗ | ✗ | ✗ | ✓ | ✗ | ✗ |
| 8 | SSO, directory sync, automated offboarding | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✗ |
| 9 | Custom integration into bespoke and legacy systems | ✓ | ✗ | ✗ | ✗ | ✗ | ✓ | ✗ | ✓ |
| 10 | Model choice and portability | ✓ | ◐ | ✗ | ✗ | ◐ | ✓ | ✗ | ✓ |
| 11 | In-perimeter, no vendor-side data path | ✓ | ✗ | ✗ | ✗ | ✗ | ✓ | ✗ | ✓ |
| 12 | In-Kingdom data residency | ✓ | ◐ | ✗ | ✗ | ✓ | ✓ | ✗ | ✓ |
| 13 | Saudi entity, SAR contracting, ZATCA e-invoicing | ✓ | ✓ | ✗ | ✗ | ✓ | ✓ | ✗ | n/a |
| 14 | Regulatory evidence pack, NCA / NDMO / SAMA / CCSPR | ✓ | ◐ | ✗ | ✗ | ✓ | ✓ | ✗ | ✗ |
| 15 | Fixed, forecastable cost per employee | ✓ | ◐ | ✗ | ✗ | ✗ | ✗ | ✗ | ◐ |
| 16 | Vendor-independent continuity, source or escrow | ✓ | ✗ | ✗ | ✗ | ✗ | ◐ | ✗ | ✓ |
| 17 | Deployment engineering and pilot method included | ✓ | ✗ | ✗ | ✗ | ✓ | ✓ | ✗ | ✗ |
| 18 | Ongoing capability development, no new invoice | ✓ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | n/a |

**Partial ratings explained.** OpenAI #1: Codex operates on code, not on the employee's general
file system with a shell. Cursor #1: real device execution, repository-scoped only.
Anthropic #4 and #6: Claude Code has permission prompts and Enterprise gained spend controls in
July 2026, but neither is an organisation-wide enforced cap set by an administrator.
Microsoft #5: Copilot handles Arabic, it is not an Arabic-first product. Microsoft #10: a
curated Azure Foundry menu, not arbitrary open weights on an arbitrary endpoint.
Microsoft #12: Saudi Arabia East is announced for Q4 2026, not live. Microsoft #14: Purview and
Entra artefacts exist; a Saudi-specific NCA, NDMO and CCSPR pack is partner-assembled.
Microsoft #15: the M365 Copilot seat is fixed; Copilot Studio consumption and Azure Foundry
usage are metered on top. HUMAIN #10: a broad but curated model estate. SI #16: contractual
deliverables can be escrowed but the platform is usually not a product to escrow.
DIY #15: no licence cost, but engineering headcount is the hidden variable and it is rarely
forecast.

**Two rows deserve a second look.** Row 7 and row 18 are the only rows where Wolffish's ✓ is
matched by exactly one competitor or by none. Row 7 is matched by the Saudi SI, and row 18 by
nobody. Those two rows are the shape of the whole competitive argument.

---

## Step 2.11 — Features rendered as benefits

Second and third-order effects from the customer's point of view.

| # | Capability | Benefit to the customer |
|---|---|---|
| 1 | Agent on the device with permissions | Work gets finished rather than drafted. The employee stops being the copy-paste layer between a chat box and their actual job. |
| 2 | Multi-step autonomous execution | A task that used to occupy an afternoon runs while its owner is in a meeting, and comes back with its working shown. |
| 3 | Chat and retrieval over documents | Institutional knowledge stops living in the heads of the four people who have been there longest. |
| 4 | Approval gates | The CISO can authorise real permissions without accepting unbounded risk, which is the only reason capability 1 is ever allowed to ship. |
| 5 | Arabic-first | Two thirds of the workforce stop being second-class users of their own company's tooling, and adoption stops being an English-fluency filter. |
| 6 | Enforced hard cap | The AI line becomes a number finance decides in advance instead of an invoice that arrives, so nobody has to ration the behaviour that creates the value. |
| 7 | Customer-owned audit log | When the regulator asks who did what with which data, the answer is in the company's own store and is produced the same day, not requested from a vendor. |
| 8 | SSO and offboarding | A leaver's access dies with their account, closing the single most common finding in a Saudi identity audit. |
| 9 | Custom internal integration | The systems that actually run the company — the bespoke admin tool, the twelve-year-old policy engine — become things an agent can operate, instead of the reason automation stops. |
| 10 | Model portability | When a better or cheaper open weight ships, it is a configuration change, not a migration project and not a renegotiation. |
| 11 | No vendor-side data path | The residency question stops being a contract to defend and becomes an architecture to point at, which shortens every security review that follows. |
| 12 | In-Kingdom residency | The deal is legally possible for a regulated buyer at all. |
| 13 | Saudi entity, SAR, ZATCA | Procurement processes the invoice as routine rather than as an exception, and legal does not have to import a foreign jurisdiction clause. |
| 14 | Regulatory evidence pack | The CISO stops being the obstacle to the project and becomes a co-author of its business case. |
| 15 | Fixed cost per employee | The CFO can put a number in next year's budget and be right, which is the difference between approval and deferral. |
| 16 | Source access and escrow | Procurement can approve a two-person supplier, because vendor failure stops being an unbounded risk and becomes a signed clause. |
| 17 | Deployment and pilot method | The organisation crosses from pilot to production, which is the exact place Saudi AI programmes are currently stalling. |
| 18 | Ongoing capability development | The second, third and fourth use case arrive without a new procurement cycle, which is where the SI relationship quietly becomes expensive. |

---

## Step 2.12 — Benefit potency

How powerfully each company delivers each benefit, one to five stars.

| # | Benefit | **Wolffish** | MSFT | OpenAI | Anthropic | HUMAIN | Saudi SI | Cursor/Cop | DIY |
|---|---|---|---|---|---|---|---|---|---|
| 1 | Work finished, not drafted | ★★★★★ | ★★☆☆☆ | ★★★☆☆ | ★★★★☆ | ★★☆☆☆ | ★★☆☆☆ | ★★★★☆ | ★★★☆☆ |
| 2 | Afternoon tasks run unattended | ★★★★☆ | ★★★☆☆ | ★★★★☆ | ★★★★★ | ★★★☆☆ | ★★☆☆☆ | ★★★★☆ | ★★★☆☆ |
| 3 | Institutional knowledge unlocked | ★★★☆☆ | ★★★★★ | ★★★★☆ | ★★★★☆ | ★★★☆☆ | ★★★★☆ | ★☆☆☆☆ | ★★★☆☆ |
| 4 | Real permissions, bounded risk | ★★★★★ | ★★☆☆☆ | ★★☆☆☆ | ★★★☆☆ | ★★☆☆☆ | ★★☆☆☆ | ★★☆☆☆ | ★☆☆☆☆ |
| 5 | Arabic-speaking staff fully served | ★★★★☆ | ★★★☆☆ | ★★★☆☆ | ★★★☆☆ | ★★★★★ | ★★★★☆ | ★☆☆☆☆ | ★★☆☆☆ |
| 6 | AI budget decided, not received | ★★★★★ | ★★★☆☆ | ★★☆☆☆ | ★☆☆☆☆ | ★★☆☆☆ | ★★☆☆☆ | ★★☆☆☆ | ★★★☆☆ |
| 7 | Regulator answered from your own store | ★★★★★ | ★★☆☆☆ | ★★★☆☆ | ★★★☆☆ | ★★★☆☆ | ★★★★☆ | ★☆☆☆☆ | ★★☆☆☆ |
| 8 | Leaver access dies cleanly | ★★★★☆ | ★★★★★ | ★★★★☆ | ★★★★☆ | ★★★★☆ | ★★★★☆ | ★★★☆☆ | ★☆☆☆☆ |
| 9 | Legacy and bespoke systems become operable | ★★★★★ | ★★☆☆☆ | ★★☆☆☆ | ★★☆☆☆ | ★★☆☆☆ | ★★★★☆ | ★☆☆☆☆ | ★★★☆☆ |
| 10 | Better model is a config change | ★★★★★ | ★★★☆☆ | ★☆☆☆☆ | ★☆☆☆☆ | ★★★☆☆ | ★★★★☆ | ★★☆☆☆ | ★★★★★ |
| 11 | Residency is architecture, not contract | ★★★★★ | ★★☆☆☆ | ★☆☆☆☆ | ★☆☆☆☆ | ★★★☆☆ | ★★★★☆ | ★☆☆☆☆ | ★★★★☆ |
| 12 | Legally possible for a regulated buyer | ★★★★★ | ★★★☆☆ | ★☆☆☆☆ | ★☆☆☆☆ | ★★★★★ | ★★★★★ | ★☆☆☆☆ | ★★★★☆ |
| 13 | Invoice processed as routine | ★★★★★ | ★★★★★ | ★☆☆☆☆ | ★☆☆☆☆ | ★★★★★ | ★★★★★ | ★☆☆☆☆ | ★★★★★ |
| 14 | CISO becomes co-author, not obstacle | ★★★★★ | ★★★☆☆ | ★★☆☆☆ | ★★☆☆☆ | ★★★★☆ | ★★★★☆ | ★☆☆☆☆ | ★☆☆☆☆ |
| 15 | Budget number that turns out to be right | ★★★★★ | ★★★☆☆ | ★★☆☆☆ | ★☆☆☆☆ | ★★☆☆☆ | ★★☆☆☆ | ★★☆☆☆ | ★★☆☆☆ |
| 16 | Small-supplier risk becomes a clause | ★★★★★ | ★★★★★ | ★★★★☆ | ★★★★☆ | ★★★★★ | ★★★★☆ | ★★★☆☆ | ★★★★★ |
| 17 | Pilot actually reaches production | ★★★★☆ | ★★☆☆☆ | ★★☆☆☆ | ★★☆☆☆ | ★★★☆☆ | ★★★★☆ | ★★★☆☆ | ★☆☆☆☆ |
| 18 | Use cases two to four arrive free | ★★★★☆ | ★★☆☆☆ | ★★☆☆☆ | ★★☆☆☆ | ★★☆☆☆ | ★☆☆☆☆ | ★★☆☆☆ | ★★☆☆☆ |

**Note on benefit 16.** Wolffish scores five stars on *small-supplier risk becomes a clause* not
because the risk is smaller — it is much larger — but because escrow and source access convert an
unbounded risk into a bounded, signed one. The large vendors score five stars because the risk
never arises. **Same score, entirely different mechanism, and sales must never blur the two.**

---

## Step 2.13 — Competitive advantage, three to four words

| Company | Competitive advantage |
|---|---|
| **Wolffish** | **No data path out** |
| Microsoft | Already inside everything |
| OpenAI | The default brand |
| Anthropic | Best reasoning available |
| HUMAIN | The national mandate |
| Saudi SI | Relationships and frame agreements |
| Cursor / Copilot | Developers already love it |
| DIY stack | No licence, total control |

---

## Step 2.14 — How each capitalises on it

| Company | Advantage | Explanation |
|---|---|---|
| **Wolffish** | No data path out | Every other claim in the pitch descends from one architectural decision: agents run on the employee's device and inference goes to the customer's own zero-retention endpoint, so no prompt, file or output can reach Wolffish. That fact removes the SDAIA transfer question entirely, produces a CCSPR-conformant answer for public-sector data, shortens the NCA evidence pack, and turns the CISO from the gate into the sponsor. Wolffish capitalises on it by leading every conversation with the security call rather than the demo — selling the absence of a risk before selling the presence of a capability. |
| Microsoft | Already inside everything | Copilot does not need to be chosen; it needs only to not be rejected. Microsoft capitalises through the existing enterprise agreement, bundling into renewals, an account team already in the building, and the Q4 2026 Saudi region plus the HUMAIN and ALLaM collaboration neutralising the two objections that used to stop it in the Kingdom. Its weakness is that incumbency wins the licence and rarely wins the *outcome*, which is why its own reviewers cite auditing gaps and price-to-value complaints. |
| OpenAI | The default brand | ChatGPT is the noun for AI, so an OpenAI proposal starts with the internal argument already half won and the board already comfortable. It capitalises through brand pull, connector breadth and, since 2026, agentic autonomy in ChatGPT Work. In Saudi Arabia the advantage is blunted by having no Kingdom residency and by its own guidance directing on-premises and air-gapped buyers elsewhere. |
| Anthropic | Best reasoning available | Anthropic wins the engineer's preference and lets that preference climb into procurement. It capitalises with a very low seat price to remove the entry barrier, then monetises consumption. That model produced the defining enterprise AI story of 2026 — Uber's budget exhausted by April, Microsoft cancelling internal licences — and the July 2026 spend controls are the admission. |
| HUMAIN | The national mandate | HUMAIN is the answer nobody is criticised for choosing. It capitalises through PIF and Aramco backing, in-Kingdom gigawatt compute, ALLaM's Arabic quality, and a partner web spanning NVIDIA, AMD, AWS, Qualcomm, xAI, Groq and Microsoft. Its limit is shape, not strength: it is infrastructure, models and a marketplace, so a 300-person insurer wanting agents on desks next quarter is not the customer it is built for. |
| Saudi SI | Relationships and frame agreements | The SI wins before the evaluation starts, because the work can be absorbed into an existing master agreement with no new vendor onboarding, no new security review and no new procurement event. It capitalises on relationship depth, local content credentials and government references. Its exposure is that time-and-materials economics never end, so the fifth use case costs as much as the first and the customer eventually notices. |
| Cursor / Copilot | Developers already love it | Bottom-up adoption bypasses the committee entirely. It capitalises on individual affection and expenses-level pricing, then converts to a team standard. It cannot become a company programme, because it never leaves the repository. |
| DIY stack | No licence, total control | It capitalises on a real internal desire for sovereignty and a real distaste for licence fees, and on the fact that a competent platform team can demo something in a fortnight. It survives until the first formal NCA or SAMA review asks for attributed action-level audit, enforced quotas and approval gates, none of which the assembled stack produces. |

---

## Step 2.15 — Category summary

**V1 · Frontier model capability**
**Leader: Anthropic (9.6).** Raw reasoning quality is what makes an engineer a champion, and
champions are what get a tool into a company before procurement has an opinion. Anthropic
acquires customers bottom-up through preference and then converts through consumption, which is
also why its acquisition efficiency is now colliding with its own invoice. For Wolffish this
vector is a **concession, not a contest**: openly concede model quality, then point out that
Wolffish runs any open weight on any zero-retention endpoint, so the model layer is a choice the
customer keeps rather than one the vendor makes for them.

**V2 · Ecosystem breadth and enterprise familiarity**
**Leader: Microsoft (9.7).** Microsoft acquires customers by not having to acquire them. The
Copilot line appears in a renewal that was happening anyway, sold by an account team that is
already in the building, into an estate that is already licensed. In the Kingdom this becomes
harder to counter from Q4 2026 when Saudi Arabia East goes live. The counter is not breadth —
it is depth: Copilot's own reviewers name **auditing and transparency** as the gap, and Copilot
does not put an agent on the employee's machine with file and command permissions.

**V3 · Sovereign legitimacy and national mandate**
**Leader: HUMAIN (9.8).** This vector does not exist in a Western GTM and it is decisive here.
HUMAIN acquires customers through alignment: choosing the PIF-backed national champion is a
decision nobody is criticised for, and for government-adjacent buyers it is close to the default.
**Wolffish's move is neutralisation, not competition.** Model portability makes ALLaM on a HUMAIN
or Groq in-Kingdom endpoint a supported configuration, which converts the objection into a
sentence: *"If you want the national model, we run on it."* Attempting to out-sovereign HUMAIN
is the fastest way to lose a Saudi deal, and it is what a generic GTM would attempt.

**V4 · Forecastable cost per employee**
**Leader: Wolffish (9.4).** The whole of 2026 built this vector for Wolffish: 78 percent of IT
leaders hit by unexpected consumption charges, 90 percent of CIOs naming cost forecasting as
their top deployment challenge, Uber's 2026 budget exhausted by April, Microsoft cancelling
internal Claude Code licences. Wolffish acquires customers here through the CFO, who is currently
the most under-served member of the AI buying committee and the one every competitor is talking
past. The hard quota plus inference on the customer's own account is not a discount, it is a
**different category of number** — a line finance decides rather than an invoice finance receives.
This vector has a shelf life measured in years, not decades, because vendors are building spend
controls. It should be spent now.

**V5 · In-perimeter execution and custom system reach**
**Leader: Wolffish (9.6).** This is the durable one. It is the reversal of three separate 2026
criticisms at once: residency that is contractual rather than architectural, auditing that the
vendor holds, and connector catalogues that cannot reach a company's own bespoke admin tool.
Wolffish acquires customers here through the CISO and the business owner of the internal system,
and it defends the position by architecture rather than by feature velocity: closing this gap
would require Microsoft, OpenAI or Anthropic to stop being multi-tenant clouds. **The real
contest on this vector is not with any AI vendor. It is with the Saudi systems integrator at
7.4**, and it is won on economics — a fixed seat with capability development included, against a
day rate that reappears for every new integration, forever.

---

## Step 2.16 — Positioning summary

Wolffish can lead this category in the Kingdom by concentrating everything on two vectors,
**forecastable cost per employee** and **in-perimeter execution with custom system reach**, and by
conceding the other three loudly enough that buyers trust the concession. Both winning vectors
resolve to a single architectural decision — agents execute on the employee's own machine, and
inference goes to a zero-retention endpoint on the customer's own account — which means neither
can be copied by a multi-tenant AI cloud without that cloud ceasing to be one. Customer
acquisition follows the same line: the entry point is not a demo but a security call and an
exposure audit, aimed at a CISO and a CFO who are both currently unserved by every other option
on the shortlist. That is a narrow door, and it is the reason a two-person company can be in a
room with Microsoft at all.

Market growth is bounded by delivery capacity rather than demand, which inverts the usual GTM
problem: at four to six deployments in the first twelve months, Wolffish needs roughly twenty
correctly chosen accounts, not a funnel. Defensibility is layered and should be read in order.
The harness layer is the weakest and is commoditising quarterly, so it must never carry the
positioning. The platform layer holds for perhaps two years before vendor spend controls close
the gap inside their own clouds. The service layer — first-class integrations into systems no
catalogue will ever reach, with ongoing capability development inside the seat — does not
commoditise, though it does not scale either. The Saudi layer is the most durable of all and the
least visible: a foreign competitor can build a better product in a quarter, but cannot acquire a
Saudi commercial registration, an RHQ-free procurement position, ZATCA invoicing, an architecture
with no cross-border transfer, and a founder who can answer an NCA question live, inside two
years. **The strategic instruction that follows is to spend the cost vector now while it is
open, and build the business on the perimeter and Saudi layers, which will still be there when
it closes.**
