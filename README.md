Here's the revised README with your requested changes:

---

# 📊 Sangam Bank Credit Card Project

## 📌 Project Overview

Sangam Bank, a legacy financial institution based in Hyderabad, is exploring a new line of credit cards to expand its product offerings. AtliQ Data Services proposed a pilot analysis to help the bank understand key customer demographics and spending insights. This project uses sample data from 4,000 customers to profile key customer segments, identify spending patterns, and recommend credit card features tailored to customer needs.

## 🛠️ Project Steps

### 1. ASK
**Stakeholder:** Mr. Bashnir Rover, Strategy Director at Sangam Bank  
**Questions to Address:**
- **Demographic Classification:** Segment customers by age, gender, occupation, etc., and derive insights based on these groups.
- **Spending Insights:** Identify major spending categories and analyze spending by occupation, gender, city, and age.
- **Key Customer Segments:** Define high-value customer segments to target with the new credit cards.
- **Feature Recommendations:** Propose credit card features that align with the spending and demographic patterns identified.

### 2. PREPARE
**Data Source:** [Code Basics Platform](https://shorturl.at/EmieW)  
**Data Structure:**
- **`dim_customers.csv`:** Contains customer demographics.
- **`fact_spends.csv`:** Tracks monthly spending by category and payment type.
- **`meta_data.txt`:** Describes data attributes.

### 3. PROCESS
**Tools Used:**  
- **Data Cleaning:** Microsoft Excel
- **Data Analysis & Visualization:** Power BI

**Data Preparation Tasks:**
- Removed duplicates and checked for data gaps using Excel functions.
- Standardized location data (e.g., “Delhi NCR” changed to “New Delhi”).

### 4. ANALYZE
**Power BI Analysis Metrics:**
- **Avg. Income Utilization %**: `avg_spends / avg_income`, indicating likelihood of credit card usage.
  
**Key Performance Indicators (KPIs):**
- **Annual Expenditure**: `Expenditure * 2`
- **Average Monthly Spend**: Average of monthly spends
- **Customer Count**: Total unique customers
- **Utilization by Payment Type**: e.g., Credit Card, Net Banking, UPI

### 5. SHARE
Explore the [Live Power BI Dashboard](https://shorturl.at/EmieW) showcasing insights on customer demographics, spending patterns, and utilization trends.

---

## 🔍 Insights and Findings

- **Customer Demographics:** Largest age group is 25-35, with Mumbai housing the highest number of customers.
- **Spending Patterns:** Credit cards are the top payment method with a utilization rate of 17.45%, peaking in September.
- **Income Utilization:** Males show higher income utilization at 44.39% compared to females at 39.92%.
  
## 🎯 Recommendations

1. **Seasonal Promotions:** Offer cashback or EMI options in September and August to capture festive season spend.
2. **Target Audience:** Focus on married males aged 25-34 in IT, particularly in Mumbai, for high-value credit offerings.
3. **Rewards on Bills and Groceries:** Incentivize spending in top categories (e.g., Bills and Groceries) with reward points.
4. **Integration with UPI Apps:** Promote indirect credit card usage by integrating credit card options within UPI apps.

---

### 🛠 How to Use This Repository
1. **Clone the Repo**: Clone this project from GitHub.
2. **Set Up Data**: Use provided data files to replicate the analysis.
3. **Analyze**: Explore and modify the Power BI dashboard for deeper insights.

---

Thank you for reviewing this project!
