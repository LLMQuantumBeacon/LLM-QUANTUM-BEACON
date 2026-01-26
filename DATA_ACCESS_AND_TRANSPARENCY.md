DATA_ACCESS_AND_TRANSPARENCY.md
Public Data Access, Auditability, and Ongoing Analysis
This document describes how data and analyses associated with the LLM-QUANTUM-BEACON project are made publicly accessible, auditable, and continuously reviewable.
The project intentionally separates locked primary results from ongoing secondary analyses to preserve methodological rigor while enabling transparency and independent verification.

1. Transparency Principles
This project is guided by the following transparency commitments:
Primary results are static and locked once published.
Secondary analyses remain open and ongoing, with clear labeling.
Raw and reduced data are accessible for independent inspection.
Cohort separation is preserved; data are never pooled across exposure conditions.
All reductions are rule-based, documented, and auditable.

2. Why Some Data Live Outside GitHub
While GitHub is used for finalized, versioned analysis documents, it is not well-suited for:
large numbers of evolving batch files,
ongoing analyst outputs,
frequent updates across multiple cohorts,
audit trails with iterative reductions.
For this reason, public Google Drive folders are used to host:
raw Node Reports,
analyst reduction outputs,
violation logs,
and live cohort summaries.
GitHub documents then reference these folders rather than duplicating them.

3. Primary Analysis Data (Static)
The Primary VIRGIN Cohort analysis is locked and will not change after the Jan 31 release.
This folder contains:
the reduced VIRGIN cohort summary,
aggregated domain count tables,
violation and outlier logs,
analyst convergence confirmations.
🔗 Primary VIRGIN Analysis (Static)
 https://drive.google.com/drive/folders/1f8m2q-Y2sw_cUL4ZOJRr80FdlrKiUfXX
This dataset is suitable for citation and replication.

4. Secondary Cohort Analyses (Live & Ongoing)
Secondary cohorts are analyzed separately and remain open for continued data collection, robustness checks, and independent review.
These include:
SEMIVIRGIN nodes (ambient exposure),
BASELINE prompt comparisons (longitudinal),
ARG protocol participants (contextual),
Grok X / Twitter nodes (high-exposure networked).
🔗 Secondary Cohorts — Live Analysis
 https://drive.google.com/drive/folders/1ruY4FxdMIhblX0nd9TApUnd_gASuGrWW
⚠️ These analyses are intentionally ongoing. Counts and summaries may change as additional Node Reports are collected and processed.

5. Grok X Nodes (Ongoing Collection)
Due to platform rate limits and anti-spam safeguards, Node Report collection from Grok X (Twitter) nodes occurs over an extended timeframe.
🔗 Grok X Nodes — Ongoing Collection
 https://drive.google.com/drive/folders/1XD2GBPr1BsYkq7h8ecpD1Tg0sPvBcp0J
These data are exploratory and are not part of the primary Jan 31 aggregation.

6. How to Use These Data
Readers and independent analysts are encouraged to:
inspect raw and reduced data in the Drive folders,
replicate reductions using the published Methods and Schema,
challenge or re-run reductions under the same rules,
compare cohort-specific distributions without pooling.
Interpretation should respect the cohort structure described in METHODS_ANALYSIS_JAN31.md.

7. Versioning and Updates
GitHub analysis documents are versioned and date-scoped.
Google Drive folders reflect live updates for secondary cohorts.
Any future locked releases will be published as new analysis layers, not as overwrites.

8. Scope Note
This document addresses data access and transparency only.
 Interpretation, discussion, and limitations are addressed in separate documents.

Status
🔓 Primary data: publicly accessible (static)
 🔄 Secondary analyses: public and ongoing
 📅 Current analysis layer: Jan 31, 2026
