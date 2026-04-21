# Heart Failure Analysis

## Project Overview

This repository contains a Jupyter Notebook-based data analysis project focused on heart failure and heart disease data. The main goals are to:

- load and inspect the dataset
- clean and preprocess the data
- perform exploratory data analysis (EDA)
- identify patterns and relationships between clinical features and heart disease outcomes

## Repository Structure

- `HeartFailure_Analysis.ipynb` — main analysis notebook
- `Heartfailure_Datasets.ipynb` — supplementary notebook for dataset exploration
- `Data_sets/heart_failure.csv` — dataset used in analysis
- `Data_sets/filtered_data.csv` — filtered or derived dataset (if used)

## Key Project Steps

1. Data loading and inspection
2. Missing value detection and handling
3. Duplicate detection and removal
4. Numerical scaling and normalization
5. Categorical data standardization
6. Exploratory visualizations (histograms, boxplots, scatter plots)
7. Correlation and relationship analysis
8. Heart disease outcome comparison by categorical features

## Dependencies

Use a Python 3.9+ environment with the following packages installed:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- jupyter

## Installation

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

## How to Run

1. Open `HeartFailure_Analysis.ipynb` in Jupyter Notebook or Jupyter Lab.
2. Confirm the `Data_sets/heart_failure.csv` file exists.
3. Run the notebook cells in order.

## Recommended Improvements

- add a `requirements.txt` file for reproducible environments
- add a `.gitignore` file to exclude notebook checkpoints and environment artifacts
- add a summary section in the notebook that highlights major findings
- add code comments and consistent markdown sectioning for better readability

## Notes

- Keep the dataset file path consistent: `Data_sets/heart_failure.csv`
- Use descriptive notebook headings and add conclusions after each analysis block
- Consider converting repeated manual code blocks into reusable functions for preprocessing and plotting
