# Bulldozer Sale Price Prediction

End-to-end regression project based on the Kaggle **Blue Book for Bulldozers** competition. The goal is to predict the auction sale price of heavy equipment from historical machine and sale information.

## Project overview

The notebook builds a complete tabular machine-learning workflow on more than **412,000 auction records**, including mixed numerical and categorical features, missing values, and time-dependent validation.

## Workflow

- Exploratory data analysis
- Parsing sale dates and engineering calendar features
- Handling missing numerical values
- Converting categorical variables to numerical representations
- Time-aware train/validation split
- Random Forest regression
- Custom RMSLE evaluation function
- Hyperparameter search with `RandomizedSearchCV`
- Model comparison using MAE, RMSLE, and R²
- Test-set preprocessing and prediction export
- Feature-importance analysis

## Selected result

The final Random Forest model obtained approximately:

- **Validation RMSLE:** 0.245
- **Validation MAE:** 5904
- **Validation R²:** 0.884

## Technologies

Python, pandas, NumPy, scikit-learn, Matplotlib, Jupyter Notebook.

## Data

The dataset comes from the Kaggle competition:

https://www.kaggle.com/c/bluebook-for-bulldozers

The competition data is not included in this repository and must be downloaded separately.

## Usage

1. Download the Kaggle dataset.
2. Update the notebook paths if necessary.
3. Open `end-to-end-bulldozer-price-regression.ipynb`.
4. Run the notebook cells in order.
