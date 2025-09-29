# 🫁 Kocaeli University Lung Cancer Pathology Dataset

The **Kocaeli University Lung Cancer Histology Dataset** is a curated collection of **H&E-stained whole-slide images (WSIs)** of lung tissue, obtained from the Medical Pathology Department of Kocaeli University, Faculty of Medicine.

Expert pathologists have annotated the dataset with **four distinct class labels**:

- 🔴 **ADENO** *(Adenocarcinoma)*  
- 🟠 **SCC** *(Squamous Cell Carcinoma)*  
- 🟡 **NOS** *(Not Otherwise Specified)*  
- 🟢 **NC** *(Not Cancerous — Normal Control)*  

> The first three classes represent subtypes of lung cancer, while the NC class includes histologically normal tissue slides used as healthy controls.

---


## 🧪 Dataset Details

- **Patch format:** `.tif` (TIFF)  
- **Patch size:** `400×400` pixels  
- **Source:** Extracted from **H&E-stained WSIs**  
- **Scan magnification:** `20×`  
- **Original WSI dimensions:** ~8,000 to 25,000 pixels  

---

## 🗂️ Dataset Structure

The dataset follows a **class-wise and patient-wise hierarchical organization**, as shown below:

```
dataset_root/
├── ADENO/
│ ├── patient_001/
│ │ ├── patch_001.tif
│ │ ├── patch_002.tif
│ │ └── ...
│ └── ...
├── SCC/
│ ├── patient_003/
│ │ └── ...
│ └── ...
├── NOS/
│ ├── patient_004/
│ │ └── ...
│ └── ...
└── NC/
├── patient_005/
│ └── ...
└── ...
```
---

## 🔗 Dataset Access  

👉 You can **download example data [here](https://drive.google.com/drive/folders/1BNtVx62udL9DisQQC208boGj8hN_dnt5)**.  

📦 You can **download the full dataset [here](https://drive.google.com/file/d/1T7GcM9boUZ3luou5vIT_uE7Y4_PUp5XW/)**.  

---

## 📄 Citation

> *Coming soon.*

---

## 🤝 Acknowledgements

Prepared in collaboration with the Medical Pathology Department of the Faculty of Medicine and the Department of Electronics and Communication Engineering of the Faculty of Engineering, Kocaeli University.
