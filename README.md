# 🇸🇬 Singapore Income Inequality Analysis  
### Programming with Data – Coursework Project

This repository contains a full data-analysis project exploring **income inequality in Singapore**, using official datasets from **SingStat**. The project includes data cleaning, ethical considerations, exploratory analysis, geospatial mapping, and statistical visualizations.

The research aims to uncover socioeconomic disparities across Singapore’s planning areas, highlight trends in the Gini coefficient, and examine the distribution of income groups across different neighbourhoods.

---

## 📌 Project Objectives

- Investigate income inequality in Singapore using publicly available government data.  
- Visualize socioeconomic differences across residential planning areas.  
- Analyse Gini coefficient trends (2000–2022).  
- Explore wage gaps between the top 10% and bottom 10% of earners.  
- Understand how government transfers and taxes reduce inequality.  
- Create choropleth maps to show the geographic distribution of income ranges.

---

## 📊 Data Sources

All datasets were obtained from **Singapore Department of Statistics (SingStat)**:

🔗 https://tablebuilder.singstat.gov.sg/

Datasets include:

- Gini Coefficient (2000–2022)  
- Household Income by Planning Area  
- Age by Resident Area  
- Government Transfers  
- Dwelling Type by Residence  
- Resident Population  
- Income Comparison (1st vs 10th Decile)

These datasets were processed ethically following the terms of use provided by SingStat.

---

## 🧰 Tools & Libraries

The project is built entirely in Python using Jupyter Notebook, leveraging:

- **Pandas** – Data cleaning and manipulation  
- **NumPy**  
- **GeoPandas** – Geospatial analysis & mapping  
- **Folium** – Interactive choropleth maps  
- **Matplotlib / Seaborn** – Statistical visualization  
- **Plotly** – Interactive charts  

Install requirements:

```bash
pip install geopandas folium matplotlib mapclassify seaborn plotly pandas numpy
