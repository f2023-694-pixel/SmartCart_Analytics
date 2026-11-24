# SmartCart Analytics
### A Big Data Approach to Grocery Purchasing Behaviour Using PySpark

**Midterm Project | Big Data Analytics**

## 1. Project Overview

SmartCart Analytics is a big data analytics project developed using Apache Spark and PySpark. The project analyzes grocery purchasing data to understand customer preferences, product popularity, purchasing patterns, and reorder behaviour.

Multiple grocery datasets are integrated, cleaned, and analyzed to generate meaningful business insights. The project demonstrates how big data technologies can help businesses understand customers and make data-driven decisions.

## 2. Problem Statement

Grocery stores generate large amounts of customer purchasing data. Analyzing this information can help businesses understand customer preferences, identify popular products, and improve inventory management.

This project uses PySpark to analyze large grocery datasets and identify purchasing trends, customer segments, popular products, and repeat purchasing behaviour.

## 3. Project Objectives

- Analyze large grocery datasets using PySpark.
- Clean and preprocess raw data.
- Integrate multiple datasets using joins.
- Identify the most frequently purchased products.
- Analyze department and aisle purchasing patterns.
- Segment customers based on purchasing frequency.
- Examine purchasing behaviour across days and hours.
- Calculate product reorder percentages.
- Apply RDD operations and Spark SQL.
- Generate visualizations and business KPIs.

## 4. Technologies Used

- Python
- Apache Spark
- PySpark
- Google Colab
- Pandas
- Matplotlib
- Spark SQL

## 5. Datasets

The project uses five CSV files:

1. `orders.csv`
2. `order_products__train.csv`
3. `products.csv`
4. `aisles.csv`
5. `departments.csv`

These datasets contain information about customer orders, purchased products, product names, aisles, and departments.

## 6. Methodology

The project follows these steps:

1. Install and import the required libraries.
2. Create a Spark session.
3. Upload and load datasets.
4. Explore datasets and examine their schemas.
5. Check missing values.
6. Clean and preprocess the data.
7. Integrate datasets using PySpark joins.
8. Perform feature engineering.
9. Analyze products and departments.
10. Examine customer purchasing behaviour.
11. Perform time-based purchasing analysis.
12. Analyze reorder behaviour.
13. Apply PySpark RDD operations.
14. Rank products using window functions.
15. Perform Spark SQL analysis.
16. Calculate project KPIs.
17. Create visualizations.
18. Save the final analytical results.

## 7. Key Findings

- Banana was the most frequently purchased product, with 18,726 purchases.
- Produce was the leading department, with 409,087 purchases.
- Sunday was the busiest shopping day, with 324,026 purchases.
- Afternoon had the highest purchasing activity, with 572,319 purchases.
- Approximately 59.86% of purchases were reorders.
- The customer analysis identified 53,931 frequent, 56,797 regular, and 95,481 occasional customers.
- The average number of products per order was approximately 10.55.

## 8. Key Performance Indicators

| KPI | Result |
|---|---:|
| Total Orders | 3,421,083 |
| Total Customers | 206,209 |
| Total Products | 49,688 |
| Total Purchase Records | 1,384,617 |
| Average Products per Order | 10.55 |
| Average Orders per Customer | 16.59 |
| Reorder Percentage | 59.86% |

## 9. Business Insights

The analysis indicates that fresh produce is an important category for grocery customers. Bananas and other fresh products have high purchasing frequencies.

Sunday and afternoon show higher shopping activity, which can help businesses plan staffing and inventory.

The high reorder percentage also highlights the importance of repeat customers. Customer segmentation can help businesses develop targeted promotions and loyalty strategies.

## 10. Conclusion

SmartCart Analytics demonstrates how PySpark can be used to process and analyze large grocery datasets. The project applies data cleaning, data integration, customer analysis, RDD operations, Spark SQL, and visualization techniques to generate useful business insights.

The findings can support better inventory planning, customer understanding, and business decision-making.

## 11. Future Improvements

- Predictive analysis of customer purchases.
- Advanced customer segmentation using clustering.
- Sales and revenue analysis.
- Product recommendation systems.
- Demand forecasting.
- Interactive dashboards using Power BI.

---

**Project:** SmartCart Analytics  
**Technology:** Apache Spark / PySpark  
**Environment:** Google Colab  
**Category:** Big Data Analytics
