# prehospital-trauma-deep-learning
MSc Dissertation: Deep Learning in Emergency Life-Saving Care: Continuous Prehospital Physiological Monitoring Data for Trauma Outcome Prediction
# Deep Learning in Emergency Life-Saving Care
MSc Data Science & AI, Queen Mary University of London

Continuous prehospital physiological monitoring data for trauma
outcome prediction (mortality, massive transfusion).

## Contents
- `Sequence_model_pipelines.ipynb`: dense AE, conv AE and LSTM pipelines
- `CAE_simple_classifier.ipynb`: whole-window CAE + logistic regression
- `interior_valid_zeroes.ipynb`: data quality analysis
- `dissertation.pdf`: full thesis

## Data
The patient data is NOT included (clinical data under restricted access).
Notebooks expect `summary.csv`, `CSVFiles.zip` and the outcomes spreadsheet
in the working directory.

## Requirements
Python 3.x, PyTorch, scikit-learn, pandas, numpy, matplotlib

## Author
Marharyta Dzhafarova
