🌊 AI for Water Quality Prediction (SDG-6)

This project is a machine learning solution that predicts whether water is safe or unsafe for use, based on key water quality parameters. It is inspired by SIH problem statements in the Software / AI domain, and aligns with United Nations SDG 6: Clean Water and Sanitation.
📌 Problem Statement

Access to safe drinking water is critical for health and sustainable living. However, water quality monitoring is often manual, slow, and resource-intensive.
The goal of this project is to:

Predict water quality automatically using AI.

Use simple sensor-like data (temperature, pH, turbidity, rainfall).

Classify water as Safe (1) or Unsafe (0).

📊 Dataset

A synthetic dataset with 1000 samples is used to simulate real-world water parameters.

Features (Columns):

Temperature_C → Water temperature (15–35 °C)

pH → Acidity/alkalinity (6–9)

Turbidity_NTU → Cloudiness due to particles (1–500 NTU)

Rainfall_mm → Daily rainfall (0–200 mm)

Water_Safe → Label (1 = Safe, 0 = Unsafe)

💡 Safety rule:

Water is safe if pH is between 6.5–8.5 AND Turbidity_NTU < 50.

Dataset file:
📂 data/synthetic_water_quality.csv

⚙️ Tech Stack

Python 3

Pandas, NumPy for data processing

Matplotlib / Seaborn for visualization

Scikit-learn for ML models
