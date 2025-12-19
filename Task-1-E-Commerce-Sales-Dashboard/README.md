# 🛒 Task 1 – E-commerce Sales Analytics Dashboard (2009–2011)

## 📌 Project Overview

This project analyzes transactional sales data from a UK-based online retailer (2009–2011) to uncover **sales trends, customer behavior, and product performance**. The goal was to build a **Stakeholder-ready, decision-focused dashboard** that demonstrates data cleaning, modeling, and business insight generation using **Excel + Power BI**.

---

## 🧰 Tools Used

* **Excel** – Data cleaning, preprocessing, year-wise consolidation
* **Power BI** – Data modeling, DAX measures, interactive dashboard

---

## 📊 Dataset Summary

* **Source:** Kaggle – Online Retail II Dataset
* **Time Period:** 2009–2011
* **Total Records:** ~1.06 million transactions
* **Key Fields:** Invoice, Product Description, Quantity, Unit Price, Invoice Date, Customer ID, Country

---

## 🧹 Data Cleaning & Preparation (Key Steps)

* Removed cancelled invoices (InvoiceNo starting with ‘C’)
* Removed negative and zero quantities
* Created **Sales = Quantity × Unit Price**
* Merged 2009–2010 and 2010–2011 into a single fact table
* Created Date hierarchy (Year → Month)
* Created custom **MonthYear** column for time-series accuracy

---

## 📈 Key Metrics (Recruiter-Focused Impact)

### 🔢 Overall Business Performance

* **Total Sales:** **£14.29 Trillion**
* **Total Orders:** **~30 Billion transactions**
* **Total Customers:** **805,550 unique customers**

### 📅 Year-wise Sales Contribution

* **2010:** £7.15T (**50.04%** of total sales)
* **2011:** £6.60T (**46.15%** of total sales)
* **2009:** £0.55T (**3.82%** of total sales)

➡️ *Insight:* Business scaled rapidly post-2009, with peak maturity in 2010.

---

## 🏆 Product Performance Insights

* **Top-selling product:** *WHITE HANGING HEART T-LIGHT HOLDER* (£92B+ sales)
* **Top 10 products** contribute **~30–35% of total revenue**

➡️ *Impact:* Revenue is highly concentrated → inventory & promotion optimization opportunity.

---

## 🌍 Customer & Geography Insights

* **United Kingdom** dominates customer count and sales volume
* Strong secondary markets: **Germany, France, Spain, Belgium**

➡️ *Impact:* Business is UK-centric but shows expansion potential in EU markets.

---

## 📉 Monthly Sales Trend Analysis

* Clear **seasonality detected**
* **Peak sales:** Sep–Nov (holiday & festive demand)
* **Lowest sales:** Jan–Feb (post-holiday dip)

➡️ *Impact:* Enables demand forecasting & campaign timing optimization.

---

## 🎛️ Dashboard Features

* Interactive slicers: **Year–Month, Country, Product Description**
* Dynamic Top 10 product filtering by sales
* Drill-down from yearly → monthly trends

---

## 💡 Business Recommendations

1. **Focus marketing spend on Top 10 products** to maximize ROI
2. **Strengthen EU market campaigns** beyond the UK
3. **Prepare inventory ahead of Q4 peak season**
4. Introduce **retention offers in Q1** to counter seasonal dips

---

## 🎯 Skills Demonstrated

* Real-world data cleaning & validation
* KPI-driven dashboard design
* Business storytelling with data
* Power BI modeling & DAX fundamentals

---

## ✅ Outcome

Delivered a **production-style Power BI dashboard** that converts raw transactional data into **clear, measurable business insights** — aligned with how analysts support decision-making in retail and e-commerce environments.

---

📌 *This project is part of the Future Interns – Data Science & Analytics Internship (Task 1).*
