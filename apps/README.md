# 🚀 Dev Apps & Tools
[<- Back to Main Hub](../README.md)

This directory contains a suite of **Earth Observation (EO)** tools and **Google Earth Engine (GEE)** applications developed for high-precision water resources monitoring. These tools bridge the gap between complex satellite algorithms and end-user accessibility.

---

## 🛠️ Tech Stack
* **Platform:** Google Earth Engine (JavaScript API & Python API)
* **Sensors:** Sentinel-2 MSI, Landsat 8/9, Sentinel-3 OLCI
* **Core Logic:** Spectral Indices, Atmospheric Correction, and ML-based retrieval

---

## 📱 Application Catalog

### 1. [Water Quality Analysis Suite](./water-quality-app/)
**Primary Focus:** Bio-optical parameter retrieval.
* **Retrievals:** Chlorophyll-a, Turbidity, CDOM, and TSM.
* **Special Feature:** Incorporates feature importance insights from the **GLORIA** dataset to ensure mission adequacy across diverse optical water types.
* **Status:** `Stable / Version 1.2`
👉 [Explore App & Methodology](./water-quality-app/)

<!-- ### 2. [Surface Water Masking & Metrics](./water-mask-app/)
**Primary Focus:** Hydrological area quantification.
* **Functionality:** Automated water body extraction with dynamic thresholding.
* **Exports:** Multi-format vector support (KML, GeoJSON, SHP, CSV).
* **Metrics:** Time-series surface area variation and trend analysis.
* **Status:** `In Development`
👉 [Explore App & Documentation](./water-mask-app/) -->

---

## 🧪 Shared Modules
To keep this repository **Lean**, I use a modular approach. The core calculations used in these apps are stored in our shared library:

* `modules/spectral_indices.js`: Optimized functions for NDWI, MNDWI, and AWEInsh.
* `modules/reflectance_utils.js`: Functions for $R_{rs}$ (Remote Sensing Reflectance) processing and scaling.

---

## 📈 Visibility & Impact
These applications are designed for:
1. **Researchers:** Reproducing results from my peer-reviewed publications.
2. **Water Managers:** Real-time monitoring of reservoir and coastal health.
3. **Data Scientists:** Accessing clean, pre-processed EO data for ML training.

---
*For questions regarding the underlying algorithms or collaboration opportunities, please open an [Issue](https://github.com/YOUR_USERNAME/GEE-Water-Hub/issues).*
