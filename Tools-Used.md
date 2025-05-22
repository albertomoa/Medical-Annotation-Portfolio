# 🛠️ Tools Used in Medical Annotation Projects

This file documents the tools, platforms, and file formats used for medical image, text, and pharmaceutical annotation in this portfolio.

---

## 📷 Medical Image Annotation

| Tool | Purpose | Format |
|------|---------|--------|
| **Labelbox** | Bounding boxes and segmentation | JSON, Pascal VOC |
| **Roboflow** | Image classification and YOLO export | YOLOv5, COCO |
| **CVAT** | Advanced annotation with polygons, masks | XML, COCO |

---

## 📝 Medical Text Annotation

| Tool | Purpose | Format |
|------|---------|--------|
| **brat** | Named Entity Recognition (NER) and relations | `.ann` & `.txt` |
| **INCEpTION** | Complex relation and coreference annotation | XML |
| **spaCy** | NER model training | JSONL, spaCy DocBin |

---

## 💊 Pharmaceutical Text Annotation

| Tool | Purpose | Format |
|------|---------|--------|
| **Prodigy** | Clinical NER and pharmacovigilance tagging | JSONL |
| **Manual Tagging** | Drug labels and adverse events | `.csv`, `.txt` |

---

## 💡 Notes

- Annotations were manually validated or double-checked for accuracy.
- Format conversion (e.g., VOC ↔ YOLO) done via Roboflow or custom scripts.

