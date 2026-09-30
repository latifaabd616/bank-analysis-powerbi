# Customer Churn & Account Activity Analysis

## 📖 Overview

An interactive **Power BI** dashboard for analyzing bank customer data, with a focus on:

- **Customer Churn Rate** and its geographic distribution.
- **Active vs. Inactive Accounts** analysis.
- **Customer distribution by gender and age group**.

This dashboard helps bank management to:

- Identify regions with high churn rates.
- Understand the characteristics of customers likely to leave.
- Develop customer retention strategies targeting the most at-risk segments.

---

## 📸 Dashboard Preview

### 📊 Executive Overview
![Executive Overview](images/Executive%20Overview.png)

### 🗺️ Customer Churn by Geography
![Customer Churn by Geography](images/Customer%20Churn%20by%20Geography.png)

### 📈 More Details
![More Details](images/More%20Details.png)

---

## 📊 Key Performance Indicators (KPIs)

The top section of the dashboard displays the following metrics:

| Metric | Value | Description |
|---|---|---|
| **Total Customers** | 10k | Total number of registered bank customers. |
| **Active Accounts** | 5.2k | Customers with account activity in the last 3 months. |
| **Inactive Accounts** | 4.8k | Customers with no transactions in the last 3 months. |
| **Churned Accounts** | 2,037 | Customers who closed their accounts during the selected period. |
| **Female Ratio** | 55% | Percentage of female customers. |
| **Male Ratio** | 44% | Percentage of male customers. |
| **Average Age** | 38.92 | Average age of customers. |

> **Note:** The sum of Female (55%) and Male (44%) ratios is 99%. Please verify whether there is an additional category (e.g., "Unspecified") or a rounding difference.

---

## 🗺️ Geographic Map: Churn Rate by Region

This map displays the distribution of the **Churn Rate** across geographic regions.

**Key Findings:**

- **Highest churn region:** France.
- **Recommendation:** Focus retention campaigns on high-churn regions and analyze the root causes of account closures there.

---

## 🛠️ Tools & Technologies

- **Power BI Desktop** — Building the data model and interactive visualizations.
- **DAX (Data Analysis Expressions)** — Creating custom measures for churn and activity rates.
- **Power Query** — Data cleaning and transformation (handling missing values, standardizing formats).
- **Data Source:** CSV / Excel / SQL containing customer, account, and transaction data.

---

## 📁 Project Structure

| File / Folder | Description |
|---|---|
| `bank.pbix` | Main Power BI project file. |
| `images/` | Screenshots of the dashboard. |
| `README.md` | This documentation file. |

---

## 🚀 How to Use

1. Download the `.pbix` file from this repository.
2. Open the file using **Power BI Desktop** (version 2023 or later).
3. Explore the dashboard and interact with the **filters** to customize the view by region, gender, or age group.

---

## ⚠️ Important Notes

- The data used in this project is **sample data** for demonstration purposes only and does not contain any real customer information.
- The dashboard is designed to be compatible with desktop displays.
- Additional measures and visualizations can be added as needed.
