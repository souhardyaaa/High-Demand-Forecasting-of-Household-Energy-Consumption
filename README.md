# High-Demand-Forecasting-of-Household-Energy-Consumption

## Introduction

This focuses on developing accurate models for forecasting household-level energy consumption, especially during high-demand periods. The goal is to support Distribution System Operators (DSOs) in managing peak loads more efficiently by comparing different forecasting approaches and evaluating their accuracy with a strong focus on high demand prediction. The project also addresses how control mechanisms can alter consumption data and how to preprocess such data to retain useful insights.

## Exploratory Data Analysis (EDA)

The repository includes EDA notebooks that provide an initial understanding of various datasets from different sources, such as UKPN, CKW, and Goiener. Each notebook explores time-series patterns, consumption distributions, missing values, and household-level consumption behaviors. The EDA phase helps in identifying trends, anomalies, and key features necessary for building robust forecasting models.

### Notebooks:

- `all_uk_data_sm_lv.ipynb` – EDA on combined UK smart meter data
- `ckw_data_a.ipynb` & `ckw_data_b.ipynb` – EDA for CKW datasets
- `es_goiener_data.ipynb` – EDA for Goiener smart meter data
- `ukpn_data_sm_lv.ipynb` & `ukpn_data_sm_ss.ipynb` – EDA for UKPN datasets

Further model development and evaluation will be built upon the insights gathered in this EDA stage.