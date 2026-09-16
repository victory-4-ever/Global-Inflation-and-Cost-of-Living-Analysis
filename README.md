# Global-Inflation-and-Cost-of-Living-Analysis
## 🌍 Global Inflation and Cost of Living Analysis

"Excel" (https://img.shields.io/badge/Microsoft%20Excel-Data%20Analysis-green)
"Power BI" (https://img.shields.io/badge/Power%20BI-Dashboard-yellow)
"Data Analytics" (https://img.shields.io/badge/Data%20Analytics-Portfolio-blue)

## 📌 Introduction

The Global Inflation and Cost of Living Analysis project explores inflation rates and cost-of-living patterns across countries and regions.

The objective is to identify significant trends, compare economic conditions across selected countries, and examine the relationship between inflation and cost of living using Microsoft Excel and Power BI.

The project demonstrates an end-to-end data analytics workflow, including data cleaning, exploratory analysis, statistical analysis, visualization, dashboard development, and insight generation.

---

## 🎯 Project Objectives

The analysis aims to:

- Analyze global inflation trends across countries and over time.
- Examine variations in cost of living across countries.
- Identify countries with the highest and lowest inflation rates.
- Identify countries with the greatest increases in cost of living.
- Compare inflation and cost of living across regions.
- Compare Nigeria, Kenya, South Africa, the United States, and the United Kingdom.
- Measure the relationship between inflation rate and cost of living.
- Develop an interactive Power BI dashboard.
- Generate actionable insights and recommendations from the data.

---

### ❓ Business Questions

The project answers the following questions:

1. What are the global inflation trends?
2. Which countries have the highest and lowest inflation rates?
3. Which countries have experienced the greatest increase in cost of living?
4. How does inflation vary across regions?
5. How does cost of living vary across countries?
6. What is the relationship between inflation and cost of living?
7. How does Nigeria compare with selected international economies?
8. How much of the variation in cost of living can be explained by inflation?

---

## 🗃️ Dataset

Dataset: Global Inflation and Cost of Living Dataset

Source: Kaggle — "edudev-commons-org"

The dataset contains country-level economic indicators used to analyze inflation and cost-of-living patterns.

# Key Variables

Variable| Description
Country| Name of the country
Country Code| Country identification code
Region| Geographical region
Inflation Rate| Inflation rate for the relevant observation
Cost of Living| Cost-of-living measure
Inflation Year| Year of the inflation observation

---

## 🧹 Data Cleaning & Preparation

The dataset was prepared before analysis using the following steps:

- Reviewed the dataset for duplicate records.
- Checked for missing values.
- Verified data types.
- Validated country and country-code information.
- Used country-code information to support data validation.
- Checked inflation and cost-of-living fields for numerical consistency.
- Prepared the data for statistical analysis and visualization.
- Ensured inflation and cost-of-living observations were properly matched before correlation analysis.

---

## 🛠️ Tools & Technologies

Microsoft Excel

Used for:

- Data cleaning
- Data validation
- PivotTables
- Descriptive analysis
- Correlation analysis
- Regression analysis
- Charts and visualizations
- Slicers
- Exploratory data analysis

Microsoft Power BI

Used for:

- Data transformation
- Data modeling
- Interactive dashboards
- KPI cards
- Bar charts
- Scatter plots
- Regional analysis
- Country comparisons
- Interactive filtering and slicers

---

## 🔎 Analytical Process

The project followed an end-to-end data analytics process:

Data Collection
       ↓
Data Cleaning
       ↓
Data Validation
       ↓
Exploratory Data Analysis
       ↓
Statistical Analysis
       ↓
Data Visualization
       ↓
Power BI Dashboard
       ↓
Insights & Recommendations

---

## 📊 Exploratory Data Analysis

The analysis focused on:

- Inflation distribution across countries.
- Cost-of-living differences.
- Inflation trends over time.
- Regional averages.
- Highest and lowest inflation rates.
- Countries with the greatest cost-of-living increases.
- Comparative analysis of selected countries.

---

## 📈 Correlation Analysis

Pearson correlation was used to examine the relationship between Inflation Rate and Cost of Living.

### Result

## Correlation coefficient:

"r = -0.321"

This indicates a weak-to-moderate negative linear relationship between the two variables in the analyzed observations.

The result suggests that higher inflation rates were not necessarily associated with higher values of the cost-of-living measure in this particular dataset.

«Important: Correlation does not imply causation.»

---

## 📉 Regression Analysis

A simple linear regression was performed to determine whether inflation rate could explain variation in cost of living.

Regression Equation

Cost of Living = 8.227 − 0.0833 × Inflation Rate

### Key Results

Metric| Result
R²| 0.0101
Inflation Rate Coefficient| -0.0833
Inflation Rate p-value| 0.1406
Significance F| 0.1406

The R² of approximately 1.01% indicates that inflation rate explains only a small proportion of the variation in the cost-of-living variable in this dataset.

The inflation-rate coefficient is also not statistically significant at the 5% level, based on the regression results.

### Interpretation

Inflation rate alone is therefore not a strong predictor of cost of living in the analyzed observations.

Other factors may have a greater influence, including:

- Exchange rates
- Housing costs
- Food prices
- Energy prices
- Income levels
- Transportation costs
- Interest rates
- Government policies
- Import dependency
- Supply-chain conditions

---

## 🌍 Country Comparison

A focused comparison was performed for:

Country| Purpose
🇳🇬 Nigeria| Primary country of comparison
🇰🇪 Kenya| Regional comparison
🇿🇦 South Africa| Regional comparison
🇺🇸 United States| Developed economy comparison
🇬🇧 United Kingdom| Developed economy comparison

This comparison provides additional context for understanding differences in inflation and cost-of-living conditions across economies.

---

## 📊 Power BI Dashboard

The Power BI dashboard provides an interactive view of the analysis.

Dashboard Components

# KPI Cards

- Average Inflation Rate
- Average Cost of Living
- Number of Countries
- Selected-year metrics

# Charts

- Inflation trends
- Top countries by inflation
- Top 10 countries by cost-of-living increase
- Regional comparisons
- Inflation vs. Cost of Living scatter plot

# Interactive Filters

- Country
- Region
- Year

The dashboard enables users to filter the analysis and explore specific countries, regions, and periods.

---

## 💡 Key Insights

1. Inflation varies significantly across countries

The analysis shows substantial differences in inflation rates between countries, indicating varying levels of inflationary pressure.

2. Cost of living differs considerably

Countries exhibit different cost-of-living levels, reflecting differences in economic structure, prices, income, and consumption patterns.

3. Inflation does not fully explain cost of living

The correlation and regression analyses indicate that inflation rate alone has limited explanatory power for the cost-of-living measure in this dataset.

4. Country-specific factors matter

Economic conditions differ across countries, meaning that country-specific variables should be considered when evaluating cost-of-living pressures.

---

## 💡 Recommendations

Based on the findings, the following recommendations are proposed:

1. Use multiple economic indicators when assessing cost-of-living pressures rather than relying solely on inflation.

2. Include income and purchasing-power data to determine how inflation affects household affordability.

3. Monitor exchange rates, especially in economies with significant import dependence.

4. Analyze housing, food, energy, and transportation costs separately to identify the major contributors to cost-of-living increases.

5. Expand the time period of the dataset to support stronger long-term trend analysis.

6. Include additional socioeconomic variables such as GDP per capita, unemployment, wages, interest rates, and household expenditure.

7. Use interactive BI dashboards to support continuous monitoring and decision-making.

---

## ⚠️ Limitations

The analysis has several limitations:

- Inflation rate alone does not capture all components of cost of living.
- Country-level data may hide differences between cities and households.
- The regression model has low explanatory power.
- Correlation does not establish causation.
- Additional economic variables would improve the predictive capability of the analysis.
- The dataset's coverage and methodology may affect the comparability of countries.

---

## 📁 Repository Structure

Global-Inflation-and-Cost-of-Living-Analysis/
│
├── README.md
│
├── data/
│   └── global_inflation_cost_of_living.xlsx
│
├── excel/
│   └── Global_Inflation_Cost_of_Living_Analysis.xlsx
│
├── powerbi/
│   └── Global_Inflation_Cost_of_Living_Dashboard.pbix
│
├── visuals/
│   ├── inflation_trend.png
│   ├── cost_of_living_comparison.png
│   ├── correlation_analysis.png
│   └── powerbi_dashboard.png
│
└── documentation/
    └── analysis_report.md

---

## 🧠 Skills Demonstrated

This project demonstrates practical skills in:

- Data Cleaning
- Data Validation
- Exploratory Data Analysis
- Statistical Analysis
- Correlation Analysis
- Regression Analysis
- Data Visualization
- Microsoft Excel
- Microsoft Power BI
- Dashboard Development
- Data Storytelling
- Business Intelligence
- Insight Generation
- Analytical Reporting

---

## 🚀 Future Improvements

Future versions of the project could include:

- GDP per capita analysis.
- Purchasing Power Parity (PPP).
- Unemployment rates.
- Wage and income growth.
- Food inflation.
- Housing costs.
- Energy prices.
- Exchange-rate analysis.
- Time-series forecasting.
- Machine-learning models for cost-of-living prediction.

---

## 🏁 Conclusion

The Global Inflation and Cost of Living Analysis demonstrates how data analytics can be used to investigate economic conditions across countries and regions.

The analysis shows that while inflation is an important economic indicator, inflation rate alone has limited explanatory power for the variation in cost of living within the analyzed dataset.

A broader analytical model incorporating income, exchange rates, housing, food, energy, employment, and other socioeconomic variables would provide a more comprehensive understanding of global cost-of-living pressures.

This project demonstrates an end-to-end approach to data analytics, from data preparation and statistical analysis to visualization, dashboard development, insight generation, and recommendations.

---

## 👤 Author

Adekoya Olabisi

Data Analyst | Accounting & Finance Professional | Business Intelligence

This project is part of my data analytics portfolio and demonstrates the application of Excel, Power BI, statistical analysis, and data storytelling to real-world economic data.

---

## ⭐ Project Highlights

Tools: Microsoft Excel | Power BI
Analysis: EDA | Correlation | Regression | Comparative Analysis
Focus: Inflation | Cost of Living | Global Economic Trends
Output: Interactive Dashboard | Statistical Analysis | Business Insights
