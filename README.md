# Seasonal Agriculture Performance Analysis

Major Project — VOIS AICTE Data Analytics Internship (August 2026 Batch)

## Overview

This project analyzes agricultural performance across three Indian cropping seasons — **Kharif**, **Rabi**, and **Zaid** — using a dataset of 4,000 farm records. The goal is to identify how yield, profit, cost, water efficiency, and risk vary by season, and to surface actionable, data-driven recommendations for seasonal agricultural planning.

## Problem Statement

Agricultural activities are influenced by seasonal variations in environmental conditions, farming practices, resource availability, and market conditions. Raw agricultural data alone does not clearly explain how performance changes across seasons. This project investigates those seasonal differences by identifying meaningful patterns, trends, relationships, and variations in the dataset.

## Dataset

- **Records:** 4,000 farms
- **Seasons:** Kharif, Rabi, Zaid
- **Crops:** Wheat, Maize, Pulses, Rice, Cotton, Chilli, Groundnut, Sugarcane
- **Key fields:** Rainfall, temperature, humidity, soil quality, irrigation method, fertilizer/pesticide use, yield, production, cost, revenue, profit, water usage, and disease/pest risk

## Key Findings

1. **Kharif is the most profitable and highest-yielding season**; **Zaid runs at a net average loss**, with 64% of Zaid-season farms reporting negative profit.
2. **Drip irrigation is the only method that stays profitable across all three seasons** — it holds up in Zaid while Flood and Rainfed irrigation turn negative.
3. **Water efficiency and yield are the strongest positive drivers of profit**; fertilizer usage shows almost no correlation with profitability.
4. **Disease/pest risk is highest in Kharif**, yet Kharif remains the most profitable season overall.
5. **The seasonal yield decline (Kharif → Rabi → Zaid) holds consistently across all 8 crop types.**

## Recommendations

- Prioritize Drip irrigation, especially for Zaid-season crops.
- Re-evaluate fertilizer application — current usage shows little return on profit.
- Target support (irrigation upgrades, crop insurance) at Zaid-season farms given their high loss rate.
- Investigate Kharif's elevated disease/pest risk further, since better management here could push profits even higher.

## Tech Stack

- **Python 3**
- **Pandas / NumPy** — data cleaning and aggregation
- **Matplotlib / Seaborn** — data visualization
- **Jupyter Notebook** — analysis environment

## Repository Structure

```
├── Seasonal_Agriculture_Performance_Analysis.ipynb   # Full analysis notebook
├── seasonal_agriculture_performance_dataset.csv      # Dataset used
└── README.md                                         # This file
```

## How to Run

1. Clone this repository:
   ```
   git clone <your-repo-url>
   ```
2. Install dependencies:
   ```
   pip install pandas numpy matplotlib seaborn
   ```
3. Open the notebook:
   ```
   jupyter notebook Seasonal_Agriculture_Performance_Analysis.ipynb
   ```
4. Run all cells.

## Author

Rahul Kumar
Chandigarh University
VOIS AICTE Data Analytics Internship — August 2026 Batch
