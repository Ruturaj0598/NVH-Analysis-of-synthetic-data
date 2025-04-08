# 🚗 NVH Analysis: Synthetic Data Generation and Dashboard Creation  

This repository contains a comprehensive project on **Noise, Vibration, and Harshness (NVH) Analysis** for vehicles. The project combines **synthetic data generation** using Python with the creation of an **interactive Power BI dashboard**, delivering actionable insights to enhance vehicle performance, ride comfort, and customer satisfaction.  

---

## 📋 Project Overview  

**Noise, Vibration, and Harshness (NVH)** are critical factors influencing vehicle occupant comfort and satisfaction. This project simulates NVH data for various vehicle models under different road surfaces and operating conditions. It also provides visualizations and insights through a Power BI dashboard to identify trends, correlations, and areas for improvement.  

### Key Features:  
- **Synthetic Dataset**: Realistic NVH metrics (noise levels, vibration readings, harshness scores) generated using Python.  
- **Interactive Dashboard**: Analyze NVH data trends, correlations, and customer feedback using Power BI.  
- **Actionable Insights**: Identify performance bottlenecks and recommend improvements to reduce noise, manage vibrations, and enhance ride comfort.  

---

## 📂 Repository Contents  

- **[`nvh_synthetic_data_final.csv`](nvh_synthetic_data_final.csv)**: Synthetic dataset used for analysis.  
- **[`data_generation.ipynb`](data_generation.ipynb)**: Python script for generating the synthetic NVH dataset.  
- **[`NVH Analysis.pbix`](NVH%20Analysis.pbix)**: Power BI dashboard file containing the NVH analysis.  
- **`README.md`**: This documentation file.  
- **[`NVH Analysis report.pdf`](NVH%20Analysis%20report.pdf)**: Task description document outlining requirements.  

---

## 🛠️ How the Data Was Generated  

1. **Vehicle Models**: Defined base characteristics for five vehicle types (Coupe, Hatchback, Sedan, SUV, Truck).  
2. **Environmental Factors**: Simulated road surfaces (e.g., Smooth Asphalt, Gravel) and operating conditions (e.g., City Driving, Highway).  
3. **Noise Levels**: Generated component-specific noise levels (e.g., Engine, Tires) and calculated total noise using logarithmic addition.  
4. **Vibration Readings**: Simulated vibrations at key points (e.g., Steering Wheel, Driver Seat).  
5. **Harshness Scores**: Created scores influenced by environmental factors to represent ride comfort.  
6. **Customer Feedback**: Realistic feedback generated based on predefined thresholds for NVH metrics.

### Data Quality Enhancements:
- Introduced missing values (~5%) for data cleaning exercises.
- Added duplicates (~2%) to mimic real-world inconsistencies.
- Excluded critical columns (e.g., Timestamp) from missing values or duplicates.

---

## 📊 Dashboard Features  

The Power BI dashboard provides two pages of analysis:  

1. **Overview Page**:
   - Summary of key NVH metrics.
   - Correlation between NVH metrics and customer satisfaction.
   - Distribution of vehicle models across road surfaces and conditions.

2. **Noise & Vibration Analysis Page**:
   - Detailed breakdown of noise sources (e.g., Engine Noise).
   - Analysis of vibration levels at key measurement points (e.g., Steering Wheel).
   - Insights into NVH performance under different road surfaces and operating conditions.

---

## 💡 Key Insights  

- Trucks exhibit significantly higher noise levels (engine/exhaust noise) under rough road conditions or during highway driving.
- SUVs and Trucks show elevated vibration levels; steering wheel and driver seat vibrations are areas for improvement.
- Sedans are the most comfortable overall; Coupes are ergonomically balanced but require some noise tolerance.
- Higher NVH levels correlate directly with lower customer satisfaction.

---

## 🚀 Recommendations  

1. Implement active noise cancellation technologies in truck cabins.
2. Use advanced sound insulation materials in engine compartments and exhaust systems.
3. Enhance suspension systems to reduce road-induced vibrations in trucks/SUVs.
4. Introduce vibration isolators in steering columns and seats to improve comfort.
5. Continuously monitor NVH metrics using real-time systems for ongoing improvements.

---

## 🔧 Getting Started  

### Prerequisites:
To run the Python script or analyze the dataset:
- Install Python 3.x
- Install required libraries (`pandas`, `numpy`, `datetime`)  

### Steps to Run the Script:
1. Clone this repository:
```
git clone https://github.com/Ruturaj0598/NVH-Analysis-of-synthetic-data)
```
2. Navigate to the repository folder:
```
cd nvh-analysis
```
3. Run the Python script to regenerate the dataset:
```
python data_generation.py
```


### Steps to Use the Dashboard:
1. Open [`nvh_synthetic_data_final.csv`](nvh_synthetic_data_final.csv) in Power BI Desktop.
2. Load the [`NVH Analysis.pbix`](NVH%20Analysis.pbix) file to explore the interactive dashboard.
3. Customize the dashboard or dataset as needed.

---

## 📝 Assumptions & Limitations  

1. The dataset is synthetic and may not fully reflect real-world scenarios.
2. Missing values were handled using assumptions like replacing blanks with "Idle."
3. Recommendations require validation through real-world testing.
4. External factors like weather or driver behavior were not considered.

---

## 📈 Potential Impact  

By addressing NVH challenges:  
- Vehicle performance can be improved through reduced noise and smoother rides.
- Customer satisfaction will increase due to enhanced comfort and quality.
- Brand loyalty can be strengthened by delivering superior products.
