# Seasonal Agriculture Performance Analysis

## 📌 Project Overview

This project analyzes agricultural performance across the three major agricultural seasons in India:

- Kharif
- Rabi
- Zaid

The analysis focuses on understanding seasonal differences in yield, production, revenue, cost, profit, water usage, environmental conditions and disease/pest risk.

The project uses Python-based data analysis, visualization and statistical techniques to identify important patterns and provide data-driven agricultural recommendations.

---

## 🎯 Objectives

The main objectives of this project are:

- Explore and understand the agricultural dataset.
- Clean and prepare the data for analysis.
- Compare agricultural performance across Kharif, Rabi and Zaid seasons.
- Analyze seasonal patterns and trends.
- Study relationships between environmental conditions and agricultural outcomes.
- Compare crop-wise and state-wise performance.
- Analyze water usage and irrigation efficiency.
- Investigate disease and pest risk.
- Identify unusual observations using outlier analysis.
- Apply statistical techniques such as ANOVA.
- Develop data-driven conclusions and recommendations.

---

## 📊 Dataset

The dataset contains **4,000 agricultural records**.

Important variables include:

- Season
- Crop
- State
- Farm Area
- Yield
- Production
- Revenue
- Cost
- Profit
- Water Usage
- Rainfall
- Temperature
- Humidity
- Sunlight
- Soil Moisture
- Soil pH
- Irrigation Type
- Disease/Pest Risk

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Statistical Analysis
- Data Visualization

---

## 🔍 Data Cleaning and Preparation

The dataset was checked for:

- Missing values
- Duplicate records
- Invalid numerical values
- Negative values
- Invalid soil pH values

Missing values were handled using median imputation.

Duplicate records were identified and removed.

Additional performance metrics were calculated, including:

- Profit Margin
- Cost per Hectare
- Revenue per Hectare
- Profit per Hectare
- Water Efficiency

---

## 📈 Analysis Performed

### Seasonal Analysis

Agricultural performance was compared across:

- Kharif
- Rabi
- Zaid

Metrics analyzed include:

- Average Yield
- Production
- Revenue
- Cost
- Profit
- Water Usage
- Water Efficiency
- Disease/Pest Risk

### Crop-wise Analysis

Crop performance was compared across different seasons.

### State-wise Analysis

Agricultural performance was compared across states and seasons.

### Irrigation Analysis

Different irrigation conditions were analyzed in relation to water usage and efficiency.

### Environmental Analysis

The project examines variables such as:

- Rainfall
- Temperature
- Humidity
- Sunlight
- Soil Moisture
- Soil pH

and their relationships with agricultural outcomes.

### Correlation Analysis

Correlation analysis was used to investigate relationships between agricultural, environmental and resource variables.

### Outlier Analysis

The Interquartile Range (IQR) method was used to identify unusual yield observations.

---

## 📊 Statistical Analysis

ANOVA was performed to determine whether agricultural performance differs significantly between seasons.

### Yield ANOVA

- F-statistic: **1.54**
- p-value: **0.214**

Since the p-value is greater than 0.05, the analysis did not find a statistically significant difference in average yield across the three seasons.

### Profit ANOVA

- F-statistic: **34.29**
- p-value: **< 0.001**

This indicates that profit differs significantly across seasons.

---

## 🏆 Key Findings

### Kharif

Kharif showed the strongest overall performance.

- Average Yield: **5.63 tonnes/hectare**
- Average Production: **46.31 tonnes**
- Average Revenue: **₹710,719**
- Average Cost: **₹531,804**
- Average Profit: **₹178,915**
- Water Efficiency: **5.89 tonnes/1,000 m³**
- Disease/Pest Risk: **54.47%**

### Rabi

- Average Yield: **5.04 tonnes/hectare**
- Average Profit: **₹87,689**
- Water Efficiency: **5.19 tonnes/1,000 m³**
- Disease/Pest Risk: **40.48%**

### Zaid

- Average Yield: **4.64 tonnes/hectare**
- Average Profit: **-₹24,805**
- Average Water Usage: **6,419.89 m³**
- Water Efficiency: **4.41 tonnes/1,000 m³**
- Disease/Pest Risk: **38.22%**

---

## 💡 Recommendations

Based on the analysis:

1. Agricultural planning should consider seasonal differences in profitability and resource requirements.

2. Water management should be improved during the Zaid season because it showed high water usage and low water efficiency.

3. Crop selection should consider season-specific performance.

4. Regional differences should be considered when planning agricultural activities.

5. Disease and pest monitoring should receive additional attention during higher-risk seasons.

6. Agricultural decisions should consider profitability along with yield.

7. Unusual observations should be investigated to determine whether they represent genuine agricultural performance or data-quality issues.

---

## 📁 Project Structure

```
seasonal-agriculture-performance-analysis/
│
├── Seasonal_Agriculture_Performance_Analysis.ipynb
├── seasonal_agriculture_performance_dataset.csv
├── README.md
└── images/
