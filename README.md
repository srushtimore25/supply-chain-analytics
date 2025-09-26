# supply-chain-analytics
This project analyzes supply chain data to uncover insights on revenue, costs, lead times, transportation modes, and inventory management. It includes a complete diagnostic report, interactive Tableau/Power BI dashboards, and actionable recommendations to optimize efficiency, reduce costs, and improve profitability

# CDACL-003 — Supply Chain Analysis

**Project summary**
Using a company's supply chain dataset, this project delivers:
- Diagnostic supply-chain report and recommendations
- Interactive dashboards (Overview, Profitability, Supply Chain Deep Dive)
- Comparative analysis across products, routes and transportation modes
- Supporting scripts to fetch and prepare data

---

## 🔍 Key Insights (Diagnostic Report)

1. **Revenue & Profitability**
   - Total Revenue: **$578K** from **46K units sold**
   - Average Profit per SKU: **$6K**
   - Profitability is highest in **Skincare ($0.24M)** followed by **Haircare ($0.17M)** and **Cosmetics ($0.16M)**

2. **Cost Analysis**
   - Average Manufacturing Cost: **$47.3**
   - Average Shipping Cost: **$5.5 per unit**
   - Shipping cost is consistent across transportation modes (suggesting flat-rate agreements or hidden inefficiencies).

3. **Supply Chain Efficiency**
   - Average Lead Time: **16 days**, varying slightly by route (15–17 days).
   - Stock Levels: Balanced, but **Cosmetics shows higher risk of out-of-stock** (lower availability).

4. **Transportation & Distribution**
   - Modes used: Road (29%), Rail (28%), Sea (26%), Air (17%).
   - Revenue distribution favors **Route A ($0.25M)** > **Route B ($0.20M)** > **Route C ($0.12M)**.
   - Heavy reliance on Road + Rail may create risks if disruptions occur.

5. **Customer Demographics**
   - Sales are diversified: Female (31%), Male (23%), Non-binary (25%), Unknown (21%).
   - Balanced customer base → marketing strategies should be inclusive and multi-segmented.

---

## 📌 Recommended Actions

1. **Optimize Costs**
   - Negotiate with carriers to ensure flat-rate contracts are not hiding inefficiencies.
   - Explore cost-sharing between Air and Road to reduce lead times without major cost increase.

2. **Improve Inventory Management**
   - Increase safety stock for **Cosmetics** due to higher risk of shortage.
   - Use demand forecasting to rebalance inventory between product categories.

3. **Enhance Transportation Strategy**
   - Diversify transportation modes to reduce dependency on Road/Rail.
   - Evaluate cost–time tradeoffs of shifting some shipments from Sea to Rail/Air.

4. **Route Optimization**
   - Route A generates the most revenue but has slightly higher lead times → consider alternate logistics partners.
   - Route C underperforms in revenue → evaluate whether to consolidate shipments or renegotiate supplier terms.

5. **Customer Engagement**
   - Tailor promotions for **Skincare**, as it delivers the highest profit margin.
   - Segment marketing campaigns by gender & product type to maximize reach.

---

## 🖼 Dashboards
See `/images/` for:
- **Overview Dashboard**
- **Profitability Analysis**
- **Supply Chain Deep Dive**

🎯 Conclusion

This project demonstrates how supply chain data can be transformed into actionable business insights.
Through diagnostic reporting and interactive dashboards, we identified key performance drivers, inefficiencies, and opportunities for optimization across costs, lead times, transportation modes, and product categories.

By implementing the recommended actions, the company can:

Reduce costs,

Improve inventory availability,

Strengthen logistics resilience, and

Maximize profitability.

📌 This repository contains all supporting code, sample data, and dashboards to reproduce the analysis.
It serves as a foundation for future enhancements, such as predictive modeling and real-time supply chain monitoring.
---

