# Global Layoffs Analysis

A data analysis project exploring global layoffs across companies, industries, and countries between 2020 and 2023 — built with Python (Pandas, NumPy, Matplotlib, Seaborn) and visualized further in an interactive Power BI dashboard. 

## Overview

This project studies real-world layoffs data to understand how global economic shifts — from pandemic disruption to the post-pandemic tech correction — affected companies across industries, countries, and funding stages. The analysis moves from data cleaning and exploratory data analysis (EDA) in Python through to a full interactive Power BI report.

csv used - Used for the project (modified) - ['dataset'](./layoffs.csv)
Original dataset is  from the [Layoffs Dataset on Kaggle](https://www.kaggle.com/datasets/swaptr/layoffs-2022) uploaded by Swapnil Tripathi.

## Key Questions Explored

- Which country had the most layoffs?
- Which company had the most layoffs?
- What are the top 10 companies by layoffs, per year (2020–2023)?
- How did layoffs change over time (year by year)?
- Does funding raised relate to layoff size?
- What are the total layoffs per industry and funding stage?
- Which quarters had the most layoffs?

## Key Findings

1. 2021 saw noticeably fewer layoffs than 2022, as the market correction that drove 2022's spike hadn't yet begun.
2. Consumer and Retail were hit hardest overall, likely reflecting the bursting of pandemic-era demand.
3. The United States had by far the most layoffs across all years (250k+), with India a distant second (35k+).
4. Post-IPO companies saw a significantly higher number of layoffs than companies at other funding stages.
5. Q1 (January–March) consistently had the highest layoffs across years, possibly tied to fiscal year-end and budget corrections.

## Tools Used

- **Python** — Pandas, NumPy (data cleaning, aggregation)
- **Matplotlib, Seaborn** — exploratory visualizations
- **Power BI** — interactive dashboard and final report

## Project Structure

```
├── layoffs_analysis.ipynb     # Full EDA and analysis notebook
├── layoffs_cleaned.xlsx       # Cleaned dataset used for Power BI
├── layoffs_report.pbix        # Interactive Power BI dashboard
└── README.md
```

## Dashboard Preview

Click on [Power BI Dashboard](./layoffs_analysis.pdf) to view the dashboard.

## How to Run

1. Clone this repository
2. Install dependencies:
   ```
   pip install pandas numpy matplotlib seaborn
   ```
3. Open `layoffs_analysis.ipynb` in Jupyter Notebook, JupyterLab, or Google Colab
4. Run cells top to bottom
5. To explore the Power BI dashboard, open `layoffs_report.pbix` in Power BI Desktop (free download from Microsoft)

## Data Source

Dataset covers global company layoffs from 2020–2023, including company name, industry, country, layoff counts, date, funding stage, and total funds raised.

## Author

Built by [Soulity31](https://github.com/Soulity31) as part of a self-taught data analysis portfolio.
