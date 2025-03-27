# 🧠 Mapping Neuromodulator Receptor Genes Across Neuronal Cell Subclasses, Cell Classes, and Brain Regions

This repository contains the source code, notebooks, and visualizations developed for my MSc thesis at the University of Bristol. The project explores how **neuromodulator receptor genes** — specifically those associated with **dopamine, serotonin, and acetylcholine** — are distributed across various **neuronal cell types** and **brain regions**, using cutting-edge **single-cell RNA sequencing data** and **machine learning**.

---

## 📘 Abstract

The regulation of neuromodulator receptor genes plays a crucial role in brain function and psychiatric health. This project presents a comprehensive computational mapping of key neuromodulator receptor gene families — **dopamine (DRD1–DRD5)**, **serotonin (HTR1A–HTR7)**, and **acetylcholine (CHRM1–CHRM5, CHRNA)** — across neuronal subclasses, classes, and multiple human brain regions. It serves as a stepping stone toward **precision psychiatry**, aiding in the development of targeted psychiatric treatments and diagnostics.

The analysis is conducted using **SMART-seq v4** single-cell transcriptomic data from the Allen Brain Atlas, and leverages both **unsupervised** (UMAP, PCA, Louvain, t-SNE) and **supervised** (Random Forest) learning techniques.

---

## 🧪 Project Objectives

- ✅ Handle high-dimensional RNA-seq data efficiently
- ✅ Map receptor gene expression across neuronal cell subclasses, classes, and brain regions
- ✅ Explore gene-level variations tied to psychiatric disorders
- ✅ Build predictive models for automatic annotation of new cells

---

## 🧬 Data Source

- **Allen Brain Institute SMART-seq v4 Dataset**
  - [Human Multiple Cortical Areas (SMART-seq)](https://portal.brain-map.org/atlases-and-data/rnaseq/human-multiple-cortical-areas-smart-seq)
  - 49,495 nuclei transcriptomes from post-mortem human brain samples

---

## 🧰 Technologies & Tools

- **Languages**: Python 3.11
- **Environments**: Jupyter Notebooks, PyCharm, AWS SageMaker
- **Libraries**: Pandas, NumPy, Dask, Scikit-Learn, Plotly, Seaborn, Matplotlib
- **ML Techniques**:
  - PCA, t-SNE, UMAP, Louvain, DBSCAN, K-means
  - Random Forest, LSTM (experimental)
- **Preprocessing**: Freeman-Tukey and Log transformations, StandardScaler, filtering

---

## 🗂 Repository Structure

| File | Description |
|------|-------------|
| `AnnotationModel.ipynb` | Predicts neuronal subclass/cell class/brain region using Random Forest |
| `DataExploration.ipynb` | EDA on metadata and gene expression matrices |
| `Mapping.ipynb` | Mapping dopamine/serotonin/acetylcholine receptor genes |
| `Serotonin-new.ipynb` | Focused serotonin receptor gene analysis |
| `Splitting (1).ipynb` | Data filtering, splitting, and class balancing |
| `FinalProject (1).ipynb` | Complete analysis pipeline |
| `EDA (3).ipynb.zip` | Additional EDA notebooks |
| `Dopamine-vis.ipynb.zip` | Dopamine-specific visualizations |
| `README.md` | Project overview |

---

## 📊 Key Visualizations

- 📈 Gene expression UMAPs and t-SNE plots
- 🧩 Louvain clustering of neuronal cell types
- 🧠 Brain region-wise receptor gene expression heatmaps
- 🧬 Violin plots of key gene markers (e.g., DRD1, HTR2A)

---

## 📌 Results

- Mapped neuromodulator genes across neuronal subclasses, classes and multiple brain regions
- Identified class-specific and region-specific gene markers
- Random Forest model achieved high accuracy in predicting unseen cell annotations
- Visual tools were used to represent nuanced gene activity patterns

---

## 🔍 Future Work

- Integrate diseased-brain transcriptomic datasets
- Expand to multimodal data: epigenomics, proteomics
- Develop interactive dashboards (e.g., Streamlit) for researchers

---

## 🤝 Acknowledgements

Special thanks to **Dr. Sean Froudist-Walsh** (University of Bristol) for invaluable supervision, and to the **Allen Brain Institute** for open-access datasets that made this research possible.

---

## 📄 License

This repository is part of an MSc dissertation and is shared for academic and research purposes. Contact the author for any collaboration or extended usage.

---

## 🔗 Citation

If you use this repository or ideas from this research, please cite:

**Tanmay Sagar Huria** (2025). *Mapping Neuromodulator Receptor Genes Across Neuronal Cell Subclasses, Cell Classes, and Brain Regions.* MSc Data Science Dissertation, University of Bristol.
