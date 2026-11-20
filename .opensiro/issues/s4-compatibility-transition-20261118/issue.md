# OpenClaw — prospective plugin compatibility transition (OpenSiro plan-only)

**Target transition:** S4=— -> S4=C
**Proposal-stage decision:** GO
**Research disposition:** NEEDS_EVIDENCE

## Why OpenSiro

OpenSiro maps organizational function ownership and proposes source-native optional constructors. This is a design hypothesis, not a product requirement, performance finding or VSM adoption request.

## Historical accepted six-function baseline

Index [included assessment](https://github.com/opensiro/vsm-harness-index/blob/e8c13c54d30969b72c5f084282e71ba4efd07efb/assessments/op/openclaw.md), reviewed 2026-09-16 at `387da5edaa9d6c6cfcfc15e167fe2e46d8647d86`, blob `e1d560bc5b28d90323b15f5f1af6a5293c614b45`. Current original `main@2aca1a1c1595e25d3cdb0bc7ce098bdcc92efb87` read separately. Grades below are historical and are **not** current regrades.

| Function | Accepted historical state | Current review scope |
| --- | --- | --- |
| **S1 · Operations** | A | Configured assistants perform user operations; no duplicate C |
| **S2 · Coordination** | C | Session messaging and lifecycle; no new target |
| **S3 · Current control** | C(P) | Host-owned exact approval, plugin/config/agent control reused as an enforcement path |
| **S3* · Complementary audit** | — | Doctor/telemetry are not automatically independent audit; other cases separate |
| **S4 · Future/external intelligence** | — | Prospective SDK/vendor plugin transition: optional **C construction** proposed only |
| **S5 · Ultimate policy** | — | Plugin approval is not identity or ultimate-policy closure |

Index was last reviewed 65 calendar days earlier; a fresh Index assessment is recommended but not performed. No new ownership grade is asserted.

## Operator problem and bounded suggestion

When an **official future plugin API/endpoint retirement** threatens a *currently installed plugin*, the user may want a plan before it fails. Today [Doctor](https://github.com/openclaw/openclaw/blob/2aca1a1c1595e25d3cdb0bc7ce098bdcc92efb87/src/cli/plugins-cli.runtime.ts), [SDK compatibility notices](https://github.com/openclaw/openclaw/blob/2aca1a1c1595e25d3cdb0bc7ce098bdcc92efb87/src/plugins/sdk-deprecation-notices.ts), status and the normal updater inform manual repairs. Existing [#131897](https://github.com/openclaw/openclaw/issues/131897) and [RFC #66](https://github.com/openclaw/rfcs/pull/66) concern version availability; [#159743](https://github.com/openclaw/openclaw/issues/159743) discusses subsequent observations. Do not duplicate these or the [#190536](https://github.com/openclaw/openclaw/issues/190536) warning fix.

An optional, first-party **plugin-specific future compatibility review** could connect a dated official announcement to local installed plugin/SDK metadata, let a host-scoped agent choose **hold, propose approved update/replacement, or escalate**, and confirm by a subsequent actual plugin invocation. The minimal new native seam is trusted typed future-notice matching and a correlated post-action result on existing `src/plugins/status.ts` / `src/agents/tools/system-agent-tool.ts`. Actual mutation remains exact operator-approved. This is not an autonomous plugin updater, generic controller or new safety policy.

**Current decision: GO / NEEDS_EVIDENCE at architectural proposal stage.** Nothing is implemented, tested or externally published. Maintainers retain product decision rights. The same case's earlier [2026-11-19 NO_GO receipt](https://github.com/opensiro-contributions/openclaw/blob/27524e961d4bf2243197aa536441cba10718730b/.opensiro/issues/s4-compatibility-transition-20261118/roadmap.md) was assessed under an earlier criterion; it remains historically valid and is **not** erased. The new proposal is limited to whether a complete S4=C path could be constructed, not whether OpenClaw should ship it.

## What could falsify it

If native current functionality already provides a developer-composable future-notice → lawful decision → later real operation feedback loop, no additional C constructor is needed. Invalid or outdated external announcements, unverified installed plugin/version, denied host permission and no observed later plugin operation must produce hold/unknown or failure, **never** an automatic update or success claim. A simple first-party fix for the Atlassian endpoint [#200928](https://github.com/openclaw/openclaw/issues/200928) is preferable for that specific problem.

## Next permitted decision

Optionally collect a concrete installed-plugin scenario and native acceptance evidence; compare manual Doctor/updater with the proposed smallest extension. Costs `NOT_MEASURED`, tests `NOT_RUN`. This is research `PLAN_ONLY`; no public fork/original Issue or PR, no index grade and no product code changed. Publication would require its own specific approval.

[constructor-sufficiency.md](constructor-sufficiency.md) · [roadmap.md](roadmap.md) · [case README](README.md). Prepared with AI assistance.