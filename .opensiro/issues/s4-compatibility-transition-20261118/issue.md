# OpenClaw — source-native S4 compatibility-transition roadmap

**OpenSiro pilot · PLAN_ONLY / DECISION_READY · DRAFT — NOT PUBLISHED**  
**Two-level case:** Human issue (this document) + [AI/developer constructor contract](https://github.com/opensiro-contributions/openclaw/blob/opensiro/meta/.opensiro/issues/s4-compatibility-transition-20261118/constructor-sufficiency.md).  
**Original:** https://github.com/openclaw/openclaw · **Working fork:** https://github.com/opensiro-contributions/openclaw · **Case:** [fork-local record](https://github.com/opensiro-contributions/openclaw/blob/opensiro/meta/.opensiro/issues/s4-compatibility-transition-20261118/README.md).

## 1. Why OpenSiro and central accepted VSM assessment

OpenSiro tests whether reusable VSM-informed organizational specifications and source-native integrations can standardize AI-agent harness development and lower implementation, integration, review and maintenance cost. That saving is **NOT_MEASURED**; OpenClaw maintainers need not adopt VSM. The object is a smaller, testable user capability than a new six-system architecture.

**CENTRAL HISTORICAL STARTING POINT — ACCEPTED INDEX, NOT CURRENT HEAD OR TARGET:**  
**S1=A · S2=C · S3=C(P) · S3*=— · S4=— · S5=—**.  
Accepted [Index assessment](https://github.com/opensiro/vsm-harness-index/blob/5f6ea0c777733813ca42e3f210390a719488dcfb/assessments/op/openclaw.md), blob §e1d560bc5b28d90323b15f5f1af6a5293c614b45§, reviewed 2026-09-16 at source §387da5edaa9d6c6cfcfc15e167fe2e46d8647d86§; Profile 0.2.1 / assessment procedure 0.3.1.

| Function | Accepted grade | Consequence for this proposed roadmap |
| --- | --- | --- |
| S1 · Operations | A | Agent performs work; no mandated constructor |
| S2 · Coordination | C | Session coordination already composable; no mandated change |
| S3 · Current control | C(P) | Parent-approved setup/config operations exist; preserve their authority |
| S3* · Complementary audit | — | Not addressed; ordinary telemetry is not independent audit |
| **S4 · Outside-and-then intelligence** | **—** | Test an independently composable future-compatibility planning/return loop |
| S5 · Ultimate policy | — | Human/operator authority stays reserved; approvals are not an S5 grade |

**Pins and boundary:** original source [main at 5cb5f15409575744f6f2f157a5eed8c5bec2071b](https://github.com/openclaw/openclaw/commit/5cb5f15409575744f6f2f157a5eed8c5bec2071b), observed 2026-11-18; system-in-focus is the first-party Gateway, installed-plugin metadata/Doctor and operator-approved system-agent control surface. External vendor release notices, provider models, downloaded plugins, maintainers and operator governance are **outside** the assessed runtime. The accepted review is **63 days old**: recommend a separate Index-owned pinned re-assessment (not a blocker), especially before claiming a current S4 grade. No pending reassessment was established by this case.

**Rights:** MIT [LICENSE](https://github.com/openclaw/openclaw/blob/5cb5f15409575744f6f2f157a5eed8c5bec2071b/LICENSE). Contribution instructions: [CONTRIBUTING](https://github.com/openclaw/openclaw/blob/5cb5f15409575744f6f2f157a5eed8c5bec2071b/CONTRIBUTING.md) (AI-assisted PRs welcomed, focused native work/tests), [VISION](https://github.com/openclaw/openclaw/blob/5cb5f15409575744f6f2f157a5eed8c5bec2071b/VISION.md) (prefer optional plugins and stable policies). Fork parent verified as openclaw/openclaw, §opensiro/meta§ owner control was §ALLOW§ and attention §ACTIVE§ at intake. This approval is **not** public-Issue consent.

## 2. Proposed user capability and decision

**P0 — S4/C design candidate:** a self-hosting operator runs enabled plugins that use APIs or endpoints with announced future retirement. A developer should be able to compose a *bounded, autonomous prospective-adaptation decision actor* to compare (a) a compatible upgrade/migration, (b) defer/hold with a dated risk, or (c) a permitted partial disable/replacement, against a **redacted current install manifest**. The actor selects and records a supported option using a first-party S4-specific port; S3's existing exact user approval still gates any durable setup/config mutation. A verified approved change must be observable in a later supported tool/agent/plugin operation. **Proposed, not shipped.**

**Native counterfactual:** use §openclaw plugins doctor§ and normal status/Doctor warnings plus human reading of release notes and manual change through the approved system agent. Prefer this simpler solution if it provides equivalent prospective comparison and user outcome at lower cost. Do not equate warning formatting or a scheduled update check with S4.

**P2:** NONE. No independent S3*, S5 or extra autonomous manager has been justified.

## 3. Existing native work and exact residual question

| Status | Source-native evidence | Residual / overlap |
| --- | --- | --- |
| **SHIPPED** | [SDK deprecation notices](https://github.com/openclaw/openclaw/blob/5cb5f15409575744f6f2f157a5eed8c5bec2071b/src/plugins/sdk-deprecation-notices.ts), [plugin status](https://github.com/openclaw/openclaw/blob/5cb5f15409575744f6f2f157a5eed8c5bec2071b/src/plugins/status.ts) | Detect/report a date; no demonstrated actor-owned future alternatives matched to the real install and later outcome |
| **SHIPPED** | [system-agent typed mutation path](https://github.com/openclaw/openclaw/blob/5cb5f15409575744f6f2f157a5eed8c5bec2071b/src/agents/tools/system-agent-tool.ts), [host approval](https://github.com/openclaw/openclaw/blob/5cb5f15409575744f6f2f157a5eed8c5bec2071b/src/system-agent/approval-intent.ts) | Current S3 approval/control, not prospective independent S4 selection |
| **OPEN ISSUE + OPEN PR** | [#190536](https://github.com/openclaw/openclaw/issues/190536), [PR #200932](https://github.com/openclaw/openclaw/pull/200932) at §e1f94d4b85d4ee65dd24b45a036fb47018a2fcd0§ | Wording/date clarity; **not** an S4 constructor; avoid duplicate change |
| **CLOSED_UNMERGED PR** | [PR #190752](https://github.com/openclaw/openclaw/pull/190752) at §71395005fe9fa5d9e3f6a2e19110e15b228445eb§ | Alternate warning implementation, not shipped |
| **CLOSED ISSUE — not a shipped feature** | [#179294](https://github.com/openclaw/openclaw/issues/179294) proposes installation manifest × release changes impact report | Closest simpler original-native alternative; requires fresh maintainer interest rather than new duplicate issue |
| **OPEN ISSUE / external disturbance** | [#200928](https://github.com/openclaw/openclaw/issues/200928): a plugin's Atlassian endpoint has a dated removal notice | Concrete future-impact scenario; third-party plugin is not first-party closure |

**Remaining proof question:** can a first-party, limited plugin-SDK/host bridge provide (1) trustworthy dated external changes; (2) a redacted install/option snapshot; (3) developer-composed decision ownership; (4) typed S3 review/enforcement; and (5) a later operational receipt? None of those five is established by an issue or generic hook alone. [Detailed code, ownership and tests](https://github.com/opensiro-contributions/openclaw/blob/opensiro/meta/.opensiro/issues/s4-compatibility-transition-20261118/constructor-sufficiency.md).

## 4. Priority and minimum sufficient outcome

| Priority | Native outcome | Sufficient complete path |
| --- | --- | --- |
| **P0 · S4** | Composed controller chooses a lawful prospective response for one affected installed plugin | Dated external fact → actual installed-impact distinction → at least two lawful options/§hold§ → composed actor decision → approved typed S3 action → durable receipt → later plugin availability/compatibility feedback |
| **P1 · prerequisites** | Safe, reusable bridge | Bound provider authenticity/freshness, redacted installed snapshot, option schema, installer/doctor reachability, host approval and no side-effect-on-preview, tests. Implement only if native baseline demonstrably insufficient |
| **P2 · optional** | NONE | Preserve parent controls; no mandatory autonomous S3/S5 or new audit function |

**C sufficiency:** the full proposed first-party vertical slice, with externally composable S4 decision actor and later-operation witness, would be *eligible for subsequent source-based reassessment*, not automatic §C§. Implementation readiness requires independently verified API and permission compatibility; this is a decision-ready plan, not a validated patch.

## 5. Proposed acceptance and stop conditions

- **AC-01 positive prospective case (NOT EXECUTED):** install a fixture plugin whose SDK/API migration has a future removal date; provide a signed/approved bounded replacement fact; composed S4 actor selects a permitted migration; host obtains exact operator approval; config/plugin transition is applied; subsequent first-party plugin inspection and a real tool operation confirm the selected path and a receipt.
- **AC-02 different lawful choice (NOT EXECUTED):** same facts, actor chooses §hold§; no mutation occurs, durable dated decision/risk is visible on the next run.
- **AC-03 negative authority/stale evidence (NOT EXECUTED):** unapproved actor proposal, fake/mismatched vendor fact, unsupported replacement, unauthorized scope or stale plan does not mutate state; approval cannot be self-granted by an LLM.
- **AC-04 minimal-native alternative (NOT EXECUTED):** compare these user tasks with stock Doctor/CLI/manual change; if they give the same outcome cheaply, prefer §NO_USEFUL_CHANGE§.
- **Stop:** no real operator need beyond wording PR #200932, no safe install manifest, no first-party composability port, or policy mismatch → §NEEDS_EVIDENCE§ / no implementation. Do not imply S3*, S5 or a grade change.

## 6. Independent follow-ups

1. Product-native: ask maintainers whether [closed #179294](https://github.com/openclaw/openclaw/issues/179294) should be revived, and whether a minimal plugin-first planning interface has real demand, **without posting yet**.
2. Profile/Skills: submit a separately evidenced methodological counterexample only if needed.
3. A legally allowed domain fork could measure the approach without upstream adoption.

## 7. Matched cost hypothesis

Same fixture, two paths: stock Doctor + manually reviewed migration versus proposed composable S4 actor + operator approval. Measure completed task correctness, person-minutes for development/integration/review/tests, regression maintenance, number of unsafe/unneeded mutations and later-run success. **Cost: NOT_MEASURED**; no demonstrated saving.

## 8. Decision / handoff

**DECISION_READY for a narrow plan-only study; NOT implementation-ready without original-native port/need verification.** The remaining gap is a prospective **S4** actor-and-return mechanism, not a missing warning, patch quota, or forced VSM adoption. Preserve #200932's open decision and avoid duplicate maintainer work.

Full companion: [AI/developer constructor contract](https://github.com/opensiro-contributions/openclaw/blob/opensiro/meta/.opensiro/issues/s4-compatibility-transition-20261118/constructor-sufficiency.md). Case receipt: [roadmap](https://github.com/opensiro-contributions/openclaw/blob/opensiro/meta/.opensiro/issues/s4-compatibility-transition-20261118/roadmap.md).

**PUBLIC FORK ISSUE: NOT PUBLISHED. EXTERNAL ORIGINAL ISSUE/COMMENT/PR: DRAFT — NOT PUBLISHED.** This entire text is a proposed fork-local Issue body; the exact destination is https://github.com/opensiro-contributions/openclaw/issues. Current-conversation approval of its title and full body is required before issue creation. No code changes, native test run, CLA action or independent human technical review was performed. **AI disclosure:** prepared with AI assistance.