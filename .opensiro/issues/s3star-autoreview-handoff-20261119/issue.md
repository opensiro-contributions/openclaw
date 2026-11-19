# OpenClaw — Auto Review handoff: native repair before S3* construction (OpenSiro plan-only)

**PLAN_ONLY / DECISION_READY · terminal operator decision: NO_GO for new S3*=C · DRAFT — NOT PUBLISHED.**  
[AI/developer companion](https://github.com/opensiro-contributions/openclaw/blob/opensiro/meta/.opensiro/issues/s3star-autoreview-handoff-20261119/constructor-sufficiency.md) · [source-pinned receipt](https://github.com/opensiro-contributions/openclaw/blob/opensiro/meta/.opensiro/issues/s3star-autoreview-handoff-20261119/roadmap.md). Working fork `opensiro-contributions/openclaw` on `opensiro/meta`.

## 1. Why OpenSiro and central accepted VSM assessment

OpenSiro tests whether reusable Viable System Model (VSM)-informed specifications can standardize AI-agent harness development and reduce total implementation, integration, review and maintenance cost versus simpler original-native solutions. This is a hypothesis: **savings and adoption are NOT established**.

> **STARTING POINT — accepted historical Index, not target/current grade.**  
> **S1=A · S2=C · S3=C(P) · S3*=— · S4=— · S5=—.**

**Accepted historical assessment (not a current-HEAD regrade): S1=A · S2=C · S3=C(P) · S3*=— · S4=— · S5=—.** [Pinned Index](https://github.com/opensiro/vsm-harness-index/blob/394ce776e6945115891b8f7cc459f5a7f7d7aa39/assessments/op/openclaw.md); reviewed 2026-09-16 at original `387da5edaa9d6c6cfcfc15e167fe2e46d8647d86`, assessment blob `e1d560bc5b28d90323b15f5f1af6a5293c614b45`, Profile 0.2.1, assessment procedure 0.3.1. Current source [`41bdde2111dd7031c93b47c57d7dad2e56bb0f5f`](https://github.com/openclaw/openclaw/commit/41bdde2111dd7031c93b47c57d7dad2e56bb0f5f) observed 2026-11-19. Review age 64 days warrants a separate source-pinned Index re-review recommendation, never silent reinterpretation of the accepted vector.

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
| [Auto Review tool](https://github.com/openclaw/openclaw/blob/41bdde2111dd7031c93b47c57d7dad2e56bb0f5f/extensions/autoreview/src/tool.ts#L361-L464) | SHIPPED process launch and submission | Reviewer and helper time budgets diverge |
| [Canonical helper](https://github.com/openclaw/agent-skills/blob/3cc834ceec0410c4ff37c09e5b81c91e65fc9fc9/skills/autoreview/scripts/autoreview#L8856-L8872) | SHIPPED by separate original owner | Exchange cleanup/late-ready race, requires coordinated design |
| [Issue #201834](https://github.com/openclaw/openclaw/issues/201834) | OPEN original bug | Native repair not yet accepted |
| [PR #173455](https://github.com/openclaw/openclaw/pull/173455) | MERGED | Restricted reviewer native path exists |
| [PR #200743](https://github.com/openclaw/openclaw/pull/200743) | MERGED | Outer watchdog liveness, not this per-pass deadline |

A bounded original PR search for explicit `#201834` returned none; absence of an exact mention is not exhaustive proof of no other work. Separate existing fork Advisor and S4 cases are not duplicates of this narrow issue.

## 3A. Source-pinned parallel contribution-on-top rerun — Upstream v0.17.0

**Previous persisted decision (historical, unchanged):** [`0045643f66ec82b556ef2ba1326484b00098a2e6`](https://github.com/opensiro-contributions/openclaw/commit/0045643f66ec82b556ef2ba1326484b00098a2e6) evaluated a new S3* controller against original `08b4ac92c1978f1f68dd78b53e7879ba24363c1b` and concluded **NO_GO**. It remains provenance, not an automatic veto for other native improvements.

**New bounded v0.17.0 review (2026-11-19 UTC):** original `41bdde2111dd7031c93b47c57d7dad2e56bb0f5f` and [accepted Index](https://github.com/opensiro/vsm-harness-index/blob/394ce776e6945115891b8f7cc459f5a7f7d7aa39/assessments/op/openclaw.md) read anew. **Evaluation object** = *additional independently composed S3* controller / durable audit capability beyond the existing Auto Review handoff fix*. **Current decision** = **NO_GO** on that bounded extra object; **native deadline/diagnostic repair remains a qualified original issue lead**, subject to its own rights and review. **Verdict evolution:** unchanged for the controller, materially clarified boundary for native contributions.

[Upstream v0.17.0 source](https://github.com/opensiro/upstream/blob/0231dfd238f8fa6cdb779393c3c5f087f7599f7c/PROTOCOL.md) · [re-run cohort #58](https://github.com/opensiro/upstream/issues/58). This case was created **after** #58's frozen 22-operational-case inventory and is **not** counted as its completed roster item. The comparison applies the same per-case two-track standard without rewriting that baseline.

| Path | Existing original-native source and coverage (Track A) | Independently evaluated OpenSiro choice (Track B) | Incremental user result | Falsifier / result |
| --- | --- | --- | --- | --- |
| **Reuse unchanged** | Shipped [Auto Review orchestration](https://github.com/openclaw/openclaw/blob/41bdde2111dd7031c93b47c57d7dad2e56bb0f5f/extensions/autoreview/src/tool.ts#L361-L464), canonical [helper handoff](https://github.com/openclaw/agent-skills/blob/3cc834ceec0410c4ff37c09e5b81c91e65fc9fc9/skills/autoreview/scripts/autoreview#L8856-L8872), and already-open [original #201834](https://github.com/openclaw/openclaw/issues/201834) | Reuse original Issue and maintainer review; make no new product change | Avoid duplicate ticket/PR, retain native issue evidence and coordination | **APPLICABLE, no new feature:** existing timeout failure persists; reusing unchanged does not itself restore successful result delivery |
| **Integrate/extend native handoff** | Plugin invokes a separate helper and resets the reviewer timeout on launch; helper may expire before submit, with wrong final diagnostic. [Merged reviewer PR #173455](https://github.com/openclaw/openclaw/pull/173455) and [merged outer-watchdog PR #200743](https://github.com/openclaw/openclaw/pull/200743) do not close this per-pass race | On top of those shipped primitives: single request-to-submission deadline ownership, phase-preserving error return, and matching real helper/plugin regressions using existing run/pass identifiers; maintain helper source ownership | A completed review is delivered once, or the actual timeout is preserved instead of a misleading file error | **SOURCE-BACKED native repair lead, but already within the intent of #201834**; no separately justified S3* audit decision owner. Falsified as extra on-top feature if the accepted native fix already supplies that same behavior |
| **Adjacent durable audit receipt** | Existing response already contains `run_id`, pass and prompt digest; existing failure is at submission/cleanup, not necessarily downstream audit history | Add a durable, cross-run reviewer-outcome/provenance receipt to later S1/S3 inspection using authorized storage and retention | Could enable post-run attribution beyond a one-pass error response | **NOT_EVIDENCED:** no first-party user demand for cross-run durability, migration/retention scope or allowable decision right. Reject if native stage-specific diagnostics suffice |
| **New independent S3* constructor** | Restricted reviewer is a shipped tool; [separate fork Advisor-case](https://github.com/opensiro-contributions/openclaw/blob/opensiro/meta/.opensiro/issues/s3star-advisor-review-20261119/README.md) covers other review-model scope. A reviewer tool is not an independent deployment-level S3* actor | Developer-composed independent auditor choosing permitted `hold`/corrective action with protected permissions, later enforced S1/S3 effect and feedback | Would provide a new organizational corrective decision only if a real unmet operator task requires it | **NOT_EVIDENCED:** no operator task, installed composition/authority or later corrective closure shown. If removing the new actor leaves the native repair outcome unchanged, the proposed C path fails materiality |

**Track verdict:** original [#201834](https://github.com/openclaw/openclaw/issues/201834) is a real **source-owned repair opportunity**, not a blanket veto against contribution. Our minimal integration hypothesis could be implemented *inside that existing Issue* after separately authorized engineering and maintainer coordination; it is **not** an independent VSM `C` construction target. Two distinct adjacent variants are rejected on current evidence, not claimed permanently useless. **New scoped decision = NO_GO for creating a separate S3* C constructor for this Auto Review handoff; not NO_GO for original-native bug work or the OpenClaw harness.**

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
