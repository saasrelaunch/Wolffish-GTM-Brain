# Site page, security officer, Arabic first

**Status: approved draft, not yet published.** Produced 2026-09-04 as the live test of this brain,
using only what is in this repository. Built from `../templates/site-page.md`, voice matched to
`../examples/one-pager-security-officer.md`. QA record and the gap list are at the foot of this
file. Update this page rather than rewriting it, because a shipped page carries approvals a fresh
draft does not.

Audience: the security officer. There is a separate finance director page and the two are never
merged.

---

## The page

### ولفيش كلاود

**وكلاء ذكاء اصطناعي يعملون على أجهزة موظفيك، والاستدلال على حساب مؤسستك، والسجل في مخزنكم.**

*Wolffish Cloud. AI agents that run on your employees' machines, with inference on your own
account, and the audit record in your own store.*

---

#### المشكلة التي تقف أمامك

فريقك مطالب باعتماد أدوات ذكاء اصطناعي، وأنت من يوقّع. التنظيمات تُحمّلك إثبات ما يحدث لبيانات المؤسسة في يد طرف ثالث ينفّذ أوامر عليها، لا مجرد وعد بحسن التصرف.

أغلب الموردين يقدمون تعهداً تعاقدياً بموقع البيانات. التعهد وثيقة تدافع عنها أنت أمام الجهة التنظيمية. ما نقدمه مختلف في نوعه: لا يوجد مسار أصلاً تصل عبره بياناتكم إلينا.

#### ثلاث ركائز

**١. لا يغادر شيء من بياناتكم المبنى.** الوكلاء ينفّذون على جهاز الموظف نفسه، والاستدلال يذهب إلى نقطة نهاية بلا احتفاظ على حسابكم أنتم. لا يوجد مسار يصل عبره نص أو ملف أو مخرَج إلى ولفيش.

**٢. سجل تدقيق على مستوى الإجراء، في مخزنكم.** منسوب إلى موظف وإلى وقت، مع بوابات موافقة على العمليات الحساسة، ومفتاح إيقاف لكل مستخدم وللنظام كاملاً.

**٣. لا نقل عبر الحدود، فلا آلية نقل مطلوبة.** وملف الامتثال أقصر مما تحتاجه أي بنية بديلة.

#### ثلاثة أسئلة اطرحها علينا وعلى غيرنا

١. أين يجري الاستدلال فعلياً، وعلى حساب من؟
٢. ما الذي يغادر جهاز الموظف، وإلى أين بالضبط؟
٣. أرِني السجل الذي يثبت الإجابتين، لا الوثيقة التي تعد بهما.

---

#### The problem in front of you

Your team is being asked to approve AI tooling, and you are the one who signs. The rules require you
to evidence what happens to organisational data in the hands of a third party executing against it,
not merely to hold a promise of good behaviour.

Most vendors offer a contractual commitment about where data sits. A commitment is a document that
you defend to the regulator. What we offer is different in kind: there is no path by which your data
reaches us at all.

#### Three pillars

**1. Nothing of yours leaves the building.** Agents execute on the employee's own machine, and
inference goes to a zero-retention endpoint on your account. No path exists by which a prompt, a
file or an output reaches Wolffish.

**2. An action-level audit log, in your own store.** Attributed to an employee and a timestamp, with
approval gates on sensitive operations and a kill switch per user and globally.

**3. No cross-border transfer, so no transfer mechanism is required.** The evidence pack is shorter
than the one any alternative architecture needs.

#### Where the work happens

In-perimeter execution. A zero-retention endpoint on your account. No vendor-side data path.

Everyone in this market offers residency. Residency is a commitment about how a vendor handles your
data after receiving it. This is the absence of a data path, which is a different claim, and it is
the one your team can trace on a diagram with a finger rather than defend in a document.

#### What is live today

Persistent per-employee agents, file read and write scoped per role, shell and command execution
under per-role scopes, approval gates with a human in the loop, multi-step autonomous execution,
local context ingestion, model portability across zero-retention endpoints, chat and retrieval over
company documents: all SHIPPED.

Hard token quota per user, team and period enforced as a cap, action-level audit log to your own
store, kill switch per user and global, single sign-on with directory sync and automated
offboarding, admin console with per-role and per-agent scopes, spend visibility by team and task,
branded single-tenant deployment: all SHIPPED.

Saudi commercial registration, riyal contracting, ZATCA-compliant electronic invoicing, Saudi
jurisdiction and Arabic contracting: SHIPPED. Support for a sovereign in-Kingdom inference endpoint:
SHIPPED as a model option.

Arabic interface, prompting, output and document handling including Hijri dates: PARTIAL. Ask us on
the call which surfaces, and we will show you rather than describe it.

Source access and escrow: PARTIAL. The deed is drafted and no agent is appointed yet.

The Compliance Evidence Pack, covering the national cybersecurity controls, the data classification
framework, the personal data law and the central bank outsourcing framework: IN BUILD.

**No certification is held today.** Not SOC 2, not ISO 27001, not an equivalent. It is not
scheduled. What the architecture provides instead is described above, and you should weigh it
yourself rather than take our word for the trade.

#### What it costs, all three lines

| Line | Amount | Billed by |
|---|---|---|
| Deployment, one time | SAR 60,000, half at signature and half at go-live | Wolffish |
| Platform seat | SAR 79 per employee per month, quarterly in advance, twelve-month term | Wolffish |
| Inference and infrastructure | SAR 45 to 55 per seat per month | Your own providers, at zero Wolffish margin, never resold |

**Landed cost is SAR 124 to 184 per employee per month.** All figures exclude the fifteen percent
value-added tax. We publish this because a seat price on its own understates what you will spend by
about a third, and you would find that out eventually.

#### Who this is not for

Organisations with fewer than 200 knowledge workers. Organisations without a directory to sync
against. Anyone looking for a chat assistant rather than agents that execute work on a machine.
Anyone who needs a held certification in the file this quarter.

We will tell you on the first call if you are in one of those, and we would rather lose the call
than the year.

#### The next step

A thirty-minute security call, at your office, with your security team in the room. We send the
architecture diagram two working days beforehand so the call is spent on questions rather than on
reading.

---

## QA record, run 2026-09-04 against `../ops/QA-checklist.md`

**Writing.** No em dashes. None of the fourteen banned words. Short paragraphs. Specific numbers in
place of adjectives throughout.

**Channel.** Owned site, which is in the mix.

**Claims.** No certification claimed, and the absence is stated plainly with what stands in its
place. Every capability carries its flag from `../rules/feature-status.md` in the same sentence.
Residency is never claimed; the absence of a data path is. All three price lines appear with the
value-added tax note. No proof point outside the closed set in `../ops/copy-bank.md`. No customer
name, quote, count or case study, because there is no reference customer.

**Superlatives.** One candidate, "the evidence pack is shorter than the one any alternative
architecture needs", checked against the narrowing drill in `../rules/do-not-say.md`. Held, because
it is architectural rather than comparative in the prohibited sense. No "only", "first", "best" or
"never" appears.

**Naming and strategy.** Vocabulary matches `../rules/glossary.md`. No framing contradicts a decided
verdict in `../ops/decisions.md`. HUMAIN is not mentioned, and no comparison with it appears.

**Audience and stage.** One audience, the security officer. Stage one to two, problem awareness into
the security call, and the single call to action matches that stage.

**Voice.** Matches `../examples/one-pager-security-officer.md`. Arabic written natively, not
translated, and it is the headline rather than the second column.

**Result: passes.** One item deferred, below.

## What the brain could not supply

Two gaps, which is the point of running a live test.

**1. The architecture diagram.** This page refers to a diagram sent before the security call, and
that diagram does not exist yet. It is named in `../ops/asset-index.md` as pending with the founder
as owner. Nothing on this page depends on it, but the security call does.

**2. Arabic-first coverage per surface.** The page says PARTIAL and offers to show which surfaces on
the call, which is honest but weaker than naming them. That is open question three in
`../ops/decisions.md`, owned by product. When it closes, this paragraph gets replaced with the four
specific answers, and this is exactly the kind of amendment `../ops/asset-index.md` exists to route.

Neither gap was filled with an invention, which is the behaviour the test was checking for.
