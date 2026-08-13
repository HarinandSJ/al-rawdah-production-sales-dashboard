# Al Rawdah - Production & Sales Performance Dashboard

![Dashboard Overview](Screenshot%202026-08-13%20200015.png)

## 📌 Business Overview & Objective
Al Rawdah requires end-to-end visibility across its manufacturing efficiency, commercial revenue, and operational sustainability. The objective of this Power BI report is to track key performance indicators (KPIs) across three main pillars:

1. **Production Analysis:** Monitoring batch yield efficiencies, defect rates, and monthly volume trends by production shifts.
2. **Sales & Revenue Overview:** Evaluating total profitability, high-performing product SKUs, regional dispatch distributions (UAE), and channel breakdowns.
3. **Operations & Sustainability:** Tracking factory downtime, energy/water intensity, warehouse cost vs. revenue, and logistics modes.

---

## 🛠️ Data Architecture & Tech Stack
* **Business Intelligence:** Power BI Desktop
* **Analytics Techniques:** DAX (Data Analysis Expressions) for custom KPI measures, Tooltip pages, interactive page navigation, and dynamic slicing.
* **Key Visuals Used:** Custom Tooltip Cards, Treemaps (Dispatch Regions), Donut Charts (Channel Distribution & Volume), Horizontal Bar Charts, Multi-Line Trend Charts.

---

## 📊 Key Insights & Dashboard Architecture

### Page 1: Navigation Landing Page
* Provides an intuitive landing interface with page navigation buttons leading to detailed functional views.

---

### Page 2: Production Analysis
![Production Analysis](Screenshot%202026-08-13%20200042.png)

* **Key Metrics:**
  * **Total Volume:** 22M Bottles Produced
  * **Yield Efficiency:** 98.14%
  * **Defect Rate:** 1.86%
* **Key Visual Insights:**
  * **Shift Performance:** Production tracks an upward volume trend from January to June, with Morning and Evening shifts consistently driving higher volumes compared to Night shifts.
  * **Line Efficiency:** Line B and Line C lead in yield efficiency (>98.15%), while Line A presents the highest opportunity for process improvement (~98.00%).
  * **Product Volume Mix:** 330ml and 500ml bottles account for nearly ~89.5% of total bottle volume combined, while 5 Gallon units represent 10.49%.

---

### Page 3: Sales Overview
![Sales Overview](Screenshot%202026-08-13%20200111.png)

* **Key Metrics:**
  * **Total Revenue:** AED 43.01M
  * **Total Profit:** AED 18.98M
  * **Profit Margin:** 44.14%
* **Key Visual Insights:**
  * **Product Profitability:** 500ml and 330ml products achieve higher profit margins (~50%) compared to 5 Gallon containers (~40%).
  * **Regional Revenue (Dispatch):** Abu Dhabi and Dubai represent the majority of regional sales dispatch revenue, followed by Sharjah, Al Ain, and Other UAE territories.
  * **Channel Mix:** Retail generates over 50% of revenue, followed by Wholesale (~29.69%), Online (~10.18%), and Subscription (~10.11%).

---

### Page 4: Operational Performance & Logistics
![Operation Performances](Screenshot%202026-08-13%20200139.png)

* **Key Metrics:**
  * **Total Downtime:** 41.88 Days
  * **Water Intensity Ratio:** 2.92
  * **Energy Consumption:** 512.25K kWh
* **Key Visual Insights:**
  * **Energy Trends:** Daily energy consumption shows noticeable spikes heading into summer months (May–June 2024), hitting peaks near 3,500 kWh.
  * **Logistics Cost Breakdown:** Company-owned trucks represent the largest transport expense category, outstripping Contractor and 3PL (Third-Party Logistics) costs.
  * **Warehouse Efficiency:** Dubai Hub and Mussafah lead in both cost and overall energy consumption.

---

## 💡 Strategic Business Recommendations
1. **Reduce Factory Downtime:** Investigate line degradation in Line A to lift its yield efficiency from 98.00% closer to the 98.15% benchmark set by Line B.
2. **Capitalize on High-Margin SKUs:** Increase production allocation and promotional spend toward 330ml and 500ml SKUs, which yield a 50% profit margin.
3. **Logistics Optimization:** Re-evaluate transport fleet utilization by analyzing if converting more routes to Third-Party Logistics (3PL) reduces fixed company truck overheads.
