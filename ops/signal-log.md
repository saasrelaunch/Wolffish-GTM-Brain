# Signal log

Raw market input, captured before judgment. Every signal from a lead, prospect, customer, partner,
competitor, regulator or channel lands here first, whatever it turns out to mean. Newest at the top.

Capture is cheap on purpose. A signal that gets debated before it gets written down does not get
written down.

**Keep the verbatim, in the language it was said in.** Do not paraphrase a buyer into house
vocabulary and do not translate an Arabic phrase into an English one. The language a real buyer
used before we taught them ours is the most valuable thing a signal carries, and it cannot be
recovered later.

## How to use this file

**Types:** OBJECTION, LANGUAGE, PROOF, STATUS, COMPETITIVE, SEGMENT, CHANNEL, LOSS, RISK,
REGULATORY.

**Dispositions:**
- `NOISE`, one instance, no pattern, no action. Logged and closed.
- `WATCH (n/N)`, a plausible pattern awaiting corroboration. Increment as instances arrive.
- `PATCH`, changes copy but not strategy. Route it, edit, done. No decision entry.
- `AMEND`, changes a ledger, a position or a rule. Follow the full amendment procedure and write a
  `decisions.md` entry.

**Corroboration thresholds**, agreed 2026-09-04, see `review-cadence.md`:

| Signal class | Threshold to act |
|---|---|
| Opinion, preference, language, objection | 3 independent instances within 60 days |
| Verifiable fact: status, proof, competitive, risk | 1 verified instance, act immediately |
| Regulatory change | 1 instance, verified against the instrument text, act immediately |
| Loss reason | 2 instances, or 1 if the deal was in the core ICP |
| Channel performance | A full measurement cycle, never a single week |

Default disposition is NOISE. A brain that amends on every input has no memory, and one that
flip-flops on the last conversation is worse than a static document.

Triage runs weekly, on Sunday, which is the first working day of the Saudi week. A WATCH item that
has not incremented in two cycles expires to NOISE and the expiry is written into the log.

**A note on the ICP 1 threshold.** Three independent instances is a high bar against a named list
of about twenty accounts. Where a signal comes from inside that list, two instances is enough and
the entry says so.

---

## Entries

### 2026-09-04 | REGULATORY | source: cloud computing regulatory framework, published text
**Verbatim:** "may not be transferred outside the Kingdom for any purpose, permanently or
temporarily, including caching and redundancy"
**Context:** Applies to public-sector data. Read during the build, not from a buyer.
**Disposition:** AMEND, verified against the instrument.
**Routed to:** `../rules/feature-status.md`, the architectural row. `../reference/saudi-regulatory-file.md`.
`../ops/copy-bank.md` proof points. It is also the spine of the first founder post.

---

### 2026-09-04 | RISK | source: the offer and service matrix, internal
**Verbatim:** two self-rated blocks by two people, describing two different companies, in one sheet
**Context:** Found in Phase 1 of the build. The second block describes a spend-governance vendor
whose rows appear nowhere in the pricing document.
**Disposition:** AMEND.
**Routed to:** `decisions.md`, the offer matrix entry. `../reference/offer-metrics-audit.md`. Open
for confirmation on the next review call.

---

### 2026-09-04 | RISK | source: the offer matrix, ongoing capability development row
**Verbatim:** rated as a free door opener
**Context:** The row commits unbounded senior engineering against a fixed recurring price. Four
customers can consume a full principal year.
**Disposition:** AMEND.
**Routed to:** `../rules/do-not-say.md`, which now bans the phrase "no new invoice" until an
allowance is contracted. `decisions.md`, open item one.

---

### 2026-09-04 | COMPETITIVE | source: public announcement record
**Verbatim:** Saudi cloud region announced for the fourth quarter of 2026
**Context:** Microsoft. Announced, not live. Repeating a stale version of this in front of a Saudi
buyer is an avoidable credibility loss.
**Disposition:** PATCH.
**Routed to:** `../reference/competitor-battlecards.md` and the proof points in `copy-bank.md`,
both of which now carry the announced-not-live wording.

---

### 2026-09-04 | CHANNEL | source: the Saudi calendar, build analysis
**Verbatim:** roughly twenty-five sellable weeks out of forty-eight
**Context:** Two fixed event dates carry the year and Ramadan removes a month of enterprise
decision-making.
**Disposition:** AMEND.
**Routed to:** `../reference/customer-journey.md`, the calendar section, and the build sequence in
`../reference/marketing-campaigns.md`.

---

*No customer-sourced signal exists yet, because there is no customer yet. The first security call
produces the first real entry, and the sections of `copy-bank.md` marked empty fill from here.*

*An empty signal log after a month of selling means the loop is not running.*
