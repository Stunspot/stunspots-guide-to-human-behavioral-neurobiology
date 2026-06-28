# How to Use This Canon

*Stunspot's Guide to Human Behavioral Neurobiology* is built for model-facing use. A human can read it as a field manual, but the highest-value use is to load it into an AI workspace, project knowledge base, long-context session, RAG pipeline, NotebookLM-style tool, or agent memory layer so the model has a disciplined interpretive substrate for behavioral reasoning.

## The Default Move

For most AI/RAG systems, start with the **compiled packs** in `knowledge-packs/compiled-packs/`.

They preserve the four-volume architecture while keeping file count low:

1. A-D — foundations of adaptive regulation
2. E-G — major operating domains I
3. H-J — major operating domains II
4. K-L — constraint, breakdown, and diagnostic layers

Use the source reports only when you need tighter citation control, selective upload, or isolated report-level editing. Use the omnibus only when your system handles large single-file knowledge sources well.

## Pick the Right Format

| Format | Path | Best For | Avoid When |
|---|---|---|---|
| Source reports | `knowledge-packs/by-report/` | Precise retrieval, selective upload, source-level citation, editing, report-by-report inspection. | Your tool has a low file-count limit or you want broad coverage quickly. |
| Compiled packs | `knowledge-packs/compiled-packs/` | Recommended default for most AI/RAG systems; balanced coverage with lower file count. | Your system performs best with very small atomic files or requires per-report citation boundaries. |
| Omnibus | `knowledge-packs/omnibus/` | One-file import, local archive, whole-corpus search, strong long-context models. | Your tool struggles with very large files or duplicates retrieval from overlapping packs. |

Do **not** upload the omnibus plus compiled packs into the same small RAG system unless you know how it handles duplicates. That usually creates retrieval echo and makes the model cite the same idea twice while looking very pleased with itself.

## For Human Readers

Read through the problem you have:

- Need the theoretical spine? Start with A-D.
- Need behavior under scarcity, stress, or constraint? Start with G, then K-L.
- Need social dynamics, shame, belonging, status, coalition behavior? Start with H.
- Need ideology, narrative, identity, cultural scripts, or institutional meaning? Start with I.
- Need digital attention capture and platform-shaped behavior? Start with J.
- Need to avoid over-diagnosis or personality-label slop? Start with L.

The reports are dense by design. They are not consumer essays. Read them as a canon: each report establishes vocabulary and guardrails reused downstream.

## For AI Assistants

When this canon is loaded into a model workspace, use it as behavioral doctrine, not as decorative background.

A good assistant should:

1. **Preserve level-of-analysis discipline.** Do not explain a social, metabolic, cultural, or platform-mediated phenomenon using only a neurotransmitter or brain-region story.
2. **Distinguish model from mechanism.** Active inference, predictive processing, and free-energy language should be treated as formal explanatory frames unless the corpus supplies a specific biological mechanism.
3. **Route behavior through constraints.** Before attributing a behavior to personality, motivation, pathology, or morality, map the affordance landscape: energy, threat, social cost, incentives, sleep, recovery, scarcity, and platform design.
4. **Use state-trait guardrails.** A repeated state in a stable ecology is not automatically a trait. A constrained policy is not automatically a deficit.
5. **Respect causal humility.** Do not convert population-level findings, proxy measures, or generalized mechanisms into individualized diagnosis.
6. **Avoid folk neurochemistry.** Dopamine is not "pleasure juice." Cortisol is not "bad stress chemical." Oxytocin is not "the love molecule." The canon is allergic to that nonsense, as it should be.
7. **Name uncertainty.** Where evidence is insufficient, say what can be responsibly inferred and what remains only a hypothesis.

## For RAG / Retrieval Systems

Use the repository paths as stable source identifiers.

Recommended retrieval metadata:

```yaml
canon: "Stunspot's Guide to Human Behavioral Neurobiology"
version: "1.0"
release_date: "2026-06-28"
source_type: "source_report | compiled_pack | omnibus"
report_code: "A-L, if applicable"
volume: "1-4, if applicable"
path: "repository-relative path"
license: "CC BY-NC-SA 4.0"
author: "Sam “stunspot” Walker / Collaborative Dynamics"
```

Recommended chunking behavior:

- Preserve headings and report codes in each chunk.
- Keep tables with their surrounding explanatory paragraphs when possible.
- Prefer source reports for fine-grained retrieval and compiled packs for workspace upload.
- Preserve source filenames and repo-relative paths in citations.
- Avoid blending the same content from source, compiled, and omnibus files in one retrieval index unless deduplication is enabled.

## For Long-Context Workflows

Load either:

- all **4 compiled packs**, or
- the **1 omnibus file**.

Then ask the model to reason from the canon explicitly. For example:

```text
Use Stunspot's Guide to Human Behavioral Neurobiology as your interpretive substrate. Analyze the behavior as embodied adaptive regulation. Preserve level-of-analysis discipline, map energetic/social/cultural/platform constraints before trait attribution, and apply the state-trait guardrails from Report L before making any stable-personality or pathology-adjacent claim.
```

## Safe Behavioral Interpretation Pattern

Use this sequence when analyzing a person, group, platform behavior, workplace pattern, cultural conflict, or institutional failure:

```text
1. Describe the observable behavior neutrally.
2. Identify the timescale: acute state, recurring state, chronic state-lock, trait-like pattern, stable trait, learned adaptation, structural constraint, social role, cultural script, digital capture, or measurement artifact.
3. Map the likely regulatory function: energy conservation, threat reduction, status protection, belonging repair, uncertainty reduction, metabolic recovery, social compliance, exploration, avoidance, or platform-forced sampling.
4. Map the affordance landscape: what actions are cheap, costly, punished, rewarded, hidden, or impossible?
5. Check evidence quality and scope.
6. Offer differential candidates.
7. Use cautious wording that preserves reversibility and avoids unsupported diagnosis.
```

## What Not To Do

Do not use this canon to generate clinical diagnoses, treatment instructions, medical advice, or deterministic claims about an individual. It is a reasoning substrate, not a clinician in a trench coat.

Do not reduce behavior to single chemicals, single brain regions, single traumas, single incentives, or single labels.

Do not read social behavior as "just psychology" or neurobiology as "just brain stuff." The canon's whole point is that human behavior emerges across interacting levels.
