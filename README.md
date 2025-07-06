# 🧯 Image Processing for Defect Detection in PCB using MATLAB

This project demonstrates how to detect manufacturing defects in Printed Circuit Boards (PCBs) using classical image processing techniques in MATLAB. It simulates a real-world visual inspection system often used in electronics manufacturing quality control (QC) environments.

---

## 🧠 Objective

To automatically identify common PCB defects such as:
- Open circuits (missing tracks)
- Short circuits (extra copper)
- Missing pads or holes
- Solder bridges

---

## 🛠️ Tools & Technologies
- MATLAB (R2021 or later)
- Image Processing Toolbox
- Morphological Operations
- Logical Image Comparison
- Thresholding and Filtering

---

## 🖼️ Workflow

1. **Read the Reference and Test PCB images**
2. **Preprocess the images**  
   - Convert to grayscale  
   - Apply filtering and thresholding  
3. **Detect structural differences** using XOR or subtraction
4. **Apply morphological operations** to highlight defects
5. **Overlay defects** onto original image for visualization
6. **Display results** (bounding boxes, red highlights)

