
#  State-wise Surface Water Quality Analysis in India (2003–2014)

A comprehensive Exploratory Data Analysis (EDA) project on India's surface water quality using Python. This project analyzes water quality measurements collected across multiple Indian states between **2003 and 2014** to identify pollution patterns, compare states, and understand long-term environmental trends.

---

## 📌 Project Overview

Water quality is one of the most critical indicators of environmental and public health. This project performs an in-depth analysis of India's surface water quality dataset by examining key physicochemical and biological parameters.

The analysis focuses on:

- Understanding dataset structure
- Cleaning and preprocessing the data
- Handling missing values
- Statistical analysis
- Detecting outliers
- Correlation analysis
- State-wise comparison
- Year-wise trend analysis
- Visualizing pollution indicators

---

## 📂 Dataset Information

**Dataset Size**

- **Rows:** 1,991
- **Columns:** 12

### Features

| Column | Description |
|---------|-------------|
| STATION CODE | Monitoring station identifier |
| LOCATIONS | Sampling location |
| STATE | State/Union Territory |
| Temp | Water Temperature (°C) |
| D.O. (mg/l) | Dissolved Oxygen |
| pH | Acidity/Alkalinity |
| CONDUCTIVITY (µmhos/cm) | Electrical Conductivity |
| B.O.D. (mg/l) | Biological Oxygen Demand |
| NITRATENAN N+ NITRITENANN (mg/l) | Nitrate & Nitrite |
| FECAL COLIFORM (MPN/100ml) | Fecal Coliform Count |
| TOTAL COLIFORM (MPN/100ml) | Total Coliform Count |
| YEAR | Observation Year |

---

## 🎯 Objectives

- Explore India's surface water quality dataset
- Identify pollution patterns across states
- Compare water quality indicators
- Study temporal trends (2003–2014)
- Detect data quality issues
- Perform statistical analysis
- Generate meaningful visualizations
- Derive environmental insights

---

## 🛠️ Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 📊 Exploratory Data Analysis

The notebook includes:

### Data Understanding

- Dataset overview
- Shape
- Data types
- Missing value analysis
- Duplicate detection
- Statistical summary

### Data Cleaning

- Missing value handling
- Data type verification
- Duplicate checking

### Statistical Analysis

- Mean
- Median
- Standard deviation
- Minimum & Maximum values
- Quartiles
- Skewness

### Visualizations

- State-wise sample distribution
- Average Dissolved Oxygen by State
- Year-wise water quality trends
- BOD distribution
- pH distribution
- Correlation Heatmap
- Boxplots
- Histograms
- Scatter plots
- Top polluted states analysis

---

## 📈 Key Water Quality Parameters

The analysis primarily focuses on:

- 🌊 Dissolved Oxygen (DO)
- 🧪 pH
- ⚡ Conductivity
- 🧫 Biological Oxygen Demand (BOD)
- 🌱 Nitrate & Nitrite
- 🦠 Fecal Coliform
- 🦠 Total Coliform
- 🌡 Temperature

---

## 🔍 Key Insights

- Dataset contains water quality observations from multiple Indian states and Union Territories.
- Water quality measurements span over **12 years (2003–2014)**.
- Significant variation exists in Dissolved Oxygen and BOD levels across different states.
- Coliform counts indicate varying levels of biological contamination.
- Correlation analysis helps identify relationships among environmental parameters.
- Statistical summaries and visualizations provide valuable insights into pollution trends.

---

## 📁 Project Structure

```
State-wise-surface-water-quality/
│
├── Analysing_State_Wise_Surface_water_Quality.ipynb
├── State wise surface water quality.csv
├── README.md
```

---

## ▶️ How to Run

1. Clone this repository

```bash
git clone https://github.com/your-username/State-wise-surface-water-quality.git
```

2. Navigate to the project folder

```bash
cd State-wise-surface-water-quality
```

3. Install the required libraries

```bash
pip install pandas numpy matplotlib seaborn
```

4. Open the Jupyter Notebook or Google Colab

```bash
jupyter notebook
```

5. Run all cells sequentially.

---

## 📚 Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Data Visualization
- Statistical Analysis
- Python Programming
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Environmental Data Analysis

---

## 🔍 Key Findings

The exploratory analysis of India's surface water quality dataset revealed several important environmental and data-driven insights:

- **Comprehensive Dataset:** The dataset contains **1,991 water quality observations** collected across multiple Indian states and Union Territories from **2003 to 2014**.

- **Data Quality Issues:** Initial analysis identified missing values, one duplicate record, and several numeric columns stored as text, all of which were cleaned during preprocessing.

- **Uneven Monitoring Coverage:** Water quality monitoring was not evenly distributed across states. Some states had significantly more sampling locations than others, which should be considered when comparing state-wise results.

- **Dissolved Oxygen (DO):** DO levels were generally concentrated between **6–8 mg/L**, indicating acceptable oxygen levels in many monitored water bodies after data cleaning.

- **pH Distribution:** Most water samples exhibited pH values between **7.0 and 7.5**, suggesting that the majority of water bodies were close to neutral.

- **Biological Oxygen Demand (BOD):** BOD values were mostly concentrated between **1–3 mg/L**, although several monitoring locations recorded considerably higher values, indicating localized organic pollution.

- **Relationship Between DO and BOD:** A **moderate negative correlation (-0.44)** was observed between Dissolved Oxygen and Biological Oxygen Demand, confirming that increased organic pollution generally reduces the amount of dissolved oxygen available in water.

- **Coliform Contamination:** **Fecal Coliform and Total Coliform exhibited a very strong positive correlation (0.92)**, indicating that locations with high fecal contamination also experienced high overall bacterial contamination.

- **Conductivity Impact:** Conductivity showed a moderate negative relationship with Dissolved Oxygen, suggesting that increased dissolved solids are often associated with lower oxygen availability.

- **Temporal Trend:** Average Dissolved Oxygen levels reached their highest value around **2004**, followed by a noticeable decline in **2005**. From **2005 to 2014**, DO levels remained relatively stable with only minor annual fluctuations.

- **Pollution Hotspots:** Several monitoring stations recorded consistently high BOD values, highlighting localized pollution hotspots that may require further environmental investigation and remediation.

- **Overall Observation:** The analysis demonstrates that while many monitored water bodies maintained acceptable water quality, certain locations experienced elevated pollution levels, emphasizing the need for continuous monitoring and targeted pollution control measures.
---

## 👨‍💻 Author

**Mohanaraj R D**

- GitHub: https://github.com/mohanarajrd
---
