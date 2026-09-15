# 🌾 Seasonal Agriculture Performance Analysis

## 📌 Project Overview

A Python-based data analysis project exploring seasonal variations
in agricultural yield, profit, rainfall, and resource usage across
Kharif, Rabi, and Zaid seasons.

The project analyzes approximately 4,000 farm records using
Python-based exploratory data analysis and visualization techniques.

## 🎯 Objectives

- Analyze agricultural performance across different seasons
- Compare crop yield across Kharif, Rabi, and Zaid seasons
- Study seasonal rainfall patterns
- Analyze agricultural profitability
- Examine water and resource usage
- Investigate relationships between environmental and agricultural variables
- Generate meaningful insights using data visualization

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 📊 Analysis Performed

### Data Understanding
- Dataset structure and dimensions
- Data types
- Numerical and categorical variables

### Data Quality
- Missing-value analysis
- Duplicate-record detection
- Missing-value handling

### Exploratory Data Analysis
- Season distribution
- Crop distribution
- Yield distribution
- Profit distribution
- Rainfall distribution

### Statistical Analysis
- Mean
- Median
- Standard deviation
- Minimum and maximum
- Range
- Interquartile range (IQR)

### Bivariate Analysis
- Season vs Yield
- Season vs Profit
- Season vs Water Usage
- Rainfall vs Yield
- Farm Area vs Production
- Irrigation Method vs Yield

### Multivariate Analysis
- Crop + Season + Yield
- Irrigation + Season + Yield
- Rainfall + Yield + Season
- Yield + Profit + Season
- Correlation analysis

## 🔍 Key Findings

### Seasonal Performance

- **Kharif** recorded the highest average yield at **5.64 tonnes/ha**.
- Kharif also generated the highest average profit of approximately **₹178,914.65** per farm.
- **Zaid** recorded the lowest average yield at **4.67 tonnes/ha**.
- Zaid had a negative average profit of approximately **₹24,804.82**.
- Kharif received the highest average rainfall at approximately **852.08 mm**.

### Irrigation Performance

- **Drip irrigation** recorded the highest average yield at **6.62 tonnes/ha**.
- Drip irrigation also had the highest average profit at approximately **₹219,626** per farm.
- Flood irrigation had the highest average water usage among the irrigation methods analyzed.

### Crop Performance

- **Sugarcane** had the highest average yield at approximately **46.94 tonnes/ha**.
- Sugarcane also recorded the highest average profit at approximately **₹817,187.99**.
- Chilli recorded the second-highest average profit at approximately **₹750,878.34**.

### Data Quality

- The dataset contains **4,000 records and 28 variables**.
- No duplicate records were identified.
- Missing values were present in `Rainfall_mm`, `Soil_Moisture_pct`, and `Yield_Tonnes_Ha`.


## 📁 Project Structure

```text
Seasonal-Agriculture-performance-Analysis/
│
├── data/
│   └── seasonal_agriculture_performance_dataset.csv
│
├── notebooks/
│   └── Seasonal_Agricultural_performance_analysis.ipynb
│
├── reports/
│   ├── Major Project...
│   └── VOIS_Major_Project...
│
├── .gitignore
├── README.md
└── requirements.txt
