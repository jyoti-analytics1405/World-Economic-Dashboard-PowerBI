# 🌍 World Economic Dashboard — Power BI

An interactive Power BI dashboard analyzing global economic and development indicators — GDP, life expectancy, unemployment, internet usage, infant mortality, and HDI — across 200+ countries.

## 📊 Overview

This project explores a global development indicators dataset to answer questions like:
- How has global GDP grown over time, and what does year-over-year growth look like?
- How does GDP vary by region and by country?
- What's the relationship between economic indicators (GDP, unemployment) and social indicators (life expectancy, infant mortality, HDI)?

The dashboard is built as a 3-page interactive report with drillthrough navigation, letting a user go from a global summary down to a single country's detailed profile in one click.

## 🗂️ Pages

**1. Front Page**
Landing/title page for the report.

**2. Overview**
High-level KPI summary of the dataset:
- KPI cards: Avg GDP per Capita, Average Life Expectancy, Avg Unemployment %, Total Countries
- World map visual (GDP per capita by country)
- Death rate trend over time (1960–2020)
- Gauge visuals: Unemployment %, Internet Users %, Infant Mortality Rate, HDI Score
- Clustered column chart: Internet Users % by Country

**3. Trend & Insights**
Deeper analytical view:
- Combo chart: Total GDP (columns) + YoY GDP Growth % (line), 1960–2020
- Donut chart: Total GDP share by Region
- Bar chart: GDP by Region and Country
- Detail table (Birth rate / Death rate by country) with a **Show/Hide Details** toggle button
- **Country-level Drillthrough**: right-click any country on the Overview page → "Drillthrough" → lands here filtered to that single country

## ⚙️ Key Power BI Features Used

- **Data modeling**: relationships across the development indicators data, region hierarchy (Region → Country)
- **DAX measures**: aggregated KPIs (GDP, life expectancy, unemployment), Total GDP and YoY GDP Growth %
- **Page Navigator**: custom navigation buttons across all 3 pages with active-page highlighting
- **Drillthrough**: country-level drillthrough filter with a dedicated Back button
- **Bookmarks + Buttons**: Show/Hide toggle for the detail table on the Trend & Insights page
- **Custom theming**: dark navy dashboard theme applied consistently across all visuals and pages

## 🛠️ Tools Used

- Power BI Desktop (data modeling, DAX, report design)
- Dataset: global development/economic indicators (GDP, life expectancy, unemployment, internet usage, infant mortality, HDI, by country and year)

## 📸 Screenshots

*(![Overview Page](Screenshot%202026-09-27%20180004.png)
![Trend & Insights Page](Screenshot%202026-09-27%20180029.png)
![Drillthrough Example](Screenshot%202026-09-27%20180052.png))*

## 🔗 Related Projects

- [Online Retail RFM Segmentation](https://github.com/jyoti-analytics1405/Online-Retail-RFM-Segmentation)
- [Swiggy Restaurant Analysis](https://github.com/jyoti-analytics1405/Swiggy-Restaurant-Analysis)
