# Asset index

Where the source deliverables, live surfaces and adapters live. This is the file an amendment
consults to find everything carrying an old claim, so keep it current. A claim that changes in the
ledger and not on a surface listed here is still a live claim.

## Source deliverables

The artifacts this brain distils. Originals in `../sources/raw/library/`, machine-readable dumps in
`../sources/extracted/`, and the per-artifact reading in `../sources/manifest.md`.

| Artifact | Type | What it settles | Dated |
|---|---|---|---|
| Product Feature Matrix | XLSX | What leads messaging and what is table stakes | 2026-09 |
| Competitive Market Analysis | XLSX | Market shape, scoring vectors, the wedge | 2026-09 |
| Positioning Framework | DOCX | Category, the fork, the one-line statement | 2026-09 |
| ICP Dashboard | XLSX | Who is sold to, who is disqualified | 2026-09 |
| Buying committee, inside the ICP build | XLSX | Six roles, the sequence, who blocks | 2026-09 |
| Value Proposition Framework | DOCX | Pillars and reasons to believe, per audience | 2026-09 |
| Customer Journey Funnel | XLSX | Seven stages per audience, with the calendar | 2026-09 |
| Marketing Assets Library | XLSX | Channel shares and the build sequence | 2026-09 |
| Pricing and Packaging | XLSX | Three lines, landed cost, the scope ladder | 2026-09 |
| Offer Metrics Audit | XLSX | Six findings, including the unreconciled matrix | 2026-09 |
| Lead Magnet Scorecard Spec | XLSX | The Kingdom AI Exposure Scorecard | 2026-09 |
| GTM Walkthrough Deck | MD | The ten-slide narrative | 2026-09 |
| Folder Index | DOCX | The library map as delivered to the founder | 2026-09 |

The go-to-market build that produced these, including the dashboards in Markdown and the HTML
dashboard suite, lives in the WolffishGTMbuild repository.

## Product and brand

- Live product or service surface: not yet published. Record the URL here on first publish.
- Architecture diagram, the artefact sent before every security call: to be produced, owner founder.
- Screenshots and demo assets: only SHIPPED capabilities may be captured. See the demonstration ban
  in `../rules/feature-status.md`.
- Brand and design system: the house format used in the delivered library. Colour-coded workbooks
  and documents, one caveat block first in every file.

## Live surfaces, every place a claim is published

None yet. The list below is what will exist, and each line gets a URL and a last-reviewed date the
day it goes live.

- Bilingual site, Arabic first: pending, see `../templates/site-page.md`.
- Kingdom AI Exposure Scorecard: pending, see `../reference/lead-magnet.md`.
- Landed cost calculator: pending.
- Founder profiles on the writing channel: pending.
- One-page bilingual leave-behind, two versions: pending, see `../templates/one-pager.md`.
- Compliance Evidence Pack: IN BUILD, internal until Saudi counsel has reviewed it.
- Long-form landing page, security officer version: drafted, not published. Markdown and DOCX in
  `../pages/`. Every figure in it reconciles to `../reference/pricing-model.md`, so grep it first
  when a price changes.

## Adapters, and who runs which tool

Each adapter is a pointer of about twenty lines that carries no strategy, no claim and no status.
The tool list is assumed rather than confirmed, which is an open item in `decisions.md`.

| Tool | File | Installed where | Who runs it |
|---|---|---|---|
| Claude Code, Claude apps | `../CLAUDE.md` | This repository root | Founder, and this build |
| Codex, Zed, Jules, opencode | `../AGENTS.md` | This repository root | Unconfirmed |
| Cursor | `../adapters/cursor.mdc` | Copy to `.cursor/rules/` in the consuming repository | Unconfirmed |
| Windsurf | `../adapters/windsurf.md` | Copy to `.windsurf/rules/` | Unconfirmed |
| GitHub Copilot | `../adapters/copilot-instructions.md` | Copy to `.github/` | Unconfirmed |
| Gemini | `../adapters/GEMINI.md` | Consuming repository root | Unconfirmed |
| Any chat model, no file access | `../adapters/portable-control-layer.md` | Pasted | Founder |

The portable control layer carries content rather than a pointer, so it decays. It is dated in its
own header, regenerated as the last step of every amendment, and checked on the ledger cycle in
`review-cadence.md`.

## Related engagements, questions this brain defers

- **Saudi counsel.** The Compliance Evidence Pack, the escrow deed, and any compliance wording that
  enters a contract or a tender submission.
- **The capability allowance.** Founder and counsel, open item one in `decisions.md`.
- **Escrow agent selection.** Founder and counsel, open item four.
- **Product, on Arabic-first coverage per surface.** Open item three.

## What this brain distils

`../context/Wolffish_GTM_Master_Context.md` is the single distilled source. When a source artifact
changes, the change lands in the relevant ledger in `../rules/` first, then the master context,
then here.
