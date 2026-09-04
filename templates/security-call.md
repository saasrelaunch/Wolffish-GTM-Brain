# Template, the security call

Audience: the security officer and their team, in the room together. This is the pivotal asset in
the funnel and it sits at stage two, before the economic conversation, not after it. Rationale:
`../reference/customer-journey.md` and `../reference/buying-committee.md`.

## Before the call
- Send the architecture diagram at least two working days ahead. A security team that first sees
  the architecture on the call spends the call reading rather than asking.
- Confirm who will attend. If the security team is not in the room, move the call. A call held
  with the sponsor alone has to be held again.
- Read `../reference/saudi-regulatory-file.md` for the instruments that govern this entity
  specifically, because a bank, a ministry and a listed company are not governed by the same set.

## The thirty-minute agenda
1. **Where the work happens, five minutes.** Agents execute on the employee's own machine.
   Inference goes to a zero-retention endpoint on the customer's own account. State plainly that
   there is no vendor-side data path, and never say data residency, which is a different and
   weaker claim that every competitor also offers.
2. **What the agent can do, ten minutes.** Shell and command execution is shipped. Introduce the
   approval gates in the same breath, because this capability alarms a security officer if it
   arrives without them.
3. **What the control plane enforces, five minutes.** Quota, audit log written to the customer's
   own store, kill switch, single sign-on and offboarding. Status flag on each.
4. **The disqualifiers, five minutes.** Say out loud who this is not for. Declining above fifteen
   percent of security calls is a target, not an accident.
5. **What happens next, five minutes.** The evidence pack, the scope ladder, the named next
   person to meet.

## Fields to fill
- Entity and its governing instruments: [regulator, classification level if known]
- Attendees and roles: [names, and confirmation the security team is present]
- The two disqualifiers most likely to apply here: [state them]

## What may not happen on this call
No proof of concept offered to move the call forward. That inverts the motion and spends senior
engineering against an unqualified account.

No claim of a certification not yet held, and no compliance claim outside the permitted forms in
`../rules/do-not-say.md`.

No price quoted without all three lines and the words landed cost.

Guardrail: every capability spoken aloud carries its flag from `../rules/feature-status.md`. The
follow-up written after this call goes through `../ops/QA-checklist.md`, and everything the
security team said that surprised you goes into `../ops/signal-log.md` the same day.
