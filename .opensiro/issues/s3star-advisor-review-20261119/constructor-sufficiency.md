# OpenClaw Advisor — native S3* complementary audit constructor contract

**Status:** PLAN_ONLY / HYPOTHETICAL. **DRAFT — NOT PUBLISHED.** Native tests NOT_RUN; benefit and costs NOT_MEASURED.
**Target transition:** S3*=— -> S3*=C
**Proposal-stage decision:** GO
**Research disposition:** NEEDS_EVIDENCE
**Validation state:** NOT_RUN

**Level 1:** [issue.md](issue.md). **Canonical single decision:** [roadmap.md](roadmap.md). This technical document does not create a second grade or a second case ID.

## 1. Function boundary and counterfactual decision owner

**Original source pin:** [openclaw/openclaw@599bc4222a48594445c7d531c063be828be3482a](https://github.com/openclaw/openclaw/commit/599bc4222a48594445c7d531c063be828be3482a) (observed 2026-11-20). Trusted Gateway plus configured assistant and bundled Advisor for admitted user-directed runs are in scope. Operator approvals and host tool permission remain authoritative; Foundation/governance, model providers, external plugins and maintenance decisions are outside. Accepted Index historical states, six-function dispositions, review ref/blob and source relevance are centralized in [roadmap.md](roadmap.md).

**Selected S3* operating disturbance:** an already admitted agent is about to continue after a settled tool outcome shows a possible harmful contradiction, repeated no-op or unsupported completion claim. Its ordinary Advisor can advise the acting model, but cannot decide a bounded enforceable hold; a model fork is not a complementary operational closure.

**Function-specific decision right:** a trusted developer-installed independent Advisor reviewer (not the acting S1 agent or parent operator) decides a limited complementary CONTINUE / HOLD_FOR_OPERATOR / CORRECT_AND_REAUDIT on an exact run/version based on settled first-party tool evidence. The existing Gateway alone enforces the valid effect according to host policy. The operator, not the reviewer, may authorize resumed execution or deny. The reviewer receives the exact applied/denied/expired outcome before a subsequent audit; S3 can observe any permitted run status without ceding S3 authority.

**Counterfactual:** with the reviewer removed, Gateway still runs sessions and enforces its own hard policies but makes no independent case-specific S3* judgment. A fixed host always-HOLD or a self-review suggestion is not equivalent to a developer-selected autonomous audit owner. If removing the reviewer changes nothing in a matched run, C is falsified. If the configured reviewer can silently turn itself into a trusted operator, the proposed parent boundary is invalid and should stop.

**Function interactions:** S1 performs user tasks; S2 delivers session/routing status; S3 hosts current operational controls; proposed S3* audits complementary evidence and closes an independent decision/effect/return; S4 is not added; S5 rights remain with original host/operator. Do not treat native security logging, a reviewer name, an unmerged PR, human preference or a ModelOps subsystem as proof of C.

## 2. First-party Track A and independent on-top Track B

| Necessary source-specific witness | Track A current first-party source or original proposal | Track B minimal missing construction | Falsifier |
| --- | --- | --- | --- |
| Settled-result review trigger | [Advisor index.ts](https://github.com/openclaw/openclaw/blob/599bc4222a48594445c7d531c063be828be3482a/extensions/advisor/index.ts) tracks started/resolved tool calls and schedules review after resolution | Reuse current event subscription and stable run identity for a bounded evidence window; do not send incomplete results | Evidence cannot be lawfully accessed or reviewed at a stable version |
| Independent configurable audit actor | [Advisor manifest](https://github.com/openclaw/openclaw/blob/599bc4222a48594445c7d531c063be828be3482a/extensions/advisor/openclaw.plugin.json) exposes triggers/instructions, not model selector. [Issue #184787](https://github.com/openclaw/openclaw/issues/184787) OPEN, [PR #196242](https://github.com/openclaw/openclaw/pull/196242) OPEN proposes model selection with host policy | Compose an independently configured trusted audit decision path in Advisor. Reuse any upstream accepted model-selection interface rather than duplicating open PR | Current model picker already has independently binding run-wide audit / nothing extra is chosen |
| Enforced later operation | Advisor [steerActiveRun](https://github.com/openclaw/openclaw/blob/599bc4222a48594445c7d531c063be828be3482a/extensions/advisor/index.ts) sends CORRECTION as advice; no plugin-supplied binding pause confirmed | Small explicitly host-owned run/step admission hook, version-checked HOLD/CONTINUE result before **next** tool/turn, with parent policy precedence and expiry | Holding work requires unauthorized S5 escalation or no first-party admission boundary can be implemented |
| Actual feedback for audit closure | [Gateway audit docs](https://github.com/openclaw/openclaw/blob/599bc4222a48594445c7d531c063be828be3482a/docs/gateway/audit.md) keep metadata-only facts; approvals retain native owners | Return actual hold applied/denied/expired, parent resume decision and later authorized task result to audit actor without inventing content ledger or approval | No feedback path; only text warning, unsafe immediate execution, or false success |

**Native alternatives:** (A) unchanged bundled Advisor for advice and manual review; (B) native original model-picker #196242 once independently accepted and tested; (C) narrow existing exec Auto Review for exec only. The proposed C is intentionally an optional run-wide complementary decision/return, not a second generic review framework or duplicate #196242.

**Original overlap facts at the time of review:** [#196242](https://github.com/openclaw/openclaw/pull/196242) OPEN / UNMERGED at cfd89afbe771bfdbc69cf5c7be203a2cd85e327f, dependent [#196240](https://github.com/openclaw/openclaw/pull/196240) OPEN / UNMERGED at 6eae1f6b169d964735d9c01432e4ce553d83b743. [#193891](https://github.com/openclaw/openclaw/issues/193891) OPEN fork-failure report; [#196230](https://github.com/openclaw/openclaw/issues/196230) OPEN nested trigger inflation; [#198097](https://github.com/openclaw/openclaw/issues/198097) OPEN persistent correction injection report. Original Issues are evidence of native ownership and possible fragility, not a maintainer product veto and not an excuse to duplicate fixes.

## 3. Smallest first-party constructor and actual authority chain

| First-party component | Current native behavior | Proposed minimal integration | Decisive owner, effect and return |
| --- | --- | --- | --- |
| extensions/advisor/index.ts + Advisor plugin metadata | Session-owned review schedule, forked model decision and nonbinding steer | Allow a trusted developer-configured independent reviewer returning typed CONTINUE, HOLD_FOR_OPERATOR, CORRECT_AND_REAUDIT for an exact settled run/step snapshot; no tool authority in review fork | Independent reviewer decides complementary audit; timestamped verdict and explicit reason return to the host |
| Existing Gateway agent execution admission / host approvals | Execution respects current caller, tool policy and operator-owned approvals | One opt-in native run-versioned admission/hold bridge, scoped only to that Gateway run; preserve existing policy and prevent stale/ended-run holds | Gateway validates authority and executes only a lawful hold or continue before a later step; parent alone approves resume |
| Existing run status, audit and result channels | Metadata-only audit and terminal host approval receipts; source-backed owner boundaries | Return exact applied / rejected / expired hold + resumed task success/failure to the independent reviewer under permitted visibility | Reviewer learns whether its decision changed later work; no fabricated approval or reinterpreted audit ledger |

**Physical ports not prescriptive.** The minimal missing link is a host-enforced, first-party, narrowly scoped later-step hold and real feedback. Existing advisor events/review scheduling are reused. Selecting an independent model without this link is not enough; adding a universal new supervisor would be unnecessarily broad. The strong positive witness requires the combination and tests, not a text sketch.

**Dependency order:** verify SDK/host policy capability and maintainer-owned support path → implement opt-in adapter with explicit parent authorization and immutable run-bound evidence → prove two different lawful audit choices and actual Gateway return → compare against unchanged Advisor. No original code changes in this PLAN_ONLY case. P0/P1/P2 values are owned by the [roadmap.md](roadmap.md) receipt, not independently redefined here.

## 4. Scope, options and stop conditions

Proposed P0 S3* bounded Advisor complementary audit. P1 rights checks, source-specific native tests and accurate overlap readback. P2 NONE. No new S1, S2, S3, S4, S5 or cross-project controller.

**Option 1:** same-model Advisor, operator review unchanged (smallest native path; no C claim). **Option 2:** original #196242 reviewer model only (not shipped; independent selection without binding closure). **Option 3:** optional trusted reviewer verdict plus Gateway-owned next-step hold, versioning and feedback (strongest bounded C candidate). **Option 4:** decline feature entirely if source-native policy, privacy, integration or measured task outcome does not justify adoption; maintainer controls that product choice independently of architecture feasibility.

Stop architectural GO if shipped native C already fulfills the same decision/authority/return, no authorized plugin host hook can enforce next-step hold, the reviewer cannot independently choose, material evidence is legally unavailable, or real later feedback is impossible. Stop any outward implementation/publication until exact authorizations are provided, regardless of the architectural result.

## 5. Proposed future native acceptance, not executed

Current original has pnpm scripts and Vitest tests, but no new test was run in this review. Future tests belong with actual first-party edited files; **native tests NOT_RUN**.

| Future test derived from OpenClaw path | Source-based native setup | Expected operational result | Falsifier |
| --- | --- | --- | --- |
| Positive independent HOLD | Opt-in Advisor enabled, controlled settled tool outcome and exact run/step; plugin event and Gateway admission | Before next tool starts, authorized version-checked hold is enforced; operator resolves; reviewer receives actual result | Advice only / next operation already ran / fabricated approval |
| Independent CONTINUE | Same active run and evidence, reviewer selects different lawful option | Next operation proceeds under unchanged Gateway policy; feedback records continued outcome | Gateway hard-codes hold regardless of reviewer |
| Missing/stale/revoked | No reviewer, expired run version, ended session or parent denial | No unauthorized hold or resume, baseline fail-safe behavior, explicit not-applied receipt | Privilege escalation, stale effect or silent success |
| Unsettled tool call / review cancellation | Pending tool event and session reset using Advisor scheduler | No audit decision made from synthetic/missing outcome; cancelled review cannot act | Provisional result treated as final |
| Matched original-native comparison | Identical permitted task with shipped Advisor, compare proposed opt-in path | Observe whether binding independent decision changes an authorized later outcome; log incremental cost | Same lawful outcome with unchanged Advisor and no extra closure |

Cost, latency and qualitative comparison: **NOT_MEASURED**. This is an acceptance sketch, not a passing test suite.

## 6. Verdict, historical attribution and next permitted action

**Proposal-stage decision:** GO
**Research disposition:** NEEDS_EVIDENCE

Evidence for first pass [sealed before reading history](https://github.com/opensiro/upstream/issues/58#issuecomment-7045525751). Earlier same case at [fork@67e1d5d](https://github.com/opensiro-contributions/openclaw/blob/67e1d5dbf58accf8b0f6cf445caf198294144c53/.opensiro/issues/s3star-advisor-review-20261119/constructor-sufficiency.md) judged duplicate reviewer-model selection NO_GO, and did not establish direct-evidence binding audit. That NO_GO remains valid for that *narrow native duplicate*. The current v0.18.1 review changes only the scoped architectural conclusion for a clearly missing binding complementary audit path, not the preexisting model selector, separate direct-evidence/AutoReview cases, or the historical assessment.

The source of truth for official grades is the Index; upstream original maintainers own any feature adoption and implementation; the [roadmap.md](roadmap.md) receipt owns structured case result. Developer and operator may evaluate actual constraints/tests under a separately authorized task. Internal fork case metadata ACTIVE / ALLOW only; external public issue/PR/comment NOT_PUBLISHED and not authorized. AI-assisted research disclosed.
