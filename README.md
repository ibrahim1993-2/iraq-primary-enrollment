# 📊 Iraq Primary School Enrollment (1971–2023)

This project analyzes Iraq’s **primary school gross enrollment ratio** (1971–2023) using **SQL-style analysis, Python (Pandas/Matplotlib), and Jupyter Notebook**.

It delivers **14 insights** across two groups:
- **Core 9 Questions** (trend, decade averages, YoY changes, etc.)
- **5 Bonus Insights** (pre/post 1990, volatility, resilience, etc.)

All results are **reproducible**, **visualized**, and **documented** in both **HTML** and **PDF** formats.

---

## 📂 Project Structure

Iraq_Data_Portfolio/
│
├── IRQ_SE.PRM.ENRR.zip                      # Original dataset (World Bank export)
│
├── results/                                 # Core 9 insights (CSVs + charts)
│   ├── enrollment_trend.png
│   ├── enrollment_trend_regression.png
│   ├── enrollment_trend_with_mean.png
│   ├── enrollment_highest_lowest.png
│   ├── enrollment_decade_average.png
│   ├── enrollment_yoy_change.png
│   ├── enrollment_average.png
│   ├── enrollment_distribution.png
│   ├── enrollment_recovery_1992_1999.png
│   ├── iraq_enrollment_growth_metrics.csv
│   ├── iraq_enrollment_statistics.csv
│   └── iraq_primary_enrollment_clean.csv
│
│   └── bonus_insights/                      # Extra 5 insights (CSVs + charts)
│       ├── enrollment_pre_post_1990.png
│       ├── enrollment_pre_post_1990.csv
│       ├── enrollment_cagr_peak.png
│       ├── enrollment_cagr_peak.csv
│       ├── enrollment_decade_volatility.png
│       ├── enrollment_decade_volatility.csv
│       ├── enrollment_peak_drop.png
│       ├── enrollment_peak_drop.csv
│       ├── enrollment_resilience.png
│       └── enrollment_resilience_index.csv
│
├── Iraq_Primary_Enrollment.ipynb            # Full notebook (core + bonus)
├── Iraq_Primary_Enrollment.html             # Exported interactive notebook
├── Iraq_Primary_Enrollment.pdf              # Polished PDF report
├── MANIFEST.csv                             # File-to-description map
└── README.txt                               # Plain-text project summary

---

## 🔎 Core 9 Insights

1. **Overall Trend** → Enrollment improved until early 1990s, then dropped, later recovered.
2. **Trend with Regression** → Long-run slope is positive (**+0.52/year**).
3. **Trend with Mean Line** → Mean ≈ **93.3%**.
4. **Highest vs Lowest** → Peak: **1991 (111.2%)**, Lowest: **1971 (70.0%)**.
5. **Decade Averages** → Highest: **1980s**, Lowest: **1970s**.
6. **Year-over-Year Changes** → Biggest rise: **1979**, Biggest drop: **1992**.
7. **Overall Average** → **93.26%**.
8. **Distribution (Mean vs Median)** → Median (95.6%) > Mean (93.3%) → skewed by 1990s drop.
9. **Recovery (1992–1999)** → Enrollment recovered to 1992 levels by **1999**.

---

## 💡 Bonus Insights

1. **Before vs After 1990** → Avg rose from **92.4% → 95.0%**.
2. **CAGR to Peak (1971→1991)** → **+2.34% per year** growth.
3. **Decade Volatility** → Most volatile = **1970s**; Least = **1980s**.
4. **Peak-to-Drop (1991→1992)** → Sharp **–16.8%** fall.
5. **Resilience Index** → Recovery speed ≈ **+2.67 points/year**.

---

## 📑 Deliverables

- 📓 **Notebook**: `Iraq_Primary_Enrollment.ipynb`
- 🌐 **Interactive HTML**: `Iraq_Primary_Enrollment.html`
- 📄 **Polished PDF Report**: `Iraq_Primary_Enrollment.pdf`
- 📋 **Manifest**: `MANIFEST.csv`
- 🗂️ **Dataset**: `IRQ_SE.PRM.ENRR.zip`

---

## 🚀 Skills Demonstrated

- **Data Cleaning & Preparation** → Handling nulls, structuring CSVs
- **Exploratory Data Analysis (EDA)** → Trends, averages, YoY, volatility
- **Visualization** → Matplotlib plots for clarity
- **Documentation** → Organized outputs, manifest tracking, portfolio-ready exports
