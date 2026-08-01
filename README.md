# 🌍 Tourism Dataset — Data Analysis Project

Exploratory data analysis and visualization of a global tourism dataset (41,923 records) covering visitor counts, revenue, ratings, categories, and accommodation availability across multiple countries.

## 📊 Dataset Overview

| Column | Description |
|---|---|
| `Location` | Name/ID of the tourist location |
| `Country` | Country where the location is situated |
| `Category` | Type of attraction (Nature, Historical, Cultural, etc.) |
| `Visitors` | Number of visitors |
| `Rating` | Average visitor rating |
| `Revenue` | Revenue generated |
| `Accommodation_Available` | Whether accommodation is available (Yes/No) |

**Rows:** 41,923 | **Columns:** 7

---

## 📈 Visualizations

### 1. 2D Density Plot — Visitors vs Revenue
![2D Density Plot](01_2d_density.png)

### 2. Average Revenue by Category
![Revenue by Category](02_revenue_by_category.png)

### 3. Cumulative Revenue by Category
![Cumulative Revenue](03_cumulative_revenue.png)

### 4. Category Distribution
![Category Distribution](04_category_distribution.png)

### 5. Top 10 Locations by Revenue
![Top 10 Locations by Revenue](05_top10_locations_revenue.png)

### 6. Visitors vs Revenue (Bubble Chart)
![Visitors vs Revenue Bubble Chart](06_visitors_revenue_bubble.png)

### 7. Accommodation Availability by Category
![Accommodation by Category](07_accommodation_by_category.png)

### 8. Visitors vs Revenue — Faceted by Category
![Visitors vs Revenue Faceted](08_visitors_revenue_faceted.png)

### 9. Revenue Trend
![Revenue Trend](09_revenue_trend.png)

### 10. Top 10 Countries by Visitors
![Top 10 Countries by Visitors](10_top10_countries_visitors.png)

### 11. Revenue Distribution — Violin + Box Plot
![Revenue Violin Box Plot](11_revenue_violin_box.png)

### 12. Visitors Distribution
![Visitors Distribution](12_visitors_distribution.png)

---

## 🛠️ Tools Used

- **R** — `ggplot2`, `dplyr`, `treemapify`, `ggridges`
- **Google Colab** (R runtime via `rpy2`)

## 📁 Project Structure



## 🚀 How to Reproduce

1. Clone this repository
2. Open `tourism_dataset.csv` in Google Colab (R runtime, or Python + `rpy2`)
3. Install required packages:
   ```r
   install.packages(c("ggplot2", "dplyr", "treemapify", "ggridges"))
   ```
4. Run the analysis scripts to regenerate the charts

---

⭐ If you found this analysis useful, consider giving the repo a star!
