📊 Iraq Primary School Enrollment (1970–2023)

This project explores Iraq’s primary school gross enrollment ratio from 1971–2023, combining SQL, Python (Pandas/Matplotlib), and Jupyter Notebook into a structured analysis.

It delivers 14 insights across two groups:

Core 9 Questions (trend, decade averages, YoY changes, etc.)

5 Bonus Insights (pre/post 1990, volatility, resilience, etc.)

All results are reproducible, visualized, and documented in both HTML and PDF formats.

📂 Project Structure

Iraq_Data_Portfolio/
│
├── API_IRQ_SE.PRM.ENRR_EN_csv_v2_200041.csv -> Original dataset (World Bank)
│
├── results/                # Core 9 questions
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
├── bonus_insights/ # Bonus 5 insights
│   ├── enrollment_pre_post_1990.png / .csv
│   ├── enrollment_cagr_peak.png / .csv
│   ├── enrollment_decade_volatility.png / .csv
│   ├── enrollment_peak_drop.png / .csv
│   └── enrollment_resilience.png / .csv
│
├── Iraq_Primary_Enrollment.ipynb -> Full notebook (core + bonus)
├── Iraq_Primary_Enrollment.html -> Exported interactive notebook
├── Iraq_Primary_Enrollment.pdf -> Polished PDF report
├── MANIFEST.csv -> File-to-description map
└── README.txt -> Project summary

🔎 Core 9 Insights (with Visuals)

Overall Trend → Iraq enrollment improved until early 1990s, then dropped, later recovered.

Trend with Regression → Long-run slope is positive.

Trend with Mean Line → Mean ≈ 93.3%.

Highest vs Lowest → Peak: 1991 (111.2%); Lowest: 1971 (70.0%).

Decade Averages → 1980s highest; 1970s lowest.

Year-over-Year Changes → Biggest rise: 1979; Biggest drop: 1992.

Overall Average (Card) → 93.26%.

Distribution (Mean vs Median) → Median > Mean → skew from 1990s drop.

Recovery (1992–1999) → Enrollment recovered to 1992 levels by 1999.

💡 Bonus Insights (Extra 5)

Before vs After 1990 → Avg rose from 92.4% → 95.0%.

CAGR to Peak (1971→1991) → 2.34% per year growth.

Decade Volatility → Most volatile = 1970s; Least = 1980s.

Peak-to-Drop (1991→1992) → Sharp –16.8% fall.

Resilience Index → Recovery speed ≈ +2.67 points/year.

📑 Deliverables

📓 Jupyter Notebook: Iraq_Primary_Enrollment.ipynb

🌐 Interactive HTML: Iraq_Primary_Enrollment.html

📄 Polished PDF: Iraq_Primary_Enrollment.pdf

📋 Manifest: MANIFEST.csv

🚀 Skills Demonstrated

Data Cleaning & Preparation → Removing nulls, structuring CSVs.

Exploratory Data Analysis (EDA) → Trends, averages, YoY, volatility.

Visualization → Matplotlib static plots for clarity.

Documentation → Organized outputs, manifest tracking, portfolio-ready exports.
