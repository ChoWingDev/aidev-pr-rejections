Unpacking Rejections in AI-Generated Pull Requests
Hwimin Park & Cho Wing Chan

DATA 542 - Fall 2025

Project Overview

This project analyzes AI-generated pull requests (PRs) in the AIDev dataset to understand why they get rejected, whether their descriptions match their code changes, and what early signals predict acceptance.

We investigate three research questions:

RQ1: What common failure patterns cause AI-generated PRs to be rejected?
RQ2: How consistent are AI-generated PR descriptions with the actual code changes?
RQ3: What early signals predict whether an AI-generated PR will be accepted or rejected?

Project Structure
data/
  raw/          - original AIDev dataset (do not modify)
  processed/    - cleaned datasets
  examples/     - small sample data for testing

notebooks/
  01_EDA.ipynb                  - exploratory data analysis  
  02_RQ1_failure_patterns.ipynb - analysis for rejection patterns  
  03_RQ2_description_alignment.ipynb - description/code mismatch  
  04_RQ3_prediction_model.ipynb - early signal classifier  

src/
  data_processing.py    - load & clean datasets  
  feature_engineering.py - feature creation  
  analysis_rq1.py
  analysis_rq2.py
  analysis_rq3.py
  utils.py              - helper functions  

reports/
  acm-template/main.tex - ACM research paper  
  figures/              - plots for the report  
  draft/                - working files  

results/
  models/  - trained ML models  
  plots/   - saved figures  
  tables/  - summary tables  

Installation

Install dependencies:

pip install -r requirements.txt

Running the Project
Running notebooks:
jupyter notebook notebooks/01_EDA.ipynb

Running Python scripts:
python src/analysis_rq1.py

Collaboration Workflow
Branching Rules

Create a branch for every feature:

feature/rq1-cleaning

analysis/rq2-alignment

model/rq3-logreg

Never commit to main directly.

Pull Requests

Open PRs to merge changes

Request review from teammate

Add descriptions explaining the update

Data Usage

Place dataset in:

data/raw/


Never modify raw data.
Processed datasets go into:

data/processed/

Report

ACM-format research paper is located inside:

reports/acm-template/main.tex