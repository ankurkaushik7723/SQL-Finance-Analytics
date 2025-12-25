# 📊 Atliq Hardware Sales & Business Analytics Project

---

## 🏢 Business Overview
**Atliq Hardware** is a leading hardware manufacturer operating across multiple regions and customer segments.  
The company aims to leverage data-driven insights to improve **sales performance, profitability, and operational efficiency**.

---

## 🎯 Project Objective
The primary objectives of this project are to:
- Analyze sales performance across markets and fiscal years  
- Build a scalable and optimized **analytical data model**  
- Enable stakeholders to make **data-backed business decisions**

---

## ❓ Problem Statement
Atliq Hardware faced several analytical challenges:
- Fragmented and unstructured sales data  
- Limited visibility into product and customer performance  
- Difficulty in tracking KPIs across custom fiscal years  

This project addresses these challenges using structured data modeling and analytics.

---

## 🗂️ Data Model
The project follows a **Star Schema** design to ensure efficient querying and reporting.

📐 Dimension Tables

Dimension tables provide contextual information and are used to slice and filter data.

dim_customer

Customer name

Market

Region

Customer segment

dim_product

Product name

Category

Variant

➡️ These tables are denormalized to reduce joins and improve performance.

⭐ Fact Tables

Fact tables store measurable business data and reference dimension tables via foreign keys.

fact_sales_monthly

fact_forecast_monthly

fact_gross_price

fact_freight_cost

fact_manufacturing_cost

fact_pre_invoice_deductions

fact_post_invoice_deductions

📌 Each fact table contains:

Foreign keys (Customer, Product, Date)

Metrics such as sales quantity, cost, revenue, deductions

---

## 🧮 Fiscal Year Logic
- Custom fiscal year mapping implemented  
- Supports accurate **Year-over-Year (YoY)** analysis  
- Aligns reporting with business financial cycles  

---

## 🔄 Project Workflow (Kanban Methodology)
The project execution followed an **Agile Kanban approach**:

1. Requirement Gathering  
2. Data Understanding  
3. Data Modeling  
4. Data Transformation & SQL Analysis  
5. Dashboard Development  
6. Review & Optimization  

---

## 🛠️ Tools & Technologies
- **SQL** – Data extraction, transformation, and analysis
- **Excel** – Data validation and exploration  
- **GitHub** – Version control and documentation  

---

## 📈 Key Insights
- Identified top-performing products and markets  
- Highlighted underperforming regions and customer segments  
- Improved visibility into revenue, cost, and profit trends  
- Enabled stakeholder-friendly analytical reporting  

---

## 📌 Key Learnings
- Designing scalable **Star Schema data models**  
- Handling custom fiscal year calculations  
- Applying business logic to raw transactional data  
- Translating analytical findings into actionable insights  

---

## 🚀 How to Use This Project
1. Clone the repository  
2. Review SQL scripts for data preparation  
3. Explore dashboards for insights  
4. Extend the data model for further analysis  

---

## 📬 Contact
**Ankur Kaushik**  
📧 ankurkaushik1288@gmail.com  
🔗 https://www.linkedin.com/in/ankur-kaushik87/

---

⭐ If you found this project helpful, consider giving the repository a star!
