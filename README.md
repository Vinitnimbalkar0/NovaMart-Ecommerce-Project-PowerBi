# NovaMart-Ecommerce-Project-PowerBi

## 📝 Project Overview
This project is an end-to-end Business Intelligence solution designed to monitor, analyze, and optimize the global operations of a large-scale e-commerce enterprise. Moving beyond basic descriptive statistics, this dashboard utilizes advanced data modeling, DAX measures, and AI-driven predictive analytics to uncover margin leaks, optimize marketing spend, and streamline supply chain logistics.

The ultimate goal of this project was to transform raw transactional data into an interactive executive tool that dictates immediate, high-ROI business decisions.

---

## 📸 Dashboard Gallery

# Executive & Revenue
<img width="1308" height="737" alt="image" src="https://github.com/user-attachments/assets/d8c54f8c-fdb2-49fd-b4ce-5b72f4bf1507" />


# Customers
<img width="1311" height="739" alt="Customers" src="https://github.com/user-attachments/assets/5bd69c2e-9b57-4e73-82ea-9385467c0c27" />




---

## 💡 Executive Intelligence Report: Strategic Optimization

### Challenge 1: Severe Marketing Budget Misallocation
* **The Problem:** The business is heavily subsidizing low-performing channels while starving highly efficient organic growth engines.
* **The Dashboard Insight:** The Marketing dashboard reveals a critical inefficiency in our Customer Acquisition Cost (CAC) and Return on Ad Spend (ROAS).
    * **The Drain:** We are currently pouring 48.9% of our total budget (1.86M) into Paid Search. However, Paid Search yields the absolute lowest ROAS of any channel (0.2K).
    * **The Missed Opportunity:** Conversely, Direct and Organic Search generate massive returns (4.7K and 2.5K ROAS, respectively) but receive a fraction of the funding.
* **Strategic Action:** Immediately reallocate 20-30% of the Paid Search budget into Organic Search SEO and Direct marketing retention campaigns.


*Visual Evidence: Marketing ROI Dashboard*
<img width="1321" height="733" alt="Marketing Spend" src="https://github.com/user-attachments/assets/a6bbb601-acf3-482f-b8ef-e443679454b3" />


### Challenge 2: Revenue Erosion via Electronics Returns
* **The Problem:** While the overall return rate is a healthy 3.07%, specific high-ticket items are quietly eroding net profit.
* **The Dashboard Insight:** The Returns dashboard successfully shifted our focus from volume to financial impact.
    * Clothing has the highest rate of returns (3.17%), and ZenLife Clothing Item 279 is the most frequently returned item by volume (19 units).
    * However, sorted by financial impact, ClearView Electronics Item 473 is the true problem. With just 12 units returned, it accounted for $13,632 in refunded revenue, making it our most expensive quality-control issue.
* **Strategic Action:** Initiate an immediate QA audit on ClearView Electronics Item 473. Furthermore, evaluate the 34% of returned inventory that is currently marked as "Sold-Out/Scrapped" to see if refurbishment or liquidation can recover lost capital.


*Visual Evidence: Returns & Refunds Dashboard*
<img width="1324" height="741" alt="Return" src="https://github.com/user-attachments/assets/93450f8c-01c7-4d12-a845-001e94416e63" />


### Challenge 3: VIP Customer Concentration Risk
* **The Problem:** Revenue is heavily reliant on a small fraction of "whale" clients, and our Premium tier is underutilized.
* **The Dashboard Insight:** 
    * Our top customer, Sara Rossi, generated 1.07M in revenue from 1,805 orders. She alone accounts for roughly 2% of total global revenue.
    * Additionally, only 21.86% of our 8K total customers are enrolled in the Premium tier, yet the USA market vastly outperforms all other regions combined.
* **Strategic Action:** Deploy a white-glove account management protocol for our top 10 spenders (Rossi, Mueller, Harris, etc.) to ensure zero churn. Launch a targeted campaign in the USA market to convert the top 20% of Standard customers into the Premium tier, utilizing targeted email campaigns (which currently have a solid 2.3K ROAS).

### Challenge 4: Supply Chain Vulnerability
* **The Problem:** Supply chain bottlenecks and stockouts threaten to halt our upward revenue trajectory.
* **The Dashboard Insight:** The Inventory dashboard highlights immediate operational risks.
    * We currently have 60 unique products sitting below their critical reorder point.
    * With an average supplier lead time of 16 days, these products are at high risk of extended stockouts.
    * Furthermore, inventory is heavily skewed toward the APAC region (1,977 active units), while US markets have tighter margins of error.
* **Strategic Action:** Expedite purchase orders for the 60 items below the threshold, prioritizing the "Most Reordered" items like ZenLife Clothing Item 55. Evaluate shifting safety stock from APAC to US warehouses to support our largest customer base.

<!-- 📸 UPLOAD YOUR "INVENTORY & SUPPLY CHAIN" SCREENSHOT HERE -->
*Visual Evidence: Supply Chain & Inventory Dashboard*
# Products & Suppliers
<img width="1326" height="737" alt="Products   Supplier" src="https://github.com/user-attachments/assets/8fde085a-4732-4b86-84ca-876091759387" />

# Inventory
<img width="1323" height="739" alt="Inventory" src="https://github.com/user-attachments/assets/2dbae439-39aa-499c-878f-0fb078197c9b" />

### Challenge 5: Margin Optimization & Pricing Parity
* **The Problem:** Determining exactly which levers to pull to increase profit margins without losing market share to competitors.
* **The Dashboard Insight:** The AI-driven Pricing and Decomposition dashboards provided a clear roadmap for margin expansion.
    * **Competitive Parity:** We are currently pricing with incredible precision. For our massive Electronics category, our listed average is $680, against a competitor average of $679.
    * **The Margin Lever:** The AI Key Influencers visual proved that the Beauty & Health and Clothing categories are our strongest drivers for margin percentage increases (+0.19 and +0.14 impact, respectively).
* **Strategic Action:** Maintain current competitive pricing on Electronics to protect market share. To drive profitability, safely execute small price increases (0.5% - 1.5%) within the Beauty & Health and Clothing categories, as the AI indicates these categories have the elasticity to absorb the hike while expanding our overall margin.

*Visual Evidence: Pricing Strategy & AI Key Influencers*
---
<img width="1316" height="739" alt="Price History" src="https://github.com/user-attachments/assets/be0377d2-b484-48f7-b59a-55977e961430" />
<img width="1313" height="737" alt="Advanced" src="https://github.com/user-attachments/assets/a9bc0f8b-09bc-466d-b560-885db9b541a5" />


## 🛠️ Technical Implementation
* **Tooling:** Power BI, Power Query, DAX
* **Analytical Techniques Used:** 
  * Advanced filtering context and DAX logic (MoM variance, ROAS modeling, active vs. inactive aggregation).
  * AI-driven Key Influencer regression analysis to isolate margin drivers.
  * Interactive UI/UX design (dynamic slicers, customized KPI cards, intelligent tooltips).
