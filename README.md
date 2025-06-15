# MAO_inhibitor_classification

End-to-end ML pipeline for classifying MAO-A and MAO-B inhibitors using PyCaret, ChEMBL, and RDKit.

This repository contains an end-to-end machine learning pipeline for classifying **MAO-A** and **MAO-B** inhibitors using data from the ChEMBL database.

## Project Structure

### MAO_A/
- `01_download_and_preprocess.ipynb`: Downloads data from ChEMBL, curates, and preprocesses it.
- `02_eda.ipynb`: Exploratory Data Analysis.
- `03_modeling.ipynb`: Classification model building using PyCaret.
- `data/`: Contains CSV files used in notebooks.
- `plots/`: Visualizations generated.
- `models/`: Saved trained models.

### MAO_B/
- Same structure as `MAO_A/` for MAO-B inhibitors.

## Goals

- Build robust ML pipelines for MAO-A and MAO-B inhibitor classification.
- Use PyCaret for model comparison and feature importance.
- Visualize insights and save models for reuse.

## Requirements

- Python ≥ 3.8
- PyCaret
- pandas, seaborn, matplotlib
- scikit-learn

## How to Run

1. Clone this repo.
2. Run each notebook sequentially in `MAO_A/` and `MAO_B/`.

## Author

Dhrubajyoti Maji
