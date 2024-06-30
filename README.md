# Online_Fraud_Analytics_Dashboard

![image](https://github.com/Priyanka-TheAnalyst/Online_Fraud_Analytics_Dasboard/assets/129527829/ee2583cc-10b7-4548-a867-91de20ec642a)

# Overview
This project focuses on detecting and analyzing online fraud using a dashboard created in Microsoft Power BI. The goal is to leverage interactive visualizations to gain insights into fraudulent activities and help stakeholders make informed decisions.

# Table of Contents
* Introduction
* Dataset
* Installation
* Dashboard Features
* Results
* Conclusion
* Contributing
* License
  
# Introduction
Online fraud is a significant issue for many businesses. This project aims to create an interactive dashboard to identify and analyze fraudulent activities. The dashboard provides a comprehensive view of fraud patterns, enabling users to detect anomalies and take preventive measures.

# Dataset
The dataset used in this project contains detailed transaction records, including both legitimate and fraudulent transactions. Key columns in the dataset include:

txn_id: Transaction ID
dt_txn_comp: Transaction Date
txn_comp_time: Transaction Completion Time
txn_type: Transaction Type (e.g., Refund, Payment, Withdrawal, Transfer, Fee)
txn_subtype: Transaction Subtype (e.g., Product Refund, Peer-to-Peer, ATM Withdrawal, Inter-bank Transfer, Account Maintenance Fee)
initiating_channel_id: Initiating Channel ID
txn_status: Transaction Status (e.g., Successful, Failed)
error_code: Error Code (if any)
payer_psp: Payer Payment Service Provider
payee_psp: Payee Payment Service Provider
remitter_bank: Remitter Bank
beneficiary_bank: Beneficiary Bank
payer_location: Payer Location
payer_city: Payer City
payer_state: Payer State
payee_location: Payee Location
payee_city: Payee City
payee_state: Payee State
cred_type: Credit Type (e.g., Debit Card, Overdraft, Auto Loan)
cred_subtype: Credit Subtype (e.g., Prepaid Debit Card, Business Overdraft, Used Car Loan)
initiation_mode: Initiation Mode
dt_time_txn_compl: Transaction Completion Date and Time
time_of_day: Time of Day (e.g., Morning, Afternoon, Evening, Night)

# Installation
To run this project, you will need to have Microsoft Power BI installed on your system. You can download and install Power BI from the official website.

# Dashboard Features
The Power BI dashboard includes the following features:

Overview Page: A summary of the total number of transactions, the number of fraudulent transactions, and the total transaction amount.
Transaction Analysis: Interactive visualizations showing the distribution of transactions over time, transaction types, and transaction amounts.
Fraud Detection: Charts and graphs highlighting suspicious patterns, high-risk transactions, and common fraud indicators.
User Behavior: Analysis of user activity, identifying users with unusual transaction patterns.
Geographical Insights: Maps showing the distribution of fraudulent transactions by location.

# Results
The dashboard provides valuable insights into online fraud, helping to:

Identify high-risk periods and transaction types.
Detect users with abnormal transaction behavior.
Highlight geographical hotspots for fraudulent activities.

# Conclusion
This project demonstrates the use of Microsoft Power BI to create a powerful and interactive dashboard for online fraud analytics. The insights gained from this analysis can assist in developing more effective fraud detection and prevention strategies.

# Contributing
Contributions are welcome! If you have any suggestions or improvements, please create a pull request or open an issue.

# License
This project is licensed under the MIT License - see the LICENSE file for details.
