# 🧬 _2026_jonsson_veps

Code and data access for the manuscript:

**“Disagreement among variant effect predictors guides experimental prioritization of target proteins.”**

---

## 👨‍🔬 Authors

- **Nicolas F. Jonsson**¹  
- **Joseph A. Marsh**²*  
- **Kresten Lindorff-Larsen**¹*  

¹ Linderstrøm-Lang Centre for Protein Science, Department of Biology, University of Copenhagen, Copenhagen, Denmark  
² MRC Human Genetics Unit, Institute of Genetics and Cancer, University of Edinburgh, Edinburgh, United Kingdom  

📧 **Correspondence**

- joseph.marsh@ed.ac.uk  
- lindorff@bio.ku.dk  

\* Corresponding authors

---

# 📖 Overview

Interpreting the functional consequences of genetic variation, particularly rare missense variants, remains a central challenge in human genetics. Computational **variant effect predictors (VEPs)** and experimental **multiplexed assays of variant effects (MAVEs)** provide complementary approaches.

VEPs offer scalable predictions across the proteome, while MAVEs provide detailed empirical measurements but remain resource intensive and cannot yet be broadly applied.

In this study we analysed predictions from **10 variant effect predictors across more than 13,000 human proteins** and quantified inter-predictor concordance.

We observed substantial variability across proteins in the degree of agreement between predictors and investigated structural, functional, and gene-level features associated with this variation.

Importantly, **inter-VEP concordance showed no relationship with agreement to experimental MAVE data**. If predictor agreement reflected how intrinsically predictable a protein is, these quantities would be expected to correlate. Their decoupling instead suggests that MAVEs provide orthogonal information relative to VEP predictions.

We therefore propose **using inter-VEP disagreement as a strategy to prioritize proteins for experimental characterization**. Focusing on proteins with low predictor concordance may maximize the informational value of new MAVEs and improve variant interpretation in both research and clinical contexts.

---

# 📂 Repository structure

```
.
├── data/                # Small metadata files used in the analysis
├── figures/             # Output figures generated for the manuscript
├── notebooks/           # Jupyter notebooks for exploratory analysis
├── scripts/             # Analysis and plotting scripts
└── README.md
```

This repository mainly contains **analysis and plotting code used to generate the figures in the manuscript**.

---

# 💾 Data availability

Due to their size, the full datasets used in this study are hosted externally.

📦 **ERDA data repository**  
(ERDA link to be added)

The ERDA archive contains:

- Variant effect predictor scores  
- Protein-level summary statistics  
- Processed datasets used in the analysis  
- Intermediate files used to generate figures  

---

# ▶️ Reproducing the figures

1. Clone this repository

```bash
git clone https://github.com/<username>/_2026_jonsson_veps.git
cd _2026_jonsson_veps
```

2. Download the dataset from ERDA

3. Extract the files and place them in the appropriate directory (e.g. `data/`)

4. Run the plotting scripts

Example:

```bash
python scripts/plot_figure_1.py
```

---

# 📑 Citation

If you use this code or data, please cite:

```
Jonsson NF, Marsh JA, Lindorff-Larsen K.
Disagreement among variant effect predictors guides experimental prioritization of target proteins.
```

(Journal reference will be added upon publication.)

---

# 📜 License

This project is released under the **MIT License**.

---

⭐ If this repository is useful for your research, please consider starring the project.
