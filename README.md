#  Customer Churn Analysis

This project explores the **IBM Telco Customer Churn dataset** to understand customer churn behavior, calculate churn rates, and visualize key factors that influence churn.

---

## Project Overview

Customer churn is when customers stop using a company's service. Identifying churn drivers helps businesses reduce customer loss.  
In this project, I:

- Cleaned and prepared the dataset (handled missing values, converted data types)
- Calculated overall churn rate
- Explored churn patterns by:
  - Gender
  - Partner status
  - Tenure months (new vs old customers)
  - Tech support availability
  - Customer importance metrics (CLTV, Churn Score)
- Visualized churn insights with pie charts, bar plots, and horizontal bar charts

---

##  Dataset

Dataset: [IBM Telco Customer Churn Dataset](https://www.kaggle.com/datasets/yeanzc/telco-customer-churn-ibm-dataset)  
Downloaded using Kaggle API.

---

##  Key Insights

- **Overall churn rate:** ~26.6%  
- **Tech support customers churn less:** Customers with tech support churn significantly less compared to those without support.
- **Tenure matters:** New customers (with tenure below average) are more likely to churn.
- **High-value customers churn too:** Some important customers (high CLTV, long tenure) are still leaving, indicating potential service issues.

---

##  Installation & Usage

  ### Clone the repository:
    git clone https://github.com/yourusername/customer-churn-analysis.git
    cd customer-churn-analysis 

  ### Install dependencies:
    pip install -r requirements.txt

  ### Run the Jupyter notebook:
    jupyter notebook customer_churn_analysis.ipynb
---

## Requirements

- numpy
- pandas
- matplotlib
- openpyxl

---

##  Author

- Debkanta Mishra
- Email: 
- LinkedIn: https://linkedin.com/in/your-profile
- GitHub: https://github.com/yourusername
