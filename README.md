# Remote Sensing – Deforestation Detection Assignment

This repository contains my solution to remote sensing assignment.  
The goal is to use Sentinel-1 SAR images to classify forest vs. non-forest pixels  
and to detect the timing of a deforestation event.

All code and analysis appear inside the notebook:
`Intro_assignment.ipynb`

---

## Dataset
The assignment provides three folders:  
• forest – images of a stable forest area  
• non_forest – images of a non-forested area  
• time_series – images of a site where deforestation occurred  
Each image is a GeoTIFF with 3 bands: VV, VH, and incidence angle.  
The acquisition date of each image is encoded in the filename  
(e.g., `..._20200326T093933_...`).
---

## Part 1 – Forest Classification
Objective:  
Develop two different methods to classify each pixel as forest or non-forest  
using only the SAR bands.  
The task allows any approach (heuristic, supervised, or unsupervised),  
as long as two methods are implemented and compared.

---

## Part 2 – Deforestation Event Detection
Objective:  
Use the methods from Part 1 to analyze the time-series images  
and determine when the forest in the given region was removed.
