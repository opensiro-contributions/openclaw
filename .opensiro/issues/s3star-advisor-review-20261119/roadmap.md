# Capability Roadmap Receipt — OpenClaw S3* Advisor review model

- Original repository: openclaw/openclaw
- Receipt contract: contribution-on-top
- Original HEAD: 8c0d54b97fe5d79b4c93591fb8794250ce7a198c
- Observed at: 2026-11-19
- Accepted Index assessment: https://github.com/opensiro/vsm-harness-index/blob/34e11ec4dd52e1ba3ee0111d8bca73f13918f54f/assessments/op/openclaw.md
- Accepted assessment blob SHA: e1d560bc5b28d90323b15f5f1af6a5293c614b45
- Accepted review ref: 387da5edaa9d6c6cfcfc15e167fe2e46d8647d86
- Accepted reviewed at: 2026-09-16
- System in focus: Original OpenClaw Gateway and bundled first-party Advisor during admitted active user-directed runs, with native plugin/session permissions; excludes third-party plugins, original maintainer governance and external code-review automation
- Result: NEEDS_EVIDENCE
- Disposition: DECISION_READY
- Final operator decision: NO_GO
- External issue: DRAFT — NOT PUBLISHED
- Cost status: NOT_MEASURED

## Identity and pins

[Original HEAD](https://github.com/openclaw/openclaw/commit/8c0d54b97fe5d79b4c93591fb8794250ce7a198c) observed 2026-11-19, distinct from the accepted [Index S1–S5 assessment](https://github.com/opensiro/vsm-harness-index/blob/34e11ec4dd52e1ba3ee0111d8bca73f13918f54f/assessments/op/openclaw.md) source pin `387da5edaa9d6c6cfcfc15e167fe2e46d8647d86`. Historical accepted vector **S1=A, S2=C, S3=C(P), S3*=—, S4=—, S5=—**, Profile `0.2.1`, Methodology `0.3.1`, reviewed 2026-09-16. Review age is 64 days; **recommend Index re-review** for current autonomy interpretation, no silent grade update. Human [issue.md](https://github.com/opensiro-contributions/openclaw/blob/opensiro/meta/.opensiro/issues/s3star-advisor-review-20261119/issue.md) ↔ AI [constructor-sufficiency.md](https://github.com/opensiro-contributions/openclaw/blob/opensiro/meta/.opensiro/issues/s3star-advisor-review-20261119/constructor-sufficiency.md) share the vector, P0/P1/P2 and NO_GO.

## Rights and authority

[Original MIT license](https://github.com/openclaw/openclaw/blob/8c0d54b97fe5d79b4c93591fb8794250ce7a198c/LICENSE), [CONTRIBUTING](https://github.com/openclaw/openclaw/blob/8c0d54b97fe5d79b4c93591fb8794250ce7a198c/CONTRIBUTING.md) source-native feature/architecture first-contact requirement and plugin preference checked at pinned source. CLA/DCO and personal acts have not been proven absent: verify before future original PR. Matching `opensiro-contributions/openclaw` fork, `opensiro/meta` initial HEAD `5b86180a66b6ac8607b405e97506cfa4b9cd53c8`, fork state `ACTIVE / ALLOW` independently read 2026-11-19. This authorizes no third-party or public fork Issue/PR.

## Existing work / overlap

[SHIPPED bundled Advisor](https://github.com/openclaw/openclaw/blob/8c0d54b97fe5d79b4c93591fb8794250ce7a198c/extensions/advisor/index.ts) reviews active sessions on the session's own model and may steer bounded corrections. [SHIPPED manifest](https://github.com/openclaw/openclaw/blob/8c0d54b97fe5d79b4c93591fb8794250ce7a198c/extensions/advisor/openclaw.plugin.json) configures schedule/instructions but lacks a configurable `model` field. [Original issue #184787](https://github.com/openclaw/openclaw/issues/184787) describes different-model oversight. [PR #196242](https://github.com/openclaw/openclaw/pull/196242), observed open earlier on 2026-11-19, head `cfd89afbe771bfdbc69cf5c7be203a2cd85e327f`, already implements the specific requested model-selection option in a proposal. Raw API refreshed status failed HTTP 403 due rate limit; **revalidate before any PR-state assertion/action**. That PR is **not shipped**; it reports mocked smoke but lacks complete native tests/provider E2E. No novel outcome beyond the issue/PR has been independently supported. Existing fork S4 case [s4-compatibility-transition-20261118](https://github.com/opensiro-contributions/openclaw/blob/opensiro/meta/.opensiro/issues/s4-compatibility-transition-20261118/README.md) is separate and not altered.


## Parallel contribution-on-top review

- Evaluation object: An additional OpenSiro-authored S3* reviewer-model or independently evidenced active-run correction capability beyond the bundled first-party OpenClaw Advisor and original #184787 / #196242
- Existing-work overlap: Shipped same-model Advisor; original Issue #184787 OPEN; original PR #196242 OPEN at cfd89afbe771bfdbc69cf5c7be203a2cd85e327f; prerequisite PR #196240 OPEN; original #193891 separate native repair; original #201834 has another fork-local case
- Our on-top contribution: No new P0 admitted; independently compared reuse unchanged (no new feature), integration/extension of existing PR with provenance or later feedback (NOT_EVIDENCED), adjacent direct-evidence audit (NOT_EVIDENCED), and unrelated native repairs (NOT_APPLICABLE)
- Incremental benefit: NOT_EVIDENCED beyond the same original model-selection task; requires concrete distinct operator scenario, actual current source gap and matched positive/negative native tests before GO
- Decision scope: NO_GO only for this redundant speculative OpenSiro reviewer-model contribution; not a verdict on OpenClaw, other S3* tasks, the pending original PR, or separately owned repairs

**Protocol:** [Upstream v0.17.0](https://github.com/opensiro/upstream/blob/0231dfd238f8fa6cdb779393c3c5f087f7599f7c/PROTOCOL.md). **Requalification observation:** 2026-11-19.
**Source recheck:** [openclaw/openclaw@af59c375011bbff913cf6d5ffc950da22eaaf0d6](https://github.com/openclaw/openclaw/commit/af59c375011bbff913cf6d5ffc950da22eaaf0d6); [current accepted Index](https://github.com/opensiro/vsm-harness-index/blob/394ce776e6945115891b8f7cc459f5a7f7d7aa39/assessments/op/openclaw.md) still contains the accepted blob e1d560bc5b28d90323b15f5f1af6a5293c614b45, historical source review_ref 387da5edaa9d6c6cfcfc15e167fe2e46d8647d86. Earlier frozen observations in this case remain intact.
**Live original overlap readback:** [Issue #184787](https://github.com/openclaw/openclaw/issues/184787) OPEN; [PR #196242](https://github.com/openclaw/openclaw/pull/196242) OPEN at head cfd89afbe771bfdbc69cf5c7be203a2cd85e327f; dependency [PR #196240](https://github.com/openclaw/openclaw/pull/196240) OPEN. These are **proposals**, not shipped code or verified native runtime tests.

| A — original native work / first-party evidence | Coverage and status | B — independent contribution-on-top hypothesis | Incremental user outcome and falsifier |
| --- | --- | --- | --- |
| [Shipped Advisor](https://github.com/openclaw/openclaw/blob/af59c375011bbff913cf6d5ffc950da22eaaf0d6/extensions/advisor/index.ts) and [manifest](https://github.com/openclaw/openclaw/blob/af59c375011bbff913cf6d5ffc950da22eaaf0d6/extensions/advisor/openclaw.plugin.json) | A tool-free review fork uses the current session model; NO_CHANGE/CORRECTION may steer its active run. No shipped model selector in the manifest | **Reuse unchanged:** no further OpenSiro product implementation | Native default already provides same-model oversight; no incremental task or S3* C witness follows from merely reusing it |
| [Original Issue #184787](https://github.com/openclaw/openclaw/issues/184787), [PR #196242](https://github.com/openclaw/openclaw/pull/196242), prerequisite [#196240](https://github.com/openclaw/openclaw/pull/196240) | All OPEN; original PR proposes a separate model, host model-policy checks and bounded transcript. Explicitly no full-context or live correction-quality proof | **Integrate/extend:** consider provenance-preserving review evidence or a measurable later-effect receipt *in addition to* the original model-selection PR | **NOT_EVIDENCED**: original PR covers the narrow other-model task. No independently supported operator case, missing first-party port or matched native test yet shows an additional benefit |
| [Closed Advisor windowed-context RFC #175708](https://github.com/openclaw/openclaw/issues/175708) and [open fork failure #193891](https://github.com/openclaw/openclaw/issues/193891) | Reported context/trigger pressure, and a separate native runtime defect; neither is a shipped autonomous S3* constructor | **Adjacent:** independently evidence-grounded corrective review with scoped direct tool receipts; or original-owner repair of fork failure | **NOT_EVIDENCED** for adjacent S3* C without a real operator counterfactual, trusted evidence access and later run effect. Fork failure is REPAIR_ONLY |
| [Separate OpenSiro Auto Review handoff case](https://github.com/opensiro-contributions/openclaw/blob/opensiro/meta/.opensiro/issues/s3star-autoreview-handoff-20261119/README.md) and [original #201834](https://github.com/openclaw/openclaw/issues/201834) | Distinct timer/handoff bug with independent fork-local case and original issue | **Reuse existing case**, no duplicated proposal | **NOT_APPLICABLE** to this specific Advisor model-selector decision; do not merge independent work units |

**Native alternative:** Keep using shipped Advisor for same-model reviews, or follow original PR #196242 for proposed different-model selection and original maintainer acceptance; unmerged code is not shipped. A future new C actor must independently prove direct evidence, lawful selection, enforced intervention and later operational feedback, including negative permission and missing-actor controls.

**Terminal decision after both tracks: NO_GO now** for this bounded redundant contribution, with additional independent feature hypotheses marked **NOT_EVIDENCED**. Historical accepted S3*=— remains unchanged. No implementation, native tests, public Issue, original PR or cost measurement is claimed.

## Function ownership

Historical accepted: **S1=A · S2=C · S3=C(P) · S3*=— · S4=— · S5=—**. This case tests S3* **independent complementary audit**, not generic logging, review text, another model name, S3 resource control, S4 adaptation or S5 policy. The original Advisor is already a first-party review path, but the separate/direct evidence, decisive independent audit owner and observed corrective closure are not freshly established here. An unmerged different-model option cannot be claimed as current S3*=C. **NO_GO** for duplicate architecture.

## Capability priority

**P0 S3***: distinct reviewer-model choice and active-run corrective receipt (already original Issue/PR scope): **NO_GO for an OpenSiro parallel implementation**. **P1**: only independent original-PR review and actual runtime/native validation if specifically authorized; **P2: NONE**. A new constructor would require a separately evidenced new task and function-specific actor→evidence→decision→lawful steer→later feedback, rather than historical grade chasing.

## Implementation options

Cheapest original-native path: existing Advisor for same-model review, original [#184787](https://github.com/openclaw/openclaw/issues/184787) / [PR #196242](https://github.com/openclaw/openclaw/pull/196242) for optional different model. Do **not** open a duplicate Issue, create competing code, assume PR adoption or claim current grade. Any future work would require a new material operator delta, original rights/CLA and live overlap preflight, source-native tests, and separate authorization.

## Specification and domain alternatives

A bounded, independently sourced **Index re-review** can examine whether source evolution changes current S3* evidence, without altering historical assessment. Only a real semantic ambiguity would route to Profile/Skills; a hypothetical domain-specific research fork is not a follow-on mandate. No VSM function, PR, Index state, or owner authority is changed by this receipt.

## Cost experiment

If reopened, measure matched work on a real user-requested task through shipped Advisor versus original PR versus a distinct independent reviewer: correction quality and later effect, token cost, latency, developer and reviewer time, build/test effort and maintenance. No costs or gains measured. **NOT_MEASURED**.

## Delivery and publication

**PLAN_ONLY; research label NEEDS_EVIDENCE; final operator decision NO_GO now.** Human fork-local [issue draft](https://github.com/opensiro-contributions/openclaw/blob/opensiro/meta/.opensiro/issues/s3star-advisor-review-20261119/issue.md), separately linked [AI contract](https://github.com/opensiro-contributions/openclaw/blob/opensiro/meta/.opensiro/issues/s3star-advisor-review-20261119/constructor-sufficiency.md) and this receipt are for the fork `opensiro/meta` only. **Public fork GitHub Issue: NOT PUBLISHED; original external issue/comment/PR: DRAFT — NOT PUBLISHED.** No implementation, source-native test, Index regrade, active monitor, PR or cost claim. This is a research record, not proof that all possible S3* improvements are useless. Before any public fork Issue or third-party action, require exact destination, full text/diff and separate current-conversation approval. AI-assisted preparation disclosed.
