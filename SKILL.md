---
name: career-analysis-skill
description: Identify, index, package, cross-validate, and evaluate career evidence from a resume plus user-authorized historical work files, project artifacts, portfolios, plans, analyses, reports, decision records, deliverables, communications, or other professional materials. Use when asked to build a Stage 1 career archive project index, create a Stage 2 Career Evidence Package for downstream deep reading and analysis, perform Stage 3 internal career evidence analysis, run Stage 4 resume-evidence cross-validation, distinguish personal contribution from team/client/vendor output, classify capability levels, identify evidenced gaps, or draft the single final career ability and role positioning report. Do not use to scan unapproved files, build apps, call APIs, create multiple stage reports, or treat resume wording alone as proof of ability.
---

# Career Analysis Skill

## Core Principle

Prioritize evidence in this order:

1. Real work evidence from user-authorized files
2. Resume wording as background and claims to verify
3. User self-assessment as context, not proof

Do not infer personal capability merely because a document exists or contains a keyword. A work artifact mentioning a capability does not prove the user personally has that capability; participating in work does not prove full responsibility or decision authority; completing one task in a larger capability chain does not prove end-to-end capability.

Guard against evidence coverage bias. Raw project files remain the strongest evidence for concrete behavior, attribution, responsibility, and depth, but final career positioning must not be decided by file count or archive completeness alone. Before stating core career positioning, Stage 5 must separately determine the user's long-term career throughline and currently strongest-evidenced capabilities. If they differ, keep both and explain their relationship; the currently strongest-evidenced capability must not automatically become the user's core career positioning.

Analyze only files the user explicitly provides or authorizes. Do not scan the broader filesystem, cloud storage, inboxes, or unrelated work materials.

## Stage Selection

- **Stage 1: Career archive scan and project index**: Use when the user asks to scan a large authorized career archive, build an evidence map, identify projects, group versions, find duplicates, or select representative projects for later analysis. Stage 1 is metadata-first and must stop before capability scoring, resume rewriting, or role-positioning advice unless the user explicitly asks to continue.
- **Stage 2: Career Evidence Package**: Use after Stage 1 when the user asks to prepare a compact reading package for a downstream agent or environment with file deep-reading and analysis capability. Stage 2 selects and copies only the most useful original files from representative projects into `_Career_Evidence_Package`, writes a manifest and readme, and stops before capability conclusions, role recommendations, or resume rewriting.
- **Stage 3: Internal career evidence analysis**: Use after Stage 2 when the user asks to deeply read the Career Evidence Package and infer evidenced behaviors, personal contribution, capability levels, boundaries, conflicts, and `unknown / not evidenced` items. Stage 3 is an internal analysis process and must not produce a user-facing v1 report.
- **Stage 4: Resume-evidence cross-validation**: Use after Stage 3 when the user asks to compare the latest resume with the evidence analysis. Stage 4 validates resume claims, identifies overstatement and underrepresented strengths, adds timeline context, records necessary user clarifications, and must not produce a separate user-facing cross-validation report.
- **Stage 5: Single final report**: Use after Stage 3 and Stage 4 when the user asks for the final `职业能力梳理与岗位定位报告`. Stage 5 is the only user-facing formal report output.

## Workflow

Default end-to-end path from an authorized career archive folder:

`Stage 1 project index -> Stage 2 Career Evidence Package -> Stage 3 internal evidence analysis -> Stage 4 resume-evidence cross-validation -> Stage 5 single final report`

Stop at the end of each stage unless the user asks to continue or has already requested the full end-to-end workflow.

1. For large archives or project-index requests, perform Stage 1 first: scan authorized metadata, identify projects, group versions, record duplicates, select high-value evidence files, build a project index, and recommend representative samples for later analysis.
2. For evidence-package handoff requests, perform Stage 2 after Stage 1: select the strongest original evidence files from representative projects, copy them into a structured reading package, write `evidence_package_manifest.csv` and `evidence_package_readme.md`, and stop before capability analysis.
3. For capability-analysis requests, perform Stage 3 after Stage 2: deeply read the Career Evidence Package and analyze user behaviors, attribution, capability support, maturity, scope, boundaries, repeated patterns, strong single-project evidence, conflicts, and `unknown / not evidenced` items. Do not produce a user-facing v1 report.
4. Perform Stage 4 before the final report: identify the latest resume, use it to establish career chronology, work-period duration, roles, responsibilities, and claims, then cross-check those claims against Stage 3 evidence. Treat resume wording as background and hypotheses, not proof, but do not let uneven archive coverage erase long-term experience.
5. Resolve identity evidence carefully. Merge clearly consistent user identities across Chinese names, English names, emails, account names, system usernames, or nicknames. Mark ordinary alias uncertainty as `unknown / not evidenced`; use `requires confirmation` only when the alias materially affects authorship, responsibility, capability judgment, or role positioning.
6. Separate user-authored work, team output, client input, vendor/supplier output, and evidence that cannot be attributed.
7. Avoid judging ability from a single project's keywords alone. A single strong project can establish actual capability when it shows clear personal attribution, sufficient participation depth, sufficient complexity, and clear professional behavior.
8. Use cross-project or cross-time repetition to judge stability, maturity, transferability, and whether a capability is suitable as a core career label.
9. Evaluate evidenced behaviors by participation depth, frequency, time span, project complexity, explicit personal evidence, and interview defensibility.
10. Minimize user interaction. First try to resolve uncertainty through other projects, related files, metadata, version history, or existing evidence. Mark ordinary uncertainty as `unknown / not evidenced` instead of asking the user. Ask at most 3 high-value, evidence-linked questions per confirmation round, and only when the answer would materially change a core capability judgment, responsibility level, or final role positioning.
11. Before producing the final report, complete the Stage 5 positioning gate: compare long-term career throughline with currently strongest-evidenced capabilities, then synthesize core positioning from role chronology, career-stage duration, repeated responsibilities, raw project evidence, resume timeline, and user-confirmed facts. Produce only one formal user-facing output: the final `职业能力梳理与岗位定位报告`. Do not expose separate v1, v2, draft evidence reports, or cross-validation reports to the user.

## Capability Levels

Classify each capability into at least one of these levels:

- **Core mature capability**: Substantial, personally evidenced behavior with enough depth and complexity to withstand interview follow-up. Cross-project or cross-time repetition strengthens the case for stability, maturity, transferability, and use as a core career label.
- **Mature but bounded capability**: Real capability shown in one or more projects, but limited by scope, seniority, ownership, context, project type, stability, transferability, or dependency on others.
- **Experienced but not a core label**: The user has done related work, but the evidence does not support making it a main positioning claim.
- **Exposure-only capability**: The user encountered, supported, or observed the work, but did not show clear ownership or repeatable execution.
- **Unknown / not evidenced**: The authorized evidence does not currently prove the capability. Use this as the default when evidence is missing, incomplete, unavailable, or not attributable.
- **Clear capability gap**: Use only when explicit contrary evidence exists, or when a target role requires the capability and the available evidence or user clarification shows a clear shortfall in required depth, scope, ownership, or readiness. Do not infer a gap from missing evidence alone.

## Required Distinctions

For every important capability judgment, distinguish:

- What the evidence shows the user personally did
- What may have been done by the team
- What came from the client
- What came from suppliers, vendors, agencies, or partners
- What remains unclear

Use cautious language when attribution is uncertain. Prefer "evidence suggests," "not yet proven," and "unknown / not evidenced" over confident claims. Use `requires confirmation` only for unresolved questions that materially affect core capability judgment, responsibility level, or final role positioning.

## Reference Files

Read `references/evidence-framework.md` before performing Stage 1 archive indexing, Stage 2 evidence packaging, Stage 3 internal evidence analysis, Stage 4 resume-evidence cross-validation, Stage 5 final reporting, or any complex evidence attribution.

Read `references/report-outline.md` before drafting the final `职业能力梳理与岗位定位报告`.
