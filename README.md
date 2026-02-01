# Customer Churn Analysis 📊

This project performs **Exploratory Data Analysis (EDA)** on a telecom **Customer Churn dataset** using Python.  
The goal is to understand customer behavior and identify patterns related to churn.

## 📁 Dataset
The dataset contains customer information such as:
- Customer demographics
- Services subscribed
- Contract type
- Payment methods
- Charges
- Churn status

Total records: **7043 customers**

## 🛠 Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## 📌 Data Cleaning Steps
- Converted `TotalCharges` from object to float.
- Replaced blank `TotalCharges` with `0` (for customers with tenure 0).
- Checked for null values.
- Verified duplicate customer IDs.
- Converted `SeniorCitizen` values from `0/1` to `Yes/No` for better readability.

## 📊 Exploratory Analysis
Analysis includes:

- Churn distribution
- Gender vs churn comparison
- Senior citizen churn analysis
- Tenure distribution by churn
- Contract type vs churn
- Percentage churn comparison
- Multiple count plots and histograms

## 📈 Key Observations
- Customers with **month-to-month contracts churn more**.
- **Short tenure customers** are more likely to churn.
- Senior citizens show higher churn percentage.
- Certain payment methods relate to higher churn.

## ▶️ How to Run
1. Clone repository
```bash
git clone https://github.com/yourusername/customer-churn-analysis.git
Install dependencies

pip install pandas numpy matplotlib seaborn
Run notebook or script.

📂 Project Structure
customer-churn-analysis/
│
├── customer_churn.csv
├── churn_analysis.ipynb
└── README.md
🚀 Future Improvements
Feature engineering

Machine learning churn prediction

Model deployment

Dashboard visualization

👤 Author
Sudip Shrestha

