# Thoracic Rangers – Emory CXR Embedding Atlas - Foundation Models - Datathon

An interactive visualization tool for **guiding subgroup analysis** of chest X-ray embeddings.  
Built during the **Emory Datathon 2025** to compare how different foundation models interpret CXR embeddings and identify outlier patterns.

---

## 🚀 Project Overview
We analyzed embeddings from the **Emory CXR dataset** using five state-of-the-art foundation models and developed a tool to visualize clustering patterns interactively.

### **Objective**
- Compare embeddings across models to understand representation differences.
- Identify **outlier clusters** and subgroup patterns.
- Enable **real-time exploration** using an interactive embedding atlas.

---

## 🧠 Models Used
- **RaD-DINO**
- **MedGemma**
- **CheXagent**
- **MedImageInsight**
- **BiomedCLIP**

---

## 🛠️ Tech Stack
| **Component** | **Tools/Methods** |
|--------------|--------------------|
| Dataset | Emory CXR |
| Visualization | UMAP + Cosine Similarity |
| Interactive Tool | Embedding Atlas |
| Language | Python (Jupyter Notebook) |
| Analysis | EDA, clustering, dimensionality reduction |

---

## 📊 Process Workflow
1. Exploratory Data Analysis (EDA) on CXR metadata & labels.
2. Selected **100K samples** per embedding model.
3. Performed **dimensionality reduction** using UMAP.
4. Generated **2D embedding visualizations**.
5. Built an **interactive real-time clustering tool**.
6. Sampled representative images from each cluster for insights.

---

## 👩‍💻 Contributors
- Mercy Nyanchama Nyambane
- Opeyami Adeniran
- Sri Jahnavi Adusumilli
- Meghana Darla
- Christopher Boon
- Jahanzaib Malik
- Chiratidzo
---

## 🔮 Future Work
- Compare cluster integrity under label misclassification.
- Cross-compare embeddings from different CXR datasets.
- Evaluate classification performance on single outcomes (e.g., pneumonia).

---

## 📄 License
MIT License. See `LICENSE` for details.

