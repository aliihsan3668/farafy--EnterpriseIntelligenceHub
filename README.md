# Farafy — Enterprise Demand Forecasting & Strategic Procurement Analytics Suite

Live Applications:
* 📈 Demand Forecasting Hub: [https://vercel.app](https://farafy.vercel.app/)
* 🛡️ Strategic Procurement Auditor: [https://vercel.app](https://farafy-supplier-risk.vercel.app)
* 🛳️ Customs Pre-Clearance Audit Engine: https://farafy-port.vercel.app/#

SaaS Category: Enterprise Business Intelligence (BI) / Risk Management & Predictive Operations
Design System: Premium Midnight Gold Palette (#030712 / #fbbf24)
Core Architecture: 100% Serverless Client-Side Processing Architecture

---

## 🏢 Executive Suite Overview
Farafy is an advanced supply chain diagnostic portfolio designed to address margin compression, operational vulnerabilities, and capital inefficiencies across global supply networks. Engineered using pure client-side JavaScript, Tailwind CSS, and Chart.js, the suite processes raw enterprise transaction logs locally inside the user's browser. This guarantees banking-grade data privacy, as sensitive corporate vendor pricing, metrics, and contracts never cross an external web server.

The portfolio is split into two specialized, high-yield operational modules:
1. **Demand Forecasting Hub:** Audits retail inventory capital traps and stabilizes multi-SKU warehousing levels.
2. **Strategic Procurement & Supplier Risk Auditor:** Models vendor concentration risks, monitors supplier performance leaks, and simulates cost deflection margins.

---

## ⚡ Core Value Provisions & Mathematical Frameworks

### 🟢 Module 1: Demand Forecasting Hub
Designed to optimize working capital cycles by determining exact replenishment schedules and identifying slow-moving inventory liabilities.

* **Economic Order Quantity (EOQ):** Pinpoints the optimal batch size where ordering costs and inventory carrying costs reach a mathematical equilibrium.
  $$EOQ = \sqrt{\frac{2 \times D \times S}{H}}$$
  *(D = Annual Unit Demand, S = Ordering Cost, H = Unit Holding Cost)*
* **Safety Stock Buffer:** Establishes an algorithmically calculated cushion protecting against daily demand volatility and lead-time delays.
  $$SS = Z \times \sqrt{L} \times \sigma$$
  *(Z = Service Level Coefficient, L = Supplier Lead Time, \sigma = Demand Standard Deviation)*
* **Continuous Reorder Point (ROP):** Automated trigger warnings signaling exactly when a replacement order must be executed.
  $$ROP = \left( \frac{D}{365} \times L \right) + SS$$

### 🟡 Module 2: Strategic Procurement & Supplier Risk Auditor
Designed to mitigate single-source asset monopolies and uncover hidden spend deflection margins within vendor supply lines.

* **Herfindahl-Hirschman Index (HHI) Concentration Analysis:** Evaluates market share dominance within corporate procurement networks. An HHI value exceeding 2,500 automatically triggers critical risk warning banners.
  $$HHI = \sum_{i=1}^{n} (MS_i)^2$$
  *(MS = Percentage Share of Annual Spend allocated to Vendor i)*
* **Geopolitical Vulnerability Index:** Computes a weighted risk metric mapping an embedded country stability registry (ranging 1.0 to 5.0) directly against raw supplier location variables.
* **Spend Deflection Simulation:** Models the redistribution of capital away from underperforming high-cost single sources toward highly efficient, optimized market alternatives.

---

## 📋 Comprehensive Operating Manual & Schema Mapping

### File 1: Warehousing Template (`farafy_b2b_template.csv`)
To utilize the Demand Forecasting Hub, structure your inventory log matching these 7 explicit metrics columns:
`SKU, AnnualDemand, CurrentStock, OrderingCost, HoldingCost, LeadTimeDays, DailyVolatilityVariance`

### File 2: Procurement Template (`farafy_procurement_template.csv`)
To run the Supplier Risk Auditor, export your purchasing ledger conforming to these 6 enterprise metrics columns:
`VendorName, MaterialCategory, AnnualSpendPKR, LeadTimeVarianceDays, QualityScore, SupplierLocation`

### Ingestion & Processing Instructions:
1. Navigate to the targeted Vercel production domain.
2. Click **"Download Template"** to fetch a pre-formatted framework file.
3. Align your enterprise data columns with the template schema and click **"Load CSV File"**.
4. Adjust sliders or dropdown configuration controls to play out real-time "what-if" strategic risk and margin simulation curves.
5. Click **"Export Master Report"** to instantly generate a print-ready spreadsheet manifest to deploy directly to your purchasing managers or global supplier network.

---

## 🛠️ Technology Stack & Performance Metrics
* **UI/UX Vector Graphics Engine:** Chart.js (Real-time dynamic canvas layout re-rendering)
* **Asynchronous Data Parser:** HTML5 Native FileReader API Object Integration
* **Style Utility Framework:** Tailwind CSS (Custom High-Contrast Cyberpunk Dark-Mode Matrix)
* **Deployment Automation:** Vercel Global Static Edge Mesh Network
