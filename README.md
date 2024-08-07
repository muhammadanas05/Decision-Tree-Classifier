# Decision Tree Classifier

This project involves analyzing bank data using a Decision Tree Classifier. The analysis includes data preprocessing and encoding categorical variables.

## Datasets

The project uses the following datasets:

1. bank.csv: Contains a subset of the bank data.
2. bank-full.csv: Contains the full bank data.
3. bank-names.txt: Provides column names for the datasets.

## Data Preparation

### Loading Data

The datasets are loaded into pandas DataFrames:

- `bank_data`: A subset of the bank data.
- `bank_full_data`: The complete bank dataset.
- `bank_names`: A text file containing column names.

### Data Inspection

- Dataset Information: Information about the datasets, including column names and data types.
- Data Structure: Display of the first few rows of each dataset to understand their structure.

### Preprocessing

- Missing Values: The presence of missing values is checked.
- Encoding: Categorical variables are encoded using one-hot encoding to convert them into numerical format. This process involves creating dummy variables and dropping the first category to avoid multicollinearity.

### Additional Information

- Column Names: The contents of `bank-names.txt` are reviewed to understand the column names used in the datasets.
- Column Details: The column names and their structure are displayed to understand the data better.

---

Feel free to adjust or expand upon this content based on any additional details or specific insights from your analysis.
