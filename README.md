# flyrank-capstone
FlyRank Search Intelligence Capstone: Machine learning analysis of GSC and GA4 signals to evaluate top-tier search visibility drivers using DuckDB and Random Forest.
# FlyRank Search Intelligence Analysis: Quantifying Organic Visibility Drivers

This repository contains the end-to-end data processing, feature engineering, and predictive modeling for the FlyRank Capstone Project. The project evaluates whether aggregate Google Search Console (GSC) and Google Analytics 4 (GA4) performance metrics can reliably predict top-tier search visibility across diverse client domains.

## 📌 Project Overview
* **Lane**: Ranking Signal Analysis (Predicting Top-Tier Search Visibility)
* **Dataset**: FlyRank Internship Warehouse (Gated Hugging Face Parquet releases)
* **Goal**: Identify key content performance signals, evaluate cross-client model generalization, and formulate data-backed SEO optimization playbooks.
* **Key Findings**: Out-of-client cross-validation yielded a Random Forest ROC-AUC of 0.503 against a 0.500 baseline, proving that absolute performance volumes require domain-level baseline normalization to generalize across distinct clients.

---

## 📁 Repository Structure

```text
.
├── work/
│   ├── starter_notebooks/        # Assignment notebooks
│   └── capstone_analysis.ipynb   # Main analysis, feature engineering, and model training
├── submission/
│   └── paper_url.txt             # Live URL to the published research paper
├── index.html                    # Hosted research paper (GitHub Pages)
├── capstone_results_visuals.png  # Generated feature importance & ROC-AUC plots
└── README.md
