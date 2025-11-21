# Global BSL labs and climate risks
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Mapping the distribution of high-containment laboratories and projected climate-related hazards

## Overview  
Visualize the global distribution of **Biosafety Level 3+ (BSL3+)** and **BSL4** laboratories alongside IPCC-projected climate risks (e.g., floods, cyclones, sea-level rise). *Where are high-containment labs located, and how might climate change impact their operational risks?*  

## Key outputs  
1. **Static maps**:  
   - Seven maps (e.g., river floods, tropical cyclones) showing labs overlaid on IPCC risk regions.  
   - Example:
     ![Heavy Precipitation Risk](figures/bslmap_heavyprecipitation.png)  

2. **Interactive map**:  
   - Explore labs and toggle climate risks [here](https://jcoa05.github.io/bsl-climate-risk/).  

## How it works  
- **Data**: IPCC-projected climate risks + lab locations, all compiled from publicly-available information
- **Tools**: `R` (sf, leaflet), RMarkdown 

Contribute
Found an error or want to expand? Open an issue or PR.

This project was developed in collaboration with Ketan Thorat (BRIC-inStem, India) and Tanya Sarawagi (IISc, India).
