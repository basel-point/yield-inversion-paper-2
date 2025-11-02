# Paper 2 — Logit: Recession Probability from the Yield Curve (12-Month Horizon)

This repository is a **publication-style showcase** for the analysis featured in  
**“When the Curve Speaks: Estimating Recession Risk with a Logistic Classification Model.”**  
It demonstrates results and method summary without exposing the full implementation.

- 🔗 **Companion article:** https://thebaselpoint.substack.com/p/when-the-curve-speaks
- 📊 **Preview (HTML):** `Paper2_Logit_Recession_12m_preview.html` (in this repo)
- 🖼️ **Figures:** `roc_auc_curve.png`, `recession_probabilities.png`

---

## What this shows
- Key results (ROC/AUC, probability series, zoomed recent window)
- A concise methods description in plain English
- Source attribution for macro data (FRED)

## What this omits (by design)
- Full notebook and pipeline logic
- Raw datasets and private paths
- Parameter sweeps and internal utilities

If you’re a hiring team, PM, or researcher who needs **full technical review**, contact me for access.

---

## Methods (summary)
We estimate a 12-month-ahead U.S. recession probability with a **logistic classification model**, using yield curve spreads as predictors:
- Spreads: **10Y–3M** and **10Y–2Y**
- Lags: **1-month** and **6-month**
- Backtest: **expanding-window (walk-forward)** evaluation
- Outputs: ROC/AUC, precision/recall snapshot, full-history probability with NBER shading, zoomed last-10-years view

This preview includes charts and a narrative summary sufficient for expert readers to understand the approach, while withholding cloneable implementation details.

---

## Data Sources
- Federal Reserve Economic Data (FRED): constant-maturity Treasury series and NBER recession indicator.
- Other macro sources as cited in the article.

> Note: No raw data files are included in this repository.

---

## Environment (minimal)
The analysis was built with Python and common scientific libraries:
pandas
numpy
matplotlib
scikit-learn
statsmodels

---

## Access & Contact
- Full code and datasets are available **by request for professional review**.
- Please reach out via Substack or your preferred contact channel.

---

## License & Use
© 2025 S.Y. Kim. All rights reserved.  
You may reference the figures and this summary with attribution.  
**Reuse of source code, data, or methods requires permission.**
Copyright (c) 2025 S.Y. Kim. All rights reserved.

This repository contains publication-style materials (figures, previews, and summaries).
You may reference or quote the materials with attribution.

Reuse, reproduction, or redistribution of source code, data, or methods is prohibited
without prior written permission from the copyright holder.

