# Capability Roadmap Receipt — OpenClaw Auto Review handoff / S3*

- Original repository: openclaw/openclaw
- Original HEAD: 08b4ac92c1978f1f68dd78b53e7879ba24363c1b
- Observed at: 2026-11-19
- Accepted Index assessment: https://github.com/opensiro/vsm-harness-index/blob/34e11ec4dd52e1ba3ee0111d8bca73f13918f54f/assessments/op/openclaw.md
- Accepted assessment blob SHA: e1d560bc5b28d90323b15f5f1af6a5293c614b45
- Accepted review ref: 387da5edaa9d6c6cfcfc15e167fe2e46d8647d86
- Accepted reviewed at: 2026-09-16
- System in focus: original first-party Gateway, bundled Auto Review restricted reviewer, process runner and Code Mode at pinned main; canonical agent-skills helper source, maintainers and external reviewer process excluded as independent organizational owners
- Result: PLAN_ONLY
- External issue: DRAFT — NOT PUBLISHED
- Cost status: NOT_MEASURED
- Receipt contract: contribution-on-top
- Evaluation object: New S3* independent audit constructor for the bundled OpenClaw Auto Review handoff, not the whole harness or the existing original defect repair
- Existing-work overlap: Shipped restricted Auto Review plus original open issue #201834 and distinct prior merged watchdog/reviewer PRs
- Our on-top contribution: Tested hypotheses for a durable audit receipt, independently composed corrective audit actor, and minimal cross-repository deadline integration
- Incremental benefit: Native issue repair has material reliable-review value; extra S3* audit-controller outcome remains NOT_EVIDENCED against native alternatives
- Decision scope: NO_GO only to new Auto Review S3* C construction now; original source-native issue #201834 is not vetoed

## Identity and pins

[Original pinned HEAD](https://github.com/openclaw/openclaw/commit/08b4ac92c1978f1f68dd78b53e7879ba24363c1b) observed 2026-11-19; **Accepted historical assessment (not a current-HEAD regrade): S1=A · S2=C · S3=C(P) · S3*=— · S4=— · S5=—.** [Pinned Index](https://github.com/opensiro/vsm-harness-index/blob/34e11ec4dd52e1ba3ee0111d8bca73f13918f54f/assessments/op/openclaw.md); reviewed 2026-09-16 at original `387da5edaa9d6c6cfcfc15e167fe2e46d8647d86`, assessment blob `e1d560bc5b28d90323b15f5f1af6a5293c614b45`, Profile 0.2.1, assessment procedure 0.3.1. Current source [`08b4ac92c1978f1f68dd78b53e7879ba24363c1b`](https://github.com/openclaw/openclaw/commit/08b4ac92c1978f1f68dd78b53e7879ba24363c1b) observed 2026-11-19. Review age 64 days warrants a separate source-pinned Index re-review recommendation, never silent reinterpretation of the accepted vector. [Human Issue](https://github.com/opensiro-contributions/openclaw/blob/opensiro/meta/.opensiro/issues/s3star-autoreview-handoff-20261119/issue.md) and [AI contract](https://github.com/opensiro-contributions/openclaw/blob/opensiro/meta/.opensiro/issues/s3star-autoreview-handoff-20261119/constructor-sufficiency.md) use the same historic vector, P0/P1/P2 and terminal decision.

## Rights and authority

[Original MIT](https://github.com/openclaw/openclaw/blob/08b4ac92c1978f1f68dd78b53e7879ba24363c1b/LICENSE) and [CONTRIBUTING](https://github.com/openclaw/openclaw/blob/08b4ac92c1978f1f68dd78b53e7879ba24363c1b/CONTRIBUTING.md) reviewed: existing native issue and normal PR/review/test rules govern any bug fix, new architecture needs prior first-party discussion; security, contributor/formalities and exact third-party publication require separate checks. Correctly parented working fork `opensiro-contributions/openclaw`, `opensiro/meta` ACTIVE/ALLOW at intake; no public fork Issue or original-project consent implied. Canonical `openclaw/agent-skills` helper is independently owned.

## Existing work / overlap

[Original issue #201834](https://github.com/openclaw/openclaw/issues/201834) is OPEN and describes loss of completed reviewer output and true helper timeout due split deadlines and late submit. [Shipped Auto Review tool](https://github.com/openclaw/openclaw/blob/08b4ac92c1978f1f68dd78b53e7879ba24363c1b/extensions/autoreview/src/tool.ts#L361-L464) and [separately owned helper](https://github.com/openclaw/agent-skills/blob/3cc834ceec0410c4ff37c09e5b81c91e65fc9fc9/skills/autoreview/scripts/autoreview#L8856-L8872) indicate distinct timeout and exchange phases; [merged PR #173455](https://github.com/openclaw/openclaw/pull/173455) introduced restricted reviewer and [merged PR #200743](https://github.com/openclaw/openclaw/pull/200743) covers an outer watchdog, not this per-pass bug. Bounded PR search mentioning `#201834` found none, not an exhaustive no-PR guarantee. Existing fork Advisor and S4 roadmaps have different targets.

## Parallel contribution-on-top review

| Track | Existing → coverage | Proposed on-top change | Incremental operator outcome | Falsifier / evidence verdict |
| --- | --- | --- | --- | --- |
| **A · Original-native bug** | [Bundled Auto Review handoff](https://github.com/openclaw/openclaw/blob/08b4ac92c1978f1f68dd78b53e7879ba24363c1b/extensions/autoreview/src/tool.ts#L361-L464) plus [open #201834](https://github.com/openclaw/openclaw/issues/201834): restricted reviewer exists, but helper and reviewer timeouts are not coordinated; no submitted accepted repair identified | Minimal shared pass deadline and authoritative error propagation, under original owner and canonical-helper dependency | Prevent lost completed result and misleading timeout in the *existing* user task | This is a useful **native repair lead**, not sufficient evidence of new S3* C. Its actual solution, tests and maintainer decision remain separate |
| **B1 · Our provenance/receipt extension** | Existing helper already exchanges `run_id`, `pass`, `prompt_sha256`; issue calls for stage-specific error and reliable completion | A first-party durable audit-result receipt linking reviewer decision, failure stage and later operator inspection | Potentially easier diagnosis across restarts or repeated review passes | **NOT_EVIDENCED:** no independent operator need beyond the original fix, no supported durability/retention contract or legitimate new audit decision owner; if native P1 fixes diagnostics, no material delta |
| **B2 · Our S3* composition extension** | Shipped restricted reviewer is a component; separate [Advisor S3* roadmap](https://github.com/opensiro-contributions/openclaw/blob/opensiro/meta/.opensiro/issues/s3star-advisor-review-20261119/README.md) examines model-selection oversight, not this helper timeout | Developer-composed independent complementary-audit actor chooses `hold`/lawful correction, returns to S1/S3 with later feedback | Would be distinct only if an operator needs a new independently owned *organizational* correction decision, not simply delivered review text | **NOT_EVIDENCED:** no such extra task, actor authority/first-party installation or corrective-return requirement demonstrated; native result-delivery repair remains cheaper |
| **B3 · Our cross-repo integration** | Original plugin invokes separately owned [canonical helper](https://github.com/openclaw/agent-skills/blob/3cc834ceec0410c4ff37c09e5b81c91e65fc9fc9/skills/autoreview/scripts/autoreview#L8856-L8872) | One bounded deadline ownership contract + matched regression tests across both repos | Correct existing result handoff with less diagnostic loss | **COVERED BY ORIGINAL ISSUE INTENT:** valid narrow engineering hypothesis, not a distinct additional S3* feature; maintainer coordination is necessary before patches |

**Incremental-value conclusion:** an original issue is **not** a categorical veto. We independently considered an additional durable audit receipt, a composable corrective auditor and the cross-repo integration beyond shipped behavior. The cross-repo integration has concrete native-repair value **within original #201834**, but the proposed extra S3* constructor and persistent receipt lack independently justified incremental benefit. **NO_GO applies only to a new S3*=C constructor for this Auto Review handoff, not to native #201834 repair, another OpenClaw task, or the whole harness.** No new API, tests, cost measurement or external maintainer adoption claimed.

**Decision at this receipt:** NO_GO for bounded unproven additional S3*=C, separately preserving the original native bug repair as source-owned work. All on-top features are unshipped research hypotheses and require distinct adoption/engineering authority.

## Function ownership

Historical S1=A, S2=C and S3=C(P) already exclude mandatory new C target. Historical S3*=— is not proof of missing native reviewer feature. The current issue is reviewer *transport and diagnostic preservation*, not evidence of a separate independent complementary-audit organizational actor selecting and returning a lawful correction to later S1/S3 operations. S4 and S5 remain outside scope.

## Capability priority

**P0 — S3*=C new constructor:** NOT QUALIFIED / terminal **NO_GO** (no distinct operator demand, first-party decision ownership and closed corrective-return warrant). **P1 — native repair:** use existing original #201834 under separate maintainer authority, coordinate deadline/error propagation and targeted native regressions; not an admitted VSM capability. **P2: NONE**. [AI companion](https://github.com/opensiro-contributions/openclaw/blob/opensiro/meta/.opensiro/issues/s3star-autoreview-handoff-20261119/constructor-sufficiency.md) describes hypothetical A–E sufficiency only as an evidence gate, not installed product ports.

## Implementation options

Prefer smallest native shared deadline and terminal-cause repair in the original project if separately authorized and tested with canonical helper; do not create competing S3* controller, duplicate original Issue, source code, feature PR or new contribution record here. **Current decision: NO_GO to speculative constructor; separately tracked native bug remains actionable by its proper owner.** No tests or patches executed.

## Specification and domain alternatives

Original-native bug #201834 with owner decision is the first alternative; independently warranted Profile/Skills feedback only on proven semantic ambiguity; lawful, separately justified domain fork experiment is optional. Only Index can reassess actual VSM function ownership at a new source pin.

## Cost experiment

Measure identical completed-review outcome and authentic timeout diagnostics for minimal native fix versus any distinct future independently composed audit controller, including engineer/reviewer hours, helper synchronization, CI/native tests, integration and future maintenance. **NOT_MEASURED**, no claims of saved engineering effort.

## Delivery and publication

**PLAN_ONLY / DECISION_READY, terminal operator decision NO_GO for new S3*=C.** Fork-local case files [Human](https://github.com/opensiro-contributions/openclaw/blob/opensiro/meta/.opensiro/issues/s3star-autoreview-handoff-20261119/issue.md), [AI](https://github.com/opensiro-contributions/openclaw/blob/opensiro/meta/.opensiro/issues/s3star-autoreview-handoff-20261119/constructor-sufficiency.md), receipt and README. **Public fork GitHub Issue: DRAFT — NOT PUBLISHED** pending exact current-conversation approval. **External original Issue/comment/PR: DRAFT — NOT PUBLISHED**. No code, tests, fork-local contribution, new canonical Index grade, active reviewer or measured savings.
