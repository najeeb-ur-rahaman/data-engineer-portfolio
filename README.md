# UK Cost of Living Analysis

This project explores the rising cost of living in the UK using real-world datasets provided by the [Office for National Statistics (ONS)](https://www.ons.gov.uk/). The goal is to analyze how inflation and housing costs have changed over recent years, and prepare the data for future visualizations and dashboards.

## 📌 Project Motivation

After a break from the tech industry, I wanted to return by working on real, practical projects involving public data. This project is my first step back, helping me practice my **data wrangling**, **analysis**, and **visualization** skills using Python and Pandas.

## 📂 Datasets Used

1. [**Consumer Prices Index including Housing (CPIH)** ](https://www.ons.gov.uk/economy/inflationandpriceindices/datasets/consumerpriceindices)

   - Captures inflation rates across different product categories (e.g., food, housing, transport).
   - Wide-format with time-series price indices by category.

2. [**Index of Private Housing Rental Prices (IPHRP)**](https://www.ons.gov.uk/datasets/index-private-housing-rental-prices/editions/time-series/versions/41)
   - Measures the change in rental prices by region across the UK.
   - Useful for regional comparison of housing cost pressures.

Data was downloaded directly from the ONS website and manually inspected for structure, completeness, and consistency.

## ✅ Analysis Performed

- CPIH Time Series Trend
- Regional Rental Comparison
- London vs East Midlands Trend
- Growth Rate Calculations
- Correlation Check (CPIH vs Rental Price)

## 🧱 Key Milestones

- **Cleaned and structured** the Consumer Price Index including Housing (CPIH) dataset
- **Transformed** the Index of Private Housing Rental Prices (IPHRP) into a usable time-series format
- **Merged datasets** to analyze regional cost trends
- **Created visual summaries** for inflation vs rent comparisons across time and regions

## ⚠️ Data Limitations

While working on this project, several data inconsistencies emerged:

- Inaccurate or conflicting values across different datasets
- Mismatched time periods between sources
- Lack of granularity or missing regional breakdowns in key areas

Due to these limitations, this project is being concluded as a learning milestone rather than a full analytical product.

## 🧰 Tools Used

- Python (Pandas)
- Google Colab
- Visual Studio Code
- Office for National Statistics (ONS) datasets

## 🚀 Getting Started

You can run the analysis notebook using Google Colab or your local environment with Python 3.

1. Clone the repository:

```bash
git clone https://github.com/najeeb-ur-rahaman/uk_cost_of_living_analysis.git
```
