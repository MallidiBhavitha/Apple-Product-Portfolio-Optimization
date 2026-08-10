# Optimizing Apple's Product Portfolio - Sales & Warranty Analytics Dashboard

## Project Overview

This project presents a Business Analytics case study focused on optimizing Apple's product portfolio by analyzing sales performance alongside warranty claims. Using Power BI, the dashboard provides interactive insights that help identify products generating strong revenue while maintaining lower warranty-related service costs.

The analysis enables data-driven decision-making by highlighting products suitable for further investment, products requiring quality improvements, and opportunities to optimize inventory and marketing strategies.

---

## Business Problem

Apple offers a wide range of products across multiple categories. While some products generate high revenue, they may also incur significant warranty-related service costs. Without analyzing both sales performance and warranty trends together, it becomes difficult to identify which products truly contribute the highest business value.

---

## Business Question

**Which Apple products should the company prioritize to maximize revenue while minimizing warranty claims?**

---

## Project Objectives

- Analyze product-level sales performance.
- Evaluate warranty claim trends across products and categories.
- Identify products that generate high revenue with relatively lower warranty claims.
- Highlight products requiring quality improvements.
- Support inventory and marketing decisions through interactive business insights.

---

## Dataset Information

The project uses multiple relational datasets representing different business entities.

**Datasets Included:**
- Sales
- Products
- Categories
- Stores
- Warranty Claims

These datasets were integrated using a relational data model within Power BI.

---

## Data Model

The project follows a relational star-schema style data model connecting products, categories, stores, sales transactions, and warranty claims.

**Data Model**

![Data Model](Images/Data%20Model.png)

---

## Dashboard Preview

The interactive Power BI dashboard summarizes sales performance, warranty analysis, product comparison, category performance, and strategic recommendations.

**Dashboard Screenshot**

![Dashboard](Images/Dashboard%20screenshot.png)

---

## Key Performance Indicators (KPIs)

- Total Revenue
- Total Units Sold
- Total Warranty Claims
- Warranty Claim Rate
- Average Revenue Per Sale

---

## Dashboard Features

- Revenue Analysis by Product
- Warranty Claims by Product
- Revenue vs Warranty Comparison
- Revenue by Product Category
- Warranty Claims by Category
- Interactive Filters
  - Sale Date
  - Country
  - Category
  - Store Name
- Strategic Business Recommendations

---

## Key Business Insights

- Apple Music, iPad (9th Generation), iPad mini (5th Generation), Beats Solo Pro, and Apple Watch SE generated strong revenue while maintaining comparatively lower warranty claims.
- Products such as Beats Fit Pro, MagSafe Charger, and iPhone 14 produced strong revenue but also experienced higher warranty claims, indicating opportunities for quality improvement.
- HomePod mini recorded the highest warranty claims despite only moderate revenue, making it a priority for product quality analysis.
- Category-level analysis highlighted differences in both revenue generation and after-sales service performance.

---

## Strategic Recommendations

- Prioritize Apple Music, iPad (9th Gen), iPad mini (5th Gen), Beats Solo Pro, and Apple Watch SE for inventory and marketing investment.
- Improve product quality for Beats Fit Pro, MagSafe Charger, and iPhone 14 to reduce warranty-related service costs.
- Investigate HomePod mini due to exceptionally high warranty claims.
- Continue balancing revenue performance with warranty trends to support future product decisions.

---

## Tools & Technologies Used

- Power BI Desktop
- Power Query
- DAX
- Data Modeling
- Data Visualization
- Business Analytics

---

## Repository Structure

```
Apple-Product-Portfolio-Optimization
│
├── Dashboard
│   └── Apple Product Portfolio Optimization.pbix
│
├── Dataset
│   └── Apple Datasets CSV.zip
│
├── Images
│   ├── Dashboard Screenshot.png
│   └── Data Model.png
│
└── README.md
```

---

## Conclusion

This project demonstrates how Business Intelligence and data visualization can support strategic product portfolio decisions by combining sales performance with warranty analytics. Rather than focusing solely on revenue, the dashboard enables a balanced evaluation of both profitability and product reliability, helping identify products that deliver sustainable business value.

---
