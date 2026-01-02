# Supply Chain Intelligence: End-to-End Analysis from Sourcing to Delivery
This project delivers a comprehensive end-to-end supply chain analytics solution covering procurement, inventory, logistics, and fulfillment. The goal was to provide data-driven insights for procurement and logistics decision-makers, enabling operational efficiency, cost optimization, and improved delivery performance.

## Why this project matters: 
Demonstrates the ability to handle real-world supply chain data, create relational models, and produce actionable insights for strategic decision-making.

## Data Scope: Tables & Business Use
Table	Purpose / Use
- **PurchaseOrders**	Track purchase headers (supplier, date, total). Measure spend, lead times, PO status.
- **PurchaseOrderLines**	Line items per PO (material, quantity, unit cost). Fact table for spend and quantities.
- **Supplier master.** Used for segmentation and spend analysis.
- **Raw-material master.** SKU-level and category reporting.
- **Inventory.** Track stock levels and days of inventory.
- **StockMovement.** Analyze turnover and traceability.
- **Warehouse	master.** Slice inventory or throughput.
- **Shipment.** Measure transit and carrier performance.
- **Carrier master.** Compare carrier performance.
- **SalesOrder	Customer orders.** Measure fulfillment and demand.
- **Fulfillment**	Links sales orders to shipments and status. Track shipped vs pending.
- **Supplier Performance**	Precomputed KPIs. Benchmark supplier performance.

## Tools & Methodology
- **Excel:** Analysis, pivot tables, KPI calculations, and visualization
- **Power Query:** Data cleaning and transformation
- **DAX (Advanced Excel):** Data modeling and calculations
-**Visualization:** KPI cards, conditional formatting, charts for actionable insights

All datasets were cleaned, transformed, and integrated into a relational model supporting dashboards and KPIs.

## Key KPIs & Insights
- **Supplier Performance:** On-time delivery, lead times, quality scores
- **Procurement Spend:** Total spend by supplier/category, trends
- **Inventory Management:** Stock levels, turnover, days of inventory
- **Logistics & Fulfillment:** Delivery time, fulfillment cycle, perfect order rate, carrier performance

## Outcomes
-Full end-to-end supply chain visibility
-Identified cost-saving opportunities and operational bottlenecks
-Optimized supplier selection and inventory strategies
-Delivered remote-ready, actionable dashboards

## 📌 How to Use
1. **Download the Excel file** from this repository (`End To End Procurement & Supply Chain Excel...`).
2. **Open the file in Excel** and enable content if prompted (macros, formulas, or Power Query).
3. **Navigate through the dashboards** using slicers and filters to explore spend, supplier performance, and inventory metrics.
4. **Review KPIs and visualizations** to identify cost-saving opportunities, supplier risks, and inventory inefficiencies.
5. Use the insights to support **strategic decisions** in procurement, logistics, and fulfillment.


