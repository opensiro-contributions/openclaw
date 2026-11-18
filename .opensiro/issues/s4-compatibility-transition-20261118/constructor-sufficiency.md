# OpenClaw — S4 prospective compatibility constructor sufficiency (developer contract)

**PLAN_ONLY / DECISION_READY · DRAFT — NOT PUBLISHED.** This is the AI/developer half of [one human issue](https://github.com/opensiro-contributions/openclaw/blob/opensiro/meta/.opensiro/issues/s4-compatibility-transition-20261118/issue.md), not a separate public Issue. Baseline, priority and stop verdict are identical in both documents.

## Boundary and historical states

Original first-party source [openclaw/openclaw@5cb5f15409575744f6f2f157a5eed8c5bec2071b](https://github.com/openclaw/openclaw/commit/5cb5f15409575744f6f2f157a5eed8c5bec2071b); observed 2026-11-18. Accepted [Index](https://github.com/opensiro/vsm-harness-index/blob/5f6ea0c777733813ca42e3f210390a719488dcfb/assessments/op/openclaw.md) blob `e1d560bc5b28d90323b15f5f1af6a5293c614b45` reviewed 2026-09-16 at `387da5edaa9d6c6cfcfc15e167fe2e46d8647d86`, Profile 0.2.1, assessment procedure 0.3.1. **Historical S1=A; S2=C; S3=C(P); S3*=—; S4=—; S5=—.** 63-day-old review: re-assessment recommended separately. Runtime in scope: Gateway, installed plugins, plugin SDK, Doctor, operator-reviewed host system-agent commands; vendor facts, external ClawHub plugins and human operator are not first-party functionality.

## Functional scope and exclusion

| Function | Observed vs proposed |
| --- | --- |
| S1 | Existing ordinary agent operations `A`; no change proposed |
| S2 | Existing session communication `C`; no change proposed |
| S3 | Existing `C(P)` exact host-approved changes in [system-agent tool](https://github.com/openclaw/openclaw/blob/5cb5f15409575744f6f2f157a5eed8c5bec2071b/src/agents/tools/system-agent-tool.ts); retain authority, never let S4 actor self-approve |
| S3* | Historically absent; neither event logging nor Doctor is an independent complementary-audit actor; out of scope |
| **S4** | Candidate `C`: external prospective distinction; developer-supplied decision actor; options and S3 dialogue; actual later-operation return |
| S5 | Identity/ultimate policy reserved to legitimate operator; host approval for S3 is not S5 closure; no proposed grade |

**P0:** one narrowly scoped S4 compatibility-transition constructor. **P1:** necessary first-party snapshot/options/host-gate/receipt ports. **P2: NONE.** No implementation, new grade, test execution or savings asserted.

## Source-native map: what is shipped and what is not

1. **SHIPPED observations:** [`src/plugins/sdk-deprecation-notices.ts`](https://github.com/openclaw/openclaw/blob/5cb5f15409575744f6f2f157a5eed8c5bec2071b/src/plugins/sdk-deprecation-notices.ts) reads registered `removeAfter` for imported SDK APIs and formats notices; [`src/plugins/status.ts`](https://github.com/openclaw/openclaw/blob/5cb5f15409575744f6f2f157a5eed8c5bec2071b/src/plugins/status.ts) integrates compatibility notice inspection. These support only current awareness of some future dates.
2. **SHIPPED current-control boundary:** [`src/agents/tools/system-agent-tool.ts`](https://github.com/openclaw/openclaw/blob/5cb5f15409575744f6f2f157a5eed8c5bec2071b/src/agents/tools/system-agent-tool.ts) lists typed read and persistent actions; the host tracks one exact proposal fingerprint and approval-arm state. [`src/system-agent/approval-intent.ts`](https://github.com/openclaw/openclaw/blob/5cb5f15409575744f6f2f157a5eed8c5bec2071b/src/system-agent/approval-intent.ts) refuses to trust model text as independent approval. These are **S3/P approval primitives**, not an S4 controller.
3. **SHIPPED reactive model discovery:** [`src/agents/prepared-model-runtime.discovery-retry.ts`](https://github.com/openclaw/openclaw/blob/5cb5f15409575744f6f2f157a5eed8c5bec2071b/src/agents/prepared-model-runtime.discovery-retry.ts) has retry and inventory freshness; it is not a proof of independent future scenarios or a plugin migration choice.
4. **ISSUE_ONLY / closed:** [#179294](https://github.com/openclaw/openclaw/issues/179294) proposed installation manifest × target release impact report; closed without evidence of shipping. Reuse idea, do not represent it as merged.
5. **OPEN ISSUE and OPEN PR:** [#190536](https://github.com/openclaw/openclaw/issues/190536) / [#200932](https://github.com/openclaw/openclaw/pull/200932) at head `e1f94d4b85d4ee65dd24b45a036fb47018a2fcd0` repair notice wording. [#190752](https://github.com/openclaw/openclaw/pull/190752) at `71395005fe9fa5d9e3f6a2e19110e15b228445eb` was closed unmerged. The proposed contract deliberately excludes date-text fixes already covered.
6. **EXTERNAL FUTURE FACT:** [#200928](https://github.com/openclaw/openclaw/issues/200928) shows a future Atlassian endpoint retirement for a plugin with re-auth implications; the third-party plugin and vendor claims are external, not OpenClaw-shipped controller capability.
7. **UNVERIFIED:** no current first-party public S4 constructor for trusted prospective vendor/release facts -> developer-authored decision -> S3-approved migration -> later-operation receipt was established by this focused read. This is a research gap statement, not proof the entire large codebase lacks all S4 functionality.

## Exact proposed S4 interface and ownership

**Counterfactual:** operator with multiple installed plugins currently must map vendor/release changes to actual use and decide tradeoffs manually; an independently composed controller could triage competing retirement deadlines and schedule safe option proposals while preserving consent. The existing CLI/Doctor might still be good enough; measure before developing.

Proposed **minimal first-party** producer and decision/return ports (API names are conceptual, not claimed to exist):

| Port | Trusted input / producer | Contract and essential negative condition |
| --- | --- | --- |
| P1-A · `compatibilityForecast.snapshot` | Host-installed plugin/SDK metadata + allowlisted signed/versioned release/deprecation facts | Redact credentials and conversations; carry source URL, retrieval time, verification and expiry; missing external fact is `UNKNOWN`, not safe |
| P1-B · `compatibilityForecast.options` | Current installed manifests + supported target versions/replacement/hold branches | At least `hold` and source-backed, permitted alternatives; no invented upgrade, no cross-plugin authority |
| P0-C · `compatibilityForecast.decide` | **Developer-composed autonomous actor** installed through first-party documented registration; receives immutable snapshot, options, policy boundary and budget | Actor actually chooses option from allowed set, or abstains; arbitrary generic hook/listener alone is insufficient |
| P1-D · `systemAgent.proposeApprovedTransition` | Typed, host-owned S3 controller / existing exact-proposal approval lifecycle | Revalidate option, policy, installed version, scope and operator approval; decision actor has **no direct mutation/approval right**; denial/expiry fails closed |
| P0-E · `compatibilityForecast.receiptAndRecheck` | Host-applied config/plugin result + next supported runtime/plugin inspection and actual agent/tool use | Durable source/decision/approval/action/after-state linkage; observed later run returns to composed S4 actor; no receipt solely on emitted recommendation |

**Required construction sufficiency:** all five ports must be reachable in a supported installation (not test-only), bind the external/future disturbance to real present affected resources, permit an independently supplied decision actor to choose among lawful options, preserve S3 and ultimate policy rights, apply a safe change when expressly approved, and return observed downstream behavior into later option selection. If the actor merely generates prose or a host hardcodes every choice, it is not the proposed S4 `C`. Operator `hold` may be a valid terminal decision without changing resources.

**S3 ↔ S4 linkage:** S3 supplies current plugin inventory, constraints and past outcomes; S4 supplies deadline/compatibility alternatives; S3 validates and may hold/approve/apply; a later S1 tool invocation plus refreshed current inventory closes feedback into S4. Parent authorization stays legitimate `P`; no S5 delegation is created.

## Native-first incremental plan (no code authored)

- **P1-1:** validate #179294 demand with maintainers and choose the smallest plugin-first extension rather than embedding a second global updater; dedupe #190536/#200932, honor [VISION](https://github.com/openclaw/openclaw/blob/5cb5f15409575744f6f2f157a5eed8c5bec2071b/VISION.md).
- **P1-2:** add read-only, bounded current-install compatibility manifest and externally sourced release/deprecation facts, documented trust/expiry. Reuse existing notices and Doctor result instead of duplicating monitors.
- **P0-1:** add a distributable function-specific S4 controller registration/action interface (distinct from general `onChange` hooks) with two genuine lawful choices, visible decision owner and explicit schema.
- **P1-3:** implement exact host-review bridge using existing system-agent approval semantics, and future source-native operational re-check; stop if the chosen action is outside existing authorized ops.
- **P0-2:** native integration tests and one actual installed plugin + later-operation demonstration before any claim of delivered C. A successful unit-only mock is insufficient.

## Proposed native acceptance and falsification — NOT EXECUTED

| Case | Stimulus and alternative | Required observable outcome | Falsifies C if |
| --- | --- | --- | --- |
| **AC-01 positive** | Installed fixture plugin with verifiable future retirement; external future update; composed actor chooses supported migration | Approved typed operation; later plugin/agent operation uses migrated surface; durable receipt attributed to this choice and checked against updated inventory | No first-party S4 actor or no actual later run/feedback |
| **AC-02 lawful hold** | Same facts, actor chooses `hold` | No mutation, recorded dated hold/recheck choice; next run revisits after facts change | Hardcoded migration ignores selected hold |
| **AC-03 untrusted signal** | Forged, unauthenticated, stale or contradictory release fact | No authorized migration; explicit unknown/conflict, safe manual review | Untrusted text becomes executable authority |
| **AC-04 denied operation** | Valid recommendation but operator denies or no approval | No effect; receipt records rejection and no false success; later operations unchanged | Model/actor self-approves, or retry bypasses hash |
| **AC-05 compatibility** | Target plugin lacks supported replacement or requires re-auth | Explicit blocked/hold branch and handoff; existing sessions and other plugins continue | Silent install or credential mutation |
| **AC-06 baseline comparison** | Same affected plugin using stock Doctor + manual change | Compare equivalent result, engineering burden and unintended effects | Proposed port duplicates a cheaper native capability |

Test location proposal (not verified present): focused tests adjacent to `src/plugins/sdk-deprecation-notices.test.ts` and host approval tests; add source-native integration case with installed plugin and later agent operation. Native commands per CONTRIBUTING, e.g. `pnpm test <file> --maxWorkers=1`, plus relevant type/lint/build. **None executed.**

## Rights, blockers, stop

MIT license and [CONTRIBUTING](https://github.com/openclaw/openclaw/blob/5cb5f15409575744f6f2f157a5eed8c5bec2071b/CONTRIBUTING.md) permit examining and preparing research. The working fork `opensiro-contributions/openclaw` parent and `opensiro/meta` current `ALLOW` were checked; this does **not** grant external publication or CLA consent. Any code requires a *separate explicit* Upgrade instruction, product branch, native tests, evidence and review. Stop / downgrade to `NEEDS_EVIDENCE` if no legitimate native need beyond date wording, sufficient standard Doctor/manual baseline, unverifiable external facts, unreachable first-party registration/enforcement port, or forbidden scope. Historical Index `S4=—` alone is not the reason to build.

**Handoff back to human:** [issue.md](https://github.com/opensiro-contributions/openclaw/blob/opensiro/meta/.opensiro/issues/s4-compatibility-transition-20261118/issue.md) · [roadmap receipt](https://github.com/opensiro-contributions/openclaw/blob/opensiro/meta/.opensiro/issues/s4-compatibility-transition-20261118/roadmap.md). **P0=S4 candidate / P1=ports / P2=NONE; PLAN_ONLY / DECISION_READY.** AI-assisted design; not independently reviewed or executed.