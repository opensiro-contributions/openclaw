# OpenClaw — S3* Advisor independent-review constructor sufficiency

**Status:** `PLAN_ONLY / NEEDS_EVIDENCE`; **final decision: NO_GO** for duplicate implementation. **DRAFT — NOT PUBLISHED**.
**Canonical location:** `opensiro-contributions/openclaw@opensiro/meta:.opensiro/issues/s3star-advisor-review-20261119/constructor-sufficiency.md`.
**Human decision:** [issue.md](https://github.com/opensiro-contributions/openclaw/blob/opensiro/meta/.opensiro/issues/s3star-advisor-review-20261119/issue.md) · [receipt](https://github.com/opensiro-contributions/openclaw/blob/opensiro/meta/.opensiro/issues/s3star-advisor-review-20261119/roadmap.md). Same boundary, vector, priorities and decision apply.

**Historical accepted vector:** `S1=A · S2=C · S3=C(P) · S3*=— · S4=— · S5=—` (not a current grade).

## Functional scope and authority

The only researched potential new constructor is **S3***: independent complementary examination of the actual running system and a return path for corrective action. The following functions retain their own owners and do **not** become additional feature targets.

| Function | Historical accepted | Distinct role and boundary |
| --- | --- | --- |
| S1 | **A** | User-facing model/harness operations; reviewer must not silently acquire operational authority |
| S2 | **C** | Native session communication and responsibility, not by itself complementary audit |
| S3 | **C(P)** | Current resource/configuration control; host approvals stay authoritative |
| S3* | **—** | Historical absence of sufficiently independent complementary audit in reviewed standard distribution |
| S4 | **—** | Future environmental adaptation not demonstrated by Advisor steering |
| S5 | **—** | Parent policy/identity authority not created by a reviewer model |

Accepted [Index assessment](https://github.com/opensiro/vsm-harness-index/blob/34e11ec4dd52e1ba3ee0111d8bca73f13918f54f/assessments/op/openclaw.md), `review_ref=387da5edaa9d6c6cfcfc15e167fe2e46d8647d86`, reviewed `2026-09-16`, Profile `0.2.1`, Methodology `0.3.1`; blob `e1d560bc5b28d90323b15f5f1af6a5293c614b45`. This is **historical**, not an assessment of [current original HEAD](https://github.com/openclaw/openclaw/commit/8c0d54b97fe5d79b4c93591fb8794250ce7a198c). Source drift and 64-day elapsed review merit Index re-review but do not force a grade or block source-only research.

## 1. Boundary, operator outcome and counterfactual

**System-in-focus:** original first-party OpenClaw Gateway and bundled Advisor plugin for admitted active, user-directed runs, including its session model fork and plugin policy. Exclude maintainer GitHub automation, external/private plugins and operator identity as an autonomous S3* actor.

**P0 investigated:** let an operator configure a *different* reviewing model to detect blind spots during a supported active agent run and issue a bounded corrective steer. The simplest supported baseline is shipped same-model [Advisor](https://github.com/openclaw/openclaw/blob/8c0d54b97fe5d79b4c93591fb8794250ce7a198c/extensions/advisor/index.ts) plus explicit operator review. The original [issue #184787](https://github.com/openclaw/openclaw/issues/184787) and [PR #196242](https://github.com/openclaw/openclaw/pull/196242) already describe the proposed cross-model model-selection implementation. No separately evidenced material task remains for an OpenSiro duplicate.

**Counterfactual:** compare the exact same user run, available transcript/evidence and permissions across (a) shipped same-model Advisor, (b) original PR's proposed independent model on its **actual** code when lawfully run, and (c) a speculative new constructor. If (b) can fulfill the user outcome and (c) changes only model-selection plumbing, it does **not** justify a separate C construction. A distinct S3* witness additionally needs genuinely complementary evidence access and a lawful return, which neither model identity nor a proposed PR proves.

**P1:** only source-native analysis and qualified tests of the original PR if independently requested. **P2: NONE.** Current decision **NO_GO** for another implementation.

## 2. Shipped baseline, original issue/PR and remaining uncertainty

| Port / evidence | First-party current-HEAD path | Status and distinction |
| --- | --- | --- |
| Reviewer trigger and original context | [`extensions/advisor/index.ts`](https://github.com/openclaw/openclaw/blob/8c0d54b97fe5d79b4c93591fb8794250ce7a198c/extensions/advisor/index.ts) | **SHIPPED:** schedules a bounded model review for an admitted run; retains session's model |
| Developer-configured review controls | [`extensions/advisor/openclaw.plugin.json`](https://github.com/openclaw/openclaw/blob/8c0d54b97fe5d79b4c93591fb8794250ce7a198c/extensions/advisor/openclaw.plugin.json) | **SHIPPED:** review frequency/instructions; `model` is **not** in the current manifest |
| Observation and corrective return | [Advisor reference](https://github.com/openclaw/openclaw/blob/8c0d54b97fe5d79b4c93591fb8794250ce7a198c/docs/plugins/reference/advisor.md) | **SHIPPED:** tool-free fork, `NO_CHANGE/CORRECTION` contract and bounded active-run steer, under original session permissions |
| Cross-model selector | [#184787](https://github.com/openclaw/openclaw/issues/184787) · [PR #196242](https://github.com/openclaw/openclaw/pull/196242) | **OPEN_PR at prior first-party read**; raw REST state refresh rate-limited; PR head `cfd89afbe771bfdbc69cf5c7be203a2cd85e327f`; do **not** count as shipped |
| S3* independence and deployed effect | No current observed live evidence in this case | **UNVERIFIED:** independent decision rights, complementary direct evidence, deployable corrected outcome and runtime quality |

One GitHub API re-read returned HTTP 403 (anonymous rate limit) during this research; the prior GitHub PR read reported `open`. Avoid converting incomplete live readback into a fresh status claim. The PR's own description reports **mocked smoke** but not complete native tests or live provider/Gateway validation; these limitations are not a reason to create a duplicate PR.

**Rights preflight:** [MIT license](https://github.com/openclaw/openclaw/blob/8c0d54b97fe5d79b4c93591fb8794250ce7a198c/LICENSE); [CONTRIBUTING](https://github.com/openclaw/openclaw/blob/8c0d54b97fe5d79b4c93591fb8794250ce7a198c/CONTRIBUTING.md) directs architectural features to an Issue/Discord first and normally prefers third-party plugins. Human-only attestation, AI disclosure and CLA/DCO requirements need confirmation *before* any later third-party PR. Verified parent-matched OpenSiro fork `opensiro-contributions/openclaw` and `ACTIVE / ALLOW` on `opensiro/meta` at intake; this only supports authorized case metadata, not public proposals.


## 2A. Mandatory parallel A+B source-native constructor review (Upstream v0.17.0)

**Evaluation object and scope:** A new OpenSiro-authored first-party independent model-review feature over the admitted active user run, only insofar as it adds demonstrable value beyond original #184787 and PR #196242. **NO_GO** is limited to this contribution, not all OpenClaw S3* research.

**Protocol:** [Upstream v0.17.0](https://github.com/opensiro/upstream/blob/0231dfd238f8fa6cdb779393c3c5f087f7599f7c/PROTOCOL.md). **Requalification observation:** 2026-11-19.
**Source recheck:** [openclaw/openclaw@af59c375011bbff913cf6d5ffc950da22eaaf0d6](https://github.com/openclaw/openclaw/commit/af59c375011bbff913cf6d5ffc950da22eaaf0d6); [current accepted Index](https://github.com/opensiro/vsm-harness-index/blob/394ce776e6945115891b8f7cc459f5a7f7d7aa39/assessments/op/openclaw.md) still contains the accepted blob e1d560bc5b28d90323b15f5f1af6a5293c614b45, historical source review_ref 387da5edaa9d6c6cfcfc15e167fe2e46d8647d86. Earlier frozen observations in this case remain intact.
**Live original overlap readback:** [Issue #184787](https://github.com/openclaw/openclaw/issues/184787) OPEN; [PR #196242](https://github.com/openclaw/openclaw/pull/196242) OPEN at head cfd89afbe771bfdbc69cf5c7be203a2cd85e327f; dependency [PR #196240](https://github.com/openclaw/openclaw/pull/196240) OPEN. These are **proposals**, not shipped code or verified native runtime tests.

| A — original native work / first-party evidence | Coverage and status | B — independent contribution-on-top hypothesis | Incremental user outcome and falsifier |
| --- | --- | --- | --- |
| [Shipped Advisor](https://github.com/openclaw/openclaw/blob/af59c375011bbff913cf6d5ffc950da22eaaf0d6/extensions/advisor/index.ts) and [manifest](https://github.com/openclaw/openclaw/blob/af59c375011bbff913cf6d5ffc950da22eaaf0d6/extensions/advisor/openclaw.plugin.json) | A tool-free review fork uses the current session model; NO_CHANGE/CORRECTION may steer its active run. No shipped model selector in the manifest | **Reuse unchanged:** no further OpenSiro product implementation | Native default already provides same-model oversight; no incremental task or S3* C witness follows from merely reusing it |
| [Original Issue #184787](https://github.com/openclaw/openclaw/issues/184787), [PR #196242](https://github.com/openclaw/openclaw/pull/196242), prerequisite [#196240](https://github.com/openclaw/openclaw/pull/196240) | All OPEN; original PR proposes a separate model, host model-policy checks and bounded transcript. Explicitly no full-context or live correction-quality proof | **Integrate/extend:** consider provenance-preserving review evidence or a measurable later-effect receipt *in addition to* the original model-selection PR | **NOT_EVIDENCED**: original PR covers the narrow other-model task. No independently supported operator case, missing first-party port or matched native test yet shows an additional benefit |
| [Closed Advisor windowed-context RFC #175708](https://github.com/openclaw/openclaw/issues/175708) and [open fork failure #193891](https://github.com/openclaw/openclaw/issues/193891) | Reported context/trigger pressure, and a separate native runtime defect; neither is a shipped autonomous S3* constructor | **Adjacent:** independently evidence-grounded corrective review with scoped direct tool receipts; or original-owner repair of fork failure | **NOT_EVIDENCED** for adjacent S3* C without a real operator counterfactual, trusted evidence access and later run effect. Fork failure is REPAIR_ONLY |
| [Separate OpenSiro Auto Review handoff case](https://github.com/opensiro-contributions/openclaw/blob/opensiro/meta/.opensiro/issues/s3star-autoreview-handoff-20261119/README.md) and [original #201834](https://github.com/openclaw/openclaw/issues/201834) | Distinct timer/handoff bug with independent fork-local case and original issue | **Reuse existing case**, no duplicated proposal | **NOT_APPLICABLE** to this specific Advisor model-selector decision; do not merge independent work units |

**Native counterfactual and construction sufficiency:** Track A distinguishes shipped Advisor from OPEN_PR implementation (never count the latter as shipped). Track B independently considers reuse, integrative extension and adjacent independent corrective audit. To qualify a further first-party C constructor, a real developer-supplied autonomous reviewer must have complementary trustworthy evidence access; options including hold and correction; enforced original-run rights; bounded, attributable decision state; and later operative effect. Neither a speculative extra model setting nor the existing Issue is such a witness.

**Rejection and tests:** Reuse only has zero incremental product effect. The proposed on-top evidence/feedback integration may be different from PR #196242, but remains **NOT_EVIDENCED** pending a real source-linked user case and verified missing port. An adjacent direct-evidence audit would require permission and tool-evidence boundary checks, positive review and changed later-run behavior; no such test or native implementation is claimed. Original #193891 is repair work and #201834 belongs to a separate case.

**P0:** no qualified new implementation. **P1:** original PR tests/CI, permission negatives, real-model Gateway run and documented model-identity, correction and cancellation outcomes *only under a future separately authorized engineering task*. **P2: NONE.** **Terminal NO_GO now only for the proposed duplicate model selector;** new evidence may reopen another bounded evaluation object. Original maintainer PR ownership, S3/S5 rights, Index semantic ownership and publication gates remain unchanged. **NOT_TESTED; NOT_MEASURED.**

## 3. Conditional S3* construction test — NOT an admitted new feature

No new code ports are proposed for implementation. If a genuinely different operator task is later established, the minimal acceptable S3* contract would need:

| Independent property | Conditional required witness | Falsifier |
| --- | --- | --- |
| Distinct review and evidence access | Separate reviewer actor gets meaningful complementary observations of the real active run, under configured permissions | Merely replaying same-model transcript, hardcoded evaluation or lacking independent observations |
| Lawful review choice | Reviewer weighs real alternatives `hold/no-change` vs bounded correction based on evidence and scope | Code unconditionally routes a predetermined correction or bypasses policy |
| Enforcement and feedback | Existing run receives the authorized steer, effect observed in later tool/task behavior with provenance | Review emits text/log only, or after-run correction is dropped |
| Negative authority path | Denied models, expired runs, canceled review, unavailable tools, prompt injection and missing credentials are safe and explicit | Fail-open execution, hidden fallback, forged principal or silent privilege escalation |

This matrix is a **hypothetical future acceptance test**, not a claim that OpenClaw has or lacks all of these interfaces and not a promised reusable constructor. Current native Advisor and PR must first be tested on matching conditions. No independently supported new capability, implementation owner or concrete additional API is established.

## 4. Priority and dependencies

- **P0 S3*:** **NO_GO** for parallel model-selection implementation; do not publish a duplicate of original #184787 / PR #196242.
- **P1 evidence only:** verify original PR's current status/head, source-diff correctness, real model permission enforcement, request transcript scope, cancellation, meaningful independent oversight and active-run feedback *if separately commissioned*.
- **P2:** **NONE**; do not add mandatory S3, S4 or S5 features.

## 5. Primary future native acceptance cases (not run)

- **AC-01 Positive:** original-native separate-model reviewer receives permitted direct evidence, returns a substantive correction, and subsequent active-run behavior reflects a lawful steer.
- **AC-02 Counterfactual:** same task, same scoped source and authority compared to shipped Advisor and PR's implemented flow; any duplicate pathway demonstrates independently material additional capability before admission.
- **AC-03 Missing actor / bad credentials:** no invented cross-model S3* ownership or fallback when separate reviewer cannot be configured.
- **AC-04 Security negatives:** denied model or principal cannot steer; canceled or completed run cannot accept late correction; advisory output does not override S3/S5 authority.
- **AC-05 Regression:** default Advisor's same-model behavior is preserved; failure returns explicit evidence, no silent fallback or fake successful review.

Required real tests would use original-native `pnpm test:extension advisor` plus relevant plugin contracts and a host-authenticated Gateway run where permitted; **NOT_TESTED** here.

## 6. Falsification, evidence owners and decision

**Final operator decision: NO_GO.** Existing native feature plus an already-open targeted PR covers the specific proposed P0 without any proven differentiated task. The historical `S3*=—` is not a mandate to construct `C`. Do not conflate an unmerged PR with shipped capabilities or any future Index regrade. A material new target could be reopened only with a distinct real operator action, matched cheaper-native counterfactual, original-maintainer overlap review and lawful authority.

**Evidence owners:** original repository / maintainers own shipped code, Issue/PR and merge/admission; Index owns accepted assessment and re-review; OpenSiro fork owns this plan-only research note. No native test, public fork Issue, third-party Issue/PR or product code is represented as delivered. **Cost: NOT_MEASURED.** Prepared with AI assistance.
