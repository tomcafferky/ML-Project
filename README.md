CT4101 Machine Learning Portfolio Project (Student ID: 23477446)

## Overview
A machine learning project using ATP tennis match data. The task is can we predict the game margin between the higher-ranked and lower-ranked player in an ATP match, using pre-match information such as rankings, recent form, surface, tournament context and head-to-head history?


Dataset Name: ATP Tennis 2000 - 2026 Daily update 
Source: Kaggle 
Licence: CC0: Public Domain  
Citation: Dissfya. (2026). ATP Tennis 2000 – 2026 Daily update. Kaggle. 
Link: https://www.kaggle.com/datasets/dissfya/atp-tennis-2000-2023daily-pull 

# Setup

Get the project from my github repository: https://github.com/tomcafferky/ML-Project. Download the dataset from https://www.kaggle.com/datasets/dissfya/atp-tennis-2000-2023daily-pull. Unzip it, then copythe CSV file into the project's `data` folder and name it `atp_tennis.csv`. The data is not stored in my repository.

# Run

Open `notebooks/baseline.ipynb` in any environment that can run Jupyter notebooks (for example JupyterLab, VS Code or Google Colab), then run all cells from top to bottom.

Before running the code make sure to check that `DATA_FILE` in the first code cell matches where your CSV is saved so the dataset loads properly and the correct one.

The notebook should run from top to bottom with no other steps to it. It audits the data, then it builds the game margin target, splits the data by date, builds the preprocessing pipeline and reports baseline results (MAE, RMSE, R2). (Pipelines and baseline results not completed yet)

Python Version: 3.12.0 (tags/v3.12.0:0fb18b0, Oct  2 2023, 13:03:39) [MSC v.1935 64 bit (AMD64)]
pandas 3.1.0 | scikit-learn 1.9.1