
# Credit Card Fraud and Risk Analysis (Power BI)
📊 Overview

This Power BI project explores credit card fraud patterns and highlights risk zones based on transaction types, regions, and months. The dashboard provides actionable insights to financial analysts and security teams for detecting and preventing fraudulent activity.

🔍 Key Objectives
Visualize the total transaction amount by fraud type and transaction category

Analyze fraud risk levels (Low, Medium, High, Critical)

Detect state-wise and month-wise patterns of fraudulent activity

Identify top fraud types, such as Card Not Present, Identity Theft, and Phishing

Help prioritize monitoring and prevention strategies based on data insights

📌 Key Visuals in Power BI
Bar Chart: Transaction amount by fraud type and transaction category

Pie Chart: Transaction share by fraud risk level

Map/Bar Graph: Fraudulent transactions by Indian states

Line Chart/Bar Graph: Monthly trend of frauds

KPI Cards: Fraud rate, total fraud count, critical risk % etc.

🗃️ Dataset (Simulated)
This dashboard is built using a simulated dataset containing:

Transaction_ID

State

Transaction_Category

Fraud_Type

Fraud_Risk (Low/Medium/High/Critical)

Transaction_Amount

Month

Is_Fraud

Note: The dataset is not real and is used for educational purposes only.

⚙️ Tools Used
Power BI Desktop

Power Query (for data transformation)

DAX (for calculated columns and KPIs)

📁 Project Structure

Credit-Card-Fraud-Risk-PowerBI/
├── Dataset/
│   └── credit_card_transactions.csv
├── Screenshots/
│   ├── dashboard-overview.png
│   └── fraud-by-month.png
├── Reports/
│   └── CreditCardFraud.pbix
├── README.md
└── LICENSE

🧠 Insights

States like Maharashtra and Karnataka had the highest number of fraudulent transactions.

Fraud types like Card Not Present and Card Skimming are more prevalent.

Fraud peaks during March and June, indicating seasonal vulnerabilities.

Over 42% of transactions were classified as Low Risk, but 10.7% were Critical and require urgent intervention.

📎 How to Run
git clone 
https://github.com/your-username/Credit-Card-Fraud-Risk-PowerBI.git

Open CreditCardFraud.pbix in Power BI Desktop

Refresh the dataset or replace it with your own

Interact with the filters and visuals
