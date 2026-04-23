# 🌍 Climate Risk AI

## 📌 Overview
Climate Risk AI is a data-driven system that builds an interpretable Climate Risk Index based on real-world economic and environmental data.

It combines GDP data from the World Bank with CO₂ emissions data from the Global Carbon Project (via Our World in Data) to evaluate the relative climate risk of different countries.

---

## 🧠 What this project does

- Loads real GDP data (World Bank)
- Loads real CO₂ emissions data (Global Carbon Project)
- Computes economic and environmental indicators:
  - CO₂ per capita
  - CO₂ growth
  - Carbon intensity
  - GDP growth
- Normalizes indicators using statistical scaling
- Builds a weighted Climate Risk Index (0–100)
- Classifies countries into:
  - 🟢 Low Risk
  - 🟡 Medium Risk
  - 🔴 High Risk

---

## 📊 Output

The system produces:
- A ranked Climate Risk Index per country
- Risk classification (Low / Medium / High)
- Visual comparison of global climate risk levels

---

## 🌍 Data Sources

- World Bank Open Data (GDP)
- Our World in Data (CO₂ emissions - Global Carbon Project)

---

## 🧠 Key Insight

Climate risk is not only about emissions, but about:
- emissions intensity
- economic growth efficiency
- per-capita impact

This model provides a simplified but interpretable approximation of these dynamics.

---

## ⚙️ Installation

pip install -r requirements.txt

## 👤 Author

Angelo Sorte
