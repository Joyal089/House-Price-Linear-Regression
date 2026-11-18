# House Price Prediction with Linear Regression

An early machine-learning exercise: a linear regression model that predicts house sale prices from living area, number of bedrooms and number of bathrooms.

## How it works

- **Data:** Kaggle's [House Prices: Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques) (`train.csv` and `test.csv`)
- **Features:** `GrLivArea` (above-ground living area, sq ft), `BedroomAbvGr`, `FullBath`, `HalfBath`
- **Target:** `SalePrice`
- The training data is split 80/20. A scikit-learn `LinearRegression` model is trained on the 80% and scored on the 20% with mean squared error. The model then predicts prices for the test set and prints the first five.

## Tech

Python 3, pandas, scikit-learn

## How to run

```bash
pip install pandas scikit-learn
```

1. Download `train.csv` and `test.csv` from the Kaggle competition page. The CSV files in this repository are empty placeholders.
2. Change the two `pd.read_csv(...)` paths in `code.py` (inside the project folder) to where you saved them.
3. Run `python code.py`.

## Results

The script prints the validation MSE and sample predictions. No results are saved in the repository.
