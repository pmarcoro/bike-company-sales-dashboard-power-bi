## Project Description

This project was developed as part of the course “Power BI Desktop for Business Intelligence” from Maven Analytics.

AdventureWorks, a company specializing in bicycles and sports equipment, has experienced significant international growth in recent years. As business analysts, our aim is to develope an interactive Power BI dashboard using data from the AdventureWorks database to:

- Analyze revenue evolution and financial performance to identify growth drivers, structural shifts, and key inflection points in the business model.

- Evaluate product performance and profitability dynamics to determine which categories and models contribute most to revenue, volume, and margin optimization.

- Perform customer segmentation and behavioral analysis to uncover changes in purchasing patterns, income composition, and lifetime value potential.

## Dashboards

The business case analysis consists of four dashboards:

### Executive Page
Designed for executives to quickly grasp the overall health of the business and make data-driven decisions. It highlights key performance metrics, such as revenue, profit, orders, and return rate, as well as the most popular and most profitable items.


<p align="center">
<img src="/screenshots/gifs/Executive_Summary.gif" width="700">
</p> 
Key insights:
- Monthly revenue reached its historical peak in June 2022, hitting €1.8M. Since January 2020, monthly revenue has grown by 210%, showing strong overall business expansion.

- On August 1st, 2021, two new product lines — Accessories and Clothing — were introduced. Although their revenue contribution remains limited, the Top 10 products by number of orders are entirely from these two categories. This shift has influenced both the customer structure and demand within the bike product line, increasing interest in lower-cost bike models (as detailed in the Product and Customer pages).

- Bikes remain the company’s primary revenue driver, accounting for more than 90% of total revenue. However, Accessories lead in volume, surpassing 1,680 orders in June 2022. That month, 78% of total orders included at least one accessory item.

- The return rate is highest in the Bikes category, exceeding 3% of orders, while Clothing and Accessories remain closer to 2%.

### Map Page:
Shows the relative importance of each market in which the company operates, based on the number of orders.

<p align="center">
<img src="/screenshots/gifs/Map.gif" width="700">
</p> 
   
Key insights:
 - AdventureWorks is present in 6 countries from 3 continents. United States is the most important market in terms of total orders (8700), followed by Australia (6060) and Canada (3024). European companies represent around 7500 orders.
 
### Product Detail Page:
Enables a deeper understanding of the performance of each individual product.

<p align="center">
<img src="/screenshots/gifs/Product_Detail.gif" width="700">
</p> 

Key insights:
- The Mountain-200 bike line generates the highest revenue, followed by the Road-250 and Road-150 lines.

- Mountain-200 orders increased significantly, from 13 orders in July 2020 to 44 in June 2022 for the Black, 46 model. In contrast, the Road-250 Black, 52 model (the most sold version) declined from 17 to 8 orders over the same period. Price differences may explain part of this shift, with the Mountain-200 priced around $2,050 versus $2,180 for the Road-250.

 - These results are consistent with the shift in customer composition observed in the Customer Detail page, where middle-income customers represent a growing share. This segment may show stronger demand for relatively lower-priced bike models.

### Customer Detail Page: 
Describes the company’s customers, allowing for a better understanding of the evolution of the number of unique customers, customer segmentation by income level or occupation, and the identification of top customers in terms of orders and revenue.

<p align="center">
<img src="/screenshots/gifs/Customer%20Detail.gif" width="700">
</p> 

Key insights:
- In 2020, the only source of revenue was bike sales. Revenue per customer was high, as each customer placed a single order, reflecting a purely transactional model with no recurring behavior.

- After the introduction of new product lines on August 1st, 2021, the number of customers tripled compared to the beginning of the previous month. However, revenue per customer dropped significantly to $430, roughly one quarter of the level observed on July 1st, indicating a shift toward products with lower average value.

- The change in the business model also modified the customer mix. In relative terms, the share of high-income customers declined in favor of middle-income customers. In absolute terms, high-income customers still increased, but the growth of middle-income customers was substantially stronger.

- Purchasing behavior evolved as well. While all customers placed only one order in 2020, multi-order behavior became common in 2021 and 2022. The top customer overall was Mr. Maurice Shan, generating $12,400 across six orders, with peak annual contribution reaching $9,600 in 2021.
 
# Actionable Actions and Business Recommendations

- The expansion of middle-income customers and the decline in revenue per customer suggest the need to increase average order value. Product bundles (Bike + Accessories), personalized recommendations, and targeted promotions can help monetize the larger customer base more effectively.

- The stronger performance of relatively lower-priced models (e.g., Mountain-200 vs. Road-250) indicates growing price sensitivity. Lower-price bike models, financing options, or entry-level configurations might better capture the expanding middle-income segment. However, it is important to asses that lower-cost bike growth is incremental and is not replacing higher-margin models.

- Although the share of high-income customers declined relatively, their absolute numbers increased. Exclusive offers, early access to new premium models  and personalized service could prevent revenue concentration risk while maximizing lifetime value.

- Accessories represent the highest order volume and appear in the majority of transactions. Designing automatic add-on recommendations, checkout bundles, or accessory subscription packs could significantly increase margin and customer lifetime value.

- The rise in multi-order behavior (2021–2022) shows improved engagement. Formalizing this trend through a loyalty program, VIP benefits for high-value customers, and targeted email remarketing campaigns can stabilize recurring revenue.

- With return rates above 3%, bikes show higher operational risk than other categories. Improving post-sale support and quality control may reduce returns and protect margins.
