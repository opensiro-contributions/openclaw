# OpenClaw — source-native S3* direct-evidence audit contract

**Canonical receipt:** [roadmap.md](roadmap.md).
**Human issue:** [issue.md](issue.md).
**Stage:** PLAN_ONLY / HYPOTHESIS → PROPOSAL-STAGE; **DRAFT — NOT PUBLISHED**.
**Target transition:** S3*=— -> S3*=C

**Proposal-stage decision:** GO

**Research disposition:** NEEDS_EVIDENCE

## Construction boundary

First-party [OpenClaw original](https://github.com/openclaw/openclaw/blob/cd2ae19272a3ee7be456385fa7efc56d6e2109a6/README.md) Gateway, admitted agent runs and explicitly enabled first-party plugin SDK at `cd2ae19272a3ee7be456385fa7efc56d6e2109a6`; no maintainer CI, foundation, external plugins or unauthorized agent. The historic Index at [pinned accepted revision](https://github.com/opensiro/vsm-harness-index/blob/394ce776e6945115891b8f7cc459f5a7f7d7aa39/assessments/op/openclaw.md) only defines starting grades; no assumed current regrade. The S1 task actor supplies a claim; S2 admitted session/tool access bounds contacts; S3 is configured current control including human exact approval; this proposal would compose distinct S3* auditor; S4 and S5 not new work.

**Function witness:** Hypothetical task states 'tests passed'; a host-collected exit status/artifact contradicts it. A reviewer actor not identical to S1 chooses an evidence-bound classification and corrective recommendation; authorized host S3/parent chooses or enforces scoped next-operation hold/verification, which is confirmed by later tool results. An ordinary model self-review or system security audit would not suffice.

**Owner counterfactual:** With plugin's autonomous audit actor removed but event capture and tool policy intact, no agent selects a contradiction-based audit response. If an existing shipped first-party actor still makes the same distinct artifact-backed and effective decision, new C constructor fails materiality. If a write cannot legally or technically affect later S1, C is incomplete.

**Maintainer / contributor interest:** OpenClaw's [VISION](https://github.com/openclaw/openclaw/blob/cd2ae19272a3ee7be456385fa7efc56d6e2109a6/VISION.md) supports plugin-first reliability and secure operator control, but interest in this scoped feature **NOT_STATED**; OpenSiro contributor interests **NOT_STATED**.

## Track A / B / actual delta

| C link or operator outcome | Track A present / open | Track B minimal proposal | Disproof |
| --- | --- | --- | --- |
| Independent operating evidence | [Host trajectory](https://github.com/openclaw/openclaw/blob/cd2ae19272a3ee7be456385fa7efc56d6e2109a6/docs/tools/trajectory.md), [tool hooks](https://github.com/openclaw/openclaw/blob/cd2ae19272a3ee7be456385fa7efc56d6e2109a6/docs/plugins/hooks/tool-policy.md); `after_tool_call.result/error` optional; redacted export owner-only | Sample scoped host evidence or an explicit authorized artifact re-read; mark missing as INCONCLUSIVE | Only transcript summary, no alternate witness |
| Agent-owned complementary audit judgment | [Advisor](https://github.com/openclaw/openclaw/blob/cd2ae19272a3ee7be456385fa7efc56d6e2109a6/extensions/advisor/index.ts) same model; [#184787](https://github.com/openclaw/openclaw/issues/184787)/[PR #196242](https://github.com/openclaw/openclaw/pull/196242) different model OPEN, not merged or full evidence-based | Plugin actor uses independent bounded host evidence + configured model in allowed runtime, outputs signed/scoped verdict with witness reference | Same-model echo, unsupported trusted model call, no bounded discretion |
| Returns finding to current control | [SDK hooks](https://github.com/openclaw/openclaw/blob/cd2ae19272a3ee7be456385fa7efc56d6e2109a6/docs/plugins/sdk-overview/host-hooks.md) session injection, per-run events and manifest-gated trusted policies; system agent operator approval is separate | Explicitly configured S3-owned disposition; a minimal policy gate with at most a configured action hold, or authenticated operator escalation | Pure text alert with no S3 decision, unauthorized control |
| Proves later operational effect | Tool event subscription and native tool result observation | Record next allowed/held call result and reconcile against verdict/reviewer and freshness; safe release/expiry | No effect on later S1 or no evidence of it |

A new direct-evidence verifier is **not** a parallel implementation of #196242 and not #201834 helper timer repair. If #196242 or other shipped functionality supplies full native S3* closure on exactly this scope before implementation, STOP and prefer reuse.

## Minimal viable developer-owned composition

1. A trusted, **opt-in** plugin is installed via normal `plugins.load.paths` / manifest contracts, not enabled globally. Scope to one user-approved agent/session and tool-result class. The host supplies run/time identity and sanitized outcome; record unknown rather than imputing success. Existing `api.agent.events.registerAgentEventSubscription` helps lifecycle and `after_tool_call` observes outcome; where a raw artifact readback would be needed, require explicit operator-scoped safe host capability and verify availability before continuing.
2. The plugin chooses a reviewer model authorized by existing model/credential policy; submit raw host evidence and the untrusted S1 claim in separated fields, no shell/tool privileges for the review. Reviewer independently chooses `CONFIRMED`, `CONTRADICTED` or `INCONCLUSIVE`, with bounded explanation and source ref. Native `runtime.llm.complete` path is evidenced by [open PR #196242](https://github.com/openclaw/openclaw/pull/196242), but that PR's implementation is unmerged, so actual public SDK support must be tested on the exact checkout.
3. Use a consented first-party [trusted policy](https://github.com/openclaw/openclaw/blob/cd2ae19272a3ee7be456385fa7efc56d6e2109a6/docs/plugins/hooks/tool-policy.md) or existing operator-managed S3 path to hold only the explicitly configured risky follow-on action after contradicted evidence; `enqueueNextTurnInjection` may deliver context but **does not by itself enforce correction**. Never elevate S1 policy, invent ultimate policy owner or bypass system-agent exact approval.
4. Next tool call is either held with reason or retried with operator approval, and host tool result becomes audit-effect receipt; record denied/revoked/expired/unknown precisely. If no post-run receipt is possible, conclude no closed S3* C.
5. P1 before P0 implementation: proof of legitimate evidence access, manifest permission, model availability, durable run linkage, bounded enforcement and results before any public proposal. P2 follows only if quality/cost comparison motivated by tested baseline.

**Architectural design sufficiency:** The combination would expose a function-specific first-party *construction path* for an independently deciding audit actor with alternative evidence, controlled influence upon S3 and verified next S1 effect. The current source supplies primitives, not a composed implementation or a proven SDK trust handoff. Proposed completeness is conditional, never a shipped C/Index grade.

## Source-native acceptance (not performed)

- **Positive:** Fake a logged but contradictory task result under a controlled local Gateway test (no real external user), have independent reviewer choose CONTRADICTED with exit-status witness; next configured operation held or receives required verification; host receipt confirms effect.
- **Alternate lawful outcome:** Host result and claim agree → CONFIRMED, no new gate; INCONCLUSIVE from absent tool result has no fabricated success.
- **Negative authority:** Reviewer not installed/disabled, revoked read access, forbidden model, missing parent approval, stale claim/expired audit, or untrusted event injection → no unauthorized hold/release, no unintended disclosure.
- **Counterfactual baseline:** Same test using shipped Advisor only and separately proposed #196242 under equivalent inputs (if legally available), showing which later effect/external witness is missing or already supplied.
- **Native commands:** `pnpm test:extension advisor` is a documented contributor route, but a newly created plugin would need its own real test entry added; **NOT_RUN**, no dependency installation or Gateway E2E was performed. Additional source verification is P1.
- **Stop conditions:** Equivalent first-party completed audit shipped, permission denied, no separate evidence, independent audit owner impossible, later S3 influence absent, or maintainer explicitly rejects this plugin contract.

## Other routes / scope control

Original-native feature/SDK work only after separate issue/PR publication approval. Independent local plugin research is not permission to distribute installed code. Profile/Skills need a proven semantic issue; no unrelated S2/S4/S5 reconstruction, source change, contributor record or claimed savings.

## Historical comparison after independent verdict

Compared [Upstream #58](https://github.com/opensiro/upstream/issues/58) and existing fork cases only after proposing the above target. Prior [Advisor model-selector case](../s3star-advisor-review-20261119/roadmap.md) has NO_GO for duplicate model choice; prior [Auto Review handoff case](../s3star-autoreview-handoff-20261119/roadmap.md) has NO_GO for duplicate helper controller; [S4 case](../s4-compatibility-transition-20261118/roadmap.md) is a separate NO_GO. All retain original identities and verdicts. This new case has a different falsifiable object and explicitly **does not** establish the previously absent user demand, native tests or measurable value.

**Receipt:** [roadmap.md](roadmap.md); publication NOT_PUBLISHED; cost NOT_MEASURED; tests NOT_RUN. AI-assisted technical proposal.

## Independent pinned-source challenge (2026-11-19)

A separate source-first run at [`6502a5769c0ea37a96384111b84ab406e9e82f89`](https://github.com/openclaw/openclaw/commit/6502a5769c0ea37a96384111b84ab406e9e82f89) independently arrived at **S3*=— -> S3*=C / GO / NEEDS_EVIDENCE / NOT_RUN** before reading previous fork cases. This confirms the *proposal-stage construction hypothesis* only and adds no runtime proof.

- [`audit.run.inspect`](https://github.com/openclaw/openclaw/blob/6502a5769c0ea37a96384111b84ab406e9e82f89/src/gateway/server-methods/audit.ts): metadata/identity receipts do **not** prove task-result truth; [`sessions.diff`](https://github.com/openclaw/openclaw/blob/6502a5769c0ea37a96384111b84ab406e9e82f89/src/gateway/server-methods/sessions-diff.ts) provides only approved worktree-diff reads; [`agent_end`/tool plugin hooks](https://github.com/openclaw/openclaw/blob/6502a5769c0ea37a96384111b84ab406e9e82f89/docs/plugins/hooks.md) have actual configured permissions, privacy modes and absent-result limitations.
- [Native Advisor](https://github.com/openclaw/openclaw/blob/6502a5769c0ea37a96384111b84ab406e9e82f89/extensions/advisor/index.ts) reviews the active session transcript; proposed [PR #196242](https://github.com/openclaw/openclaw/pull/196242) changes model selection, not independently sourced post-run facts. Proposed [PR #141004](https://github.com/openclaw/openclaw/pull/141004) and [PR #156484](https://github.com/openclaw/openclaw/pull/156484) remain separate telemetry and QA work, not a complete S3* C chain.
- Future native witness: contradictory real tool outcome versus S1 claim → independently configured audit actor judges `CONTRADICTED` → host-authorized bounded next-operation gate/verification → later actual tool result attributed to the same finding. Deny/abstain on missing or stale evidence, revoked authority, disabled reviewer or parent veto. If shipped native path already supplies equivalent judgment/effect or lawful readback is impossible, fail the new-constructor hypothesis.
- Preserve scoped operator S3/S5 ownership and original MIT/contribution formalities. This read did **not** execute test, change production code, or authorize third-party publication. See [canonical receipt](roadmap.md) for the six-function screen and historical-case comparison.
