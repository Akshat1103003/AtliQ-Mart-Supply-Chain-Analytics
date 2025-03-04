# AtliQ-Mart-Supply-Chain-Analytics
This Report aims to provide analytics related to Supply Chain Analysis .
-----
### 1.  Overall Performance (Grand Total) 
- ✔ OT% (On-Time Percentage): **59.03%** → Nearly 41% of orders are delayed.
- ✔ IF% (In-Full Percentage): **52.78%** → Almost 47% of orders are not fully fulfilled.
- ✔ OTIF% (On-Time In-Full): **29.02%** → Only 29% of orders are delivered both on time and in full.
- ✔ LFR% (Line Fill Rate): **66.0%** → 34% of line items are not fulfilled.
- ✔ VFR% (Volume Fill Rate): **96.59%** → High, indicating that overall order volume is mostly fulfilled.
- ✔ Order Lead Time: **2.42** days on average.
- ✔ Delayed Orders: **28.88%** → Nearly 1 in 3 orders is delayed.
- ✔ Backorder Rate: **34.0%** → 1 in 3 orders experiences a backorder, affecting customer satisfaction.
------------------
### 2. 🏙️ City Level Performance
- Best City in OTIF%: Surat (**30.07%**), but still below ideal levels.
- Worst City in OTIF%: Vadodara (**27.78%**), indicating major fulfillment issues.
- Highest Delayed Orders: Vadodara (**30.09%**), requiring urgent attention.
- Worst Backorder Rate: Vadodara (**36.3%**), suggesting significant supply issues.
  
| City      | OT%    | IF%    | OTIF%  | LFR%  | VFR%  | Order Lead Time | Delayed Orders | Backorder Rate |
|----------|--------|--------|--------|-------|-------|----------------|----------------|----------------|
| Ahmedabad | 58.16% | 54.20% | 29.33% | 67.6% | 96.76% | 2.45 days | 30.00% | 32.4% |
| Surat     | 61.21% | 52.55% | 30.07% | 66.7% | 96.65% | 2.37 days | 26.33% | 33.3% |
| Vadodara  | 57.98% | 51.56% | 27.78% | 63.7% | 96.37% | 2.44 days | 30.09% | 36.3% |
-----
### 3. 🏪 Store-Level Analysis  
#### 3.1 : Best-Performing Stores (High OTIF%)

| Store                        | OTIF%  | OT%    | IF%    | Order Lead Time | Delayed Orders |
|------------------------------|--------|--------|--------|----------------|----------------|
| Propel Mart (Vadodara)       | 42.48% | 74.08% | 61.31% | 2.12 days      | 14.26%         |
| Expression Stores (Vadodara) | 41.59% | 70.49% | 63.54% | 2.23 days      | 16.59%         |
| Info Stores (Vadodara)       | 41.33% | 71.14% | 62.59% | 2.21 days      | 17.42%         |
| Sorefoz Mart (Vadodara)      | 41.13% | 73.70% | 60.80% | 2.11 days      | 14.62%         |
#### 👉 Insights :
- Propel Mart with  ( **42.48%** )  has the highest OTIF%, indicating the best fulfillment rate.
- Low delayed orders (~ **14%** ) and lower order lead times (<2.2 days) help drive better performance.

#### 3.2 : Worst-Performing Stores (Low OTIF%)

| Store                      | OTIF%  | OT%    | IF%    | Order Lead Time | Delayed Orders | Backorder Rate |
|----------------------------|--------|--------|--------|----------------|----------------|----------------|
| Acclaimed Stores (Surat)   | 6.93%  | 29.84% | 22.38% | 3.20 days      | 71.84%         | 70.6%          |
| Coolblue (Vadodara)        | 7.14%  | 28.65% | 22.25% | 3.26 days      | 73.37%         | 70.8%          |
| Lotus Mart (Vadodara)      | 7.97%  | 28.33% | 23.83% | 3.32 days      | 73.72%         | 69.2%          |
| Elite Mart (Vadodara)      | 9.72%  | 72.20% | 16.61% | 2.16 days      | 15.36%         | 70.3%          |

👉 **Insights:**  
- **Acclaimed Stores (Surat)** has the lowest **OTIF% (6.93%)** → **Severe supply chain inefficiency**.  
- **Coolblue & Lotus Mart** also struggle with **OTIF <10%**, **high backorders (70%+),** and **long lead times (3.3 days)**.  
- These stores need **urgent process improvement & supply chain adjustments**. 🚨

---------------
### 4. Overall Performance (Grand Total) :
- Order Fill Rate: **96.6%** (Good, but slight improvements can be made).
- OTIF% (On-Time In-Full Delivery): **29.02%** (Very low, indicating inefficiencies in on-time and in-full deliveries).
- Backorder Rate: **34.0%**  -> Suggests High, showing frequent stockouts or supply issues .
- Delayed Orders: **28.88%** -> Suggests persistent delays in fulfillment  .

------------------
### 📊 Category-Specific Analysis  

#### 🥤 Beverages : 
✅ **High VFR% (96.52%–96.59%)** → Most orders are being validated successfully.  
⚠️ **Backorder Rate (33.9%–34.8%)** & **Delayed Orders (~28.5%)** indicate room for improvement in supply chain execution.  

#### 🥛 Dairy :
🔹 **Slightly better OTIF% (~29.02%)** compared to other categories but still low.  
⚠️ **Backorder Rate (32.5%–36.5%)** with **higher delays** compared to Beverages.  
🚨 **Ghee & Milk products** show the highest delayed orders → **Possible supply constraints or logistics issues.**  

#### 🍪 Food :
🏆 **Best Order Fill Rate (~96.9%)** among all categories.  
⚠️ **Backorder Rate (32.0%–34.8%)** shows similar challenges as Dairy & Beverages.  
🔴 **OTIF% remains at 29.02%**, meaning fulfillment issues persist across all categories.  

-----------
### 5. Performance Analysis : Actuals VS. Targets 📊

| Metric                  | Actual (%) | Target (%) | Gap (%)  |
|-------------------------|-----------|-----------|---------|
| **OT (On-Time Delivery)**  | 59.03     | 87        | -27.97  |
| **IF (In-Full Delivery)**  | 52.78     | 79        | -26.22  |
| **OTIF (On-Time In-Full)** | 29.02     | 68        | -38.98  |

#### 🔍 Key Takeaways:
- OT % (On-Time Delivery) is 28% below target – Orders are not being dispatched/delivered as scheduled, causing delays.
- IF % (In-Full Delivery) is 26% below target – Many orders are not being fulfilled completely. This may be due to stock shortages, inaccurate demand forecasting, or supply chain inefficiencies.
- OTIF % (On-Time In-Full) is the biggest concern (39% below target) – This suggests a major breakdown in end-to-end supply chain execution.

## 📈 Opportunities for Improvement  for Cities & Customers  : 

✔ **Reduce Order Lead Time**  
   - Target stores with **high lead times (3.2–3.3 days)** and optimize **logistics**.  

✔ **Improve Supplier Performance for Struggling Stores**  
   - **Lotus Mart, Coolblue, and Acclaimed Stores** need **better inventory planning**.  

✔ **Enhance On-Time Delivery (OT%) Across All Locations**  
   - Aim to increase **OT% from 59% → 75%+** for better **reliability**.  

✔ **Monitor & Reduce Backorders**   
   - Stores with **70%+ backorders** should implement **demand forecasting & stock optimization**.

### 📌 Action Plan for Improvement  

#### 🔹 Address Delivery Delays (Improve OT%)  
✅ Optimize **logistics & routing** to minimize transit delays.  
✅ Strengthen **supplier performance tracking** & contracts with **stricter SLAs**.  
✅ Implement **real-time tracking** for better visibility.  

####🔹 Improve Order Fulfillment (Boost IF%)  
✅ Reduce **stockouts** by enhancing **demand forecasting using AI/ML**.  
✅ Strengthen **warehouse operations** & **order picking efficiency**.  
✅ Improve **supplier reliability** and **inventory planning**.  

####🔹 Enhance Overall OTIF Performance  
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








