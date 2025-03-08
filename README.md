# 💳 SQL Portfolio Project: Credit Card Transactions Analysis

## 📊 Project Overview
This project involves analyzing credit card transactions in India to uncover spending patterns, city-level insights, and card-type trends using **SQL Server**. The dataset contains transaction records across cities and different card types like Gold, Silver, Platinum, and Signature.

The goal of this project is to demonstrate practical SQL skills by answering critical business questions that can drive insights for banks, financial institutions, or credit card companies.

## 📂 Dataset
- **Source:** [Kaggle - Credit Card Transactions](https://www.kaggle.com/datasets/thedevastator/analyzing-credit-card-spending-habits-in-india)
- **Table Name:** `credit_card_transactions`
- **Modifications:**
  - Changed all column names to lowercase.
  - Replaced spaces with underscores in column names.
  - Adjusted column data types for accurate analysis.

## 📜 SQL Queries
I wrote **9 SQL queries** to answer various business questions and gain insights from the data.

### ✅ 1. Top 5 Cities with Highest Spends
- Identified the top 5 cities contributing the most to overall credit card spending along with their percentage contribution.

### ✅ 2. Highest Spend Month per Card Type
- Determined the month with the highest spending for each card type.

### ✅ 3. Cumulative Spend of 1 Million per Card Type
- Extracted transaction details when cumulative spending reached **1 million** for each card type.

### ✅ 4. City with Lowest Spend for Gold Card
- Found the city where Gold card spending contributed the least percentage.

### ✅ 5. Highest and Lowest Expense Type per City
- Identified the highest and lowest spending category per city.

### ✅ 6. Percentage Spend by Females for Each Expense Type
- Calculated the percentage contribution of female spending across all expense types.

### ✅ 7. Highest MoM Growth in Jan-2014
- Identified the card and expense type combination that showed the highest **month-over-month growth** in January 2014.

### ✅ 8. City with Highest Weekend Spend-to-Transaction Ratio
- Found the city with the highest ratio of total spending to the total number of transactions during weekends.

### ✅ 9. City that Reached 500 Transactions Fastest
- Determined which city reached **500 transactions** in the shortest number of days from their first transaction.

## 🧠 Skills Demonstrated
This project demonstrates my ability in:
- ✅ Writing complex SQL queries.
- ✅ Performing data analysis and generating insights.
- ✅ Using **window functions** like `ROW_NUMBER()`, `SUM() OVER()`, `LAG()`.
- ✅ Performing time-based analysis using `EXTRACT()`, `DATEDIFF()`.
- ✅ Handling data transformations and cumulative calculations.

## 💼 Why This Project Stands Out
- **Real-World Data:** This dataset is very similar to actual credit card transaction datasets, making the insights realistic.
- **Practical Insights:** The queries are designed to uncover actionable business insights that banks and financial institutions would care about.
- **Professional Documentation:** The project is presented in a clean, structured manner to attract the attention of recruiters.

## 💾 How to Run This Project
1. **Download the Dataset:** [Download Here](https://www.kaggle.com/datasets/thedevastator/analyzing-credit-card-spending-habits-in-india)
2. **Import the Data into SQL Server:**
   - Rename columns to lowercase.
   - Replace spaces with underscores.
   - Adjust data types accordingly.
3. **Run the SQL Queries:**
   - Execute each query in the `credit_card_transactions` table.

## 📂 Repository Structure
```
|-- Credit Card Transactions Project
    |-- credit_card_transactions.sql   <-- Contains all SQL queries
    |-- README.md                      <-- Project Documentation
```

## 💡 Insights
The project highlights the following business insights:
1. **City-Level Spend Analysis:** Certain cities contribute significantly to total spending.
2. **Card-Type Preferences:** Different card types show spending patterns by month and category.
3. **Gender-Based Analysis:** Female contribution to spending varies significantly by expense type.
4. **Fastest Growing Transactions:** Certain cities quickly reached high transaction counts.

## 🚀 Next Steps
I plan to extend this project by:
- ✅ Creating visualizations in **Power BI** or **Tableau**.
- ✅ Creating a stored procedure to automate cumulative spend analysis.
- ✅ Building a predictive model using Python for future spending trends.

## 📬 Connect With Me
If you liked this project or would like to collaborate, feel free to connect with me on:
- 💼 [LinkedIn](https://www.linkedin.com/in/imamul-hasan-5420b1241/)
- 📧 Email: your.email@gmail.com

## ⭐ Star This Repository
If you found this project helpful, please consider giving it a **star** ⭐ on GitHub.

## 📜 License
This project is for educational purposes only and uses publicly available data from Kaggle.

