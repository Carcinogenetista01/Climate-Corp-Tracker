# 🌱 Climate-Corp-Tracker
**Analyzing Corporate Environmental Accountability & Climate Action**  

![Badge](https://img.shields.io/badge/License-MIT-blue) 
![Badge](https://img.shields.io/badge/Version-1.0.0-green)  

## 📖 Overview  
This repository leverages open climate and corporate data to evaluate the environmental performance of global companies. It combines datasets on greenhouse gas emissions, energy usage, and sustainability pledges to create interactive dashboards and actionable insights.  

## 🔍 Key Features  
- **Corporate Emission Tracking**: Integrate data from **Climate TRACE** and **EPA eGRID** to map emissions by industry and region :cite[2]:cite[4].  
- **Sustainability Scorecards**: Compare corporate climate commitments (e.g., net-zero pledges) against actual performance using **CDP reports** :cite[4].  
- **Interactive Visualizations**: Generate heatmaps, trend graphs, and sector comparisons with **Plotly** and **Python**.  
- **Greenwashing Detection**: Identify discrepancies between self-reported data and third-party audits :cite[2].  

## 📂 Dataset Sources  
1. **Climate TRACE**  
   - **Focus**: High-resolution emissions data for 80,000+ global facilities.  
   - **URL**: [https://climatetrace.org](https://climatetrace.org)  
   - **Example**: Monthly CO2 emissions from manufacturing sectors (2015–2025) :cite[4].  

2. **EPA eGRID**  
   - **Focus**: U.S. power plant emissions and energy generation data.  
   - **URL**: [https://www.epa.gov/egrid](https://www.epa.gov/egrid)  
   - **Example**: Annual GHG emissions by utility provider (1996–2022) :cite[2].  

3. **CDP (Carbon Disclosure Project)**  
   - **Focus**: Corporate sustainability reports from 18,000+ companies.  
   - **URL**: [https://cdp.net](https://cdp.net)  
   - **Example**: Climate risk disclosures and reduction strategies :cite[4].  

4. **World Bank Climate Change Data**  
   - **Focus**: National GHG inventories and energy use metrics.  
   - **URL**: [https://climateknowledgeportal.worldbank.org](https://climateknowledgeportal.worldbank.org)  
   - **Example**: Country-level emissions vs. GDP trends :cite[4]:cite[7].  

5. **NOAA Climate.gov**  
   - **Focus**: Historical climate trends and future projections.  
   - **URL**: [https://www.climate.gov/maps-data](https://www.climate.gov/maps-data)  
   - **Example**: Sea-level rise impact on coastal industries :cite[5].  

## 🛠️ Installation  
```bash
git clone https://github.com/yourusername/ClimateCorpInsights.git  
cd ClimateCorpInsights  
pip install -r requirements.txt  # Includes pandas, plotly, requests  
