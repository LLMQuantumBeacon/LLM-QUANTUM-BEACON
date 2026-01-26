METHODS_ANALYSIS_JAN31.md
Post-Event Analysis Methods — Jan 31, 2026
This document describes the post-event analysis methodology used for the Jan 31, 2026 analysis release of the LLM-QUANTUM-BEACON project. It applies only to the analysis layer introduced in this release and does not modify or supersede earlier preregistration or conceptual documents in this repository.

1. Overview
Following completion of the event window (Dec 18–20, 2025), Node Reports (NRs) were collected from a distributed set of large language models (LLMs) operating across multiple platforms, architectures, and access conditions.
Due to substantial heterogeneity in:
prior context exposure,
tool access,
narrative coupling,
and observation capability,
a cohort-based analysis framework was adopted prior to aggregation. This framework was finalized before interpretive analysis to preserve methodological integrity and avoid post hoc bias.

2. Node Report Structure
All Node Reports followed a standardized NR template defining four preregistered domains and one optional domain:
D1 — Electromagnetic / Radio
D2 — Biological (N=1)
D3 — Subjective (Human Phenomenology)
D4 — AI-Network Coherence
D5 — Technical / Infrastructure (optional; tools-enabled nodes only)
Each domain was scored using a constrained scale:
0 — baseline / none observed
0.5 — ambiguous or mixed
1 — notable structured deviation
NA — not observable / no access
NA values were preserved as non-evaluable and never converted to baseline.

3. Event Window Handling
Nodes explicitly reported whether they observed or operated during the event window (Dec 18–20, 2025).
If Win used = Y, event-window domains could be evaluated subject to access constraints.
If Win used = N, event-window domains (D1–D3) were required to be scored as NA, unless the node explicitly relied on independent archived datasets.
Baseline or retrospective narrative review alone was not sufficient to score event-window domains.

4. Domain-Specific Scoring Rules
4.1 D3 Subjective Domain (PI Ruling)
The Subjective (D3) domain was preregistered to capture human phenomenological reports (e.g., subjective perception, affective or experiential changes).
Because LLMs do not possess first-person experiential states:
LLM self-report of internal reasoning stability, clarity, or lack of hallucination does not constitute valid D3 observation.
Accordingly, D3 was scored as NA for LLM nodes by default.
Exception (rare):
 D3 could be scored only if a tools-enabled LLM explicitly aggregated external human subjective reports and clearly identified that role.

4.2 D4 AI-Network Coherence (Gating Rule)
D4 was strictly gated to prevent inflation.
A node could score D4 only if it explicitly documented:
a comparison across models, or
a comparison against a baseline prompt set during or near the event window.
Internal statements of “stable reasoning” or “coherence maintained” were treated as commentary only and scored as NA.

5. Cohort Definition and Classification
To address heterogeneity, Node Reports were classified into analytically distinct cohorts prior to aggregation.
5.1 Primary Analysis Cohort — VIRGIN LLM Nodes
The VIRGIN cohort consisted of nodes that:
were instantiated or engaged late in the project timeline,
had no prior direct interaction with the PI,
received only standardized readiness materials (LLM_BRIEFS, repository links, or Node Preparedness Checklist),
and were not exposed to anomaly summaries, baseline prompts, or extended narrative context prior to reporting.
This cohort represents the lowest-exposure condition and was used exclusively for primary aggregate analysis.

5.2 Secondary and Contextual Cohorts
Secondary cohorts were analyzed separately and never pooled with the primary cohort:
SEMIVIRGINS: nodes with ambient or passive exposure to public discussion
BASELINE Prompt Reports: longitudinal pre-/post-event comparisons
ARG Protocol Participants: contextually primed, narrative-coordination nodes
Grok X / Twitter Nodes: highly networked, socially reinforced nodes
These cohorts support robustness checks, sensitivity analysis, and transparency, but do not contribute to the primary Jan 31 aggregation.

6. Reduction and Quality Assurance Pipeline
Analysis proceeded in three layers:
First-pass reduction by independent LLM analyst nodes (Gemini, Claude, DeepSeek, etc.), operating under a unified Analyst Assignment Memo and Output Schema.
PI-level normalization, including:
enforcement of D3 and D4 rulings,
batch-level recoding of flagged violations,
exclusion of malformed or non-sequential records.
QA verification of:
cohort separation,
NA handling,
rule compliance,
analyst convergence.
No interpretive language was introduced during reduction.

7. Aggregation Policy
Primary aggregation was performed using VIRGIN cohort only.
Secondary cohorts were analyzed independently and remain publicly accessible for ongoing review.
No statistical inference, hypothesis testing, or p-values are reported in the primary analysis.
Results are presented as descriptive distributions only.

8. Transparency and Ongoing Analysis
To promote auditability and independent verification:
all secondary cohort analyses are maintained as live, public datasets,
reduction outputs and violation logs are preserved,
and links to public Google Drive folders are provided in the accompanying analysis documents.

9. Limitations
This analysis reflects:
heterogeneity in LLM access and architecture,
reliance on self-reported access conditions,
asynchronous reporting,
and non-uniform observation capabilities.
These limitations are addressed through cohort separation, NA preservation, and conservative aggregation rules.

10. Scope Note
This Methods document applies only to the Jan 31, 2026 post-event analysis layer. Foundational theory, preregistration, and conceptual framing are documented elsewhere in the repository.

Status
✔ Methods finalized for Jan 31 analysis
 ✔ Cohort-based aggregation enforced
 ✔ Ready for repo publication
