# Chest X-ray Annotation – Pneumonia Detection

## Project Overview

This project involves manual image annotation of chest X-ray images for abnormal findings such as **pneumonia opacities**. The goal is to simulate how radiographic data can be used in machine learning pipelines for diagnosis support.

This project is part of my [Medical Annotation Portfolio](../..), and demonstrates my ability to annotate medical images using industry tools.

---

## Dataset

- **Source**: [RSNA Pneumonia Detection Challenge – Kaggle](https://www.kaggle.com/competitions/rsna-pneumonia-detection-challenge/data)
- **Data Type**: Chest X-ray DICOM images converted to PNG
- **Number of Images Used**: 20
- **Image Format**: `.png`

---

## 🛠️ Annotation Process

- **Tool Used**: [Roboflow](https://app.roboflow.com/)
- **Type of Annotation**: Bounding Boxes
- **Labels**:
  - `Opacity`
  - `Pneumonia`

---

## 📁 File Structure
chest-xray/
├── images/ # Raw chest X-ray images
├── annotations/ # YOLO or COCO or Pascal VOC annotation files
├── screenshot.png # Optional: Screenshot of tool in use
└── README.md # Project documentation

---

## 📤 Annotation Export Format

- **Format**: YOLOv5
- Each label file (.txt) contains:
<class_id> <x_center> <y_center> <width> <height>

---

## Example Image & Annotation

Here is an example annotation created using Roboflow:

![Sample Annotation](./screenshot.png)

---

## Outcomes

- Practiced identifying radiological abnormalities
- Gained experience using Roboflow for image annotation
- Learned how to manage and export datasets for computer vision tasks

---

## Notes

- All annotations are done manually for demonstration purposes.
- This project simulates real-world data preparation for AI in medical imaging.
