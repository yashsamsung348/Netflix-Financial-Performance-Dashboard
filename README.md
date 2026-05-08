# 📊 Netflix Global Financial Performance Dashboard

## 📌 Project Overview
This project is an end-to-end business intelligence dashboard built in Power BI, designed to track and analyze Netflix's global revenue streams and regional growth. Modeled from the perspective of a Financial Controller, this interactive tool transforms raw, multi-regional financial data into an executive-level summary of corporate performance.

The primary objective of this project was to move beyond basic data visualization and architect a dynamic financial reporting system using robust relational data modeling and advanced DAX calculations.

## 🛠️ Technical Highlights & Methodologies

### 1. Data Engineering & Transformation (ETL)
* Utilized **Power Query** to extract, clean, and structure raw financial datasets.
* Executed complex transformations, including unpivoting regional revenue columns into a scalable, machine-readable format.
* Ensured data integrity by handling missing values, standardizing data types, and structuring a clean schema.

### 2. Relational Data Modeling
* Engineered a star-schema data model linking localized financial facts with dimensional lookup tables.
* Established active 1-to-Many relationships to enable seamless cross-filtering across all dashboard visuals without performance degradation.

### 3. Advanced DAX (Data Analysis Expressions)
* Bypassed standard aggregations to build a custom financial engine using functions like `CALCULATE`, `SUMX`, and `RELATED`.
* Developed dynamic, context-aware measures to calculate critical KPIs, including Quarter-over-Quarter (QoQ) growth and accurate total revenue summations across filtered timeframes.

### 4. UI/UX & Executive Design
* Architected a dual-theme executive interface.
* Implemented a dark-mode layout for granular regional data to reduce eye strain, contrasted with highly visible, bright KPI cards for top-line executive summaries.

## 📈 Key Business Insights Discovered
* **Total Tracked Revenue:** Dynamically modeled over $45M in global revenue across the dataset timeframe.
* **Growth Metrics:** Calculated and validated a consistent 14.30% Quarter-over-Quarter growth trajectory.
* **Geographic Distribution:** Highlighted the primary regional drivers of subscription revenue through interactive geographic filtering.

## 🧰 Tools & Technologies Used
* **Microsoft Power BI Desktop** (Data Modeling & Visualization)
* **Power Query** (ETL pipeline)
* **DAX** (Business logic & calculations)

## 🚀 How to Interact with This Project
1. Download the `Netflix_Financial_Performance.pbix` file from this repository.
2. Open the file in **Microsoft Power BI Desktop**.
3. Interact with the regional bar charts to see how the cross-filtering engine dynamically updates the executive KPI cards in real-time.

---
Here is the screenshot : https://github.com/yashsamsung348/Netflix-Financial-Performance-Dashboard/blob/main/Image.jpeg
