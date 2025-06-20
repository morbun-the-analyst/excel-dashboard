# excel-dashboard
This repository contains data that has been cleaned and transformed in excel and dashboard that has been created in excel.

---

## **Business** Coffee Sales Dashboard 2019–2022 Performance Insights Report

### 📌 Project Description Summary

A business coffee sales dashboard built to analyze multi-year sales data and derive actionable insights on customer behavior, product performance, and country-level sales trends. The dashboard integrates data from three key tables — Orders, Customers, and Products — and enables interactive exploration using filters and slicers.

---

### 📊 Project Overview

The business seeks to optimize sales performance and customer engagement across different regions (USA, Ireland, UK) from 2019–2022. To support strategic decisions, a dashboard was developed for the **Sales and Marketing Teams** to track key metrics such as:

* Sales by country and customer
* Product performance by roast type and size
* Loyalty program impact

The dashboard facilitates a detailed understanding of revenue drivers and product preferences across customer segments.

---

### 🧠 Executive Summary

From 2019 to 2022, the company generated significant coffee sales primarily from the USA and Ireland. Surprisingly, loyalty card holders contributed **less sales** overall compared to non-loyalty customers. The **2.5 kg Light Roast** emerged as the top-performing product variant in both the US and Ireland. Despite being part of a loyalty program, most high-value customers made purchases without using a loyalty card. These insights suggest a potential gap in the effectiveness of the loyalty program.

---

### 📂 Data Description

* **Orders Table**: Contains transaction-level data including date, coffee type, quantity, and unit price.
* **Customers Table**: Includes customer names, countries, and loyalty card status.
* **Products Table**: Offers product attributes like roast type and package size.
* Data spans **2019 to 2022** and includes **1,000 records**.

---

### 🧱 Customer Report ERD (Entity Relationship Description)

* **Customers** (1-to-many) → **Orders**
* **Products** (1-to-many) → **Orders**
* The `Orders` table serves as the fact table with keys linked to both Customers and Products for enriched analysis.

---

### 🔍 Insights Deep Dive

| Insight Category        | Key Findings                                                                                                                                                                                                      |
| ----------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Country Performance** | The USA contributed the highest total sales, followed by Ireland and the UK.                                                                                                                                      |
| **Customer Loyalty**    | Non-loyalty card customers generated more revenue overall. For example, US non-loyalty customers drove more than \$16,465 in sales. In the UK, loyalty members generated only \$886 vs. \$1,912 from non-members. |
| **Product Performance** | The **2.5 kg Light Roast** consistently outperformed all other size/roast combinations. The smallest 0.2 kg packages underperformed.                                                                              |
| **Customer Segments**   | Among the top 5 customers, only **one** used a loyalty card — suggesting high-value customers may not see loyalty benefits.                                                                                       |

---

### 📊 Visualizations Included

* **Line Chart**: Sales over time by coffee type (monthly view from 2019–2022)
* **Bar Chart**: Top 5 customers by total sales
* **Bar Chart**: Sales by country
* **Slicers**: Roast type, weight (size), loyalty card
* **Timeline Filter**: Monthly period filter

---

### 💡 Recommendations

| Area                      | Recommendation                                                                                                                                                                         |
| ------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Loyalty Program**       | Reevaluate or redesign the loyalty card program. Consider personalized offers, clearer benefits, or tiered rewards to increase usage among high-value customers.                       |
| **Product Strategy**      | Increase focus on promoting and stocking the **2.5 kg Light Roast**, especially in US and Ireland. Consider bundling this size with loyalty offers to drive both sales and card usage. |
| **Customer Targeting**    | Identify non-loyal top spenders and run targeted email or promo campaigns to convert them into loyalty members.                                                                        |
| **Geographical Strategy** | Invest more in the Irish market where loyalty card impact is stronger and shows potential for nurturing brand loyalty.                                                                 |
| **Underperforming SKUs**  | Consider phasing out or discounting the 0.2 kg size based on low sales performance. Focus marketing on more profitable sizes.                                                          |

---

### ❓ Clarifying Questions for Stakeholders

* What are the current incentives offered through the loyalty card program?
* Is there a communication or UX issue that discourages loyalty card use?
* What channels are being used to promote larger roast sizes and premium roasts?
* Are customer satisfaction and repeat purchase data available to deepen segmentation?

---

### ⚠️ Caveats

* The analysis is based solely on sales data. No cost or profit margin data was available to assess profitability.
* Customer behavior beyond purchases (e.g., satisfaction, reviews, frequency) was not analyzed.
* Sales seasonality or campaign promotions were not identified in the data.

---


