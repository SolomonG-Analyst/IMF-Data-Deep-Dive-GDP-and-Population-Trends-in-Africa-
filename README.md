# IMF Data Deep Dive: GDP and Population Trends in Africa

This project investigates GDP and population trends in African countries from 2015 to 2025 using data from the International Monetary Fund (IMF). The main motivation came after observing that Ethiopia became the second-largest economy in East Africa in 2025, which was partly due to the devaluation of the local currency. This analysis includes data preparation, trend analysis, and visualizations to better understand the relationship (or lack thereof) between GDP and population in the region.

## 📊 Project Description

- Collected and analyzed GDP and population data for African countries (2015–2025) from the IMF database.
- Cleaned and transformed the data using Python (pandas).
- Conducted exploratory and descriptive analysis.
- Explored GDP per capita, growth rates, and identified top-performing countries.
- Visualized key trends using libraries such as matplotlib and seaborn.
- Make Dashboard using power BI.

## 🔍 Key Insights

- Ethiopia became the second-largest economy in East Africa by 2025, largely driven by nominal changes in GDP due to currency devaluation.
- There is 0.837 spearmans correlation was found between population growth and GDP growth. I didn't use Pearson correlation b/c the data is right skewed!
- GDP per capita provided more realistic economic comparison among countries than total GDP alone.
- See the below power BI dashboards
  ![Dashboard1](https://github.com/user-attachments/assets/033e5fe2-1b2d-49ac-a025-7476e39585d1)

![Dashboard3](https://github.com/user-attachments/assets/f8872681-570a-4bc0-8b8b-247a69e0255d)

## 🛠 Technologies Used

- **Python** – Data cleaning, transformation, and analysis
- **Pandas** – Data manipulation
- **Matplotlib & Seaborn** – Data visualization
- **Jupyter Notebook** – For analysis and experimentation
-  **Power BI** – Dashboard creation
  
## Limitation
- Most Data for years after 2023 are projections/estimates by the IMF
- Eritrea is excluded from this analysis, as IMF data is not available for the country beyond 2020.

