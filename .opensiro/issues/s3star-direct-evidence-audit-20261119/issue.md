# OpenClaw — direct-evidence S3* review and feedback (OpenSiro draft)

**PLAN_ONLY · proposal-stage GO · research NEEDS_EVIDENCE · DRAFT — NOT PUBLISHED**

**One-sentence proposal:** Test an opt-in OpenClaw plugin that independently checks an agent's result against authorized host evidence and sends a bounded corrective finding into existing current control; do not reimplement Advisor's model selector.

**Canonical decision receipt:** [roadmap.md](roadmap.md).
**Technical companion:** [constructor-sufficiency.md](constructor-sufficiency.md).
**Working fork:** `opensiro-contributions/openclaw` · case `.opensiro/issues/s3star-direct-evidence-audit-20261119/` on `opensiro/meta`.

## Why this is an OpenSiro research proposal

The accepted [Index assessment](https://github.com/opensiro/vsm-harness-index/blob/394ce776e6945115891b8f7cc459f5a7f7d7aa39/assessments/op/openclaw.md) is the *historical* 2026-09-16 classification under Profile 0.2.1 and Methodology 0.3.1 — not a defect list or a grade for the current HEAD.

> **Historical autonomy:** `S1=A · S2=C · S3=C(P) · S3*=— · S4=— · S5=—`

**Original pinned:** [OpenClaw at cd2ae19272a3ee7be456385fa7efc56d6e2109a6] (https://github.com/openclaw/openclaw/commit/cd2ae19272a3ee7be456385fa7efc56d6e2109a6). Product boundary: user-facing Gateway/runtime and supported plugins, not CI, Foundation governance or unrelated third-party plugins. Source map includes agent and session orchestration, system agent approvals, security and tool policy, trajectory, Advisor, automations, SDK plugins, distributed apps and testing inventory.

| Function / plain-language role | Historical Index state | Current source-backed owner/closure | Disposition |
| --- | --- | --- | --- |
| **S1 · Operations** | A | [Admitted agent runs](https://github.com/openclaw/openclaw/blob/cd2ae19272a3ee7be456385fa7efc56d6e2109a6/docs/concepts/session-tool.md) choose and perform authorized work | NO_TARGET: already operates |
| **S2 · Coordination** | C | Session messaging and access/ownership boundaries support coordination construction | DEFER: no distinct inter-S1 counterexample |
| **S3 · Current management** | C(P) | [System agent](https://github.com/openclaw/openclaw/blob/cd2ae19272a3ee7be456385fa7efc56d6e2109a6/src/agents/tools/system-agent-tool.ts) and host-approved operations change present config/resources | DEFER: keep parent authority |
| **S3* · Independent review** | — | [Advisor](https://github.com/openclaw/openclaw/blob/cd2ae19272a3ee7be456385fa7efc56d6e2109a6/extensions/advisor/index.ts) same-model active correction; [host trajectory](https://github.com/openclaw/openclaw/blob/cd2ae19272a3ee7be456385fa7efc56d6e2109a6/docs/tools/trajectory.md) transports evidence without distinct audit closure | **P0: complement** |
| **S4 · Future adaptation** | — | Scheduled jobs/dreaming do not establish external prospective options and S3 return | DEFER: no grounded new actor |
| **S5 · Identity/policy** | — | Human operator owns ultimate policy, not equivalent to routine approval | NO_TARGET: human ownership legitimate |

**Priority:** S3* permits a bounded hypothesis with source-reused APIs and a concrete falsifier; it outranks speculative autonomous S4/S5, duplicate S1/S2/S3. Do not mandate a new VSM function in the original. Maintainer interest: [VISION](https://github.com/openclaw/openclaw/blob/cd2ae19272a3ee7be456385fa7efc56d6e2109a6/VISION.md) prioritizes reliability, evidence and plugin-first approach; precise interest in *this* audit is **NOT_STATED**. OpenSiro contributor preferences for this specific plugin are **NOT_STATED**.

## Selected P0 and intended user result

**Target transition:** S3*=— -> S3*=C

**Proposal-stage decision:** GO

**Research disposition:** NEEDS_EVIDENCE

**Problem (HYPOTHETICAL, not a reported real bug):** an agent claims tests passed, but a protected tool record shows a failure or unknown outcome. The requested effect is not merely telling the same agent to reconsider; it is a separate audit decision with a lawful hold/verification path affecting later permitted operations.

**Existing alternative:** [Bundled Advisor](https://github.com/openclaw/openclaw/blob/cd2ae19272a3ee7be456385fa7efc56d6e2109a6/extensions/advisor/index.ts) can correct an *active* session; [issue #184787](https://github.com/openclaw/openclaw/issues/184787) and open [PR #196242](https://github.com/openclaw/openclaw/pull/196242) concern a separate model, not checked artifact-based post-run closure.

**Minimum complete design:** sample only authorized host-recorded result/artifact; an independently composed auditor selects CONFIRMED / CONTRADICTED / INCONCLUSIVE; a privileged but **existing and bounded** S3/parent policy surface enforces a narrow follow-on check/hold (not self-authorized new tool rights); observe and attribute actual next-run result. Detailed source/authority gates are in [constructor-sufficiency.md](constructor-sufficiency.md).

| S3* sufficiency | Track A existing | Track B missing |
| --- | --- | --- |
| Alternative evidence vs S1 report | [Trajectory](https://github.com/openclaw/openclaw/blob/cd2ae19272a3ee7be456385fa7efc56d6e2109a6/docs/tools/trajectory.md), [after-tool observation](https://github.com/openclaw/openclaw/blob/cd2ae19272a3ee7be456385fa7efc56d6e2109a6/docs/plugins/hooks/tool-policy.md) shipped; events can be incomplete | Safe bounded readback, independent comparison; unknown≠success |
| Autonomous audit decision | Advisor same-run model, #196242 proposes other model on transcript | Reviewer with actual independent witness, bounded verdict/provenance |
| S3 control and later closure | [Plugin host hooks](https://github.com/openclaw/openclaw/blob/cd2ae19272a3ee7be456385fa7efc56d6e2109a6/docs/plugins/sdk-overview/host-hooks.md) offer policy/injection, while operator owns approval | Explicit authorized hold/check and observed subsequent execution; reject report-only |

**P0:** bounded direct-evidence S3* constructor prototype. **P1:** verify host evidence, permission/manifest contracts, reviewer model, durable custody and next-operation effect under real SDK. **P2:** optional matched quality/latency/cost study with native Advisor and #196242.

**C sufficiency:** design-level PROPOSED_C_SUFFICIENT; testing **NOT_RUN**. Positive: false claim contradicted by host evidence and a later authorized action changes or is held. Negative: missing/revoked evidence, parent veto, stale data or unprotected later operation => deny/INCONCLUSIVE, never silent success. Falsifier: same output achieved by existing native path without novel audit actor, or incomplete access/authority/feedback.

## Alternatives, rights and handoff

Prefer native Advisor for the live review task; original bug fix #201834 concerns a different Auto Review timer and is not this proposal. Only if the controlled prototype establishes distinct value should maintainers be asked about a minimal source-native plugin/SDK route. Separate Profile/Skills work needs a genuine semantic counterexample; no Index reclassification is requested. All benefit and cost **NOT_MEASURED**.

Original MIT; [CONTRIBUTING](https://github.com/openclaw/openclaw/blob/cd2ae19272a3ee7be456385fa7efc56d6e2109a6/CONTRIBUTING.md) requests feature/architecture discussion before implementation and favors plugins; legal CLA/DCO/formality details remain to verify for any future PR. Fork `ACTIVE/ALLOW` for internal metadata only. **No original/fork public Issue, PR, comment, implementation, external publication or authority grant.** AI-assisted PLAN_ONLY draft, not independently human-tested or shipped.

**Canonical links:** [roadmap.md](roadmap.md) · [constructor-sufficiency.md](constructor-sufficiency.md).
