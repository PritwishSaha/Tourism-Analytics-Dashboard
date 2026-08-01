🌍 Tourism Data Analysis & Visualization

📊 Project Overview

This project analyzes tourism data using R and ggplot2 toexplore visitor numbers, revenue, ratings, tourism categories,countries, and accommodation availability.

The project focuses on Exploratory Data Analysis (EDA) and visualstorytelling through multiple ggplot2 visualizations.

🎯 Objectives

Analyze tourism visitors across countries and locations

Explore revenue distribution across tourism categories

Identify top locations by revenue

Analyze the relationship between visitors and revenue

Study tourism category distribution

Analyze accommodation availability

Explore visitor and revenue distributions

Identify countries with the highest total visitors

🛠️ Technologies Used

R

RStudio

ggplot2

dplyr

tidyr

readr

Exploratory Data Analysis (EDA)

📁 Dataset

The dataset contains tourism-related information for different locationsand countries.

Dataset Columns

Column                      Description

Location                  Tourism locationCountry                   Country of the locationCategory                  Tourism categoryVisitors                  Number of visitorsRating                    Tourism location ratingRevenue                   Revenue generatedAccommodation_Available   Whether accommodation is available

🔄 Project Workflow

Tourism Dataset
      ↓
Data Loading
      ↓
Data Cleaning & Preparation
      ↓
Exploratory Data Analysis
      ↓
ggplot2 Visualization
      ↓
Pattern & Relationship Analysis
      ↓
Tourism Insights

📈 Visualizations

1. 2D Density --- Visitors vs Revenue

Shows the concentration of observations based on visitor numbers andrevenue.

<p align="center">

<img src="images/01_2d_density.png" alt="2D Density - Visitors vs Revenue" width="800">{=html}

</p>

2. Revenue Distribution by Category

Shows revenue distribution across different tourism categories.

<p align="center">

<img src="images/02_revenue_by_category.png" alt="Revenue Distribution by Category" width="800">{=html}

</p>

3. Cumulative Revenue by Category

Shows cumulative revenue across tourism categories.

<p align="center">

<img src="images/03_cumulative_revenue.png" alt="Cumulative Revenue by Category" width="800">{=html}

</p>

4. Category Distribution

Shows the distribution of tourism locations across different categories.

<p align="center">

<img src="images/04_category_distribution.png" alt="Category Distribution" width="800">{=html}

</p>

5. Top 10 Locations by Revenue

Highlights the top 10 tourism locations based on revenue.

<p align="center">

<img src="images/05_top10_locations_revenue.png" alt="Top 10 Locations by Revenue" width="800">{=html}

</p>

6. Visitors vs Revenue --- Bubble Chart

Shows the relationship between visitors and revenue, with bubble sizerepresenting rating.

<p align="center">

<img src="images/06_visitors_revenue_bubble.png" alt="Visitors vs Revenue Bubble Chart" width="800">{=html}

</p>

7. Accommodation Availability by Category

Compares accommodation availability across tourism categories.

<p align="center">

<img src="images/07_accommodation_by_category.png" alt="Accommodation Availability by Category" width="800">{=html}

</p>

8. Visitors vs Revenue --- Faceted by Category

Compares the visitors-revenue relationship separately across tourismcategories.

<p align="center">

<img src="images/08_visitors_revenue_faceted.png" alt="Visitors vs Revenue Faceted by Category" width="800">{=html}

</p>

9. Revenue Trend

Visualizes the overall revenue pattern with a fitted trend line.

Note: If the dataset does not contain a time/date variable, thisshould be interpreted as an observation-order trend rather than atime-series trend.

<p align="center">

<img src="images/09_revenue_trend.png" alt="Revenue Trend" width="800">{=html}

</p>

10. Top 10 Countries by Total Visitors

Shows the countries with the highest total number of visitors.

<p align="center">

<img src="images/10_top10_countries_visitors.png" alt="Top 10 Countries by Total Visitors" width="800">{=html}

</p>

11. Revenue Distribution --- Violin + Box Plot

Shows revenue distribution, spread, central tendency, and potentialoutliers across tourism categories.

<p align="center">

<img src="images/11_revenue_violin_box.png" alt="Revenue Distribution Violin and Box Plot" width="800">{=html}

</p>

12. Distribution of Visitors

Shows the distribution of visitor numbers across the dataset.

<p align="center">

<img src="images/12_visitors_distribution.png" alt="Distribution of Visitors" width="800">{=html}

</p>

🔍 Analysis Areas

👥 Visitors Analysis

Visitor distribution

Top countries by visitors

Visitors vs revenue relationship

Visitor patterns across categories

💰 Revenue Analysis

Revenue by category

Top locations by revenue

Cumulative revenue

Revenue distribution and outliers

Visitors vs revenue relationship

⭐ Rating Analysis

Tourism location ratings

Rating represented through bubble size

🏨 Accommodation Analysis

Accommodation availability

Accommodation availability by category

🌍 Country Analysis

Country-level visitor comparison

Top countries by total visitors

🚀 How to Run

1. Clone the repository

git clone https://github.com/yourusername/Tourism-Data-Analysis.git

2. Open the project in RStudio

Open:

tourism_analysis.R

3. Install required packages

install.packages(c(
  "ggplot2",
  "dplyr",
  "tidyr",
  "readr"
))

4. Load packages

library(ggplot2)
library(dplyr)
library(tidyr)
library(readr)

5. Load the dataset

tourism_data <- read_csv("tourism_dataset.csv")

6. Run the analysis

Run the R script to perform the analysis and generate thevisualizations.

📌 Key Skills Demonstrated

R Programming

Data Cleaning

Data Manipulation

Exploratory Data Analysis

Data Visualization

Statistical Distribution Analysis

Categorical Analysis

Relationship Analysis

ggplot2

Data Storytelling

🔮 Future Improvements

Build an interactive Shiny dashboard

Add statistical hypothesis testing

Perform correlation analysis

Add predictive tourism revenue modeling

Build a Machine Learning model for tourism revenue prediction

Add interactive filters and dashboards

👨‍💻 Author

Pritwish Saha

Engineering Student | Data Analytics & Machine Learning Enthusiast

