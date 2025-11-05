# Drought Analysis in Konya, Türkiye  
**Spatial and Temporal Variations of Composite Drought Indices and Crop Yield Prediction**  
*A. Ünal Şorman · İrem Tanrıverdi · Berkay Akpınar · Ceylan Yozgatlıgil (METU)*  

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)]()  
[![R](https://img.shields.io/badge/R-4.2.2+-green.svg)]()  
[![License](https://img.shields.io/badge/License-Research%20Only-lightgrey.svg)]()  
[![Paper](https://img.shields.io/badge/Paper-Under%20Review-orange.svg)]()  

---

## Overview
This repository accompanies the paper:  
> **Spatial and temporal variations of composite drought indices using remote sensing, meteorological factors, and their use to assess winter crop yield predictions with machine learning algorithms — Case Study: Konya, Türkiye.**

It explores **agricultural drought monitoring** and **winter wheat yield prediction (2007–2021)** using  
machine learning and deep learning models with satellite, meteorological, and crop data.

---

## Repository Structure

| Folder | Description |
|--------|--------------|
| `classification/` | Scripts for drought classification (CatBoost, LSTM-GRU). |
| `yield_prediction/` | Models for annual wheat yield prediction (LightGBM, LSTM-GRU-Attention). |
| `index_data/` | Derived drought indices (VHI, TCI, SPI, GLNM). |
| `outputs/` | Model results, metrics, and visualizations. |

---

## Methods Summary
- **Composite Drought Index (GLNM):** Combines the Green Leaf Index (GLI) and Normalized Multiband Drought Index (NMDI).  
- **Classification:** CatBoost & LSTM-GRU with attention mechanism.  
- **Yield Prediction:** LightGBM & LSTM-GRU sequence models.  
- **Evaluation:** Accuracy, F1-score, RMSE, and R² metrics.

---

## 🌦️ Data Sources
- **Meteorological Data:**  
  Turkish State Meteorological Service (MGM) — restricted access  
  🔗 [https://www.mgm.gov.tr/](https://www.mgm.gov.tr/)
- **Crop Yield:**  
  Turkish Statistical Institute (TÜİK)  
  🔗 [https://www.tuik.gov.tr/](https://www.tuik.gov.tr/)
- **Satellite Data:**  
  - MODIS & Landsat (NASA EarthData): [https://earthdata.nasa.gov/](https://earthdata.nasa.gov/)  
  - USGS Earth Explorer: [https://earthexplorer.usgs.gov/](https://earthexplorer.usgs.gov/)

All remote sensing data were processed using **standard open-source tools** and **publicly available software packages** (Python, R, GDAL, raster, pandas, scikit-learn, TensorFlow).
