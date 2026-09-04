# Diagrams, maps and flowcharts

The whole go-to-market in pictures. Every diagram here renders natively on GitHub. Nothing in this
file is new information: each one is a view of something written elsewhere in the brain, and the
source file is named underneath it.

Contents: [the product](#1-what-is-being-sold) · [load policy](#2-what-to-load-and-when) ·
[producing an asset](#3-producing-an-asset-end-to-end) · [signal to amendment](#4-signal-to-amendment) ·
[amendment propagation](#5-amendment-propagation-what-changes-when) ·
[the funnel](#6-the-seven-stage-funnel-and-the-channels-that-feed-it) ·
[buying committee](#7-the-buying-committee-sequence) · [the calendar](#8-the-saudi-selling-calendar) ·
[channel mix](#9-channel-mix-and-what-is-refused) · [the wedge](#10-where-wolffish-actually-competes) ·
[refusal logic](#11-should-this-be-produced-at-all)

---

## 1. What is being sold

Four layers, sold as one thing. Reading it as any single layer is the most common error, and the
caveat that opens every deliverable in this go-to-market.

```mermaid
flowchart TB
    subgraph D["D. Saudi regulatory and commercial fit"]
        direction LR
        D1["Saudi registration<br/>riyal contracting<br/>Arabic contracting"]
        D2["ZATCA electronic<br/>invoicing"]
        D3["No data crosses the border,<br/>so no transfer mechanism<br/>is required"]
        D4["Compliance Evidence Pack<br/>IN BUILD"]
    end
    subgraph C["C. Cloud service, delivered by engineers"]
        direction LR
        C1["Deployment with<br/>a pilot cohort"]
        C2["Integration into internal,<br/>bespoke and legacy systems"]
        C3["Ongoing capability<br/>development"]
        C4["Service level<br/>and source escrow"]
    end
    subgraph B["B. Platform control plane"]
        direction LR
        B1["Hard token quota,<br/>enforced as a cap"]
        B2["Action-level audit log<br/>in the customer's store"]
        B3["Kill switch,<br/>single sign-on, scopes"]
        B4["Spend visibility<br/>by team and task"]
    end
    subgraph A["A. Agentic harness, on the employee's machine"]
        direction LR
        A1["Persistent<br/>per-employee agent"]
        A2["Files and shell,<br/>scoped per role"]
        A3["Approval gates,<br/>human in the loop"]
        A4["Model portability across<br/>zero-retention endpoints"]
    end
    A --> B --> C --> D
    NOTE["Layer A is where Wolffish is least defensible<br/>and is commoditising fastest.<br/>Positioning rests on B, C and D."]
    A -.-> NOTE
```

Source: `../reference/feature-matrix.md`, `../rules/feature-status.md`.

---

## 2. What to load, and when

The always-loaded layer stays small. Everything else is pulled in on demand. This is the single
rule that decides whether a brain gets used or quietly abandoned.

```mermaid
flowchart TD
    START(["A task arrives"]) --> Q1{"Is anything a<br/>customer will read<br/>going to be produced?"}
    Q1 -->|No| ROUTER["Router only<br/>CLAUDE.md or AGENTS.md"]
    Q1 -->|Yes| BASE["Router<br/>plus all four rules files<br/>plus the matching reference file"]
    BASE --> Q2{"What kind of task?"}
    Q2 -->|"Channel content"| CH["Add reference/relationship-engine.md<br/>the template<br/>the matching example"]
    Q2 -->|"Competitive or sales"| CO["Add competitor-battlecards.md<br/>and objection-handling.md"]
    Q2 -->|"Pricing or proposal"| PZ["Add pricing-model.md<br/>and offer-metrics-audit.md"]
    Q2 -->|"Compliance or tender"| RG["Add saudi-regulatory-file.md"]
    Q2 -->|"Strategy question"| ST["Master context<br/>plus ops/decisions.md"]
    Q2 -->|"A new signal or snapshot"| SG["ops/signal-log.md, ops/decisions.md,<br/>and the ledger the signal points at"]
    CH --> QA
    CO --> QA
    PZ --> QA
    RG --> QA
    ST --> QA
    SG --> QA
    QA["Before shipping:<br/>ops/QA-checklist.md"] --> DONE(["Ship, then log it in<br/>ops/asset-index.md"])
```

Source: `../llms.txt`, and the load policy in the blueprint.

---

## 3. Producing an asset, end to end

```mermaid
sequenceDiagram
    autonumber
    participant OP as Operator
    participant AG as Agent
    participant CTRL as rules/ and router
    participant REF as reference/
    participant TPL as templates/ and examples/
    participant QAC as ops/QA-checklist.md
    participant OPS as ops/ state

    OP->>AG: "Write the landed cost email for 300 seats at this bank"
    AG->>CTRL: load router, writing rules, do-not-say, feature status, glossary
    CTRL-->>AG: audience rule, banned claims, status flags, channel discipline
    AG->>REF: pricing-model.md, saudi-regulatory-file.md
    REF-->>AG: three lines, landed cost band, the instruments for a bank
    AG->>TPL: landed-cost-email.md, examples/landed-cost-email.md
    TPL-->>AG: structure and the approved voice
    AG->>AG: draft
    AG->>QAC: check every item
    QAC-->>AG: one failure, a superlative left unscoped
    AG->>AG: fix, re-check
    AG-->>OP: draft plus the one rule it came closest to breaking
    OP->>OPS: file it in asset-index.md
    OP->>OPS: log what the work taught you in signal-log.md
```

Source: `../ops/QA-checklist.md`, `../prompts/common-tasks.md`.

---

## 4. Signal to amendment

The default disposition is NOISE. A brain that amends on every conversation has no memory. One
that never amends is a static document that quietly stops being true.

```mermaid
stateDiagram-v2
    [*] --> Captured: something is heard or observed
    Captured --> Triaged: weekly, Sunday
    Triaged --> NOISE: one instance, no pattern
    Triaged --> WATCH: a plausible pattern
    Triaged --> PATCH: copy changes, strategy does not
    Triaged --> AMEND: a rule, a ledger or a position changes
    WATCH --> WATCH: increment on each new instance
    WATCH --> AMEND: threshold met
    WATCH --> NOISE: two quiet cycles, expired in the log
    PATCH --> [*]: edit the copy, no decision entry
    AMEND --> Ledger: 1. the ledger in rules/
    Ledger --> Context: 2. the master context
    Context --> Decision: 3. a dated entry in ops/decisions.md
    Decision --> Copy: 4. every asset in the asset index
    Copy --> Portable: 5. regenerate the portable control layer
    Portable --> [*]
    NOISE --> [*]
```

Thresholds: three independent instances in sixty days for an opinion, preference or objection, and
two where the account is on the named list. One verified instance for a fact, a status, a
competitive move or a regulatory change. A full measurement cycle for channel performance, never a
single week.

Source: `../ops/signal-log.md`, `../ops/review-cadence.md`.

---

## 5. Amendment propagation, what changes when

The map an amendment follows. Read it in the direction of the arrows and nothing gets left carrying
an old claim.

```mermaid
flowchart LR
    FS["rules/feature-status.md<br/>a capability ships"]
    DN["rules/do-not-say.md<br/>a claim becomes<br/>sayable or unsayable"]
    GL["rules/glossary.md<br/>a term changes"]
    PR["reference/pricing-model.md<br/>a price moves"]
    RG["reference/saudi-regulatory-file.md<br/>an instrument changes"]

    MC["context/Master Context<br/>sections and status_notes"]
    DEC["ops/decisions.md<br/>dated entry"]
    CB["ops/copy-bank.md<br/>approved lines"]
    EX["examples/<br/>the voice reference"]
    TPL["templates/"]
    PG["pages/<br/>shipped assets"]
    SURF["Live surfaces<br/>listed in ops/asset-index.md"]
    PORT["adapters/portable-control-layer.md"]

    FS --> MC
    DN --> MC
    GL --> MC
    PR --> MC
    RG --> DN
    RG --> MC
    MC --> DEC --> CB
    CB --> EX
    CB --> TPL
    CB --> PG
    PG --> SURF
    EX --> SURF
    DEC --> PORT
    PR -.->|"grep every figure"| EX
    PR -.->|"grep every figure"| SURF
```

The two files most likely to be forgotten are `examples/`, because an approved example is copied
without a second look, and the portable control layer, because it lives outside every tool that
would have caught it.

Source: `../ops/asset-index.md`.

---

## 6. The seven-stage funnel, and the channels that feed it

```mermaid
flowchart LR
    subgraph CHAN["Channels"]
        C1["Events<br/>~35%"]
        C2["Warm introduction<br/>~30%"]
        C3["Founder writing<br/>~15%"]
        C4["Messaging<br/>~10%"]
        C5["Partner co-sell<br/>~10%"]
        C6["Owned: site,<br/>scorecard, calculator"]
    end
    S1["1. Problem awareness<br/>2 to 8 weeks"]
    S2["2. Security call<br/>2 to 4 weeks<br/>security team in the room"]
    S3["3. Vendor evaluation<br/>4 to 10 weeks"]
    S4["4. Pilot cohort<br/>6 to 12 weeks<br/>SAR 25,000, credited"]
    S5["5. Value realisation<br/>6 to 8 build, then 12"]
    S6["6. Expansion<br/>months 4 to 12"]
    S7["7. Renewal<br/>timed before December"]
    C1 --> S1
    C2 --> S1
    C3 --> S1
    C6 --> S1
    C5 --> S1
    S1 --> S2 --> S3 --> S4 --> S5 --> S6 --> S7
    C4 -.->|"accelerant across all stages,<br/>after introduction only"| S3
    S2 -.->|"decline above 15%<br/>is a target,<br/>not an accident"| OUT(["Disqualified, and told so"])
    NOTE2["Sixteen to thirty-four weeks to signature,<br/>plus six to eight to go-live.<br/>ICP 2 is roughly double."]
    S7 -.- NOTE2
```

The security call sits at stage two rather than the usual stage three. That single move is the
highest-return process decision in this go-to-market, because in Saudi regulated enterprises the
security officer blocks rather than reviews.

Source: `../reference/customer-journey.md`, `../reference/marketing-campaigns.md`.

---

## 7. The buying committee sequence

Six roles in ICP 1, three more in ICP 2. The order is deliberate and inverts the standard Western
sequence, which starts with the economic buyer and treats security as a late compliance hurdle.

```mermaid
sequenceDiagram
    autonumber
    participant SP as Sponsor
    participant SO as Security officer
    participant TL as Technology lead
    participant FD as Finance director
    participant PC as Pilot cohort
    participant DM as Decision maker
    participant PROC as Procurement

    SP->>SO: introduction, forwardable paragraph
    SO->>SO: security call, architecture walkthrough
    Note over SO: blocks or clears. Nothing<br/>proceeds past an unconvinced<br/>security officer.
    SO->>TL: integration feasibility
    TL->>TL: "could we build this ourselves"<br/>held deliberately, not avoided
    TL->>FD: landed cost, all three lines
    FD->>PC: ten seats, three weeks, one workflow
    PC->>DM: a pilot result, not a vendor evaluation
    Note over DM: presented with a convinced security<br/>officer and a finance director<br/>who already has the number
    DM->>PROC: a complete pack, not a request
```

Source: `../reference/buying-committee.md`.

---

## 8. The Saudi selling calendar

Calendar weeks are not selling weeks. This is the fact most often missed, and a plan that assumes
even months is wrong by about forty percent of the year.

```mermaid
gantt
    title Roughly twenty-five sellable weeks in twelve months, not forty-eight
    dateFormat YYYY-MM-DD
    axisFormat %b
    section Live windows
    Window one about 14 weeks   :active, w1, 2026-09-01, 2026-12-20
    Window two about 5 weeks    :active, w2, 2027-01-04, 2027-02-07
    Window three about 6 weeks  :active, w3, 2027-03-15, 2027-05-01
    section Fixed dates
    National AI summit           :milestone, m1, 2026-09-15, 0d
    Regional security conference :milestone, m2, 2026-12-01, 0d
    section Closed
    Ramadan six-hour working day :crit, r1, 2027-02-08, 2027-03-08
    First religious holiday      :crit, h1, 2027-03-09, 2027-03-15
    Executive travel season      :done, s1, 2027-06-01, 2027-08-31
```

A deal that has not reached stage three by October is a next-year deal and should be managed as
one rather than forecast as this year's.

Source: `../reference/customer-journey.md`.

---

## 9. Channel mix, and what is refused

```mermaid
pie showData
    title Expected share of qualified pipeline, year one
    "Events and physical presence" : 35
    "Warm introduction and sponsors" : 30
    "Founder writing, bilingual" : 15
    "Messaging, after introduction" : 10
    "Partner co-sell" : 10
```

Two channels carry sixty-five percent and neither can be automated. The founder's calendar, not an
advertising budget, is the constraint on this funnel.

Three channels are refused outright rather than deprioritised:

```mermaid
flowchart LR
    R1["Automated outreach sequencing"] -->|"reads as disrespect in a culture<br/>built on personal introduction,<br/>and degrades the founder profile<br/>the two largest channels depend on"| X(("REFUSED"))
    R2["Volume cold email"] -->|"negligible response where senior<br/>executives do business in person;<br/>email is a confirmation medium"| X
    R3["Paid social"] -->|"optimises for volume against a<br/>market of about twenty accounts"| X
    X --> ALT["Offer instead: the introduction path,<br/>an event conversation, or a founder post"]
```

Source: `../reference/relationship-engine.md`, `../reference/marketing-campaigns.md`.

---

## 10. Where Wolffish actually competes

```mermaid
quadrantChart
    title Governance depth against how defensible the position is
    x-axis Commoditising fast --> Defensible
    y-axis Shallow governance --> Deep governance
    quadrant-1 Where the wedge is
    quadrant-2 Costly to hold
    quadrant-3 Table stakes
    quadrant-4 Feature parity race
    Harness layer A: [0.24, 0.66]
    Control plane layer B: [0.68, 0.86]
    Service delivery layer C: [0.78, 0.55]
    Saudi regulatory fit layer D: [0.86, 0.9]
    Incumbent assistant: [0.6, 0.3]
    Do it yourself stack: [0.2, 0.25]
    Integrator build: [0.35, 0.45]
```

Layer A holds three of the four most negative competitive scores. Any deck built on harness
capability has a twelve-month shelf life. The wedge is layers B and D together, which is why the
security call leads and the feature list does not.

Source: `../reference/competitive-analysis.md`, `../reference/positioning-verdict.md`.

---

## 11. Should this be produced at all?

The refusal logic, as a single decision tree. Most of the value of a control layer is in the
outputs it prevents.

```mermaid
flowchart TD
    REQ(["A request arrives"]) --> Q1{"Is it for a market<br/>outside Saudi Arabia?"}
    Q1 -->|Yes| NO1["Decline. Say the go-to-market<br/>is Kingdom-only and why."]
    Q1 -->|No| Q2{"Is it for sequencing,<br/>volume cold email<br/>or paid social?"}
    Q2 -->|Yes| NO2["Decline. One-sentence reason,<br/>then offer the in-scope alternative."]
    Q2 -->|No| Q3{"Does it need a customer name,<br/>quote, count or metric?"}
    Q3 -->|Yes| NO3["Decline that element.<br/>There is no reference customer.<br/>Offer the architecture or the<br/>published price instead."]
    Q3 -->|No| Q4{"Does it demonstrate anything<br/>flagged IN BUILD or ROADMAP?"}
    Q4 -->|Yes| NO4["Describe it, do not demonstrate it,<br/>and attach the flag."]
    Q4 -->|No| Q5{"Does it state a price<br/>as a single line?"}
    Q5 -->|Yes| FIX["Rewrite with all three lines<br/>and the words landed cost."]
    Q5 -->|No| Q6{"Does it position<br/>against HUMAIN?"}
    Q6 -->|Yes| NO5["Neutralise in one sentence.<br/>Do not compete."]
    Q6 -->|No| Q7{"Does it blend<br/>two audiences?"}
    Q7 -->|Yes| SPLIT["Split it. One audience per asset."]
    Q7 -->|No| GO["Produce it, then run<br/>ops/QA-checklist.md"]
    FIX --> GO
    SPLIT --> GO
    NO4 --> GO
```

Source: `../CLAUDE.md`, `../rules/do-not-say.md`.
