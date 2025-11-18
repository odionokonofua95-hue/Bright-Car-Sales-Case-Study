## Bright Motors Car Sales Analysis (BRIGHTLEARN)
#### Data Exploration • SQL Analytics • Business Insights • Visualization
### 📌 1. Introduction

This project analyzes historical car sales data from Bright Motors, a dealership expanding its footprint and sales performance under a new Head of Sales. The goal is to use data analytics and SQL to uncover actionable insights that will support strategic decision-making, improve profitability, and optimize dealership operations.

The dataset contains daily vehicle sales transactions, including pricing, mileage, year, model, region, and other attributes.

### 📌 2. Project Objectives

This analysis aims to answer key business questions such as:

✔ Which car makes and models generate the highest revenue?
✔ How do vehicle price, mileage, and year affect sales performance?
✔ Which states/regions have the most sales activity?
✔ What trends exist in customer purchasing behaviour?
✔ What insights can guide dealership expansion and inventory planning?

SQL, data cleaning techniques, and visualization tools were used to transform raw sales data into meaningful KPIs and insights.

### 📌 3. Tools & Technologies Used

* Snowflake

* Databricks

* Excel

* Miro

* Figma

* Canva


### 📌 4. Project Tasks
#### Task 1 — Planning & Architecture (Miro / Figma)

Created a project board outlining:

#### 🔹 Data Flow Architecture

1. Source: Bright Motors Car Sales CSV

2. ETL Pipeline: Cleaning, formatting, classification, grouping

3. Database: Loaded into Snowflake

4. Analysis Layer: SQL transformations

5. Visualization Layer: Power BI / Excel

6. Presentation Layer: PowerPoint

#### 🔹 Key Insight Areas

1. Revenue by make, model, and year

2. Sales distribution by state and region

3. Price vs mileage and price vs MMR analysis

4. Seasonal trends (monthly sales patterns)

#### 🔹 Key Metrics Calculated

1. Total Revenue = selling_price

2. Profit = selling_price – MMR

3. Profit Margin %

4. Profitability Category (High, Medium, Low)

5. Year classification (1980s, 1990s, 2000s, 2010s, 2020s)

6. State → Region Mapping (West, Northeast, Southeast, etc.)

### 📌 5. Task 2 — Data Processing & SQL (Snowflake)

Performed extensive data preparation including:

#### ✔ Data Cleaning

1. Removed duplicate entries

2. Standardized missing values (e.g., model, color, state, year)

3. Converted selling price and MMR to integer

4. Replaced invalid dates in model

5. Converted "-" to "Not given"

6. Classified states into U.S. regions

#### ✔ Data Transformations

1. Created entry_id using ROW_NUMBER

2. Created profit, profit_percentage, and profit_category

3. Created sale_month using timestamp conversion

4. Added year_classification buckets

✔ Example SQL Script Included

The repository contains:
📄 sql

### 📌 6. Task 3 — Analysis & Visualization

Using the cleaned dataset:

📊 Presentation Included

1. Revenue by Make & Model

2. Sales by Region and State

3. Profitability Distribution

4. Trend Analysis (Monthly Sales)

5. Price vs Mileage Scatter & Heatmap

### 🔎 Key Exploratory Insights

* Certain states (e.g., CA, TX, FL) drive most sales volume

* Profit margins vary heavily by make & year group

* Mileage strongly influences price but varies by model

* Some models appear with date-formatted names and required cleaning


### 📌 7. Task 4 — Executive Presentation

A business-focused report was created summarizing:

* High-level views and KPIs

* Insights on revenue drivers

* Recommendations for dealership expansion

* Inventory stocking strategy

* Pricing optimization and profit improvement

📄 BrightMotors_Presentation.pdf included.


### 📌 10. Conclusion

This project demonstrates the end-to-end analytics workflow for a real-world automotive sales environment—covering data ingestion, transformation, SQL modeling, exploratory analysis, visualization, and executive reporting.

The insights generated support Bright Motors’ strategic objectives of:

* Expanding dealership networks

* Improving sales performance

* Optimizing vehicle inventory

* Increasing profitability
