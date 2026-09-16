# Hi, I'm Siya Gupta

2026 B.Tech graduate from Manipal University Jaipur, building data pipelines, forecasting applications and Python software.

My main focus is **data science and data engineering**. I'm interested in remote entry-level roles hiring in India, including AI/ML and backend development.

## Start here

| Focus | Project | Evidence to explore |
| --- | --- | --- |
| Data engineering | [Retail Data Platform](https://github.com/SJ-14-SJ/retail-data-platform) | Streaming ingestion, transactional recovery, PostgreSQL and dbt. [Case study](https://github.com/SJ-14-SJ/retail-data-platform/blob/main/docs/CASE-STUDY.md) · [Measured benchmark](https://github.com/SJ-14-SJ/retail-data-platform/blob/main/docs/BENCHMARK.md) |
| Data science + application development | [DemandLab](https://github.com/SJ-14-SJ/demand-forecasting-app) | Chronological forecasting, FastAPI and React. [Case study](https://github.com/SJ-14-SJ/demand-forecasting-app/blob/main/docs/CASE-STUDY.md) · [Evaluation](https://github.com/SJ-14-SJ/demand-forecasting-app/blob/main/docs/EVALUATION.md) · [Error analysis](https://github.com/SJ-14-SJ/demand-forecasting-app/blob/main/docs/ERROR-ANALYSIS.md) |

The two projects connect: versioned retail events become a tested analytical dataset, then a forecasting application with explicit evaluation and failure cases. Both include setup instructions, tests, GitHub Actions and documented limitations.

**Measured engineering:** at 100,000 synthetic records, streaming reduced peak traced Python reader allocations from 159.51 MiB to 0.289 MiB in the published local experiment. This is reader memory, not total process memory; the benchmark includes raw observations and reproduction commands.

**Measured modelling:** DemandLab compares a weekly baseline with Ridge on three UCI product series. Validation chooses the baseline for two products. The reports retain both models' results and inspect all 84 holdout product-days, including large misses and imperfect band coverage.

## More work

| Project | What it demonstrates |
| --- | --- |
| [ScholarMatch](https://github.com/SJ-14-SJ/Scholarship-AI) | Streamlit scholarship filtering, heuristic ranking and an optional Resend email digest. |
| [Power Plant Efficiency Analysis](https://github.com/SJ-14-SJ/PowerPlantEfficiencyAnalysis) | Python and SQL analysis of boiler/turbine measurements, tested forecasting and reproducible SQLite reports. [SQL case study](https://github.com/SJ-14-SJ/PowerPlantEfficiencyAnalysis/tree/main/sql). |
| [MoodMate](https://github.com/SJ-14-SJ/-MoodMate-Your-Mental-Wellness-Chatbot) | PyTorch intent classification using NLTK preprocessing and bag-of-words features. |

## Open-source contribution

[eBuild PR #125](https://github.com/embeddedos-org/ebuild/pull/125): preserve toolchain linker flags for shared-library targets, with regression coverage. Submitted with Codex assistance; see the linked PR for its current review status.

## Tools

Python · SQL · PostgreSQL · dbt · pandas · NumPy · scikit-learn · PyTorch · FastAPI · React · Power BI · Streamlit · Git

Recent portfolio improvements were implemented with Codex assistance. Reproduction steps, tests and development exercises are included in the repositories.
