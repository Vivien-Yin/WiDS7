# WiDS Datathon++ 2025 University Challenge
## Age Prediction from fMRI Connectivity Data —Using Autoencoder and Regularized Regression

### Author: Liwen Yin, Jin Wen Lin, Zilu sun, Xiaohan Shi | Boston University | May 2025

The objective of this project is to predict each individual’s age based on the fMRI data provided by Healthy Brain Network (HBN) and a metadata that includes demographic features. The fMRI data focused on each participant’s brain activity during the resting-state. 

The challenge data can be found on the kaggle page (we were unable to upload it due to the large dataset)：https://www.kaggle.com/competitions/widsdatathon2025-university

Since we took several different approaches, the code is divided into several rmd files with the contents shown in the filenames. The report is also uploaded as pdf file.
- `data_cleaning.Rmd`: Data cleaning
- `EDA Code.R`: EDA
- `WiDS_PCA`: PCA + Model
- `Autoencoder.Rmd`: Autoencoder + Model
- `Autoencoder Dimensionality reduction_.Rmd`: Bayesian optimization of XGBoost on compressed fMRI + meta features
- `xgb_bayesopt_results.csv`: Bayesian Optimization Parameters & Results for XGBoost （Table）
