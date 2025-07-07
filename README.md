# Wine Cultivar Chemical Analysis

This project explores whether there is a significant difference in **phenol** and **proline** content between wines from two Italian cultivars. The analysis was conducted as part of a STAT 201 final project at UBC.

## 📊 Objectives
- Investigate if the mean **total phenols** differs between cultivars 1 and 2.
- Investigate if the mean **proline content** differs between cultivars 1 and 2.

## 🛠 Tools & Methods
- **Language:** R
- **Libraries:** `tidyverse`, `tidymodels`, `infer`, `broom`
- **Techniques:**  
  - Data wrangling and visualization (histograms, facet grids)  
  - Hypothesis testing (bootstrap method, CLT-based confidence intervals)  
  - Confidence interval construction for difference in means  

## 📌 Dataset
- **Source:** [UCI Wine Dataset](https://archive.ics.uci.edu/dataset/109/wine)  
- **Features used:** total phenols, proline, cultivar class (1 or 2)

## 🔑 Results
- **Total phenols:** No significant difference in mean content between cultivars (bootstrap p ≈ 0.98, 90% CI [0.45, 0.71])
- **Proline:** No significant difference in mean content between cultivars (bootstrap p ≈ 0.93, 90% CI [540, 654])
- Both bootstrap and CLT methods produced consistent results.

## 📈 How to View
- Open `Final Project.ipynb` using Jupyter Notebook or RStudio with an R kernel.
- All code, plots, and statistical output are included in the notebook.

## 🌱 Future Directions
- Extend analysis to other chemical components or sensory attributes.
- Explore the impact of terroir or winemaking practices on wine composition.

## 👥 Contributors
- Yilin Long  
- Tamara Nammao  
- Sahil Vashist  

## 📂 Files
- `Final Project.ipynb` — The complete R Notebook with code, plots, and analysis.
