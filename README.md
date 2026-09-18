# nyc-airbnb-data-analysis
End-to-end NYC Airbnb data analysis using Excel for data cleaning and Power BI for interactive analysis and visualization.
NYC Airbnb Data Analysis
# NYC Airbnb Data Analysis

## 📌 Project Overview

This project presents an end-to-end analysis of the **New York City Airbnb Open Dataset**.

The project started with an Excel dataset containing information about Airbnb listings, hosts, neighbourhoods, room types, prices, reviews, and availability.

The raw data was first cleaned and prepared in **Microsoft Excel**. The cleaned dataset was then imported into **Power BI** to perform analysis, create visualizations, and build an interactive dashboard.

The main objective was to identify meaningful patterns in Airbnb listings and answer key business questions related to properties, hosts, neighbourhoods, pricing, room types, reviews, and availability.

---

## 🎯 Problem Statement

The objective of this project is to analyze Airbnb listing data and identify patterns across different neighbourhood groups, hosts, room types, prices, reviews, and property availability.

The analysis was performed to answer key business questions and derive meaningful insights that could help understand the Airbnb market in New York City.

---

## 📂 Dataset

The project uses the **New York City Airbnb Open Dataset**.

The dataset contains approximately **48,895 listings and 16 columns** covering information about:

* Listing ID
* Property name
* Host ID
* Host name
* Neighbourhood group
* Neighbourhood
* Latitude and longitude
* Room type
* Price
* Minimum nights
* Number of reviews
* Last review date
* Reviews per month
* Host listing count
* Availability

**Dataset Source:** Kaggle – New York City Airbnb Open Dataset

---

## 🧹 Data Cleaning

The original dataset was provided in Excel and was cleaned before being used for analysis in Power BI.

The data preparation process included reviewing the dataset, identifying missing values, checking the data structure, and preparing the data for analysis and visualization.

The cleaned dataset was then imported into Power BI for further analysis.

---

## 🛠️ Tools & Technologies

* **Microsoft Excel** – Data cleaning and preparation
* **Power BI** – Data analysis and visualization
* **Power Query** – Data transformation and preparation
* **DAX** – Measures and calculations
* **Power BI Slicers** – Interactive filtering
* **Charts and Visualizations** – Presenting analytical findings

---

## 🔍 Business Questions

The analysis answers the following questions:

1. In which neighbourhood group are the maximum number of properties listed?
2. Which host has the maximum number of properties listed?
3. Which host has the maximum number of properties listed in the neighbourhood group having the maximum number of properties?
4. What is the average price of different properties?
5. What may be the reason for higher prices in certain neighbourhood groups?
6. What is the most preferred room type in each neighbourhood group?
7. What is the total availability of properties by room type?
8. Which host is the busiest?
9. Which property has the maximum number of reviews?

---

## 📊 Analysis Performed

The Power BI analysis includes:

* Property count by neighbourhood group
* Host-wise property listings
* Price analysis by neighbourhood group
* Room-type distribution
* Room-type preference across neighbourhood groups
* Property availability by room type
* Review analysis
* Reviews per month
* Last review information
* Host activity analysis
* Most-reviewed properties
* Interactive filtering using slicers

---

# 📷 Dashboard Preview

## Overall Dashboard

---

## 🏙️ Neighbourhood Analysis

This analysis explores the distribution of Airbnb properties and pricing patterns across different neighbourhood groups.

---

## 🛏️ Room Type Analysis

This analysis compares the different room types available across neighbourhood groups and examines their availability and distribution.

---

## 💰 Price Analysis

This analysis explores differences in Airbnb prices across neighbourhood groups and other relevant categories.

---

## ⭐ Review Analysis

This analysis examines review activity, including review counts, reviews per month, and highly reviewed properties.

---

## 💡 Key Insights

The analysis helped identify patterns in Airbnb listings, hosts, neighbourhoods, room types, prices, reviews, and availability.

### Key findings from the analysis:

* **Neighbourhood group with the highest number of listings:** [MANHATTAN]
* **Host with the highest number of listings:** Sonder(NYC)
* **Most preferred room type:** Entire home/apt.
* **Neighbourhood group with the highest average price:** Brooklyn
* **Property with the highest number of reviews:** Room near JFK Queen Bed

---

## 💼 Business Value

The analysis provides insights into Airbnb property distribution, pricing patterns, room-type preferences, host activity, reviews, and property availability across New York City.

These insights can help in understanding accommodation preferences and identifying patterns in the Airbnb market across different neighbourhood groups.

---

## 📁 Repository Structure

```text
nyc-airbnb-data-analysis/
│
├── data/
│   ├── raw/
│   │   └── AB_NYC_2019.xlsx
│   │
│   └── cleaned/
│       └── Airbnb_Cleaned.xlsx
│
├── powerbi/
│   └── NYC_Airbnb_Analysis.pbix
│
├── images/
│   ├── dashboard.png
│   ├── neighbourhood-analysis.png
│   ├── room-type-analysis.png
│   ├── price-analysis.png
│   └── review-analysis.png
│
└── README.md
```

---

## 👨‍💻 Author

**Harshveer**

Aspiring Data Analyst

**Skills:** Excel | Power BI | SQL | Python | Tableau
