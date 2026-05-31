# Banking Fraud Detection and Credit Risk Analysis using Python, EDA, and Power BI

## Brief Summary

A data analytics project that uses Python, Exploratory Data Analysis (EDA), and Power BI to identify fraud indicators, assess credit risk, and analyze customer financial behavior using banking data.

---

## Overview

The banking and financial sector faces increasing challenges related to fraud detection and credit risk management. Identifying risky customers and understanding financial behavior are essential for minimizing losses and improving lending decisions.

This project analyzes a real-world banking dataset provided by Paisabazaar containing customer demographics, income details, debt information, repayment behavior, and credit scores. Using Python for data preprocessing and exploratory data analysis, and Power BI for interactive dashboard visualization, the project uncovers patterns associated with fraud risk and customer creditworthiness.

The analysis focuses on understanding how factors such as income, outstanding debt, credit utilization, delayed payments, loan burden, and payment behavior influence customer credit scores and overall financial health.

---

## Problem Statement

Financial institutions must accurately identify high-risk customers and detect potential fraud before financial losses occur. Traditional manual analysis is time-consuming and often fails to uncover hidden relationships within large datasets.

The objective of this project is to:

- Analyze customer financial behavior.
- Identify indicators of credit risk.
- Detect patterns associated with fraudulent activities.
- Understand factors affecting customer credit scores.
- Build an interactive dashboard for business decision-making.
- Support financial institutions in improving risk assessment and customer profiling.

---

## Dataset

### Dataset Name
Paisabazaar Banking Dataset

### Dataset Size
- Records: 1,00,000
- Features: 28

### Key Features
- Age
- Occupation
- Annual Income
- Monthly Inhand Salary
- Number of Bank Accounts
- Number of Credit Cards
- Interest Rate
- Number of Loans
- Outstanding Debt
- Credit Utilization Ratio
- Credit History Age
- Delay from Due Date
- Number of Delayed Payments
- Number of Credit Inquiries
- Payment Behaviour
- EMI per Month
- Credit Score

### Credit Score Categories
- Good
- Standard
- Poor

---

## Tools and Technologies

### Programming Language
- Python

### Python Libraries
- Pandas
- NumPy
- Matplotlib
- Seaborn

### Data Visualization
- Power BI

### Development Environment
- Google Colab

### Techniques Used
- Data Cleaning
- Data Wrangling
- Feature Engineering
- Exploratory Data Analysis (EDA)
- Statistical Analysis
- Dashboard Development

---

## Methods

### Step 1: Data Collection
- Import and load the Paisabazaar dataset.

### Step 2: Data Cleaning
- Convert data types.
- Handle null values.
- Remove duplicates.
- Verify data consistency.

### Step 3: Data Wrangling
- Create derived features.
- Group customers into income categories.
- Calculate financial ratios.

### Step 4: Outlier Detection
- Identify and remove extreme values using the IQR method.

### Step 5: Feature Engineering
- Create Income per Account.
- Create Credit Score Levels.
- Generate customer segments.

### Step 6: Exploratory Data Analysis (EDA)
- Univariate Analysis
- Bivariate Analysis
- Correlation Analysis
- Behavioral Analysis

### Step 7: KPI Calculation
Key business KPIs include:
- Average Annual Income
- Average Monthly Salary
- Debt-to-Income Ratio
- Credit Utilization Ratio
- Average Outstanding Debt
- Average EMI Burden
- Delayed Payments
- Credit Inquiries
- Credit Score Distribution

### Step 8: Dashboard Development
Interactive visualizations were developed using Power BI to enable business users to explore customer behavior and risk factors.

---

## Key Insights

### Customer Demographics
- Most customers belong to the working-age population.
- Certain occupations contribute significantly to the customer base.

### Income Analysis
- Income distribution is concentrated in low and middle-income groups.
- Higher-income customers generally maintain better credit scores.

### Credit Risk Analysis
- Customers with Poor credit scores have higher debt burdens.
- High credit utilization ratios are strongly associated with poor creditworthiness.
- Customers with multiple loans show higher financial risk.

### Payment Behavior Analysis
- Frequent delayed payments significantly impact credit scores.
- Customers paying only the minimum amount tend to fall into the Poor credit score category.

### Fraud Indicators
- High debt combined with low income indicates elevated risk.
- Excessive credit inquiries may signal suspicious financial behavior.
- Significant changes in credit limits can act as early warning signals.

### Correlation Findings
- Annual Income and Monthly Salary show strong positive correlation.
- Outstanding Debt and EMI are strongly related.
- Credit Utilization Ratio is one of the most important risk indicators.

---

## Dashboard Output

The project includes a fully interactive Power BI dashboard featuring:


### KPI Cards
- Total Customers
- Total Applications
- Fraud Rate
- Average Annual Income
- Average Outstanding Debt
- High Risk Customer Count

### Filters
- Age Group
- Credit Score Category
- Income Group

### Visualizations
- Risk Count by Occupation
- Fraud by Age Group
- EMI vs Credit Score
- Delay from Due Date Analysis
- Credit Utilization Analysis
- High-Risk Trend by Month
- Payment Behavior Analysis
- Credit Score Distribution

The dashboard provides actionable insights for fraud monitoring and credit risk management.

---

## How to Run this Project

### Clone the Repository

```bash
git clone https://github.com/yourusername/banking-fraud-analysis.git
```

### Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn
```

### Run the Jupyter Notebook

```bash
Google Colab notebook
```

### Open Power BI Dashboard

Open the `.pbix` file in Power BI Desktop and interact with the dashboard.

---

## Results and Conclusion

This project successfully identified key financial indicators influencing customer creditworthiness and fraud risk.

The analysis demonstrated that repayment behavior, credit utilization ratio, outstanding debt, and EMI obligations have a stronger impact on credit scores than income alone. Customers with frequent delayed payments, high debt burdens, and excessive utilization were more likely to belong to high-risk categories.

The Power BI dashboard transforms complex banking data into actionable business insights, enabling financial institutions to improve fraud detection, strengthen risk assessment processes, and make informed lending decisions.

Overall, the project highlights the value of data-driven analytics in building safer, more transparent, and more efficient banking systems.

---

## Future Work

Future enhancements for this project include:

- Building Machine Learning models for fraud prediction.
- Developing customer risk scoring algorithms.
- Implementing real-time fraud monitoring systems.
- Integrating additional financial datasets.
- Creating automated alert systems for high-risk customers.
- Deploying the solution as a web-based analytics platform.
- Using AI-powered anomaly detection techniques.

---

## Author

**Jay Vasant Rande**

---

## Contact

### LinkedIn
https://www.linkedin.com/in/jay-rande/?skipRedirect=true

### Email
jayrandecs@gmail.com

---