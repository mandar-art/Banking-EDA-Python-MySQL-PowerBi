# 🟦 **Problem Statement**

Banks and financial institutions face a major challenge: **lending money without increasing the risk of defaults**.
Risk analytics helps banks evaluate a customer’s ability to repay loans by analyzing financial behavior, income levels, existing liabilities, and asset ownership.

The objective of this analysis is to:

* Develop a basic understanding of **risk analytics in banking**
* Identify **key financial indicators** that influence customer risk
* Understand how customer data can be used to **minimize losses while lending**
* Extract **important insights** from the dataset
* Present a clear **result and conclusion** on factors affecting loan risk

# 🟧 **Tools and Technologies & Method**
Tools & Technologies:

* SQL (MSSQL Server): Used to import data from csv file. Created database and table to setup connection with Python.
* Python : Completed Data Profiling, Data Cleaning and Exploratory Data Analysis in Python
* Power BI: Used for connecting to the server, data modeling, calculating advanced DAX measures (especially Time Intelligence), and creating dynamic visualizations.

# 🟧 **Dataset Information**
The dataset contains **3,000 banking customers** with **25 attributes**, covering:

### **Customer Profile**
* Age
* Nationality
* Gender
* Occupation
* Location ID

### **Financial Indicators**
* Estimated Income
* Superannuation Savings
* Bank Deposits
* Checking Accounts
* Saving Accounts
* Credit Card Balance
* Amount of Credit Cards
* Bank Loans
* Business Lending
* Foreign Currency Accounts
* Properties Owned

### **Risk Variable**
* **Risk Weighting (1 to 5)**
  * 1 = Low Risk
  * 5 = High Risk
    This is the target metric that helps assess customer lending risk.

# 🟩 **Important Insights From the Data**

### 🔹 **1. Income strongly influences risk**
`Estimated Income` has the **highest correlation (0.66)** with Risk Weighting.
Higher income in this dataset is surprisingly linked with **higher risk**, indicating:
* Customers earning more may have **higher credit exposure**
* They may take bigger loans, increasing risk score

### 🔹 **2. High savings also link to higher risk**
`Superannuation Savings` shows a **0.50 correlation**, meaning:
* Customers with larger savings still carry risk
* Indicates the bank may weigh other liabilities heavily

### 🔹 **3. Large loan amounts increase risk**
Both **Bank Loans (0.42)** and **Business Lending (0.41)** have strong positive relationships with risk:
* Higher outstanding loan values increase risk classification

### 🔹 **4. High credit card balances signal greater risk**
`Credit Card Balance (0.40)` is also a key influencer:
* Customers with large credit card debt are riskier to lend more to

### 🔹 **5. Multiple accounts = higher exposure**
Checking, Saving, and Deposits all have moderate correlation (~0.34–0.37):
* More bank activity may indicate higher financial engagement and exposure

### 🔹 **6. Age and Gender do NOT influence risk**
Age has **no correlation**, Gender has **negative low correlation**:
* Risk is **not dependent on demographic factors**
* It is purely driven by **financial behavior and liabilities**
  
# 🟦 **Result**
**The major drivers of loan/lending risk are:**
### ✔ Estimated Income
### ✔ Superannuation Savings
### ✔ Loan Amounts
### ✔ Business Lending Exposure
### ✔ Credit Card Balances
### ✔ Large Bank Account Balances
Demographics like **age, gender, location** have almost **no effect** on risk.

This confirms that **financial exposure**, not personal background, determines customer risk levels.

# 🟩 **Conclusion**
Risk analytics allows banks to make informed decisions by analyzing customer financial behavior.
From this dataset, the following conclusions can be drawn:
* Customers with **higher income, significant savings, and large outstanding loans** tend to fall into **higher risk categories**.
* Heavy engagement with multiple banking products (credit cards, foreign currency accounts, checking accounts) indicates higher overall exposure, raising risk levels.
* Lenders should carefully evaluate **total liabilities**, not just income levels, before approving loans.
* Using this data-driven approach, banks can minimize **loan defaults** and optimize **credit decision-making**.

#  🟦  **Author and Contact**

Author: Mandar Manjare.

Email: mandar.manjare07@gmail.com          Linkedin: www.linkedin.com/in/mandar-manjare-24b8b1117
