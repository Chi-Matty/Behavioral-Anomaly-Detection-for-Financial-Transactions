# Behavioral-Anomaly-Detection-for-Financial-Transactions

A fraud-focused analysis of transaction anomalies using logic-based thresholds and behavioural metrics.

### 🗂️ Project Summary

This project focuses on anomaly detection in financial transactions using Python and Excel. Suspicious activities were identified using a scoring model based on the following metrics:

    Login attempts ≥ 4
    Transaction duration < 60 seconds
    Transaction amount > 2× the average for that account

Each metric was assigned a weight, and transactions were classified as Suspicious or Legitimate based on total anomaly score. The analysis explored suspicious activity trends over months, customer occupations, transaction channels, and age groups. All findings were visualised and summarised with pandas, seaborn, and matplotlib. Outputs were exported to Excel for external reporting.
