# 🚗 BI Car Purchase Helper: Multi-Criteria Decision Analysis (MCDA)

This Business Intelligence project provides a structured framework for selecting the optimal vehicle from a set of alternatives. By applying **Multi-Criteria Decision Analysis (MCDA)**, the tool balances technical specifications with user-defined priorities to rank vehicles objectively.

## 🎯 The Decision Problem
Choosing a car involves conflicting criteria such as cost, performance, safety, and fuel efficiency. This project implements a **Decision Support System (DSS)** that quantifies these factors to identify the best "compromise" solution tailored to a specific user profile.

## 🛠️ Methodology & Techniques
The project follows a rigorous BI decision-making workflow:

1. **Criteria Weighting:** Assigning relative importance to different attributes (e.g., Price vs. Horsepower) based on user preference.
2. **Data Normalization:** Converting different units (e.g., liters per 100km and price in euros) into a comparable scale (0 to 1).
3. **MCDA Implementation:**
    * **Weighted Sum Model (WSM):** Aggregating scores to find the highest-ranking alternative.
    * **Decision Matrix:** Construction of a matrix comparing each car model across all selected criteria.
4. **Sensitivity Analysis:** Testing how changes in priority weights affect the final ranking to ensure the decision is robust.

## 📊 Key Features
* **Dynamic Ranking:** Instant update of the car rankings based on real-time weight adjustments.
* **Trade-off Analysis:** Objective comparison between high-performance/high-cost models and economical alternatives.
* **Customizable Criteria:** Ability to add or remove criteria like fuel consumption, engine power, or brand reliability.

## 📂 Project Structure
* `BI_car_buy_helper.ipynb`: Python implementation of the decision algorithms and data processing.
* `data/`: Dataset containing technical specifications for various car models.
* `documentation/Rapport_APP_BI_Data_Mining.pdf`: Full technical documentation (Part 3) covering the decision-making theory and results.

## ⚙️ Installation & Usage

### 1. Requirements
Install the necessary Python libraries:
```bash
pip install pandas numpy matplotlib seaborn
```

### 2. Run the Helper
Launch the Jupyter Notebook and adjust the weights in the analysis section to reflect your priorities:
```Bash
jupyter notebook BI_car_buy_helper.ipynb
```
---
*Developed as part of the Business Intelligence curriculum at Avignon University, focusing on Decision Support Systems.*
