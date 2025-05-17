# Yulu – Hypothesis Testing for Shared Electric Cycle Demand

This project applies statistical hypothesis testing to analyze factors affecting the demand for shared electric cycles in India. Yulu, a micro-mobility platform, aims to understand the impact of season, weather, and working days on rental volumes to guide future business strategies.

---

## 📊 Problem Statement

Yulu has experienced a dip in revenue and seeks to identify the drivers behind changes in electric cycle rentals. This analysis uses t-tests, ANOVA, and chi-square tests to evaluate the significance of various variables on cycle demand.

---

## 📁 Dataset Overview

The dataset includes the following features:
- `datetime` – Timestamp of rental
- `season` – 1: Spring, 2: Summer, 3: Fall, 4: Winter
- `holiday` – 0 or 1
- `workingday` – 0 or 1
- `weather` – 1 to 4 (from clear to severe)
- `temp`, `atemp`, `humidity`, `windspeed`
- `casual`, `registered`, `count` (rental totals)

---

## 🛠️ Tools & Techniques Used

- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Scipy (stats)
- Hypothesis Testing:
  - Two-sample T-test
  - One-way ANOVA
  - Chi-Square Test
- Visual Distribution Checks (Histograms, Boxplots, QQ plots)

---

## 📈 Analysis Steps

1. **EDA** – Examined distribution of variables, null values, and segment-wise trends
2. **T-Test** – Tested whether working days have a significant impact on demand
3. **ANOVA** – Assessed rental variation across:
   - Different seasons
   - Weather categories
4. **Chi-Square Test** – Checked dependency between weather and season
5. **Assumption Testing** – Used QQ plots and Shapiro-Wilk to verify normality
6. **Significance Levels** – Applied α = 0.05 and reported p-values

---

## 📌 Key Findings

- ✅ Working days **significantly impact** rental counts (p < 0.05)
- ✅ Seasons and weather types show **statistical differences** in rental demand
- ⚠️ Weather is **dependent** on season (chi-square p < 0.01)
- 🚴 Rentals peak in summer and fall, especially on working weekdays with clear weather

---

## 💡 Business Recommendations

- Increase fleet availability and zone coverage during **summer and fall working days**
- Promote usage during holidays with **discount campaigns**
- Use **weather forecasting models** for demand planning
- Refine season-based pricing to align with expected usage

---

## 📂 Files Included

- `Yulu_Hypothesis_Testing.ipynb` – Jupyter Notebook with full analysis
- `Dataset/yulu_data.csv` – Dataset
- `README.md` – This project summary

---

## 🔗 Links

- [Portfolio Project Page](https://www.datascienceportfol.io/varshilgandhi308)
- [GitHub Repo](https://github.com/varshilgandhi/Yulu-Hypothesis-Testing)

---

## 🤝 Let’s Connect

Feedback or ideas? Connect with me on [LinkedIn](https://www.linkedin.com/in/varshil-gandhi-08470b200/).
