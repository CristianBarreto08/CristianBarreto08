## Hi, I'm Cristian

### Operations Automation Specialist · E-commerce & Supply Chain

I build the systems that let operations run without someone grinding through spreadsheets all day.

For the past 7 years I've worked inside real operations: trucking logistics, freight finance, and supply chain for a US e-commerce brand selling primarily on Amazon (800+ SKUs). In each one I ended up doing the same thing. I find the manual, error-prone process that eats the team's time and replace it with something automated, verified and documented.

- **Demand planning on autopilot.** I turned a sales-for-ordering report that took a full workday into a **~20-minute** run that downloads its own ERP exports and checks them.
- **Import purchasing without the line-by-line checks.** Packing plans, vendor instructions, three-way invoice matching and container receiving are all automated and self-verifying.
- **I understand what I automate.** I've negotiated with factories in China and Vietnam, tracked containers through customs, processed freight payables and dispatched a 13-truck fleet.

[LinkedIn](https://www.linkedin.com/in/cristianbarreto13) · [Portfolio](https://cristianbarreto08.github.io) · cristianbarreto294@gmail.com

---

### Operations automation suite

Six production tools I built for an Amazon brand's import supply chain, rewritten as clean, tested, open-source versions with synthetic data. Together they cover the whole cycle from *what to order* to *what arrived*.

| Step | Project | What it automates |
|---|---|---|
| 1. Plan | **[inventory-reorder-engine](https://github.com/CristianBarreto08/inventory-reorder-engine)** | ERP sales + inventory exports become a seasonality- and trend-adjusted reorder report with stock-out priority. A full day of work now takes **~20 min**. |
| 2. Order | **[po-packing-plan-builder](https://github.com/CristianBarreto08/po-packing-plan-builder)** | An approved PO becomes per-vendor factory packing plans. It runs a multi-step ERP export cascade, de-duplicates by channel and writes live Excel formulas. **~12 min, mostly unattended.** |
| 3. Instruct | **[vendor-packing-instructions](https://github.com/CristianBarreto08/vendor-packing-instructions)** | Builds the packing, labeling and invoicing workbook the factory works from, then double-checks it against the ERP purchase order. |
| 4. Pay | **[three-way-match-reconciliation](https://github.com/CristianBarreto08/three-way-match-reconciliation)** | Matches the ERP PO against the vendor invoice and packing list before paying. Writes an executive Word report with the dollar impact next to every issue. |
| 5. Validate | **[packing-spec-validator](https://github.com/CristianBarreto08/packing-spec-validator)** | Checks case quantity and carton dimensions SKU by SKU against what the ERP says and what the vendor was told. |
| 6. Receive | **[container-receiving-automation](https://github.com/CristianBarreto08/container-receiving-automation)** | Turns a packing list into the ERP container upload, the PO allocation and the warehouse unpacking list, verified against the vendor's own totals. |

Every repo ships with a seeded sample-data generator, a one-command demo, pytest tests and CI.

---

### Interactive tools

**[Amazon Demand Planning Dashboard](https://github.com/CristianBarreto08/amazon-demand-planning-dashboard)** ([live demo](https://cristianbarreto08.github.io/amazon-demand-planning-dashboard/))
Demand forecast, reorder points, safety stock and coverage risk across a multipack Amazon catalog.

[![Dashboard preview](https://raw.githubusercontent.com/CristianBarreto08/amazon-demand-planning-dashboard/main/assets/dashboard-preview.png)](https://cristianbarreto08.github.io/amazon-demand-planning-dashboard/)

**[Landed Cost & FBA Margin Calculator](https://github.com/CristianBarreto08/landed-cost-calculator)** ([live demo](https://cristianbarreto08.github.io/landed-cost-calculator/))
What a unit really costs once it's sitting in Amazon. It allocates freight by shipping mode (including air chargeable weight), then adds duty, tariffs and Amazon fees to reach net margin and break-even price.

[![Calculator preview](https://raw.githubusercontent.com/CristianBarreto08/landed-cost-calculator/main/assets/calculator-preview.png)](https://cristianbarreto08.github.io/landed-cost-calculator/)

---

### Toolbox

**Automation:** Python · Playwright (browser automation) · Excel VBA & macros · Power Query · n8n · AI-assisted workflows
**Data:** SQL · pandas · openpyxl · Excel modeling · dashboards
**Operations:** demand forecasting · reorder points & safety stock · PO management · three-way match · landed cost · freight & container logistics
**Platforms:** Amazon Seller Central (FBA) · SellerCloud · Shopify
**Engineering habits:** tests (pytest) · CI (GitHub Actions) · SOPs and documentation for every process I automate

---

### Earlier work

Data science projects from my 800-hour bootcamp at Henry:

- **[MLOps API: Recommendation System](https://github.com/CristianBarreto08/Steam-Game-Recommender-MLOps-Project)**: a deployed game-recommendation API with item-item and user-item models
- **[Roadway Safety Analysis, Buenos Aires](https://github.com/CristianBarreto08/Buenos-Aires-Road-Safety-Data-Analysis)**: ETL, dashboards and predictive analysis over accident data
- **[Yelp & Google Maps Reviews](https://github.com/Joaqrz/Proyecto_Final_Yelp)**: a recommendation system on GCP with scikit-learn, Airflow, Streamlit and Power BI

---

Bogotá, Colombia · Bilingual English/Spanish (EF SET C2) · Open to on-site, hybrid, remote and relocation
