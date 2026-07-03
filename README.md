# Titanic Exploratory Data Analysis

## Project Overview

This project performs Exploratory Data Analysis (EDA) on the Titanic dataset using Python. The goal is to clean the data, explore relationships between different features, visualize important patterns, and summarize the factors that influenced passenger survival.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Structure

```
Titanic-EDA/
│
├── data/
│   └── titanic.csv
├── images/
├── notebook/
│   └── Titanic_EDA.ipynb
├── requirements.txt
└── README.md
```

## Data Cleaning

- Filled missing values in the Age column using the median.
- Filled missing values in the Embarked column using the mode.
- Removed the Cabin column because it contained many missing values.
- Verified that there were no duplicate records.

## Exploratory Data Analysis

The notebook includes:
- Survival Count
- Gender vs Survival
- Passenger Class vs Survival
- Age Distribution
- Fare Distribution
- Correlation Heatmap

## Key Findings

- More passengers died than survived.
- Female passengers had a much higher survival rate than male passengers.
- First-class passengers survived more often than third-class passengers.
- Most passengers were between 20 and 40 years old.
- Higher ticket fares were generally associated with better survival.

## How to Run

1. Clone the repository.
2. Install the required libraries:

```bash
pip install -r requirements.txt
```

3. Open the notebook:

```bash
jupyter notebook
```

4. Run all cells from top to bottom.

## Author

Archita kumari