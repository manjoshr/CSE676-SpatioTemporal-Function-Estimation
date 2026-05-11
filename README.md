# CSE 676 Deep Learning Final Project
## Spatio-Temporal Function Estimation

This project estimates hidden chemical reactivity function k(x, y, t) from satellite-based geoscience observations.

The physical relationship is:

dd = k(x, y, t) × vcd

where dd is directional derivative, vcd is vertical column density and k is the chemical reactivity function.

## Models Used

- MLP baseline
- CNN-only model
- CNN-LSTM spatio-temporal model

## Evaluation Metrics

- MAE
- RMSE
- MSE
- Robustness test with 30% missing data

## Dataset

The dataset was provided by Dr. Kang Sun’s research group for CSE 676 course project.  
It is not included in this repository due to course/research data restrictions.

Expected dataset file name:

spatiotemporal_dl.pkl

## How to Run

1. Open the notebook in Google Colab.
2. Mount Google Drive or upload dataset file.
3. Run all notebook cells from top to bottom.

## Student

Manjosh Roy Kalimela  
UB Person Number: 50668585
