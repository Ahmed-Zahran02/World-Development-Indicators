# World Development Indicators Analysis

Brief exploratory data analysis and cleaning project based on `WDI.ipynb`.

## Files
- `WDI.ipynb`: notebook with data exploration, missing-value handling, outlier filtering, and visualization.
- `WDI.csv`: dataset used by the notebook (2,938 rows, 19 columns).

## What the notebook does
- Loads and explores World Development Indicators data.
- Checks missing values, duplicates, and basic distributions.
- Cleans data by dropping unused columns, filling selected missing values, and reducing extreme outliers.
- Visualizes key variables to understand indicator patterns.

## Main findings noted in the notebook
- Most countries have more than 80% Hepatitis B vaccination coverage.
- Total health expenditure appears approximately Gaussian.

## Dependencies
The notebook imports:
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `fuzzywuzzy`

## Usage
Open `WDI.ipynb` in Jupyter Notebook or JupyterLab and run cells top to bottom.
