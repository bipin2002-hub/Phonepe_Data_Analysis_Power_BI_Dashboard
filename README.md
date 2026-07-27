PhonePe UPI Transactions Dashboard 📊

A real-time Power BI dashboard providing a comprehensive overview of UPI transactions processed through PhonePe and other UPI apps. The dashboard tracks transaction volume, value, success rates, fraud detection, and behavioral patterns across states, banks, transaction types, and time

📌 Overview
This dashboard offers a real-time overview of UPI transactions, enabling stakeholders to monitor performance, detect anomalies, and analyze user behavior across multiple dimensions — geography, time, bank, transaction type, and more.

🖼️ Preview

<img width="1242" height="752" alt="image" src="https://github.com/user-attachments/assets/a3355eaf-3e7c-4cdb-be5d-1fdb425bb298" />


🎯 Key Metrics (KPIs)
Metric	Description

Total Transaction	Total count of UPI transactions processed

Total Amount	Total value (INR) of all transactions

Total Cashback	Total cashback disbursed to users

Success Rate	Percentage of successful transactions

Total Fraud	Count of transactions flagged as fraudulent

📈 Visualizations Included

Transaction Amount (INR) Over Time (Daily) — Area chart tracking daily transaction value trends across the month

Transactions by UPI App — Donut chart showing market share split (PhonePe, Google Pay, Paytm, Amazon Pay, BHIM, Cred Pay, WhatsApp Pay)

Transactions by Status — Donut chart of Success / Failed / Pending / Refunded transactions

Transaction Amount (INR) by State — Choropleth map + ranked bar chart of transaction value across Indian states

Transaction Amount by Bank — Bar chart comparing transaction value across major banks (HDFC, SBI, ICICI, Axis, Kotak, Canara, PNB, BoB)

Total Amount by Transaction Type — Bar chart across P2M, P2P, Bill Payment, Online Shopping, Recharge, Subscription, and Wallet Transfer

Total Amount by Hour — Hourly distribution of transaction value to identify peak usage windows

Total Transactions by Day & Hour — Heatmap-style matrix showing transaction volume across weekdays and hours

🎛️ Interactive Filters (Slicers)

The dashboard supports dynamic slicing across:

Age Group,
Payment Mode,
City,
Gender,
Merchant Name
,Merchant Category
Failure Reason.

🛠️ Tools & Technologies

Power BI Desktop — Dashboard development and data modeling

DAX — Measures for KPIs, success rate, and aggregations

Power Query (M) — Data cleaning and transformation

TomTom / OpenStreetMap / Microsoft Maps — Geospatial visualization for state-wise data

📂 Repository Structure
├──Phone pay Data Dashboard.pbix      # Power BI project file
├── [data/ ](https://docs.google.com/spreadsheets/d/1TPhloLNhXTmI0yiV80kwiiezonLJApKF/edit?usp=drive_link&ouid=107391669064925097398&rtpof=true&sd=true)                            # Source dataset(s) used for the dashboard
├── Phone pay Data Dashboard.pdf                           # Screenshots and preview images
└── README.md                         # Project documentation


📊 Dataset

(Describe your dataset here — source, size, fields such as Transaction ID, Amount, UPI App, Bank, State, City, Age Group, Gender, Transaction Type, Status, Hour, Weekday, Merchant Name/Category, Failure Reason, etc.)

Note: This dataset appears to be simulated/synthetic data created for analytical and portfolio purposes, not actual PhonePe transaction records.

👤 Author

Bipin Chandra

📄 License

This project is open-source and available for learning and portfolio purposes. Add a license (e.g., MIT) if you plan to share it publicly.
