# Telco Customer Churn Analysis

Lab 1 explores customer churn using the Telco Customer Churn dataset.

## Work Completed

- Loaded the dataset and displayed its first and last records.
- Converted churn from Yes/No to 1/0.
- Inspected data types and converted TotalCharges to numeric.
- Identified and removed 11 incomplete records, leaving 7,032 customers.
- Compared churn across demographic groups, phone service, contracts,
  paperless billing, and payment methods.
- Presented tables, charts, and brief interpretations.

## Project Files

- `lab1.ipynb`: analysis and results.
- `data/`: original CSV dataset.
- `requirements.txt`: required Python packages.
- `.gitignore`: excludes the virtual environment and temporary files.

## Setup

Install Python and the Microsoft Python and Jupyter extensions in VS Code.
Open the project folder and run these commands in the terminal.

### Windows

```powershell
python -m venv .venv
.venv\Scripts\python.exe -m pip install -r requirements.txt
```


## Main Findings

Churn is higher among month-to-month customers, electronic check users,
senior citizens, and customers without partners or dependents.
These are observed associations and do not establish causes.

## Dataset

[Telco Customer Churn on Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)