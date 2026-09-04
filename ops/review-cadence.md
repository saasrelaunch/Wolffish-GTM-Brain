# Review cadence

Who reviews what, how often, and when a file is considered stale. Agreed 2026-09-04.

This is a two-person company, so every owner below is the founder until somebody else exists. That
is not a reason to skip the ritual. It is the reason to keep it short enough to actually happen.

## Rituals

| Ritual | Frequency | Owner | Work |
|---|---|---|---|
| Signal triage | Weekly, Sunday | Founder | Disposition every new signal, increment WATCH counters, execute PATCHes, expire dead WATCH items |
| Ledger sweep | Monthly, first Sunday | Founder | Read all four `../rules/` files against reality, update `last_reviewed`, regenerate the portable control layer if anything moved |
| Snapshot | Quarterly | Founder | The full capture in `../snapshots/`, ending in what it changed or an explicit note that nothing did |
| Master context version | Quarterly, or on any AMEND | Founder | Bump the version, refresh `status_notes`, verify the sections against the ledgers |
| Brain audit | Quarterly | Founder | Run the audit script, then produce one live asset using only the brain |
| Account list review | Quarterly | Founder | The twenty named accounts: who moved, who left, who was added, against a delivery ceiling of four to six |

## Ledger ownership and staleness

| File | Owner | Stale after |
|---|---|---|
| `../rules/feature-status.md` | Founder, as product | 30 days |
| `../rules/do-not-say.md` | Founder, with Saudi counsel on anything contractual | 90 days |
| `../rules/glossary.md` | Founder | 90 days |
| `../rules/writing-rules.md` | Founder | 180 days |
| `../context/Wolffish_GTM_Master_Context.md` | Founder | 90 days |
| `../adapters/portable-control-layer.md` | Founder | Regenerated on every ledger change, and stale after 90 days regardless |
| `../reference/saudi-regulatory-file.md` | Founder, with Saudi counsel | 90 days, and immediately on any instrument change |

Staleness is not a formality. `feature-status.md` goes stale fastest and its staleness does the most
damage, because it is the only thing standing between a roadmap and a promise.

`saudi-regulatory-file.md` is the second most dangerous. The instruments in this market are young
and they move. An adequacy list published under the personal data law would change the central
argument of this entire go-to-market inside a week, which is why a regulatory signal acts on one
verified instance rather than three.

## Authority

- A PATCH can be made by anyone producing work.
- An AMEND to any file in `../rules/` requires the founder.
- A change to positioning, the ICP or the channel mix requires the founder and a dated entry in
  `decisions.md`.
- Any compliance wording that enters a contract, a tender submission or the evidence pack requires
  Saudi counsel before external use, recorded here as a dated line.

## The failure mode this cadence exists to prevent

The brain drifts silently. Nothing in it announces that it has gone wrong. A capability ships and
the ledger still says IN BUILD, or an instrument changes and the regulatory file still describes the
old one, and every asset produced in between inherits the error while looking exactly as
authoritative as a correct one. The rituals above are cheap. Discovering the drift in front of a
security officer is not.
