# OpenClaw — Auto Review handoff: native repair before S3* construction (OpenSiro plan-only)

**PLAN_ONLY / DECISION_READY · terminal operator decision: NO_GO for new S3*=C · DRAFT — NOT PUBLISHED.**  
[AI/developer companion](https://github.com/opensiro-contributions/openclaw/blob/opensiro/meta/.opensiro/issues/s3star-autoreview-handoff-20261119/constructor-sufficiency.md) · [source-pinned receipt](https://github.com/opensiro-contributions/openclaw/blob/opensiro/meta/.opensiro/issues/s3star-autoreview-handoff-20261119/roadmap.md). Working fork `opensiro-contributions/openclaw` on `opensiro/meta`.

## 1. Why OpenSiro and central accepted VSM assessment

OpenSiro tests whether reusable Viable System Model (VSM)-informed specifications can standardize AI-agent harness development and reduce total implementation, integration, review and maintenance cost versus simpler original-native solutions. This is a hypothesis: **savings and adoption are NOT established**.

> **STARTING POINT — accepted historical Index, not target/current grade.**  
> **S1=A · S2=C · S3=C(P) · S3*=— · S4=— · S5=—.**

**Accepted historical assessment (not a current-HEAD regrade): S1=A · S2=C · S3=C(P) · S3*=— · S4=— · S5=—.** [Pinned Index](https://github.com/opensiro/vsm-harness-index/blob/34e11ec4dd52e1ba3ee0111d8bca73f13918f54f/assessments/op/openclaw.md); reviewed 2026-09-16 at original `387da5edaa9d6c6cfcfc15e167fe2e46d8647d86`, assessment blob `e1d560bc5b28d90323b15f5f1af6a5293c614b45`, Profile 0.2.1, assessment procedure 0.3.1. Current source [`08b4ac92c1978f1f68dd78b53e7879ba24363c1b`](https://github.com/openclaw/openclaw/commit/08b4ac92c1978f1f68dd78b53e7879ba24363c1b) observed 2026-11-19. Review age 64 days warrants a separate source-pinned Index re-review recommendation, never silent reinterpretation of the accepted vector.

| Function | Accepted state | Relevance |
| --- | --- | --- |
| S1 · Operations | A | Ordinary agent work; no mandatory C construction |
| S2 · Coordination | C | Session messaging/lifecycle composability already established |
| S3 · Current management | C(P) | Host and parent-approved control authority preserved |
| **S3* · Complementary audit** | **—** | No complete sufficiently independent runtime audit at historical source; not a specific missing feature |
| S4 · Outside-and-then intelligence | — | Separate future-adaptation question, out of scope |
| S5 · Identity and policy | — | Operator approval is not S5 closure or authority delegation |

**System-in-focus:** installed first-party Gateway and bundled Auto Review reviewer, process runner, Code Mode bridge. Canonical helper `openclaw/agent-skills` is a separate source-owned dependency, not automatically a first-party organizational audit actor. GitHub maintainers, review bots and model providers are excluded from runtime S3* ownership by default.

## 2. Operator outcome, counterfactual and current decision

**Observed user outcome:** reliably return a completed restricted reviewer result, or the authentic stage-specific timeout. [Open original issue #201834](https://github.com/openclaw/openclaw/issues/201834) reports the helper starting its deadline before the reviewer is launched, and response submission occurring after the helper may have retired its exchange; the true timeout can become `FileNotFoundError`. The issue is OPEN with source-reproduction evidence and maintainer-review advisory.

**NO_GO for a new OpenSiro-built S3* controller now.** Removing a hypothetical independent audit controller does not prevent the cheaper native fix: one coordinated pass deadline including result delivery, preserved helper error through cleanup and Code Mode, and regressions. This is a demonstrated transport/diagnostic repair, not a proven new developer-composable independent complementary-audit decision-and-corrective-return capability.

## 3. Shipped and proposed original-native work

| Evidence | Observed first-party status | Difference to address |
| --- | --- | --- |
| [Auto Review tool](https://github.com/openclaw/openclaw/blob/08b4ac92c1978f1f68dd78b53e7879ba24363c1b/extensions/autoreview/src/tool.ts#L361-L464) | SHIPPED process launch and submission | Reviewer and helper time budgets diverge |
| [Canonical helper](https://github.com/openclaw/agent-skills/blob/3cc834ceec0410c4ff37c09e5b81c91e65fc9fc9/skills/autoreview/scripts/autoreview#L8856-L8872) | SHIPPED by separate original owner | Exchange cleanup/late-ready race, requires coordinated design |
| [Issue #201834](https://github.com/openclaw/openclaw/issues/201834) | OPEN original bug | Native repair not yet accepted |
| [PR #173455](https://github.com/openclaw/openclaw/pull/173455) | MERGED | Restricted reviewer native path exists |
| [PR #200743](https://github.com/openclaw/openclaw/pull/200743) | MERGED | Outer watchdog liveness, not this per-pass deadline |

A bounded original PR search for explicit `#201834` returned none; absence of an exact mention is not exhaustive proof of no other work. Separate existing fork Advisor and S4 cases are not duplicates of this narrow issue.

## 4. P0/P1/P2 and minimum sufficient capability

| Priority | Decision | Sufficiency / next action |
| --- | --- | --- |
| **P0 · new S3*=C** | **NO_GO / NOT QUALIFIED** | Require distinct useful operator task; independently developer-composed auditor, lawful choice, authorized correction/return and later operation feedback, none proven necessary for this issue |
| **P1 · existing native repair** | Original #201834, separate engineering lane | Shared pass deadline, true result/cause preservation and native red/green acceptance; original maintainer/dependency owner decision required |
| **P2 · optional second mode** | **NONE** | No unrelated S4/S5 controller or new permissions |

## 5. Native acceptance and stop conditions

**Tests proposed, NOT EXECUTED:** delayed reviewer start must not receive a second full helper pass budget; emitted JSON before process exit is not success; late submission after helper expiry must preserve true timeout, not missing-file noise; multipass/cancellation must clean up; Code Mode must retain diagnostics; any changed canonical helper runs its native-handoff suite. See [issue #201834](https://github.com/openclaw/openclaw/issues/201834) for source-linked focused test guidance.

**Stop speculative C work** while the identical user outcome can be achieved by native repair. A historic S3*=— does not justify a new feature. Only a genuinely different source-proven first-party independent audit decision with real authority and corrective return could reopen it.

## 6. Three independent paths

(a) Reuse original bug #201834 for a minimal native fix if separately requested and authorized; (b) independent Profile/Skills feedback only when an actual methodological ambiguity is evidenced; (c) optional legally permitted domain-specific fork experiment with a distinct task, not automatic third-party publication.

## 7. Cost hypothesis

Compare identical completed-review delivery and correct failure diagnostics under native repair and any future separately justified controller; measure engineering, integration, dependency coordination, tests, review and maintenance. **NOT_MEASURED**; no asserted savings.

## 8. Terminal decision / publication

**NO_GO for a new S3*=C controller.** Do now: retain link to original issue and let native owners resolve the pass deadline. Do not: create duplicate original issue/PR, build speculative control architecture, alter accepted assessment or implement without a separately authorized engineering request. **Public fork Issue: DRAFT — NOT PUBLISHED** (exact destination/title/full body approval still required). **External Issue/comment/PR: NOT PUBLISHED**. No product changes, native tests or grade update made here. Prepared with AI assistance.
