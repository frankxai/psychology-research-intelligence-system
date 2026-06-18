# Psychology Research Intelligence System

**Helps researchers map constructs, synthesize evidence, design studies, evaluate measures, and improve reproducibility in psychological science.**

## Purpose
A domain-specific research intelligence system focused on psychology. Never for clinical diagnosis — research infrastructure only.

## How People Experience It
Psychologists use it to:
- Map fuzzy constructs to measurable variables (construct-mapper agent + human-mind models).
- Systematically review literature with evidence tables.
- Design and critique studies/surveys with psychometrics checks.
- Run qualitative coding and behavioral experiment design.

Onboarding: Start with construct-to-measurement workflow, link to personal canon from Agentic Mind OS.

## How Agents Explore It
- psychologyresearch.yaml
- agents/ (construct-mapper, literature-scout, methods-critic, psychometrics-agent, qualitative-analysis-agent, behavioral-experiment-designer)
- skills/ (construct-map-builder, systematic-review-matrix, survey-design-review, psychometrics-check, qualitative-coding)
- workflows/ (construct-to-measurement.md, literature-to-evidence-table.md, behavioral-experiment-design.md)
- schemas/ (construct.schema.json, measure.schema.json, study.schema.json)

**Example Prompt** (with latest best tech):
"As psychometrics-agent + methods-critic, using human-mind models (belief.md, motivation.md), evaluate this self-efficacy scale. Run reliability/validity checks with modern psychometrics (pingouin, factor analysis). Output to measure.schema.json. Generate preregistration template per Registered Reports standards."

## Usefulness
- **Humans**: Raises rigor in psychological science. Helps with reproducibility crisis solutions.
- **Agents**: Domain-specific agents that stay grounded.
- **Integrations**: Connects to Research Intelligence Systems packs and Research OS runtime. Uses shared human mind models.
- **Latest Best Tech**: Preregistration, Registered Reports, modern psychometrics libraries, structured outputs, qualitative + quantitative mixed methods.

See psychologyresearch.yaml, AGENTS.md, HERMES.md, EXPERIENCE.md.

Guardrail: Research only. No individual diagnosis.