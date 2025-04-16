# 🧪 Product Defects: Poisson Distribution Simulation

![Python](https://img.shields.io/badge/Python-3.9%2B-blue.svg)
![NumPy](https://img.shields.io/badge/Library-numpy-yellow)
![SciPy](https://img.shields.io/badge/Library-scipy-blue)
![License](https://img.shields.io/badge/License-MIT-green.svg)

This project explores the **Poisson(λ = 7)** distribution to simulate and analyze the number of defective products produced daily in a factory. We use Python libraries such as `scipy.stats` and `numpy` to calculate theoretical probabilities and analyze simulated real-world data.

---

## 📌 Project Goals

- Understand theoretical properties of the Poisson distribution
- Simulate a full year's worth of defect data (365 days)
- Compare theoretical expectations with simulated results
- Analyze percentiles and rare event probabilities

---

## 📁 Dataset

- Simulated using `stats.poisson.rvs(lam=7, size=365)`
- Represents the number of defective items per day across 1 year

---

## 📊 Key Tasks and Findings

### 📐 Theoretical Insights
- **Expected Value**: 7 defects/day
- **P(7 defects)**: ~0.149
- **P(≤4 defects)** (a great day): ~0.173
- **P(>9 defects)** (a bad day): ~0.173

### 💻 Simulated Data (365 Days)
- Generated using `scipy.stats.poisson.rvs()`
- **Total expected defects**: 2555
- **Actual total defects** (from simulation): Slightly below or close to 2555
- **Average defects/day**: Approximately 7 (close to λ)
- **Maximum defects in a day**: Varies per run (e.g., 15)
- **P(observing ≥ max observed value)**: Rare event probability calculated

### 🎯 Percentile Analysis
- **90th percentile** threshold: ~10 defects/day
- **Proportion of days exceeding this**: ~10%, matching theoretical expectations

---

## 🔧 Libraries and Tools Used

- Python 3
- NumPy
- SciPy (stats module)
- Jupyter Notebook / script.py

---

## 📂 Repository Structure
```
Poisson-Defect-Analysis/
├── poisson_defect_simulation.ipynb
├── README.md
```

---

## 📬 Contact
**Irmak Erkol**  
📧 irmakerkol00@gmail.com  
💼 [LinkedIn](https://linkedin.com/in/ierkol)

---

