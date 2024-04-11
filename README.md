# Analyze Sales Data and Identify the Products that generated 80% of Profit
This project is part of the 8-week challenge initiated by the hosts of [Data Careers Summit](https://datacareerssummit.com/).

The original dataset is a year's worth of electronics sales transactions. It has around 185K records and 11 attributes. The dataset can be downloaded [here](https://www.kaggle.com/datasets/aemyjutt/salesdata/data).

### Overview
Business owners can use this information to identify the most valuable products in their assortment and allocate resources appropriately. This enables them to focus on these products while increasing sales. In the retail industry, if your key products are out of stock, it can negatively impact your sales, profit, and marketing costs. Especially for ecommerce, if the customer lands on your product page and the product they want is out of stock, they will simply find another retailer online who has what they need and is available to be purchased right away.

### Project Tasks:
1. Data Exploration and Preprocessing
2. Exploratory Data Analysis
3. ABC Product Segmentation
4. Key Products Analysis
5. Explanatory Data Analysis
6. Dashboard

### Data Findings and Insights:
1. All our products have performed well, with a total profit of $21.43M and a gross margin of 62.16%, however, ***ONLY 18% of the products contributed to 78% of total profit***, with a profit of $16.8M and a gross margin of 67%; with this information, we recommend focusing marketing efforts on these key products, maintaining sufficient supply, and ensuring they are the latest models. 
2. Products in segment A, our key products, have an average profit of $499, products in Segment C have an average profit of $11. In order to match a product's profit in segment A, a customer needs to purchase about 45 units from segment C.
3. If we have a customer who says he wants to buy items as gifts from our store with a budget of $100K, which products should we recommend? High-priced products? Slow-moving products? If we sell products worth $100K from segment A, with a gross margin of 67%, our profit would be $67K. If we sell for the same amount from segment B and C, the profit would only be $48K, and $52K. We would recommend that he buys from segment A.
4. Sales above $2M were generated between 11AM and 2PM and between 5PM and 9PM, so these are the best time periods for any marketing strategy campaigns. 
5. Products with the highest unit sales are not always the most profitable.
6. Our highest-performing product is Macbook Pro Laptop and our biggest market is San Francisco, CA.


The notebook can also be viewed on [Kaggle](https://www.kaggle.com/code/dorothykunth/sales-and-profitability-analysis) and the dashboard on my [Tableau Public](https://public.tableau.com/app/profile/dorothy.kunth/viz/ElectronicsSalesPerformance/SalesSummary).