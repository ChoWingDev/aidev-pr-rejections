# Unpacking Rejections in AI-Generated Pull Requests
Cho Wing Chan & Hwimin Park
Data 542 - Fall 2025

---

## Project Overview

This project analyzes **AI-generated pull requests (PRs)** in the AIDev dataset to understand why they get rejected, whether their descriptions match their code changes, and what early signals predict acceptance.

We investigate three research questions:

**RQ1: What common failure patterns cause AI-generated PRs to be rejected?**

**RQ2: How consistent are AI-generated PR descriptions with the actual code changes?**

**RQ3: Do AI-generated PRs attract different types or amounts of reviewer comments compared to
human PRs?**

---

## 📁 Project Structure

```
aidev-pr-rejections/
│
├── README.md
├── .gitignore
├── requirements.txt
│
├── notebooks/
│   ├── 01_EDA.ipynb
│   ├── 02_RQ1_failure_patterns.ipynb
│   ├── 03_RQ2_description_alignment.ipynb
│   ├── 04_RQ3_prediction_model.ipynb
│   └── shared_utils.ipynb
│
├── reports/
│   ├── acm-template/
│   │   └── main.tex
│   ├── figures/
│   └── draft/

```

---

## 🛠 Installation

Install dependencies:
```
pip install -r requirements.txt
```
