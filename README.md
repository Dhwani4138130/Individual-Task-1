# Individual Task 1 – Part 1

Machine learning analysis for a Data Science case study, predicting student pass/fail outcomes using two publicly available education datasets.

## Overview
This project applies two machine learning models — a Decision Tree and a Random Forest — to predict whether students pass or fail, based on their demographic, social, and study-related features.

## Datasets
1. **UCI Student Performance** (secondary school, Portugal) — 649 instances, 33 attributes.
   https://archive.ics.uci.edu/dataset/320/student+performance
2. **Higher Education Students Performance Evaluation** — 145 instances, 31 features.
   https://archive.ics.uci.edu/dataset/856/higher+education+students+performance+evaluation

## Files
- `Part1_analysis.ipynb` — Jupyter notebook containing the full analysis
- `student-por.csv` — Dataset 1
- `DATA (1).csv` — Dataset 2

## Method
- Converted the final grades into a pass/fail target
- Trained a Decision Tree and a Random Forest on each dataset separately
- Evaluated using accuracy, precision, recall, and F1-score

## Requirements
Python 3, with pandas, numpy, scikit-learn, and matplotlib (all included in Anaconda).
