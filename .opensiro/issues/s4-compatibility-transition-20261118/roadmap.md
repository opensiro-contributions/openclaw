# Capability Roadmap Receipt — OpenClaw S4 compatibility rerun

- Original repository: openclaw/openclaw
- Original HEAD: 307d9c45fb2548d300276c473ccb7c5cab4768bc
- Observed at: 2026-11-19
- Accepted Index assessment: https://github.com/opensiro/vsm-harness-index/blob/394ce776e6945115891b8f7cc459f5a7f7d7aa39/assessments/op/openclaw.md
- Accepted assessment blob SHA: e1d560bc5b28d90323b15f5f1af6a5293c614b45
- Accepted review ref: 387da5edaa9d6c6cfcfc15e167fe2e46d8647d86
- Accepted reviewed at: 2026-09-16
- System in focus: First-party OpenClaw Gateway, plugin SDK/status/Doctor/update and host-approved S3 control; external vendors, outside plugins and operator organization excluded
- Result: NEEDS_EVIDENCE
- Receipt contract: contribution-on-top
- Evaluation object: Additional first-party developer-composable autonomous S4 plugin compatibility transition controller above native status, update and approval
- Existing-work overlap: Shipped SDK notices; open #190536 and PR #200932; open #131897 and RFC #66; open #159743; closed not_planned #179294; open #200928; closed unmerged PR #164501
- Our on-top contribution: Conditionally extend the existing plugin availability RFC with read-only installed impact, verified update candidate and hold option; reject a speculative autonomous S4 controller and duplicate notice wording
- Incremental benefit: An installed-plugin read-only preview might save manual correlation; no supported S4 actor/return path or matched benefit beyond native Doctor and dry-run is evidenced
- Decision scope: Terminal NO_GO NOW for the bounded new autonomous S4 controller, not for the entire original or native bug fixes
- External issue: DRAFT — NOT PUBLISHED
- Cost status: NOT_MEASURED

## Identity and pins

Accepted [Index](https://github.com/opensiro/vsm-harness-index/blob/394ce776e6945115891b8f7cc459f5a7f7d7aa39/assessments/op/openclaw.md) at Index main **394ce776e6945115891b8f7cc459f5a7f7d7aa39** and included catalog matched the exact original/review ref; accepted blob as above, Profile **0.2.1** and procedure **0.3.1**. Historical **S1=A, S2=C, S3=C(P), S3*=—, S4=—, S5=—**. Review is **64 days old**, so source-pinned Index re-review is recommended separately. Current source [307d9c4](https://github.com/openclaw/openclaw/commit/307d9c45fb2548d300276c473ccb7c5cab4768bc) observed 2026-11-19. Original 2026-11-18 design-only **DECISION_READY** remains preserved in Git history, not retroactively labeled a verdict.

## Rights and authority

Original MIT and [CONTRIBUTING](https://github.com/openclaw/openclaw/blob/307d9c45fb2548d300276c473ccb7c5cab4768bc/CONTRIBUTING.md) prefer issue/RFC first for new architecture. Verified fork **opensiro-contributions/openclaw** parent original with metadata **opensiro/meta**; owner control **ALLOW / ACTIVE** read on 2026-11-19. No public fork Issue or original publication authorized; no product implementation from plan-only.

## Existing work / overlap

SHIPPED [SDK notice](https://github.com/openclaw/openclaw/blob/307d9c45fb2548d300276c473ccb7c5cab4768bc/src/plugins/sdk-deprecation-notices.ts), [status](https://github.com/openclaw/openclaw/blob/307d9c45fb2548d300276c473ccb7c5cab4768bc/src/plugins/status.ts), [plugin update](https://github.com/openclaw/openclaw/blob/307d9c45fb2548d300276c473ccb7c5cab4768bc/src/cli/plugins-update-command.ts), and host approval. OPEN [#190536](https://github.com/openclaw/openclaw/issues/190536), OPEN [PR #200932](https://github.com/openclaw/openclaw/pull/200932) head **e1f94d4b85d4ee65dd24b45a036fb47018a2fcd0**, actual diff notice wording only. OPEN [#131897](https://github.com/openclaw/openclaw/issues/131897), OPEN [RFC #66](https://github.com/openclaw/rfcs/pull/66) head **eb7d01d73d9555d1280b1ac5cae9d0c8b28d8607** concern plugin update availability. OPEN [#159743](https://github.com/openclaw/openclaw/issues/159743) concerns later post-upgrade observation. CLOSED_not_planned [#179294](https://github.com/openclaw/openclaw/issues/179294) is administrative, unshipped. OPEN [#200928](https://github.com/openclaw/openclaw/issues/200928) is a concrete future vendor endpoint. CLOSED_UNMERGED [#190752](https://github.com/openclaw/openclaw/pull/190752) and [#164501](https://github.com/openclaw/openclaw/pull/164501) are not shipped.

## Parallel contribution-on-top review

| Existing → covered (Track A) | Our on-top change (Track B) | Incremental user outcome | Falsifier / disposition |
| --- | --- | --- | --- |
| Shipped SDK notice + open #200932 → warning/date words | Reuse unchanged | Date warning preserved | Already native; no extra S4 |
| Open #131897/RFC #66 → proposed availability read surface | Conditional read-only local installed-impact + dated compatibility + update-or-hold projection | One view rather than manual join | Native Doctor/dry-run sufficient, missing trusted facts or owner decline; **NOT_EVIDENCED for S4 C** |
| Open #159743 → proposed later-run observer | Reuse only after accepted and shipped | Subsequent plugin-result evidence | No settled owner/API or first-party S4 actor |
| Closed #179294 → unshipped large release impact | Plugin-only subset, not global planner | Possible bounded impact preview | Unsupported metadata/maintainer scope; no broad GO |
| Open #200928 → future Atlassian plugin endpoint defect | Issue-native endpoint repair + reauth help | Specific plugin continues working | A simple plugin fix closes the user task |
| Shipped S3 exact approval → controlled current mutation | Hypothetical S4 actor plus trusted future facts/selection/return | Autonomous update/hold and later outcome | No actor port/feedback/cost evidence; **NO_GO for this controller** |

An original Issue/PR is a reuse starting point, not automatic veto or claimed shipped function. Independent ideas B were challenged against the exact same user task and lowest-cost baseline.

## Function ownership

Historically **S1=A and S2=C** need no mandatory new C; **S3=C(P)** retains host/operator approval; S3* and S5 are out of scope. Historical **S4=—** is a research lead only. For a qualified later C constructor: dated authenticated external fact → actual installed affected resources → lawfully supported options including hold → independently developer-composable first-party S4 deciding actor → typed S3 host approval → durable after-state plus next actual plugin/tool operation returned to S4. Neither current first-party completeness nor benefit is established; no present grade changed.

## Capability priority

**P0: NONE QUALIFIED NOW** for autonomous S4 controller. **P1: CONDITIONAL original-native read-only plugin impact/hold preview** on #131897/RFC #66 if demand, first-party ownership, trusted metadata and baseline delta are independently established; this is not S4 C. **P2: NONE.** Full conditional [AI contract](https://github.com/opensiro-contributions/openclaw/blob/opensiro/meta/.opensiro/issues/s4-compatibility-transition-20261118/constructor-sufficiency.md) includes positive, negative, hold, denied approval, compatibility and native baseline acceptance. Not executed.

## Implementation options

Now use native Doctor/status/update dry-run and existing original issue/PR work, including plugin-specific #200928. If later qualified, propose the smallest metadata-only preview under #131897/RFC #66; never add broad controller just to fill a historical grade. Actual implementation would require separate explicit Upgrade, current source pin, native tests/rights and material-delta check. No code changed or native test run.

## Specification and domain alternatives

Original-native limited integration, separately evidenced Profile/Skills methodology improvement, and legally permitted opt-in plugin experiments are distinct paths. The latter cannot establish a shipped first-party C or imply original adoption.

## Cost experiment

Same affected plugin: baseline Doctor/inspect/dry-run + manual migration versus a potential read-only preview; measure correctness, operator minutes, engineering/review/test/maintenance cost, false-safe suggestions and later real plugin use. **NOT_MEASURED**.

## Delivery and publication

**New terminal NO_GO on 2026-11-19** for the exact new autonomous S4 migration controller after both tracks. Research disposition **NEEDS_EVIDENCE** is closed for this invocation, not an interim checkpoint. Historical design state **DECISION_READY** is retained as prior provenance. **Next lawful choice:** current native workflow, and reconsider separately upon concrete installation + RFC owner scope + supported actor/benefit evidence; not an automatic code/publication/Index change.

[Human draft](https://github.com/opensiro-contributions/openclaw/blob/opensiro/meta/.opensiro/issues/s4-compatibility-transition-20261118/issue.md) · [AI developer contract](https://github.com/opensiro-contributions/openclaw/blob/opensiro/meta/.opensiro/issues/s4-compatibility-transition-20261118/constructor-sufficiency.md) · [case README](https://github.com/opensiro-contributions/openclaw/blob/opensiro/meta/.opensiro/issues/s4-compatibility-transition-20261118/README.md). Fork public Issue **NOT PUBLISHED** (draft exact title/body in issue.md); original Issue/comment/PR **DRAFT — NOT PUBLISHED**. No native tests, no contribution record, no cost claim or assessment regrade.