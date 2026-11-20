# OpenClaw — S3* Advisor native complementary audit construction

**OpenSiro Wave 4 research; PLAN_ONLY / HYPOTHETICAL; DRAFT — NOT PUBLISHED.**

**Target transition:** S3*=— -> S3*=C
**Proposal-stage decision:** GO
**Research disposition:** NEEDS_EVIDENCE
**Validation state:** NOT_RUN

This is a proposal-stage architectural verdict, not a deployed feature, demanded product change, Index reassessment, or third-party publication. [roadmap.md](roadmap.md) is canonical; [constructor-sufficiency.md](constructor-sufficiency.md) has the technical construction and falsifiers.

## 1. Accepted historical six-function assessment and methodology

Accepted [Index assessment](https://github.com/opensiro/vsm-harness-index/blob/a3fcf7c156ef4d1132680890bc11544681fd30c0/assessments/op/openclaw.md) remains included, blob e1d560bc5b28d90323b15f5f1af6a5293c614b45, reviewed 2026-09-16, original review ref 387da5edaa9d6c6cfcfc15e167fe2e46d8647d86, Profile 0.2.1 and Methodology 0.3.1. Current observed [original main@599bc422](https://github.com/openclaw/openclaw/commit/599bc4222a48594445c7d531c063be828be3482a) (2026-11-20) is a separate source snapshot.

| Function (meaning at original reviewed boundary) | Historical state | Current-source treatment and roadmap priority |
| --- | --- | --- |
| **S1 · Operations** | A | Autonomous user tasks, first-party agent and subagent runtime; no new S1 requested |
| **S2 · Coordination** | C | First-party Gateway session/messaging/lifecycle; no S2 build |
| **S3 · Current management** | C(P) | System-agent status/config, host approvals and controlled mutations; not another S3 owner |
| **S3* · Complementary audit** | — | Advisor has nonbinding review and correction; selected narrow optional independent binding construction, P0 |
| **S4 · Future adaptation** | — | Knowledge, memory and update facilities are not a separately proven prospective owner; no S4 build |
| **S5 · Identity and policy** | — | Actual operator and host policy remain parent authority, not reviewer S5; no S5 build |

A = autonomous decisive function owner, C = a first-party path enabling developer-composed autonomous ownership, P = a supported parent-owned mode, A(P)/C(P) = mixed evidenced modes, — = bounded absence at the reviewed boundary, ? = unresolved evidence. These are not quality scores, defects or requirements to fill six functions. First identify function and legal decision owner; do not infer C from a plugin, reviewer text or independent model name.

Source map: [Gateway session tools](https://github.com/openclaw/openclaw/blob/599bc4222a48594445c7d531c063be828be3482a/docs/concepts/session-tool.md), [system-agent operations](https://github.com/openclaw/openclaw/blob/599bc4222a48594445c7d531c063be828be3482a/src/agents/tools/system-agent-tool.ts), [Advisor implementation](https://github.com/openclaw/openclaw/blob/599bc4222a48594445c7d531c063be828be3482a/extensions/advisor/index.ts), [Gateway audit](https://github.com/openclaw/openclaw/blob/599bc4222a48594445c7d531c063be828be3482a/docs/gateway/audit.md) and [operator approvals](https://github.com/openclaw/openclaw/blob/599bc4222a48594445c7d531c063be828be3482a/docs/cli/approvals.md).

## 2. User outcome and bounded hypothesis

A developer who explicitly enables the bundled Advisor could compose a separate, trusted reviewer responsible for deciding whether to allow a **later** tool/agent step or hold it for operator review after an observed problematic settled result. Today Advisor can send an advisory CORRECTION into an active run; it does not own a binding host decision or prove the agent acted on it. Proposal P0 adds an independent reviewer choice with a Gateway-enforced, run-scoped HOLD, followed by actual authorized resume/deny feedback. A held step is not retried or approved by the reviewer; the host/parent retains that authority. A second lawful choice CONTINUE distinguishes independent decision ownership from a permanently hardcoded block.

**Potential benefit is hypothetical.** No new operator request, demonstrated comparative utility, or accepted maintainer need is claimed. Architecturally a sufficiently specified C route is possible; product selection is entirely OpenClaw's.

## 3. Track A native overlap versus Track B missing C

| Existing first-party source and status (A) | Missing native-specific edit (B) | Source-native falsifier |
| --- | --- | --- |
| [Advisor index.ts](https://github.com/openclaw/openclaw/blob/599bc4222a48594445c7d531c063be828be3482a/extensions/advisor/index.ts) counts tool results, waits for pending calls, forks same model and steers active run with advice | Explicit trusted reviewer verdict CONTINUE / HOLD_FOR_OPERATOR / CORRECT_AND_REAUDIT over settled tool-result window; no hidden new permissions | An existing binding, independently selectable audit closure already exists in shipped first-party path |
| [Advisor manifest](https://github.com/openclaw/openclaw/blob/599bc4222a48594445c7d531c063be828be3482a/extensions/advisor/openclaw.plugin.json) supports review interval and instructions, not model override | Reuse original issue [#184787](https://github.com/openclaw/openclaw/issues/184787) and open [PR #196242](https://github.com/openclaw/openclaw/pull/196242) for optional reviewer model, **not** a competing OpenSiro model-selection implementation | Merely selecting a model proves neither S3* independence nor a binding review result |
| [Gateway approvals](https://github.com/openclaw/openclaw/blob/599bc4222a48594445c7d531c063be828be3482a/docs/cli/approvals.md) and run identity own lawful action admission | Narrow, version-checked first-party Gateway admission effect before future tool/turn; return applied/denied/expired result, fail closed on stale state or revoked policy | Plugin cannot lawfully enforce without overriding parent S5 or silently blocking unrelated runs |
| [Audit ledger](https://github.com/openclaw/openclaw/blob/599bc4222a48594445c7d531c063be828be3482a/docs/gateway/audit.md) records metadata only; exec Auto Review is task-narrow | Use settled tool-result events inside existing trusted plugin boundary, not broad external audit data access; preserve privacy and evidence provenance | Evidence inaccessible or same resulting decision as native Advisor across matched tasks |

Original [#193891](https://github.com/openclaw/openclaw/issues/193891) reports an independent Advisor fork failure, [#196230](https://github.com/openclaw/openclaw/issues/196230) nested event inflation, [#198097](https://github.com/openclaw/openclaw/issues/198097) correction persistence. Original PR #196242 (OPEN, unmerged at head cfd89afbe771bfdbc69cf5c7be203a2cd85e327f) depends on #196240 (OPEN at head 6eae1f6b169d964735d9c01432e4ce553d83b743). Existing repair and reviewer-model work remain original-owned; they do not independently implement bounded, separately owned S3* hold and return.

## 4. Minimal C sufficiency and priorities

**P0:** a single opt-in developer-composable S3* owner in Advisor, deciding complementary audit outcomes using completed tool evidence, with host-enforced versioned next-step effect and visible later feedback. Its host permission is pre-granted by the operator; no reviewer-driven escalation.

**P1:** demonstrate lawful first-party plugin SDK / Gateway hook for next-step admission; genuine reviewer independence and evidence provenance; operator-policy, stale/revoked/missing owner negatives; native runtime tests and comparison to unchanged Advisor. Existing bugs are independently routed. **P2:** NONE.

**Why C is constructible:** Reviewer is the function-specific decision owner; Advisor's existing scheduling/evidence and Gateway control provide source-native adjacent surfaces, but the essential missing first-party admission-and-return link must be built. The resulting lawful independent CONTINUE/HOLD choice and downstream observed return would close a bounded S3* loop, rather than merely produce a suggestion or score. It remains an unexecuted architecture hypothesis.

## 5. Native acceptance and stop conditions

Positive proposed test: a developer-installed reviewer gets a completed tool outcome, chooses HOLD on a specific run and step version, Gateway safely prevents **the next** step, the operator reviews under existing policy, and the reviewer sees a definite approved/denied/expired receipt. Alternative proposed test: CONTINUE permits normal work with no extra rights. Negative proposed tests: missing configured reviewer preserves baseline; a stale/ended/changed run cannot be held; revoked or forbidden policy cannot be overridden; a pending tool outcome is not reviewed as completed. Run matched native Advisor unchanged to falsify incremental effect. All proposed, **NOT_RUN**; cost **NOT_MEASURED**.

No implementation should proceed if first-party binding requires illegitimate S5 ownership, the needed evidence violates agent privacy, or an equivalent C owner/decision/return is already provided by shipped code. A native fork/model selector by itself is insufficient.

## 6. Historical comparison (performed after independent verdict)

[Independent first pass](https://github.com/opensiro/upstream/issues/58#issuecomment-7045525751) was recorded before reading any prior OpenSiro same-case argument. Earlier [2026-11-19 case at fork SHA 67e1d5d](https://github.com/opensiro-contributions/openclaw/blob/67e1d5dbf58accf8b0f6cf445caf198294144c53/.opensiro/issues/s3star-advisor-review-20261119/roadmap.md) concluded NO_GO to **duplicating a reviewer-model selector** already proposed in #184787/#196242, and treated independently binding audit as NOT_EVIDENCED. That scoped no-duplicate decision remains valid. The new v0.18.1 neutral verdict is GO for a **different complete functional closure**, not a claim of a new model picker or measured demand. Prior evidence remains attributable at its frozen fork commit, and separate OpenClaw S3* AutoReview and Direct Evidence Audit cases are not changed.

## 7. Costs and alternatives

Lowest-effort native alternative: keep the shipped Advisor unchanged, use operator intervention, and let the original maintainers handle #184787/#196242 and #193891. Compare with a genuinely optional binding audit on identical lawful tasks; observe false holds, prevented next steps, time/latency, extra review calls and maintenance. No numeric gain or cost claim has been measured. Operator adoption preference: NOT_STATED.

## 8. Handoff and publication

**Proposal-stage decision:** GO
**Research disposition:** NEEDS_EVIDENCE

GO refers exclusively to source-grounded *architectural constructibility*, not native success or maintainer preference. Research is PLAN_ONLY, scenario HYPOTHETICAL, validation NOT_RUN, product code NOT_IMPLEMENTED. [roadmap.md](roadmap.md) is the authoritative current result and [constructor-sufficiency.md](constructor-sufficiency.md) the proposed technical witness.

Verified public original license MIT and [CONTRIBUTING](https://github.com/openclaw/openclaw/blob/599bc4222a48594445c7d531c063be828be3482a/CONTRIBUTING.md) directs feature discussions to original Issue/Discord first. Fork metadata ACTIVE/ALLOW permits internal case files only. No public fork Issue, original Issue/PR/comment, source code, Index regrade or release has been authorized. AI-assisted preparation disclosed.
