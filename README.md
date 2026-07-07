# Blinkit Retail Sales Performance Analysis

## 🎯 Project Overview & Objectives

The core objective of this project is to conduct a comprehensive data analysis of Blinkit's sales performance, customer satisfaction, and warehouse inventory distribution. By aligning clear Key Performance Indicators (KPIs) with data visualizations, this project isolates growth opportunities, tracks consumer health preferences, and optimizes local supply chain structures.

### 📊 Core KPI Goals

* **Total Revenue Assessment:** Summing total platform sales across all dark stores to monitor baseline business growth.
* **Average Transaction Evaluation:** Calculating the average revenue generated per sale to understand consumer basket sizes and spending behavior.
* **Inventory & Volume Tracking:** Measuring the absolute count and variety of distinct items sold to analyze warehouse stock movement and velocity.
* **Customer Satisfaction Mapping:** Aggregating and tracking product ratings to ensure strict quality control and gauge consumer service sentiment.

---

## 🛠️ Tools Used & Tech Stack

* **Programming Language:** Python 3 (For core data manipulation, custom data grouping, and engineering workflows).
* **Development Environment:** Google Colab  (For interactive development and execution).
* **Data Manipulation Library:** `Pandas` (Used for reading the dataset, handling schema column adjustments, and performing structured matrix aggregations).
* **Mathematical Operations:** `NumPy` (Used for managing numerical arrays and internal mathematical tracking).
* **Data Visualization Libraries:** `Matplotlib.pyplot` & `Seaborn` (Used to construct production-ready charts, plot time-series lines, and style categorical distribution layouts).

---

## 📊 Strategic Business Insights & Analysis

### 1. Fat Content Impact Analysis (Consumer Behavior)

* **Objective:** To analyze how the fat content classification of products impacts total revenue distribution and examine baseline metrics.
* **Data-Driven Insight:** Products categorized as **Low Fat capture a dominant 64.6%** of total platform sales, while Regular fat items make up the remaining 35.4%.
* **Operational Strategy:** Health-conscious or standard dietary items drive the vast majority of consumer volume. Dark stores should maintain a structural inventory storage ratio favoring low-fat options to prevent stockouts of high-demand core variants.

![Total Sales by Fat content](filename.png)
<p align="center">
  <img src="fat_content.png" width="400" alt="Total Sales by Fat Content">
</p>
### 2. Product Performance Identification (Revenue Drivers)

* **Objective:** To identify the performance of different item types in terms of total sales and their associated volume variations.
* **Data-Driven Insight:** Fresh produce and quick snacks act as the primary financial engines for the platform. **Fruits and Vegetables lead total revenue at 178,124**, closely followed by **Snack Foods at 175,434** and Household items at 135,977. Niche specialty lines like Seafood sit at the bottom, contributing minimal platform value.
* **Operational Strategy:** The top three product categories constitute the massive bulk of platform transactions. These specific high-velocity item zones must be physically positioned closest to order-picking and dispatch tables inside dark stores to minimize fulfillment time and satisfy strict 10-to-15 minute delivery Service Level Agreements (SLAs).
![Total Sales by Item Type](item_type.png)
<p align="center">
  <img src="item_type.png" width="750" alt="Total Sales by Item Type">
</p>
### 3. Outlet Segmentation Analysis (Localized Product Mix)

* **Objective:** To compare total sales across individual outlet location types, segmented specifically by product fat content.
* **Data-Driven Insight:** The heavy consumer preference for Low Fat items remains uniform across all geographic market tiers. Total volume climbs progressively from Tier 1 up to Tier 3, with Tier 3 registering the highest overall sales numbers for both regular and low-fat classifications.
* **Operational Strategy:** The strong baseline performance in Tier 2 and Tier 3 markets indicates that instant delivery adoption is no longer exclusive to major Tier 1 metros. Regional supply chain distribution centers can scale up operations confidently in secondary markets without altering the localized core product mix ratio.
![Outlet Tier by Item Fat Content](outlet_tier.png)
<p align="center">
  <img src="outlet_tier.png" width="600" alt="Outlet Tier by Item Fat Content">
</p>
### 4. Establishment Age Evaluation (Growth Maturity)

* **Objective:** To evaluate how the operational lifespan or establishment age of an outlet influences its revenue stability and growth.
* **Data-Driven Insight:** Outlets established in the earliest recorded year hit a historical peak of **204,522 in sales**. Revenue has leveled out to a highly uniform, predictable baseline of roughly ~130,000 across subsequent launch cohorts, with the exception of a sharp localized dip down to 78,132 around the year 2011.
* **Operational Strategy:** The older dark stores demonstrate the immense value of long-term customer maturity and retention. The distinct dip around 2011 serves as an ideal case study to audit internal warehouse changes or regional supply disruptions that occurred during that specific operational period.
  
![Total Sales by Outlet Establishment](establishment_year.png)
<p align="center">
  <img src="establishment_year.png" width="650" alt="Total Sales by Outlet Establishment">
</p>
### 5. Outlet Size Correlation (Space Optimization)

* **Objective:** To analyze the structural correlation between the physical footprint of a warehouse store and the total revenue it is capable of generating.
* **Data-Driven Insight:** **Medium-sized stores generate the largest slice of sales at 42.3%**, followed closely by Small stores at 37.0%. Massive "High" scale warehouses contribute the least, generating only 20.7%.
* **Business Strategy:** Small and Medium micro-warehouses together command **79.3% of platform sales**. This proves that an agile, decentralized network of smaller fulfillment centers located directly inside dense residential clusters is far more effective at driving instant delivery revenue than investing capital into massive, distant centralized hubs.
  
![Sales Share by Outlet Size](outlet_size.png)
  <p align="center">
  <img src="outlet_size.png" width="400" alt="Sales Share by Outlet Size">
</p>

### 6. Geographic Distribution Assessment (Regional Market Trends)

* **Objective:** To map the geographic distribution of revenue across location tiers to spot clear regional expansion trends.
* **Data-Driven Insight:** The horizontal revenue distribution confirms that **Tier 3 locations generate the highest gross sales**, Tier 2 holds the middle rank, and Tier 1 contributes the least overall platform revenue.
* **Business Strategy:** Corporate growth, marketing budgets, and future dark-store real estate investments should be heavily prioritized toward Tier 3 and Tier 2 urban extensions where real transaction velocity is actively outpacing traditional Tier 1 dense city centers.

![Outlet Location Type](location_type.png)
<p align="center">
  <img src="location_type.png" width="600" alt="Total Sales by Outlet Location Type">
</p>
---

## 📈 Executive Conclusion

The Blinkit business model functions at its highest profitability when scaled horizontally through **Tier 3 and Tier 2 geographic expansions** utilizing **Small to Medium micro-warehouses**. Operational layout configurations should emphasize rapid accessibility to daily high-velocity essentials (Fruits, Vegetables, and Snack Foods) while biasing fulfillment stock heavily toward Low-Fat alternatives to systematically match consumer purchase velocities.
