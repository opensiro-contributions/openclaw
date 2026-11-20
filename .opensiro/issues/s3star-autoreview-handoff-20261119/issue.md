# OpenClaw — opt-in AutoReview-to-publication S3* constructor (OpenSiro roadmap)

**PLAN_ONLY · proposal-stage GO · research NEEDS_EVIDENCE · DRAFT — NOT PUBLISHED.**

**One-sentence proposal:** Compose an independent quality reviewer over an exact sandboxed Git candidate using shipped AutoReview, then bind its hold/allow judgment to one permitted first-party tool action before publication; a rejected or outdated review denies the action and returns a repair reason to the agent.

**Canonical decision receipt:** [roadmap.md](roadmap.md) — source of truth for assessment and decision.
**Technical companion:** [constructor-sufficiency.md](constructor-sufficiency.md) — exact first-party review/hook path, Track A/B and future tests.
**Working fork:** opensiro-contributions/openclaw · **Case:** .opensiro/issues/s3star-autoreview-handoff-20261119/ on opensiro/meta.

## 1. Why Opensiro and central accepted VSM assessment

Opensiro tests whether Stafford Beer's VSM-informed descriptions help compose agent systems. It **does not** certify OpenClaw, prescribe six features or prove developer cost reduction.

### Central starting point — accepted Index, not the target

> **ACCEPTED HISTORICAL INDEX — not current HEAD grades or proposed after-states.**
>
> **S1=A · S2=C · S3=C(P) · S3*=— · S4=— · S5=—.**
>
> [Accepted Index pinned at a3fcf7c156ef4d1132680890bc11544681fd30c0](https://github.com/opensiro/vsm-harness-index/blob/a3fcf7c156ef4d1132680890bc11544681fd30c0/assessments/op/openclaw.md); document blob e1d560bc5b28d90323b15f5f1af6a5293c614b45; original assessed at 387da5edaa9d6c6cfcfc15e167fe2e46d8647d86 on 2026-09-16; Profile 0.2.1 / Skills assessment procedure 0.3.1.

**Repository-wide audit:** Current original [main HEAD 1a7f34f](https://github.com/openclaw/openclaw/commit/1a7f34ffd7873e2b3ddb90073fc1220a852cf741) (2026-11-20): agent/session tools, Gateway/host config and policy, bundled optional reviewer and Advisor, system-agent parent approval, automation and dreaming, plugin hooks, source tests/docs, current original Issues/PRs and contribution policy. The system-in-focus is supported first-party runtime/Gateway plus opt-in sandbox execution, **not** the foundation, external GitHub review process, canonical helper's separate repository, model provider or developer CI. Accepted historical assessment is 65 days old; an Index-owned re-review is recommended but not silently performed.

**One combined historical-and-current six-function table:**

| Function / plain-language role | Historical Index state | Current source-backed owner/closure | Candidate / justified no-target / uncertainty and rank |
| --- | --- | --- | --- |
| **S1 · Operations** — task execution | A | [First-party agent/session tools](https://github.com/openclaw/openclaw/blob/1a7f34ffd7873e2b3ddb90073fc1220a852cf741/docs/concepts/session-tool.md) perform user work | NO_TARGET: autonomous S1 already present |
| **S2 · Coordination** — agent interference management | C | Session messages, visibility, spawn/cancel and owner/child controls at [session tools](https://github.com/openclaw/openclaw/blob/1a7f34ffd7873e2b3ddb90073fc1220a852cf741/docs/concepts/session-tool.md) | NO_TARGET: composable coordination already documented |
| **S3 · Current management** — present priorities/resources | C(P) | [system-agent exact host approvals](https://github.com/openclaw/openclaw/blob/1a7f34ffd7873e2b3ddb90073fc1220a852cf741/src/agents/tools/system-agent-tool.ts) and existing session/control tools; parent decision preserved | NO_TARGET: no mandate to replace parent mode |
| **S3* · Independent review** — complementary correction | — | Bundled [optional sandbox AutoReview](https://github.com/openclaw/openclaw/blob/1a7f34ffd7873e2b3ddb90073fc1220a852cf741/extensions/autoreview/src/tool.ts) supplies independent candidate evidence to agent; [reviewer of exec risk](https://github.com/openclaw/openclaw/blob/1a7f34ffd7873e2b3ddb90073fc1220a852cf741/src/agents/exec-auto-reviewer.ts) is a distinct safety policy, not candidate-quality ownership | **P0 HYPOTHETICAL**: reviewer choice + protected exact post-review Git action + feedback, if native action coverage proven |
| **S4 · Future adaptation** — outside/then | — | [Automation/heartbeat migration](https://github.com/openclaw/openclaw/blob/1a7f34ffd7873e2b3ddb90073fc1220a852cf741/docs/gateway/heartbeat.md) and [dreaming](https://github.com/openclaw/openclaw/blob/1a7f34ffd7873e2b3ddb90073fc1220a852cf741/docs/concepts/dreaming.md) do not themselves demonstrate a prospective external decision owner | DEFER: no sourced scope or intentional omission established |
| **S5 · Identity/policy** — ultimate authority | — | Host configuration, per-request authorization and original maintainers own limits; approvals not equivalent to local S5 closure | NO_TARGET: do not invent reviewer's ultimate policy power |

**Interpretation:** These are ownership categories, not quality ranks. A = autonomous ownership; C = developer-composable closure; P = valid parent-owned mode; A(P)/C(P) = separately evidenced additional parent mode; — = bounded lack of material constructor; ? = unknown, **not quality scores**. Historical grades are not updated.

**Priority rationale:** S3* has the narrowest potentially composable missing return in an actual first-party reviewer flow. S1/S2/S3 are already present in the accepted modes; S4/S5 would require unsupported new environment/authority decisions. The scope is **one opt-in sandbox publication action**, not a universal auditing layer. The hook and exact hash binding need testing before the new path may be trusted.

**Deliberate exclusions / methodology challenge:** The runtime does not claim a standard local S5; operator approval remains legitimate. No statement that missing S4 is deliberately omitted was established; classify intent UNKNOWN. An advisory reviewer, a severity rubric or a risk model cannot by itself close S3*. Original human PR checks stay outside runtime function ownership.

**Contributor / maintainer interests:** [CONTRIBUTING](https://github.com/openclaw/openclaw/blob/1a7f34ffd7873e2b3ddb90073fc1220a852cf741/CONTRIBUTING.md) specifically prefers pre-discussion for architecture/features and third-party plugins where possible. Interest in this exact quality-to-egress constructor is NOT_STATED; no external permission inferred.

## 2. Selected construction hypothesis and operator outcome

**Target transition:** S3*=— -> S3*=C

**Function-specific disturbance:** HYPOTHETICAL coding agent prepares a Git candidate for an authorized push after one AutoReview pass, but code changes after that pass or the reviewer returns a substantive hold. Existing optional reviewer output does not by itself block the later push.

**Proposed C capability (P0):** An OpenClaw developer can configure a genuinely independent candidate-quality decision owner whose validated review for *this* sandbox snapshot selects **allow for this exact prepared action** or **hold for rework**. The runtime checks source identity/freshness and actual tool authority, denies when stale/negative/absent, and returns denial/success to the work agent. The model reviewer cannot override human approval or tool-policy rules.

**Best native operator alternative:** Existing [AutoReview](https://github.com/openclaw/openclaw/blob/1a7f34ffd7873e2b3ddb90073fc1220a852cf741/docs/tools/autoreview.md) produces an independent report; normal human [PR reviewer workflow](https://github.com/openclaw/openclaw/blob/1a7f34ffd7873e2b3ddb90073fc1220a852cf741/docs/reference/pull-request-review-flow.md) and exec approval/policy remain separate. Keep manual review for deployments not enabling this candidate experiment.

**Expected user benefit:** HYPOTHETICAL prevention of one otherwise permitted premature publish of unreviewed/stale work with reasoned repair feedback; real adoption, security gain and time saving NOT_MEASURED.

**Architectural sufficiency argument:** Reuse the existing sandbox candidate capture and validated AutoReview outcome, bind its immutable candidate identity and attributable decision at host-owned [pre-tool gate](https://github.com/openclaw/openclaw/blob/1a7f34ffd7873e2b3ddb90073fc1220a852cf741/docs/plugins/hooks/tool-policy.md), and require an exact matching permitted action before effects. A separate configurable reviewer owns quality judgment, host ownership enforces permission and result; later agent work receives the actual denial/effect. The crucial missing interface is a trustworthy *review output ↔ candidate revision ↔ protected action* join, not a new supervisor. Unsupported egress pathways must be excluded or blocked at a higher host permission boundary.

## 3. Existing native work versus missing construction

**Track A — native coverage:** [AutoReview tool](https://github.com/openclaw/openclaw/blob/1a7f34ffd7873e2b3ddb90073fc1220a852cf741/extensions/autoreview/src/tool.ts) SHIPPED, [hook terminal block contract](https://github.com/openclaw/openclaw/blob/1a7f34ffd7873e2b3ddb90073fc1220a852cf741/docs/plugins/hooks/tool-policy.md) SHIPPED, [exec safety reviewer](https://github.com/openclaw/openclaw/blob/1a7f34ffd7873e2b3ddb90073fc1220a852cf741/src/agents/exec-auto-reviewer.ts) SHIPPED but for a different decision. [Original #201834](https://github.com/openclaw/openclaw/issues/201834) OPEN is a *different* review handoff timeout bug. Merged [#173455](https://github.com/openclaw/openclaw/pull/173455), [#175529](https://github.com/openclaw/openclaw/pull/175529), [#200743](https://github.com/openclaw/openclaw/pull/200743) supply reviewer and lifetime fixes, not an independently chosen quality-to-egress gate. Open [PR #156804](https://github.com/openclaw/openclaw/pull/156804) modifies original maintainer review guidance, not native runtime authority.

**Track B — independent on-top C construction:** Reuse AutoReview capture/report + original host policy. Add one opt-in first-party source-matched evidence/action binding for the admitted host exec tool path; require strict snapshot and authority proof at execution time, not a passive listener or universal generic review service.

| C-sufficiency requirement | Already present / proposed in original (A) | What still must be constructed (B) |
| --- | --- | --- |
| Independent evidence and discretionary quality choice | AutoReview [validated report](https://github.com/openclaw/openclaw/blob/1a7f34ffd7873e2b3ddb90073fc1220a852cf741/docs/tools/autoreview.md), permitted configured reviewer; risk-only [exec classifier](https://github.com/openclaw/openclaw/blob/1a7f34ffd7873e2b3ddb90073fc1220a852cf741/src/agents/exec-auto-reviewer.ts) is not substitute | Native report-to-decision identity/hold outcome from a **separately configured** reviewer, not host static hardcoded allow |
| Protected lawful later action and return | Terminal [before_tool_call block](https://github.com/openclaw/openclaw/blob/1a7f34ffd7873e2b3ddb90073fc1220a852cf741/docs/plugins/hooks/tool-policy.md), host approval and tool result | Source/revision freshness join to exactly one permitted Git publication action; deny with recovery reason; record true allowed effect/status, prevent bypass in declared mode |

**Distinctness and falsifier:** Earlier fork case evaluated separate general audit added to **AutoReview timeout repair** and found NO_GO. This proposed construction is a *different controlled post-review action* at an explicit first-party boundary; the earlier NO_GO remains valid for repair's unrelated audit. The new proposal fails if native execution cannot guarantee correct exact-action interception, if the reviewer cannot independently choose quality outcomes, or if same correction happens under manual review without a meaningful new constructor capability. There is no assertion that product developers want this.

## 4. Priorities and minimum sufficient result

- **P0:** Opt-in developer-composable S3* quality reviewer decision bound to one supported sandbox Git publication operation with protected deny/allow effect and real later feedback.
- **P1:** Demonstrate exact native hook reachability, reviewed candidate digest and freshness, matched host execution requester and operation, deny on bypass/staleness/absent model/parent refusal and no-opt-in compatibility.
- **P2:** NONE; do not force separate S4 or S5 construction.

**Proposed C-sufficiency verdict:** PROPOSED_C_SUFFICIENT **only** for the bounded path if all P1 proof obligations are met; not shipped, not Index-grade C.

## 5. Proposed acceptance and stop gates

**Future positive test:** On a pinned sandbox candidate, a separately composed reviewer chooses allow after a complete clean report; one exact authorized Git action executes; a real native completion/return is visible to subsequent agent work.

**Future negative test:** Independent reviewer returns hold or evidence is absent/failed/stale/changed, requester/host approval is denied, or tool/Code Mode bypass is attempted: the protected operation never executes; work agent receives accurate reason; older normal operation without opt-in is unchanged.

**Proposed falsifier:** Any unmediated way to issue the same in-scope publication action, stale digest accepted, or only static allowlist (no independent judgment owner) means C chain is incomplete; do not ship/call it S3* C.

**Validation state:** NOT_RUN. No native test pass, production rollout, cost data or accepted Index regrade claimed.

## 6. Independent paths

**Original-native contribution:** Prefer current AutoReview and existing hook/exec policy first. Original [CONTRIBUTING](https://github.com/openclaw/openclaw/blob/1a7f34ffd7873e2b3ddb90073fc1220a852cf741/CONTRIBUTING.md) requires prior Issue/discussion for architecture; do not open competing PR or contact maintainer now. Existing #201834 should be handled as native timing repair, not this new audit constructor.

**Profile / Skills:** If tests prove classification ambiguity, submit a separate evidence-backed method question through its owner; no presumed methodology defect.

**Domain fork:** Optional isolated lawful experiment with owner consent; NONE proposed by default.

## 7. Cost hypothesis

Compare one identical candidate/manual AutoReview + human PR gate with opt-in independent quality-to-action constructor. Include engineering, integration, reviewer inference, failure recovery, validation, first-party maintenance, human review and security/TOCTOU risk. **Cost status: NOT_MEASURED**.

## 8. Decision / handoff

**Proposal-stage decision:** GO

**Research disposition:** NEEDS_EVIDENCE

**Decision reason / next permitted step:** Current first-party source supports a plausible **new bounded C-construction chain**, so GO denotes architectural hypothesis only. Before implementation obtain exact action coverage and source-hash proof, do matched native tests and assess maintainer priorities; a failure of enforcement or legitimation closes **this proposed scope** NO_GO. The prior 2026-11-19 same case [NO_GO receipt](https://github.com/opensiro-contributions/openclaw/blob/51ba426d95e2f65e0274d48e6f333439b7c19df7/.opensiro/issues/s3star-autoreview-handoff-20261119/roadmap.md) addressed a different extra auditor for the reviewer timeout bug. The independent new source-only verdict was sealed [in Upstream #58](https://github.com/opensiro/upstream/issues/58#issuecomment-7047187780) *before* comparison.

**Agent/developer handoff:** [constructor-sufficiency.md](constructor-sufficiency.md) and [roadmap.md](roadmap.md). Selected target and priority must remain consistent across files.

**Rights and publication:** Original [MIT](https://github.com/openclaw/openclaw/blob/1a7f34ffd7873e2b3ddb90073fc1220a852cf741/LICENSE) + [CONTRIBUTING](https://github.com/openclaw/openclaw/blob/1a7f34ffd7873e2b3ddb90073fc1220a852cf741/CONTRIBUTING.md); matching fork original parent, owner_control ACTIVE/ALLOW before write, but separate **public fork GitHub Issue**, original external contact/PR, code implementation, grade change and host authority are **NOT AUTHORIZED / NOT PUBLISHED** by this plan. A public Issue requires exact current-conversation approval of destination, action and text. Human Issue remains a stored **draft**.

**AI disclosure:** Prepared with AI assistance; no native tests, measured utility or independent human approval claimed.
