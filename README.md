# Black Friday Sales - EDA & Feature Engineering

## Project Overview
This project performs Exploratory Data Analysis (EDA) and feature engineering on the Black Friday sales dataset. The goal is to understand customer purchasing behavior and prepare the data for predictive modeling.

## Dataset
- **train.csv**: Contains customer purchase records for training.
- **test.csv**: Contains customer purchase records for testing.

## Main Steps
1. **Data Loading**: Read train and test datasets using pandas.
2. **Data Concatenation**: Combine train and test data for unified processing.
3. **EDA**: Analyze data types, missing values, and distributions using pandas, matplotlib, and seaborn.
4. **Feature Engineering**:
	- Encode categorical variables (Gender, Age, City_Category).
	- Handle missing values in Product_Category_2 and Product_Category_3.
	- Convert string features to numeric where needed.
5. **Visualization**: Use bar plots to explore relationships between features and purchase amounts.

## Requirements
Install dependencies using:
```bash
pip install -r requirements.txt
```

## Usage
Open `blackfriday.ipynb` in Jupyter Notebook or VS Code and run the cells sequentially to reproduce the analysis and feature engineering steps.

## Author
Gokul-bit165
