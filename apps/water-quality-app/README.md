# 🧪 Reservoir Monitoring & Water Quality Analysis App
[<- Back to Apps Catalog](../README.md)

## 1. Overview
The **Reservoir Monitoring & Vegetation Analysis App** is a professional-grade, lightweight tool built on **Google Earth Engine (GEE)**. It is designed for researchers, students, and environmental managers to conduct rapid, interactive analysis of inland water bodies and surrounding vegetation.

By leveraging the **Sentinel-2 MSI** constellation, the app provides a dual-track analysis:
1. **Physical Hydrology:** Water masking, surface area quantification, and temporal variation.
2. **Bio-Optical Monitoring:** Retrieval of key Water Quality Parameters (WQPs) including Chlorophyll-a, Turbidity, CDOM, and TSM.

---

## 📸 Application Preview

<img width="1024" height="1024" alt="Generated Image January 07, 2026 - 11_35AM" src="https://github.com/user-attachments/assets/daba812d-3010-4836-a98f-8c92f19da7b5" />
<img width="371" height="558" alt="4" src="https://github.com/user-attachments/assets/b5b8639b-7b9d-4b81-b9c5-1961222a0dfa" />
<img width="1474" height="855" alt="3" src="https://github.com/user-attachments/assets/28d5aa09-9a62-4274-b604-7b7055b2e016" />
<img width="363" height="604" alt="2" src="https://github.com/user-attachments/assets/031b8094-fd3d-4700-83cd-005f00d7962d" />



---

## 🛠 2. Main Functionalities

### 📍 Spatial & Temporal Control
* **Universal ROI Selection:** Use the search bar for locations or manually click the map. The app automatically captures coordinates.
* **Custom Study Period:** Define precise start and end dates to capture seasonal dynamics or specific flood/drought events.
* **Cloud Management:** Dynamic filter for Max Cloud Cover (%) to ensure high-quality spectral retrieval.

### 🛰️ Visualization Modules
* **True Color (RGB):** Standard Sentinel-2 visualization.
* **False Color Infrared:** Enhanced visualization for distinguishing between healthy vegetation and water boundaries.
* **Opacity Control:** Integrated sliders to blend satellite imagery with analytical layers.

### 💧 Module 1: Water Surface & Vegetation Dynamics
* **NDVI Analysis:** Compute and map the Normalized Difference Vegetation Index. Includes a pixel-level time-series chart for phenology studies.
* **Automated Water Masking:** Threshold-based extraction of water bodies.
* **Surface Area Quantification:** Draw a polygon to calculate area in **square meters (m²)** and **hectares (ha)**.
* **Variation Tracking:** Generate time-series charts of water surface area to monitor reservoir depletion or expansion.

### 🧪 Module 2: Advanced Water Quality Analysis
Monitor the "optical fingerprint" of the water with dedicated indices for:
* **Chlorophyll-a (Chl-a):** Indicators of algal biomass and eutrophication.
* **Turbidity:** Measurement of water clarity and light scattering.
* **Total Suspended Matter (TSM):** Quantifying inorganic and organic particles.
* **CDOM:** Colored Dissolved Organic Matter analysis.

**Features:** Choose specific spectral indices, visualize spatial distribution layers, and generate temporal plots to observe concentration trends.

---

## 🎥 Demo Video
https://github.com/user-attachments/assets/a619e74a-5933-4303-b1ed-7cf599f95116



---

## 📥 3. Data Export & Portability
The app is designed for "Open Science" and GIS integration. Users can export:
* **Vector Data:** Download the Water Mask as a **KML** for use in Google Earth Pro, QGIS, or ArcGIS.
* **Tabular Data:** Export area calculations and time-series metrics as **CSV/Geojson**.
* **Visuals:** Save generated charts (NDVI, Area, WQPs) directly from the UI.

---

## 📋 4. User Workflow
1. **Define Location:** Search or click to set the ROI.
2. **Set Timeframe:** Input dates and click **"Apply Dates."**
3. **Select Module:** * Choose **Vegetation/Water Mask** for physical area analysis.
    * Choose **Water Quality** and select your parameter (e.g., Turbidity).
4. **Interact:** Draw a polygon over a reservoir to activate the "Surface Area" tools.
5. **Analyze:** Click any point on the map to generate a 1-pixel time-series chart.
6. **Export:** Use the download buttons to take your data offline.

---

## 🎯 5. Use Cases
* **Reservoir & Lake Management:** Track volume fluctuations and siltation trends.
* **Environmental Change Detection:** Monitor the impact of droughts or land-use changes on water health.
* **Academic Research:** Rapidly extract spectral data for $R_{rs}$ validation and ML training (GLORIA dataset integration).
* **Vegetation Phenology:** Studying the relationship between catchment greenery and water quality.

---
## 🚀 Launch the App
https://aymenzegaargee.users.earthengine.app/view/remon-app-for-reservoirs-management-2

*Developed by Dr. Aymen Zegaar. For technical inquiries regarding the algorithms (Chl-a, TSM, etc.), please refer to the [Research Folder](../../research/README.md).*
