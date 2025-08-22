# GLOBAL RENEWBALE ENERGY(GRE) ANALYSIS

### INTRODUCTION
This project analyzes global renewable energy production and adoption across 212 countries, based on data from the "Renewable_Energy_Production.xlsx" dataset. 
The dataset includes total renewable energy production (TWh) and percentages for five energy types: hydroelectric, wind, solar, biomass, and geothermal. 
The analysis aims to identify leaders in renewable energy production and adoption, highlighting trends and opportunities for global renewable energy expansion.

### OBJECTIVE
The objective is to:
1. Identify the highest and lowest producers for each renewable energy type (non-zero values).
2. Highlight countries with the highest and lowest renewable energy percentages.
3. Summarize global renewable energy trends, including the prevalence of each energy type.
4. Provide insights for policymakers, researchers, and enthusiasts to understand renewable energy landscapes.

### METHODOLOGY

Data Source: The dataset (Renewable_Energy_Production.xlsx) contains 212 countries with columns for total renewable energy (Renew_twh, Renew_percent) and specific energy types (Hydro_twh, Wind_twh, Solar_twh, Bio_twh, Geo_twh, and their percentages) which is being scraped with selennium. The website is: https://en.wikipedia.org/wiki/List_of_countries_by_renewable_electricity_production
Tools: Analysis was conducted using Python (pandas for data processing) and Tableau Public (web version) for visualizations.
Steps:
1. Scraped the webpage with selenium with scraper.ipynb and preprocessed the dataset with preprocessing.ipynb.
2. Calculated highest and lowest production (TWh) and percentage values for each energy type.
3. Determined the number of countries utilizing each energy type.
4. Visualized key metrics using choropleth maps and bar charts in Tableau to highlight global patterns.
5. Summarized findings, focusing on top performers, laggards, and global averages.

### KEY FINDINGS

1. Total Renewable Energy:
  i. Highest Production: China (2,894 TWh)
  ii. Lowest Production: Turkmenistan (0.01 TWh)
  iii. Highest Percentage: Paraguay (100%)
  iv. Lowest Percentage: Turkmenistan (0.03%)

2. Hydroelectric Energy:
  i. Highest Production: China (1,226 TWh)
  ii. Lowest Production: Turkmenistan (0.01 TWh)
  iii. Highest Percentage: Bhutan (100%)
  iv. Lowest Percentage: Algeria (0.02%)

3. Wind Energy:
  i. Highest Production: China (886 TWh)
  ii. Lowest Production: Saint Kitts and Nevis (0.01 TWh)
  iii. Highest Percentage: Denmark (58%)
  iv. Lowest Percentage: Algeria (0.02%)

4. Solar Energy:
  i. Highest Production: China (584 TWh)
  ii. Lowest Production: Trinidad and Tobago (0.01 TWh)
  iii. Highest Percentage: Cook Islands (50%)
  iv. Lowest Percentage: Venezuela (0.01%)

5. Biomass:
  i. Highest Production: China (198 TWh)
  ii. Lowest Production: Bermuda (0.01 TWh)
  iii. Highest Percentage: Macau (41%)
  iv. Lowest Percentage: Iran (0.01%)

6. Geothermal Energy:
  i. Highest Production: United States (18 TWh)
  ii. Lowest Production: Martinique (0.01 TWh)
  iii. Highest Percentage: Kenya (47%)
  iv. Lowest Percentage: Norway (0.01%)


### INSIGHTS
1. 10 countries achieve 100% renewable energy, led by Paraguay (44 TWh).
2. China dominates absolute production across all renewable sources except geothermal.
3. 20 countries have 90%+ renewable energy share.
4. Global average renewable percentage is 36.8%.
5. Solar is the most widespread (171 countries), while geothermal is the rarest (26 countries).

<div>
  <img src="https://i.postimg.cc/jd6qz8B4/Screenshot-From-2025-08-23-00-18-50.png">
  <img src="https://i.postimg.cc/5tLs0CXy/Screenshot-From-2025-08-23-00-22-13.png">
</div>
