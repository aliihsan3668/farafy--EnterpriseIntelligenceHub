# Farafy Pro — Enterprise Demand Forecasting & Inventory Intelligence Hub

Live Production URL: https://farafy.vercel.app/#
SaaS Category: Business Intelligence (BI) / Predictive Operations Management
UI Theme: Midnight Gold Premium B2B 

Farafy Pro is an enterprise-grade, client-side software application designed to transform raw corporate transactional logs into automated procurement logistics and cash-flow diagnostics. Engineered strictly using pure client-side JavaScript, Tailwind CSS, and Chart.js, Farafy allows business owners and supply chain managers to optimize their warehouse capital requirements without external server dependencies, ensuring absolute corporate data privacy.

---

## ⚡ Core Business Value Provisions
* **Frozen Capital Diagnostics:** Automatically identifies overstocked surplus inventory and computes the exact monetary capital (in PKR) frozen on warehouse shelves.
* **Stockout Preemption Engine:** Calculates continuous Reorder Points (ROP) factoring in historical supplier lead times and daily demand standard deviations to trigger timely replenishment alarms.
* **Procurement Optimization:** Solves for the Economic Order Quantity (EOQ) to isolate the mathematical sweet spot where annual ordering costs and inventory carrying costs are perfectly minimized.

---

## 📐 Implemented Logistics Formulations

Farafy runs continuous client-side calculations using industry-standard supply chain mathematical models:

1. **Economic Order Quantity (EOQ):**
   $$EOQ = \sqrt{\frac{2 \times D \times S}{H}}$$
   *Where: $D$ = Annual Demand (Units), $S$ = Administrative Ordering Cost, $H$ = Unit Holding Cost per Year.*

2. **Safety Stock Buffer Cushion:**
   $$SS = Z \times \sqrt{L} \times \sigma$$
   *Where: $Z$ = Service Level Coefficient Confidence Factor, $L$ = Supplier Procurement Lead Time (Days), $\sigma$ = Daily Demand Volatility Standard Deviation.*

3. **Continuous Reorder Point (ROP):**
   $$ROP = \left( \frac{D}{365} \times L \right) + SS$$

---

## 📋 Comprehensive Operating Manual (How to Use)

### Step 1: Format Your Corporate Data Spreadsheet
To analyze data via Farafy, structure your internal inventory ledger matching our standard B2B schema parameters. Your `.csv` file must contain these exact columns in order:
* **SKU**: Unique Item Identifier/Code
* **AnnualDemand**: Total units projected or sold over a 365-day cycle
* **CurrentStock**: Total available units physically sitting in your warehouse today
* **OrderingCost**: Flatt-rate administrative/freight cost incurred per replenishment order
* **HoldingCost**: Annualized cost to hold a single unit of stock in storage
* **LeadTimeDays**: Total days required for your supplier to deliver stock after an order is cut
* **DailyVolatilityVariance**: The historical standard deviation of daily retail sales demand

*Tip: Click the **"Download CSV Template"** button on the top right of the application navigation ribbon to instantly fetch a pre-formatted template spreadsheet.*

### Step 2: Secure Data Ingestion
1. Navigate to the deployed production link.
2. Click the **"Load Business CSV"** command button.
3. Select your prepared `.csv` spreadsheet file from your local computer.
4. **Data Privacy Assurance:** Processing occurs instantly via the browser's native `FileReader API`. Your corporate financial data is processed in a client-side memory loop and is never uploaded to any remote web server.

### Step 3: Run Executive Diagnostics & Filters
* **Review Financial Drain:** Check the top metric dashboard ribbon to audit your total frozen overstock capital liabilities.
* **Isolate High-Risk SKUs:** Utilize the dynamic dropdown configuration menu above the data table to filter rows instantly by **"Critical Stockouts Only"** to identify immediate material shortages.

### Step 4: Execute Automated Procurement
Click the **"Export Master Report (.CSV)"** button. Farafy will instantly compile all calculated optimization benchmarks (EOQ, Safety Stock, ROP) into a clean procurement template file ready to be dispatched directly to your supplier network or purchasing division.

---

## 🛠️ Technological Architecture Stack
* **Frontend Markup:** HTML5 Structural Schema
* **Style Engine:** Tailwind CSS (Custom Dark-Mode & Industrial Yellow Palette)
* **Visual Graphics Platform:** Chart.js Engine (Dynamic Canvas Data Re-rendering)
* **Data Parsing Protocol:** JavaScript FileReader Core Object Integration
* **Hosting Pipeline:** Vercel Global Static Server Mesh Architecture
