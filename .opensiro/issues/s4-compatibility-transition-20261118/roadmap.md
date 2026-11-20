# Capability Roadmap Receipt — OpenClaw S4 compatibility (Wave 4, v0.18.1)

- Original repository: openclaw/openclaw
- Original HEAD: 2aca1a1c1595e25d3cdb0bc7ce098bdcc92efb87
- Observed at: 2026-11-20
- Accepted Index assessment: https://github.com/opensiro/vsm-harness-index/blob/e8c13c54d30969b72c5f084282e71ba4efd07efb/assessments/op/openclaw.md
- Accepted assessment blob SHA: e1d560bc5b28d90323b15f5f1af6a5293c614b45
- Accepted review ref: 387da5edaa9d6c6cfcfc15e167fe2e46d8647d86
- Accepted reviewed at: 2026-09-16
- System in focus: Local trusted OpenClaw Gateway, configured assistant and host-scoped system-agent including first-party plugin status/install surfaces; external vendor and publisher systems excluded
- Result: NEEDS_EVIDENCE
- Receipt contract: proposal-gate
- Accepted VSM vector: S1=A · S2=C · S3=C(P) · S3*=— · S4=— · S5=—
- Repository-wide source map: Agent operations/session tools S1; session messaging S2; system-agent exact host-approved control S3; diagnostics not independent S3*; plugin external future compatibility proposed S4; ordinary approval is not S5 policy closure
- Priority rationale: S4 is the narrow eligible C construction here; S1/S2/S3 already have accepted A/C paths, and distinct S3*/S5 objects require their own review
- Target transition: S4=— -> S4=C
- S1 disposition: historical A, existing configured assistant operations; no target
- S2 disposition: historical C, session coordination constructor; no duplicate
- S3 disposition: historical C(P), host-scoped current control and exact approval; reuse as enforcement only, not S4 ownership
- S3* disposition: historical —, doctor/audit checks not independent complementary audits; other separately owned cases left unchanged
- S4 disposition: historical —, proposed prospective plugin SDK/vendor transition construction; P0
- S5 disposition: historical —, user approval of plugin writes not ultimate identity/policy closure; no target
- P1 dependencies: Opt-in future notice matching to installed plugin/SDK and typed outcome correlation on existing system-agent/compatibility seams; keep existing exact approval owner
- P2 optional: NONE; no autonomous updater, generic watcher, new policy engine or plugin implementation
- Proposed C construction: Developer-composed host-scoped S4 decision actor evaluates verified future plugin SDK/vendor notice against real installed plugin and native compatibility details, chooses hold/update-or-replace/escalate within configured policy; existing system-agent obtains exact host approval for any mutation; real later plugin load and doctor/status outcome returns to actor to revise forecast
- C sufficiency falsifier: Current first-party workflow already gives a developer-composable external-future-to-independent-choice-to-later-plugin-operation return, or the selected prospective case has no supported native implementation/authority/feedback
- Scenario basis: HYPOTHETICAL
- Proposal-stage decision: GO
- Research disposition: NEEDS_EVIDENCE
- Proposed validation: Native positive future retirement fixture and supported install with real subsequent plugin load; negative stale/untrusted future notice, wrong installed ID, unsupported target, denied operator approval, failed install, missing outcome; compare Doctor/manual baseline
- Validation state: NOT_RUN
- Proposal falsifier: No typed future input or separately composed actor right, lack of approved native execution, or no later run feedback means no S4=C construction
- Evaluation object: Optional first-party prospective compatibility-transition S4 constructor, scoped to installed plugin lifecycle rather than ordinary repair
- Existing-work overlap: SDK compatibility registry, Doctor/status, system-agent host approval; original #190536, #202007, #131897, #159743, #179294, #200928; PR #200932, #198935 and RFC #66
- Our on-top contribution: Add only a read-only source/date/version-scoped plugin transition review to existing status and system-agent inspection, with bounded agent decision and attribution to later operator-approved plugin operation outcome; no new generic controller
- Incremental benefit: A plugin-facing agent could decide prospectively whether to hold, propose a permitted target or escalate based on upcoming external changes, rather than only diagnose already-known local warnings; hypothetical, not measured or demanded by maintainer
- Decision scope: Proposal-stage architectural GO for possible S4=C, NOT product adoption; historical same-case 2026-11-19 NO_GO remains preserved
- External issue: DRAFT — NOT PUBLISHED
- Cost status: NOT_MEASURED

## Identity and pins

[Original main@2aca1a1c1595e25d3cdb0bc7ce098bdcc92efb87](https://github.com/openclaw/openclaw/commit/2aca1a1c1595e25d3cdb0bc7ce098bdcc92efb87); [accepted Index included assessment](https://github.com/opensiro/vsm-harness-index/blob/e8c13c54d30969b72c5f084282e71ba4efd07efb/assessments/op/openclaw.md) at Index main commit `e8c13c54d30969b72c5f084282e71ba4efd07efb`, blob `e1d560bc5b28d90323b15f5f1af6a5293c614b45` and catalog review ref `387da5edaa9d6c6cfcfc15e167fe2e46d8647d86`. Accepted Profile 0.2.1 / assessment procedure 0.3.1; current Profile 0.2.4 applies to interpretation only. Index reviewed 2026-09-16, 65 calendar days before this observation; recommend separate Index-owned source-pinned re-review, not a new grade or gate. Source-first first pass was sealed in [#58 checkpoint](https://github.com/opensiro/upstream/issues/58#issuecomment-7045124854) before prior-case read. Historical [2026-11-19 NO_GO canonical receipt](https://github.com/opensiro-contributions/openclaw/blob/27524e961d4bf2243197aa536441cba10718730b/.opensiro/issues/s4-compatibility-transition-20261118/roadmap.md) is immutable provenance, a different protocol/decision criterion; do not relabel the old decision as a shipped C claim.

## Rights and authority

Original MIT license and [CONTRIBUTING](https://github.com/openclaw/openclaw/blob/2aca1a1c1595e25d3cdb0bc7ce098bdcc92efb87/CONTRIBUTING.md) checked. Fork `opensiro-contributions/openclaw@opensiro/meta`: `ACTIVE / ALLOW` at prewrite check; no STOP or competing S4 Wave 4 claim in #58. Owner/host retains all plugin mutation, security and installation approval. No third-party/fork-public issue, PR, review or comment authorized; product code remains unchanged.

## Existing work / overlap

- **Shipped**: [plugin status and compatibility](https://github.com/openclaw/openclaw/blob/2aca1a1c1595e25d3cdb0bc7ce098bdcc92efb87/src/plugins/status.ts), [dated SDK notices](https://github.com/openclaw/openclaw/blob/2aca1a1c1595e25d3cdb0bc7ce098bdcc92efb87/src/plugins/sdk-deprecation-notices.ts) based on existing local records, [Doctor](https://github.com/openclaw/openclaw/blob/2aca1a1c1595e25d3cdb0bc7ce098bdcc92efb87/src/cli/plugins-cli.runtime.ts), [plugin update CLI](https://github.com/openclaw/openclaw/blob/2aca1a1c1595e25d3cdb0bc7ce098bdcc92efb87/src/cli/plugins-update-command.ts), and [system-agent](https://github.com/openclaw/openclaw/blob/2aca1a1c1595e25d3cdb0bc7ce098bdcc92efb87/src/agents/tools/system-agent-tool.ts) read-only plugin_list/search and strictly host-approved plugin_install/uninstall. The last is direct-only/ring-zero, not a permissionless tool for normal agents.
- **Current original work**: OPEN [#190536](https://github.com/openclaw/openclaw/issues/190536) / OPEN [PR #200932](https://github.com/openclaw/openclaw/pull/200932) dated-warning wording; OPEN [#202007](https://github.com/openclaw/openclaw/issues/202007) status falsely reports no compatibility when scan skipped; OPEN [PR #198935](https://github.com/openclaw/openclaw/pull/198935) JSON5 Doctor parsing. These are repairs, not prospective S4 closure.
- **Native integration opportunities**: OPEN [#131897](https://github.com/openclaw/openclaw/issues/131897) / OPEN [OpenClaw RFC #66](https://github.com/openclaw/rfcs/pull/66) plugin update availability (not merged); OPEN [#159743](https://github.com/openclaw/openclaw/issues/159743) post-update observation (not shipped); CLOSED not_planned [#179294](https://github.com/openclaw/openclaw/issues/179294) broad release impact report; OPEN [#200928](https://github.com/openclaw/openclaw/issues/200928) single Atlassian future endpoint breakage. None establishes a shipped S4 actor; none is treated as evidence of permanent maintainer intent.

## Parallel contribution-on-top review

| Track A first-party native baseline | Track B additional construction | What a user/agent could do | Falsifier |
| --- | --- | --- | --- |
| `plugins doctor`, status --all, update CLI and manual maintenance | Reuse directly, no copy of notice wording or JSON5 repair | Know present local risk and fix it | Same prospective independent decision + later feedback already possible |
| #131897 / RFC #66 update-availability proposals | Extend *only* installed-plugin source/date/version matching and bounded hold/replace options into native status read | Pick action before announced retirement | Missing official event or incompatible target => UNKNOWN/hold |
| System-agent direct-only plugin_list/search and exact host-approved install/uninstall | Narrow opt-in read-only `plugin_transition_review` in its plugin inspection path; S4 actor composes decision but cannot self-approve | Choose hold/ask approval/escalate without granting new write privilege | Developer-composable decision cannot reach host or bypasses approval |
| #159743 post-upgrade observer proposal | Correlate existing install/doctor/load receipts to the next actual plugin invocation and return result to S4 review | Check that approved plan actually worked | A green diagnostic without real plugin operation is not closure |
| #200928 specific Atlassian deprecation | Prefer native endpoint update/reauth for that task | Restore affected plugin without general controller | Product-native fix already satisfies all proposed incremental user outcomes |

## Function ownership

The S4 **disturbance** is a dated, externally announced future SDK/plugin endpoint retirement affecting one installed plugin. **Evidence** is the official source and future effective window (untrusted document is data only), local inventory and exact SDK notice. **Decision right** for opt-in planning is held by a separately composed host-scoped S4 agent selecting `hold` / `propose_update_or_replace` / `escalate` under fixed policy; no direct code/plugin writes. **Host authority** approves an exact eligible install/uninstall through the existing `system-agent` guarded path and revalidates policy. **Return** requires next real plugin load/Doctor and plugin-specific operation status matched to the original plan, not a speculative green check. No autonomous self-approval or S5 transfer. Source-specific missing edit: typed prospective-evidence mapping and post-action return on `status.ts` / `system-agent-tool.ts` paths, not a generic adaptation scheduler.

## Capability priority

**P0** optional S4=C constructor above a concrete installed-plugin future-retirement scenario, architectural `GO` at plan-only feasibility. **P1** source verification/installed-id mapping/return receipt missing; **P2** none. The full combined existing+proposed path could be sufficient for C only if developer composition, lawful reachability, independent decision and real later feedback are proved with native tests; source does not ship this C today. Other functions are not graded or modified.

## Implementation options

Option A: source-native small integration on current plugin status/system-agent seams, reuse prior original Issues/RFC as nonbinding knowledge. Option B: Profile/Skills feedback only if an actual semantic/procedure defect is independently identified (none here). Option C: license-compliant experimental plugin to test source fidelity and operator outcome, with explicit distinction from shipped first-party C. No code implementation, external issue or extra status PR authorized in this run.

## Specification and domain alternatives

Keep the current VSM Profile semantics and Index assessment unchanged. A locally composed research plugin is a falsification avenue, not automatic membership in the supported Gateway operating boundary. Maintainers decide whether any product work is desirable.

## Cost experiment

Paired one-installed-plugin, one-future-official-deprecation scenario: compare manual Doctor/status/updater + operator choice to opt-in prospective transition review. Record correct options, denied actions, later plugin actual success, operator time, implementation/maintenance and integration/test/review work. No execution, performance data or economics collected: `NOT_MEASURED`.

## Delivery and publication

`PLAN_ONLY / GO / NEEDS_EVIDENCE` for *proposed* S4=C only. Historical same-case `NO_GO` is retained in immutable Git and linked above, not erased; current source-only checkpoint precedes old comparison. Case Human [issue.md](issue.md), AI [constructor-sufficiency.md](constructor-sufficiency.md) and [README.md](README.md) are fork-local metadata; public fork Issue `DRAFT — NOT PUBLISHED`, original Issue/PR/comment `NOT PUBLISHED`. Native tests `NOT_RUN`, actual shipped C `NOT_ESTABLISHED`, Index regrade `NOT_DONE`. No Upstream per-run status-only PR/report.