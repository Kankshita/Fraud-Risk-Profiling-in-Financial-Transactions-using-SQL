# Fraud Risk Profiling in Financial Transactions using SQL
SQL-based fraud analytics project analyzing 555K+ financial transactions to identify fraud patterns, risk concentration, and behavioral insights.

## 🎯 Objective

To analyze financial transaction data and identify fraud patterns, risk concentration, and behavioral trends using SQL.

## 📁 Project Structure

fraud-analytics-sql/

│ 

├── schema.sql       # Table creation scripts (DDL)

├── queries.sql      # Analytical SQL queries (KPIs, fraud insights)

├── etl.py           # Data loading & transformation logic

└── README.md        # Project overview and insights



## 📊 Key Insights

- Analyzed 555K+ transactions with ~2.1K fraud cases (~0.39% fraud rate)
- Identified "shopping_net" as the highest fraud category by both count and transaction value
- Observed peak fraud activity during late-night hours (10 PM – 11 PM)
- Detected repeat suspicious transaction patterns across specific users and merchants


## 💡 Business Implication

- Fraud monitoring systems should prioritize high-risk categories (e.g., online transactions) and late-night time windows to improve detection efficiency  
