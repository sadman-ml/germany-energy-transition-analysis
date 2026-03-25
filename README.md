# Germany's Energy Transition: Impact of Nuclear Phase-out on CO2 Emissions

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![ML](https://img.shields.io/badge/Model-Random%20Forest-orange.svg)](https://scikit-learn.org/)
[![Data](https://img.shields.io/badge/Source-Our%20World%20in%20Data-green.svg)](https://ourworldindata.org/)

## Project Overview
Germany's **"Energiewende"** (Energy Transition) is one of the most ambitious national policy shifts in the world. This project provides a comprehensive data-driven analysis of Germany's energy landscape from 1990 to 2023. The primary focus is to evaluate how the progressive shutdown of nuclear power plants affected the country's **Carbon Intensity** and its transition toward renewable energy.

### Research Questions:
- How has Germany's energy mix evolved following the decision to phase out nuclear power?
- Did the nuclear exit lead to an increase in carbon emissions, or did renewables successfully fill the gap?
- Using Machine Learning, what are the most significant drivers of carbon intensity in the German power grid?

---

## Tech Stack & Engineering Skills
- **Language:** Python 
- **Libraries:** - `Pandas` & `NumPy`: For data engineering, cleaning, and structural auditing.
  - `Matplotlib` & `Seaborn`: For advanced stacked area charts and dual-axis trend visualizations.
  - `Scikit-learn`: Implementation of the **Random Forest Regressor** for predictive modeling.
  - `Joblib`: For model persistence and deployment-ready file handling.
- **Environment:** Google Colab.

---

## Key Discoveries (What I Found?)
Based on my analytical pipeline, I extracted three major insights:

1.  ** Successful Decarbonization:** Despite the nuclear shutdown, Germany's carbon intensity (gCO2/kWh) has continued to decline significantly.
2.  ** Renewable Integration:** The deficit created by the nuclear exit was effectively filled by a massive surge in **Wind and Solar** energy production.
3.  ** Predictive Power:** My Random Forest model identified **Renewable Growth** and **Coal Reduction** as the most critical features influencing carbon levels, achieving an **R² Score of 97%+**.

---

## Visualizations
The project features three professional-grade analytical plots:
- **Energy Mix Evolution:** A stacked area chart showing the transition of power sources over 33 years.
- **Impact Analysis:** A dual-axis correlation between nuclear generation and CO2 intensity reduction.
- **Feature Importance:** A mathematical ranking of variables that drive carbon emissions in the grid.

---

## Project Structure
- **Germany_Nuclear_Analysis.ipynb**: Complete source code with a step-by-step analytical audit.
-  **data/processed/processed_data.csv**: The curated and cleaned dataset used for training.
-  **outputs/plots/**: High-resolution professional graphs and charts.
-  **models/germany_energy_model.pkl**: The saved Machine Learning model ready for future predictions.

---

## How to Explore My Work
1. Clone the repository or download the files.
2. Open the `.ipynb` file in **Google Colab** or Jupyter Notebook.
3. Upload the `owid-energy-data.csv` to the environment.
4. Execute the cells sequentially to reproduce the data audit and ML results.

---

## Why I Created This?
I am passionate about the intersection of Data Science and Sustainability. By quantifying the "Energiewende," I wanted to learn how to transform raw global data into actionable insights that can influence environmental policy.

---

## Contact & Support
If you find this analysis insightful or useful for your research, please **give it a star ⭐!**

**Sadman Ahmed** 

---
