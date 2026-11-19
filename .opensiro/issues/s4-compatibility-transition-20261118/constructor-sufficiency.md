# OpenClaw — S4 compatibility: AI/developer on-top and sufficiency contract

**2026-11-19 · PLAN_ONLY · terminal NO_GO** for an additional first-party developer-composable autonomous S4 compatibility-transition controller; current research label NEEDS_EVIDENCE. [Human decision](https://github.com/opensiro-contributions/openclaw/blob/opensiro/meta/.opensiro/issues/s4-compatibility-transition-20261118/issue.md) is the single proposed public Issue, not this technical companion.

## System, assessment, functional boundary

Original [openclaw/openclaw@307d9c45fb2548d300276c473ccb7c5cab4768bc](https://github.com/openclaw/openclaw/commit/307d9c45fb2548d300276c473ccb7c5cab4768bc), observed 2026-11-19. Accepted [Index](https://github.com/opensiro/vsm-harness-index/blob/394ce776e6945115891b8f7cc459f5a7f7d7aa39/assessments/op/openclaw.md), blob **e1d560bc5b28d90323b15f5f1af6a5293c614b45**, reviewed **2026-09-16**, review source **387da5edaa9d6c6cfcfc15e167fe2e46d8647d86**, Profile 0.2.1, procedure 0.3.1, matching included catalog on Index **394ce776e6945115891b8f7cc459f5a7f7d7aa39**. Historical accepted **S1=A / S2=C / S3=C(P) / S3*=— / S4=— / S5=—**, not new current grades; 64 days old, recommend separate Index reassessment.

First-party in scope: Gateway, installed plugin metadata, SDK notices/status, plugin update commands/Doctor, system-agent exact host approval. Vendors, ClawHub third-party plugins and human operator organization remain outside. S1/S2/S3 have no mandatory duplicate C engineering. S3* and S5 are out of scope. S4 outside-and-then must use an external future distinction and return to an actual operation; a current warning, generic hook or host approval alone is not that function.

**Operator counterfactual:** can an OpenClaw operator respond to an upcoming API retirement for an actually installed plugin *more accurately or cheaply* using an actor-owned S4 selection than with first-party Doctor, update dry-run and manual migration?

## Track A: current shipped and original work

- SHIPPED: [SDK usage registry](https://github.com/openclaw/openclaw/blob/307d9c45fb2548d300276c473ccb7c5cab4768bc/src/plugins/sdk-deprecation-usage.ts), [notice generation](https://github.com/openclaw/openclaw/blob/307d9c45fb2548d300276c473ccb7c5cab4768bc/src/plugins/sdk-deprecation-notices.ts), [status](https://github.com/openclaw/openclaw/blob/307d9c45fb2548d300276c473ccb7c5cab4768bc/src/plugins/status.ts), [plugin update command](https://github.com/openclaw/openclaw/blob/307d9c45fb2548d300276c473ccb7c5cab4768bc/src/cli/plugins-update-command.ts) and [host approval](https://github.com/openclaw/openclaw/blob/307d9c45fb2548d300276c473ccb7c5cab4768bc/src/system-agent/approval-intent.ts). Those do not establish the future-actor/options/feedback chain.
- OPEN [#190536](https://github.com/openclaw/openclaw/issues/190536) and [PR #200932](https://github.com/openclaw/openclaw/pull/200932), head **e1f94d4b85d4ee65dd24b45a036fb47018a2fcd0**; actual diff changes dated wording in SDK notice, Control UI and tests, not S4 decisions. [PR #190752](https://github.com/openclaw/openclaw/pull/190752) CLOSED_UNMERGED is overlapping warning work.
- OPEN [#131897](https://github.com/openclaw/openclaw/issues/131897) and [RFC #66](https://github.com/openclaw/rfcs/pull/66), head **eb7d01d73d9555d1280b1ac5cae9d0c8b28d8607**, propose update-availability metadata and displays, with an unresolved original-scope decision; not shipped by the proposal.
- OPEN [#159743](https://github.com/openclaw/openclaw/issues/159743) proposes *post*-upgrade observations, with unsettled lifecycle/status ownership. CLOSED_NOT_PLANNED [#179294](https://github.com/openclaw/openclaw/issues/179294) is an administratively closed proposed pre-upgrade install × release report, not shipped. CLOSED_UNMERGED [PR #164501](https://github.com/openclaw/openclaw/pull/164501), head **f559dae7f3d3c6a3a44fe232f2a8eaab660a6580**, is not an installed recipe.
- OPEN [#200928](https://github.com/openclaw/openclaw/issues/200928) is a real future Atlassian endpoint issue, but the plugin-specific owner fix plus human reauth is the best small baseline; no S4 controller required for that task.

## Track B: independently developed on-top options

| Source covered | On-top delta | User outcome vs current | Falsifier / now |
| --- | --- | --- | --- |
| SDK notice / #200932 | Reuse unchanged | Keep migration date visibility | No material extra result; do not duplicate |
| #131897/RFC #66 update availability proposal | Add **read-only plugin-specific** installed/retirement/target/hold projection, on owner-approved metadata surface | Operator sees actionable installed risk instead of manually joining lists | Current dry-run sufficient, source data missing, owner declines scope. **P1 conditional / NOT_EVIDENCED for S4 C** |
| #159743 post-update observer | Conditionally consume later-run status once owner/API accepted and shipped | See effect of an approved upgrade | Not a prospective decision owner today |
| #179294 broad release report | Narrow plugin-only impact, avoid another global planner | Potentially cheaper first slice | No release metadata owner/supported contract; broader P0 rejected |
| #200928 future endpoint | Issue-native patch/re-auth docs | Specific incident resolved | Native fix makes global controller unnecessary |
| System-agent host approval | Hypothetical S4 actor sends bounded proposals to exact S3 owner | Developer-composed lawful update-or-hold and later feedback | No first-party composability/independent choice or actual later outcome proven; **NO_GO** |

An open Issue is an interface/demand lead, not a built feature. No PR was altered, and no native test or external maintainer conversation occurred.

## Conditional S4 C construction — rejected P0, not current work

A sufficient future combination would need: (1) **trusted, source/expiry-bound prospective external changes**; (2) **redacted actual installed plugin/SDK and supported update choices**, including hold and UNKNOWN; (3) **documented first-party registration for an independent developer-composed S4 decision actor**, not mere prose or generic callback; (4) **typed S3 exact host approval and atomic revalidation**, no self-approval; (5) **durable result with a later real plugin/tool-run observation**, returned to S4 to revise future options. The code, demand and authority for this whole path have not been established. A current alternative is native Doctor/update dry-run + human choice, or a narrowly scoped preview if the RFC owner asks.

**Historical S4=— → current source evidence incomplete → C target NOT QUALIFIED. P0: NONE. P1: conditional native read-only preview. P2: NONE.** No grade change. S3(P) approval remains separate; S5 owner rights and S3* independence are not invented.

## Native acceptance / falsifiers — proposed, NOT RUN

- **AC-01 future positive:** installed plugin with verified future date and supported target; independently registered actor chooses update, host approves exact typed mutation; later actual plugin tool call works and attributed receipt is returned. Without an actor or actual later feedback, no C.
- **AC-02 lawful hold:** same facts but actor chooses hold; zero mutation, risk/expiry retained and subsequent source update can change choice. Hardcoded upgrade falsifies composition.
- **AC-03 bad facts/authority:** stale or fabricated vendor information, unsupported target, credential reauth, denied/missing approval fail closed; no silent install, model self-approval, or credential route selection.
- **AC-04 manual baseline:** compare the same installed plugin against stock Doctor/inspect/update dry-run and operator migration. No improved observable task with acceptable all-in cost means no useful controller.
- **AC-05 backwards compatibility:** unaffected plugins, installed packages and existing owner-controlled system-agent actions continue unchanged.

Future real engineering would use native notice/update/approval fixture tests, supported installed-plugin integration and a later-run witness, plus a new Upgrade material-delta preflight; this roadmap executed **no** tests.

## Decision, costs, rights, and handoff

**Terminal NO_GO NOW** for the named speculative S4 migration controller, not for useful source-native bugfixes. No demonstrated first-party future actor, safe vendor fact contract, later feedback or incremental advantage; generic missing historical S4 grade alone never justifies a new controller. Reconsider only if a concrete installation, maintainer-chosen #131897 scope and complete new actor/outcome evidence emerge. All-in cost **NOT_MEASURED**.

[OpenClaw contributing rules](https://github.com/openclaw/openclaw/blob/307d9c45fb2548d300276c473ccb7c5cab4768bc/CONTRIBUTING.md): new architecture requires prior original discussion; public fork/original Issues/PRs need separate exact current-conversation approval. Verified working fork **opensiro-contributions/openclaw** parent original, metadata control **ALLOW / ACTIVE** on 2026-11-19. This is plan-only research; no code, third-party contact, public fork Issue, Index reassessment or measured saving. [Human issue](https://github.com/opensiro-contributions/openclaw/blob/opensiro/meta/.opensiro/issues/s4-compatibility-transition-20261118/issue.md) · [receipt](https://github.com/opensiro-contributions/openclaw/blob/opensiro/meta/.opensiro/issues/s4-compatibility-transition-20261118/roadmap.md).