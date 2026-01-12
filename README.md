# Wetland Permanence Classification Using Multi-Temporal Sentinel-2 NDWI

**Author:** Image Bhattarai  
**Location:** Brookings County, South Dakota  
**Year:** 2024  

---

## Project Overview
This project develops an automated method to classify wetland hydroperiods
(permanent, vegetated, seasonal) using temporal variability of NDWI derived from
multi-season Sentinel-2 imagery.

---

## Methods
- Sentinel-2 NDWI (Spring, Summer, Fall)
- Coefficient of Variation (CV)
- CDL-based wetland masking
- Patch filtering (>0.01 ha)
- 2-pixel erosion buffer

---

## Results

### Wetland Mask
![Wetland Mask](figures/Figure1_Wetland_Mask.jpg)

### CV Map
![CV Map](figures/Figure2_CV_Map.png)

### Classification
![Classification](figures/Figure3_Classification_Map.png)

---

## Presentation
📄 [View full presentation](presentation/Wetland_Permanence.pdf)

---

## Code
Full Python workflow available in `/code`.
