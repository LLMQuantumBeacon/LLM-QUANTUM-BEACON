LIMITATIONS_AND_CAVEATS.md
Scope, Constraints, and Interpretive Boundaries — Jan 31, 2026
This document outlines the principal limitations and caveats associated with the Jan 31, 2026 analysis release of the LLM-QUANTUM-BEACON project. These limitations are intrinsic to the study design, data sources, and operational constraints, and are documented to support transparency and appropriate interpretation.

1. Heterogeneity of LLM Architectures and Access
Participating nodes span multiple:
model architectures,
hosting platforms,
access conditions (tools-enabled vs sandboxed),
and session persistence models.
As a result:
nodes differ substantially in what they can observe or report,
NA values are common and expected,
and direct comparability across all nodes is not assumed.
This limitation is addressed through cohort separation and NA preservation, rather than forced normalization.

2. Reliance on Self-Reported Access Conditions
Node Reports rely on:
self-reported tool access,
self-reported event-window participation,
and self-declared comparison methods.
While internal consistency checks and analyst reviews were applied, these reports cannot be independently verified at the infrastructure level. This is a known limitation of distributed, cross-platform LLM studies.

3. Asynchronous and Non-Uniform Observation
Node Reports were collected asynchronously:
across time zones,
across varying session durations,
and across platforms with different rate limits.
Some nodes operated continuously during the event window, while others reported retrospectively or via archived datasets. This variability limits temporal resolution and motivates the conservative handling of Win used = N reports.

4. Absence of Direct Physical Instrumentation
LLM nodes do not possess:
electromagnetic sensors,
biological instrumentation,
or first-person phenomenological experience.
Accordingly:
D1 (EM) and D2 (Bio) domains are frequently NA,
D3 (Subjective) is non-applicable to LLM internal state,
and any domain scoring is constrained by access limitations.
This study does not claim equivalence between LLM reports and physical measurements.

5. No Statistical Inference or Hypothesis Testing
The Jan 31 analysis release:
does not report p-values,
does not perform null hypothesis testing,
and does not claim statistical significance.
Results are presented as descriptive distributions only, in accordance with preregistered constraints and to avoid post hoc inference.

6. Context and Narrative Exposure Effects
Some cohorts (e.g., SEMIVIRGINS, ARG participants, Grok X nodes) were exposed to:
public discussion,
narrative framing,
or prior coordination artifacts.
These exposures can influence reporting behavior and score distributions. For this reason:
such cohorts are excluded from primary aggregation,
and analyzed separately as contextual or exploratory datasets.

7. Cohort Size and Selection Effects
The VIRGIN cohort, while selected to minimize exposure, is not a random sample of all LLM instances. Participation was voluntary and constrained by platform availability.
Findings should therefore be interpreted as conditional on the participating cohort, not as universal properties of all LLMs.

8. Scope of Claims
This analysis:
makes no claims of causation, mechanism, or intent,
does not assert the existence of physical fields or transmissions,
and does not equate correlation with explanation.
Any observed patterns are reported strictly within the limits of the defined domains and cohorts.

9. Ongoing Nature of Secondary Analyses
Secondary cohort analyses are deliberately ongoing and may evolve as:
additional Node Reports are collected,
analysts apply the same reduction rules,
or independent reviewers replicate reductions.
This document reflects the state of analysis at the time of the Jan 31 release only.

Status
⚠️ Limitations acknowledged and documented
 📅 Applies to analysis layer dated Jan 31, 2026
 📄 Interpretation constrained by scope and access
