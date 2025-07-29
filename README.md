# AAI590_Group_1: Predicting S&P 100 Stock Returns with LSTM

This repository contains all code, notebooks, and supporting files for our group project in USD's Applied Artificial Intelligence program (AAI 590). Our project explores the use of deep learning (LSTM) and XGBoost for predicting 5-day directional returns on S&P 100 stocks using historical market and engineered feature data.

## Repository Structure

- `AAI_590_Team_1_Data_Cleaning.ipynb`: Data loading, validation, and cleaning steps for raw OHLCV and fundamentals files.
- `AAI_590_Team_1_EDA.ipynb`: Exploratory data analysis (EDA) with visualizations and summary statistics.
- `AAI_590_Team_1_Feature_Engineering.ipynb`: Creation of technical indicators, macro signals, and XGBoost-based feature selection.
- `AAI_590_Team_1_Model_Build_Design_Train.ipynb`: LSTM model architecture, sequence generation, and baseline training.
- `AAI_590_Team_1_Model_Optimization_Analysis.ipynb`: Model optimization, hyperparameter tuning, cross-validation, and final performance evaluation.

## Datasets

All datasets used in this project are **hosted on Google Drive** due to file size limits on GitHub.  
You can download all data files here:  
[AAI590 Group 1 Datasets (Google Drive)](https://drive.google.com/drive/folders/1BhoH-VO5rYq1E251Da8aW6yTvtH61Kx6?usp=drive_link)

**Included in the folder:**
- `engine_final_allfeatures_wfund.csv` (final engineered dataset)
- `ohlcv_master_clean.csv` (cleaned OHLCV data)
- `ohlcv_master.csv` (raw OHLCV data)
- `spy_ohlcv.csv` (SPY benchmark)
- `top20_features_xgb.csv` (top 20 features, used in modeling)
- `top10_features_xgb.csv` (top 10 features, reference)

> **Note:**  
> No dataset files are included directly in this GitHub repo. Please use the Google Drive link above to access all necessary data for reproducing our analysis and results.

Our modeling scripts and final results used the **top 20 features** as input (`top20_features_xgb.csv`), although both top 10 and top 20 lists are provided.

## Reproducibility

- All notebooks are intended to be run in order: from data cleaning through EDA, feature engineering, model design, and optimization.
- Each notebook is commented with step-by-step explanations.
- If you wish to substitute your own OHLCV or fundamental datasets, ensure they follow similar column names and formats.

## Requirements

- Python 3.8 or newer
- Key libraries: pandas, numpy, scikit-learn, tensorflow/keras, matplotlib, xgboost
- See the first code cell of each notebook for the full requirements list.

## Acknowledgments

This work was completed as part of the MS Applied Artificial Intelligence curriculum at USD. We thank the maintainers of open-source Python data science libraries, as well as all data providers.

---

**Contact:**  
For questions or data requests, please open a GitHub issue or reach out to [AryazRez](https://github.com/AryazRez).

