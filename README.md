# SNPRA Dataset (Smart Number Plate Recognition for Access)

Welcome to the official release of the **SNPRA Dataset**, a curated collection of annotated vehicle images focused on **Bangladeshi number plates**. This dataset is a part of our broader research on energy-efficient, multilingual, and scalable license plate recognition systems aimed at industrial and smart transportation applications.

---

## 🔍 Overview

The SNPRA dataset is specifically designed to assist in the development and evaluation of **Automatic License Plate Recognition (ALPR)** systems under diverse real-world conditions. It contains a diverse set of **1,500+ images** of Bangladeshi number plates across multiple vehicle types, captured in varied lighting, angles, and environmental conditions to ensure robustness and realism.

This is an **initial subset** of our full dataset. We are actively working on expanding the dataset in terms of volume, quality, and multilingual plate representation. A comprehensive version will be released soon to promote **reproducibility**, **benchmarking**, and **open collaboration**.

---

## 📂 Dataset Structure

```bash
SNPRA_Dataset/
├── images/
│   ├── train/
│   ├── val/
│   └── test/
├── annotations/
│   ├── train/
│   ├── val/
│   └── test/
└── data_split_info.json
```

## 🛠️ Annotation Format
• Each annotation file (in JSON) includes:

• Bounding box coordinates (x_min, y_min, x_max, y_max)

• Class label (number_plate)

• Image metadata (file name, dimensions)

Example:
```
json
Copy
Edit
{
  "filename": "vehicle_001.jpg",
  "width": 1280,
  "height": 720,
  "annotations": [
    {
      "label": "number_plate",
      "bbox": [482, 610, 582, 650]
    }
  ]
}
```
## 🔬 Use Cases
• License Plate Detection and Recognition (ALPR)

• Multilingual OCR and Localization

• Cross-Script Validation and Generalization Studies

• Benchmarking Computer Vision Models in Real-World Scenarios

## 📈 Future Plans
• We are actively expanding this dataset to include:

• Multilingual number plates from multiple countries

• Annotations in XML, YOLO, and COCO formats

• Higher-resolution images and challenging weather scenarios

• Integration with video-based ALPR tasks

• We welcome contributions and collaborations from the research community.

## 📜 License
This dataset is released for non-commercial research use only. Please cite our work if you use the SNPRA dataset in your research or publications.

## 📧 Contact
For collaboration, contributions, or questions:

📮 Email: eshansengupta2000@gamil.com

🧑‍🔬 Project Lead: Eshan Sengupta

🏛️ Institution: Guru Nanak Dev University, Amritsar, India
