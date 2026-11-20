# OpenClaw — source-native S3* AutoReview quality-action contract

**Canonical storage:** opensiro-contributions/openclaw@opensiro/meta:.opensiro/issues/s3star-autoreview-handoff-20261119/constructor-sufficiency.md
**Level 1 / Human decision Issue:** [issue.md](issue.md).
**Canonical decision receipt:** [roadmap.md](roadmap.md) owns all historical states, target and decisions; Human contains the single combined six-function table.
**Stage:** PLAN_ONLY / HYPOTHESIS → PROPOSAL-STAGE; **DRAFT — NOT PUBLISHED**; no code or tests run.

## 1. Function-specific construction boundary and methodology checks

**Source and mode boundary:** Original openclaw/openclaw@1a7f34ffd7873e2b3ddb90073fc1220a852cf741 (2026-11-20); first-party Gateway agent/execution runtime. Narrow mode: explicitly opt-in sandbox coding agent using bundled [AutoReview](https://github.com/openclaw/openclaw/blob/1a7f34ffd7873e2b3ddb90073fc1220a852cf741/extensions/autoreview/src/tool.ts) before one specified host-mediated Git publication operation. External GitHub maintainer review, canonical helper's separate repository, third-party model provider and non-mediated execution paths excluded.

**Target transition:** S3*=— -> S3*=C

**Six-function dependencies (S1/S2/S3/S3*/S4/S5):** See six dispositions in [receipt](roadmap.md): S1 performs agent work; S2 communicates/coordinates sessions; S3 host execution/parent approvals retain lawful current-control rights; independent S3* candidate-quality reviewer selects hold/allow before the controlled effect; S4 not required; S5 original operator/maintainer keeps ultimate authority. No automatic new S5 actor.

**Function witness:** HYPOTHETICAL disturbance: candidate changed after review or reviewer reports uncorrected risk, but S1 agent requests otherwise authorized push. Separately configured quality reviewer chooses accepted versus hold with validated same-candidate report. Host-owned [before_tool_call policy](https://github.com/openclaw/openclaw/blob/1a7f34ffd7873e2b3ddb90073fc1220a852cf741/docs/plugins/hooks/tool-policy.md) and native exec approval enforce an exact action; rejection/success is observed by agent in later work.

**Counterfactual owner test:** Remove independent reviewer while leaving AutoReview report, native exec safety/risk reviewer and parent approval. A manually permitted push still occurs without automatic candidate-quality choice; replacing the proposed reviewer with a fixed static bool is not evidence of S3* C.

**Possible methodological negative control:** Existing manual AutoReview/human review is legitimate; local S5 and prospective S4 construction need not be mandatory.

**Contributor / maintainer priorities:** [CONTRIBUTING](https://github.com/openclaw/openclaw/blob/1a7f34ffd7873e2b3ddb90073fc1220a852cf741/CONTRIBUTING.md) requires feature discussion; interest in this exact construction NOT_STATED.

## 2. Source-pinned baseline and parallel native Track A / on-top Track B

**Original native workflow:** Sandbox agent prepares Git diff. Shipped [AutoReview tool](https://github.com/openclaw/openclaw/blob/1a7f34ffd7873e2b3ddb90073fc1220a852cf741/extensions/autoreview/src/tool.ts) uses canonical helper and restricted host reviewer, returns complete validated report; agent independently executes later authorized Git operation or asks human/maintainer. No first-party link requiring a same-candidate independent quality outcome before later action was established.

**Closest existing solution:** [AutoReview](https://github.com/openclaw/openclaw/blob/1a7f34ffd7873e2b3ddb90073fc1220a852cf741/docs/tools/autoreview.md) + manual check + host approval + GitHub maintainer [PR review](https://github.com/openclaw/openclaw/blob/1a7f34ffd7873e2b3ddb90073fc1220a852cf741/docs/reference/pull-request-review-flow.md).

**Relevant original Issues/PRs:** [#201834](https://github.com/openclaw/openclaw/issues/201834) OPEN is result-handoff timeout bug, separate from this candidate gate; [#172336](https://github.com/openclaw/openclaw/issues/172336) OPEN was native review entry request; [#173455](https://github.com/openclaw/openclaw/pull/173455) MERGED supplies shipped reviewer path, [#175529](https://github.com/openclaw/openclaw/pull/175529) and [#200743](https://github.com/openclaw/openclaw/pull/200743) MERGED fix lifetime/watchdog; [#172345](https://github.com/openclaw/openclaw/pull/172345) CLOSED UNMERGED is not shipped proof; [#156804](https://github.com/openclaw/openclaw/pull/156804) OPEN is maintainer guidance not native enforcement. PR search was bounded, no exhaustive negative claim.

| Required S3* link / actor outcome | Track A source status | Track B smallest native addition | Falsifier |
| --- | --- | --- | --- |
| Independent candidate observation | Shipped [AutoReview source](https://github.com/openclaw/openclaw/blob/1a7f34ffd7873e2b3ddb90073fc1220a852cf741/extensions/autoreview/src/tool.ts) returns restricted reviewed result | Bind eligible fresh result, candidate Git identity and separate independent judgment to proposed action | A first-party review-permit already exists |
| Discretionary hold/allow | Shipped [exec auto-reviewer](https://github.com/openclaw/openclaw/blob/1a7f34ffd7873e2b3ddb90073fc1220a852cf741/src/agents/exec-auto-reviewer.ts) checks command safety, **not** candidate quality | Developer-composed separate quality reviewer picks among outcomes; not a fixed threshold | No actual decision owner |
| Protected effect/return | Shipped [before_tool_call](https://github.com/openclaw/openclaw/blob/1a7f34ffd7873e2b3ddb90073fc1220a852cf741/docs/plugins/hooks/tool-policy.md) can terminal-block and return reason; exec approvals remain | Narrow host-owned gate checks matching one-time evidence and exact Git action, denies old/invalid, returns denial or true effect to S1 | Alternate egress bypass remains or host authorizations escalated |

**On-top distinctness:** Prior NO_GO [same-case historical receipt](https://github.com/opensiro-contributions/openclaw/blob/51ba426d95e2f65e0274d48e6f333439b7c19df7/.opensiro/issues/s3star-autoreview-handoff-20261119/roadmap.md) rejected general auditor attached to the **#201834 native timing fix**. Current independent scope is a different *post-review exact protected Git action*, not a justification to undo earlier native-repair NO_GO.

**Source ambiguity / rights blockers:** Need prove exact host exec and Git command interception for one declared mode. Host Code Mode JavaScript wrapper is not automatically a protected inner shell operation. Alternate egress must be absent, externally denied or separately mediated. Prove candidate hash/expiry cannot be forged/reused. No rights or complete source coverage claimed.

## 3. Minimal complete S3* first-party C construction

**Required property:** First-party developer can compose genuinely independent quality decision owner and connect it to enforceable later S1 Git action with status/denial feedback under unchanged parental policy.

| Native component or port | Existing original | Smallest proposed edit / developer integration | Owner, effect and feedback |
| --- | --- | --- | --- |
| Candidate review outcome | [AutoReview implementation](https://github.com/openclaw/openclaw/blob/1a7f34ffd7873e2b3ddb90073fc1220a852cf741/extensions/autoreview/src/tool.ts) already validates reviewer and sandbox state | Expose host-validated, invocation-bound report/candidate descriptor and eligible independent hold/allow outcome, not model-supplied credentials | Independent developer-composed quality reviewer owns decision; host verifies provenance |
| Protected action admission | [Tool policy hook contract](https://github.com/openclaw/openclaw/blob/1a7f34ffd7873e2b3ddb90073fc1220a852cf741/docs/plugins/hooks/tool-policy.md) permits terminal block/approval, original native exec approval | Host-owned exact candidate-hash-to-action binding, rechecking freshness, scope and requester before effects; no other egress in supported mode | Operator controls publication rights, reviewer further restricts, never grants rights |
| Return to operation | Tool result/denial is returned to agent | Reflect actual denied/performed Git effect and repair reason to S1 and optional reviewer followup | Agent revises candidate or continues after actual successful action |

**Native-specific design advice:** Reuse existing sandbox candidate capture, prepared pass digest and protected installed helper, preserve original runtime isolation. A before_tool_call check on the outer Code Mode JavaScript cannot claim coverage of indirect Git shell commands. Either identify and validate a deeper native gate or declare those paths unsupported and deny their egress by host policy. No generic reviewer supervisor.

**Architectural C-sufficiency argument:** Candidate A — reuse AutoReview + first-party pre-tool hook to enforce independently chosen quality decision for one allowed host-exec Git operation, with sandbox digest and exact effect. Candidate B — a narrower dedicated host push API only if existing exec is unmediable, higher code/maintenance cost. Candidate C — GitHub branch protection/human maintainer review is valid parent governance, not first-party autonomous S3* C. Only A is P0 proposal; other candidates are falsifiers/alternatives, not implemented. Without whole path source proof, accepted grade remains unchanged.

**Explicit non-goals:** No new S4 controller/S5 authority, no unrelated approval grant, no generic audit database, no forced PR, no fix to #201834 in this PLAN_ONLY case.

**Implementation dependency graph:** P1 exact source action/candidate/runtime rights → P1 no-bypass freshness and legitimate owner checks → P0 review decision/action join → future matched positive/negative/compatibility native evidence. P2 NONE.

## 4. Priorities, optional alternative and stopping rules

**P0 and P1:** Canonical [roadmap.md](roadmap.md) defines one opt-in independent S3* quality decision to exact authorized Git egress with feedback, and mandatory source/action/rights/freshness proof. These are not a second set of priorities.

**P2:** NONE; no separate S4, S5 or cross-session reviewer.

**Alternative path:** Keep manual original AutoReview + human PR review and established exec approvals, particularly where required host boundaries cannot be proven.

**Stop:** Existing identical first-party completed S3* path, no genuinely independent quality decision, bypassable action or no lawful owner makes proposed constructor incomplete. Maintainer adoption is separate from architectural GO.

## 5. Future source-native acceptance — derive tests, do not copy a matrix

**Native test commands and entry points:** Original [AutoReview tests](https://github.com/openclaw/openclaw/blob/1a7f34ffd7873e2b3ddb90073fc1220a852cf741/extensions/autoreview/src/tool.test.ts) and [package.json](https://github.com/openclaw/openclaw/blob/1a7f34ffd7873e2b3ddb90073fc1220a852cf741/package.json) are first-party source entry points; select owning execution gate tests after investigation. Proposed CLI by standard repository conventions: pnpm test extensions/autoreview/src/tool.test.ts --maxWorkers=1. **NOT_RUN**; not a claim of validated runner execution.

**Positive functional closure:** independent reviewer returns allow on exact clean candidate; one otherwise authorized Git egress is performed, true result returned to subsequent agent work.

**Independent alternative (where applicable):** same authorized actor with reviewer hold sees blocked action and reason, reworks candidate; new digest requires re-review rather than stale reuse.

**Negative authority and compatibility (where applicable):** missing/stale/revoked review, failed helper, changed source tree, host denial or alternative publication route must be blocked in selected opt-in mode. No-opt-in original path stays unchanged; reviewer cannot override parent.

**Matched native alternative:** compare the same candidate under manual AutoReview/human review, including effort and failure behavior; no cost benefit claims without measurement.

| Proposed case (NOT_RUN) | Native test seam / setup | Expected downstream effect and return | Falsifier |
| --- | --- | --- | --- |
| Allow | AutoReview result and host pre-tool protected Git action | One otherwise authorized effect; real status to S1 | Only a report, no action binding |
| Hold | Independent reviewer chooses hold | No effect, meaningful repair reason to S1 | Static permission masquerades as S3* |
| Stale | Change Git candidate after report | Deny until new review | Old report accepted |
| No rights | Missing reviewer, revoked requester, failed pass, host approval deny | No publication; no policy escalation | Any fail-open write |
| Compatibility | Opt-in disabled; indirect Code Mode / other egress | Baseline unchanged; unsupported egress excluded or denied | Bypass in claimed supported mode |

No fixed test/port count imported from historical Paperclip templates. Native tests and external deployment not executed.

## 6. Proposal verdict, falsification, evidence ownership and handoff

**Proposal-stage decision:** GO

**Research disposition:** NEEDS_EVIDENCE

**Primary falsifier:** Exact protected action cannot be mediated with fresh independent outcome or user later-operation feedback, or a true equivalent first-party complete path already ships. **Validation state:** NOT_RUN; GO + NEEDS_EVIDENCE is an untested proposal, not shipped capability.

**Ownership of truth:** Profile owns VSM semantics, Skills method, Index accepted historical grades, original OpenClaw owns code/maintainer policy, [roadmap.md](roadmap.md) owns this case. Independent source-only [first pass](https://github.com/opensiro/upstream/issues/58#issuecomment-7047187780) preceded reading prior negative case; NO_GO remains valid for old generic controller tied to #201834 handoff timing.

**Cost status:** NOT_MEASURED. **Next permitted action:** Source/native tests only after separate engineering authority, before any original feature issue/PR obtain separate exact owner consent. Public fork GitHub Issue DRAFT — NOT PUBLISHED. AI assisted; no human review, code/test pass, grade change or maintainer buy-in inferred.

**Human backlink:** [issue.md](issue.md).
**case receipt:** [roadmap.md](roadmap.md).
**AI disclosure:** Prepared with AI assistance; no product implementation, real tests or reviewer approval.
