# 🌍 COVID-19 Country-Level Data Analysis

## 📌 Project Description
A Python-based analytical exploration of global COVID-19 metrics across countries and WHO regions. 
This project processes raw case data to reveal patterns in infection rates, mortality, recovery trends, 
and regional disparities through statistical analysis and visual storytelling.

## 🎯 Objectives
1. **Data Exploration**: Profile global case distribution and data quality
2. **Comparative Analysis**: Benchmark countries by key metrics:
   - Confirmed cases
   - Fatality rates (`Deaths / 100 Cases`)
   - Recovery efficiency (`Recovered / Confirmed`)
3. **Regional Trends**: Compare WHO regions' pandemic responses
4. **Anomaly Detection**: Identify statistical outliers in reporting

## 🛠️ Tools & Libraries
### Core Stack
```python
import pandas as pd       # Data wrangling (v1.3+)
import numpy as np        # Numerical operations (v1.21+)
import seaborn as sns     # Visualizations (v0.11+)
import matplotlib.pyplot as plt  # Plotting (v3.5+)

**## 🚀 How to Run/View the Project**

# 1. Clone the repo
git clone https://github.com/sandy56-hash/COVID-19-Data-Tracker.git

# 2. Install dependencies (Python 3.8+ required)
pip install pandas numpy matplotlib seaborn jupyter

# 3. Launch Jupyter Notebook
jupyter notebook

****🔍 Key Insights & Reflections****

 Notable Findings:
✓ Extreme Fatality Variance: Yemen (28.5%) vs. Qatar (0.15%)
✓ Data Gaps: 12 countries reported 0 recoveries despite >1k cases
✓ Regional Patterns: Western Pacific had highest median recovery rate (89%)

Technical Reflections:
• Challenge: Handling inconsistent "Active Cases" calculations across countries
• Success: Dynamic metric generation (e.g., Death_Rate) proved versatile
• Lesson: Log-scale visualizations may better represent skewed distributions

****Future Directions:****
◉ Integrate population-normalized metrics
◉ Build interactive Dash/Plotly dashboard

