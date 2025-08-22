# Global Renewable Energy (GRE) Analysis

### Introduction
This project analyzes global renewable energy production and adoption across 212 countries, based on data from the "Renewable_Energy_Production.xlsx" dataset. 
The dataset includes total renewable energy production (TWh) and percentages for five energy types: hydroelectric, wind, solar, biomass, and geothermal. 
The analysis aims to identify leaders in renewable energy production and adoption, highlighting trends and opportunities for global renewable energy expansion.

### Objective
The objective is to:
1. Identify the highest and lowest producers for each renewable energy type (non-zero values).
2. Highlight countries with the highest and lowest renewable energy percentages.
3. Summarize global renewable energy trends, including the prevalence of each energy type.
4. Provide insights for policymakers, researchers, and enthusiasts to understand renewable energy landscapes.

### Methodology

Data Source: The dataset (Renewable_Energy_Production.xlsx) contains 212 countries with columns for total renewable energy (Renew_twh, Renew_percent) and specific energy types (Hydro_twh, Wind_twh, Solar_twh, Bio_twh, Geo_twh, and their percentages).
Tools: Analysis was conducted using Python (pandas for data processing) and Tableau Public (web version) for visualizations.
Steps:
1. Loaded and cleaned the dataset, ensuring non-zero values for accurate rankings.
2. Calculated highest and lowest production (TWh) and percentage values for each energy type.
3. Determined the number of countries utilizing each energy type.
4. Visualized key metrics using choropleth maps and bar charts in Tableau to highlight global patterns.
5. Summarized findings, focusing on top performers, laggards, and global averages.



Key Findings

Total Renewable Energy:
Highest Production: China (2,894 TWh)
Lowest Production: Turkmenistan (0.01 TWh)
Highest Percentage: Paraguay (100%)
Lowest Percentage: Turkmenistan (0.03%)
Adoption: 197 countries use renewables.


Hydroelectric Energy:
Highest Production: China (1,226 TWh)
Lowest Production: Turkmenistan (0.01 TWh)
Highest Percentage: Bhutan (100%)
Lowest Percentage: Algeria (0.02%)
Adoption: 154 countries.


Wind Energy:
Highest Production: China (886 TWh)
Lowest Production: Saint Kitts and Nevis (0.01 TWh)
Highest Percentage: Denmark (58%)
Lowest Percentage: Algeria (0.02%)
Adoption: 109 countries.


Solar Energy:
Highest Production: China (584 TWh)
Lowest Production: Trinidad and Tobago (0.01 TWh)
Highest Percentage: Cook Islands (50%)
Lowest Percentage: Venezuela (0.01%)
Adoption: 171 countries.


Bioenergy:
Highest Production: China (198 TWh)
Lowest Production: Bermuda (0.01 TWh)
Highest Percentage: Macau (41%)
Lowest Percentage: Iran (0.01%)
Adoption: 123 countries.


Geothermal Energy:
Highest Production: United States (18 TWh)
Lowest Production: Martinique (0.01 TWh)
Highest Percentage: Kenya (47%)
Lowest Percentage: Norway (0.01%)
Adoption: 26 countries.


Highlights:
10 countries achieve 100% renewable energy, led by Paraguay (44 TWh).
China dominates absolute production across all renewable sources except geothermal.
20 countries have 90%+ renewable energy share.
Global average renewable percentage is 36.8%.
Solar is the most widespread (171 countries), while geothermal is the rarest (26 countries).


