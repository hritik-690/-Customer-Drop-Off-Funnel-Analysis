# -Customer-Drop-Off-Funnel-Analysis
# 📉 Customer Drop-Off Funnel Analysis

This project analyzes customer drop-offs in the loan application funnel at a Finance DSA (Direct Selling Agent) firm. The goal is to identify where users exit the process — from lead to loan approval — and uncover actionable insights to improve conversion rates and operational efficiency.

---

## 🏢 Business Context

As a Data Analyst at a financial consulting firm operating as a DSA, we generate leads through multiple channels (Facebook, Google Ads, WhatsApp, Referrals, etc.), and connect potential customers with banks or NBFCs based on their profiles.

However, many customers drop off at various stages of the funnel — from call attempts to final loan approvals.

---

## 🎯 Objective

- Quantify customer drop-off at each funnel stage
- Visualize bottlenecks
- Identify drop-off patterns by lead source
- Recommend improvements to increase conversions

---

## 📁 Dataset

A simulated dataset of 1,000 customer interactions was created with the following funnel stages:

| Column              | Description                                      |
|---------------------|--------------------------------------------------|
| `customer_id`       | Unique customer ID                              |
| `lead_source`       | Source of lead (Facebook, WhatsApp, etc.)       |
| `call_status`       | Whether the customer answered the initial call  |
| `verification_status` | KYC verification status                        |
| `document_upload`   | Whether the customer submitted documents        |
| `bank_forwarded`    | Whether the profile was forwarded to banks/NBFCs|
| `loan_approved`     | Final loan approval status                      |
| `timestamp`         | Time of first interaction                       |

📄 File: [`customer_dropoff_funnel.csv`](./customer_dropoff_funnel.csv)

---

## 🛠 Tools & Technologies

- Python (Pandas, Matplotlib)
- Jupyter Notebook
- CSV data processing
- (Optional) Power BI / Tableau for dashboarding

---

## 📊 Key Analyses

- 📈 Funnel visualization from lead to approval
- 📉 Drop-off rate between funnel stages
- 📊 Segment analysis by `lead_source`
- 📋 Recommendations based on findings

---

## 📷 Sample Output

![Funnel Chart Example](assets/funnel_chart_example.png)

---

## 🔍 Insights & Recommendations

- **Document upload** stage had the highest drop-off (~30%) → add customer reminders or improve UX
- **WhatsApp leads** had 20% lower verification rates → investigate lead quality
- **Referral leads** showed higher conversion → allocate more budget to referrals

---

## 💡 Future Enhancements

- Add time-based trends (e.g., weekly drop-off)
- Automate weekly report generation
- Streamlit web app for real-time interaction
- Connect to live CRM or SQL database

---

## 📁 Project Structure

