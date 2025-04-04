# 🌍 Global BSL Labs & Climate Risks  
*Mapping the distribution of high-containment laboratories and projected climate-related hazards*

## 🔍 Overview  
This project visualizes the global distribution of **Biosafety Level 3+ (BSL3+)** and **BSL4** laboratories alongside IPCC-projected climate risks (e.g., floods, cyclones, sea-level rise). It answers:  
*Where are high-containment labs located, and how might climate change impact their operational risks?*  

## 📊 Key Outputs  
1. **Static Maps**:  
   - 7 thematic maps (e.g., river floods, tropical cyclones) showing labs overlaid on IPCC risk regions.  
   - *Example:*  
     ![Heavy Precipitation Risk](figures/bslmap_heavyprecipitation.png)  

2. **Interactive Map**:  
   - Explore labs and toggle climate risks [here](outputs/map.html).  

3. **Lab Counts by Region**:  
   - Summary table of labs per IPCC region ([labcounts.csv](data/processed/labcounts.csv)).  

## 🛠️ How It Works  
- **Data**: IPCC reference regions (shapefile) + lab locations (CSV).  
- **Tools**: `R` (tidyverse, sf, leaflet), RMarkdown.  
