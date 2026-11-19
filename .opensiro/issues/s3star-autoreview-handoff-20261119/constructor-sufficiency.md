# OpenClaw — S3* Auto Review handoff: independent AI/developer decision contract

**PLAN_ONLY / DECISION_READY · terminal NO_GO for speculative S3*=C**. This is the separate technical layer of [the Human Issue](https://github.com/opensiro-contributions/openclaw/blob/opensiro/meta/.opensiro/issues/s3star-autoreview-handoff-20261119/issue.md), not a second public Issue. Same historical starting profile and P0/P1/P2.

## Function-specific scope, accepted evidence and rights

**Accepted historical assessment (not a current-HEAD regrade): S1=A · S2=C · S3=C(P) · S3*=— · S4=— · S5=—.** [Pinned Index](https://github.com/opensiro/vsm-harness-index/blob/394ce776e6945115891b8f7cc459f5a7f7d7aa39/assessments/op/openclaw.md); reviewed 2026-09-16 at original `387da5edaa9d6c6cfcfc15e167fe2e46d8647d86`, assessment blob `e1d560bc5b28d90323b15f5f1af6a5293c614b45`, Profile 0.2.1, assessment procedure 0.3.1. Current source [`41bdde2111dd7031c93b47c57d7dad2e56bb0f5f`](https://github.com/openclaw/openclaw/commit/41bdde2111dd7031c93b47c57d7dad2e56bb0f5f) observed 2026-11-19. Review age 64 days warrants a separate source-pinned Index re-review recommendation, never silent reinterpretation of the accepted vector.

| Function | Decisive organizational scope |
| --- | --- |
| S1 | Existing autonomous agent work |
| S2 | Composable agent/session coordination |
| S3 | Current whole-deployment control and parent-approved changes, preserve existing C(P) |
| **S3*** | Requires sufficiently independent complementary audit evidence, a distinct accountable judgment/choice, authorized correction and later operational feedback |
| S4 | External future adaptation is not the handoff bug |
| S5 | Ultimate legitimate policy cannot be granted by a reviewer or prompt |

## 1. Boundary and actor counterfactual

Current original [`41bdde2111dd7031c93b47c57d7dad2e56bb0f5f`](https://github.com/openclaw/openclaw/commit/41bdde2111dd7031c93b47c57d7dad2e56bb0f5f), observed 2026-11-19. Include Gateway, installed bundled Auto Review and process/Code Mode runtime; canonical helper `openclaw/agent-skills` is a separately source-owned executable dependency. External GitHub reviews, maintainer organization, model vendor and the operator are not automatically OpenClaw's autonomous S3* function.

[Open #201834](https://github.com/openclaw/openclaw/issues/201834) records the observed race: the helper deadline begins at request publication; a new reviewer process gets its own full timeout on subsequent launch; helper may retire exchange before the subprocess completes/submits. Late submit may replace a helpful timeout with `FileNotFoundError`. This research independently inspected source and source-based issue discussion, but **did not rerun the reported runtime reproduction**.

**Counterfactual:** remove a new composable S3* audit agent while keeping a native shared deadline, process-settlement guard and proper failure propagation. The same user outcome can still be delivered. Thus existing evidence does not establish material new independent-audit decision capability to construct.

## 2. First-party current source, open issues and competing PRs

| Element | Source/status | Meaning |
| --- | --- | --- |
| [Bundled Auto Review](https://github.com/openclaw/openclaw/blob/41bdde2111dd7031c93b47c57d7dad2e56bb0f5f/extensions/autoreview/src/tool.ts#L303-L480) | SHIPPED at pinned HEAD | `helperRun`, `runCommandWithTimeout`, `submitResponse`, cleanup; review result handoff is timing-sensitive |
| [Process runner](https://github.com/openclaw/openclaw/blob/41bdde2111dd7031c93b47c57d7dad2e56bb0f5f/src/process/exec-runner.ts#L662-L676) | SHIPPED | True subprocess completion distinct from terminal-looking stdout |
| [Code Mode bridge](https://github.com/openclaw/openclaw/blob/41bdde2111dd7031c93b47c57d7dad2e56bb0f5f/src/agents/code-mode-controller-source.ts#L369-L385) | SHIPPED | Caller error classification; producer must not lose true timeout |
| [Canonical helper](https://github.com/openclaw/agent-skills/blob/3cc834ceec0410c4ff37c09e5b81c91e65fc9fc9/skills/autoreview/scripts/autoreview#L8856-L8872) | Separate repo SHIPPED | Native request-to-ready timeout and exchange cleanup |
| [#201834](https://github.com/openclaw/openclaw/issues/201834) | OPEN | Defect report and maintainer-review advisory, not a merged fix |
| [PR #173455](https://github.com/openclaw/openclaw/pull/173455) | MERGED | Restricted reviewer introduction |
| [PR #200743](https://github.com/openclaw/openclaw/pull/200743) | MERGED | Different outer watchdog liveness |

**Rights preflight:** [MIT](https://github.com/openclaw/openclaw/blob/41bdde2111dd7031c93b47c57d7dad2e56bb0f5f/LICENSE), [CONTRIBUTING](https://github.com/openclaw/openclaw/blob/41bdde2111dd7031c93b47c57d7dad2e56bb0f5f/CONTRIBUTING.md): native bug fixes need tests, link source issue and respect original review/security gates; architecture features require Issue/Discord before PR. CLA/DCO personal legal formalities must be verified for an actual submission, not inferred from MIT. Matching verified fork `opensiro-contributions/openclaw`, `opensiro/meta` owner ACTIVE/ALLOW at intake; does not authorize public fork Issue or external communication.

## 2A. New-protocol independent Track A / Track B / incremental sufficiency

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

**Function-specific counterfactual:** remove the proposed independent auditor while keeping the original-native repair and supported review process. The documented operator task (correct result or truthful timeout) is still achieved, so **additional S3* C is unqualified**. The native issue's patch would be a source-native repair, not an autonomy regrade. The distinct receipt alternative requires a separate data retention/authority case and positive downstream need before becoming P2.

## 3. Why no supported new S3* C sufficiency path

A separate future S3* proposal would need these **logical** properties, none claimed as installed APIs: **A** independent attributable audit observation of an operational disturbance; **B** credible evidence/options including hold; **C** developer-composed autonomous auditor actually owning a complementary decision, independently and lawfully; **D** a first-party authorized correction/escalation bridge returning to S1/S3; **E** observable downstream action and later feedback to auditor. A timer, generic hook, code review report or another model name is not by itself A–E.

For #201834, no source-supported unmet independent organizational corrective decision beyond reliable transport was found. Proposed A–E would be extra complexity with unproven material operator benefit. A fix to handoff reliability cannot be counted as future S3*=C, nor can an unmerged issue/PR confer an Index grade.

## 4. Priority and dependency verdict

**P0:** NO_GO; a new independent auditor C constructor is NOT QUALIFIED. **P1:** a distinct original-native bug lane under #201834 if separately authorized: coordinate canonical-helper/plugin single pass deadline, wait for real subprocess completion, preserve authoritative error through late submit/cleanup and Code Mode. **P2: NONE**. A native repair is not an automatically admitted P0 dependency. No S3 parent rights transfer, S4 mode, S5 policy agent or independent-reviewer runtime is created.

## 5. Proposed native regression acceptance — NOT RUN

| Case | Stimulus | Required result |
| --- | --- | --- |
| NR-01 | Four-second timeout, delayed reviewer process launch | Effective single bounded pass, truthful timeout stage |
| NR-02 | Reviewer emits terminal JSON before actual exit | Must not accept incomplete process as success |
| NR-03 | Successful process exit followed by late submit | Preserve helper timeout; no misleading file-not-found replacement |
| NR-04 | Cancellation/multipass/cleanup | No false success, abandoned exchange or swallowed failure |
| NR-05 | Code Mode bridge wraps timeout | Accurate cause and error phase visible |
| NR-06 | Canonical helper contract changed | Canonical helper native-handoff tests on exact revised source |

Original suggested local command: `pnpm test extensions/autoreview/src/tool.test.ts src/agents/code-mode.bridge.lifecycle.test.ts --maxWorkers=1`, plus separate helper-native tests if changed. **Tests not executed; no runtime proof or S3* ownership witness claimed.**

## 6. Falsification, evidence ownership, authority

**NO_GO stands** while the cheapest native repair achieves the task or no distinct developer-composed complementary audit choice and corrective feedback is demonstrated. A future reopen needs source-backed operator demand, true independent audit decision owner, legal right to return a correction into actual running S1/S3 work, positive/negative/compatibility tests, later operational feedback and original maintainer context. A new Index assessment, if desired, is exclusively Index-owned and separately governed.

## 7. Alternatives, cost and publication

Independent original-native repair; distinct evidence-supported Profile/Skills clarification; or a lawful domain-specific fork experiment. All require their own permissions. Compare like-for-like engineering/review/integration/maintenance costs; **NOT_MEASURED**. **Final NO_GO** for speculative C controller. Public fork GitHub Issue and external original Issue/PR/comment **NOT PUBLISHED**. No code, tests, contribution record or regrade.
