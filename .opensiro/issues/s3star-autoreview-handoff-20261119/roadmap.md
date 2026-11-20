# Capability Roadmap Receipt — OpenClaw AutoReview quality-action handoff, post-v0.18.2

- Original repository: openclaw/openclaw
- Original HEAD: 1a7f34ffd7873e2b3ddb90073fc1220a852cf741
- Observed at: 2026-11-20
- Accepted Index assessment: https://github.com/opensiro/vsm-harness-index/blob/a3fcf7c156ef4d1132680890bc11544681fd30c0/assessments/op/openclaw.md
- Accepted assessment blob SHA: e1d560bc5b28d90323b15f5f1af6a5293c614b45
- Accepted Index commit SHA: a3fcf7c156ef4d1132680890bc11544681fd30c0
- Accepted review ref: 387da5edaa9d6c6cfcfc15e167fe2e46d8647d86
- Accepted reviewed at: 2026-09-16
- Profile version: 0.2.1
- Skills / assessment procedure version: 0.3.1
- System in focus: supported OpenClaw Gateway agent runtime, opt-in bundled sandbox AutoReview tool, host-owned tool policy and execution gate; external GitHub maintainers and canonical openclaw/agent-skills helper ownership excluded
- Result: PLAN_ONLY
- Receipt contract: proposal-gate
- Protocol pin: 5d004be0000bc6ecb7be62be4584318e8afcf315
- External issue: DRAFT — NOT PUBLISHED
- Cost status: NOT_MEASURED
- Accepted VSM vector: S1=A · S2=C · S3=C(P) · S3*=— · S4=— · S5=—
- Repository-wide source map: https://github.com/openclaw/openclaw/blob/1a7f34ffd7873e2b3ddb90073fc1220a852cf741/docs/concepts/session-tool.md; https://github.com/openclaw/openclaw/blob/1a7f34ffd7873e2b3ddb90073fc1220a852cf741/src/agents/tools/system-agent-tool.ts; https://github.com/openclaw/openclaw/blob/1a7f34ffd7873e2b3ddb90073fc1220a852cf741/extensions/autoreview/src/tool.ts; https://github.com/openclaw/openclaw/blob/1a7f34ffd7873e2b3ddb90073fc1220a852cf741/src/agents/exec-auto-reviewer.ts; https://github.com/openclaw/openclaw/blob/1a7f34ffd7873e2b3ddb90073fc1220a852cf741/docs/plugins/hooks/tool-policy.md; https://github.com/openclaw/openclaw/blob/1a7f34ffd7873e2b3ddb90073fc1220a852cf741/extensions/advisor/index.ts; https://github.com/openclaw/openclaw/blob/1a7f34ffd7873e2b3ddb90073fc1220a852cf741/docs/gateway/heartbeat.md; https://github.com/openclaw/openclaw/blob/1a7f34ffd7873e2b3ddb90073fc1220a852cf741/docs/concepts/dreaming.md; https://github.com/openclaw/openclaw/blob/1a7f34ffd7873e2b3ddb90073fc1220a852cf741/docs/reference/pull-request-review-flow.md; https://github.com/openclaw/openclaw/blob/1a7f34ffd7873e2b3ddb90073fc1220a852cf741/CONTRIBUTING.md
- Priority rationale: Source-native optional independent sandbox reviewer and terminal pre-tool policy already exist but do not yet connect independent candidate-quality judgment to an exact later controlled egress operation; small opt-in additional join rather than inventing deployment-wide S3* controller. Feasibility in Codex and indirect Code Mode remains a necessary falsifier.
- S1 disposition: Existing user agents perform operations through current tools; no additional S1 target.
- S2 disposition: Existing authorized session communications and child lifecycle construct coordination; no S2 target.
- S3 disposition: Session lifecycle and host-approved system-agent operations implement present control with legitimate parent reserved rights; no S3 target.
- S3* disposition: Current AutoReview produces complete independent sandboxed candidate review but only returns a report to the caller; no demonstrated host-enforced review-to-exact-following-action closure for the narrow opt-in operation; P0 HYPOTHETICAL.
- S4 disposition: Automation/cron and dreaming support scheduled/current work and memory, not proved independent external prospective adjustment; no S4 objective selected.
- S5 disposition: Configured permissions, approvals and external maintainers are legitimate parent authority, not evidence of local identity/policy C; NO_TARGET.
- Target transition: S3*=— -> S3*=C
- P1 dependencies: Pin and test exact first-party pre-tool interception for allowed exec / Codex native shell, ensure other publication routes are out of scope or independently denied; bind current sandbox Git candidate identity and reviewer report to execution request and expiry; prove legitimate host permissions and complete negative/compatibility tests.
- P2 optional: NONE
- Proposed C construction: In an explicitly enabled sandbox development mode, an independent developer-composed candidate-quality reviewer decides allow-to-present or hold-to-rework from native AutoReview's validated snapshot/report; a first-party restricted execution hook binds that decision to one exact approved Git publication action and requires matching fresh evidence before effect. A hold denies the operation with feedback to the working agent; a lawful accepted action returns effect/status. The reviewer can choose a different quality outcome without obtaining host authorization rights.
- C sufficiency falsifier: Existing shipped original code already binds exact independent candidate-quality outcomes to protected publication; or the chosen original-native tool path cannot reliably mediate the operation and exclude bypasses/TOCTOU; or reviewer is merely a preset boolean policy rather than developer-composable independent decision owner.
- Scenario basis: HYPOTHETICAL
- Proposal-stage decision: GO
- Research disposition: NEEDS_EVIDENCE
- Proposed validation: Native matched sandbox tests for allow, hold/rework, stale candidate or report, missing/revoked reviewer, failed review, parent/host deny, path bypass, no-opt-in compatibility and downstream confirmed delivery/failure. Compare minimal manual AutoReview + maintainer gate under the same task.
- Validation state: NOT_RUN
- Proposal falsifier: No enforceable exact supported egress operation or distinguishable autonomous quality decision and return; any direct or indirect bypass yields NO_GO for the declared construction.
- Claim status: First-pass independent and sealed in https://github.com/opensiro/upstream/issues/58#issuecomment-7047187780, then compared to historical same-case NO_GO.
- Case ID: s3star-autoreview-handoff-20261119
- Fork metadata branch: opensiro-contributions/openclaw@opensiro/meta

## Identity and pins

2026-11-20 original [source HEAD](https://github.com/openclaw/openclaw/commit/1a7f34ffd7873e2b3ddb90073fc1220a852cf741); separate historical accepted [Index document](https://github.com/opensiro/vsm-harness-index/blob/a3fcf7c156ef4d1132680890bc11544681fd30c0/assessments/op/openclaw.md) / blob e1d560bc5b28d90323b15f5f1af6a5293c614b45 from 2026-09-16. Historical review age 65 days suggests a separately owned reassessment, never a silent promotion to C. [Human Issue](issue.md) and [AI contract](constructor-sufficiency.md) derive target and verdict here.

## Rights and authority

[MIT](https://github.com/openclaw/openclaw/blob/1a7f34ffd7873e2b3ddb90073fc1220a852cf741/LICENSE); [first-party contributor rules](https://github.com/openclaw/openclaw/blob/1a7f34ffd7873e2b3ddb90073fc1220a852cf741/CONTRIBUTING.md) require original feature/architecture discussions before feature PRs. No automatic original maintainer interest, contributor CLA status, GitHub publication, model privileges or right to change parent authority was inferred. Matching fork opensiro-contributions/openclaw, parent openclaw/openclaw, state ACTIVE / ALLOW read 2026-11-20; recheck before effect. Public fork Issue and original communication require separate exact owner approval.

## Existing work / overlap

Current SHIPPED [optional AutoReview tool](https://github.com/openclaw/openclaw/blob/1a7f34ffd7873e2b3ddb90073fc1220a852cf741/extensions/autoreview/src/tool.ts), [host reviewer isolation and validated sandbox result](https://github.com/openclaw/openclaw/blob/1a7f34ffd7873e2b3ddb90073fc1220a852cf741/docs/tools/autoreview.md), [pre-tool block/approval policy](https://github.com/openclaw/openclaw/blob/1a7f34ffd7873e2b3ddb90073fc1220a852cf741/docs/plugins/hooks/tool-policy.md), [command risk-only reviewer](https://github.com/openclaw/openclaw/blob/1a7f34ffd7873e2b3ddb90073fc1220a852cf741/src/agents/exec-auto-reviewer.ts), and [ordinary maintainer PR review](https://github.com/openclaw/openclaw/blob/1a7f34ffd7873e2b3ddb90073fc1220a852cf741/docs/reference/pull-request-review-flow.md). Issue [#201834](https://github.com/openclaw/openclaw/issues/201834) remains OPEN for a **different** real AutoReview timeout/result-handoff bug. PR [#173455](https://github.com/openclaw/openclaw/pull/173455) is merged and first-party reviewer path shipped. PR [#200743](https://github.com/openclaw/openclaw/pull/200743) is merged but covers outer watchdog; [#175529](https://github.com/openclaw/openclaw/pull/175529) is merged and fixes parent limits. Original [#172336](https://github.com/openclaw/openclaw/issues/172336) is open; draft PR [#172345](https://github.com/openclaw/openclaw/pull/172345) is closed unmerged. These do not demonstrate the scoped quality-decision-to-egress path. An open original [PR #156804](https://github.com/openclaw/openclaw/pull/156804) adjusts maintainer review guidance, not first-party runtime enforcement. No extra PR created.

## Parallel contribution-on-top review

- Evaluation object: Narrow opt-in independent S3* review decision controlling one host-mediated sandbox Git egress operation, not generic AutoReview reliability, all publishing routes or deployment-wide review authority.
- Existing-work overlap: AutoReview validated sandbox diff/report, first-party pre-tool blocking, native exec restrictions; existing original timeout bug #201834 is separate, and maintainer PR reviews are external human governance.
- Our on-top contribution: Proposed host-authoritative binding of authenticated review-candidate snapshot and independently chosen quality disposition to an exact one-time native publication call plus denial/effect feedback; no new generic reviewer, durable audit database or mandatory model call.
- Incremental benefit: HYPOTHETICAL ability for a developer to compose an independent quality reviewer that prevents an otherwise permitted premature candidate push and reports what to repair; unmatched against current manual AutoReview + human PR gate; NOT_MEASURED.
- Decision scope: GO / NEEDS_EVIDENCE only for source-grounded proposed opt-in S3* C construction, not maintainer adoption, native bug fix, Index regrade or shipped solution.

Historical after-sealing comparison: the 2026-11-19 fork-local [prior receipt](https://github.com/opensiro-contributions/openclaw/blob/51ba426d95e2f65e0274d48e6f333439b7c19df7/.opensiro/issues/s3star-autoreview-handoff-20261119/roadmap.md) made **NO_GO** against an extra **general S3* auditor added to a timeout/diagnostic repair** after inspecting original [#201834](https://github.com/openclaw/openclaw/issues/201834). That NO_GO remains valid for its object. The independent 2026-11-20 first-pass added a different, narrower object: binding an independent reviewer outcome to an exact downstream operation via native authorization. GO is thus a new prospective scope hypothesis, not retroactive evidence that prior timeout repair needed S3* or the earlier verdict was defective.

| Track A — actual current native path | Track B — one bounded hypothetical bridge | Remaining structural/falsification question |
| --- | --- | --- |
| Optional [AutoReview](https://github.com/openclaw/openclaw/blob/1a7f34ffd7873e2b3ddb90073fc1220a852cf741/extensions/autoreview/src/tool.ts) reports independent sandboxed Git findings | Compose an independent allow/hold decision from validated same-candidate report | Report alone does not decide/enforce later operational work |
| [before_tool_call](https://github.com/openclaw/openclaw/blob/1a7f34ffd7873e2b3ddb90073fc1220a852cf741/docs/plugins/hooks/tool-policy.md) can block calls and return reason | Bind a protected exact Git action to hash-matching reviewer verdict in declared host-exec lane | Can indirect commands and alternate egress bypass? Fail closed or disqualify lane |
| Host approval and [original contributor process](https://github.com/openclaw/openclaw/blob/1a7f34ffd7873e2b3ddb90073fc1220a852cf741/CONTRIBUTING.md) remain authoritative | Do not grant publication or override human approval; hold reports back to agent | Is developer composed auditor truly independent, not deterministic permission check? |

## Function ownership

Historical six-function baseline remains unchanged; current source roles and exclusions are recorded in [Human combined table](issue.md). Narrow S3* requires the independently configured reviewer to make the quality choice, while host enforcement is subordinate transport. Keep existing S2 coordination, S3 parent control, scheduled S4-like tasks and legitimate S5 operator identity separate. Reviewer must not approve otherwise unauthorized action.

## Capability priority

**P0:** one proposed original-native S3* quality decision → protected egress → downstream effect/denial → feedback loop. **P1:** exact tool and requester policy coverage, freshness/snapshot verification, mandatory no-bypass boundaries, source-native tests. **P2:** NONE. Architectural sufficiency PROPOSED_C_SUFFICIENT on a restricted explicitly configured path, UNVALIDATED outside it. An optional path may be purposely unsupported without changing other modes.

## Implementation options

Use the shipped sandbox AutoReview helper and existing hook/approval infrastructure first. Add a narrowly scoped first-party state join at https://github.com/openclaw/openclaw/blob/1a7f34ffd7873e2b3ddb90073fc1220a852cf741/extensions/autoreview/src/tool.ts and the host-owned pre-tool policy/execution boundary documented in https://github.com/openclaw/openclaw/blob/1a7f34ffd7873e2b3ddb90073fc1220a852cf741/docs/plugins/hooks/tool-policy.md; do not build a separate S3* process supervisor. If precise evidence binding cannot be made for the permitted source/native exec path, close this scope NO_GO rather than claiming a generic safety guard.

## Specification and domain alternatives

Preserve current manual AutoReview followed by human maintainer review as simplest baseline. Any claim that Profile or Skills must reclassify AutoReview as S3* needs its own source-reasoned method review; none made here. A domain research fork is optional only with legal permissions and a real use case. Original maintainers control features, implementation and acceptance.

## Cost experiment

Proposed paired task: same sandbox candidate, compare existing manual review plus permitted push and a future opt-in independent reviewer enforcement path; measure total integration, review and maintenance, refusal quality and genuinely avoided errors. **NOT_MEASURED**; no saved effort or benefit asserted.

## Delivery and publication

**PLAN_ONLY · GO / NEEDS_EVIDENCE · NOT_RUN**, fork-local Human / AI / receipt / README, no native code changes, no new contribution ID, no public fork Issue, no original Issue/comment/PR, no Index change. Public fork GitHub Issue draft remains **DRAFT — NOT PUBLISHED**; external action needs exact current-conversation approval. Upstream #58 holds only short coordination; no status-only Upstream PR per current v0.18.2 protocol.
