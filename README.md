# Product Sales Exploratory Data Analysis ZARA

## Project Background
Zara, founded in 1974, is a global fashion retailer that designs, manufactures, and sells clothing and accessories worldwide through its stores, website, and mobile app.

The Company has significant amounts of data on its product inventory(over 20000 products), how they are categorized and their sales performance. This project thoroughly analyzes and explores this data in order to uncover critical insights and help improve Zara's success in the retail/fashion industry.

Insights and recommendations are provided on the following key areas:

⦁	Sales Trends Analysis: Evaluation of sales patterns across seasons and product types, focusing on Revenue, SKU count, and Average Revenue per Product.
⦁	Product Category Performance: An analysis of ZARA's product categories, understanding their impact on sales and revenue.
⦁	Season comparisons: An evaluations of sales across seasons
⦁	Promotions Effectiveness: Assessment of how promotions impact sales volume and revenue across different product types.
⦁	Gender Performance: Analysis of revenue and average revenue per SKU by gender





## Dataset Overview
Zara's database that was given consist of one table - business_sales_eda with a row count of 20253 products.

Prior to beginning the analysis in Excel, I standardized product categories by correcting labels and assigning categories based on product names. I also removed columns that were not relevant to sales analysis, such as origin, material, URLs, currency, brand, and descriptions, as they did not impact revenue or volume metrics. Finally, I reordered columns to improve readability and ensure a smoother analysis workflow.

<img width="259" height="308" alt="Screenshot 2025-12-22 160106" src="https://github.com/user-attachments/assets/887478ed-f1db-4340-b5b4-010cc37c132e" />




## Executive Summary

### Overview of Findings

We generated $885M in total sales, with Jackets/Outerwear contributing about 40% of total revenue at $358M.Revenue is highest in Autumn and Winter, while Summer items earn the most per product despite fewer SKUs. Promotions boost sales volumes by about 61% across all product types, even at lower prices. Most revenue across multiple categories contribute to having high product inventory, the following section will explore additional contributing factors and highlight key opportunity areas for improvement.

Below is a overview snapshot of a interactive dashboard I made in excel with more examples included below. You can download excel dashboard here

### Sales Trends

* **Total sales across all products reached $885M**, driven primarily by a high SKU count with over 20000 products.

* Average revenue per product is $43.7K, indicating revenue is spread evenly rather than concentrated in a few items.

* Sales performance is driven more by product mix and assortment breadth than by price changes or volume spikes.

### Promotion Effectiveness

⦁	Promoted products sell 1,412 units on average vs 872 for non-promoted, **showing promotions increase sales volume by 62%** across all SKUs.

⦁	Promotions reduce average price from $45 to $38, yet generate nearly equal total revenue ($441M promoted vs $444M non-promoted), indicating that volume lift offsets lower margins.

⦁	Promotions drive higher sales in both men(816 → 1,319 units) and women (902 → 1,461 units), showing the tactic is effective across gender categories and supports broad demand growth.

<img width="662" height="464" alt="image" src="https://github.com/user-attachments/assets/a95457e4-b7a5-4ae0-9d6c-efab33b938c3" />

### Product Type Performance

⦁	Jackets/Outerwear dominate in inventory and revenue, **accounting for 41% of total SKUs and 40% of total revenue($358M)**, indicating revenue is largely driven by assortment size rather than higher per-product performance.

⦁	Sweaters and T-shirts together earn $373M(42% of total revenue) with fewer SKUs, and their average revenue per product is higher($44K), compared to top performing Jacket/Outerwear category. indicating stronger per-item efficiency.

⦁	Avg price are all clustered together at about $42 per product across all categories. Revenue differences are driven mostly by product mix and SKU allocation, not pricing strategy, leaving room to rebalance assortment toward more efficient categories.

<img src="https://github.com/user-attachments/assets/4833a3c2-aadf-48dc15261d0a7" width="610" height="373" />

### Season Comparisons

* **Autumn generates the highest total revenue at $308M (35% of total)**, driven by the largest product assortment (7,665 SKUs).

* **Summer products earn the highest average revenue per product ($49K)** despite having the smallest SKU count, indicating stronger per-item efficiency.

* Winter leads in sweater sales of $88.5M in revenue across 1,816 SKUs. Also has **top average revenue per product of $48.7K**, showing high productivity and strong seasonal demand.


  ### Gender Performance

* Women’s products generate $598M(68% of total revenue) compared to men’s $286M due to high product inventory.

* Average revenue per SKU is higher for women ($45K vs $41K for men), indicating stronger per-product performance.

* Revenue growth is concentrated in women’s assortment with over 13000 SKUs, driven by both scale and efficiency.

<img src="https://github.com/user-attachments/assets/410f4783-7d01-4ed1-abc5-f8ed1148456f" width="645" height="367" />


  






  

