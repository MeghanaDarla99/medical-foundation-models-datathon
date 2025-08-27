# medical-foundation-models-datathon
# EmoryCXR-first: EDA & Embedding Comparisons (with supporting MIMIC-CXR)

This repo centers on **EmoryCXR**: we perform EDA, build **study-level (frontal-first) cohorts**, define a **binary Pleural Effusion** endpoint (drop −1 uncertain), and compare **foundation-model embeddings** (RAD-DINO, BioMedCLIP, CheXagent, MedGemma, MedImageInsight).  
We also include **supporting EDA on MIMIC-CXR** for cross-dataset sanity checks.

## 🔎 What’s inside
- **EmoryCXR EDA**: view mix (AP/PA/Lateral), images per study & per year, label prevalence, and class balance
- **Cohort building**: one image per study (frontal-first), **patient-level splits** to avoid leakage
- **Primary endpoint**: **Pleural Effusion** (binary 0/1; uncertain −1 dropped) + split-wise counts
- **Embedding comparisons**: UMAP (cosine) plots across multiple models (Emory embeddings)
- **MIMIC-CXR (supporting)**: mirrored EDA and label landscape to contextualize Emory findings

## 🚀 Quickstart
```bash
# optional virtual env
python -m venv .venv && source .venv/bin/activate   # Windows: .venv\Scripts\activate
pip install -r requirements.txt
# open the notebooks and run
