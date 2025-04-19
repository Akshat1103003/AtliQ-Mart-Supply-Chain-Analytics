# AtliQ-Mart-Supply-Chain-Analytics
This Report aims to provide analytics related to Supply Chain Analysis .
## 📊 Link of Live Dashboard  

🔗 **[View Dashboard in Power BI](https://app.powerbi.com/view?r=eyJrIjoiYzJjM2ZhNWMtNDg4Zi00MmUwLWI1ZjItMDk4MDJjNGM0MGE0IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9&pageName=094201de7f7b8f9fcfc8)**  

-----
### 1.  Overall Performance (Grand Total) 

- ✔ Total Order Lines -	**31.73K**	Total unique order transactions across all customers.
- ✔ Ordered Qty	**13,427K** -	Total quantity of items ordered.
- ✔ Delivered Qty	**12,969K** - Total quantity of items delivered.
- ✔ D/O Gap %	**-3.41%** -	Overall delivery shortfall of 3.41% – some demand not fulfilled.
- ✔ ADDD	**1.69** -	Average Days Delay in Delivery – indicates moderate delays.
- ✔ OT %	**59.03%** -	59.03% of orders were delivered on time.
- ✔ IF %	**52.78%** - 52.78% of orders were delivered in full (complete quantity).
- ✔ OTIF %	**29.02%** - Only 29.02% of orders met both on-time and in-full criteria.
- ✔ LFR %	**65.96%** - Line Fill Rate – 65.96% of ordered lines were fulfilled (regardless of time).
- ✔ VFR %	**96.59%** - Volume Fill Rate – 96.59% of ordered volume was fulfilled.
- ✔ Delayed Orders %	**40.97%** - 40.97% of orders were delivered late.
- ✔ BR %	**34.00%** - Backorder Rate – 34% of items were not fulfilled and backordered.
------------------
### 2. 🏙️ City & Customer Insights – Analysis

### 🔍 General Observations :
✅ Strengths:
- **High Volume Fulfillment (VFR%**) : All cities maintain a VFR above 96%, indicating strong ability to deliver ordered quantities.
- **Consistent OT and IF %** : While not optimal, all cities show similar On-Time and In-Full performance, suggesting no outlier city is dragging performance down.
- **Surat has best OTIF% (30.07%)** : Leading city in overall fulfillment quality .

⚠️ Opportunities for Improvement :
- **Low OTIF % across all** : All cities have OTIF below 31%, far from ideal.
- **Significant Backorder Rate (BR%)** : Average BR across cities is 34%, with Vadodara highest at 36.3%.
- **Delivery Gaps (D/O Gap%)** : All cities show negative D/O Gap, meaning under-delivery vs order quantity.
- **High Delayed Orders** : Delayed orders still affect over 40% of the total city performance.

- **Total Order Lines**: Highest in **Ahmedabad (11.06K)**, followed closely by **Vadodara (10.97K)**.
- **Delivery Performance**:
  - All three cities show similar delivery performance with a **D/O Gap %** around **-3.63 - -3.35%**.
- **ADDD (Average Days to Deliver)**: Fairly consistent across cities (~1.69 days).
- **On-Time % (OT)**: **Moderate**, suggesting compromised delivery times.
- **In-Full % (IF)**: Indicates average performance in delivering complete quantities, with values between **51% - 52%**.
- **OTIF % (On Time In Full)**: ** Very low **(29%)**, pointing toward major fulfillment challenges.
- **LFR % (Line Fill Rate)** & **VFR % (Volume Fill Rate)**: These are **much better** (~96%) compared to OTIF, showing that the **volume was delivered**, but not on time or completely by line.
- **Delayed Orders %**:
  - Surprisingly **high overall **(40.9%)**.
  - **Surat** performs much better with  **only 11.85% delayed orders**.

- **BR % (Backorder Rate)**: Highest in **Vadodara (36.3%)**, which might indicate capacity constraints or inventory gaps.
- **Contribution %**: Ahmedabad leads slightly in contribution (34.86%), followed by Vadodara (34.58%).

| City        | Total Order Lines | Ordered Qty | Delivered Qty | D/O Gap % | ADDD | OT %  | IF %  | OTIF % | LFR % | VFR %  | Delayed Orders % | BR %  | Contribution % |
|-------------|-------------------|-------------|----------------|------------|------|-------|-------|--------|--------|--------|-------------------|--------|----------------|
| Vadodara    | 10.97K            | 4624K       | 4456K          | -3.63%     | 1.69 | 57.98% | 51.56% | 27.78% | 63.69% | 96.37% | 14.53%            | 36.3% | 34.58%         |
| Ahmedabad   | 11.06K            | 4612K       | 4463K          | -3.24%     | 1.70 | 58.16% | 54.20% | 29.33% | 67.56% | 96.76% | 14.59%            | 32.4% | 34.86%         |
| Surat       | 9.70K             | 4190K       | 4050K          | -3.35%     | 1.67 | 61.21% | 52.55% | 30.07% | 66.69% | 96.65% | 11.85%            | 33.3% | 30.56%         |
| Total       | 31.73K            | 13427K      | 12969K         | -3.41%     | 1.69 | 59.03% | 52.78% | 29.02% | 65.96% | 96.59% | 40.97%            | 34.0% | 100.00%       |

--------

### 3. 🏪 Customer-Level Performance Insights -  Analysis  

### 📌 Highlights: Metric Value Insights : 
- Total Order Lines	**31.73K** : Substantial overall volume indicating wide customer engagement.
- **Ordered Qty	13.43M** units - Total demand across all customers.
- **Delivered Qty	12.97M units** - ~96.5% fulfillment rate (strong performance).
- **D/O Gap %	-3.41%**	Indicates under-delivery trend.
- **Average ADDD 1.69 days** - Reasonably short average delay from dispatch to delivery.
- **OT % (On Time)	59.03%** - Needs improvement (below optimal threshold of ~80%).
- **IF % (In Full)	52.78%** - Indicates gaps in order completeness.
- **OTIF %	29.02%** - Critical metric – below ideal, showing alignment issues in delivery.
- **LFR % (Line Fill Rate)	65.96%** - Indicates partial order fulfillment is frequent.
- **VFR % (Volume Fill Rate)	96.59%** - Strong performance in volume-based fulfillment.
- **Delayed Orders %	40.97%** - High – requires attention to delivery planning.
- **BR % (Backorder Rate)	34.0%** -	High backorder rate, major operational bottleneck.
  
----------------

## 3.1 🏆 Top 5 Best Performing Customers (By OTIF % ) :
| Customer         | OTIF % | IF %    | OT %    | BR %   | Delayed Orders % |
|------------------|--------|---------|---------|--------|------------------|
| **Propel Mart**     | **40.92%** | 59.74% | 73.64% | 24.4% | 2.01% |
| **Atlas Stores**    | 39.55% | 59.78% | 71.81% | 24.5% | 1.46% |
| **Viveks Stores**   | 39.44% | 60.07% | 70.61% | 24.9% | 1.51% |
| **Expert Mart**     | 39.11% | 59.81% | 72.54% | 24.5% | 1.43% |
| **Logic Stores**    | 38.78% | 60.14% | 70.82% | 25.6% | 1.54% |

- ✅ **Why They Perform Well:**
  - High **IF** & **OT** values.
  - Low **Backorder %**.
  - Minimal **delays** and strong VFR.

---

## 3.2 🚨 Bottom 5 Worst Performing Customers (By OTIF % ) :
| Customer            | OTIF % | IF %    | OT %    | BR %   | Delayed Orders % |
|---------------------|--------|---------|---------|--------|------------------|
| **Coolblue**           | **13.75%** | 44.73% | 29.13% | 48.5% | 5.44% |
| **Acclaimed Stores**   | 15.47% | 52.36% | 29.43% | 41.1% | 7.81% |
| **Lotus Mart**         | 16.34% | 53.35% | 28.11% | 39.9% | 8.04% |
| **Elite Mart**         | 24.37% | 37.94% | 72.45% | 47.3% | 1.42% |
| **Info Stores**        | 25.52% | 41.16% | 70.94% | 46.9% | 1.53% |

- ⚠️ **Why They Underperform:**
  - Very low **OT** or **IF** scores.
  - High **Backorder %** (up to ~49%).
  - Delays common in some high-volume customers.

---

## 🧠 Key Takeaways :
1. **Focus Recovery on Coolblue, Acclaimed, Lotus**
   - Major improvement needed in **OT** and **inventory accuracy**.
   - Investigate **backorder reasons**, improve warehouse allocation.

2. **Strengthen High Potential Customers**
   - Propel Mart, Atlas, and Viveks show what’s working. Replicate their practices.
   - Reward reliable customers with better SLAs or lead-time reductions.

3. **Improve OTIF Through Digital Coordination**
   - Use advanced planning tools or real-time alerts to reduce delays.
   - Build an **early-warning system** based on IF % drops or rising BR%.

4. **Inventory Optimization**
   - Backorder rate >30% shows potential **stocking or forecasting issues**.
   - Work with planning team to revise forecast inputs & reorder points.

-----------
### 4. 📊 Category & Product Insights – Performance Analysis  

## ✅ Overall Performance Summary

| Metric                | Total        | Insight                                                                 |
|----------------------|--------------|------------------------------------------------------------------------|
| **Total Orders**     | 31.73K       | Healthy order volume overall                                           |
| **Ordered Qty**      | 13.43M       | Large scale operation, with ~97% delivery success                      |
| **Delivered Qty**    | 12.97M       | Strong performance despite delays                                      |
| **OTIF %**           | 47.95%       | Only ~48% orders delivered *on-time and in-full* — improvement needed  |
| **IF %**             | 65.96%       | 2/3rd of the orders delivered fully                                    |
| **OT %**             | 71.12%       | Fairly strong on-time performance overall                              |
| **VFR %**            | 96.59%       | Very high quantity fulfillment rate                                    |
| **Delayed Orders %** | 40.97%       | Alarmingly high — nearly half the orders have delays                   |
| **ADDD**             | 1.69 days    | Average Delay in Days Delivered                                        |
| **BR %**             | 34.0%        | Return rate is consistent across categories                            |

---

## 🥇 Category-Wise Performance

### 1. 🧀 **Dairy** (Top Contributor)
- **Contribution**: 66.72% of total volume
- **IF %**: 65.95% – consistent with total
- **OTIF %**: 47.83% – moderate
- **Delayed Orders %**: **29.93%** – much higher than others
- **VFR %**: 96.59% – stable quantity fulfillment

**Insight**: Dairy is the backbone but suffers from **high delivery delays**. Prioritize logistics and supply planning.

---

### 2. 🍽 **Food**
- **IF %**: 66.43% – best among categories
- **OTIF %**: **48.84%** – **highest**
- **LFR & VFR %**: Strong fill performance
- **Contribution**: 16.71%

**Insight**: Best in service performance with room for **growth and expansion**.

---

### 3. 🥤 **Beverages**
- **IF %**: 65.54%
- **OTIF %**: 47.55% – lowest
- **Delayed Orders %**: 8.28%
- **Contribution**: 16.57%

**Insight**: Consistent but underperforming on OTIF and IF %. Needs focus on **improving delivery reliability**.

---

## 🔧 Recommendations

1. **Reduce Delays in Dairy**: Improve scheduling, transport, and inventory management.
2. **Leverage Food Category**: Excellent service metrics — ideal for scaling.
3. **Improve Beverages**: Streamline fulfillment to boost OTIF and reliability.
4. **Track OTIF Trends**: Continuously monitor performance gaps to act proactively.

---
# 📦 Product Performance Analysis

## 🏆 Top 5 Overall Performing Products

| Rank | Product           | Highlights                                                                 |
|------|-------------------|---------------------------------------------------------------------------|
| 1    | **AM Biscuits 750** | Highest OTIF (50.48%), strong across OT%, IF%, LFR%, BR, lowest delayed orders |
| 2    | **AM Biscuits 500** | High OTIF (48.58%), strong OT%, IF%, good fill rates                      |
| 3    | **AM Butter 100**   | Good OT%, IF%, OTIF (48.08%), strong LFR and low delay %                   |
| 4    | **AM Milk 100**     | Very balanced performance across all metrics                               |
| 5    | **AM Curd 250**     | Strong IF% (67.05%), high OTIF, low D/O Gap, balanced delivery             |

---

## 🚩 Bottom 5 Overall Performing Products

| Rank | Product           | Issues                                                                       |
|------|-------------------|-------------------------------------------------------------------------------|
| 1    | **AM Butter 250**  | Lowest IF % (63.52%), poor OTIF %, high BR %, poor fill rates                |
| 2    | **AM Ghee 250**    | Low IF%, OT%, OTIF; weak delivery consistency                                |
| 3    | **AM Ghee 150**    | Below average across all KPIs                                                |
| 4    | **AM Tea 100**     | Low OT%, IF%, OTIF %; fair D/O Gap but lags elsewhere                        |
| 5    | **AM Butter 500**  | Low OTIF %, moderate performance overall but slightly underperforms others   |

---

## 📊 Summary Statistics

| Metric              | Value       | Insights                                                                 |
|---------------------|-------------|--------------------------------------------------------------------------|
| **Avg OTIF %**      | 47.95%      | Less than half the orders delivered *on-time and in-full*                |
| **Avg IF %**        | 65.96%      | ~2/3 orders delivered in full                                            |
| **Avg OT %**        | 71.12%      | Better on-time delivery overall                                          |
| **Delayed Orders %**| 40.97%      | High — major area for improvement                                        |
| **ADDD**            | 1.69 days   | On average, deliveries are delayed by ~1.7 days                          |
| **BR %**            | 34.0%       | Return rates are stable                                                  |

---

## 🛠 Recommendations

1. **Focus on AM Butter 250 & AM Butter 500**  
   - High contribution, **lowest OTIF %** — improve logistics, planning.

2. **Leverage Top Products (Curd & Biscuits)**  
   - AM Curd 250 & AM Biscuits 750 show **consistently high performance**.

3. **Address Delays Across All**  
   - 40% delayed orders is significant; reduce ADDD to improve OTIF.

4. **Improve OTIF to Boost Service Level**  
   - Even small improvements can raise overall customer satisfaction.

------

## 🔍 Observations & Insights

- **Best Overall Performer**:  
  `AM Biscuits 750` stands out with **highest OTIF (50.54%)**, **highest LFR (68%)**, and **lowest D/O Gap (-3.15%)** among biscuit products.

- **Worst OTIF Performer**:  
  `AM Butter 500` with **46.39% OTIF**, despite good order volume, signals delivery issues.

- **High Contribution Products**:  
  `AM Milk 100`, `AM Milk 250`, and `AM Milk 500` contribute around **5.58% - 5.60%**, suggesting they are key volume drivers.

- **Delayed Orders Concerns**:  
  - `AM Ghee 250` (30.41%) and `AM Ghee 150` (30.13%) have **high delayed order %**, pointing to upstream bottlenecks or inventory challenges.

- **Category Patterns**:
  - **Milk & Curd** products generally perform better in OTIF and IF.
  - **Ghee** and **Butter** products show higher BR and delay risks.
  - **Tea** products are stable but have limited contribution share.

---
--------------
### 5. Performance Analysis : Actuals VS. Targets 📊

| Metric                  | Actual (%) | Target (%) | Gap (%)  |
|-------------------------|-----------|-----------|---------|
| **OT (On-Time Delivery)**  | 59.03     | 87        | -27.97  |
| **IF (In-Full Delivery)**  | 52.78     | 79        | -26.22  |
| **OTIF (On-Time In-Full)** | 29.02     | 68        | -38.98  |

#### 🔍 Key Takeaways:
- OT % (On-Time Delivery) is 71.12% -  **below target** – Orders are not being dispatched/delivered as scheduled, causing delays.
- IF % (In-Full Delivery) is 65.96% - **below target** – Many orders are not being fulfilled completely. This may be due to stock shortages, inaccurate demand forecasting, or supply chain inefficiencies .
- OTIF % (On-Time In-Full) is the **biggest concern** **(47.95%)** - **below target**  – This suggests a major breakdown in end-to-end supply chain execution .

## 📈 Opportunities for Improvement  for Cities & Customers  : 

✔ **Reduce Order Lead Time**  
   - Target stores with **high lead times (3.2–3.3 days)** and optimize **logistics**.  

✔ **Improve Supplier Performance for Struggling Stores**  
   - **Lotus Mart, Coolblue, and Acclaimed Stores** need **better inventory planning**.  

✔ **Enhance On-Time Delivery (OT%) Across All Locations**  
   - Aim to increase **OT% from 71% → 75%+** for better **reliability**.  

✔ **Monitor & Reduce Backorders**   
   - Stores with **70%+ backorders** should implement **demand forecasting & stock optimization**.

------------ 
### 📌 Action Plan for Improvement  

#### 🔹 Address Delivery Delays (Improve OT%)  
✅ Optimize **logistics & routing** to minimize transit delays.  
✅ Strengthen **supplier performance tracking** & contracts with **stricter SLAs**.  
✅ Implement **real-time tracking** for better visibility.  

#### 🔹 Improve Order Fulfillment (Boost IF%)  
✅ Reduce **stockouts** by enhancing **demand forecasting using AI/ML**.  
✅ Strengthen **warehouse operations** & **order picking efficiency**.  
✅ Improve **supplier reliability** and **inventory planning**.  

#### 🔹 Enhance Overall OTIF Performance  
✅ Align **production planning** with **demand fluctuations**.  
✅ Implement **buffer inventory** for critical SKUs to avoid fulfillment issues.  
✅ Improve **coordination** between **procurement, warehouse, and logistics teams**.  


### Final Thoughts for City & Customer Analysis :
- The supply chain performance is sub-optimal, with significant gaps in fulfillment.
- Key priority should be increasing OTIF% and reducing delayed orders.
- Some stores (Coolblue, Acclaimed, Lotus Mart) require urgent intervention to improve service levels.
-------------
### 🔄 Potential Improvement Strategies  for Products  :

✔ **Increase Inventory Buffer** → High backorder rates indicate **stock shortages**.  
   - Improve **demand forecasting** and maintain **safety stock levels**.  

✔ **Enhance Supplier Coordination** → Delayed orders suggest **inefficiencies in supplier performance**.  
   - Strengthen **partnerships** and implement **better tracking mechanisms**.  

✔ **Optimize Distribution & Logistics** → Reduce **average delivery delay (~1.68 days)**.  
   - Improve **routing, warehouse optimization,** or leverage **third-party logistics partnerships**.  

✔ **Improve OTIF% Performance** → Focus on **on-time deliveries** by enhancing:  
   - **Supply chain visibility**  
   - **Warehouse efficiencies**  








