# amazon-sales-analysis

### Dashboard Link :https://app.powerbi.com/groups/me/reports/924266e6-dade-421b-918d-1da71b043d54/ReportSection?experience=power-bi

## Problem Statement
The provided dataset contains information about sales transactions for various products across different regions and countries. Each entry includes details such as the region, country, item type, sales channel, order priority, order date, order ID, ship date, units sold, unit price, unit cost, total revenue, total cost, and total profit.

The challenge is to analyze and extract meaningful insights from the dataset, addressing specific business questions or concerns


### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : It was observed that in none of the columns errors & empty values were present.
  Step 5: Visualization Setup:

Clustered Column Chart: You employed a clustered column chart to provide a visual representation of key metrics. The X-axis was populated with distinct item types, while the Y-axis showcased the aggregated values of total cost and total profit. Additionally, a filter was applied to focus specifically on the top 5 categories, allowing for a more targeted analysis of strengths.

Line Chart: For a dynamic view, you introduced a line chart with item types on the X-axis. The primary Y-axis depicted the sum of unit cost, and the secondary Y-axis illustrated the sum of unit price. This dual-axis approach enables a comprehensive analysis of cost and pricing trends.

Score Card: A score card was incorporated to present a concise summary of the business performance. By displaying the sum of units sold, you gained insights into the quantity of units sold per category or region, aiding in strategic decision-making. 

Donut Chart: Utilizing a donut chart, you visualized the distribution of total revenue across different item types. The legend played a crucial role in categorizing the data, offering a quick and intuitive understanding of revenue contribution from each item type.

-Step 6: Filters:

To enhance interactivity and user control, you implemented filters that allowed users to selectively analyze data by choosing one or multiple regions. This flexibility facilitates a more personalized exploration of the dataset based on specific criteria or areas of interest.
-Step 7: Beautification:
Understanding the importance of aesthetics, you dedicated attention to beautifying the report. This involved the addition of a smooth background to the entire screen, contributing to a visually appealing and cohesive design that enhances the overall user experience.
-Step 8:Title Addition:
Concluding your report development, you incorporated a meaningful title, "Amazon Sales Data Analysis." This title serves as a clear identifier, instantly communicating the report's purpose and focus, providing users with context as they delve into the presented insights.
- Step 9 : The report was then published to Power BI Service.
 

# Snapshot of Dashboard (Power BI Services

![2023-12-20 (2)](https://github.com/Parshavkhandelwal/amazon-sales-analysis/assets/124446315/5a7246c4-3cb6-40bb-b4d9-b43f419b57cd)

 
 # Report Snapshot (Power BI DESKTOP)

 
![Screenshot 2023-12-20 175222](https://github.com/Parshavkhandelwal/amazon-sales-analysis/assets/124446315/e62ff9c0-4819-4561-b4e4-c89a798b2e52)

# Insights

A single page report was created on Power BI Desktop & it was then published to Power BI Service.

Following inferences can be drawn from the dashboard;

### [1] Insights of asia

top 5 products in terms of profit-office supplies, house hold ,cosmetics ,clothes ,vegetables

       top 5 products in terms total revenue in percentage 
       1-office supplies-37.82%
       2-house hold -35.75%
       3-cosmetics -14.24%
       4-clothes -7.24%
       5-vegetables-1.88%
total units of products -60000

1-Profitable Priorities: While office supplies and household goods lead in profit, cosmetics stand out with a high margin, suggesting potential for increased focus.

2-Consumer Staples: Office supplies and household items dominate total revenue, reflecting their essential nature for consumers.

3-Diversify for Growth: Explore opportunities to diversify the cosmetics line and introduce high-margin clothing to enhance overall revenue.

4-Veggie Margins: With only 1.88% revenue, vegetables show a highly competitive market with limited profit margins.

5-Unit Efficiency: Analyzing the distribution of 60,000 units sold across categories guides inventory management and marketing strategies.


  
           
### [2] insights of australia and oceania

  top 5 products in terms of profit - cosmetics, meat ,baby food ,office supplies ,cereal

    top 5 products in terms total revenue in percentage 
       1-cosmeticss-29.95%
       2-meat -23.36%
       3-baby food -17.68%
       4-office supplies -13.51%
       5-cereal-1.88%
total units of products -68000  

1-Cosmetic Crown: Cosmetics lead in both profit and revenue, indicating a strong market demand and potential for continued growth.

2-Meat's Market Muscle: Meat follows closely, boasting substantial profit and revenue, reflecting its significance in the region's consumption patterns.

3-Baby Boom: Baby food, with a high-profit margin and significant revenue share, highlights the importance of catering to the parental market.

4-Office Supplies Steady: While office supplies contribute to profit and revenue, their lower rank suggests a steady but not dominant market presence.

5-Cereal's Niche: Cereal, though having a low revenue share, might still represent a niche market with room for growth or specialization.

6-Scale Management: With 68,000 units sold, efficiently managing the scale and distribution of these products becomes critical for operational success and market responsiveness.
  
  ### [3] insights of central america

  top 5 products in terms of profit -house hold, cosmetics, cereal ,snacks ,clothes

    top 5 products in terms total revenue in percentage 
       1-household-65.4%
       2-cosmetics -8.13%
       3-clothes -6.55%
       4-cereal -6.29%
       5-personal care-5.71%
total units of products -36000.

1-Household Dominance: Household products not only lead in profit but also command a substantial 65.4% of total revenue, indicating their central role in consumer spending in Central America.

2-Cosmetic Allure: Cosmetics contribute significantly to profit and revenue, showcasing a growing market for beauty and personal care products.

3-Clothing and Style: Clothing, though ranking third in revenue, demonstrates a noteworthy 6.55% share, suggesting a steady demand for fashion items in the region.

4-Cereal and Snack Appeal: Cereal and snacks, while contributing to profit, showcase an appetite for convenient and on-the-go food options in Central America.

5-Personal Care Niche: Personal care products secure a place in the top 5 revenue earners, underlining the importance of health and wellness in consumer choices.

6-Moderate Scale: With 36,000 units sold, managing inventory efficiently becomes crucial to meet consumer demands and maximize market presence.

 ### [4] insights of europe

  top 5 products in terms of profit -cosmetics, officesupplies ,baby food ,house hold ,clothes

    top 5 products in terms total revenue in percentage 
       1-cosmetics-39.44%
       2-office supplies -27.43%
       3-baby food -16.9%
       4-house hold -9.6%
       5-clothes-3.86%
total units of products -98000

1-Cosmetic Triumph: Cosmetics lead in both profit and revenue, indicating a lucrative market and high consumer demand for beauty products.

2-Office Supplies Solid: Office supplies contribute significantly to profit and revenue, reflecting their importance in both business and personal spheres.

3-Baby Boom: Baby food, with a high-profit margin and notable revenue share, highlights the significance of catering to the parental market.

4-Household Essentials: Household products contribute to profit and revenue, underscoring their role as essential commodities in consumer spending.

5-Clothing Style: Clothing, while lower in revenue, maintains a presence, showcasing the fashion and personal style preferences of consumers.

6-Scale Management: With 98,000 units sold, strategic inventory management is crucial for meeting demand and optimizing market presence.






 
 ### [5]  insights of middle east

  top 5 products in terms of profit -cosmetics, officesupplies ,clothes,cereal,fruits

    top 5 products in terms total revenue in percentage 
       1-cosmetics-73.47%
       2-clothes -10.89%
       3-office supplies -9.37%
       4-cereal-5.95%
       5-fruits--%
total units of products -49000

1-Cosmetic Domination: Cosmetics not only lead in profit but also command a significant 73.47% of total revenue, illustrating a strong consumer demand for beauty and personal care products in the Middle East.

2-Fashion Influence: Clothes follow, contributing notably to revenue, showcasing the region's penchant for fashion and style.

3-Office Supplies Significance: While ranking third in revenue, office supplies contribute substantially to both profit and revenue, indicating their importance in business and personal contexts.

4-Cereal Appeal: Cereal products, though lower in revenue share, demonstrate a market for convenient and nutritious food options in the region.

5-Fruitful Choices: Fruits, while contributing to profit, hold a modest share in total revenue, suggesting a potential for growth in the fresh produce market.

6-Optimizing Inventory: With 49,000 units sold, efficient inventory management is vital to meet consumer demands and maximize market share in the Middle East.
         
### [6] insights of north america

  there arwe only 2 products which are sold through amazor those are house hold and personal care
      1- house hold -82.35%
      2-personal care-17.65%
    
total units of products -19000

1-Amazon Duo: In North America, the e-commerce giant Amazon predominantly sells household products, comprising a substantial 82.35% of total sales, indicating the high demand for everyday essentials.

2-Personal Care Preference: Personal care products, while occupying a smaller share at 17.65%, still reflect a notable consumer interest in health and self-care through online platforms.

3-Streamlined Selection: With a focus on just two product categories, Amazon's strategy in North America appears to be streamlining, potentially optimizing logistics and enhancing customer experience.

4-Consumer Convenience: The dominance of household products suggests that consumers in North America prioritize the convenience of online shopping for everyday items.

5-Strategic Inventory: With 19,000 units sold, managing inventory efficiently becomes crucial to meet the demands of a consumer base accustomed to the convenience of e-commerce platforms like Amazon.






### [7] Insights of sub-sahara africa

top 5 products in terms of profit-office supplies, house hold ,cosmetics ,cereal ,vegetables

       top 5 products in terms total revenue in percentage 
       1-office supplies-29.9%
       2-house hold -22.52%
       3-cosmetics -14.44%
       4-cereal -10.65%
       5-vegetables-6.98%
total units of products -183000

1-Office Supplies Lead: Office supplies dominate both profit and revenue, showcasing their significance in Sub-Saharan Africa's market, potentially driven by business and educational needs.

2-Household Essentials: Household products follow closely, contributing significantly to revenue, highlighting their essential role in daily life for consumers in the region.

3-Cosmetic Appeal: Cosmetics, while lower in revenue, still demonstrate a notable market demand for beauty and personal care products, reflecting evolving consumer preferences.

4-Cereal Sustenance: Cereal products, though ranking fourth in revenue, contribute to profit and suggest a market for staple food items in the region.

5-Vegetable Variety: Vegetables, while holding a smaller revenue share, reflect a market for fresh produce, emphasizing a connection to healthier food choices.

6-Scale of Operations: With 183,000 units sold, efficient scale management becomes crucial for meeting diverse consumer needs and optimizing market penetration in Sub-Saharan Africa.
