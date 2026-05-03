# Bank Customer Churn Prediction

This project focuses on analyzing bank customer data to predict churn behavior. Customer churn occurs when customers stop doing business with a company. Predicting churn is crucial for banks as it allows them to proactively engage at-risk customers with retention strategies.

## Project Overview

The analysis includes data cleaning, exploratory data analysis (EDA), and feature engineering to prepare the dataset for machine learning modeling.

### Key Objectives:
- Identify significant factors influencing customer churn.
- Perform data preprocessing (handling categorical variables, dropping irrelevant features).
- Visualize data distributions and correlations.

## Dataset

The dataset contains information about 10,000 bank customers with the following features:

- **Credit Score**: A numerical value representing the customer's creditworthiness.
- **Country**: The customer's location (France, Spain, Germany).
- **Gender**: Male or Female.
- **Age**: The customer's age.
- **Tenure**: Number of years the customer has been with the bank.
- **Balance**: The amount of money in the customer's account.
- **Products Number**: Number of bank products the customer uses.
- **Credit Card**: Whether the customer has a credit card (1 = Yes, 0 = No).
- **Active Member**: Whether the customer is an active member (1 = Yes, 0 = No).
- **Estimated Salary**: The customer's estimated annual salary.
- **Churn**: The target variable (1 = Churned, 0 = Retained).

## Requirements

To run the analysis notebook, you will need the following Python libraries:

- pandas
- matplotlib
- seaborn

You can install them using pip:

```bash
pip install pandas matplotlib seaborn
```

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/Semordzi-Eric/Bank-Customer-Churn.git
   ```
2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Bank_customer_churn.ipynb
   ```
3. Ensure the dataset path in the first code cell is updated to your local directory.

## Analysis Steps

1. **Data Loading**: Importing the dataset and initial inspection.
2. **Data Cleaning**: Removing unnecessary columns like `customer_id`.
3. **Feature Engineering**: Converting categorical variables (Country, Gender) into numerical format using one-hot encoding.
4. **Data Visualization**: (In progress) Analyzing distributions and relationships between features.

## License

This project is open-source and available under the [MIT License](LICENSE).
