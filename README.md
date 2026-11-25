# 📌 Vehicle Parts Sales Analysis & Regional Account Performance

## Overview
This project delivers a comprehensive data-driven analysis of vehicle parts sales performance, regional warehouse distribution, and B2B vs. B2C client purchasing behavior. Leveraging relational database queries on CRM order data, this analysis evaluates volume dynamics, revenue contribution across channels, hub efficiency, and product demand patterns to guide inventory management, regional stocking, and revenue optimization strategies.


# Business Questions.
## Question 1 : Which vehicle part product lines drive the highest overall volume demand, and how are sales distributed across product categories?
<img width="392" height="240" alt="image" src="https://github.com/user-attachments/assets/e2312270-25fe-4cd3-8e57-abdec2578758" />

## Key Highlights & Answer:

- **Core Volume Drivers:** Suspension & traction ranks #1 overall with 2,145 units sold, closely followed by Breaking system at 2,130 units. Together, these two categories represent the bulk of transactional inventory movement.
- **Secondary Tier:** Electrical system (1,698 units) and Frame & body (1,619 units) maintain strong, consistent turnover.
- **Niche & Low-Volume Lines:** Miscellaneous parts recorded 1,176 units, while Engine parts generated the lowest volume at 627 units—indicating a lower-turnover, higher-margin profile typical of major engine components.

## Question 2 : What are the top three best-selling vehicle part categories for each regional warehouse, and how does customer demand vary geographically?
<img width="571" height="333" alt="image" src="https://github.com/user-attachments/assets/c00c29c7-230f-4c4a-b39f-a70fefadac70" />

## Key Highlights & Answer:

- **Central Warehouse:** Breaking system leads at 1,024 units, followed by Suspension & traction (980 units) and Electrical system (838 units).
- **North Warehouse:** Suspension & traction leads at 866 units, followed by Frame & body (675 units) and Electrical system (607 units).
- **West Warehouse:** Breaking system leads at 501 units, followed by Suspension & traction (299 units) and Miscellaneous (259 units).

## Question 3 : How is revenue distributed between Wholesale (B2B) and Retail (B2C) clients across each vehicle part product line?
<img width="597" height="427" alt="image" src="https://github.com/user-attachments/assets/42ccffdb-1e4a-49e3-af7b-0759b7f41c1b" />


## Key Highlights & Answer:

- **Wholesale Dominance:** Wholesale accounts generate the majority share of total revenue in almost all categories, led by Breaking system (60.32% Wholesale / $23,130.90) and Frame & body (57.19% Wholesale / $39,477.89).
- **Balanced Demand:** Electrical system exhibits the most balanced split between Retail (50.12% / $21,858.30) and Wholesale (49.88% / $21,754.41).
- **High-Value Categories:** Frame & body and Suspension & traction represent the highest gross revenue categories for both client types.

## Question 4 : What is the total annual sales performance for each warehouse, and which product lines are the top and bottom performers per facility?
<img width="800" height="140" alt="image" src="https://github.com/user-attachments/assets/77d78862-5adc-436c-9266-0a4f2f0f1826" />

## Key Highlights & Answer:

- **Central Hub Leadership:** Central Warehouse generated the highest revenue at $141,982.88, driven by Suspension & traction as the most sold line and Miscellaneous as the least sold line.
- **North Performance:** North Warehouse recorded $100,203.63 in total revenue, with Suspension & traction leading sales and Engine parts yielding the lowest turnover.
- **West Growth Opportunity:** West Warehouse recorded $46,926.49 in revenue, with Frame & body as its top product line and Engine parts as the lowest performer.

## 💡 Final Insights & Strategic Recommendations

### Core Insights
The empirical findings underscore a strong operational reliance on fast-moving replacement parts (**Suspension & traction** and **Breaking systems**), which reliably drive both high transactional volume and major revenue shares. Regionally, fulfillment capability is heavily centralized, with the Central warehouse accounting for nearly half of overall revenue ($141.98k out of ~$289.11k). Channel-wise, **Wholesale accounts represent the primary financial engine**, delivering over 50% to 60% of total revenue across nearly all major inventory categories. Conversely, major **Engine components** exhibit low sales turnover across all facilities, frequently lagging as the least-sold item in multiple territories.

### Recommendations
* **Dynamic Regional Stock Allocation:** Realign safety stock thresholds by allocating expanded floor space for high-velocity lines (**Suspension & traction**, **Breaking systems**) at Central and North hubs while minimizing slow-moving **Engine** holdings to cut carrying costs.
* **Wholesale Loyalty & B2B Expansion:** Develop structured bulk-pricing tiers and commercial credit incentives targeting auto repair chains and regional fleets, specifically around heavy wholesale drivers like **Frame & body** and **Breaking systems**.
* **West Hub Operational Review:** Conduct a logistics and market demand audit for the West warehouse region to pinpoint root causes for its low revenue performance ($46.9k) relative to Central ($141.9k) and explore regional marketing initiatives to stimulate commercial account acquisition.
