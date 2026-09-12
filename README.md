# Reproduction Package — Systematic Literature Review on Data-Driven Digital Governance in Public Administration

Supplementary material submitted alongside the manuscript *"Data-Driven Digital Governance in
Public Administration: a systematic literature review on Decision Support Technologies"*,
currently under double-blind review. This repository contains only what can be published without
violating third-party copyright: audit spreadsheets of the review's results. It does not contain
the PDFs, extracted text, or condensed text of the reviewed studies, nor the software pipeline
used to produce these results.

## Contents

| File | Content |
|---|---|
| `01_search_strategy_by_database.xlsx` | Search string, filters, execution date, and record count per database |
| `02_excluded_studies_with_reasons.xlsx` | The 104 studies excluded at quality assessment, and the 59 excluded for lacking full text or being ineligible by publication type, each with its specific reason (PRISMA 2020, item 22) |
| `03_quality_scores_Q4_Q8_by_study.xlsx` | The two independent raters, the consensus, and the final score per study (Q4-Q8) |
| `04_kappa_worksheet.xlsx` | Cohen's weighted kappa calculation per question (Q1-Q8), with live formulas — auditable cell by cell, without depending on rerunning any code |
| `05_data_extraction_83_included.xlsx` | The 13 data-extraction fields for the 83 included studies |
| `06_thematic_coding_matrix.xlsx` | Thematic coding (Technology, Context, Benefits, Challenges, Gaps) of the 83 included studies |
| `07_prisma_2020_checklist.xlsx` | PRISMA 2020 checklist, item by item, with where the manuscript addresses each one |

## What is not here, and why

- **PDFs of the studies, extracted text, and condensed text.** Third-party copyright. The full
  list of the 83 included studies, with the citation for each, is in Appendix A of the manuscript.
- **The software pipeline** used to run the review (PDF extraction, text condensation,
  double-checked automated assessment, quality gates, CSV assembly). Not included in this version
  of the package.
- **Internal result files** (per-study assessment CSVs, human-consensus records, raw rater
  outputs). Editorial decision: even though these contain only short quotations (≤25 words) from
  the sources, we chose not to publish any content derived from the studies' full text — only the
  aggregated results already auditable in the seven spreadsheets above.

## Reproducibility notes

Without the internal result files, an independent re-run cannot be automatically compared against
the published numbers cell by cell — any such comparison would be manual, study by study, against
these seven spreadsheets. The title/abstract screening cutoff (Q1–Q3, applied over the 1,939
identified records) depends on selection spreadsheets that are also not published here.
