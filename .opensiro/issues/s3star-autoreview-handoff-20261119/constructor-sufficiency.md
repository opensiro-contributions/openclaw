# OpenClaw — S3* Auto Review handoff: independent AI/developer decision contract

**PLAN_ONLY / DECISION_READY · terminal NO_GO for speculative S3*=C**. This is the separate technical layer of [the Human Issue](https://github.com/opensiro-contributions/openclaw/blob/opensiro/meta/.opensiro/issues/s3star-autoreview-handoff-20261119/issue.md), not a second public Issue. Same historical starting profile and P0/P1/P2.

## Function-specific scope, accepted evidence and rights

**Accepted historical assessment (not a current-HEAD regrade): S1=A · S2=C · S3=C(P) · S3*=— · S4=— · S5=—.** [Pinned Index](https://github.com/opensiro/vsm-harness-index/blob/34e11ec4dd52e1ba3ee0111d8bca73f13918f54f/assessments/op/openclaw.md); reviewed 2026-09-16 at original `387da5edaa9d6c6cfcfc15e167fe2e46d8647d86`, assessment blob `e1d560bc5b28d90323b15f5f1af6a5293c614b45`, Profile 0.2.1, assessment procedure 0.3.1. Current source [`08b4ac92c1978f1f68dd78b53e7879ba24363c1b`](https://github.com/openclaw/openclaw/commit/08b4ac92c1978f1f68dd78b53e7879ba24363c1b) observed 2026-11-19. Review age 64 days warrants a separate source-pinned Index re-review recommendation, never silent reinterpretation of the accepted vector.

| Function | Decisive organizational scope |
| --- | --- |
| S1 | Existing autonomous agent work |
| S2 | Composable agent/session coordination |
| S3 | Current whole-deployment control and parent-approved changes, preserve existing C(P) |
| **S3*** | Requires sufficiently independent complementary audit evidence, a distinct accountable judgment/choice, authorized correction and later operational feedback |
| S4 | External future adaptation is not the handoff bug |
| S5 | Ultimate legitimate policy cannot be granted by a reviewer or prompt |

## 1. Boundary and actor counterfactual

Current original [`08b4ac92c1978f1f68dd78b53e7879ba24363c1b`](https://github.com/openclaw/openclaw/commit/08b4ac92c1978f1f68dd78b53e7879ba24363c1b), observed 2026-11-19. Include Gateway, installed bundled Auto Review and process/Code Mode runtime; canonical helper `openclaw/agent-skills` is a separately source-owned executable dependency. External GitHub reviews, maintainer organization, model vendor and the operator are not automatically OpenClaw's autonomous S3* function.

[Open #201834](https://github.com/openclaw/openclaw/issues/201834) records the observed race: the helper deadline begins at request publication; a new reviewer process gets its own full timeout on subsequent launch; helper may retire exchange before the subprocess completes/submits. Late submit may replace a helpful timeout with `FileNotFoundError`. This research independently inspected source and source-based issue discussion, but **did not rerun the reported runtime reproduction**.

**Counterfactual:** remove a new composable S3* audit agent while keeping a native shared deadline, process-settlement guard and proper failure propagation. The same user outcome can still be delivered. Thus existing evidence does not establish material new independent-audit decision capability to construct.

## 2. First-party current source, open issues and competing PRs

| Element | Source/status | Meaning |
| --- | --- | --- |
| [Bundled Auto Review](https://github.com/openclaw/openclaw/blob/08b4ac92c1978f1f68dd78b53e7879ba24363c1b/extensions/autoreview/src/tool.ts#L303-L480) | SHIPPED at pinned HEAD | `helperRun`, `runCommandWithTimeout`, `submitResponse`, cleanup; review result handoff is timing-sensitive |
| [Process runner](https://github.com/openclaw/openclaw/blob/08b4ac92c1978f1f68dd78b53e7879ba24363c1b/src/process/exec-runner.ts#L662-L676) | SHIPPED | True subprocess completion distinct from terminal-looking stdout |
| [Code Mode bridge](https://github.com/openclaw/openclaw/blob/08b4ac92c1978f1f68dd78b53e7879ba24363c1b/src/agents/code-mode-controller-source.ts#L369-L385) | SHIPPED | Caller error classification; producer must not lose true timeout |
| [Canonical helper](https://github.com/openclaw/agent-skills/blob/3cc834ceec0410c4ff37c09e5b81c91e65fc9fc9/skills/autoreview/scripts/autoreview#L8856-L8872) | Separate repo SHIPPED | Native request-to-ready timeout and exchange cleanup |
| [#201834](https://github.com/openclaw/openclaw/issues/201834) | OPEN | Defect report and maintainer-review advisory, not a merged fix |
| [PR #173455](https://github.com/openclaw/openclaw/pull/173455) | MERGED | Restricted reviewer introduction |
| [PR #200743](https://github.com/openclaw/openclaw/pull/200743) | MERGED | Different outer watchdog liveness |

**Rights preflight:** [MIT](https://github.com/openclaw/openclaw/blob/08b4ac92c1978f1f68dd78b53e7879ba24363c1b/LICENSE), [CONTRIBUTING](https://github.com/openclaw/openclaw/blob/08b4ac92c1978f1f68dd78b53e7879ba24363c1b/CONTRIBUTING.md): native bug fixes need tests, link source issue and respect original review/security gates; architecture features require Issue/Discord before PR. CLA/DCO personal legal formalities must be verified for an actual submission, not inferred from MIT. Matching verified fork `opensiro-contributions/openclaw`, `opensiro/meta` owner ACTIVE/ALLOW at intake; does not authorize public fork Issue or external communication.

## 2A. Parallel source-native and independently conceived on-top options

| Track | Existing → coverage | Proposed on-top change | Incremental operator outcome | Falsifier / evidence verdict |
| --- | --- | --- | --- | --- |
| **A · Original-native bug** | [Bundled Auto Review handoff](https://github.com/openclaw/openclaw/blob/08b4ac92c1978f1f68dd78b53e7879ba24363c1b/extensions/autoreview/src/tool.ts#L361-L464) plus [open #201834](https://github.com/openclaw/openclaw/issues/201834): restricted reviewer exists, but helper and reviewer timeouts are not coordinated; no submitted accepted repair identified | Minimal shared pass deadline and authoritative error propagation, under original owner and canonical-helper dependency | Prevent lost completed result and misleading timeout in the *existing* user task | This is a useful **native repair lead**, not sufficient evidence of new S3* C. Its actual solution, tests and maintainer decision remain separate |
| **B1 · Our provenance/receipt extension** | Existing helper already exchanges `run_id`, `pass`, `prompt_sha256`; issue calls for stage-specific error and reliable completion | A first-party durable audit-result receipt linking reviewer decision, failure stage and later operator inspection | Potentially easier diagnosis across restarts or repeated review passes | **NOT_EVIDENCED:** no independent operator need beyond the original fix, no supported durability/retention contract or legitimate new audit decision owner; if native P1 fixes diagnostics, no material delta |
| **B2 · Our S3* composition extension** | Shipped restricted reviewer is a component; separate [Advisor S3* roadmap](https://github.com/opensiro-contributions/openclaw/blob/opensiro/meta/.opensiro/issues/s3star-advisor-review-20261119/README.md) examines model-selection oversight, not this helper timeout | Developer-composed independent complementary-audit actor chooses `hold`/lawful correction, returns to S1/S3 with later feedback | Would be distinct only if an operator needs a new independently owned *organizational* correction decision, not simply delivered review text | **NOT_EVIDENCED:** no such extra task, actor authority/first-party installation or corrective-return requirement demonstrated; native result-delivery repair remains cheaper |
| **B3 · Our cross-repo integration** | Original plugin invokes separately owned [canonical helper](https://github.com/openclaw/agent-skills/blob/3cc834ceec0410c4ff37c09e5b81c91e65fc9fc9/skills/autoreview/scripts/autoreview#L8856-L8872) | One bounded deadline ownership contract + matched regression tests across both repos | Correct existing result handoff with less diagnostic loss | **COVERED BY ORIGINAL ISSUE INTENT:** valid narrow engineering hypothesis, not a distinct additional S3* feature; maintainer coordination is necessary before patches |

**Incremental-value conclusion:** an original issue is **not** a categorical veto. We independently considered an additional durable audit receipt, a composable corrective auditor and the cross-repo integration beyond shipped behavior. The cross-repo integration has concrete native-repair value **within original #201834**, but the proposed extra S3* constructor and persistent receipt lack independently justified incremental benefit. **NO_GO applies only to a new S3*=C constructor for this Auto Review handoff, not to native #201834 repair, another OpenClaw task, or the whole harness.** No new API, tests, cost measurement or external maintainer adoption claimed.

**Decision counterfactual:** remove the new audit actor but retain the native deadline repair; the original user outcome is still met. Scope is a proposed new S3* controller for Auto Review handoff, not a ban on the source-owned original bugfix.

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
