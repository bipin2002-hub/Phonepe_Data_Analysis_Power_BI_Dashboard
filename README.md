# PhonePe UPI Transactions Dashboard 📊

This dashboard was developed to provide a real-time, comprehensive view of UPI transaction activity across India, enabling stakeholders to monitor performance, identify fraud risk, and understand user and merchant behavior at scale.

#  Overview
This dashboard offers a real-time overview of UPI transactions, enabling stakeholders to monitor performance, detect anomalies, and analyze user behavior across multiple dimensions — geography, time, bank, transaction type, and more.

🖼️ Preview

<img width="1242" height="752" alt="image" src="https://github.com/user-attachments/assets/a3355eaf-3e7c-4cdb-be5d-1fdb425bb298" />


# Key Findings

# Overall Performance

> The platform processed 503K transactions totaling ₹442.48M in transaction value.

> The overall success rate stands at 91%, with 7% of transactions failing and a negligible 0.01% pending.

> ₹3.46M was disbursed in cashback, reflecting active user incentive programs.

> 17.09K transactions (~3.4%) were flagged as fraudulent, representing a key area for continued monitoring and risk mitigation.

# Market Position

PhonePe leads the UPI app landscape with 48.26% share of transactions, followed by Google Pay (21.88%) and Paytm (14.89%). Amazon Pay, BHIM, Cred Pay, and WhatsApp Pay collectively account for the remaining ~12%.

# Geographic Distribution

Transaction value is fairly evenly distributed across major states, with Maharashtra (₹45.41M), Karnataka (₹45.09M), and Delhi (₹44.79M) leading.
Kerala is a notable outlier with significantly lower transaction value (₹1.39M), suggesting either lower market penetration or a data/regional gap worth investigating.

# Banking Partners

HDFC Bank (₹58.92M) and SBI (₹58.37M) are the top-performing banking partners by transaction value, with the remaining top 8 banks (Kotak Mahindra, Canara, ICICI, Axis, Bank of Baroda, PNB) clustered closely between ₹51M–₹56M.

# Transaction Behavior

P2M (Person-to-Merchant) payments dominate transaction value at ₹188.77M (43%), more than double the next largest category, P2P (₹87.74M) — indicating the platform is used primarily for merchant payments over peer transfers.
Bill Payments, Online Shopping, Recharge, Subscription, and Wallet Transfer make up the remaining transaction mix.

# Time-Based Patterns

Transaction activity peaks between 6 PM–8 PM, with the highest hourly value recorded at ₹46M around 7 PM.

Activity is lowest overnight (12 AM–5 AM), consistent with expected consumer usage patterns.

Friday and Saturday show the highest transaction counts across most hours, suggesting elevated weekend spending behavior.
Strategic Implications

Fraud monitoring should remain a priority given the ~3.4% fraud rate; deeper segmentation by merchant category, failure reason, or age group could help isolate root causes.

Regional expansion opportunity exists in states like Kerala, where transaction value significantly lags peers.

Merchant payment infrastructure (P2M) is the core value driver and warrants continued investment in merchant onboarding and reliability.

Peak-hour capacity planning (6–8 PM, weekends) should be prioritized to maintain success rates during high-load periods.
Filters & Segmentation Available

The underlying dashboard supports drill-down analysis by Age Group, Payment Mode, City, Gender, Merchant Name, Merchant Category, and Failure Reason — enabling further investigation into any of the trends highlighted above.

Prepared using Power BI, based on UPI transaction data across Indian states, banks, and UPI applications.

# 📂 Repository Structure
├──Phone pay Data Dashboard.pbix      # Power BI project file
├── [data/ ](https://docs.google.com/spreadsheets/d/1TPhloLNhXTmI0yiV80kwiiezonLJApKF/edit?usp=drive_link&ouid=107391669064925097398&rtpof=true&sd=true)                            # Source dataset(s) used for the dashboard
├── Phone pay Data Dashboard.pdf                           # Screenshots and preview images
└── README.md                         # Project documentation


# 📊 Dataset

(Describe your dataset here — source, size, fields such as Transaction ID, Amount, UPI App, Bank, State, City, Age Group, Gender, Transaction Type, Status, Hour, Weekday, Merchant Name/Category, Failure Reason, etc.)

Note: This dataset appears to be simulated/synthetic data created for analytical and portfolio purposes, not actual PhonePe transaction records.

👤 Author

# Bipin Chandra

📄 License

This project is open-source and available for learning and portfolio purposes. Add a license (e.g., MIT) if you plan to share it publicly.
