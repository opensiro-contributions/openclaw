# Capability Roadmap Receipt — OpenClaw direct-evidence S3* complement

- Original repository: openclaw/openclaw
- Original HEAD: cd2ae19272a3ee7be456385fa7efc56d6e2109a6
- Observed at: 2026-11-19
- Accepted Index assessment: https://github.com/opensiro/vsm-harness-index/blob/394ce776e6945115891b8f7cc459f5a7f7d7aa39/assessments/op/openclaw.md
- Accepted assessment blob SHA: e1d560bc5b28d90323b15f5f1af6a5293c614b45
- Accepted review ref: 387da5edaa9d6c6cfcfc15e167fe2e46d8647d86
- Accepted reviewed at: 2026-09-16
- System in focus: Self-hosted OpenClaw Gateway, admitted agent runs and first-party enabled plugins under operator session/tool policy; excludes Foundation governance, CI and third-party installed plugins
- Receipt contract: proposal-gate
- Result: NEEDS_EVIDENCE
- Repository-wide source map: Pinned Git tree inventory of src, extensions, docs, apps, packages plus Gateway, agents, S3 control, Advisor, audit, automations, policy and plugin SDK; issue/PR bodies screened; NOT exhaustive per-file reading
- Priority rationale: S3* supports a narrowly falsifiable missed-claim versus host-evidence outcome with reusable SDK, unlike redundant S1/S2/S3 and speculative S4/S5 controllers
- Accepted VSM vector: S1=A · S2=C · S3=C(P) · S3*=— · S4=— · S5=—
- S1 disposition: NO_TARGET — admitted autonomous task runs already operate
- S2 disposition: DEFER — cross-session tools exist; no incremental interference-specific case proved
- S3 disposition: DEFER — host-approved system agent and current control; preserve operator authority
- S3* disposition: P0 — opt-in direct-evidence sampled complementary audit with decisive reviewer and lawful S3 feedback
- S4 disposition: DEFER — Dreaming/automations alone do not show external prospective strategy/return
- S5 disposition: NO_TARGET — legitimate human ultimate authority; no forced policy agent
- Target transition: S3*=— -> S3*=C
- P1 dependencies: Verify scoped host tool-result/artifact evidence, plugin model permission, durable finding custody, right to invoke existing trusted policy and later effect readback
- P2 optional: Matched effectiveness/cost comparison with shipped Advisor and original PR #196242 if qualified after P1
- Proposed C construction: Optional first-party SDK plugin with host-observed evidence sampler, independent bounded audit actor, scoped policy handoff and verified next-run effect
- C sufficiency falsifier: No independently available host evidence, forbidden reviewer/S3 transfer, nonbinding report, or equivalent native complete audit already present
- Scenario basis: HYPOTHETICAL
- Proposal-stage decision: GO
- Research disposition: NEEDS_EVIDENCE
- Proposed validation: Positive claim/result contradiction and authorized next-operation hold/repair receipt; negative missing result, revoked scope, operator veto, unchanged baseline and no feedback
- Validation state: NOT_RUN
- Proposal falsifier: The same authorized operator outcome is achieved by the shipped Advisor or merged native PR without added audit actor or permission is insufficient
- Evaluation object: Post-run or sampled host-evidence-based independent verification of an agent result and bounded return of a disputed claim to current control; not an Advisor model-selector or Auto Review timer repair
- Existing-work overlap: Bundled Advisor SHIPPED, trajectory export SHIPPED with owner controls, Advisor model issue #184787 OPEN, PR #196242 OPEN at cfd89afbe771bfdbc69cf5c7be203a2cd85e327f
- Our on-top contribution: Reuse existing plugin hooks, evidence capture, model-completion and policy primitives to compose a distinct opt-in verifier; add only minimal necessary bounded evidence/hold bridge if source test proves required
- Incremental benefit: HYPOTHETICAL contradiction detection and corrected or safely held subsequent work even after an Advisor active run expires; no measured reliability, demand or cost improvement
- Decision scope: GO for testable proposal-stage S3* constructor at exact pinned boundary only, NOT shipping, method regrade, external maintainer acceptance or a claim older scoped NO_GO was wrong
- External issue: DRAFT — NOT PUBLISHED
- Cost status: NOT_MEASURED

## Identity and pins

**Independent route:** Organization START_HERE → ECOSYSTEM → Upstream `4db2e1cd8666afd4981afb6c2270c37e96c36ead` (v0.18.0) → accepted Index `394ce776e6945115891b8f7cc459f5a7f7d7aa39` → original `cd2ae19272a3ee7be456385fa7efc56d6e2109a6`. The historic accepted Index vector above is **NOT** a current-HEAD reassessment. Accepted Profile 0.2.1, Methodology 0.3.1; reviewed 2026-09-16, 64 days old; recommend separately scoped Index re-review.

**Boundary:** First-party deployed Gateway agent runs and bundled/explicitly enabled plugins, including optional Advisor. Operation is not the repository's development CI, Foundation governance or an untrusted external plugin. Current original tree read through pinned git tree APIs; all major top-level src/extensions/docs/apps/packages enumerated without truncation and salient source code inspected. This is a **repository-wide architectural screen**, not proof every file or future branch was read.

## Rights and authority

[Original MIT license](https://github.com/openclaw/openclaw/blob/cd2ae19272a3ee7be456385fa7efc56d6e2109a6/LICENSE); [CONTRIBUTING](https://github.com/openclaw/openclaw/blob/cd2ae19272a3ee7be456385fa7efc56d6e2109a6/CONTRIBUTING.md) and [VISION](https://github.com/openclaw/openclaw/blob/cd2ae19272a3ee7be456385fa7efc56d6e2109a6/VISION.md) favor new feature discussions first and plugin-first implementation. CLA/DCO and contributor AI requirements beyond these documents are NOT_FULLY_VERIFIED; check before future original PR. Correctly parented `opensiro-contributions/openclaw` (`parent=openclaw/openclaw`), fork `opensiro/meta` and `.opensiro/state.json` owner `ACTIVE/ALLOW` re-read before fork metadata effects. No original/fork public Issues, PRs or code publications; no operator control override, no automatic trusted permission grant.

## Existing work / overlap

- SHIPPED [session tools](https://github.com/openclaw/openclaw/blob/cd2ae19272a3ee7be456385fa7efc56d6e2109a6/docs/concepts/session-tool.md) for admitted agent operations and approved hierarchy, [ring-zero system agent](https://github.com/openclaw/openclaw/blob/cd2ae19272a3ee7be456385fa7efc56d6e2109a6/src/agents/tools/system-agent-tool.ts) for explicitly approved current mutations; not independent audit by component name.
- SHIPPED [Advisor](https://github.com/openclaw/openclaw/blob/cd2ae19272a3ee7be456385fa7efc56d6e2109a6/extensions/advisor/index.ts) + [manifest](https://github.com/openclaw/openclaw/blob/cd2ae19272a3ee7be456385fa7efc56d6e2109a6/extensions/advisor/openclaw.plugin.json) **off by default**, reviewer same model and transcript, current-run `steerActiveRun`; no return after run ended; no claim of alternative artifact verification.
- SHIPPED [trajectory export](https://github.com/openclaw/openclaw/blob/cd2ae19272a3ee7be456385fa7efc56d6e2109a6/docs/tools/trajectory.md) with owner-only, approval-mediated redacted export, [security audit](https://github.com/openclaw/openclaw/blob/cd2ae19272a3ee7be456385fa7efc56d6e2109a6/src/security/audit.ts) for posture, and [after_tool_call](https://github.com/openclaw/openclaw/blob/cd2ae19272a3ee7be456385fa7efc56d6e2109a6/docs/plugins/hooks/tool-policy.md) observation where outcomes may be absent/unknown. These are evidence transports, NOT yet demonstrated autonomous complementary-audit closure.
- SHIPPED [SDK host hooks](https://github.com/openclaw/openclaw/blob/cd2ae19272a3ee7be456385fa7efc56d6e2109a6/docs/plugins/sdk-overview/host-hooks.md) supports event subscriptions, per-run contexts, next-turn injection, host-scoped policy actions; [plugin integration](https://github.com/openclaw/openclaw/blob/cd2ae19272a3ee7be456385fa7efc56d6e2109a6/docs/plugins/building-plugins.md) is preferred to new core feature.
- ORIGINAL ISSUE [#184787](https://github.com/openclaw/openclaw/issues/184787) OPEN, model selector for Advisor. ORIGINAL [PR #196242](https://github.com/openclaw/openclaw/pull/196242) OPEN, head `cfd89afbe771bfdbc69cf5c7be203a2cd85e327f`, unmerged different-model completion, short transcript, no independent evidence verifier nor native E2E proof. Its required precursor #196240 was not accepted as shipped on this run. [Original #201834](https://github.com/openclaw/openclaw/issues/201834) is a separate Auto Review helper deadline repair, not duplicated here.
- [Dreaming](https://github.com/openclaw/openclaw/blob/cd2ae19272a3ee7be456385fa7efc56d6e2109a6/docs/concepts/dreaming.md) and [automations](https://github.com/openclaw/openclaw/blob/cd2ae19272a3ee7be456385fa7efc56d6e2109a6/docs/automation/cron-jobs.md) do not by themselves close an external-prospective S4 loop. Vendor, tester, CI, sample or security object must meet same deployed-boundary authority test.

## Parallel contribution-on-top review

| Track A current owner and coverage | Track B strictly incremental on-top option | Targeted benefit and falsifier |
| --- | --- | --- |
| Bundled same-model Advisor reviews only a live run | REUSE unchanged for best native base, no competing model-selector PR | Already sufficient if operator only needs live drift detection; no S3* audit delta |
| #184787 / open PR #196242 propose separate model with limited transcript | On-top direct, host-recorded artifact witness and durable post-run finding, NOT model selection | Added quality only if raw evidence contradicts a plausible S1 report and later actions change; same-model-only PR does not close that |
| Host trajectory, after_tool_call and plugin events are shipped; outcomes may be unknown | Constrain sample to authorized real tool result/raw artifact; independently verify claim using distinct model and record INCONCLUSIVE on absent evidence | Fail closed when raw outcome missing; stale artifact or inaccessible files cannot be treated as success |
| SDK trusted tool policies and injected next-turn context support an enforcement/return bridge | Owner-authorized bounded hold/escalation on next S1 operation, together with S3/parent audit finding, then readback effect | If only chat advice is sent, if host rejects authority, or if no later behavior changes, C chain is incomplete |
| [Security audit](https://github.com/openclaw/openclaw/blob/cd2ae19272a3ee7be456385fa7efc56d6e2109a6/src/security/audit.ts) + Auto Review issue #201834 serve unrelated needs | DO NOT duplicate posture audit or helper timeout fix | Counterfactual: replacing plugin with existing native work yields same evidence + outcome => NO_GO to new design |

**Design independence:** An unmerged other-model reviewer is not a proof of independent S3*. This proposal isolates the particular *agent output claim vs host/operation ground truth* and later S3 control. Track B changes are prospective and conditional on native API/permissions tests; source alone does not prove usefulness.

## Function ownership

| Function | Historic | Original shipped/source-backed owner and closure | Selected action |
| --- | --- | --- | --- |
| S1 | A | Admitted agent runner owns primary user-directed tool decisions | NO_TARGET |
| S2 | C | Session message/ownership controls and coordination constructor; no incremental disturbance shown | DEFER |
| S3 | C(P) | Gateway/system-agent and operator exact-hash approval for current config/team action; controls are not policy-level S5 | DEFER, preserve parent |
| S3* | — | Advisor is same-session review, trajectory/audit are supporting observations without demonstrated independent alternative evidence and S3 return | **P0 S3*=C** |
| S4 | — | Scheduled turns/dreaming consolidate work and memory, not necessarily outside-and-then adaptation | DEFER |
| S5 | — | Operator controls ultimate policy; generic setup approval is not autonomously composed policy/identity | NO_TARGET |

**Actor/right/effect:** An optional plugin's separately configured model (or another demonstrably independent audit actor) decides a bounded, evidence-linked `CONFIRMED / CONTRADICTED / INCONCLUSIVE` audit; it cannot grant new tool permissions. An authorized current-control/parent S3 path receives the result; an existing trusted policy gate may hold *only configured risky follow-on actions* or request operator decision, and a later allowed operation supplies effect feedback. Without the audit actor, host event transport/policy defaults do not choose this evidence-based hold, satisfying the owner counterfactual *only if proved by future tests*. Deliberate human authority over S3 and S5 must remain.

## Capability priority

**P0:** S3*=— -> S3*=C, bounded complementary evidence audit plugin with independently selecting reviewer, lawful S3 hold/decision/feedback; **PROPOSED_C_SUFFICIENT by design, NOT_PROVEN by tests**.

**P1:** Confirm actual authorized raw artifact/host evidence, no unsafe transcript exfiltration, reviewer provider/model allowlist, plugin trusted-policy contract, durable next-run delivery, matching original test fixtures, parent refusal and after-effect readback. If any indispensable API unavailable, narrow plugin SDK port proposal before code; no core replacement by default.

**P2:** Only if separately valuable, compare deterministic native baseline, bundled Advisor and open #196242 reviewer with the composed audit on same task: correction accuracy, false holds, token cost, latency, engineering/review/maintenance.

## Implementation options

1. Pinned-source opt-in standalone or bundled plugin. Receive admitted bounded events/tool result via SDK after-tool and agent-event subscription, store minimal structured evidence, prefer explicit approved readback where raw artifact needed. `unknown` must never count as successful.
2. On qualifying claim, call policy-permitted different-model (or independently sourced) auditor, with no tool authority increase and untrusted claim data. Distinguish actual independent data source from another model merely echoing S1.
3. Persist scoped `claim, source-ref, verdict, reviewer, freshness, reason` finding. Through a manifest-gated native trusted tool policy and host-approved S3/parent channel, enforce only a narrow next-action hold/verification, not an independent final policy; use standard next-turn injected context when legitimate.
4. Inspect subsequent authorized run/tool result and reconcile finding with effect. If later link cannot be proved, reduce to advisory alert, NOT S3*=C.

Keep library/SDK compatibility pinned; no S4 agent, S5 role, global monitoring/default-on, permission bypass or new external Issue without separate authority. No native build/test performed in this research-only run.

## Specification and domain alternatives

**Original-native:** shipped Advisor for simple live drift review, and integrate #184787/#196242 only if own different-model requirement. If plugin SDK insufficient for direct evidence or controlled later effect, submit *separately authorized* narrowly scoped SDK request, not duplicate PR. **Profile/Skills:** only raise semantic issue if concrete Profile S3* independent-access boundary contradiction emerges; no Index regrade here. **Domain fork:** opt-in permitted sandbox experiment with no third-party publication or special status.

## Cost experiment

No token, latency, effectiveness, error-rate, developer time or maintainer adoption measurements. Matched baseline should compare exactly the same misreported tool outcome and permitted later operation with and without the composed audit. Cost status **NOT_MEASURED**; zero ROI claims.

## Delivery and publication

**PLAN_ONLY. Proposal-stage decision GO, research NEEDS_EVIDENCE; validation NOT_RUN.** This is a complete testable architectural proposal, not verified autonomous S3*=C. Published code, original issues/PR, public fork issue: **DRAFT — NOT PUBLISHED**. Case-local Human [issue.md](issue.md), AI [constructor-sufficiency.md](constructor-sufficiency.md), and [README.md](README.md) are internal fork-meta documents only; no contribution record solely from research.

## Historical comparison (performed only after independent verdict)

- [Upstream #58](https://github.com/opensiro/upstream/issues/58) records three **separate** OpenClaw old cases; their old verdicts were not used for the independent six-function screen or P0 selection.
- [s3star-advisor-review-20261119](../s3star-advisor-review-20261119/roadmap.md) previously **NO_GO** for duplicating other-model Advisor in the existing original Issue/PR; agrees with our reject-duplicate Track A, but our new **post-run direct-evidence and later-effect** object is distinct. Its prior `NOT_EVIDENCED` adjacent audit remains an earlier observation, not overwritten proof.
- [s3star-autoreview-handoff-20261119](../s3star-autoreview-handoff-20261119/roadmap.md) previously **NO_GO** for a separate Auto Review helper controller; native timer/diagnostic repair belongs original #201834. Our new proposal neither repairs that timer nor repackages its reviewer.
- [s4-compatibility-transition-20261118](../s4-compatibility-transition-20261118/roadmap.md) previously **NO_GO** for a speculative S4 autonomous transition controller; our S4 is explicitly DEFER and its record remains untouched.
- **Change in research choice, not retrospective contradiction:** previous NO_GO scoped objects → current distinct direct-evidence S3* proposal-stage GO + NEEDS_EVIDENCE. No new empirical proof or runtime test invalidates those historical conclusions.
