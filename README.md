# Iran Quarterly Electricity Consumption Analysis

This project involves the analysis of historical electricity consumption data in Iran. It utilizes time-series data processing techniques to identify trends, seasonal patterns, and quarterly fluctuations over a 13-year period.

## Project Overview

### 1. Data Processing

The analysis is based on the `data.csv` dataset, which records quarterly electricity consumption.

- **Dataset Characteristics**: 54 entries representing quarters from 1387-Q1 to 1400-Q2.
- **Feature Engineering**: Extracted 'Year' and 'Quarter' (Q1-Q4) from the raw `quarter` string to allow for granular seasonal analysis.
- **Data Cleaning**: Verified that there are no missing values (NaN) within the consumption records.

### 2. Exploratory Data Analysis (EDA)

The project focuses on visualizing the consumption trajectory to understand long-term growth and recurring seasonal dips or peaks.

- **Time-Series Visualization**: A line chart with markers was developed to show consumption units over time, specifically highlighting the progression from year 1387 to 1399+.
- **Trend Analysis**: The visualization reveals a clear upward trend in electricity usage, with specific quarterly cycles repeating annually.

### 3. Key Findings

- The data covers a span of roughly 14 years.
- Quarterly consumption shows significant variance, likely corresponding to seasonal shifts in energy demand within the region.

## Technology Stack

- **Language**: Python 3.x
- **Libraries**:
  - `pandas`: For time-series data manipulation and cleaning.
  - `numpy`: For numerical operations and data range handling.
  - `matplotlib`: For generating high-quality line charts and trend visualizations.

## How to Run

1. Place `data.csv` in the project root directory.
2. Install the required Python packages:
   ```bash
   pip install pandas numpy matplotlib
   ```
3. Open `electricity_consumption_analysis.ipynb` in a Jupyter environment.
4. Execute the cells to generate the data summaries and the quarterly consumption plot.
