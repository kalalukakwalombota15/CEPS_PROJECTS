# CEPS Load Forecasting Project

This repository contains a time-series electricity load forecasting project
based on CEPS data.

## Project structure
- `CEPS_dataset_assessment.ipynb`  
  Dataset inspection, cleaning, feature engineering, and suitability assessment.

- `01_onestep_forecasting_baselines.ipynb`  
  One-step-ahead forecasting using baselines and neural networks.

- `ceps_preprocessed.csv`  
  Cleaned and preprocessed dataset used for modeling.

## Objective
The goal of this project is to build and compare baseline models and neural
networks (MLP, LSTM, GRU, TCN, Transformer) for short-term electricity load
forecasting.

## Environment
- Notebooks are intended to be run in **Google Colab**
- PyTorch is used for neural network models
M  
