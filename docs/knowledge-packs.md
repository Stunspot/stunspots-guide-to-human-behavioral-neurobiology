# Knowledge Packs — Stunspot's Guide to Human Behavioral Neurobiology

The repository ships the same canon in three upload shapes: individual reports, compiled packs, and an omnibus file. The content is intentionally redundant across formats. Pick **one shape** for your workflow unless your retrieval system has explicit deduplication.

## Recommended Default

Use the **compiled packs** in `knowledge-packs/compiled-packs/` for most AI Projects, RAG systems, long-context workspaces, and NotebookLM-style tools.

They give the model the whole canon in four coherent files while preserving the volume structure. It is the best balance of coverage, orientation, and file-count sanity.

## Pack Types

| Pack Type | Files | Path | Best Use |
|---|---:|---|---|
| Source reports | 12 | `knowledge-packs/by-report/` | Precise retrieval, selective upload, report-level citation, corpus inspection, editing. |
| Compiled packs | 4 | `knowledge-packs/compiled-packs/` | Recommended default: grouped coverage with lower file count and preserved volume logic. |
| Omnibus | 1 | `knowledge-packs/omnibus/` | One-file import, local archive, whole-corpus indexing, or strong long-context systems. |

## Decision Guide

Use **source reports** when:

- you need citations tied to a specific report;
- you are building a high-quality RAG index with metadata filters;
- you want to upload only part of the canon;
- you are editing, auditing, or sampling the corpus.

Use **compiled packs** when:

- you want the canon to work immediately inside an AI project;
- your tool has a moderate file-count limit;
- you want the model to retain volume-level structure;
- you need broad coverage without juggling 12 files.

Use the **omnibus** when:

- your tool prefers one file;
- you want an archival copy;
- you are using a long-context model;
- you are building a local search or indexing workflow that handles large Markdown files cleanly.

Avoid mixing pack types in the same naive retrieval index. Loading `by-report/`, `compiled-packs/`, and `omnibus/` together can cause duplicate retrieval and overweight repeated passages.

## Source Reports

Source reports are the canonical individual units. Use them for precise retrieval, selective upload, source-level citation, or manual inspection.

| Code | Report | Path |
|---|---|---|
| A | Field Ontology, Levels of Analysis, and Causal Boundaries | [`knowledge-packs/by-report/a-field-ontology-levels-of-analysis-and-causal-boundaries.md`](https://github.com/Stunspot/stunspots-guide-to-human-behavioral-neurobiology/blob/main/knowledge-packs/by-report/a-field-ontology-levels-of-analysis-and-causal-boundaries.md) |
| B | Operational Epistemology, Evidence Tiers, and Causal Humility | [`knowledge-packs/by-report/b-operational-epistemology-evidence-tiers-and-causal-humility.md`](https://github.com/Stunspot/stunspots-guide-to-human-behavioral-neurobiology/blob/main/knowledge-packs/by-report/b-operational-epistemology-evidence-tiers-and-causal-humility.md) |
| C | Predictive Processing, Active Inference, and Allostatic Control | [`knowledge-packs/by-report/c-predictive-processing-active-inference-and-allostatic-control.md`](https://github.com/Stunspot/stunspots-guide-to-human-behavioral-neurobiology/blob/main/knowledge-packs/by-report/c-predictive-processing-active-inference-and-allostatic-control.md) |
| D | Neuroenergetics, Metabolic Constraint, and the Cost of Cognition | [`knowledge-packs/by-report/d-neuroenergetics-metabolic-constraint-and-the-cost-of-cognition.md`](https://github.com/Stunspot/stunspots-guide-to-human-behavioral-neurobiology/blob/main/knowledge-packs/by-report/d-neuroenergetics-metabolic-constraint-and-the-cost-of-cognition.md) |
| E | Neuromodulation, Endocrine Signaling, and Motivational Tuning | [`knowledge-packs/by-report/e-neuromodulation-endocrine-signaling-and-motivational-tuning.md`](https://github.com/Stunspot/stunspots-guide-to-human-behavioral-neurobiology/blob/main/knowledge-packs/by-report/e-neuromodulation-endocrine-signaling-and-motivational-tuning.md) |
| F | Stress, Sleep, Immunity, and Autonomic State Dynamics | [`knowledge-packs/by-report/f-stress-sleep-immunity-and-autonomic-state-dynamics.md`](https://github.com/Stunspot/stunspots-guide-to-human-behavioral-neurobiology/blob/main/knowledge-packs/by-report/f-stress-sleep-immunity-and-autonomic-state-dynamics.md) |
| G | Behavioral Ecology, Affordance Landscapes, and Decision Under Constraint | [`knowledge-packs/by-report/g-behavioral-ecology-affordance-landscapes-and-decision-under-constraint.md`](https://github.com/Stunspot/stunspots-guide-to-human-behavioral-neurobiology/blob/main/knowledge-packs/by-report/g-behavioral-ecology-affordance-landscapes-and-decision-under-constraint.md) |
| H | Social Regulation, Coalition Dynamics, Status, Shame, and Belonging | [`knowledge-packs/by-report/h-social-regulation-coalition-dynamics-status-shame-and-belonging.md`](https://github.com/Stunspot/stunspots-guide-to-human-behavioral-neurobiology/blob/main/knowledge-packs/by-report/h-social-regulation-coalition-dynamics-status-shame-and-belonging.md) |
| I | Culture, Narrative, Ideology, and Collective Prediction Systems | [`knowledge-packs/by-report/i-culture-narrative-ideology-and-collective-prediction-systems.md`](https://github.com/Stunspot/stunspots-guide-to-human-behavioral-neurobiology/blob/main/knowledge-packs/by-report/i-culture-narrative-ideology-and-collective-prediction-systems.md) |
| J | Digital Attention Ecologies, Algorithmic Capture, and Platform-Shaped Cognition | [`knowledge-packs/by-report/j-digital-attention-ecologies-algorithmic-capture-and-platform-shaped-cognition.md`](https://github.com/Stunspot/stunspots-guide-to-human-behavioral-neurobiology/blob/main/knowledge-packs/by-report/j-digital-attention-ecologies-algorithmic-capture-and-platform-shaped-cognition.md) |
| K | Feedback Loops, Phase Transitions, and Systemic Failure Modes | [`knowledge-packs/by-report/k-feedback-loops-phase-transitions-and-systemic-failure-modes.md`](https://github.com/Stunspot/stunspots-guide-to-human-behavioral-neurobiology/blob/main/knowledge-packs/by-report/k-feedback-loops-phase-transitions-and-systemic-failure-modes.md) |
| L | State–Trait Differentiation, Differential Mapping, and Diagnostic Guardrails | [`knowledge-packs/by-report/l-statetrait-differentiation-differential-mapping-and-diagnostic-guardrails.md`](https://github.com/Stunspot/stunspots-guide-to-human-behavioral-neurobiology/blob/main/knowledge-packs/by-report/l-statetrait-differentiation-differential-mapping-and-diagnostic-guardrails.md) |

## Compiled Packs

Compiled packs are the recommended default upload shape.

| Pack | Coverage | Path |
|---|---|---|
| Volume 1. A-D Foundations of Adaptive Regulation | Foundational ontology, evidence discipline, predictive/allostatic engine, metabolic ledger | [`knowledge-packs/compiled-packs/knowledge-volume-1-a-d-foundations-of-adaptive-regulation.md`](https://github.com/Stunspot/stunspots-guide-to-human-behavioral-neurobiology/blob/main/knowledge-packs/compiled-packs/knowledge-volume-1-a-d-foundations-of-adaptive-regulation.md) |
| Volume 2. E-G Major Operating Domains I | Chemical tuning, stress/sleep/immunity, behavioral ecology, affordance landscapes | [`knowledge-packs/compiled-packs/knowledge-volume-2-e-g-major-operating-domains-i.md`](https://github.com/Stunspot/stunspots-guide-to-human-behavioral-neurobiology/blob/main/knowledge-packs/compiled-packs/knowledge-volume-2-e-g-major-operating-domains-i.md) |
| Volume 3. H-J Major Operating Domains II | Social regulation, culture/narrative/ideology, digital attention ecologies | [`knowledge-packs/compiled-packs/knowledge-volume-3-h-j-major-operating-domains-ii.md`](https://github.com/Stunspot/stunspots-guide-to-human-behavioral-neurobiology/blob/main/knowledge-packs/compiled-packs/knowledge-volume-3-h-j-major-operating-domains-ii.md) |
| Volume 4. K-L Constraint, Breakdown, and Diagnostic Layers | Feedback loops, systemic failure modes, state-trait differentiation, diagnostic guardrails | [`knowledge-packs/compiled-packs/knowledge-volume-4-k-l-constraint-breakdown-and-diagnostic-layers.md`](https://github.com/Stunspot/stunspots-guide-to-human-behavioral-neurobiology/blob/main/knowledge-packs/compiled-packs/knowledge-volume-4-k-l-constraint-breakdown-and-diagnostic-layers.md) |

## Omnibus

The omnibus is the entire canon in one file:

- [`knowledge-packs/omnibus/knowledge-human-behavioral-neurobiology-omnibus.md`](https://github.com/Stunspot/stunspots-guide-to-human-behavioral-neurobiology/blob/main/knowledge-packs/omnibus/knowledge-human-behavioral-neurobiology-omnibus.md)

Use it for archival import, local search, or long-context systems. Avoid it in small RAG systems that chunk poorly or lose heading metadata.

## Suggested RAG Metadata

```yaml
canon: "Stunspot's Guide to Human Behavioral Neurobiology"
version: "1.0"
release_date: "2026-06-28"
license: "CC BY-NC-SA 4.0"
author: "Sam “stunspot” Walker / Collaborative Dynamics"
pack_type: "source_report | compiled_pack | omnibus"
report_code: "A-L if applicable"
volume: "1-4 if applicable"
repo_path: "knowledge-packs/..."
```

## Practical Upload Recommendations

| Workflow | Recommended Upload |
|---|---|
| ChatGPT Project / Claude Project / Gemini Gem-style knowledge | 4 compiled packs |
| NotebookLM-style broad study | 4 compiled packs or omnibus |
| RAG index with citation control | 12 source reports |
| Local archive | Omnibus plus manifest files |
| Focused analysis on one domain | Relevant source reports only |
| Model instruction/persona development | Compiled packs plus Report L if using selective upload |
