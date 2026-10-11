# Amazon ML Challenge 2026 – Entity Resolution

## Overview
A machine learning project focused on business entity resolution, identifying matching entities across datasets using text similarity, feature engineering, and predictive matching techniques.

## Problem Statement
Business information may appear differently across multiple datasets due to variations in names, addresses, spelling, and formatting. The goal is to identify corresponding entities accurately and reduce incorrect matches.

## Tech Stack
- Python
- Pandas and NumPy
- Scikit-learn
- LightGBM / XGBoost (as used in the final pipeline)
- TF-IDF and text similarity techniques
- Kaggle Notebooks

## Methodology
- Data preprocessing and text normalization
- Candidate entity matching
- Text similarity and feature engineering
- Machine learning-based match prediction
- Threshold tuning and output validation

## Results
- Developed a matching pipeline for large-scale entity resolution.
- Generated a submission containing 1,732,544 source-entity records.
- Best recorded leaderboard score: 0.990621.

*Note: Add the exact evaluation metric and final model details after verifying them against the competition results and notebook.*

## Repository Contents
- `amazon_ml_challenge.ipynb` – Notebook containing the project implementation.
- `README.md` – Project documentation.

## How to Run
1. Clone or download this repository.
2. Install the required Python libraries.
3. Open the notebook in Jupyter or Kaggle.
4. Configure the dataset paths and run the notebook cells.

## Disclaimer
This project was developed as part of work on the Amazon ML Challenge 2026. Refer to the official competition rules before redistributing datasets or competition materials.
