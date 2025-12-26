# DSA Food and Beverage Sales Report
Tools and Techniques: **MS Excel, Power Query, Power Pivot, Pivot Tables**

![header](https://github.com/jiannelibunao/customer-campaign-intelligence/blob/217526b343122ecec4ba074c9362b032979fb1a3/Assets/marketing_dashboard.jpg)

## Table of Contents
1. Project Background
2. Data Structure and Initial Checks
3. Executive Summary
4. Insights Deep Dive
5. Recommendations

## **Project Background**
DSA’s needed a dynamic, user-friendly sales dashboard to support decision-making across its Food and Beverage section. The company requested an interactive report that would provide high-level metrics, sales performance and seasonal trends, identify top-selling products, and recognize best employees across teams. This project delivered a clear, actionable view of its performance using their two years of historical data.

Insights and recommendations are provided on the following key areas:
-	**Revenue Trend:** Evaluation of historical sales over the past two years with high-level Key Performing Indicators (KPIs) in relation to the data.
-	**Weekly Transactions:** A visual breakdown of weekly product order transactions, offering a quick snapshot of consumer activity patterns.
-	**Revenue Drivers:** Exploration of different areas of revenue growth focusing on channel and product performance, understanding their impact on sales.
-	**Product Performance:** Identification of the best and least products among its customers, accompanied with quick metrics to understand better the data.
-	**Team Efficiency:** An assessment of each employee’s efforts in contributing to the company’s sales.

## **Data Structure and Initial Checks**
DSA Food and Beverage Excel dataset structure as see below consists of two sheets, [fSales] and [dProduct]. [fSales] sheet has 10 native columns with one primary key and has 245,848 sales records. [dProduct] has 5 native columns with one foreign key and has 799 unique products.

![data-structure](https://github.com/jiannelibunao/customer-campaign-intelligence/blob/217526b343122ecec4ba074c9362b032979fb1a3/Assets/marketing_dashboard.jpg)

Prior to beginning the analysis, an inspection was conducted in Power Query to check any data errors. No issues were found and familiarization of the dataset was established.

## **Executive Summary**
With a 59.6% revenue increase year-over-year, the company has achieved meaningful growth amounting to $20.4M in total sales revenue, 6.6M of units sold, and 49.5K of total orders. Weekly orders showed a different perspective, pre-weekend demand surges with Thursdays having the highest order counts. Various factors were involved in this continued success. Main revenue driver stems from the food section where 93% of the sales was generated, with Wheat product as the top product. In terms of customer engagement, retail purchases are the most popular contributing to 49% of the sales. Part of the success also comes from the team’s efforts in promoting and selling their products, specifically Mikaela Ong being the best sales agent with $5.5M sales (34.32%).

## **Insights Deep Dive**
### Revenue Trajectory
![revenue-trajectory](https://github.com/jiannelibunao/customer-campaign-intelligence/blob/217526b343122ecec4ba074c9362b032979fb1a3/Assets/marketing_dashboard.jpg)

####	Performance Highlights and Trends
-	A 59.6% revenue increase year-over-year is a strong signal of overall business momentum.
-	October 2023 was the peak revenue month, which may reflect seasonal demand or a successful campaign.
-	Average monthly revenue sits at $848.8K, offering a solid benchmark for future planning.
-	The 29.26% average month-over-month rate shows consistent upward movement, supported by the trend line.

####	Operational Pressure Points
-	Units sold dropped by 16.3% compared to previous month, which may suggest fewer items sold at higher prices.
-	Total orders fell by 20.8%, possibly indicating fewer transactions but larger basket sizes.
-	Revenue declined 17.3% month-over-month after October’s peak, hinting at a post-promo cooldown or supply constraints.

### Daily Transaction Patterns
![daily-transaction](https://github.com/jiannelibunao/customer-campaign-intelligence/blob/217526b343122ecec4ba074c9362b032979fb1a3/Assets/marketing_dashboard.jpg)

-	**Thursday leads in activity with 14.63% of weekly transactions**, but the margin over Tuesday (13.87%) is modest. This suggests a relatively even distribution across the week, with no extreme drop-offs.
-	**Thursday to Sunday form the busiest stretch**, indicating that consumer engagement ramps up toward the weekend. This could reflect payday cycles, leisure shopping behavior, or promotional timing.
-	**Tuesday consistently ranks lowest**, which may be useful for scheduling maintenance, testing, or low-risk experiments when traffic is lighter.
-	**The difference between peak and trough is just 0.76 percentage points**, reinforcing that while Thursday is optimal, the week remains fairly balanced — ideal for consistent campaign pacing.

### Revenue Drivers
![revenue-drivers](https://github.com/jiannelibunao/customer-campaign-intelligence/blob/217526b343122ecec4ba074c9362b032979fb1a3/Assets/marketing_dashboard.jpg)
-	**Retail channel dominates**, contributing nearly half of total revenue at 49.16%. This suggests strong in-person engagement and possibly higher-margin transactions compared to online or distributor channels.
-	**Food product account for 93.04% of total revenue**, making them the core driver of business performance. Drinking products, while present, play a minor role at just 6.96%.
-	**Distributor sales at 33.92% show solid support**, possibly from B2B or wholesale partnerships. This channel could be optimized for scaling food product reach.
-	**Online channels contribute only 16.92%**, which may indicate untapped potential for digital expansion, especially if food products can be packaged or marketed for e-commerce.

### Product Performance
![product-performance](https://github.com/jiannelibunao/customer-campaign-intelligence/blob/217526b343122ecec4ba074c9362b032979fb1a3/Assets/marketing_dashboard.jpg)
-	**Wheat Flour is the top performer**, contributing 39.41% of revenue among the top five products. Its dominance suggests strong demand for baking or staple ingredients.
-	**Tomato Sauce ranks lowest**, with only 1.24% share among the bottom five. Despite a 107.1% increase from the previous month, its overall impact remains minimal.
-	**Top products are baking-related**, which includes flour, yeast, and oil. This could indicate that ingredients used in bread or pastry preparation drive the bulk of sales.
-	**Bottom products include beverages like red wine**, energy drinks, and tea. This supports the idea that the drink category contributes only a small fraction to overall revenue.
-	**Wheat Flour’s monthly unit sales dropped 16.5%**, which may signal saturation, seasonality, or pricing shifts despite its leading position.

### Employees’ Efficiency
![employee-performance](https://github.com/jiannelibunao/customer-campaign-intelligence/blob/217526b343122ecec4ba074c9362b032979fb1a3/Assets/marketing_dashboard.jpg)
-	**Mikaela Ong leads both in revenue and volume**, contributing 34.32% of total sales and 37.01% of units sold. Her dual dominance confirms consistent high-value and high-volume performance.
-	**The top three performers, Mikaela, Marco, and Isabella, account for over 75% of total sales**, indicating a strong concentration of output among a few key contributors.

## **Recommendations**
Based on the uncovered insights, the following recommendations have been provided:
### 1. **Double Down on High-Performing Products**
- Prioritize inventory and marketing for **Wheat Flour, Yeast, and Oil**, which dominate revenue and unit sales.
- Consider bundling these into baking kits or seasonal promos to boost volume and cross-sell.

### 2. **Reevaluate Beverage Strategy**
- With **drinks underperforming** across both product and category views, explore repositioning, rebranding, or reducing SKUs.
- Test new formats (e.g., ready-to-drink, sampler packs) or shift focus to higher-margin food items.

### 3. **Optimize Channel Investment**
- **Retail leads in revenue**, but **online channels lag** at 16.92%. Invest in digital campaigns, UX improvements, and targeted promotions to grow online share.
- Strengthen distributor relationships with volume incentives or exclusive product lines to maintain their 33.92% contribution.

### 4. **Leverage Weekly Transaction Patterns**
- **Thursday to Sunday are peak days**. Schedule major launches, discounts, and email campaigns during this window.
- Use **Tuesday’s low traffic** for backend updates, A/B testing, or staff training.

### 5. **Capitalize on Seasonal Revenue Peaks**
- October’s revenue spike suggests seasonal or campaign-driven success. Replicate timing and tactics for future cycles.
- Build a promotional calendar around proven high-performing months to stabilize month-over-month fluctuations.

### 6. **Empower and Retain Top Talent**
- **Mikaela Ong’s performance is exceptional**, contributing over a third of sales and units. Recognize, reward, and replicate her approach across the team.
- Use her metrics as benchmarks for onboarding, training, and performance reviews.

### 7. **Monitor Product Saturation**
- Despite leading sales, **Wheat Flour saw a 16.5% drop in monthly units**. Investigate pricing, competition, or seasonal demand shifts to prevent erosion.
