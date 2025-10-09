# Governance Dashboard

_Updated: 2025-10-09_

This page consolidates governance-oriented glossary content so compliance, policy, legal,
and risk teams can quickly assess coverage, discover gaps, and coordinate actions.

<div class="stats-grid compact">
  <div class="stat-card">
    <span class="meta-label">Total glossary entries</span>
    <h2>112</h2>
    <p class="muted">All terms are approved, citation-backed, and tagged for downstream review.</p>
  </div>
  <div class="stat-card">
    <span class="meta-label">Governance &amp; risk coverage</span>
    <h2>42 terms</h2>
    <p class="muted">Assurance, privacy, safety, audit trails, and compliance touchpoints.</p>
  </div>
  <div class="stat-card">
    <span class="meta-label">Role reach</span>
    <h2>6 teams</h2>
    <p class="muted">Product, engineering, data, policy, legal, and security have tailored takeaways.</p>
  </div>
</div>

???+ info "How to use this dashboard"
    - Pin the snapshot metrics in governance check-ins to track freshness and coverage.
    - Link glossary terms directly in risk registers, launch checklists, and assurance evidence to keep artefacts aligned.
    - When new terms land, tag NIST AI RMF controls and accountable roles immediately so downstream dashboards stay accurate.

## Snapshot metrics (Oct 09 2025)

- **Top categories:** Governance & Risk (42), LLM Core (26), Operations & Monitoring (19)
- **Most represented roles:** Product (98 terms), Engineering (98), Policy & Data Science (60 each)
- **Recently added governance terms:** [prompt registry](terms/prompt-registry.md), [planner executor pattern](terms/planner-executor-pattern.md), [activation function](terms/activation-function.md)

## NIST RMF coverage by tag

| NIST tag | Representative terms | Action |
| --- | --- | --- |
| Accuracy | [hallucination](terms/hallucination.md), [precision](terms/precision.md) | Ensure evaluation suites report precision/recall alongside hallucination incidents. |
| Fairness | [algorithmic bias](terms/algorithmic-bias.md), [fairness metrics](terms/fairness-metrics.md) | Align fairness thresholds with policy requirements and document in model cards. |
| Transparency | [model interpretability](terms/model-interpretability.md), [model card](terms/model-card.md) | Capture explanation tooling and documentation updates before launch. |
| Privacy | [data minimization](terms/data-minimization.md), [privacy impact assessment](terms/privacy-impact-assessment.md), [data retention](terms/data-retention.md) | Validate retention schedules and PIA sign-offs for new features. |
| Risk Management | [content moderation](terms/content-moderation.md), [voice cloning](terms/voice-cloning.md) | Review incident response playbooks and escalation paths for emerging risks. |
| Documentation | [model card](terms/model-card.md), [model governance](terms/model-governance.md) | Keep model cards and governance logs up to date with each release. |

## Quick tasks for governance partners

1. Review the [Role Starter Pack for Policy & Risk](roles.md#policy--risk) and ensure open tasks are assigned.
2. For each upcoming launch, record fairness, privacy, and interpretability decisions in the appropriate glossary term relationships (e.g., link mitigation plans under “related”).
3. Schedule quarterly audits of the [Category Explorer](categories.md#governance--risk) to confirm coverage is current and identify new terms to add.
4. Use the [interactive search](search.md?category=Governance%20%26%20Risk) with the status filter to prioritise review queues.

## Intake & backlog signals

- **Incoming requests:** Monitor submissions from the [term intake form](term-request.md) and tag them for governance review as needed.
- **Backlog priorities:** The [keyword backlog](keyword-backlog.md#compliance--assurance) highlights assurance, audit, and transparency terms awaiting owners.
- **Review cadence:** Add backlog review as a standing agenda item for the governance or risk council so high-impact drafts move toward approval.

## Useful resources

- [Prompt Engineering Playbook](prompting.md)
- [Category Explorer – Governance & Risk](categories.md#governance--risk)
- [Role Starter Packs – Legal & Compliance](roles.md#legal--compliance)
