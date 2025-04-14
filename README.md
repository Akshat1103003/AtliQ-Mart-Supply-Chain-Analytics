# AtliQ-Mart-Supply-Chain-Analytics
This Report aims to provide analytics related to Supply Chain Analysis .
## 📊 Link of Live Dashboard  

🔗 **[View Dashboard in Power BI](https://app.powerbi.com/view?r=eyJrIjoiZGU4OGNjOWItZDMwMy00ZTFkLWFkYWItMDVkODNlN2I2M2Q5IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9&pageName=094201de7f7b8f9fcfc8)**  

-----
### 1.  Overall Performance (Grand Total) 
- ✔ Total Order Lines: **57.10K** → Order Lines were made over the last 6 months .
- ✔ OT% (On-Time Percentage): **71.12** → Nearly 30% of orders are delayed.
- ✔ IF% (In-Full Percentage): **65.96%** → Almost 34% of orders are not fully fulfilled.
- ✔ OTIF% (On-Time In-Full): **47.95%** → Only 52% of orders are delivered both on time and in full.
- ✔ LFR% (Line Fill Rate): **66%** → 34% of line items are not fulfilled.
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
  # City & Customer Insights

| City       | Total Order Lines | Ordered Qty | Delivered Qty | D/O Gap % | ADDD | OT %   | IF %   | OTIF % | LFR %  | VFR %  | BR %   | Contribution % |
|------------|-------------------|-------------|----------------|------------|------|--------|--------|--------|--------|--------|--------|-----------------|
| Vadodara   | 19.58K            | 4624K       | 4456K          | -3.63%     | 1.69 | 69.91% | 63.69% | 45.22% | 63.7%  | 96.37% | 36.3%  | 34.29%           |
| Ahmedabad  | 19.68K            | 4612K       | 4463K          | -3.24%     | 1.70 | 70.00% | 67.56% | 48.33% | 67.6%  | 96.76% | 32.4%  | 34.46%           |
| Surat      | 17.84K            | 4190K       | 4050K          | -3.35%     | 1.67 | 73.67% | 66.69% | 50.54% | 66.7%  | 96.55% | 33.3%  | 31.25%           |
| **Total**  | **57.10K**        | **13427K**  | **12969K**     | **-3.41%** | 1.69 | 71.12% | 65.96% | 47.95% | 66.0%  | 96.59% | 34.0%  | 100.00%          |

-----
### 3. 🏪 Store-Level Analysis  
#### 3.1 : Best-Performing Stores (High OTIF%)

| Customer        | Total Order Lines | Ordered Qty | Delivered Qty | D/O Gap % | ADDD | OT %   | IF %   | OTIF % | LFR %  | VFR %  | BR %   | Contribution % |
|----------------|-------------------|-------------|----------------|------------|------|--------|--------|--------|--------|--------|--------|-----------------|
| Propel Mart    | 4.85K             | 1144K       | 1118K          | -2.30%     | 1.45 | 85.62% | 75.62% | **65.05%** | 75.6%  | 97.70% | 24.4%  | 8.50%           |
| Atlas Stores   | 3.25K             | 761K        | 742K           | -2.42%     | 1.49 | 84.20% | 75.48% | 63.80% | 75.5%  | 97.58% | 24.5%  | 5.69%           |
| Expert Mart    | 3.33K             | 790K        | 769K           | -2.56%     | 1.48 | 84.62% | 75.48% | 63.61% | 75.9%  | 97.44% | 24.5%  | 5.83%           |
| Viveks Stores  | 3.22K             | 760K        | 742K           | -2.43%     | 1.57 | 83.42% | 75.06% | 63.04% | 75.1%  | 97.57% | 24.9%  | 5.64%           |
| Rel Fresh      | 4.90K             | 1156K       | 1126K          | -2.57%     | 1.52 | 84.84% | 74.54% | 63.04% | 74.5%  | 97.43% | 25.5%  | 8.59%           |

#### 👉 Insights :
- Propel Mart with  ( **65.05%** )  has the highest OTIF%, indicating the best fulfillment rate.
- Low delayed orders (~ **14%** ) and lower order lead times (<2.2 days) help drive better performance.

#### 3.2 : Worst-Performing Stores (Low OTIF%)

| Customer          | Total Order Lines | Ordered Qty | Delivered Qty | D/O Gap % | ADDD | OT %   | IF %   | OTIF % | LFR %  | VFR %  | BR %   | Contribution % |
|-------------------|-------------------|-------------|----------------|------------|------|--------|--------|--------|--------|--------|--------|-----------------|
| **Coolblue**          | 3.34K             | 777K        | 738K           | -4.92%     | 1.83 | 26.81% | 51.53% | **13.75%** | 51.5%  | 95.08% | 48.5%  | 5.85%           |
| Acclaimed Stores  | 4.80K             | 1120K       | 1074K          | -4.15%     | 1.81 | 26.89% | 58.93% | 15.24% | 58.9%  | 95.85% | 41.1%  | 8.40%           |
| Lotus Mart        | 4.87K             | 1157K       | 1111K          | -3.99%     | 1.82 | 25.73% | 60.08% | 16.06% | 60.1%  | 96.01% | 39.9%  | 8.53%           |
| Info Stores       | 3.23K             | 768K        | 731K           | -4.76%     | 1.55 | 83.14% | 53.05% | 43.48% | 53.1%  | 95.24% | 46.9%  | 5.65%           |
| Elite Mart        | 3.28K             | 772K        | 736K           | -4.71%     | 1.47 | 84.74% | 52.74% | 44.88% | 52.7%  | 95.29% | 47.3%  | 5.75%           |

👉 **Insights:**  
- **Coolblue** has the lowest **OTIF% (13.75%)** → **Severe supply chain inefficiency**.  
- **Coolblue ,Acclaimed Stores & Lotus Mart** also struggle with **OTIF 10-15%**, **high backorders in range 40% ,** and **long lead times (3.3 days)**.  
- These stores need **urgent process improvement & supply chain adjustments**. 🚨

---------------
### 4. Overall Performance (Grand Total) :
- Volume Order Fill Rate (VOFR%): **96.6%** (Good, but slight improvements can be made).
- OTIF% (On-Time In-Full Delivery): **47.95%** (Low, indicating inefficiencies in on-time and in-full deliveries).
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








