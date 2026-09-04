# Capability status ledger

last_reviewed: 2026-09-04

**Update this file the moment status changes, before any copy follows.** Checked on every
capability mention. A capability without a flag in the same sentence is a claim nobody checked.

Legend. **SHIPPED** live now, present tense allowed. **PARTIAL** partly live, say what works
today and nothing more. **IN BUILD** committed and unshipped, mark as coming or omit.
**ROADMAP** vision, never a launch claim.

## Agentic harness

| Capability | Status |
|---|---|
| Persistent per-employee agent on the employee's own machine | SHIPPED |
| File read and write on the device, scoped per role | SHIPPED |
| Shell and command execution under per-role scopes | SHIPPED |
| Approval gates on sensitive actions, human in the loop | SHIPPED |
| Multi-step autonomous execution | SHIPPED |
| Local context ingestion, the employee's own files, never uploaded | SHIPPED |
| Model portability across zero-retention endpoints | SHIPPED |
| Arabic interface, prompting and output | PARTIAL |
| Arabic document handling and Hijri dates | PARTIAL |
| Chat and retrieval over company documents | SHIPPED |
| Native mobile application | ROADMAP, and deliberately not pursued |

## Platform control plane

| Capability | Status |
|---|---|
| Hard token quota per user, team and period, enforced as a cap | SHIPPED |
| Action-level audit log written to the customer's own store | SHIPPED |
| Kill switch, per user and global | SHIPPED |
| Single sign-on, directory sync, automated offboarding | SHIPPED |
| Admin console with per-role and per-agent scopes | SHIPPED |
| Spend visibility by team and by task | SHIPPED |
| Branded single-tenant deployment | SHIPPED |
| Usage analytics beyond spend | ROADMAP, and deliberately not pursued |

## Cloud service

| Capability | Status |
|---|---|
| Deployment engineering with a pilot cohort before rollout | SHIPPED |
| First-class integration into internal, bespoke and legacy systems | SHIPPED |
| Ongoing capability development inside the seat fee | SHIPPED, but see the caution below |
| Service level, 99.5 percent uptime and four-hour P1 response | SHIPPED |
| Source access and escrow | PARTIAL, the deed is drafted and no agent is appointed |
| Deployment scope ladder, three tiers | IN BUILD, proposed and not yet contracted |
| Capability allowance, the quarterly bound | IN BUILD, proposed and not yet contracted |

## Saudi regulatory and commercial fit

| Capability | Status |
|---|---|
| Saudi commercial registration and riyal contracting | SHIPPED |
| ZATCA-compliant electronic invoicing | SHIPPED |
| Saudi jurisdiction and Arabic contracting | SHIPPED |
| Personal data never crosses the border, so no transfer mechanism is required | SHIPPED, architectural |
| No public-sector data leaves the Kingdom, including for caching | SHIPPED, architectural |
| Compliance Evidence Pack, the assembled document set | IN BUILD, six weeks, the largest unbuilt asset |
| Support for a sovereign in-Kingdom inference endpoint | SHIPPED as a model option |
| SOC 2, ISO 27001 or equivalent certification | NOT HELD. See the claim ledger. |

## Cautions

**Ongoing capability development** is flagged SHIPPED as a capability and IN BUILD as a commercial
bound. The engineering happens. What does not yet exist is the contracted allowance that limits
it. Until it does, the phrase "no new invoice" must not appear in writing.

**Arabic-first** is flagged PARTIAL across four surfaces and the exact state of each is an open
question in `../ops/decisions.md`. It is a claim a Saudi buyer will test in the first meeting, so
a partial implementation described as complete is worse than a partial one described accurately.

**Nothing unshipped may be demonstrated.** No screen recording, no live demo, no narrated
walkthrough of a capability flagged IN BUILD or ROADMAP. Video and live demos are where status
discipline breaks first.
