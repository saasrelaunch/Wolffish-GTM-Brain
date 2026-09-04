# Lead Magnet Specification — The Kingdom AI Exposure Scorecard

**Wolffish Cloud · Kingdom of Saudi Arabia · v1.0 · 4 September 2026**
*Source skill "Lead Magnet Specification" deliverable. Built on the Phase 1 demand driver. For implementation on ScoreApp.com.*
*Arabic name: مقياس انكشاف الذكاء الاصطناعي في المملكة*

---

## ⚠️ Standing caveats for this deliverable

**C1 — Not SaaS.** The scorecard sells a **conversation**, not a trial. Its conversion target is a
booked 30-minute security call with the security team in the room, and every result tier funnels
there or to a lower-commitment document. It never points at a signup.

**C2 — No self-serve.** The strongest result tier does **not** offer a product. It offers a free
one-week founder-led audit. A high scorer who is offered a free trial will take the trial and
never speak to anyone.

**C3 — Landed cost.** The cost-trajectory half of the score models the respondent's own
twelve-month AI spend. It must show all three lines when it presents a Wolffish comparison, or it
becomes the misleading arithmetic this suite exists to prevent.

**C4 — Saudi only, and this is the whole design.** The scorecard is bilingual with Arabic as the
default for Saudi traffic, RTL-correct, and every regulatory reference — PDPL, NDMO, CCSPR, SAMA,
NCA — is to a Saudi instrument. **A generic "AI readiness" scorecard would be worthless here**,
because readiness is not the Saudi buyer's problem; 81 percent of Saudi enterprises already deploy
AI. Their problem is exposure and forecast, and no existing instrument measures either.

**C5 — Offer metrics unreconciled.** The scorecard is the scaled form of the Agent Exposure and
Spend Diagnostic, promoted from the Ali block to a co-equal entry offer in
`00-OFFER-METRICS-AUDIT.md` Finding 6. If the review call rejects that promotion, this deliverable
should not be built.

---

## Scorecard overview

| Element | Specification |
|---|---|
| **Scorecard name** | **The Kingdom AI Exposure Scorecard** · مقياس انكشاف الذكاء الاصطناعي في المملكة |
| **Subtitle** | How much of your data left the Kingdom this month, and what your AI bill looks like in twelve months. Four minutes. · كم من بياناتكم غادر المملكة هذا الشهر، وكيف ستبدو فاتورتكم بعد اثني عشر شهراً؟ |
| **Target ICP** | ICP Level 1 primary: Saudi regulated or IP-sensitive enterprise, 200 to 600 knowledge workers. Respondent should be a CISO, Head of Information Security, CIO, CDO, CFO or CEO. |
| **Problem it reveals** | Two, deliberately paired. **One:** company data is reaching AI vendors outside the Kingdom, with no documented SDAIA transfer basis, and nobody has inventoried it. **Two:** AI spend is on a growth curve nobody has forecast, because agentic usage consumes roughly a thousand times the tokens of a chat turn. |
| **Immediate value to the respondent** | An exposure score they can put in front of their own audit committee, benchmarked against Saudi peers, with a twelve-month spend projection based on their own inputs. Useful whether or not they ever speak to Wolffish, which is the condition of it being believed at all. |
| **Conversion path to Wolffish** | High scorers → free one-week Agent Exposure and Spend Audit → security call → live residency session → pilot cohort → deployment. Medium scorers → security call plus the Compliance Evidence Pack. Low scorers → the regulation explainer series and quarterly re-scoring. |
| **Why it converts** | It does not argue for Wolffish. It measures two things, and both findings are **structurally unfixable inside a vendor-cloud AI product**. Cross-border exposure cannot be resolved by a better ChatGPT tier, because the data path is the product. Cost trajectory cannot be resolved on a metered plan, because the meter is the business model. The respondent reaches the conclusion without being led to it, which in a market this sceptical of vendor claims is worth more than any argument. |
| **Deviation from the source skill** | The skill specifies 5 to 7 questions. **Twelve are used**, because the score has two independent dimensions that must each be measured credibly. A six-question composite would produce a number a CISO would not take to an audit committee, and a number they will not carry internally has no value. |

---

## Questions

Twelve questions, four minutes. Arabic primary, English secondary. Six measure residency exposure,
six measure cost trajectory. Question order alternates between the two dimensions so the
instrument does not feel like two surveys stapled together.

| # | Dim. | Question | Answer options | Scoring | What it reveals |
|---|---|---|---|---|---|
| 1 | R | **Which AI tools are in use across your organisation today, sanctioned or not?**<br>ما أدوات الذكاء الاصطناعي المستخدمة لديكم اليوم، المعتمدة وغير المعتمدة؟ | (a) None that we know of · (b) One sanctioned tool · (c) Several sanctioned tools · (d) Sanctioned tools plus staff using personal accounts · (e) We do not know | a=0 · b=4 · c=8 · d=14 · e=**16** | "We do not know" scores highest. Unknown exposure is worse than known exposure, and stating that in the scoring is itself the first insight. |
| 2 | C | **What did your organisation spend on AI tools and API usage last month?**<br>كم أنفقتم على أدوات الذكاء الاصطناعي واستهلاك الواجهات البرمجية الشهر الماضي؟ | (a) Nothing · (b) Under SAR 10,000 · (c) SAR 10,000 to 50,000 · (d) Over SAR 50,000 · (e) It is spread across departments and we cannot total it | a=0 · b=3 · c=6 · d=9 · e=**12** | Fragmented departmental spend is the precursor to the surprise invoice, and it is extremely common. |
| 3 | R | **Which classes of data have your staff placed into an AI tool in the last 90 days?**<br>ما أنواع البيانات التي أدخلها موظفوكم في أدوات الذكاء الاصطناعي خلال التسعين يوماً الماضية? | (a) Public information only · (b) Internal documents · (c) Customer or employee personal data · (d) Regulated data: financial, medical or contractual · (e) We have no way to know | a=0 · b=5 · c=12 · d=**16** · e=14 | Options c and d are PDPL-regulated categories. This is the question most likely to change the respondent's afternoon. |
| 4 | C | **How many of your employees use an AI tool at least weekly?**<br>كم عدد موظفيكم الذين يستخدمون أداة ذكاء اصطناعي أسبوعياً على الأقل؟ | (a) Fewer than 10 · (b) 10 to 50 · (c) 50 to 200 · (d) Over 200 · (e) We do not measure it | a=2 · b=5 · c=8 · d=10 · e=**12** | Combined with Q2 this produces the per-employee cost baseline the result page projects forward. |
| 5 | R | **Do you hold a documented SDAIA-compliant basis for transferring personal data to your AI vendors outside the Kingdom?**<br>هل لديكم أساس موثّق ومتوافق مع سدايا لنقل البيانات الشخصية إلى موردي الذكاء الاصطناعي خارج المملكة؟ | (a) Yes, documented and reviewed by counsel · (b) We believe our vendor contract covers it · (c) We have not assessed it · (d) No · (e) I do not know what this refers to | a=0 · b=10 · c=14 · d=**16** · e=**16** | Option b is the most common answer and the most dangerous, because a vendor DPA is not a transfer basis. SDAIA has published no adequacy list. |
| 6 | C | **How has your AI spend changed over the last six months?**<br>كيف تغيّر إنفاقكم على الذكاء الاصطناعي خلال الأشهر الستة الماضية? | (a) Flat or down · (b) Up under 25 percent · (c) Up 25 to 100 percent · (d) More than doubled · (e) Not tracked | a=2 · b=5 · c=9 · d=**12** · e=11 | The growth rate is the input to the twelve-month projection, and it is usually much steeper than the respondent expects when they see it extrapolated. |
| 7 | R | **How is your data classified under the NDMO framework, and does that classification govern your AI tool decisions?**<br>كيف تُصنَّف بياناتكم وفق إطار مكتب إدارة البيانات الوطنية، وهل يحكم ذلك قراراتكم بشأن أدوات الذكاء الاصطناعي؟ | (a) Classified, and it governs AI decisions · (b) Classified, but AI decisions are made separately · (c) Classification in progress · (d) Not classified · (e) Unfamiliar with NDMO | a=0 · b=11 · c=13 · d=**16** · e=**16** | Option b is the single most common gap in Saudi enterprise: classification exists on paper and does not reach the AI decision. |
| 8 | C | **Are your AI tools billed per seat, per usage, or both?**<br>هل تُحتسب فواتير أدواتكم بالمقعد أم بالاستهلاك أم بكليهما؟ | (a) Per seat only, fixed · (b) Mostly per seat with some usage · (c) Significantly usage-based · (d) Mostly usage-based · (e) Mixed and unclear | a=2 · b=6 · c=10 · d=**12** · e=11 | Usage-based exposure is the mechanism behind every 2026 budget-overrun story. |
| 9 | R | **If your regulator asked today which employee sent which data to which AI system on a specific date, how long would it take to answer?**<br>لو سألكم الجهة التنظيمية اليوم عن أي موظف أرسل أي بيانات إلى أي نظام ذكاء اصطناعي في تاريخ محدد، كم تحتاجون للإجابة؟ | (a) Same day, from our own logs · (b) Within a week · (c) We would need to ask the vendor · (d) We could not answer · (e) We have never considered it | a=0 · b=6 · c=12 · d=**16** · e=15 | Option c is where most organisations sit, and it is the question that most reliably converts a CISO from curious to engaged. |
| 10 | C | **Do you enforce a hard cap on AI spend per user or per team, or do you rely on alerts?**<br>هل تفرضون سقفاً صارماً على إنفاق الذكاء الاصطناعي لكل مستخدم أو فريق، أم تعتمدون على التنبيهات؟ | (a) Hard enforced cap · (b) Alerts with manual intervention · (c) Monthly review only · (d) No control · (e) Not applicable, no usage billing | a=0 · b=8 · c=11 · d=**12** · e=3 | The difference between an alert and a cap is the difference between knowing the budget is gone and it never having been. |
| 11 | R | **Do your AI tools reach your internal systems — your own database, bespoke admin tools or legacy applications?**<br>هل تصل أدوات الذكاء الاصطناعي لديكم إلى أنظمتكم الداخلية وقواعد بياناتكم وأدواتكم المخصصة؟ | (a) Yes, with logged approval gates · (b) Yes, without action-level logging · (c) No, and this blocks our main use cases · (d) No, and we have not attempted it · (e) Unsure | a=0 · b=**16** · c=8 · d=6 · e=12 | Option b is the highest-risk state in the whole instrument: real system access with no attributed audit trail. |
| 12 | C | **If AI usage tripled across your organisation next year, what would happen to your bill?**<br>لو تضاعف استخدام الذكاء الاصطناعي ثلاث مرات العام القادم، ماذا سيحدث لفاتورتكم؟ | (a) Nothing, it is a fixed cost · (b) It would rise modestly · (c) It would roughly triple · (d) We do not know · (e) We would have to restrict usage | a=0 · b=5 · c=**12** · d=11 · e=**12** | Option e is the trap the whole product exists to escape: the organisation rationing exactly the behaviour that creates the value. |

**Maximum score: 168, normalised to 100 on the result page.**
Residency dimension maximum 96 → normalised to 100. Cost dimension maximum 72 → normalised to 100.

---

## Result tiers

The result page shows a composite **Kingdom AI Exposure Score** out of 100, plus the two sub-scores
displayed separately, plus a Saudi peer benchmark band. Sub-scores are shown because a respondent
can be low on one dimension and severe on the other, and the recommended action differs.

| Score range | Tier name | Arabic | Message | CTA |
|---|---|---|---|---|
| **0–39** | **Governed** | تحت السيطرة | You are ahead of most Saudi organisations. Your data classification reaches your AI decisions, you can answer a regulator from your own records, and your cost structure is not on an unforecast growth curve. Two things to watch as usage scales: enforced caps behave differently from alerts under load, and the first agentic use case will change your token profile by an order of magnitude overnight. | **Soft.** Download the six questions to ask any AI vendor. Join the monthly Saudi AI regulation briefing. Re-score in six months. |
| **40–69** | **Exposed** | منكشف | You have real exposure and it is the ordinary kind: classification that exists on paper but does not reach the AI decision, a vendor contract standing in for a transfer basis, and spend that is growing faster than anyone has projected. None of this is unusual. All of it is answerable, and it is considerably cheaper to answer before an auditor asks than after. | **Medium.** Book a 30-minute security call, with your security team in the room. Request the Compliance Evidence Pack: NCA ECC and CCC mapping, NDMO classification treatment, PDPL architecture note. |
| **70–100** | **Unmapped** | غير محدّد | Your organisation cannot currently answer, from its own records, which employee sent which data to which AI system. You also have no forecastable ceiling on what AI will cost you next year. Under PDPL, enforcement is active and SDAIA has issued 48 decisions in the past year. Under CCSPR, public-sector data may not leave the Kingdom even for caching. This is not a tooling problem you can buy your way out of with a better tier. It is an architecture question. | **Strong.** Request the free one-week Agent Exposure and Spend Audit. Founder-led, delivered to your CISO and CFO together, yours to keep whether or not you work with us. |

**Sub-score overrides.** If either sub-score exceeds 80 while the composite lands in a lower band,
the result page escalates to the higher tier's CTA and names the reason. A respondent with
negligible cost exposure and severe residency exposure needs the audit, and a composite score
would hide that.

---

## Post-scorecard sequence

**Saudi timing rules applied throughout.** The working week is Sunday to Thursday. **No sends on
Friday or Saturday.** During Ramadan (approximately 8 February to 8 March 2027), sends move to
21:00 to 23:00 Riyadh time, where engagement is materially higher, and no sends land during Eid
al-Fitr or Eid al-Adha. Email is the delivery medium; WhatsApp is where the reply happens, and the
sequence is built around that asymmetry rather than against it.

| # | Day | Channel | Subject line (EN / AR) | Content focus | CTA |
|---|---|---|---|---|---|
| **1** | 0 | Email, bilingual | *Your Kingdom AI Exposure Score: [score]/100* / *نتيجتكم في مقياس انكشاف الذكاء الاصطناعي: [score]/١٠٠* | Result delivery, both sub-scores, the Saudi peer benchmark band, and a plain-language reading of the two or three answers that drove the score. No selling. | Download your full result as a PDF you can circulate internally |
| **2** | 2 | Email, bilingual | *The one question your regulator will ask first* / *السؤال الأول الذي ستطرحه الجهة التنظيمية* | Deeper on Q9. What "we would need to ask the vendor" actually means when SDAIA has issued 48 decisions and has published no adequacy list. Includes the anonymised example of an organisation that could not answer within its own retention window. | Read the PDPL and CCSPR briefing |
| **3** | 5 | Email, bilingual | *What your AI bill looks like in twelve months* / *كيف ستبدو فاتورة الذكاء الاصطناعي لديكم بعد اثني عشر شهراً* | Their own Q2, Q4 and Q6 answers extrapolated to a twelve-month projection with the arithmetic shown. Then the 2026 record: 78 percent surprise charges, Uber's exhausted budget, the thousand-times token ratio. **Three-line landed-cost comparison, pass-through named.** | Model your own landed cost in the calculator |
| **4** | 8 | Email, bilingual | *Both of these have one fix, and it is not a better tier* / *لكليهما حلٌّ واحد، وليس باقة أفضل* | The synthesis. Cross-border exposure cannot be fixed by upgrading a vendor cloud, because the data path is the product. Cost trajectory cannot be fixed on a metered plan, because the meter is the business model. Then, briefly, what an in-perimeter architecture with an enforced cap does to both. First and only mention of Wolffish as a product. | Book a 30-minute security call, with your security team in the room |
| **5** | 12 | **WhatsApp**, only if introduced or if a number was volunteered | — | A personal message from the founder, not a template. One line referencing their actual score and one specific finding. Offers a 90-second Arabic voice note explaining the architecture. | Reply here, or book directly |
| **6** | 30 | Email | *Three things that changed in Saudi AI regulation this month* / *ثلاثة تغييرات في تنظيم الذكاء الاصطناعي بالمملكة هذا الشهر* | Entry into the ongoing monthly briefing. No CTA beyond staying subscribed. | — |
| **7** | 180 | Email | *Has your exposure changed? Re-score in four minutes* / *هل تغيّر انكشافكم؟ أعيدوا القياس في أربع دقائق* | Re-score invitation. Shows their previous score and offers a comparison. | Re-take the scorecard |

**Sequence rules.**
Stop the sequence immediately on a booked call. Never send more than two emails in a week. **Never
use WhatsApp before an introduction or a volunteered number** — an unsolicited WhatsApp message to
a Saudi executive costs more goodwill than any email ever recovers. Every email is signed by the
founder personally, from a personal address, and every reply is answered by the founder. **At the
volumes this instrument produces, roughly 150 completions a quarter, that is possible, and it is
the whole point.**

---

## Implementation notes for ScoreApp

| Item | Specification |
|---|---|
| Language | Arabic default for Saudi IP and Arabic browser locale; English toggle always visible. **Not** an English default with an Arabic option. |
| Layout | Full RTL for Arabic, verified on real iOS and Android devices before GAIN. RTL rendering of mixed Arabic and Latin numerals must be checked specifically, as it is the most common failure. |
| Lead capture | **After the score is shown, not before.** Gating the score behind a form roughly halves completion and, more importantly, breaks the promise that the instrument is useful in its own right. |
| Fields captured | Name, work email, organisation, role, headcount band. **Not** phone number — asking for a phone number before a relationship exists reads as intrusive in this market and depresses completion. |
| Result page | Composite score, both sub-scores, peer benchmark band, the three answers that drove the score, tier message, tier CTA. Under 400 words in each language. |
| PDF export | Branded, bilingual, formatted to be forwarded internally to someone with no context. **This is the real conversion asset** — the CISO forwards it to the CFO, and the CFO reads it cold. |
| Benchmark data | Seeded from the GASTAT, SAP and PwC figures in `00-RESEARCH-DOSSIER.md`, then replaced with real respondent data once n exceeds 50. **Label it as modelled until then.** |
| Analytics | Completion rate, drop-off by question, score distribution, ICP-match rate, call-booking rate by tier. |
| Integration | ScoreApp to email platform to a simple CRM. **No automated LinkedIn or dialler integration** — see Dashboard 08, caveat C4. |
| Launch deadline | **Live before GAIN, 15 September 2026.** This is eleven days out and it is the constraint that sets the build priority in Dashboard 08. |
