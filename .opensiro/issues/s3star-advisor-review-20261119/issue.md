# OpenClaw — S3* independent Advisor review-model roadmap (OpenSiro plan-only)

**OpenSiro research case · PLAN_ONLY / NEEDS_EVIDENCE · DRAFT — NOT PUBLISHED**
**Final operator decision: NO_GO** for a new OpenSiro implementation or duplicate public proposal now.
**Working fork:** [opensiro-contributions/openclaw](https://github.com/opensiro-contributions/openclaw) · **Case:** `.opensiro/issues/s3star-advisor-review-20261119/` on `opensiro/meta`.
**AI/developer companion:** [constructor sufficiency](https://github.com/opensiro-contributions/openclaw/blob/opensiro/meta/.opensiro/issues/s3star-advisor-review-20261119/constructor-sufficiency.md) · **receipt:** [roadmap](https://github.com/opensiro-contributions/openclaw/blob/opensiro/meta/.opensiro/issues/s3star-advisor-review-20261119/roadmap.md).

## 1. Why OpenSiro and central accepted VSM assessment

OpenSiro tests whether reusable, VSM-informed specifications can standardize AI-agent harness engineering and reduce the total implementation, integration and maintenance cost. **This is a hypothesis**, not an observed saving, a demand that OpenClaw adopt VSM, or a claim that every missing Index function requires new code.

> **STARTING POINT — ACCEPTED HISTORICAL INDEX, NOT CURRENT HEAD OR A TARGET:**
> **`S1=A · S2=C · S3=C(P) · S3*=— · S4=— · S5=—`**
> [Accepted assessment](https://github.com/opensiro/vsm-harness-index/blob/34e11ec4dd52e1ba3ee0111d8bca73f13918f54f/assessments/op/openclaw.md), `review_ref=387da5edaa9d6c6cfcfc15e167fe2e46d8647d86`, `reviewed_at=2026-09-16`, Profile `0.2.1`, assessment procedure `0.3.1`, blob SHA `e1d560bc5b28d90323b15f5f1af6a5293c614b45`.

| Function | Accepted grade | Meaning at the accepted source boundary |
| --- | --- | --- |
| S1 · Operations | **A** | Configured assistant performs autonomous user tasks; no mandatory C replacement |
| S2 · Coordination | **C** | First-party session messaging and coordination/lifecycle construction |
| S3 · Current management | **C(P)** | Constructor and parent-governed present-control path, with exact user approval for mutations |
| S3* · Complementary audit | **—** | No sufficiently independent, closed autonomous complementary audit in that **2026-09-16** review |
| S4 · Future adaptation | **—** | No demonstrated prospective S3↔S4 adaptation closure in that review |
| S5 · Identity/policy | **—** | Parent approvals for current operations are not themselves ultimate-policy closure |

**Pins and scope:** [original current source HEAD](https://github.com/openclaw/openclaw/blob/8c0d54b97fe5d79b4c93591fb8794250ce7a198c/extensions/advisor/index.ts) = `8c0d54b97fe5d79b4c93591fb8794250ce7a198c`, observed 2026-11-19. System-in-focus: the first-party installed OpenClaw Gateway/Advisor plugin during user-directed runs, with its native plugin SDK and session permissions. External proprietary plugins, original maintainers, GitHub PR-review automation and human organization are outside. Assessment is **64 days old**: recommend a separate Index-owned source-pinned re-review before making any new autonomy claim; freshness is advisory, not a blocker.

**Rights:** original [MIT license](https://github.com/openclaw/openclaw/blob/8c0d54b97fe5d79b4c93591fb8794250ce7a198c/LICENSE) and [contribution policy](https://github.com/openclaw/openclaw/blob/8c0d54b97fe5d79b4c93591fb8794250ce7a198c/CONTRIBUTING.md) were read. New architectural features need an original Issue/Discord discussion first and normally prefer third-party plugins; publication and any required identity/CLA attestations need separate verification. Matching working fork has `opensiro/meta` owner control `ALLOW` (read 2026-11-19), which does not authorize a public fork Issue or third-party communication.

## 2. User outcome, proposed capability and terminal decision

**Investigated P0 / S3*:** an operator with a running agent wants a review performed by another configured model, rather than by the agent's own model, to reduce shared blind spots and return a bounded correction while the run remains active.

**Decision: NO_GO for a *new* implementation.** [Issue #184787](https://github.com/openclaw/openclaw/issues/184787) already specifies that outcome, and [original PR #196242](https://github.com/openclaw/openclaw/pull/196242) already proposes optional reviewer-model routing in the native Advisor. There is no independently established further operator task or material delta to justify a parallel OpenSiro construction. The PR is **not** equivalent to shipped behavior; its acceptance, review and runtime correctness remain original-maintainer decisions.

**P1:** source-check and independently validate the existing original PR if specifically requested, including authentic host policy, attribution, failure handling and native tests. **P2: NONE.**

## 3. Existing native work versus residual gap

| Topic | Verified shipped native source or original proposal | Residual evidence needed |
| --- | --- | --- |
| Advisor, session review | [Bundled Advisor](https://github.com/openclaw/openclaw/blob/8c0d54b97fe5d79b4c93591fb8794250ce7a198c/extensions/advisor/index.ts) forks the existing session model, evaluates in-flight work and can steer a correction back into the original active run | Same-model review does not itself prove independent S3* closure |
| Configurable reviewer model | [Issue #184787](https://github.com/openclaw/openclaw/issues/184787) and [PR #196242](https://github.com/openclaw/openclaw/pull/196242); proposed `runtime.llm.complete`, model/agent permissions, bounded transcript | Open PR is not shipped; independently validate when appropriate; do not duplicate |
| Authority and safety | [Advisor documentation](https://github.com/openclaw/openclaw/blob/8c0d54b97fe5d79b4c93591fb8794250ce7a198c/docs/plugins/reference/advisor.md): no tools on review fork; steering occurs under original agent's permissions | Need separate complementary evidence and corrective effect to support a full S3* conclusion |

Native alternative: use the shipped Advisor for same-model review now, or follow the original PR for cross-model configuration rather than shipping a second competing implementation. Original project and security owners control publication, model permissions and acceptance.

## 4. Priority and minimum sufficient result

| Priority | Candidate outcome | Decision |
| --- | --- | --- |
| P0 · S3* | A configurable different-model reviewer can inspect a running agent and return one authorized correction, with proper isolation and feedback | **NO_GO for duplicate construction** while the original PR covers the proposed interface |
| P1 · Evidence | Review the original PR and test an actual cross-model run, policy refusals, cancellations and correction receipt if later requested | Research only; no new implementation authorized |
| P2 | No distinct independently supported second function | **NONE** |

A future **new C constructor**, if independently justified, must expose the actual developer-supplied autonomous reviewer owner, its separate trustworthy evidence access, bound scope, review decision, authorized return and later effect. The current request has **no qualified new constructor**; extra model selection alone does not establish S3* autonomy.

## 5. Acceptance, stop and falsification

- **Positive future test:** separate-model reviewer sees attributable operational evidence, makes a supported independent finding, and a real active run receives a permitted correction.
- **Negative controls:** provider failure, cancellation, denied model/agent permissions, expired run, prompt-injection data and unavailable tools must never silently steer or escalate permissions.
- **Native counterfactual:** if the existing Advisor plus PR #196242 already fulfills the same authorized task, a parallel constructor fails the material-delta requirement; preserve the original project's review and CI gates.
- **Stop now:** no fresh first-party demand beyond #184787, no unique post-PR capability, no reproducible improvement-over-alternative evidence. Do not build, open a duplicate original Issue or assert a new Index S3* grade.
- All acceptance cases are **proposed**; no source-native tests, live model calls or measured benefit were executed in this roadmap.

## 6. Independent paths

Original-native: observe or contribute only to the existing Issue/PR under a **separate, explicit implementation and publication request**. Methodology: re-review the historical Index boundary independently if the present VSM classification matters. Domain-specific experiment: consider only if new evidence demonstrates a distinct domain task and lawful fork scope; none is authorized by this NO_GO.

## 7. Cost hypothesis

Compare the same user request handled through shipped Advisor, existing proposed cross-model PR, and a hypothetical independent plugin: attributable correction quality, tokens, latency, implementation/test/review effort and maintenance. **Cost status: NOT_MEASURED**. A separate OpenSiro implementation is not justified by guessed savings.

## 8. Decision / handoff

**Disposition: NEEDS_EVIDENCE** for any distinct new S3* constructor; **terminal operator decision: NO_GO** for duplicating the existing original-native proposal. Do not implement or publicly propose a second reviewer-model feature. Conditional reopening requires evidence of an unmet, materially different operator outcome after examining original PR status and supported implementation. Historical S3*=— remains immutable; only Index can assess current ownership.

The [AI/developer analysis](https://github.com/opensiro-contributions/openclaw/blob/opensiro/meta/.opensiro/issues/s3star-advisor-review-20261119/constructor-sufficiency.md) links back here and shares the same vector and P0/P1/P2. **Public fork Issue: NOT PUBLISHED. Original Issue/comment/PR: NOT PUBLISHED.** This text is a prepared fork-local discussion draft, not an original-maintainer request, delivery of code, approval grant or engineering-cost claim. External publication requires exact destination/text consent in the current conversation.

**AI disclosure:** Prepared with AI assistance; independent human review, native executable evidence and cost improvements are not claimed.
