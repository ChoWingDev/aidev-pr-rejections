# Unpacking Rejections in AI-Generated Pull Requests
Cho Wing Chan & Hwimin Park
Data 542 - Fall 2025

---

## Project Overview

This project analyzes **AI-generated pull requests (PRs)** in the AIDev dataset to understand why they get rejected, whether their descriptions match their code changes, and what early signals predict acceptance.

We investigate three research questions:

**RQ1: What common failure patterns cause AI-generated PRs to be rejected?**

**RQ2: How consistent are AI-generated PR descriptions with the actual code changes?**

**RQ3: What early signals predict whether an AI-generated PR will be accepted or rejected?**

---

## 📁 Project Structure

```
aidev-pr-rejections/
│
├── README.md
├── .gitignore
│
├── data/
│   ├── raw/
│   ├── processed/
│   └── examples/
│
├── notebooks/
│   ├── 01_EDA.ipynb
│   ├── 02_RQ1_failure_patterns.ipynb
│   ├── 03_RQ2_description_alignment.ipynb
│   ├── 04_RQ3_prediction_model.ipynb
│   └── shared_utils.ipynb
│
├── src/
│   ├── data_processing.py
│   ├── feature_engineering.py
│   ├── analysis_rq1.py
│   ├── analysis_rq2.py
│   ├── analysis_rq3.py
│   └── utils.py
│
├── reports/
│   ├── acm-template/
│   │   └── main.tex
│   ├── figures/
│   └── draft/
│
└── results/
    ├── tables/
    ├── models/
    └── plots/

```

---

## 🛠 Installation

Install dependencies:
```
pip install -r requirements.txt
```
