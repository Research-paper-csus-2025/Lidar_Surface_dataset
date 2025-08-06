# README

## 1. Indoor LiDAR Specularity Dataset for Material Classification

This repository consists of LiDAR scan data from 15 different indoor surfaces, computing IR specularity. This dataset is meant for the research paper on material classification, mmWave reflection analysis, and reflection prediction using machine learning (ML).

---

## 2. Dataset Overview

- **Environment**: Microwave laboratory at California State University, Sacramento  
- **Used Sensor**: Quanergy M8 LiDAR with 3D scanning application  
- **Distance from surface**: 44 inches from the material  
- **Used reflective border material**: 34 × 18 inches  
- **Scan Duration**: 10 seconds per surface material  
- **Software used**: 
  - *Qview*: 3D point capture from LiDAR scan data  
  - *CloudCompare*: Data post-processing and viewing of point clouds  
- **Data format**: Excel to process and analyze the point cloud data for specific surfaces  

---

## 3. Surface Materials Intensity (Point Count Per Material in the LiDAR Dataset)

| **Material**           | **Number of Points** |
|------------------------|----------------------|
| Linoleum               | 5,189                |
| Smooth wood            | 5,073                |
| Silver plates          | 5,066                |
| Rough wood             | 5,048                |
| Drywall                | 5,032                |
| Concrete wall          | 5,025                |
| Cardboard              | 5,010                |
| Projector screen       | 4,994                |
| TV                     | 4,993                |
| Fabric pinboard        | 4,984                |
| Styrofoam              | 4,977                |
| Corkboard              | 4,956                |
| Whiteboard             | 4,940                |
| Metal copper           | 4,896                |
| Metal tin              | 4,780                |
| Carpet                 | 3,193                |
| **Total**              | **78,165**           |

---

## 4. Tools Used

- **CloudCompare**: For cropping 3D point clouds to fit within the bounding box based on our reflective border.  
- **Qview**: iOS app for 3D point capture from LiDAR scan data.  
- **Microsoft Excel**: To process and analyze the point cloud data for specularity computation.  
- **Python**: For ML modeling and visualization.  

---

## 5. Files in this Repository

- **Specularities.xlsx** – Dataset of different materials with intensity and rings.  
- **README.md** – Dataset documentation  
