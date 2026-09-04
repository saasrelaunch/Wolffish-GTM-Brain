# Examples, the approved voice reference

Gold-standard output, one per major asset type. These are the few-shot reference an agent matches
before writing anything new, and they do more work than any amount of tone description.

Each file holds the asset first and a short "why this works" second. Read both. The annotation is
what makes the voice teachable rather than only imitable.

| File | Asset type | Template it demonstrates |
|---|---|---|
| `founder-post-cloud-rules.md` | Bilingual founder post, instrument explainer archetype | `../templates/founder-post.md` |
| `forwardable-paragraph.md` | The paragraph a sponsor pastes into an introduction | `../templates/warm-introduction.md` |
| `landed-cost-email.md` | The cost breakdown that reaches a finance director | `../templates/landed-cost-email.md` |
| `one-pager-security-officer.md` | Bilingual leave-behind, security officer version | `../templates/one-pager.md` |
| `messaging-followup.md` | The message after an introduction lands | `../templates/messaging-followup.md` |
| `objection-response-price.md` | A written answer to the recurring price objection | `../reference/objection-handling.md` |

## Status of these examples
Written during the build on 2026-09-04 and approved as the voice reference. They contain no
customer name, quote, metric or count, because there is no reference customer. When one exists,
these get revised rather than replaced, and the revision is recorded in `../ops/decisions.md`.

Every figure in these examples reconciles to `../reference/pricing-model.md`. If a price changes,
grep this directory before anything else, because an approved example is copied without a second
look. That is what makes it useful and what makes it dangerous when it goes stale.
