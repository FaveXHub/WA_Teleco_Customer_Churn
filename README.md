# WA_Teleco_Customer_Churn
# Telco Customer Churn Analysis

This project analyzes customer churn data from a telecommunications company to understand **why customers leave (churn)** and what factors contribute to their decision.  
The main focus is on **data cleaning, exploratory data analysis (EDA), visualization, and storytelling** to uncover key business insights.


## Project Objectives
- Clean and prepare the dataset for analysis  
- Explore customer demographics and service usage patterns  
- Visualize churn trends and correlations 
- Identify key insights that can guide business decisions  


## Tools & Libraries Used
- **Python**
   ***Pandas*** – for data cleaning and manipulation  
   ***NumPy*** – for numerical operations  
   ***Matplotlib*** – for static visualizations  
   ***Seaborn*** – for detailed statistical plots
- **Google sheets** - for data cleaning, EDA and data Visualization


## Workflow
--> data → raw & cleaned datasets

--> notebooks → analysis notebook (telco_customer_analysis.ipynb)

--> results → saved charts and visualizations and insights (text-based insights summary)

### 1️⃣ Data Cleaning
- Handle missing values and duplicates  
- Convert data types where needed  

### 2️⃣ Exploratory Data Analysis (EDA)
- Understand customer distribution by gender, contract type, payment method, etc.  
- Compare churn vs non-churn customers across multiple factors  
- Identify the strongest churn drivers (e.g., contract type, tenure, monthly charges)  

### 3️⃣ Data Visualization
- Churn Distribution – Bar Chart
→ Shows how many customers churned vs. stayed.

- Churn by Contract Type – Bar Chart
→ Displays how churn rate varies by contract duration (Month-to-month, One year, Two year).

- Churn Rate by Internet Service Type – Bar Chart
→ Visualizes which internet service category has the highest churn (DSL, Fiber optic, None).

- Monthly Charges vs. Tenure – Scatter Plot
→ Shows the relationship between how long a customer has stayed and how much they pay monthlys

  
###  Insights & Storytelling
- Customers with **month-to-month contracts** are more likely to churn.  
- Higher **monthly charges** are linked with increased churn probability.  
- **Electronic check** payment method shows the highest churn rate.  
- Customers with **short tenure** are at higher risk of leaving.  



##  Folder Structure

data/          → raw & cleaned datasets
notebooks/     → analysis notebook (telco_customer_analysis.ipynb)
results/       → saved charts and visualizations
insights/      → text-based insights summary


##  Sample Visualizations
- Churn rate by contract type  
- Monthly charges vs churn  
- Tenure vs churn distribution  
- Payment method impact on churn  



## Dataset Overview
The dataset contains customer information such as:
- **Demographics:** gender, senior citizen, partner, dependents  
- **Services:** phone, internet, streaming, security  
- **Account Info:** contract, payment method, monthly charges, tenure  
- **Target Variable:** Churn (Yes/No)  

---

## Author
**Favour Edet**  
📧 [favouranalyticsai@gmail.com]  
🌍 Data Analyst | Aspiring Data Scientist  

---

## 📜 License
This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.

