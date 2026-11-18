# Sport Analytics - Basketball Second-Half Outcome Prediction

This repository contains the project report and analysis tools for forecasting second-half basketball outcomes using first-half statistics from the Turkish Basketball Super League (BSL) 2020-2021 season.

## Authors
* Anıl Alpay
* Yusuf Hakan Aktaş

---

## About the Project
This study investigates the predictive power of first-half basketball statistics in forecasting second-half outcomes, offensive aggression, and team discipline. Moving beyond traditional box-score metrics, custom strategic engineered metrics were introduced to capture in-game momentum and qualitative dynamics.

## Engineered Metrics
* **Chaos Control Factor (CCF):** Measures defensive discipline and efficiency by evaluating defensive actions relative to fouls committed.
* **Net Disruption Index (NDI):** Quantifies which team is more successful at physically interrupting the opponent's offensive rhythm.
* **Assist-to-Scoring Ratio (ASR):** Evaluates the collective efficiency and organizational quality of a team's offense.
* **Tempo/Substitution Pressure (TEMPOSUB):** Captures physical load, pace, and the coach's rotation strategy.
* **Run Differential (RD):** Acts as a momentum factor capturing scoring trends during the final minutes of the second quarter.

## Models and Methods
* **Models:** Decision Tree and XGBoost classification algorithms.
* **Prediction Targets:** 
  1. Match Winner
  2. Second-Half Two-Point Attempt Comparison
  3. Second-Half Turnover Comparison

## File Structure
* `Anıl Alpay-Yusuf Hakan Aktaş_STAT438_Project2.pdf`: Detailed academic project report.
