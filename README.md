### 1. Project Title
* Title: Blinkit Grocery Sales & Outlet Performance Analytics Dashboard
* Repository Name: blinkit-grocery-sales-tableau-dashboard

### 2. Short Description
* An end-to-end interactive business intelligence dashboard developed in Tableau analyzing grocery sales, item assortments, and outlet operations for Blinkit.
* Uncovers patterns across product categories, fat content profiles, store formats, outlet age, and tier-based geographic locations using dynamic parameter switching.

### 3. Purpose
* Evaluate Revenue Drivers: Track overall sales, average order value, item volumes, and customer ratings across diverse grocery categories.
* Assess Outlet Performance: Compare store tiers (Tier 1, Tier 2, Tier 3), store sizes (Small, Medium, High), and retail formats (Grocery Store vs. Supermarket Types) to identify high-margin locations.
* Analyze Inventory & Product Characteristics: Examine customer preferences between Low Fat vs. Regular fat items and determine optimal category assortments.
* Implement Advanced Tableau Architecture: Build a production-ready dashboard featuring custom dual-axis donut charts, reversed-scale funnel charts, dynamic calculated metric parameters, and a dedicated floating filter panel.

### 4. Tech Stack
* Business Intelligence & Visualization: Tableau Desktop / Tableau Public
* Data Modeling & Calculations: Tableau Calculated Fields, CASE Statements, Parameters, Dual-Axis Visualizations
* Data Storage / Source: Microsoft Excel (.xlsx) / CSV

### 5. Example Walkthrough
* Use Case: Analyzing sales and inventory performance across geographic tiers.
* Action: Select "Tier 3" in the Outlet Location Type filter and switch the dynamic metric parameter to "Total Sales".
* Observed Insight: Tier 3 locations generate substantial sales volume, driven predominantly by Medium-sized Supermarket outlets, while Low Fat products account for the majority share of food items sold.
* Conclusion: Directs expansion and inventory replenishment toward larger-footprint supermarket formats in non-metro growth corridors.

### 6. Data Source
* Dataset: Blinkit Grocery Store Dataset
* Format: .xlsx / .csv
* Key Attributes:
  * Item Fat Content: Categorization of nutritional fat profile (Low Fat, Regular)
  * Item Identifier: Unique SKU / product code
  * Item Type: Product category (Fruits and Vegetables, Snack Foods, Dairy, Baking Goods, etc.)
  * Item Visibility: Relative shelf display allocation ratio
  * Item Weight: Physical product weight
  * Sales: Gross revenue generated per item transaction
  * Rating: Customer feedback score
  * Outlet Establishment Year: Year the outlet launched operations
  * Outlet Identifier: Unique store identification number
  * Outlet Location Type: City tier classification (Tier 1, Tier 2, Tier 3)
  * Outlet Size: Physical floor capacity classification (Small, Medium, High)
  * Outlet Type: Store retail model (Grocery Store, Supermarket Type 1, Type 2, Type 3)

### 7. Features & Highlights
* Core KPI Cards: Summary metric cards reporting Total Sales ($1M+), Average Sales ($141), Total Items Sold (8,523), and Average Customer Rating (3.97).
* Dynamic Metric Parameter Engine: Custom parameter allowing users to dynamically switch chart measures between Total Sales, Average Sales, Number of Items, and Average Rating via CASE calculated fields.
* Dual-Axis Donut Charts: Custom dual-axis implementation illustrating sales breakdown by Item Fat Content and Outlet Size.
* Custom Funnel Chart: Innovative reversed-axis dual-bar technique illustrating revenue distribution across Tier 1, Tier 2, and Tier 3 store locations.
* Outlet Establishment Growth Trend: Dual-axis area and line chart depicting sales trajectory by outlet establishment year.
* Item Type Performance Matrix: Ranked horizontal bar chart detailing best-performing product categories.
* Store Format Breakdown Table: Heatmap matrix comparing Grocery Stores against Supermarket variants across sales, ratings, item visibility, and SKU volumes.
* Branded Dashboard UI: Blinkit brand-themed styling (Yellow, Green, and Dark contrasts) with a collapsible-style floating filter panel.

### 8. Business Impact & Insights
* Supermarket Formats Outperform Small Groceries: Supermarket Type 1 formats account for the lion's share of revenue, outperforming small standalone grocery stores in item turnover and average transaction size.
* High Demand for Health-Conscious SKUs: Low Fat items constitute roughly two-thirds of the item volume, demonstrating a consumer preference that supports expanding healthy and organic SKU lines.
* Tier 3 Market Expansion Opportunity: Tier 3 locations demonstrate strong aggregate sales potential, indicating quick-commerce demand extends well beyond primary metropolitan centers.
* Strategic Recommendations:
  * Prioritize opening Medium and Supermarket Type 1 formats in expanding tier cities rather than high-overhead large footprints.
  * Adjust dark-store shelf visibility to feature high-rating, high-margin categories (such as Fruits, Vegetables, and Snack Foods) on the app homepage to lift average order value.
 
* * ### 9.	Screenshots / Demos
Show what the dashboard looks like.
Example: ![Dashboard Preview](https://github.com/pchaitali0013/blinkit-grocery-sales-tableau-dashboard/blob/main/blinkit.jpeg)
