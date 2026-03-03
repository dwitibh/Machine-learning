**📊 Customer Churn Analysis📌**

**Project Overview** :This project focuses on exploratory data analysis (EDA) and data preprocessing of a customer churn dataset. The goal is to identify patterns and correlations between customer attributes (like tenure and charges) and their likelihood of churning, providing actionable insights for retention strategies.

**🛠 Tech StackLanguage**: PythonLibraries: Pandas, Matplotlib, NumPyTools: Jupyter Notebook
📂 **Dataset Breakdown** :The dataset contains 1,000 customer records with 10 key features:Demographics: Age, GenderAccount Info: CustomerID, Tenure, ContractTypeServices: InternetService, TechSupportFinancials: MonthlyCharges, TotalChargesTarget: Churn (Yes/No)

**🚀 Analysis Workflow**
1. **Data Cleaning & PreprocessingMissing Value Handling**: Identified 297 missing values in the InternetService column and imputed them with blanks to maintain data integrity without dropping rows.Duplicate Check: Verified dataset uniqueness (0 duplicates found).Data Type Validation: Ensured numeric fields (TotalCharges, MonthlyCharges) were correctly typed for calculation.
2.  **Exploratory Data Analysis (EDA)Statistical Profiling**: Generated descriptive statistics to understand the distribution of age, tenure, and spending.Correlation Analysis: * Found a strong positive correlation (0.89) between Tenure and TotalCharges.Analyzed the relationship between MonthlyCharges and total revenue.Segmentation: Grouped data by ContractType and InternetService to identify high-risk segments.
  
📈 **Key Insights**: (Initial)The average customer tenure is approximately 19 months.Monthly charges range from $\$30$ to $\$120$, with a mean of $\$74.39$.High correlation suggests that long-term retention is the primary driver of total customer lifetime value.

🔧** How to UseClone this repository**.
Ensure you have the dataset customer_churn_data.csv in the root directory.
Install dependencies: pip install pandas matplotlib
.Run the Jupyter Notebook to replicate the analysis
.Author: Dwiti,Senior Data Analyst & Power BI Specialist
