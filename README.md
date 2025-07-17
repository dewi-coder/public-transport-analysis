README
# 🚇 Public Transport Trend Analysis (2020–2025)

This project analyzes the usage trends of public transportation in City X over the period of 2020 to 2025. The goal is to understand how different transportation modes evolved before, during, and after the COVID-19 pandemic as an indicator of economic recovery.

## 📌 Project Objective
- Analyze monthly and yearly usage of 5 major public transport modes.
- Visualize trends using Seaborn and Matplotlib.
- Extract insights on transportation growth and public mobility.
- Simulate 360 data rows (5 modes × 12 months × 6 years) for a realistic analysis.

## 📊 Dataset
Synthetic data generated using Python:
- Year: 2020–2025
- Month: 1–12
- Mode of Transport: Bus, MRT, TransJakarta, KRL, LRT
- Users: 30,000–300,000 per month

## 🛠️ Tools
- pandas
- matplotlib
- seaborn
- Jupyter Notebook

## 📈 Sample Output
(See trend_transport.png in /outputs)

## 🧠 Insights
- User count increases post-2021
- TransJakarta and KRL dominate
- Recovery trend supports economic rebound theory

## 🚀 How to Use
Clone and run the notebook:
```bash
git clone https://github.com/dewi-coder/public-transport-analysis.git
cd public-transport-analysis
jupyter notebook notebook/public_transport_analysis.ipynb
