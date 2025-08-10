# AAI590_Group_1: Predicting S&P 100 Stock Returns with LSTM

This repository contains all materials for our AAI-590 team project: developing a deep learning model to predict the 5-day directional return of S&P 100 stocks. Our workflow covers data cleaning, exploratory analysis, feature engineering, model development, optimization, and in-depth diagnostics.

## Recommended Workflow

To fully reproduce the project pipeline and follow our methodology, **run the notebooks in the following order**:

1. **AAI_590_Team-1_Data_Cleaning.ipynb**  
   *Data import, initial quality checks, fixing missing values, and data type standardization.*

2. **AAI_590_Team-1_EDA.ipynb**  
   *Exploratory data analysis: summary statistics, class balance, raw variable correlations, and initial insights.*

3. **AAI_590_Team-1_Feature_Engineering.ipynb**  
   *Feature creation: technical indicators, sector/macro features, and selection of the top predictors using XGBoost.*

4. **AAI_590_Team-1_Model_Build_Design_Train.ipynb**  
   *LSTM model built from scratch in TensorFlow/Keras. Walk-forward sliding window training with extensive comments and hyperparameter setup.*

5. **AAI_590_Team-1_Model_Optimization_Analysis.ipynb**  
   *Systematic model tuning, robust cross-validation, and export of per-window performance metrics to `results_df.csv`.*

6. **AAI_590_Team-1_Diagnostics_Summary.ipynb**  
   *Use this notebook for additional diagnostics and visualization of model performance using `results_df.csv`.*

## Datasets

- Download all project datasets from the [Google Drive link above](https://drive.google.com/drive/folders/1BhoH-VO5rYq1E251Da8aW6yTvtH61Kx6?usp=drive_link).
- If you only want to explore diagnostics and visualizations, start from step 6 after downloading `results_df.csv`.

## Requirements

- Python 3.8 or newer
- Key libraries: pandas, numpy, scikit-learn, tensorflow/keras, matplotlib, xgboost
- See the first code cell of each notebook for the full requirements list.

## Acknowledgments

This work was completed as part of the MS Applied Artificial Intelligence curriculum at USD. We thank the maintainers of open-source Python data science libraries, as well as all data providers.

## Contributors

- Aryaz Zomorodi
- Brian Johnson
- Jay Patel


---

**Contact:**  
For questions or data requests, please open a GitHub issue or reach out to [AryazRez](https://github.com/AryazRez).



