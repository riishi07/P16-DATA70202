# P16-DATA70202


# Network Analysis of Algal Blooms in UK Lakes

This repository contains the full analysis pipeline for the MSc Applied Data Science project titled **"Network Analysis of Algal Blooms in UK Lakes"**. The project uses ecological datasets to investigate the relationships between environmental forcing variables and algal bloom dynamics using clustering and network community detection methods.

---

## 🔍 Project Description

This study applies a multivariate, network-based methodology to historical lake monitoring data from UK Centre for Ecology & Hydrology (UKCEH), focusing on:

- Exploratory Data Analysis (EDA)
- Feature engineering (seasonal trends, rolling averages, stratification phases)
- Random Forest feature importance analysis
- PAM clustering for seasonal pattern detection
- Louvain community detection on cosine similarity networks

The analysis was conducted separately for four lakes:
- Windermere South Basin
- Windermere North Basin
- Esthwaite Water
- Blelham Tarn

---

## 📁 Folder Structure

```
📁 notebooks/              # Jupyter Notebooks for EDA, clustering, RF, Louvain
📁 data/                   # Processed datasets (excluding raw due to size limits)
📁 figures/                # Visualizations and outputs
📄 requirements.txt        # Python package dependencies
📄 LICENSE                 # MIT License
📄 README.md               # This file
```

---

## 📦 Data

Due to GitHub file size limitations, raw datasets are **not included** in this repository.

You can access the original datasets here:
🔗 **UKCEH Dataset Link**: https://catalogue.ceh.ac.uk/documents/bf30d6aa-345a-4771-8417-ffbcf8c08c28

Included in this repository:
- `Processed Datasets/`: Monthly forcing matrices ready for analysis
- `EDA Visualizations/` and `Lakes Visualization/`: Key plots and exploratory figures
- `Forcing Matrix for dashboard/`: Aggregated and reshaped matrices used for interactive dashboards

All datasets are shared for academic and non-commercial use only.

---

## ▶️ How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/algal-bloom-network-analysis.git
   cd algal-bloom-network-analysis
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Launch notebooks:
   ```bash
   jupyter notebook
   ```

Start with `notebooks/01_EDA.ipynb` and follow the pipeline sequentially.

##DOI
10.5281/zenodo.15395703
[![DOI](https://zenodo.org/badge/982768730.svg)](https://doi.org/10.5281/zenodo.15395702)




## 📝 License

This project is licensed under the MIT License. See [LICENSE](./LICENSE) for details.
