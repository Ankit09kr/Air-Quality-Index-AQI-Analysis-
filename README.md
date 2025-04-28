# Air Quality Index (AQI) Analysis

This project focuses on analyzing air quality levels across various cities and states in India using AQI data. The aim is to understand pollution trends, identify highly polluted regions, and visualize the distribution of air quality over time.

## 📂 Dataset Description

The dataset contains the following key columns:

- `Date`: The date of AQI recording
- `City`: City name
- `State`: State name 
- `AQI`: Numerical Air Quality Index value
- `AQI_Bucket`: Categorical classification of AQI (e.g., Good, Moderate, Poor, etc.)

## 📊 Exploratory Data Analysis (EDA)

EDA was conducted to:
- Check for missing values and duplicates
- Convert data types appropriately
- Analyze AQI distribution by state and city
- Explore AQI trends over time
- Understand the spread of AQI categories (Good, Moderate, Poor, etc.)

## 🔍 Key Analyses

### 1. AQI by State
- Computed average AQI for each state
- Identified most and least polluted states

### 2. AQI Trend Over Time
- Analyzed monthly/yearly AQI trends
- Visualized pollution rise or improvement

### 3. AQI Category Distribution
- Counted number of entries in each AQI_Bucket
- Presented proportions with pie/bar charts

## 📈 Visualizations

The project includes several visualizations created using Matplotlib and Seaborn to display:
- Bar charts of average AQI by state
- Line plots for AQI trends over time
- Pie charts for AQI_Bucket distribution

## 🛠 Tools & Technologies

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Jupyter Notebook
- CSV file as data source

## 📌 Conclusion

The analysis highlights critical pollution hotspots and temporal trends in air quality across India. It emphasizes the need for improved environmental regulations and cleaner practices to improve public health.

## 🚀 Future Scope

- Integrating real-time AQI data
- Correlating AQI with weather conditions
- Predictive modeling using machine learning

## 📚 References

- Dataset provided for academic use
- AQI classification based on CPCB (Central Pollution Control Board)
- Official data sources: [https://data.gov.in](https://data.gov.in), [https://cpcb.nic.in](https://cpcb.nic.in)

## 🙏 Acknowledgment

Thanks to the instructor and peers for their continuous guidance and support throughout this project.


