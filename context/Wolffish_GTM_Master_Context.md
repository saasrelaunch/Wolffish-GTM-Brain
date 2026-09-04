---
title: Wolffish Cloud Go-To-Market Master Context
project: Wolffish Cloud
type: gtm_context_file
purpose: Single source of truth for any AI agent or human operator executing Wolffish Cloud go-to-market work in the Kingdom of Saudi Arabia.
version: 1.0
last_updated: 2026-09-04
status_notes: Kingdom of Saudi Arabia only, do not produce for any other market. No reference customer exists yet, so no logo, quote, metric or case study may be cited. The capability allowance that bounds ongoing capability development is proposed and not contracted, so the phrase "no new invoice" must not appear in any proposal. Pricing is published and fixed. The offer matrix is unreconciled between two blocks; the founder block governs. Deployment capacity is four to six customers in twelve months, so volume marketing is out of scope by arithmetic, not preference.
canonical_vocabulary: Wolffish Cloud, agentic harness, platform control plane, cloud service, Saudi regulatory fit, in-perimeter, zero-retention endpoint, capability allowance, deployment scope ladder, landed cost, pass-through, Compliance Evidence Pack, Agent Exposure and Spend Audit, Kingdom AI Exposure Scorecard, security call, pilot cohort, capability, seat
---

# Wolffish Cloud Go-To-Market Master Context

## 0. Agent operating instructions

You are working inside the Wolffish Cloud go-to-market. This file is the distilled version of a
nine-dashboard go-to-market build plus a pricing model and an offer audit. Read it once, then
execute from it. Do not re-derive strategy that is settled here.

How to use this file.

1. Read Section 15 first if you only need a fact. It answers most lookups without a full read.
2. Pick the audience before writing a word. There are two and they never mix in one asset.
3. Check every capability mention against Section 3, and every superlative against Section 4.
4. Load the matching file in `reference/` for depth. This file is the map, not the territory.
5. Run `ops/QA-checklist.md` before returning anything customer-facing.

Six hard guardrails. These are absolute.

- **Kingdom of Saudi Arabia only.** Every ICP, channel, price and claim here is scoped to Saudi
  Arabia. Refuse requests to produce for the wider Gulf, Egypt or globally, and say why.
- **No proof point outside the closed set in Section 4.** There is no reference customer. Any
  logo, quote, metric, case study or customer count is fabrication.
- **Every capability carries its status flag in the same sentence.** Not in a footnote, not once
  at the top of a page.
- **Landed cost on both sides, always.** Never quote the SAR 79 seat against a competitor seat
  price. That comparison hides a third of the cost and a competent finance director will catch it.
- **Never position against HUMAIN.** Neutralise, do not compete. One sentence, then move on.
- **Three channels are refused outright.** Automated outreach sequencing, cold email at volume,
  and paid social. If asked for them, decline and offer the in-scope alternative.

## 1. House writing rules

Full detail in `rules/writing-rules.md`. The short version.

No em dashes anywhere. Use commas, or restructure the sentence.

Banned words: the fourteen-word list in `../rules/writing-rules.md`, which is authoritative. It bans the usual hype vocabulary and their obvious variants.

Short paragraphs, one to three sentences. Specific numbers, named capabilities and verifiable
facts instead of adjectives. Prose over lists unless the content is genuinely a list. No stacked
adjectives. No superlative that has not been through the claim ledger.

Every asset ships bilingual or it does not ship. In Arabic-first channels the Arabic is the
headline and the English is the subhead, never the reverse, and the Arabic is written natively
rather than translated.

Register: precise, unhurried, and willing to say no. The audience is a security officer or a
finance director who is accountable for being wrong, so certainty that is not earned reads as
risk rather than confidence.

## 2. Canonical vocabulary

Full table in `rules/glossary.md`. The terms that carry weight.

**Wolffish Cloud** is the product name, both words, always capitalised. Not "Wolffish AI",
not "the Wolffish platform" as a proper noun.

**In-perimeter** describes where the work happens. Agents execute on the employee's own machine
and inference goes to a zero-retention endpoint on the customer's own account. It is not
"on-premise", which implies a server room, and it is not "private cloud", which implies a tenant.

**Capability** is the unit of function, and it is what the allowance is denominated in. Not
"feature", which invites a comparison with a software catalogue.

**Landed cost** is the sum of all three price lines including the customer's own inference and
infrastructure. Any cost figure without this word attached is incomplete.

**Pass-through** is the inference and infrastructure line billed by the customer's own providers
at zero Wolffish margin. Never described as revenue.

**Seat** is one employee with an agent. Not "user", not "licence".

The distinction that must never blur: **data residency** is a contractual commitment about how a
vendor handles data after receiving it. **No vendor-side data path** means the vendor never
receives it. Wolffish claims the second and must never claim the first, because the first is
what every competitor also offers.

## 3. Status ledger for capabilities

Full ledger in `rules/feature-status.md`, which is authoritative and updated first when status
changes. Flags: SHIPPED, PARTIAL, IN BUILD, ROADMAP.

The four groups.

**Agentic harness.** Persistent per-employee agent on the employee's machine, file read and write
scoped per role, approval gates on sensitive actions, multi-step autonomous execution, local
context ingestion, model portability across zero-retention endpoints. Shell and command execution
is shipped and is the capability that alarms a security officer if introduced before approval
gates are explained.

**Platform control plane.** Hard token quota enforced per user, team and period. Action-level
audit log written to the customer's own store. Kill switch per user and global. Single sign-on,
directory sync and offboarding. Admin console with per-role and per-agent scopes. Spend
visibility by team and task. Branded single-tenant deployment.

**Cloud service.** Deployment engineering with a pilot cohort. First-class custom integrations
into internal, bespoke and legacy systems. Ongoing capability development inside the seat fee.
The service level of 99.5 percent uptime with a four-hour P1 response. Source access and escrow.

**Saudi regulatory fit.** Saudi commercial registration, riyal contracting, ZATCA-compliant
electronic invoicing, Saudi jurisdiction and Arabic contracting. Personal data never crosses the
border, so no transfer mechanism is required. The Compliance Evidence Pack covering the national
cybersecurity controls, the data classification framework, the personal data law and the central
bank outsourcing framework. Support for a sovereign in-Kingdom inference endpoint as a model
option.

Two capabilities carry a caution. Arabic-first coverage is claimed across interface, prompting,
output and document handling, and the exact current state per surface is an open question in
`ops/decisions.md`. The Compliance Evidence Pack is the single largest unbuilt asset in the plan.

## 4. Claim hygiene ledger

Full ledger with replacements in `rules/do-not-say.md`. The spine.

**The closed proof-point set.** Wolffish has no reference customer. The permitted proof points
are: the published three-line price, the published token ceilings, the architecture itself, and
publicly sourced third-party figures with their source named. Nothing else exists. Any customer
name, logo, quote, count, case study or outcome metric is fabrication.

**Four superlatives were run through a counter-example drill.** Three narrowed, one held.

- "The only platform where your data never leaves" narrows to "no path exists by which a prompt,
  a file or an output reaches Wolffish", because a self-hosted open-source stack also keeps data
  in the perimeter.
- "The cheapest option" fails outright. Microsoft's assistant is cheaper per seat and a
  do-it-yourself stack is close on cost. The safe form is forecastable rather than cheapest.
- "The fastest deployment" narrows to six to eight weeks for a standard scope, because a complex
  multi-entity deployment is ten to fourteen weeks and an integrator can move faster on a narrow
  brief.
- "No transfer mechanism is required, because nothing crosses the border" **holds**. It is
  architectural, not comparative, and it survives cross-examination.

**Hard bans.** No certification claim, because none is held. No customer proof of any kind. No
capability described in the present tense that is not flagged SHIPPED. No cost comparison that
omits the pass-through line. No claim to be more sovereign than the national champion. No
production for a refused channel. No use of the phrase "no new invoice" in writing until the
capability allowance is contracted.

## 5. What the product actually is

Wolffish Cloud is a deployed agent platform that runs inside a customer's own perimeter. Three
stacked products, not one, plus a fourth layer that is market structure rather than software.

The **agentic harness** is the runtime on each employee's machine, with real file and command
permissions and approval gates the customer configures. The **platform control plane** is what a
security officer and a finance director can see and stop: quotas, audit, kill switch, identity,
scopes. The **cloud service** is the engineering that builds the deployment and wires the
customer's own internal systems in as agent capabilities. The **Saudi regulatory and commercial
fit** is a Saudi entity, riyal contracting, compliant invoicing, and an architecture with no
cross-border transfer.

The commercial shape is three lines. A one-time deployment at SAR 60,000, a platform seat at
SAR 79 per employee per month on a twelve-month term billed quarterly in advance, and a
pass-through of roughly SAR 45 to 55 per seat for inference and infrastructure billed by the
customer's own providers at zero Wolffish margin. Landed cost is SAR 124 to 184 per employee per
month, everything counted.

The constraint that shapes everything: deployment consumes six to eight weeks of principal
engineering time regardless of customer size, so the company can take four to six customers in
twelve months. This is not a funnel business. It is twenty named accounts.

## 6. Capability matrix, what leads and what is table stakes

Full analysis in `reference/feature-matrix.md`. Thirty-six capabilities scored on demand and
competitive advantage, tagged to one of the four layers.

**Lead with these.** No vendor-side data path. Compliance by architecture rather than by contract.
First-class integration into the internal systems no vendor catalogue will ever support. Saudi
entity with riyal contracting and compliant invoicing. Action-level audit in the customer's own
store. The hard enforced quota. The persistent per-employee agent with real permissions. The
Arabic-first agent.

**Table stakes, claim but never lead.** Multi-step autonomous execution. Chat and retrieval over
company documents. Kill switch. Single sign-on and offboarding. Admin console. The service level.
In-Kingdom support hours and Arabic documentation, which in this market every local integrator
already has and which a foreign-authored plan routinely mistakes for an advantage.

**Introduce only after the problem is named.** Shell and command execution, which frightens a
security officer if it arrives before approval gates. Model portability. Escrow. Founder
engineering delivery. Conformity for public-sector data. The sovereign endpoint option.

**Do not build or mention.** Prompt libraries, usage analytics of message counts, a mobile
application. The agent's value comes from executing on a machine with files and a shell, so a
phone application would be a worse product pretending to be a broader one.

The uncomfortable reading: the harness layer holds the most negative competitive scores and is
commoditising every quarter. Positioning must never rest there.

## 7. Competitive market analysis

Full analysis in `reference/competitive-analysis.md`, per-rival cards in
`reference/competitor-battlecards.md`.

Seven options a Saudi buyer shortlists: Microsoft's assistant, OpenAI's enterprise product,
Anthropic's enterprise product and coding agent, the national AI champion, a Saudi systems
integrator building it bespoke, developer coding tools, and a do-it-yourself open-source stack.

Five positioning vectors, scored zero to ten. Wolffish leads two.

| Vector | Leader | Wolffish |
|---|---|---|
| Frontier model capability | Anthropic, 9.6 | 5.2 |
| Ecosystem breadth and enterprise familiarity | Microsoft, 9.7 | 2.6 |
| Sovereign legitimacy and national mandate | The national champion, 9.8 | 6.8 |
| Forecastable cost per employee | **Wolffish, 9.4** | 9.4 |
| In-perimeter execution and custom system reach | **Wolffish, 9.6** | 9.6 |

Concede the first three loudly. The concession is what makes the last two believable.

Two findings govern the sales motion. First, the nearest competitor on the two vectors Wolffish
leads is the Saudi systems integrator at 3.6 and 7.4, not any of the AI vendors, so most deals
are won or lost on product economics against project economics. Second, the sovereignty question
is neutralised rather than won: model portability makes the national Arabic model on an
in-Kingdom endpoint a supported configuration, which turns the hardest objection in the market
into a configuration line.

Two capability rows carry the whole argument. A customer-owned audit log is matched by exactly
one competitor. Ongoing capability development at no additional invoice is matched by none.

## 8. Ideal customer profile and buying committee

Full profile in `reference/icp-personas.md`.

**ICP 1, the founder-led motion.** A Saudi-owned, regulated or intellectual-property-sensitive
enterprise with 200 to 600 knowledge workers, a document-heavy back office, and a named
information security owner. Insurance and takaful, mid-tier banks and licensed finance companies,
private healthcare groups, law firms, engineering and industrial groups, family holding companies
with a shared services centre. Riyadh first, the Eastern Province second.

The strongest qualifying signal is an organisation that has already run an artificial intelligence
pilot that stalled. They have spent the enthusiasm and now want the governance parts.

**ICP 2, the channel-assisted motion.** Regulated large enterprises and government-adjacent
entities with 600 to 2,500 knowledge workers, bought through a tender platform or under an
integrator's prime agreement.

**The qualification floor is 200 seats and it is hard.** Year-one revenue is SAR 60,000 plus
SAR 948 per seat, while deployment costs the same principal weeks regardless of size. Below 200
seats the engagement cannot repay that time at any point in the contract. Decline.

**The committee has seven roles in ICP 1, not three.** The three classic levels are the knowledge
worker, the department head and the owner. Four more decide Saudi deals: the security officer who
holds an absolute veto and is frequently the real decision maker, the finance director who can
defer indefinitely by declining to create a budget line, the procurement and legal function that
cannot approve a foreign-jurisdiction contract without an exception process, and the relationship
sponsor who has no formal role and determines how everyone else first hears about Wolffish.

**The sequence is the highest-return process decision in this go-to-market.** Sponsor
introduction, then the security officer with the decision maker present, then the technology
lead, then finance, then the pilot cohort, then the decision maker, and procurement last with a
complete pack rather than a request. The standard Western sequence starts with the economic buyer
and produces a deal that dies in month four.

## 9. Strategic verdicts already decided

Recorded with dates and rationale in `ops/decisions.md`. Do not reopen these without new evidence.

**The category is a deployed agent platform, not spend governance.** The offer matrix contains a
second reading that frames Wolffish as an artificial intelligence spend-governance vendor. That
framing puts the company in a different room, against different competitors, selling to a
different buyer, with a ceiling set by overspend rather than by headcount. It would reprice the
company by roughly an order of magnitude. Cost control is one of two winning arguments, not the
category.

**Concede three vectors, contest two.** Model quality, ecosystem breadth and sovereign legitimacy
are conceded openly and early.

**Never position against the national champion.** The gap on sovereign legitimacy cannot be
closed, only made irrelevant.

**Three channels are refused.** Automated outreach sequencing, volume cold email, and paid social.
Against twenty named accounts and a delivery ceiling of four to six, they spend money reaching
people who cannot buy, and automation aimed at a Saudi security officer damages the founder's own
profile, which is the asset the two largest channels depend on.

**The security call comes before the economic conversation.** This inverts the standard sequence
deliberately.

**Pricing is published.** In a market of quote-only competitors, publishing the three lines is a
positioning move, not a convenience.

**The deployment fee is a land fee, not margin.** SAR 60,000 buys six to eight weeks of principal
engineering. It is recognised as a paid pilot that consumes the only non-scalable resource.

## 10. Value proposition, audience one, ICP 1

Full framework in `reference/value-proposition-icp1.md`. Three pillars, three reasons to believe
each, all bilingual.

**Pillar one. Nothing of yours leaves the building.** Data residency stops being a contractual
promise the buyer has to defend and becomes an architecture they can point at. Agents execute on
the employee's own machine, inference goes to a zero-retention endpoint on the customer's account,
the action-level audit log lives in the customer's own store, and because nothing crosses the
border no transfer mechanism is required.

**Pillar two. An artificial intelligence bill you write, not one you receive.** On a metered plan
the more the agents work the more the company pays, so finance ends up rationing exactly the
behaviour that creates the value. The seat is fixed, the token quota is a hard enforced cap, and
inference bills to the customer's own account at open-weight rates far below frontier models.

**Pillar three. An agent that reaches the systems that actually run your company.** Every vendor
offers connectors: a catalogue built for the average customer. The bespoke administration tool
and the twelve-year-old policy engine are not in that catalogue and never will be.

Lead pillar one with a security officer, pillar two with a finance director, pillar three with a
chief executive or a technology lead. The wrong pillar in the right chair reads as not having
understood who is in the room.

## 11. Value proposition, audience two, ICP 2

Full framework in `reference/value-proposition-icp2.md`. Same three pillars, different weighting
and two additions.

The security and architecture argument arrives first and carries more of the load, because an
enterprise architect can rule Wolffish out as non-standard before any commercial discussion
begins. The strongest single asset for this audience is an architecture document showing that
Wolffish adds no new external dependency, which is unusual enough to state explicitly.

Two additions that do not appear in ICP 1. **Conformity for public-sector data**, where the cloud
regulations forbid transfer outside the Kingdom for any purpose including caching, which
disqualifies most of the competitive set outright. **Procurement position**, where a Saudi entity
faces no regional-headquarters barrier and benefits from local-bidder preference.

The blocker that has no answer yet is the absence of a reference at comparable scale. Only a
security-officer-to-security-officer call answers it, which is why the ICP 1 design partners
matter more than their revenue suggests.

Never blend the two audiences in one asset. ICP 1 buys speed and a single decision. ICP 2 buys
evidence and a defensible evaluation trail. An asset written for both reads as written for
neither.

## 12. Positioning statement

Full set of six statements in `reference/positioning.md`.

**Category, English:** in-perimeter agentic workforce platform.
**Category, Arabic:** منصة وكلاء ذكيين داخل نطاق منشأتك

The name excludes every competitor by construction. In-perimeter excludes the vendor clouds.
Workforce excludes the developer tools. Platform excludes the integrator project.

**One-liner:** One agent per employee, running on their own machine, inside your own perimeter,
on a bill you set.

**Arabic one-liner:** وكيل ذكي لكل موظف، على جهازه، داخل نطاقك، وبتكلفة تُقرّرها أنت

The six statements answer, in order: the vendor clouds, the residency answer every vendor gives,
the metered stack, the systems integrator, the national champion, and the status quo. Statement
four decides the most deals and is the one most often skipped, because the integrator is rarely
in the room and is rarely named by the buyer as a competitor.

Three labels are refused. Not "AI assistant", which invites a comparison with a bundled
productivity tool. Not "AI agent spend governance", which is the rejected category. Not
"sovereign AI", which belongs to the national champion.

## 13. Customer journey funnels

Full funnels in `reference/customer-journey.md`. Seven stages per audience.

Stage one is problem awareness, driven by the scorecard and the cost calculator. Stage two is the
security call, moved forward from its usual position, and it is the pivotal asset in the entire
funnel. Stage three is vendor evaluation, carried by a free one-week exposure audit and the
Compliance Evidence Pack. Stage four is a paid pilot cohort of ten seats over three weeks, priced
at SAR 25,000 and credited in full against the deployment fee on conversion within ninety days.
Stage five is the build and go-live. Stage six is expansion by business unit. Stage seven is
renewal, timed before the December budget statement.

Cycle length is sixteen to thirty-four weeks for ICP 1 and roughly double for ICP 2, plus six to
eight weeks to go-live.

**The Saudi calendar removes about forty percent of the year.** Ramadan runs approximately
8 February to 8 March 2027 with a statutory six-hour working day, both religious holidays follow,
and executives travel in July and August. That leaves roughly twenty-five sellable weeks in
twelve months, not forty-eight. A plan that assumes even months is wrong by the difference.

The live window at the time of this build is September to December 2026: the national artificial
intelligence summit on 15 to 17 September, the regional security conference on 1 to 3 December,
and the budget cycle that culminates in the December budget statement. A deal that has not reached
stage three by October is a next-year deal and should be managed as one.

## 14. Campaign and asset plan

Full plan in `reference/marketing-campaigns.md`, method in `reference/relationship-engine.md`.

Seven channels, ordered by expected share of qualified pipeline. Events and physical presence at
about thirty-five percent. Warm introduction and the sponsor network at about thirty. Founder-led
organic writing on two platforms at about fifteen. Messaging after introduction at about ten.
Channel partner co-sell at about ten in year one and more later. Public tender in year two. The
owned layer of site, scorecard and calculator underpins all of them.

Two channels carry sixty-five percent of expected pipeline and both are physical and cannot be
automated, which is why the founder's calendar rather than an advertising budget is the
constraint on this funnel.

The build sequence is ordered by return per week of founder time. The scorecard first, because it
is the only asset that scales without founder time and it has a fixed deadline. Then the stand
assets, the cost calculator, the sponsor map, the leave-behind, the bilingual site. Then the
Compliance Evidence Pack, which is six weeks and the largest single build, and which makes the
second deal's evaluation materially shorter than the first.

Three channels are refused and the refusal is recorded as an absence in the prompt library.

## 15. Quick-reference execution cheatsheet

The facts an operator looks up most.

- **One-liner.** One agent per employee, on their own machine, inside your own perimeter, on a bill you set.
- **Category.** In-perimeter agentic workforce platform.
- **Flagship differentiator.** No vendor-side data path, so no transfer mechanism is required.
- **Second differentiator.** A hard enforced quota and inference on the customer's own account.
- **Table stake most often mistaken for a differentiator.** Arabic support and in-Kingdom hours.
- **Top-of-funnel hook.** The Kingdom AI Exposure Scorecard, twelve questions, four minutes.
- **The two audiences.** ICP 1 founder-led, 200 to 600 knowledge workers. ICP 2 channel-assisted, 600 to 2,500.
- **Qualification floor.** 200 seats, hard. Decline below it.
- **Delivery ceiling.** Four to six deployments in twelve months.
- **Sellable weeks per year.** About twenty-five, not forty-eight.
- **Price.** SAR 60,000 deployment, SAR 79 per seat per month, plus SAR 45 to 55 pass-through. Landed SAR 124 to 184.
- **Breakeven.** A productivity gain of 0.77 percent across 300 knowledge workers repays the year.
- **Permitted proof points.** The published price, the published token ceilings, the architecture, and sourced third-party figures. Nothing else.
- **Signature reframe.** Everyone offers residency. We offer the absence of a data path.
- **The hardest objection.** Why not the national champion. Answer: different products, and we run on their endpoint if you want their model. You will probably buy both.
- **Primary rival in practice.** The Saudi systems integrator, not any AI vendor.
- **Refused channels.** Automated outreach sequencing, volume cold email, paid social.
- **Mechanics.** No em dashes. No banned words. Bilingual or it does not ship.
- **The one thing never to say.** Any customer name, logo, quote, metric or case study. None exists.
