# Capability Roadmap Receipt — OpenClaw S3* Advisor, Wave 4 v0.18.1

- Original repository: openclaw/openclaw
- Receipt contract: proposal-gate
- Original HEAD: 599bc4222a48594445c7d531c063be828be3482a
- Observed at: 2026-11-20
- Accepted Index assessment: https://github.com/opensiro/vsm-harness-index/blob/a3fcf7c156ef4d1132680890bc11544681fd30c0/assessments/op/openclaw.md
- Accepted assessment blob SHA: e1d560bc5b28d90323b15f5f1af6a5293c614b45
- Accepted review ref: 387da5edaa9d6c6cfcfc15e167fe2e46d8647d86
- Accepted reviewed at: 2026-09-16
- System in focus: First-party trusted OpenClaw Gateway, configured assistant and bundled Advisor for admitted user-directed runs; external provider, third-party plugins and foundation governance excluded
- Repository-wide source map: Gateway sessions/subagents in docs/concepts/session-tool.md; S3 system-agent in src/agents/tools/system-agent-tool.ts; S3* Advisor in extensions/advisor/index.ts and openclaw.plugin.json; audit in docs/gateway/audit.md; S5 parent approvals in docs/cli/approvals.md
- Priority rationale: S3* alone has a source-native independent reviewer path and a clear missing binding admission decision; other absent grades do not imply feature need
- Accepted VSM vector: S1=A · S2=C · S3=C(P) · S3*=— · S4=— · S5=—
- S1 disposition: A / existing user tasks and subagents; preserve current autonomous execution
- S2 disposition: C / native session lifecycle, messaging and coordination; not the target
- S3 disposition: C(P) / current host-scoped operations and operator-approved config writes; not the target
- S3* disposition: historical — / native Advisor supplies nonbinding correction; opt-in independent bounded audit closure remains a proposed C constructor, not shipped
- S4 disposition: historical — / memory and update facilities are not evidence of separately owned prospective S4
- S5 disposition: historical — / operator-controlled policy and approval are parent rights, not reviewer-owned S5
- Target transition: S3*=— -> S3*=C
- P1 dependencies: Explicit host authorization for a reviewer-run hold interface; source-native negative policy tests; existing Advisor reliability issues and independent model routing are separately owned
- P2 optional: NONE
- Proposed C construction: Trusted developer-configured Advisor complementary auditor reads settled tool-result evidence; independently chooses CONTINUE/HOLD_FOR_OPERATOR/CORRECT_AND_REAUDIT; version-checked Gateway admission guard enforces a lawful hold before a later operation and returns actual resume/denial/outcome feedback
- C sufficiency falsifier: Equivalent independent first-party run-wide binding audit already shipped; no lawful plugin-host gate can be exposed; no independent audit decision owner or effective returned correction after matched native tests
- Scenario basis: HYPOTHETICAL
- Proposal-stage decision: GO
- Research disposition: NEEDS_EVIDENCE
- Proposed validation: Native mocked Gateway run and actual plugin integration tests for continue versus hold, stale run, missing/revoked reviewer, policy deny and delivery of later disposition; matched against unchanged Advisor
- Validation state: NOT_RUN
- Proposal falsifier: An identical downstream user result from unchanged Advisor or an existing native auto-review without independent S3* owner, or failure to enforce the bounded hold without overriding parent policy
- Result: NEEDS_EVIDENCE
- Final operator decision: GO (architectural hypothesis only; no implementation/product decision)
- External issue: DRAFT — NOT PUBLISHED
- Cost status: NOT_MEASURED

## Identity and pins

Fresh source-only first pass was sealed before any earlier OpenSiro case read at [Upstream #58 comment #7045525751](https://github.com/opensiro/upstream/issues/58#issuecomment-7045525751). Original main [599bc4222a48594445c7d531c063be828be3482a](https://github.com/openclaw/openclaw/commit/599bc4222a48594445c7d531c063be828be3482a) was observed on 2026-11-20. Accepted Index [included assessment](https://github.com/opensiro/vsm-harness-index/blob/a3fcf7c156ef4d1132680890bc11544681fd30c0/assessments/op/openclaw.md) is separate historical evidence, with unchanged blob/review ref, Profile 0.2.1 and Skills Methodology 0.3.1. Accepted source ref resolves; Index catalog matches harness_id openclaw, original URL and review_ref. Current protocol [Upstream v0.18.1](https://github.com/opensiro/upstream/blob/3a411a810b4679e07ccf095c5652c9625f916603/PROTOCOL.md). No Index regrade or new source-grade inference.

## Rights and authority

Original MIT license, [contribution rules](https://github.com/openclaw/openclaw/blob/599bc4222a48594445c7d531c063be828be3482a/CONTRIBUTING.md), third-party plugin preference and feature request routing inspected. Matching fork parent openclaw/openclaw; opensiro-contributions/openclaw on independent opensiro/meta branch has ACTIVE / ALLOW, rechecked before any write. This allows internal source-pinned metadata, not a fork-public issue, external issue/PR/comment, code implementation or S5 grant. Existing operator approvals and execution policy remain authoritative. No claim of accepted maintainer product preference or waived attestations.

## Existing work / overlap

Track A shipped: [bundled Advisor](https://github.com/openclaw/openclaw/blob/599bc4222a48594445c7d531c063be828be3482a/extensions/advisor/index.ts) uses current session model, completed tool events, a cancellable scheduled review, NO_CHANGE/CORRECTION, and nonbinding steerActiveRun; [manifest](https://github.com/openclaw/openclaw/blob/599bc4222a48594445c7d531c063be828be3482a/extensions/advisor/openclaw.plugin.json) currently has no independent model selector. [Gateway audit](https://github.com/openclaw/openclaw/blob/599bc4222a48594445c7d531c063be828be3482a/docs/gateway/audit.md) is metadata-only evidence, not model semantic audit. Exec Auto Review operates at a separate tool/approval boundary. Original Issue [#184787](https://github.com/openclaw/openclaw/issues/184787) OPEN and [PR #196242](https://github.com/openclaw/openclaw/pull/196242) OPEN / UNMERGED at cfd89afbe771bfdbc69cf5c7be203a2cd85e327f propose independent model selection; prerequisite [PR #196240](https://github.com/openclaw/openclaw/pull/196240) OPEN / UNMERGED at 6eae1f6b169d964735d9c01432e4ce553d83b743. #193891 reports fork failures, #196230 trigger inflation; not new permissions or an enforced audit outcome. These facts cannot by themselves veto a distinct C construct or authorize publication.

## Parallel contribution-on-top review

- Evaluation object: Independently developer-composed, complementary S3* audit of an admitted Advisor-reviewed user task, with lawful binding hold or corrective return beyond model choice alone
- Existing-work overlap: Current Advisor can inject advice; #184787/#196242 address reviewer-model selection but no binding independent run-level audit decision; exec Auto Review is narrower; direct-evidence S3* and AutoReview cases remain separate
- Our on-top contribution: Reuse Advisor settled-tool event scheduling, add minimal host-enforced run-versioned admission hold for trusted independent configured reviewer, return operator-approved outcome without transferring S5
- Incremental benefit: Hypothetical safe prevention of next bad step or independent re-audit versus a correction the executor may ignore; no operator outcome or saved cost measured
- Decision scope: GO only for a coherent source-specific S3*=C architecture; NO_GO still applies to a duplicate review-model selector. OpenClaw maintainers decide adoption.

| A — existing native behavior | B — smallest original-native on-top path | Counterfactual |
| --- | --- | --- |
| Advisor review is tool-free and sends advisory steering when active | Trusted config selects a separate audit decision owner and settled tool evidence; do not clone #196242 model selector | If existing model selector alone supplies binding independent audit and later return, B duplicates |
| Gateway owns real run admission, tool policies, operator approval | One run-version-checked hold/continue effect at the Gateway admission boundary plus auditable feedback; no speculative external controller | If a plugin cannot lawfully bind this boundary, architecture stops |
| Native audit ledger records limited metadata without content | Use existing settled result events for bounded evidence; keep sensitive data in the host, not an external audit corpus | If evidence cannot lawfully be shown to the auditor, no GO at supported boundary |

## Function ownership

Historical S1=A, S2=C, S3=C(P), S3*=—, S4=—, S5=— are ownership classifications, not ranks or present-day deficits. Advisor's same-model review and steering is not an independent binding audit owner; Gateway owns transport/policy; the developer-installed reviewer would own only the bounded complementary C choice if built. No new S3 or S5 owner; operator veto and parent recursion unchanged.

## Capability priority

P0: one opt-in S3* Advisor complementary audit constructor, not a generic controller and not the existing model selector alone. P1: actual plugin SDK/Gateway authorization boundary, negative permission and stale-run tests, source-native integration; unrelated open bugs remain original-owned. P2: NONE. The best simpler alternative is unchanged Advisor plus current manual operator intervention, or existing original PRs for model choice, when binding independent audit is not required. Product adoption and utility remain unmeasured.

## Implementation options

Option A: reuse native Advisor unmodified (no C witness). Option B: integrate open #196242 model selection when maintained (independence of model without enforceable S3* closure). Option C, proposed: preserve Advisor's completed-tool event cadence and add an explicit developer-selected independent audit verdict + Gateway-enforced versioned hold before the next tool turn, returning actual resume/reject result. If even the narrow admission hook requires unlawful parent authority or first-party development is prohibited, stop without implementing. No new code proposed in this run.

## Specification and domain alternatives

Accepted Skills/Profile semantics remain unchanged. Index can separately re-evaluate the evolved current OpenClaw architecture; this receipt cannot regrade S3*. No mandatory S4/S5 expansion or unrelated domain-specific repository. Distinct other OpenClaw S4, direct-evidence S3* and AutoReview cases must not be overwritten.

## Cost experiment

Compare two identical authorized tasks: native Advisor unmodified versus opt-in independent review and bounded hold. Observe actual premature step prevention, false holds, correction/return latency, tokens, integration/review effort and ongoing cost. No actual run or economic measurement: NOT_MEASURED. No maintenance or benefit claims.

## Delivery and publication

**Historical comparison only after independent verdict:** The 2026-11-19 [prior case](https://github.com/opensiro-contributions/openclaw/blob/67e1d5dbf58accf8b0f6cf445caf198294144c53/.opensiro/issues/s3star-advisor-review-20261119/roadmap.md) said NO_GO to a duplicate reviewer-model selector and found adjacent direct-evidence audit NOT_EVIDENCED. Preserve that narrow NO_GO as valid history, but v0.18.1 evaluates architectural constructibility of a **different, explicitly bounded missing binding audit link**, not product demand. The new scoped GO neither disproves the original no-duplicate conclusion nor creates a second separate case for the same Advisor evaluation stream. Separate OpenClaw S3* Direct Evidence and AutoReview original cases remain untouched.

Current research is PLAN_ONLY, GO / NEEDS_EVIDENCE, HYPOTHETICAL. Native code/tests NOT_RUN, costs NOT_MEASURED, fork-public/original-public publication NOT_PUBLISHED. Detailed Human [issue.md](issue.md) and AI [constructor-sufficiency.md](constructor-sufficiency.md) must mirror this target and verdict. External original Issue/PR/review/comment requires distinct exact current-conversation approval; none is provided. No Upstream status-only PR or per-run report created.
