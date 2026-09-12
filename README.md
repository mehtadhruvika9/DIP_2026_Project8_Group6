# DIP_2026_Project8_Group6

## Vehicle Orientation Estimation Using Conventional Image Processing

**Course:** ECE 501 – Digital Image Processing  
**Institution:** Ahmedabad University  
**Topic:** 8 – Vehicle Orientation Estimation Using Conventional Image Processing

---

## Project Overview

This project aims to estimate the orientation of vehicles in aerial images using conventional digital image-processing techniques.

The project will use the **DRASHTI-HaOBB** dataset, which contains drone-based vehicle images with Oriented Bounding Box (OBB) annotations, vehicle classes, difficulty levels, and heading angles.

The estimated vehicle orientation will be compared with the ground-truth orientation provided by the dataset.


---

## Objectives

- Extract individual vehicle crops using OBB annotations.
- Convert the dataset heading angle from **0°–359°** to the required **0°–90° orientation** representation.
- Implement conventional image-processing methods for orientation estimation.
- Compare different methods such as:
  - Contour/shape-based methods
  - PCA-based orientation estimation
  - Hough Transform
  - Minimum-area rectangle fitting
- Calculate the angular error between estimated and ground-truth orientations.
- Analyze the effect of vehicle class, size, image quality, and difficulty level on performance.

---

## Dataset

**DRASHTI-HaOBB – Drone Nadir-view Annotated Images of Vehicles Detection Dataset for India with Heading-angle Oriented Bounding Box**

Dataset:  https://zenodo.org/records/18278989

The dataset contains vehicle images along with OBB coordinates, class labels, difficulty levels, and heading-angle annotations.

---

## Methodology

The project will broadly follow these steps:

1. Dataset preparation and annotation parsing
2. Vehicle crop extraction using OBBs
3. Ground-truth orientation conversion
4. Image preprocessing
5. Orientation estimation using conventional methods
6. Comparison with ground-truth orientation
7. Angular error calculation
8. Class-wise and size-wise performance analysis

---

## Repository Structure
 ```text
DIP_2026_Project8_Group6/
│
├── README.md
├── Code/
├── Results/
├── Mid_Sem_Report/
└── End_Sem_Report/
```
## Progress Tracking

- Weekly commits pushed every **Saturday, 5:00 PM**
- Mid-semester presentation: ~12 October 2026
- End-semester presentation: ~16 November 2026

## References

1. Y. Bhavsar, M. Zaveri, M. Raval, K. R. Patel, and S. B. Zaveri, "Descriptor: Drone Nadir-view Annotated Images of Vehicles Detection Dataset for India with Heading-angle Oriented Bounding Box (DRASHTI-HaOBB)," *IEEE Data Descriptions*, 2026, doi: 10.1109/IEEEDATA.2026.3670752.
2. Y. Bhavsar, M. Zaveri, M. Raval, S. Zaveri, and Ahmedabad University, "DRASHTI-HaOBB: Drone nadiR-view Annotated imageS of veHicles dataseT for India - Heading-angle Oriented Bounding Box," *Zenodo*, 2026, doi: 10.5281/zenodo.18278989.
3. "Vehicle Position Monitoring Using Hough Transform," *IERI Procedia*, vol. 4, pp. 316–322, 2013.
