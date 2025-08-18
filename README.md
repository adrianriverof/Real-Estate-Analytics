# Real Estate Analytics: Tourist Rentals in Madrid & Valencia

## Overview
This project explores the short-term rental market (Airbnb) in Madrid and Valencia, aiming to uncover **profitable investment opportunities** and understand the key drivers of rental income.  
The analysis combines Airbnb listing data with external pricing information to estimate the **earnings potential of properties**, based on acquisition cost, occupancy ratios, and guest capacity.

---

## Process
1. **Data collection**  
   - Airbnb listings datasets for Madrid and Valencia (CSV).  
   - External pricing data scraped from real estate websites.  

2. **Data preparation**  
   - Cleaning, handling missing values, manual adjustments for district differences.  
   - Integration of multiple sources into a **SQLite database** (accessed with SQLAlchemy).  

3. **Analysis**  
   - Calculation of potential ROI for each apartment.  
   - Segmentation by district, property type, and guest capacity.  
   - Visualization of spatial patterns using **folium** maps.  

---

## Key Insights
- **10 neighborhoods** maximize cost-income ratio, segmented by type and quality.  
- Optimal property type: **1-bedroom apartments for 3 guests**.  
- Proximity to points of interest showed **low relevance** to ROI.  
- Strong **market opportunity** around major sporting events in specific districts.  

<p align="center">
  <img width="600" height="400" src="https://github.com/user-attachments/assets/0c9801df-364e-4ffb-bce7-909a766ff745">
</p>

---

## Challenges
- **Data scraping**: some data had to be scraped manually with a Chrome extension.  
- **Non-uniform districts**: Valencia’s district structure required additional manual adjustments.  
- **Data quality**: missing values handled through imputation.  

---

## Tech Stack
<img align="right" width="400" height="400" src="https://github.com/user-attachments/assets/235a738c-5872-4890-8885-ee23869c8471">

- **Python**: pandas, numpy, matplotlib, seaborn
- **Database**: SQLite + SQLAlchemy  
- **Visualization**: folium (maps), matplotlib/seaborn (plots)  
- **Other**: creation of a subcube for fast querying during analysis  

---

### [Results notebook](https://github.com/adrianriverof/Real-State-Market-Analysis-for-Tourist-Rentals/blob/main/Madrid/6-%20Results.ipynb)




