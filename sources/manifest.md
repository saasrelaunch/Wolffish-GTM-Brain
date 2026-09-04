# Source manifest

What each source artifact settles, and where it landed in this brain. Written during Phase 1 of
the build, before any distillation, so that a later disagreement can be resolved by opening the
source rather than by argument.

Build date: 2026-09-04. All sources dated September 2026 unless noted.

| Artifact | Type | What it settles | Destination |
|---|---|---|---|
| Wolffish Business Model, Pricing and Value Prop | MD, PDF | The three price lines, landed cost by headcount, competitor cost models, token ceilings, the integration argument, the eight reasons to choose | `context/`, `rules/feature-status.md`, `reference/pricing-model.md` |
| Service and Offer Matrix | XLSX, two rated blocks | What is sold, and by two people who describe two different companies. Unreconciled. | `reference/offer-metrics-audit.md`, `ops/decisions.md` |
| 00-OFFER-METRICS-AUDIT | MD | Six findings against the Service and Offer Matrix, the corrected offer stack this brain runs on | `reference/offer-metrics-audit.md`, `ops/decisions.md` |
| 00-RESEARCH-DOSSIER | MD | The Saudi regulatory, procurement, demand, cost and calendar file. Competitor research. | `reference/saudi-regulatory-file.md`, `reference/competitive-analysis.md` |
| 01-product-feature-matrix | MD, XLSX | Which capability leads messaging, which is table stakes, the four-layer split, the demand driver | `reference/feature-matrix.md`, `rules/feature-status.md` |
| 02-competitive-analysis | MD, XLSX | Seven-competitor set, five positioning vectors, the eighteen-capability grid, the wedge | `reference/competitive-analysis.md`, `reference/competitor-battlecards.md` |
| 03-positioning | MD, DOCX | Category claim, six positioning statements, message hierarchy, objection reversals | `reference/positioning.md`, `ops/copy-bank.md` |
| 04-icp | MD, XLSX | Two ICP stages, eleven Saudi attributes, the anti-ICP, the twenty-account target map, seat economics | `reference/icp-personas.md` |
| 05-buying-committee | MD, XLSX | Seven personas for ICP 1, ten for ICP 2, the committee sequence, the design partner profile | `reference/icp-personas.md`, `reference/customer-journey.md` |
| 06-value-proposition | MD, DOCX | Brand promise, three pillars, nine reasons to believe, bilingual copy at three registers | `reference/value-proposition-icp1.md`, `reference/value-proposition-icp2.md`, `ops/copy-bank.md` |
| 07-customer-journey | MD, XLSX | Seven stages per audience, the security-call-first sequence, the Saudi selling calendar | `reference/customer-journey.md` |
| 08-assets-library | MD, XLSX | Seven channels, the three excluded channels, the ninety-day build sequence | `reference/marketing-campaigns.md`, `reference/relationship-engine.md` |
| 09-pricing-packaging | MD, XLSX | Value metric, deployment scope ladder, capability allowance, Saudi commercial mechanics, ROI anchors | `reference/pricing-model.md`, `rules/do-not-say.md` |
| 10-lead-magnet-spec | MD, XLSX | The Kingdom AI Exposure Scorecard: twelve questions, three tiers, the seven-step sequence | `reference/lead-magnet.md` |
| 11-gtm-walkthrough-deck | MD | The ten-slide summary for Gamma | `pages/gtm-walkthrough-deck.md` |
| Google Drive library | 8 XLSX, 3 DOCX | The client-facing format of everything above. Same content, house formatting. | `sources/raw/library/`, indexed in `ops/asset-index.md` |

## Conflicts found and how they were resolved

**One conflict, and it is material.** The Service and Offer Matrix contains two self-rated blocks
by two people describing two different companies. The founder block describes a deployed agent
platform inside the customer's perimeter, which matches the pricing document exactly. The second
block describes an AI agent spend-governance vendor, and not one of its five rows appears in the
pricing document at any price, in any tier, under any name. The sheet itself flags the second
block as a first-pass read rather than a live product audit.

Resolved with the user during the GTM build: the founder block is treated as the sold product.
The second block is held as a candidate adjacent offer, flagged, not merged. Two of its five rows
survive in altered form. Recorded as a dated decision in `ops/decisions.md` and still open for
confirmation on the review call.

## Open questions carried forward

These were not answered by any source and are recorded in `ops/decisions.md` under open items
rather than invented here.

1. The capability allowance that bounds ongoing capability development. Proposed, not contracted.
2. Whether the Agent Exposure and Spend Diagnostic ships founder-led, as a self-assessment, or both.
3. The exact current state of Arabic-first coverage per surface.
4. Escrow agent selection.
5. Whether the second offer block is confirmed or rejected as a category.
