# House Price Exploratory Data Analysis (EDA)

## Project Overview
This project explores the factors associated with residential house sale prices using the **House Prices: Advanced Regression Techniques** dataset. The analysis is performed in a Jupyter Notebook and focuses on understanding the data, identifying patterns, examining relationships, and detecting unusual observations.

## Objectives
- Inspect the structure and dimensions of the housing dataset.
- Explore missing values and their percentages.
- Understand the distribution of `SalePrice`.
- Compare sale prices across overall quality levels and neighborhoods.
- Study correlations between numeric features and sale price.
- Explore relationships between sale price and selected features.
- Identify potential outliers using Z-score and IQR-based methods.
- Create an EDA dashboard and summarize key observations.

## Dataset
The notebook uses the following CSV files:

- `train.csv` – training data, including the target column `SalePrice`
- `test.csv` – test data
- `sample_submission.csv` – example submission format

Download the dataset from Kaggle:
[House Prices: Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data)

After downloading, place the CSV files in the same folder as the notebook. The dataset files are not included in this repository.

## Project Files
```text
House-Price-EDA/
├── House_Price_EDA_Project_.ipynb
├── README.md
├── requirements.txt
├── train.csv                 # Download separately
├── test.csv                  # Download separately
└── sample_submission.csv      # Download separately
```

## Tools and Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Jupyter Notebook

## Analysis Workflow
1. Load and inspect the dataset.
2. Review missing values and missing-value percentages.
3. Visualize the sale-price distribution.
4. Classify variables as numerical, categorical, or ordinal.
5. Inspect training and test datasets.
6. Handle missing values in the training data using median values for numerical columns and mode values for categorical columns.
7. Explore sale price by quality and neighborhood.
8. Analyze correlations and the top features associated with `SalePrice`.
9. Visualize relationships involving `GrLivArea`, `TotalBsmtSF`, and `YearBuilt`.
10. Detect potential outliers using Z-score and IQR methods.
11. Generate an EDA dashboard and summarize findings.

## Key Observations
The notebook's concluding observations are:
- The `SalePrice` distribution is right-skewed.
- `OverallQual` has a strong positive relationship with `SalePrice`.
- Houses with larger above-ground living areas generally have higher sale prices.
- Sale prices vary across neighborhoods.
- Some unusually large houses may be outliers.
- Some missing values indicate that particular house features may be absent.

These are exploratory observations, not a predictive model or proof of causation.

## Installation and Usage

### 1. Clone or download this repository
```bash
git clone <your-repository-url>
cd House-Price-EDA
```

### 2. Create and activate a virtual environment (recommended)
```bash
python -m venv .venv
```

On macOS/Linux:
```bash
source .venv/bin/activate
```

On Windows:
```bash
.venv\Scripts\activate
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

### 4. Add the dataset files
Place `train.csv`, `test.csv`, and `sample_submission.csv` in the project directory.

### 5. Launch Jupyter Notebook
```bash
jupyter notebook
```

Open `House_Price_EDA_Project_.ipynb` and run the cells in order.

## Dashboard Output
The notebook saves a dashboard image named:

```text
eda_dashboard.png
```

It is generated when the dashboard cell is executed.

## Scope
This repository contains exploratory data analysis. It does not currently implement or evaluate a house-price prediction model.

## Author
**Pushkar Thombare**
