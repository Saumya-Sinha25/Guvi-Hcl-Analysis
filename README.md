# 📊 Interactive Sales & Performance Dashboard for E-commerce

## 📋 Project Overview  
This repository contains the files for an **interactive business intelligence dashboard** built with **Power BI**.  
As a BI Analyst, I was tasked with analyzing a real-world business scenario to help stakeholders make **data-driven decisions**.  
This project uses the **Olist E-commerce dataset** to uncover key insights into sales trends, regional performance, and top product categories.  

---

## 🎯 Business Problem & Objective  
The core objective is to provide the **management of the Olist marketplace** with a clear and interactive tool to analyze business performance.  
The dashboard is designed to answer critical questions such as:  

- 📌 What are our key performance indicators (KPIs) for sales and order volume?  
- 🌍 Which geographic regions are our primary markets?  
- 🛒 Which product categories drive the most revenue?  
- 🚚 What is the efficiency of our order fulfillment process?  

---

## 🛠️ Tools & Technologies  
- **Data Visualization & BI:** Power BI Desktop  
- **Data Transformation (ETL):** Power Query  
- **Data Modeling & Calculations:** DAX (Data Analysis Expressions)  

---

## 📊 The Dataset  
The analysis is based on the **Brazilian E-Commerce Public Dataset by Olist**, a large, anonymized dataset of **100,000+ orders (2016–2018)**.  

- **Source:** [Kaggle - Olist E-commerce Dataset](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)  
- **Structure:** The dataset consists of multiple relational tables. The following four were used to build the data model:  
  - `olist_orders_dataset.csv`  
  - `olist_customers_dataset.csv`  
  - `olist_order_items_dataset.csv`  
  - `olist_products_dataset.csv`  

---

## ⚙️ Project Workflow  
The project followed a **standard BI workflow**:  

1. **Data Extraction:** Connected to the four core CSV files.  
2. **Data Transformation (ETL):** Cleaned data, handled missing values, verified data types, and ensured integrity using **Power Query**.  
3. **Data Modeling:** Built a **star schema** data model in Power BI for accurate and efficient analysis.  
4. **DAX Calculations:** Created custom measures/columns such as **Total Sales, Total Orders, and Delivery Status**.  
5. **Dashboard Design:** Developed an intuitive, **single-page dashboard** with visuals to present insights clearly.  

---

## 💡 Key Insights & Recommendations  

- **Insight 1: Geographic Dominance of São Paulo**  
  - São Paulo (SP) drives **40%+ of all orders**.  
  - ✅ *Recommendation:* Focus marketing and logistics efforts here for maximum ROI.  

- **Insight 2: Top-Performing Product Categories**  
  - *Bed, Bath & Table* (`cama_mesa_banho`) is the **highest revenue driver**.  
  - ✅ *Recommendation:* Maintain strong inventory for this and other high-demand categories.  

- **Insight 3: High Order Fulfillment Rate**  
  - Majority of orders are **successfully delivered**.  
  - ✅ *Recommendation:* Use this operational strength as a **competitive advantage** in marketing.  

---

## 🖼️ Dashboard Preview  

![WhatsApp Image 2025-08-23 at 00 53 02 (1)](https://github.com/user-attachments/assets/ae9cd28c-a3fa-4cc4-8318-a46c2048ee02)



---

## 🚀 How to View This Project  

1. **Clone this repository**  
   ```bash
   git clone https://github.com/Saumya-Sinha25/Guvi-Hcl-Analysis.git
2. **Download the Zip File.**
3. **Open the project.pbix file in your Power BI desktop**
