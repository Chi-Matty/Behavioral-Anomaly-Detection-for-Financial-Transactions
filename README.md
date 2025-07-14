# Behavioral-Anomaly-Detection-for-Financial-Transactions

A fraud-focused analysis of transaction anomalies using logic-based thresholds and behavioural metrics.

## 🗂️ Project Summary

This project focuses on anomaly detection in financial transactions using Python and Excel. Suspicious activities were identified using a scoring model based on the following metrics:

    Login attempts ≥ 4
    Transaction duration < 60 seconds
    Transaction amount > 2× the average for that account

Each metric was assigned a weight, and transactions were classified as Suspicious or Legitimate based on total anomaly score. The analysis explored suspicious activity trends over months, customer occupations, transaction channels, and age groups. All findings were visualised and summarised and outputs were exported to Excel for external reporting.

## 🔍 Key Insights

- March 2023 had the highest concentration of suspicious activity, accounting for 15% of all flagged transactions. The surge was largely driven by multiple fraud indicators triggering simultaneously, particularly login attempts ≥ 4, transaction durations < 60 seconds, and unusually high transaction amount relative to typical account behaviour.

- Online and Branch channels each contributed 39% of flagged activities, suggesting that a significant portion of these anomalies occurred on digital platforms such as mobile devices or laptops. This underlines the vulnerability of online banking.

- Engineers were the most affected customer group across all four indicators, which are; frequent login attempts, high-value transactions, fast durations, and online usage. Their consistent exposure may be attributed to greater online activity and higher transaction volumes, making them easier targets for behavioural-based flagging.

- The 25–44 age group showed the highest rate of anomalies. This demographic also aligned closely with high-value transactions and fast transaction duration, reinforcing the need for targeted fraud protocols by age segment.

- Correlation analysis showed the Anomaly Score had the strongest positive relationship with Transaction Amount (0.46), indicating that larger transactions are more likely to be flagged as suspicious.

- It also had a strong negative correlation with Transaction Duration (-0.40), suggesting that shorter transaction sessions often corresponds with fraudulent behavior.

- These behavioural patterns align with known fraud indicators and reinforce the validity of the rule-based detection approach used.

## ✅ Recommendations 

- Prioritize monitoring in March and any month with matching behavioural patterns, especially high login attempts and fast session durations.

- Implement real-time flagging rules that monitor:

        - Login attempts ≥ 4
        - Transaction duration < 60 seconds
        - Transaction value > 2× account average
        - Online channel usage

- Segment risk protocols by age and occupation. Focus on 25–44 age group and Engineering professionals, who show disproportionately high anomaly patterns.

- Apply tighter verification on online transactions, especially for accounts with recent rapid logins or high transaction amount.

- Educate customers about fraud risks and prevention. 

## 🧰 Tools & Technologies

    - Python (pandas, numpy, matplotlib, seaborn)
    - Excel (for final reporting and export)

## 📬 Contact

📧 [Your Email](mathiasmichael2@gmail.com)  
🔗 [LinkedIn](inkedin.com/in/michael-matty)




