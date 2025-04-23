# Investigating the Effects of Renewable Energy and Energy Efficiency on Economic Growth in Low- and Middle-Income Nations

## Project Overview

This repository presents the complete MSc Data Science research project, which explores how **renewable energy usage** and **energy efficiency improvements** contribute to **sector-specific economic growth**—specifically within **agriculture**, **industry**, and **services**—across **low- and middle-income countries (LMICs)**. The study incorporates differences in **carbon dioxide emissions** to better understand how environmental and energy-related factors interact with economic development in varying national contexts.

---

## Dataset Overview

The dataset originates from the [World Development Indicators](https://databank.worldbank.org/source/world-development-indicators#), incorporating 266 countries & 91 indicators across the following themes:

- **Economic Policy & Debt** → National Accounts → Growth Rates  
- **Environment** → Emissions  
- **Environment** → Energy Production & Use

The primary dataset is stored in:
```
/P_Data_Extract_From_World_Development_Indicators
```

---

## Folder Structure

```
datasets/                     # Cleaned and raw data files
notebooks/
    ├── data_preprocessing.ipynb
    ├── EDA.ipynb
    ├── PCA_clustering.ipynb
    └── regression.ipynb
plots/                        # All visual outputs and graphs
requirements.txt              # Project dependencies
LICENSE.txt                   # License information
README.md                     # This file
```

---

## Tools & Technologies

- **Core Languages**: Python  
- **Libraries**:
  - Data Analysis: `pandas`, `numpy`
  - Visualization: `matplotlib`, `seaborn`, `plotly`
  - Machine Learning & Clustering: `scikit-learn`
  - Econometric Modelling: `statsmodels`, `linearmodels`
- **Platforms**: Jupyter Notebooks, Google Colab

---

## Requirements

Ensure all dependencies are installed by running:

```bash
pip install -r requirements.txt
```

---

## How to Use

1. **Clone the repository**:

   ```bash
   git clone https://github.com/nazmul-nil/MSc-DS-Research-Project-UH.git
   cd MSc-DS-Research-Project-UH
   ```

2. **Open notebooks** in your preferred environment (Jupyter, Colab, etc.)

3. **Follow the workflow**:
   - Begin with `data_preprocessing.ipynb`
   - Continue with `EDA.ipynb` for exploration and correlation analysis
   - Use `PCA_clustering.ipynb` for dimensionality reduction and grouping
   - Finalize with `regression.ipynb` to examine panel regression models

---

## LICENSE

Refer to `LICENSE.txt` for license details.

---

## Citation

If you reference this work in academic research or publications, please cite it as:

> Hossain, N. (2025) *Investigating the Effects of Renewable Energy and Energy Efficiency on Economic Growth in Low- and Middle-Income Nations*. GitHub Repository. Available at: [https://github.com/nazmul-nil/MSc-DS-Research-Project-UH](https://github.com/nazmul-nil/MSc-DS-Research-Project-UH) [Accessed date].

---
