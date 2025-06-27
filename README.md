# 🧪 A/B Testing Deep Dive — Real-World Marketing Insights

This project is a complete **end-to-end A/B testing case study** using marketing campaign data.  

---

## 🚀 What This Project Covers

### 🔹 Data Source
- **Dataset:** `marketing_AB.csv` (real-world simulated data)
- Key features:
  - `test group` — Control vs Test group
  - `converted` — Whether user completed desired action (conversion)
  - `most ads day` / `most ads hour` — Timeframes of ad exposure
  - `total ads` — Number of ads seen by user

### 🔹 Workflow Breakdown
1. **Data Cleaning & Preprocessing**
   - Dropped irrelevant features (e.g., user ID)
   - Converted categorical columns for analysis

2. **Exploratory Data Analysis**
   - Univariate analysis with histograms, pie charts, count plots
   - Bivariate analysis with bar plots, box plots

3. **Statistical Hypothesis Testing**
   - **Chi-squared test**: Checking significance of `test group`, `ad day`, `ad hour` on conversion rates
   - **Shapiro-Wilk**: Normality of `total ads` distribution
   - **Levene’s Test**: Variance check between groups
   - **T-test / Mann-Whitney U**: Mean difference of `total ads` based on conversion

4. **Insights**
   - Identified which group converted better
   - Pinpointed best ad timings for higher conversions
   - Validated significance with stats — no guesswork

---

## 📊 Tech Stack
- Python 🐍
- pandas, numpy
- seaborn, matplotlib
- scipy.stats for all stat 

---



