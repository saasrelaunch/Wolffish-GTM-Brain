# Dashboard 08 — Assets and Collaterals Library

**Wolffish Cloud · Kingdom of Saudi Arabia · v1.0 · 4 September 2026**
*Source skill Phase 8, step 8.1. **The channel set has been replaced, not extended.** Rationale below.*

---

## ⚠️ Standing caveats for this dashboard

**C1 — Not SaaS.** Assets are grouped by **which layer they defend**, because a four-layer product
needs four kinds of proof. A residency architecture diagram and a landed-cost calculator are not
variants of the same asset; they are addressed to different people who will never read each
other's.

**C2 — No self-serve.** Every asset ends in a conversation, a document or a diagnostic. **None
ends in a signup.** Assets whose only function would be to drive self-serve traffic are not built.

**C3 — Landed cost.** The Landed Cost Calculator shows all three lines by default, with the
pass-through named and attributed. Building a version that shows SAR 79 alone would be the single
most damaging asset in this library.

**C4 — Saudi only, and this is where the source skill fails hardest.**

> The source skill prescribes three channels: **LinkedIn outreach automation via HeyReach**,
> **cold email via Instantly**, and **LinkedIn Ads**. For a two-person Saudi vendor selling a
> SAR 250,000-plus committee purchase to twenty named accounts, that is close to the **worst
> available channel mix in this market**, and it is not extended below. It is replaced.
>
> **Why each fails here.** Automated LinkedIn sequencing to a Saudi CISO or CEO reads as
> disrespect in a business culture built on personal introduction, and it burns the founder's own
> profile — the single most valuable asset the company has. Cold email into Saudi enterprise has
> negligible response even before considering that senior Saudi executives conduct real business
> on WhatsApp and in person, with email as a confirmation medium rather than a conversation one.
> LinkedIn Ads optimise for volume against a total addressable market of roughly twenty accounts,
> where the entire annual budget could be spent reaching people who cannot buy. **All three are
> volume instruments deployed against a capacity ceiling of four to six deployments a year.**
>
> The replacement channels below are ordered by expected yield in the Kingdom, and the ordering
> is itself the recommendation.

**C5 — Offer metrics unreconciled.** The Compliance Evidence Pack and the Agent Exposure and Spend
Audit are the two highest-effort assets here, and both derive from the corrected offer stack in
`00-OFFER-METRICS-AUDIT.md`. Neither exists in the source Service and Offer Matrix.

---

## The Saudi channel set

| # | Channel | Why it works here | Expected share of qualified pipeline |
|---|---|---|---|
| 1 | **Events and physical presence** — GAIN (15–17 Sep 2026), Black Hat MEA (1–3 Dec 2026), LEAP (Aug–Sep), sector and CISO forums | Puts the CISO, CIO and decision maker in the same building for three days. In a relationship-first market, three days of face-to-face is worth six months of digital. | **35 percent** |
| 2 | **Warm introduction and the sponsor network** | A deal that arrives through a trusted introduction starts at trust. This is not a soft channel; it is the primary one, and it is the reason the target map is twenty named accounts rather than a list. | **30 percent** |
| 3 | **Founder-led organic LinkedIn and X, bilingual** | Saudi executives read LinkedIn in English and X in Arabic. A founder posting substantively on PDPL, CCSPR and agent cost economics builds the authority that makes introduction 2 possible. **Organic and personal, never automated.** | **15 percent** |
| 4 | **WhatsApp Business, post-introduction only** | The genuine business channel in the Kingdom. Never for cold outreach; entirely for nurture, scheduling, document delivery and the fast question a buyer will not put in an email. | **10 percent** (as an accelerant across the others) |
| 5 | **Channel partner and SI co-sell** | Brings frame agreements, local content credentials and Etimad access Wolffish does not have. Converts ICP Level 2 from unreachable to reachable. | **10 percent** in year one, materially more in year two |
| 6 | **Etimad and public tender** | ICP Level 2 only. Wolffish has no RHQ barrier and benefits from local-bidder preference, which is a structural advantage most competitors cannot answer. | Year two |
| 7 | **Owned: bilingual site, scorecard, calculator** | The forwardable layer. Their job is to survive being sent onward inside the buyer's organisation without the founder present. | Underpins all of the above |

---

## Step 8.1 — Full-funnel asset mapping

### ═══ CHANNEL 1 · EVENTS AND PHYSICAL PRESENCE ═══

| Funnel stage | Asset / collateral | Description | Format | Content outline | Content specs and QA | Contributors | Inputs required | Timeframe | Notes |
|---|---|---|---|---|---|---|---|---|---|
| **TOFU** | **Kingdom AI Exposure Scorecard, event edition** | The demand driver as a 4-minute self-assessment, run from a QR code at the stand. Produces a Residency Exposure Score and a Cost Forecast Band on the spot. | ScoreApp, bilingual, mobile-first, RTL correct | 12 questions across shadow AI usage, data classes in prompts, transfer basis on file, current AI spend, adoption trajectory · instant score · benchmarked result page · booked call CTA | Arabic must be primary and RTL layout must be verified on iOS and Android before the event. Result page under 400 words. No lead-capture before the score is shown. Full spec in `10-lead-magnet-spec.md`. | Founder (logic and thresholds) · Arabic copy reviewer · ScoreApp build | Threshold definitions · benchmark bands · bilingual copy | 2 weeks build, 3 days QA | **Highest-yield TOFU asset. Must be live before GAIN on 15 Sep 2026.** |
| **TOFU** | Stand narrative panel, single question | One sentence, Arabic primary, large: *"كم من بياناتكم غادر المملكة هذا الشهر؟"* / "How much of your data left the Kingdom this month?" plus the QR. | Printed panel, 2m | One question. One QR. The wolffi.sh URL. Nothing else. | Arabic typography reviewed by a native reader. No feature list, no logo wall, no product screenshot. | Founder · designer | Brand assets | 1 week | The discipline of a single question is the asset. A feature panel at Black Hat MEA is indistinguishable from forty other stands. |
| **TOFU** | Speaking abstract and talk, bilingual | A 20-minute session on architectural versus contractual residency under PDPL and CCSPR, with the cost-forecast data as the second half. | Slides plus speaker notes, Arabic and English versions | The SDAIA adequacy-list gap · what CCSPR actually prohibits including caching · why an agent task is a thousand times a chat turn · the 2026 cost-shock record · what to ask any AI vendor | Every regulatory claim cited to the instrument. No Wolffish product slide until the final minute. Deliverable in Arabic on request. | Founder | Regulatory dossier · cost data | 2 weeks | Speaking converts far better than exhibiting at GAIN specifically, where the audience is regulator-adjacent. |
| **MOFU** | Landed Cost Calculator, tablet edition | The web calculator, run at the stand with the visitor's real headcount. | Web app on a tablet, bilingual | Headcount and usage profile in · three-line landed cost out · comparison against ChatGPT Enterprise, Claude and an SI build · emailed PDF of their own numbers | **Pass-through line always shown and attributed.** All competitor figures carry their source and the estimate caveat. SAR primary, USD secondary. | Founder · developer | Pricing model · competitor assumptions | 2 weeks | The emailed PDF is the real asset: it is what gets forwarded to the CFO who was not at the event. |
| **BOFU** | Security-call booking, on the spot | A calendar slot booked in the conversation, not "we will be in touch". | Calendar link plus a physical card with a WhatsApp QR | Slot · a one-line agenda · who should be in the room | The agenda line must say "with your security team in the room". That sentence does most of the qualifying. | Founder | Calendar | Immediate | Booking in the room converts several times better than any follow-up sequence. |
| **BOFU** | One-page bilingual leave-behind | The only printed collateral. Architecture diagram on one side, three-line pricing on the other. | A4, double-sided, Arabic on the front | Front, Arabic: the promise, the architecture diagram, the three price lines · Back, English: the same, plus contact | Must be readable without explanation. No feature list. Diagram must be traceable with a finger. | Founder · designer | Architecture diagram · pricing | 1 week | Assume it is photographed and sent to someone who was not there. Design for that reader. |

---

### ═══ CHANNEL 2 · WARM INTRODUCTION AND SPONSOR NETWORK ═══

| Funnel stage | Asset / collateral | Description | Format | Content outline | Content specs and QA | Contributors | Inputs required | Timeframe | Notes |
|---|---|---|---|---|---|---|---|---|---|
| **TOFU** | **Sponsor map, per target account** | An internal working document: for each of the twenty named accounts, who could credibly introduce, what the introduction costs them socially, and what makes it reflect well on them. | Internal spreadsheet | Account · decision maker · candidate sponsors · relationship strength · what the sponsor gains · current status | Internal only. Updated after every event. **Never shared, never automated, never exported to a CRM sequence.** | Founder | Personal network audit | Ongoing, reviewed monthly | This document is the actual top of the funnel for this business. Everything else supports it. |
| **TOFU** | **The forwardable paragraph** | A single paragraph a sponsor can forward without endorsing, that makes the introduction easy and low-cost for them. | Plain text, WhatsApp-ready, Arabic and English | One sentence on what Wolffish is · one on why it is relevant to that specific organisation · one on what is being asked for, which is thirty minutes, not a purchase | Under 80 words. **No attachment, no deck, no link tracking.** A tracked link in a personal introduction reads as a campaign and costs the sponsor's credibility. | Founder | Account context | 30 minutes per account | The asset is the brevity. A sponsor will not forward a deck. |
| **MOFU** | Sponsor briefing note | A half-page giving the sponsor enough to answer one follow-up question without needing the founder. | PDF, one page, bilingual | What it is · who it is for · what it costs · why it is Saudi-relevant · one line on what to say if asked "are they any good" | Written to be read once and remembered, not filed. | Founder | Positioning statements | 3 days | Sent after the introduction, never before. |
| **BOFU** | Peer reference call, CISO to CISO | An existing customer's CISO speaking to a prospect's CISO, unscripted. | 30-minute call, no Wolffish presence | Prospect asks anything. Wolffish does not attend. | Negotiated into the design-partner agreement at signature (Dashboard 05). Never requested ad hoc, which puts the customer on the spot. | Founder arranges only | A live reference customer | Available from customer 1 onward | **The single highest-converting asset in this library.** Budget it as a channel because it is one. |

---

### ═══ CHANNEL 3 · FOUNDER-LED ORGANIC LINKEDIN AND X ═══

| Funnel stage | Asset / collateral | Description | Format | Content outline | Content specs and QA | Contributors | Inputs required | Timeframe | Notes |
|---|---|---|---|---|---|---|---|---|---|
| **TOFU** | **Saudi AI regulation explainer series** | Eight posts over eight weeks, each explaining one thing a Saudi executive needs and cannot easily get: what CCSPR actually prohibits, why SDAIA's missing adequacy list matters, what NDMO classification does to a cloud decision, what SAMA requires before signing. | LinkedIn long-form (English) and X threads (Arabic) | One instrument per post · what it says · what it means for an AI decision · what to ask a vendor | Every claim cited to the instrument. **No product mention in six of the eight.** Arabic threads written natively, not translated. | Founder | Regulatory dossier | 1 post per week, ongoing | This is how a two-person company becomes credible to a CISO who has never heard of it. It compounds and cannot be shortcut. |
| **TOFU** | Cost-shock commentary | Short posts on the 2026 record: Uber's exhausted budget, the 78 percent surprise-charge figure, Anthropic's spend controls, the thousand-times token ratio. | LinkedIn and X, bilingual | The fact · the mechanism · what a CFO should do about it | Never gloating about a competitor. The tone is analytical, because the CFO reading it may already own the product being discussed. | Founder | Cost dossier | Reactive, as news lands | The most shareable content Wolffish has, because it is useful to someone who will never buy. |
| **MOFU** | **"Ask any AI vendor these six questions"** | A checklist post that a buyer can use against every vendor including Wolffish, and that Wolffish happens to be the only one that passes cleanly. | Carousel plus downloadable one-pager, bilingual | Where does my data physically go · what is my transfer basis · what can the agent touch · who owns the audit log · what is the cap, and is it enforced · what happens if you disappear | The questions must be genuinely fair. A checklist that is transparently rigged fails with exactly the audience it is aimed at. | Founder | Competitive analysis | 1 week | The highest-utility MOFU asset. Works because it is useful whether or not the reader buys. |
| **MOFU** | Deployment write-up, anonymised | A technical account of one real deployment: the integration nobody would touch, what broke, what it cost. | LinkedIn article, English primary, Arabic summary | The organisation, anonymised · the internal system · the approach · what went wrong · measured outcome | Customer approval required, negotiated at signature. **Must include something that went wrong** or it reads as marketing and stops being evidence. | Founder · customer | A live deployment | 2 weeks after go-live | Available only from customer 1 onward, which is why the design-partner agreement asks for it up front. |

**Explicitly not built:** automated connection sequences, InMail campaigns, LinkedIn Ads,
lookalike audiences, retargeting pixels. Against twenty named accounts these spend money to reach
people who cannot buy, and automation on the founder's profile degrades the one asset channels 2
and 3 both depend on.

---

### ═══ CHANNEL 4 · WHATSAPP BUSINESS, POST-INTRODUCTION ONLY ═══

| Funnel stage | Asset / collateral | Description | Format | Content outline | Content specs and QA | Contributors | Inputs required | Timeframe | Notes |
|---|---|---|---|---|---|---|---|---|---|
| **MOFU** | WhatsApp document set | The five documents a buyer asks for between meetings, formatted to open cleanly on a phone: architecture diagram, three-line pricing, compliance pack summary, escrow summary, one-page leave-behind. | PDF, phone-optimised, bilingual, under 2MB each | As named | Must be legible on a phone without zooming. Arabic filenames as well as English. **Never a link requiring a login.** | Founder · designer | Existing assets | 1 week to reformat | Saudi executives forward documents in WhatsApp groups. Design for the second reader, who has no context. |
| **MOFU** | Voice-note explainer, Arabic | A 90-second Arabic voice note explaining the architecture, sent when a buyer asks a quick question between meetings. | Voice note | The one-sentence architecture · why it removes the transfer question · an offer to explain properly on a call | Recorded fresh per conversation, never a stock recording. A recycled voice note is obvious and costly. | Founder | — | Per conversation | Extremely high-trust medium in the Kingdom, and almost no B2B vendor uses it well. |
| **BOFU** | Meeting confirmation and agenda | The confirmation of a security call, with the agenda and who should attend. | WhatsApp message, bilingual | Time · agenda in three lines · "please have your security team in the room" · what to send in advance | The attendee line is the qualification instrument. | Founder | Calendar | Per meeting | Email confirms. WhatsApp is what gets read. |

---

### ═══ CHANNEL 5 · CHANNEL PARTNER AND SI CO-SELL ═══

| Funnel stage | Asset / collateral | Description | Format | Content outline | Content specs and QA | Contributors | Inputs required | Timeframe | Notes |
|---|---|---|---|---|---|---|---|---|---|
| **TOFU** | Partner proposition one-pager | Why a Saudi SI should carry Wolffish rather than build: they keep the integration and change-management revenue, Wolffish carries the platform and the SLA. | PDF, one page, English and Arabic | The margin split · what the partner owns · what Wolffish owns · why building it costs them more · reference architecture | Must lead with **what the partner earns**, not with what Wolffish does. An SI reads a platform pitch as a threat until the economics are on the first line. | Founder | Commercial model | 1 week | Target one partner, not several. A partner who feels like one of five will not invest. |
| **MOFU** | Partner enablement pack | What a partner's pre-sales team needs to run a first conversation without the founder. | Deck plus FAQ plus objection handling, bilingual | Positioning · the six questions · competitive comparison · pricing model · qualification criteria including the 200-seat floor · when to bring the founder in | Must state plainly when the partner should escalate. A partner running an unwinnable deal alone damages both. | Founder | All dashboards | 3 weeks | Build only after a partner is signed. Building it speculatively is a common and expensive mistake. |
| **BOFU** | Co-sell commercial framework | Reseller or referral terms, margin, delivery split, escrow position, IP boundaries. | Contract template, Arabic and English, Saudi jurisdiction | Terms · margin · delivery responsibilities · support boundary · escrow · local content contribution | Legal review required. Local content contribution should be stated explicitly, since it is a live benefit to the partner under LCGPA direction of travel. | Founder · counsel | Legal | 4 weeks | Do not start until a specific partner is in view. |

---

### ═══ CHANNEL 6 · ETIMAD AND PUBLIC TENDER (ICP LEVEL 2, YEAR TWO) ═══

| Funnel stage | Asset / collateral | Description | Format | Content outline | Content specs and QA | Contributors | Inputs required | Timeframe | Notes |
|---|---|---|---|---|---|---|---|---|---|
| **TOFU** | Etimad supplier registration and profile | Complete registration with classifications and documentation current. | Etimad portal | CR · ZATCA · classifications · financial standing · past performance | Must be complete before a relevant tender appears, not after. Registration during a live tender is usually too late. | Founder | Company documentation | 4 weeks | Prerequisite for the entire channel. |
| **MOFU** | Tender response template | A pre-built response covering the sections that recur: security architecture, data residency, local content, support model, escrow. | Document template, Arabic and English | Standard sections pre-written · placeholders for tender-specific scope | Arabic must be the primary submission language. Security and residency sections reused verbatim from the Compliance Evidence Pack. | Founder · Arabic technical writer | Compliance pack | 3 weeks | Reduces per-tender effort from weeks to days, which is what makes the channel viable for two people. |
| **BOFU** | Local content statement | Documented local content position: Saudi entity, Saudi employment, in-Kingdom delivery. | Formal statement | Entity · employment · delivery location · supply chain | Accuracy matters more than the number. LCGPA weighting on IT services begins 1 April 2027 at SAR 10m and extends to SAR 5m from 1 January 2028. | Founder · accountant | Company records | 2 weeks | Also usable in private-sector deals, where several large buyers apply their own local content preferences. |

---

### ═══ CHANNEL 7 · OWNED, ALWAYS-ON ═══

| Funnel stage | Asset / collateral | Description | Format | Content outline | Content specs and QA | Contributors | Inputs required | Timeframe | Notes |
|---|---|---|---|---|---|---|---|---|---|
| **TOFU** | **Bilingual site, Arabic-first** | wolffi.sh/cloud with Arabic as the default for Saudi visitors, not a language toggle in the footer. | Web, RTL-correct | Promise · architecture · three-line pricing · the six questions · scorecard · calculator · security-call booking | RTL layout verified on real devices. Arabic copy written natively. **Page must state the three price lines publicly** — transparency is a differentiator against a market of quote-only competitors. | Founder · Arabic copywriter · developer | Positioning, pricing | 3 weeks | Publishing the price is itself a positioning move against quote-only vendors. |
| **TOFU** | **Landed Cost Calculator** | Headcount in, three-line landed cost out, with comparisons. | Web app, bilingual | Inputs · three lines · comparison table · assumptions and estimate caveats · emailed PDF | **The pass-through line is never hidden.** Every competitor number carries its source and the estimate caveat. | Founder · developer | Pricing model | 2 weeks | The most forwardable asset in the library. Built to survive reaching a CFO with no context. |
| **MOFU** | **Compliance Evidence Pack** | The document set a Saudi CISO and their auditor need: NCA ECC and CCC control mapping, NDMO classification treatment, PDPL architecture note, SAMA CSF outsourcing annex, CCSPR conformity statement, audit log schema, approval-gate reference, escrow deed. | PDF pack, Arabic and English | One section per instrument, each stating the control, the architectural answer, and the evidence | **The single largest asset build in this library and the highest leverage.** Reviewed by Saudi counsel with regulatory experience. Built once, reused in every deal, and it is what makes deal two's evaluation shorter than deal one's. | Founder · Saudi counsel · Arabic technical writer | Regulatory dossier · architecture | **6 weeks** | Replaces the Ali-block "Enterprise Rollout & Procurement Support" as an embedded free deliverable rather than a paid service. See Finding 6. |
| **MOFU** | **Agent Exposure and Spend Audit method pack** | The internal method, templates and output format for the one-week diagnostic. | Internal templates plus a client-facing two-page output | Data collection checklist · classification mapping worksheet · cost trajectory model · output template | Output must be useful if Wolffish is never bought. A diagnostic that only makes sense as a sales document is not a diagnostic. | Founder | Method design | 2 weeks | The demand driver made repeatable, which is what keeps it from consuming unbounded principal time. |
| **BOFU** | Deployment scope ladder and SOW | Pilot, Standard and Complex deployment scopes with what each includes and what triggers the next tier. | Document plus contract annex | Three tiers · inclusions · integration count · the capability allowance · exclusions | Directly implements Findings 1 and 4. **Must exist before the next contract is signed.** | Founder · counsel | Offer metrics audit | 2 weeks | The commercial control that bounds the largest margin risk in the business. |
| **BOFU** | Pre-packaged escrow deed | Standing escrow with a named agent, release conditions pre-written, ready to hand over. | Legal deed plus one-page summary | Agent · deposit schedule · release conditions · verification | Executed with the agent in advance so it is a data-room artefact, not a negotiation. Implements Finding 3. | Founder · counsel · escrow agent | Legal | 4 weeks | Converts the longest pole in the deal into a document reviewed in parallel. |

---

## Build sequence and the ninety-day plan

Ordered by yield per week of founder time, against the fact that **GAIN is 11 days away** and
**Black Hat MEA is 12 weeks away**.

| Priority | Asset | Weeks | Why now |
|---|---|---|---|
| **1** | Kingdom AI Exposure Scorecard | 2 | Must be live before GAIN, 15 Sep 2026. Everything else at the event depends on it. |
| **2** | Stand panel and speaking abstract | 1 | Same deadline. |
| **3** | Landed Cost Calculator | 2 | Most forwardable asset; supports every channel. |
| **4** | Sponsor map and the forwardable paragraph | 1 | The actual top of funnel. Costs almost nothing and gates everything. |
| **5** | One-page bilingual leave-behind | 1 | Needed for GAIN. |
| **6** | Bilingual Arabic-first site | 3 | Everything above points at it. |
| **7** | **Compliance Evidence Pack** | **6** | The largest build and the highest leverage. Start now so it is complete before Black Hat MEA on 1 Dec. |
| **8** | Deployment scope ladder and SOW | 2 | Must exist before the next contract. Bounds the Finding 1 exposure. |
| **9** | Pre-packaged escrow deed | 4 | Runs in parallel with 7; both are counsel-dependent. |
| **10** | Regulation explainer series | ongoing | Compounds. Start immediately, one post per week. |
| **11** | Audit method pack | 2 | Needed before the third diagnostic, not the first. |
| **12** | Partner proposition one-pager | 1 | Only when a specific partner is in view. |
| **13** | Etimad registration and tender template | 7 | Year two. Do not start before a live opportunity. |

**Total founder time to a complete year-one library: roughly 25 weeks of part-time effort**, which
against a deployment capacity of four to six is the correct order of magnitude, and is the reason
the sequence above matters more than the list.
