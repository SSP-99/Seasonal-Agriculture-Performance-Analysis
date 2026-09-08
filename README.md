 # Seasonal Agriculture Performance Analysis

**VOIS AICTE Batch1 2026-2027 — Major Project (Data Visualization)**

## Overview
This project analyzes a seasonal agriculture performance dataset of 4,000 farm records spanning three seasons (Kharif, Rabi, Zaid), 8 crops, and 15 Indian states. It investigates how agricultural performance — yield, profit, resource usage, and environmental conditions — varies across seasons, and derives evidence-based insights and recommendations for seasonal agricultural planning.

## Problem Statement
Agricultural activities are influenced by seasonal variations in environmental conditions, farming practices, resource availability, and market conditions. As a result, agricultural performance may differ from one season to another. This project analyzes the dataset to identify meaningful patterns, trends, relationships, and variations across seasons.

## Dataset
- **Records:** 4,000 farms
- **Seasons:** Kharif, Rabi, Zaid
- **Crops:** 8 (Rice, Wheat, Maize, Cotton, Pulses, Groundnut, Chilli, Sugarcane)
- **Features:** 28 columns covering environmental conditions, soil and resource inputs, yield, production, and economic outcomes (cost, revenue, profit)

## Tools & Technologies
- Python 3
- Pandas, NumPy — data cleaning and manipulation
- Matplotlib, Seaborn — data visualization
- SciPy — statistical testing (ANOVA)
- Google Colab / Jupyter Notebook

## Key Analysis Steps
1. Data exploration and cleaning (handling missing values via group-wise median imputation)
2. Seasonal comparison of yield, production, and profit
3. Statistical significance testing (ANOVA) on seasonal differences
4. Resource usage analysis (fertilizer, water, pesticide) by season
5. Correlation analysis between environmental conditions and yield
6. Regional (state-wise) consistency check of seasonal patterns
7. Crop-wise seasonal performance comparison
8. Insights and recommendations for seasonal planning

## Key Findings
- Profit differs significantly across seasons (ANOVA p < 0.00001), while yield differences are not statistically significant (p = 0.23) — cost and pricing factors drive seasonal economic gaps more than yield itself.
- Zaid season shows the lowest yield, highest average cost, and highest water use per unit output — the least efficient season overall.
- Environmental factors (rainfall, temperature, soil moisture) show weak correlation with yield in this dataset.
- Kharif season has the highest disease/pest risk (~54%), consistent with monsoon-season humidity.
- The "best" season for yield is state-dependent, not universal — e.g., Punjab peaks in Rabi, Karnataka peaks in Zaid.

## Repository Contents
- `Seasonal_Agriculture_Performance_Analysis.ipynb` — full analysis notebook with code, charts, and interpretation
- `seasonal_agriculture_performance_dataset.csv` — dataset used
- `Seasonal_Agriculture_Performance_Analysis.pptx` — project presentation

## How to Run
1. Open the notebook in Google Colab or Jupyter
2. Upload `seasonal_agriculture_performance_dataset.csv` when prompted
3. Run all cells in order (Runtime → Restart and run all)

