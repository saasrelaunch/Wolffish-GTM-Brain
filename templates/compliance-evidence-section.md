# Template, one section of the Compliance Evidence Pack

Audience: the security officer, their team, and the counsel or risk function reading behind them.
The pack is the single largest unbuilt asset in the plan and the one that makes the second
evaluation materially shorter than the first. Instruments: `../reference/saudi-regulatory-file.md`.

## One section per control framework
The pack is assembled section by section, one per instrument that governs the entities in the
pipeline. A section written for a bank does not serve a ministry, so write the section the account
in front of you needs and add the others as accounts arrive.

## Structure of a section
- **The instrument, named exactly,** with its issuing body and the version or year in force.
- **What it requires,** stated in the instrument's own language, not paraphrased into marketing
  terms. Cite the article or control number.
- **How the architecture meets it.** The mechanism, not the intention. Where the data sits, which
  component enforces it, what the audit log records.
- **What the customer must do.** Every framework leaves obligations with the customer, and naming
  them is the difference between an evidence pack and a brochure.
- **What is not yet met, and when.** Any control the current build does not satisfy, stated
  plainly with its status flag. A pack that claims full coverage of everything is disbelieved in
  full.
- **The artefact.** The diagram, log sample, configuration or contract clause that a reviewer can
  attach to their own file.

## Fields to fill
- Instrument: [name, issuing body, version in force]
- Entity class this section serves: [bank, government entity, listed company, other]
- Controls addressed: [numbers]
- Controls not met: [numbers, with status and expected date]

## Standing constraints
Certification language follows the permitted forms in `../rules/do-not-say.md` exactly. Alignment
with a framework and certification against it are different claims and only one of them is true.

Personal data never crosses the border in this architecture, so no transfer mechanism is claimed
or required. Say the mechanism, not the reassurance.

This pack is reviewed by Saudi counsel before its first external use. Until that review is
recorded in `../ops/decisions.md`, the pack is internal.

Guardrail: every control claim traces to the instrument text, every capability to
`../rules/feature-status.md`, and the section passes `../ops/QA-checklist.md` before it is filed
into a customer's evaluation.
