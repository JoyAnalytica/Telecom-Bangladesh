# 📊 Telecom Analytics Dashboard

An end-to-end Power BI dashboard project designed to analyze telecom operations, financial performance, customer experience, and churn patterns in Bangladesh. The project provides actionable insights to optimize revenue, improve customer retention, and understand regional network performance.

---

## 🛠️ Tech Stack & Skills Demonstrated
*   **Business Intelligence Tool:** Power BI Desktop
*   **Data Modeling:** Star Schema (Fact and Dimension tables)
*   **DAX (Data Analysis Expressions):** Created custom measures for KPI tracking (ARPU, Churn Rate, VAS Adoption)
*   **Data Transformation:** Power Query (Data cleaning, handling missing values, and data type formatting)

---

## 🎛️ Global Filters (Slicer Panel)
Every page includes a dynamic left-side slicer panel for granular data exploration:
*   **Churned Status** (All / Churned / Retained)
*   **Churn Risk Score** (High, Medium, Low Risk)
*   **NPS Score** (Promoters, Passives, Detractors)
*   **Roaming Enabled** (Yes / No)
*   **Auto Renewal** (Enabled / Disabled)

*   ## 📈 Dashboard Breakdown
*   <img width="1448" height="816" alt="Screenshot 2026-06-21 205142" src="https://github.com/user-attachments/assets/336ed836-d524-4876-b288-22b53fcf6e4b" />

### 🟢 Table 1: Financial & Operator Overview
*This page focuses on key revenue drivers, billing trends, and market share distribution among operators.*

#### 🔑 Key Metrics (KPIs)
*   **Total Customers:** 100K
*   **Total Revenue:** 37.32M BDT
*   **Avg Monthly Bill:** 405.11 BDT
*   **ARPU (Avg Revenue Per User):** 405.11 BDT

#### 📊 Visualizations & Insights
| Chart Title | Chart Type | Key Data Points / Insights |
| :--- | :--- | :--- |
| **Monthly Bill By Operator** | Donut Chart | Market dominated by Grameenphone (45%), followed by Robi (28%) and Banglalink (18%). Teletalk (5%) and Airtel (4%) hold smaller shares. |
| **Customers Segment By Bill** | Pie Chart | Student segment contributes highest revenue (12.2M), closely followed by Business (10.2M) and Rural (8.0M). |
| **Plan Type By Bill** | Donut Chart | Prepaid plans generate the major share of billing (24.17M) compared to Postpaid (16.34M). |
| **Monthly Bill By District** | Horizontal Bar | Dhaka division leads revenue generation with 14.1M, followed by Chattogram at 8.1M. |
| **Monthly Recharge Bill** | Line Chart | Highlights seasonal trends, peaking in December (3.53M) and January (3.51M), with a noticeable dip in February (3.12M). |

---


<img width="1443" height="809" alt="Screenshot 2026-06-21 205156" src="https://github.com/user-attachments/assets/5b6dda59-fa85-461b-88b7-13b787e382b7" />

### 🔵 Table 2: Customer Experience & Service Usage
*This page analyzes service quality, network preference, customer complaints, and payment behaviors.*

#### 🔑 Key Metrics (KPIs)
*   **Avg Call Minutes:** 199.48 mins
*   **Avg Data Usage:** 2.69 GB
*   **Complaint Rate:** 34.77%
*   **Avg NPS Score:** 5.49 / 10

#### 📊 Visualizations & Insights
| Chart Title | Chart Type | Key Data Points / Insights |
| :--- | :--- | :--- |
| **Complaint By Customers** | Bar Chart | 65.23K customers had no complaints. Among issues, **Network Issue** (9.89K) and **Billing Error** (7.95K) are the most frequent. |
| **Internet Type By Monthly Bill** | Donut Chart | Daily high-volume packs (1GB/day at 10.1M and 2GB/day at 8.2M) are preferred over monthly lump-sum packs. |
| **Total Customers By City** | Horizontal Bar | Customer concentration is highest in Dhaka (35K) and Chattogram (20K), matching the revenue trend. |
| **Operator Wise Churned Rate** | Donut Chart | Churn trends mirror operator market shares, indicating consistent market-wide competition. |
| **Customer By Payment Method** | Vertical Bar | Mobile Financial Services (MFS) dominate: **bKash** is the top payment mode (40K), followed by **Nagad** (25K). |
| **Network Type By Monthly Bill** | Donut Chart | **4G** is overwhelmingly the dominant network type, accounts for 28.4M of total billing. |

<img width="1444" height="825" alt="Screenshot 2026-06-21 205210" src="https://github.com/user-attachments/assets/ac6ceb36-b280-4ceb-8ba0-a79b2a216eb9" />

### 🟡 Table 3: Geographical & Granular Data View
*An advanced drill-down page combining deep customer-level analytics with geographical mapping.*

#### 🔑 Key Metrics (KPIs)
*   **Region Revenue Rank:** #1
*   **Churn Rate:** 8.27%
*   **VAS (Value Added Services) Adoption Rate:** 29.95%
*   **Total Active Revenue:** 37.32M BDT

#### 📊 Visualizations & Insights
*   **Granular Customer Data Table:** A comprehensive tabular view mapping unique `customer_id` with their exact monthly billing, district region, active network type (2G/3G/4G/5G), and handset tier (`Smartphone (Premium)`, `Mid`, or `Budget`). This allows account managers to target high-value customers.
*   **Geographical Map (Bangladesh Map Visual):** Uses spatial data points to visually represent regional revenue density across Dhaka, Chittagong, Sylhet, Khulna, and other key divisions. 

---

## 💡 Key Business Recommendations Based on Insights
1.  **Network Optimization:** Since **Network Issues** and **Call Drops** are the top drivers for customer complaints, infrastructure upgrades should be prioritized in lower-performing clusters.
2.  **MFS Partnerships:** Given that **bKash** and **Nagad** make up the vast majority of customer payments, launch targeted cashback or recharge campaigns through these MFS channels.
3.  **Targeted Retention for High-Value Segments:** Leverage the **Granular Customer Table** to identify premium tier smartphone users with high monthly bills who show a "High Churn Risk Score" and offer them customized VAS loyalty programs.


