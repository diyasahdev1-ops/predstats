# Car Price Prediction Model

This repository contains an end-to-end Machine Learning pipeline designed to predict automotive vehicle prices based on various structural, performance, and mechanical attributes. 

## Project Workflow
The notebook implements a structured data science approach:
* **Data Ingestion & Cleaning:** Loading the automotive dataset and handling missing values.
* **Exploratory Data Analysis (EDA):** Visualizing feature distributions and analyzing target variables.
* **Feature Engineering:** Implementing transformation mapping for nested data structures (e.g., categories, lists) and engineering critical numeric predictors.
* **Model Training & Comparison:** 
  * Linear baseline utilizing **Ridge Regression**.
  * Non-linear modeling using **Random Forest Regressor**.
* **Hyperparameter Tuning:** Fine-tuning models using search strategies (`RandomizedSearchCV`/`GridSearchCV`).
* **Evaluation & Visualization:** Comparing actual vs. predicted pricing trends with `matplotlib`.

## Installation & Setup
To run this notebook locally, ensure you have the required Python environments installed:

```bash
pip install numpy pandas scikit-learn matplotlib seaborn
```

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/diyasahdev1-ops/predstats
   ```
2. Open the notebook in **Google Colab** or a local **Jupyter Notebook** environment.
3. Execute the cells sequentially to preprocess the data, train the estimators, and visualize the prediction plots.
