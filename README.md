# Credit Risk / Loan Default Predictor

A portfolio project predicting consumer loan default risk, built on Kaggle's
[Home Credit Default Risk](https://www.kaggle.com/c/home-credit-default-risk) dataset.
Goal: production-style ML system (feature pipeline, calibrated model, SHAP-based
explanations, adverse-action-notice generation, and a serving API) rather than a
notebook-only Kaggle submission.

## Status

- [x] Phase 0 — Project scaffolding
- [ ] Phase 1 — (TBD)
- [ ] Phase 2 — (TBD)
- [ ] Phase 3 — Data & Exploratory Data Analysis
- [ ] Phase 4 — Feature engineering
- [ ] Phase 5 — Modeling & calibration
- [ ] Phase 6 — SHAP-based explainability
- [ ] Phase 7 — Adverse action notice generation (RAG)
- [ ] Phase 8 — Serving API (FastAPI)
- [ ] Phase 9 — Business case / dashboard

## Repo layout

- `pipeline/` — data ingestion, cleaning, feature engineering
- `modeling/` — training, calibration
- `explain/` — SHAP analysis
- `rag/` — adverse action notice generator
- `backend/` — FastAPI serving app
- `business/` — dashboard / business case assets
