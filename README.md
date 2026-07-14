# NovaMart-Ecommerce-Project-PowerBi
📝 Project Overview

This project is an end-to-end Business Intelligence solution designed to monitor, analyze, and optimize the global operations of a large-scale e-commerce enterprise. Moving beyond basic descriptive statistics, this dashboard utilizes advanced data modeling, DAX measures, and AI-driven predictive analytics to uncover margin leaks, optimize marketing spend, and streamline supply chain logistics.

The ultimate goal of this project was to transform raw transactional data into an interactive executive tool that dictates immediate, high-ROI business decisions.
🛠️ Tech Stack & Technical Implementation

    Tooling: Power BI, Power Query

    Data Transformation: Cleaned raw boolean database flags into user-friendly categorizations (e.g., Premium/Standard, Restocked/Sold-Out).

    Data Modeling: Established a robust relational model to ensure complex geographic and category-level filter contexts flowed accurately across millions of rows.

    Advanced DAX: Engineered dynamic measures for Month-over-Month (MoM) variance, Profit Margin Percentage, and Return on Ad Spend (ROAS), actively bypassing standard aggregation traps (e.g., shifting from Price sums to Averages).

    AI & Predictive Analytics: Deployed the Key Influencers visual to run regression analysis on product categories and competitor pricing to isolate specific drivers for profit margin increases.

💡 Key Business Problems Solved
1. Marketing ROI & Budget Misallocation

    The Challenge: The business was pouring capital into marketing without clear visibility into channel-specific efficiency.

    The Insight: A custom scatter plot and dynamic ROAS tracking revealed that 48.9% of the total marketing budget (1.86M) was being spent on Paid Search, which yielded the lowest ROAS (0.2K). Conversely, Organic Search and Direct traffic were generating massive returns (2.5K and 4.7K ROAS) with minimal funding.

    The Solution: The data dictates an immediate 20-30% budget reallocation from Paid Search into SEO and direct retention campaigns.

2. Supply Chain Vulnerability & Stockouts

    The Challenge: Determining which products were at immediate risk of stockouts across a global warehouse network.

    The Insight: The inventory model identified 60 unique items sitting below their critical reorder threshold. By calculating the average supplier lead time (16 days), the dashboard prioritized restock alerts for high-velocity items like ZenLife Clothing Item 55.

    The Solution: Expedite purchase orders for the 60 critical items and evaluate shifting safety stock from the APAC warehouses (holding 1,977 active units) to the high-demand US markets.

3. Margin Optimization & Competitor Parity

    The Challenge: Identifying which product categories had the elasticity for price increases to drive profit margins without losing market share.

    The Insight: AI-driven Key Influencer analysis proved that the Beauty & Health and Clothing categories were the strongest drivers for margin percentage increases (+0.19 and +0.14 impact, respectively). Simultaneously, average listed pricing charts proved our Electronics division ($680) is priced in perfect parity with competitors ($679).

    The Solution: Hold the line on Electronics pricing to protect market share, while executing targeted 0.5% - 1.5% price hikes in Beauty & Health to maximize profitability.

4. Precision Return Analytics

    The Challenge: Moving beyond a generic return rate to find the actual financial drain of refunded products.

    The Insight: By sorting a custom matrix by negative financial impact rather than volume, the dashboard isolated ClearView Electronics Item 473. Despite only having 12 units returned, it accounted for $13,632 in lost revenue—the highest of any product.

    The Solution: Trigger an immediate QA audit on the ClearView Electronics line to stem the most expensive quality-control leak.
   
