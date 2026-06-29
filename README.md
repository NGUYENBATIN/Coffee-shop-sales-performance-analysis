# ☕ Coffee Shop Sales Performance Dashboard (Excel Project)

An interactive data analytics project that transforms raw transactional data into an executive-level business intelligence dashboard using **Microsoft Excel**. This project tracks performance metrics, revenue trajectories, and consumer purchasing behavior for a multi-location coffee shop chain.

*Inspired by the Data Tutorials financial analytics framework.*

---

## 📂 Project Structure & Dataset Overview

The project utilizes a comprehensive, large-scale transactional dataset containing **149,116 rows** of retail customer orders spanning from January to June 2023:
*   `Coffee Shop Sales Performance Dashboard Project.xlsx`: The core workbook containing:
    *   `Transactions` Sheet: Raw transactional data (149,116 records) with calculated fields like `Revenue`, `Month Name`, `WeekDay Name`, and `Hour`.
    *   `DASHBOARD` Sheet: The interactive analytical interface featuring dynamic charts, KPI cards, and slicers.

---

## 📊 Core Analytics & Features Included

The dashboard delivers insights across four major retail dimensions:
1. **Sales Performance over Time:** Tracked monthly revenue growth trends and identified top-performing operational periods.
2. **Temporal & Peak Hour Analysis:** Analyzed sales distribution by hours (`Hour`) and weekdays (`WeekDay Name`) to pinpoint morning rushes and optimize staffing schedules.
3. **Product Portfolio Matrix:** Evaluated `product_category` (Coffee, Tea, Bakery, etc.) and specific `product_type` performance based on volume and total sales to manage inventory.
4. **Location Intelligence:** Segmented sales dynamics across distinct locations (`store_location` like Lower Manhattan, Astoria, and Hell's Kitchen) to uncover regional preferences.

---

## 🛠️ Excel Skills & Features Demonstrated

*   **Data Engineering:** Formulated custom attributes using Excel formulas (extracting hours, calculating row-level revenue via `transaction_qty * unit_price`).
*   **Data Aggregation:** Designed robust Pivot Tables to handle large-scale calculations smoothly.
*   **UI/UX Dashboard Design:** Built a clean, non-gridline dashboard utilizing a cohesive coffee-themed color palette, custom shape-based KPI cards, and fully linked interactive Slicers for dynamic filtering.

---
## Dashboard overview
<img src="Coffee shop Sales dashboard.png" width="100%">

## 🎯 Actionable Business Recommendations

Based on the data insights generated from the dashboard, the following strategic recommendations are proposed to optimize operations and drive revenue:

### 1. 🕒 Staff Scheduling & Resource Optimization (Peak Hours)
* **Insight:** The data shows consistent demand spikes during morning hours (**7:00 AM – 10:00 AM**), accounting for the highest transaction counts.
* **Action:** Increase frontline staffing and pre-batch high-demand items (like brewed coffees and popular bakeries) during these hours to minimize customer wait times, improve table turnover, and capture maximum morning revenue.

### 2. ☕ Product Portfolio & Cross-Selling (Top Products)
* **Insight:** **Coffee** and **Tea** categories (specifically *Brewed Chai Tea*, *Gourmet Brewed Coffee*, and *Barista Espresso*) are the primary revenue drivers. 
* **Action:** Implement strategic cross-selling techniques by bundling these top-selling beverages with lower-volume, high-margin items (e.g., Bakery or Merchandising) at a slight discount to increase the Average Order Value (AOV).

### 3. 🗺️ Location-Based Inventory Management
* **Insight:** Sales dynamics and product preferences vary across individual foot-prints (Lower Manhattan, Astoria, Hell's Kitchen).
* **Action:** Customize localized stock inventories. For example, allocate higher volumes of premium or quick-serve grab-and-go products to high-traffic commuter zones like Lower Manhattan during weekdays, while optimizing seating layout and slower-brewed options for residential areas like Astoria.

### 4. 📉 Low-Demand Period Promotions (Happy Hour)
* **Insight:** Transaction volume experiences a noticeable dip during late afternoons and specific weekdays (e.g., Sundays).
* **Action:** Launch targeted "Happy Hour" loyalty promotions or limited-time bundles between **3:00 PM – 5:00 PM** to stimulate demand, utilize idle labor, and smoothen the daily revenue curve.

---

## 🚀 How to Explore the Project

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/NGUYENBATIN/YOUR_REPO_NAME.git](https://github.com/NGUYENBATIN/YOUR_REPO_NAME.git)

2. **Download Dataset:**
   Download dataset and use dashboard file: Coffee Shop Sales Perfomance Dashboard Project.xlsx
   
