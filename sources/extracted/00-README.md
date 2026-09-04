# Wolffish Cloud — Saudi Go-To-Market Suite

**v1.0 · 4 September 2026 · Kingdom of Saudi Arabia only**

Built by running the `gtm-builder` skill (v3.1.0) against this repository's two source documents,
with four adaptations requested at the outset and applied throughout.

## The four adaptations

1. **This is not SaaS.** Wolffish is an agentic harness plus a platform control plane plus a cloud
   service, so every feature, benefit, score and price is tagged to a layer and the layers are never
   averaged. A fourth layer, Saudi regulatory and commercial fit, has no equivalent in the source
   skill and was added because in this market it closes deals the product alone would lose.
2. **The caveats are built into every dashboard.** Each of the nine dashboards, the lead magnet
   specification, the research dossier and the walkthrough deck opens with the same five standing
   caveats, restated in terms specific to that dashboard. They also appear as the first sheet of
   every exported workbook and the first section of every exported document, so no artefact can be
   read without them.
3. **The offer metrics were read carefully rather than accepted.** `00-OFFER-METRICS-AUDIT.md`
   challenges six things in the Service and Offer Matrix, including one — ongoing capability
   development priced as a free door opener while committing unbounded senior engineering time
   against a fixed recurring price — that is the largest hidden margin risk in the business model.
4. **Saudi judgment replaces generic instruction where the two conflict.** Six deliberate
   deviations from the skill are listed below, each argued at the point it occurs.

## Deliberate deviations from the source skill

| # | Skill says | This suite does | Why |
|---|---|---|---|
| 1 | Three steps require external deep research by the user | All three executed in-session against live sources | The research is the foundation. Handing back a research brief instead of research would have produced a template, not a GTM. |
| 2 | Four positioning vectors | **Five**, adding *Sovereign Legitimacy and National Mandate* | In the Kingdom this vector decides deals. Omitting it produces a map that flatters Wolffish and then loses in the room. |
| 3 | Pricing tiers as Decoy / Hero / Anchor with a free entry tier | **Deployment scope ladder plus in-account seat expansion** | There is no free tier, no self-serve upgrade and a customer count in single digits. A percentage-of-customers target is meaningless at n=5. |
| 4 | Channels: HeyReach LinkedIn automation, Instantly cold email, LinkedIn Ads | **Replaced** with events, warm introduction, founder-led organic, WhatsApp, channel partner, Etimad, owned | Volume instruments deployed against a capacity ceiling of four to six deployments a year, in a market where automation reads as disrespect. |
| 5 | Three buying-committee personas | **Seven** for ICP 1, **ten** for ICP 2 | The CISO holds a real veto, procurement applies a process a foreign-invoiced vendor fails, and the relationship sponsor decides how everyone else first hears about you. |
| 6 | Lead magnet scorecard of five to seven questions | **Twelve**, across two independent scored dimensions | A six-question composite produces a number a CISO will not carry to an audit committee, and a number they will not carry has no value. |

## Files

| File | What it is | Exports |
|---|---|---|
| `00-CAVEATS.md` | The five standing caveats, canonical | — |
| `00-RESEARCH-DOSSIER.md` | Skill steps 1.1, 2.1 and 2.7 executed, plus the Saudi regulatory, procurement, demand, cost, calendar and infrastructure files | `research_dossier.xlsx` |
| `00-OFFER-METRICS-AUDIT.md` | Six findings against the Service and Offer Matrix, plus the corrected matrix this suite runs on | `offer_metrics_audit.xlsx` |
| `01-product-feature-matrix.md` | Dashboard 01. 36 features across four layers, scored, quadranted, validated. Demand driver and six variants. | `product_feature_matrix.xlsx` |
| `02-competitive-analysis.md` | Dashboard 02. Seven competitors, five positioning vectors, 18-capability grid, benefit potency, category summary | `competitive_analysis.xlsx`, `positioning_summary.docx` |
| `03-positioning.md` | Dashboard 03. Category claim, six positioning statements, message hierarchy, the "we are not" list, objection reversal | `positioning_statements.docx` |
| `04-icp.md` | Dashboard 04. Two ICP levels with eleven Saudi attributes, anti-ICP, twenty-account target map, seat economics | `icp_dashboard.xlsx` |
| `05-buying-committee.md` | Dashboard 05. Seven personas for ICP 1, ten for ICP 2, committee choreography, design partner profile | `buying_committee.xlsx` |
| `06-value-proposition.md` | Dashboard 06. Brand promise, three pillars, nine reasons to believe, nine copy drills, bilingual | `value_proposition.docx` |
| `07-customer-journey.md` | Dashboard 07. Seven stages with the security call moved to stage two, mapped to twenty-five sellable Saudi weeks | `customer_journey.xlsx` |
| `08-assets-library.md` | Dashboard 08. Seven Saudi channels, full-funnel assets, ninety-day build sequence | `assets_library.xlsx` |
| `09-pricing-packaging.md` | Dashboard 09. Value metric, deployment ladder, capability allowance, Saudi commercial mechanics, three ROI anchors | `pricing_dashboard.xlsx` |
| `10-lead-magnet-spec.md` | Kingdom AI Exposure Scorecard for ScoreApp, bilingual, twelve questions, seven-step sequence | `lead_magnet_spec.xlsx`, `scorecard_spec.docx` |
| `11-gtm-walkthrough-deck.md` | Ten slides for Gamma AI | `gtm_walkthrough.md` |
| `wolffish-kingdom-gtm.html` | The whole suite as one tabbed dashboard, published at [claude.ai/code/artifact/543adf52](https://claude.ai/code/artifact/543adf52-3100-42c9-a48b-1488458dab4b). Fourteen panels, four charts on the real data, the caveat strip pinned into every panel. | — |
| `build/build_exports.py` | Regenerates all exports from the markdown | — |

Markdown is the source of truth. To regenerate everything: `python3 gtm/build/build_exports.py`
(requires `openpyxl` and `python-docx`).


## Google Drive folder library — `gtm/library/`

Twelve deliverables rebuilt in the client's house format, matched cell-for-cell to the five
HealthPlanChat reference documents supplied: Arial throughout, the navy `1F2A44` header rows,
amber `F2C14E` section banners, pale-blue `EAEEF5` attribute columns, cream `FFF6E6` highlight
cells for Wolffish's own claims, and the blue and peach palettes for the journey and assets
workbooks respectively. The five standing caveats open every file.

| File | Format | Reference it matches |
|---|---|---|
| `Wolffish_00_Folder_Index.docx` | DOCX | new — folder cover, reading order, provenance |
| `Wolffish_ICP_Dashboard.xlsx` | XLSX | HealthPlanChat_ICP_Dashboard |
| `Wolffish_Competitive_Market_Analysis.xlsx` | XLSX | HealthPlanChat_Competitive_Market_Analysis |
| `Wolffish_Customer_Journey_Funnel.xlsx` | XLSX, 3 sheets | HealthPlanChat_Customer_Journey_Funnel |
| `Wolffish_Value_Proposition_Framework.docx` | DOCX | HealthPlanChat_Value_Proposition_Framework |
| `Wolffish_Marketing_Assets_Library.xlsx` | XLSX | HealthPlanChat_Marketing_Assets_Library |
| `Wolffish_Positioning_Framework.docx` | DOCX | house DOCX style |
| `Wolffish_Product_Feature_Matrix.xlsx` | XLSX | house XLSX style, quadrant colour-coding added |
| `Wolffish_Pricing_and_Packaging.xlsx` | XLSX | house XLSX style |
| `Wolffish_Lead_Magnet_Scorecard_Spec.xlsx` | XLSX | house XLSX style |
| `Wolffish_Offer_Metrics_Audit.xlsx` | XLSX | house XLSX style |
| `Wolffish_GTM_Walkthrough_Deck.md` | MD | for Gamma AI |

`gtm/Wolffish_GTM_Library.zip` is the whole folder, ready to drop into Drive.
Regenerate everything: `for f in gtm/build/lib_0*.py; do python3 "$f"; done`
(requires `openpyxl` and `python-docx`; shared style in `gtm/build/house.py`).

## The five numbers that shape everything

| Number | What it is |
|---|---|
| **4 to 6** | Deployments possible in the first twelve months. One principal, six to eight weeks each. This is the binding constraint on the whole GTM, and it is why the plan targets twenty named accounts rather than a funnel. |
| **200 seats** | Hard qualification floor. Year-one revenue is SAR 60,000 + SAR 948 per seat while deployment consumes the same principal time regardless. Below 200, the engagement cannot repay the time. |
| **25** | Sellable weeks in a Saudi twelve-month period, once Ramadan, the two Eids and the summer are removed. A plan assuming forty-eight is wrong by forty percent of the year. |
| **0.77 percent** | Productivity improvement across 300 knowledge workers that repays the entire landed cost of the platform for a year. |
| **11 days** | From this document's date to GAIN, 15 to 17 September 2026. It sets the asset build sequence in Dashboard 08. |

## Open actions before any of this is treated as validated

1. Reconcile the Younes and Ali blocks of the Service and Offer Matrix. Everything downstream hangs
   on which framing is the category.
2. **Agree and contract the capability allowance.** This is the most urgent item in the suite.
   Until it exists, the business sells unbounded senior engineering time against a fixed price.
3. Approve the deployment scope ladder and the 200-seat qualification floor.
4. Pre-package escrow and appoint the agent, so it stops being the longest pole in the deal.
5. Decide whether the Agent Exposure and Spend Diagnostic ships as a founder-led read, a ScoreApp
   self-assessment, or both. This suite assumes both.
6. Kill or restaff the Managed Optimization Retainer.
7. Ship the Kingdom AI Exposure Scorecard before 15 September 2026.

---

*Younes Alturkey · Founder & Engineer, Wolffish · younes@wolffi.sh · +966 53 865 4514 · wolffi.sh/cloud*
