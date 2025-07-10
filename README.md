# District-wise Evapotranspiration and Precipitation Analysis in Sri Lanka (May 2024 – May 2025)
This project provides a comprehensive analysis of district-level evapotranspiration (ET) and precipitation across Sri Lanka using MODIS and CHIRPS satellite datasets via Google Earth Engine (GEE). The objective is to assess water availability and balance by visualizing ET, rainfall, and their ratio (ET/P) using choropleth maps, bar charts, and scatter plots.

## 📌 Objectives
- Estimate annual mean evapotranspiration (May 2024 – May 2025) using MODIS MOD16A2 product.
- Calculate district-wise precipitation for the same period using CHIRPS.
- Visualize spatial patterns using interactive choropleth maps.
- Compare ET and precipitation values per district via:
- Dual-axis bar chart
- Scatter plot with labels
- ET-to-Precipitation ratio bar chart

## 🛰️ Data Sources
1. Dataset	Description	Source
2. MODIS MOD16A2	8-day Evapotranspiration (ET)	MODIS GEE
3. CHIRPS	Precipitation (monthly)	CHIRPS GEE
4. GAUL Level 2	District boundaries for Sri Lanka	FAO GAUL

## 🛠️ Tools & Libraries
-Google Earth Engine (GEE)
-Python 3.10+ (run in Google Colab)

Packages: geemap, geopandas, matplotlib, adjustText, numpy, pandas

## 📊 Visualizations
1. Interactive Map: Mean Annual ET (mm)
Displays mean evapotranspiration across Sri Lanka using MODIS data.
<img width="1920" height="1080" alt="Screenshot (227)" src="https://github.com/user-attachments/assets/f50a8251-b179-46c5-b210-8f01244fc314" />

2. Choropleth Map: District-wise ET
<img width="1920" height="1080" alt="Screenshot (228)" src="https://github.com/user-attachments/assets/fec02b2b-2dc4-4522-9a31-88ec67b35531" />

3. Bar Chart: ET vs Precipitation per District
<img width="1763" height="787" alt="Screenshot (229)" src="https://github.com/user-attachments/assets/ea6490b0-07a5-46eb-a367-9ab7d9c53bc2" />

4. Scatter Plot: ET vs Precipitation
<img width="994" height="992" alt="Screenshot (230)" src="https://github.com/user-attachments/assets/0f38bc0f-15bf-41e6-8a44-e09a11f54cb6" />

5. Bar Chart: ET-to-Precipitation Ratio
<img width="1762" height="630" alt="Screenshot (231)" src="https://github.com/user-attachments/assets/6051f07d-0e20-4872-90e8-a20f1f82ac17" />


## 📈 Key Insights (2024–2025)
- ET values range from ~20–33 mm annually per district.
- Precipitation ranges from ~1500–4000 mm.
- ET/P ratio is very low (~0.006–0.02), indicating high rainfall relative to ET — useful for irrigation and water resource planning.

## 💡 Applications
- Agricultural water management
- Drought vulnerability mapping
- District-level irrigation planning
- Climate impact monitoring

