# Capability Roadmap Receipt — OpenClaw S4 prospective compatibility

- Original repository: openclaw/openclaw
- Original HEAD: 5cb5f15409575744f6f2f157a5eed8c5bec2071b
- Observed at: 2026-11-18
- Accepted Index assessment: https://github.com/opensiro/vsm-harness-index/blob/5f6ea0c777733813ca42e3f210390a719488dcfb/assessments/op/openclaw.md
- Accepted assessment blob SHA: e1d560bc5b28d90323b15f5f1af6a5293c614b45
- Accepted review ref: 387da5edaa9d6c6cfcfc15e167fe2e46d8647d86
- Accepted reviewed at: 2026-09-16
- System in focus: OpenClaw Gateway, installed plugin metadata/Doctor, first-party plugin SDK and host-approved system-agent control at pinned main; excludes external vendor feeds, remote plugins, maintainers and operator organization
- Result: PLAN_ONLY
- External issue: DRAFT — NOT PUBLISHED
- Cost status: NOT_MEASURED

## Identity and pins

Observed [original revision](https://github.com/openclaw/openclaw/commit/5cb5f15409575744f6f2f157a5eed8c5bec2071b) on 2026-11-18. Accepted [Index historical six-vector](https://github.com/opensiro/vsm-harness-index/blob/5f6ea0c777733813ca42e3f210390a719488dcfb/assessments/op/openclaw.md): **S1=A, S2=C, S3=C(P), S3*=—, S4=—, S5=—**. Index assessment review on 2026-09-16 (Profile 0.2.1; procedure 0.3.1) was 63 days old; recommend separately an Index-owned source-pinned reassessment, not as an Upstream gate. [Human-first issue](https://github.com/opensiro-contributions/openclaw/blob/opensiro/meta/.opensiro/issues/s4-compatibility-transition-20261118/issue.md) and [AI/developer contract](https://github.com/opensiro-contributions/openclaw/blob/opensiro/meta/.opensiro/issues/s4-compatibility-transition-20261118/constructor-sufficiency.md) have the same baseline and priorities.

## Rights and authority

Source [MIT license](https://github.com/openclaw/openclaw/blob/5cb5f15409575744f6f2f157a5eed8c5bec2071b/LICENSE) and [CONTRIBUTING](https://github.com/openclaw/openclaw/blob/5cb5f15409575744f6f2f157a5eed8c5bec2071b/CONTRIBUTING.md); note AI-assisted contribution and small, tested native changes. Verified working fork opensiro-contributions/openclaw parent openclaw/openclaw, `opensiro/meta` attention ACTIVE, owner_control ALLOW at intake. No permission for public fork Issue or original publication inferred.

## Existing work / overlap

[SHIPPED SDK notice](https://github.com/openclaw/openclaw/blob/5cb5f15409575744f6f2f157a5eed8c5bec2071b/src/plugins/sdk-deprecation-notices.ts), [SHIPPED plugin status](https://github.com/openclaw/openclaw/blob/5cb5f15409575744f6f2f157a5eed8c5bec2071b/src/plugins/status.ts), [SHIPPED exact host approval controller](https://github.com/openclaw/openclaw/blob/5cb5f15409575744f6f2f157a5eed8c5bec2071b/src/agents/tools/system-agent-tool.ts). [OPEN #190536](https://github.com/openclaw/openclaw/issues/190536) + [OPEN PR #200932](https://github.com/openclaw/openclaw/pull/200932) head e1f94d4b85d4ee65dd24b45a036fb47018a2fcd0 treat date wording, not S4 construction. [CLOSED_UNMERGED #190752](https://github.com/openclaw/openclaw/pull/190752) covers alternate text. [CLOSED feature #179294](https://github.com/openclaw/openclaw/issues/179294) proposed local-install × release planning and is not shipped proof. [OPEN #200928](https://github.com/openclaw/openclaw/issues/200928) documents an external endpoint future-deprecation trigger; not first-party S4. No existing roadmap case was located in the verified fork.

## Function ownership

Existing S1 A and S2 C need no construction; S3 C(P) is current control and explicit human authorization; S3* and S5 historical — are outside this case. **Target S4=C candidate:** a developer-composed autonomous agent selects a lawful future adaptation on verified external retirement evidence, uses S3 dialogue for current config/install authority, and receives later-run feedback. Present first-party complete path is **UNVERIFIED**, so this is a proposed constructor, not a present grade.

## Capability priority

**P0:** prospective compatibility options and an installable S4-specific developer-composed decision owner, with later operational closure. **P1:** redacted installed-state snapshot, trusted future release/retirement facts, two safe options including hold, policy/approval bridge, durable receipt, and native validation. **P2: NONE.** The full five-port architecture and function-specific native acceptance are documented [in the AI contract](https://github.com/opensiro-contributions/openclaw/blob/opensiro/meta/.opensiro/issues/s4-compatibility-transition-20261118/constructor-sufficiency.md). Stop if native Doctor/manual plan is sufficient or no eligible controller port and operator demand can be established.

## Implementation options

Preferred: reuse existing plugin SDK / status / Doctor and exact system-agent proposal gate; provide the smallest supported plugin-first S4 compatibility-planning interface. Alternative: manual Doctor + release notes, and native impact-report idea [#179294](https://github.com/openclaw/openclaw/issues/179294). For any explicit later implementation, apply Upstream Upgrade gates and source-native tests. No product code was written or run in this plan-only invocation.

## Specification and domain alternatives

Maintain separate options: an original-native small implementation or maintainer clarification; source-backed feedback to [Profile](https://github.com/opensiro/vsm-harness-profile) / [Skills](https://github.com/opensiro/vsm-harness-skills) only if semantics demand it; or a lawful domain-specific experimental fork. No automatic original-project adoption.

## Cost experiment

Compare a single plugin-API retirement across stock Doctor + manual migration and a bounded composed S4 controller + exact host approval. Record task correctness, developer/operator minutes, integration and review effort, regression time, missed deadlines and unintended mutations. No figures collected. **NOT_MEASURED**.

## Delivery and publication

**PLAN_ONLY research disposition: DECISION_READY (design study, not implementation-ready).** Human entry issue, separate linked AI contract and this source-pinned receipt prepared for the matched fork. External original Issue/comment/PR: **DRAFT — NOT PUBLISHED**. Public fork-local GitHub Issue: **NOT PUBLISHED**, requires exact current-conversation authorization for https://github.com/opensiro-contributions/openclaw/issues and final text. No grade alteration, code, tests, approval grant, or actual engineering cost saving claimed.